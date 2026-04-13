# Price Tracker

This is a full stack application which is in development to help user track product prices from
e-commerce sites like Amazon, eBay, and more. User can view price history, and receive email alerts when
price drops. They can also paste any product URL to track price drops.
The application works best with major e-commerce sites, with growing support for others.

## Back End Technology Used

- Spring Boot
- Spring Web → Handles HTTP requests (REST API, controllers)
- Spring Data JPA → Database access using Java objects instead of raw SQL
- Validation → Validates request data (@NotNull, @Email, etc.)
- PostgreSQL → Production database
- H2 Database → In-memory database for development and testing
- Spring Security → Authentication and authorization framework
- Java Mail Sender → Sends price alert emails to users
- Lombok → Reduces boilerplate (auto-generates getters, setters, constructors)
- Spring Boot DevTools → Auto-restarts server on code changes during development
- JUnit → Test framework (runs tests, assertions)
- Mockito → Mocks dependencies in unit tests
- Docker Compose Support → Runs containers (PostgreSQL, etc.) with one command
- JWT → Token-based authentication (stateless login)
- Jsoup → Parses HTML from websites for price handling

## Front End Technology Used

- React → UI library (components, hooks, JSX)
- Next.js → Framework on top of React (routing, SSR, API routes)
- TypeScript → Type safety for JavaScript
- Tailwind CSS → Utility-first CSS framework for styling
- Axios → HTTP client for API calls to Spring backend
- Chart.js → Renders price history graphs
- NextAuth.js → Handles user authentication (JWT, sessions)
- ESLint → Linter that catches code errors and enforces consistency
- App Router → Next.js routing system (file-based, each folder = a route)

## Cloud Infrastructure Used

- AWS (EC2, RDS, S3, CloudFront, SES)
