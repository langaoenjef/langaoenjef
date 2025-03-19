flowchart TD
  0[Quest Dialogue Tree >>]

  A[Start: Speak to Thais] --> B["Thais: 'Ah, a kind and intelligent traveler approaches! Your aura is simply magnificent—almost as magnificent as mine, of course.'"]
  B --> C["Thais: 'Alas, even a goddess such as myself has suffered injustice!'"]
  C --> D["Thais: 'I have been cursed, doomed to wallow in filth for my… ahem… unparalleled talents in flattery.'"]
  D --> E["Thais: 'Only a mirror can restore balance! I must gaze upon my own perfection, for I fear my beauty has been tarnished by this wretched grime.'"]
  E --> F["Thais: 'Will you retrieve one for me, dear champion of elegance?'"]

  F --> G["Player: 'Of course, O radiant one.'"] 
  F --> H["Player: 'Get your own mirror, you self-absorbed grease stain.'"]

  G --> I["Thais: 'Ah! A fellow appreciator of true beauty! I knew you had taste!'"]
  H --> J["Thais: 'Hmph! Jealousy is so unbecoming. Not everyone can handle basking in my presence.'"]
  J --> K["Thais: 'Go on, scurry away like the peasants who shunned me!'"]
  K --> L[QUEST DECLINED]

  I --> M["QUEST ACCEPTED"]
  M --> N["(There's a lingering question inside your mind.)"]
  N --> O["Player: 'Where exactly am I supposed to find this mirror?'"]
  N --> P["Player: 'How did you even end up like this?'"]

  O --> Q["Thais: (Scoffs) 'Do I look like someone who *finds* things? No, no, no—that’s your job.'"]
  Q --> R["Thais: 'I am merely the dazzling beacon of grace in this arrangement.'"]
  R --> S["Player: '...'"]
  S --> T["(Ignoring her remarks, you decide to check with merchants. They hoard random junk, right?)"]

  P --> V["Thais: 'Ah, an inquisitive mind! A rare trait in one so... rugged.'"]
  V --> W["Thais: 'You see, I once lavished praise upon a wizard’s mustache.'"]
  W --> X["Thais: 'A mustache so grand, so powerful, so exquisitely groomed!'"]
  X --> Y["Thais: 'But alas! I praised it *one* too many times… and he cursed me for it.'"]
  Y --> Z["Thais: 'Now, my magnificence is hidden beneath this *vile, wretched, unspeakable* filth!'"]
  Z --> AA["Thais: 'So tragic… So cruel… So—'"]
  AA --> AB["Player: '...Yeah, I think I get it.'"]
  AB --> AC["Thais: 'Anyway, stop wasting time and get me my mirror! Chop chop!'"]
  AC --> N

  T --> AD["Speak to Thais again"]
  AD --> AE["Without the mirror"]
  AD --> AF["With the mirror in hand"]

  AE --> AG["Thais: 'Ah, you return! With a mirror, I presume?'"]
  AG --> AH["Player: 'Not yet.'"]
  AH --> AI["Thais: 'Tragic. Devastating. A true betrayal of beauty itself.'"]
  AI --> AJ["Thais: 'Do not tarry too long, hero! Every moment without my reflection is agony!'"]
  AJ --> AK["Thais: 'A masterpiece such as I must be admired—especially by myself!'"]
  AK --> S

  AF --> AL["Thais: 'At last! The instrument of my redemption!'"]
  AL --> AM["Thais: 'Quickly, hand it over! I must gaze upon my own splendor!'"]
  AM --> AN["(She snatches the mirror and dramatically holds it up to her face.)"]

  AN --> AO["Thais: (Gasp) 'Oh no… I’m beautiful!'"]
  AO --> AP["Thais: 'This whole time I thought I was doomed to be hideous!'"]
  AP --> AQ["Thais: 'I was just covered in mud!'"]
  AQ --> AR["Thais: (Sniffles) 'It was so tragic. But also inspiring. The courage I showed… the resilience…'"]
  AR --> AS["Thais: 'I truly am a marvel!'"]

  AS --> AT["Thais: 'As a reward, I grant you something far more valuable than gold—'"]
  AT --> AU["Thais: 'My sincerest flattery.'"]

  AU --> AV["Player: '...That's it? No actual reward?'"]
  AV --> AW["Thais: 'Oh, darling, words from lips as divine as mine are worth more than any treasure.'"]
  AW --> AX["(She tosses her hair dramatically—right as the mirror emits a dazzling light.)"]
  AX --> AY["(In a sudden flash, she vanishes, leaving the mirror behind.)"]
  AY --> AZ["(...The silence lingers. You blink. You definitely did not expect that.)"]
  AZ --> BA["(You glance at the mirror she left behind.)"]
  BA --> BB["(There's something written on the back: 'Made by Re-Logic'.)"]
  BB --> BC["Player: '...Huh.' (You pocket the mirror and walk away.)"]
  BC --> BD[QUEST COMPLETE]
