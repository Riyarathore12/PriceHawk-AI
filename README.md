# PriceHawk AI — Day 05/30
Shopping comparison prototype using SerpAPI Google Shopping, RapidFuzz title matching, Streamlit, SQLite and optional Gemini. Demo mode uses illustrative prices. Live coverage depends on provider. Verify variants and checkout totals; title matching is not exact identity. History records live search observations only. Wishlist is local. No background alerts or forecasting implemented.

## Run
`pip install -r requirements.txt` then `streamlit run app.py`. Enter API keys in sidebar or set SERPAPI_KEY and GEMINI_API_KEY environment variables. Never commit keys or private databases. Gemini receives listing data only with consent. Use demo mode for public screenshots.

## Shop by Image
Choose Search by Image, upload a JPG, PNG or WebP (up to 8 MB), grant consent and click Identify product from image. Gemini generates an editable shopping phrase. Click Search prices to retrieve listings through SerpAPI. This is image-to-text shopping search, not reverse-image matching; similar products are not necessarily identical. Demo prices are illustrative. Images are sent to Gemini only after consent and are not saved by the app.
