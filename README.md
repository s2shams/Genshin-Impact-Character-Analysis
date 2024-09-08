# Genshin-Impact-Character-Analysis

### Problem Statement
Genshin Impact is amongst one of the most popular Gacha RPGs (Role Playing Game) as of recent. A common issue that most new players face, especially F2Ps (Free-To-Play Players) is choosing their first first 5 star character. The gacha system in Genshin is as follows: You have a 0.6% chance of receiving a 5 star, once you've crossed 70 wishes, the percentage starts ramping up, by the 90th wish, you are guaranteed to receive a 5 star. However, assuming this is your first 5 star, or your last 5 star was a limited event character, the chances of your 5 star being the one you want is 50%. It can take several months to save up enough primogems (in-game currency used for the wishing system) to guarantee a 5 star. Due to the long time, a lot of players don't want to pick a "bad" 5 star. This project aims to provide a data-driven apporach for new players to pick a character to save for based on information such as popularity, banner profits, spiral abyss usage etc.

### Future Goals Of The Project:
- Automate the data collection so the dashboard is updated with every new character.

### Info
- All the datasets were webscraped from genshinlab.com and paimon.moe
- Since it's impossible to know the distribution of revenue between the characters in a double banner, a ratio from the global wish tracker on paimon.moe was used to estimate the indivual character revenue.

### Folders
- Notebooks: Contains all the jupyter notebooks used in the project.
- Dashboard: This contains the dashboard bluprints of each page.
- Images: This contains all images used in the project/dashboard. This includes elemental backgrounds and also character images.
- Raw: Contains all the rough/preprocessed data and analysis.

### Dictionary
- Spiral Abyss: It's a series of trials that frequently change. Player's can use the characters they have to compete in this trials for rewards. A lot of people use these trials as a deciding factor on which character to pull, since some characters are usually more versatile/efficient than others.

- Banner: Not all characters can be obtained at any given moment. They have to be released in what is called a banner. A banner is essentially when a character is obtainable, in every version, the banner rotates once, and since there are always 2 banners at any given moment, in every version, there are 4 characters that are available to obtain. It's worth mentioning that a version is usually 42 days long, and since there are 34 limited characters, sometimes you have to wait over a year for the character you want to show up in a banner.

- Elements: Anemo = Air, Pyro = Fire, Hydro = Water, Electro = Electricity, Geo = Rock, Dendro = Earth.

