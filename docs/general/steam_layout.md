
# How to Create Your Own Steam Input Layout For Blind Players

If you want to create a controller layout that fits your personal needs, making your own layout is the best choice. I did it myself too!

Creating a Steam Input Layout is not as hard as you might think once you understand the concept. It is just a bit annoying because you have to remap many buttons. It took me three days to finish my first layout, and I am still tweaking it today!

> **Note 1:** Steam Input turns your controller inputs into XInput (simulating an Xbox controller). You should know how Xbox buttons map to your controller if you use a PlayStation controller.
> 
> **Note 2:** This guide is not for any specific game. Once you know how to do it, you can apply these steps to any game on Steam.
> 
> **Note 3:** This method works on PC handhelds like the ASUS ROG Ally, Steam Deck, and others. It also supports all controller types, including Xbox, PlayStation DualShock/DualSense, and third-party controllers.

---

## Getting Started

We will do this step by step. This guide uses Steam Desktop Mode (not Big Picture Mode) and the NVDA screen reader. If you use JAWS or another screen reader, some steps might be slightly different.

1. Open the Steam client, go to your **Library**, and select the game you want to edit (for example, Skyrim).
2. Look for the **"Configure Controller"** button, which is usually under the **Play** button and **Manage** button.
3. If you use NVDA, press `NVDA + Spacebar` to exit Browse Mode. Then look for the button that says **"Using the game's built-in support Enable Steam Input"** and press Enter or Spacebar to change it.
4. Scroll down until you find the **"Current Button Layout"** heading. Below this heading, Steam will read out links for the layout name, View Layout, and Edit Layout, as well as a Settings button (used to save or share layouts). Choose **Edit Layout**.

---

## Quick Overview of the Editing Screen

This screen has a lot of options. Press `Ctrl + Home` to jump to the top of the page first.

* **Section 1 (Tabs):** These tabs show which part of the controller you are editing: **Buttons**, **D-Pad**, **Triggers**, and **Joysticks**.
  * **Buttons:** Includes face buttons (A, B, X, Y), Back, Start, LB, and RB.
  * **D-Pad:** Standard directional pad buttons.
  * **Triggers:** LT and RT.
  * **Joysticks:** Includes stick clicks and movements.
  * *Note:* You might see Virtual Menus and Action Sets here. You can ignore them because they are not needed for basic remapping.
* **Section 2 (Navigation):** Press `H` to jump through headings on the page, or press `G` to quickly find individual buttons.

---

## Changing Buttons on the Controller

When you scroll through the buttons, you will see a structure like this:

```text
Graphic A Button
Executes 1 Command
A Button Executes 1 Command Options
Command 1
Command 1 A Button
Command 1 Options

```

* Lines 1 and 2 refer to the **physical button** on your controller.
* The lines starting with **"Command 1"** tell Steam what key action to send to the game.

For example, even if the physical button is the A button, you can change **"Command 1 A Button"** to act as the X button, the Enter key on a keyboard, or a mouse click instead.

### How to change a button:

1. Press Enter or Spacebar on **"Command 1 A Button"**.
2. A menu will open. Press `Ctrl + Home` to go to the top, then scroll down to see tabs like **Gamepad**, **Keyboard**, **Mouse**, and **Numpad**.
3. Select the tab you want (for example, Gamepad) and scroll down to the command list.
4. Select the button you want and press Enter.
5. You will return to the main screen, and **Command 1** will show your new button assignment.

---

## Pressing One Controller Button for Multiple Keys

You can set a single controller button to press key shortcuts like `Ctrl + C`. Here is how to do it:

1. Find **"Command 1 Options"** and click it to open a pop-up menu.
2. Select **"Add extra command"**. This creates a second command slot for this button.
3. A button selection screen will open. Select your first key (for example, go to the Keyboard tab and select **Control**).
4. Return to the main screen. You will now see **"Command 2 Control"** and **"Command 2 Options"**.
5. Click **"Command 2 Options"** to open its menu, then select **"Add sub command"**.
6. Select your second key (for example, **C**). Now, pressing that single controller button sends `Ctrl + C`.
7. If you need a three-key shortcut (like `Ctrl + Shift + S`), go to **Command 2 Options**, select **Add sub command** again, and add **Shift**, then repeat to add **S**.

> 💡 **Tip:** Always select **"Add extra command"** from **Command 1 Options** to avoid input confusion.

---

## Creating Combo Buttons (e.g., Right D-Pad + X = Shift + O)

Here is how to set up button combinations (chords):

1. Click **Command 1 Options** and select **"Add extra command"**.
2. Select the first key you want from the Keyboard tab (for example, **Shift**).
3. Now you have **Command 2 Shift**. Click **Command 2 Options**.
4. Click on **"Regular press"**. A list of press types will appear. Select **"Chord button"**.
5. The text will change to **"Command 2 Button Chord Shift"**. Click **"Command 2 Button Chord Options"** and select **"Add sub command"** to choose your second key (for example, **O**).
6. Click **"Command 2 Button Chord Options"** again and select **"Settings"**.
7. Under **"Select Button"**, pick the controller button that triggers this combo (for example, Right D-Pad).
8. Press `Esc` twice to return to the main editing screen.

Now, pressing Right D-Pad + X on your controller will send `Shift + O` to the game!

---

## How to Save and Share Your Layout

When you are done editing:

1. Press `Esc` to go back to the main controller screen.
2. Under **Edit Layout**, select the **Settings** button.
3. **To Save for Yourself:** Click **"Export Layout"**, type a name and description, and click **Confirm**.
4. **To Share with the Community:** Click **"Share Layout With Community"**, enter a name and description, and click **Confirm**.

---

## Final Words

I hope this guide helps everyone who wants to play games using a controller when accessibility mods only support keyboards. Enjoy gaming with your controller! If you have any questions, feel free to send me a private message or contact me via my links.

* 💬 **Contact Me:** Reach out via **Discord (@on1xn_th)** or **[Steam](https://steamcommunity.com/id/on1xn/)**

> **A short note:** contact me through Steam maybe easier. Because I turn it on all the time.

---