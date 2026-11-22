# ClosetIQ — Shop What You're Missing

A no-backend, wardrobe-aware shopping hackathon prototype. It runs directly on GitHub Pages.

## What it does

- **My Closet:** View, add, photograph, and remove owned clothing.
- **Style DNA:** See wardrobe mix, dominant colors, and inferred category gaps.
- **Shop My Gaps:** See ranked demo products and calculated outfit combinations; adjust the price cap.
- **Live updates:** Removing or adding clothing immediately recalculates insights and recommendations.
- **Privacy:** No account, server, API key, or tracking. Wardrobe and photos are saved in browser `localStorage`.

## Publish on GitHub Pages (no command line)

1. Create a new repository on GitHub, e.g. `closetiq-hackathon`.
2. Upload **index.html** and **README.md** to the repository root using **Add file > Upload files**, then commit.
3. Open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main**, folder **/(root)**, and click **Save**.
5. Wait for GitHub Pages to publish, then open `https://YOUR-USERNAME.github.io/closetiq-hackathon/`.
6. Test in a private/incognito browser window before submitting.

GitHub repository: `https://github.com/YOUR-USERNAME/closetiq-hackathon`

## Suggested demo

1. Open **My Closet** and show 12 sample owned items.
2. Open **Style DNA** to show the missing-layer signal.
3. Open **Shop My Gaps** and explain the ranked olive overshirt and outfit combinations.
4. Return to **My Closet**, remove the denim jacket, and show the updated gaps and recommendations.
5. Adjust the budget slider to show responsive filtering.

## Important limitations

- Photo uploads require **manual tagging**; the app does not claim AI photo recognition.
- Product names/prices are **illustrative mock catalog data**, not live retailer offers.
- Gap detection uses category reference targets, not proof that an item is missing.
- Outfit combinations are computed from simple color/style compatibility rules, not fit prediction.
- Large photos may exceed browser storage quotas. Keep images under 4 MB and preferably smaller.
- Data is stored per browser/device. It is not synced between users.

## Stack

Plain HTML, CSS, and JavaScript. No dependencies, build step, backend, or API keys.

## Hackathon pitch

**Problem:** Conventional retail recommendations do not consider the clothing customers already own, encouraging repetitive purchases.

**Solution:** ClosetIQ identifies wardrobe coverage and recommends purchases based on the new combinations they can create with confirmed owned garments.

**Differentiator:** Shopping for incremental wardrobe value, not just visual similarity or click propensity.
