![GitHub last commit](https://img.shields.io/github/last-commit/dakkafex/Twitch-spam-blacklist?label=Las%20Updated&style=for-the-badge)

# Twitch Spam Blacklists

Hello,

This is an attempt to create a centralized repository for curated lists for the most popular streaming tools, like Nightbot.

Apart from just regular phrases, the lists also incorporates regular expressions ([regex](https://en.wikipedia.org/wiki/Regular_expression))  
don't worry if you have never heard of it, that's what this list is for 😉

There are different lists for different content.  
Are you a mature stream but want to bar racial slurs, including ones spelled in a way to get around simple content filters\* :

*   _hey streamer, i think you are a dirty d o o d o o face_

You can for example choose to copy the racial slurs list, or if you want to keep sexual remarks out of your chat, use the sexual comments list.

**Do keep in mind**

That these lists aren't perfect and are not a catch all solution to moderating your community, people are always going to find ways around filters.

The main intention (in our case at least) for using blacklists, is to stop bots, spammers, trolls and the likes.  
It is up to you to create the community you want instead of muzzling them, because nobody likes overzealous chat filters.

## Blacklist Types

As you can see we have different folders and different names per list, here is an attempt to explain what each list is for.  
Because not every bot/tool supports regex, some lists might be less flexible and only contain words where as some only contain regex.  
|List Name           |Description |  
|-|-|  
|spam |General spam bots that try to advertise services or things with malicious links|  
|slurs| Common slurs for any group ( ethnic, sexuality, ableist, etc... ) |  
|furry| Common derogatory words and phrases used against the furry community|  
|horny jail | Words that contain sexual explicit meaning excluding overlapping swears like fuck or pussy|  
|nsfw| General list for nsfw |

## Instructions

In order to make use of these lists, simply check out the directory and look for the list that applies to your use case, copy the text and paste it in your blacklists settings.

**For Nightbot:**

1.  Go to your dashboard.
2.  Go to the **Spam Protection** page.
3.  Go to the options of **Blacklist Words/Phrases**(make sure it is enabled).
4.  Paste the raw text into **Blacklist** option.
5.  Save the list.
6.  If you want to use multiple lists, copy and paste multiple ones, we try to not re-use words in other lists.

## The Big User Ban list

This list is made up out of users that have been reported by multiple users/teams, not just a single person.

As this list is compiled from different ban lists that can possibly contain the same user multiple times, we check the list and make sure it is **free of duplicates**.

**I am on this list!**  
If you find yourself on this list **please do not** make an issue or contact us, we have no way of verifying if your ban was unjust, if you have been blocked from a streamers channel and your name is on this list, try to contact the streamer/team, they wil contact us to confirm your removal.

## Improve the lists

Everyone is welcome to improve the list, just fork the repo and make a pull request when you are done so it can be added to our main repository.

## Notes

\* These methodes do require regex support in your bot/tool
