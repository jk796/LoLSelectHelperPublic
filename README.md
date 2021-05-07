# LoLSelectHelperPublic
Public repository created for receiving Riot API's production API Key

## Application Description
The product is designed to help summoners with their champion selection process and gain better insights on team's champion compositions. The users of LoLSelectHelper will be asked to choose 0 to 4 hovered or already selected teammate champions and 0 to 5 already selected enemy champions. Then, the application will display the remaining champions win rates with 0 to 4 chosen teammate champions against 0 to 5 chosen enemy champions.

## Application Flow Screenshots
Below screenshots are produced with 37,807 match data for testing purposes.
After the acquisition of the production API Key, I plan to include at least 1 million and at most 10 miilion match data from NA server by platinum+ players based on query speed of SQLite database I'm planning to include in my app bundle. As of now, the 37,807 matchdata is organized in a JSON structure and decoded by JSONDecoder. This will not be fast enough for 1 million + records.

### 1. Sign In/Sign Up

![SignIn View](https://user-images.githubusercontent.com/25420198/117507335-dd4f2f80-af54-11eb-93d8-b80111e80279.png)   ![Sign Up View](https://user-images.githubusercontent.com/25420198/117507346-e0e2b680-af54-11eb-8bf2-6414cf9de4ee.png)<br />
Users will be able to sign up with valid email addresses and passwords. They will also be able to sign in using Google and Facebook accounts.

### 2. Each role's champion selection(My Champions Selection) upon first time sign in.

![TopSelection](https://user-images.githubusercontent.com/25420198/117508130-1340e380-af56-11eb-974d-854955f99b01.png)  ![JungleSelection](https://user-images.githubusercontent.com/25420198/117508142-16d46a80-af56-11eb-93da-fbe625b9ff8f.png) ![MidSelection](https://user-images.githubusercontent.com/25420198/117508149-1a67f180-af56-11eb-8c48-3ff21d5ceb3d.png)  ![AdcSelection](https://user-images.githubusercontent.com/25420198/117508151-1c31b500-af56-11eb-8d21-3d4a435c9b46.png)  ![SupportSelection](https://user-images.githubusercontent.com/25420198/117508153-1e940f00-af56-11eb-8bbd-7e65ecda06d2.png)  <br />
Upon their first time signing in, they will be prompted to select the champions they like to use to go each corresponding lanes.

### 3. Main Champion/ Enemy Champion Compositions View(After non-first time signins/after My champion selections after first time sign in)

![Main Select View](https://user-images.githubusercontent.com/25420198/117508469-a11cce80-af56-11eb-89e7-903aa49017d6.png)  ![Simulator Screen Shot - iPhone 12 Pro Max - 2021-05-07 at 17 08 39](https://user-images.githubusercontent.com/25420198/117508693-05d82900-af57-11eb-8e67-b998d2b11fa6.png)  ![Simulator Screen Shot - iPhone 12 Pro Max - 2021-05-07 at 17 09 21](https://user-images.githubusercontent.com/25420198/117508703-083a8300-af57-11eb-8d19-014752718292.png)<br />
On this view, users can select 0 to 4 hovered/already selected teammate champions and 0 to 5 already selected enemy champions by clicking on blue/red selection icons. After each blue/red icon selection, the view will then present current composition's win rates/number of games played at the bottom.











