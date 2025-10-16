# Shuttle Monitoring & Control System

A real-time shuttle monitoring and control system that enables tracking shuttle operations on an interactive map, managing operational scenarios, and storing activity history.

## 🎯 Key Features

- **Real-time Monitoring**: Track shuttle position and status on an interactive map in real-time
- **Shuttle Control**: Send control commands and manage operational scenarios
- **Warehouse Management**: Create, edit, and manage warehouses where shuttles operate
- **Activity History**: Store and query movement history and scenario-based operations
- **Scenario Management**: Create and manage automated operational scenarios

## 🚀 Demo
- Setting warehouse
![alt text](image.png)
- Monitor Shuttle
![alt text](image-1.png)
## 📋 Prerequisites

- Node.js >= 16.x
- npm >= 8.x or yarn >= 1.22.x
- ES6+ compatible browser

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/khoascada/SHUTTLE_CORE_FE.git
cd shuttle-monitoring-system
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Configure environment variables:
```bash
cp .env.example .env
```

Edit the `.env` file with your configuration:
```env
VITE_API_BASE_URL=your_api_url
VITE_MAP_API_KEY=your_map_api_key
VITE_WS_URL=your_websocket_url
```

4. Run the application in development mode:
```bash
npm run dev

```

The application will run at `http://localhost:8084`

## 🏗️ Build for Production

```bash
npm run build

```

Preview the build:
```bash
npm run preview

```

## 💻 Tech Stack

- **Framework**: React 18 + Vite
- **UI Library**: Ant Design (antd)
- **Styling**: Tailwind CSS
- **State Management**: Redux Toolkit
- **Routing**: React Router
- **Real-time Communication**: WebSocket - SocketIO
- **HTTP Client**: Axios

## 📱 Main Features

### 1. Map Monitoring
- Display shuttle positions on interactive map
- Real-time position updates
- Route visualization
- Multiple shuttle tracking

### 2. Shuttle Control
- Send movement commands
- Start/stop operations
- Emergency stop
- Speed control

### 3. Warehouse Management
- Create new warehouses
- Edit warehouse layouts
- Define work zones
- Set shuttle operating areas

### 4. Scenario Management
- Create operational scenarios
- Schedule automated tasks
- Define waypoints and routes
- Monitor scenario execution

### 5. History & Logs
- View movement history
- Track scenario execution logs
- Export activity reports
- Filter by date/shuttle/scenario

## 🔧 Configuration

### Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `VITE_API_BASE_URL` | Backend API base URL | Yes |
| `VITE_MAP_API_KEY` | Map service API key | Yes |
| `VITE_WS_URL` | WebSocket server URL | Yes |
| `VITE_REFRESH_INTERVAL` | Map refresh interval (ms) | No |

### Map Configuration

Configure map settings in `src/config/map.config.js`:
```javascript
export const mapConfig = {
  center: [latitude, longitude],
  zoom: 15,
  maxZoom: 20,
  minZoom: 10
}
```

## 📚 Usage

### Monitoring Shuttles
1. Navigate to the Dashboard
2. Select warehouse from dropdown
3. View shuttles on the map
4. Click on shuttle markers for detailed information

### Creating a Scenario
1. Go to Scenarios page
2. Click "Create New Scenario"
3. Define waypoints on the map
4. Set actions at each waypoint
5. Save and assign to shuttle

### Managing Warehouses
1. Access Warehouse Management
2. Click "Add Warehouse"
3. Draw warehouse boundaries on map
4. Define zones and obstacles
5. Save configuration

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Code Style
- Follow ESLint configuration
- Use Prettier for formatting
- Write meaningful commit messages
- Add comments for complex logic

