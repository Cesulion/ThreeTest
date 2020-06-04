<template>
  <div class="test" id="container2">hellooo</div>
</template>

<script>
export default {
  name: "ThreeTest",

  data: () => ({}),
};

// import * as Three from "three";
// export default {
//   name: "ThreeTest",
//   data() {
//     return {
//       camera: null,
//       scene: null,
//       renderer: null,
//       cube: null,
//       targetElement: null,
//     };
//   },
//   methods: {
//     init: function() {
//       this.scene = new Three.Scene();

//       let container = document.getElementById("container2");

//       this.camera = new Three.PerspectiveCamera(
//         70,
//         container.clientWidth / container.clientHeight,
//         0.01,
//         1000
//       );
//       this.camera.position.z = 1;

//       let geometry = new Three.BoxGeometry(1, 1, 1);
//       let material = new Three.MeshBasicMaterial({ color: 0x00ff00 });
//       this.cube = new Three.Mesh(geometry, material);
//       this.scene.add(this.cube);

//       this.renderer = new Three.WebGLRenderer({ antialias: true });
//       this.renderer.setSize(container.clientWidth, container.clientHeight);
//       document.body.appendChild(this.renderer.domElement);
//     },
//     animate: function() {
//       requestAnimationFrame(this.animate);
//       this.cube.rotation.x += 0.01;
//       this.cube.rotation.y += 0.01;
//       this.renderer.render(this.scene, this.camera);
//     },
//   },
//   mounted() {
//     this.init();
//     this.animate();
//   },
// };
//
</script>

<style>
.test {
  background-color: rgb(61, 3, 3);
  height: 100%;
}
</style>
