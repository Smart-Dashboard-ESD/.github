# **Smart Dashboard**

Smart Dashboard is a web application that allows you to check water consumption and other data from IoT device that installed in water meter. It is built with [Go](https://go.dev/) and Using [Fiber](https://gofiber.io/) Framework for Backend Services. The Frontend is built with [React](https://reactjs.org/) and The Mobile App is built with [Flutter](https://flutter.dev/).

<br/>

## **Repo are still private (under development) will set to public when applications ready to use**
<br/>

## **Repository Structure**

The repository is structured as follows:

- `main` is main branch of the repository and contains the latest stable version of the code.
- `dev` is the development branch of the repository and contains the latest development version of the code.
- `feature/feature_name` branches are used to develop new features and are merged into `dev` when they are ready.
- commits formatted as `feat/feature_name` are used to fix bugs in the code and are merged into `dev` when they are ready.

<br/>

## **Installation**

### **Installation For Frontend (Website)**

Prerequisites

- ReactJS 18.2.0
- NodeJS LTS

### Running the application

```bash
npm i && npm start
```
<br> </br>

### **Installation For Frontend (Mobile)**

Prerequisites

- Flutter SDK 3.3.2
- Dart 2.18.0 (stable)

### Running the application

```bash
flutter run lib/main.dart
```
<br> </br>

### **Installation For Backend (Golang)**

Prerequisites

- Go 1.18
- Docker
- Docker Compose

### Running the application

```bash
docker-compose up
```
