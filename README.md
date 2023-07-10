# Hello, Juncture

This Juncture essay illustrates the use of a few Markdown formatting tags and the incorporation of an image and a map into a Juncture essay.
<br><br>

## Official tutorial
[Juncture home page](https://www.juncture-digital.org/)
<br><br>

## Implement : ALA Annual Conference 2023 - Poster
<style>
    .textColor1 {
        color: #0D00C0;
    }

</style>

.ve-media gh:weihungtseng/media/picture/ALA_Annual_Conference_2023.png

<!--
<div style="padding: 10px; background-color: #FFCE9C;">
-->
<div style="padding: 10px; background-color: #9ACEEB;">
    <br>
    <h1 style="text-align: center;"><span class="textColor1">Subject Heading Prediction based on the BERT Model</span></h1>
    <table style="width: 85%; border: none" align="center">
        <tr style="border: none;">
              <td style="width: 10%; height: 10%; border: none;" align="center" valign="center">
                  <ve-media anno-base="None/None/" src="gh:weihungtseng/program-juncture/media_source/NTNU_School_Badge.png"></ve-media>
              </td>
              <td style="border: none;" >
                  <h4 style="text-align: left;"><span class="textColor1">Huei-Yu Wang   |   Wei-Hung Tseng   |   Yu-Hao Lai   |   Ming-Hsin Phoebe Chiu</span></h4>
                  <h4 style="text-align: left;"><span class="textColor1">Graduate Institute Of Library & Information Studies</span></h4>
                  <h4 style="text-align: left;"><span class="textColor1">National Taiwan Normal University</span></h4>
              </td>
        </tr>
    </table>
    
    <br>
    <details style="border: 1px solid #000; padding: 10px; background-color: #DFECFF;">
        <summary><h3 style="text-align: center;">Motivation</h3></summary>
        <p style="border: 1px solid #000; padding: 10px; background-color: #EEF5FF;">Cataloging is an essential part of the mission of the libraries, as the collection serves as a carrier of knowledge, so the users can effectively retrieve and utilize this knowledge. Automatic classification technologies have been introduced to the library technical services to enhance efficiency and improve inconsistency in cataloging.
    </details>
    
    <br>
    <details style="border: 1px solid #000; padding: 10px; background-color: #DFECFF;">
        <summary><h3 style="text-align: center;">Problem to be solved</h3></summary>
        <p style="border: 1px solid #000; padding: 10px; background-color: #EEF5FF;">To address the actual cataloging needs and problems in libraries, this study used 620,217 titles from the National Taiwan Normal University Library as experiment datasets and trained with the BERT distilbert-base-multilingual-cased model on different combinations of call number, titles, and authors’ data to make multiple subject cataloging predictions in both Chinese and English languages.
    </details>
    <br>
    
        <details style="border: 1px solid #000; padding: 10px; background-color: #DFECFF;">
        <summary><h3 style="text-align: center;">Procedure</h3></summary>
        <p style="border: 1px solid #000; padding: 10px; background-color: #EEF5FF;">After analyzing the dataset, we found that there are 191,478 usable data entries. Each entry has at least one subject keyword, with a total of 66,548 subject keywords distributed among them. The subject keyword with the highest frequency appears 5,085 times, while the subject keyword with the lowest frequency appears only once. Due to the large number of subject keywords and significant differences in frequency, we will sort them in descending order based on their occurrence frequency. Furthermore, we define the coverage of data entries as the dataset, and only when all the subject keywords of these data entries fall within the current range of subject keywords, they are considered part of the dataset.
            
        <ve-media anno-base="None/None/" src="gh:weihungtseng/program-juncture/media_source/Table1_Analysis_and_Statistics_of_Subject_Keywords.png"></ve-media>

        In this study, BERT technology was applied, using a pre-trained model for fine-tuning. During training, different combinations of the first three digits of the call number, book title, and author were attempted as the text input, while the subject keywords served as labels. The data set was divided into a training set and a test set using the iterative_train_test_split() function from the scikit-multilearn package, with a ratio of nine to one, achieving stratification for multi-label data.
        <br>
        Initially, due to the large number of subject keywords, the experiment focused on the top 50 subject keywords with the highest occurrence frequency. The data set consisted of records covered by these subject keywords, and training experiments were conducted using the text input as the call number. Finally, the distilbert-base-multilingual-cased model, which performed better, was selected as the model for subsequent experiments. This model is capable of handling multilingual classification tasks.

    </details>
    <br>
    
        <details style="border: 1px solid #000; padding: 10px; background-color: #DFECFF;">
        <summary><h3 style="text-align: center;">Conclusion</h3></summary>
        <p style="border: 1px solid #000; padding: 10px; background-color: #EEF5FF;">From the experiments, it can be concluded that the most suitable BERT model for this study is distilbert-base-multilingual-cased. Among the different Text options, the combination of Book Title and Call Number achieved the best prediction performance. When considering the data set covered by the top 50 subject keywords, the Micro-F score reached 0.8623. In summary, there are two key factors for achieving good performance in predicting subject keywords using BERT. The first factor is the frequency of occurrence (sample size) of the subject keywords, and the second factor is ensuring that the meaning represented by the Text is closely related to the meaning of the subject keywords.
    </details>
    <br>
    <!--example-->
    <ve-media anno-base="None/None/" caption="Dynamic image" left src="wc:The_Bug_Peek.jpg"></ve-media>
</div>



## Aulacophora indica

.ve-media wc:The_Bug_Peek.jpg right

The image depicts a leaf beetle (Aulacophora indica) (Family: Chrysomelidae; subfamily: Galerucinae) looking out from a leaf hole of Alnus nepalensis tree. Adult leaf beetles make holes in host plant leaves while feeding. They camouflage themselves with these holes.

This image is hosted on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:The_Bug_Peek.jpg) and was runner-up for Wikimedia Commons Picture of the Year for 2021.

Image controls are located in the top-left corner of the image and can be seen when hovering over the image.  These controls support image zoom, rotation, full-screen viewing, and repositioning to the start position.  Panning can be performed with keyboard arrow keys or by mouse click-and-drag.

Image information can be seen when hovering the cursor over the info icon located in the top-right corner of the image.  The Image information popover includes the image title, description, attribution statement, and reuse rights.

## Chitwan National Park, Nepal

.ve-map Q1075023 right

The map is centered on the Chitwan National Park in Nepal, which is the location associated with the image above.  The Wikidata identifier for Chitwan National Park is `Q1075023`.  When a map location is specified using a Wikidata ID (or QID) Juncture can automatically retrieve the geographic coordinates for map centering.

An alternative to using a Wikidata identifier for map positioning is to use regular latitude and longitude coordinates.  In that approach the QID would be replaced with the coordinates `27.5,84.333`, resulting in an identical map.

Similar to the image viewer, map zooming is controlled using the buttons located in the top-left corner of the map viewer.  Panning is performed with the keyboard arrow keys or by mouse click-and-drag.``