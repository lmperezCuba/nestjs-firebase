# Instructions

## Development

### Add Firebase Functions

- `firebase login` cli auth.
- `firebase init functions` cli functions setup.


### Deploy functions
- `firebase deploy --only functions` deploy "only" edited functions.
- `firebase deploy --only functions:addMessage,functions:makeUppercase` deploy a simple function to avoid a 429 error.

### Delete functions
- `functions:delete`  delete previously deployed functions.
- `firebase functions:delete myFunction` Delete all functions that match the specified name in all regions.
- `firebase functions:delete myFunction --region us-east-1` Delete a specified function running in a specific region.
- and more commands at https://firebase.google.com/docs/functions/manage-functions?gen=2nd