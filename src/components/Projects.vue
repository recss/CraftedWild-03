<template>
  <section id="projects" class="grid--c12">
    <h2>The Results</h2>

    <!-- test -->
    <!-- <section id="light-gallery" v-on:click="lightItTheFuckUp" style="margin-bottom: 1em;">
      <a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1523241345/chicago__transitional/IMG_9978.jpg">
        <img src="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1523241345/chicago__transitional/IMG_9978.jpg" />
      </a>
      <a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1523241350/des-plaines__industrial-penthouse/IMG_0697.jpg">
        <img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1523241350/des-plaines__industrial-penthouse/IMG_0697.jpg" />
      </a>
    </section> -->

    <div id="blueimp-gallery" class="blueimp-gallery blueimp-gallery-controls">
        <div class="slides"></div>
        <h3 class="title"></h3>
        <a class="prev">‹</a>
        <a class="next">›</a>
        <a class="close">×</a>
        <a class="play-pause"></a>
        <ol class="indicator"></ol>
    </div>

    <section id="projects-gallery">
		<a id="west-town-sleek" v-on:click="blueImp($event, 'west-town-sleek')">
			<img src="https://res.cloudinary.com/craftedwild/image/upload/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_17.jpg" style="width: 100%; object-position: center top;">
			<p class="style">Sleek</p>
			<p class="location">West Town, Chicago, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_17.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_18.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_4.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_9.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_8.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_14.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_12.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_2.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331213/west-town__sleek/pdetphotography-craftedwild-714throop-chicago-12_22_2019_16.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="deerfield-rustic-farmhouse" v-on:click="blueImp($event, 'deerfield-rustic-farmhouse')">
			<img src="https://res.cloudinary.com/craftedwild/image/upload/v1585332201/deerfield__rustic-farmhouse/8.jpg" style="width: 100%; object-position: center top;">
			<p class="style">Rustic Farmhouse</p>
			<p class="location">Deerfield, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585332201/deerfield__rustic-farmhouse/8.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331091/deerfield__rustic-farmhouse/pdetphotography-craftedwild-woodvaleave-deerfield-kitchen_20.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331091/deerfield__rustic-farmhouse/4.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331091/deerfield__rustic-farmhouse/pdetphotography-craftedwild-woodvaleave-deerfield-kitchen_6.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331091/deerfield__rustic-farmhouse/9.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331091/deerfield__rustic-farmhouse/3.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331091/deerfield__rustic-farmhouse/7.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585331090/deerfield__rustic-farmhouse/5.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="noble-square-precision" v-on:click="blueImp($event, 'noble-square-precision')">
			<img src="https://res.cloudinary.com/craftedwild/image/upload/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_6.jpg" style="width: 100%; object-position: center top;">
			<p class="style">Minimalistic Precision</p>
			<p class="location">Noble Square, Chicago, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_6.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_12.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_10.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_24.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_1.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_20.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_21.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_13.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330964/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_17.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330963/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_16.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,h_800/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1585330963/noble-square__minimalistic-precision/pdetphotography-craftedwild-330wdiversey-chicago_15.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="modern-gem" v-on:click="blueImp($event, 'modern-gem')">
			<img src="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_600/v1555946205/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_23.jpg" style="width: 100%; object-position: center top;">
			<p class="style">Mid-Century Modern Gem</p>
			<p class="location">Barrington Hills, IL</p>

			<!-- gallery -->
			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946205/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_23.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946208/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_29.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946206/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_22.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946767/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_14.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946204/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_30.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946767/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_21.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946207/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_24.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946207/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_25.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946204/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_16.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946767/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_8.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946767/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_10.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946208/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_27.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946207/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_26.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946208/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_28.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946767/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_15.jpg"></a>

			<a href="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1555946205/barrington__modern-gem/pdetphotography-craftedwild-280-leeds-barrington_19.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="walnut-accents-kildeer" v-on:click="blueImp($event, 'walnut-accents-kildeer')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1551725308/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_4.jpg">
			<p class="style">Bright with Walnut Accents</p>
			<p class="location">Kildeer, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725306/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_7.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725308/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_14.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725307/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_13.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725306/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_11.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725305/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_12.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725303/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_5.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725303/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_9.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725302/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_8.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725301/kildeer__bright-walnut-accents/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_10.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="oasis-kildeer" v-on:click="blueImp($event, 'oasis-kildeer')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1551725178/kildeer__5-piece-oasis/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_23.jpg">
			<p class="style">5-Piece Oasis</p>
			<p class="location">Kildeer, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725222/kildeer__5-piece-oasis/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_25.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725222/kildeer__5-piece-oasis/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_27.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725182/kildeer__5-piece-oasis/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_15.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725181/kildeer__5-piece-oasis/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_18.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725178/kildeer__5-piece-oasis/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_20.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725177/kildeer__5-piece-oasis/pdetphotography-craftedwild-cabinetry-21211-laurel-kildeer_17.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="pop-barrington" v-on:click="blueImp($event, 'pop-barrington')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1551724761/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_2.jpg">
			<p class="style">Three-Tone with POP</p>
			<p class="location">Barrington, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724854/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_16.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724854/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_4.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724765/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_9.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724764/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_8.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724761/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_12.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724761/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_2.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724760/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_11.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724759/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_10.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724758/barrington__three-tone-pop/pdetphotography-craftedwild-cabinetry-851-summit-barrington_5.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="elegance-highland" v-on:click="blueImp($event, 'elegance-highland')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1551724905/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_2.jpg">
			<p class="style">Black &amp; White Elegance</p>
			<p class="location">Highland Park, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551725002/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_15.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724904/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_17.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724903/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_11.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724902/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_14.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724902/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_4.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724899/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_12.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724898/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_3.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1551724898/highland-park__bw-elegance/pdetphotography-craftedwild-cabinetry-2146sheridan-highlandpark_1.jpg"></a>
		</a>

		<!--  -->
		<!--  -->
		
		<a id="contemporary-chicago" v-on:click="blueImp($event, 'contemporary-chicago')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1525628596/lakeview__contemporary-matte-white/owner/Lakeview1_kitchen2_ERA.jpg">
			<p class="style">Contemporary, Matte White</p>
			<p class="location">Chicago, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525628565/lakeview__contemporary-matte-white/owner/Lakeview1_kitchen_island_back_ERA.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525630084/lakeview__contemporary-matte-white/DPP_0717.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525630076/lakeview__contemporary-matte-white/DPP_0718.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525630083/lakeview__contemporary-matte-white/DPP_0719.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525630084/lakeview__contemporary-matte-white/DPP_0720.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525630076/lakeview__contemporary-matte-white/DPP_0721.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525630085/lakeview__contemporary-matte-white/DPP_0723.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525630085/lakeview__contemporary-matte-white/DPP_0724.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1525630085/lakeview__contemporary-matte-white/DPP_0725.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="penthouse-desplaines" v-on:click="blueImp($event, 'penthouse-desplaines')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1523241350/des-plaines__industrial-penthouse/IMG_0697.jpg">
			<p class="style">Industrial Penthouse</p>
			<p class="location">Des Plaines, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241350/des-plaines__industrial-penthouse/IMG_0697.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241353/des-plaines__industrial-penthouse/IMG_0701.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241366/des-plaines__industrial-penthouse/IMG_0702.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241365/des-plaines__industrial-penthouse/IMG_0704.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241369/des-plaines__industrial-penthouse/IMG_0705.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="glossy-schaumburg" v-on:click="blueImp($event, 'glossy-schaumburg')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1523241401/schaumburg__bw-splash/DPP_0641.jpg">
			<p class="style">Glossy White with Bold Backsplash</p>
			<p class="location">Schaumburg, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241401/schaumburg__bw-splash/DPP_0641.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241389/schaumburg__bw-splash/DPP_0635.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241395/schaumburg__bw-splash/DPP_0637.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241408/schaumburg__bw-splash/DPP_0638.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="open-portage" v-on:click="blueImp($event, 'open-portage')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1523241393/portage-park__open-concept/IMG_9465.jpg">
			<p class="style">Open Concept, Painted Shakers</p>
			<p class="location">Portage Park, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241393/portage-park__open-concept/IMG_9465.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241398/portage-park__open-concept/IMG_9464.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241395/portage-park__open-concept/IMG_9466.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241397/portage-park__open-concept/IMG_9467.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241398/portage-park__open-concept/IMG_9473.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="minimalist-chicago" v-on:click="blueImp($event, 'minimalist-chicago')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1548005462/lakeview__minimalist-warm/Lakeview_Apartment2_kitchen_and_dining.jpg">
			<p class="style">Minimalist, Warm</p>
			<p class="location">Chicago, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1548005462/lakeview__minimalist-warm/Lakeview_Apartment2_kitchen_and_dining.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1548005464/lakeview__minimalist-warm/Lakeview_Apartment2_kitchen_detail1.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1548005464/lakeview__minimalist-warm/Lakeview_Apartment2_kitchen_detail2.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1548005459/lakeview__minimalist-warm/Lakeview_Apartment2_Entry.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="chic-evanston" v-on:click="blueImp($event, 'chic-evanston')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1523241363/evanston__chic-farm/DPP_0003.jpg">
			<p class="style">Chic Farm</p>
			<p class="location">Evanston, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241363/evanston__chic-farm/DPP_0003.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241369/evanston__chic-farm/DPP_0001.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241375/evanston__chic-farm/DPP_0004.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241380/evanston__chic-farm/DPP_0008.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1523241372/evanston__chic-farm/DPP_0012.jpg"></a>
		</a>

		<!--  -->
		<!--  -->

		<a id="concrete-university" v-on:click="blueImp($event, 'concrete-university')">
			<img src="http://res.cloudinary.com/craftedwild/image/upload/c_scale,w_400/v1543940250/university-village__concrete-loft/DPP_0860.jpg">
			<p class="style">Concrete Loft</p>
			<p class="location">University Village, Chicago, IL</p>

			<!-- gallery -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1543940250/university-village__concrete-loft/DPP_0860.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1543940249/university-village__concrete-loft/DPP_0857.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1543940249/university-village__concrete-loft/DPP_0858.jpg"></a>

			<!-- counters, shelves -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1543940254/university-village__concrete-loft/DPP_0867.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1543940252/university-village__concrete-loft/DPP_0863.jpg"></a>

			<!-- cabinets -->
			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1543940251/university-village__concrete-loft/DPP_0861.jpg"></a>

			<a href="https://res.cloudinary.com/craftedwild/image/upload/c_scale,w_1500/l_CraftedWild_logos:logo_white,o_60,w_0.25,g_north_west/v1543940253/university-village__concrete-loft/DPP_0865.jpg"></a>
		</a>
    </section>
  </section>
