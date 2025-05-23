# SMADIMO_GP_2  


---

### **Тема проекта:**  
**Анализ маркетплейсов для бренда браслетов из натурального жемчуга**  

---

### **Цель проекта**  
Оценить перспективность выхода на маркетплейсы с линейкой браслетов из натурального жемчуга, выявить уровень конкуренции, спрос и потенциальные стратегии позиционирования

---

### **Описание репозитория**  

- `EDA-№.ipynb` - блокноты с проведенным EDA. В них содержится все исследование данных: от первичного анализа и очистки до статистических исследований
- `'***'_parsing.ipynb` - блокноты со скриптом сбора данных с каждого маркетплейса (парсинг + api)
- `'***'_data_z_№.csv` - собранные данные со всех маркетплейсов по 5 разным запросам (в нашем анализе используются запросы 1,2 и 4, остальные планируется использовать в дальнейшем)
- `'***.log'` - логи скриптов по сбору данных 

---

### **Описание данных**

- `product_url` - ссылка или id товара
- `product_name` - название товара
- `brand` - бренд товара (если есть)
- `is_original` - метка об оригинальности товара (если есть)
- `final_price` - итоговая цена
- `old_price` - цена до скидки
- `discount` - размер скидки в процентах
- `rating` - рейтинг товара
- `reviews_count` - количество оценок товара
- `delivery_time` - сроки доставки
- `market` - код маркетплейса, на котором этот товар опубликован
