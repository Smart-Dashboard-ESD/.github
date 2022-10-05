# **Smart Dashboard**

Smart Dashboard is a web application that allows you to check water consumption and other data from IoT device that installed in water meter. It is built with [Go](https://go.dev/) and Using [Fiber](https://gofiber.io/) Framework for Backend Services. The Frontend is built with [React](https://reactjs.org/) and The Mobile App is built with [Flutter](https://flutter.dev/).

<br/>

## **Repo's are still private (under development) will set to public when applications ready to use**
<br/>

## **About Frontend**

The Smart Dashboard Frontend is the result of translating the design from the UI/UX Designer and shows the data fetched from the Smart Dashboard Backend API. This dashboard is built with the JavaScript Framework namely [ReactJS](https://reactjs.org/docs/getting-started.html) and the CSS Framework namely [TailwindCSS](https://tailwindcss.com/docs/installation).

<br/>

## **About Mobile App**

The Smart Dashboard Frontend is the result of translating the design from the UI/UX Designer and shows the data fetched from the Smart Dashboard Backend API. This mobile application is built with the [Flutter SDK](https://docs.flutter.dev/get-started/install).

<br/>

## **About Backend**

Smart Dashboard Backend is a service that provides API for Smart Dashboard Frontend and Mobile App. It is built with [Go](https://go.dev/) and Using [Fiber](https://gofiber.io/) Framework. Backend Services communicate with IoT device using [Antares IoT Platform](https://antares.id/). It also communicate with Database using [GORM](https://gorm.io/) ORM. The Database used is [PostgreSQL](https://www.postgresql.org/).

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
