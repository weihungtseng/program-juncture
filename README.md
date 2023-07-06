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
    
    .pictureSize1 {
        object-fit: cover;
        width: 20%;
        height: 20%;
    }
    
    table th, td {
        border: 0;
    }
</style>

.ve-media gh:weihungtseng/media/picture/ALA_Annual_Conference_2023.png

<!--
<div style="padding: 10px; background-color: #FFCE9C;">
-->
<div style="padding: 10px; background-color: #9ACEEB;">
    <br>
    <h1 style="text-align: center;"><span class="textColor1">Subject Heading Prediction based on the BERT Model</span></h1>
    <table style="width: 85%;" align="center">
        <!--
        <tr>
              <th>Header 1</th>
              <th>Header 2</th>
              <th>Header 3</th>
        </tr>
        -->
        <tr>
              <td style="width: 15%; height: 10%" align="center" valign="center">
                  <img src="https://www.google.com/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fzh%2Fthumb%2Fc%2Fc3%2FNational_Taiwan_Normal_University_logo.svg%2F1200px-National_Taiwan_Normal_University_logo.svg.png&tbnid=HXnoMzzReWOx-M&vet=12ahUKEwjbkInUrvr_AhU7H94AHRUnDVYQMygBegUIARC8AQ..i&imgrefurl=https%3A%2F%2Fzh.wikipedia.org%2Fzh-tw%2F%25E5%259C%258B%25E7%25AB%258B%25E8%2587%25BA%25E7%2581%25A3%25E5%25B8%25AB%25E7%25AF%2584%25E5%25A4%25A7%25E5%25AD%25B8&docid=-jvmY5GMm8cXEM&w=1200&h=1200&q=%E5%B8%AB%E5%A4%A7logo%20png&ved=2ahUKEwjbkInUrvr_AhU7H94AHRUnDVYQMygBegUIARC8AQ" alt="NTNU School Badge">
              </td>
              <td>
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