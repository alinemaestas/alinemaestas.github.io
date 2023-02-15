---
layout: nice-text
---
  
{{ content }}




# Ryan vs Ryan: Liquid Table Demo 

<table id="ryan-v-ryan">

<thead>
  <tr>
 ## Ryan Reynolds
 ##  Ryan Gosling 
  </tr>
</thead>

<tbody>

<tr>
  
  
  <td>
  
    
### Strengths  
    <ul>
      
      {% for item in page.reynolds.strengths %}
         <li>{{ item }}</li>
      {% endfor %}
      
    </ul>
    
    <br>

### Weaknessess 
    <ul>
      
      {% for item in page.reynolds.weaknesses %}
         <li>{{ item }}</li>
      {% endfor %}
      
    </ul>  
    
    
  </td>
  


  <td>
  
    <h4>  Strengths  </h4>
    <ul>
      
      {% for item in page.gosling.strengths %}
        <li>{{ item }}</li>
      {% endfor %}
      
    </ul>
    
    <br>
    
    <h4>  Weaknessess  </h4>
    <ul>
      
      {% for item in page.gosling.weaknesses %}
         <li>{{ item }}</li>
      {% endfor %}
      
    </ul>

  </td>
</tr> 

</table>


<br>

<hr>

<br>

![]([https://github.com/alinemaestas/alinemaestas.github.io/blob/854c60de0f57ae4e536bbd23cfef502c66c50aa5/ryan-v-ryan.jpeg) 

