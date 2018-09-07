func canWeSit(placeDispoBus: Int, nombreDePersonne: Int) {
if placeDispoBus > nombreDePersonne
{
print("Il y a encore de la place")
} 
else if placeDispoBus == nombreDePersonne {
print("Il n'y a plus de place")
} 
else {
print("Il y a des gens debout")
}
}

canWeSit(placeDispoBus: 15, nombreDePersonne: 18)
