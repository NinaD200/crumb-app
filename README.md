# Crumb 1.3 — installation

Back up recipes first: Settings → Export recipes. Upload the five unpacked files in this ZIP to the root of your GitHub Pages repository, replacing the previous files; commit. Wait for deployment and reopen Crumb on iPhone. Existing recipe data remains under `crumb.recipes.v1`.

New: fully tappable recipe cards (heart stays separate); stable search field without rerender/focus loss; My ingredients with configurable pantry staples and flexible matching (0–2 missing recognized ingredients); updated recipe-photo OCR text extraction (printed and handwritten, English and some German heuristics); larger bottom navigation buttons. Ingredient preferences are saved locally under `crumb.pantry.v1`.

Important limitations: OCR uses English Tesseract in browser, requires an internet connection on first use and cannot guarantee handwriting or complex page layout recognition. Matching is heuristic; unknown ingredients are not counted as missing, so always review a recipe before cooking. No backend or cross-device sync. Ingredient amounts are not checked. Export recipes includes cover images but not pantry preferences.
