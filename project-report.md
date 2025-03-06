# Software Praktikum (SoPra) - FS25
## Milestone 1 - Project Report

### Group Information
**Group Number:** [45]

**Group Members:**
| Name | UZH Email | Student ID | GitHub Username |
|------|-----------|------------|-----------------|
| [Yutian Lei] | [yutian.lei@uzh.ch] | [23-746-258] | [IsSaudade] |
| [Maorong Lin] | [maorong.lin@uzh.ch] | [23-746-761] | [Qavrox] |
| [Zhan Yang] | [zhan.yang@uzh.ch] | [24-742-603] | [zyangbg] |
| [Member 4] | [email4@uzh.ch] | [12-345-681] | [github-user4] |
| [Member 5] | [email5@uzh.ch] | [12-345-682] | [github-user5] |

## Project: CardMaster Arena

### Project Description (max. 150 words)
CardMaster Arena is a strategic online card game platform designed for multiplayer gameplay and competitive tournaments. The platform addresses the challenge of finding engaging and intellectually stimulating card games that incorporate modern AI capabilities. Players can register accounts, build customized decks, and compete in real-time multiplayer matches with intuitive drag-and-drop gameplay. The platform features AI-powered assistants that can provide strategic suggestions, analyze past games, and help organize card collections. CardMaster Arena also offers tournament organization, leaderboards, and social features like friend lists and direct messaging. The game's unique mechanics combine elements of resource management, strategic positioning, and tactical card combinations. By integrating AI technologies with competitive gameplay and community features, CardMaster Arena aims to create an engaging, strategic gaming experience for casual players and competitive enthusiasts alike.

## User Stories

### User Profile Management

#### ID: US1
**Category:** User Management  
**Story:** As a new user, I want to create an account with my credentials so that I can access the game platform and save my progress.  
**Acceptance Criteria:**
- Users can register with username, email, and password
- Email validation ensures that email addresses are valid
- Users receive a confirmation notification after successful registration
- Users can log in with their credentials after registration  

**Priority:** Critical  
**Estimate:** 8h

#### ID: US2
**Category:** User Management  
**Story:** As a registered user, I want to set up my gaming profile so that I can personalize my experience and be recognized by other players.  
**Acceptance Criteria:**
- Users can add a display name, avatar, and short biography
- Users can set their game preferences and notification settings
- Users can specify their skill level (beginner, intermediate, expert)
- Profile information can be edited at any time  

**Priority:** High  
**Estimate:** 6h

#### ID: US3
**Category:** User Management  
**Story:** As a user, I want to update my online/offline status so that other players know if I'm available for games.  
**Acceptance Criteria:**
- Users can toggle between "online," "busy," and "offline" status
- Status is visible to other users on friends list and in game lobbies
- Status automatically changes to "offline" after prolonged inactivity
- Users can set a custom status message (e.g., "Looking for tournament partners")  

**Priority:** Medium  
**Estimate:** 4h

### Deck Building and Card Management

#### ID: US4
**Category:** Card Management  
**Story:** As a player, I want to browse the available cards so that I can understand game mechanics and plan my strategy.  
**Acceptance Criteria:**
- Cards are organized by categories (attack, defense, special, etc.)
- Users can search cards by name, type, or attributes
- Card details include visual representation, stats, and effects
- Cards show rarity indicators and collection status  

**Priority:** Critical  
**Estimate:** 10h

#### ID: US5
**Category:** Card Management  
**Story:** As a player, I want to build and save multiple custom decks so that I can use different strategies for different game modes.  
**Acceptance Criteria:**
- Users can create named deck configurations
- Decks enforce game rules (min/max cards, card limits, etc.)
- Users can edit, duplicate, or delete existing decks
- System validates deck legality before saving
- Users can set a default deck for quick play  

**Priority:** Critical  
**Estimate:** 12h

### Gameplay Features

#### ID: US6
**Category:** Gameplay  
**Story:** As a player, I want to join or create a game room so that I can play against other users in real-time.  
**Acceptance Criteria:**
- Users can create private or public game rooms
- Room creator can set game parameters (time limits, game mode)
- Users can browse and filter available public rooms
- Game rooms show current players and spectator count
- Players receive notifications when game is ready to start  

**Priority:** Critical  
**Estimate:** 14h

#### ID: US7
**Category:** Gameplay  
**Story:** As a player, I want to use a drag-and-drop interface to play cards during my turn so that I can execute my strategy intuitively.  
**Acceptance Criteria:**
- Cards can be dragged from hand to appropriate play areas
- Invalid moves are visually indicated and prevented
- Card animations provide feedback on successful plays
- Players can view detailed card information during gameplay
- Interface adapts to different screen sizes  

**Priority:** Critical  
**Estimate:** 16h

#### ID: US8
**Category:** Gameplay  
**Story:** As a player, I want to spectate ongoing games so that I can learn strategies from more experienced players.  
**Acceptance Criteria:**
- Users can join games as spectators without affecting gameplay
- Spectator view shows all public information but hides players' hands
- Spectators can chat with other spectators without distracting players
- Users can find games to spectate through a browsable list
- Optional delayed viewing to prevent cheating  

**Priority:** Medium  
**Estimate:** 8h

