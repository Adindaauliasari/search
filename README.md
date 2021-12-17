#include "iostream"
  
using namespace std;

int main(){
  
	string kelas[3] = {"adinda","aulia","sari"};
	string cari;
  
	bool cek = false;
	
	cout << "nama yang ingin dicari : ";
	getline(cin, cari);
	
	for(int i=0;i<3;i++){
	
		if(cari==kelas[i])
		{ 
		
		cout << "nama tersebut adalah mahasiswa kelas B" << endl;
                                                              
	cek = true;
		}
	}
	
	if(cek==false){
	
	cout << "nama tersebut tidak ditemukan pada kelas B";
	}
}
