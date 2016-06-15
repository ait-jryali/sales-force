# sales-force
code read
public class MyHelloWorld {
2
   public static void applyDiscount(Book__c[] books) {
3
      for (Book__c b :books){
4
         b.Price__c *= 0.9;
5
      }
6
   }
7
}
