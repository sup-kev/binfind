# 📚 Project Name

BinFind is an innovative app that helps you locate the nearest trash bins in Tokyo. With just a few clicks, you can find the nearest bin to dispose of your waste and keep the city clean.


![IMG_6250](https://user-images.githubusercontent.com/122064462/224602457-1e2b7e3b-7b8f-406c-a00a-c0ac9fc31d45.jpg)
![IMG_6250](https://user-images.githubusercontent.com/122064462/224602510-5d467b40-fd28-4471-b8a8-3bb510978d66.jpg)
![IMG_6253](https://user-images.githubusercontent.com/122064462/224602516-226dd49e-3f0c-4671-93d8-047bef234a15.jpg)
![IMG_6256](https://user-images.githubusercontent.com/122064462/224602517-e8d5b2a7-0ac8-47cd-8202-15978661949a.jpg)
![IMG_6260](https://user-images.githubusercontent.com/122064462/224602519-0cd15c08-a789-4730-9be1-57622f9e7339.jpg)
<br>

App home: https://www.binfind.online/
   

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
yarn build --watch
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
MAPBOX_API_KEY=your_own_mapbox_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
rails bin:attach_photos
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements


## Team Members
- [Julien Afonso](https://www.linkedin.com/in/julien-afonso-59568124b/)
- [Ruka Okuyama](https://www.linkedin.com/in/luka-okuyama-14b87213a/)
- [Wanyu Jiang](https://www.linkedin.com/in/wanyu-jiang-144195248/)
https://www.linkedin.com/in/kevin-s-tsai/

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
