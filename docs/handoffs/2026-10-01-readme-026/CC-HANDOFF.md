# GalShelf 0.2.6 README redesign — owner brief for Claude Code

## The owner's request, translated and clarified

Yes, that is the demonstration window I meant. Please present our application with the same level of visual polish as the demonstration you previously selected. Choose attractive material that works well as a coherent showcase: the screenshots should share a consistent style, atmosphere, composition and level of finish.

I have one additional requirement: hide the companion character artwork in the screenshots, but keep the companion feature's button visible and usable. I also feel the current README does not show what is distinctive about GalShelf. Redo the writing and image selection so readers can actually see how the application helps them organise games and what its in-game experience offers.

Show the normal, everyday features as well as the distinctive in-game interface. Good game management matters. Cloud saves and Guard can be explained in expandable details. Having two interface layouts is not a selling point I want emphasised here. Present more of the product visually, using polished, consistent examples rather than a long, undifferentiated feature list.

**Do not change the existing language arrangement. Keep the complete Chinese README first and the complete English version below it on the same repository homepage. Keep a working English jump link near the top and a return-to-Chinese link in the English section. Improve the content and screenshots within that arrangement.**

## Task and scope

Rebuild the public-facing README presentation for the **released GalShelf 0.2.6** in:

- Repository: <https://github.com/Harihi86/galshelf-releases>
- Main README: `README.md`
- Standalone Chinese page: `README.zh-CN.md`
- Screenshot assets: `assets/screenshots/`
- Release truth: <https://github.com/Harihi86/galshelf-releases/releases/tag/v0.2.6> and the versioned release notes/manifests.

Baseline before this handoff: `58c2d31958cea2a7f527bd375dea47b37ce525b6`. That commit implemented the requested Chinese-first / English-below layout. Fetch and inspect current remote state before making changes; preserve subsequent unrelated work.

This task concerns release-repository documentation and showcase media. It is not a new client version, application feature change, installer replacement, release/tag publication or website deployment. Complete the README/media update, commit and push the scoped changes through the repository's permitted workflow, and verify the remote result. Do not create or overwrite release binaries, tags, signed manifests or signatures.

## Non-negotiable requirements

### 1. Preserve the language layout

- `README.md` must contain the full Chinese version first, followed by the full English version on the same page.
- Keep a prominent, functioning `English` hyperlink that jumps to the lower English section; keep an English-section link back to Chinese.
- Keep `README.zh-CN.md` aligned with the Chinese content and point its English link to `README.md#english` or the actual equivalent anchor.
- Do not replace the lower English content with a separate-file link, reverse the order, or hide either complete language version inside a language-switcher or collapsed language block.
- Translate the final revised content faithfully; the two versions should explain the same product and limitations.

### 2. Show the released 0.2.6 honestly

- Capture the released 0.2.6 application, not a 0.2.7 candidate or an HTML recreation of a future interface.
- Confirm the build record and executable identity before capturing. The locally verified released executable SHA-256 is `91a8224e02645b20a0f81688f5c2efb1a8cead5467360f415af676a8f63d5564`.
- Navigate and populate actual product pages; do not draw missing features into screenshots, patch UI markup to imply capabilities, or manufacture successful connection/security states.
- Use the original language of a surface if 0.2.6 has no English translation for it. The in-game menu and capture editor observed in this version use Chinese controls; explain that in the English caption rather than fabricating translated controls.

### 3. Synthetic records and privacy

- Use a fresh, isolated demonstration data directory. Never seed from the owner's installed account, library, saves, notes, screenshots or play history.
- Public work names, cover art, developers and VNDB metadata can be real. The chosen shelf, ratings, statuses, playtime, completion dates, reviews, route notes, tags and personal progress must be invented.
- Maintain one believable, internally consistent demonstration collection across the gallery. A work's rating, playtime and status should agree between the library, records and cards.
- Keep accounts signed out or use an unmistakably synthetic identity. Avoid visible account identifiers, credentials, local usernames, real installation paths, private notifications and unrelated desktop content.
- For in-game demonstrations, use an isolated demo scene/window with suitable project/public artwork and invented dialogue. Clearly distinguish it from footage of an actual commercial game and from real play-session evidence.
- Add a short, readable demo-data disclosure near the first screenshot. Keep source attribution and rights notices concise.

### 4. Hide companion artwork while retaining the feature

- No floating/standing companion portrait or companion thumbnail in the captured sidebar; keep the companion entry icon, button and function available.
- Do not disable the entire feature or remove its navigation entry to achieve this.
- Confirmed 0.2.6 settings for the isolated profile: `ui.illustration = "off"` and `companion.enabled = true`. Verify the resulting screenshots and button, rather than assuming settings alone prove compliance.
- This requirement concerns companion artwork. Game covers, the application background and artwork deliberately placed inside a share card are separate content; choose them coherently.
- Apply screenshot preferences only to the demonstration profile, not to the owner's normal installation.

## Editorial priorities

Use the product's actual appearance and workflows to establish its character. Build a concise visual story, for example:

