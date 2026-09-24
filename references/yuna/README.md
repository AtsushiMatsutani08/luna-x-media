# YUNA reference images

These are YUNA's approved visual references for X and note images. Preserve the same character identity across images. The selfie used in X posting is at [`../../media/yuna/yuna-morning-2026-09-23-selfie.jpg`](../../media/yuna/yuna-morning-2026-09-23-selfie.jpg); check it together with the boards below.

- `official-reference-board.jpeg`: primary face and pose board.
- `official-image-guide.jpeg`: daily selfie, outdoor, note and X visual guide.
- `scene-walk-cafe.jpeg`, `scene-outdoors.jpeg`, `day-in-life.jpeg`: natural setting and camera angle examples.
- `face-bun.jpeg`, `face-hair-down.jpeg`: close facial detail references only. Do not repeatedly copy their hand-on-cheek pose or head tilt.

For each new thumbnail, keep the original gentle and approachable expression. Vary the gesture and camera angle; avoid repeated hand-on-face and tilted-head compositions. Do not imply that a product was purchased or used if it was not.

Source: seven master images supplied by the account owner on 2026-09-24.

## Identity lock workflow — mandatory

LUNA, the SNS & MEDIA team, and YUNA must all enforce this gate before any YUNA image is approved or published:

1. Fetch the designated PRIMARY MASTER image from GitHub as actual image data before generation.
2. Pass that actual image as a reference-image input to a reference-capable generator. A text-only instruction such as "same YUNA" is prohibited.
3. Use one PRIMARY MASTER for facial identity. Other boards/images may guide pose, outfit, camera angle, and setting only; they must not override or average the face.
4. After generation, compare the result against the PRIMARY MASTER. Reject any result with materially different facial identity.
5. LUNA performs publishing QA: verify identity, non-duplicate recent image, post/context fit, and media validity before queueing.
6. If the PRIMARY MASTER cannot be fetched or cannot be supplied as an actual reference input, FAIL CLOSED: do not generate and do not publish.
7. Never claim an image was reference-generated unless the generator call actually contained the reference image.
8. Free-first operation: prefer previously approved YUNA assets; use paid/credit generation only when necessary.

Approval chain: YUNA identity check -> SNS & MEDIA visual QA -> LUNA final publish gate.
