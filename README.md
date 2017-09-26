# EexTags



```elixir
Plug

send_resp(conn, 200, EEx.eval_file("template_name.eex",[tags: EexTags]))

file.eex

<% tags.version %>
<% tags.say("your name") %>

```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/eex_tags](https://hexdocs.pm/eex_tags).

