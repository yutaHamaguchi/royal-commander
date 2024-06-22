Below is the translated and detailed specification document for developing a game similar to "Royal Revolt 2" using Unreal Engine 5. This includes the Game Design Document (GDD) and the Technical Specification Document.

## Game Design Document (GDD)

### 1. Game Overview
- **Title**: Royal Revolt 2 Clone
- **Genre**: Tower Defense, Real-Time Strategy
- **Platform**: PC, iOS, Android
- **Target Audience**: Gamers aged 13 and above

### 2. Gameplay
- **Basic Concept**: Players take on the role of a king, defending their castle while attacking other players' castles. They gather resources to upgrade and strengthen their castle and troops, aiming to build the strongest castle.
- **Key Game Mechanics**:
  - **Castle Construction and Upgrades**: Players upgrade and strengthen their castle facilities.
  - **Troop Training and Deployment**: Players train troops and deploy them during battles.
  - **Battles**: Players attack other players' castles to steal resources.
  - **Resource Management**: Players produce money and bread in taverns and farms to manage resources.
  - **Card System**: Character skills and troop upgrades are managed through cards. A card deck editing screen is not required in Phase 1 but will be needed in Phase 2 and beyond.

### 3. Game Flow
- **Tutorial**: A comprehensive tutorial at the start of the game teaches players the basic controls and strategies.
- **Castle Restoration**: Players restore a dilapidated castle and upgrade its facilities.
- **Battles**: Players attack other players' castles to acquire resources.
- **Upgrades**: Players use acquired resources to upgrade their castle and troops.

### 4. Characters and Units
- **Player Character**: The King (controlled by the player)
- **Types of Troops**: Initially, players start with a few types of troops, with more types becoming available as the barracks are upgraded.
- **Enemy Characters**: Troops and defense towers of other players

### 5. Level Design
- **Castle Layout**: Players draw paths and set traps with their fingers.
- **Tower Placement**: Players strategically place towers to prevent enemy advancement.

### 6. Art Style
- **Visual Theme**: Medieval Fantasy
- **Color Customization**: Players can change the coloring of their equipment.

### 7. Sound Design
- **Music**: Medieval-themed background music
- **Sound Effects**: Battle sounds, construction sounds, resource collection sounds

### 8. Monetization
- **In-App Purchases**: Players can use real money to purchase items and resources within the game.
- **Card Purchases**: Players can buy specific cards to enhance character skills and troop upgrades.

## Technical Specification Document

### 1. Development Environment
- **Game Engine**: Unreal Engine 5
- **Programming Language**: Blueprints
- **Version Control**: Git
- **Infrastructure**: AWS
- **Project Management and Bug Tracking**: GitHub Projects

### 2. System Requirements
- **Minimum System Requirements**:
  - **OS**: Windows 10, macOS 10.15, iOS 13, Android 8.0
  - **CPU**: Intel Core i5-2500K / AMD FX-6300
  - **RAM**: 8GB
  - **GPU**: NVIDIA GeForce GTX 770 / AMD Radeon R9 280
  - **Storage**: 20GB of free space

### 3. Architecture
- **Module Structure**:
  - **Core**: Basic game logic and data management
  - **UI**: User Interface
  - **AI**: Enemy behavior patterns and troop AI
  - **Networking**: Multiplayer functionality
  - **Rendering**: Graphics rendering

### 4. Database
- **Database Management System**: MySQL
- **Data Model**:
  - **Player Data**: User ID, castle status, resource amounts, types and numbers of troops
  - **Battle Data**: Battle history, wins and losses, acquired resources
  - **Card Data**: Types of cards, effects, ownership status

### 5. Network
- **Communication Protocol**: TCP/IP
- **Server**: Cloud servers using AWS
- **Security**: SSL/TLS encryption for communication

### 6. Test Plan
- **Unit Testing**: Functional testing of each module
- **Integration Testing**: Testing the interaction between modules
- **Load Testing**: Testing server load capacity
- **Usability Testing**: Testing player operability and game experience

This specification document will enable engineers to quickly start the game development process.
