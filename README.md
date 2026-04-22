Hyper-Realistic Pīwakawaka Web Plugin 🌿🐦

A fully autonomous, zero-dependency Vanilla JS plugin that brings the native New Zealand Fantail (Pīwakawaka) to your website.

The bird acts completely natively, featuring a custom kinematic physics engine, anatomically correct SVG vector graphics, 3D layering, and intelligent DOM-interaction (it will physically land on your buttons, navigation menus, and vertical borders).

✨ Features

Zero Dependencies: No React, jQuery, or external image assets needed. All SVGs and CSS are injected directly by the JS class.

True Kinematic Physics: Flies with a custom sine-wave flutter, true parabolic arcs when jumping, and velocity-based aerodynamic pitching.

Dynamic Posture Engine: Features 6 distinct perching postures, including horizontal stretching, alert posing, and vertical wall-clinging.

3D Tree Hideaway: Includes a fully animated SVG tree sequence with depth-masking.

🚀 How to Use

Simply include the PiwakawakaPlugin class in your project and initialize it:

window.addEventListener('DOMContentLoaded', () => {
    window.piwakawaka = new PiwakawakaPlugin({
        // Provide CSS selectors for elements the bird is allowed to land on
        perchSelector: '.bird-perch, nav a, button' 
    });
});


API Methods

window.piwakawaka.hideInTree(): Spawns the tree and sends the bird into the hideaway.

window.piwakawaka.emergeFromTree(): The bird performs a waking stretch and flies out of the tree.

window.piwakawaka.scare(): Forces the bird to immediately take off and fly away.