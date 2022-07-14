## How to position footer at bottom in Bootstrap?

In order for this element [position](https://mdbootstrap.com/docs/standard/utilities/position/) at the bottom of the page, you have to add `fixed-bottom` to the class `footer`.

```html
<footer class="bg-info text-center text-lg-start fixed-bottom">
  <!-- Grid container -->
  <div class="container p-4">
    <!--Grid row-->
    <div class="row">
      <!--Grid column-->
      <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
        <h5 class="text-uppercase">Links</h5>

        <ul class="list-unstyled mb-0">
          <li>
            <a href="#!" class="text-dark">Link 1</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 2</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 3</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 4</a>
          </li>
        </ul>
      </div>
      <!--Grid column-->

      <!--Grid column-->
      <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
        <h5 class="text-uppercase mb-0">Links</h5>

        <ul class="list-unstyled">
          <li>
            <a href="#!" class="text-dark">Link 1</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 2</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 3</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 4</a>
          </li>
        </ul>
      </div>
      <!--Grid column-->

      <!--Grid column-->
      <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
        <h5 class="text-uppercase">Links</h5>

        <ul class="list-unstyled mb-0">
          <li>
            <a href="#!" class="text-dark">Link 1</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 2</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 3</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 4</a>
          </li>
        </ul>
      </div>
      <!--Grid column-->

      <!--Grid column-->
      <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
        <h5 class="text-uppercase mb-0">Links</h5>

        <ul class="list-unstyled">
          <li>
            <a href="#!" class="text-dark">Link 1</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 2</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 3</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 4</a>
          </li>
        </ul>
      </div>
      <!--Grid column-->
    </div>
    <!--Grid row-->
  </div>
  <!-- Grid container -->

  <!-- Copyright -->
  <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
    © 2020 Copyright:
    <a class="text-dark" href="https://mdbootstrap.com/">MDBootstrap.com</a>
  </div>
  <!-- Copyright -->
</footer>
```

#### More information and detailed description can be found at [📄 Documentation page](https://mdbootstrap.com/how-to/bootstrap/footer-at-bottom/)