</template>

<script>
export default {
  name: 'Projects',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
    blueImp: function($event, _id) {
      let thing = document.getElementById(_id);

      (function() {
        $event = event || window.event;
        var target = event.target || event.srcElement,
          link = target.src ? target.parentNode : target,
          options = {index: link, event: event},
          links = thing.getElementsByTagName('a');
        blueimp.Gallery(links, options);
      })();
    }
  },
  created: function () {
    // NOTHING
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#projects {
	padding: 1em;
	color: #fff;
	background-color: #000;
	/* background-color: rgb(58,58,60); */
	line-height: 1.4;
}

#projects-gallery {
  width: 80vw;
  margin: 0 auto;
  display: flex;
    flex-flow: row wrap;
    justify-content: center;
}

#projects-gallery a {
  /* height: 20em; */
  flex-basis: calc(100%/4);
  margin-right: 1em;
  margin-bottom: 1em;
  padding-bottom: 0.25em;
  /* border: 1px solid #333; */
  /* border-radius: 0 0 5px 5px; */
  background-color: #333;
  cursor: pointer;
  opacity: 1;
  transition: 1s;
}

#projects-gallery a:focus,
#projects-gallery a:hover {
  opacity: 0.7;
}

#projects-gallery img {
  /*height: 75%;*/
  height: 225px;
  object-fit: cover;
  object-position: center;
}

#projects-gallery .style {
  margin-bottom: 0;
  color: rgba(255,255,255,0.5);
  font-size: 0.9em;
}

#projects-gallery .location {
  margin-top: 0;
  color: #fff;
}

@media (max-width: 1000px) {
  #projects-gallery a {
    height: 22.5em;
    flex-basis: calc(100%/2.5);
  }
}

@media (max-width: 800px) {
  #projects-gallery a {
    font-size: 0.9em;
    flex-basis: 100%;
  }
}
</style>
