# Clueminati - Medium Questions

## Question 1: 

In a grim dystopian future, three prisoners are lined up, each shackled and doomed to wear a hat—either black or white. The harsh regime forces them into a deadly game of chance. Each prisoner can see the hats of those in front but remains blind to their own and those behind. The prisoners are given a chance to escape, but only if they correctly guess the color of their own hat. The prisoner at the back, who can see the other two, must guess first. The second prisoner, who can see only the one in front, guesses next. Finally, the prisoner at the front, who sees no one, must make their guess. In this high-stakes scenario, how can they strategize to maximize their odds of escaping the oppressive regime?

**Answer:** They use a parity-based strategy where the third prisoner announces the color based on the parity (even or odd) of the number of white hats he sees, allowing the subsequent prisoners to deduce their own hat colors.

**Explanation:**

- **Third Prisoner (Back):**
  - Counts the number of white hats he sees on the prisoners ahead.
  - If the number of white hats is **even**, he says "white".
  - If the number is **odd**, he says "black".

- **Second Prisoner (Middle):**
  - Hears the third prisoner's announcement.
  - Sees the hat of the first prisoner.
  - Using the parity information and what he sees, he deduces his own hat color.
    - If the third prisoner said "white" and the second prisoner sees a white hat ahead, he knows he must be wearing a white hat to maintain even parity.
    - If the third prisoner said "black" and he sees a white hat, he knows his hat is black.

- **First Prisoner (Front):**
  - Hears previous answers.
  - Uses the information to deduce his own hat color.
    - If both prisoners behind didn't correctly identify their hats immediately, he can infer his hat color.

This strategy maximizes their chances, ensuring at least one prisoner can correctly guess their hat, leading to their escape.

---

## Question 2: 

First think of the person who lives in disguise,  
Who deals in secrets and tells naught but lies,  
Next tell me what’s always the last thing to mend,  
The middle of middle and end of the end?  
And finally give me the sound often heard,  
During the search for a hard-to-find word.  
Now string them together, and answer me this,  
Which creature would you be unwilling to kiss?

**Answer:** **Spider**

**Explanation:**

- **First Clue:** "The person who lives in disguise, who deals in secrets and tells naught but lies."
  - **Spy**

- **Second Clue:** "What's always the last thing to mend, the middle of middle and end of the end?"
  - The letter **D** (middle of "middle" is "d", end of "end" is "d")

- **Third Clue:** "The sound often heard during the search for a hard-to-find word."
  - The sound **"er"** (the utterance "er" when thinking)

- **String Together:** **Spy** + **D** + **Er** = **Spyder**

- **Creature:** **Spider**

---

## Question 3: 

There are 10 sets of 10 coins. You know how much the coins should weigh. You know all the coins in one set of ten are exactly a hundredth of an ounce off, making the entire set of ten coins a tenth of an ounce off. You also know that all the other coins weigh the correct amount. You are allowed to use an extremely accurate digital weighing machine only once.

How do you determine which set of 10 coins is faulty?

**Answer:** Weigh a specific number of coins from each set corresponding to their set number and determine the faulty set based on the total weight difference.

**Explanation:**

- **Procedure:**
  - Label the sets from 1 to 10.
  - Take:
    - 1 coin from **Set 1**,
    - 2 coins from **Set 2**,
    - ...
    - 10 coins from **Set 10**.
  - Place all these coins on the scale at once.

- **Calculation:**
  - Calculate the **expected total weight** if all coins were perfect.
  - If the weight is less (or more) than expected, the difference indicates the faulty set.
    - For example, if the weight is off by 0.03 ounces, then **Set 3** is faulty.

- **Conclusion:**
  - Since each coin in the faulty set is off by 0.01 ounces, the total difference corresponds to the set number.

---

## Question 4: 

"In a forgotten journal, you find a cryptic message: ‘When the shadow of the Earth painted the moon red, two travellers took a leap into the unknown. One took a "small step" that echoed across time, while the other carried the name of a guardian of the cosmos, destined to reach 'beyond the stars.' Find the tale where the guardian's name lives on, immortalized as a fearless voyager to the infinite. Which story does he belong to?"

**Answer:** **Toy Story**

**Explanation:**

- **"Small step" Traveller:**
  - **Neil Armstrong**—first man on the moon, said "That's one small step for man..."

