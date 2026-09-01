# Mikaso-Nakamoto


<div class="profile-container">
  <!-- Левая колонка: иконки -->
  <div class="left-col">
    <img src="icon-c.png" alt="C#">
    <img src="icon-net.png" alt=".NET">
    <img src="icon-js.png" alt="JS">
    <!-- остальные иконки -->
  </div>

  <!-- Правая колонка: текст -->
  <div class="right-col">
    <h2>Мой стек</h2>
    <p>Ya krutoy specialist!</p>
  </div>
</div>

<style>
  .profile-container {
    display: flex;           /* Включаем флекс */
    justify-content: space-between; /* Разносит блоки по краям */
    gap: 40px;               /* Расстояние между колонками */
    align-items: center;     /* Центрирует по вертикали (чтобы текст был по центру иконок) */
    min-height: 100vh;      /* На весь экран, если нужно */
  }

  .left-col, .right-col {
    flex: 1;                 /* Каждый блок занимает 50% места */
  }

  /* Стили для иконок, чтобы стояли в столбик */
  .left-col img {
    display: block;
    margin-bottom: 15px;
    width: 40px;             /* Фиксируем размер иконок */
    height: auto;
  }
</style>
