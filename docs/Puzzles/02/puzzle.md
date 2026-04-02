---
icon: lucide/chess-knight
---

# 小谜

![img](./img/puzzle.png)

本题目没有 meta，你只需要解开所有的小题即可。小题的答案都是中文。

*本题有 8 个小题答案*

<input id="answer" placeholder="Enter your answer" />
<button onclick="checkAnswer()">Submit</button>

<p id="result"></p>

<script>
const config = {
  "meta": {
    "version": 1
  },
  "rules": [
    {
      "type": "correct",
      "texts": [
        "尰凅馘骖",
        "佧骖",
        "骖尾伍奕",
        "骖迨",
        "骖釶妏",
        "骖吸烘",
        "骖冗畜涡崋",
        "髡髯骖"
      ]
    }
  ]
};
document.addEventListener("DOMContentLoaded", function () {
    bindAnswerBox(config);
});
</script>