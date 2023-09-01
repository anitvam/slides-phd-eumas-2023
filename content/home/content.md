+++
weight = 10
+++

# We searched for popular AOP languages

* {{% fragment %}}
**PYPL** PopularitY of Programming Language [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://pypl.github.io/PYPL.html)
{{% /fragment %}}

* {{% fragment %}}
**TIOBE** [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://www.tiobe.com/tiobe-index/)
{{% /fragment %}}

* {{% fragment %}}
**Stackoverflow developer survey** [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://survey.stackoverflow.co/2023/#most-popular-technologies-language-prof)
{{% /fragment %}}

<br>
<br>
<br>


{{% fragment %}}

# No one at all &#129335; 

{{% /fragment %}}

---

# Why?

We identified 4 possible reasons

---

# 1. Learning curve vs ergonomics
<br>
<br>

{{< multicol >}}{{< col >}}

{{< fragment >}}
<h4> AOP Libraries </h4>
<br>
{{< /fragment >}}

{{< fragment >}}
<div>
<i class="fa-solid fa-check" style="color: green;"></i>
Gentle learning curve
</div>
{{< /fragment >}}

{{< fragment >}}
<div>
<i class="fa-solid fa-check" style="color: green;"></i>
Large community
</div>
{{< /fragment >}}

{{< fragment >}}
<div>
<i class="fa-solid fa-xmark" style="color: red;"></i>
Poor ergonomicity
</div>
{{< /fragment >}}

{{< /col >}}{{< col >}}

{{< fragment >}}
<h4> Custom Languages </h4>
<br>
{{< /fragment >}}

{{< fragment >}}
<div>
<i class="fa-solid fa-check" style="color: green;"></i>
High ergonomicity
</div>
{{< /fragment >}}

{{< fragment >}}
<div>
<i class="fa-solid fa-xmark" style="color: red;"></i>
Steep learning curve
</div>
{{< /fragment >}}

{{< fragment >}}
<div>
<i class="fa-solid fa-xmark" style="color: red;"></i>
Small community
</div>
{{< /fragment >}}

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

# 2. Tooling
#### (IDE, code suggestion, syntax highlighter, ...)
<br>
<br>

{{< multicol >}}{{< col >}}

{{< fragment >}}
<h4> AOP Libraries </h4>
<br>
{{< /fragment >}}

{{% fragment %}}
Come with a large set of well-known **development tools** and **utilities libraries** built for the mainstream language in which they rely on
{{% /fragment %}}

{{< /col >}}{{< col >}}

{{< fragment >}}
<h4> Custom Languages </h4>
<br>
{{< /fragment >}}

{{% fragment %}}
Needs to **implement** all the tooling required to support programmers, which is a time-valuable task
{{% /fragment %}}

{{< /col >}}{{< /multicol >}}

---

# 3. Middleware/Runtime requirements
<br>

{{% fragment %}}

The majority of BDI AOP libraries rely on specific runtimes, e.g. **JVM**, **Python interpreter**, ...

{{% /fragment %}}

<br> 

{{% fragment %}}

But BDI AOP systems could be designed to run on a large variety of devices, 
<br>
from **web** to **wearable**-oriented applications 

{{% /fragment %}}

---

# 4. Concurrency model
<br>

{{% fragment %}}
Current BDI AOP languages offer limited configuration over the **execution** of an agent system.
{{% /fragment %}}

<br>

{{% fragment %}}
We believe that a BDI model definition should be completely agnostic of the underlying concurrency model, which should be **pluggable**.
{{% /fragment %}}

---

# Jakta
## <u>Ja</u>son-like <u>K</u>o<u>t</u>lin <u>A</u>gents

Internal DSL implemented in Kotlin

* {{< frag c="Native tools maintained by the community" >}}

* {{< frag c="Multi-paradigm support" >}}

* {{< frag c="Gentler learning curve, leveraging a mainstream language" >}}

* {{< frag c="Good ergonomy" >}}

<br>
<br>
<br>

{{% fragment %}}

{{< figure src="images/qr-code.svg" width="20%" >}}
[github.com/jakta-bdi/jakta-examples](https://github.com/jakta-bdi/jakta-examples)

{{% /fragment %}}

---

# is multicol working ?

{{< multicol >}}{{< col >}}
First column
{{< /col >}}{{< col >}}
Second column
{{< /col >}}{{< /multicol >}}

<div class="container">
  <div class="row">
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
    <div class="col">
      Columns
    </div>
        <div class="col">
      Column
    </div>
  </div>
</div>