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

## BACK END | Java Development Kit (JDK) 👨‍💻🔵👩‍💻
- **Listar versiones de `JDK` (LTS), tecla "Q" para salir de la lista**
```
sdk list java
```
- **Instalar una versión de `JDK` según la lista anterior, por ejemplo:**
```
sdk install java 17.0.12-jbr
```
- **Instalar la extensión de: `Extension Pack for Java` en Codespaces**
- **Finalmente puedes ejecutar tu proyecto Spring Boot con el arcivo principal "Application.java"**
- **También puedes ejecutar tu proyecto Spring Boot ubicado en el directorio de tu proyecto con el comando:**
```
mvn spring-boot:run
```

## FRONT END | Node.js 👨‍💻🔵👩‍💻
- **Listar versiones de `Node.js` con la versión `Angular` (LTS)**
```
npm show @angular/cli dist-tags
```
- **Instalar una versión de `Node.js` según la lista anterior, por ejemplo:**
```
nvm install 20.9.0
```
- **Instalar una versión de `Angular` compatible con `Node.js` según la lista anterior, por ejemplo:**
```
npm install -g @angular/cli@17.3.0
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

## DOCKER 👨‍💻🔵👩‍💻
- **A**
```
a
```

## DOCKER COMPOSE 👨‍💻🔵👩‍💻
- **A**
```
a
```

## KUBERNETES 👨‍💻🔵👩‍💻
- **Crear | actualizar un namespace mediante un archivo `.yml`**
```
kubectl apply -f namespace.yml
```

- **Crear | actualizar un configmap mediante un archivo `.yml`**
```
kubectl apply -f configmap.yml
```
- **Crear | actualizar un secret mediante un archivo `.yml`**
```
kubectl apply -f secret.yml
```
- **Crear | actualizar un deployment mediante un archivo `.yml`**
```
kubectl apply -f deployment.yml
```
- **Crear | actualizar un service mediante un archivo `.yml`**
```
kubectl apply -f service.yml
```
- **Crear | actualizar un horizontalpodautoscaler mediante un archivo `.yml`**
```
kubectl apply -f horizontalpodautoscaler.yml
```
