# TF2 Item Attribute List

A collaborative effort to document every attribute that exists in TF2 for use in my [TF2 Custom Weapon Creator app](https://gamepro5.com/programs/tf2_custom_weapon_creator/).

## How to help:

1. Visit [the json file](/attributeList.json).
2. We need to fill out a short name that describes the attribute. Put that string in the ".name" parameter of the json entry.
3. We also need to write a better documentation in the .desc parameter.
4. For the ".type" parameter, either put a "number" if it's as a multiplier or an additive attribute, or if it sounds like a boolean, but "checkbox". If it's a text entry, put "text". A lot of attributes have their valtype listed as an "additive" or a "on" when they are actually a boolean. Hence why we need to do the testing!
5. Create a [Pull Request](https://github.com/Gamepro5/TF2_Item_Attribute_List/compare) to submit your changes to the json file. You will immortalized in the "contributors" list!


