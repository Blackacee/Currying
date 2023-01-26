# Currying

var prism = function(l, w, h) {
 return l * w * h;
}
function prism(l) {
 return function(w) {
 return function(h) {
 return l * w * h;
 }
 
