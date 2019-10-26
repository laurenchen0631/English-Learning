# [Elephants Under Attack Have An Unlikely Ally: Artificial Intelligence](https://www.npr.org/2019/10/25/760487476/elephants-under-attack-have-an-unlikely-ally-artificial-intelligence)
- DINA TEMPLE-RASTON | October 25, 20196:00 AM ET
---------------------------------------------------------------------------------------------------------------------
A few years ago, Paul Allen, the co-founder of Microsoft, published the results of something called the Great Elephant Census, which counted all the savanna elephants in Africa. What it found *rocked* the conservation world: In the seven years between 2007 and 2014, Africa's savanna elephant population decreased by about a third and was *on track to* disappear completely from some African countries in as few as 10 years.

To reverse that trend, researchers landed on a technology that is rewriting the rules for everything from our household appliances to our cars: artificial intelligence. AI's ability to find patterns in enormous volumes of information is *demystifying* not just elephant behavior but human behavior — specifically poacher behavior — too.

"AI can process huge amounts of information to tell us where the elephants are, how many there are," said Cornell University researcher Peter Wrege. "And ideally tell us what they are doing."

There are two kinds of elephants in Africa: savanna elephants, which were counted by Allen's census, and forest elephants, which the census couldn't account for because that elephant lives beneath a thick rainforest canopy. Even at the level of the jungle, Wrege says, losing a forest elephant is easy to do. "Sometimes you see them, let's say, 15 meters [16 yards] away from you and then they move 5 meters into the forest and you can't see them," he said. "Somehow they just disappear."

Researchers at Cornell University have been studying the forest elephant for years, trying to figure out — like Allen did with the savanna elephant — how many there are and how fast they are being killed. Given how stealthy the forest elephants are, Wrege began to think that rather than look for them, maybe he should try something a little different: Maybe he should listen for them.

To do this, Wrege had 50 custom audio recorders made. He divided the rainforest into 25 square kilometer grids and headed to Central Africa. His team placed one recorder in every grid square about 23 to 30 feet up in the *treetops*, just a little higher than an elephant could reach with its trunk while standing on its hind legs. And then they hit record. Three months later, they would return to the forest, locate the recorders, change the batteries, put in new audio cards, and start all over again.

As the months wore on, the recorders were collecting hundreds of thousands of hours of jungle sounds, more than any team of graduate students could realistically listen to — which meant Wrege had another problem: How could he sort through all these recordings to find the elephant voices he wanted?

"In AI circles this is known as the 'cocktail party problem,' " said computer scientist Josephine Wolff, who is now a professor at the Fletcher School at Tufts University. "At a party with a lot of background noise, the human brain can focus on a specific person's voice and amplify that above all the other voices. AI can do the same thing."

In fact, there's a subset of AI — something called a neural network — that is very good at this. A neural network is essentially a group of algorithms, or mathematical equations, working together to cluster and classify information and find patterns humans wouldn't necessarily see. It is particularly good at working with images, so Wrege ran the audio through a software program that turned the recordings he had collected into *spectrograms* — *ghostly* little pictures of sound waves. He then had a company in Santa Cruz, Calif., called Conservation Metrics build him a neural network that could sort through the cacophony of jungle sounds and find elephants.

"Basically each of these 'neurons' in the network is determining how likely one piece of the spectrogram is to belong to an elephant call," Wolff explains. "Neurons in the first layer have just the spectrogram to consider, and so will likely recognize things like pitch and other things it sees as defining characteristics of elephant calls." Then the next neuron recognizes something else relatively simple, building on what has come before it, and so on.

When the network thinks it has what it needs, it makes a statistical calculation; essentially asking itself, what's the likelihood that the pattern I see is an elephant? 50%? 80%? Until it finally gets what it wants, that elephant. The neural network started producing files with lots and lots of isolated elephant sounds.

But then an interesting thing happened — Wrege and his team at the Elephant Listening Project heard something else they weren't expecting in all those recordings: gunshots.

Assuming the gunshots were a pretty good proxy for poaching attempts, Wrege decided to ask Conservation Metrics to build another neural network, this time to look for the sounds of gunshots. He hoped it would provide additional information about where the forest elephants were being killed and perhaps even stop poachers before they fired.

## A technology solution

