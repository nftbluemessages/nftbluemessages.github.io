# Live Quote collections (NFT tokens derived from tweets)

## Introduction
The Live Quotes NFT collections follow one specific Twitter account, and
mint digital image NFTs derived from tweets from those accounts, as follows:

1. each NFT is derived from ONE specific tweet, and is minted within one hour (often sooner) than the tweet publication.
2. the chosen NFT image style and properties is derived from the tweet text.

This creates a one-to-one mapping between each tweet and the corresponding minted NFT item,
as both WHEN an NFT is minted and WHAT it contains, is actually determined by/derived from the tweet.

Important: these collections are not sanctioned by either Twitter or the Twitter accounts. 
Thus, ownership of the NFTs in the collections do NOT in any way imply ownership of the tweets.


## Example, how it works
1. On december 24, 2022, Elon Musk tweets "Merry Christmas!"
2. Within an hour, the tweet has triggered the minting of a new NFT in the "Elon Live Quotes" NFT collection.
4. An image of Elon Musk is selected as the base image for the NFT.
5. There are 5000 possible AI-based styles that can be applied to an image. Using the "Merry Christmas!" tweet text as a pseudorandom seed, this results in the style 300 being applied to the image.
6. The pseudorandom seed also determines that the image should be rendered in grayscale, and flipped vertically.
7. The base image of Elon Musk is rendered with AI-style 300, and then rendered in grayscale, and flipped vertically.
8. The NFT is minted. It contains:
   * the Tweet account name, timestamp of the original tweet, and a partial quote of the tweet text as title.
   * the AI-rendered image.
   * properties indicating what style was used, and that the image was rendered in grayscale, and flipped. 
   * a link to the original tweet in the description. 
9. The NFT is listed on sale.
10. Hopefully, someone buys the NFT, as he/she thinks it's will be interesting/fun to own the NFT associated with that particular tweet.

## Current NFT collections:
* [Elon Live Quotes](https://opensea.io/collection/elon-live-quotes)


## FAQ

### How is this approach better than having NFT collections with one-time randomly generated tokens?
This approach is not necessarily better. It's just different, and quite interesting.
Because this way, it's not really up to the NFT collection creators to determine WHEN and WHAT NFTs to render, 
but instead this is determined by the actions of the followed Twitter accounts.

Also, having the real-world dependency to tweets makes tokenomics of the NFTs interesting in several ways.
For instance:
* the scarcity of the tokens depends on whether tweets are posted or not.
* the uniqueness of the image styles and properties, which affects the desirability of the NFTs, are not predetermined/known beforehand.
* as each NFT is derived from ONE specific tweet, this could make some NFTs may be more desirable than others, depending on things like:
  * the popularity and/or controversy of the tweet they are derived from.
  * the likes/retweets of the original tweet.

### The AI-styled images are lazy/shoddy work, so why should I care about this?
Most of the work in implemented this NFT collection has not been centered in the 
NFT artwork itself, but rather in concept itself, of live-creating NFTs derived from posted tweets.
Having said that, the roadmap at the bottom of this page DOES contain plans to enhance the image generation, 
so this should improve over time.

Also, just as with many other NFT collections based on random/pseudorandom NFT minting, 
desirability of the NFTs is not really about the art quality of the generated NFT images themselves.
Instead, this resides in the tokenomics and uniqueness of the properties of the individual NFT:s.

This still applies here, as certain property combinations will be more unique than others.
And again, as mentioned in the answer to the previous question, 
the desirability of these NFTs is also mostly likely to depend on 
the one-to-one mappings between the NFTs and the tweets they are derived from.

### The pseudorandom seed does not guarantee unique NFTs, right? 
True. Different tweet messages may result in the same AI-rendered image style and properties. 
Also, many tweets may contain the same text, which of course will determine the chosen AI-rendered style for the images.

So yes. This can happen. BUT this is necessarily not a bad thing. For instance, one could argue that NFTs that
happen to share the same style than other NFTs, may instead add more uniqueness/value to them. 
That is really up to the market to decide.

### Aren't there copyright infringements issues at hand here?
Maybe. We are quite sure that Twitter might not be too happy about this.
And probably neither might some/most of the Twitter account owners.

BUT, regarding whether this is copyright infringement or not, we feel quite confident that is not the case.

For instance, we quote tweet texts in the title, and tweets are copyrightable, 
but ONLY if they are original and contain a minimum amount of creativity. 
Additionally, we are quoting them, and trimming them if they are too long, 
thus not using the entire tweet text as title.

Also, the main contents of the NFT is not the title, but the image.

And in our case, all base images have licenses that allows us to use them for commercial purposes.
Additionally, to the fact that the images represent the account holders, we don't see any problem with this.
Artists are allowed to paint and sell portraits of famous people, so why should this be any different?

Also, relating to the NFTs linking to the tweets themselves, this is not illegal. These are regular links,
with an information purpose, to let the owner of the NFT knowing what tweet was the source for the NFT minting.
This does not in any way imply ownership of the tweet themselves, 
something that we also mention very clearly at the very beginning of this page, 
AND within the description of each minted NFT.

### Why are these NFTs so expensive? 
We have set an intentional pricing ladder, setting a high
price on the first 20 items of each NFT collection. 

Just simply because they  are the first ones, and thus might be more desirable than the rest.
But after those first 20 items, the price goes down.

### Image attributions for base images from Wikimedia Commons:
* https://upload.wikimedia.org/wikipedia/commons/d/da/Justin_Bieber_in_2015.jpg
* https://commons.wikimedia.org/wiki/File:Elon_Musk_2015.jpg
* https://commons.wikimedia.org/wiki/File:Michael_J._Saylor.png
* https://commons.wikimedia.org/wiki/File:Vitalik_Buterin_TechCrunch_London_2015_(cropped).jpg
* https://commons.wikimedia.org/wiki/File:Gary_Vaynerchuk_public_domain.jpg
* https://commons.wikimedia.org/wiki/File:Kim_Kardashian_portrait_2009.jpg
* https://commons.wikimedia.org/wiki/File:KBryant8.jpg
* https://commons.wikimedia.org/wiki/File:Lady_Gaga_(30358885287).jpg
* https://commons.wikimedia.org/wiki/File:Britney_Spears_2,_2011.jpg

## Roadmap and ideas of upcoming features.
* Reduce delay between tweet publications and NFT minting.
* JSON data generation and export, for other devs to toy around with.
* More interesting and diverse NFT image generation:
  * Striped and tiled images.
  * Overlays depending on tweet text (Bitcoin/Doge logo on top of image etc).
  * tweet text quote at the bottom of image (maybe not, due to copyright issues).
  * Etc.
* More Twitter accounts/NFT collections.
* Post-greation properties/traits for tweet views and retweets.
* Giveaways, such as special edition items to the owners of NFTs derived from most popular tweets of the month etc.
* NFT image and properties generation tester (for people to test the algorithm).