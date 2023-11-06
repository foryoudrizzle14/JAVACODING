public class Solution {
    public int solution(int num1, int num2) {
        return num1 - num2;
    }

    public static void main(String[] args) {
        Solution solution = new Solution();
        
        int result1 = solution.solution(2, 3);
        System.out.println("Result 1: " + result1); // 출력 예상 결과: -1
        
        int result2 = solution.solution(100, 2);
        System.out.println("Result 2: " + result2); // 출력 예상 결과: 98
    }
}
