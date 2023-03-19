public class Main {

    public static void main(String[] args) {
        //Гардероб
        double coat = 70;
        int coatDiscount = 45;
        double het = 25;
        int hatDiscount = 37;
        
        //Счёт
        double account = 312;
        
        //Сумма всех товаров
        double sumAll = coat -(coat * coatDiscount / 100) + hat - (hat * hatDiscount / 100);
        
        //Вывод результатов
        if (account >=sumAll) System.out.println("Имеющихся средств для покупки деловогогардероба достаточно");
        else System.out.println("Денег недостаточно");
        }
        
  
    }
    
}
  
  
