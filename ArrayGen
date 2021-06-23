<?php
		function genArray($start, $stop) {
			$arr = [];
			$first = $start;
			do {				
				array_push($arr, $first);
				$first += 1;
			} while  ($first <= $stop);
			return $arr;
		}

		function sum($arr_elements) {
			return array_sum($arr_elements);
		}

		$generated = genArray(1, 10);
		echo sum($generated);
?>
