# Bienvenido a configurar GitHub Codespaces y Gitpod <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px" height="30px">

<div align="center">
 
```
 __          __  _                          _ 
 \ \        / / | |                        | |
  \ \  /\  / /__| | ___ ___  _ __ ___   ___| |
   \ \/  \/ / _ \ |/ __/ _ \| '_ ` _ \ / _ \ |
    \  /\  /  __/ | (_| (_) | | | | | |  __/_|
     \/  \/ \___|_|\___\___/|_| |_| |_|\___(_)
```
</div>

## BACK END | Java Development Kit (JDK)
- **Listar versiones de `JDK` (LTS)**
```
sdk list java
```
- **Instalar una versión de `JDK` según la lista anterior, por ejemplo:**
```
sdk install java 17.0.11-jbr
```
- **Instalar la extensión de: `Extension Pack for Java` en Codespaces**
- **Finalmente puedes ejecutar tu proyecto Spring Boot con el arcivo principal "Application.java"**
- **También puedes ejecutar tu proyecto Spring Boot ubicado en el directorio de tu proyecto con el comando:**
```
mvn spring-boot:run
```

## FRONT END | Node.js
- **Listar versiones de `Node.js` con la versión `Angular` (LTS)**
```
npm show @angular/cli dist-tags
```
- **Instalar una versión de `Node.js` según la lista anterior, por ejemplo:**
```
nvm install 17
```
- **Instalar una versión de `Angular` compatible con `Node.js` según la lista anterior, por ejemplo:**
```
npm install -g @angular/cli@17.3.8
```
- **Verificar las versiones instaladas de `Node.js` y `Angular`**
```
ng version
```
- **Instalar las dependencias de tu archivo `package.json` y crear la carpeta `node_modules`**
```
npm install
```
- **Ejecutar tu `Angular`**
```
npm start
```
