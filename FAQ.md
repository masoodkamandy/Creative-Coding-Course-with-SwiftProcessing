# Frequently Asked Questions

## Table of Contents

- [Turning In Your Assignments](#Turning-In-Your-Assignments)
  - [What deliverables are expected with each programming assignment?](#What-deliverables-are-expected-with-each-programming-assignment)
  - [What should I name my zipped exercise and project files?](#What-should-I-name-my-zipped-exercise-and-project-files)
  - [What header should I always place at the top of my code?](#What-header-should-I-always-place-at-the-top-of-my-code)
  - [How should I archive my own projects?](#How-should-I-archive-my-own-projects)
- [SwiftProcessing and Xcode](#swiftprocessing-and-xcode)
  - [Where can I find the textbook?](#where-can-I-find-the-textbook)
  - [Where do I write my code?](#where-do-i-write-my-code)
  - [What is a Playground?](#what-is-a-playground)
  - [How do I run my Playground?](#how-do-i-run-my-playground)
  - [How do I run my Sketch.swift file?](#how-do-i-run-my-sketchswift-file)
  - [What things should I check if my file isn't running?](#what-things-should-i-check-if-my-file-isnt-running)
  - [If nothing works and my template still won't run what else can I do?](#if-nothing-works-and-my-template-still-wont-run-what-else-can-i-do)
- [macOS](#macos)
  - [How do I take a screen grab?](#how-do-i-take-a-screen-grab)
  - [How do I create a zip file from a folder?](#how-do-i-create-a-zip-file-from-a-folder)

## Turning In Your Assignments

### What deliverables are expected with each programming assignment?

Unless otherwise stated, **you should be zipping your entire template folder and turning that in**. The Xcode template needs to be together in order to function, so zipping it to turn in preserves all of the relationships within the file.

The kinds of files that are in this structure that need to be present for projects to function are the SwiftProcessing library, images, permissions files, and information that Xcode needs to be able to compile your project.

**Important:** *Do not* just turn in a `.swift` or Playground file. Projects turned in like this will receive no credit.

[Table of Contents](#Table-of-Contents)

### What should I name my zipped exercise and project files?

Project names should be in the following format:

`LastFirst_AssignmentName.zip`

**Note:** Change the title of the zip file *after* it has been zipped. This preserves the original name of the project.

[Table of Contents](#Table-of-Contents)

### What header should I always place at the top of my code?

Headers give information to your professor and to your future self about projects. Use the format below for all of your assignments:

```swift
/*
 * Course: DMA 64 - Creative Coding for Mobile Devices
 * Assignment: Assignment Name
 *
 * by First Last
 * 
 * Initiated: 1/1/1
 * Last updated: 1/1/1
 * 
 * DEVICE TESTED ON: iPhone 13 Simulator
 *
 * CITATIONS: List all sources you used for this assignment.
 *
 * NOTE: This is where you write any notes you would like
 * to leave yourself or others using your code.
 * 
 * */
```

[Table of Contents](#Table-of-Contents)

### How should I archive my own projects?

The work you do in this class is precious and depending on where you end up going after this course, it may be useful to you in the future. It's important to store and keep track of your work in a system that works for you. Here is one suggestion for a system that might be useful to you.

When starting a project, rename the external folder of the template with the following format:

`YYYYMMDD_ProjectName`

For example, a project called DrawingMachine that I started on October 20, 2021 would have an external folder called:

`20211021_DrawingMachine`

This ensures that when you navigate to a folder, all of your files are in order by the date that you started them and you don't have to spend a lot of time searching around a long list.

[Table of Contents](#Table-of-Contents)

## SwiftProcessing and Xcode

### Where can I find the textbook?

The textbook is a series of Xcode Playgrounds available in the SwiftProcessing package. When you download the  **[Empty App Template](https://github.com/masoodkamandy/Swift-Processing-Template-w-Playground/archive/refs/heads/main.zip)**, you will see the Playgrounds in the file structure. Within the Navigation sidebar open **SwiftProcessing > Playgrounds** and you will find 3 Playgrounds that you can expand. Each of these Playgrounds contain all of the textbook chapters.

![A screenshot showing the user interface of Xcode. Within the navigation pane several files are outlined. First is the SwiftProcessing.playground file, which is an empty Playground for prototyping. Second is the Sketch.swift file which is for app development. Last is the Playgrounds folder which contains the SwiftProcessing Playground Textbook.](images/Template.png)

When you expand the three Playground you'll see the 25 chapters you'll be reading.

![The SwiftProcessing Playground textbook expanded to show all 25 chapters.](images/PlaygroundTextbook.png)

### Where do I write my code?

The **[Empty App Template](https://github.com/masoodkamandy/Swift-Processing-Template-w-Playground/archive/refs/heads/main.zip)** I provide for my students has two possible locations to code in. One is the **`SwiftProcessing.playground`**, which is an Xcode Playground file. The other is a Sketch.swift file. You can code in either places, but they have different purposes.

#### **Playgrounds** are good for:

- Prototyping or testing something out.
- A good starting point for most projects.
- Any project that can be contained in a single file.

#### **`Sketch.swift`** is good for:

- Writing an app that works on a phone or tablet.
- Anything that requires speed or is more complex.
- Any project where you need to use more than one file. You can use multiple `.swift` files as your project becomes more comlex.

![Screengrab of the Xcode intervace showing the Navigation panel, which lists the file structure in the template. Two files are highlighted are the SwiftProcessing.playground and the Sketch.swift files.](images/Template_crop.png)

[Table of Contents](#Table-of-Contents)

### What is a Playground?

Xcode Playgrounds are a programming environment that allows for rapid prototyping with a live view. Rather than having to compile and run software on a hardward device or in a simulator, the results of your programming appear next to your code inside of the development environment.

![Xcode Playground user interface.](images/Playground.png)

[Table of Contents](#Table-of-Contents)

### How do I run my Playground?

Your playground has two buttons in the lower left-hand corner of the interface that will help with the execution of your code.

![Running your Playground.](images/Playground_Run.png)

In the **bottom left corner of the window** there is a button that is either a ?????? button or a ??? button. This is for running your code the first time and starting/stopping the compiler.

On the left side of the window beside the code there is a **blue ?????? button**. This is for re-running your code quickly when you've made small changes. This will be faster than the other button.

**Note**: If your code or the editor begins **running slowly**, press the ??? button and you'll notice that the environment will become more responsive.

[Table of Contents](#Table-of-Contents)

### How do I run my Sketch.swift file?

At the top of your template's main interface you will see a ?????? button or a ??? button. These are the **build** and **stop** buttons in Xcode. ?????? will compile your code and open up the **Simulator** for whichever device you would like to simulate.

![RunButton](images/RunButton.png)

To choose a simulator, click on the button to the right of the stop button and select your simulator. **Note**: You want to make sure you keep `Swift-Processing-Template-w-Playground` checked after you pick a simulator.

![SimulatorChoices](images/SimulatorChoices.png)

[Table of Contents](#Table-of-Contents)

### What things should I check if my file isn't running?

Getting the hang of an Xcode workflow can be intimidating at first, but once you know what things to check when things go wrong, you'll become accustomed to it. Here are a few tips for the two methods for coding in SwiftProcessing that you can follow if things go wrong.

#### General Suggestions

- Check that all `{` is accompanied with a `}`.
- Check your tabs by choosing **Edit > Select All** (or **command-a**) and then **Editor > Structure > Re-Indent** (**control-i**). This will reformat your code with proper tabs and will show you when there is a misplaced bracket.

#### Playgrounds

- Make sure your Playground code follows this format:

  ```swift
  // 1
  import SwiftProcessing
  import PlaygroundSupport
  import UIKit
  
  // 2
  class MySketch: Sketch, SketchDelegate {
      
      // 3
      func setup() {
      }
      
      // 4
      func draw() {
      }
  }
  
  // 5
  PlaygroundPage.current.needsIndefiniteExecution = true
  PlaygroundPage.current.setLiveView(MySketch())
  ```

  The commented numbers in the example refer to:

  1. Import statements
  2. The line that starts with `class` which gives us access to all of SwiftProcessing's features.
  3. `setup()` which runs once when a sketch first launches.
  4. `draw()` which runs at 60 frames per second (by default) and loops until the sketch is stopped.
  5. This sets up the Playground's live view. If this is missing, you will receive no error and it will **simply do nothing**. This is a **common error** in Playgrounds.

- If the Playground is giving you console errors about missing methods, **try pressing the Play button a second time**. Sometimes when a project is first run, it takes a couple of plays before the Playground will see all of the available code.

- If you're still getting errors about missing methods or an error that says SwiftProcessing was not found, then switch to the SwiftProcessing library build target, click build, and try to play the Playground again. Follow the steps in the image below:
  ![RebuildLIbrary](images/RebuildLIbrary.png)

  1. Select the **SwiftProcessing build target** in the choices to the right of the build and stop buttons.
  2. Select any **target iOS device**.
  3. Hit the build (??????) button to **rebuild the library**.
  4. Go back to your Playground and try to **play it again**.

#### Sketch.swift

- Make sure your code follows the following format similar to the code above. Notice that there doesn't need to be  quite as much code as in the Playground code:

  ```swift
  import SwiftProcessing
  import UIKit
  
  class MySketch: Sketch, SketchDelegate {
      func setup() {
      }
      
      func draw() {
      }
  }
  ```

- Make sure that you've **chosen a simulator** to use that matches what you'd like to develop on.

[Table of Contents](#Table-of-Contents)

### If nothing works and my template still won't run what else can I do?

There are times when Xcode just needs a reboot. Xcode is fairly good about saving your files, but if things won't work, a good thing to sometimes try is just save your changes with Command-s, quit, and relauch. This can sometimes fix some errors.

If this does not work, you can also clean your build folder by selecting **Product > Clean Build Folder** or **Command-Shift-k**. This erases any files that were created in previous builds and starts fresh.

[Table of Contents](#Table-of-Contents)

## macOS

### How do I take a screen grab?

In macOS you can take a screen grab with a keyboard combination.

**Command-Shift-3** takes a screen grab of your **entire screen**.

**Command-Shift-4** takes a screen grab of a **selected area**.

Pressing the **space bar** after you've entered selection mode will allow you to **capture a window**.

Your image files will save to your desktop.

Add a **Control** to either of the above methods and you will **copy your screen grab to the clipboard** rather than create a file.

[Table of Contents](#Table-of-Contents)

### How do I create a zip file from a folder?

In macOS you can create a zip file by **right or control-clicking any file** and choosing **Compress File**.

![Compress](images/Compress.png)

[Table of Contents](#Table-of-Contents)

[Next Section: Module 1](1_DrawingWithCode/README.md)
