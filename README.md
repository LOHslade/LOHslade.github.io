# 슬레닷컴 beta

### [쿠폰 사용](https://legendofheroes-fow.com/KR/coupon?v=KR) -> XHPIP FJQDW (+카톡 친추 쿠폰 받으세요)

## ✅ 숙제 체크

<form>
  <input type="checkbox" id="task1" onchange="saveCheckboxState('task1')">
  <label for="task1">전장 5판, 동굴 소탕, 스태미나 사용</label><br>

  <input type="checkbox" id="task2" onchange="saveCheckboxState('task2')">
  <label for="task2">경험치 던전, 금화 던전, 광석 던전, 악세 던전</label><br>

  <input type="checkbox" id="task3" onchange="saveCheckboxState('task3')">
  <label for="task3">친구 포인트, 길드 포인트, 일일 무료 소환, </label><br>

  <input type="checkbox" id="task4" onchange="saveCheckboxState('task4')">
  <label for="task4">길드 레이드, 위협 레이드</label><br>

  <input type="checkbox" id="task5" onchange="saveCheckboxState('task5')">
  <label for="task5">일퀘 보상, 주퀘 보상, 상점 무료템(도탑 포함)</label><br>
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
- [공략](https://LOHslade.github.io/tip)
- [디노 요약](https://LOHslade.github.io/director)
- [캐릭터](https://LOHslade.github.io/character)

## 기타
- [한마디](https://LOHslade.github.io/diary)
- [길드](https://LOHslade.github.io/guild)
- [후원](https://LOHslade.github.io/donate)
