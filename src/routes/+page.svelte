<script>
	// Import the image if you have it locally, or use a direct URL
	import gameImage from './pooh.png';
</script>

<div class="container h-full mx-auto flex flex-col justify-center items-center">
	<div class="space-y-10 text-center">
		<h2 class="h1">WINNER THE POOH</h2>
		<h2 class="h2 mt-0">COMMITS INDUSTRIAL SABOTAGE</h2>
	</div>

	<div class="flex flex-row mt-10 mx-20">
		<div class="flex-none">
			<!-- Replace 'src' with the path or URL of your image -->
			<img src={gameImage} alt="..." class="w-48 h-48 object-cover" />
		</div>
		<div class="flex-grow ml-5">
			<h4 class="text-left h4">
				Winnie the Pooh Commits Industrial Sabotage is a single player Linear story FPS game.
			</h4>
			<p class="text-left">
				It was a beautiful day in the 100 acre forest when Winnie received a phone call from his
				friend Piglet informing him that the evil Rattington corporation has seized all of the land
				in the 100 acre forest and means to cut it down in the name of industrialization. Pooh
				angered by the information grabs for his rifle and seeks to stop the Rattington corporation
				from expanding into the woods The game is currently under development in the Unity Engine
				and will be available in late 2024 Click here to join the mailing list and recieve updates
				as the game production progresses
			</p>
		</div>
	</div>

	 <!-- Footer with Email Subscription Form -->
	 <div class="w-full mt-10 p-4">
        <div class="max-w-3xl mx-auto text-center">
            <h3 class="font-semibold text-lg">Subscribe to Our Newsletter</h3>
            <p class="text-gray-300">Get the latest updates about the game.</p>
            <form class="mt-4 flex justify-center">
				<label class="label">
					<input class="input p-2" type="text" placeholder="Enter your email" />
					<button type="button" class="btn variant-filled">Add Email To Newsletter</button>
				</label>
			
            </form>
        </div>
    </div>
</div>