- **"Guardian of the cosmos":**
  - **Buzz Aldrin**—second man on the moon.
  - His name inspired **Buzz Lightyear**, a character in **Toy Story**.

- **Conclusion:**
  - The tale where Buzz Lightyear belongs is **Toy Story**.

---

## Question 5: 

"Named after a bird often found in North America but incorrectly associated with its native country, this bird shares its name with a nation famed for its unique position straddling two continents. Within this country lies a city historically known as Byzantium and later as Constantinople, renowned for its stunning architecture and cultural significance. In the grand tapestry of football history, a legendary match is remembered for its miraculous turn of events. The setting was the aforementioned city known for its historic conquests and dramatic comebacks. During this unforgettable game, a team defied the odds in a match forever etched in the annals of football history. The leader of this miraculous comeback, often hailed as a prince of the pitch, is celebrated for his heroic efforts that inspired and guided his team to triumph."

**Answer:** **Steven Gerrard**

**Explanation:**

- **Bird and Country:**
  - **Turkey**—a bird native to North America, shares its name with the country **Turkey**.

- **City:**
  - **Istanbul**—formerly Byzantium and Constantinople.

- **Historic Match:**
  - **The Miracle of Istanbul**—2005 UEFA Champions League Final.
  - **Liverpool FC** came back from 0-3 to win.

- **Leader:**
  - **Steven Gerrard**—captain of Liverpool, key in the comeback.

---

## Question 6: 

### Survival Challenge: Crossing the Bridge

In a world ravaged by chaos, four survivors must navigate a treacherous, crumbling bridge under the cover of darkness. They possess only one flickering flashlight, a crucial tool for ensuring their safety. The bridge is unstable and too dangerous to traverse without it.

They must cross in pairs, and only the slower of the two determines the crossing time. Their individual crossing times are:

- **Survivor 1:** 1 minute
- **Survivor 2:** 2 minutes
- **Survivor 3:** 5 minutes
- **Survivor 4:** 10 minutes

**Objective:** Get all four survivors across the bridge safely in **17 minutes** or less.

**Answer:**

1. **Survivor 1 and Survivor 2** cross. (Time: 2 minutes)
2. **Survivor 1** returns with the flashlight. (Time: 1 minute)
   - **Total Time:** 3 minutes
3. **Survivor 3 and Survivor 4** cross. (Time: 10 minutes)
4. **Survivor 2** returns with the flashlight. (Time: 2 minutes)
   - **Total Time:** 15 minutes
5. **Survivor 1 and Survivor 2** cross again. (Time: 2 minutes)
   - **Total Time:** 17 minutes

**Explanation:**

- **Strategy:**
  - Use the fastest survivors to minimize return times.
  - Ensure the two slowest survivors cross together.

- **Result:**
  - All survivors cross safely within the 17-minute limit.

---

## Question 7: 

"In the midst of the deadliest conflict the world has ever seen, a battle was not only waged on the front lines but also in the shadows—where secrets were concealed within ciphers and encrypted codes. Amidst this invisible war, a genius emerged whose intellect and determination would unravel the mysteries hidden within an 'unbreakable' machine, shifting the course of history. With nothing but his brilliance and a primitive computing device, he led a team that cracked the code once thought to be impenetrable, turning the tide of a global struggle. Who was this visionary codebreaker, and what was the name of the machine he created?"

**Answer:** **Alan Turing**; the machine he created was the **Bombe**

**Explanation:**

- **Codebreaker:** **Alan Turing**

- **Machine Created:** **Bombe**
  - Designed to decrypt messages from the **Enigma Machine** used by Nazi Germany.

- **Impact:**
  - His work significantly shortened World War II.
  - Laid the foundations for modern computing.

---

## Question 8: 

"A famous riddle involves a farmer who needs to transport a fox, a chicken, and a bag of grain across a river but can only take one at a time without the others eating each other. The logic puzzle finds its roots in a civilization home to one of the ancient world's greatest libraries. What city housed this legendary library?"

**Answer:** **Alexandria**

**Explanation:**

- **Riddle Origin:** The fox, chicken, and grain puzzle is a classic logic problem.

- **Civilization:** Ancient Egypt.

- **Library:** **The Library of Alexandria**

- **City:** **Alexandria**

---

## Question 9: 

