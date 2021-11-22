# 404-page-not-found-template
404 Page Not Found - HTML, CSS, Full Optimized


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="404 Page Not Found, Please contact your IT department">

    <title>Aradığınız sayfaya ulaşılamıyor - 123456789</title>
    <link
      rel="shortcut icon"
      href="https://www.erciyesanadolu.com/favicon/favicon.ico"
    />
  </head>
  <body>
    <div class="error">
      <svg
        width="80"
        height="80"
        xmlns="http://www.w3.org/2000/svg"
        xml:space="preserve"
        viewBox="0 0 26.2 27.5"
      >
        <path
          d="m26.2 13-8.7-8.4-2 2.1L8.4 0 0 8.7l5.3 5.1-5 5.2L9 27.5l7.1-7.4 1.7 1.6 8.4-8.7zM8.5 2.7l5.7 5.5-3.8 3.8-1-1-.7-.6-2 2.1-4-3.8 5.8-6zm6.3 16.1-5.7 6L3 19l3.7-3.9 2-2.1.3.3.8.7.6.6 2.8 2.7 1.6 1.5zm-.2-2.8-2.8-2.7 5.8-6 6 5.8-5.8 6-3.2-3.1z"
        />
      </svg>
      <h1 class="error__header">404 Page Not Found</h1>
      <p class="error__description">
        Please contact your IT department
      </p>
      <hr class="error__line" />
      <p class="error__support-code">
        Request Number: <a class="error__link" href="#">123456789</a>
      </p>
    </div>
    <div class="footer">
      <svg
        width="30"
        height="30"
        xmlns="http://www.w3.org/2000/svg"
        xml:space="preserve"
        viewBox="0 0 26.2 27.5"
      >
        <path
          d="m26.2 13-8.7-8.4-2 2.1L8.4 0 0 8.7l5.3 5.1-5 5.2L9 27.5l7.1-7.4 1.7 1.6 8.4-8.7zM8.5 2.7l5.7 5.5-3.8 3.8-1-1-.7-.6-2 2.1-4-3.8 5.8-6zm6.3 16.1-5.7 6L3 19l3.7-3.9 2-2.1.3.3.8.7.6.6 2.8 2.7 1.6 1.5zm-.2-2.8-2.8-2.7 5.8-6 6 5.8-5.8 6-3.2-3.1z"
        />
      </svg>
      <a class="footer__link" href="https://www.ismailenesayhan.com">
        www.ismailenesayhan.com
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
