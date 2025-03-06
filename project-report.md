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
| [Guanqiao Li] | [guanqiao.li@uzh.ch] | [23-746-241] | [unscttp] |
| [Zhengxun Yin] | [zhengxun.yin@uzh.ch] | [23-754-179] | [YinZhengxun] |

## Project: PokerMaster Arena

### Project Description (max. 150 words)
PokerMaster Arena is an online Texas Hold'em poker platform designed for multiplayer gameplay. The platform addresses the challenge of finding engaging and accessible poker games that incorporate modern AI capabilities. Players can register accounts and compete in real-time multiplayer matches with intuitive betting controls. The platform features AI-powered assistants that can provide strategic suggestions, analyze hand histories, and help players improve their poker skills. PokerMaster Arena also offers basic tournament organization and win-rate leaderboards. The game follows standard Texas Hold'em rules with blinds, betting rounds, and community cards. By integrating AI technologies with competitive gameplay, PokerMaster Arena aims to create an engaging poker experience for casual players and poker enthusiasts alike.

## User Stories

### User Profile Management

#### ID: US1
**Category:** User Management  
**Story:** As a new user, I want to create an account with my credentials so that I can access the poker platform and save my progress.  
**Acceptance Criteria:**
- Users can register with username and password
- Users receive a confirmation notification after successful registration
- Users can log in with their credentials after registration  

**Priority:** Critical  
**Estimate:** 8h

#### ID: US2
**Category:** User Management  
**Story:** As a registered user, I want to set up my gaming profile so that I can be recognized by other players.  
**Acceptance Criteria:**
- Users can add a display name and avatar
- Users can specify their poker experience level (beginner, intermediate, expert)
- Profile information can be edited at any time  

**Priority:** High  
**Estimate:** 4h

#### ID: US3
**Category:** User Management  
**Story:** As a user, I want to update my online/offline status so that other players know if I'm available for games.  
**Acceptance Criteria:**
- Users can toggle between "online" and "offline" status
- Status is visible to other users in game lobbies
- Status automatically changes to "offline" after prolonged inactivity  

**Priority:** Medium  
**Estimate:** 3h


### Gameplay Features

#### ID: US6
**Category:** Gameplay  
**Story:** As a player, I want to join or create a poker table so that I can play against other users in real-time.  
**Acceptance Criteria:**
- Users can create private or public tables
- Table creator can set basic parameters (blind levels, starting chips)
- Users can browse available public tables
- Tables show current players and available seats
- Players receive notifications when game is ready to start  

**Priority:** Critical  
**Estimate:** 12h

#### ID: US7
**Category:** Gameplay  
**Story:** As a player, I want to place bets, call, raise, or fold during my turn so that I can execute my poker strategy.  
**Acceptance Criteria:**
- Clear buttons for betting actions (fold, check, call, raise)
- Betting slider for raise amounts
- Invalid moves are prevented
- Visual feedback on successful actions
- Timer for decision-making to keep the game moving  

**Priority:** Critical  
**Estimate:** 14h

#### ID: US8
**Category:** Gameplay  
**Story:** As a player, I want to spectate ongoing games so that I can learn strategies from more experienced players.  
**Acceptance Criteria:**
- Users can join tables as spectators without affecting gameplay
- Spectator view shows all community cards but hides players' hole cards
- Users can find games to spectate through a browsable list  

**Priority:** Medium  
**Estimate:** 6h

#### ID: US9
**Category:** Gameplay  
**Story:** As a player, I want to see my hole cards and community cards so that I can make strategic decisions based on the current state of the game.  
**Acceptance Criteria:**
- Player's private hole cards are only visible to themselves
- Community card area clearly displays all shared cards
- Card suits and values have clear visual distinction
- Interface highlights winning hand at showdown  

**Priority:** Critical  
**Estimate:** 10h

### AI Integration

#### ID: US10
**Category:** AI Features  
**Story:** As a player, I want to receive basic AI-powered recommendations during gameplay so that I can improve my strategy.  
**Acceptance Criteria:**
- AI assistant provides simple odds calculations
- Users can toggle AI assistance on/off
- AI explains basic poker concepts to beginners  

**Priority:** High  
**Estimate:** 16h

#### ID: US12
**Category:** AI Features  
**Story:** As a new player, I want to practice against an AI opponent so that I can learn the game without pressure.  
**Acceptance Criteria:**
- AI opponents available in beginner difficulty
- AI plays with realistic basic strategies
- Practice mode provides tips
- Game results don't affect official rankings  

**Priority:** High  
**Estimate:** 20h

### Social and Community Features

#### ID: US13
**Category:** Social Features  
**Story:** As a player, I want to add friends so that I can arrange matches with people I know.  
**Acceptance Criteria:**
- Users can send and accept friend requests
- Friend list shows online status
- Users can invite friends to poker tables  

**Priority:** Medium  
**Estimate:** 8h

#### ID: US14
**Category:** Social Features  
**Story:** As a competitive player, I want to view win rate leaderboards so that I can track my progress.  
**Acceptance Criteria:**
- Leaderboard shows rankings by win rate only
- Personal statistics page shows basic performance metrics
- Players can see their total hands played and win percentage  

**Priority:** Medium  
**Estimate:** 6h


### Additional Features

#### ID: US15
**Category:** Accessibility  
**Story:** As a player with visual impairments, I want basic accessibility features so that I can enjoy the game.  
**Acceptance Criteria:**
- High contrast mode for cards and betting controls
- Larger text option for important game information
- Simple keyboard shortcuts for common actions  

**Priority:** Medium  
**Estimate:** 8h
