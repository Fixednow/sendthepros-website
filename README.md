# Send the Pros — website

The public homepage for sendthepros.ie: what Send the Pros does, how it works,
and the two ways in ("I need help" for customers, "I'm a pro" for Partners).

Plain static HTML, no build step.

## Deploy on Render

New → Static Site → this repo, then:

- Build Command: *(leave empty)*
- Publish Directory: `.`

## Links to the apps

The buttons point at the two apps. Change these in `index.html` once the
apps have their own addresses (e.g. app.sendthepros.ie and partner.sendthepros.ie):

- Customer app: https://fixednow-customer-web.onrender.com
- Partner app: https://fixednow-provider-web.onrender.com
