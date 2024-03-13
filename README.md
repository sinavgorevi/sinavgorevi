<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Src Sınavı Görev Formu</title>
    <!-- Buraya CSS dosyalarınızı ekleyebilirsiniz -->
</head>
<body>
    <h1>Src Sınavı Görev Formu</h1>
    <form id="srcForm">
        <label for="adSoyad">Ad Soyad:</label>
        <input type="text" id="adSoyad" name="adSoyad" required><br><br>
        
        <label for="okulAdi">Okul Adı:</label>
        <input type="text" id="okulAdi" name="okulAdi" required><br><br>
        
        <label for="telefon">Telefon:</label>
        <input type="tel" id="telefon" name="telefon" pattern="[0-9]{10}" required><br><br>
        
        <label for="srcGorev">Src Sınavı Görevi:</label><br>
        <input type="radio" id="evet" name="srcGorev" value="evet" required>
        <label for="evet">EVET</label><br>
        <input type="radio" id="hayir" name="srcGorev" value="hayir" required>
        <label for="hayir">HAYIR</label><br><br>
        
        <button type="submit">Gönder</button>
    </form>

    <!-- Buraya JavaScript dosyalarınızı ekleyebilirsiniz -->
</body>
</html>
