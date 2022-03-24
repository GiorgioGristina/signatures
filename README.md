![This is an image](/app/assets/images/EZContractBlack.png)

## what is about?
<p> EZ-contracts is a product that allows organizations to manage electronic agreements.
Who benefits from this product?</p>

<strong> Company </strong>
<ul>
  <li>smooth business bureaucracy;</li>
  <li>save space in the office storing contract in the clouds;</li>
  <li>let the company focus on their core mission;</li>
</ul>
<strong> individual/signatories</strong>
<ul>
  <li>no more wasting time, going to the office to sign the contract</li>
  <li>everything safely stored in the clouds</li>
</ul>


<p>checkout the website: <a href="https://signing-contr.herokuapp.com/">EZ-contracts</a></p>

### tech-stack
<p>Our Product has being created Using RoR framework for the back end, following the pattern MVC because is the languages where My group and I were more confident at the end of the Bootcamp for the front end side we used HTML, CSS and a little of JS.</p>
For Acheving our goal with have to use different Gems to implement the different features:

<table>
  <tr>
    <th>GEM</th>
    <th>feature</th>
    <th>description</th>
  </tr>
  <tr>
    <td>PG_search</td>
    <td>search bar</td>
     <td>search bar to find the contracts by name or description available in the section unsigned and signed by name or description</td>
  </tr>
  <tr>
    <td>device</td>
    <td>log-in and sign-up</td>
    <td>Devise Gem is a flexible user authentication</td>
  </tr>
  <tr>
    <td>combine_pdf</td>
    <td>merge signature on existing pdf</td>
    <td>CombinePDF is a nifty model, written in pure Ruby, to parse PDF files and combine (merge) them with other PDF files, watermark them or stamp them (all using the PDF file format and pure Ruby code).</td>
  </tr>
  <tr>
    <td>pundit</td>
    <td>build the authorization system</td>
    <td>It is to verify that the user have persmission to perform an action</td>
  </tr>
  <tr>
    <td>wicked_pdf</td>
    <td>deal with pdf file uploaded</td>
    <td>Wicked PDF uses the shell utility wkhtmltopdf to serve a PDF file to a user from HTML. In other words, rather than dealing with a PDF generation DSL of some sort, you simply write an HTML view as you would normally, then let Wicked PDF take care of the hard stuff.</td>
  </tr>
</table>

