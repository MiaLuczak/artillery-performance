# <p align="center">GoIT - HW 5 </br>Artillery performance testing</p>

## <p align="center">Main goal</p>

The main goal was to make performance tests in Artillery

## <p align="center">Resources used</p>

- Artillery

  > npm package </br> [Link to package](https://www.npmjs.com/package/artillery)\

- Fake Shop API

  > [Link to API](https://fakestoreapi.com/) </br>
  > _Credits of API goes to their respective owner_

## <p align="center">Files info</p>

- [test.yml](./test.yml)

  > Main test file, with test config and test flow for Artillery

- [cart_content.csv](./cart_content.csv)

  > CSV file, that provides external informations to `test.yml` file

## <p align="center">Execution</p>

|           |          |        Tests        |        |        |
| :-------: | :------: | :-----------------: | :----: | :----: |
|   Name    | Duration | Vusers arrival rate | Passed | Failed |
| Load Test |    10    |          1          |   x    |        |

</br>
Note: </br>
_Due to use of public free APIs, and to ensure their uptime, all tests are shorter with smaller ammount of VUsers_

</br>
Planned Load Test with real values (avarage ammount of users in normal shop per hour):

|           |           |    Planned Test     |        |        |
| :-------: | :-------: | :-----------------: | :----: | :----: |
|   Name    | Duration  | Vusers arrival rate | Passed | Failed |
| Load Test | 7200 (2h) |         10          |        |        |
