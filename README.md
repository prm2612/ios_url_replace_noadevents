# ios_url_replace_noadevents

Before running the code, you will need to generate a valid DAI URL. To do so, follow these steps:
1. Go to: https://developers.google.com/interactive-media-ads/docs/sdks/html5/dai/testing-dai?streamType=live&streamFormat=hls&assetKey=kZSVNX98RMGd1H3VEAkNGg
2. Load the stream and copy the master manifest path from network logs.
3. In the code, in the VideoViewController class on line 536, replace the manifest path with what you copied in #2.
