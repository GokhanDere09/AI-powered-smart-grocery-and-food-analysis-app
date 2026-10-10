## BACKEND:
FastAPI ile geliştirdiğim bu uygulamada ürünleri isim fiyat kategorisini veri tabanında tutar. Kalori protein yağ ve karbonhidrat bilgisi önceden Gemini API üzerinden sorgulanıp alınan veriler db ye kaydedilir ve o veriler kullanılır eğer yoksa her yeni bir ürün için Gemini API üzerinden besin değeri alınır db ye yazılır. Silinen ürünün besin değeri db de kalmaya da devam eder(soft delete).

## FRONTEND:
React kütüphanesinden yararlanarak modern bir görüntü sağlamaya çalıştım.

## Kullandığım teknolojiler: 
React: JS kütüphanesi
FastAPI: API framework
SQLAlchemy:veritabanı ORM
SQLite: veri tabanı
Google Gemini API: besinlerin değerini  AI yardımıyla döndürür


## BACKEND:
In this application developed with FastAPI, product details—such as name, price, and category—are stored in the database. Nutritional data (calories, protein, fat, and carbohydrates) is retrieved via the Gemini API and saved to the database for future use; if the data does not exist for a new product, it is fetched from the Gemini API and written to the database. Nutritional data remains in the database even after a product is deleted (soft delete).

## FRONTEND:
I utilized the React library to create a modern user interface.

## Technologies Used:
React: JS library
FastAPI: API framework
SQLAlchemy: Database ORM
SQLite: Database
Google Gemini API: Retrieves nutritional values ​​using AI