Wrege wasn't alone in trying to find ways to *marry* cutting-edge technology with conservation and poaching prevention. Four years ago, a park manager named Craig Reid was navigating a slow-motion crisis at Liwonde National Park in *Malawi*. The wildlife reserve was on the verge of collapse: Infrastructure was crumbling, roads *were washed out*, people came in and out of the park to hunt, poaching was endemic, and elephants were *terrorizing* nearby villagers.

"I would describe Liwonde when we found it as being in a state of terminal decline," he told me during a recent visit to the park. "Effectively what would have happened had we not intervened would be a total elimination of all wildlife over the 10-year period following."

So Reid stole a page from big-city policing and decided to use artificial intelligence and predictive analytics to see whether it could help him manage the park. He thought technology could help him uncover the secret rhythms of the place, anticipate poaching, and create an environment where the animals could safely be animals.

"When we were *rugged* *rangers* in the bush down in South Africa we would talk about the day when we'd sit behind our desks and manage the park from behind a computer screen," Reid told me. "And that really is exactly what has happened."

*As fate would have it*, the resurrection of Liwonde was happening right around the time that Allen, who died in 2018, was wrapping up that Great Elephant Census. If Allen learned anything from that project it was that actionable information was the key to saving the elephant and better managing parks. So his company, Vulcan Inc., created EarthRanger: an analytics program *turbocharged* with artificial intelligence and predictive analytics.

"EarthRanger was entirely customer-driven, and when I say customers here, it's essentially the park rangers," said Pawan Nrisimha, the director of product management at Vulcan, which Allen founded to tackle a host of these kinds of problems. "They are the ones who said, 'OK, we are logging all our reports on paper. We need a technology solution.' And that's where we started."

The idea was to take all the information park managers like Reid had both in their heads and in their daily field reports and then make it smarter.

They started by creating a real-time visualization program that would allow managers to see all the park assets on one screen: rangers, animals, helicopters and information from sensors and security cameras were all brought together in one place, just a mouse click away. The second part was providing park managers with the analytics tools they needed to manage their patrols better.

"We have things like heat maps that tell about problem areas, where there are *snares* and animal traps happening, where there are fence breaks," said Nrisimha. "That allows them to respond to security problems in the park much more quickly." The program actually produces an animation that allows operators to run incidents back, like a real-life interactive video game.

Finally, there is an artificial intelligence component. "We are trying to see how we can build artificial intelligence or predictive analytics to proactively tell the park management how to do the patrols and manage the security effort better," Nrisimha said. The program ingests all the information and then essentially learns the rhythms of the park to offer suggestions for how to run it most efficiently.

At Liwonde, the EarthRanger program is housed in an innocuous-looking brick building behind the main ranger station. There are rangers in camouflage uniforms sitting at computer screens and manning the radios. It looks like the command center of a medium-size-city police department. There are flat screens on the wall, closed circuit television monitors, and two long tables with a series of computers analyzing and categorizing information coming into headquarters and running it through the EarthRanger program.

Lawrence Munro is the park's operations manager. A key part of his job is to plan, schedule and deploy ranger patrols. EarthRanger is helping him work out the best way to do that. To get an idea of what it looks like, the screens on the wall are showing a real-time satellite image of the park. There are little elephant icons tracking GPS location signals from *collared* elephants and little rhino icons that track the rare black rhinos kept in a special sanctuary deep inside the park.

Munro and the park's enforcement chief, Paul Chidyera, are moving back and forth between a whiteboard at the back of the room and the EarthRanger monitor at the front. They are focused on two specific datasets on the screen before them: the concentration of snares that have been found in the park in the past month and footprints that rangers recorded coming in and out of the park over the same period.

One of the rangers clicks a mouse, and EarthRanger moves through an animation of suspicious activity in the park over the last moon phase. The concentration of snares populates the screen: They look like little lassos and dot the area off a main road traversing the park. Munro points them out and thinks for a minute. "Let's set up a checkpoint there," Munro says, pointing to the intersection of two roads.

"The old system was a map on the wall," Munro said. "I still have it in my office and it's a similar type process but you wouldn't be able to see exactly where all your assets are," he said, referring to the men, planes, jeeps and helicopters he has at his disposal to police the park. "You have to rely a lot more on memory, a lot more radio traffic. Here, you can do a lot more preemptive stuff because you can see the picture."

Preemption is about anticipating where a poacher might appear, in the same way that police departments might beef up patrols in a high-crime area. While this is standard practice in policing, it really hasn't been a focus in conservation until relatively recently. Part of the issue is one of expanse — animals, particularly elephants, roam across great distances — and rangers can patrol only a small area at a time. That tension, researchers believe, may be resolved by analytics and AI.

