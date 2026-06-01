# Prompt_Engineering_Portfolio_Assignment

# Prompt Engineering Portfolio
Name: [Swetha Priya, Brahmanla Palli]
Date: [June 4th, 2026]
LLM Used: [ChatGPT-4, Claude 3.5 Sonnet]

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation
Goal: Explain a complex technical concept(Neural Networks) to a 10-year-old
Initial Prompt(V1): Explain about Neural Networks
Initial Summary(V1): High level of explanation defficult for 10 year old to understand.
Refined Prompt(V2): Explain about Neural Networks to 10 year old kid.
Refined Summary(V2): Provided explanation easier for 10 year old to understand at a better level.
Final Prompt (V3): I'm 10 year old trying to know about Neural Networks. Give me one simple example for better understanding.
Final Output(V3): 
Imagine your brain has millions of tiny switches. When you learn something new, those switches turn on and off to remember it. A neural network works the same way — but inside a computer. It is a Computer system that learns from examples — just like how we do. Instead of someone programming every rule, the computer figures things out by practicing itself millions of times. Neural Networks are a type of artificial intelligence model inspired by how the human brain processes information.

For example think of it like this:
Imagine you're teaching a child to recognize cats and dogs. At first, they make mistakes. But after seeing many examples, they start noticing patterns:
Cats often have pointy ears.
Dogs may have longer snouts.
Different sizes, fur colors, and shapes help identify them.

A neural network learns in a similar way. It looks at many examples and gradually learns patterns that help it make predictions.


