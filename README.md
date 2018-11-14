public class TallyCounter {

   private int tally = 0;

   public void pressButton() {
      tally++;
   }

   public void pressButton(int numTimes) {
      tally += numTimes;
   }
   
   public void reset() {
      tally = 0;
   }
   
   public int getTally() {
      return tally;
   }

}
