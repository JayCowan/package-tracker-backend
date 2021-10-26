# Package Tracking App Backend W/ Firebase
Create your own firebase project (same as the one for web/flutter), fork this repo and run `firebase init` to set this up for your firebase project.
Run your own github actions with hosting, as it will not work otherwise for automated deployment. 

### To Set Up Security Rules: 
Either take from the example or write your own from:
1. Run `npm install -g firebase-bolt`
2. Create a file `security-rules.bolt`
3. Write your security rules in `security-rules.bolt`
4. Run `firebase-bolt security-rules.bolt` to compile your security rules. 
5. Rename the generated file `database.rules.json`.