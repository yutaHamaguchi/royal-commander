# royal-commander



## Game Design Document (GDD)

### 1. Game Overview
- **Title**: Royal Revolt 2 Clone
- **Genre**: Tower Defense, Real-Time Strategy
- **Platform**: PC, iOS, Android
- **Target Audience**: Gamers aged 13 and above

### 2. Gameplay
- **Core Concept**: Players become kings, defending their own castles while attacking others. They gather resources to upgrade and strengthen their castles and soldiers, aiming to build the strongest castle.
- **Key Game Mechanics**:
  - **Castle Construction and Upgrades**: Players upgrade and strengthen their castle facilities.
  - **Training and Deploying Soldiers**: Train soldiers and deploy them during battles.
  - **Battles**: Attack other players' castles to steal resources.
  - **Resource Management**: Produce money and bread in taverns and farms, and manage resources.
  - **Card Deck Editing**: Character skills and soldier enhancements are managed through cards. The card deck editing screen is required from Phase 2 onwards.

### 3. Game Flow
- **Tutorial**: A detailed tutorial at the start of the game teaches players basic operations and strategies.
- **Castle Restoration**: Restore a dilapidated castle and upgrade its facilities.
- **Battles**: Attack other players' castles to acquire resources.
- **Upgrades**: Use acquired resources to upgrade the castle and soldiers.
- **Card Deck Editing**: Use the card deck editing screen from Phase 2 onwards to manage character skills and soldier enhancements.

### 4. Characters and Units
- **Player Character**: The King (controlled by the player)
- **Types of Soldiers**: Start with a few types of soldiers, with more types unlocked as the training grounds are upgraded.
- **Enemy Characters**: Soldiers and defense towers of other players

### 5. Level Design
- **Castle Layout**: Players draw paths and set traps.
- **Tower Placement**: Strategically place towers to prevent enemy advancement.

### 6. Art Style
- **Visual Theme**: Medieval Fantasy
- **Color Customization**: Players can change the coloring of their equipment.

### 7. Sound Design
- **Music**: Medieval-style background music
- **Sound Effects**: Battle sounds, construction sounds, resource collection sounds

### 8. Card Deck Editing Screen
- **Deck Construction**:
  - **Number of Cards in Deck**: Players can choose the number of cards in their deck (e.g., 30, 40, 60).
  - **Card Search**: Players can search for and select cards to add to their deck.
  - **Drag & Drop**: Add or remove cards from the deck using drag and drop.
  - **Regulation Check**: Function to check if the deck complies with game rules.
  - **Deck Name and Sleeve Change**: Change the deck name and card sleeves (card back design).
  - **Save and Load Decks**: Save edited decks and load them later.

## Technical Specifications

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
  - **UI**: User interface
  - **AI**: Enemy behavior patterns and soldier AI
  - **Networking**: Multiplayer functionality
  - **Rendering**: Graphics rendering

### 4. Database
- **Database Management System**: MySQL
- **Data Model**:
  - **Player Data**: User ID, castle status, resource amounts, types and numbers of soldiers
  - **Battle Data**: Battle history, wins and losses, acquired resources
  - **Card Data**: Card ID, card name, card effects, rarity

### 5. Network
- **Communication Protocol**: TCP/IP
- **Server**: Cloud server using AWS
- **Security**: SSL/TLS encryption for communication

### 6. Test Plan
- **Unit Testing**: Functional testing of each module
- **Integration Testing**: Testing the interaction between modules
- **Load Testing**: Testing server load capacity
- **Usability Testing**: Testing player operability and game experience

---
