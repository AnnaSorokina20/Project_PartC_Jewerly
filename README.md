# Оновлення Програми Управління Намистом з Дорогоцінними Каменями

### Нові Функції:

- **Додано Делегати:** Програма тепер використовує делегати `Action`, `Func`, та власний делегат `StoneFilter` для впровадження додаткової логіки обробки каменів.
  - `Action` делегат використовується для виведення інформації про кожен камінь.
  - `Func` делегат дозволяє обчислювати та виводити загальну вартість каменів.
  - `StoneFilter` використовується для фільтрації каменів за заданими критеріями.

- **Впровадження Подій:** Додано події `StoneAdded` та `StoneRemoved`, які спрацьовують при додаванні чи видаленні каменів з намиста.

### Покращення:

- **Покращена Валідація Вводу:** Додано додаткові перевірки для забезпечення введення коректних даних про `clarity` та `hardness` каменів.
- **Рефакторинг Коду:** Проведено рефакторинг коду для підвищення його читабельності та ефективності.


### Діаграма класів
![image](https://github.com/AnnaSorokina20/Project_PartC_Jewerly/assets/149331565/61a210c5-5db0-4a4d-ae08-88e5309ad394)
