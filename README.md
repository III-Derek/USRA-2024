# Understanding the Synchorization Properties of Two Coupled Izhikevich Neurons (USRA - 2024)

\subsection{The Model Itself}
Similar to integrate and fire model, the Izhikevich model has a resetting condition, but, this model also have a current variable u that modulates the faster voltage variable v. The dimensional Izhikevich model is as follows:
\begin{equation}\label{eq:1}
    \begin{aligned}
        C\dot{v} &= k(v - v_r)(v - v_t) - u + I_{\text{app}} \hspace{1cm} \text{if } 
        v \geq v_{\text{peak}}, \text{ then} \\
        \dot{u} &= a(b(v - v_r) - u) \hspace{3.2cm} v \rightarrow c, u \rightarrow u + d
    \end{aligned}
\end{equation}

Department: Department of Applied Mathematics at University of Waterloo

Supervisor: Sue Ann Campbell

Student: XinYe(Derek) Cheng

Thanks: Thank you for everyone in Professor Campbell's research group who helped me, and Ivan O. Shevchenko who worked on this previously. Big thank you to Professor Campbell!


