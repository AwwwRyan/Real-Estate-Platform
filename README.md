# Real-Estate-Platform

A comprehensive digital marketplace connecting property buyers and sellers through a seamless web experience.

## 👥 Team Members

- **Aryan Srivastava** - A073
- **Aryan Walia** - A078  
- **Aayush Chawla** - A008
- **Priya Pandey** - A048

## Overview

This project is a modern web application that serves as a comprehensive real estate marketplace. Built with microservices architecture, it enables property sellers to list their properties, buyers to search and discover suitable properties, and facilitates seamless communication between parties.

### Key Capabilities

- **Property Listing Management** - Create, edit, and manage property listings with images
- **Advanced Search & Filtering** - Find properties based on location, price, amenities, and more
- **Secure Communication** - In-app messaging system for buyer-seller interactions
- **Appointment Scheduling** - Book property viewings and inspections
- **Review & Rating System** - Build trust through user feedback and ratings
- **User Verification** - Document-based authentication for enhanced security

## 🎯 Problem Statement

The traditional real estate market faces several challenges that our platform addresses:

### For Property Sellers
- ❌ Limited reach and visibility for listings
- ❌ Difficulty managing inquiries and scheduling
- ❌ Lack of centralized showcase platform
- ❌ Time-consuming buyer communication
- ❌ No standardized credibility system

### For Property Buyers  
- ❌ Scattered information across platforms
- ❌ Difficulty finding matching properties
- ❌ Lack of verified seller information
- ❌ Complex viewing scheduling process
- ❌ Limited access to genuine reviews

### Our Solution
✅ **Centralized marketplace** with unified property listings  
✅ **Enhanced user experience** with intuitive interface  
✅ **Secure communication** through in-app messaging  
✅ **Trust & transparency** via review system  
✅ **Efficient scheduling** for property viewings

## ✨ Features

### Core Features
- 🔐 **User Authentication** - Secure login/signup with JWT tokens
- 🏘️ **Property Listings** - Comprehensive property showcase with images
- 🔍 **Smart Search** - Advanced filtering by location, price, amenities
- 💬 **In-App Messaging** - Direct communication between users
- 📅 **Appointment Booking** - Schedule property viewings
- ⭐ **Review System** - Rate properties and sellers
- ✅ **User Verification** - Document-based identity verification

### Technical Features
- 🏗️ **Microservices Architecture** - Scalable and maintainable
- 📱 **Responsive Design** - Works on desktop and mobile
- 🔒 **Secure APIs** - Protected endpoints with authentication
- 📊 **Performance Optimized** - Fast loading and responsive UI

## 🏛️ Architecture

The platform follows a **microservices architecture** with the following services:

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│ Authentication  │    │   Property      │    │   Messaging     │
│    Service      │    │   Service       │    │   Service       │
└─────────────────┘    └─────────────────┘    └─────────────────┘
         │                       │                       │
         └───────────────────────┼───────────────────────┘
                                 │
         ┌───────────────────────┼───────────────────────┐
         │                       │                       │
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│    Profile      │    │  Appointment    │    │     Review      │
│    Service      │    │    Service      │    │    Service      │
└─────────────────┘    └─────────────────┘    └─────────────────┘
```

## 🛠️ Technology Stack

### Backend
- **Java Spring Boot 3.x** - Core framework for REST APIs
- **Spring Security** - Authentication and authorization
- **Spring Data JPA** - Database operations and ORM
- **Hibernate** - Object-relational mapping
- **Maven** - Dependency management
- **MySQL 8.0** - Primary database

### Frontend  
- **Next.js 15** - React framework with SSR
- **React 18** - Component-based UI development
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Axios** - HTTP client for API calls

### Development Tools
- **IntelliJ IDEA / VS Code** - IDEs
- **Postman** - API testing
- **Git** - Version control
- **Docker** - Containerization
- **MySQL Workbench** - Database management

## 🧩 System Modules

### 1. Authentication Service
- User registration and login
- JWT token management
- Password security and validation

### 2. Property Service  
- Property CRUD operations
- Image upload and management
- Search and filtering logic

### 3. Profile Service
- User profile management
- Document verification
- User role management

### 4. Messaging Service
- Real-time chat functionality
- Conversation management
- Message history

### 5. Appointment Service
- Viewing appointment booking
- Calendar integration
- Appointment status tracking

### 6. Review Service
- Property and seller ratings
- Review management
- Trust score calculation

## 🚀 Getting Started

### Prerequisites
- Java 17+
- Node.js 18+
- MySQL 8.0
- Maven 3.6+
- Git

## 🎯 Expected Outcomes

### Functional Outcomes
- ✅ Secure user management system
- ✅ Comprehensive property listing platform
- ✅ Real-time communication features
- ✅ Efficient appointment scheduling
- ✅ Trust-building review system

### Technical Outcomes  
- ✅ Scalable microservices architecture
- ✅ Secure authentication and authorization
- ✅ Optimized database performance
- ✅ Responsive and intuitive UI

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
