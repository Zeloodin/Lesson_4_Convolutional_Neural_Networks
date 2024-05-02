# Итог, результаты, тесты

---
# Original
На графике видно, Original постепенно обучался. Плавная кривая линия.

loss плавно понижался.

val_loss, остановился в диапазоне, 0.6 - 0.8

Примерно на 35-ом шаге, val_loss остановился на 0.6 и постепенно приближался к 0.8

7/7 [==============================] - 0s 6ms/step - loss: 0.6655 - accuracy: 0.8376

[+] Accuracy: 83.76%

---

---


---
# +1
На графике видно, +1 постепенно обучался. Плавная кривая линия.

loss плавно понижался.

val_loss, остановился в диапазоне, 0.6 - 0.8

Примерно на 35-ом шаге, val_loss остановился на 0.6 и постепенно приближался к 0.8

7/7 [==============================] - 0s 6ms/step - loss: 0.7045 - accuracy: 0.8376

[+] Accuracy: 83.76%
---

---


---
# +2
На графике видно, +2 скачкамми обучался. Резкие нестабильные линии.

loss плавно понижался.

val_loss, остановился в диапазоне, 0.6 - 0.8

7/7 [==============================] - 0s 7ms/step - loss: 0.7234 - accuracy: 0.8579

[+] Accuracy: 85.79%
---

---


---
# 01
На графике видно, 01 постепенно обучался. Плавные и Резкие полу-стабильные линии.

7/7 [==============================] - 0s 15ms/step - loss: 0.4062 - accuracy: 0.8934

[+] Accuracy: 89.34%

7/7 [==============================] - 0s 11ms/step - loss: 0.5338 - accuracy: 0.8579

[+] Accuracy: 85.79%
---

---


---
# 02
На графике видно, 02 постепенно обучался. Плавные и Полу-резкие стабильные линии.

7/7 [==============================] - 0s 6ms/step - loss: 0.4968 - accuracy: 0.8680

[+] Accuracy: 86.80%
---

---


---
# 03
На графике видно, 03 постепенно обучался. Плавные и Резкие полу-стабильные линии.

7/7 [==============================] - 0s 10ms/step - loss: 0.4889 - accuracy: 0.8629

[+] Accuracy: 86.29%

Но, accuracy и val_accuracy, loss и val_loss, значения между ними, практически одинаковы.
---

---





---
# Original

Epoch 10

loss: 0.9568 - accuracy: 0.5197 - val_loss: 0.9109 - val_accuracy: 0.5584

Epoch 100

loss: 0.1910 - accuracy: 0.9238 - val_loss: 0.6655 - val_accuracy: 0.8376
---

---





---
# +1

Epoch 10

loss: 0.9705 - accuracy: 0.5299 - val_loss: 0.8892 - val_accuracy: 0.5330

Epoch 100

loss: 0.1446 - accuracy: 0.9441 - val_loss: 0.7045 - val_accuracy: 0.8376
---

---





---
# +2

Epoch 10

loss: 0.9592 - accuracy: 0.5235 - val_loss: 0.9154 - val_accuracy: 0.6142

Epoch 100

loss: 0.1682 - accuracy: 0.9365 - val_loss: 0.7234 - val_accuracy: 0.8579
---

---





---
# 01

Epoch 10

loss: 0.9853 - accuracy: 0.5375 - val_loss: 0.9545 - val_accuracy: 0.5330

Epoch 100

loss: 0.1164 - accuracy: 0.9619 - val_loss: 0.4062 - val_accuracy: 0.8934

---


Epoch 10

loss: 0.9103 - accuracy: 0.5642 - val_loss: 0.9300 - val_accuracy: 0.5736

Epoch 100

loss: 0.1409 - accuracy: 0.9441 - val_loss: 0.5338 - val_accuracy: 0.8579
---

---





---
# 02

Epoch 10

loss: 0.8406 - accuracy: 0.5947 - val_loss: 0.8014 - val_accuracy: 0.6548

Epoch 100

loss: 0.1888 - accuracy: 0.9314 - val_loss: 0.4968 - val_accuracy: 0.8680
---

---





---
# 03

Epoch 10

loss: 0.9953 - accuracy: 0.4943 - val_loss: 0.9497 - val_accuracy: 0.5228

Epoch 100

loss: 0.1557 - accuracy: 0.9479 - val_loss: 0.4889 - val_accuracy: 0.8629

