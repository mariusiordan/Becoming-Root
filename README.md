# Becoming Root

A small static blog I'm building by hand to practise HTML — a learning
journal about my path into Linux systems administration. It starts on the
homepage and threads through three posts: deciding to become a sysadmin,
choosing the RHCSA certification, and installing Rocky Linux to study on.
Plain, semantic HTML for now; styling comes next.

## Homepage layout

```
+---------------------------------------------------------+
| <header>                                                |
|   Becoming Root   <h1>                                  |
|   <nav>  Home . About . Categories . Contact            |
+----------------------------------+----------------------+
| <main>                           | <aside>              |
|                                  |                      |
|   <article>  - post preview 1    |   <section>          |
|     <h2>  <time>  <img>          |     About  <h3>      |
|     <p>   <a> read more          |                      |
|                                  |   <section>          |
|   <article>  - post preview 2    |     Recent posts     |
|                                  |                      |
|   <article>  - post preview 3    |   <section>          |
|     <blockquote>                 |     Categories       |
+----------------------------------+----------------------+
| <footer>   contact . links                              |
+---------------------------------------------------------+
```

## Files

```
becoming-root/
├── index.html 
├── style.css        
├── images/          
└── posts/
    ├── becoming-a-sysadmin.html
    ├── choosing-rhcsa.html
    └── installing-rocky-linux.html
```