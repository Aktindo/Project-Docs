{% block extrahead %}
  <meta property="og:type" content="website" />
  <meta property="og:title" content="{{ title }}" />
  <meta property="og:description" content="{{ config.site_description }}" />
  <meta property="og:url" content="{{ page.canonical_url }}" />
  <meta content="#4051b6" data-react-helmet="true" name="theme-color">
{% endblock %}

# Home

Welcome to the all in one place for Aktindo's Projects. Here you can find

- Information on how to use all the projects.
- Tips on how to use them more immensly.
- How to setup the projects on your own machine.

## Documentation Notation

- Any argument that is wrapped with a `[]` is **optional**.
- Any argument that is wrapped with a `<>` is **required**.
- A `|` after the argument means that you can use either of the arguments.
- A `{}` after the argument means you can use those variables in it to create dynamic stuff.

!!! tip "Regular Tip"
    Arguments that have a `?` after them have to be followed by a rule.

    **For example:** If you have a argument - `<time?number>`, it states that time has to be a number and nothing else. 

    You can even see an another type - `<time?(number|literal)>`, it states that time can either be a number or a literal. 

## Documentation Status
- [ ] Fully Built
- [x] Fully Reviewed 