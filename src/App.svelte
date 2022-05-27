<script lang="ts">
	import LayoutGrid, { Cell } from "@smui/layout-grid";
	import FaCircle from "svelte-icons/fa/FaCircle.svelte";
</script>

<div>
	<LayoutGrid>
		<Cell span={1}>
			<div class="right spacer">&nbsp;</div>
		</Cell>
		<Cell span={2}>
			<div class="peg-area">
				<div class="icon peg-senso-civico"><FaCircle /></div>
				<span class="peg-title">Senso civico</span>
			</div>
		</Cell>
		<Cell span={2}>
			<div class="peg-area">
				<div class="icon peg-corporeita"><FaCircle /></div>
				<span class="peg-title">Corporeità</span>
			</div>
		</Cell>
		<Cell span={2}>
			<div class="peg-area">
				<div class="icon peg-creativita"><FaCircle /></div>
				<span class="peg-title">Creatività</span>
			</div>
		</Cell>
		<Cell span={2}>
			<div class="peg-area">
				<div class="icon peg-carattere"><FaCircle /></div>
				<span class="peg-title">Carattere</span>
			</div>
		</Cell>
		<Cell span={2}>
			<div class="peg-area">
				<div class="icon peg-spiritualita"><FaCircle /></div>
				<span class="peg-title">Spiritualità</span>
			</div>
		</Cell>
		<Cell span={1}>
			<div class="right spacer">&nbsp;</div>
		</Cell>
	</LayoutGrid>
</div>

<style>
	.peg-area {
		display: flex;
		justify-content: center;
	}

	.spacer {
		display: flex;
		justify-content: center;
	}

	.icon {
		width: 20px;
		height: 20px;
		display: inline-block;
	}

	.peg-senso-civico {
		color: #ffa8b0;
	}

	.peg-corporeita {
		color: #99ff99;
	}

	.peg-creativita {
		color: #fffa8a;
	}

	.peg-carattere {
		color: #66ccff;
	}

	.peg-spiritualita {
		color: #d9b3ff;
	}

	.peg-title {
		margin-left: 1em;
	}
</style>