In Liwonde, EarthRanger's analytics have helped Reid and his team find patterns in poaching behavior that they might have missed. It turns out that after chewing through two years of data, EarthRanger — not unlike Wrege's Elephant Listening Project — has helped *tease out* a number of factors that *at first blush* wouldn't have intuitively occurred to Reid's team as playing a role in the calculus of poaching.

Weather patterns and animal movements are things they have watched for some time, but they have also found that religious holidays and government paydays have a correlation with an uptick in criminal activity in the park. Why? Bush meat is considered a delicacy in Malawi, so it stands to reason that people will put in orders for the expensive meat right after they get paid and then hunters go into Liwonde to fill the orders.

"We pick up trends; we pick up patterns," Munro said. "It used to take a month to start to see these kinds of things emerge because everything was on paper. Now we study it *intently* every Wednesday because we want to deploy our guys accordingly. But you could do it daily. That's the difference. It's basically the speed at which you can strategize."

Just how well this is working came into stark relief earlier this year when Chidyera, the head of law enforcement at the park, got an unexpected alert on his phone. A sensor linked to EarthRanger had detected some suspicious movement in the eastern part of the park; so he and his team set up a poacher cam — a small, motion-activated camera with a special algorithm inside that helps the camera determine whether whatever is going past has a human shape or an animal one. A few days later, the camera snapped a picture of someone coming into the park and sent it to EarthRanger and Chidyera's cellphone with GPS coordinates.

The photo was good enough to allow Chidyera to go to a nearby village and identify the trespasser. It turned out he was a well-known poacher in the area. "When he was arrested and was confronted, he revealed all he [had] been doing," Chidyera said. Back at the park, rangers scrolled back through the EarthRanger database and found other pictures of the same man entering the park with weapons and snares. Those photographs were submitted as evidence at trial. "He was even wearing the same clothes in some of the photographs, so it was clear he was the same guy," Chidyera said. "He got 27 years as a repeat offender."

It is still early for assessing Vulcan's analytic solution for wildlife parks, but the numbers from Liwonde so far are encouraging. In the past two years, poaching in the park has plummeted. Reid says it hasn't lost a single high-value animal in 30 months.

While all this has been going on, EarthRanger's machine learning algorithm has been training. By the end of the year, the program will have ingested enough data to start its next phase, something called "Pre-Bang Enforcement," Nrisimha from Vulcan predicts.

"Post-bang is you see a poacher come in and fire the shot and then you hear it, maybe because you have some sensors there," he said. "You might be successful in that case to intercept the poacher but the animal would have been hurt." Pre-bang is about intercepting poachers before they have a chance to do any harm.

Conservationists hope it will fundamentally change poaching as we know it.

## Unraveling long-held elephant mysteries

Wrege's use of artificial intelligence in the rainforest has been less dramatic, but no less important. The neural networks on which his forest elephant count depends are still training, so he doesn't have a precise forest elephant count yet. He has found that trying to count forest elephant trunks depends on myriad variables: weather, where in the forest they're listening, the season. But the AI has uncovered some unexpected things.

For example, it appears that elephants don't go to some parts of the forest during specific times of the year. That's important to know because it can inform the way park managers deploy their forces. "You can say OK, we know that elephants are not using this huge part of this park for these seven months," Wrege said. "We don't need to send any anti-poaching teams there because no poachers are going to find an elephant anyway."

AI is also helping Wrege unravel some other long-held elephant mysteries — like whether they have a language and how sophisticated it might be. Researchers agree that elephants, like humans, are very intelligent. They have observed their complicated social systems and how they maintain long-term relationships throughout their lives. And researchers believe elephants communicate in a sophisticated way, too.

"When you look at some of the pictures of these rumbles elephants are doing, it looks very much like the picture for humans saying vowels," Wrege said. "When you look at the spectrogram, you can see that the energy is changing from one call to the next and those very well could be different words."

Translating those words is another natural job for a neural network. Wrege envisions a time when it will be able to distinguish the sounds of distress or danger in the calls recorded in the forest. Eventually maybe they'd be able to send out authorities in real time as soon as they hear from the elephants themselves. That may be some years away, but if you ask Wrege whether he thinks AI will save the elephant, he is unequivocal.

"I actually do," he said. "It is definitely going to be our salvation."

