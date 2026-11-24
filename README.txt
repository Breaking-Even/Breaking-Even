BREAKING EVEN — NOVEMBER EDITION
Website installation and maintenance guide

1. Extract the ZIP (Windows: right-click > Extract All; Mac: double-click).
2. Open the extracted folder. Double-click index.html to preview in a normal browser. Keep all files and subfolders together. No installation or server is required for ordinary local preview; browser restrictions may affect local audio/storage.
3. Before publishing, confirm you have permission to reuse each supplied photograph and complete its credits in references.html. The image-credit checklist below identifies each file. The watermarked Adobe Stock image from the scenario introduction was excluded. No generated images are used.
4. Back up your existing GitHub repository: open the repository, choose Code > Download ZIP, and save it separately. Work with your teacher/group if you need permission to update the site.
5. Open https://github.com/omcg123/Breaking-Even-1 (assuming this remains your repository). On the Code tab, choose the branch used by GitHub Pages, then Add file > Upload files. Drag in the CONTENTS of the extracted website folder, not the outer folder or ZIP itself. Keep index.html, edition.html, definitions.html, scenarios.html, quiz.html, references.html, style.css, script.js, content.js, .nojekyll, images/ and audio/ together at the same level. README.txt is optional. Confirm the paths in the upload list. Commit changes. Existing files of the same name will be replaced; do not delete unrelated files unless you have a backup and permission.
6. Go to Settings > Pages. If Pages already uses the correct branch and folder, leave it alone. Otherwise select Deploy from a branch, the branch you uploaded to (usually main), and / (root). Save. If your existing site uses a docs folder or an Actions workflow, keep that configuration and place these files in its publishing source instead.
7. Check the Pages deployment in Actions and open https://omcg123.github.io/Breaking-Even-1/ after the deployment succeeds. Check every next-page link, menu button, flashcard, scenario and quiz. If an old design appears, refresh the browser or try a private window. If you see a 404, check the publishing branch/folder and ensure index.html is directly inside it.
8. When the podcast is recorded, export as an MP3 and rename it exactly november-edition.mp3. Upload it to the audio folder on the same publishing branch. Its full path should be audio/november-edition.mp3. Commit. The player is already configured to load it. Verify playback after deployment. GitHub browser uploads have file-size limits; compress the MP3 or use Git if necessary. Do not post recordings without the consent of the people recorded.
9. Update definitions and quiz questions in content.js (correct answer indices 0=A, 1=B, 2=C, 3=D). The scenario feedback and policy outcomes also live there. Page introductions and scenario prompts live in their corresponding HTML files. Edit style.css for design changes. Do not change file names unless you also update links. Keep a backup before editing.

CONTENT AND REVIEW NOTES
- The supplied Word document is the source for all 17 definitions, 20 quiz questions, five scenario situations, outcomes and headlines. Navigation names follow the requested six-page order. The final next-page button returns to Overview.
- The document had no separate reference list or image source links; five relevant background links from the earlier conversation have been checked using search results and included, along with the textbook reference. They are not confirmed as your exact podcast sources. Add those if different.
- Q8 option C accidentally combined a distractor with the intended correct answer; the corrected option is “Vaccination reduces the spread of Covid 19, benefiting other people in society.” Answer key C unchanged. Q6 option A and Q18 option B received small typo corrections. Q3's explanation was shortened to the non-operational purpose of forest clearing; answer D unchanged. Scenario prompts omit implementation instructions and use direct visitor-facing controls. The duplicate forest depletion sentence in the steel scenario was omitted as it belongs to the forest topic and is already conveyed there. The scenario wording otherwise follows the document, including the revised feedback. Review before publishing.
- Audio is intentionally not included. Scenario completion is stored in the current browser where local storage is available; quiz results are local and not sent to teachers or collected centrally.
- Images are extracted from your Word document and resized for the web. Their provenance, licences, accuracy as depictions of named locations, and original credits are unverified. Confirm permission and exact captions before public publishing; replace anything you cannot clear. Do not assume an image being online means it is free to use.
- Testing: JavaScript syntax, page links, navigation structure, image files, quiz data and scenario arithmetic checked. Full real-browser click-through and visual QA could not be performed because browser navigation is blocked in the creation environment. Use the preview steps above to verify on your device.

IMAGE CREDIT CHECKLIST (add actual author, source URL and licence)
images/forest-headline.jpg — forest fire headline (Word p.1)
images/steel-headline.jpg — industrial plant headline (p.2)
images/books-headline.jpg — books headline (p.2)
images/flood-headline.jpg — flooded street headline (p.3)
images/asic-headline.jpg — ASIC headline (p.3)
images/newspaper.jpg — newspaper image (p.4)
images/economics.jpg — economics print (p.6)
images/forest-scenario.jpg — forest scenario (p.8)
images/steel-scenario.jpg — steel scenario (p.10)
images/books-scenario.jpg — books scenario (p.12)
images/flood-scenario.jpg — flood scenario (p.13)
images/asic-scenario.jpg — ASIC scenario (p.15)
