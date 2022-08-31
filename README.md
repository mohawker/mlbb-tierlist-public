# mlbb-tierlist-public
Mobile Legends: Bang Bang dynamic hero tier list. Currently hosted at: https://mlbb.ninja/ 

Codebase is kept private temporarily, but will make codebase open source in the future after cleaning up/migration to Next.js

Hero Tier List is calculated from Hero Win, Pick and Ban rates in Mythical Glory Ranked games on the Mobile Legends server. 
Data is obtained from the official website https://m.mobilelegends.com/en/rank and various Liquipedia websites with Selenium.

## Tech Used:
### Backend (Scraping and Scripting)
- Selenium
- Python3
- Bash Scripting
### Backend (DB + Endpoint)
- Google Realtime Firebase
### Frontend
- ReactJS (create-react-app)

## Screenshot of Webpage
<img width="1136" alt="image" src="https://user-images.githubusercontent.com/48997733/187604509-3ecf3409-d03f-4f68-baee-754ef5aea56a.png">

## Future Expansion
- Will look to migrate to Next.js to support static site generation for improved performance
- Hero Trends and individual hero pages for each hero
