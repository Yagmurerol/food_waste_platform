 🥗 FoodWaste – Food Waste Reduction & Sharing Platform

FoodWaste is a multi-tier platform designed to minimize food waste and enable safe surplus food distribution among restaurants, grocery stores, and individual users. The project bridges a scalable N-Tier .NET Core RESTful API backend service with a user-friendly mobile application.

📌 The Platform Includes

* 📦 **Surplus Food Listing & Inventory:** Listing consumable surplus items with category, quantity, and expiration date filters.
* 📍 **Location-Based Matching & Tracking:** Connecting food donors with beneficiaries or consumers through proximity-based workflow management.
* 🔐 **Secure Authentication & Hashing:** Robust authentication architecture featuring hash verification and secure credential workflows (`FoodWaste.Entities`, `_tmp_hashgen`).
* 📊 **Business Rules & Scenario Handling:** Comprehensive business layer managing role authorization and sustainability operations (`FoodWaste.Business`).
* 📱 **Mobile Client Interface:** Mobile application providing real-time feed exploration, map-based pickups, and listing creation (`food_waste_app`).
* ⚙️ **Automated CI/CD Pipeline:** Integrated GitHub Actions workflow to build, validate, and execute unit test suites on pushes (`backend-ci.yml`, `FoodWaste.Tests`).

 💡 My Contribution

* 🏗 **Layered Architecture (N-Tier):** Architected clean separation of concerns across API, Business, Data, and Entities layers.
* 🔗 **Database & ER Modeling:** Designed relational database schemas and Entity-Relationship diagrams (`foodwaste-er-diagram`).
* 🧪 **Unit Testing & Validation:** Developed automated unit test cases to verify business logic consistency (`FoodWaste.Tests`).
* 🔄 **Continuous Integration (CI):** Configured automated build and test pipelines using GitHub Actions (`backend-ci.yml`).
* 📱 **Mobile & API Integration:** Coordinated REST API endpoint communication and data serialization with the mobile client.
 🧠 What I Learned

* Applying enterprise N-Tier architectural patterns within ASP.NET Core.
* Designing relational databases and documenting data models using ER diagrams.
* Setting up automated CI pipelines with GitHub Actions to maintain code health.
* Writing isolated unit tests to safeguard critical domain logic.
* Bridging backend services with modern mobile frontend interfaces.

🛠 Tech Stack
* **Backend:** ASP.NET Core Web API, C#
* **Architecture:** N-Tier Architecture (API, Business, Data, Entities)
* **Database & ORM:** Relational Database, Entity Framework Core
* **Mobile:** Dart / Flutter (`food_waste_app`)
* **DevOps & CI/CD:** GitHub Actions (`backend-ci.yml`), Git
* **Documentation & Design:** Mermaid (`.mmd`), Markdown

🚀 Project Purpose

* Mitigate supply chain and retail-level food waste through digital coordination.
* Create a transparent, dependable, and measurable infrastructure for surplus food donation.
* Apply scalable backend engineering, automated testing, and cross-platform mobile integration to a social impact initiative.
