---
-api-id: M:Windows.Devices.Lights.Effects.LampArrayUpdateRequestedEventArgs.SetSingleColorForIndices(Windows.UI.Color,System.Int32[])
-api-type: winrt method
ms.custom: RS5
---

<!-- Method syntax.
public void LampArrayUpdateRequestedEventArgs.SetSingleColorForIndices(Color desiredColor, Int32[] lampIndexes)
-->

# Windows.Devices.Lights.Effects.LampArrayUpdateRequestedEventArgs.SetSingleColorForIndices

## -description
Sets all lamps specified to the same color.

## -parameters
### -param desiredColor
The desired color.

### -param lampIndexes
Array of lamp indexes to set.

## -remarks
If the lamp doesn't support the desired color, it is set to the [NearestSupportedColor](../windows.devices.lights/lampinfo_getnearestsupportedcolor_1689565521.md)

If an index does not exist on the device or was not specified in the effect, it is ignored and the remaining are still applied.

[Black](../windows.ui/colors_black.md) is equivalent to a lamp being 'off'.

## -see-also

## -examples

