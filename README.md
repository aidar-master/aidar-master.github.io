<style>
  .blue-form-wrapper {
    background-color: #2c5aa0;
    color: #ffffff;
    padding: 30px;
    border-radius: 8px;
    font-family: Arial, sans-serif;
  }
  .blue-form-wrapper label {
    display: block;
    margin-top: 15px;
    font-weight: 600;
  }
  .blue-form-wrapper input,
  .blue-form-wrapper textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border: none;
    border-radius: 4px;
    box-sizing: border-box;
  }
  .blue-form-wrapper button {
    margin-top: 20px;
    background-color: #ffffff;
    color: #2c5aa0;
    border: none;
    padding: 12px 24px;
    font-weight: bold;
    border-radius: 4px;
    cursor: pointer;
  }
  .blue-form-wrapper button:hover {
    background-color: #f0f0f0;
  }
  .mail-link {
    display: inline-block;
    margin-top: 15px;
    color: #ffffff;
    text-decoration: underline;
    font-size: 14px;
  }
  .mail-link:hover {
    text-decoration: none;
  }
  .consent {
    font-size: 12px;
    margin-top: 10px;
    color: #cccccc;
    text-align: center;
  }
</style>

<div class="blue-form-wrapper">
  <h3>Оставьте заявку — отвечу за 5 минут!</h3>
  <form action="https://formspree.io/f/xkjnyvqa" method="POST">
    <div>
      <label for="name">Ваше имя</label>
      <input type="text" id="name" name="name" required placeholder="Как к вам обращаться">
    </div>
    <div>
      <label for="contact">Телефон или e‑mail</label>
      <input type="text" id="contact" name="contact" required placeholder="+7… или почта">
    </div>
    <div>
      <label for="message">Что нужно (кратко)</label>
      <textarea id="message" name="message" rows="3" required placeholder="Например: настройка ПК, установка Windows"></textarea>
    </div>
    <button type="submit">Отправить заявку</button>
    <p class="consent">Нажимая кнопку, вы даёте согласие на обработку персональных данных.</p>
  </form>
  <a class="mail-link" href="mailto:Aidar443@yandex.ru?subject=Заявка с сайта&body=Здравствуйте! Меня интересует:">Или сразу написать на почту</a>
</div>
