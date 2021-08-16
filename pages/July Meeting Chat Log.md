tags:: #chatlog

- 00:31:23	Bruno Winck:	do we have an agenda?
  00:32:31	Boris Mann:	@Bruno —> https://lu.ma/tfti-july
  00:32:32	Jess Martin:	9am - Linus Lee, 9:30am - Kevin Lin (Dendron), 10am - Rafael Nepo (mee.cc)
  00:33:06	Jess Martin:	(based on timing we'll probably run ~10 minutes long)
  00:36:37	Boris Mann:	https://thesephist.com/posts/inc/
  00:37:26	Joe Trellick:	Yeah, time is one of the most fundamental memory concepts! I don't feel like many tools make as much of that as they could
  00:38:33	Boris Mann:	It’s interesting to me where people are definitely highlighting “offline compatible” as a needed feature
  00:38:41	Jess Martin:	Trellick - agree! I started working on an OS oriented around a timeline rather than a filesystem and the experience was really thought-provoking
  00:38:54	Boris Mann:	Append == immutable / versioning
  00:39:09	Steven Ritchie (he/him):	Agreed, the only value I’ve ever found from Roam-like tools is the daily note paradigm, nothing else really stuck for me.
  00:39:55	Boris Mann:	The plugin / query / template I need to work on is “On This Day” features — to surface old notes / blogs / etc
  00:40:37	Jess Martin:	@SR: same. it's the paradigm I use for all my notes. one exception: topical notes I link to from my "daily notes". but it's a clunky interface from time-bound to topical. research needed here.
  00:41:10	Bruno Winck:	Lol I've been using cinremental note-taking for 15 years without knowing :)
  00:42:31	Jess Martin:	live demos👏👏👏
  00:42:53	Boris Mann:	Like Karlicoss’ Promnesia https://fission.codes/blog/human-programming-interface-by-karlicoss/
  00:43:26	Matt Gauger:	(I use karlicoss's grasp for links->orgmode. I need to check out Promnesia)
  00:43:33	Boris Mann:	https://github.com/karlicoss/promnesia
  00:44:10	Boris Mann:	Linked blog post I have a couple of things in there and tried it myself by “just” indexing the published web version of my website — pretty good start
  00:45:12	Jess Martin:	re: real-time feedback, my fav feature of my note-taking system is the live autocomplete across my notes when I type [[. But that's just titles! Would love a full index.
  00:45:13	Bruno Winck:	what about alias?
  00:49:11	Boris Mann:	Makes me think about how to share personal search engines — there are a couple of these projects floating around, aggregating blogs / digital gardens
  00:49:50	Joe Trellick:	Oh neat, I was thinking about lifecamming my entire screen the other day, I'll have to look at APSE
  00:49:52	Boris Mann:	See https://github.com/cblgh/lieu
  00:50:21	Boris Mann:	Mostly for Mastodon Merveilles.town
  00:50:26	Joe Trellick:	APSE = https://apse.io/
  00:50:28	Tani Olhanoski:	@boris we’ve been hacking on that idea. i’ve always hated publishing but would be fine with people searching my garden notes to access my information
  00:50:48	Boris Mann:	Also Agora, of course, that has my garden in it —> https://anagora.org
  00:50:55	Boris Mann:	@tani — yeah, totally cool!
  00:51:07	Boris Mann:	So more relevant to get “recommendations” from people where you have some trust already
  00:51:54	Tani Olhanoski:	yep! also very relevant for marketing. broadcast isn’t actually the most effective way to reach people: https://www.asc.upenn.edu/news-events/news/study-finds-surprising-source-social-influence
  00:52:03	Joshua Fontany:	Well presented
  00:52:44	Gyuri Lajos:	Linus you said something like "Highlight first rather than graph first"
  00:52:59	Gyuri Lajos:	need an image too
  00:53:01	Jared Pereira:	Perhaps a personal search engine could be a standardizing force for the tools-for-thought web in the same way that google is for the web web
  00:53:16	Boris Mann:	https://av.tib.eu/media/46574
  00:53:18	Jess Martin:	Jared: that's super interesting
  00:53:18	Tani Olhanoski:	https://mymind.com/ has a pretty powerful image search, i’ve been surprised how good it is at matching words to the content of images
  00:54:01	Rafael Nepô:	It’s creepy good Tani
  00:54:32	Joe Trellick:	Yes @Jared, a popular enough "consumer"/"renderer" tool could incentivize APIs for integration
  00:56:42	Boris Mann:	Oh right, here’s the actual memex article https://hyfen.net/memex/
  00:57:23	Jess Martin:	also good to note that Linus has written over 400k. His writing is his curation, IMO.
  00:57:38	Jess Martin:	he has a pretty solid discipline for writing new material, in which he synthesizes
  00:58:47	Jess Martin:	(y'all should subscribe to his newsletter: https://thesephist.com/)
  00:58:52	Jess Martin:	Gyuri: did you have a question?
  00:59:38	Jess Martin:	Writers tend to think in terms of "writing" and "editing" as two different workflows
  00:59:43	Jess Martin:	for example
  01:00:04	Matt Gauger:	Should tools have modal UIs to match those different modes of thinking/working?
  01:00:50	Jess Martin:	John, I see ya - will get to ya next.
  01:01:43	Bruno Winck:	Logs are easy to organize
  01:01:54	Jess Martin:	easy to "browse" because ordering is forced and explicit
  01:01:57	Brian James Rubinton - Kanopi.io:	I think of time as 1 dimension, arguably the default one, in a knowledge graph. Associations through adjacent times are a useful indicator of relevance, just not the only one.
  01:02:20	Eric Burns:	Agreed!
  01:02:24	Brian James Rubinton - Kanopi.io:	Place is also important. All about context!
  01:02:57	Jess Martin:	BJR: Yes! I so want to be able to see my daily notes alongside the code I wrote at that time and the tweet I sent and the article I read. Highly related.
  01:03:12	Brian James Rubinton - Kanopi.io:	Linus made a good point regarding capturing > missing. Time makes it easy to attach quickly captured notes to a graph.
  01:04:25	Eric Burns:	I try to quickly capture ideas in an unorganized mess … then at some regular cadence, I go back through the notes and fit them into my organized "ontology".
  01:04:27	Jess Martin:	for personal tools, "many small tools" makes a lot of sense
  01:04:28	Brian James Rubinton - Kanopi.io:	@Jess: Exactly! That's how to re-enter a mental space.
  01:05:00	Bruno Winck:	@Eric, same, usually a day or two after
  01:05:20	Matt Gauger:	For you all commenting: Does anyone have a tool that assists in organize the quick capture notes? (Beyond the built in functionality of things like orgmode, etc.)
  01:05:44	Matt Gauger:	I've seen processes described in things like How to build a Second Brain but no software tools that help with it.
  01:05:49	Jess Martin:	Matt: do you mean organize after the fact?
  01:05:53	Boris Mann:	atJSON!
  01:06:33	Matt Gauger:	@Jess Martin: Yes, basically anything to help take unorganized notes -> some tool -> organized and "connected" in whatever way.
  01:06:35	Joshua Fontany:	TiddlyWiki's "Filter" language is very relevant here
  01:06:42	Eric Burns:	I'm using Dendron!  :)
  01:07:15	Boris Mann:	“Interchange” is our extremely broad phrase of talking about how we connect things together
  01:07:26	Brent Anderson:	Also a happy Dendron user
  01:07:42	Boris Mann:	Import, export, live connections between tools, formats etc.
  01:10:37	Tanner Seidman:	Cool! looks like org-mode + org-roam meets markdown and vs-code
  01:11:28	Jess Martin:	I wish people were doing as much work on visualizing timelines of notes as they are on visualizing knowledge graphs...
  01:11:47	Boris Mann:	https://timeline.knightlab.com/
  01:12:15	Boris Mann:	TimelineJS!
  01:12:31	Jess Martin:	noice!
  01:12:54	Matt Gauger:	Was going to say, writing timeline UI from scratch is a big pain there. Good to know there's a JS library for it.
  01:12:59	Boris Mann:	For media purposes, but some “out of the box” views
  01:13:45	Boris Mann:	Hardest problem is that my public and private are most valuable when intertwined.
  01:14:37	Jess Martin:	@BMann - precisely why I have so few of my ~700 notes on my public site... and the few notes that are there have deadlinks to private notes :-\
  01:16:10	Miguel:	Foam bubble is also based on vscode
  01:16:47	Jess Martin:	doesn't code have that structure because the languages themselves have syntactic limits?
  01:16:54	Boris Mann:	AST!
  01:16:58	Jess Martin:	whereas human languages have far more expressivity
  01:17:09	Tanner Seidman:	And they're far more messy
  01:17:14	Jess Martin:	precisely
  01:17:29	Gyuri Lajos:	everything is a remix
  01:17:34	Boris Mann:	AST == Abstract Syntax Tree https://en.wikipedia.org/wiki/Abstract_syntax_tree
  01:17:39	Jess Martin:	but even if seedbank just made it easier to reference and remix, that would be really awesome
  01:17:40	Boris Mann:	“Abstract syntax trees are data structures widely used in compilers to represent the structure of program code. An AST is usually the result of the syntax analysis phase of a compiler. It often serves as an intermediate representation of the program through several stages that the compiler requires, and has a strong impact on the final output of the compiler.”
  01:17:48	Joshua Fontany:	"bricolage"
  01:17:56	Boris Mann:	Can we parse notes into ASTs? That’s basically entity analysis
  01:17:59	Boris Mann:	"nouns"
  01:18:42	Linus Lee:	JSON is the new plain text
  01:18:43	Bruno Winck:	dependencies?
  01:19:05	Gyuri Lajos:	We need really Abstract Syntax Graphs!
  01:21:18	Tanner Seidman:	Transclusion! That's cool
  01:22:08	Tanner Seidman:	Someone is working on that for org-mode rn, https://github.com/nobiot/org-transclusion
  01:22:16	Boris Mann:	Like https://github.com/cheat/cheat
  01:22:25	Boris Mann:	“cheat allows you to create and view interactive cheatsheets on the command-line. It was designed to help remind *nix system administrators of options for commands that they use frequently, but not frequently enough to remember.”
  01:22:46	Brent Anderson:	Dendron Transclusion is solid.
  01:23:09	Brent Anderson:	I used Foam before Dendron, and it’s a great model. Agree that Timeline support would be very interesting.
  01:24:11	Brent Anderson:	“Open Knowledge Registry” - see also the GGG (Giant Global Graph) from Tim Berners-Lee.
  01:25:22	Jess Martin:	begs to be used for cooking recipes
  01:25:29	Jess Martin:	like, in a kitchen.
  01:25:48	Tanner Seidman:	The Dendron Cookbook could be a very confusing title
  01:26:48	Jess Martin:	a la Food for Thought 🤣
  01:27:13	Joshua Fontany:	Very cool system
  01:27:32	Miguel:	How will the business model be?
  01:28:40	Gyuri Lajos:	https://medium.com/@jessitron/symmathecist-n-c728957ce71f
  01:29:07	Gyuri Lajos:	https://hypothes.is/a/WfS0Vu7ZEeubs-8Vkwiv9Q
  01:29:25	Jess Martin:	the "map" of the knowledge
  01:29:40	Matt Gauger:	How many hours have we all spent in Lexus-Nexus? :laugh:
  01:30:07	Joe Trellick:	Another problem is sometimes even figuring out the right terms for the area you're interested in
  01:30:45	Gyuri Lajos:	You can try also to think for yourleves on a problem first. Your reading the literature will be way more valueable
  01:30:47	Jess Martin:	...or wikipedia
  01:32:07	Brent Anderson:	I see the Seed Bank’s primary future as being our ability to add connections. Its like the references section in academic papers: so much of the value of knowledge lies in the network connections between pieces of knowledge.
  01:32:40	Jess Martin:	public back links
  01:32:43	Brent Anderson:	So, if there’s a seed bank on particle physics, you can look at one of its pages and see backlinks from other published Dendron vaults.
  01:33:30	Joe Trellick:	One of the tricks is contextualizing connections (which research papers do well). Connections without sufficient context end up with the frustratingly spurious hits that you get on sites like alternativeto.net
  01:33:58	Brent Anderson:	I think contextualizing connections could be really interesting with a social graph layer on top.
  01:35:09	Brent Anderson:	If I follow Jess Martin, I should see his Backlinks. Maybe I can see people that he follows as well, or building lists of people to follow. Discovery of social circles would be a challenge as well, but the social component on top of the knowledge seems necessary.
  01:35:53	Jess Martin:	@Brent: I was thinking about Christopher Alexander's A Pattern Language as a seedbank that I could reference and build off of. I'd love to see who else is referencing the patterns as well!
  01:36:50	Brent Anderson:	@Jess - Bingo. What I’m getting at is options for filtering those references as this thing scales. But being able to see who’s talking about a topic is gold!
  01:39:33	Jess Martin:	@Brent: side note - one of my favorite uses of rdio was viewing albums and seeing other users who commented on the album and added the album to their playlists. Then I would browse those users libraries. my fav music discovery experience!
  01:39:54	Jess Martin:	similar idea- rdio was the canonical "vault" for all music albums
  01:40:33	John Lam (he/him):	I wonder how Seed Banks can be mapped to Wikipedia? Is it right for me to think about it as being a way to annotate / create derivative works from existing content from things like Wikipedia?
  01:40:51	Boris Mann:	I don’t think so. It’s new knowledge scope by user
  01:40:56	Brendan Langen:	++ @Jess. spotify missing a large opportunity around an individual's album canon.
  01:40:59	Brent Anderson:	Makes sense when you think about how often social + “knowledge” are layered together. Wikipedia has conversations, Twitter and Facebook as well.
  01:41:04	Boris Mann:	So if you like bmann/tips-for-zoom that might work for you
  01:41:23	Boris Mann:	Hence: reputation
  01:41:47	Bruno Winck:	also called SDL, self directed learning
  01:41:51	Brent Anderson:	@Boris - True you can scope by user, but ostensibly Wikipedia could be built on top of Git using Markdown/Dendron and it becomes part of the broader knowledge graph.
  01:42:32	Brent Anderson:	It would be wikemedia/wikipedia but I could build off of bmann/wikipedia if I preferred your fork ;)
  01:42:33	Boris Mann:	@BA — yes, but Wikipedia is explicitly not namespaces — editors curate canonical commons
  01:42:50	Boris Mann:	I’m thinking about Dendron up, not wikipedia down — which is a different thing than Wikipedia
  01:42:55	Jess Martin:	I love that photo
  01:43:03	Jared Pereira:	Wow yeah
  01:43:07	Jess Martin:	that wall 😍
  01:43:27	Boris Mann:	And, I think, different _kinds_ of info — my list of “top links for Zoom” is going to be biased by what I think, not what a group thinks is canonical
  01:43:37	Rosano:	gorgeous!
  01:43:41	Jess Martin:	physical spaces for containing ideas and presenting them ❤️
  01:45:08	John Lam (he/him):	I love this photo because it gives you space to immerse in the ideas contained within it. What I find frustrating about computers is the lack of real estate that I can see all at once. Sure there's a virtual infinite canvas, but I want to see connections (perhaps serendipitously) between things
  01:45:12	Jess Martin:	hmmm... infinite regress problem :)
  01:45:43	Jess Martin:	@John: totally agree - need. more. space.
  01:46:48	Jess Martin:	@John: I wrote about the infinite thinking canvas in an essay called "An Infinite Room for Thought": https://jessmart.in/articles/infinite-room
  01:47:31	Brent Anderson:	VR is promising in a way, but it’s not the same without a lot of work. Spatially exploring a space is very different than using a VR controller to change your point of view while sitting in a chair.
  01:47:34	John Lam (he/him):	cool! added to my notes to read :)
  01:48:09	Matt Gauger:	Lots of links from today going into the "to read" pile. Thanks all :D 
  01:48:23	Boris Mann:	Yes! This is also what I mean by “bias” — point of view is the other way to explain this
  01:48:29	Boris Mann:	Not necessarily a bad thing
  01:48:54	Tani Olhanoski:	we are leaning into bias as a good thing. but instead call them “lenses”
  01:49:13	Jess Martin:	@Tani: I love that re-framing
  01:49:17	Tani Olhanoski:	i want to see how someone else sees the world from their point of view because there’s so much more context there
  01:49:45	Eric Burns:	Knowledge Pinterest!
  01:50:00	Rosano:	@Tani what's that project?
  01:50:00	Eric Burns:	(Sorry, I can only understand things in relation to things I already understand)  ;)
  01:50:09	Boris Mann:	@Eric: Haha. That’s kind of MyMind, which was mentioned earlier
  01:50:32	Boris Mann:	@rosano! The fine people of Understory https://www.understory.coop/team
  01:50:43	John Lam (he/him):	I love the search demo and found it really relatable :) I like @Tani's comment about other people's context as well. I generate context from a bunch of tabs in short "microblog" things that I save in my notes. I would imagine that stuff is probably useful for others going down similar/related rabbit holes!
  01:50:45	Boris Mann:	#ZeroDataApp for the win :)
  01:50:49	Rosano:	thanks
  01:51:42	Tani Olhanoski:	@rosano i just got caught up on the zero data session you ran, we should catch up! we’re building on Solid but aiming to be interoperable by mapping to RDF
  01:53:12	Joshua Fontany:	Ha, flipping over the virtual 2d object for metadata. Thats pretty brilliant. 👏
  01:54:05	John Lam (he/him):	I would love a tool that would create something like Rafael's photo of his room as context for a conversation or something that I'm working on. "Computer - give me context for foo"
  01:54:07	Rosano:	@tani oh boy we got into that this morning with michiel de jong at the 0data swap, yes let's chat, maybe send a dm? http://twitter.com/@rosano
  01:54:19	Eric Burns:	Unfortunately, I need to run … but I'm glad to have met you all and hear what you're working on!
  01:54:23	Jess Martin:	We're now at the scheduled end time for the meeting. If anyone needs to drop off, feel free! Recording will be on YouTube. I'll give Rafael a few more minutes, and will also hang around for 10-15 minutes for Q&A afterwards. No need to leave if you don't have to go :)
  01:54:28	Jess Martin:	@Eric: thanks for coming!
  01:55:06	Brendan Langen:	quite beautiful work, @Rafael!
  01:55:35	Matt Gauger:	Yes, this has all been visually appealing
  01:55:41	Jared Pereira:	Hopping off, really exciting stuff everyone!
  01:55:58	Boris Mann:	We’ll email follow up links to everyone who signed up
  01:56:51	Jess Martin:	reminds me of museapp.com
  01:58:26	Jess Martin:	silky smooth UX
  01:59:06	Rosano:	gardening!
  01:59:20	Tanner Seidman:	digitally!
  01:59:21	Jess Martin:	👏
  02:00:23	Gyuri Lajos:	Is it local first or SaaS
  02:00:27	Boris Mann:	https://mee.cc/
  02:02:02	Jess Martin:	interop formats for visual formats would be... difficult
  02:02:08	Jess Martin:	of course, this is a 2d grid :)
  02:02:16	Jess Martin:	so, there's some rigidity
  02:02:36	John Lam (he/him):	Thank you everyone, this was a great conversation!
  02:02:55	Matt Gauger:	Thank you, need to run! :wave:
  02:03:17	Gyuri Lajos:	Structured XML?
  02:04:30	Jess Martin:	effectively want backlinks