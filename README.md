void main() {
  const nbre = 70; 

  
  print('Devinez le nombre mystère (entre 1 et 100) :');
  String input = stdin.readLineSync()!;
  int nbre_s = int.tryParse(input) ?? 0;

  
  if (nbre_s < nbre) {
    print('ou rantre yon nonb ki pi piti.');
  } else if (nbre_s > nbre) {
    print('ou rantre yon nomb ki two gwo.');
  } else {
    print('Félicitations ! ou genyen');
  }
}
