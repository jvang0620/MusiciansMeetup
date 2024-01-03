# Musicans Meetup

<!-- Event Listing -->

![Musicans Meetup Event Listing](/public/images/img-readmeMd/eventlistings.PNG)

<!-- Description of App -->

This Fullstack MVC Express.js application serves as a dynamic and engaging social media platform tailored for seamlessly hosting and coordinating both in-person and virtual activities, gatherings, and events. It provides a centralized hub for individuals and communities with shared interests, hobbies, and professions to come together and connect. Whether it's organizing a local meetup, planning a virtual workshop, or coordinating a professional networking event, the platform empowers users to create, discover, and participate in a wide array of activities that resonate with their passions and preferences. With its intuitive interface and robust features, the application fosters a sense of community, making it easier for like-minded individuals to build connections and share meaningful experiences.

Musicans Meetup was my final project for ITSC 4166 at UNCC with additional feastures added by myself.

> Adhering to the REST architectural style, this application guarantees a user-friendly and intuitive experience when it comes to exploring, participating in, adding, and editing music events.

<!-- Features includes -->

## Features

- User sessions; authentication using bcrypt
- Event creation
- Event RSVP feature
- Input validation and santization using express-validator
- Flash messages for user feedback using connect-flash
- File upload capabilities using express-fileupload
- Data storage using MongoDB Atlas

<!-- Build with -->

### Build With

[![Node][Node.js]][Node-url]
[![Express][Express.js]][Express-url]
[![Bootstrap][Bootstrap.com]][Bootstrap-url]
[![MongoDB][MongoDB]][MongoDB-url]
[![Mongoose][Mongoose]][Mongoose-url]

<!-- Getting Started -->

## Getting Started

To run Musicans Meetup on your local machine, please follow the steps below:

1. Clone the repository to your local machine one of the following:
   HTTPS: <pre><code>git clone https://github.com/jvang0620/MusicansMeetup.git</code></pre>
   SSH: <pre><code>git clone git@github.com:jvang0620/MusicansMeetup.git</code></pre>

2. Install [Node](https://nodejs.org/en "Node Homepage") and install the necessary dependencies by running `npm i` in the project root directory:

3. Create a `.env` file in the root directory of the project following the `.env.sample` as a guide:

4. Start the server by running `npm start`:

5. Navigate to `http://localhost:3000` or `http://<env.HOST>:<env.PORT>` in your browser to access Musicans Meetup

<!-- MARKDOWN LINKS & IMAGES -->

[product-screenshot]: public/images/screenshot.png
[Node.js]: https://img.shields.io/badge/node.js-7FC729?style=for-the-badge&logo=nodedotjs&logoColor=white
[Node-url]: https://nextjs.org/
[Express.js]: https://img.shields.io/badge/express-EEEEEE?style=for-the-badge&logo=express&logoColor=black
[Express-url]: https://expressjs.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[MongoDB]: https://img.shields.io/badge/MongoDB-F5F7FA?style=for-the-badge&logo=mongodb&logoColor=6BA242
[MongoDB-url]: https://www.mongodb.com/
[Mongoose]: https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=FFFFFF
[Mongoose-url]: https://mongoosejs.com/
