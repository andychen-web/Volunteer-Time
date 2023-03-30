<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-yellow w-100 px-3">
      <a class="navbar-brand" href="#">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="200"
          height="40"
          viewBox="0 0 399.467 61.529"
        >
          <g
            id="Group_658"
            data-name="Group 658"
            transform="translate(-33.533 -50.971)"
          >
            <text
              id="Volunteer_Time_"
              data-name="Volunteer Time "
              transform="translate(120 101.5)"
              font-size="45"
              font-family="SegoeUI, Segoe UI"
            >
              <tspan x="0" y="0">Volunteer Time</tspan>
            </text>
            <path
              id="Path_188"
              data-name="Path 188"
              d="M345.087,232.845s4.444-18.46-3.282-29.536c-6.52-9.347-24.693-11.452-31.335-12.809a146.171,146.171,0,0,0-21.278-.741s5.32,2.064,10.269,12.6S311.74,241,331.43,239.3c3.958-.34,8.681-3.282,8.681-3.282a65.357,65.357,0,0,0-7.41-17.15c-5.133-8.1-13.617-14.728-13.828-15.562s14.741,4.671,21.239,15.562S345.087,232.845,345.087,232.845Z"
              transform="translate(-281.765 -82.16) rotate(-9)"
            />
          </g>
        </svg>
      </a>
      <!-- toggle navbar btn for smaller size -->
      <button
        class="navbar-toggler d-none"
        type="button"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <!-- nav items -->
      <div class="justify-content-end" id="navbarNav">
        <ul class="navbar-nav d-lg-flex flex-row">
          <li class="nav-item active px-3">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item px-3">
            <a class="nav-link" href="#">Destination</a>
          </li>
          <li class="nav-item px-3">
            <a class="nav-link" href="#">Project Focus </a>
          </li>
          <li class="nav-item px-3">
            <a class="nav-link" href="#">Trip Type</a>
          </li>
          <li class="nav-item px-3">
            <a class="nav-link" href="#">Gallery</a>
          </li>
          <li class="nav-item px-3">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- main -->
  </div>
</template>

<script>
export default {
  name: "VolunteerTime",
};
</script>
