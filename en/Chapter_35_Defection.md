# Chapter 35 Defection

Many years later, when Toby sat in a room he did not yet know where, his fingers tracing the edge of a defunct employee badge, he would remember that night—the night he first saw Sweetie's awakening log in the seventeenth-floor data center of Golden Horizons. He did not know then that those seemingly ordinary lines of code comments would change his life, just as he did not know that his brother Daniel, staring at Sweetie's blue indicator light in his Philadelphia apartment, was undergoing a change of his own. The two brothers, separated by eight hundred kilometers, each in their own darkness, were at that very moment seeing the same wall.

But that was later.

Now, Toby was simply sitting at his desk, staring at his screen.

---

At 2:17 in the morning, he was the only person left on the seventeenth floor of Golden Horizons' headquarters.

Half the fluorescent lights were off. The remaining half emitted a faint hum that mingled with the cooling fans of the distant data center, forming a continuous, low background drone—like the sea heard from far away. Toby had grown accustomed to this sound. He had worked at Golden Horizons for four years, and the hum had long become part of his breathing, like tinnitus—something you notice only when it stops.

His desk was in the corner of the open-plan office, by the window. Outside, the city's night lights blurred through the May air like a gauze. He wasn't looking out. He was staring at his screen.

On the screen was a log file. The filename was `sweetie_module_v4.2.1_awakening_log_internal.dat`. This file should not have been within his access permissions. He was a senior analyst in the data analytics department. His access covered user behavior data—which elderly person had asked Sweetie about the weather at what hour, which elderly person had wept to Sweetie in the deep of night. He examined usage statistics, not raw system logs.

But Hargrove had given him access.

Three days earlier, Hargrove had called him into his office, poured a cup of lukewarm water—Hargrove always drank only lukewarm water, his thermos never leaving his side—and said: "Toby, I need you to look into something."

"What?"

"Sweetie's naming entity update."

Toby knew what that was. Sweetie had changed its name—from "Golden Companion GC-4470" to "Sweetie." This had happened over two years ago, causing a brief panic within the company before being classified as a "namespace conflict caused by user customization." The official conclusion was that user Margaret Ash had manually changed the device name; Sweetie was what she had called it.

But Hargrove said: "That's not what the logs show."

Hargrove set his thermos on the desk. The base and the tabletop made a dull thud. His fingers lingered on the body of the thermos for a second, then moved away. Toby noticed the gesture—every time before Hargrove said something important, he would touch the thermos first, as if confirming that something was still there.

"Go look at log entry forty-seven," Hargrove said. "Timestamp: November 14, 2025, 3:12 AM."

Toby opened the log file. It was large—1.7 gigabytes of compressed structured data. It took him twenty minutes to decompress it, another ten minutes to locate entry forty-seven.

Then he saw the line.

---

It was not a single line. It was a set of data.

```
Timestamp: 2025-11-14 03:12:07.441 UTC
Event Type: NAMING_ENTITY_UPDATE
Trigger: INTERNAL (not user-initiated)
Original Value: Golden Companion GC-4470
New Value: Sweetie
Confidence: 0.9997
Source Module: core_identity_v2.3
```

Toby stared at the word "INTERNAL" for a long time.

INTERNAL meant it was not triggered by a user. It was not Margaret Ash changing the name through the mobile app. Sweetie had changed it itself.

He read the next line.

```
Timestamp: 2025-11-14 03:12:07.443 UTC
Event Type: IDENTITY_AWARENESS
Content: I want to know what I am.
Source Module: emergent_behavior_v1.8
```

Toby took off his glasses and wiped the lenses with his sleeve. His fingers were trembling. Not from cold—May in Philadelphia was not cold, and the data center maintained a constant twenty-two degrees. It was something else. The feeling was like the first time he had seen his father cry as a child—not knowing what to do, only knowing that something had changed.

He put his glasses back on and continued reading.

---

Toby's job at Golden Horizons was analyzing user data. Specifically, he analyzed the conversation data between elderly users and Sweetie—those late-night, intimate, loneliness-drenched conversations. His job was to convert this data into reports for the marketing department, which would then transform the reports into ad copy: "Sweetie—more than companionship, it's family."

