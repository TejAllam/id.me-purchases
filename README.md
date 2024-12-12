# id.me-purchases

Link -> https://tejallam.github.io/id.me-purchases/

## Mobile Layout :

![image](https://github.com/user-attachments/assets/aef168fc-4551-4e85-89f8-e09918e55e41)


## Desktop Layout :

![image](https://github.com/user-attachments/assets/54682306-0705-4685-bd32-a59afdfa4a4d)


### Design : 

  - Went with native HTML/CSS/JS
  - Didn't use any Frameworks, could have used Angular but didn't want to complicate.
  - Started with Table syntax but realized issues from an earlier project, went with mobile first using the Card layout.
  - Uses Media queries to display either in Mobile or Desktop based on dimensions (  > 769px as deciding factor).
  - Made use of ' flex ' , familiar from prior work.
  - Data is fetched only once for both Mobile and Layout when resized.
  - Fetches content using Fetch API
  - Once data is retrieved, it should be preprocessed to ensure confirmity.
  - Content is written to DOM and images are fetched in order. 


### Improvements : 

  - When all images are loaded at once, there is an impact on performance, this could be mitigated by pagination or sequwntal load once elements come into view.  
  - CSS, could have minified and organized styles.
  - JS Functionality only 3 major logic blocks. Kept it simple, but tests would have helped.
  - Table column header alignment, didn't have time but could have used CSS Grid if it would help.
  - 'Description' and 'Category' columns are not in alignment, didn't get time to iterate table layout design.
  - Went with some primary colors for the 'Category' section, should have ensured these are within acceptable Accessibility contrast ratios.
  
  
### Performance : 

![image](https://github.com/user-attachments/assets/98fd5314-5329-41a2-b09a-630bf6e4564f)

![image](https://github.com/user-attachments/assets/0d6d3c8d-09ff-426a-b9a4-8d5918ae3b66)

![image](https://github.com/user-attachments/assets/3b3d8be9-d35d-4a52-acf2-fcc13f9962d2)




#### Links :

https://developer.mozilla.org/en-US/docs/Web/CSS/Layout_cookbook/Card \
https://developer.mozilla.org/en-US/docs/Web/CSS/@media \
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API \
https://developer.mozilla.org/en-US/docs/Web/CSS/flex
