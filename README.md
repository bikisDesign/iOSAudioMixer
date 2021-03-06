iOS Audio Mixer Challenge
This challenge is meant to evaluate not only your ability to complete the challenge, but to see how you organize and write code. There are several required steps to this challenge, and several bonus aspects to this challenge. Feel free to use any 3rd party libraries you see fit, except for audio playback. You can create the UI programmatically, or in code.
Required:
-Create an autocomplete search field that queries the iTunes Search API for music matching what the user is typing.
-Parse the JSON object for the following keys: "artistName", "collectionName", "trackName", "artworkUrl100", and "previewUrl"
-Display the parsed JSON in a table view, in an UI that you think a user would understand it. -By tapping on the table view cell, push to a new view controller that plays the previewUrl 30-second preview.
Bonus:
-Use RxSwift & RxAlamofire to retrieve data from the API.
-Add playback functionality for the song playback (volume, play/pause) -Implement this with MVVM architecture.
iTunes Search API Documentation: https://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/
