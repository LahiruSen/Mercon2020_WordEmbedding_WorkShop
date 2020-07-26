# Mercon2020_WordEmbedding_WorkShop
A HANDS-ON WORKSHOP IN WORD EMBEDDING: From Word2Vec to StarSpace


Steps to setup workspace on Google Colab

1. Open google drive(https://drive.google.com/) tab on your browser. 
2. Create a folder named "Mercon_WordEmbedding_Workshop" on a desired place on your google drive. 
3. Create a new colab notebook in above folder. (by clicking "new" button
   [if you haven't use colab bofore, you may have to add it first.]
4. Mount google drive to colab run time. (by clicking on "mount button" in left navigation bar.)
5. Navigate to the folder created above. 
```
cd <folder_path>
eg: cd /content/drive/My Drive/Mercon_WordEmbedding_Workshop
```
6. Clone required repo to your google drive by running below command.
```
!git clone https://github.com/LahiruSen/Mercon2020_WordEmbedding_WorkShop.git
```
7. Add required files to your google drive.(Navigate to Shared folder and click on "Add shortcut to drive", place this inside above created folder.)
  ```
  https://drive.google.com/drive/folders/1JqGCyodH4twjP0ET6mt3i0MkUpSth9Wo?usp=sharing
  ```
8. Now open "Operations_on_word_vectors_en_final.ipynb" file using colab. (This should be available in cloned folder), and run fisrt cell in this notebook to mount google drive again. 

9. Change "folder_path" variable to shared folder shortcut created in the step 7. 
```
eg: 
folder_path = '/content/drive/My Drive/Mercon_WordEmbedding_Workshop/WordEmbed workshop'
```
10. Repeat step 8 and 9 to setup "sentiment_analysis_v4.ipynb" file also. [change flder path]

11. Now you are all ready to proceed with the workshop. 
