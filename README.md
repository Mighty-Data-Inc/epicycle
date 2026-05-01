# Geocentric Meteors

A real-time defense game built around rotating circles, presented as a stylized medieval cosmological orrery.

## How it works

Meteors appear on an outer ring called the **Wheel of Perdition** and slowly fall inward toward an inner white circle called the **Wheel of Grace**. If a meteor touches the Wheel of Grace, you take a hit. Your only defense is a rotating white wedge called the **Arc of Grace**, which is attached to the Wheel of Grace and extends outward like a sweeping shield. When a meteor passes through the Arc, it is pushed back outward instead of continuing inward — but it only counts as safely cleared once it is forced all the way past the outermost boundary, the **Circle of the Abyss**.

## The gear mechanic

Under the medieval theme, the system is mechanically a true planetary gear simulation, similar in principle to an automotive transmission. **Earth**, **Sun**, and **Astral** are the three coupled elements (with the unconventional twist of Earth at the center and the Sun orbiting around it, consistent with geocentric cosmology). Changing which one is fixed, driven, or free-spinning changes the resulting output speed of the Wheel of Grace through gear ratios. Playing well is partly about internalizing those ratio relationships so you can predict how each binding choice will reposition the Arc in time to intercept incoming meteors.


