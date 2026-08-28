📊 E-commerce Satış Analizi

Python (pandas, scikit-learn, matplotlib) istifadə edərək 540,000+ tranzaksiyalıq real e-commerce datasetinin (UCI Machine Learning Repository — "Online Retail") tam analizi. 12 aylıq dövr (2010-12 – 2011-12), 4,300+ müştəri, 3,900+ məhsul.

🔍 Nə edilib
Data təmizləmə və dərin keyfiyyət yoxlaması — ləğv edilmiş sifarişlər, mənfi dəyərlər, xidmət sətirləri (çatdırılma haqqı və s.) təmizlənib. Əlavə olaraq, satışdan bir neçə dəqiqə sonra tam ləğv edilmiş "xəyali" sifarişlər aşkarlanıb və düzəldilib (~£300K dəyərində).
Kəşfiyyat analizi (EDA) — aylıq satış trendi, ölkə üzrə paylanma, həftənin günü/saat üzrə aktivlik.
ABC (Pareto) analizi — məhsulların hansı hissəsinin gəlirin böyük hissəsini yaratdığının müəyyənləşdirilməsi.
RFM müştəri seqmentasiyası — Recency, Frequency, Monetary göstəricilərinə əsasən müştərilərin VIP/Loyal/At Risk/Lost qruplarına bölünməsi.
Cohort analizi — yeni müştərilərin zaman keçdikcə geri qayıtma (retention) faizinin izlənməsi.
Market Basket Analysis — hansı məhsulların birlikdə alındığının aşkarlanması.
Sadə xətti reqressiya — gələcək aylıq gəlirin proqnozlaşdırılması.
🛠️ İstifadə olunan alətlər

Python · pandas · scikit-learn · matplotlib · Jupyter Notebook

📈 Əsas Tapıntılar
Gəlirin ~85%-i Birləşmiş Krallıqdan gəlir — bazar tək ölkəyə ciddi bağlıdır.
Məhsulların cəmi ~22%-i ümumi gəlirin 80%-ni yaradır.
İlk dəfə alış-veriş edən müştərilərin yalnız ~36%-i bir ay sonra geri qayıdır.
Dərin data-keyfiyyəti araşdırması nəticəsində, iki "top məhsul" əslində sonradan tam ləğv edilmiş sifarişlər olduğu üçün analizdən çıxarılıb.
📄 Tam Hesabat

Bax: Ecommerce_Satis_Analizi_Hesabat.docx

📂 Fayllar
analysis.ipynb — tam kod və analiz addımları
Ecommerce_Satis_Analizi_Hesabat.docx — yekun hesabat (qrafiklər və tövsiyələrlə)
