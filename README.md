Basketsim Ratings Custom
Chrome Extension – Description & User Guide

What is Basketsim Ratings Custom?

Basketsim Ratings Custom is a free Chrome extension that allows Basketsim managers to calculate personalized player ratings for all five basketball positions:

- PG – Point Guard
- SG – Shooting Guard
- SF – Small Forward
- PF – Power Forward
- C – Center

Instead of relying on fixed positional formulas, managers can assign their own percentage weights to individual player skills.

The extension automatically reads player skills from Basketsim and calculates weighted positional ratings based on the user's preferences.

It is a separate extension from Basketsim Ratings Classic. Both extensions can be installed and used simultaneously.

Installation

1. Download the Basketsim Ratings Custom ZIP file.
2. Extract the ZIP into a permanent folder on your computer.
3. Open Google Chrome.
4. Enter `chrome://extensions` in the address bar.
5. Enable **Developer mode** in the upper-right corner.
6. Click **Load unpacked**.
7. Select the extracted extension folder containing `manifest.json`.
8. Make sure the extension is enabled.
9. Open Basketsim or refresh the page if it is already open.

Keep the extracted folder on your computer. Chrome needs it to load the extension.

Where does it work?

The extension works on:

- Players: Your squad page, where you can see ratings for your players.
- Individual player profiles: Open any player's profile to view their custom ratings.

The extension does not display ratings directly on Transfer Market listing pages. However, you can open a player from the Market to see their custom ratings on the individual profile.

Understanding Custom Ratings

For each player, the extension displays five positional ratings:

Custom Ratings | PG 8.45 | SG 9.20 | SF 7.85 | PF 6.40 | C 5.75

These ratings are calculated using the percentage weights selected by the user.

A higher rating indicates a better match for that position according to your chosen skill priorities.

Ratings are displayed with two decimal places.

Configuring Skill Weights

Each position has its own independent configuration.

1. Open the Players page or an individual player profile.
2. Find the Custom Ratings section below the player's skills.
3. Click PG, SG, SF, PF or C to expand that position's settings.
4. Enter a percentage weight for each skill.
5. Make sure the total equals exactly 100%.
6. The extension recalculates the ratings automatically.

You can expand one, several or all five positions at the same time.

Available skills:

- Handling
- Quickness
- Passing
- Dribbling
- Rebounds
- Positioning
- Shooting
- Freethrows
- Defense
- Experience (optional)

Each skill can have a weight between 0% and 100%.

A weight of 0% means that skill does not contribute to the rating.

How Are Ratings Calculated?

The extension uses a weighted average:

Rating = Σ (Skill Value × Weight %) / 100

Example:

| Skill | Player Value | Weight |
|---|---:|---:|
| Handling | 8 | 30% |
| Quickness | 10 | 30% |
| Passing | 12 | 40% |
| Total | | 100% |

Calculation:

(8 × 30 + 10 × 30 + 12 × 40) / 100 = 10.20

The same principle applies independently to PG, SG, SF, PF and C.

A valid configuration must total 100%. Incomplete configurations do not produce a valid rating.

Including Experience

The extension provides an Include Experience in ratings checkbox.

- Unchecked: ratings use the nine regular player skills.
- Checked: Experience can also contribute to the weighted calculation.

Experience is optional. Users can choose whether it should influence their positional ratings.

When using Experience, ensure that the active skill weights total 100%.

Saving Your Preferences

Your custom weight configurations are saved locally in Chrome.

The same preferences are used across players, so you do not need to configure each player separately.

Changing a weight updates the relevant ratings automatically.

Your saved settings remain available when you return to Basketsim.

Resetting Settings

Use Reset Defaults to restore the extension's predefined positional weights.

This is useful if you want to start over with a fresh configuration.

Basketsim Ratings Classic Compatibility

Basketsim Ratings Custom is independent of Basketsim Ratings Classic.

You can use:

- Classic only
- Custom only
- Both extensions simultaneously

Classic provides its predefined rating calculations, while Custom allows you to define your own positional priorities.

Important Notes

- The extension does not modify player skills or game data.
- It does not provide an official Basketsim player rating.
- Ratings are mathematical estimates based on your chosen weights.
- The extension is intended for desktop Google Chrome.
- The ZIP installation requires Developer mode.
- The extension is currently provided for testing and feedback.

Feedback

If you discover a bug, an incorrect calculation or an issue with the interface, please report it.

Suggestions for improving the extension are also welcome.

Enjoy Basketsim!
