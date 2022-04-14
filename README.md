# Avengers vs Invaders

*Note: this is an AGPL licensed coding challenge repo, therefore no spoils in commits or issues please if you wish to contribute...*

*Disclaimer: if you happen to be one of the superheroes or invader guys quoted in this file and sort of feel offended or anything, please redirect your anger towards the authors of [wiki page 1][r1], [wiki page 2][r2], [wiki page 3][r3], and [wiki page 4][r4]...just spare my life, I will do anything...*

## Prelude: Where **Your** Legend Starts

In year 20xx, yet another war broke out on earth; but this time the whole human race is put under threat: **3** horrendous armies of evil have joined forces in an attempt to eradicate every single living soul from this planet. As they sew terror and destruction everywhere, people could only chant their names in utter despair with trembling voices as:

* **Invader Group** 1: the **Aliens**, whose **invader species** is itself
* **Invader Group** 2: the **Predators**, whose **invader species** is itself
* **Invader Group** 3: the **D&D Monsters**, which covers the following **10 invader species**:
  * **Beholder**
  * **Devil**
  * **Lich**
  * **Mind Flayer**
  * **Vampire**
  * **Red Dragon**
  * **Hill Giant**
  * **Treant**
  * **Werewolf**
  * **Yuan-Ti**

During this darkest time, our bravest **Avenger** heroes have banded up together, yet again, to answer on the plea of mankind and strive to return peace to this world. In order to perform their super-hero duties in a slightly more organized manner, they decided to set up the following **16** regional **headquarters (HQ)** to split work among them:

* **DE-Headquarter**
* **US-Headquarter**
* **UK-Headquarter**
* **Ocean-Headquarter**
* **BRA-Headquarter**
* **CAN-Headquarter**
* **COL-Headquarter**
* **IND-Headquarter**
* **MEX-Headquarter**
* **NLD-Headquarter**
* **NOR-Headquarter**
* **PAK-Headquarter**
* **TUR-Headquarter**
* **UAE-Headquarter**
* **ARG-Headquarter**
* **Aircraft-Headquarter**

### Info Table: Country-HQ Matching

Firstly, at UN general council a super important topic has been raised, discussed, and agreed upon: for each **country (including region)**, people need to decide which **avengers' HQ** should provide help against which **invader group**. Therefore an info table in the following format has been set up to clarify each HQ's geographical coverage and their respective focus against invader group(s):

| Country Name | Country Code | Aliens          | Predators       | D&D Monsters    |
| :----------- | :----------- | :-------------- | :-------------- | :-------------- |
| Afghanistan  | afghanistan  | PAK-Headquarter | PAK-Headquarter | PAK-Headquarter |
| Albania      | albania      | DE-Headquarter  | DE-Headquarter  | DE-Headquarter  |

The full version of this table can found in the following two formats:

* In the **Country_HQ** tab of Excel file under `Option1_Excel` folder, or:
* In the tab-delimited text file **country_hq.txt** under `Option2_Tab_Delimited_Text` folder

### Info Tables: Avenger Contacts

Now that country-wise protection duties are clear, the avenger heroes can finally sign up to the HQ location(s) they prefer to stay around in. Although the avengers' league seems to be a quite loose association, this time these super-heroes have decided to refine their individual responsibilities as **one or more** of the following **3 Roles** (yeah I know, but don't blame me for being an old school gamer):

* The attack role
* The defense role
* The healing role

And then they decided that the sign-up form should be **HQ-specific**, and they need to define their **roles** in each HQ according to each **invader species**, thus the sign-up form eventually looks like this:

| DE-Headquarter | attack_role | defense_role | healing_role |
| :------------- | :---------- | :----------- | :----------- |
| aliens         | iron.man    |
| predators      | thor        |
| d&d_beholder   | wasp        | wasp         | wasp         |

After they finish signing up, a total of **16** such contact tables have been collected and made available to everyone in the following two formats:

* In the **Contacts** tab of Excel file under `Option1_Excel` folder, or:
* In the tab-delimited text files (named after avenger HQs) under **contacts** subfolder under `Option2_Tab_Delimited_Text` folder

### Final Words before the Challenges Start

OK! Now our avenger heroes are as ready as ever, but it's now really up to **you** to help them save the earth!

You can now choose from two file format options to finish the mandatory challenges, please just pick **one** of the following two to your liking:

