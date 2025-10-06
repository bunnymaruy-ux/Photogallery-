index.html# Photogallery<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>📸 Моя фотогалерея</title>
  <style>
    body {
      font-family: "Segoe UI", sans-serif;
      background: #f5f5f5;
      color: #333;
      text-align: center;
      padding: 40px 20px;
    }

    h1 {
      margin-bottom: 20px;
      font-size: 28px;
    }

    .upload-box {
      background: white;
      padding: 20px;
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      display: inline-block;
      margin-bottom: 30px;
    }

    input[type="file"] {
      margin: 10px 0;
    }

    button {
      cursor: pointer;
      background: #3b82f6;
      color: white;
      border: none;
      padding: 10px 18px;
      border-radius: 8px;
      font-size: 14px;
      transition: 0.2s;
    }

    button:hover {
      background: #2563eb;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
      gap: 15px;
      max-width: 900px;
      margin: 0 auto;
    }

    .photo {
      position: relative;
      border-radius: 12px;
      overflow: hidden;
      background: white;
      box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    }

    .photo img {
      width: 100%;
      height: auto;
      display: block;
    }

    .delete-btn {
      position: absolute;
      top: 6px;
      right: 6px;
      background: rgba(0,0,0,0.6);
      color: white;
      border: none;
      border-radius: 6px;
      padding: 4px 8px;
      font-size: 16px;
      cursor: pointer;
      line-height: 1;
    }

    .delete-btn:hover {
      background
