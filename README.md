# Ocean
Öncelikle Context dosyasındaki OnConfiguring methodunun içindeki sql connection string bağlantısını kendi veritabanınıza göre ayarlayınız.
Sonrasında Package Manager Consoldan migration oluşturun (add-migration InıtıalCreate),yükleme sorunsuz tamamlandıktan sonra Update-database yazınız.
Artık program çalışmaya hazır.
