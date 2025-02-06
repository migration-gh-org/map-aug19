# 📺 MapApp

**MapApp** is a sleek and intuitive iOS application built with **SwiftUI**, allowing users to explore different locations and view detailed information about them.

## ✨ Overview

MapApp provides users with an interactive experience to **explore various locations on a map**. Users can tap on markers to reveal details, search for specific locations, and seamlessly navigate through the app.

## 🚀 Features

- **Interactive Map** – Explore locations using a dynamic **MapKit-powered** interface.  
- **Search Functionality** – Quickly find locations by name or city.  
- **Location Details** – View in-depth information, including **images, descriptions, and links**.  
- **Seamless Navigation** – Effortlessly switch between map views and detailed pages.  

## 🏭️ Architecture

MapApp follows the **Model-View-Controller (MVC)** architecture for maintainability and scalability:

- **Model** – `Location` struct stores data like name, coordinates, description, and images.
- **View** – SwiftUI views such as `LocationView`, `LocationListView`, and `LocationDetailsView` handle UI presentation.
- **Controller** – `LocationViewModel` manages data flow, search queries, and interactions.

## 🛠️ Code Structure

- `LocationView` – Displays the main map interface with **search and location previews**.  
- `LocationListView` – Shows a list of all available locations.  
- `LocationDetailsView` – Provides **detailed information, images, and links** for a selected location.  
- `LocationViewModel` – Manages **data retrieval, selection, and search functionality**.

## 📸 Screenshots

<table align="center">
  <tr>
    <td align="center"><img src="ScreenShots/Screenshot-01.png" width="300" alt="Home Page"/></td>
    <td align="center"><img src="ScreenShots/Screenshot-02.png" width="300" alt="Location DropDown"/></td>
  </tr>
  <tr>
    <td align="center"><img src="ScreenShots/Screenshot-03.png" width="300" alt="Location Details"/></td>
    <td align="center"><img src="ScreenShots/Screenshot-04.png" width="300" alt="Location Description and Map"/></td>
  </tr>
</table>

## 💾 Installation

To install and run MapApp on your iOS device:

1️⃣ **Clone** the repository to your local machine:  
   ```sh
   git clone https://github.com/your-username/MapApp.git
   ```
2️⃣ **Open** the project in Xcode.  
3️⃣ **Build & Run** the app on an **iOS device or simulator**.

## 📌 Requirements

✅ **iOS 14.0+**  
✅ **Xcode 12.0+**  

## 👏 Acknowledgments  

Special thanks to:  
- [SwiftfulThinking](https://www.youtube.com/@SwiftfulThinking) for SwiftUI tutorials and inspiration.  

## 📧 Contact  

💼 **Sabbir Nasir**  
- 🔗 LinkedIn: [Sabbir Nasir](https://www.linkedin.com/in/sabbirn26/)  
- 🛠️ GitHub: [@sabbirn26](https://github.com/sabbirn26)  

---

🚀 **Made with ❤️ using SwiftUI!**  
