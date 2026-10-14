# DENNIS J. BARTECK / GITHUB PAGES WEBSITE

## Upload

Upload the contents of this folder into the repository root. `index.html`, `styles.css`, `credits.html`, `.nojekyll`, and `assets/` should sit together, not inside an extra enclosing folder.

In GitHub Pages settings, select the intended branch and its root directory. No build step is needed. All website paths are relative, so deployment under `/DENNIS_v10/` works. The original repository has not been modified automatically.

## Included

- Uppercase page copy and browser-tab titles.
- The introduction starts directly with the muscle-level anatomy animation, with organs and vascular anatomy; no sketch, skin, or reproductive anatomy.
- The skeleton turns to its posterior view, then the camera moves continuously into its blue X-ray spine as the surrounding bones fade. The final frame aligns with the hero spine.
- Two independent, fixed blue X-ray spine instances remain in the hero and interactive study. Scrolling never moves a canvas between the two sections.
- All 26 vertebral labels, individual selection, referenced anatomical information, orbit/pan/zoom, fullscreen, separation, regional views, and editable GLB export.
- Page scrolling passes through the hero; vertical touch scrolling is supported there. Dragging rotates the spine, and the study supplies dedicated zoom controls.
- Gentle rotation, expansion, and separation run by default. Direct interaction pauses this motion. Selected vertebrae enlarge, illuminate, and pulse; reduced-motion settings use static highlights.
- Label anchors follow their vertebrae while the text faces the viewer and remains readable in either rotation direction.
- Hovering a bone, label, or level button previews a brighter outline and slight enlargement. Selected levels retain a stronger glowing highlight and an active button state.
- One continuous X-ray film, image tint, and subtle calibration grid runs through the page. The loading camera continues from the skeleton into the spine and hero without resetting its pose.
- Locally hosted models, fonts, images, JavaScript, and Draco decoder. No API keys or external asset CDN.
- `assets/anatomy.glb`: upgraded full 4.8-second reveal.
- `assets/spine.glb`: compact spine-only model with 26 editable units and labels.

The animation runs after model preparation; download time depends on the connection. The website renders real 3D geometry at up to 2x display pixel density, not a fixed-resolution movie.

## Contact Form

The form prepares an email in the visitor's email application. It does not send a request automatically, store medical details, or confirm an appointment. The practice must confirm availability directly.

## Model Compatibility

The GLBs use Draco compression. Smooth alpha dissolves require `KHR_animation_pointer`; the included viewer supports it. Other viewers may use fallback cuts. Animated cameras require selection of the embedded camera. Webpage transitions and the browser's blue rim enhancement are not embedded GLB features.

Camera-facing labels and pulsing selection effects run in the website. An edited GLB saves labels in their current orientation and the current static view; other viewers supply their own interaction behavior.

The model is educational, not patient-specific or diagnostic. Anatomical descriptions distinguish bones from nerve roots and do not promise that adjusting one level treats an organ. Exploded separation is a teaching view, not normal joint motion.

## Credits and Review

Keep `credits.html` and the license notices in `assets/`. Adapted anatomy is CC BY-SA 4.0, based on BodyParts3D and Z-Anatomy. Preserve attribution and share-alike terms for anatomical adaptations. Practice photography retains its original rights; fonts and software have separate bundled licenses.

Before public clinical use, the practice should approve contact details, service descriptions, educational content, and photography rights.
