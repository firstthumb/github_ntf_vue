<template>
    <div class="app">
      <section class="hero is-fullheight is-light is-fullheight-with-navbar" >
		  <b-navbar>
        <template slot="brand">
            <b-navbar-item href="/">
                <img
                    src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>

        <template slot="end">
            <b-navbar-item href="#" class="has-text-weight-semibold">
                Home
            </b-navbar-item>
            <b-navbar-item href="#" class="has-text-weight-semibold">
                Notifications
            </b-navbar-item>
            <b-navbar-item href="#" class="has-text-weight-semibold">
                Settings
            </b-navbar-item>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-primary">
                        <strong>Sign up</strong>
                    </a>
                    <a class="button is-light">
                        Log in
                    </a>
                </div>
            </b-navbar-item>
        </template>
      </b-navbar>


		<div class="hero-body">
			<div class="container">
				<div class="columns is-centered">
					<div class="column is-7">
						<div class="search-form">
							<form>
								<div class="field has-addons has-shadow-field">
									<div class="control has-icons-left is-expanded">
										<input type="text" id="mainSearch" defaultvalue="" placeholder="Search repositories..." class="input is-large"> 
										<span class="icon is-small is-left">
											<svg class="svg-inline--fa fa-search fa-w-16" aria-hidden="true" data-prefix="fa" data-icon="search" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
												<path fill="currentColor" d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z">
												</path>
											</svg>
										</span>
									</div> 
									<div class="control">
										<a type="button" class="button is-large is-primary" v-smooth-scroll href="#container">
											<span class="has-text-weight-semibold">Search!</span>
										</a>
									</div>
								</div>
							</form>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>


	<section class="hero is-medium has-text-centered" >

		<div class="hero-body">
			<div id="container" class="container">
				<h1 class="title has-text-centered">
					Search for "Golang"
				</h1>
				<br>
				<div class="columns is-centered">
					<div class="column is-10">
						<div class="columns is-multiline">

              <column class="column is-full">
                <div class="box is-full">
                  <article class="media">
                    <div class="media-left">
                      <figure class="image is-64x64">
                        <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
                      </figure>
                    </div>
                    <div class="media-content">
                      <div class="content">
                        <p>
                          <strong>Tetris</strong> / <small>dtrupenn</small> 
                          <br>
                          A C implementation of Tetris using Pennsim through LC4
                        </p>
                      </div>
                      <nav class="level is-mobile">
                        <div class="level-left">
                          <a class="level-item" aria-label="reply">
                            <span class="icon is-small">
                              <i class="fas fa-reply" aria-hidden="true"></i>
                            </span>
                          </a>
                          <a class="level-item" aria-label="retweet">
                            <span class="icon is-small">
                              <i class="fas fa-retweet" aria-hidden="true"></i>
                            </span>
                          </a>
                          <a class="level-item" aria-label="like">
                            <span class="icon is-small">
                              <i class="fas fa-heart" aria-hidden="true"></i>
                            </span>
                          </a>
                        </div>
                      </nav>
                    </div>
                  </article>
                </div>
              </column>  

							

              <column class="column is-full">
                <div class="box is-full">
                  <article class="media">
                    <div class="media-left">
                      <figure class="image is-64x64">
                        <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
                      </figure>
                    </div>
                    <div class="media-content">
                      <div class="content">
                        <p>
                          <strong>Tetris</strong> / <small>dtrupenn</small> 
                          <br>
                          A C implementation of Tetris using Pennsim through LC4
                        </p>
                      </div>
                      <nav class="level is-mobile">
                        <div class="level-left">
                          <a class="level-item" aria-label="reply">
                            <span class="icon is-small">
                              <i class="fas fa-reply" aria-hidden="true"></i>
                            </span>
                          </a>
                          <a class="level-item" aria-label="retweet">
                            <span class="icon is-small">
                              <i class="fas fa-retweet" aria-hidden="true"></i>
                            </span>
                          </a>
                          <a class="level-item" aria-label="like">
                            <span class="icon is-small">
                              <i class="fas fa-heart" aria-hidden="true"></i>
                            </span>
                          </a>
                        </div>
                      </nav>
                    </div>
                  </article>
                </div>
              </column>

              <column class="column is-full">
                <div class="box is-full">
                  <article class="media">
                    <div class="media-left">
                      <figure class="image is-64x64">
                        <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
                      </figure>
                    </div>
                    <div class="media-content">
                      <div class="content">
                        <p>
                          <strong>Tetris</strong> / <small>dtrupenn</small> 
                          <br>
                          A C implementation of Tetris using Pennsim through LC4
                        </p>
                      </div>
                      <nav class="level is-mobile">
                        <div class="level-left">
                          <a class="level-item" aria-label="reply">
                            <span class="icon is-small">
                              <i class="fas fa-reply" aria-hidden="true"></i>
                            </span>
                          </a>
                          <a class="level-item" aria-label="retweet">
                            <span class="icon is-small">
                              <i class="fas fa-retweet" aria-hidden="true"></i>
                            </span>
                          </a>
                          <a class="level-item" aria-label="like">
                            <span class="icon is-small">
                              <i class="fas fa-heart" aria-hidden="true"></i>
                            </span>
                          </a>
                        </div>
                      </nav>
                    </div>
                  </article>
                </div>
              </column>

							

							
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>

	<footer class="hero is-small is-light">
		<div class="hero-body">
			<div class="container has-text-centered">
				<div class="columns m-t-10">
					<div class="column">
						<nav class="has-text-grey-light">
							<a href="#" class="has-text-primary">About</a> &bullet;
							<a href="#" class="has-text-primary">Description</a> &bullet;
							<a href="#" class="has-text-primary">Contact us</a> &bullet;
						</nav>
					</div>
				</div>
				<div class="b-t m-t-30 p-t-30 has-text-grey-light is-size-7">
					Github Notifier 2019 &copy; Erol Kocaman <br> <a href="#" class="has-text-primary">Terms of use</a> and <a class="has-text-primary" href="#">Privacy policy</a>.
					<a href="#" class="has-text-primary">Kocaman Housing</a>
				</div>
			</div>
		</div>
	</footer>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                name: 'John Silver'
            }
        }
    }
</script>

<style lang="scss">
.b {
  color: red;
}
</style>
