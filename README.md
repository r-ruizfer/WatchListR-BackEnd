# Project Name

This repository is a [json-server](https://github.com/typicode/json-server) created to feed data into the React Application below.

#### [Client Repo here](https://github.com/r-ruizfer/WatchListR-FrontEnd)

# Server Structure

## Collections

### personalWatchLists

```javascript
{
  name,
  poster_path,
  id,
  genres:[
    {
        id,
        name
    }
  ],
  rating,
  status
}
```

## Used API Endpoints in the App

| HTTP Method | URL                     | Request Body        | Description                   |
| ----------- | ----------------------- | ------------------- | ----------------------------- |
| GET         | `/personalWatchlists`   |                     | Sends all series              |
| POST        | `/personalWatchlists`   | {rating, watchlist} | adds a series to my list      |
| GET         | `/watchlists/:seriesId` |                     | Sends all details of a series |
| DELETE      | `/watchlists/:seriesId` |                     | Deletes a series from my list |
| PATCH       | `/watchlists/:seriesId` | {rating, watchlist} | Edits series info             |

## Links

### Collaborators

[Enrique Paez](https://github.com/enriquepaez)

[Ruben Ruiz](https://github.com/r-ruizfer)

### Project

[Repository Link Client](https://github.com/r-ruizfer/WatchListR-FrontEnd)

[Repository Link Server](https://github.com/r-ruizfer/WatchListR-BackEnd)

[Deploy Link](https://watchlistrih.netlify.app/)

### Slides

[Slides Link](https://docs.google.com/presentation/d/1scOEHRTyLoO-AQEKXj7lb90xm0zJ2DyGXGN3HxBtHzs/edit#slide=id.g308410ea4d3_0_29)
