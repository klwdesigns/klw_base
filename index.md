---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Krista Lyn White
---
<details>
  <summary style="outline:none;"><h1 style="display: inline; color:#23348e;">Books</h1></summary>
  <ul>
     <li><a style="color:#23348e; text-decoration:underline;" href="https://www.amazon.com/dp/0988580586/">Over Oceans: A Memoir</a></li>
     <li><a style="color:#23348e; text-decoration:underline;" href="https://www.amazon.com/dp/0988580578/">Take Me Deeper: Reflections & Prayers from the Edge</a></li>
     <li><u>The Bible and Western Culture</u><br> written for use in ResponsiveEd charter schools</li>
     <li><u>World Geography</u><br> written for use in ResponsiveEd charter schools</li>
     <li><u>World History</u><br> written for use in ResponsiveEd charter schools</li>
     <li>Co-author, <u>Speech: Essentials of Communications</u><br> written for Alpha Omega Publications</li>
     <li><u>High School Health</u><br> written for Alpha Omega Publications</li>
     <li><u>British Literature</u><br> written for Alpha Omega Publications</li>
     <li><u>American Literature</u><br> written for Alpha Omega Publications</li>
     <li>Co-author, <u>Health Quest</u><br> written for Alpha Omega Publications</li>
  </ul>     
</details>
<details>
  <summary style="outline:none;"><h1 style="display: inline; color: #ba2086;">Work</h1></summary>
  <ul>
     <li>2015 ~ Founder of <a style="color:#ba2086" href="https://wsoteam.org">Women's Sports Outreach</a></li>
     <li>2012 ~ <a style="color:#ba2086" href="https://bibpress.com">Blue Iris Books</a></li>
  </ul>     
</details>
<details>
  <summary style="outline:none;"><h1 style="display: inline; color:#e9560e;">Notes</h1></summary>
  <ul>
     {% for post in site.posts %}
      <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </li>
     {% endfor %}
  </ul>     
</details>
<details>
  <summary style="outline:none;"><h1 style="display: inline; color:#f7b523;">Hyperlinks & Contact</h1></summary>
  <ul>
     <li>Saint-Bisou.com</li>
     <li>Podcast [in the works]</li>
     <li>Email: [anything] at this domain</li>
  </ul>     
</details>
<details>
  <summary style="outline:none;"><h1 style="display: inline; color:#ffdf05;">About</h1></summary>
  <ul>
     <li>Based in Dallas since 1992</li>
     <li>Lived in France and Germany</li>
     <li>Studied psychology, theology, and literature</li>
     <li>Loves to eat bánh mì</li>
     <li>Born in California</li>
     <li>Photo: <a style="color:#ffdf05;" href="https://kristalynwhite.com/assets/kristalynwhite.jpg"> here</a> [for the curious]</li>
  </ul>     
</details>
