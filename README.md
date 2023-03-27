# Portfolio Website

## General Info
Hosted on Google [Firebase](https://console.firebase.google.com/u/0/?pli=1).

Must have Firebase CLI installed to upload changes.
```
npm install -g firebase-tools
```

## Development
To run the site locally
```
npx http-server public
```

To upload changes
1. Make desired changes to files.
2. Log into Firebase with `firebase login`
3. Check for proper access with `firebase projects:list` to get a list of projects. If you receive an error, try logging out with `firebase logout` and logging back in.
4. Upload changes with `firebase deploy --only hosting`
5. Test site at https://rthompson.dev
