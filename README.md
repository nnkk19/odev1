import java.util.Scanner; 
public class OrtlmHesapla {
	
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
	
				
				// değişkenleri oluştur
		     int mat,fızık,kımya,tarih,muzik;
			
		     
		     // scanner sınıfımızı tanımla
		    Scanner inp = new Scanner(System.in);
			
			// kullanıcıdan değerleri alma
		   System.out.println("matematik notunu giriniz:");
		    mat= inp.nextInt();
		    
		    System.out.println("fızık notunu giriniz:");
		    fızık= inp.nextInt();
		    
		    System.out.println("kımya notunu giriniz:");
		    kımya= inp.nextInt();
		    
		    System.out.println("tarih notunu giriniz:");
		    tarih= inp.nextInt();
		    
		    System.out.println("muzik notunu giriniz:");
		    muzik= inp.nextInt();
		    
		    int toplam = (mat +fızık+ kımya+ tarih +muzik);
		    double sonuc = (toplam/5);
		    
		    System.out.println("ortalamanız"+sonuc);
		    
		    System.out.println(sonuc> 60.0 ? "Sınıfı Geçti": "Sınıfta Kaldı");
		    
			}
		}

	
