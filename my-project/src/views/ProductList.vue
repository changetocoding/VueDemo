<template>
  <div class="container-fluid">
    <h1>Bonsai Trees</h1>

    <div class="row mx-auto d-flex">
      <div class="card col-sm-4">
        <!-- You can refer to the image in the assets folder this way -->
        <!-- <img class="card-img-top" src="../assets/img/OutdoorBonsai/OutdoorBonsai_1.jpg" /> -->
        <!-- Or use the image on the api like this -->
        <img class="card-img-top" src="https://tbhpwebdevapi.azurewebsites.net/img/OutdoorBonsai/OutdoorBonsai_1.jpg" />
        <div class="card-body">
          <h5 class="card-title">Chinese Juniper Itagawa</h5>
          <p class="card-text">£2000.00</p>
          <a href="/product/1" class="btn btn-primary">More Info</a>
        </div>
      </div>
      <div class="card col-sm-4">
        <img class="card-img-top" src="../assets/img/OutdoorBonsai/OutdoorBonsai_2.jpg" />
        <div class="card-body">
          <h5 class="card-title">Large Chinese Juniper Itagawa</h5>
          <p class="card-text">£1495.00</p>
          <a href="/product/2" class="btn btn-primary">More Info</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      products: [
        {
          id: 1,
          productTitle: 'Chinese Juniper Itagawa',
          productPrice: 2000,
          productDescription:
            'Spectacular Itoigawa Chinese Juniper Tree, approximately 35-39cm tall and in a ceramic bonsai pot.',
          productImage: './img/OutdoorBonsai/OutdoorBonsai_1.jpg',
          checkoutOptions: ['Tools', 'Soil', 'Care'],
        },
        {
          id: 2,
          productTitle: 'Large Chinese Juniper Itagawa',
          productPrice: 1495,
          productDescription:
            'Lovely Large Itoigawa Chinese Juniper Tree, approximately 98-100cm tall.',
          productImage: './img/OutdoorBonsai/OutdoorBonsai_2.jpg',
          checkoutOptions: ['Tools', 'Soil', 'Care'],
        },
        {
          id: 3,
          productTitle: '35-38cm Itagawa',
          productPrice: 3250,
          productDescription:
            'Beautiful Chinese Itiogawa Juniper, approximately 35-38cm tall and planted in an oval ceramic bonsai pot.',
          productImage: './img/OutdoorBonsai/OutdoorBonsai_3.jpg',
          checkoutOptions: ['Tools', 'Soil', 'Care'],
        },
        {
          id: 4,
          productTitle: 'Brussels Bonsai',
          productPrice: 195,
          productDescription:
            'Lovely Brussels Bonsai Tree in a ceramic bonsai pot, approximately 27-29cm tall.',
          productImage: './img/OutdoorBonsai/OutdoorBonsai_4.jpg',
          checkoutOptions: ['Tools', 'Care'],
        },
        {
          id: 5,
          productTitle: 'Satsuki Azalea ',
          productPrice: 595,
          productDescription:
            'Gorgeous Satsuki Azalea  Bonsai Tree, approximately 28-33cm tall and planted in an unglazed oval ceramic bonsai pot.',
          productImage: './img/OutdoorBonsai/OutdoorBonsai_5.jpg',
          checkoutOptions: ['Tools', 'Care'],
        },
      ],
    };
  },
};
</script>

<style scoped>


</style>
