<template>
  <div id="contact">
    <div class="container">
      <div class="title-div">
        <h2 class="">
          Get in touch!
        </h2>
        <span class="subtitle">
          Have a question or want to work together?
        </span>
      </div>
      <div class="contact-card">
        <div class="columns contact-info">
          <div class="column is-one-third">
            <div class="container">
              <h5 class="">Contact Form</h5>
              <h6 class="">
                Fill out the form and I will get back to you within 24 hours.
              </h6>

              <ul class="contact-list">
                <li class="contact-info">
                  <i class=""></i>
                  <span class="contact-font">
                    443 774 5505
                  </span>
                </li>
                <li class="contact-info">
                  <i class=""></i>
                  <span class="contact-font">
                    phill.mitchell211@gmail.com
                  </span>
                </li>
                <li class="contact-info">
                  <i class=""></i>
                  <span class="contact-font">
                    Baltimore, MD
                  </span>
                </li>
              </ul>
              <ul class="social-icons">
                <li class="">
                  <i class=""></i>
                </li>
                <li class="">
                  <i class=""></i>
                </li>
              </ul>
              <img src="" alt="bubbles" />
            </div>
          </div>
          <div class="column">
            <div class="container">
              <h5 class="">Contact Form</h5>
              <form action="" class="contact-form">
                <div class="columns">
                  <div class="column">
                    <div class="field">
                      <label class="label">Name</label>
                      <div class="control">
                        <input
                          class="input"
                          type="text"
                          placeholder="Text input"
                        />
                      </div>
                    </div>
                    <div class="field">
                      <label class="label">Email</label>
                      <div class="control">
                        <input
                          class="input"
                          type="text"
                          placeholder="Text input"
                        />
                      </div>
                    </div>
                    <div class="field">
                      <label class="label">Phone</label>
                      <div class="control">
                        <input
                          class="input"
                          type="text"
                          placeholder="Text input"
                        />
                      </div>
                    </div>
                  </div>
                  <div class="column">
                    <div class="field">
                      <div class="control">
                        <textarea
                          class="textarea"
                          placeholder="Normal textarea"
                        ></textarea>
                      </div>
                    </div>
                  </div>
                </div>
                <span class="service-contact-title">Services</span>
                <h6 class="service-contact-subtitle">
                  choice one or more service
                </h6>
                <div class="buttons">
                  <button class="button is-primary">Primary</button>
                  <button class="button is-primary">Primary</button>
                  <button class="button is-primary">Primary</button>
                </div>
                <div class="field">
                  <div class="control">
                    <button class="button is-link">Submit</button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact"
};
</script>

<style>
#contact {
  background-color: #ffffff;
}
</style>
