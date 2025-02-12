# Infinite Bargaining Simulation

This project is an interactive **bargaining simulation** inspired by evolutionary game theory. The simulation models how strategies evolve over time – through mutation and selection – when haggling over a divisible prize. 

## **How It Works**
- Agents are **haggling** over a prize.
- Two agents are **randomly selected** from the population.
- Each agent **demands** a share of a prize.
– If the sum of their demands is more than the total prize, then they both get **nothing**.
- Otherwise, they **get what they demand** and reproduce based on their success.
- Each new generation **inherits demand strategies** with some probability of mutation.
  - When a mutation occurs, the demand value changes by a random amount up to the mutation amount. (For example, a mutation rate of .10 means that there is a 10% chance of a mutation in the demand of a random anount up to 10% of the prize total.)
- The chart (histogram) shows the **number of agents** making each demand.
- The **'rolling median'** demand from the previous ten rounds is shown below.
- The results of the simulation show that a **sense of fairness** evolves spontaneously in bargaining situations; agents tend to demand (just under) half the prize.
---

## **Features**
✅ **Interactive Controls**:
- **Adjust Prize Size**: Controls the total amount available for bargaining.
- **Adjust Mutation Rate**: Modifies how frequently demand strategies mutate.
- **Adjust Population Size**: Tests how population size affects evolution.
- **Start/Stop Simulation Button**: Lets you control when to run or pause.

✅ **Visual Evolution Tracking**:
- **Live Strategy Distribution Graph**: Displays the frequency of different demand strategies.

✅ **Optimized Performance**:
- Updates every **10 frames** to improve performance.

---

## **How to Run**
1. Click [here](https://oliverscottcurry.github.io/bargaining/fairness.html) or download `fairness.html`.
2. Open the file in **any modern web browser** (Chrome, Firefox, Edge, etc.).
3. The simulation will start when you click **"Start Simulation"**.
4. Adjust sliders and observe **how strategies evolve over time**!

---

## **Credits**
Developed by: Oliver Scott Curry (https://github.com/oliverscottcurry) using Chat GPT
  
Inspired by:

**Skyrms, B. (1996).** *Evolution of the Social Contract.* Cambridge University Press.
**Wilensky, U. (1997).** *NetLogo Divide The Cake model.* Northwestern University.  
  [NetLogo Divide The Cake Model](http://ccl.northwestern.edu/netlogo/models/DivideTheCake)

---

## **License**
This project is licensed under the Creative Commons License.
