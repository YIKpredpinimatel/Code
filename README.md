html
<!DOCTYPE html>
<html>
<head>
  <title>Мой сайт</title>
  <style>
    /* Общие стили для всех страниц */
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    
    header {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    
    h1 {
      margin: 0;
      font-size: 24px;
    }
    
    /* Стили для главной страницы */
    .main-content {
      padding: 20px;
    }
    
    /* Стили для поисковой страницы */
    .search-results {
      padding: 20px;
    }
    
    .search-result {
      margin-bottom: 10px;
    }
    
    /* Стили для страницы ввода файлов */
    .file-upload {
      padding: 20px;
    }
    
    input[type="file"] {
      margin-bottom: 10px;
      display: block;
    }
  </style>
</head>
<body>
  <header>
    <h1>Мой сайт</h1>
  </header>
  
  <!-- Главная страница -->
  <div class="main-content">
    <h2>Добро пожаловать на главную страницу!</h2>
    <p>Здесь вы можете узнать информацию о нашем сайте.</p>
  </div>
  
  <!-- Поисковая страница -->
  <div class="search-results">
    <h2>Результаты поиска</h2>
    <div class="search-result">
      <h3>Заголовок результата поиска</h3>
      <p>Описание результата поиска.</p>
    </div>
    <div class="search-result">
      <h3>Заголовок результата поиска</h3>
      <p>Описание результата поиска.</p>
    </div>
  </div>
  
  <!-- Страница ввода файлов -->
  <div class="file-upload">
    <h2>Загрузка файла</h2>
    <input type="file" name="file" accept=".jpg, .png, .pdf">
    <input type="submit" value="Загрузить">
  </div>
</body>
</html>
