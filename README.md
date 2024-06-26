<br/>
<div style="text-align: center;">
    <img src="https://i.ibb.co/4VgXJRG/ezgif-5-9ff2993766.gif" alt="comments output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- Initially,
  - Score should be `0` and time should be `60` sec
  - The image to be matched should have the src attribute value as the value of the key `imageUrl` from the first object in **imagesList** provided
  - The **Fruits** tab should be active and the thumbnails with **FRUIT** as their category should be displayed
- The timer should start running backwards from the `60` sec
- When a tab is clicked, then the thumbnails in the corresponding category should be displayed
- When a thumbnail is clicked, if that is matched with the image to be matched,
  - Score is incremented by one
  - The new image to be matched should be generated randomly among the value of the key `imageUrl` from **imagesList** provided
- When a thumbnail is clicked, if it is not matched with the image to be matched,
  - The game should end, and the [Scorecard](https://assets.ccbp.in/frontend/content/react-js/match-game-score-card-lg-output.png) view should be displayed
  - When **PLAY AGAIN** button is clicked, then we should be able to play the game again
    - The score and time values should be reset to `0` and `60` sec respectively
    - The image to be matched should reset to the value of the key `imageUrl` from the first object in **imagesList** provided
    - The active tab should reset to **Fruits**, and the thumbnails with **FRUIT** as their category should be displayed
- When the timer reached `0` sec, then the game should end, and the [Scorecard](https://assets.ccbp.in/frontend/content/react-js/match-game-score-card-lg-output.png) view should be displayed
- The App is provided with `tabsList`. It consists of a list of tabItem objects with the following properties in each tabItem object

  |     Key     | Data Type |
  | :---------: | :-------: |
  |    tabId    |  String   |
  | displayText |  String   |

- The App is provided with `imagesList`. It consists of a list of imageItem objects with the following properties in each imageItem object

  |     Key      | Data Type |
  | :----------: | :-------: |
  |      id      |  String   |
  |   imageUrl   |  String   |
  | thumbnailUrl |  String   |
  |   category   |  String   |

</details>


### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/match-game-bg.png](https://assets.ccbp.in/frontend/react-js/match-game-bg.png)
- [https://assets.ccbp.in/frontend/react-js/match-game-score-card-lg-bg.png](https://assets.ccbp.in/frontend/react-js/match-game-score-card-lg-bg.png)
- [https://assets.ccbp.in/frontend/react-js/match-game-score-card-sm-bg.png](https://assets.ccbp.in/frontend/react-js/match-game-score-card-sm-bg.png)
- [https://assets.ccbp.in/frontend/react-js/match-game-website-logo.png](https://assets.ccbp.in/frontend/react-js/match-game-website-logo.png)
- [https://assets.ccbp.in/frontend/react-js/match-game-timer-img.png](https://assets.ccbp.in/frontend/react-js/match-game-timer-img.png)
- [https://assets.ccbp.in/frontend/react-js/match-game-play-again-img.png](https://assets.ccbp.in/frontend/react-js/match-game-play-again-img.png)
- [https://assets.ccbp.in/frontend/react-js/match-game-trophy.png](https://assets.ccbp.in/frontend/react-js/match-game-trophy.png)

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color:#2c0e3a; width: 150px; padding: 10px; color: white">Hex: #2c0e3a</div>
<div style="background-color:#ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color:#fec653; width: 150px; padding: 10px; color: black">Hex: #fec653</div>
<div style="background-color:#cf60c8; width: 150px; padding: 10px; color: black">Hex: #cf60c8</div>
</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>
