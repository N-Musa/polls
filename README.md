### Polls


this API is bare-bones. has no routing/controllers.

view [Here](https://api-fed-election-votes.herokuapp.com/results).

You can make GET, POST, PUT, DELETE etc requests to this API

## Usage/Examples

```javascript
(async function fetchData() {
    const URL = `https://api-election-data.herokuapp.com/federal_election_votes`
    const res = await fetch(URL);
    const data = await res.json();
    console.log(data);
})()
```
