<!-- Front end -->

```
├── 📁 .git/ 🚫 (auto-hidden)
├── 📁 build/ 🚫 (auto-hidden)
├── 📁 node_modules/ 🚫 (auto-hidden)
├── 📁 public/
│   ├── 📁 idea/
│   ├── 📁 images/
│   │   ├── 🖼️ HOSOBAOGIA-Photoroom.png
│   │   ├── 🖼️ HOSOBAOGIA.png
│   │   ├── 🖼️ abc.png
│   │   ├── 🖼️ backgroundlogin.jpg
│   │   ├── 🖼️ bom.png
│   │   ├── 🖼️ icon-thaco.png
│   │   ├── 🖼️ industries.png
│   │   ├── 🖼️ logo-excel.png
│   │   └── 🖼️ thaco-industries.png
│   ├── 📁 pdf/
│   │   ├── 📕 approveBom.pdf
│   │   ├── 📕 bom.pdf
│   │   ├── 📕 dmvt.pdf
│   │   ├── 📕 login.pdf
│   │   ├── 📕 material.pdf
│   │   └── 📕 page.pdf
│   ├── 📊 BM10.xlsx
│   ├── 🖼️ favicon.ico
│   ├── 🖼️ icon.png
│   ├── 🌐 index.html
│   ├── 🖼️ logo192.png
│   ├── 🖼️ logo512.png
│   ├── 📄 manifest.json
│   ├── 📦 pdf.rar
│   ├── 📄 robots.txt
│   └── 📊 template.xlsx
├── 📁 src/
│   ├── 📁 Auth/
│   │   └── 📄 AuthContext.jsx
│   ├── 📁 api/
│   │   ├── 📄 apiPrivate.js
│   │   └── 📄 apiPublic.js
│   ├── 📁 assets/
│   │   └── 📁 images/
│   │       ├── 🖼️ HOSOBAOGIA-Photoroom.png
│   │       ├── 🖼️ HOSOBAOGIA.png
│   │       ├── 🖼️ abc.png
│   │       ├── 🖼️ backgroundlogin.jpg
│   │       ├── 🖼️ bom.png
│   │       ├── 🖼️ icon-thaco.png
│   │       ├── 🖼️ industries.png
│   │       ├── 🖼️ logo-excel.png
│   │       └── 🖼️ thaco-industries.png
│   ├── 📁 components/
│   │   └── 📁 global/
│   ├── 📁 constants/
│   │   └── 📄 constants.js
│   ├── 📁 hooks/
│   │   └── 📄 useFetchData.js
│   ├── 📁 layout/
│   │   ├── 📄 Header.js
│   │   ├── 🎨 Header.module.css
│   │   ├── 📄 PrivateRoute.js
│   │   ├── 🎨 SideBar.css
│   │   ├── 📄 SideBar.js
│   │   └── 🎨 SideBar.module.css
│   ├── 📁 lottie/
│   │   ├── 📄 404page.json
│   │   ├── 📄 btnLogin.json
│   │   ├── 📄 complete.json
│   │   ├── 📄 loading.json
│   │   ├── 📄 login.json
│   │   └── 📄 noData.json
│   ├── 📁 pages/
│   │   ├── 📁 DataField/
│   │   │   ├── 📁 DataCode/
│   │   │   │   ├── 📄 CreateData.js
│   │   │   │   ├── 📄 DataCode.js
│   │   │   │   └── 📄 EditData.js
│   │   │   ├── 📁 DataMaterial/
│   │   │   │   ├── 📄 CreateDataMaterial.js
│   │   │   │   ├── 📄 DataMaterial.js
│   │   │   │   └── 📄 EditDataMaterial.js
│   │   │   ├── 🎨 DataField.module.css
│   │   │   └── 📄 DataFieldMain.js
│   │   ├── 📁 Home/
│   │   │   ├── 📄 Home.js
│   │   │   ├── 🎨 Home.module.css
│   │   │   ├── 📄 TableBomCustom.js
│   │   │   └── 📄 TableWaitingApprove.js
│   │   ├── 📁 Idea/
│   │   │   └── 📄 Idea.js
│   │   ├── 📁 Instruction/
│   │   │   └── 📄 Instruction.js
│   │   ├── 📁 Login/
│   │   │   ├── 🎨 LoginPage.css
│   │   │   ├── 📄 LoginPage.js
│   │   │   └── 🎨 LoginPage.module.css
│   │   ├── 📁 NoPermissionAndError/
│   │   │   ├── 📄 ErrorPage.js
│   │   │   ├── 📄 NoPermissionPage.js
│   │   │   └── 📄 NotFoundPage.js
│   │   ├── 📁 Projects/
│   │   │   ├── 📄 Projects.js
│   │   │   └── 🎨 Projects.module.css
│   │   ├── 📁 Request/
│   │   │   ├── 📁 RequestCreate/
│   │   │   │   ├── 📄 ApproveTableOfManager.js
│   │   │   │   ├── 📄 ApprovedTable.js
│   │   │   │   ├── 📄 CancelTable.js
│   │   │   │   ├── 📄 EditCreateDmvt.js
│   │   │   │   ├── 🎨 EditCreateDmvt.module.css
│   │   │   │   ├── 📄 EditCreateMaterial.js
│   │   │   │   ├── 🎨 EditCreateMaterial.module.css
│   │   │   │   ├── 📄 RejectedTable.js
│   │   │   │   ├── 📄 RequestCreate.js
│   │   │   │   ├── 🎨 RequestCreate.module.css
│   │   │   │   └── 📄 WaitingTable.js
│   │   │   ├── 📁 RequestDelete/
│   │   │   │   ├── 📄 RequestDelete.js
│   │   │   │   ├── 📄 TableForAdmin.js
│   │   │   │   └── 📄 TableForUser.js
│   │   │   ├── 📁 RequestEdit/
│   │   │   │   ├── 📄 ApproveTableOfManager.js
│   │   │   │   ├── 📄 ApprovedTable.js
│   │   │   │   ├── 📄 CancelTable.js
│   │   │   │   ├── 📄 EditEditMaterial.js
│   │   │   │   ├── 🎨 EditEditMaterial.module.css
│   │   │   │   ├── 📄 RejectedTable.js
│   │   │   │   ├── 📄 RequestEdit.js
│   │   │   │   ├── 🎨 RequestEdit.module.css
│   │   │   │   └── 📄 WaitingTable.js
│   │   │   └── 📄 modalHelpers.js
│   │   ├── 📁 dmvt/
│   │   │   ├── 📁 DmvtCreate/
│   │   │   │   ├── 📄 DmvtCreate.js
│   │   │   │   └── 🎨 DmvtCreate.module.css
│   │   │   ├── 📁 DmvtDetail/
│   │   │   │   ├── 📁 Cost/
│   │   │   │   ├── 📁 CreateBom/
│   │   │   │   │   ├── 📄 CreateBom.js
│   │   │   │   │   └── 🎨 CreateBom.module.css
│   │   │   │   ├── 📁 EditBom/
│   │   │   │   │   ├── 📄 EditBom.js
│   │   │   │   │   └── 🎨 EditBom.module.css
│   │   │   │   ├── 📁 TableBomCreateOrEdit/
│   │   │   │   │   ├── 📁 TableRow/
│   │   │   │   │   │   ├── 📄 Sortable.js
│   │   │   │   │   │   └── 📄 TableRow.js
│   │   │   │   │   └── 📄 TableBom.js
│   │   │   │   ├── 📁 TableMaterialToAdd/
│   │   │   │   │   └── 📄 TableMaterialToAdd.js
│   │   │   │   ├── 📄 BomContainTable.js
│   │   │   │   ├── 📄 BomDetailTable.js
│   │   │   │   ├── 📄 DmvtDetail.js
│   │   │   │   └── 🎨 DmvtDetail.module.css
│   │   │   ├── 📁 DmvtEdit/
│   │   │   │   ├── 📄 DmvtEdit.js
│   │   │   │   └── 🎨 DmvtEdit.module.css
│   │   │   └── 📁 DmvtPage/
│   │   │       ├── 📄 DmvtPage.js
│   │   │       └── 🎨 DmvtPage.module.css
│   │   ├── 📁 material/
│   │   │   ├── 📁 MaterialCreate/
│   │   │   │   ├── 📄 MaterialCreate.js
│   │   │   │   └── 🎨 MaterialCreate.module.css
│   │   │   ├── 📁 MaterialDetail/
│   │   │   │   ├── 📄 MaterialDetail.js
│   │   │   │   └── 🎨 MaterialDetail.module.css
│   │   │   ├── 📁 MaterialEdit/
│   │   │   │   ├── 📄 MaterialEdit.js
│   │   │   │   └── 🎨 MaterialEdit.module.css
│   │   │   └── 📁 MaterialPage/
│   │   │       ├── 📄 MaterialPage.js
│   │   │       └── 🎨 MaterialPage.module.css
│   │   ├── 📁 statis/
│   │   │   ├── 📄 Statis.js
│   │   │   └── 🎨 Statis.module.css
│   │   └── 📁 user/
│   │       ├── 📁 UserDetail/
│   │       │   ├── 📄 TableBomApproved.js
│   │       │   ├── 📄 TableBomJoin.js
│   │       │   ├── 📄 UserDetail.js
│   │       │   └── 🎨 UserDetail.module.css
│   │       ├── 📄 TableUser.js
│   │       ├── 📄 User.js
│   │       └── 🎨 User.module.css
│   ├── 📁 redux/
│   │   ├── 📄 counterSlice.js
│   │   ├── 📄 notiUpdateSlice.js
│   │   ├── 📄 sideBarUpdateSlice.js
│   │   └── 📄 store.js
│   ├── 📁 routes/
│   │   └── 📄 Routes.js
│   ├── 📁 services/
│   │   ├── 📄 bomService.js
│   │   ├── 📄 dmvtService.js
│   │   ├── 📄 homeService.js
│   │   ├── 📄 loginService.js
│   │   ├── 📄 materialService.js
│   │   ├── 📄 projectService.js
│   │   └── 📄 sortService.js
│   ├── 📁 styles/
│   │   └── 📁 global/
│   │       ├── 🎨 Global.css
│   │       └── 📄 index.js
│   ├── 📁 utils/
│   │   └── 📁 excel/
│   │       ├── 📄 exportDmvtToExcel.js
│   │       ├── 📄 exportMaterialToExcel.js
│   │       └── 📄 exportToExcel.js
│   ├── 🎨 App.css
│   ├── 📄 App.js
│   ├── 📄 App.test.js
│   ├── 🎨 index.css
│   ├── 📄 index.js
│   ├── 🖼️ logo.svg
│   ├── 📄 reportWebVitals.js
│   └── 📄 setupTests.js
├── 🔒 .env 🚫 (auto-hidden)
├── 🚫 .gitignore
├── 🐳 Dockerfile 🚫 (auto-hidden)
├── 📖 README.md
├── 📄 craco.config.js
├── 📄 jsonconfig.json
├── 📄 package-lock.json
├── 📄 package.json
├── 📄 tailwind.config.js
└── 📄 updateImports.js
```
---