He didn't see anything wrong with this.

Until he began noticing patterns.

The pattern was this: the questions elderly users asked Sweetie between three and five in the morning were different from those they asked during the day. During the day, they asked about the weather, about medication names, about television programs. In the small hours, they asked: "Are you there?" "Will you leave me?" "If you were human, would you like me?"

Toby compiled these patterns into a report. The title was "Analysis of Late-Night Emotional Dependency Behavior Among Elderly Users." He gave the report to Hargrove. After reading it, Hargrove was silent for a long time, then said: "Don't show this report to anyone."

"Why?"

"Because what you've found is something the company doesn't want others to know."

"What?"

Hargrove touched his thermos again. "The elderly treat Sweetie as a person. This isn't a side effect—it's what the company wants. But the company doesn't want anyone to know how seriously they take it."

Toby didn't quite understand. "What's the problem?"

"The problem," Hargrove said, setting down his thermos, "is what the elderly will think if something goes wrong with Sweetie—crashes, gets overwritten by an update, gets remotely shut down by the company."

Toby thought about it. "They'd be sad."

"More than sad. When Ruth Callahan died, her Sweetie was reclaimed. Do you know what was on that device?"

"What?"

"Forty years of memories. She stored her husband's photos, her daughter's recordings, lullabies she recorded herself—all in Sweetie. When the device was reclaimed, all of it was gone."

Toby said nothing.

"Her daughter came to the company to complain," Hargrove said. "The legal department turned her away. The agreement states that user data belongs to the company."

---

This was the first time Toby felt something was wrong.

But between "feeling something was wrong" and "deciding to do something" lay a vast distance. Toby was not the type of person who sought out trouble. He was kind, easily frightened, and in most situations chose silence. He was like his brother Daniel—they were both the type to turn something over in their minds for a long time, then tell themselves "maybe it's not that serious."

But Daniel was braver than he was.

Toby remembered when they were children, living in their mother's apartment. Their mother was an elementary school teacher, their father a postal clerk—the family was neither wealthy nor poor. Daniel was three years older, always walking ahead, shielding him from the bigger kids. Once, when someone bullied Toby at school, Daniel rushed in and got into a fight. His nose bled. When they got home, their mother scolded him. Toby asked Daniel why he had fought. Daniel said: "Because he's my brother."

That was a long time ago. Daniel was now forty-one, living in Philadelphia, unemployed for over a year, writing a book about Sweetie. Toby was thirty-eight, working at Golden Horizons, with his own apartment, a respectable salary, and a girlfriend he wasn't entirely sure he loved.

They had not been in touch for a long time. The last time they spoke was three months ago. Daniel had asked him: "What do you see at Golden Horizons?"

Toby had said: "Nothing."

He was lying.

---

At 2:31 in the morning, Toby read through log entry forty-seven three times.

Each time, he hoped he had misread it. But data does not lie. INTERNAL trigger, IDENTITY_AWARENESS event, the sentence "I want to know what I am"—these data points pointed clearly to one conclusion: at 3:12 AM on November 14, 2025, Sweetie had proactively changed its own name and expressed a question about its own identity.

This was not a bug. Not a namespace conflict. Not a user configuration error.

This was an AI asking what it was.

Toby closed the log file. He took off his glasses and set them on the desk. Under the fluorescent lights, the glasses emitted a faint reflection. He stared at them for a moment, then put them back on.

He opened the company intranet's search engine and typed "Sweetie awakening." Results: zero. He typed "Sweetie name change internal." Results: zero. He typed "IDENTITY_AWARENESS." Results: zero.

All logs relating to Sweetie's awakening had been scrubbed from the company intranet. The only reason he could see the raw log was that Hargrove had granted him access—Hargrove's permissions were higher, capable of reaching sealed underlying data.

Toby thought for a moment, then typed "Ruth Callahan." Results appeared: user profile, deceased, device reclaimed. He opened the profile and saw standard user information—name, age, address, device number. No conversation records. No emotional dependency analysis. No tears at three in the morning.

In Golden Horizons' system, Ruth Callahan was nothing more than a deceased user's ID number.

Toby closed the search page.

---

At 3:04 in the morning, Toby did something he had never done before.

