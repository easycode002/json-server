## What is JSON-Server?
>[!NOTE]
> JSON Server is a simple yet powerful tool frontend developers use to create a mock REST API for development and testing purposes. It allows front end developers to develop a full fake REST API with zero coding in seconds.

## Two method JSON-Server
#### Global install
`npm install -g json-server`
- This command installs the json-server package globally on your system. can be used from any directory in your terminal or command prompt.
```
npm install -g json-server
```

#### Locally install
`npm install json-server`
- This command installs the json-server package locally in the current project directory. The package will be placed in the `node_modules` directory of your project.
```
npm install json-server
```

#### Usage
> Create a db.json or db.json5 file
```
{
  "posts": [
    { "id": "1", "title": "a title", "views": 100 },
    { "id": "2", "title": "another title", "views": 200 }
  ],
  "comments": [
    { "id": "1", "text": "a comment about post 1", "postId": "1" },
    { "id": "2", "text": "another comment about post 1", "postId": "1" }
  ],
  "profile": {
    "name": "typicode"
  }
}
```
##### Pass it to JSON Server CLI
```
npx json-server db.json
```
##### Get a REST API
Pass it to browser:`curl http://localhost:3000/posts/1`
It will be show like this
```
{
  "id": "1",
  "title": "a title",
  "views": 100
}
```
![json vs obj](https://github.com/user-attachments/assets/71753308-a704-45db-90d5-6df2755ef9bb)

<div align="center">
  <h1>The End - JSON Server</h1>
</div>
## Contact
Your Name - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/your-username/your-repo-name](https://github.com/your-username/your-repo-name)
