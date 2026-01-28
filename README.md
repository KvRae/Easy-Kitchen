<h2 align="center"><b>Easy Kitchen</b></h2>
<h4 align="center">A comprehensive food recipe platform - Mobile, Web & Desktop applications</h4>

![easy kitchen](https://github.com/KvRae/Easy-Kitchen/assets/58667227/2fccf9a8-ab3d-42b8-8862-8a2a3fff477f)

## 🍽️ Description

"Roses are Red, Violets are Blue, so you're Hungry and you Don't Know What to Do!"

Easy Kitchen is a user-friendly and comprehensive food recipe platform designed to help users discover, share, and enjoy healthy recipes. The platform provides an intuitive interface with beautiful visual presentations of recipes, cooking tips, ingredient information, and nutrition guidance. It adopts thoughtful graphic elements and color solutions to make browsing and discovering new dishes an enjoyable experience.

### 🎯 Project Overview

Easy Kitchen is a **full-stack, multi-platform application** consisting of:
- **Mobile Applications**: Native iOS and Android apps built with modern frameworks
- **Web Application**: React-based web interface using Jetpack Compose
- **Backend API**: Node.js REST API server for data management
- **Database**: MongoDB integration for storing recipes, users, and comments

The project is currently in **BETA phase** and is actively being developed with regular updates to features and APIs.

## 📋 Table of Contents
- [Description](#description)
- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Tech Stack](#tech-stack)
- [Requirements](#requirements)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Usage](#usage)
- [Credits](#credits)
- [Contributing](#contributing)
- [License](#license)
- [Privacy Policy](#policy)
- [Questions](#questions)

## ✨ Features

- **Browse & Discover**: Explore thousands of recipes organized by categories and cuisines
- **Search & Filter**: Advanced search with filters by ingredients, cooking time, and difficulty level
- **User Accounts**: Create accounts, save favorite recipes, and track your cooking history
- **Recipe Details**: Comprehensive recipe information including ingredients, instructions, nutrition facts, and cooking tips
- **Comments & Ratings**: Share your feedback and read reviews from other users
- **Image Upload**: Upload and share photos of your cooked dishes
- **Multi-Platform**: Access your recipes across iOS, Android, Web, and Desktop applications
- **Responsive Design**: Beautiful UI that works seamlessly on all devices

## 📁 Project Structure

This is a **monorepo** containing multiple submodules:

```
Easy-Kitchen/
├── Easy-Kitchen-Android/       # Native Android application
├── Easy-Kitchen-IOS/           # Native iOS application  
├── Easy-Kitchen-Backend/       # Node.js REST API server
├── Easy-Kitchen-Compose/       # Jetpack Compose Desktop & Web app
├── Easy-Kitchen-Website/       # Web application interface
└── README.md                   # This file
```

### Submodule Descriptions

- **Easy-Kitchen-Android**: Native Android app built with modern Android development practices
- **Easy-Kitchen-IOS**: Native iOS app with Swift and SwiftUI
- **Easy-Kitchen-Backend**: Node.js/Express server handling all business logic and data management
- **Easy-Kitchen-Compose**: Native Android app built using Jetpack Compose
- **Easy-Kitchen-Website**: Responsive web application for browser access

## 🛠️ Tech Stack

### Frontend
- **Android**: Kotlin, XML layouts, MVVM architecture
- **iOS**: Swift, SwiftUI
- **Web/Desktop**: Jetpack Compose, React
- **UI/UX**: Material Design principles

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **File Storage**: Multer for image uploads

### Infrastructure
- **Docker**: Containerized deployment
- **API**: RESTful API architecture
  
## 📋 Requirements

### General Requirements
- Git (for cloning the repository and submodules)
- Node.js v14+ (for backend development)
- MongoDB (for database)

### For Android Development
- Android Studio 4.0+
- Android SDK 21+
- JDK 8+

### For iOS Development
- Xcode 12.0+
- Swift 5.0+
- iOS 12.0+

### For Web/Desktop Development
- Node.js v14+
- Modern web browser

### Documentation
For detailed project specifications and requirements, see: [Project Specifications Document](https://docs.google.com/document/d/1JPOoeVi4zhh0dRaGI5FAmBIi-SBxxCzN/edit?usp=sharing&ouid=105148018597387491435&rtpof=true&sd=true)

## 💻 Installation

### Clone the Repository with Submodules

```bash
# Clone with all submodules
git clone --recursive https://github.com/KvRae/Easy-Kitchen.git

# Or if you've already cloned, initialize submodules
cd Easy-Kitchen
git submodule update --init --recursive
```

### Setup Instructions by Platform

#### Backend Setup
```bash
cd Easy-Kitchen-Backend
npm install
# Configure your MongoDB connection in .env file
npm start
```

#### Android Setup
```bash
cd Easy-Kitchen-Android
# Open in Android Studio and sync Gradle
# Or build from command line
./gradlew build
```

#### iOS Setup
```bash
cd Easy-Kitchen-IOS
pod install
# Open EasyKitchen.xcworkspace in Xcode
```

#### Web/Desktop Setup
```bash
cd Easy-Kitchen-Compose
npm install
npm start
```

#### Website Setup
```bash
cd Easy-Kitchen-Website
npm install
npm start
```

### Download from App Stores
You can also download the latest release from:
- **Android**: Google Play Store or Huawei App Gallery
- **iOS**: Apple App Store

**NOTE**: This app is in **BETA phase**, so APIs and features may change frequently. Always refer to the latest documentation.

## Screenshots

<table>

  <tr>
    <td><img src="https://github.com/user-attachments/assets/4b2d998c-c585-427b-a373-2e5356362aef" alt="Easy Kitchen 1" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/d2ddf0da-61d8-4d6e-bcc5-57ed4e6b23dd" alt="Login Screen" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/7f122f70-8c66-41f3-9e10-65287ee9fd91" alt="Home Screen – 2" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/a4d6c41f-6871-4eaf-b022-181a0db2c005" alt="Home Screen – 2" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/5ea6ec42-faf6-45f1-b21b-ef98e95be12b" alt="Home Screen – 3" width="200"/></td>
    
  </tr>
  <tr>
    <td>Splash Screen</td>
    <td>Login Screen</td>
    <td>Home Screen </td>
    <td>Meals Screen</td>
    <td>Meal Detail Screen</td>
    
  </tr>
</table>



## 🚀 Usage

### For Users
1. Download the app from your device's app store or visit the website
2. Create an account with your email
3. Browse recipes by category or search for specific dishes
4. View detailed recipe information including ingredients and instructions
5. Save your favorite recipes for quick access
6. Upload photos of your cooked dishes
7. Rate and comment on recipes
8. Explore cooking tips and nutrition information

### For Developers
- Each submodule has its own README with detailed development instructions
- Refer to the API documentation in the Easy-Kitchen-Backend README
- Follow the code style and architecture patterns established in each module
- Submit pull requests for new features or bug fixes

## 👥 Credits

**Project Lead & Creator**: Karam Mannai ([@kvrae](https://github.com/kvrae))

**Contributors**: 
- Yassin Khabthani ([@medyassin-khabthani](https://github.com/medyassin-khabthani))

We thank all contributors who have helped make Easy Kitchen better!

## 🤝 Contributing

We welcome contributions from the community! To contribute to Easy Kitchen:

1. **Fork** the repository
2. **Create a new branch** for your feature (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add some amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request** with a detailed description of your changes

### Contribution Guidelines
- Follow the existing code style and architecture patterns
- Write clear commit messages
- Add tests for new features
- Update documentation as needed
- Be respectful and collaborative

### Areas for Contribution
- Bug fixes and improvements
- New recipe categories or features
- Performance optimizations
- UI/UX enhancements
- Documentation improvements
- Translations for other languages

## 📄 License

MIT License

Copyright (c) 2022-2026 Karam Mannai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 🔒 Privacy Policy
  
  **Privacy Policy**

KvRae, Glarados built the Easy Kitchen app as a Free app. This SERVICE is provided by KvRae, Glarados at no cost and is intended for use as is.

This page is used to inform visitors regarding my policies with the collection, use, and disclosure of Personal Information if anyone decided to use my Service.

If you choose to use my Service, then you agree to the collection and use of information in relation to this policy. The Personal Information that I collect is used for providing and improving the Service. I will not use or share your information with anyone except as described in this Privacy Policy.

The terms used in this Privacy Policy have the same meanings as in our Terms and Conditions, which are accessible at Easy Kitchen unless otherwise defined in this Privacy Policy.

**Information Collection and Use**

For a better experience, while using our Service, I may require you to provide us with certain personally identifiable information. The information that I request will be retained on your device and is not collected by me in any way.

The app does use third-party services that may collect information used to identify you.

Link to the privacy policy of third-party service providers used by the app

*   [App Store & Privacy](https://www.apple.com/legal/privacy/data/en/app-store/)

**Log Data**

I want to inform you that whenever you use my Service, in a case of an error in the app I collect data and information (through third-party products) on your phone called Log Data. This Log Data may include information such as your device Internet Protocol (“IP”) address, device name, operating system version, the configuration of the app when utilizing my Service, the time and date of your use of the Service, and other statistics.

**Cookies**

Cookies are files with a small amount of data that are commonly used as anonymous unique identifiers. These are sent to your browser from the websites that you visit and are stored on your device's internal memory.

This Service does not use these “cookies” explicitly. However, the app may use third-party code and libraries that use “cookies” to collect information and improve their services. You have the option to either accept or refuse these cookies and know when a cookie is being sent to your device. If you choose to refuse our cookies, you may not be able to use some portions of this Service.

**Service Providers**

I may employ third-party companies and individuals due to the following reasons:

*   To facilitate our Service;
*   To provide the Service on our behalf;
*   To perform Service-related services; or
*   To assist us in analyzing how our Service is used.

I want to inform users of this Service that these third parties have access to their Personal Information. The reason is to perform the tasks assigned to them on our behalf. However, they are obligated not to disclose or use the information for any other purpose.

**Security**

I value your trust in providing us your Personal Information, thus we are striving to use commercially acceptable means of protecting it. But remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable, and I cannot guarantee its absolute security.

**Links to Other Sites**

This Service may contain links to other sites. If you click on a third-party link, you will be directed to that site. Note that these external sites are not operated by me. Therefore, I strongly advise you to review the Privacy Policy of these websites. I have no control over and assume no responsibility for the content, privacy policies, or practices of any third-party sites or services.

**Children’s Privacy**

These Services do not address anyone under the age of 13. I do not knowingly collect personally identifiable information from children under 13 years of age. In the case I discover that a child under 13 has provided me with personal information, I immediately delete this from our servers. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact me so that I will be able to do the necessary actions.

**Changes to This Privacy Policy**

I may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. I will notify you of any changes by posting the new Privacy Policy on this page.

This policy is effective as of 2023-01-18

**Contact Us**

If you have any questions or suggestions about my Privacy Policy, do not hesitate to contact me at karamelmannai@gmail.com.

## ❓ Questions & Support

For questions, issues, or suggestions, please reach out to us:

- **Email**: [karamelmannai@gmail.com](mailto:karamelmannai@gmail.com)
- **GitHub Issues**: [Open an Issue](https://github.com/KvRae/Easy-Kitchen/issues)
- **Creator**: [Karam Mannai](https://github.com/kvrae)
- **Contributor**: [Yassin Khabthani](https://github.com/medyassin-khabthani)

---

<div align="center">
  <p>Made with ❤️ by the Easy Kitchen Team</p>
  <p>© 2022-2026 Easy Kitchen. All rights reserved.</p>
</div>
