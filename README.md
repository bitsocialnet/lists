# temporary-default-communities

### NOTE: ./subplebbits.json is deprecated, use ./multisub.json instead

Submit a pull request to have your community added, or contact devs on Telegram [@bitsocial](https://t.me/bitsocialnet).

In the future, this process will be automated by voting.

## Repository Layout

- `5chan-directories/5chan-<code>-directory.json`: candidate boards for each 5chan directory code. 5chan builds the active directory list by reading these files and choosing the highest-ranked board in each file.
- `5chan-directories/5chan-directories-defaults.json`: expected 5chan UX defaults keyed by directory code, including directory identity, title, and feature defaults. These defaults apply to the directory, not to individual candidate boards.
- Root JSON files are shared lists for other Bitsocial clients or challenge configuration.

>### What is this?
This list is used to show communities by default in our clients' homepages, automatically subscribing all our users to them.

## Requirements to have your community included
- 99% uptime: your community must be online 24/7 to appear by default in our clients.
- non-random topic: communitys about specific topics are preferred, such as technology, movies, anime, business, etc.
- unique topic: please check if your community's topic is already taken in our list.
- no self-promotion, unless in partnership: please contact the @bitsocialnet org devs for partnership inquiries.

>### Isn't this list supposed to be decentralized? Why are there requirements to have my community included?
This list is not mandatory on Bitsocial itself, which is fully decentralized: nobody can stop a Bitsocial user from connecting P2P to your community, if they know its address.

However, the developer of each Bitsocial client effectively holds veto power over the list, since the list has to be manually implemented in the frontend code of the interface/client. If you don't like how a Bitsocial client dev implements this list, you are always free to create your own Bitsocial client, even using your own list.

Our web and desktop clients (Seedit, 5chan) don't use blacklists. You can use our clients to connect to any specific community by using its address, whether it's included in this default list or not.

## NSFW communities

NSFW content is supported, but it might be hidden by default in the client, depending on its target audience.

A NSFW community must have at least 1 of these 4 NSFW tags: "adult", "anti", "gore", "vulgar".

- "adult" (NSFW): all communities with nudity/pornographic content.
- "anti" (may be considered inappropriate, depending on the client): all communities anti-anything.
- "gore" (NSFW): all communities with graphic violence/gore/war content.
- "vulgar" (may be considered inappropriate, depending on the client): all communities with vulgar content.
