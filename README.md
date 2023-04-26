# muhasebe-sistemi
Muhasebe Sistemi
Bu proje, bir işletmenin muhasebe ihtiyaçlarını karşılamak için tasarlanmıştır. Sistemin temel özellikleri şunlardır:

Anasayfa:
Bu bölümde, bugünün satışları, son 3 aylık ciro grafiği, bu ayki toplam satış, bu ayki toplam alınan ödeme gibi temel bilgileri gösterilir.

Günsonu kayıtları:
Bu bölüm, bir önceki günde kaydedilen tüm siparişleri alır ve sisteme kaydeder. Bu bölümde sipariş detayları görüntülenebilir ve düzenlenebilir.

Günsonu pdf'leri:
Bu bölümde veriler pdf formatında saklanır. Bu kayıtlar, müşterilerin imza vermesi gereken teslimat formları, fatura ve diğer belgeler gibi işlemler için kullanılabilir.

Teslimat formları:
Bu bölüm, müşterilerden teslimata dair imza alır ve satış sözleşmesi hazırlar. Bu bölümde, teslimat detayları ve müşteri bilgileri de görüntülenebilir.

Kasa:
Bu bölüm, şirketin kasasına giren ve kasadan çıkan para durumunu kaydeder. Bu bölümde, gelir ve giderlerin ayrıntılı bir görünümü ve Excel formatında çıktı alınabilen raporlar yer alır.

Gereksinimler:
Bu projeyi yerel bir ortamda çalıştırmak için, bilgisayarınızda Node.js ve MongoDB yüklü olmalıdır. Ayrıca, projenin çalıştırılması için aşağıdaki adımları takip etmelisiniz:

Bu projeyi bilgisayarınıza kopyalayın.
Ana dizinde bir .env dosyası oluşturun ve MONGODB_URI değişkenine MongoDB veritabanı bağlantı dizesini ekleyin.
Terminalde npm install komutunu çalıştırarak gerekli paketleri yükleyin.
npm start komutunu kullanarak projeyi başlatın.
Katkıda Bulunma:
Herhangi bir katkıda bulunmak isterseniz, lütfen bir çekme isteği oluşturun. Önerilerinizi ve geri bildirimlerinizi her zaman memnuniyetle karşılıyoruz.

Lisans:
Bu proje, MIT lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakın. (Dosyalar güvenlik amacı ile Github'a eklenmemiştir.)


This project is designed to meet the accounting needs of a business. The system's main features are as follows:

Dashboard: Displays basic information such as today's sales, a 3-month revenue chart, this month's total sales, and total payments received this month.
End-of-day records: Records all orders entered in the system from the previous day. Order details can be viewed and edited in this section.
End-of-day PDFs: Stores data in PDF format. The records in this section can be used for tasks such as delivery forms that customers need to sign, invoices, and other documents.
Delivery forms: Obtains signatures from customers for deliveries and prepares sales contracts. Delivery details and customer information can also be viewed in this section.
Cash register: Records the money that goes in and out of the company's cash register. This section provides a detailed view of income and expenses, as well as reports that can be exported to Excel.

Ekran Resimleri:

![muhasebe](https://user-images.githubusercontent.com/83727951/234595497-e7799879-3c00-4273-a55a-66d43dc11c81.png)
