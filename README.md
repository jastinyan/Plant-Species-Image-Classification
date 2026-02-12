
# 🌿 Plant Image Classification Model
   ### Gourd Family Plant
## 📌 A. Project Overview

### 📖 Brief Description
This project focuses on designing, training, evaluating, and documenting an **image classification model** that can recognize **20 related plant species**. The model was created using **Google Teachable Machine**, where a dataset of plant images was collected, organized into classes, and trained to accurately classify plant species based on visual features such as leaves, flowers, fruits, and overall plant structure. The entire process, including dataset preparation, model evaluation, and testing results, is documented using **GitHub**.

### 🎯 Purpose 
The purpose of this model is to:
- Automatically identify and classify different plant species using images
- Demonstrate the application of machine learning in plant recognition
- Improve skills in dataset handling, model training, and evaluation using accuracy metrics

---

## 🌱 B. Plant Species Section

The following plant species were included in the dataset:

Belong to **GOURD FAMILY PLANT** or the **_Cucurbitaceae_.**

It is a group of mostly vining plants that usually grow creeping or climbing and produce large fruits with seeds inside. Many members are important vegetables and fruits, especially in tropical and warm climates.

| Plant | Scientific Name | Short Description | Image | 
|------|-----------------|------------------|-------------------|
| Cucumber | _Cucumis sativus_ | A climbing or creeping vine plant that produces long green fruits commonly eaten fresh or pickled. | <img src="sample/cucumber.jpg" width="250"> |
| Watermelon | _Citrullus lanatus_ | A spreading vine plant known for its large round or oval fruit with sweet red flesh and high water content. |<img src="sample/watermelon.jpg" width="250"> |
| Cantaloupe | _Cucumis melo_ | A vine plant that produces sweet, orange-fleshed melon fruit with a netted rind, commonly eaten fresh. |<img src="sample/cantaloupe.jpg" width="250"> |
| Pumpkin | _Cucurbita pepo_ | A creeping vine plant that produces large orange fruits commonly used for cooking, soups, and desserts. | <img src="sample/pumpkin.jpg" width="250"> |
| Calabaza | _Cucurbita moschata_ | A squash variety with thick flesh and sweet flavor, widely used in stews and traditional dishes. | <img src="sample/calabaza.jpg" width="250"> |
| Zucchini | _Cucurbita pepo_ | A summer squash plant that produces smooth green cylindrical fruits often cooked or eaten fresh. | <img src="sample/zucchini.jpg" width="250"> |
| Bitter Melon | _Momordica charantia_ | A climbing vine known for its bumpy green fruit with a bitter taste, commonly used in medicinal and Asian dishes. | <img src="sample/bitter_melon.jpg" width="250"> |
| Bottle Gourd | _Lagenaria siceraria_ | A vine plant producing large bottle-shaped fruits, used as a vegetable when young or as containers when dried. | <img src="sample/bottle_gourd.jpg" width="250"> |
| Sponge Gourd | _Luffa aegyptiaca_ | A climbing vine whose mature fruit dries into a fibrous sponge, also eaten as a vegetable when young. | <img src="sample/sponge_gourd.jpg" width="250"> |
| Ridge Gourd | _Luffa acutangula_ | A vine plant producing long ridged fruits, commonly cooked in soups and stir-fry dishes. | <img src="sample/ridge_gourd.jpg" width="250"> |
| Chayote | _Sechium edule_ | A climbing plant producing pear-shaped green fruits with mild flavor, often used in soups and salads. | <img src="sample/chayote.jpg" width="250"> |
| Winter Melon | _Benincasa hispida_ | A vine plant that produces large waxy fruits with pale flesh, commonly used in soups and drinks. | <img src="sample/winter_melon.jpg" width="250"> |
| Ivy Gourd | _Coccinia grandis_ | A fast-growing climbing plant producing small green fruits, often cooked as a vegetable in tropical regions. | <img src="sample/ivy_gourd.jpg" width="250"> |
| Snake Gourd | _Trichosanthes cucumerina_ | A vine plant producing long twisting fruits resembling a snake, usually cooked when young. | <img src="sample/snake_gourd.jpg" width="250"> |
| Cucamelon | _Melothria scabra_ | A small vine plant producing grape-sized fruits that look like mini watermelons and taste like cucumber with citrus. | <img src="sample/cucamelon.jpg" width="250"> |
| Butternut Squash | _Cucurbita moschata_ | A squash plant producing tan, bell-shaped fruits with sweet orange flesh, popular for roasting and soups. | <img src="sample/butternut_squash.jpg" width="250"> |
| Teasel Gourd | _Momordica subangulata_ | A climbing vine producing spiny fruits, commonly eaten in Southeast Asia and valued for its nutritional benefits. | <img src="sample/teseal_gourd.jpg" width="250"> |
| Acorn Squash | _Cucurbita pepo_ | A squash plant producing small ribbed fruits with hard skin and sweet yellow-orange flesh. | <img src="sample/acorn_squash.jpg" width="250"> |
| Pattypan Squash | _Cucurbita pepo_ | A summer squash plant producing flat, round fruits with scalloped edges, often cooked or stuffed. | <img src="sample/pattypan_squash.jpg" width="250"> |
| Horned Melon | _Cucumis metuliferus_ | A vine plant producing spiky orange fruits with jelly-like green flesh, known for its refreshing taste. | <img src="sample/horned_melon.jpg" width="250"> |



---

## ⚙️ C. Model Training Details

The model was trained using the following parameters:

- **Epochs:** `50`
- **Batch Size:** `16`
- **Learning Rate:** `0.001`
- **Number of Images per Class:** `Minimum of 250`

### 📂 Dataset Summary

| Plant Species / Class | Number of Images |
|----------------------|------------------|
|Cucumber | 250 |
|Watermelon | 292 |
| Cantaloupe | 313 |
| Pumpkin | 288 |
| Calabaza | 264 |
| Zucchini | 274 |
| Bitter Melon | 281 |
| Bottle Gourd | 253 |
| Sponge Gourd | 268 |
| Ridge Gourd | 263 |
| Chayote | 267 |
| Winter Melon | 278 |
| Ivy Gourd | 276 |
| Snake Gourd | 262 |
| Cucamelon | 269 |
| Butternut Squash | 276 |
| Teasel Gourd | 289 |
| Acorn Squash | 280 |
| Pattypan Squash | 272 |
| Horned Melon | 269 |

---

## 📊 D. Model Evaluation
- Confusion matrix
- Accuracy per class
- Overall model accuracy
---

## 🧪 E. Model Testing

Below are **10 testing screenshots** taken from the Preview section:

### 🔍 Testing Results Screenshots

1. ![Test 1](screenshots/test1.png)
2. ![Test 2](screenshots/test2.png)
3. ![Test 3](screenshots/test3.png)
4. ![Test 4](screenshots/test4.png)
5. ![Test 5](screenshots/test5.png)
6. ![Test 6](screenshots/test6.png)
7. ![Test 7](screenshots/test7.png)
8. ![Test 8](screenshots/test8.png)
9. ![Test 9](screenshots/test9.png)
10. ![Test 10](screenshots/test10.png)

📌 *All screenshots are saved inside the `screenshots/` folder.*

---

# 📝 Reflection Questions

### 1. How did the number of images per class affect your model’s accuracy?

---

### 2. Which plant species were most commonly misclassified and why?

---

### 3. How did changing the epochs, batch size, or learning rate affect the training results?

---

### 4. What challenges did you encounter during dataset collection and labeling?

---

### 5. If you were to improve your model, what specific changes would you make and why?
