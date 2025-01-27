<template>
  <div>
    <Navbar />
    <ComponentTwo />
    <MyComponent />
    <ComponentFour />
    <ComponentFive />
    <ComponentSix />
    <ComponentSeven />
    <ComponentEight />
    <ComponentNine />
    <FooterComponent />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';
import ComponentTwo from '~/components/ComponentTwo.vue';
import MyComponent from '~/components/MyComponent.vue';
import ComponentFour from '~/components/ComponentFour.vue';
import ComponentFive from '~/components/ComponentFive.vue';
import ComponentSix from '~/components/ComponentSix.vue';
import ComponentSeven from '~/components/ComponentSeven.vue';
import ComponentEight from '~/components/ComponentEight.vue';
import ComponentNine from '~/components/ComponentNine.vue';
import FooterComponent from '~/components/FooterComponent.vue';


export default {
  name: 'MainLayout', // Provide a meaningful name for the component
  components: {
    Navbar, // Register the Navbar component
    ComponentTwo, // Register the  component
    MyComponent, // Register the  component
    ComponentFour,
    ComponentFive,
    ComponentSix,
    ComponentSeven,
    ComponentEight,
    ComponentNine,
    FooterComponent
  },
};
</script>

