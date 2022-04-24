# Governet: Self-Governing over the Internet


## Guiding Principals



1. What is Governet

Governet represents the idea of people being able to set up organizational structures over the internet. It is the idea that people can efficiently and effectively come together as a community to pursue shared goals. The idea of Governet is to be an open-source framework that is easily adaptable to many different use-cases, such as social media or a whole new open-source platform (ideas that will be discussed later on). Here are the basic principles of Governet:



* The people who are part of the group have complete control over the decision-making through votes.
* People can be “elected” to certain positions.
    * For example, for social media, there could be a moderator.
    * If elected, though, the people have total control over whether or not the person is doing a good job and therefore can retract any special permissions granted.
    * The idea of having “elected officials” is not to be some sort of abstract figure in the group that deserves special recognition/power. They are an _extension of the people’s will_.
        * For more details on this type of philosophy, refer to Chapter I Section 4 (“The ‘Withering Away’ of the State, and Violent Revolution”) in V.I. Lenin’s _State and Revolution._
    * In this case, people elected to positions _decided by the people of the group_ serve as a way to make the group more efficient.
        * For example, if Governet were applied to a video-sharing website, it would be tedious and very inefficient for there to be a democratic vote on whether a certain video should be flagged as inappropriate.
            * Instead, there could be a person/people with certain permissions (a power granted by the group) that allow them to censor/flag certain content.
            * If the group decides the people in charge of this are doing a bad job, a vote could be held to determine what should happen.
            * Again, the idea that the _people_, at the end of the day, have complete control over the functions and people in charge of these positions is vital.
* The people have the ultimate veto power
    * No matter what, power, in terms of who has _absolute control over the future of the group_, should not be concentrated.
    * This is why it is essential that anyone who has special permission by being elected can be voted out at any time by the people.


## A Social-Media Application of Governet

To concretize what exactly Governet could be, imagine Reddit. Within each subreddit, usually, the creator of the subreddit (really, the owner) has the power to control who the mods are. People can apply to the position, but usually, it is the subreddit’s creator who controls who the mods are. If Reddit operated with the principles of Governet, however, a moderator would simply be a position with those certain “mod” permissions. If the people in the group decided the subreddit needed mods, they could vote on the people to do it. Instead of having just one person who maintains the most control, the people of the subreddit can make decisions past just having moderators. For example, say there is a subreddit specifically for showing artwork. Someone brings up how it would be a cool idea for there to be an art showcase where certain people’s posts are displayed at the top of the subreddit for the week. If the group decides this is a good idea, then that person could be put in charge of carrying out that specific function. 

* It would be very interesting to have people be able to have their own plug-ins for each group. This would allow them to create their own custom aspects for each group (like in the case of the artwork showcase). This is something for much much later.


## Problems with Governet



2. Scalability in Terms of Participation: As specific networks get bigger and bigger, participation could become an issue. This is not necessarily a problem with Governet so much as it is a problem with democracy in general. There are a couple of issues to address this:
    1. Have a threshold number of votes for a decision to be adopted. This would mean that although not everyone has to/will participate, there is a minimum number of votes for a proposal to even be adopted based on the vote.
3. Time-consuming for people to maintain a group.
    2. 




# Bide: Social Media with Governet Principals


## Notes

Evernote link for [notes](https://www.evernote.com/shard/s745/sh/60d25410-e852-6a0a-7690-18f0ac342ba0/e04ad6767fc2de7193e395b84286585c). 


## Concept



1. Overview

    Take the example of the Governet Reddit from above. Within each group is a different community of people interested in different activities/ideas. The fundamental goal of this social platform is to connect people with similar ideas/goals to work together and bring the idea to fruition. For example, there could be a group of 50 people who are interested in some sort of activism. People post their different philosophies for how the group should advance their missions, educational resources, potential meeting places, etc. Bide allows groups to have separate public and private sections for their postings. The public section of the group allows for people outside of the group to give their input on the group itself or specific posts through criticism/praise. The private section is for those who are internal to continue developing their own ideas independently of the public. 

2. The Issue with Likes/Dislikes

    Traditionally, social media platforms use some version of likes and dislikes in order to gauge the quality of a post or the overall reception a post receives. When people comment, it is usually to express their reaction to the post, interact with others, suggest something, etc. The problem with this is that comments are often very low-effort and promote hate. For something like Bide where the point of it is to be productive with social media and really build a community around ideas, this type of paradigm is largely ineffective. Instead, the idea of praise/criticism is much more appealing. Here, when someone wants to “like” something, they have to give a reason for liking it. Same with criticism. People cannot just dislike something, they must provide a meaningful critique of what the post is. What must be figured out is how to sort the meaningful responses from the useless ones (most likely some sort of ML algorithm).

3. Sub-Sections

    Within a group, people could create sections within it to better organize the groups’ ideas/goals. Think of subreddits within a subreddit. In the activism example, different sub-sections could be educational resources, events, proposals, etc.



## Forking

A concept used in the Blockchain that could be applied here is the idea of forking other chains. A fork in Blockchain happens when the people in charge of the chain differ in ideology and therefore want to pursue their own goals with a copy of the chain, when upgrades are needed for a chain, or when a catastrophe happens and the chain must be reverted to a previous state. Two of the largest Blockchain forks happened with [BitCoin (many times)](https://www.investopedia.com/tech/history-bitcoin-hard-forks/) and [Ethereum in 2021](https://www.cnbc.com/2021/08/05/ethereum-just-activated-its-london-hard-fork-and-its-a-big-deal.html). Forking with Bide would not be as dramatic as what happens 


## Technical Aspect


### Languages/Frameworks



* Front-End
    * TypeScript
    * Vue
* The back-end will most likely be written in Python (for now)
    * Python has so many good frameworks for back-end programming but, for a large project like this, it may not be wise to use an interpreted language.
        * Could use mypy, though, for type-annotations


### Concepts To Use



* Bide is going to heavily borrow from concepts used in Blockchain
    * For example, the privileges and permissions users can be granted will be based on the concept of having tokens.
        * Each token (for example, a moderator token) could give the user a different set of privileges from other ones
* Modular design
    * The design of the back-end especially should be broken down into smaller modules to have very re-usable code.
        * This is especially important for the tokens because 


### Note on Blockchain

Eventually, Bide should be moved to a Blockchain, specifically a Level 2 Blockchain (one that has both smart contracts and cryptocurrency coins)


### Note on Open-Source

Everything about this project should be open-source, especially before it moves to a Blockchain. One of the key aspects of this project is the idea that people work well in communities with one another. Therefore, it would not make sense for this to be closed-source.
