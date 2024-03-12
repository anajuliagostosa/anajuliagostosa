@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

@font-face {
  font-family: Kelson;
  src: url('./assets/font/KelsonSans-Bold.woff') format('woff'),
      url('./assets/font/KelsonSans-Bold.eot') format('embedded-opentype');
  font-weight: bold;
}

@font-face {
  font-family: Kelson;
  src: url('./assets/font/KelsonSans-Normal.woff') format('woff'),
      url('./assets/font/KelsonSans-Normal.eot') format('embedded-opentype');
  font-weight: normal;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  font-family: 'Montserrat', Arial, sans-serif;
  background-color: #ededed;
}

@@ -22,14 +38,16 @@ body {
  padding-right: 2vw;
}
.header h1 {
  font-family: 'Kelson', Arial, sans-serif;
  font-size: 56px;
  font-weight: bold;
  margin: 0;
  font-weight: 400;
}
.header p {
  font-family: 'Kelson', Arial, sans-serif;
  font-size: 32px;
  font-weight: normal;
  margin: 0;
  font-weight: 500;
}

/* Formulario */
@@ -67,7 +85,8 @@ select {
  height: 40px;
  background-color: #ff5100;
  color: #ffffff;
  width: 80%;
  font-family: inherit;
  width: 78%;
  text-align: center;
}
input:focus,
@@ -76,6 +95,7 @@ select:focus {
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.25);
}
button {
  font-family: inherit;
  border-radius: 10px;
  border: 0;
  background-color: #ff5100;
@@ -106,6 +126,7 @@ button h2 {

/* Assinatura */
.assinatura-wrapper {
  font-family: Arial, sans-serif;
  margin: auto;
  display: flex;
  align-items: center;
@@ -127,7 +148,6 @@ footer {
  margin: 40px auto 40px auto;
  padding: 20px;
  box-shadow: 2px 2px 20px rgba(0, 0, 0, 0.25);
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  width: fit-content;
}
footer div {
