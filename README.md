flowchart TD
  0[Quest Dialogue Tree >>]

  A[Start: Speak to Thais] --> B["Thais: 'Ah, a kind and intelligent traveler approaches! Your aura is simply magnificent—almost as magnificent as mine, of course.'"]
  B --> C["Thais: 'Alas, even a goddess such as myself has suffered injustice!'"]
  C --> D["Thais: 'I have been cursed, doomed to wallow in filth for my… ahem… unparalleled talents in flattery.'"]
  D --> E["Thais: 'Only a mirror can restore balance! I must gaze upon my own perfection, for I fear my beauty has been tarnished by this wretched grime.'"]
  E --> F["Thais: 'Will you retrieve one for me, dear champion of elegance?'"]

  F --> G["Player: 'Of course, O radiant one.'"] 
  F --> H["Player: 'Get your own mirror, you self-absorbed grease stain.'"]
  F --> I["Player: 'Actually, I think my beauty outshines yours. Maybe I should be the one with a mirror.'"]

  G --> J["Thais: 'Ah! A fellow appreciator of true beauty! I knew you had taste!'"]
  H --> K["Thais: 'Hmph! Jealousy is so unbecoming. Not everyone can handle basking in my presence.'"]
  K --> L["Thais: 'Go on, scurry away like the peasants who shunned me!'"]
  L --> M[QUEST DECLINED]

  I --> N["Thais: 'Oh? Oh! A challenger! How bold!'"]
  N --> O["Thais: 'But alas, you are *tragically* mistaken. Very well, bring me a mirror, and we shall settle this once and for all!'"]
  O --> P["Thais: 'Prepare to witness your own defeat… in dazzling reflection!'"]
  
  J --> Q["QUEST ACCEPTED"]
  O --> Q

  Q --> R["(There's a lingering question inside your mind.)"]
  R --> S["Player: 'Where exactly am I supposed to find this mirror?'"]
  R --> T["Player: 'How did you even end up like this?'"]

  S --> U["Thais: (Scoffs) 'Do I look like someone who *finds* things? No, no, no—that’s your job.'"]
  U --> V["Thais: 'I am merely the dazzling beacon of grace in this arrangement.'"]
  V --> W["Player: '...'"]
  W --> X["(Ignoring her remarks, you decide to check with merchants. They hoard random junk, right?)"]

  T --> Y["Thais: 'Ah, an inquisitive mind! A rare trait in one so... rugged.'"]
  Y --> Z["Thais: 'You see, I once lavished praise upon a wizard’s mustache.'"]
  Z --> AA["Thais: 'A mustache so grand, so powerful, so exquisitely groomed!'"]
  AA --> AB["Thais: 'But alas! I praised it *one* too many times… and he cursed me for it.'"]
  AB --> AC["Thais: 'Now, my magnificence is hidden beneath this *vile, wretched, unspeakable* filth!'"]
  AC --> AD["Thais: 'So tragic… So cruel… So—'"]
  AD --> AE["Player: '...Yeah, I think I get it.'"]
  AE --> AF["Thais: 'Anyway, stop wasting time and get me my mirror! Chop chop!'"]
  AF --> R

  X --> AG["Speak to Thais again"]
  AG --> AH["Without the mirror"]
  AG --> AI["With the mirror in hand"]

  AH --> AJ["Thais: 'Ah, you return! With a mirror, I presume?'"]
  AJ --> AK["Player: 'Not yet.'"]
  AK --> AL["Thais: 'Tragic. Devastating. A true betrayal of beauty itself.'"]
  AL --> AM["Thais: 'Do not tarry too long, hero! Every moment without my reflection is agony!'"]
  AM --> AN["Thais: 'A masterpiece such as I must be admired—especially by myself!'"]
  AN --> W

  AI --> AO["Thais: 'At last! The instrument of my redemption!'"]
  AO --> AP["Thais: 'Quickly, hand it over! I must gaze upon my own splendor!'"]
  AP --> AQ["(She snatches the mirror and dramatically holds it up to her face.)"]

  AQ --> AR["Thais: (Gasp) 'Oh no… I’m beautiful!'"]
  AR --> AS["Thais: 'This whole time I thought I was doomed to be hideous!'"]
  AS --> AT["Thais: 'I was just covered in mud!'"]
  AT --> AU["Thais: (Sniffles) 'It was so tragic. But also inspiring. The courage I showed… the resilience…'"]
  AU --> AV["Thais: 'I truly am a marvel!'"]

  AV --> AW["Thais: 'As a reward, I grant you something far more valuable than gold—'"]
  AW --> AX["Thais: 'My sincerest flattery.'"]

  AX --> AY["Player: '...That's it? No actual reward?'"]
  AY --> AZ["Thais: 'Oh, darling, words from lips as divine as mine are worth more than any treasure.'"]
  AZ --> BA["(She tosses her hair dramatically—right as the mirror emits a dazzling light.)"]
  BA --> BB["(In a sudden flash, she vanishes, leaving the mirror behind.)"]
  BB --> BC["(...The silence lingers. You blink. You definitely did not expect that.)"]
  BC --> BD["(You glance at the mirror she left behind.)"]
  BD --> BE["Player: 'Wait—what if it's a bomb?!'"]
  BE --> BF["(You hesitate... but then flip it over.)"]
  BF --> BG["(There's something written on the back: 'Made by Re-Logic'.)"]
  BG --> BH["Player: '...Huh.' (You pocket the mirror and walk away.)"]
  BH --> BI[QUEST COMPLETE]
