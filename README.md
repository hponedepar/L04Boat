

# L04Boats – GetABoat

GetABoat is a local SME (Small Medium Enterprise) authorised power boat dealer.
This React Native (Expo) app is the first phase of their mobile application.
It displays the 6 power boats they are selling, with each boat's name, description, price, picture and a boat icon.

## Features
- Custom reusable `Boat` component in a separate file `Boat.js`
- Data passed to each boat using props: `name`, `description`, `picture`, `icon`, `price`
- A different boat-themed icon for each boat using `@expo/vector-icons` (MaterialCommunityIcons)
- **Enhancement:** added a `price` prop that shows each boat's price in green bold text
- Local images loaded with `require()` from the `img` folder
- Scrollable list of all 6 boats using `ScrollView`
#
## Boats Listed
| No. | Boat | Price |
|---|---|---|
| 1 | Sea Ray 500 Sundancer | $1,200,000 |
| 2 | Four Winns Horizon 180 | $45,000 |
| 3 | Flipper 640 ST | $80,000 |
| 4 | Princess V48 | $950,000 |
| 5 | Bayliner 175 Bowrider | $30,000 |
| 6 | Fairline Targa 47 | $850,000 |



## Screenshots
<img alt="Screenshot 1" height="600" src="Screenshots/screenshot1.png" width="300"/>
<img alt="Screenshot 2" height="600" src="Screenshots/screenshot2.png" width="300"/>