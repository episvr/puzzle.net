---
icon: lucide/magnet
---

# 三极

![img](./img/puzzle.png)

*本题有 1 个答案*

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
        "NW\\^[N"
      ]
    },
    {
      "type": "close",
      "texts": [
        "`W\\^[`"
      ]
    }
  ]
};
document.addEventListener("DOMContentLoaded", function () {
    bindAnswerBox(config);
});
</script>