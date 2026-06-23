# Figma import checklist

Follow these steps to recreate the clickable Figma prototype from the assets in this folder.

1. Create a new Figma file named "SupplierSys_Prototype".
2. Create a "Tokens" page: add color styles and text styles using design-tokens.json values.
3. Create a "Components" page: build atomic components (buttons, inputs, badges) using components.md as spec. Use Auto Layout and the spacing tokens.
4. Create pages "Company_Desktop", "Supplier_Desktop", and "Mobile". Create frames with the exact sizes from the screen filenames (1440x1024 for desktop, 375x812 for mobile).
5. Import SVGs from /assets and /icons into the Figma file and place them on the Components page. Convert frequently used icons to components.
6. Use the screen SVG placeholders in /screens as visual references — rebuild them using the created components for full fidelity.
7. Add prototype interactions: on click → Navigate to frame; modals as Overlay.
8. Export slices or assets as needed (1x/2x). Use naming from this repo for easy mapping.

