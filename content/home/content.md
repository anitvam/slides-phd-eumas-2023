+++
weight = 10
+++

## We searched for popular BDI AOP languages

* **PYPL** PopularitY of Programming Language [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://pypl.github.io/PYPL.html)

* **TIOBE** [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://www.tiobe.com/tiobe-index/)

* **Stackoverflow developer survey** [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://survey.stackoverflow.co/2023/#most-popular-technologies-language-prof)

<br>
<br>
<br>

{{% fragment %}}

# No one <i class="fa-regular fa-face-frown"></i>

{{% /fragment %}}

---

# Why?

We identified 4 possible reasons

---

## 1. Learning curve vs ergonomics
<br>
<br>

{{< multicol >}}{{< col >}}

<h4> Libraries </h4>
<br>

<div>
<i class="fa-solid fa-check" style="color: green;"></i>
Gentle learning curve
</div>

<div>
<i class="fa-solid fa-check" style="color: green;"></i>
Large community
</div>

<div>
<i class="fa-solid fa-xmark" style="color: red;"></i>
Poor ergonomicity
</div>

{{< /col >}}{{< col >}}

<h4> Custom Languages </h4>
<br>

{{< tick >}}
High ergonomicity
{{< /tick >}}

{{< cross >}}
Steep learning curve
{{< /cross >}}

<div>
<i class="fa-solid fa-xmark" style="color: red;"></i>
Small community
</div>

{{< /col >}}{{< /multicol >}}

<!-- {{% fragment %}}
**AOP libraries** provide low ergonomics:
<br>
non-experienced users find difficulties to describe AOP entities
{{% /fragment %}}

{{% fragment %}}
vs
{{% /fragment %}}

{{% fragment %}}
**Custom Languages** have a steeper learning curve,
<br>
due to the custom syntax
{{% /fragment %}} -->

---

## 2. Tooling
#### (IDE, code suggestion, syntax highlighter, ...)
<br>
<br>

{{% multicol %}}{{% col %}}

<h4> Libraries </h4>
<br>

* Rely on existing **development tools**
* Can be integrated with existing **libraries**

{{% /col %}}{{% col %}}

<h4> Custom Languages </h4>
<br>

* Require **novel tooling**
    * and related **maintenance**
* Require **novel libraries** or **explicit bridges** to other ecosystems

{{< /col >}}{{< /multicol >}}

---

## 3. Middleware/Runtime requirements
<br>

* BDI AOP libraries rely on specific runtimes
    * e.g. **JVM**, **Python interpreter**, ...

* But systems could be designed to run on a large variety of devices, 
    * from **web** to **wearable**-oriented applications 

---

## 4. Concurrency model
<br>

* Limited configuration over the system **execution**
    * impact the system design
* BDI model definition should be completely agnostic<br>of the underlying concurrency model
    * Which should be **pluggable**.

---

# Jakta
## <u>Ja</u>son-like <u>K</u>o<u>t</u>lin <u>A</u>gents

Internal DSL implemented in Kotlin

* Native tools maintained by the community
* Multi-paradigm support
* Gentle learning curve, leveraging a mainstream language
* Good ergonomy

<br>

{{% fragment %}}

{{< figure src="images/qr-code.svg" width="15%" >}}
[github.com/jakta-bdi/jakta-examples](https://github.com/jakta-bdi/jakta-examples)

{{% /fragment %}}