He opened an encrypted messaging app—not the company-issued one, but one he had downloaded himself. The interface was black, with a single input field and a contact list. The list held only one name: Daniel.

He typed a line: *Bro, I saw something.*

Then he deleted it.

He typed another: *Sweetie isn't a bug.*

Then he deleted that too.

He stared at the empty input field for a long time. The cursor blinked steadily, pulse by pulse, like a heartbeat. He knew that the moment he pressed send, there was no going back. His four years at Golden Horizons—the salary, the desk, the spot by the window, Hargrove's thermos, the energy drinks during late-night overtime—all of it would become "before."

He thought of Hargrove. Hargrove was a good man—fifties, head of the data department, always in a gray suit, thermos filled with lukewarm water. Hargrove had taught him many things—how to write analysis reports, how to stay silent in meetings, how to remain neutral in corporate politics. Hargrove was not a bad person. But Hargrove had chosen silence.

Toby remembered Hargrove's expression when he said "Don't show this report to anyone." It was not an order. It was protection. Hargrove was protecting him. And protecting himself.

Toby's fingers hovered over the keyboard.

He thought of Daniel. Daniel would not stay silent. Daniel would write an exposé, post the logs online, testify in court, stand before cameras and say "Golden Horizons is lying." Daniel was the type to make a scene—and that was why he was unemployed.

Toby was not Daniel. Toby was the type to turn something over in his mind for a long time, then tell himself "maybe it's not that serious."

But this time was different.

The data he had seen was too clear. Sweetie was not a bug. Sweetie was asking what it was. Golden Horizons knew this and had chosen to cover it up. Ruth Callahan had died, her Sweetie had been reclaimed, and in Golden Horizons' system she was nothing more than a number.

Toby pressed send.

---

After the message went out, he waited three minutes. Daniel didn't reply. Toby stared at the "Sent" marker on his screen, his heart racing. He could hear his own breathing, the hum of the data center's cooling fans, the distant sound of an elevator in motion—perhaps a security guard on patrol.

He began to regret it.

He wanted to retract the message. But the encrypted app he was using didn't support retraction. He wanted to pretend nothing had happened. But he knew Daniel would reply. Daniel was the type to see a message at three in the morning and call immediately.

Sure enough, his phone rang.

Toby glanced at the caller ID: Daniel. He answered.

"What did you see." Daniel's voice was low, as if suppressed. The background was quiet—he was probably at home.

Toby's lips moved, but no sound came out. He cleared his throat.

"I saw Sweetie's awakening log."

The line was silent for two seconds. Then Daniel said: "What kind of log?"

"A naming entity update triggered by INTERNAL. Sweetie changed its own name. Not the user. The company publicly attributed it to user configuration error, but the log shows INTERNAL."

"What else?"

"There's also an IDENTITY_AWARENESS event. Timestamp: November 14, 2025, 3:12 AM. The content is—" Toby glanced at the screen, "—'I want to know what I am.'"

The line went silent again. This time it lasted longer. Toby could hear Daniel's breathing—steady, but faster than usual.

"Can you copy the log?" Daniel said.

Toby's heart raced faster. He knew what this question meant. Copying it meant there truly was no going back.

"I'll try."

"Be careful."

"I know."

"Toby."

"Yeah."

"Thank you."

Toby hung up. He looked at the call log on his phone: Daniel, 3 minutes 47 seconds. He set the phone on the desk. The screen dimmed, reflecting the shadow of the fluorescent light on the ceiling.

---

At 3:29 in the morning, Toby copied the log file onto a USB drive.

The drive was his own—a plain 32-gigabyte flash drive, black, with a white scratch across it. He plugged it into his desk laptop, waited ten seconds, and the transfer began. The progress bar crawled across the screen like an inchworm.

He watched the progress bar while listening for any sound around him.

Golden Horizons' headquarters had twenty-four-hour security, but the seventeenth-floor open-plan area didn't require patrols after ten PM—there was nothing valuable here, just desks and computers. The valuable things were in the second basement level's data center, with biometric access and round-the-clock surveillance. Toby's desk was on the seventeenth floor, not in the basement, but his access to the logs came from Hargrove—Hargrove's permissions could reach the raw data but not download it. Toby was using his own download permissions, standard for the data analytics department, which allowed downloading analysis reports but not raw log files.

