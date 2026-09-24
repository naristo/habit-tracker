Option A: Vercel Global Config (Recommended for Ultra-Low Latency Reads)
In the Vercel Dashboard, go to Storage > Create Database.
Select Global Config (Ultra-low latency reads).
Give your store a name (e.g. habit-tracker-global-config) and click Create.
Connect it to your Vercel Project. Vercel will automatically inject:
EDGE_CONFIG or GLOBAL_CONFIG_TOKEN
The habit tracker app will automatically detect these credentials in your Vercel environment!

Option B: Vercel Blob (Fast Object & JSON File Storage)
