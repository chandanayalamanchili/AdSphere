# AdSphere
Developed a cross-platform app for personalized offline ads using online data. Implemented the UI with React, backend with Node.js, and database with MongoDB Atlas. Used DSA to map
customers to targeted ads, following Agile methodology.
### Installing NODE modules
We don't push ```node_modules``` folder to the main repository because it consumes a lot of space, and is not efficient. All the modules with the versions which are used will be listed in ```package.json``` file. The following command will directly install all modules in the ```package.json```
```
    npm install
```
(in both frontend and backend).

### Files / folders in the ```.gitignore``` will ge ignored, and won't be pushed
```node_modules``` is one of such.

---
### Development environment
- In frontend, React automatically re-renders if any changes are noticed.
- But in backend, this is not the case. So, we are using a dev dependency called ```nodemon```.
- ```npm start``` - static, won't restart on code changes
- ```npm run dev``` - development mode, restart on every code change.

Summing this, in frontend,
```
    npm start
```

In backend,
```
    npm run dev
```
