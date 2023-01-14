---
title: Documentation
url: "docs"
description: Learn more about the team maintaining Docura, how and why the project started, and how to get involved.
aliases:
- "/docs/overview"
---

## h2 header

### h3 header

#### h4 header

##### h5 header

###### h6 header

_Lorem ipsum_ dolor sit amet, `consectetur` adipisicing elit, sed do eiusmod tempor incididunt ut **labore** et dolore magna aliqua. Ut enim ad minim veniam quis nostrud [exercitation ullamco](https://github.com/dumindu/css-playground) laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Lorem ipsum dolor sit amet, consectetur adipiscing elit

1. consectetur adipisicing elit
    1. t enim ad minim veniam

* consectetur adipisicing elit
    * consectetur adipisicing elit

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.
>
> commodo consequat [Duis aute](https://github.com/dumindu/css-playground)

```rust
fn main() {
    println!("Hello, world!");
}
```

```go
package app

import "net/http"

func HandleIndex(w http.ResponseWriter, _ *http.Request) {
	w.Header().Set("Content-Length", "12")
	w.Header().Set("Content-Type", "text/plain; charset=utf-8")
	w.Header().Set("X-Content-Type-Options", "nosniff")

	w.Write([]byte("Hello World!"))
}
```

{{< highlight yml "linenos=inline,hl_lines=5-6,linenostart=4" >}}
app:
  build:
    context: .
    dockerfile: ./docker/app/Dockerfile
  env_file:
    - ./docker/app/.env
  ports:
    - "8080:8080"
{{< / highlight >}}

![Colorful galaxy](https://images.unsplash.com/photo-1464802686167-b939a6910659?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2650&q=80)
Image credit: [Jeremy Thomas](https://unsplash.com/@jeremythomasphoto)