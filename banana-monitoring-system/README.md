
```
├── 📁 dist/ 🚫 (auto-hidden)
├── 📁 node_modules/ 🚫 (auto-hidden)
├── 📁 public/
│   ├── 📁 images/
│   │   ├── 📁 flag/
│   │   │   ├── 🖼️ china.png
│   │   │   └── 🖼️ japan.png
│   │   ├── 📁 language/
│   │   │   ├── 🖼️ en.png
│   │   │   └── 🖼️ vi.png
│   │   └── 📁 logo/
│   │       ├── 🖼️ background.png
│   │       ├── 🖼️ background1.png
│   │       ├── 🖼️ logo.png
│   │       └── 🖼️ logo_agri.png
│   ├── 📁 report/
│   │   ├── 📊 template_data_export_storage_report.xlsx
│   │   ├── 📊 template_data_storage_report.xlsx
│   │   ├── 📊 template_detailed_report.xlsx
│   │   ├── 📊 template_overall_report.xlsx
│   │   ├── 📊 template_overall_waiting_area_report.xlsx
│   │   └── 📊 template_plan_report.xlsx
│   └── 🖼️ banana.png
├── 📁 src/
│   ├── 📁 components/
│   │   └── 📁 ui/
│   │       ├── 📁 ant/
│   │       │   ├── 📄 Button.jsx
│   │       │   ├── 📄 DatePicker.jsx
│   │       │   ├── 📄 Input.jsx
│   │       │   ├── 📄 Menu.jsx
│   │       │   ├── 📄 Select.jsx
│   │       │   └── 📄 Table.jsx
│   │       ├── 📁 icon/
│   │       │   └── 📄 IconFontAwesome.jsx
│   │       └── 📁 normal/
│   │           ├── 📄 IconFontAwesome.jsx
│   │           └── 📄 Title.jsx
│   ├── 📁 configs/
│   │   ├── 📁 apis/
│   │   │   └── 📄 index.jsx
│   │   ├── 📁 menu/
│   │   │   └── 📄 index.jsx
│   │   ├── 📁 queryParams/
│   │   │   └── 📄 index.jsx
│   │   └── 📁 socket/
│   │       └── 📄 SocketContext.jsx
│   ├── 📁 fonts/
│   │   └── 📁 BeVietNamPro/
│   │       ├── 📄 BeVietnamPro-Black.ttf
│   │       ├── 📄 BeVietnamPro-BlackItalic.ttf
│   │       ├── 📄 BeVietnamPro-Bold.ttf
│   │       ├── 📄 BeVietnamPro-BoldItalic.ttf
│   │       ├── 📄 BeVietnamPro-ExtraBold.ttf
│   │       ├── 📄 BeVietnamPro-ExtraBoldItalic.ttf
│   │       ├── 📄 BeVietnamPro-ExtraLight.ttf
│   │       ├── 📄 BeVietnamPro-ExtraLightItalic.ttf
│   │       ├── 📄 BeVietnamPro-Italic.ttf
│   │       ├── 📄 BeVietnamPro-Light.ttf
│   │       ├── 📄 BeVietnamPro-LightItalic.ttf
│   │       ├── 📄 BeVietnamPro-Medium.ttf
│   │       ├── 📄 BeVietnamPro-MediumItalic.ttf
│   │       ├── 📄 BeVietnamPro-Regular.ttf
│   │       ├── 📄 BeVietnamPro-SemiBold.ttf
│   │       ├── 📄 BeVietnamPro-SemiBoldItalic.ttf
│   │       ├── 📄 BeVietnamPro-Thin.ttf
│   │       └── 📄 BeVietnamPro-ThinItalic.ttf
│   ├── 📁 hooks/
│   │   ├── 📄 socketInstance.js
│   │   └── 📄 useSocket.js
│   ├── 📁 locales/
│   │   ├── 📁 en/
│   │   │   └── 📄 translation.json
│   │   └── 📁 vi/
│   │       └── 📄 translation.json
│   ├── 📁 pages/
│   │   ├── 📁 layout/
│   │   │   ├── 📄 Header.jsx
│   │   │   ├── 📄 MenuList.jsx
│   │   │   ├── 📄 MenuMain.jsx
│   │   │   └── 📄 Navbar.jsx
│   │   ├── 📁 snoul/
│   │   │   └── 📁 bp1-1/
│   │   │       ├── 📁 exporting-storage/
│   │   │       │   ├── 📁 Images/
│   │   │       │   │   ├── 🖼️ ban.svg
│   │   │       │   │   ├── 🖼️ pallet.svg
│   │   │       │   │   ├── 🖼️ print.svg
│   │   │       │   │   └── 🖼️ truck.svg
│   │   │       │   ├── 📄 Data.jsx
│   │   │       │   ├── 📄 DataContainer.jsx
│   │   │       │   ├── 📄 DataImportContainer.jsx
│   │   │       │   ├── 🎨 Exporting.scss
│   │   │       │   └── 📄 Monitor.jsx
│   │   │       ├── 📁 packaging-area/
│   │   │       │   ├── 📁 data/
│   │   │       │   │   ├── 📄 Chart.jsx
│   │   │       │   │   ├── 📄 Data.jsx
│   │   │       │   │   ├── 📄 DetailedStatistic.jsx
│   │   │       │   │   ├── 📄 OverallStatistic.jsx
│   │   │       │   │   └── 📄 Plan.jsx
│   │   │       │   └── 📁 monitor/
│   │   │       │       ├── 📄 Module.jsx
│   │   │       │       ├── 📄 Monitor.jsx
│   │   │       │       └── 📄 Overall.jsx
│   │   │       ├── 📁 setting/
│   │   │       │   ├── 📁 settingUser/
│   │   │       │   │   ├── 📄 ModalAdd.jsx
│   │   │       │   │   └── 📄 SettingUser.jsx
│   │   │       │   ├── 📄 ModalDetail.jsx
│   │   │       │   ├── 📄 Setting.jsx
│   │   │       │   ├── 📄 SettingCountry.jsx
│   │   │       │   ├── 📄 SettingFarm.jsx
│   │   │       │   ├── 📄 SettingGates.jsx
│   │   │       │   ├── 📄 SettingGroupType.jsx
│   │   │       │   ├── 📄 SettingModule.jsx
│   │   │       │   ├── 🎨 SettingStyle.scss
│   │   │       │   ├── 📄 SettingTypeBanana.jsx
│   │   │       │   └── 📄 SettingUi.jsx
│   │   │       ├── 📁 storage-area/
│   │   │       │   ├── 📄 Data.jsx
│   │   │       │   └── 📄 Monitor.jsx
│   │   │       ├── 📁 waiting-area/
│   │   │       │   ├── 📁 data/
│   │   │       │   │   ├── 📄 Chart.jsx
│   │   │       │   │   ├── 📄 Data.jsx
│   │   │       │   │   └── 📄 Parameter.jsx
│   │   │       │   └── 📄 Monitor.jsx
│   │   │       ├── 📄 Overall.jsx
│   │   │       ├── 📄 OverallDataDemo.jsx
│   │   │       └── 📄 OverallDemo.jsx
│   │   ├── 📄 Forbidden403.jsx
│   │   ├── 📄 HomePage.jsx
│   │   ├── 📄 Loading.jsx
│   │   └── 📄 Login.jsx
│   ├── 📁 redux/
│   │   ├── 📁 actions/
│   │   │   └── 📄 index.js
│   │   ├── 📁 reducers/
│   │   │   ├── 📄 index.js
│   │   │   └── 📄 reducers.js
│   │   ├── 📁 types/
│   │   │   └── 📄 index.js
│   │   └── 📄 index.js
│   ├── 📁 services/
│   │   ├── 📄 error.service.jsx
│   │   ├── 📄 kho_mat.server.jsx
│   │   ├── 📄 khu_dong_goi.server.jsx
│   │   ├── 📄 khu_tram_cho.server.jsx
│   │   ├── 📄 module.server.jsx
│   │   ├── 📄 module_dong_goi.service.jsx
│   │   ├── 📄 nhom_pham_cap.server.jsx
│   │   ├── 📄 nongTruong.service.jsx
│   │   ├── 📄 nuoc_xuat_khau.server.jsx
│   │   ├── 📄 pham_cap_chuoi.jsx
│   │   ├── 📄 socket.service.jsx
│   │   ├── 📄 system.service.jsx
│   │   ├── 📄 tag.service.jsx
│   │   ├── 📄 user.service.jsx
│   │   └── 📄 xuat_kho.server.jsx
│   ├── 📁 styles/
│   │   ├── 🎨 _element.scss
│   │   ├── 🎨 _fonts.scss
│   │   ├── 🎨 _global.scss
│   │   ├── 🎨 _vars.scss
│   │   └── 🎨 index.scss
│   ├── 📁 utils/
│   │   ├── 📁 download/
│   │   │   └── 📄 ExcelSystem.jsx
│   │   ├── 📁 language/
│   │   │   └── 📄 i18n.jsx
│   │   ├── 📁 role/
│   │   │   └── 📄 PrivateRouter.jsx
│   │   └── 📁 tools/
│   │       └── 📄 index.jsx
│   ├── 📄 App.jsx
│   └── 📄 main.jsx
├── 🔒 .env 🚫 (auto-hidden)
├── 🚫 .gitignore
├── 📜 LICENSE
├── 📖 README.md
├── 📄 components.json
├── 📄 eslint.config.js
├── 📄 i18next-parser.config.js
├── 🌐 index.html
├── 📄 jsconfig.json
├── 📄 package-lock.json
├── 📄 package.json
├── 📄 postcss.config.js
├── 📄 tailwind.config.js
├── 📄 vite.config.js
└── 🔒 yarn.lock
```
