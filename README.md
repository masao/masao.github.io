# masao.github.io
c4ljp22 workshop

[テストだよー](test)

<div>
  <ul>
    <!-- _data フォルダの books.csv からデータを取り出す -->
    {% for book in site.data.books %}
      <li>
        <!-- books.csv の title 列を表示、 url 列をリンク先に設定 -->
        <!-- <p class="title"><a href="{{ book.url }}">{{ book.title }}</a></p>-->
<p class="title"><a href="{{ book.url }}">{{ book.title }}</a> <i>{{ book.author }}</i></p>
      </li>
    {% endfor %}
  </ul>
</div>
