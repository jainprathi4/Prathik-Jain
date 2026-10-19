NPMU- Predictive Engine Intelligence — website deployment

1. Extract this package.
2. Open Netlify Drop: https://app.netlify.com/drop
3. Sign in or create a Netlify account if prompted.
4. Drag the extracted folder named 'npmu_website_deploy' into the deploy area.
5. Wait for deployment and open the generated website URL.

Notes:
- Keep index.html at the root of the deployed folder.
- This is a static website. Training data and analysis history are saved in the browser's local storage, not synced to other users/devices.
- Excel (.xlsx/.xls) import loads a reader library from a CDN and therefore needs an internet connection. CSV is the most reliable format.
- Do not upload confidential vehicle data unless you are comfortable with the hosting provider's terms and access settings.
