# Shop history data

One file per day: `shop-YYYY-MM-DD.json` — the raw response of
`https://fortnite-api.com/v2/shop` for that day (UTC date).

Files are added automatically every day by the
"Save daily shop snapshot" GitHub Actions workflow
(`.github/workflows/save-shop.yml`), and can also be added by hand
from the Actions tab ("Run workflow").

This history powers FortShop's predictions (likely-to-return items),
price history, and rarest-skins features.
