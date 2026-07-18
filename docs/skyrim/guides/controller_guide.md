# Even A Blind Can Control The Skyrim, Controller Guide by ON1XN

> It's very long guide, please be patient to read. And this is not a replacement or overrid the existing controller support from the Skyrim Access mod, treat it an extension that enhance your gameplay.

If you're playing the Skyrim Access mod with a controller, you've probably encountered situations where you have to move your hands to your lovely keyboard to perform certain actions that the controller can't handle. For example, pressing "B" to check enemy health, "Shift + O" to set a navigation object, and other actions. In my opinion, it isn't a smooth experience.

Unfortunately, many gamepad mods on Nexus aren't accessible for Skyrim Access. That's why I decided to create this Steam Input layout to suit my own needs. Who knows? Someone else might benefit from this layout too, enjoying their controller experience without a complex setup. (This may complex any way. But easier than manual set up or mess around with mods like I did.)

As far as I'm concerned, with this layout, you rarely to touch your pouting keyboard. (Since you aren't touching your keyboard, she's going to pout, so don't forget to take your keyboard out on a date after playing Skyrim!) 

Yes, I have mapped every single Skyrim Access keybind that used to be exclusive to the keyboard into this layout. As long as they don't change the default keybinds in the future, everything should work perfectly.

However, there are a few situations the controller doesn't work as expect for my case, and probably yours as well. Please keep this in mind, and roughly 99% in the game can be done with my input layout.

Plus, you get a total of 18 extra hotkeys to create crazy combos! That should be more than enough for most players, I suppose. At least, it's more than enough for me.

> **Note 1:** This layout is not just for a blind mage, you can assign these extra hotkeys to potions, equipment, or any items the game allows you to add to the favorite menu.

> **Note 2:** I created this layout based on the Logitech F310, which uses XInput, but its shape is similar to a PS3 controller. Therefore, the key combinations and user experience are optimized for PlayStation controllers. While the layout works regardless of the controller's shape or brand, Xbox controller users might find some combinations tricky to press, which could lower their user experience.

> **Note 3:** As mentioned, this layout is not specific to XInput (e.g., Xbox or my Logitech). If you are using a PS3, PS4, PS5, Switch Joy-Con, Razer, or Steam Controller, everything should work as expected since all of them are supported by Steam.

> **Note 4:** This includes handheld devices like the Steam Deck and Asus ROG Ally. I can't guarantee it will work, but in theory, as long as the device has a console-shaped controller and you play the game on Steam, you should be able to use it without any problems.

---

## Requirements

Before using this Steam Input layout, there are two requirements you need to prepare:

1. **The game must be on Steam.** This layout is not supported on GOG or anywhere you might have the game.
2. **Two specific mods must be installed.** Otherwise, my Steam Input layout won't work properly, and weird behaviors await you... heheheh.

Here are the mod pages:

* **Auto Input Switch:** [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/54309)
* **Extended Hotkey System:** [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/32225)

Load order, I'm not quite sure. But to be safe, *Auto Input Switch* should be placed before *Extended Hotkey System*. Well, in theory, it should be that way, since we need to modify the input system before extending it.

---

## Installing the Steam Input Layout

After both mods have been installed and enabled in your choice of mod manager, you're ready to grab this layout!

> This step assume you're using Steam in normal mode, not a big picture mode. However, in big picture mode may easier in certain parts, I just didn't use it to write this guide.


1. Open Steam, go to your library, and select Skyrim.

2. Look for the **"Configure Controller"** button, which is located below the Play and Manage buttons, and click on it.

3. Find **"Using the game's built-in support Enable Steam Input"** and click on it. Your NVDA should now read: *"Using Steam Input Translation Disable Steam Input"*. Oh, you're almost there!
And you may need to press NVDA + space to out from their browse mode to move around. If you can't find the text I mentioned on this page. Actually next step too.

4. Click the link under the **"Current Button Layout"** heading. It should currently be something like the official Skyrim layout from Valve, but the exact name doesn't matter. In this area, there should be a link showing the layout name, along with options to view and edit it. Please click on the layout name itself.

5. On this page, look for the search tab and type **"Blind Skyrim"** into the search box. You should see *"The Elder Scrolls V: Skyrim Special Edition: Blind Skyrim V. 1 ON1XN"* on the searched result, Click on it, apply layout, and done.


