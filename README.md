#include 

int main()
{
    int tamsayi1,tamsayi2,tamsayi3,sonuc;
    
    printf("Birinci Tam Sayiyi Giriniz:");
    scanf("%d",&tamsayi1);
    
    printf("Ikinci Tam Sayiyi Giriniz:");
    scanf("%d",&tamsayi2);
    
    printf("Ucuncu Tam Sayiyi Giriniz:");
    scanf("%d",&tamsayi3);
    
    sonuc= tamsayi1*tamsayi2*tamsayi3;
    
    printf("%d*%d*%d=%d", tamsayi1,tamsayi2,tamsayi3,sonuc);
    

    return 0;
