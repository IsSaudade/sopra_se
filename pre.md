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

### Project Description
PokerMaster Arena is an online Texas Hold’em platform where players can join or create game rooms and play in real time. Users can set up profiles, track their stats, and compete on leaderboards. The game includes social features like friends lists and chat, as well as AI-powered tips and probability calculations to help players improve. Spectator mode lets users watch ongoing games, and simple tutorials make it easy to learn. Whether you're a beginner or an expert, PokerMaster Arena offers a fun and competitive poker experience.

## User and Account Management

### ID: US1  
**Category:** User Management  
**Story:** As a registered user, I want to set and edit my game profile so that I can personalize my account and be recognized by other players.  
**Acceptance Criteria:**
- Users can add and change display names and avatars.
- Users can specify their poker experience level (Beginner, Intermediate, Expert).
- Users can update their birthdate (optional).
- Users can only edit their own profiles, not others'.
- Profile information can be edited and saved to the database at any time.
  
**Priority:** High  
**Estimated Time:** 12 hours  

### ID: US2  
**Category:** User Management  
**Story:** As a logged-in user, I want to view a list of all registered users and check their profiles to learn about potential opponents.  
**Acceptance Criteria:**
- Users can view a list of all registered users.
- Users can click on a username to see a detailed profile.
- Profile pages display username, online status, creation date, and birthday (if set).
- Only logged-in users can access the user list and profile pages.  

**Priority:** High  
**Estimated Time:** 8 hours  

## Game Features

### ID: US3  
**Category:** Game  
**Story:** As a player, I want to create or join a game room so that I can play real-time Texas Hold'em with other players.  
**Acceptance Criteria:**
- Users can create private or public game tables.
- The table creator can set basic parameters (blind levels, starting chips).
- Game rooms support 2 to 10 players.
- Users can browse available public game tables.
- Tables display current players and available seats.
- The room creator decides when to start the game.  

**Priority:** Critical  
**Estimated Time:** 18 hours  

### ID: US4  
**Category:** Game  
**Story:** As a player, I want to perform standard Texas Hold'em actions (check, bet, call, raise, fold) so that I can apply poker strategy and participate in the game.  
**Acceptance Criteria:**
- The game interface displays a player's private cards and community cards.
- Players can take appropriate actions based on the game phase (bet, call, raise, fold).
- Players can see the current pot size and other players' actions.
- The game follows Texas Hold'em rules, handling flop, turn, and river phases automatically.
- The interface highlights the winning hand at showdown.  

**Priority:** Critical  
**Estimated Time:** 24 hours  

### ID: US5  
**Category:** Game  
**Story:** As a player, I want to view real-time game status and statistics so that I can make informed decisions.  
**Acceptance Criteria:**
- The interface displays the current pot size and odds.
- The interface shows the current betting round and placed bets.
- Players can see their chip balance.
- Players can see other players' actions (e.g., betting, calling, folding).
- The interface includes a timer to ensure timely decisions.  

**Priority:** High  
**Estimated Time:** 14 hours  

### ID: US6  
**Category:** Game  
**Story:** As a player, I want to view results and analysis at the end of a game so that I can learn and improve my strategy.  
**Acceptance Criteria:**
- The game announces the winner and the winning hand at the end.
- Players can view key statistics (e.g., participation rate, pots won).
- Players can review game history, including critical hands and decisions.
- If all other players fold, the winner can choose whether to reveal their hand.  

**Priority:** High  
**Estimated Time:** 16 hours  

## Social and Community Features

### ID: US7  
**Category:** Social Features  
**Story:** As a player, I want to add friends and chat in real-time with other players to enhance the social experience.  
**Acceptance Criteria:**
- Users can send and receive friend requests.
- The friends list displays online status and current activity.
- Users can invite friends to join poker tables.
- Game rooms provide real-time chat functionality.
- Players can send and receive private messages.  

**Priority:** Medium  
**Estimated Time:** 16 hours  

### ID: US8  
**Category:** Game Features  
**Story:** As a player, I want to spectate ongoing games so that I can learn strategies from more experienced players.  
**Acceptance Criteria:**
- Users can join tables as spectators without affecting gameplay.
- Spectators see all community cards but not private hands until showdown.
- Users can browse available games to spectate.
- Spectators can chat with other spectators but not with active players.
- Spectators can view game statistics and player profiles.
- Spectator mode supports up to 50 simultaneous viewers.  

**Priority:** Medium  
**Estimated Time:** 16 hours  

## Game Analytics

### ID: US9  
**Category:** Game Analytics  
**Story:** As a competitive player, I want to view detailed game statistics and leaderboards so that I can track my progress and compare myself to others.  
**Acceptance Criteria:**
- Personal statistics page displays win rate, participation rate, and key metrics.
- Leaderboards rank players by different criteria (e.g., win rate, total profit).
- Users can view historical game records and trend analysis.
- Statistics can be filtered by time range (last 7 days, 30 days, etc.).
- Players can compare their stats with friends or global averages.  

**Priority:** Medium  
**Estimated Time:** 18 hours  

## Simplified AI and Assistance Features

### ID: US10  
**Category:** AI Features  
**Story:** As a player, I want to view win probability calculations for my current hand and community cards so that I can make more informed betting decisions.  
**Acceptance Criteria:**
- The interface displays the win probability based on the current hand and community cards.
- Probability calculation follows standard Texas Hold'em odds.
- Users can toggle probability display on or off at any time.
- Probability calculations do not impact game fairness.  

**Priority:** Medium  
**Estimated Time:** 12 hours  

### ID: US11  
**Category:** AI Features  
**Story:** As a new player, I want to see basic poker strategy tips so that I can learn during gameplay.  
**Acceptance Criteria:**
- The interface provides basic poker strategy tips (e.g., betting, calling, folding suggestions).
- Tips are based on the current game state and hand.
- Users can toggle strategy tips on or off at any time.
- Tips do not affect game fairness.  

**Priority:** Medium  
**Estimated Time:** 10 hours  

## Additional Features

### ID: US12  
**Category:** Game Features  
**Story:** As a player, I want to configure game preferences (e.g., auto-fold, auto-call) so that I can customize my gameplay experience.  
**Acceptance Criteria:**
- Users can set auto-fold or auto-call preferences.
- Preferences can be adjusted before or during a game.
- Preferences are saved to the user profile.
- Preferences do not impact game fairness.  

**Priority:** Medium  
**Estimated Time:** 10 hours  

### ID: US13  
**Category:** Game Features  
**Story:** As a player, I want to view game rules and tutorials so that I can quickly understand how to play Texas Hold'em.  
**Acceptance Criteria:**
- The interface provides basic Texas Hold'em rules and tutorials.
- Tutorials include how to bet, call, raise, and fold.
- Users can access tutorials at any time.
- Tutorial content is clear and easy to understand.  

**Priority:** Low  
**Estimated Time:** 8 hours  

