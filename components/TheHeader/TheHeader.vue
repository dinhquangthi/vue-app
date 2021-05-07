<template >

        	<div id="Homepage" class="Homepage_Class">
		<img class="landscape" src="@/assets/images/landscape.png">
		<div class="Div_main">
			<div class="Logo">
				<div class="Travello_Go">
					<span>Travello </span><span style="color:rgba(255,158,78,1);">Go</span>
				</div>
				<svg class="icon_point" viewBox="0 0 28.353 50.405">
					<path fill="rgba(255,158,78,1)" stroke="rgba(0,0,0,1)" stroke-width="0.10000000149011612px"
						stroke-linejoin="miter" stroke-linecap="butt" stroke-dasharray="0 9" stroke-dashoffset="0"
						stroke-miterlimit="4" shape-rendering="auto" class="icon_point_Class"
						d="M 11.02634525299072 31.20258522033691 L 11.02634525299072 46.62863922119141 L 13.1942024230957 49.87944793701172 C 13.66183662414551 50.58041000366211 14.69260406494141 50.58041000366211 15.16023826599121 49.87944793701172 L 17.32711410522461 46.62863922119141 L 17.32711410522461 31.20258522033691 C 16.30422210693359 31.39161109924316 15.25376510620117 31.50384330749512 14.17672920227051 31.50384330749512 C 13.09969234466553 31.50384330749512 12.04923534393311 31.39161109924316 11.02634525299072 31.20258522033691 Z M 14.17672920227051 0 C 6.347039699554443 0 0 6.347039699554443 0 14.17672920227051 C 0 22.00642204284668 6.347039699554443 28.35345840454102 14.17672920227051 28.35345840454102 C 22.00642204284668 28.35345840454102 28.35345840454102 22.00642204284668 28.35345840454102 14.17672920227051 C 28.35345840454102 6.347039699554443 22.00642204284668 0 14.17672920227051 0 Z M 14.17672920227051 7.482162475585938 C 10.48487186431885 7.482162475585938 7.482162475585938 10.48487186431885 7.482162475585938 14.17672920227051 C 7.482162475585938 14.82846450805664 6.952504634857178 15.35812282562256 6.300768375396729 15.35812282562256 C 5.649032592773438 15.35812282562256 5.11937427520752 14.82846450805664 5.11937427520752 14.17672920227051 C 5.11937427520752 9.18238639831543 9.183370590209961 5.11937427520752 14.17672920227051 5.11937427520752 C 14.82846450805664 5.11937427520752 15.35812282562256 5.649032592773438 15.35812282562256 6.300768375396729 C 15.35812282562256 6.952504634857178 14.82846450805664 7.482162475585938 14.17672920227051 7.482162475585938 Z">
					</path>
				</svg>
			</div>

			<div class="form_corner">
				<div class="Group_1">
					<div class="Home">
						<span>Home</span>
					</div>
					<div class="Explore">
						<span>Explore</span>
					</div>
					<div class="Travel">
						<span>Travel</span>
					</div>
					<div class="Blog">
						<span>Blog</span>
					</div>
				</div>
				<div><button class="Login" id="Login-btn"><a style="text-decoration: none; color: white;"
							href="/login">Sign In</a></button></div>
			</div>

			<!-- Slogan -->
			<div class="Slogan">
				<div class="Slogan-up">
					<span>Let's Make <br />Your Best <br />Trip Ever</span>
				</div>
				<div class="Slogan-down">
					<span>The best travel for your journey<br />respectful of the environment</span>
				</div>
			</div>

			<div class="Search-form">
				<div class="Rectangle-9"></div>
				<div><button class="Search" id="Search-btn"><a style="text-decoration: none;">Search</a></button></div>

				<!-- From -->
				<div class="wrapper">
					<div id="From-text">
						<span>From</span>
					</div>
					<select id="selectCountry" name="selectCountry">
						<option value="">Choose Country</option>
					</select>
				</div>
				<script src="Js/script.js"></script>

				<!-- To -->
				<div class="wrapper2">
					<div id="From-text2">
						<span>To</span>
					</div>

					<select id="selectCountry2" name="selectCountry">
						<option value="">Choose Country</option>
					</select>
				</div>
				<script src="Js/script2.js"></script>

				<!-- Expected Date -->
				<div class="Expected-date">
					<div class="Expected-text">
						<span>Expected Date</span>
					</div>
					<input type="date" id="Expected" name="Expected">
				</div>

				<!-- One way -->
				<div class="one-way"><span class="one-way-text">One Way</span></div>

				<!-- Round trip -->
				<div class="round-trip"><span class="round-trip-text">Round Trip</span></div>

				<!-- Multi City -->
				<div class="multi-trip"><span class="multi-trip-text">Multi-City</span></div>
			</div>
		</div>
	</div>

</template>
<script>
export default {
    name: 'TheHeader'
}
</script>
