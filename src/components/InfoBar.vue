<template>
  <div class="art-info-bar">
    <div class="art-info-bar-frame">
      <div class="art-info-bar-header">
        <a class="art-info-bar-btn" href="#.">
          <i class="fas fa-ellipsis-v"></i>
        </a>
      </div>
      <div class="art-header">
        <div class="art-avatar">
          <a
            data-fancybox="avatar"
            href="img/face-1.jpg"
            class="art-avatar-curtain"
          >
            <img src="img/face-1.jpg" alt="avatar" />
            <i class="fas fa-expand"></i>
          </a>
          <div class="art-lamp-light">
            <div class="art-available-lamp"></div>
          </div>
        </div>
        <h5 class="art-name mb-10">
          <a href="/home.html">NGUYEN VAN THAO</a>
        </h5>
        <div class="art-sm-text">Back-end Developer <br />MMO Online,</div>
      </div>
      <div id="scrollbar2" class="art-scroll-frame">
        <div class="art-table p-15-15">
          <ul>
            <li>
              <h6>Residence:</h6>
              <span>Viet Nam</span>
            </li>
            <!-- city -->
            <li>
              <h6>City:</h6>
              <span>Ho Chi Minh</span>
            </li>
            <!-- age -->
            <li>
              <h6>Age:</h6>
              <span>19</span>
            </li>
          </ul>
        </div>
        <!-- info bar about end -->
        <div class="art-ls-divider"></div>

        <!-- knowledge list -->
        <ul class="art-knowledge-list p-15-0">
          <li>
            Have in programming with good communication and quick learning
            skills
          </li>
        </ul>
        <!-- divider -->
        <div class="art-ls-divider"></div>

        <!-- knowledge list -->
        <ul class="art-knowledge-list p-15-0">
          <li>HTML, CSS, JavaScript</li>
          <li>PHP, MySQL</li>
          <li>CMS (WordPress)</li>
          <li>RESTful API</li>
          <li>Server (Apache), Docker, Github</li>
          <li>
            <a target="_blank" href="https://github.com/thaolaptrinh">Github</a>
          </li>
        </ul>
        <!-- knowledge list end -->

        <!-- divider -->
        <div class="art-ls-divider"></div>

        <!-- links frame -->
        <div class="art-links-frame p-15-15">
          <!-- download cv button -->
          <a href="files/CV_Nguyen_Van_Thao.pdf" class="art-link" download
            >Download cv <i class="fas fa-download"></i
          ></a>
        </div>
        <!-- links frame end -->
      </div>
      <!-- scroll frame end -->

      <!-- sidebar social -->
      <div class="art-ls-social">
        <!-- social link -->
        <a href="#." target="_blank"><i class="far fa-circle"></i></a>
        <!-- social link -->
        <a href="#." target="_blank"><i class="far fa-circle"></i></a>
        <!-- social link -->
        <a href="#." target="_blank"><i class="far fa-circle"></i></a>
        <!-- social link -->
        <a href="#." target="_blank"><i class="far fa-circle"></i></a>
        <!-- social link -->
        <a href="#." target="_blank"><i class="far fa-circle"></i></a>
      </div>
      <!-- sidebar social end -->
    </div>
    <!-- menu bar frame end -->
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
