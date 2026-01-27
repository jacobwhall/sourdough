# Changelog

This file documents notable changes to the Sourdough schema and its reference implementation.

## v0.2.0

- Include `highway=services` elements as areas instead of lines
- Add `building:levels:underground` attribute to the buildings layer
- Upgrade `informal` to a primary attribute on highways
- Add `colour` attribute to public transit routes
- Modify power plant minzooms based on the plant's output (from `plant:output:electricity` tag)
- Tweak minzooms for `aeroway=aerodrome` labels to show major airports at lower zooms
- Add label points for named `place=archipelago`, `place=island`, and `place=islet` areas to the places layer

## v0.1.0

The initial public release of Sourdough.
