# Bank Management - Frontend

Angular client for the [bank-management-backend](https://github.com/dejan3dejan/bank-management-backend) REST API. Built as part of the *Razvoj veb aplikacija* (Web Application Development) course.

## Features

- Tables for banks, branches, service users and services, built with Angular Material
- Create and edit through dialog forms with validation
- Delete with a confirmation dialog
- Search and filtering across all fields

## Stack

- Angular 16, TypeScript
- Angular Material
- RxJS / HttpClient

## Structure

```
src/app/
  components/   one component per entity, each with its own edit dialog
  models/       TypeScript models matching the backend entities
  services/     HTTP services, one per REST resource
```

## Running locally

Start the backend first (it runs on `http://localhost:8082`), then:

```bash
npm install
npx ng serve
```

Open `http://localhost:4200/`.
