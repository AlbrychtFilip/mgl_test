


## Installation
Run `npm install` command in root folder and backend folder
```
npm install 
```
## How to Run

```
npm run dev 
```


fixes:
1. migration missing , in backend/src/db/new_mgldefi.sql line 213
2. sending emails doesnt work because of wrong credentials - new values required
3. confirm_password - no need to send that
4. added check on verify email to not allow to verify email if already verified


Also I added some comments in code, check falbrycht phase