# Flipkart_robotics_6.0 
Project Title: "SmartVision: AI-Powered inventory management for eCommerce"
## You can check here ----> https://robotics-teamyuktika.netlify.app/
# "SmartVision: AI-Powered inventory management for eCommerce"
# Project Overview:
The Smart Product Analysis Dashboard is a comprehensive quality control solution designed for the e-commerce and manufacturing industries. It leverages computer vision technology, machine learning,deep learning and advanced image processing techniques to automate product quality testing. This system is capable of extracting important product information, identifying brand details, counting objects, and detecting product freshness, making it a versatile tool for industry automation.

**Features:**
## Manufacturing & Expiry Extraction (Task 1):
**Github link ---> https://github.com/Kanakt326/mexp**

Extracts manufacturing and expiry date of products packaging using paddleocr.Helps  manage inventory more efficiently by flagging soon-to-expire products, enabling proactive restocking and promotions.

## Brand Recognition & Object Counting (Task 2):
**Github link --> https://github.com/Priya-161/Count_and_Brand**

Employs yolov8 to annotate brand name from product image and train model to identify brand label for new images  to identify product brands and validate packaging 
Leverage computer vision for  object counting functionality using opencv for accurate inventory management, ensuring the correct number of products are processed.
## Fruit Freshness Detection (Task 3):
**Github link --> https://github.com/Priya-161/shelf_life**

We trained dataset of 5601 fruit images on MobilenetV2 model .The images were annotated based on shelf life that we observed over the time span taken for a fresh fruit till it get rotten for various fruits like apple,orange,melon,banana and so on.It predicts the classification of fruit and its estimated shelf life.
## Product Detail Extraction (Task 4):
**Github link -->  https://github.com/riyakush0611/image_extraction**

Demonstrates the fine-tuning of the Qwen2-VL model on a custom dataset for OCR extraction tasks. The objective is to extract important product information such as:
Brand Name,  Manufacturing Details ,Category ,Weight,Volume .The model is optimized to work with product images, where it automatically identifies and extracts this textual information.


**Applications:**

E-commerce: Ensuring product accuracy, timely delivery, and quality management.
Manufacturing: Automating inspection and validation processes for product quality assurance.
Logistics: Improving inventory control and shipment accuracy by ensuring product details are verified before dispatch.


**Benefits:** Accurate product identification, reduced manual effort, real-time data logging, and enhanced inventory management.
The system automatically rejects defective products, records quality data, and provides real-time feedback for inventory management.


**Conclusion:**
The Smart Quality Test System offers a scalable and efficient solution for product inspection and quality control in eCommerce.It directly addresses challenges like expiration date management, brand authentication, freshness detection, and object counting, which are critical in high-volume ecommerce environments.
