# About ToDoList
ToDoモデルを親とし、ToDoDaily, ToDoWeekly, ToDoMonthlyを子とする。
子要素は必須ではなく、ToDoモデルのdaily, weekly, monthlyの絡むがtrueとなるidの予定にのみ存在する。  
なお、日付などが決まった際、それに応じて他の子要素にもデータを追加する。

## ToDo
- title     (t.string)
- body      (t.text)
- daily     (t.boolean)
- weekly    (t.boolean)
- monthly   (t.boolean)
- finished  (t.boolean)

## ToDoDaily
- todo_id
- date

## ToDoWeekly
- todo_id
- week

## ToDoMonthly
- todo_id
- month