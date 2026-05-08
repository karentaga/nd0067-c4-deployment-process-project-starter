# Application Dependencies

## 1. Backend (API) Dependencies

- **Runtime:** Node.js v14.15.0
- **Language:** TypeScript v4.2.3
- **Web Framework:** Express v4.16.4
- **Database (ORM):** Sequelize v6.26.0 & Sequelize-Typescript v2.1.5
- **Cloud Integration:** AWS SDK v2.429.0 (for S3 and Signed URLs)
- **Authentication:** JSON Web Token (JWT) v8.5.1 & BcryptJS v2.4.3
- **Database Driver:** pg (PostgreSQL) v8.7.1
- **Infrastructure:** AWS Elastic Beanstalk (EC2), AWS RDS (PostgreSQL)

## 2. Frontend (Client) Dependencies

- **Core Framework:** Angular v8.2.14
- **UI Toolkit:** Ionic Angular v4.1.0
- **Language:** TypeScript v3.5.3
- **Reactive Programming:** RxJS v6.5.4
- **Build Tools:** Angular CLI v8.3.25
- **Deployment:** custom `bin/deploy.sh` script
- **Infrastructure:** AWS S3 (Static Website Hosting)

## 3. Global Development Tools
- **AWS CLI:** For managing S3 buckets and IAM permissions.
- **EB CLI:** For managing Elastic Beanstalk environments and deployments.
- **npm:** Package manager for both frontend and backend libraries.

## 4. AWS Services
- **S3:** For storing user-uploaded images.
- **RDS:** For storing user and image metadata.
- **Elastic Beanstalk:** For deploying the backend API.
- **IAM:** For managing permissions for the backend API and frontend client.