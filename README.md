# University Management System

A comprehensive web application for managing university data, courses, and student information built with Next.js, React, and TypeScript.

## 🚀 Features

### Core Functionality
- **Complete CRUD Operations** for Students, Courses, Instructors, Departments, and Enrollments
- **Multi-table Join Queries** with advanced database operations
- **Interactive Data Visualization** with charts and graphs
- **Real-time Dashboard** with statistics and metrics
- **Authentication System** with login functionality
- **Responsive Design** that works on all devices

### 5 Main Interfaces
1. **Login/Authentication Screen** - Secure access with validation
2. **Dashboard Interface** - Overview with key metrics and quick actions
3. **Data Management Interface** - CRUD operations for all database tables
4. **Advanced Queries Interface** - Complex multi-table database queries
5. **Data Visualization Interface** - Interactive charts and analytics

## 🏗️ Technical Stack

- **Framework**: Next.js 15 with App Router
- **Frontend**: React 19, TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Shadcn/ui
- **Charts**: Recharts
- **Database**: Mock data with proper schema structure

## 📋 Prerequisites

- Node.js 18+ 
- npm or yarn package manager

## 🛠️ Installation & Setup

1. **Clone or Download** the project
2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Open your browser** and navigate to:
   ```
   http://localhost:8000
   ```

## 🎯 Usage

### Login Credentials
- **Username**: admin
- **Password**: admin123

### Navigation
- **Dashboard**: View key metrics and statistics
- **Tables**: Manage all database records (Students, Courses, Instructors, Departments, Enrollments)
- **Queries**: Run predefined complex database queries
- **Visualization**: View interactive charts and data analytics
- **Login**: Authentication interface

### Available Operations
- **Create**: Add new records to any table
- **Read**: View all records with proper formatting
- **Update**: Modify existing records
- **Delete**: Remove records with confirmation
- **Query**: Execute complex multi-table joins
- **Visualize**: View data in charts and graphs

## 📊 Database Schema

The application includes a complete university database schema with 11 tables:

- **student**: Student information and enrollment details
- **course**: Course catalog with credits and departments
- **instructor**: Faculty information with salaries
- **department**: Department details with budgets
- **section**: Course sections and scheduling
- **teaches**: Instructor-course assignments
- **takes**: Student enrollments and grades
- **advisor**: Student-advisor relationships
- **time_slot**: Class scheduling information
- **prereq**: Course prerequisites
- **classroom**: Room and building information

## 🔧 API Endpoints

All endpoints support full CRUD operations:

- `GET/POST/PUT/DELETE /api/university/student`
- `GET/POST/PUT/DELETE /api/university/course`
- `GET/POST/PUT/DELETE /api/university/instructor`
- `GET/POST/PUT/DELETE /api/university/department`
- `GET/POST/PUT/DELETE /api/university/takes`
- `GET /api/university/join` (for complex queries)

## 📁 Project Structure

```
university-management-system/
├── src/
│   ├── app/
│   │   ├── api/university/          # API routes
│   │   ├── dashboard/               # Dashboard page
│   │   ├── login/                   # Authentication
│   │   ├── tables/                  # Data management
│   │   ├── queries/                 # Advanced queries
│   │   ├── visualization/           # Charts and analytics
│   │   ├── layout.tsx               # Main layout
│   │   └── page.tsx                 # Homepage
│   ├── components/ui/               # Reusable UI components
│   └── lib/                         # Utility functions
├── database/
│   └── university_schema.sql        # Complete database schema
├── package.json                     # Dependencies and scripts
└── README.md                        # This file
```

## 🎨 UI Features

- **Modern Design**: Clean, professional interface
- **Responsive Layout**: Works on desktop, tablet, and mobile
- **Interactive Elements**: Hover effects, loading states, animations
- **Data Tables**: Sortable, searchable data grids
- **Charts**: Bar charts, pie charts, and analytics
- **Form Validation**: Real-time input validation
- **Error Handling**: Graceful error messages and fallbacks

## 🚀 Deployment

### Build for Production
```bash
npm run build
npm start
```

### Environment Variables
No additional environment variables required for basic functionality.

## 🔍 Testing

The application includes:
- **Mock Data**: Realistic university data for testing
- **Error Handling**: Comprehensive error management
- **Validation**: Form and data validation
- **Responsive Testing**: Cross-device compatibility

## 📝 Development Notes

- **TypeScript**: Full type safety throughout the application
- **ESLint**: Code quality and consistency
- **Tailwind CSS**: Utility-first styling approach
- **Component Architecture**: Modular, reusable components
- **API Design**: RESTful endpoints with proper HTTP methods

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 🆘 Support

For issues or questions:
1. Check the console for error messages
2. Verify all dependencies are installed
3. Ensure Node.js version compatibility
4. Check that port 8000 is available

## 🎯 Future Enhancements

- Real database integration (PostgreSQL, MySQL)
- User role management
- Advanced reporting features
- Email notifications
- File upload capabilities
- Advanced search and filtering
- Data export functionality

---

**University Management System** - A complete solution for educational institution data management.
