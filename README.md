# 404-page-not-found-template
404 Page Not Found - HTML, CSS, Full Optimized


```html
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="Aradığınız sayfaya ulaşılamıyor, Lütfen bilgi işlem departmanınız ile iletişime geçiniz ">
    <title>Aradığınız sayfaya ulaşılamıyor - 123456789</title>
    <link
      rel="shortcut icon"
      href="https://www.erciyesanadolu.com/favicon/favicon.ico"
    />
  </head>
  <body>
    <div class="error">
      <img width="250" src="https://cdn.erciyes.com/logos/gumussuyu.png" />
      <h1 class="error__header">Aradığınız sayfaya ulaşılamıyor</h1>
      <p class="error__description">
        Lütfen bilgi işlem departmanınız ile iletişime geçiniz
      </p>
      <hr class="error__line" />
      <p class="error__support-code">
        Talep Numarası: <a class="error__link" href="#">123456789</a>
      </p>
    </div>
    <div class="footer">
      <svg
        width="30"
        height="30"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 41.5 41.5"
      >
        <path
          d="M36.5 8C31 1.1 21.4-1.3 13.2 2 5.2 5.2-.1 13.6.6 22.2c.7 8.2 6.3 15.4 14.1 17.9 8.5 2.7 17.9-.7 22.8-8 5-7.3 4.6-17.3-1-24.1z"
          fill="#fff"
        />
        <path
          d="M38 32.4c5.1-7.5 4.6-17.7-1.1-24.8C31.2.6 21.4-1.9 13 1.4 4.7 4.8-.6 13.4.1 22.3c.7 8.4 6.4 15.8 14.5 18.3 8.6 2.7 18.3-.7 23.4-8.2zm-3.5 2.1c-4.7 4.7-11.5 6.6-17.9 5.2-3.2-.7-6.2-2.2-8.7-4.4-.7-.6-1.3-1.3-1.9-1.9l-.9-1.2c-.1-.1-.4-.4-.4-.5 0-.2 9.5-11.3 11.8-14 .9-1 2.1-2.4 3.4-1.1.6.5.9 1.3 1.4 2 .5.7 1.1 1.4 1.4 2.1.3.6.1.9-.2 1.4-.8 1.4-6.1 10.9-8 14.2 3.1-4.1 6.2-8.3 9.2-12.4 1-1.4 2.8-4.7 4.8-2.7 1.7 1.7 8.4 10 8.4 10.2 0 .3-.6.9-.7 1.1-.5.7-1.1 1.3-1.7 2z"
          fill="#0082ca"
        />
      </svg>
      <a class="footer__link" href="https://www.erciyesanadolu.com">
        www.erciyesanadolu.com
      </a>
    </div>

    <style>
      body {
        padding: 0;
        margin: 0;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        flex-direction: column;
        background-color: #f3f3f3;
        background: -moz-radial-gradient(
          circle,
          rgba(255, 255, 255, 1) 0%,
          rgba(193, 193, 193, 1) 100%
        );
        background: -webkit-radial-gradient(
          circle,
          rgba(255, 255, 255, 1) 0%,
          rgba(193, 193, 193, 1) 100%
        );
        background: radial-gradient(
          circle,
          rgba(255, 255, 255, 1) 0%,
          rgba(193, 193, 193, 1) 100%
        );
        filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#ffffff",endColorstr="#c1c1c1",GradientType=1);
      }
      .error {
        background-color: white;
        padding: 80px;
        border: 1px solid rgba(0, 0, 0, 0.1);
      }
      .error__header {
        font-family: sans-serif;
        font-weight: 400;
      }
      .error__description {
        font-family: sans-serif;
        font-weight: 400;
        letter-spacing: 0.1em;
        color: #747474;
      }
      .error__support-code {
        font-family: sans-serif;
        font-weight: 400;
      }
      .error__line {
        border-color: #fff;
      }
      .error__link {
        color: #007cc1;
      }
      .footer {
        margin-top: 30px;
        display: flex;
        flex-direction: column;
        align-items: center;
      }
      .footer__link {
        font-family: sans-serif;
        font-weight: 400;
        color: #747474;
        text-decoration: none;
        margin-top: 10px;

      }
      @media only screen and (max-width: 600px) {
        body {
          background-color: #fff;
          background: none;
        }
        .error {
          border: none;
        }
        .error__description {
          letter-spacing: normal;
        }
      }
    </style>
  </body>
</html>

```
