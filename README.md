# K_toolbox
Matlab functions used in the book Krylov methods for nonsymmetric linear systems by G. Meurant and J. Duintjer Tebbens, Springer (2020)

% Files

%   K_Arnoldi_CGS               - Arnoldi with classical Gram-Schmidt

%   K_Arnoldi_CGS_2             - Arnoldi with classical Gram-Schmidt and reorthogonalization

%   K_Arnoldi_Householder       - Arnoldi with Householder transformations

%   K_Arnoldi_Householder_basic - Arnoldi with Householder transformations

%   K_Arnoldi_MGS               - Arnoldi with modified Gram-Schmidt

%   K_ASGMRES                   - Adaptive Simpler GMRES

%   K_Axel                      - Axelsson's method

%   K_BiCG                      - Biconjugate gradient

%   K_BiCGS                     - Biconjugate gradient squared

%   K_BiCGStab                  - Biconjugate gradient squared stabilized

%   K_BiCGStab2                 - Biconjugate gradient squared stabilized 2

%   K_BiCGStabl                 - Biconjugate gradient squared stabilized (ell)

%   K_biortho                   - Biorthogonal basis with 3-term recurrence

%   K_biortho_2t                - Biorthogonal basis with 2-term recurrence

%   K_biortho_bis               - Biorthogonal basis with 3-term recurrence

%   K_Chebyshev                 - Chebyshev basis

%   K_CMRH_new                  - CMRH optimized version

%   K_CMRHm                     - Restarted CMRH

%   K_CSBiCGStab                - Composite Step Biconjugate gradient squared stabilized

%   K_FOM_CGS                   - Full FOM with classical Gram-Schmidt

%   K_FOM_MGS                   - Full FOM with modified Gram-Schmidt

%   K_FOMm_MGS                  - Restarted FOM with modified Gram-Schmidt

%   K_GCR                       - Generalized conjugate residual

%   K_GCROT                     - GCROT, truncated version of Hicken and Zingg

%   K_givens                    - It zeroes the second component of [x; y]

%   K_GMRES_CGS                 - Full GMRES with classical Gram-Schmidt

%   K_GMRES_MGS                 - Full GMRES with modified Gram-Schmidt

%   K_GMRES_MGS_A               - Full GMRES with modified Gram-Schmidt, Ayachour's version

%   K_GMRES_MGS_err_est         - Full GMRES with modified Gram-Schmidt and error norm estimates

%   K_GMRESm_MGS                - Restarted GMRES with modified Gram-Schmidt

%   K_GPBiCG                    - GPBi-CG of S.L. Zhang

%   K_GPBiCGSafe                - GPBi-CGSafe Fujino and al

%   K_Hessenberg                - Hessenberg basis

%   K_HMRZ_stab                 - HMRZ Stab

%   K_housec                    - Householder transformation, x can be complex

%   K_householder               - Householder transformation, x must be real

%   K_householderc              - Householder transformation, x can be complex

%   K_IDR                       - IDR with s shadow vectors

%   K_IDR_Bio                   - Biorthogonal IDR with s vectors

%   K_IDR_classical             - Classical IDR with one vector, IDR(1)

%   K_IDR_QMR                   - QMR IDR with s vectors from Van Gizjen, Sleijpen and Zemke

%   K_IDRStab                   - IDR(s)Stab(ell) from Sleijpen and Van Gizjen

%   K_Newton_RS                 - Newton basis using Reichel's spoke sets

%   K_Orthodir                  - Orthodir

%   K_Orthores                  - Orthores

%   K_presc_convGMRES           - Matrix and right-hand side with a prescribed GMRES convergence

%   K_QMR_2t                    - QMR 2-term recurrences without look-ahead

%   K_QMR_3t                    - QMR 3-term recurrences without look-ahead

%   K_QMRBiCGStab               - Quasi Minimum Residual Biconjugate gradient squared stabilized

%   K_QORm_optinv               - Restarted Q-OR optimal

%   K_QORopt                    - Q-OR Opt basis

%   K_QORopt_basic              - Q-OR Opt basis, straightforward coding

%   K_QORopt_basis_trunc        - Truncated Q-OR optimal basis

%   K_QORopt_T                  - Q-OR Opt basis

%   K_QORopt_tridiag            - Q-OR Opt, uses V^T V = tridiagonal matrix

%   K_QORopt_trunc              - Q-OR Opt truncated with inverses of the Cholesky factors

%   K_QORoptinv                 - Q-OR Optinv with inverses of the Cholesky factors

%   K_TFQMR                     - Transpose free QMR of Roland Freund
