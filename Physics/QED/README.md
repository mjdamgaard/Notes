# QED

In my QED paper of 2022, I left some tasks for "future work." These tasks were:

* Task 1: Showing that a domain exists on which the Hamiltonian is self-adjoint.

* Task 2: Showing that its propagator can be approximated with bounded and discretized generators.

* Task 3: Showing Lorentz covariance.

* Task 4: Showing that pure states transform into pure states. (This task is not very important, but it might be interesting for some.)

* Task 5: Completing a Dirac sea reinterpretation and showing Lorentz covariance for the resulting theory.

I have just (d. 12.11.23 in the moment of writing) submitted a paper on the self-adjointness of a simplified Dirac interaction operator.
And the hope is that this result can be extended to the full Dirac Hamiltonian (and a wide range of other opertors).
So completing Task 1 might be feasable.


I think I have a way to solve Task 2 now (d. 27.11.23 in the moment of editing). I will write about it here sometime soon.
<!--
I thought that I had found a solution for Task 2, but that turned out not to be the case. So this task is still open.
The task is to show that all the $\varepsilon$-almost eigenstates of the discretized Hamiltonian converge into those of the continuous one
(given that these Hamiltonians have already been shown to be self-adjoint).
*\[I have just (d. 24.11.23) realized that the only reason that we would want to put an ultraviolet cutoff on the momenta for the operator
is if we want to derive the path integral from Section 4 in my QED paper, which is only something that we want to do, if we want to argue
the the operator is Lorentz-covariant! But since I no longer feel the need to do this very strongly, I will thus not need an ultraviolet
cutoff for this task! And without that, the task becomes really easy (which is not hard to see).
So consider this task as being in the same category as Task 3 and 4, i.e. of tasks that are only needed if one wants to complete the arguement
introduced in my QED paper that the operator is Lorentz-covariant (if one is not satisfied with the existing arguments of physics literature)!\]
*\[Oh no, I forgot that we need the ultraviolet cutoff in order for the constant energy coming from
$\hat d^\dagger \hat d \to \hat d^\dagger \hat d - 1$ to be finite!
...Oh, but one can just make a cutoff for the free energy first, so we might be good after all..:D\]
*\[I have just (d. 25.11.23) realized that the free energy might be infinite for the $\varepsilon$-almost eigenstates,
so it is not quite so simple after all... ...Oh, never mind: For any $\psi \in$ Dom($\hat H$) with an infinite free energy, we can just find
a $\psi + \phi$ that does not have an infinite free energy, where $\phi$'s norm can be much smaller than $\varepsilon$.\]
*\[Okay, I think we still need to solve this Task 2, since we need to argue that the Hamiltonian retains its Lorentz-covariance after the
Dirac sea reinterpretation. Luckily, however, I think I have just found a solution. The idea is to first make a cutoff for all final states,
and then afterwards make an ultraviolet cutoff on $k$. I think this works. ... Never mind! I ruined the symmetry again! x) ..But I might have just
had another breakthrough regarding this task, though...\]
-->

<!--
Let me just mention here that if one could show that all $\varepsilon$-almost eigenstates decreases faster than a certain polynomial
w.r.t. both photon number and momentum, then it seems that it be easy to show. But I am not very optimistic about this approach, though.
--> 

Task 3 and 4 deals with showing the Lorentz covariance of the theory, which is not quite as important for me now that I have realized
that the theory that I derived in my 2022 paper is equivalent to the conventional theory. (I thought the conventional theory did not contain a Coulomb potential.)
But they would still be nice to complete at some point. In my qed.tex document, which can currently be found in my backup folder, I believe I have worked out how to
solve these Tasks. (Task 4 is very easy but Task 3, on the other hand, is quite complicated.)
But I will probably not resume this work in the near future myself, at least not before the other tasks are already dealt with.

Now, Task 5 is were the really interesting stuff lies: Not only are its potential prospects increadibly exciting on a pure theoretical level, but the way I see it,
there is even a chance that it could lead to slightly altered experimental predictions! (Becasue it might tell us that we need to cut away all pair productions.)
I included a small note on how to solve this problem in Appendix C of the self-adjointness paper. I should elaborate some more on this idea, and in fact,
I have just (d. 23.11.23 in the moment of editing) started working on a new paper doing exactly this.


<!-- I will, however, also want to get back and work on my 'Semantic Database' project, which I have obviously neglected while writing my self-adjointness paper
in the past two months (from mid september to mid november). So I will probably focus on that project for a little while.
But I do certainly look forward to coming back and working more on this again, especially on Task 5: Not only is it increadibly exciting theoretically, but the way I see it,
there is even a chance that it could lead to slightly altered predictions! (Becasue it might tell us that we need to cut away all pair productions.) -->

(All my ideas here are also described (poorly, of course) in my working notes found in qed.tex and 23-xx note collection.tex, but I do not really expect anyone to read those.)

Feel free to email me if you have any questions about my work.
