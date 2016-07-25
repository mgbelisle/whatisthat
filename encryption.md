I am a programmer, and one of things I use frequently and understand fairly well is the concept of how to secure data so that only authorized parties can access it. That being the case, friends and family and strangers who are not programmers often ask me to explain things they hear in the news related to the following topics which are all somewhat related on different levels. I hope the info is understandable enough to shed some light on the subjects so readers can see the social implications of each one.

# What is encryption?

Encryption is when you have data, like `The dog ate my pizza`, and with some fancy math turn it into ciphertext, like this, which can only be read by someone who has a special key.

```
jA0EBwMCrPvXs9Mt+7tg0kkBSFdcRef5GBvxX1cJBrJQynGJRlzc1US5OxBZGDZkQJu4fmn35vl4R2U+/lr9hV/dhEoY043j/6VSf4CbqAK8KcT2bVDF/CmE
```

In this case the key was ``5EScJ'xM@1ABa5'Olm1*)`;98l:f~l-K``, and with that key you can decrypt the ciphertext back into the original plaintext `The dog ate my pizza`. The important part is that the data *cannot* be read without the key, and even a key that short is too big for anyone to guess. No matter how much computation you do, even if you ran all the supercomputers in the world for several years, it wouldn't even come close to guessing the key. This is called *strong encryption* and has existed for a couple decades now, and it means that people without the key cannot read the data, which means *theives cannot read it* and *governments cannot read it*.

That second point is what has brought the topic of encryption into the news, because governments do not like it when they want to read something, but cannot, because of math. It becomes very painful some times, like when a convicted murderer's hard disk contains possible evidence exposing other murderers' identities, and the police cannot read the disk because it is encrypted and the owner is dead. The judges and politicians involved in such cases have been fighting against the existence of strong encryption, and hopefully everyone can see why, because sometimes it hurts. What the news media and the policitians usually fail to explain is that every day in millions of instances, strong encryption protects your data from other less lawful parties who would like to read it. Every bank account, credit card number, medical record, and personal email is or should be protected by strong encryption. You cannot have digital security which blocks a thief but somehow does not block the government, and that is not because of any laws, it is because that is the way math works.

## What went on with the San Bernadino shooter's iPhone?

The San Bernadino shooter's iPhone event was an interesting case with lots of nuances, but the important parts to know was that the shooter's iPhone was an old model with relativlely weak encryption (model 5C with a four digit guessable pin instead of a 256 bit unguessable key which the newer iPhones have), which is why the FBI was able to pay some specialists $1.3 million to crack it. Apple's response that they would not crack it was a good one in my opinion, because they were not only legitimately protecting their customers from identity thieves who would steal the government's "back door", but also because legal requests to crack into the current generation of iPhones under the same circumstances are not possible even for Apple.

# What is bitcoin?

Bitcoin is a digital currency, like the US dollar or the British Pound, except it is more like gold than a dollar. It is based on a computer's proof that it has done a certain amount of computation via encryption. It is in my opinion a revolutionary concept that fulfills its claim of having the following characteristics, even though it is mysterious to most people.

* Impossible to counterfeit (like gold, you can test if gold is gold)
* Impossible to inflate (like gold, you can't print one million new pounds of it)
* Easy to exchange (like gold or cash, I can give you some and you can give me some, no middle man needed)

It has been around since 2009. Here are the most common questions I get asked about bitcoin:

## Who decides a bitcoin's value?

Just like gold, the market decides the value of a bitcoin, aka people's willingness to trade it for X. The value has been highly volatile since its beginning as people's perception of it changes (today, July 20th 2016, you can exhange one bitcoin for $667), but that volatility will probably steady itself out over time as it becomes more and more well known and used.

## What government is in charge of bitcoin?

Just like gold, there is no government in charge of bitcoin. Its value will collapse if the whole internet dies or if people abandon it, but it will not collapse if some government does.

## Who invented bitcoin?

In October 2008, the idea of bitcoin was sent to the world by an anonymous individual who called himself Satoshi Nakamoto, and to this day his identity is unknown despite many attempts to discover it. He emailed a nine page academic paper to the world's leading cryptographers in which he explained the idea of bitcoin and posted the computer source code necessary to run it.

https://bitcoin.org/bitcoin.pdf

Then, over the next couple years he helped them setup the network until it was running well, and then he just disappeared. There have been many guesses about his identity but most of them have been proveably wrong, and it is likely that his identity will never be uncovered.

## Is bitcoin anti-government?

No. Even if the very extreme were to happen that the American people abandoned the dollar in place of bitcoin, there are many effective governments that operate on currency issued by someone else, like Germany or the State of Montana or the City of Boonville Missouri. They are just as legitimate, they still collect taxes, prosecute criminals, etc. without issuing their own currency.

But in the US, our leaders all swear to uphold and defend the Consitution so what it has to say about currency is important to us. It says:

[Article 1 Section 8 and 10](http://www.archives.gov/exhibits/charters/constitution_transcript.html)

> Congress shall have Power To lay and collect Taxes ... To coin Money, regulate the Value thereof, and of foreign Coin, and fix the Standard of Weights and Measures;

> No State shall ... coin Money; emit Bills of Credit; make any Thing but gold and silver Coin a Tender in Payment of Debts;

And that is fine. The US can still issue its US dollar, states cannot issue their own currencies, and both bitcoins and dollars can be exchanged for gold or silver so I see no fundamental problem there.

One reason that people blame bitcoin for being anti-government is because there are criminal groups that find it useful. This is very true, but it is in my opinion a weak and ill informed view of what it means for something to be anti-government. Paper shreaders, matches, cars, shovels, and cash are all "anti-government." Criminals shread their paperwork, they light things on fire, drive to their criminal activities, bury corpses, and pay with cash, but does this mean that we should outlaw or even regulate the shreaders, matches, cars, shovels, and cash they used for those things? No, of course not. Blaming bitcoin for the online black market (called the dark web) is like blaming Exon gas stations for the string of arsons in Kentucky last month.

Another reason why people blame bitcoin for being anti-government is because they think it is *entirely anonymous*. People take this claim very far, sometimes arguing that bitcoin was designed specifically for criminal activities because of its anonymity. This is in my opinion another ill informed view that is easily cleared up when you look at the technical details. All bitcoin transactions are stored visibly, traceably, and permanently in the bitcoin public ledger. This means that you can see every time which bitcoin address paid which other bitcoin address exactly how many bitcoins. That provides an unprecedented level of transparency to the currency, but "anonymous" payments are still possible if you want to do them by making a new address for each transaction. If you never reveal the fact that you own that address e.g. `1FNNY51HzjkSEkNt7yJ7pkwrxNbgJiGHxN` then no one will know it was you. So the bottom line is that some bitcoin payments are anonymous, but some are not, and it depends what the user wants.

## Is bitcoin a good investment?

No. When bitcoin's value jumped from ~$25 to ~$1100 dollars per bitcoin in 2013, people started thinking that it was a good investment, but unfortunately it is not. Long term high risk stock portfolios are a good investment; bitcoin is a currency, a particularly volatile one right now, and is not a good investment.

## How do you create bitcoins?

A bitcoin is created when any computer on the bitcoin network finds the numeric solution to an extremely difficult math problem, and the bitcoin is awarded to that computer when it announces the solution to the network. The math problem is called a cryptographic hash, and the most important characteristic of a hash is that it is 1) very hard to calculate, and 2) very easy to verify. For explanatory purposes, it is like I give you a pencil and paper and say `Find the prime factors of 23792243`. No matter how talented at math you are, it would take months or years to find that the solution is `367 * 269 * 241` but then it would take just a few minutes for anyone else with a pencil and paper to verify that is correct `367 * 269 * 241 = 23792243`.  The difficulty of the math problems are adjusted by the bitcoin network so that bitcoin supply roughly approximates the world wide supply of gold over the centuries.

# What is the dark web?

There is a subset of the internet that is widely referred to as the "dark web," but that is a loaded term in my opinion and I prefer to use the term "anonymity networks." The point of these networks is to provide anonymous sharing of online content, and they include networks like TOR, Freenet, and I2P which use strong encryption to keep users anonymous, whereas normal internet use is not anonymous for a number of technical reasons. There are of course legitimate uses and illegitimate uses of these networks, but since the media focuses on the illegitimate ones I would like to explain both:

## Do bad things happen on the anonymity networks?

Yes. Astonishingly bad things happen on these networks, unfortunately. You can order a kilo of cocain to your doorstep as if it were amazon.com, and you can buy ten thousand stolen credit card numbers, or ten thousand counterfeit bills from a seller with a five star rating. You can radicalize a suicide bomber or hire a hitman. To say all of these things are terrible is an understatement.

## Do good things happen on the anonymity networks?

Yes. Human rights activists report government atrocities. FBI agents track down ISIS cells. Whistleblowers expose political leaders doing offshore tax evasion. All of these people need anonymity to avoid retaliation from the entities they seek justice against.

Whether you agree or disagree with the existence of these networks, the important thing to understand is that they an all or nothing proposition. Anonymity is anonymity whether it is for Hitler or Mother Teresa, and you cannot eliminate one without eliminating both.