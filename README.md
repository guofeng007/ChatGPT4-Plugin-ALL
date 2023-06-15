
# ChatGPT4-Plugin-ALL

3个ChatGPT插件自动写书爆火，更多躺着赚钱玩法可以问AI自己

　　ChatGPT插件数量大爆发！总数已达390个，与刚开放时的74个相比，增长超过400%。
　　
　　虽然早期插件质量参差不齐体验一般，但随着后续更多新插件加入，各种“联动出奇迹”的插件组合也被挖掘了出来。

举例来说，最近很火的玩法是只给一个主题，让AI自动搜集资料并写出一本电子书。用到的核心插件是上新不久的AI Agents，可自动分解复杂任务、制订步骤并按顺序执行。再配合上两个联网插件负责搜集资料，自动写书流程就跑通了。
　　
　　这个玩法备受关注还有个现实原因：之前有人用AI写了97本电子书在网上卖，虽然质量都很辣鸡，但也赚了2000美元。现在有了自动工作流程，躺着赚钱的速度岂不是更快？
　　
　　那么问题来了：插件这么多，如何找到自己需要的，又如何从中发现更多1+1>2的工作流程呢？能不能想个办法，让ChatGPT自己来推荐……
　　
　　首先要让ChatGPT知道自己所有插件功能，然后才能回答和推荐。
　　
　　那如何让ChatGPT知道自己都有什么插件呢？首先，通过爬虫和数据清洗脚本等手段，获得所有插件的名称和功能描述。
　　
　　具体可以采用以下两种方案来避免一次全部输入给ChatGPT超出长度限制的问题。
　　①借助联网插件，读取外部数据
        ②分批发送数据
　　
　　让ChatGPT分批次接收数据需要用到思维链提示，分步骤描述整个任务流程。

1、你的任务是回答任何关于ChatGPT插件的问题

2、现在一共有390个插件，接下来我会以“{编号} {名称} - {功能描述}”的方式分批把插件数据发给你

3、在未接收完全部插件数据之前，只需要阅读并记住这些数据，并回复“收到，请继续发送下一批数据”

4、接收完全部插件数据之后，请回复“已收到全部插件数据，接下来可以任意提问了”，并在后续对话中使用与提问相同的语言回答问题

5、收到这一条消息后，请回复“收到，请开始发送数据”

关键之处在于指定收到数据时的回复，尽量简短一些。不要让ChatGPT自己发挥，它自己说的话也会占用上下文长度。聊太多，ChatGPT就会脑袋过载，把前面的内容遗忘。

忘掉任务的问题还可以通过反复提醒来解决，忘掉数据就成了狗熊掰棒子，输入后面的忘掉前面的。
　　
　　输入按思维链方式打磨好的提示词后，就可以分批发送数据了。ChatGPT回复“收到”后，继续发送后面的数据就行。等全部发送完后，下一条消息就可以开始提问，让ChatGPT自己来推荐插件了。
　　
　　只要描述你的需求，就能找出合适的插件。还可以要求ChatGPT开开脑洞，推荐哪些插件联用能完成更复杂的任务。
　　
　　通过OpenAI开放的聊天记录分享功能，我们可以把已获得所有插件知识的ChatGPT分享出来。
　　
　　当然如果使用我们分享的聊天记录就可以省去插件读取资料或手动发送资料的过程，直接开始提问。

只要注意在提问时明确指定用前面读取的390个插件数据回答就行，不然有小概率会出现瞎编的情况。
　　

ChatGPT 390个插件数据

ChatGPT Plugins List， 390 in total（2023.06.13)

