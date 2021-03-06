# Bullz and Bearz

**HackTX 2020 - Finalists**

Code snippets and supporting documentation for the Bullz and Bearz project by The Mistfits for HackTX

API Root: https://bearz-and-bullz.herokuapp.com/

![App Screen 1](https://github.com/simmsss/Bullz-and-Bearz/blob/main/UI%20Elements/Screenshots/1.png?raw=true)

### VIDEO WALKTHROUGHS:

For a detailed video explanation with voice-over, click [here](https://www.youtube.com/watch?v=cmA_M69heNs).

### INSPIRATION 

The Covid-19 pandemic has adversely affected the global economy, leaving investors baffled over questions like, should they invest or stay put?  With this in mind, we developed a mobile application- Bullz and Bearz, that helps individuals in making their investment decisions, particularly in the Stock Market. 

### WHAT IT DOES?

In the world of investing, there is a popular saying that market crashes should be seen as opportunities to lap up quality stocks and there’s something that we hear over and over again, that an investor should avoid putting all their eggs in the same basket.
Bullz and Bearz does exactly that for you, it serves personalised recommendations to the users and uses sentiment analysis based on latest news headlines to render a sentiment score to each stock, which users can use to compare against other stocks.
Instead of predicting a volatile environment like the stock market, the sentiment analysis score is a statistical score that doesn’t give false directions to the users, and rather gives them a statistical comparison between different stocks.
That makes both our things; Recommendation (Clustering) and Sentiment Analysis subjective instead of giving false objective values.

![App Screen 2](https://github.com/simmsss/Bullz-and-Bearz/blob/main/UI%20Elements/Screenshots/2.png?raw=true)
![App Screen 3](https://github.com/simmsss/Bullz-and-Bearz/blob/main/UI%20Elements/Screenshots/3.png?raw=true)

### TECHNICAL IMPLEMENTATION

The Bullz and Bearz iOS application (built with Swift) acts as the portal between the layman user and our Flask APIs deployed on Heroku. Making use of several key financial indicators and Machine Learning techniques, the application serves personalised recommendations to the users. To enable third-party developers and first-party improvements, all APIs are exposed publicly without any restrictions.
Using Web Scraping, News Analysis and NLTK, we give each stock a subjective sentiment rating based on current headlines regarding the company. Instead of providing half-baked predictions, this sentiment rating can be judged by the user to reduce risk and to make decisions regarding their holdings.

To facilitate user privacy, no data from the user is collected and/or stored by the application.
The UI elements are built and exported from Sketch. To conform with Apple’s Human Interface Guidelines, the app looks and works just as expected in Dark Mode.

![Technical framework](https://github.com/simmsss/Bullz-and-Bearz/blob/main/UI%20Elements/Technical%20Framework.jpg?raw=true)

### Requirements

#### Hardware

* MacBook, Mac Mini, iMac, Mac Pro or any other variant running macOS 10.15.4 (Catalina) or later.
* Atleast 4GB of RAM recommended (For running on Simulator)
* An iPhone or iPad running iOS/iPadOS 14.0 or later. (For running on physical device)

#### Software

* Xcode version 12.0
* Xcode Command Line Tools
* CocoaPods
* Python 3.7+

#### Instructions

Clone the GitHub repo on your local machine. Navigate to the project folder in the terminal and run `pod install` to install dependencies. Open the workspace in Xcode, configure the profiles and hit run for the simulator to load up. 

Made with ❤️ by [Simran](https://simmsss.github.io/) and [Utkarsh](https://skhiearth.github.io/)