In a world where balance is the key to survival, you stand in the ruins of a once-thriving city, now shadowed in gray. The last 12 identical spheres, relics of a forgotten past, lie before you. One of these spheres holds a secret—it is slightly heavier or lighter than the rest, and the imbalance threatens the fragile remnants of order.

You have only three chances to weigh them on an ancient balance scale, and failure to find the anomaly could tip the world further into chaos. To identify the heavier or lighter sphere, how many groups will you divide the spheres into?

**Answer:** Divide the 12 spheres into **three groups of 4 spheres each**.

**Explanation:**

- **Strategy:**
  - By dividing into **three groups of 4**, you can systematically compare them using the balance scale.
  - This method allows you to identify the odd sphere and determine if it's heavier or lighter within **three weighings**.

- **Reasoning:**
  - Dividing into other group sizes would not be efficient for solving within the limited weighings.

---

## Question 10: 

In the shattered remains of civilization, you stand before the last challenge, tasked with finding the final bunker—the one holding the vital supplies needed for survival. A coded sequence is all that guides you, left behind by those who once held the knowledge:

`(10,2), (9,3), (8,5), (7,7), (6,11), (5,13), (4,17), …`

What are the coordinates of the `(0, y)`?

**Answer:** **(0,31)**

**Explanation:**

- **X-Values:**
  - Decreasing by 1: 10, 9, 8, 7, 6, 5, 4, 3, 2, 1, 0

- **Y-Values:**
  - Sequence of prime numbers starting from the 2nd prime:
    - 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, **31**

- **Conclusion:**
  - When **x = 0**, **y = 31**

---

## Question 11: 

In the remnants of a shattered world, you stumble upon an ancient chest, encrusted with the grime of ages. Its once-glorious exterior hints at the power it conceals. The power to bring back colour: Answer the following riddle:

“In the heart of the city, I’m often found,  
A symbol of life, in a circular mound,  
I’m broken yet whole, in a paradox of fate,  
A staple of life yet often left to wait.”

**Answer:** **Bread**

**Explanation:**

- **"Heart of the city":** Bakeries are often central hubs.

- **"Symbol of life, in a circular mound":** Bread symbolizes sustenance; loaves can be round.

- **"Broken yet whole":** Bread is broken to eat but represents unity.

- **"Staple of life yet often left to wait":** Bread is a basic food but can be left uneaten.

---

## Question 12: 

In the remnants of a shattered world, you stumble upon an ancient chest, encrusted with the grime of ages. Its once-glorious exterior hints at the power it conceals. The power to bring back colour: Answer the following riddle:

“I am born in the mind, but live in the heart,  
You may chase me forever, though never depart.  
I am both truth and illusion, part joy and part pain,  
Though I dance in the light, I am born in the rain.”

**Answer:** **A Dream**

**Explanation:**

- **"Born in the mind, but live in the heart":** Dreams originate mentally but affect us emotionally.

- **"You may chase me forever, though never depart":** Pursuing dreams without leaving one's place.

- **"Both truth and illusion, part joy and part pain":** Dreams can be realistic or fantastical, bringing mixed emotions.

- **"Dance in the light, born in the rain":** Hope arising after hardship.

---

## Question 13: 

In a post-war world stripped of colour, four upturned cups sit on a counter. These cups, stripped of any hue, hold the final fragments of sweetness in a universe devoid of joy. All the cups have the same number of sweets and all of them have an inscription etched into the surface. However only one holds true. The inscriptions on the cups read:

1. **"Five or Six"**
2. **"Seven or Eight"**
3. **"Six or Seven"**
4. **"Seven or Five"**

How many sweets are under each cup?

**Answer:** **8**

**Explanation:**

- **Possible Numbers:** 5, 6, 7, 8

- **Testing Number 8:**
  - Cup 1: "Five or Six" — **False**
  - Cup 2: "Seven or Eight" — **True**
  - Cup 3: "Six or Seven" — **False**
  - Cup 4: "Seven or Five" — **False**

- **Conclusion:**
  - Only one inscription is true (Cup 2).
  - Therefore, there are **8 sweets** under each cup.

---

## Question 14: 
"This ancient city, renowned for its grand architecture and as the heart of a powerful empire, is home to a famous structure that once served as the center of public spectacles and political gatherings. This city is often associated with an enormous amphitheater, also known as the Colosseum. Identify this city. From the city you identified, a famous leader known for his military conquests and pivotal role in the expansion of the Roman Empire is often referred to by his given name. He was famously assassinated on the Ides of March. Who is this leader?"

