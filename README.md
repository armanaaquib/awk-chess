# awk-chess
Welcome to Awk Chess

<img width="582" alt="image" src="https://user-images.githubusercontent.com/44823431/178434373-a84c2179-51a5-4e80-9c9a-6899a43b9d12.png">


## How to start

```
> awk -f chess2.awk
```

## How to play
Please read guide carefully before playing:

| Pieces | Options | Action |
| ------ | ------- | ------ |
| Pawn   | ff   | to go forward two step if it is pawn's first move |
|        | f    | to go forward one step |
|        | fr   | to go forward right one step |
|        | fl   | to go forward left one step |
| Knight | fr   | to go 2 steps forward and 1 step right |
|        | fl   | to go 2 steps forward and 1 step left |
|        | br   | to go 2 steps backward and 1 step right |
|        | bl   | to go 2 steps backward and 1 step left |
|        | rf   | to go 2 steps right and 1 step forward |
|        | rb   | to go 2 steps right and 1 step backward |
|        | lf   | to go 2 steps left and 1 step forward |
|        | lb   | to go 2 steps left and 1 step backward |
| Rook   | l n  | to go left n steps |
|        | r n  | to go right n steps |
|        | f n  | to go forward n steps |
|        | b n  | to go backward n steps |
| Bishop | fr n | to go forward right diagonally n steps |
|        | fl n | to go forward left diagonally n setps |
|        | br n | to go backward right diagonally n steps |
|        | bl n | to go backward left diagonally n steps |
| Queen  |      | all Rook and Bishop options |
| King   |      | all Rook and Bishop options withou [n] option |

### Input Format:
> boxpos option [n]
##### Example:
> a7 f <br />
> b2 ff <br />
> b8 fr <br />
> a8 r 1 <br />
> c8 fr 3 <br />
> f5 br 2 <br />
> a6 b 5 <br />
