# Sample repo for a bug request

Launching "ng serve" and "ng serve -ec -sm" changes the order the styles are loaded from styles.scss

Look at:
 - src/styles.scss
 - packages.json: notice the 'start' and 'start:debug' scripts

Then, "npm install" and launch both 'npm run start' and 'npm run start:debug'. 
Then visit localhost:4200 and localhost:3000 to see a difference.
Notice the css is not applicated seamlessly between the two instances of the app.
