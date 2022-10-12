﻿# 테스트 코드 작성 예시
 
 ### Entity
 - Product (상품)
 
 ### Service
 - ProductService (인터페이스)
 - DefaultProductService (구현체)

 ### Repository
 - ProductRepository
 
 ### 2022-10-11 폴더구조
 ```
 ├─main
│  ├─generated
│  ├─java
│  │  └─com
│  │      └─ij
│  │          └─tdd
│  │              │  TddApplication.java
│  │              │
│  │              ├─controller
│  │              │      ProductController.java
│  │              │
│  │              ├─dto
│  │              │      ApiResponse.java
│  │              │      ObjectResponse.java
│  │              │      ProductParam.java
│  │              │
│  │              ├─entity
│  │              │      Product.java
│  │              │
│  │              ├─repository
│  │              │      ProductRepository.java
│  │              │
│  │              └─service
│  │                      DefaultProductService.java
│  │                      ProductService.java
│  │
│  └─resources
│      │  application.yml
│      │
│      ├─static
│      └─templates
└─test
    └─java
        └─com
            └─ij
                └─tdd
                    │  TddApplicationTests.java
                    │
                    └─service
                            ProductServiceTest.java
 ```