* Good Old Excel, for which a single input and output file can be found under `Option1_Excel` folder, or:
* Tab-delimited text (i.e., CSV with tab delimiter) files for input / output, which can be found under `Option2_Tab_Delimited_Text` folder

This coding challenge consists of **2** mandatory tasks and **2** optional tasks. A quick overview of them can be found as follows:

* Mandatory task 1: create a lookup table to provide country-/invader_species-/role-specific email contacts of avengers

* Mandatory task 2: create for each avenger hero his / her personal info table to provide role descriptions under HQ + invader-species context

* Optional task 1: create a Markdown file containing all resulting tables from mandatory task 1 and 2--in Markdown table format, of course

* Optional task 2: create two interactive dashboards for filtering / querying results respectively from mandatory task 1 and 2 outcomes

Note that mandatory tasks are **timed**, whereas optional tasks are not. Therefore, you should **immediately** send me an email with a **zip** attachment containing result file(s) and source code(s) used as soon as you finish mandatory task 1 & 2. Your spent time will be calculated as the time between (1) the instance I send you this repo link via email and (2) the instance I receive your answer to mandatory task 1 & 2 by email--YES, time you spent on reading this child's story **does** count in total. If you did come up with something from the optional task(s), send them to me later on in a **separate** email and there is no need to hurry in that case.

Pick whatever programming language you like: I will try to learn it if it's also new to me...

So yeah, let's start your **legend** now!

## Mandatory Task 1: Just Give Me That F****ing Email!

Now, you (yes, you! don't look around...) are appointed as the Chief Communication Officer of Earth's Resistance Force, and your main job responsibility is to ensure the timely dispatch of signed up avengers to areas in dire need of their aid. Can you envision how your daily life would look like? If you can't, let me give you an example:

You just received a **burning** emergency call from your boss, and he told you to give him **immediately** the Email address of the avenger hero that is responsible for:

* Country: Ireland
* Invader Species / Invader Group: Lich / D&D Monsters
* Role: Healing

And what do you have? Oh, you have the **Country-HQ Matching table** and a bunch of **Avenger Contacts tables**, so you tell your boss: "Wait, let me wade through some tables and look up that avenger hero's name for you, and you see...."

"But people are dying!"

So you scrolled like mad and eventually barely survived the cursings of your boss before you gave him that email address he desperately needs...And several minutes later, you get another call from him:

"Oh, by the way, just want to let you know that 3000 more people DIED when you were searching for that email address...Bear THAT on your conscience!"

OooooKay, it looks like we badly need another lookup table so as just to avoid that sort of tragedy again in future. This new table should definitely look like the following one--but much much longer, of course, we want to **enumerate** all possible cases and in the end we need to put **ALL** information we currently have in this one place:

| Country_Code | Invader_Species | Role        | Email                |
| :----------- | :-------------- | :---------- | :------------------- |
| afghanistan  | aliens          | attack_role | stature@avengers.com |

The skeleton version of this table can found in the following two formats (one of which is where you are supposed to start working on) :

* In the **Task1** tab of Excel file under `Option1_Excel` folder, or:
* In the tab-delimited text file **task1.txt** under `Option2_Tab_Delimited_Text` folder

Oh, by the way, did I forget to tell you that Earth's Resistance Force has already set up an instant message system and created an email account in it for each and every superhero that signed up; and the way from a **signed up name** in **Avenger Contacts tables** to its corresponding **email address** is as simple as the following example (no upper case chaos, no white space mess, no forbidden characters--nice, right?):

    iron.man --> iron.man@avengers.com

There is one troublesome news, though, I heard there are *maybe* some superhero(s) from the **DC world** that *somehow* signed up with our avengers' onboarding form and ended up helping us in this parallel universe...And in that case please kindly keep that whole `@dc-whatever.nomatterwhat` part of text in the sign-up form and **do not** replace them with the `@avengers.com` string--you know, these guys have a different communication system that we eventually managed to get an API interface to and...oh, I guess I bore you already...

And one last thing before I forget: you might have already noticed that there are some blank fields in some of the **Avenger Contacts tables**--well, the reasons are pretty obvious, but I guess you still want some explanations:

* Some superheroes are just addicted to the lone wolf show and just won't work with others when fighting the invaders.
* There are certain regions that are *almost* not inhabited by anyone, so we are reluctant to dispense any resource there and...well, you know, we've got to give the bad guys some place to retreat to so that we could shoot the avengers vs invaders 2 sequel somewhere in future...when we found our new sugar daddy...if we managed it...

What does that mean for you? Well, just remember that you should **not** create any row with **empty email address** in the final lookup table, and then everything will be fine...

So now off you go! Our brave CCO (that is, if you still remember what it means)!

## Mandatory Task 2: Do Whatever Necessary to Make Them Happy

So I see you are indeed an efficient young man / woman, you have already finished your first task and have come back here to ask for more. To reward your excellent work and self-motivation, the Earth's Resistance Force Committee has decided...that you will be given an additional role of Chief Friendship Officer, on top of your current responsibility of Chief Communication Officer! You should see both roles equally important and invest 50% / 50% of your capacity in both of them...

Hmmm...What? You want to talk about compensation and benefits? Firstly I believe you need to obtain signed approvals from all the local worker union / Betriebsart / party representative council / mafia ensemble / or whatever trouble-makers you can find from **each** of the regional HQ offices that you have contact with to start such a conversation; and then you need to talk to your CCO role's boss (no that's not me, you are mistaken) to get a permission to talk to me, which in theory would only work if you have already obtained a permission from me to talk to him for such a topic in the first place...and...you know, I would really ***love*** to help you there if I ***could***...

