public class Productofarray
{
    public static  void main(String[]args)
    {
        int[]arr=new int[]{5,8,9,3,7};
        int product=0;
            for(int i=0;i<arr.length;i++) {
         product=product+arr[i];
          }
         System.out.println("Product of all the elements of an array:"+product);
    }
}
