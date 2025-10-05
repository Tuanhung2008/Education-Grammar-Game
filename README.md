# Education-Grammar-Game
Ý tưởng từ tựa game Rise of Kingdoms, đố vui minigame giữa học sinh trong lớp
## 📚 Một website học tập đơn giản
> Có thể áp dụng với tất cả các môn học **dạng trắc nghiệm** và giúp nâng cao chất lượng bài giảng

### Hướng dẫn thay đổi câu hỏi
Bạn vào **cqz/lib/questions.ts**
```  {
    question: "I _____ TV when the phone rang.",
    options: ["watched", "was watching", "watch", "am watching"],
    correctAnswer: 1,
    explanation: "We use Past Continuous (was watching) for an action in progress when another action interrupted it.",
    difficulty: "easy",
  },
```
Một số **định nghĩa** trong phần này bạn có thể chỉnh sửa

> ``` question: "Câu hỏi bạn muốn đặt vào"``` <- thay đổi thành câu hỏi mà bạn muốn
> 
> ``` options: ["đáp án 1", "đáp án 2", "đáp án 3", "đáp án 4"] ``` <- thay đổi đáp án mà bạn muốn cho câu hỏi
> 
> ``` correctAnswer: <value> ``` <- thay đổi thành giá trị đáp án ở trên [ 0, 1, 2, 3 ] - theo thứ tự đáp án 1, 2, 3, 4
>
> ``` explanation: "Lời giải thích vì sao lại chọn đáp án đó"``` <- thêm lời giải thích cho đáp án bạn chọnchọn