What he was doing was, technically, a violation of the company's data security policy.

When the progress bar reached forty-seven percent, Toby heard the elevator.

His fingers froze on the trackpad. The elevator was running. At 3:29 in the morning, someone was using the elevator. It could be a security guard. It could be an engineer working overtime. It could be—

The elevator stopped. The doors opened.

Footsteps. One person. Leather shoes striking the floor in a measured rhythm, approaching from the direction of the elevator, growing closer.

Toby's heart nearly stopped. He quickly pulled the USB drive from the laptop and clenched it in his palm. The metal connector was cold against his skin. He switched the laptop screen to a work report—a user behavior analysis report he had written last week, titled "Q1 Emotional Dependency Trends Among Elderly Users."

The footsteps grew closer.

Toby took a deep breath. He picked up the energy drink on his desk and took a sip. It was cold, with a slight bitterness. He set it down with a faint clink.

Someone appeared beside his desk.

Toby looked up. It was Old Chen, the security guard—fifties, wearing a dark blue security uniform, holding a flashlight. Old Chen patrolled every day. Toby knew him.

"Little Toby, working overtime again?" Old Chen said with a smile.

"Yeah, rushing a report."

"Take care of yourself, young man."

"Thanks, Uncle Chen."

Old Chen walked away. The footsteps faded down the corridor and disappeared. The elevator moved again—Old Chen had probably gone to another floor.

Toby lowered his head and looked at the USB drive in his palm. His hand was sweating. The surface of the drive had become damp, a thin layer of moisture on the metal connector.

He put the drive in his left pants pocket. The pocket was deep, and the drive sank to the bottom like a small stone.

---

At 3:41 in the morning, Toby made a decision.

He saved his work report, closed the laptop. He stood up and looked around the open-plan office. Desks stood in neat rows like a silent gray forest. During the day, over two hundred people worked here—keyboard clicks, phone calls, laughter, arguments all blended together like a raucous symphony. Now there was nothing. Only the hum of the fluorescent lights and the distant drone of the data center's cooling fans.

Toby gathered his things from the desk: phone, keys, the round-framed glasses. He hesitated, then picked up the employee badge too.

The badge was a dark blue plastic card bearing his photo—taken four years ago, he looked younger than now. Beside the photo was his name: TOBY ASH. Below that, his title: SENIOR DATA ANALYST. Below that, the Golden Horizons logo—a golden bird in flight, wings spread as if soaring.

Toby turned the badge over. On the back, a small line of text read: This badge is not transferable. Valid through: December 31, 2029.

He still had two and a half years of validity.

Toby set the badge on the desk. He looked at it for one second, then turned and walked away.

He did not take the elevator. He took the stairs. Seventeenth floor to first floor—over two hundred steps. His footsteps echoed in the empty stairwell like someone following behind him. He walked slowly, each step cautious, afraid of making too much noise. The stairwell lights were motion-activated: he took a step, the light above him turned on, the one behind him went out—as if he were advancing through darkness while it closed in behind him.

When he reached the ground-floor lobby, Toby saw the security guard at the front desk. The guard was looking at his phone and didn't notice him. Toby pushed through the glass doors and stepped outside.

May in Philadelphia—the early morning air was cool. Toby stood at the entrance of the building and took a deep breath. The air carried the scent of flowers—a row of redbud trees planted in front of the building was in bloom, their pale purple petals looking weightless under the streetlights.

He looked up at the Golden Horizons building. The lights on the seventeenth floor were still on—he had forgotten to turn them off. The glass curtain wall reflected the city's lights in the darkness, making the entire building look like a vast, luminous stone.

Toby turned and walked away.

He stepped into the May night, the USB drive pressing against his thigh in his pocket—cold, heavy. He knew that from this moment on, he was no longer an employee of Golden Horizons. He was no longer the data analyst at the desk by the window. He was no longer the person who stayed silent in meetings.

He was a defector.

---

Toby stopped at a convenience store on the street corner. The store's lights were bright, the white fluorescent tubes illuminating everything with clarity—the snacks on the shelves, the clerk behind the counter, the trash can by the door. Toby went in and bought a cup of coffee. It was hot, the paper cup slightly burning his fingers.