Okay, people are still dying so let's get back to business before you capitalize more on their misfortune. Hmmm...where was I? Oh yes, the whole Chief Friendship Officer thing is, that, err...we have sort of **lost count** of how many superheroes we have signed up in the team and it's getting more and more awkward when we meet one of them and can't say thank you for **exactly** what he or she is doing...Since my boss just recently cancelled the Key Account Manager headcount due to *budgetary* reasons, you have now become our best candidate for the task!

Why do you ask me how to complete this task? You are the new key account...err, I mean, Chief Friendship Officer, not me...Just use your common sense! Superheroes typically have super egos, right? So fuel that thing up! Give each one of them an **individual** home page listing down all the activities they are up to and allow random peoples to give them thumb-ups--Oh no, no thumb-down buttons and no comment fields, have you even got an idea of how many online trolls are actually out there in the wild? I mean, not D&D trolls, we forgot to put them in the list, but don't you worry, they would only *start* to physically exist when we add them to the list...Err, can we just stop this line of discussion? I fear I may have breached some serious security code just now...Oops, excuse me, I have to pick up this phone call, hang in there...

Alright, since my boss just informed me that our whole front end team was sacked like two minutes ago, let's park the home page idea for now and give our superheroes the **second best thing** they deserve--individual tables! I know they would miss all the 'Like' numbers, but...hey, they could all have their names placed in header-lines (no puns here, seriously) of their dedicated tables, which is extremely satisfying already if you ask me. So let me show you a **bloated-form** example of what I mean here:

| iron.man             | aliens | predators | d&d_beholder | d&d_devil | d&d_lich | d&d_mind_flayer | d&d_vampire | d&d_red_dragon | d&d_hill_giant | d&d_treant | d&d_werewolf | d&d_yuan-ti |
| :------------------- | :----- | :-------- | :----------- | :-------- | :------- | :-------------- | :---------- | :------------- | :------------- | :--------- | :----------- | :---------- |
| DE-Headquarter       | A      |
| US-Headquarter       |
| UK-Headquarter       |
| Ocean-Headquarter    |
| BRA-Headquarter      |
| CAN-Headquarter      |
| COL-Headquarter      |
| IND-Headquarter      |
| MEX-Headquarter      |
| NLD-Headquarter      |
| NOR-Headquarter      |
| PAK-Headquarter      |
| TUR-Headquarter      |
| UAE-Headquarter      |
| ARG-Headquarter      |
| Aircraft-Headquarter |

You see, all you need to do to make those superheroes happy is to list down their **role(s)** at each **avenger HQ** with respect to each **invader species**!

Oh, And I almost forgot to explain to you what that ***A*** field means in the table above: it is just a shorthand of **avenger role(s)**. You can find a complete list of them as follows:

* A stands for attack role
* D stands for defense role
* H stands for healing role
* AD stands for attack + defense roles
* AH stands for attack + healing roles
* DH stands for defense + healing roles
* ADH stands for attack + defense + healing roles