Now, under "Current Button Layout," it should display the layout name as "Blind Skyrim V. 1," meaning you're officially done. If it doesn't show up, click the link again and try looking under the "Your layouts" tab. However, I don't think you'll need to do that.

---

## Extra Keybinds for Skyrim Access!

Some of these explanations are taken from the official mod's manual. I assume you're already familiar with the default keybinds for Skyrim Access. Since I only added missing options from the original mod, I won't explain everything here, only the keybinds I created. Again, besides the keybinds listed below, the rest remain completely default.

I highly recommend keeping the official mod's GitLab or manual open to read along for the full list of keybinds you need to know.

[Here's the official Skyrim Access GitLab to read along](https://gitlab.com/SkyrimAccessibilityProject/SkyrimAcces)

> **A Big Warning:** You should NOT remap any default keys in the MCM (Mod Configuration Menu) of the Skyrim Access mod. Otherwise, it will break and won't work properly. Moreover, if you do, I'll bite you.

### Keybinds

* **Right + A** = Report of the selected object.
* **Right + B** = Open journal.
* **Right + X** = Select or deselect the current object (sound beacon).
* **Right + Y** = Enemy health.
* **Right + LB** = Follow the selected NPC or object.
* **Right + RS click** = Lock the currently selected NPC or creature.
* **Right + Back** = Scan the surrounding area or items. *(Please make sure your Num Lock is turned on, otherwise, this won't work. It might be a little clumsy to press, but since Skyrim Access auto-rescans nearby objects pretty reliably, you probably won't use it very often, I guess.)*
* **Right + Start** = List all active effects.
* **LS click + Start** = Teleport back to the nearest walkable ground.
* **RS click + Back** = Check the direction you're facing (similar to pressing N on the keyboard). I put it here because I don't use it very often either, but it might be useful in certain situations.
* **Start double tap** = Simulates the Enter key on a keyboard. Since the map menu sometimes doesn't allow you to use the A button to fast travel when using a controller, you can double-tap the Start button to solve this.

Actually, I could have mapped some keybinds to RB, LT, and RT to make them easier and more intuitive, but those are attack keys. During my testing, there were minor situations where I accidentally used a weapon, spell, or shout. Yes, and then the guards or nearby NPCs turned around to bite me, or I accidentally swung my Katana at them! Therefore, I decided to block those attack keys. Although those accidents didn't happen often, it's definitely better to avoid them altogether.

And I didn't include the quest-guide authoring feature here, because it doesn't affect my gameplay.

---

## Hotkeys

This section is dedicated to hotkeys, combos, or whatever else you want to call them. Yes, you can even call it a cat if you'd like to! Personally, I call it an onion, simply because I want to. 
This section might take a bit of reading to understand the setup and key combinations, but don't worry, you can take your time reading it through.

Alright, time to get a little bit of a headache. You will need your lovely keyboard to finish this part as well.

I need to warn you beforehand: these hotkeys only swap your equipped spell or gear. They don't mean that pressing an X + X hotkey will automatically cast a spell or swing a weapon, it doesn't work like that. You still need to use **LT** for your left-hand spell/shield, and **RT** for your right-hand weapon/bow/spell.

> Before creating hotkeys and using this layout, you'll want to rebind **F5** (Quick Save), **F9** (Quick Load), and **F12** (Steam Screenshot) to something else. Otherwise, you might run into issues using this input layout.

**Changing F12:** Please open your Steam client, go to your library, select Skyrim, and click on the "Manage" button. After that, click on "Properties." You'll see an option that says "Enable the Steam Overlay while in-game." Uncheck that box.

**Note for NVDA users:** Please ensure you don't have the *Speech history review* add-on installed on your NVDA. If you do (like me), please change its shortcut key to something else.

**Changing F5 and F9:** This can be done very easily in the in-game control settings. Just use your keyboard to go to Settings > Controls, look for the Quick Save and Quick Load keys, and rebind them to something else. I personally use `[` and `]` respectively. You can follow my setup or rebind them to any keys you don't use at all on your keyboard. And as a reminder, we never recommend using Quick Save and Auto Save in Skyrim anyway, heheheh.


1. In-game, add your desired spell, item, potion, or equipment to the favorite menu. I guess you already know how to do this.

2. Open the favorite menu by pressing **Q**. I think you already know this one too.

3. Press **Left Ctrl + 1 to 8**, or **F3 to F12** to create a hotkey.

> My layout only supports the key list mentioned above, so don't try to map it to other keys. If you do, I'll spank you.

Once set up, the game will say something like *"Fireball hotkey 1"* for example. And now you're done!

I only use F3 through F12 because Skyrim Access uses **F2** to open the collection menu to learn their keybinds, and I don't know how to change that. I also avoided using **F1** because some mods out there utilize it. For example mods that use the *SKSE Menu Framework*. 
Although it doesn't support accessibility at the moment I made this layout, who knows? In the future, the Skyrim Access developer might implement it.

Actually, **F6 through F12** are used by some graphics or photo mode mods, but I assume blind players don't install those mods anyway. (Although I installed them... hmm... what a weird blind?) So this shouldn't be a problem for most players. 

---

### Here are the combinations you need to remember to access the hotkeys you created above

* **Left + A** = Hotkey 1
* **Left + B** = Hotkey 2
* **Left + X** = Hotkey 3
* **Left + Y** = Hotkey 4
* **Left + LB** = Hotkey 5 *(This won't break the default Skyrim Access modifier key; I've already tested it.)*
* **Left + RB** = Hotkey 6
* **Left + LT** = Hotkey 7
* **Left + RT** = Hotkey 8
* **LS click + A** = Hotkey F3
* **LS click + B** = Hotkey F4
* **LS click + X** = Hotkey F5
* **LS click + Y** = Hotkey F6
* **LS click + LB** = Hotkey F7
* **LS click + RB** = Hotkey F8
* **LS click + LT** = Hotkey F9
* **LS click + RT** = Hotkey F10
* **Left + RS click** = Hotkey F11
* **Left + Start** = Hotkey F12

#### How to use it in real action

Assuming I assigned Fireball to Hotkey 1, when I press **Left + A**, my character will equip Fireball instantly, and I can press **LT** to cast it normally.

It works exactly the same way for weapons. I can assign my sword to Hotkey F5 and my bow to Hotkey F11. When I want to switch between them, I just press **LS click + X** or **Left + RS click** respectively to swap weapons on the fly. And of course, after switching, you can press **RT** to swing or shoot as usual.

Furthermore, you can press the hotkey twice to equip the spell to your right hand, and follow up with other hotkeys to change the spells in both of your hands. This opens up a ton of room for creativity in your mage gameplay!

---

## Known issues

These are minor issues, but I wanted to mention it here in case you encounter it. (Because I saw it sometimes as well.)

* When you close and reopen the game and check your favorite menu again, it won't explicitly display the hotkeys you created. But don't be afraid! Everything still works perfectly fine. It just won't announce them like it used to, so you'll need to remember what you've mapped to these hotkeys by yourself. Unfortunately, my poor brain can't remember all 18 hotkeys I made either, waaaa!

> Note: This might just be an issue on my game, you might see the hotkey labels or you might not see them at all, I'm not sure. Since I have nearly 100 mods installed, one of them might be causing this without actually breaking my game. Everything should be perfectly fine in your case, I suppose.

* If your Left or Right D-pad buttons stop functioning properly, please open your favorite menu and make sure you haven't accidentally assigned a hotkey to them. (Holding left / right D pad here will create a hotkey to the controller, so be careful)
If you did, you can easily fix this by rebuilding your hotkeys following the instructions in the section above. Setting up the hotkeys again will overwrite and delete the old, accidental mappings, restoring your Left/Right D-pad buttons to their intended behavior in this layout.

* Sometimes, the A button on a controller does not work in the map menu for fast traveling or placing markers. You can use the keybinds mentioned above, or try reloading your save file or restarting the game to fix this. (At times, these steps might not help at all, or the button might suddenly start working as expected again for no reason, so use my extra keybinds above can help you for sure.) Please note that this is a bug within the game itself, one of my 100 mods or anything I don't know, it's not an issue with my input layout.

---

## Final words

Thanks for reading this long guide. I hope you like it and enjoy playing Skyrim Access without having to touch a keyboard. But don't forget: take your keyboard out for a date. Don't let a girl (your keyboard) cry!