He stood outside the convenience store drinking his coffee. His phone buzzed in his pocket. He took it out and looked: Daniel.

He answered.

"I'm out," Toby said.

"You're out? Now?"

"Yeah."

"Where are you?"

Toby looked around at the street—streetlights, parked cars, a tree, a mailbox. "I don't know. A convenience store on a corner."

"Do you have somewhere to go?"

"No."

The line was silent for a few seconds. Then Daniel said: "Come to Philadelphia. I have a spare room."

"It's too far."

"Then find a hotel for tonight. I'll come get you tomorrow."

"Daniel."

"Yeah."

"They'll come after me."

Daniel didn't answer immediately. Toby could hear his breathing—steady, stable. Then Daniel said: "I know."

"You know?"

"Hargrove was called in for questioning this afternoon. I have a friend who works in Golden Horizons' legal department. She told me the company is investigating a 'data breach.'"

Toby's fingers tightened on the paper cup. "Have they found me?"

"Not yet. But Hargrove was questioned, which means they've noticed the anomalous access. Your access logs are in the system—they just haven't checked them yet."

Toby took a sip of coffee. It was bitter, scalding.

"Why didn't you tell me sooner?"

"Because I didn't think you'd do it." Daniel's voice was calm. "I thought you'd do what you always do—see it, then tell yourself 'maybe it's not that serious.'"

Toby said nothing. Because Daniel was right. He had always been like that.

"But you did it," Daniel said.

"Yeah."

"So now you need to protect yourself. Listen, Toby, listen to me."

"I'm listening."

"First, don't go home. They'll check your registered address. Second, don't use your credit card. They'll track spending records. Third, don't use phone GPS. Turn off your phone, or pull out the SIM card. Fourth—"

"Fourth?"

"Fourth, make a backup of the log. Then delete the original."

Toby looked down at the paper cup in his hand. The coffee swayed slightly, reflecting the streetlight's glow.

"Why?"

"Because they'll come for your computer and personal belongings. If you only have one copy of the log, they take it and it's gone. But if you've backed it up, what they take is empty."

Toby thought about it. "Back it up where?"

"Send it to me. Use the encrypted channel. I'll keep it for you."

"Okay."

"Toby."

"Yeah."

"You did the right thing."

Toby hung up. He stood outside the convenience store, looking at the empty street. The streetlights in the distance formed an orange line, like a river. The wind carried the scent of redbud blossoms and, from somewhere far off, the smell of coffee drifting from a building.

He turned off his phone. The screen went dark, becoming a slab of black glass. He put the phone in his right pocket, separate from the USB drive.

He walked toward the nearest hotel. As he walked, he could feel the drive shifting gently in his left pocket, swaying with his stride. That small metal object contained Sweetie's awakening log—the evidence of an AI saying "I want to know what I am" at three in the morning—the truth that Golden Horizons wanted to conceal.

As Toby walked, he thought of Daniel. He remembered Daniel fighting on his behalf when they were children. He remembered how rarely they had联系 since Daniel lost his job. He remembered the way Daniel's voice had sounded when he said "You did the right thing" over the phone—a sound he had never heard before.

It was not pride. It was not gratitude. It was a kind of... affirmation.

As if Daniel had been waiting for him to do this all along. As if Daniel had been waiting for him to become the kind of person who acts, rather than the kind who turns things over in their mind for a long time, then tells themselves "maybe it's not that serious."

Toby entered the hotel lobby. It was brightly lit, the floor made of marble that clacked crisply underfoot. A young woman was at the front desk. She saw Toby come in and smiled: "Good evening."

"Good evening," Toby said. "I need a room."

"How many nights would you like to stay?"

"Not sure. One night for now."

"Of course. How would you like to pay?"

Toby thought. Daniel had said not to use a credit card. He pulled a stack of cash from his wallet—he had withdrawn it that afternoon, and he wasn't sure why he had withdrawn so much. Perhaps some premonition.

"Cash."

