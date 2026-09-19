CS2 Low Float Tracker v6

Upload these files to the root of your GitHub Pages repository, replacing the old ones:
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

New in v6:
1) "Проверено"
   - Opening a Steam link automatically marks the skin as checked.
   - There is also a ✓ button for manual marking.
   - The card shows "проверено X мин/ч/дн назад".
   - Sorting "Давно не проверял" puts never/oldest checked skins first.

2) Free Steam balance
   - Set your current free Steam balance in Statistics.
   - New purchases automatically reduce it.
   - When the same tracked trade is marked Sold, the balance increases by the sale amount after the configured Steam fee.
   - Editing/deleting tracked trades reverses/recalculates their balance effect.
   - Steam deposits increase the free balance automatically.
   - Old pre-v6 trades are NOT retroactively applied to the balance.

3) Sorting
   - Priority
   - Price ascending / descending
   - ROI descending
   - Sales/day descending
   - Float ascending
   - Longest since checked

4) Favorites
   - Tap ☆/★ on any skin.
   - Use the "⭐ Избранное" filter to show only favorites.

Existing localStorage keys are preserved so old saved Steam links/settings continue to work.
