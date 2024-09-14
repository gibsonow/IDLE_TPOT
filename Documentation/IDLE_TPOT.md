I want to create an in-browser clicker idle game named IDLE TPOT. "TPOT" is an anagram that reads as "This Part of Twitter", and refers to my own niche twitter community. This game will serve as an homage to that community, and many of my mutuals. I am inexperienced in simple web game design, and would like you to write a beta version of this game, which I will then take and improve upon.

INSPIRATION: Things that inspire the look and feel of this game.
- Universal Paperclips: A visually simple html / javascript game, one of the first idle clicker games. I want to pull the design simplicity from this game - it just runs.
- Cookie Clicker: One of the most popular clicker games. The upgrade path is simple, and the number going up is effective. 

VISUALS: The look of the game.
- Twitter / X: Black background, white text, light blue accents. Poasts appear in a center column, Upgrades appear on the far right, and the Poast button / Menu appears on the left column.

CORE CLICKER GAMEPLAY: Click the Poast button to post a tweet. Each tweet will semi-randomly award you three currencies - LIKES, RTS and BOOKMARKS.
- LIKES: Common, highest amount rewarded, lowest worth
- RTS: Uncommon, medium amount rewarded, medium worth
- BOOKMARKS: Rare, low amount rewarded, high worth

STATS: There are three stats that your account has a small amount of to start, but you can purchase more. These stats are AURA, ALGO PULL, and CRACKED.
- LIKES buy AURA
- RTS buy ALGO PULL
- BOOKMARKS buy CRACKED
- Chances of a banger tweet going viral are decided with an equation that uses FOLLOW COUNT, AURA, ALGO PULL, CRACKED, and a random value as its variables
- LIKES are awarded as a function of FOLLOWERS, ALGO PULL and CRACKED
- RTS are awarded as a function of FOLLOWERS, AURA and CRACKED
- BOOKMARKS are awarded as a function of FOLLOWERS, AURA, ALGO PULL and CRACKED

FOLLOWERS: The overall reach of your account. You start with zero.
- Awarded as a function of the RELEVANCE of a Poast. AURA, ALGO PULL, and CRACKED affect the number of FOLLOWERS gained, but RELEVANCE dictates how long a Poast will last.
- Poasts have RELEVANCE, which start at its highest value when the Poast is made, and falls off rapidly after a short amount of time. This lasts about 1 second at the start of the game.

UPGRADES: Unlock different types of content for you to Poast about. Purchased with a combination of LIKES, RTS and BOOKMARKS. Only a few of these are filled out as examples, I can populate them in the code myself later.
- Lowbie shoutouts
	- Desc: You've been shouted out by a big account! Congrats, Goated Lowbie!
	- Cost: 10 LIKES, 2 RTS
	- Gain: RELEVANCE now lasts +1 second longer.
- Learning Computer Arch from transistors
	- Desc: You fully understand the might of the silicon stack.
	- Cost: 15 LIKES, 5 RTS, 1 BOOKMARKS
	- Gain: ALGO PULL now has higher potency.
- Web Framework hateposting
	- Desc: Who needs websites? Low-Level is where it's at!
	- Cost: 30 LIKES, 10 RTS, 3 BOOKMARKS
	- Gain: +2% more LIKES per Poast.
- Getting added to the "Getting hunted down and eaten" list
- Dating spaces
- Esoteric poasting
- AI/ML Progress updates
- Bearblog posts
- Studying CS textbook
- Anime PFP
- New LLM hype train
- Built something from scratch in C
- Built a joke website
- Land SF job
- Start a Startup
- Non-Anime PFP
- Spike in Aura
- Learning Zig
- Get accepted into Y-Combinator
- Guest on the Lex Friedman Podcast

AUTOPOASTERS: LLM bots that hit the Poast button for you at a fraction of your current stats for AFK earnings. Multiple of each model listed below can be bought and used concurrently.
- GPT2
	- Desc: The first of many to come.
	- Cost: 100 LIKES, 30 RTS, 10 BOOKMARKS
	- Gain: 1 Poast per 10 seconds, at 10% of your Stats.
- GPT3
	- Desc: The first leap.
	- Cost: 300 LIKES, 100 RTS, 50 BOOKMARKS
	- Gain: 1 Poast per 7 seconds, at 12% of your Stats.
- CHATGPT
- CLAUDE
- LLAMA
- GPT4
- CLAUDE SONNET
- LLAMA 2
- GPTO1
- CLAUDE ORCHESTRA
- LLAMA 5

PRESTIGE
- SMURF: Once you hit 8 billion followers (everyone on Earth), start over on new account. Permanent +1% Increased follower rate due to rumors that you're a smurf of your last account.

ADDITIONAL FEATURES
- Automatic progress saves using cookies
- Exportable / Importable saves in text file format
- Ko-Fi link