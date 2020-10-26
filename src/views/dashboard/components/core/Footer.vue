<template>
  <v-footer
    id="dashboard-core-footer"
    absolute
  >
    <v-container>
      <v-row
        align="center"
        no-gutters
      >
        <div>
          <a
            target="_blank"
          >KISM</a>
          <span
            class="ml-1"
          >&copy; 2020.</span>
        </div>

        <v-spacer class="hidden-sm-and-down" />

        <v-col
          cols="12"
          md="auto"
        >
          <div class="ml-auto">
            <span class="mr-1">Developed by</span>
            <a
              href="https://kinetics.co.ke"
              target="_blank"
            >Kinetics Technology LTD</a>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </v-footer>
</template>

<script>
  export default {
    name: 'DashboardCoreFooter',

    data: () => ({
      links: [
        {
          href: '#',
          text: 'Creative Tim',
        },
        {
          href: '#',
          text: 'About Us',
        },
        {
          href: '#',
          text: 'Blog',
        },
        {
          href: '#',
          text: 'Licenses',
        },
      ],
    }),
  }
</script>

<style lang="sass">
  #dashboard-core-footer
    a
      font-size: .825rem
      font-weight: 500
      text-decoration: none
      text-transform: uppercase
</style>