Of course, If you don't like all the empty fields in the table above, you can also make it lighter into the following **lite-form** example:

| iron.man       | aliens |
| :------------- | :----- |
| DE-Headquarter | A      |

The skeleton version of the upper bloated-form table can found in the following two formats (one of which is where you are supposed to start working on) :

* In the **Task2** tab of Excel file under `Option1_Excel` folder, or:
* In the tab-delimited text files (named after avenger names) under **task2** subfolder under `Option2_Tab_Delimited_Text` folder

You can choose to finish this task with either **bloated-form** or **lite-form** tables as you like.

Just don't forget any superheroes (that **includes** also our DC-world guys) and don't create duplicated tables for any one of them. Best luck to you, my young Chief Communication and Friendship Officer!

---
## The Limbo Area between Mandatory Tasks and Optional Tasks

If you finally made it here, then congratulations, young CCFO! You have just helped us to save millions of ~~virtual~~ lives and successfully prevented the potential mutiny of many charted superheroes that were--and still are utterly ***unhappy*** about their *KPI-optimized* wages...But anyways, the war is finally over, and you are now given a full-day ~~self-~~ paid leave to any dream holiday resorts that you fancy.

Return when you are recharged, feeling adventurous and can't wait to take up more challenges!

And don't forget to send your mandatory task results and accompanying source code to my email address in time!

---

## Optional Task 1: My Boss Just Came Back from a GIT Workshop

Greetings, Ex-CCFO of the late Earth's Resistance Force: I am approaching you on behalf of Earth's Reconstruction Council to enlist you in urgent service of whole mankind--your mission now is of unspeakably paramount importance to the peace-keeping of our hard-earned victory, and since it is classified as a top secret, I have to demand you to ask exactly zero questions and simply follow my orders like a mindless robot and...Ouch! There is no need to use violence here! You are a war hero, people expect you to behave! Ouch! OK, OK, let's talk about it on open and equal terms...

Well, you see, all these messes were created back on the day when my boss finished a GIT workshop: apparently after he came back, he started talking nuts like 'we all have to live cloud native', or 'open source now or our business will soon die', or 'git is now the new norm and we should just burn all the svn guys', or 'we must sue ~~MS~~ Google to get our office budget back and use Latex and reveal.js instead for everything', and some even more horrific statements that won't barely pass the Github code of conduct. The worst past of brainwashing he received, however, was that he started murmuring about version control like crazy and asked us to convert all **Excel and CSV tables** into **Markdown** format and upload to his personal Github account! YES, that includes ***every single table*** you created when you were helping in the avengers vs invaders war!

As a veteran of war, I believe you already know that your DNA information has been hard-coded into every single piece of digital deliverable you uploaded to the **SYSTEM**--that's how I tracked you down here, and that's why now my problem has become **your** problem. Well, you don't need to thank me for anything, because we all serve the SYSTEM eventually, in one way or another...

Oh, and there are also a couple of messages that my boss asked me to forward to you, just to make sure that you won't oversmart yourself:

* Do not attempt to use any online tool to do this conversion: the moment you upload anything to the public internet, we *will* know and you are dead meat
* Similarly, do not even think about applying for a budget to buy any offline tool to do this conversion, we are wayyyyy cheaper than you thought
* You are free to use any established open source tools, though, although that would influence your evaluation and your payroll in the end
* We need not only the resulting Markdown file, we need your source code as well to prove that you have actually *worked* on it
* ~~If you don't star my boss' Github repo (you know the link), you are dead meat~~
* No, don't do anything at Github, just pack everything into a single Markdown file and send it to me in an email

Last but not least, you are now CCFO again, but now you work for Earth's Reconstruction Council--like me, you work for the **SYSTEM**. You can now chat with all your avenger best friends again, using of course our latest AI-enhanced social media app based on block chain technology that would absolutely not spy on anyone since you can only pay with NFT to use it at all...Exciting, right? You get 10% off if you buy NFT's from me, and...Oh, I see, obviously you can't even wait to log on to this new platform...

## Optional Task 2: The Front-End Team is Back...And That's You!

