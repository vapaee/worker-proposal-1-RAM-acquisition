Vapaée - worker proposal 1
------------------------

# Financing the RAM cost of the **Cards & Tokens** smart contracts

## How much is asked and for what exactly ?
  - ### Summary: 35,000.0000 TLOS to buy resources for the Cards & Tokens platform.
    - ~33K TLOS for buying 300Mb RAM for tree of the four smart contracts of the system (100Mb each).
    -  ~3K TLOS for staking (CPU & BW) for both contracts.
  - ### More detailed:  
    - The entire system of **Cards & Tokens** consists of four smart contracts:
        - **cardsntokens**: implements the details of the application *per se* (cards, contnet, points, album integration, templates, prices, etc).
        - **boardgamebox**: implements abstract gamification services (profiles, authorship, ownership, items, containers and many more comming soon).
        - **vapaeetokens**: implements system tokens (CNT, and others to come). Plus some other features like: auto claim airdrop, token exchange and staking.
        - **categorizers**: implements decentralized content categorization and filtering.
    - Because the total RAM cost for the contract **vapaeetokens** was not that high (less than 5Mb), I was able to pay it off completely from my own money.
    - However, I needed several months to raise some money to pay the cost of a reasonable amount of RAM for the entire system but unfortunately I lost everything when I was hacked recently. It was planned to buy 100M of RAM for each of the other three contracts (**cardsntokens**, **boardgamebox** and **categorizers**).
    - The total cost in TLOS is less than 35K TLOS for the 300Mb RAM. The rest of the Tokens are planned to be distributed and staked for CPU and Band Width.
## What is **Cards & Tokens** ?
  - ### It's an entertainment platform where users can create collectible cards and thematic albums to fill and win tokens.  
    - In this platform content creators may publish great trading cards embedding their work on each card. Then they can sell, auction or give away copies of those cards for the rest of users to collect.
    - Cards will gain points as people interact with them through likes, comments, categorizations and market stats. That makes the cards to level up.
    - The albums are the first type of minigame in which users may play using the copies they have, add points to the album and competing with others users for a position in the ranking.
    - The platform is a plugin-driven structure, allowing other Apps to implement all kind of plugins using the cards as the main gaming object.
  - ### This platform is designed to provide abstract gamification services to other applications through its low-level **boardgamebox** module.
    Some of those services would be:
    - profiles: each account can have more than one profile (like in facebook you can have your personal acount plus several pages)
    - items & containers: apps may register and define several items and containers. Then delegate to this module all kind of functionalities arround those concepts like:
      - creation: create containers with specific item filters, issue container instances for specific profile, create new specific items, issue units of those specific items, etc.
      - storage: store item's units inside a specific container instance, swap unit's places, swap unit's container, modify container instance capacity, etc.
      - market: create buy/sell order for specific unit and specific amount, auction a lot of units of specific item, give away a lot of units of specific item, etc.
    - ownership: each instance of any element (item or container) has an owner profile. If the element provides any benefit, all owners of each instance will receive it.
    - authorship: each element has at least one author profile. If the element receives rewards it will be distributed among all author profiles depending on the percentage of authorship.
    - more coming soon...
  - ### Another type of service this platform will provide is content categorization through its low-level **categorizers** module.   
    Some of the items in the system are user made and those we can't trust the user's first categorization. We need lots of people to take the time to watch each item closely and make a good categorization. The **categorizers** module will implement an economy model with the following features:
      - cats (categorizers) will level up as they categorize more and more content and get support from other cats (they agree).
      - monetary inflation finances the rewards of cats, depending on their level.
      - content creators may pay for their work to be seen and categorized.
      - publishers may pay to cats fo find and redirect specific content that fits certain filter
## Why does it need so much RAM ?
  - ### **Cards & Tokens** platform is a very high RAM consumer because users will collect NFTs, which are stored separately on memory.
    - NTF: stands for Not Fungible Token, meaning that two units of the same token type can not be merged together. Each of them must be stored on its own place (physically on memory). That is because each instance has its own properties.
    Eg: where is the unit located? is there any add-on affecting a specific unit? has the unit any enhancement over the rest?
    - In this platform users collect copies of cards and each one has to be stored in a specific container in a specific place (like the inventory or any album). Some slots of some albums will have specific modifiers on the points that a copy of the card grants if it's placed there. For that to work, we need to store all of that data separately on memory.
  - ### This platform is planned to be implemented in such way that users don't have to worry about the technology behind (until certain threshold).
    - In Cards & Tokens users can create an account by simply login with other social medias like twitter, google or steemit. This way we can reduce the addoption friction for new users to start using the platform.
    - Under the hood, the platform manages all the interaction with the blockchain without the user even being aware of that. It creates a temporary profile in the **boardgamebox** module and keeps the ownership of that profile until the user claims it.
    - These temporary profiles will have certain limitations, which will motivate the users to create their own account on the Telos blockchain and claim the authorship of their profile. This way the user is forced to learn how to interact with the blochcian are his own account and as a prize he gets access to all the functionalities of the system.
    - we will have alot of categorization data for each card. That data is generated by people that is actually contributing with work, so is not good idea to charge those people for that data's RAM. We need the system to store that for them.
## Who benefit from this financing ?
  - The beneficiaries would be the users of **Cards & Tokens** because they will not have to run with the high RAM costs that the platform requires.
  - The main and biggest beneficiaries will be the new users, who despite having few resources to interact with the blockchain will still be able to interact with this platform and collect lots of cards.
  - **Cards & Tokens** will be fully developed on Telos chain. So, if it is successful (and I am very confident that it will be) it will attract many users to this network, which will greatly benefit the entire Telos community.
## Why go to a worker proposal ?
  - Given that "if **Cards & Tokens** is successful it would benefit the Telos community", it is prudent to ask the community itself for help to make this success even more likely.
  - Although I am working hard to form a company and be able to dedicate myself completely to this, I still do not have the financial resources to do it and I must work on something else (have a job) to cover the basic cost of living.
  - Throughout these last three months I have been able to save the extra earnings on my normal salary, in order to pay the cost of that RAM. However, I had the misfortune of being hacked in my account and all the funds that I had saved were stolen.

## Links and References
  - [web site](http://cardsandtokens.com)
  - [video - last year promo (outdated)](https://www.youtube.com/watch?v=YSVJgKsSobA)
  - [demo web app](http://app.cardsandtokens.com/)
  - [video - demo](https://www.youtube.com/watch?v=jhL1KyifGEs)
  - [CNT airdrop](https://steemit.com/eos/@viterbo/cards-and-tokens-cnt-token-airdrop)
  - [Telegram group](https://t.me/cardsandtokens)
  - post about my hack
