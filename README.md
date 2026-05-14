# Markdown in Jupyter Notebook
In this tuorial learn how to use and write with different markup tags in Jupyter Notebook
1. Heading
2. Bold
3. italc
4. Bullets
5. Numbered lists
6. Mathematical symbols
7. Indented quoting
8. Line breaks
9. Image
10. Color
11. Links

# 1. Headings

Use #s followed by a blank space for notebook titles and section headings:
# Title
## Major Headings
### Subheadings
#### 4th level Subheadings

# 2. Bold
1. use code tags

<b> This is bold text

3. '**' i.e, 'Doube asterisk'

**This is bold test**

# 3. Italic
1. 'Single asterisk' i.e., '*'

*This is italic text*

3. 'Single underscore' i.e., '_

_This is Italic text_

## 4. Bullets:
1. Circular Bullet:
Use the dash sign ( - ) with a space after it or Ue the asteris sign (*) with a space after it.
2. Sub bullet:
To create a sub bullet, use a tab followed a dash and space. You can also use an asterisk instead of a dash, and it worksthe same.
- This is bullet
* This is bullet
    - This is bullet
    * This is bullet

## 5. Number lists:
Start with 1. followed by a space, then it starts numberig for you. Start each line with some number and a period,
then a space. Tab to indent to get subnumbering.
1. Line number <b>one<b>
2. Line number <b>two<b>
 
   __A__. Sub line number one
   
   __B__. Sub line number two

## 6. Mathematical Symbols
Use this code: $ mathematical symbols $
$√$ 500 $-$ 5 $X$ 10 $÷$ 100 $ = $ ?

# 7. Indented quoting:
Use a greater than sign (>) and then a space, then type the text. The text is indented and has a gray horizontal linve to the left of it until the next carriage return.
> This is 1st line of 1st Blockquotes<br>
This is 2nd line of 1st Blockquote

>This is 1st line of 2nd Blockquote<br>
This is 2nd line of 2nd Blockquote
4. '__' i.e., 'double underscore'

# 8. Line breaks:
Use code: <br>

line break <br> line break

# 9. Image
You can attach image files directly to a notebookin Markdown cells. Drag and drop your imagesto the Markdown cellto attach it to the notebook
![Alt Text](images/https://github.com/kyawsanoo5/git-journey/images/CreditCard-FraudDetection.png)

# 10. Colors
Use this code:<font color=blue|red|green|pink|yellow>Text</font> Not all markdown code works withina font tag, so review your colored text carefully!
<font color=blue>Front color is blue</font>

<font color=red>Front color is blue</font>

<font color=yellow>Front color is blue</font>

# 11. Links:
Use this code and test all links: [link_text](http://url)

[Click here to Google](https://www.google.com/)

END

## Requirements
- Python 3.x
- `pip` packages:
  ```bash
  pip install -r requirements.txt
  ```
  Or individually:
  ```text
  numpy==1.21.0
  pandas>=1.3.0
  ```

  ### (Demographic & Loyalty Patterns)

It looks at information such as age and gender of buyers and their purchasing behavior.

| Pattern you want to know | Variables to be used | Method/chart to be used |
|--------------------------|----------------------|-------------------------|
| Purchase amount by age | Age, Purchase Amount (USD) |	Grouping/Box Plot: Divide age into groups (e.g. 20-30, 31-40) and see which age group spends more on average with a Box Plot. |
| Usage by gender |	Gender, Purchase Amount (USD) |	Bar Chart: Compare the average purchase amount between men and women. |
| Customer loyalty | Subscription Status, Previous Purchases | Correlation/Pivot Table: Check if Subscription Status (Subscription/No Subscription) is correlated with the number of Previous Purchases and see how loyal the customer is. |

__This is bold test__
