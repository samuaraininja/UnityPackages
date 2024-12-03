Custom: Packages that I've made myself or edited
  - Animation Curve Drawing creates Scriptable Objects that draw animation curves based on the input values. Updates in the inspector using OnValidate.
    - It also has a Static Extension class for creating, calculating, and evaluating animation curves with code.
  - Attributes are a few of the custom scripts for setting up customs inspector tools
    - Includes: Serialized Interfaces & Types and ListToPopUp
      - Serialized Interfaces is a property drawer that allows interfaces and their derived classes to be viewed in the inspector
        - From this video by Git-Amend: https://www.youtube.com/watch?v=xcGPr04Mgm4
      - Serialized Types is a class with a property drawer that allows the inspector to view derived classes as an enum to decide behavior or quickly switch a script's state.
        - From this video by Git-Amend: https://www.youtube.com/watch?v=a62D6IiVMTw&t=454s
      - ListToPopUp is an attribute that draws a list as an enum popup, similar to how Extendable Enums works.
  - Audio Manager is my current solution for handling Music and SFX within my games using Scriptable Objects as its base.
  - Canvas Tools is a collection of UI editing tools for stylizing UI objects in Unity.
  - Editor Shortcuts are any tools I've found or written to make using Unity Editor easier.
    - Will be updated intermittently.
  - Effects 2D are a few particle systems I've made for past games and their associated sounds.
  - Either Struct is a generic struct for setting up two actions based on the variables/scripts you pass through.
    - Slightly edited from this video by Git-Amend: https://www.youtube.com/watch?v=3xIB6zowVDM
  - Extendable Enums is precisely what it sounds like; it creates a list of Enums that you can customize through scripts or the inspector (based on how you modify it)
    - Essentially finished. But in the future, I will be working on the Editor Window to add the ability to show the current list with a toggle so that you can edit it in the inspector.
  - Game Events Listener is a Scriptable Object-based Event Subscription System.
    - Gets a list of references to Game Events Listeners with a Game Event Scriptable Object that holds the active Listeners' responses and invokes them simultaneously when its Raise method is called.
    - Based on this talk at Unite 2017 by Ryan Hipple: https://www.youtube.com/watch?v=raQ3iHhE_Kk.
  - Group Scene Loading is based on a Git-Amend YouTube video I've heavily edited for my systems.
    - I'd advise against downloading it in this state.
    - But if you do, you will need:
      - This Repository: https://github.com/starikcetin/Eflatun.SceneReference.git#4.1.1
      - Odin Inspector: a paid tool, so you'll either need to buy it or remove the Odin Inspector References by hand.
        - I plan on eventually making an editor for this.
  - Input Reader is a system that allows and blocks player controls based on the scenario, such as being in a cutscene.
    - It is a very opinionated solution and will only work based on the controls you set up.
    - It is only recommended to download it in its current state if you want to kitbash it to work for your specific needs.
  - Optional Struct is a wrapper struct that allows you to decide what to do with a variable/script based on whether it is enabled or disabled,
    - Based on these videos:
      - aartificial: https://www.youtube.com/watch?v=uZmWgQ7cLNI
      - Git-Amend: https://www.youtube.com/watch?v=3xIB6zowVDM
  - Save Streamer is my WIP solution for saving and loading game data. It is mostly untested and needs some work.
    - Includes Optional Struct and Serializable Types from Attributes.
    - Based on these videos:
      - Sasquatch B Studios: https://www.youtube.com/watch?v=1mf730eb5Wo
      - Git-Amend: https://www.youtube.com/watch?v=z1sMhGIgfoo
  - Thimble is a custom logging tool for Yarn Spinner that I wrote. Instructions are included in the package.
  - Variable References is a collection of Structs / Scriptable Objects made to hold value references.
    - Based on this talk at Unite 2017 by Ryan Hipple: https://www.youtube.com/watch?v=raQ3iHhE_Kk.
    - Includes Conditional Structs:
        - Framework for setting up behaviors or interactions based on floats, ints, bools, and transform values.
    - Supports Float, Int, String, Bool, Transform, & Vector3
  - World Shaper is my custom method of handling Scene Loading, Camera Movement, and Variables that depend on where the Player is in a Scene.
    - Based on these videos:
      - aartificial: https://www.youtube.com/watch?v=ZjfhGEziEEk&t=71s
      - Sasquatch B Studios: https://www.youtube.com/watch?app=desktop&v=CQEqJ4TJzUk
    - It is almost finished but is currently a 2D-only system; I will look into adding 3D Support.
    - I'd advise against downloading it in this state, as there are no instructions yet.

GitHub: Packages from repositories that are available via GitHub that I've packaged to make them easier to import or send to other people. 
  - A-Star_Pathfinding is, well pathfinding, for 2D games
  - Auto Save saves scenes periodically at intervals you decide in your project settings.
  - Editor Scene Loader creates a menu, organized via its file path, that allows you to load any scene in your project in seconds
    - From this video by Scott___S: https://www.youtube.com/watch?v=_iEWvNyfkL0
  - Rename In Bulk allows you to rename multiple GameObject and Assets at the same time
  - Fungus is an older dialogue system with Unity Integration
  - Yarn Spinner is a popular, more updated dialogue system with Unity Integration

Project Set Up: My method of quickly setting up all the packages that I use in my projects. You can reconfigure it for your own purposes if you want.
