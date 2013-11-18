#!/usr/local/bin/perl

$inf = $ARGV[0];

open(IN, "$inf");
$otf = $inf.".UNR";
open(OUT, ">$otf");

while($line = <IN>){

  chop($line);
  $line  =~ s/(.*)\/faces\/(.*)/..\/faces\/$2/g;
  print OUT "$line \n";
}
