# brand_dataset


## Brand
Brand information are store in:
  - brand_credircard.csv
  - brand_pointcard.csv
  - brand_popular.csv
  
  format: brand_name, brand_id, brand_category
  
  link to the brand could be retrived by the brand name:
  
  e.g,
  
  brand name: 3coins_official
  
  link to brand: https://www.instagram.com/3coins_official/


## Followers
Followers posts are store in:
  - brandname.json

  link to download followers posts(https://drive.google.com/open?id=1y3Uokhm_xS5u0vNzZbCyWXb61c9f_m9K)

  format:
  one user per line
  {"username": username, "posts":{"shortcode":"tags"}}
  
  link to the post could be retrived by the shortcode:
  
  e.g,
  
  shortcode: B3LoSw8pPgV
  
  link to image: https://www.instagram.com/p/B3LoSw8pPgV/
  
  tags are split by ',' tags are url encoded.
  
  
## Citation
Please cite our paper if you use this dataset.


Yiwei Zhang, Xueting Wang, Yoshiaki Sakai, and Toshihiko Yamasaki. Measuring Similarity between Brands using Followers' Post in Social Media. In Proceedings of the ACM International Conference on Multimedia Asia (MMAsia'19). December 15--18, 2019, Beijing, China

