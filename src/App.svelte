<script>
	import { LayerCake, Svg } from "layercake";
	import { data } from "./data/data";

  
  </script>
  
  <main>
	<div class="chart-container">
	  <!-- <LayerCake
		data={grouped}
		padding={{ top: 0, right: 0, bottom: 0, left: 0 }}
	  >
		<Svg>
		  <Treemap bind:hovered {formatDollars} {rootHeight} />
		</Svg>
		<Tooltip {hovered} {formatDollars} />
	  </LayerCake> -->
	</div>
  </main>
  
  <style>
  
	main {
	  width: 100%;
	  height: 100%;
	}
  
	.chart-container {
	  width: 100%;
	  height: 100%;
	}
  </style>
  