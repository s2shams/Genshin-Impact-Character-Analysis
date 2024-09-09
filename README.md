# Genshin-Impact-Character-Analysis

## Problem Statement
Genshin Impact is amongst one of the most popular Gacha RPGs (Role Playing Game) as of recent. A common issue that most new players face, especially F2Ps (Free-To-Play Players, i.e they don't spend actual money on the game) is choosing their first first 5 star character. The gacha system in Genshin is as follows: You have a 0.6% chance of receiving a 5 star in a pull below the 70th wish, once you've crossed the 70th wish, the percentage starts ramping up, by the 90th wish, you are guaranteed to receive a 5 star. However, assuming this is your first 5 star, or your last 5 star was a limited event character, the chances of your 5 star being the one you want is 50%. It can take several months to save up enough primogems (in-game currency used for the wishing system) to guarantee a 5 star. Due to the long time, a lot of players don't want to pick a "bad" 5 star. This project aims to provide a data-driven apporach for new players to pick a character to save for based on information such as popularity, banner profits, spiral abyss usage etc.

### Future Goals Of The Project:
- Automate the data collection so the dashboard is updated with every new character.

### Info
- All the datasets were webscraped from genshinlab.com and paimon.moe using selenium and some manual data entry
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

# Dashboard
In this section I will showcase the dashboard that was built on Power BI and the reasoning behind each visual and what information they are meant to convey.
The dashboard can be found in the "Dashboard" folder. I highly suggest you to install and play around with it (if you can), since there are a lot of features that are lost when shown through images.

### Page 1 (Revenue)
![image](https://github.com/user-attachments/assets/bd6f3edd-75c2-4d51-bed7-68787c82d813)

A character in Genshin can be popular for lots of reasons. They can be useful in Spiral Abyss, they can have fun mechanics, they can be "good looking",they could have beautiful animations etc. I personally pulled for my first 5 star simply because I thought the character had a really sick animation, you can see it yourself [here](https://www.youtube.com/watch?v=VQkZ1tKMC4I&ab_channel=Tyr).

Anyways, the idea is that, usually people want to get a popular 5 star, since if they are popular, they are popular for some good reason. The purpose of this page is to let players find out, who's actually popular, when were they popular, and if they're as popular as they were when they first released, since characters can get powercrept (meaning that a new character could do what they do but way better, so people stop using the old character. One example of this would be Venti and Kazuha)

### Page 2 (Characters)
![image](https://github.com/user-attachments/assets/067f2d21-e312-45e9-9ecc-93839ab7292d)

In this page you can get information specific to characters. How satisfied people are with the character, a breakdown of why people wished for the character, a breakdown of revenue generated during their banner(s), and how their Spiral Abyss usage fluctuated over time. Players can use this page to compare the characters they're interested in.

