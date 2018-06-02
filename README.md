# bitbucket-server-api

## Usage

```javascript
const BitbucketServerApi = require('bitbucket-server-api');
const api = new BitbucketServerApi('https://www.example.com', 'user123', 'secret');
const repos = api.getRepos('ABC');
repos.then(
  (repos) => {
    repos.forEach(
      (repo) => console.log(repo.name);
    )
  }
);
```
