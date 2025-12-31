# 808 Hate Speech & Radicalization Model

## About the Project
This project is a NetLogo simulation that explores the dynamics of hate speech spread, radicalization, and social polarization through social networks and media. The model simulates the interaction of users with different political orientations, the influence of media, and the emergence of extremism.

## Key Questions
The model attempts to answer the following questions:
* What events and how many of them are needed for the majority of agents on both sides (left/right) to become polarized into extremes?
* How strong must the influences be and how many extremists are needed for these extremes to become "normal"?

## Model Entities

### Users
Agents representing people on the social network.
* **Orientation**: Political spectrum from -100 (left) to 100 (right).
* **Satisfaction**: Level of satisfaction with the current state.
* **Anger**: Current level of anger (0-100).
* **Reach**: How far the user sees posts and spreads their influence.
* **Sensitivity**: How easily the user gets angered by content.
* **User Types**:
    * *Hate Posters*: Actively spread hate.
    * *Educated Posters*: Try to calm the situation and educate.
    * *Clout Posters*: Seek popularity (aggressiveness).
    * *Regular Users*.

### Posts
Content shared by users.
* **Seriousness**: The strength of the post's influence.
* **Radius**: The range of the post.
* **Type**: Can be "hateful" (hate speech) or stabilizing.

### Organizations (Orgs)
Represent media houses or lobbies.
* **Types**: Left (blue), Center (green), Right (red).
* **Reputation**: The influence of the organization.
* **Coverage**: How far they spread news.

## Model Dynamics
1. **Content Creation**: Users and media create posts.
2. **Spread and Reaction**: Similar agents see similar posts more often. Posts can change a user's opinion or anger them.
3. **Radicalization**: If the anger threshold is crossed, incidents occur (protests, attacks).
4. **Media Reaction**: Media report on events, which can further radicalize the opposing side (depending on media bias).
5. **Trust**: Users have different levels of trust in media depending on their orientation (Trust System).

## Visualization
* **Agent Color**: Indicates political orientation.
* **Symbols**: Display posts above agents.
