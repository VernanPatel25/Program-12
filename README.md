public class Q9
{
    public static void main(int x, int a)
    {
        int j=0;
        switch(a)
        {
            case 1://fractional addition
                  for(int i=2;i<=20;i+=3)
                   {
                       j= (x/i);
                       System.out.println(j);
                   }
                   break;
            case 2://even addition, with alternate negative
                  for(int i=2;i<=20;i+=2)
                  {
                    if(i%4==0)
                    {
                         j=j-i;
                                             }
                    else
                    {
                        j=i+j;
                                            }
                  }
                  System.out.println(j);
                  break;
            default:
                  System.out.println("Wrong input");
        }
    }
}
