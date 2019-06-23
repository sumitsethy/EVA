![](https://i0.wp.com/syncedreview.com/wp-content/uploads/2017/05/32.png?resize=372%2C171&ssl=1)

![](https://2.bp.blogspot.com/-HQo2Kx39Q6A/WsqZQn5pJHI/AAAAAAAAVhY/FBkgOeS06vQNvZN2KI2hhGZmfS1cNPg8wCLcBGAs/s1600/enasdiscoverednetwork.png)

Below is the Receptive field calculation for the above ENAS network using the above formula.

| Layer(conv/stride) | Receptive field (rout) | Jump (Jin) |
| :----------------: | :--------------------: | :--------: |
|         -          |           1            |     1      |
|       7x7/2        |           7            |     1      |
|     3x3/2 (MP)     |           11           |     2      |
|       3x3/1        |           19           |     4      |
|     3x3/2 (MP)     |           27           |     4      |
|   inception(3a)    |           59           |     8      |
|   inception(3b)    |           91           |     8      |
|     3x3/2 (MP)     |          101           |     8      |
|   inception(4a)    |          171           |     16     |
|   inception(4b)    |          235           |     16     |
|   inception(4c)    |          299           |     16     |
|   inception(4d)    |          363           |     16     |
|   inception(4e)    |          427           |     16     |
|     3x3/2 (MP)     |          459           |     16     |
|   inception(5a)    |          587           |     32     |
|   inception(5b)    |          715           |     32     |
|     7x7/1 (AP)     |          907           |     32     |

Final Receptive Field is 907x907.