### AI Integration

#### ID: US9
**Category:** AI Features  
**Story:** As a player, I want to receive AI-powered recommendations during gameplay so that I can improve my strategy and decision-making.  
**Acceptance Criteria:**
- AI assistant analyzes current game state and suggests possible moves
- Recommendations consider card synergies and opponent's likely strategies
- Users can toggle AI assistance on/off and set skill level
- AI explains rationale behind recommendations
- System integrates with DeepSeek or similar AI API  

**Priority:** High  
**Estimate:** 20h

#### ID: US10
**Category:** AI Features  
**Story:** As a player, I want the AI to help organize my card collection and suggest optimal deck builds based on my playstyle.  
**Acceptance Criteria:**
- AI analyzes user's play history and preferred strategies
- System suggests card combinations that complement user's style
- AI provides deck improvement recommendations
- Users can accept suggestions automatically or manually
- AI explains rationale behind suggestions  

**Priority:** Medium  
**Estimate:** 16h

#### ID: US11
**Category:** AI Features  
**Story:** As a new player, I want to practice against an AI opponent of adjustable difficulty so that I can learn the game at my own pace.  
**Acceptance Criteria:**
- AI opponents available in multiple difficulty levels
- AI plays with realistic and varied strategies
- Practice mode provides tips and explanations
- Game results are recorded but don't affect official rankings
- Practice sessions can be paused and resumed  

**Priority:** High  
**Estimate:** 24h

### Social and Community Features

#### ID: US12
**Category:** Social Features  
**Story:** As a player, I want to add friends and communicate with them so that I can build a gaming community and arrange matches.  
**Acceptance Criteria:**
- Users can send and accept friend requests
- Friend list shows online status and current activity
- Users can send direct messages to friends
- Users can invite friends to game rooms
- Players can block unwanted communications  

**Priority:** High  
**Estimate:** 10h

#### ID: US13
**Category:** Social Features  
**Story:** As a competitive player, I want to view leaderboards and player statistics so that I can track my progress and set goals.  
**Acceptance Criteria:**
- Leaderboards show rankings by win rate, rating, or other metrics
- Users can filter leaderboards by time period or game mode
- Personal statistics page shows detailed performance metrics
- Players can see their ranking history over time
- Option to make profile statistics public or private  

**Priority:** Medium  
**Estimate:** 8h

#### ID: US14
**Category:** Tournament Features  
**Story:** As a player, I want to create and participate in tournaments so that I can compete in a structured format with other players.  
**Acceptance Criteria:**
- Users can create custom tournaments with various bracket formats
- Tournament creator can set entry requirements and prizes
- Players receive notifications about tournament progress
- Tournament results are recorded and viewable in history
- Integration with leaderboard system for ranking points  

**Priority:** Low  
**Estimate:** 30h

### Additional Features

#### ID: US15
**Category:** Integration  
**Story:** As a user, I want to share my game results on social media so that I can showcase my achievements to friends outside the platform.  
**Acceptance Criteria:**
- Integration with major social media platforms
- Customizable sharing templates with game highlights
- Privacy settings to control what information is shared
- Ability to capture and share game replays or key moments
- Links back to the game platform to encourage new sign-ups  

**Priority:** Low  
**Estimate:** 6h

#### ID: US16
**Category:** Accessibility  
**Story:** As a player with visual impairments, I want accessibility features so that I can enjoy the game equally.  
**Acceptance Criteria:**
- High contrast mode and customizable text sizes
- Screen reader compatibility for UI elements
- Audio cues for important game events
- Keyboard shortcuts for all game actions
- Settings are saved to user profile  

**Priority:** Medium  
**Estimate:** 12h


### Gameplay Experience


#### ID: US17
**Category:** Gameplay  
**Story:** As a player, I want to see my hole cards and community cards so that I can make strategic decisions based on the current state of the game.  
**Acceptance Criteria:**
- Player's private hole cards are only visible to themselves
- Community card area clearly displays all shared cards
- Card suits and values have clear visual distinction
- Interface highlights the current best possible hand combination
- Players can check odds and possible hand types at any time  
**Priority:** Critical  
**Estimate:** 12h


### AI Features


#### ID: US19
**Category:** AI Features  
**Story:** As a beginner player, I want to receive real-time strategy suggestions from AI so that I can learn basic strategies and probabilities.  
**Acceptance Criteria:**
- AI analyzes current hole cards, community cards, and odds to provide suggestions
- Recommendations include action choices and explanations
- Shows current win probability and potential hand possibilities
- Users can adjust the level of detail in AI suggestions
- Suggestions consider current pot size and other players' behavior patterns  
**Priority:** High  
**Estimate:** 18h



### Game Analysis
#### ID: US22
**Category:** Game Analysis  
**Story:** As a player, I want to view my game history and statistical analysis so that I can understand and improve my playing strategy.  
**Acceptance Criteria:**
- Detailed game history including key hands, decisions, and outcomes
- Statistical metrics displayed (profit/loss, VPIP, PFR, etc.)
- Visual charts showing long-term performance trends
- AI-provided strategy analysis and improvement suggestions
- Ability to replay important hands and key decision points  
**Priority:** Medium  
**Estimate:** 15h
