Ката-1 
function square_sum($numbers) : int {
  $sum = 0;
  foreach ($numbers as $i) {
    $sum = $sum + ($i * $i);
  }
  return $sum;
}
https://www.codewars.com/kata/reviews/5b7350df86283d6338000089/groups/5dc252ed4814bd00017a057e

Ката-2 

function DNA_strand($dna) {
  $new_dna = strtr($dna, 'ATCG', 'TAGC');
  return $new_dna;
}