### 1.1 Scenario B: Professional Email
Goal: Draft an email declining job offer poiletly while expressing continued intrest in company
Initail Prompt(V1): Write an email declining a job offer
Output Summary(V1): Eamil declines offer but lacks Professionalism.
Refined Prompt(V2): Write professional email declining job offer polietly with positive tone.
Output Summary(V2): Email is professional but it does not explain the reason and lacks to include intrest in future opportunities.
Final Prompt(V3): You are a professional Advisor. Draft a professional email declining a job offer because I accepted another  opportunity. Thank hiring team for their time and consideration and include that I would like to stay connected for future opportunities.
Final Output(V3): 
Dear [Hiring Manager's Name],

Thank you sincerely for offering me the [Job Title] position at [Company Name]. I deeply appreciate the time and thoughtfulness you and your team invested throughout the entire interview process.
After careful consideration, I have made the difficult decision to decline the offer, as I have accepted another opportunity. This was by no means an easy decision — I have tremendous respect for [Company Name] and the incredible work your team is doing.
I would very much like to stay connected for potential future opportunities. I have no doubt that our paths may cross again, and I would welcome that possibility greatly. I'll be sure to connect with you on LinkedIn.
Thank you once more for your time, your generosity, and your confidence in me. I wish you and the entire team continued success.

Warm regards,
[Your Full Name]
[LinkedIn Profile URL]
[Phone Number]

### 1.1 Scenario C: Creative Content
Goal:Generate a creative marketing tagline for a new eco friendly waterbottle brand
Initial Prompt(V1):Generate tagline for water bottle brand
Output Summary(V1):The tagline was generic and did not highlight any unique features of the brand.
Refined Prompt(V2):Generate tagline for ecofriendly water bottle brand
Output Summary(V2):The tagline included environmental benefits but was still somewhat broad and lacked creativity.
Final Prompt(V3):I'm planning to startup a water bottle company. Generate tagline for an eco friendly water bottle brand. Be creative and make sure to include eco friendly feature.
Final Output(V3)
 - Hydrate Today, Protect Tomorrow.
 - Every Refill Saves a Little More Earth.
 - Pure Water. Cleaner Planet.
 - Drink Green. Live Clean.
 - One Bottle, Endless Refills, Less Waste.


### 1.2 Iteration Documentation
### Scenario A:
| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|--------------|-----------------------------|
| V1 | Explain about Neural Networks | N/A | N/A |
| V2 | Explain about Neural Networks to 10 year old| Made it simple | Provided explanation easier for 10 year old to understand at a better level|
| V3 | I'm 10 year old trying to know about Neural Networks. Give me one simple example for better understanding | Added analogy and age-specific language. | Produced more simple, clear and engaging explanation with an example |

### Scenario B:
| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|--------------|-----------------------------|
| V1 | Write an email declinign job offer | N/A | N/A |
| V2 | Write Professional email declining a job offer polietly with a positive tone
 | Added gratitude and tone requirements in a professional way| Providied Respectful and polite email|
| V3 | You are a professional advisor. Draft a professioanl email declining job offer because I accepted another opportunity. Thank Hiring team for their time and consideration and include that I would like to stay connected for future opportunities. | Added role assignment, context, reason for declining and included future intrest.| Generated high professional response expressing gratitude for hiring team including intrest in future opportunities.|

### Scenario C:
| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|--------------|-----------------------------|
| V1 | Generate tagline for water bottle brand | N/A | N/A |
| V2 | Generate tagline for ecofriendly water bottle brand | Added the eco-friendly feature to the prompt.| Helped generate taglines that emphasized sustainability and environmental benefits rather than generic water bottle slogans.|
| V3 | I'm planning to startup a water bottle company. Generate tagline for an eco friendly water bottle brand. Be creative and make sure to include eco friendly feature. | Added business context, creativity requirement, and specific brand values (sustainability, reusability, environmental responsibility).| Produced more targeted, memorable, and marketable taglines that clearly communicate the brand's eco-friendly mission and appeal to environmentally conscious customers.


### 1.3 Role and Context Analysis
Role Explanation and Context settings were used in all of the above three scenarios which has significantly improved the quality and the content in the generated output.

In Scenario A, when we asked about neural networks, the initial response from the LLM was high-level and difficult for a 10-year-old to understand. However, after refining the prompt to include a clear role and context (explaining for a 10-year-old with examples), the response became much simpler and easier to understand. The explanation also included relatable examples that made the concept more clearer. This shows that adding role assignment and context significantly improves the quality and relevance of LLM outputs by tailoring them to the intended audience.

In Scenario B, using the role of a professional career advisor helped create a polished email. Adding interest in future opportunities showed professionalism and maintained a positive relationship with the company.

In Scenario C, assigning the role of a marketing and providing startup context resulted in providing more creative and relevant eco-friendly taglines. It improved the quality by making the output focusing more on branding with ecofriendly feature.

Addinga role in the prompt tells AI who you are and what you are trying to accomplish at what level.It shapes the tone, vovabulary and style without needing to spell out more details.
Adding context in the prompt tells AI about the specific situation. This prompts the LLM to generate a tailored and revelant information rather than a generic details. 
Both role and context work like a creative instructions - which replaces random details with clear persona and scenarion based information. This helps generate more relevant and appropriate responce. 


## Part 2: Temperature & Parameter Control
### 2.1 Temperature Experimentation
Task opted: Writing Product description for a laptop

###  Temperature 0.2 — Low (Precise & Consistent)
Prompt Given: Write a product description for a high-performance laptop aiming college students. Be precise and consistent with the details.
Output Response: The ProBook X15 is a high-performance laptop built for college students. It features an Intel Core i7 processor, 16GB DDR5 RAM, and a 512GB NVMe SSD for fast, reliable performance. The 15.6-inch Full HD anti-glare display delivers sharp visuals for studying and creative work. A 72Wh battery provides up to 12 hours of use on a single charge. Weighing 3.8 lbs and measuring 0.71 inches thin, it is easy to carry between classes. Wi-Fi 6E, Bluetooth 5.3, and a full port selection including Thunderbolt 4 and HDMI 2.1 ensure seamless connectivity. Priced at $999, the ProBook X15 is a dependable, practical choice for four years of college.

### Temperature 0.7 — Medium (Balanced)
Prompt Given: Write a product description for a high-performance laptop aiming college students.
Output Response: Meet the laptop that was made for your college years. The ProBook X15 combines serious horsepower with an all-day battery and a design slim enough to slip into any backpack. Powered by an Intel Core i7 and 16GB of RAM, it breezes through coding assignments, design projects, and a hundred open browser tabs without breaking a sweat. The crisp 15.6-inch Full HD display makes everything from lecture slides to late-night Netflix look amazing. At 3.8 lbs with a 12-hour battery, you'll forget you're even carrying it — until you need it most. The ProBook X15 isn't just a laptop. It's your most reliable study partner for the next four years.

### Temperature 1.4 — High (Creative & Unpredictable)
Prompt Given: Write a product description for a high-performance laptop aiming college students. Be creative and explore diverse ideas.
Output Response: Your dorm room has seen a lot. Empty pizza boxes. Highlighter-stained notes. Three alarms you slept through. But the ProBook X15? That stays. Thin as your patience before finals, powerful as your third espresso shot, and stubborn enough to outlast every all-nighter you throw at it. An Intel Core i7 hums quietly beneath a military-grade shell — ready for your design thesis, your startup pitch deck, your 47-tab research spiral at 2am. The battery doesn't quit. The display doesn't lie. And unlike your last group project partner, it always shows up. Welcome to the laptop that actually gets college.


### Comparison Table:

| Feature | Low (0.2) | Medium (0.7) | High (1.4) |
|---|---|---|---|
| **Tone** | Neutral, factual | Friendly, engaging | Witty, bold, humorous |
| **Creativity** | Minimal | Moderate | Very high |
| **Spec accuracy** | Exact — all specs cited | Moderate — key specs included | Loose — specs mentioned casually |
| **Structure** | Straightforward sentences | Flowing narrative | Punchy, fragmented, story-driven |
| **Predictability** | Very consistent | Mostly consistent | Surprising and unpredictable |
| **Best use case** | Tech spec sheets, retailer pages | General marketing copy | Social media ads, brand campaigns |

### When to use Low Temperature: Detailed Description
1. When preparing Technical specification Documents — 
Example: When writing exact product specifications like processor speed, RAM, and battery life where every detail must be precise and consistent.
2. When preparing patient Medical details
Example: When accuracy is critical and even a small factual error could have serious consequences.

### When to use High Temperature:During Social Media ads, brand campaigns
1. Advertising campaigns
Example: When brainstorming bold, unexpected taglines and creative angles that grab attention and stand out from competitors.
2. Creative fiction writing 
Example:Story telling, Keep engaging content,completely unpredictable situations. Like opening a fantasy or thriller novel.

### 2.2 Analysis & Recommendations
### Which temperature worked best for the laptop task:

Medium temperature (0.7) worked best for the laptop product description.
It has balanced factual accuracy with a warm and engaging tone that felt natural and realistic.
The low temperature output was too dry and simple like a plain spec sheet — lacking personality to connect with college students.
The high temperature output was entertaining but facts were too loosely described whicg is defficult to be trusted as reliable product information.
Conclusion: Medium temperature hit the sweet spot — informative enough to be useful, compelling enough to sell.



## Part 3: Strategic Prompting Techniques
### 3.1 Chain-of-Thought Prompting
### 3.2 Few-Shot Prompting

## Part 4: Responsible AI & Limitations
### 4.1 Testing for Hallucinations
### 4.2 Testing for Bias
### 4.3 Limitations & Responsible Use
