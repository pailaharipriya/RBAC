# Role-Based Access Control (RBAC) UI

A modern, responsive Role-Based Access Control (RBAC) user interface built with React, TypeScript, and Tailwind CSS. This application provides a comprehensive solution for managing users, roles, and permissions in a secure and user-friendly way.

![RBAC UI Screenshot](https://images.unsplash.com/photo-1633356122544-f134324a6cee?auto=format&fit=crop&q=80&w=1920)

## Features

- 👥 **User Management**
  - View and manage user accounts
  - Assign roles to users
  - Track user status (active/inactive)
  - CRUD operations for user accounts

- 🛡️ **Role Management**
  - Create and manage roles
  - Assign permissions to roles
  - Visual permission indicators
  - Role-based access control
 
- 🔑 **Permission System**
  - Module-based permission grouping
  - Granular permission control
  - Clear permission descriptions
  - Visual permission overview

## Technology Stack

- **Frontend Framework**: React 18
- **Type System**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Code Quality**: ESLint

 ## Project Structure

```
src/
├── components/          # React components
│   ├── Sidebar.tsx     # Navigation sidebar
│   ├── UsersList.tsx   # User management
│   ├── RolesList.tsx   # Role management
│   └── PermissionsList.tsx # Permission overview
├── types/              # TypeScript interfaces
│   └── index.ts        # Type definitions
├── data/              # Mock data
│   └── mockData.ts    # Sample users, roles, permissions
└── App.tsx            # Main application component
```

## Getting Started

1. **Clone the repository**

```bash
git clone <repository-url>
cd rbac-ui
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npm run dev
```

4. **Build for production**

```bash
npm run build
```

## Usage

### Managing Users

- View all users in a table format
- Add new users with the "Add User" button
- Edit existing users by clicking the edit icon
- Delete users with the delete icon
- View user roles and status

### Managing Roles

- Create new roles with specific permissions
- Edit existing role permissions
- Delete roles when no longer needed
- View all permissions assigned to each role

### Viewing Permissions
- Browse permissions grouped by module
- View detailed permission descriptions
- Understand permission hierarchies

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Icons provided by [Lucide Icons](https://lucide.dev)
- UI components styled with [Tailwind CSS](https://tailwindcss.com)
- Built with [Vite](https://vitejs.dev) and [React](https://reactjs.org)
  
