# 슬레닷컴 beta

## ✅ 숙제 체크

<form>
  <input type="checkbox" id="task1" onchange="saveCheckboxState('task1')">
  <label for="task1">HTML 공부</label><br>

  <input type="checkbox" id="task2" onchange="saveCheckboxState('task2')">
  <label for="task2">JavaScript 연습</label><br>

  <input type="checkbox" id="task3" onchange="saveCheckboxState('task3')">
  <label for="task3">프로젝트 작업</label><br>
</form>

<script>
  function saveCheckboxState(id) {
    localStorage.setItem(id, document.getElementById(id).checked);
  }

  function loadCheckboxState() {
    document.querySelectorAll("input[type=checkbox]").forEach((checkbox) => {
      checkbox.checked = localStorage.getItem(checkbox.id) === "true";
    });
  }

  window.onload = loadCheckboxState;
</script>



## 영가브
- [공략](https://LOHslade.github.io/tip.md)
- [캐릭터](https://LOHslade.github.io/character.md)

## 기타
- [한마디](https://LOHslade.github.io/diary.md)
- [길드](https://LOHslade.github.io/guild.md)
- [후원](https://LOHslade.github.io/donate.md)
