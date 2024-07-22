# Awesome resources for ATProto & Bluesky

Bluesky is an open source micro-blogging platform powered by the AT protocol. This protocol enables the creation of
powerful third-party tools, listed here for easy reference.

Are you a programmer? Check out this GitHub repository which overlaps with some items on this list, but has many other
resources for libraries, clients, bots, etc.

Do you know of another tool? Either submit it here as a [pull request](https://github.com/pirmax/awesome-bluesky/pulls),
or just tell me about it ([@pirmax.fr](https://bsky.app/profile/pirmax.fr)) on Bluesky.

**When using third-party apps, please always use an [app password](https://bsky.app/settings/app-passwords) and never your master password!**

## Table of Contents

- [Alternative Clients](#alternative-clients)
- [API](#api)
- [Clients](#clients)
- [Bots](#bots)
- [Feeds](#feeds)
- [Languages](#languages)
- [Migration](#migration)
- [Other Tools](#other-tools)
- [Statistics](#statistics)
- [User Interactions](#user-interactions)
- [Videos](#videos)

## Alternative Clients

| Name                                              | Description                                                                      | Source                                           |
|:--------------------------------------------------|:---------------------------------------------------------------------------------|:-------------------------------------------------|
| [deck.blue](https://deck.blue/)                   | Alternative web client with column view                                          |                                                  |
| [Graysky](https://graysky.app/)                   | Alternative mobile client for both Android and iOS                               |                                                  |
| [Kite](https://kite.black)                        | Alternative web client                                                           |                                                  |
| [Langit](https://langit.pages.dev/)               | Alternative mobile web client                                                    |                                                  |
| [Nootti](https://nootti.com)                      | Alternative native iOS/iPad cross-posting client for Bluesky, Mastodon and Nostr |                                                  |
| [Sky.app](https://github.com/jcsalterego/Sky.app) | Alternative MacOS client                                                         | [Source](https://github.com/jcsalterego/Sky.app) |
| [SkyFeed](https://skyfeed.app)                    | Alternative web client with a powerful custom feed builder                       |                                                  |
| [TOKIMEKI](https://tokimekibluesky.vercel.app/)   | Alternative web client                                                           |                                                  |
| [vSky](https://www.vsky.social/)                  | Alternative client in the form of a progressive web app                          |                                                  |

## API

| Name                                                                                                 | Description                                    | Source                                                     |
|:-----------------------------------------------------------------------------------------------------|:-----------------------------------------------|:-----------------------------------------------------------|
| [BlueSky Wrapper](https://blue.amazingca.dev)                                                        | Interactive API Wrapper to test queries        |                                                            |
| [DID Lookup Endpoint](https://bsky.social/xrpc/com.atproto.identity.resolveHandle?handle=YourHandle) | Get a handles DID                              |                                                            |
| [Feed Generator](https://github.com/bluesky-social/feed-generator)                                   | A repository to create a basic feed in bluesky | [Source](https://github.com/bluesky-social/feed-generator) |
| [SkyBridge](https://skybridge.fly.dev)                                                               | Mastodon Instance Proxy                        |                                                            | 

## Clients

| Name                                                  | Description                                                | Source |
|:------------------------------------------------------|:-----------------------------------------------------------|:-------|
| [GreySky](https://graysky.app)                        | Mobile Client                                              |        |
| [Kite](https://kite.black)                            | Web client for Bluesky                                     |        |
| [SkeetDeck](https://tokimekibluesky.vercel.app/login) | TweetDeck Clone                                            |        |
| [SkyFeed](https://skyfeed.app)                        | Alternative web client with a powerful custom feed builder |        |

## Bots

| Name                                                                                       | Description                                                                               | Source                                                        |
|:-------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------|:--------------------------------------------------------------|
| [@earthquake.bsky.social](https://bsky.app/profile/earthquake.bsky.social)                 | Bot that posts earthquakes of 5.0+ magnitude                                              | [Source](https://github.com/emilyliu7321/bsky-earthquake-bot) |
| [@haiku-bot.bsky.social](https://bsky.app/profile/haiku-bot.bsky.social)                   | Bot that posts a haiku every 15 minutes on Bluesky!                                       | [Source](https://github.com/ssempervirens/bluesky-haiku)      |
| [@indigitalcolor.bsky.social](https://staging.bsky.app/profile/indigitalcolor.bsky.social) | A basic example of a script to create posts with images generated by p5.js to Bluesky     | [Source](https://github.com/M0nica/bluesky-artbot)            |
| [@limerick.bot.gar.lol](https://staging.bsky.app/profile/limerick.bot.gar.lol)             | Bot that posts limericks                                                                  | [Source](https://github.com/rothos/limerickbot)               |
| [@remind.bluesky.bot](https://bsky.app/profile/remind.bluesky.bot)                         | Official Bluesky Reminder Bot                                                             |                                                               |
| [@skies.bsky.social](https://bsky.app/profile/skies.bsky.social)                           | Bluesky Emoji Bot                                                                         | [Source](https://github.com/emilyliu7321/bluesky-emoji-bot)   |
| [@spells.bsky.social](https://bsky.app/profile/spells.bsky.social)                         | Bluesky Emoji Spells Bot                                                                  | [Source](https://github.com/MichaelPriebe/emoji-spells-bot)   |
| [@vvvot.bsky.social](https://bsky.app/profile/vvvot.bsky.social)                           | @vvvot.bsky.social bot implementation                                                     | [Source](https://github.com/vvakame/atproto-vvvot)            |
| [Bluesky Account Creator](https://bluesky-account-creator.vercel.app)                      | Bluesky Account Creator                                                                   | [Source](https://github.com/akiomik/bluesky-account-creator)  |
| [Bluesky APOD Bot](https://github.com/myConsciousness/bluesky-apod-bot)                    | APOD Bot for Bluesky Social                                                               |                                                               |
| [Bluesky Bots](https://github.com/whyrusleeping/bskybots)                                  | Some bot programs for the bluesky network                                                 |                                                               |
| [Bluesky Food Safety Bot](https://github.com/lovelaced/bluesky-food-safety-bot)            | Bot that posts food safety notices from the UK Food Standards Agency to your Bluesky feed |                                                               |
| [Bluesky HugFairy](https://github.com/haideralipunjabi/bluesky-hugfairy)                   | Bot to send hugs to other users on bluesky                                                |                                                               |
| [KoanBot](https://github.com/trozzelle/koanbot)                                            | GPT3.5-powered bot that posts Zen koans                                                   |                                                               |

## Feeds

| Name                                      | Description                                                | Source |
|:------------------------------------------|:-----------------------------------------------------------|:-------|
| [BlueStream](https://bluestream.deno.dev) | RSS feed generator                                         |        |
| [Good Feeds](https://goodfeeds.co/)       | Custom feed directory/search engine and builder            |        |
| [SkyFeed](https://skyfeed.app)            | Alternative web client with a powerful custom feed builder |        |

## Languages

### Python

| Name                                                       | Description                                                                           | Source                                               |
|:-----------------------------------------------------------|:--------------------------------------------------------------------------------------|:-----------------------------------------------------|
| [atproto](https://github.com/MarshalX/atproto)             | The AT Protocol SDK for Python                                                        | [Source](https://github.com/MarshalX/atproto)        |
| [atprototools](https://github.com/ianklatzco/atprototools) | Easy-to-use and ergonomic library for interacting with bluesky                        | [Source](https://github.com/ianklatzco/atprototools) |
| [nanoatp](https://github.com/susumuota/nanoatp)            | A nano implementation of the AT Protocol (Authenticated Transfer Protocol) for Python | [Source](https://github.com/susumuota/nanoatp)       |
| [psychonaut](https://github.com/jbn/psychonaut)            | Python async bluesky client and TUI (eventually)                                      | [Source](https://github.com/jbn/psychonaut)          |

### C# (CSharp)

| Name                                                       | Description                                               | Source                                              |
|:-----------------------------------------------------------|:----------------------------------------------------------|:----------------------------------------------------|
| [ATProto Sharp](https://github.com/taranasus/atprotosharp) | 3rd Party C# library for interacting with the AT protocol | [Source](https://github.com/taranasus/atprotosharp) |

### Elixir

| Name                                            | Description                                            | Source                                         |
|:------------------------------------------------|:-------------------------------------------------------|:-----------------------------------------------|
| [ATProto](https://github.com/moomerman/atproto) | Implementation of the ATProtocol client spec in Elixir | [Source](https://github.com/moomerman/atproto) |

### Dart Flutter

| Name                                                            | Description                             | Source                                                    |
|:----------------------------------------------------------------|:----------------------------------------|:----------------------------------------------------------|
| [atproto.dart](https://github.com/myConsciousness/atproto.dart) | Dart/Flutter ATProto & BlueSky packages | [Source](https://github.com/myConsciousness/atproto.dart) |
| [flutter_bluesky](https://github.com/tacsotai/flutter_bluesky)  | Dart/Flutter BlueSky client             | [Source](https://github.com/tacsotai/flutter_bluesky.git) |

### Go

| Name                                                                  | Description                        | Source                                                       |
|:----------------------------------------------------------------------|:-----------------------------------|:-------------------------------------------------------------|
| [bluesky](https://github.com/PiccoloMondoC/bluesky)                   | Bluesky Go Library                 | [Source](https://github.com/PiccoloMondoC/bluesky)           |
| [bsky](https://github.com/mattn/bsky)                                 | CLI Application for Bluesky Social | [Source](https://github.com/mattn/bsky)                      |
| [blueskyfirehose](https://github.com/CharlesDardaman/blueskyfirehose) | Simple golang firehose for Bluesky | [Source](https://github.com/CharlesDardaman/blueskyfirehose) |

### Java

| Name                                                | Description                        | Source                                          |
|:----------------------------------------------------|:-----------------------------------|:------------------------------------------------|
| [bsky4j](https://github.com/uakihir0/bsky4j)        | Bluesky/ATProtocol client for Java | [Source](https://github.com/uakihir0/bsky4j)    |
| [SoftLibATP](https://github.com/okomeki/SoftLibATP) | SoftLibATP                         | [Source](https://github.com/okomeki/SoftLibATP) |

### Kotlin

| Name                                                                                             | Description                                        | Source                                             |
|:-------------------------------------------------------------------------------------------------|:---------------------------------------------------|:---------------------------------------------------|
| [Example App for Android](https://play.google.com/store/apps/details?id=io.github.akiomik.seiun) | An experimental ATP/Bluesky client app for Android | [Source](https://github.com/akiomik/seiun)         |
| [OZone](https://github.com/christiandeange/ozone)                                                | Android/desktop client for Bluesky                 | [Source](https://github.com/christiandeange/ozone) |

### Rust

| Name                                                     | Description                                                 | Source                                             |
|:---------------------------------------------------------|:------------------------------------------------------------|:---------------------------------------------------|
| [ATP](https://github.com/nrempel/atp)                    | A command line tool for the Authenticated Transfer Protocol | [Source](https://github.com/nrempel/atp)           |
| [ATProto Rust](https://github.com/ngerakines/atproto-rs) | A suite of libraries, tools, and daemons for atproto        | [Source](https://github.com/ngerakines/atproto-rs) |
| [Bisky](https://github.com/jesopo/bisky)                 | Bluesky API library                                         | [Source](https://github.com/jesopo/bisky)          |
| [Bsky Rust](https://github.com/sizumita/bsky-rs)         | The ATProto(Bluesky) API implementation in Rust             | [Source](https://github.com/sizumita/bsky-rs)      |

### Swift

| Name                                              | Description                                  | Source                                          |
|:--------------------------------------------------|:---------------------------------------------|:------------------------------------------------|
| [Swiftsky](https://github.com/rmcan/swiftsky.git) | Unofficial Bluesky/ATProto client in SwiftUI | [Source](https://github.com/rmcan/swiftsky.git) |

### TypeScript

| Name                                                                                                    | Description                                                                | Source                                                              |
|:--------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------|:--------------------------------------------------------------------|
| [ATProto Feed Generator Starter Kit](https://github.com/bluesky-social/feed-generator)                  | ATProto Feed Generator Starter Kit                                         | [Source](https://github.com/bluesky-social/feed-generator)          |
| [ATProto Starter Kit](https://github.com/aliceisjustplaying/atproto-starter-kit)                        | ATProto Starter Kit                                                        | [Source](https://github.com/aliceisjustplaying/atproto-starter-kit) |
| [ATProto Starter Kit for deno](https://github.com/sharunkumar/atproto-starter-kit)                      | ATProto Starter Kit for deno                                               | [Source](https://github.com/sharunkumar/atproto-starter-kit)        |
| [Azure](https://github.com/ajroberts0417/azure)                                                         | Web client for Bluesky using Next.js                                       | [Source](https://github.com/ajroberts0417/azure)                    |
| [at.syui.ai](https://at.syui.ai/)                                                                       | Web client for Bluesky using Vue                                           | [Source](https://github.com/syui/at.syui.ai)                        |
| [boobeeblue](https://github.com/KingYoSun/boobeeblue)                                                   | Web client for Bluesky using Next.js                                       | [Source](https://github.com/KingYoSun/boobeeblue)                   |
| [Bluesky client for Mac, Linux and Windows](https://github.com/pram11/Jet)                              | Bluesky client for Mac, Linux and Windows                                  | [Source](https://github.com/pram11/Jet)                             |
| [Bluesky Expo client](https://github.com/jonsamp/bluesky-expo)                                          | Bluesky Expo client                                                        | [Source](https://github.com/jonsamp/bluesky-expo)                   |
| [Bluesky Experiments](https://github.com/susumuota/bluesky-exp)                                         | Bluesky Experiments                                                        | [Source](https://github.com/susumuota/bluesky-exp)                  |
| [Bluesky Photo Test](https://github.com/robpc/bluesky-photo-test)                                       | Bluesky Photo Test                                                         | [Source](https://github.com/robpc/bluesky-photo-test)               |
| [Bluesky React Native Example app for AT Protocol](https://github.com/pfrazee/example-atproto-rn-app)   | Bluesky React Native Example app for AT Protocol                           | [Source](https://github.com/pfrazee/example-atproto-rn-app)         |
| [CLI tools for posting on bluesky](https://github.com/Jazzkid0/bsky-cli-tools)                          | CLI tools for posting on bluesky                                           | [Source](https://github.com/Jazzkid0/bsky-cli-tools)                |
| [poastbox](https://github.com/tautologer/poastbox)                                                      | Web client for Bluesky using Svelte                                        | [Source](https://github.com/tautologer/poastbox)                    |
| [Practice Bluesky API (deno)](https://github.com/Neos21/practice-bsky)                                  | Practice Bluesky API (deno)                                                | [Source](https://github.com/Neos21/practice-bsky)                   |
| [Skylight](https://penpenpng.github.io/skylight/)                                                       | Web client for Bluesky using Vue                                           | [Source](https://github.com/penpenpng/skylight)                     |
| [Template bot with GitHub Action to schedule posts](https://github.com/philnash/bsky-bot)               | Template bot with GitHub Action to schedule posts                          | [Source](https://github.com/philnash/bsky-bot)                      |
| [The Bluesky Social application for Web, iOS, and Android (Official client)](https://staging.bsky.app/) | The Bluesky Social application for Web, iOS, and Android (Official client) | [Source](https://github.com/bluesky-social/social-app)              |
| [Web client for Bluesky](https://blueskyweb.vercel.app/)                                                | Web client for Bluesky                                                     | [Source](https://github.com/fredabila/blueskyweb)                   |
| [Web client for Bluesky](https://flat-bs.vercel.app)                                                    | Web client for Bluesky                                                     | [Source](https://github.com/sabigara/flat)                          |
| [Web client for Bluesky](https://github.com/angelocho/BlueSkyweb)                                       | Web client for Bluesky                                                     | [Source](https://github.com/angelocho/BlueSkyweb)                   |
| [Web client for Bluesky](https://kite.black/)                                                           | Web client for Bluesky                                                     | [Source](https://github.com/callmearta/kite)                        |
| [Web client for Bluesky](https://treyp.github.io/nightsky)                                              | Web client for Bluesky                                                     | [Source](https://github.com/treyp/nightsky)                         |

## Migration

| Name                                                                                                                  | Description                                                         | Source |
|:----------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------|:-------|
| [Fedifinder](https://fedifinder.glitch.me/)                                                                           | Your X/Twitter contacts on Bluesky and the fediverse                |        |
| [Follow the Sky](https://gggdomi.github.io/follow-the-sky/)                                                           | Find again in Bluesky people you follow on Twitter                  |        |
| [Skeet](https://skeet.labnotes.org/)                                                                                  | find your Twitter or Mastodon mutuals on Bluesky                    |        |
| [Skeeter](https://skeeter.streamlit.app/)                                                                             | Twitter/Mastodon to Bluesky User Search                             |        |
| [Sky Follower Bridge](https://chrome.google.com/webstore/detail/sky-follower-bridge/behhbpbpmailcnfbjagknjngnfdojpko) | Chrome add-on to find your Twitter follows and followers on Bluesky |        |

## Other Tools

| Name                                                                               | Description                                                                                                                                                     | Source                                                        |
|:-----------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------|
| [atproto-website-docs-jp](https://github.com/encrypteduse/atproto-website-docs-jp) | Japanese ATProto Docs                                                                                                                                           |                                                               |
| [bannerizer](https://bannerizer.glitch.me/)                                        | Easily crop or resize an image to fit Bluesky's banner size requirements                                                                                        |                                                               |
| [blue-mirage](https://jiftechnify.github.io/blue-mirage/)                          | Tool for copying someone else's follow list on Bluesky                                                                                                          | [Source](https://github.com/jiftechnify/blue-mirage)          |
| [Bluesky ESPHOME](https://github.com/softplus/bluesky_esphome)                     | Bluesky-ESPHOME basic config                                                                                                                                    |                                                               |
| [Bluesky Follow Back All](https://jiftechnify.github.io/bsky-follow-back-all/)     | Bluesky Follow Back All                                                                                                                                         | [Source](https://github.com/jiftechnify/bsky-follow-back-all) |
| [Bluesky Link Preview](https://github.com/capjamesg/bsky-link-preview)             | Generate embeddable link previews to posts on Bluesky                                                                                                           |                                                               |
| [Bluesky Post Action](https://github.com/zentered/bluesky-post-action)             | A GitHub Action to post to Bluesky Social                                                                                                                       |                                                               |
| [Bluesky.bot](https://bluesky.bot)                                                 | Claim your handle.bluesky.bot username for free if you have a bot on Bluesky.                                                                                   |                                                               |
| [BlueskyAutoPost](https://github.com/alextoma1217/BlueskyAutoPost)                 | Schedule daily posts on Bluesky                                                                                                                                 |                                                               |
| [bluesky-crossposter](https://github.com/Linus2punkt0/bluesky-crossposter)         | Python script to crosspost bluesky content to Twitter and Mastodon                                                                                              | [Source](https://github.com/Linus2punkt0/bluesky-crossposter) |
| [bluesky-overhaul](https://github.com/xenohunter/bluesky-overhaul)                 | UX improvements for Bluesky web app (browser extension)                                                                                                         |                                                               |
| [Bluestream Deno](https://bluestream.deno.dev/)                                    | RSS feed generator for Bluesky                                                                                                                                  | [Source](https://github.com/kawarimidoll/bluestream)          |
| [Blueviewer](https://blueviewer.pages.dev/)                                        | Bluesky thread viewer                                                                                                                                           |                                                               |
| [Blockenheimer](https://blockenheimer.click/)                                      | Quickly block or mute users who have liked or reposted any given post                                                                                           |                                                               |
| [BskyThreadReader](https://bskythreadreader.glitch.me/)                            | Look at and share any Bluesky Thread without logging in.                                                                                                        |                                                               |
| [bsky-event-handlers](https://github.com/juni-b-queer/bsky-event-handlers)         | A simple and extendable Typescript framework and package for creating Bluesky bots that consume the firehose stream, without having to touch any firehose code. |                                                               |
| [ClearSky Search Tool](https://bsky.thieflord.dev/)                                | See who is blocking you, who a user is blocking, the total amount of Bluesky users, or look up a DID.                                                           |                                                               |
| [Combine Twitter/Bluesky](https://test-maker-khaki.vercel.app/)                    | Combine your Twitter and Bluesky feeds into one                                                                                                                 | [Source](https://github.com/devyboy/Skybird)                  |
| [create-bsky-bot](https://github.com/juni-b-queer/create-bsky-bot)                 | A `bunx` template to scaffold all the files for a bot built with bsky-event-handlers. Built in Typescript, meant for use with BunJS.                            |                                                               |
| [did:plc Tracker](https://plc-handle-tracker.kpherox.dev/)                         | Tracker for did:plc & atproto handle                                                                                                                            |                                                               |
| [Firesky](https://firesky.tv/)                                                     | Every post everywhere all at once                                                                                                                               |                                                               |
| [graysky.social](https://graysky.social/)                                          | Community handle provider                                                                                                                                       |                                                               |
| [Link](https://bsky.link)                                                          | Embed BSky Links                                                                                                                                                |                                                               |
| [newwords](https://github.com/capjamesg/newwords)                                  | Post new words used in my blog posts to Bluesky.                                                                                                                |                                                               |
| [NightSky](https://github.com/asamaree/NightSky)                                   | NightSky is a browser extension that transforms your BlueSky social experience into a sleek, dark interface that's easy on the eyes                             |                                                               |
| [Polls](https://poll.blue)                                                         | Create a poll on Bluesky                                                                                                                                        |                                                               |
| [psky.app](https://github.com/ianklatzco/psky.app/)                                | Replace "bsky" in URLs with "psky" to embed posts in Discord, Telegram, etc                                                                                     |                                                               |
| [QNA.blue](https://qna.blue)                                                       | A popular Questions & Answers messaging platform for the next generation.                                                                                       |                                                               |
| [Send Bluesky Post](https://github.com/marketplace/actions/send-bluesky-post)      | A GitHub Actions workflow to send a post to Bluesky                                                                                                             | [Source](https://github.com/myConsciousness/bluesky-post)     |
| [skeet](https://crates.io/crates/skeet)                                            | A simple command line tool to create text posts                                                                                                                 | [Source](https://github.com/sharunkumar/skeet)                |
| [SkyBridge](https://skybridge.fly.dev/)                                            | Proxy between Bluesky and Mastodon                                                                                                                              |                                                               |
| [Skycle.app](https://skycle.app)                                                   | Visualize your circle of friends on Bluesky                                                                                                                     |                                                               |
| [Skyname](https://skyna.me)                                                        | Username registrar with fun domains like bsky.cool, tired.io                                                                                                    | [source](https://github.com/darnfish/skyname)                 |
| [SkySweeper](https://skysweeper.p8.lu/)                                            | Automatically delete old posts                                                                                                                                  |                                                               |
| [Skythread](https://mackuba.github.io/skythread/)                                  | Thread viewer                                                                                                                                                   |                                                               |
| [SkyTools](https://skytools.anon5r.com/)                                           | User handle history and DID look up tool                                                                                                                        |                                                               |
| [Skyview](https://skyview.social/)                                                 | View and share BlueSky threads without needing a BlueSky account.                                                                                               |                                                               |
| [sunblock](https://github.com/trozzelle/sunblock)                                  | Script to block spam accounts that follow you                                                                                                                   |                                                               |

## Statistics

| Name                                                  | Description                                                                                                                 | Source                                                          |
|:------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------|
| [Atlas](https://bsky.jazco.dev)                       | Engagement based social graph                                                                                               |                                                                 |
| [Bluesky Heatmap](https://bluesky-heatmap.fly.dev)    | Bluesky Posts Heatmap Generator                                                                                             | [Source](https://github.com/aliceisjustplaying/bluesky-heatmap) |
| [Bluesky Stats](https://vqv.app/stats)                | Stats and top lists                                                                                                         |                                                                 |
| [Firesky](https://firesky.tv)                         | BlueSky Firehose visualiser                                                                                                 | [Source](https://github.com/aliceisjustplaying/bluesky-heatmap) |
| [SkeetDeck](https://tokimekibluesky.vercel.app/login) | Bluesky Tweetdeck client                                                                                                    | [Source](https://github.com/aliceisjustplaying/bluesky-heatmap) |
| [Twexit.nl](https://twexit.nl)                        | Self-described experimental bluesky web client. Includes functions for seeing who has blocked or muted you and other stats. |                                                                 |
| [Wolfgang](https://wolfgang.raios.xyz)                | Charts, interactions, social circles, top lists                                                                             |                                                                 |

## User Interactions

| Name                                                                    | Description                                  | Source                                                       |
|:------------------------------------------------------------------------|:---------------------------------------------|:-------------------------------------------------------------|
| [Atlas](https://bsky.jazco.dev)                                         | An Engagement-based social graph for Bluesky |                                                              |
| [Interaction graphic](https://wolfgang.raios.xyz/interactions)          | Interaction image generator for past 7-days  |                                                              |
| [Posting Leaderboards](https://vqv.app/stats)                           | Posting Leaderboards                         |                                                              |
| [Twt Mutual Finder](https://github.com/kawamataryo/sky-follower-bridge) | Twitter Mutual Finder                        | [Source](https://github.com/kawamataryo/sky-follower-bridge) |

## Videos

| Name                                                                       | Description                                | Source |
|:---------------------------------------------------------------------------|:-------------------------------------------|:-------|
| [ActivityPub vs AT Protocol](https://youtu.be/wJBCpzM1VfM)                 | ActivityPub vs AT Protocol                 |        |
| [Is Bluesky fediverse, web3, or blockchain?](https://youtu.be/qI7LR6FSLrI) | Is Bluesky fediverse, web3, or blockchain? |        |
| [Use a custom domain as username in Bluesky](https://youtu.be/lP3OVCwyqJA) | Use a custom domain as username in Bluesky |        |