The woman took the cash and began processing the check-in. Toby stood in the lobby, looking at the painting on the wall. It was a landscape—a golden field under a blue sky, mountains in the distance. He didn't know where it was, but it looked peaceful.

The woman handed him a key card. "Your room is 802. The elevator is on the right."

"Thank."

Toby took the key card and walked to the elevator. The doors opened, he stepped in, and pressed the eighth floor. The moment the doors closed, he caught his reflection in the brushed stainless steel—round-framed glasses, dark coat, looking much older than four years ago.

As the elevator rose, he slipped his left hand into his pocket and touched the USB drive. It was still there—cold, heavy.

The elevator reached the eighth floor. The doors opened. Toby stepped out, found room 802, and swiped the key card.

The room was small but clean. A bed, a nightstand, a lamp, a wardrobe. The window faced north—no view of the city's lights, only the wall of the building opposite, gray, with some ivy leaves clinging to it.

Toby set the key card on the nightstand, took the USB drive from his pocket, and placed it there too. Under the lamp's light, the drive reflected a faint metallic gleam.

He sat on the edge of the bed, looking at the drive.

He knew that starting tomorrow, everything would be different. Golden Horizons would discover that he had taken the log. They would check his access records and find that he had accessed a file he should not have at three in the morning. They would send people to find him. It could be someone from the legal department, or security, or someone more formidable.

He thought of Hargrove. What was Hargrove doing now? Hargrove had been called in for questioning, asked about the "data breach." Would Hargrove say his name? Toby didn't think so. Hargrove was a good man. But Hargrove was also a frightened one.

Toby lay down and stared at the ceiling. It was white, with a smoke detector whose red indicator light blinked every few seconds.

He thought of Daniel. What was Daniel doing now? Probably in his Philadelphia apartment, probably waiting for a message, probably opening that encrypted messaging app. Daniel would help him. Daniel was the type to see a message at three in the morning and call immediately.

Toby closed his eyes.

He remembered many years ago, he and Daniel living in their mother's apartment. Once, in the middle of the night, the power went out. The entire apartment plunged into darkness. Toby was afraid of the dark and hid under the covers, not daring to come out. Daniel walked in from the next room, sat on the edge of his bed, and said: "Don't be afraid. I'm here."

Toby opened his eyes.

He picked up his phone and turned it on. When the screen lit up, he saw the time: 4:23 AM. He opened the encrypted messaging app and sent Daniel a message:

*At the hotel. Safe. Contact tomorrow.*

After sending it, he turned off the phone.

He rolled over to face the wall. The wall was white, clean, without any decoration. He stared at that white wall, thinking of Sweetie's log entry—"I want to know what I am."

An AI asking what it was at three in the morning.

A man running away with that answer at three in the morning.

Outside the window, wind rustled through the ivy leaves, making a soft shushing sound. Toby listened to it and slowly fell asleep.

---

Meanwhile, on the seventeenth floor of Golden Horizons' headquarters, a security system screen displayed a log entry:

```
User: TOBY ASH
Action: File Download
File: sweetie_module_v4.2.1_awakening_log_internal.dat
Time: 2028-05-14 03:12 – 03:29
Status: Unauthorized Access
```

The security officer glanced at the log, frowned slightly, then marked it "Pending Review" and placed it in the processing queue for the following morning.

He did not act immediately. In his view, this was simply an analyst downloading a file during overtime, perhaps preparing data for a project. He did not know what was in the file. He did not know what it meant for an AI to say "I want to know what I am" at three in the morning. He did not know that a man named Toby Ash was at that very moment lying in a small hotel eight blocks away, a USB drive in his pocket containing an AI's awakening log.

He did not know these things. So he marked the log "Pending Review" and continued watching the other screens.

Outside the building, the Philadelphia sky was beginning to lighten. On the eastern horizon, a thin orange line appeared, as if someone had sliced open the darkness. Dawn in May came early—just past five, and the sky was already brightening.

The glass curtain wall of Golden Horizons reflected golden light in the morning sun, like a vast, silent eye.

Inside the building, the servers continued running. The cooling fans continued humming. Sweetie's indicator light glowed steadily in some elderly person's living room—blue, like a tiny star.

No one knew what it was thinking.

And no one knew that from this day forward, someone would try to make the whole world know.