## Structure Project
```
├── 📁 .git/ 🚫 (auto-hidden)
├── 📁 node_modules/ 🚫 (auto-hidden)
├── 📁 public/
│   └── 🖼️ vite.svg
├── 📁 src/
│   ├── 📁 api/
│   │   └── 📄 index.js
│   ├── 📁 assets/
│   │   ├── 🖼️ abc.png
│   │   ├── 🖼️ login_background.jpg
│   │   ├── 🖼️ login_warehouse.jpg
│   │   ├── 🖼️ logo-thaco.png
│   │   └── 🖼️ userlog.png
│   ├── 📁 components/
│   │   ├── 📁 antd/
│   │   │   ├── 📁 button/
│   │   │   │   ├── 📄 CustomButton.jsx
│   │   │   │   └── 🎨 CustomButton.module.css
│   │   │   ├── 📁 card/
│   │   │   │   ├── 📄 CustomCard.jsx
│   │   │   │   └── 🎨 CustomCard.module.css
│   │   │   ├── 📁 collapse/
│   │   │   │   ├── 📄 CustomCollapse.jsx
│   │   │   │   └── 🎨 CustomCollapse.module.css
│   │   │   ├── 📁 segmented/
│   │   │   │   ├── 📄 CustomSegmented.jsx
│   │   │   │   └── 🎨 CustomSegmented.module.css
│   │   │   └── 📁 table/
│   │   │       ├── 📄 CustomTable.jsx
│   │   │       └── 🎨 CustomTable.module.css
│   │   ├── 📁 icon/
│   │   │   ├── 📄 CustomIcon.jsx
│   │   │   ├── 🎨 CustomIcon.module.css
│   │   │   └── 📄 IconFontAwesome.jsx
│   │   ├── 📁 infoUser/
│   │   │   └── 📄 ModalInfoUser.jsx
│   │   └── 📁 layouts/
│   │       ├── 📄 Header.jsx
│   │       └── 📄 Sidebar.jsx
│   ├── 📁 constants/
│   │   └── 📄 index.js
│   ├── 📁 context/
│   ├── 📁 hooks/
│   │   ├── 📄 useDebounce.js
│   │   ├── 📄 useFetchService.js
│   │   └── 📄 useSocket.js
│   ├── 📁 layouts/
│   │   ├── 📄 AuthLayout.jsx
│   │   └── 📄 MainLayout.jsx
│   ├── 📁 mock/
│   │   ├── 📄 history.js
│   │   ├── 📄 mapPoint.js
│   │   ├── 📄 shuttle.js
│   │   ├── 📄 tasks.js
│   │   └── 📄 warehouseMock.js
│   ├── 📁 pages/
│   │   ├── 📁 admin/
│   │   │   ├── 📁 shuttle/
│   │   │   │   ├── 📄 ModalAdd.jsx
│   │   │   │   ├── 📄 ModalEdit.jsx
│   │   │   │   └── 📄 Shuttle.jsx
│   │   │   ├── 📁 users/
│   │   │   │   ├── 📄 ModalAdd.jsx
│   │   │   │   └── 📄 User.jsx
│   │   │   └── 📁 warehouse/
│   │   │       ├── 📁 list_warehouse/
│   │   │       │   ├── 📄 ModalAdd.jsx
│   │   │       │   └── 📄 Warehouse.jsx
│   │   │       └── 📁 setting/
│   │   │           ├── 📄 Area.jsx
│   │   │           ├── 📄 Declare.jsx
│   │   │           ├── 📄 Location.jsx
│   │   │           ├── 📄 Map copy.jsx
│   │   │           ├── 📄 Map.jsx
│   │   │           └── 📄 Setting.jsx
│   │   ├── 📁 login/
│   │   │   └── 📄 Login.jsx
│   │   ├── 📁 monitor/
│   │   │   ├── 📁 manual/
│   │   │   │   ├── 📄 Manual.jsx
│   │   │   │   └── 📄 SortableItem.jsx
│   │   │   ├── 📄 Collapse.jsx
│   │   │   ├── 📄 History.jsx
│   │   │   ├── 📄 Map.jsx
│   │   │   └── 📄 Monitor.jsx
│   │   ├── 📄 Forbidden.jsx
│   │   └── 📄 HomePage.jsx
│   ├── 📁 providers/
│   │   └── 📄 AuthProvider.jsx
│   ├── 📁 routes/
│   │   ├── 📄 PrivateRoute.jsx
│   │   └── 📄 index.jsx
│   ├── 📁 services/
│   │   ├── 📁 base/
│   │   │   └── 📄 BaseService.js
│   │   ├── 📄 cellService.js
│   │   ├── 📄 commonService.js
│   │   ├── 📄 shuttleService.js
│   │   ├── 📄 taskService.js
│   │   ├── 📄 userService.js
│   │   └── 📄 warehouseService.js
│   ├── 📁 store/
│   │   ├── 📁 middleware/
│   │   │   ├── 📄 authMiddleware.js
│   │   │   ├── 📄 index.js
│   │   │   └── 📄 persistMiddleware.js
│   │   ├── 📁 slices/
│   │   │   ├── 📄 authSlice.js
│   │   │   └── 📄 uiSlice.js
│   │   └── 📄 index.js
│   ├── 📁 styles/
│   │   ├── 🎨 colors.css
│   │   ├── 🎨 fonts.css
│   │   └── 🎨 fontsize.css
│   ├── 📁 utils/
│   │   ├── 📄 filterHelpers.js
│   │   ├── 📄 getKeysFrom.js
│   │   ├── 📄 notificationService.js
│   │   ├── 📄 storage.js
│   │   └── 📄 stringUtils.js
│   ├── 🎨 App.css
│   ├── 📄 App.jsx
│   ├── 🎨 index.css
│   └── 📄 main.jsx
├── 🔒 .env 🚫 (auto-hidden)
├── 📄 .env.development 🚫 (auto-hidden)
├── 📄 .env.production 🚫 (auto-hidden)
├── 🚫 .gitignore
├── 📄 .prettierignore
├── 📄 .prettierrc
├── 📖 README.md
├── 📄 eslint.config.js
├── 🌐 index.html
├── 📄 package-lock.json
├── 📄 package.json
└── 📄 vite.config.js
```

---

## 📝 License

[Specify your license - e.g., MIT, Apache 2.0, etc.]

## 👥 Authors

- **Your Name** - *Initial work* - [YourGithub](https://github.com/yourusername)

## 📞 Contact

- Email: hinkhoa28@gmail.com
- Project Link: [https://github.com/yourusername/shuttle-monitoring](https://github.com/yourusername/shuttle-monitoring)

## 🙏 Acknowledgments

- [List any libraries, tools, or resources you want to credit]
- [Contributors or inspiration sources]

---

Made with ❤️ by Nguyen Phuc Dang Khoa