## Vocab
- rock (n)岩石, 礁岩, 礦石, 巨岩, 石頭, 寶石, 古柯鹼, [俗]睪丸, 靠山, 暗礁, [非]錢, 搖滾樂, 搖滾, 搖動 (v)(使)搖動, 使震驚, 演奏搖滾樂, 充滿社交活動, 有趣, 因穿戴而顯得好看
	- 岩石 |The solid mineral material forming part of the surface of the earth and other similar planets, exposed on the surface or underlying the soil.| the beds of rock are slightly tilted
	- 礁岩 |A mass of rock projecting above the earth's surface or out of the sea.| there are dangerous rocks around the island
	- 礦石 |Any natural material, hard or soft (e.g. clay), having a distinctive mineral composition.|
	- 巨岩 |A large piece of rock which has become detached from a cliff or mountain; a boulder.| the stream flowed through a jumble of rocks
	- 石頭 |A stone of any size.| the crowd threw a few rocks and dispersed
	- 寶石 |A precious stone, especially a diamond.| It's like a trip through a jewelry store that sells nothing but pricey diamond rings with big rocks.
	- 古柯鹼 |A small piece of crack cocaine.| crack sells for $20 a rock
	- [俗]睪丸 |A man's testicles.|
	- 靠山 |Used to refer to someone or something that is extremely strong, reliable, or hard.| the Irish scrum has been as solid as a rock
	- 暗礁 |(especially with allusion to shipwrecks) a source of danger or destruction.| the new system is heading for the rocks
	- [非]錢 |Money.|
	- 搖動 |Move gently to and fro or from side to side.| she rocked the baby in her arms
	- 使搖晃 |(with reference to a building or region) shake or cause to shake or vibrate, especially because of an impact, earthquake, or explosion.| minutes later a second blast rocked the city
	- 使震驚 |Cause great shock or distress to (someone or something), especially so as to weaken or destabilize.| diplomatic upheavals that rocked the British Empire
	- 演奏搖滾樂 |Dance to or play rock music.| he looked a totally different man and ready to rock
	- 充滿社交活動 |(of a place) be exciting or full of social activity.| the new town really rocks
	- 有趣 |Be very good or pleasing.| this is when the job really rocks
	- 因穿戴而顯得好看 |Wear (a garment) or affect (an attitude or style), especially in a confident or flamboyant way.| she was rocking a clingy little leopard-skin number
	- 搖滾樂 |Rock music.| the store plays a peculiar blend of 70s and 80s rock
	- 搖滾 |Rock and roll.| It is a film for everyone, both those who were touched by this era of rock and those who just remember that fleeting second when the world didn't slow down.
	- 搖動 |A gentle movement to and fro or from side to side.| she placed the baby in the cot and gave it a rock
- on track (to sth) 有望成功/在正軌上
	- They're on track to make record profits.
- demystify (v)使易懂
- treetop (n)樹梢
- spectrogram (n)光譜圖
- ghostly (adj)(聲音或外型)像鬼似的 = eerie 
- marry (v)娶/嫁, 成婚, [into]嫁入/入贅, 把..嫁出, 融合/結合
- Malawi (n)馬拉威，是一個位於非洲東南部的內陸國家
- (be) washed out (adj)洗得褪色的, 極為疲憊的/筋疲力盡的
	- She was wearing an old washed-out T-shirt and jeans.
	- I have to wear make-up in the winter or I look completely washed out.
- terrorize (v)恐嚇/使恐懼
- rugged (adj)高低不平的, 強健的/能吃苦耐勞的, 堅固耐用的 = durable
- ranger (n)護林員, 突擊隊員 = commando, 漫遊者
- as luck would have it 碰巧/幸好 == by chance
	- We ran out of petrol on the way home, but as luck would have it, we were very near a garage.
- wrap up (v)完成 == to complete or finish something
	- It’s getting late – let’s wrap it up.
	- She wrapped up a deal just before she left on vacation.
- turbocharge (v)為..裝配渦輪增壓器, 使更強而有力
- snare (n)陷阱/羅網, 圈套/誘惑, (鼓的)響弦 (v)用陷阱捕捉, 抓到 = catch = trap
- collared (adj)有領子的
- tease out (v)套取/套出, 梳理
- at first blush 乍看之下 == when you first see or experience something:
	- It looks at first blush like a standard smartphone.
- intently (adv)熱切地/熱心地