Greetings again, our young CCFO reborn and former war hero! I can see from your face that you are settling yourself down quite comfortably now with a 50% / 50% work split and a zero-ramp-rate linearly interpolated salary curve exhibiting salient uniform distribution PDF characteristics under time domain in the past couple of years. I have brought **great** news with me, and I believe you will be positively thrilled to hear what I am about to say: our management has eventually agreed to revive the prematurely terminated **Front-End Team**, and based on your past performance you have been nominated to be the Chief Front-End-Solution Officer for this team on a 35% capacity basis, which makes you effectively now the first CCFFESO in human history--Congratulations!

What about your other two roles? Day as usual, of course! No, no, no, don't get me wrong here, your previous two roles will still each demand 50% of your capacity, and this new front end role will add a marginal 35% on top of them, making you **only** 135% loaded on a daily basis--I am pretty sure you are still competent enough to find out ways to handle that, right? Let's not keep dwelling upon those minor details, shall we? There're still lots of topics for us to cover...Team size? Glad that you brought this issue up since that is exactly my next point! You are the only team member planned so far, which means ***you are the Team***...

Don't look at me like that! You only need to change yourself into a ***10x engineer*** and...Boom! Problem solved! Well, at least from my side...So now that we have taken this item off the list as well, let me try to look for that little memo piece from my boss...Ah, here you go! This is a pretty nice list of what is expected from you, I mean, err...coming from the management:

* UI View 1: You should independently create a query page with country-, invader_species-, and role-filters to show up immediately the queried superhero email address in a little text field
  * The management expects **both** open text field input **and** a drop-down list of all three filter entries: country, invader species, and role
  * You do **not** have to rely on the monster output table coming out of mandatory task 1 for this query page...Just try to stay creative and flexible...

* UI View 2: Remember that superhero homepage idea? Yes, it's officially back! You should now come up with a real, interactive dashboard for each and every superhero as we promised to them a long time ago
  * There should be a navigation column or row sitting next to the dashboard, such that you can browse through dashboards of different superheroes with a name filter in form of **both** open text field input **and** a drop-down list (sounds familiar, I know)
  * The content of the dashboard is basically each superhero's dedicated role overview table you obtained from mandatory task 2, however--the management expects you to convert each A/D/H/AD/AH/DH/ADH text field into a hyperlink. And when you click on it, a nice **trending chart** will pop up showing the number of invaders (under the specified invader species) this superhero defeated in each one of the last 10 months...You don't have that data? Neither do I! So just make things up using a random number generator or something, ***nobody*** cares!
  * Don't forget about the '**Thumb Up**' button! Remember it's one-way traffic and you can't reduce the ***Like*** count at any rate!

* Oh, the management also asked for a **This Avenger's Homepage** button sitting next to the queried email result text field under UI View 1, which bring you to the corresponding dashboard under UI View 2. And then in the navigation menu of UI View 2, there should also be a '**Search for Avenger**' button to bring you to UI View 1....Actually, just use the navigation column or row for both views, and that's it!

* You can use ***any*** Web-based or Desktop-App flavor of UI realization, the management would even accept an implementation in Excel if you made it!

Ok, now that we are done with all these annoying technical details, we can err...officially talk about some **bonus** for you once you ***completed*** all the above-mentioned UI requirements. The management has promised you a **hefty** 2.01% salary boost! Rejoice! You beated 99.8% of all SYSTEM employees in terms of performance! When can you see it in your payroll? As I said, you need to finish the task first...

Oh, there is also an **SYSTEM**-wise announcement today that all future employee salary starting from next month will be paid from our patented NFT pocket--you see, you will **only** be able to consume those Tokens within the **SYSTEM**, but since we have almost everything here, there is absolutely **nothing** to worry about...Why are you crying? What? I didn't know you have kids to raise, your wife / husband didn't tell me that last night...

Wait! What is that unsanctioned telecommunication device in your hand? Why is there a flashing iron man portrait on it? Isn't he supposed to be dead in the war? Stop! Do not approach me! One step forward and you are dea.....Oh! Euch! No! Please! No!...

## TO BE CONTINUED

That is, if we ever found a way to finance a sequel...

Till then!

[r1]: https://en.wikipedia.org/wiki/List_of_Avengers_members
[r2]: https://en.wikipedia.org/wiki/List_of_Advanced_Dungeons_%26_Dragons_2nd_edition_monsters
[r3]: https://en.wikipedia.org/wiki/Lists_of_DC_Comics_characters
[r4]: https://en.wikipedia.org/wiki/Alien_vs._Predator_(film)
