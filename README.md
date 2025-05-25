![problem](https://github.com/XTarekkX/markov-decision-process/assets/153951595/8216fa39-ff91-41bd-aa7f-90f890bb8884)
# Value Iteration on a 3x3 Grid World

## 1. Problem Statement
This project involves implementing **value iteration** on a simple 3x3 grid world environment. The grid world consists of an agent that can take four possible actions: **Up**, **Down**, **Right**, and **Left**.

### Environment Details:
- The agent attempts to move in the intended direction with **80% probability**.
- With the remaining **20% probability**, the agent moves at right angles (either perpendicular left or right of the intended direction).
- If the agent tries to move into a wall or off the grid, it stays in the same position (no movement occurs on collision).

The goal is to analyze the agent's policy behavior under different reward values.

---

## 2. Requirements

1. **Implement Value Iteration** for the grid world with each of the following rewards (`r`):
   - **r = 100**
   - **r = 3**
   - **r = 0**
   - **r = -3**

2. Use a **discount factor (γ) of 0.99** for the discounted rewards.

3. **Show the policy** obtained for each value of `r`.

4. **Explain intuitively** why the chosen value of `r` leads to each resulting policy.

---

## Additional Notes

- This project explores how varying the reward influences the optimal policy derived through value iteration.
- The stochastic nature of the agent's movement (80% intended, 20% sideways) introduces uncertainty, making the value iteration a meaningful way to derive policies that maximize expected rewards under these dynamics.

---

## How to Run
1. Run the value iteration code with each reward value.
2. Visualize and compare the policies.
3. Analyze the policy changes as the reward `r` varies.

---

Feel free to reach out for any questions or clarifications!

