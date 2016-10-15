---
layout: project

root: "seaquence"
title: "Seaquence"
release: "Nov 15, 2016"
website: "seaquence.org"
"press-can-request-copy": true # true | true
"monetization-permission": false # false | ask | non-commercial | monetize

platforms:
  - name: "iOS App Store"
    link: "http://www.itunes.com/"

#prices:
#  - currency: USD
#    value: "$6.99"
#  - currency: EUR
#    value: "€6.59"
#  - currency: CAD
#    value: "$6.99"
#  - currency: GBP
#    value: "£6.29"

keywords:


description: "Seaquence is a novel synthesizer and composition app that can create and explore dynamic musical soundscapes. Living compositions are created by combining groups of organic swimming creatures that each have their own voice. Intricate, layered soundscapes emerge as the voices of each creature combine into a dynamic, spatialized composition. As the player moves around, only the closest creatures can be heard, resulting in a sonic experience that evolves and changes as you listen. Musical creations made with Seaquence are a result of collaboration between the creator and the system."

history: "Way back in 2009, Ryan Alexander, Gabriel Dunne, and Daniel Massey participated in SF arts organization Gray Area’s first residency program. While in residence they created the original Seaquence web app. It evolved from ideas around social music, audio/visual connections and sensibilities, alternative musical composition methods, and musical experimentation. Since it went online users of the original version of Seaquence <http://seaquence.org> have made it a vibrant community, sharing well over 200,000 compositions."

unique: "Seaquence is a uniquely fun and dynamic approach to electronic music composition. Creators are encouraged to add and layer multiple voices, resulting in an exploratory sonic experience, rather than an A to B listening experience."

philosphy: "The interface is bright, colorful and mostly devoid of text, encouraging exploration and playful interaction between audio and visual. A custom physics engine was developed which allows the creatures swimming motions to feel organic and playful. Each creature has a unique swimming movement that is derived from the notes in their individual sequencer tempo and pattern, represented by pulsing nodes in their antennae, and their tail is a graphical representation of their waveform.<br/><br/>The musical composition design approach is one that encourages exploration and education. By tying visual interface components to their synthesis counterparts, a composer who is unfamiliar with synthesizer or musical concepts are encouraged to experiment and create sounds freely. Creatures appear to swim under a microscope, both representing an exploration of the unseen and unknown, and a discovery of new sounds and tones. The online Session Browser encourages users to browse what other people have made, and share their own creations. If a user starts a composition from an existing session, the family tree is maintained so you can always trace back up the tree to the parent session."

technicals: "Under the hood, Seaquence utilizes a full-featured polyphonic synthesis engine, built entirely with Pure Data and integrated into the app using libpd. Each voice features a step-sequencer grid with 5-note polyphony, waveform type, amplitude envelope, filter and filter attack envelope, and more. The mixing engine can support up to 10 simultaneous voices, allocated dynamically based on their position relative to the listening “center” as the user pans around the app. There are master composition controls for tempo, base note, and a delay effect.

<br/><br/>The user interface is entirely custom, written in C++ using the Cinder framework.

<br/><br/>Each creature’s voice can be assigned a midi channel that can be used to trigger other apps, external synths and other midi enabled gear, further expanding creative sonic possibilities."

features:
  - "Fully Specialized Stereo Mixing Engine and Listening Experience"
  - "Fully-Featured Synthesis Engine"
  - "Up to 10 Simultaneous Voice Playback"
  - "Up to 5 note polyphony per voice"
  - "Up to 64 Voices per session"
  - "Transpose +/- 12"
  - "BPM"
  - "Delay"
  - "Feedback"
  - "Time (quantized or free)"
  - "Individual Voice Effect Send"
  - "Master Mix Volume"
  - "Individual Voice Features"
  - "Multiple Voice Modes"
  - "5-Note Polyphony"
  - "Unison w/Detune"
  - "Monophonic w/Sub-oscillator"
  - "16-Step Sequencer"
  - "Swing/Shuffle"
  - "Portamento/Glide"
  - "Note Step (1/1 to 1/64)"
  - "Scale Editor"
  - "Octave"
  - "Square, Saw, Sine, Triangle and Noise Waveform Oscillator Types"
  - "ADSRL Amplitude Envelope Editor"
  - "Voice Velocity"
  - "Voice Solo"
  - "Amplitude Envelope Curves"
  - "Filter Cutoff and Resonance"
  - "Filter Attack Envelope"
  - "Filter Envelope Curve"
  - "Lo Pass Filter Mode"
  - "Hi Pass Filter Mode"
  - "Band Pass Filter Mode"
  - "Band Reject (notch) Filter Mode"
  - "MIDI Notes i/o"
  - "MIDI Clock out (sync)"
  - "Online Session Browser"
  - "Share links to sessions you’ve created"
  - "Open Share links in App"

trailers:
  - name: Trailer
    youtube: c7nRTF2SowQ
  - name: "Playing with MIDI"
    youtube: wm1h49rQNC8

# awards:
  # - description: "Winner in this highly relevant contest."
  #   info: "Award Location, 20 October, 1989"
  # - description: "Nomination for this prestigious award."
  #   info: "Award Ceremony, 4 December, 1991"
  # - description: "Winner in this highly relevant contest."
  #   info: "Award Location, 20 October, 1989"
  # - description: "Nomination for this prestigious award."
  #   info: "Award Ceremony, 4 December, 1991"

# quotes:
#   - description: "This is a rather insignificant quote by a highly important person."
#     name: "Person Name"
#     website: Website
#     link: "http://"
#   - description: "An extremely positive quote from a rather insignificant person. Also great."
#     name: "Some Guy"
#     website: "This Page Is Visited By 12 Visitors A Month"
#     link: "http://"
#   - description: "I pretend to love this game even though I do not actually understand it."
#     name: "Pretentious Bastard"
#     website: "Artsy Page"
#     link: "http://"
#   - description: "HOLY SHIT SO AMAZING"
#     name: "Caps Guy"
#     website: "Angry Review"
#     link: "http://"

# additionals:
#   - title: "Original Soundtrack"
#     description: "Available for free!"
#     link: "http://somemusicsite.com/thislink"
#   - title: "Release Blog Post"
#     description: "The blog-post through which this game was released."
#     link: "http://vlambeer.com/bloglink"

credits:
  - person: "Gabriel Dunne"
    website: "http://gabrieldunne.com"
  - person: "Ryan Alexander"
    website: "http://onecm.com"

collaborators:
  - person: "Daniel Massey"
    website: "http://daniel-massey.com"
  - person: "Gray Area"
    website: "http://grayarea.org"

---