**Answer:** **Julius Caesar**

**Explanation:**

- **City:** **Rome**

- **Structure:** **The Colosseum**

- **Leader:** **Julius Caesar**

- **Notable Event:** Assassinated on the **Ides of March** (March 15).

---

## Question 15: 

In a dystopian world, a rebellion hides its plans within a sequence of colors encoded as hexadecimal values. Each color is converted to RGB format, and the sum of its digits reveals a clue. But there's a catch: some colors use a shifting cipher where each digit in the hex code is shifted forward by its index position (0-based). The intercepted message is: **#3A5F2C**, **#2E4B7D**, **#F1A8E3**.

Decrypt the message by reversing the cipher and find the sum of the RGB digits for each color.

**Answer:**

- **First Color:**

  - **Original Hex:** #3A5F2C
  - **Shifted Back:** #393CE7
  - **RGB Values:** 57, 60, 231
  - **Sum:** **348**

- **Second Color:**

  - **Original Hex:** #2E4B7D
  - **Shifted Back:** #2D2838
  - **RGB Values:** 45, 40, 56
  - **Sum:** **141**

- **Third Color:**

  - **Original Hex:** #F1A8E3
  - **Shifted Back:** #F085AE
  - **RGB Values:** 240, 133, 174
  - **Sum:** **547**

**Explanation:**

- **Cipher Reversal:**
  - Each digit in the hex code is shifted back by its index position.

- **Conversion:**
  - After shifting, convert hex to decimal RGB values.

- **Sum Calculation:**
  - Add the decimal RGB values to find the sums.

---

## Question 16: 

In a dystopian prison, inmates are forced to wear colored bracelets that determine the amount of food they are allocated each day. The bracelet color changes based on their behavior the previous day:

- **Red:** Inmate receives **1** portion of food.
- **Blue:** Inmate receives **2** portions of food.
- **Yellow:** Inmate receives **3** portions of food.

**Rules:**

- Silent all day → Bracelet turns **Red**.
- Speaks but doesn’t argue → Bracelet turns **Blue**.
- Argues with a guard → Bracelet turns **Yellow**.
- After **three consecutive days** of wearing a **Red** bracelet, inmate is denied food.

An inmate follows this pattern over 14 days:

- **Speak → Argue → Silent → Argue → Silent → Silent → Argue → Argue → Speak → Silent → Silent → Silent → Speak → Speak**

How many portions of food does the inmate receive by the end of the fourteenth day?

**Answer:** **24**

**Explanation:**

| Day | Behavior | Bracelet Next Day | Portions Received |
|-----|----------|-------------------|-------------------|
| 1   | Speak    | Blue              | 2                 |
| 2   | Argue    | Yellow            | 3                 |
| 3   | Silent   | Red               | 1                 |
| 4   | Argue    | Yellow            | 3                 |
| 5   | Silent   | Red               | 1                 |
| 6   | Silent   | Red               | 1                 |
| 7   | Argue    | Yellow            | 3                 |
| 8   | Argue    | Yellow            | 3                 |
| 9   | Speak    | Blue              | 2                 |
| 10  | Silent   | Red               | 1                 |
| 11  | Silent   | Red               | 1                 |
| 12  | Silent   | Red               | **0** (No food)   |
| 13  | Speak    | Blue              | 2                 |
| 14  | Speak    | Blue              | 2                 |

- **Total Portions:** 2 + 3 + 1 + 3 + 1 + 1 + 3 + 3 + 2 + 1 + 1 + 0 + 2 + 2 = **24**

---

## Question 17: 

“In a world stripped of color, shadows reign,  
War has left everything dull and plain.  
In their hair, a secret they hide,  
A glimmer of hope, concealed with pride.

What do they carry in this bleak affair?  
To hold onto hope in a world laid bare?”

**Answer:** **Rice**

**Explanation:**

- **Historical Reference:**
  - Enslaved Africans hid **rice** in their hair during the transatlantic slave trade.

- **Symbolism:**
  - Rice represented hope and survival.
  - It was a means to ensure sustenance in an uncertain future.

- **Connection to Riddle:**
  - "In their hair, a secret they hide" refers to hiding rice grains.
  - "A glimmer of hope, concealed with pride" emphasizes the importance.

---

