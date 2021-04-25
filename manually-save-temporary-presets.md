# Manually save temporary presets in GIMP

**"If only GIMP could temporarily save the brush size!"**
<br />This is a feature I want, But GIMP doesn't seem to have this feature! But today I stumbled across this feature: **Manually save temporary presets in GIMP.**
<br />(Although it's not autosave, but it works pretty well. It can save all temporary presets, not just brush size.)

- If you installed the brush package according to the README method in my SLOS-GIMPainter project, you have already got this feature.

**Manual saving of temporary presets in GIMP, prerequisites:**
- Use the menu, Edit -> Preferences -> Folder(Folder Options) to add the corresponding folder directory. Do not copy to the GIMP-Profile-Folders.
- After adding the corresponding folder directory, do not check the Checkbox. This will disable editing and keep the default value.

	Check the installation method of SLOS-GIMPainter in GIMP: [here](https://github.com/SenlinOS/SLOS-GIMPainter#installation)

**Confirm that the SLOS-GIMPainter's brushes cannot be edited:**

- Double-clicking a brush in SLOS-GIMPainter will bring up the "Tool Preset Editor", but the interface is frozen, which means that you can't modify the preset default value.
<br />This is correct, because it can prevent the setting of SLOS-GIMPainter from being messed up.

**Re-selecting the Brush Preset can return the parameter to the default value:**

- When you change parameters of a Brush, such as brush size. Then, after you select another brush, re-select this Brush, and this Brush parameter will return to the default value.
<br />Re-select the brush preset, which is the correct way to reset the default parameters of the preset.

# All the above are correct, which shows that the temporary preset can not be saved, but miracles will always appear :)

- We selected `028a_Roller Brush-3` in SLOS-GIMPainter, Its default brush size is **192**. We set the brush size to **12**.

- Right-click on the `028a_Roller Brush-3's Icon` and click <mark>**Save Tool Options to Preset**</mark> in the pop-up menu. "Reselect the Brush Preset" and the brush size for 028a_Roller Brush-3 will remain at: **12**. Manually saving temporary preset succeeded.

![temporary-presets](https://raw.githubusercontent.com/SenlinOS/databox/master/temporary-presets.jpg)

Yes, this is the way to manually save temporary presets. Brush mode, brush opacity, brush angle, spacing, etc. can be temporarily saved manually as long as they are parameters included in the preset.

- When we restart GIMP and you reselect the brushes of SLOS-GIMPainter, all parameters will be the default values. Because of the correct installation method, the default parameters of SLOS-GIMPainter cannot be changed :)

---

Video Demo: https://youtu.be/ZBRkZWnwI68

---

2021-04-25, By: SenlinOS