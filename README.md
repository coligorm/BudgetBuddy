# BudgetBuddy
Personal Finance Budgeting App

## Technology Stack
[![My Skills](https://skillicons.dev/icons?i=dotnet,sqlite,react,ts,docker,azure)](https://skillicons.dev)

### Backend:

- **ASP.NET Core Web API (C#)** for server-side application
- **Entity Framework Core** for database operations and ORM
- **SQLite** for database

### Frontend:

- **React with TypeScript** for web interface
- **React Native with TypeScript** for mobile apps
- **React Query** for state management
- **Axios** for API communication

### DevOps/Infrastructure:

- **Docker** for containerization
- **Azure** for hosting (good integration with .NET)

This architecture creates a RESTful API with a C# backend that both the web and mobile applications can consume.

---

## Project Plan

### Phase 1: Backend Foundation

#### Setup ASP.NET Core project

- [ ] Create a new ASP.NET Core Web API project
- [ ] Configure development environment and tools
- [ ] Set up Entity Framework Core with Code First approach
- [ ] Create initial database migration

#### Design and implement data models

- [ ] Define entity classes for accounts, transactions, budgets, debts, savings goals
- [ ] Establish relationships between entities
- [ ] Implement database context and repository pattern

#### Create core API endpoints

- [ ] Design RESTful API structure
- [ ] Implement CRUD operations for all core entities
- [ ] Set up proper routing and controller organization
- [ ] Add input validation and error handling

#### Implement authentication system

- [ ] Set up ASP.NET Core Identity
- [ ] Create user registration and login endpoints
- [ ] Implement JWT token authentication
- [ ] Configure authorization policies

### Phase 2: Frontend Web Application

#### Setup React project

- [ ] Create new React application with TypeScript
- [ ] Configure project structure and essential packages
- [ ] Set up routing with React Router
- [ ] Implement authentication context and protected routes

#### Develop core UI components

- [ ] Create reusable component library (buttons, forms, cards, etc.)
- [ ] Implement responsive layout components
- [ ] Design consistent styling system (with CSS-in-JS or styled-components)

#### Implement account and transaction features

- [ ] Create dashboard overview with financial summary
- [ ] Build account management screens (list, add, edit, delete)
- [ ] Develop transaction entry and categorization interfaces
- [ ] Implement basic reporting and visualization components

#### Connect frontend to backend

- [ ] Create API service layer with Axios
- [ ] Implement API request hooks or services
- [ ] Add loading states and error handling
- [ ] Set up authentication flow with token management

### Phase 3: Debt Management and Budgeting Features

#### Backend implementation

- [ ] Create endpoints for debt tracking and management
- [ ] Implement budget calculation algorithms
- [ ] Add reporting and analytics endpoints

#### Frontend implementation

- [ ] Build debt tracking dashboard and detail screens
- [ ] Create debt repayment planning interface
- [ ] Implement budget creation and monitoring screens
- [ ] Add visual representations of financial data (charts, graphs)

### Phase 4: Savings Goals and Notifications

#### Backend implementation

- [ ] Develop savings goals tracking endpoints
- [ ] Create notification system and scheduled events
- [ ] Implement reminder logic for payments and transfers

#### Frontend implementation

- [ ] Build savings goals creation and tracking interface
- [ ] Implement progress visualization components
- [ ] Create notification preferences screen
- [ ] Add notification display and management in the UI

### Phase 5: Mobile Application Development

#### Setup React Native project

- [ ] Initialize React Native project with Expo
- [ ] Configure project structure similar to web app
- [ ] Set up navigation using React Navigation
- [ ] Reuse authentication logic and API services from web app

#### Core mobile features

- [ ] Adapt dashboard and transaction screens for mobile
- [ ] Optimize input forms for touch interfaces
- [ ] Implement mobile-specific navigation patterns

#### Implement mobile-specific features

- [ ] Add push notification handling
- [ ] Implement biometric authentication
- [ ] Create quick-entry transaction features
- [ ] Add receipt scanning capability (optional advanced feature)

### Phase 6: Integration, Testing and Deployment

#### Integration testing

- [ ] Test API endpoints with Postman or similar tools
- [ ] Perform end-to-end testing across platforms
- [ ] Fix cross-platform issues and edge cases

#### Deployment setup

- [ ] Configure Docker containers for backend
- [ ] Set up CI/CD pipeline (optional)
- [ ] Deploy backend to Azure or alternative hosting
- [ ] Publish web application
- [ ] Prepare mobile app for distribution (personal use)

#### Documentation and finalization

- [ ] Document API endpoints
- [ ] Create user guide for personal reference
Final performance optimizations
