# Genshin-Impact-Character-Analysis

## Problem Statement
Genshin Impact is amongst one of the most popular Gacha RPGs (Role Playing Game) as of recent. A common issue that most new players face, especially F2Ps (Free-To-Play Players, i.e they don't spend actual money on the game) is choosing their first first 5 star character. The gacha system in Genshin is as follows: You have a 0.6% chance of receiving a 5 star in a pull below the 70th wish, once you've crossed the 70th wish, the percentage starts ramping up, by the 90th wish, you are guaranteed to receive a 5 star. However, assuming this is your first 5 star, or your last 5 star was a limited event character, the chances of your 5 star being the one you want is 50%. It can take several months to save up enough primogems (in-game currency used for the wishing system) to guarantee a 5 star, you can read more about the gacha system [here](https://www.thegamer.com/how-gacha-system-works-genshin-impact/#:~:text=Whenever%20you%20get%20a%20five,even%20if%20the%20banner%20expires.). Due to the long time, a lot of players don't want to pick a "bad" 5 star. This project aims to provide a data-driven apporach for new players to pick a character to save for based on information such as popularity, banner profits, spiral abyss usage etc.

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
- Spiral Abyss: It's a series of trials that frequently change, it's worth mentioning that sometimes, some characters are more suited against some enemies, the same goes for elements. Players can use the characters they have to compete in this trials for rewards. A lot of people use these trials as a deciding factor on which character to pull, since some characters are usually more versatile/efficient than others.

- Banner: Not all characters can be obtained at any given moment. They have to be released in what is called a banner. A banner is essentially when a character is obtainable, in every version, the banner rotates once, and since there are always 2 banners at any given moment, in every version, there are 4 characters that are available to obtain. It's worth mentioning that a version is usually 42 days long, and since there are 34 limited characters, sometimes you have to wait over a year for the character you want to show up in a banner.

- Elements: Anemo = Air, Pyro = Fire, Hydro = Water, Cryo = Ice, Electro = Electricity, Geo = Rock, Dendro = Earth.

# Dashboard
In this section I will showcase the dashboard that was built on Power BI and the reasoning behind each visual and what information they are meant to convey.
The dashboard can be found in the "Dashboard" folder. I highly suggest you to install and play around with it (if you can), since there are a lot of features that are lost when shown through images.

<div align="center">
  <h3>__________Page 1 (Revenue)__________</h3>
</div>
![image](https://github.com/user-attachments/assets/bd6f3edd-75c2-4d51-bed7-68787c82d813)

A character in Genshin can be popular for lots of reasons. They can be useful in Spiral Abyss, they can have fun mechanics, they can be "good looking",they could have beautiful animations etc. I personally pulled for my first 5 star simply because I thought the character had a really sick animation, you can see it yourself [here](https://www.youtube.com/watch?v=VQkZ1tKMC4I&ab_channel=Tyr).

Anyways, the idea is that, usually people want to get a popular 5 star, since if they are popular, they are popular for some good reason. The purpose of this page is to let players find out, who's actually popular, when were they popular, and if they're as popular as they were when they first released, since characters can get powercrept (meaning that a new character could do what they do but way better, so people stop using the old character. One example of this would be Venti and Kazuha)

<div align="center">
  <h3>__________Page 2 (Characters)__________</h3>
</div>
![image](https://github.com/user-attachments/assets/067f2d21-e312-45e9-9ecc-93839ab7292d)

In this page you can get information specific to characters. How satisfied people are with the character, a breakdown of why people wished for the character, a breakdown of revenue generated during their banner(s), and how their Spiral Abyss usage fluctuated over time. Players can use this page to compare the characters they're interested in.

<div align="center">
  <h3>__________Page 3 (Spiral Abyss)__________</h3>
</div>
![image](https://github.com/user-attachments/assets/b6c3f258-925d-4161-8eda-1ee4de04d294)

This page is all about Spiral Abyss. If you just want a character that performs well in Spiral Abyss consistently, you can find that out here. You can also see how the popularity of an element changes over time, additionally the average usage of a character and an element. This will allow players to pick an element/character that will help them in Spiral Abyss regardless of what type of lineup they have to go against.

# Final Remarks

- This dashboard was made back when version 3.8 was the latest version (around late Summer 2023). Right now Genshin is at version 5.0, hence the data is not upto date as of now. And the information of 6 characters are missing.

- A lot can be done to improve the dashboard. Some ideas I have in mind right now is to add information on how long it takes on average to level up a character and how long it takes to achieve their best loadout, this would be added in the "Characters" tab. I also want to add information about the most used teams of a chosen character and how F2P friendly a character is, since some characters require other limited 5 star characters to perform well, this would be added in the "Spiral Abyss" tab.

- It's worth mentioning that this game can be 100% completed with any 5 star, in fact it can be completed without any 5 stars at all. My personal advice to anyone is to simply wish for characters that you are interested in. There is no "must have" character, but there are a lot of characters that make the game significantly easier (Ex: Neuvillete).

- You can take a brief look at my Genshin profile over [here](https://akasha.cv/profile/721888609). FYI, I don't play this game as much as I used to, it's still one of my favourite games though, and I am a proud Xiao main, as you can tell by my top 1% build 😌



