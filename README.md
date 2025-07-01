 PushPullBoundary
# Push-Pull Boundary in Supply Chain Management

🥖 Push or Pull? How We Decided What to Pre-Bake and What to Customize in Our Bakery
When you run a bakery, deciding how much to bake in advance vs. what to make fresh per order is a daily balancing act.

We faced this exact challenge:
✅ Some products have stable, predictable demand.
❓ Others are made-to-order with unpredictable preferences.
And almost all of them share common ingredients.

🔍 The Dilemma
Pre-baking (Push) reduces preparation time, but can lead to waste if items aren't sold.

On-demand customization (Pull) ensures freshness and personalization, but risks stockouts or delays if not prepared in time.

We needed a way to:

Reduce spoilage,

Avoid losing customers due to delays,

And make the most of our limited kitchen capacity.

🧠 The Approach: Segment by Demand Behavior
We looked at each product’s:

Average daily demand

Variability (standard deviation / mean)

Holding cost (e.g., spoilage risk for pre-baked items)

Stockout cost (e.g., missed orders, customer dissatisfaction)

Then, we applied a push–pull boundary simulation:

💻 What We Simulated
For each product, we varied how much of its expected demand to pre-produce (push)
vs. how much to respond to on demand (pull)

We tracked total cost = holding cost + stockout cost

We identified the "sweet spot" boundary that minimizes total cost

🧪 For example:
A product with Mean=100, Std=20 showed optimal cost when we pre-made 45 units (push) and left 55 units for customization (pull).

✅ The Outcome
By simulating each product:

Croissants, sandwich bread → pre-baked in batches (low variability → push)

Custom cakes, eggless pastries, gluten-free requests → base prepped, finished upon order (high variability → pull)

Special orders → fully pulled with short lead-time slots

💡 Key Takeaway
The right mix of push vs. pull is not gut feeling—it's quantifiable.

Whether it’s food, fashion, or pharma—products with shared ingredients but variable final forms benefit immensely from delayed differentiation + simulation-driven planning.

👉 Want to apply this to your business?
Let’s chat about demand modeling or postponement strategies.

#SupplyChain #PushPull #BakeryBusiness #Customization #Postponement #OperationsResearch #Simulation #DecisionMaking #InventoryOptimization


