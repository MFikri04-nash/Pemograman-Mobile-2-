# Pemograman-Mobile-2-
'''
import 'dart:async';

Future<void> main() async {
  String nama = 'M Fikri Nasrulloh';
  String nim = '23552011337';

  print('========================================');
  print('DATA DIRI');
  print('Nama: $nama');
  print('NIM: $nim');
  print-

  var input = [
    ["1", "Sistem Mikroprosessor"],
    ["2", "Pemrograman Mobile 2"],
    ["3", "Pemrograman Web 1"],
    ["4", "Keamanan Informasi"],
    ["5", "Bahasa Indonesia"],
    ["6", "Keamanan Jaringan"],
    ["7", "Pengembangan Diri"],
    ["8", "Sistem Informasi Enterprise"],
    
  ];

  List<String> harapanNilai = List.filled(input.length, "A");

  print('\n========================================');
  print('MATA KULIAH YANG DIAMPU');
  for (var matkul in input) {
    print('${matkul[0]}. ${matkul[1]}');
  }

  print('\n========================================');
  print('HASIL HARAPAN NILAI');
  for (int i = 0; i < input.length; i++) {
    print('${input[i][1]}: ${harapanNilai[i]}');
  }
  print('========================================\n');

  await tampilkanMotivasi();
}

Future<void> tampilkanMotivasi() async {
  await Future.delayed(Duration(seconds: 1));
  
  print('Kata Motivasi:');
  print('"Jangan Takut Gagal, Sukses Datang Dari Akal."');
}
'''