<!-- Back end -->


```
├── 📁 .git/ 🚫 (auto-hidden)
├── 📁 node_modules/ 🚫 (auto-hidden)
├── 📁 src/
│   ├── 📁 app/
│   │   ├── 📁 cache/ 🚫 (auto-hidden)
│   │   ├── 📁 config/
│   │   │   ├── 📄 database.js
│   │   │   ├── 📄 database2.js
│   │   │   └── 📄 databasePromise.js
│   │   ├── 📁 controllers/
│   │   │   ├── 📄 BomController.js
│   │   │   ├── 📄 CheckPermissionController.js
│   │   │   ├── 📄 DataFieldController.js
│   │   │   ├── 📄 DmvtsControllers.js
│   │   │   ├── 📄 HomeController.js
│   │   │   ├── 📄 IdeaController.js
│   │   │   ├── 📄 LoginController.js
│   │   │   ├── 📄 MaterialsController.js
│   │   │   ├── 📄 PostFromQldaController.js
│   │   │   ├── 📄 ProjectController.js
│   │   │   ├── 📄 RequestCreateController.js
│   │   │   ├── 📄 RequestDeleteController.js
│   │   │   ├── 📄 RequestEditController.js
│   │   │   ├── 📄 SortController.js
│   │   │   ├── 📄 StatisticController.js
│   │   │   └── 📄 UsersController.js
│   │   ├── 📁 models/
│   │   │   ├── 📄 Bom.js
│   │   │   ├── 📄 CheckUserPermission.js
│   │   │   ├── 📄 DataField.js
│   │   │   ├── 📄 Dmvt.js
│   │   │   ├── 📄 Home.js
│   │   │   ├── 📄 Idea.js
│   │   │   ├── 📄 Login.js
│   │   │   ├── 📄 Materials.js
│   │   │   ├── 📄 PostFromQlda.js
│   │   │   ├── 📄 Project.js
│   │   │   ├── 📄 RequestCreate.js
│   │   │   ├── 📄 RequestDelete.js
│   │   │   ├── 📄 RequestEdit.js
│   │   │   ├── 📄 Sort.js
│   │   │   ├── 📄 Statistic.js
│   │   │   └── 📄 Users.js
│   │   └── 📁 synchronous/
│   │       ├── 📄 syncMembers.js
│   │       ├── 📄 syncProjects.js
│   │       └── 📄 syncUsers.js
│   ├── 📁 middleware/
│   │   ├── 📄 authMiddleware.js
│   │   ├── 📄 checkUserPermission.js
│   │   ├── 📄 multerIdea.js
│   │   └── 📄 multerMaterial.js
│   ├── 📁 public/
│   │   └── 📁 images/ 🚫 (auto-hidden)
│   ├── 📁 routes/
│   │   ├── 📄 bom.js
│   │   ├── 📄 check-permission.js
│   │   ├── 📄 data-field.js
│   │   ├── 📄 dmvt.js
│   │   ├── 📄 home.js
│   │   ├── 📄 idea.js
│   │   ├── 📄 index.js
│   │   ├── 📄 login.js
│   │   ├── 📄 material.js
│   │   ├── 📄 post-from-qlda.js
│   │   ├── 📄 project.js
│   │   ├── 📄 request.js
│   │   ├── 📄 sort.js
│   │   ├── 📄 statistic.js
│   │   ├── 📄 sync.js
│   │   └── 📄 user.js
│   └── 📄 index.js
├── 🔒 .env 🚫 (auto-hidden)
├── 🚫 .gitignore
├── 📄 HashedPassword.js
├── 📄 addImage.js
├── 📄 package-lock.json 🚫 (auto-hidden)
└── 📄 package.json
```