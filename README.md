This App connects to NYtimes Books Api and returns top seller books and basic information about them according to New York times.

User can add queryParameter called "top" in order to return more books .

In case if queryParameter "top" is not defined, App will return best of 3 books .

App has one endpoint /NewYorkTimesBestSeller

Example requests for NewYorkTimesBestSeller:

'http://localhost:8081/NewYorkTimesBestSeller'

'http://localhost:8081/NewYorkTimesBestSeller?top=5'
