# Google Summer Of Code 2020 - Final Work Product
![](./images/logo.svg) 
### sugarlabs/[musicblocks](https://github.com/sugarlabs/musicblocks) 
#### author:sksum ([Saksham Mrig](https://github.com/sksum)) 
#### Project Details 
- Project Title: **Resolve 100 issues in Music Blocks**
- Proposal: [ Proposal ](summerofcode.withgoogle.com/projects/#6367628337086464)
- Organization: [Sugarlabs](https://github.com/sugarlabs/)

## Abstract/Summary 
Spending the summer of 2020 working on MusicBlocks has been an amazing experience .
I'm very grateful to Sugarlabs for accepting my contributions and supporting me through the process of fixing bugs and adding new features.<br/>
For the past 4 months I along with my peers have been working tirelessly to make musicblocks better. I have successfully added new features, widgets, new Blocks and also refactored a lot of code.
___
## Highlights
- MusicKeyboard and Midi: <br />
    The MusicKeyboard widget in MusicBlocks now considers BPM and Tempo info to generate notes . 
    The MusicKeyboard widget now accepts Midi keyboard (usb) as an input source with the help of the [Web MIDI API](https://www.w3.org/TR/webmidi/) . There are still some performance issues with the [.mid file input]()
    &nbsp;

    ![keyboard](./images/midi.gif)
    &nbsp;

- Widgets: <br />
    Oscilloscope widget was added this summer which allows users to visualize their music waveforms .
    &nbsp;

    ![oscilloscope](./images/oscilloscope.gif)
    &nbsp;

    Issues related to temperament widget and the pitch slider were mostly resolved .
    Statistics are now displaed as a widget and we have added new Stats which are better oriented for musical parameters and some of them are used to suggest tags when publishing.
    &nbsp;

    ![stats](./images/stats.png)
    &nbsp;


- Palette & Pelette menu: <br />
    Palette and Palette menu buttons now use simple HTML/CSS instead of CreateJS ,this has made the user experience much smoother and also handles any issues pertaining to layout distortion on resize .
    &nbsp;

    ![palette](./images/palette.gif)
    &nbsp;

- on everybeatdo: <br />
    This is a new block which uses a seperate turtle as a beat compainion to run tasks on every beat regardless of note playing , whereas the **on everynotedo** block only worked when a note was queued in the project .
- Search: <br />
    I helped revamp the JqueryUI Search widget to use searchIds for to use images as identifiers .
    &nbsp;

    ![search](./images/search.gif)
    &nbsp;

- New Blocks: <br />
    Some of the blocks I helped develop this summer were :
    - Pitch Analyser : Converts audio input to musical pitch .
     For more Info - https://musicblocks.net/2020/07/15/how-to-make-a-tuner-with-music-blocks/
    - Panning : alows mixinig capabilities 
    
    &nbsp;
    along with hover sensors , crescendo , set grid etc

    &nbsp;

    ![pitch](./images/pitch.gif)
    &nbsp;




Thank You for Reading <br />

Regards -<br />
Saksham Mrig  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![](./images/me.png)

Contact:
- [LinkedIn](https://www.linkedin.com/in/saksham-mrig-b772851a3/)
- [Github](https://github.com/sksum)
