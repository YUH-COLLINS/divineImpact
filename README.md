# Kingdom Assignment Foundation - Website

A comprehensive Christian foundation website built with React, Express.js, and Tailwind CSS, featuring donation system integration with Cameroon payment gateways (MTN Mobile Money & Orange Money).

## 🌟 Features

- **Responsive Design**: Mobile-first approach with beautiful UI
- **Program Management**: Four core programs (CTEP, WAN, KM, EC)
- **Donation System**: Integrated with Cameroon mobile money services
- **Event Management**: RSVP system for conferences and workshops
- **Blog & Gallery**: Content management for stories and photos
- **Volunteer Portal**: Application and management system
- **Prayer Requests**: Community prayer support system
- **Contact Forms**: Multiple contact channels
- **Newsletter**: Email subscription system
- **Admin Dashboard**: Content and donation management

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ and npm
- Docker and Docker Compose
- Visual Studio Code (recommended)

### Installation Commands

```bash
# Clone the repository
git clone <your-repo-url>
cd kingdom-assignment-foundation

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Start PostgreSQL with Docker
docker-compose up postgres -d

# Generate Prisma client and push schema
npx prisma generate
npx prisma db push

# Start development server
npm run dev
# divineImpact
