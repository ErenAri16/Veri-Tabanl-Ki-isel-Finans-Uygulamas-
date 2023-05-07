Amacım 

Bu projenin amacı, kişisel finans yönetimini kolaylaştıran bir uygulama geliştirmektir. Uygulama, kullanıcılara gelir ve giderlerini takip etme, bütçe oluşturma, harcamaları kategorilere ayırma ve genel olarak mali durumlarını gözlemleme imkanı sunar. Bu sayede kullanıcılar, mali hedeflerine ulaşmak için daha bilinçli kararlar alabilir, tasarruf etme alışkanlıkları geliştirebilir ve finansal durumlarını daha iyi yönetebilirler.

Uygulama aynı zamanda veritabanı entegrasyonunu içerir. Kullanıcılar, gelir ve gider verilerini veritabanında saklayabilir ve gerektiğinde geri alabilirler. Bu, verilerin güvenli ve kalıcı bir şekilde saklanmasını sağlar ve kullanıcılara uzun vadeli finansal takip ve analiz yapma imkanı sunar.

Projedeki amaç, kullanıcılara finansal durumlarını anlamaları ve yönetmeleri için pratik bir araç sunmaktır.

Motivasyonum

Finansal sağlığı iyileştirmek, harcamaları takip etmek, bütçe oluşturmak veya tasarruf etmek gibi hedeflerle ilgilidir. Ayrıca, kişisel finans yönetimi becerilerini geliştirmek, mali hedefleri belirlemek ve finansal özgürlüğe ulaşmak gibi uzun vadeli hedeflere de motivasyon kaynağı olması.

Olası Veritabanı

Users (Kullanıcılar)

user_id (Kullanıcı ID)
username (Kullanıcı adı)
password (Şifre)
email (E-posta adresi)
created_at (Oluşturma tarihi)
Incomes (Gelirler)

income_id (Gelir ID)
user_id (Kullanıcı ID - Users tablosuna referans)
amount (Gelir miktarı)
category (Gelir kategorisi)
description (Açıklama)
date (Tarih)
created_at (Oluşturma tarihi)
Expenses (Giderler)

expense_id (Gider ID)
user_id (Kullanıcı ID - Users tablosuna referans)
amount (Gider miktarı)
category (Gider kategorisi)
description (Açıklama)
date (Tarih)
created_at (Oluşturma tarihi)
Budgets (Bütçeler)

budget_id (Bütçe ID)
user_id (Kullanıcı ID - Users tablosuna referans)
amount (Bütçe miktarı)
category (Bütçe kategorisi)
created_at (Oluşturma tarihi)
