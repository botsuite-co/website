---
title: UncRobot
pubDate: 2026-10-29T03:38:58.746Z
updatedDate: 2026-10-29T03:38:58.746Z
fmContentType: blog
description: UncRobot info & TOS
hidden: true
heroImage: /thumbnail_tos_and_whatever.png
tldr: <p>Some information about uncrobot and how your data is being used</p>
QnA:
  - question: is uncrobot reading comments?
    answer: Yes, it has to read comment content to work. However, it's never stored anywhere.
    fieldGroup: QnA
  - question: Is it better?????
    answer: Yes, leugues better. Uncrobot uses reddits new Devvit toolset which allows quicker and better feedback
    fieldGroup: QnA
  - question: is it more secure now?
    answer: Yes. UncRobot stores 0 comment content whereas auntierobot DID store the first 300 characters of all comments
    fieldGroup: QnA
---

Hello, I'm [u/auntierob](https://reddit.com/u/auntierob), the developer behind [u/auntierobot](https://reddit.com/u/auntierobot) and now **[u/uncrobot](https://reddit.com/u/uncrobot)**. Every December I try my best to hand out flairs to yall as some sort of second rate santa. Sometimes it works out well (yay :D) but sometimes it does not... and you dont get a flair (NAY D:).

UncRobot is a complete rewrite of AuntiRobot and will offer some nice features! :D I suck at writing text so enjoy this list of super cool stuff:

1. **less breaky breaks.** UncRobot will now read **ALL** comments posted on a rollcall instead of only the top-level-comments. Go crazy, write your "still in" 10 levels deep into a comment chain discussing the.... turkey dude. UncRobot will still read it, reward you if you are still in, and it wont even judge you :D (i havent figured out how to implement that yet)
2. **Directly integrated in Reddit.** UncRobot is built atop [Devvit](https://developers.reddit.com/docs/) which allows me to essentially build a "website" that you will see live in your reddit client. From this integrated website you can handle your flair and will also be reminded to answer the rollcall (if you havent)
3. **Less sketchy data handling.** The bot is hosted directly by Reddit which means it lives completely on their servers. Your data NEVER leaves reddit and your rollcall comment text will no longer end up in [Uppsala](https://maps.app.goo.gl/4oYtVca4tkJ3eERH7).
4. **Ability to grow.** The world is your (my?) oyester... oister... oyster?.. Anyways, what i mean to say is I can easily build more cool stuff on top of this bot. I am **planning** an achivements system but ran out of time. Keep your eyes open :D

### Suggest Features?

I'm all ears. Send me a DM on reddit or find me on the Discord server where my username is **@stoleyourwallet**. I promise I won't steal _your_ wallet tho.

## Policy Statements

Below are some policy statements. Feel free to read my attempt at legalese, but essentially I'm only processing your data to provide stuff.

### Privacy Policy

_Last updated: October 29, 2026_

**SHORT VERSION:** UncRobot reads comments on rollcall posts to figure out whether you're in or out, remembers the result, and that's it. I ain't selling it, sharing it, or hexxing it. It never even leaves reddit servers.

#### What UncRobot stores

- Your Reddit username and user ID
- Your result for each year of the challange (won or lost), plus any overide on it: who set it, when, and the reason if one was given.
- For the current (ongoing) challange, one small record per rollcall you answered: the comment ID, when it was posted or edited, and how it was read (in, out, or unclear)

#### What it's used for

Working out who won, setting your flair, sending you a message with your result, showing your own profile card in the post, and letting mods fix mistakes.

#### Who can see it

- you can see your own results
- moderators can look up and correct anyones details
- your flair is public, because that's how they work :D
- nobody else gets your data: no ads, no data brokers, no sending it to my sketchy russian cousin, and no third-party services.

#### Where it lives

On Reddit's own developer platform (Devvit), tied to the subreddit where the app is installed. uncrobot doesn't use outside servers. Reddit's own [Privacy Policy](https://www.reddit.com/policies/privacy-policy) covers that infrastructure.

For debugging, logs may include usernames or user IDs, comment IDs and how a comment was parsed, **NEVER** comment text. Only the developer (me, [u/auntierob](https://reddit.com/u/auntierob)) gets the pleasure of viewing that.

#### Keeping, correcting, and deleting

Your results are kept for as long as we keep operating this challange. To get something fixed or deleted, [send a modmail](https://www.reddit.com/message/compose?to=r/nonutnovember) or email [uncrobot@botsuite.co](mailto:uncrobot@botsuite.co). You can correct a faulty win (marking a year you lost bot the bot counted as a win) by using the menu in the pinned post.

#### Kids

you need to be old enough to use Reddit (13+). UncRobot isn't aimed at children.

#### Changes

I reserve the right to update and/or modify any part of this Privacy Policy without prior notice. It is your responsibility to periodically review this Privacy Policy to stay informed of any changes. Any changes will be reflected by the "Last Updated" date at the top of this page.

### Terms of Service

_Last updated: October 29, 2026_

**The short version:** its a silly little bot for a silly community challange. Be decent, expect the occasional bot mistake, and that the mods have the final say.

1. **What this is.** uncrobot tracks a community challenge and hands out flair. The flair is cosmetic, there are no prizes, and none of this has monetary value.
2. **Using it.** By commenting on a rollcall or using the UncRobot post, you agree to these terms. Reddit's User Agreement and the subreddit's rules still apply on top.
3. **How results work.** Comments are read automatically, and the bot gets it wrong sometimes. If your result looks wrong, contact the mods and we'll fix it. Mods can override any result, and their decision is final. You can mark one of your _own_ years as lost yourself; only mods can mark a year as won.
4. **Play fair.** No spam, no impersonating other users, and no trying to break, game or probe the bot. Mods can exclude you from the challenge if you do.
5. **Messages.** uncrobot may send you a private message with your result. If your messages are closed you won't get it, so check the pinned post.
6. **No guarantees.** uncrobot is a hobby project provided "as is". It can break, be down, lose data or change, and I can discontinue it at any time. To the extent the law allows, I'm not liable for losses related to using it, including a missing flair.
7. **Not affiliated with Reddit.** uncrobot is an independent app built on Reddit's developer platform.
8. **Changes.** I may update these terms. Continuing to take part after a change means you accept it.
9. **Governing law.** These terms are governed by the laws of Sweden.

   <small>(non-binding) you also agree that Sweden is far better than Denmark :D</small>
