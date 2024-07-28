<p align="center">
  <br/>
  <img src="https://private-user-images.githubusercontent.com/2731362/352783188-fd5da8d5-2164-4742-accf-e2299a9409c4.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjIxMjcyNzQsIm5iZiI6MTcyMjEyNjk3NCwicGF0aCI6Ii8yNzMxMzYyLzM1Mjc4MzE4OC1mZDVkYThkNS0yMTY0LTQ3NDItYWNjZi1lMjI5OWE5NDA5YzQuanBlZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MjglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzI4VDAwMzYxNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWY4OGM0NTcwMmJiMTRhNzI3ZmU4NWI4NTBhY2Q2MmJlNjM5OWFjOWJlZGIzNThmMTA4NDdiYzkwNDFhNjdiNzUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.ZpUQguhqhbig-J9_9EH730qnc7MrylqnMnEvY8Xkydk" alt="Audius Logo" width="200">
  <br/>

  <p align="center">
    <b>Blinks On Workers</b>
  </p>
</p>

<p align="center">60 second forkable starting point to set up a Blink and deploy it on Cloudflare Workers using the donation example</p>

<br/>
<br/>


1. Create a free Cloudflare account https://dash.cloudflare.com/ and install ngrok https://ngrok.com/

2. Fork this repo

3. Install deps
```
npm i
```

4. Update your blink name in wrangler.toml

5. Test your blink
```
npm run dev
ngrok http 8787
```

6. Check out your blink at `https://dial.to/?action=solana-action:https://<your-ngrok-link>`

7. Deploy blink
```
npm run deploy
```

8. Make updates to the code in `index.ts` to your liking


Check out the [Dialect docs](https://docs.dialect.to/documentation/actions/guide-integrate-blinks-into-your-client) for more.
