# LuchPolicyID
Merupakan platform analisis sentimen terhadap kebijakan pemerintah (studi kasus Makan Bergizi Gratis) berbasis web yang realtime dan menggunakan deep learning untuk menganalisis sentimen dari sosial media X.
Sistem ini dibangun menggunakan framework Python, yaitu Flask. Menggunakan deep learning LLM IndoBERT untuk memprediksi sentimen dari komentar yang didapat dari input manual maupun scraping otomatis. Sistem ini juga terhubung dengan database mysql sehingga persebaran sentimen dari setiap kelas dapat dimonitor dengan mudah pada laman dashboard. Sistem ini juga sudah diintegrasikan dengan scheduler yang akan menjalankan scraping otomatis menggunakan selenium pada platform sosial media X setiap harinya (per 24 jam).

Sistem ini dibuat untuk memenuhi persyaratan kelulusan atau tugas akhir
