# Pages

- [Apartment Hunting Guide]({% link apartment-questions.md %})
- [Forer's Demonstration / Barnum Effect]({% link forers-demonstration.md %})
- [Seneca on the Shortness of Life]({% link on-the-shortness-of-life.md %})
- [The Parable of Two Programmers]({% link parable-of-two-programmers.md %})
- [Miscellaneous Quotes]({% link miscellaneous-quotes.md %})
- [Questions to Ask on a Serious Date]({% link probing-questions.md %})
- [Vanity Notes]({% link vanity.md %})

# Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
