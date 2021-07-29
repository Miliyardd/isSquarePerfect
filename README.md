# isSquarePerfect
public static int isPerfectSquare(int n) {
		int nxtSqr = 0;

		while (nxtSqr * nxtSqr <= n) {
			nxtSqr++;
		}

		return nxtSqr * nxtSqr;
	}
