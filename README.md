<!DOCTYPE html>
<html>
<head>
  <title>Minha Página HTML</title>
  <style>
    body {
      border: 5px solid black;
      padding: 20px;
    }

    h1 {
      font-size: 48px;
      color: red;
      text-align: center;
      font-family: Arial, sans-serif;
      text-transform: uppercase;
    }
    
    p {
      font-size: 24px;
      text-align: center;
      font-family: Arial, sans-serif;
      margin-top: 20px;
    }
    
    .floating-hearts {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 9999;
    }
    
    .floating-heart {
      position: absolute;
      width: 20px;
      height: 20px;
      background-color: red;
      border-radius: 50%;
      animation: float 4s ease-in-out infinite;
    }
    
    @keyframes float {
      0% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-100px);
      }
      100% {
        transform: translateY(0);
      }
    }
    
    .marriage-proposal {
      font-size: 64px;
      text-align: center;
      font-family: Arial, sans-serif;
      color: blue;
      margin-top: 50px;
    }
    
    .button {
      display: block;
      margin: 20px auto;
      padding: 10px 20px;
      font-size: 24px;
      text-align: center;
      font-family: Arial, sans-serif;
      background-color: blue;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    
    footer {
      text-align: center;
      font-family: Arial, sans-serif;
      font-size: 18px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <h1>Olá, amor da minha vida</h1>
  
  <p>Eu te amo mais do que as palavras podem expressar. Você é a pessoa que ilumina minha vida, meu porto seguro e minha fonte de felicidade. Não há medida para o meu amor por você, é imensurável. Serei sempre grato por tê-la ao meu lado.</p>
  
  <div class="floating-hearts">
    <div class="floating-heart"></div>
    <div class="floating-heart"></div>
    <div class="floating-heart"></div>
    <div class="floating-heart"></div>
    <div class="floating-heart"></div>
  </div>
  
  <p>Esta é uma página HTML simples.</p>
  
  <p class="marriage-proposal">Quer casar comigo?</p>
  
  <button class="button">Claro que sim</button>
  
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>
  
  <footer>
    Minha vida todinha pra você ♥
  </footer>
  
  <p>Para mais informações, consulte a <a href