1. **A useful, attractive game library:** importing and checking matches, a readable cover shelf, status filters, developer/collection grouping, search, and batch organisation.
2. **The in-game experience:** the game menu, taking a screenshot and opening the editor, useful window/scaling controls, locally recognised dialogue and its handoff to a share card. Show real visible operations and states, not only the name of a feature.
3. **Records worth revisiting:** dango ratings, completion/route notes, readable session ticket stubs and continuity between sessions.
4. **Creating something to share:** a completed, attractive card in the real editor, with useful editable layers or controls visible. Prepare an actual composition rather than capturing an empty default canvas.
5. **Other visually useful everyday surfaces:** include Big Picture, Home or reading progress only when the selected shot contributes something distinct. Avoid padding the gallery with repetitive page tops.

This is a priority guide, not a mandatory five-section template. Choose the strongest coherent sequence. The owner wants more visually demonstrated value, not merely more screenshots.

Do not claim exclusivity or superiority over competitors without evidence. Describe concrete user benefits and the workflow that produces them. Replace generic inventories and excessive character dialogue with clear, natural copy, while retaining GalShelf's warm visual-novel atmosphere.

## Art direction and screenshot selection

- The primary visual reference is **the polished demonstration window and coherent material previously selected by CC**, which the owner explicitly referred to. Revisit that reference and its capture setup first.
- The release gallery and original capture setup provide useful secondary references. Preserve the bright, gentle Galgame atmosphere and an intentionally chosen collection of compatible scenes/cards.
- Make the entire set feel curated: compatible palette and wallpaper, consistent viewport proportions and scaling, readable text, deliberate crop/scroll positions, and a balanced amount of interface and artwork.
- Show the part of a page that proves the point. For records, expose the ticket stubs and rating; for creation, expose a finished design and editing controls; for organisation, show an actual selected/grouped/filtered state.
- The abandoned Codex draft included a crude dark geometric “Rainy Bookmark” scene and a mixed gallery. Those are **not an approved visual direction or accepted final assets**. The owner corrected the direction to “beautiful, stylistically consistent and suitable for demonstration.” Rebuild or replace any weak material.
- Reuse appropriate existing project artwork when possible. Keep demo artwork clearly described; never present a made-up scene as a screenshot from a named commercial game.
- Keep product chrome faithful to 0.2.6. Visual cohesion is achieved by selecting and configuring genuine content, not repainting controls or hiding limitations.
- Prefer a few strong, legible images with meaningful captions. Smaller previews may link to full-resolution originals. Keep asset sizes practical for GitHub.

## Secondary details and factual boundaries

Put these in concise expandable feature-detail sections, rather than making them the hero:

- **Cloud saves and shelf sync:** distinguish game-save backup from account/library-record sync. Describe upload, sync and restore directions accurately. The public 0.2.6 package does not include the application registrations required for direct Google Drive/OneDrive connections; a cloud-client-synchronised local folder is the available documented route.
- **Guard and identity:** describe the optional Guard component, file-change checks, scanning/quarantine and repair carefully. A changed file is not automatically malware; work fingerprint identification is not a security guarantee. The 0.2.6 release notes say the first maintainer-signed fingerprint dataset had not yet been published. Do not imply successful identification or coverage that the demonstrated release does not have.
- **Appearance and discovery:** custom backgrounds, discovery, calendars, characters and companion configuration can be supporting details. Explain linked-service prerequisites where relevant. Do not position the A/B layout switch as a headline differentiator.
- **Installation and updates:** retain practical Windows/WebView2 requirements, whole-ZIP extraction, version-specific download links, data-location guidance and useful verification instructions. Do not modify signed updater artifacts.

## State left by Codex

Only the earlier language-order change is on `main`. No redesigned README or replacement screenshot from the interrupted effort was published.

There are local exploratory drafts, capture helpers and an isolated demo profile; their machine paths are provided in the owner's local handoff copy. Treat these as optional reference material, not a finished handoff implementation. Some captures have incomplete English coverage, weak composition or inconsistent demo details and need replacement.

The owner stopped native window automation with Escape, then explicitly reassigned this work to CC. Respect the owner's current desktop activity and inspect any existing isolated processes before starting or closing anything. Do not terminate all GalShelf processes or disturb the installed client.

## Completion checklist

- Full Chinese above full English; both language jump links work.
- Chinese standalone page and main Chinese section agree.
- Build identity is 0.2.6; screenshots show real application surfaces.
- Synthetic data is coherent and no real personal information is visible.
- Companion portraits are absent, but the companion feature button remains visible on applicable desktop pages.
- The image set is attractive and visually consistent with the accepted CC demonstration reference.
- Everyday management and the in-game experience are visibly prominent; two-layout marketing is not.
- Saves/Guard have accurate expandable details and prerequisites.
- Review every final image at readable size. Check image paths, anchors, proportions, wording, file sizes and actual rendered Markdown.
- Inspect the final diff, commit/push only the documentation/media changes, and verify the remote commit.
- Report the final README link, commit SHA, chosen screenshots, what changed and any remaining limitations. Do not describe unverified native/gamepad/cloud behaviour as tested.
