# A_Differentiable_Joint_Trajectory_Approach（文章已被接收，正文和源码将在文章正式发表后开放）
This paper formulates this problem as maximizing the worst-user cumulative throughput over a time horizon,and introduces Differentiable Joint Trajectory Optimization,a fully differentiable framework that replaces hard max-min operations with smooth approximations, enabling gradient-based joint optimization of all UAV positions across time slots. 


![DJTO-OURS VS DG VS MCP](fig2_heatmap_waterfall.png)

第六代（6G）通信中，空中-地面一体化网络（SAGIN）与数字孪生（DT）系统对移动地面用户向核心网络传输数据提出了极高的端到端可靠性要求。采用双层无人飞行器（UAV）架构，包括接入无人机和回传无人机，可提供可扩展的解决方案，但因接入与回传之间存在耦合瓶颈，如何在用户移动性下长期保证公平性仍是一个未解决的挑战。本文将该问题建模为在一定时间范围内最大化最差用户的累计吞吐量，并提出可微分联合轨迹优化（DJTO）框架。该框架通过平滑逼近替代传统的硬性最大-最小操作，实现了在所有时隙内对所有UAV位置的梯度驱动联合优化。通过与解耦贪婪算法（DG）和模型预测控制（MPC）基准方法进行的全面实验表明，DJTO相比DG提升了最差用户的累计吞吐量20.5%，相比MPC提升20.4%；同时，时空热力图瀑布流可视化结果进一步验证了其在端到端覆盖范围和公平性方面的优越性。
