```mermaid
flowchart TD
  0[Quest Dialogue Tree >>]

  %% --- INITIAL QUEST DIALOGUE --- %%
  A[Start: Speak to Thais] --> B["Thais: 'Ah, a kind and intelligent traveler approaches! Your aura is simply magnificent—almost as magnificent as mine, of course.'"]
  B --> C["Thais: 'Alas, even a goddess such as myself has suffered injustice!'"]
  C --> D["Thais: 'I have been cursed, doomed to wallow in filth for my… ahem… unparalleled talents in flattery.'"]
  D --> E["Thais: 'Only a mirror can restore balance! I must gaze upon my own perfection, for I fear my beauty has been tarnished by this wretched grime.'"]
  E --> F["Thais: 'Will you retrieve one for me, dear champion of elegance?'"]

  %% --- ACCEPT OR DECLINE QUEST --- %%
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
  
  P --> Q["QUEST ACCEPTED"]

  %% --- ASKING ABOUT THE MIRROR --- %%
  Q --> R["(There's a lingering question inside your mind.)"]
  R --> S["Player: 'Where exactly am I supposed to find this mirror?'"]
  R --> T["Player: 'Wouldn’t a puddle work just fine?'"]

  S --> U["Thais: (Scoffs) 'Do I look like someone who *finds* things? No, no, no—that’s your job.'"]
  U --> V["Thais: 'I am merely the dazzling beacon of grace in this arrangement.'"]
  V --> W["Player: '...'"]
  W --> X["(Ignoring her remarks, you decide to check with merchants. They hoard random junk, right?)"]

  T --> Y["Thais: (GASPS) 'Are you seriously suggesting I admire myself in a *PUDDLE*?!'"]
  Y --> Z["Thais: 'The *horror*! The *indignity*! The absolute *nerve* of you!'"]
  Z --> AA["(She dramatically faints. You walk away while she recovers.)"]
  AA --> X

  %% --- ASKING ABOUT HER CURSE (FIRST) --- %%
  R --> AB["Player: 'How did you even end up like this?'"]

  AB --> AC["Thais: 'Ah, an inquisitive mind! A rare trait in one so... rugged.'"]
  AC --> AD["Thais: 'You see, I once lavished praise upon a wizard’s mustache.'"]
  AD --> AE["Thais: 'A mustache so grand, so powerful, so exquisitely groomed!'"]
  AE --> AF["Thais: 'But alas! I praised it *one* too many times… and he cursed me for it.'"]
  AF --> AG["Thais: 'Now, my magnificence is hidden beneath this *vile, wretched, unspeakable* filth!'"]
  AG --> AH["Thais: 'So tragic… So cruel… So—'"]
  AH --> AI["Player: '...Yeah, I think I get it.'"]
  AI --> AJ["(After hearing the story, a new question lingers in your mind.)"]

  %% --- ASKING ABOUT THE WIZARD (NOW UNLOCKED) --- %%
  AJ --> AK["Player: 'Wait… is the wizard still around?'"]

  AK --> AL["Thais: 'H-Haha! Oh, don’t worry about that!'"]
  AL --> AM["Thais: 'It’s not like he’d hold a grudge for *centuries* or anything… right? Haha… right?'"]
  AM --> X

  %% --- RETURNING TO THAIS --- %%
  X --> AN["Speak to Thais again"]
  AN --> AO["Without the mirror"]
  AN --> AP["With the mirror in hand"]

  %% --- WITHOUT THE MIRROR --- %%
  AO --> AQ["Thais: 'Ah, you return! With a mirror, I presume?'"]
  AQ --> AR["Player: 'Not yet.'"]
  AQ --> AS["Player: 'These things take time, Princess Mudpile.'"]

  AR --> AT["Thais: 'Tragic. Devastating. A true betrayal of beauty itself.'"]
  AS --> AU["Thais: (GASPS) 'HOW DARE YOU?!'"]
  AT --> AV["Thais: 'Do not tarry too long, hero! Every moment without my reflection is agony!'"]
  AU --> AV

  AV --> X

  %% --- WITH THE MIRROR --- %%
  AP --> AW["Thais: 'At last! The instrument of my redemption!'"]
  AW --> AX["Thais: 'Quickly, hand it over! I must gaze upon my own splendor!'"]
  AX --> AY["(She snatches the mirror and dramatically holds it up to her face.)"]

  %% --- REACTION TO HER REFLECTION --- %%
  AY --> AZ["Thais: (Gasp) 'Oh no… I’m beautiful!'"]
  AZ --> BA["Thais: 'This whole time I thought I was doomed to be hideous!'"]
  BA --> BB["Thais: 'I was just covered in mud!'"]
  BB --> BC["Thais: (Sniffles) 'It was so tragic. But also inspiring. The courage I showed… the resilience…'"]
  BC --> BD["Thais: 'I truly am a marvel!'"]

  BD --> BE["Player: 'I mean… yeah, I could’ve told you that.'"]
  BD --> BF["Player: 'So, what now? Do you start a religion?'"]

  BF --> BG["Thais: 'Hmm… The Church of Thais does have a *divine* ring to it.'"]
  BG --> BH["Thais: 'But enough about that—your reward!'"]
  BE --> BH

  %% --- THE REWARD (SORT OF) --- %%
  BH --> BI["Thais: 'As a reward, I grant you something far more valuable than gold—'"]
  BI --> BJ["Thais: 'My sincerest flattery.'"]

  BJ --> BK["Player: '...That's it? No actual reward?'"]
  BK --> BL["Thais: 'Oh, darling, words from lips as divine as mine are worth more than any treasure.'"]
  BL --> BM["(She tosses her hair dramatically—right as the mirror emits a dazzling light.)"]
  BM --> BN["(In a sudden flash, she vanishes, leaving the mirror behind.)"]

  %% --- FINAL PLAYER REACTION --- %%
  BN --> BO["Player: 'Wait—what’s happening?!'"]
  BO --> BP["(You are left alone. Only the mirror remains where she once stood.)"]

  BP --> BQ["Player: 'OH GOD IT’S A BOMB!'"]
  BQ --> BR["(You dive for cover.)"]
  BR --> BS["(…Silence.)"]
  BS --> BT["(After a moment, you cautiously peek out.)"]
  BT --> BU["(Thais is gone. Only the mirror remains where she once stood.)"]

  BU --> BV["(You hesitate... but then flip the mirror over.)"]
  BV --> BW["(There's something written on the back: 'Made by Re-Logic'.)"]
  BW --> BX["Player: '...Huh.' (You pocket the mirror and walk away.)"]
  BX --> BY[QUEST COMPLETE]
```
