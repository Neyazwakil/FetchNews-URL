## News Scraper Application
----
### Overview
- This is a Java-based application that scrapes news URLs from Google News based on a search term using Playwright. The application is built using Spring Boot and follows a simple architecture with controllers, services, and utility classes.

### Features

- Scrape news URLs from Google News using Playwright.
- Spring Boot RESTful service for fetching news based on user queries.
- Dockerized for easy deployment.

### Prerequisites

- Java 17
- Maven
- Playwright (installed via dependency)

### Dependencies:- 
- Spring Web
- Spring Actuator
- Spring Devtools
- Project Lombok
- Playwright 
- Spring Doc for swagger

### Setup
#### Clone the Repository

```bash
git clone https://github.com/iamaniketg/NewsApp.git
cd news-scraper
```
### Build the Jar of Project
```bash
mvn clean install
```

### Running the Application
```bash
mvn spring-boot:run
```


### Swagger url:-
```bash
- http://localhost:7575/api/news/swagger-ui/index.html#/news-controller/fetchNews
```
### Curl :-
- ```curl -X 'GET' \
  'http://localhost:7575/api/news/fetch-news?searchTerm=india' \
  -H 'accept: */*'
  ```
### Licence:- 
- This project is licensed under the MIT License.

### Author
Neyaz Wakil