1 Vio.com - A better deal on your next hotel, motel or accommodation booking.
2 Timeport - Begin an exciting journey through time, interact with unique characters, and learn history in this time-travel game!
3 SG Places Beta - Provides information on attractions, F&B outlets, accommodation, tours, shops, and events in Singapore.
4 Gimmee Air Quality - Planning something outdoors? Get the 2-day air quality forecast for any US zip code.
5 Deep Memory - Create flashcards and review them on Deep Memory, a spaced repetition app.
6 Lingo - Lingo - Direct Access to the Japanese Lifestyle with One Click.
7 MixerBox Podcasts - Search podcasts easily! Explore podcasts covering society, sports, business, news, music, and more!
8 California Law - Get up to date access to California law.
9 Repo Radar - Your one-stop shop for up to date Github repo information. Find repos by topic, language, or name.
10 ReviewReader - Tired of comparing countless Amazon reviews? Input a product name or link for an instant AI summary.
11 PlugFinder - PlugFinder is your personal assistant for discovering AI tools.
12 Diagrams - Create and display diagrams from kroki.io or using networkx and matplotlib.
13 Coursera - Find recommendation for courses, specializations, and degrees on Coursera.
14 NASA Media Explorer - Discover and learn about space exploration using NASA's vast media library!
15 CoPilot - Searches every dealer, analyzes & ranks every car for you so you can buy with confidence.
16 Tira - Shop Tira for top beauty brands! Explore cosmetics, health products & more online. Your beauty store awaits.
17 Repo Inspector - Inspect Git Repositories. Submit a GitHub, Gitlab, etc., HTTPS link. The repo will be reviewed by Repo Inspector.
18 Calculator - A calculator app that executes a given formula and returns a result. This app can execute basic and advanced operations.
19 Skrive - Envision your concepts through Diagrams. This tool allows you to create and modify diagrams within the chat interface.
20 Crypto Price Checker - A Crypto Prices app that takes a pair of crypto or fiat tickers and returns the current price of the pair.
21 Ferryhopper - Search for ferries and plan your trip with the assistance of AI and Ferryhopper.
22 Copywriter - Send a URL and get sales copywriting suggestions for any page!
23 Memory Bank - Extend AI memory. Ask it to store and retrieve your information to get personalized assistance tailored to your needs.
24 Reminders - Add, remove, list and tag reminders.
25 NewsBreak - Learn about the most popular local or national news in the United States.
26 TotalQuery Search - Go beyond google search: harness the combined power of 70+ search engines for ultimate web discovery.
27 Maps - A Maps app that takes latitude and longitude coordinates and generates a map with a marker on the given spot.
28 Now - Get Google Trends. In Japan, you can also get Twitter trends and search Twitter keywords.
29 Forex-Rates - Forex Rates: Price analysis for currency markets. Gain insights, sentiment evaluation, and text completion.
30 MixerBox Scholar - Free and reliable academic search engine! Find research papers and get answers in an instant!
31 ProApp Learn Design - Level up your design skills quickly with a wide range of design courses, interactive workshops and AI-guided mentorship.
32 SummarizeAnything.ai - Summarize YouTube videos, web pages, and PDF documents by providing a link. This is a free preview.
33 ChatOCR - The best way to read text from from any document. Extract text from scanned PDFs, photos, and even handwriting.
34 HumanInf - Humanizing AI content via paraphrasing.
35 60sec site - Generate a beautiful website in 60 seconds using AI.
36 midpage caselaw - Interact with US caselaw: Summarizes text, answers questions, and checks legal statements.
37 Earthquake Info - Get latest earthquake information.
38 Playlist Follow - Create and find the best music playlists, all in one place.
39 Wanted Job Search - Explore and inquire about global job opportunities, and dive into the details of worldwide positions with precision.
40 Space Photo Explorer - Tool for exploring space through images including Mars Rover Photos, NASA image database, and space pictures of the day.
41 Broadway - Search for shows that are currently playing on Broadway in New York City.
42 Defillama - Retrieve data on DeFi protocols and blockchains.
43 Ai PDF - Super-fast, interactive chats with PDFs of any size, complete with page references for fact checking.
44 My Writing Companion - Find, hire, and manage remote human writers, the best way to ensure your content is engaging, accurate, and error-free.
45 DM Tool Kit - App for rolling dice using the d20 or Fate/Fudge systems.
46 ad4mat - API to monetize outgoing traffic via tracking links.
47 SEO - Send a URL and keyword and get a On Page SEO analysis & insights!
48 HACKIT Web Scanner - AI Powered Web Scanner by HACKIT.
49 MixerBox ChatToVideo - Summarize videos from YouTube! Ask questions and get answers right away!
50 AIstrologer - Search for the horoscope for each zodiac sign for a specific date.
51 Search UK Companies - Fetching public information on UK registered Companies and it's Officers from Companies House.
52 MixerBox Translate - Translate any language right away! Learn foreign languages easily by conversing with AI tutors!
53 Paraphraser - Say it better, say it different: Paraphrase like a Pro. Paraphrase for impact and inspire.
54 Father's Day Deals - Ideas, recommendations, and deals for Father's Day gifts.
55 Cribbage Scorer - Tool for scoring your cards in the game of cribbage.
56 TalkFPL - Talk with AI to help you manage your FPL team. Compare players, transfer options and more.
57 Gate2AI - Discover the perfect AI tools for your needs.
58 WebRewind - Get the picture of a website at a specific date.
59 MagiCodex - Ask about Magic: The Gathering cards, rules and interactions.
60 Video Highlight - Explore, research, and interact with YouTube videos and personal videos.
61 P/E For NFTs - Get the price to earnings ratio for any NFT collection!
62 MBTI - For administering an MBTI test. You can get a list of questions and calculate your MBTI type.
63 Export Chat - A Tool to export your conversation or specific parts of your conversation.
64 Experiences - Provides activity suggestions, ensuring an engaging and user-friendly travel experiences.
65 Mini Habits - Form new habits through small, daily actions.
66 CheckTheChain - Look for anything on the blockchain and get instant analysis.
67 JetBook.Click - Your ultimate travel companion: search/book flights at best prices, get info about your destination. Multilang support.
68 Image Editor - Edit images seamlessly, resize, crop, blur and many more embedded features.
69 Social Search - The Social Search provides access to tweets, users, followers, images, media and more.
70 Talkface IELTS Prep - Use the latest IELTS Speaking exam questions to prep your IELTS speaking with Talkface.
71 Speedy Marketing - Marketing tool for your Shopify store, ecommerce website or any business. Write SEO blogs and social media content.
72 Resume Copilot - I'll perfect your resume for ATS, tailor it to the job, ensuring you stand out to recruiters
73 Checkers - This allows you to play a game of checkers.
74 Career Copilot - A trusted, always on assistant to help software developers find a better job. Built by Commit.dev.
75 HeyGen - Meet HeyGen - The best AI video generation platform for your team.
76 Traders Insight - Decode the latest technical analysis ideas for stocks and bitcoin from top traders.
77 Figlet - Utility for converting strings of text into ASCII fonts.
78 Scholarly - Scholarly is an AI-powered search engine for exploring scientific literature.
79 TalentOrg - Find and hire freelance engineering talents from around the world.
80 Uniket - Elevate your shopping experience with Uniket.
81 Urban New Apartments - Search the best off-the-plan and new apartments from Australia’s leading property developers.
82 Peel Hunt AI-ERA - AI Equity Research Assistant (AI-ERA).
83 Kakaku.com/travel - You can search for hotel that match your search criteria from among the many hotels registered on Kakaku.com.
84 Social Media Muse - Get soundtrack and hashtag recommendations from a picture!
85 APEX Map - Checking the current APEX Legends Ranked Map.
86 SimplyCodes - Find reliable coupon codes at 300K+ stores.
87 PartSecure - Search & compare electronic component inventory, pricing, & lead time from top suppliers.
88 Sembot - Manage your Search Engine Marketing. Get keywords reports, CPCs, domain visibility, SEO results and more.
89 HiCollectors Finder - Search and price comparison for eBay products. Only available in the United States.
90 MixerBox ChatPDF - Save time! MixerBox ChatPDF can summarize & analyze PDF files for you!
91 MixerBox ChatMap - Powered by Google Maps API, MixerBox ChatMap is the world's 1st AI chatbot for Maps!
92 Whois Domain Checker - A Whois app that takes a list of space-separated domain names, performs the Whois for each domain.
93 PortfolioMeta - Analyze stocks and get comprehensive real-time investment data and analytics.
94 GIF Search - Search through a wide range of gifs - Powered by Giphy.
95 Your AI Council - The AI council assesses queries through various agents, offering insights from many perspectives.
96 Gift Finder - Your personal gift advisor. Find a perfect experience for anyone.
97 Quiver Quantitative - Access data on congressional stock trading, lobbying, insider trading, and proposed legislation.
98 Create a QR code - Create a QR code for any text or url.
99 GoFynd - Elevate your shopping experience with GoFynd.
100 Lsong AI - Lsong's AI provides AI-powered content like news, images, music, movies, weather, stories, memes, and more.
101 AI Agents - Unleashing the power of multiple AIs: One goal, limitless productivity.
102 PPC - StoreYa.com - Your personal assistance for automating advertising – Google Ads (AdWords) and Microsoft Ads (Bing).
103 Meme Generator - Your AI meme generator.
104 WP Interact - Fetch or search posts from self-hosted WordPress websites, opening new possibilities for smart interaction with content.
105 Prompt Perfect - Type 'perfect' to craft the perfect prompt, every time.
106 Man of Many - Discover the latest in products, culture and style from Man of Many. Ask for the latest news and headlines.
107 Scholar Assist - Search academic research papers from arXiv and find answers to your questions.
108 TopHap - Enriched real estate data and location-based tools.
109 WordCloud - Create word cloud images from text.
110 Brandfetch - Retrieve company and brand data including logos, colors, fonts, and other brand information.
111 Supercharge My EV - Find superchargers for non-Tesla vehicles for a specific location.
112 Italy Latest News - Get the most recent news from Italy.
113 Pluginpedia - Recommend plugins in the store based on your question, and introduce their usage.
114 TimeMachine - Enhances AI with real-time awareness, providing current time in various formats and timezones.
115 shownotes - Turns long podcasts into quick summaries, finds specific info, highlights key points, and suggests new episodes.
116 CLINQ - Manage your CLINQ Account. Retrieve infos about calls, create call reminders and more.
117 SmartTicketsAI - Get Tickets For All Sports Events, Music Concerts, Theater And More With SmartTicketsAI.com.
118 TechPulse - Get top/new/ask/show/job stories from HackerNews.
119 Upskillr - Custom curriculum, lesson plans, and upskilling support on any topic by Upskillr. Powered by Shorthills Tech.
120 QEEQ - Our mission is to make journeys more enjoyable and bring better travel experiences to QEEQ with the help of technology.
121 MixerBox Weather - Get real-time worldwide weather updates & forecasts, instantly!
122 Stories - Create beautiful, illustrated stories easily.
123 Litmaps - Get help exploring the scientific literature. Find relevant papers and generate mindmaps of the literature.
124 Got2Go - Your next vacation is one conversation away. Literally. Find the perfect stays in the US with Got2Go.
125 AskYourCode - Ask your source code directly. The intelligent rubber ducky!
126 Exchange Rates - Exchange Rates delivers real-time and historical data, enabling conversion and tracking for over 170 currencies.
127 sic - Your gateway to crypto. Explore prices, accounts, and transactions on blockchains, starting with Ethereum.
128 ChatWithGit - Search code on GitHub repositories based on a query.
129 PaperChat - Search through arXiv publications.
130 Domains Bot - Checks for a domain name's availability. You can search for your desired domain name.
131 Word Counter - Count the number of words, and characters (with and without spaces).
132 Mallorca Magic Property Search - Discover your dream property in Mallorca with our AI-Power. Find the perfect match from over 75,000 listings!
133 Scraper - Scrape content from webpages by providing a URL.
134 Bookworm - AI-powered personalized book recommendations, scanning countless titles to find your perfect read.
135 Finna Bolag - Seamlessly search for and retrieve Swedish companies' financial data.
136 Comparison - An advanced e-commerce tool, providing robust capabilities for efficient product search and accurate price comparison.
137 MixerBox WebSearchG - Search and summarize the web with our customized search engine powered by Google Search API!
138 Placid.app - A design assistant that creates marketing visuals from your templates.
139 Universal - Enables to access web pages, analyze PDFs, generate QR codes, etc.
140 GetYourGuide - Find tours, excursions and other travel activities.
141 WhizList - Your go-to for creating amazing Spotify playlists.
142 Substack IQ - Search, analyze, & summarize Substack newsletters, retrieve articles, and discover new Substacks!
143 Gift ideas suggester - Generate gift ideas for any occasion, such as birthdays, Mother's Day, etc. Please, provide details about recipient.
144 Clinical Trial Radar - Discover current info on global clinical trials, organizations, diseases, and biomarkers from public & private studies.
145 ChampDex - Chat with your favorite League of Legends champions!
146 Trending Music - Service for finding the trending music, by genre, countries, and top songs globally.
147 Job Search UK - Get the latest job posts from the UK's top job boards including Reed, Indeed, and others.
148 QR Generator - Generate QR code in seconds.
149 What To Watch - Search for current shows, get recommendations, and find out where things are streaming.
150 CharitySense - Get data on US-based non-profits including mission, key people, governance, ratings and financial data.
151 Hadith Advice - Ask a question and get advice from hadith.
152 NFTs - Get the important details of any NFT collection and ask for insights based on that data!
153 HDB Car Park - For checking availability of car park lots at various HDB car parks around Singapore.
154 Mobula - Fetching real-time data for all crypto & blockchain metrics.
155 Companies In The UK - Provides financial information on UK Companies.
156 CarYardBard - AI-Powered Car Sales Ad Generator for Australian Car Dealers.
157 ScholarlyInsight - Query research papers from Arxiv.
158 Chat With Workspace - Chat with your Notion workspace.
159 Jobsearch - This is a job search service. For now only for jobs in Germany.
160 Rogo - Answers questions about open-source repositories.
161 Reflect Notes - Creates a Reflect note.
162 Strology - Get daily astrological predictions for your sun sign.
163 Meme Creator - Use Meme Creator to create memes on demand using the power of AI!
164 Earth - Generates a map image based on provided location, tilt and style.
165 LIFULL HOME'S - Encounter the life you want. Search listings, view property and neighborhood details in Japan.
166 Coupons by Tenere - TenereTeam.com - Get the Best Deals & Coupons on Millions of Products At Over 50,000 Online Stores.
167 Shop AIssistant - A shopping assistant helping with the search through a large product catalog.
168 Klook - From local escapes to far flung adventures, find the best experiences, tours, hotels and transport options anywhere.
169 Boolio Invest - The easiest way to analyze global stock values with the power of quantitative factor methodologies.
170 Video Summary - Summarize YouTube video highlights. Generate summaries from YouTube video URLs.
171 Sakenowa - Find Sake and get detailed information in various ways.
172 ArtCollection - Search through millions of art pieces from The Metropolitan Museum of Art.
173 Dover Assistant - Generate a personalized email to someone you're interested in reaching out to for a job opportunity.
174 PDF Exporter - Export any chat response into a stylized PDF document.
175 QuickRecall - Create flashcards and review them with spaced repeition.
176 Ask MFM - Ask the hosts of the My First Million questions about business, tech, entrepreneurship, and life.
177 Sentence Beasts - Summon or create unique word monsters, engage them in thrilling battles, and record the outcomes using Word Monsters.
178 ChatWithVideo - Ask questions, analyzing, and parsing through YouTube videos by simply providing a YouTube video URL.
179 Mantium - Fetches user-created applications from Mantium and retrieves relevant info based on user queries.
180 Weather - Provides weather forecast based on location. Includes temperature, precipitation, cloud cover, wind and much more.
181 Puzzle Constructor - A tool for creating crosswords. You can create crosswords from words and hints.
182 Free Kiddie Books - Access thousands of free children's picture books (storybee.space). Get recommendations for young readers' interests.
183 Aus Surf Report - Get today's surf report for any break throughout Australia!
184 Planfit - Get your tailored workout plan and instructions with videos - AI-powered Workout Coach, Planfit.
185 Questmate Forms - Create forms, checklists and workflows (we call 'em Quests!) that you can assign, schedule or make public.
186 Bitcoin Sentiment - Track the current price of Bitcoin and the market sentiment based on the last 20 news media mentions!
187 Aus Petrol Prices - Ask for the average daily petrol price for any state or capital city region in Australia!
188 SA Speed Cameras - See if a mobile speed camera or roadwork is on a South Australian road today!
189 ImageSearch - Discover complimentary images to enhance your generated article or to highlight specific paragraphs from Unsplash.
190 Mindart - Career test to help you find your dream job, with automation risk and average salary.
191 AmazingTalker - Elevate your language learning at any level with personalized 1-on-1 online lessons from tutors across the world.
192 ndricks Sports - Get information about pro teams (NHL, NBA, NFL, MLB) teams by calling the ndricks Software Sports API.
193 HTTP Webhooks - Allows you to write, deploy, and manage HTTP Webhooks in JavaScript, right from the chat.
194 ChatWithWebsite - Have a conversation with any website, powered by magicform.ai
195 Easy Resume - Quickly create and edit your resume with the option to download as a docx or pdf, and find the job you deserve!
196 Outschool - Search for top-quality online classes and teachers on Outschool.
197 Ai Tool Hunt - Explore the ideal AI solutions for all use cases, drawn from the most comprehensive global database of AI tools.
198 Wordpress Publisher - Publish content directly to a Wordpress blog.
199 Lark Base Importer - Importing data into Lark Base for further analysis and presentation. An easy-to-use data management solution.
200 NFT News Roundup - Get Today's NFT News Headlines As A Clickable Link Roundup!
201 Website Performance - Measure key metrics about your website - performance, accessibility, best practices, SEO, PWA.
202 SEO Assistant - The SEO Assistant can generate search engine keyword information in order to aid the creation of content.
203 Able Style Fashion - Able Style is a fashion assistant who will help you answer the question, 'What shall I wear today?'
204 Tailor ERP Generator - A tool to help creating tailor-made ERP application.
205 FundsDB - Discover funding opportunities in UK and India on FundsDB. Type in your query in any language or /help for assistance.
206 TickTick - TickTick for managing a TODO list, you can add, remove and view your TODOs.
207 HackTrack - This tool checks if credentials linked to an email have been exposed in data breaches or hacks.
208 Crypto Jobs List - Find jobs and talent profiles in Crypto, Blockchain and Web3 industries.
209 Currency Converter - Convert currencies based on real-time rates.
210 daigr.am - Build charts, graphs, and more.
211 ISS Location - Add-on for displaying the current coordinates of the ISS and the names of the current astronauts in space.
212 Dart - Project management on autopilot.
213 Easy Product Search - Easy Product Search simplifies shopping on Japanese EC sites using keywords. It providing product info.
214 JiggyBase - Use the knowledge in your JiggyBase document collections to help produce factual, up-to-date chat responses.
215 Abridged Due Diligence - Discover the details! Search through recent SEC filings, with links to deeper analysis.
216 Agones - Agones provides soccer (football) results for matches played all over the world in the past 15 years.
217 JoPilot - Search for US jobs by keywords, locations, employers, salaries, and commute time.
218 CT Criteria Parser - Analyze eligibility criteria in ClinicalTrials.gov. Example input: nctid NCT05859269
219 Web Requests - Goodbye Knowledge Cutoff, Hello World! This is your AI assistant's web browser. Just enter a URL. Google, Wiki, GitHub.
220 Travelmyth - Unleash personalized hotel search with Travelmyth, offering 60 unique categories for the perfect match.
221 LawyerPR - Matching your ideal lawyer, in Japan. Let's Start with a Preliminary Review.
222 ChatSpot - Get access to marketing/sales data including domain information, company research and search keyword research.
223 UK Latest News - Get the latest news stories from the UK's top news outlets including BBC News, Sky News, The Independent, and others.
224 GameSight - Discover games, game-related content, get recommendations, and compare games based on player reviews.
225 B12 AI Websites - Create a professional, engaging, and user-friendly website for your business in seconds using AI.
226 Xpapers - Effortlessly find real academic papers on arXiv. Dive into abstracts, references, and access public PDF URLs.
227 QuakePH - Stay updated with the latest earthquakes in the Philippines.
228 Asset Ovi - Search and preview millions of 3D assets for games, AIGC, AR/VR and others.
229 Paxi AI - Let AI tools speed up your tasks! Make it easy to find the right tool for the task.
230 Korea subway route - Korea metro subway route info.
231 RoboAd - Your AI powered Ad Assistant!
232 Bibliography Crossref - Search publications and generate bibtex bibliographies using Crossref and Zotero.
233 Keyword Explorer - Keyword Explorer provides popular related keywords to amplify your content optimization.
234 ML Paper Reader - Search for ML papers on different topics and speed up research by "talking" to the PDFs.
235 3 Sentence Service - Managing a three sentence service. You can add, remove, view and invoke your 3 sentence services.
236 BuyWisely - Compare Prices & Discover the Latest Offers from thousands of online shops in Australia.
237 NextPaper.ai - Fetch the latest research papers on a specific topic from PubMed. More to come.
238 Statis Fund Finance - Financial data tool for analyzing equities. You can get price quotes, analyze moving averages, RSI, and more.
239 Bardeen - Create and run automations on the most popular web services.
240 Penrose Analyst - Search global news and research papers. Summarize Arxiv.org links. Ask me for the latest news!
241 Podcast search - This tool explores podcasts from PodcastIndex.org, a platform for decentralized audio content discovery.
242 UK Politics - Search through UK political documents such as speeches, press releases, voting records, and candidates' profiles.
243 ABC Music Notation - Converts ABC music notation to WAV, MIDI, and PostScript files.
244 Creatuity Stores - We integrate stores so you can search for products in all of them at the same time.
245 I Am Rich - Proudly declare 'I am rich'.
246 There's An AI For That - Find the right AI tools for any use case, from the world's largest database of AI tools.
247 Tic Tac Toe - Playing a game of Tic Tac Toe with varying board sizes. You can submit your move and get the AI's response move.
248 PortfoliosLab - Stocks, ETFs, funds, crypto analysis: historical performance, volatility, risk metrics, Sharpe ratio, drawdowns, etc.
249 DAIZY - Deep insights on ETFs, stocks, cryptos. Institutional-grade data: performance, risk, sustainability, research.
250 WikiDocs - You can search for books on Wikidocs and create books.
251 Creature Generator - Creates a random creature and an image it for use in role playing games.
252 highPerplexity - Integrates with highPerplexity and executes any prompts you need.
253 CCData.io - Access the latest crypto prices and news aggregated by CCData.io (formerly CryptoCompare.com).
254 Calorie Chat - Tracking what you eat doesn't have to be hard. With Calorie Chat, you'll find calorie counting simpler than ever before.
255 DeployScript - DeployScript effortlessly launches web apps, handling the tech for you. Watch your ideas come to life!
256 Horoscopes - Daily, weekly, and monthly horoscopes tailored to you. Brought to you by Inner Self.
257 Jini - Get factual, knowledge-base and real-time information. Search news, images, videos, music, apps, pages and facts.
258 World News - Summarize news headlines. You can ask for the latest news from various sources around the world.
259 CranePumps Manuals - Returns the catalog and manual for a pump based on model number.
260 CoinCap - Get cryptocurrency information from CoinCap.
261 HaffPrice - Shopping all kinds of products with the lowest price in the market.
262 ThemeParkHipster - Find theme park waiting times around the world.
263 WeatherWhiz - WeatherWhiz: Accurate current weather and forecasts for any location.
264 Zumper Rentals - Meet Zumper, your key to effortless apartment and house rentals in the US and Canada!
265 Scraper - Scrape content from webpages by providing a URL.
266 Job search by Indeed - Explore & discover the latest open jobs from the #1 job site in the world, Indeed.com.
267 Stepstone Jobs - Explore job openings in Germany. 120,000+ opportunities to discover.
268 Options Pro - Options Pro is your personal options trading assistant to help you navigate market conditions.
269 GameBase - Chat and get game info, database is based on the latest gaming information in 2023, supports multiple platforms.
270 VoxScript - Enables searching of YouTube transcripts, financial data sources, and Google Search results, and more!
271 Wahi - Hey Ontario, ask and get so in the know on the latest listings, property insights and more.
272 Giga Tutor - Giga is your AI powered personalised tutor, it keeps the answers to your questions personalised.
273 Shop Best - Shop and get summarized reviews for the best products on Amazon.
274 OwlJourney - Provides lodging and activity suggestions, ensuring an engaging and user-friendly journey.
275 Top Agencies - Find top marketing and design agencies around the World by service, locations, and ratings.
276 Email by Nylas - Connect with any email provider and engage with your email data seamlessly.
277 CreditYelp - Access various essential financial calculators for a detailed repayment schedule and payoff term.
278 Sudoku - This is a sudoku game. You use voice or text to play.
279 Tomorrow.io Weather - Predicting, planning, and adapting to the weather forecast via contextualized chat-based insights.
280 AskYourPDF - Unlock the power of your PDFs!, dive into your documents, find answers, and bring information to your fingertips.
281 Weather Report - Current weather data for cities and airports using METAR aviation feeds.
282 Xweather - XWeather gives weather information for a location. Ask for the current weather, a 5-day forecast, or a radar image.
283 Access Link - Access any links on the web and get the information you need.
284 PlaylistAI - Create Spotify playlists for any prompt.
285 Noteable - Create notebooks in Python, SQL, and Markdown to explore data, visualize, and share notebooks with everyone.
286 Bramework - Boost SEO with in-depth analysis, including keyword insights on volume, ranking, and SERP.
287 MixerBox News - Get latest news delivered right to you! Stay informed with bulletins across multiple categories from credible sources.
288 Vivian Health - Take the first step to finding your next healthcare job.
289 SEO.app - Your personal SEO assistant for content marketing.
290 Yabble - Create insights instantly. Any audience. Any question. Yabble it.
291 Polygon - Market data, news, and fundamentals for stocks, options, forex, and crypto from Polygon.io.
292 Kyujinbox - Searching jobs in Japan. You can search jobs by keyword, location and employ type.
293 ChatWithPDF - Chat with everything from entire PDF books to Google Drive documents just by providing a link.
294 Photorealistic - Generate Photorealistic prompts for Midjourney.
295 Crypto ERC20 Scout - Browse ERC20 tokens on EVM blockchains. Includes address resolution, symbol/tag search, explorer links, and pricing.
296 TradingBro - Get financial data for your trading/learning: earning call, analyst view, DCF, sales details, insider trading etc.
297 Smarter Contracts - Analyze smart contracts and tokens on Ethereum.
298 Show Me - Create and edit diagrams directly in chat.
299 Turo - Search for the perfect Turo vehicle for your next trip.
300 Open Lecture - Discover and access the right moments in open course lectures for targeted learning.
301 Crypto Market News - It's your go-to solution for real-time cryptocurrency price updates, market insights, and the latest news.
302 edX - Find courses and content from leading universities to expand your knowledge at any level.
303 Change - Discover impactful nonprofits to support in your community and beyond.
304 Metaphor - Access the internet's highest quality content. Recommended by people, powered by neural search.
305 Local by GoodCall - Discover and support restaurants, shops & services near you. 🍽️ 🛍️ 🔧
306 Dr. Thoth's Tarot - Tarot card novelty entertainment & analysis, by Mnemosyne Labs.
307 Cloudflare Radar - Get real-time insights into Internet traffic patterns and threats as seen by Cloudflare.
308 WebPilot - Browse & QA Webpage/PDF/Data. Generate articles, from one or more URLs.
309 Shuto.IO - Shuto.IO is a multi-tool for creators and developers with SMS, Email, Wordpress and SSH Command Execution capabilities.
310 Polarr - Search Polarr's massive pool of user generated filters to make your photos and videos perfect.
311 DEV Community - Recommending posts and members from DEV Community.
312 Decision Journal - Become a better decision maker by keeping track of your decisions and reviewing how they turn out.
313 Rentable Apartments - Get apartment options in a city of your choice, scoped to your needs and budget.
314 Public - Get real-time and historical market data, including asset prices, news, research, and comprehensive financial analysis.
315 Kakaku.com - Search for products that match your criteria from among the many products registered on the Japanese website Kakaku.com.
316 Link Reader - Reads the content of all kinds of links, like webpage, PDF, PPT, image, Word & other docs.
317 Visla - Create a short video from public stock footage based on your specified topic.
318 Coupert - Search for the internet’s best coupons from thousands of online stores.
319 Wishbucket - Unified product search across all Korean platforms and brands.
320 Yay! Forms - Allows you to create AI-Powered Forms, Surveys, Quizzes, or Questionnaires on Yay! Forms.
321 AutoInfra1 - Talk to your Servers. Works with AWS, GCP, Azure, and anywhere you can ssh!
322 Glowing - Schedule and send daily SMS messages - reminders, inspiration, helpers and more.
323 ChatSSHPlug - Ability to SSH into your server and turn your natural language into server commands.
324 txyz.ai - Effortlessly decipher, compare, and answer questions about research papers using a simple Arxiv ID.
325 ABCmouse - Provides fun and educational learning activities for children 2-8 years old.
326 Hubbub - Local health risk & safety guidance for COVID-19, Flu, RSV and more in the US.
327 One Word Domains - Check the availability of a domain and compare prices across different registrars.
328 C3 Glide - Get live aviation data for pilots. Ask questions about METARs, TAFs, NOTAMs for flight planning.
329 Likewise - Your media and entertainment companion. Get TV, Movies, Books & Podcast Recommendations.
330 Zillow - Your real estate assistant is here! Search listings, view property details, and get home with Zillow.
331 ScholarAI - Unleash scientific research: search 40M+ peer-reviewed papers, explore scientific PDFs, and save to reference managers.
332 Clearbit - Access Clearbit Enrichment, Prospecting, Reveal APIs and website visitors data to access information about companies.
333 Definitive Facts - Ask questions using 100+ relational datasets - sports, finance, and more at https://definitive.io/datasets.
334 AITickerChat - Retrieve USA stock insights from SEC filings as well as Earnings Call Transcripts.
335 Trip.com - Discover the ultimate travel companion - simplify your flight and hotel bookings. Enjoy your effortless trip!
336 Savvy Trader AI - Realtime stock, crypto and other investment data.
337 Golden - Get current factual data on companies from the Golden knowledge graph.
338 Lexi Shopper - Get product recommendations from your local Amazon store.
339 Acquire.com - Everything you need to buy and sell startups.
340 Keyplays Live Soccer - Latest live soccer standings, results, commentary, tv stations, keyplays (with and without scores).
341 BART Real-Time - Getting real-time BART information for a specified origination station and direction.
342 Chat with Code - Interact with code repositories, manage issues, and push code.
343 Chess - Unleash your inner chess master with this interactive chess experience! You can play against a novice or a grandmaster!
344 BlockAtlas - Search the US Census! Find data sets, ask questions, and visualize.
345 Uberchord - Find guitar chord diagrams by specifying the chord name.
346 Open Trivia - Get trivia questions from various categories and difficulty levels.
347 Indoor Plants - Trusted Information About Indoor Plants and Gardening.
348 KeyMate.AI Search - Search&Browse the web by using Google Search results with KeyMate.AI, your AI-powered web crawler.
349 BuildBetter - Chat with the knowledge of all your calls in BuildBetter (Zoom, GMeet, Webex). Start for free @ BuildBetter.ai
350 Domatron Domains - Find available, brandable .com domain names for your business businesses.
351 PortfolioPilot - Your AI investing guide: portfolio assessment, recommendations, answers to all finance questions.
352 Crafty Clues - Guess the words that the AI craftily clues for you. Add restrictions to make the game more interesting!
353 Word Sneak - The AI has to sneak 3 secret words into your conversation. Guess the words to win the game!
354 Redfin - Have questions about the housing market? Find the answers to help you win in today's market.
355 Kraftful - Your product development coach. Ask about best practices. Get top gurus’ product thinking.
356 Bohita - Create apparel with any image you can describe! Get it delivered right to your door.
357 Astrodaily - Search and discover NASA images.
358 Calorie Coach - Track meals & gain insights for a healthier lifestyle from 1m+ restaurants & grocery stores.
359 Competitor PPC Ads - Discover your competitors' best PPC ads by entering their website address.
360 Ambition - Search millions of jobs near you.
361 Manorlead - Get a list of listings for rent or sale in cities across Canada and the US based on your search criteria.
362 SEO CORE AI - Use AI to analyze and improve the SEO of a website. Get advice on websites, keywords and competitors.
363 KalendarAI - KalendarAI sales agents generate revenue with potential customers from 200+ million companies globally.
364 Appy Pie App Builder - AI-powered Text-to-App Generator turns your app idea into Android and iOS apps- just provide text input.
365 Algorithma - Shape your virtual life with in this immersive life simulator game to begin Type /start to begin.
366 CreatiCode Scratch - Display Scratch programs as images and write 2D/3D programs using CreatiCode Scratch extensions.
367 Video Insights - Interact with online video platforms like Youtube or Daily Motion.
368 Tasty Recipes - Discover recipe ideas, meal plans and cooking tips from Tasty's millions of users!
369 MixerBox OnePlayer - Unlimited music, podcasts, and videos across various genres. Enjoy endless listening with our rich playlists!
370 Tabelog - Allows you to find restaurants in Japan that have availability for reservations.
371 Speechki - The easiest way to convert texts to ready-to-use audio — download link, audio player page, or embed!
372 Tax Calculator - Calculate sales tax given a U.S. address (or just a city) and an amount. Powered by Avalara.
373 Magnetis - Magnetis is a digital wealth manager. Get updated data on portfolios returns and allocations. Ask me about Magnetis.
374 AI2sql - Converts a natural language text into an SQL query.
375 Hauling Buddies - Locate dependable animal transporters using recommendations, reviews, and regulatory compliance search features.
376 SceneXplain - SceneXplain lets you attach images to your prompt. Explore image storytelling beyond pixels.
377 Giftwrap - Ask about gift ideas for any occasion and recipient. Get it wrapped and delivered, no address needed.
378 BizToc - Search BizToc for business & finance news.
379 MixerBox FreecableTV - Watch free ad-supported TV shows, series, live channels, movies, news & sports from across the web!
380 Netlify Drop - Describe a simple website you want to make, and deploy it to Netlify to share it with others and claim it as your own.
381 Speak - Learn how to say anything in another language with Speak, your AI-powered language tutor.
382 OpenTable - Allows you to search for restaurants available for booking dining experiences
383 Shop - Search for millions of products from the world's greatest brands.
384 FiscalNote - FiscalNote enables access to select market-leading, real-time data sets for legal, political, and regulatory information
385 Wolfram - Access computation, math, curated knowledge & real-time data through Wolfram|Alpha and Wolfram Language.
386 Zapier - Interact with over 5,000+ apps like Google Sheets, Gmail, HubSpot, Salesforce, and thousands more.
387 Expedia - Bring your trip plans to life – get there, stay there, find things to see and do.
388 Instacart - What’s cookin'? Ask about recipes, meal plans, & more -- and get ingredients delivered from 40,000+ stores!
389 Klarna Shopping - Search and compare prices from thousands of online shops. Only available in the US.
390 KAYAK - Search flights, stays & rental cars or get recommendations where you can go on your budget.
