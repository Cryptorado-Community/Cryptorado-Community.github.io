# Cryptorado Community Website

### Live at: https://cryptorado.org

A community run and maintained website that **anyone can host** and contribute to.
It is the place to find out what is going on in the Cryptorado & Web3 community.
Resources live here to connect, learn, and get involved in all that is going on in the community!

## Development

This is a simple HTML site, no frameworks 😸 .

### Local update-on-change `live-server`

Open up the containing directory in a terminal and use the command:

```bash
cd site
npx live-server
```

This will serve the website in your default browser on `127.0.0.1:8080` by default and has live-reload on any file changes in `./site`.

### Deploy

Automated on github pages.

## Architecture and Features:

The site aims to be _static_ and _client side only compute (or integrated API calls for distributed compute)_ to enable one to completely own and manage their own data on the site, and are _incentivized_ to host and run operations related to the site.
(see [Desired Architecture and Features](https://github.com/Cryptorado-Community/Cryptorado-Quasar#desired-architecture-and-features) in the archived old version of the site)

### Static Website

Desire no server side compute needed.
Everyone who hosts our resources can be a server and client.
What does a static site model provide?

- Optimized SEO
- Lightning fast and light to host and load
- Flat pages as database
- Can be tracked in a Git repo - so history is maintained and easy to host among distributed peers

#### Distributed Backend

API to Web3 services to hold the events calendar (replace google) would be an awesome addition!

##### Self hosted site:

Want a very easy onboarding process - just install and you are a host + node for all the community resources.
To host the site under our own domain on IPFS, [this is pretty comprehensive](https://gist.github.com/claus/1287f47b5fbaaea338ac8a04d02bf258).

## Built with OSS

- Site Template: `Directive by HTML5 UP` (html5up.net)
- [Icons](https://iconfinder.com/)
- Tooling: [jQuery](https://jquery.com), [Responsive Tools](github.com/ajlkn/responsive-tools)
