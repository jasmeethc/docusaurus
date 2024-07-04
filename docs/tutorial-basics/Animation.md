---
sidebar_position: 4
---

# Selfserve V2 Animation Tool

![Example Image](https://s.hcurvecdn.com/interactive_avenues/apvideo/69rysq/frame_1/300x250-1120x400/still.webp)

## Asset to Animate

In this section, the only asset that gets visible is for the asset type module, e.g., rich media where the user can select any asset to apply animations to it. For component type modules, the user won't be able to see this section.

## Applied Animation Section

In this section, the user can see the applied animations to respected assets or components. The animation will get added only after proper selection of all required animation functionalities and after pressing the add button.

Beside the selected animation, the user will be able to see the edit icon.

### Edit Button

Helps to edit the animation. As the user clicks on this button, the user will see the preview below.

### Delete Button

Helps to delete the animation.

Here the user can see their selected fields in the animation functionality section and they can edit when edit mode is on. After selecting or correcting animation from the animation functionality section, click on the update button to store the changes, and if not, press the cancel button to cancel the update process.

## Animation List

In this section, users are able to select desired animations from the list. As users select any animation from the list, that animation related functionality will be visible in the animation functionality section.

## Animation Effect From (In) / To (Out)

Here users can select an animation transition effect as a particular animation starting from effect and that same animation ending effect. E.g.: fadein animation starts with from effect and fadeout animation starts with to effect.

## Animation Functionality Section

In this section, users are able to select desired animation effects with respect to the selected animation from the animation list.

### Type

In types, users can select the animation start position from Top, Left, Right, Bottom, and Center. Also, users are able to select two values at the same time, e.g., top-right, top-left, bottom-right, and bottom-left with respected values. By clicking on the cross button, the user can deselect the selected options.

### Mode

In mode, users can set animation repeat count as Repeat (2), No-Repeat (1), and Custom (user input value).

### Opacity

In opacity, users can set opacity as 0 or 1 as per the desired animation effect. This value cannot exceed above 1, if it exceeds, it will show that box in red color.

### Speed

In speed, users can select desired animation speed from Slow (3), Medium (2), Fast (1), and Custom (user input value).

### Delay

In delay, the user can set the animation delay where after how many seconds the animation will start. They can select delay from One (1), Two (2), Three (3), and Custom (user input value).

### Transform Origin

Here users can set origin to selected asset or component as some animations do not give desired effect for canvas size assets due to shifted origin, so it is necessary to set origin with respect to the selected animation. Once the user clicks on the transform origin button, one popup will appear below where the user needs to set the origin.

After selecting origin, press the apply button. We can remove the transform origin just by clicking the clear button.

### Ease

In ease, users can set the animation smoothness where animation will start or end with elastic, bouncy, or normal effect. Users can select ease from power1-in, power1-out, elastic, bounce, and none.

### Repeat-Delay

Users can set repeat delay time (sec) for a particular animation (repeat delay is nothing but in how many seconds the animation will get repeated again after 1 rotation of animation gets completed). Users can select repeat delay from One (1), Two (2), Three (3), and Custom (user input value).

## Custom Animation Button

In some cases, some complex animations cannot be applied using animation tools. In this case, users can apply Custom GSAP Animation for components and modules. To do this, just press the custom button, and one big text area appears where users have to write the custom animations.

## Add Animation Button

Once the user selects the animation from the animation list and selects all functionalities from the animation functionality section, then press the add button to add the animation. After clicking the add button, the animation will be visible in the applied animation section.

## Save Animation for Preset

After applying the animations to any module or component, the user can save the selected module or component animation as a preset to use the animation for different components. To save the animation as a preset, just click on the save animation button, and one popup appears where users have to enter the animation name and press the save button.

Saved animation will be visible in the Previously Saved Animation Presets Dropdown.
[Note: Saved animation only applies to the same assets or components names.]

## Previously Saved Animation Presets Dropdown

To apply saved animations, just select the animation from the dropdown. If the saved animation asset is equal to the current asset, then the animation gets applied to the respected components or modules.


