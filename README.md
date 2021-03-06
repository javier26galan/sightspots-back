# SightSpots

SightSpots is an app prototype for tourism. Through a clean CMS, admins can create, modify and delete location entries for places of tourist interest (museums, religious buildings, parks...). Upon registration, users can interact with the locations views in several ways.

This repository is the API to which the app connects. It contains the endpoints and controllers needed to register/authenticate users and to create/modify/delete the location entries.

## Resources

The back end of the SightSpots project is made with Node.js and Express. Other core dependencies are:

- Authentication: Passport local, bcrypt, Express session, Connect Mongo
- Database: MongoDB via Mongoose
- Image uploading: Multer, streamifier, Cloudinary
