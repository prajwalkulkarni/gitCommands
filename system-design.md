### Frontend System design

System design is the process of ideating and designing a scalable system adhering to a problem statement.
System design consists of two parts -> HLD and LLD

#### HLD
HLD or high-level design involves defining:
- Requirements: functional and non-functional
- Scoping and prioritizing the functional and non-functional requirements that will be touch-based.
- Tech choices to accomplish the design successfully

#### LLD
LLD or low-level design involves:
- Component architecture
- Protocols, schemas, and implementation details


### HLD
- Requirements: Functional
  - Essentially building blocks of the application
  - Mandatory features that shape the product

- Requirements: Non-functional
  - Generic features that enhance the UX, although it is termed as non-functional, it is important to implement the non-functional requirements as well.
  - Accessibility
  - Availability
  - Asset Optimization
  - Web Vitals
  - Consistency
  - Localisation
  - Performance
  - Logging & Monitoring
  - Security
 

#### Performance
- Lazy loading
- Using `async` & `defer` in script tags to avoid render blocking
- Intersection Observer (content-visiblity)
- Resource hinting (dns-prefetch, preconnect, prefetch, prerender)
- Rendering (Parsing -> Creating DOM & CSSOM -> Create render tree -> Create layout tree -> Create paint tree -> Draw pixels(Compositing))
