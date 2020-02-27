title: Microfrontends - Server Side Integration
class: animation-fade
layout: true


<!-- This slide will serve as the base layout for all your slides -->

---

class: impact center middle

# Introduction to Microfrontends

---

class: impact center middle

## Mario Fernandez
## Matthias Kainer
 
 **Thought**Works
 
---

class: center middle

## .bubble[Nov 19] Tech Radar

--

> We've seen significant benefits from introducing microservices, which have allowed teams to scale the delivery of independently deployed and maintained services. Unfortunately, we've also seen many teams create a front-end monolith — a large, entangled browser application that sits on top of the back-end services — largely neutralizing the benefits of microservices. 

--

<hr />

> Micro frontends have continued to gain in popularity since they were first introduced. We've seen many teams adopt some form of this architecture as a way to manage the complexity of multiple developers and teams contributing to the same user experience.

---

class: center middle

# What is a microfrontend?

---

picture of a service decomposed in microfrontends

---

### martinfowler.com/articles/micro-frontends.html

---

class: transition

# Benefits

---

class: center middle

## Incremental updates

???

- no big bang releases

---

class: center middle

## Decoupling

---

class: center middle

## Independent deployment

???

- path to production

---

class: center middle

## Autonomous teams

???

- vertical slicing instead of horizontal slicing

---

class: impact

# A fundamental tradeoff

---

picture: autonomy vs speed vs complexity

---

class: impact

# Integration approaches

---

chart with dimensions

build time integration
server side includes
iframes
client side composition (multiple approaches)
 - react components
 - the zalando lib
 - webcomponents

---

class: transition center middle

## Build time integration

---

lerna

---

example of package structure

---

how does a pipeline look like

---

pros / cons

---

class: transition center middle

## Server Side Includes

---

class: center middle

## what is a SSI?

---

class: center middle

> Server Side Includes (SSI) is a simple interpreted server-side scripting language used almost exclusively for the World Wide Web. It is most useful for including the contents of one or more files into a web page on a web server, using its #include directive.

---

nginx config

---

pros/cons

---

class: center middle

### thoughtworks.com/talks/a-high-performmance-solution-to-microservice-ui-composition

---

class: transition center middle

## Interacting with a Backend

---

picture of cross comunication

---

no-go mixing sources

---

talking about CI/CD


---

for MK

styling
inter app communication









