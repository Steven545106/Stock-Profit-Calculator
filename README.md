# Stock-Profit-Calculator

A professional, terminal-style profit/loss simulator designed for Taiwan stock traders. This tool uses a high-contrast dark theme and real-time calculation logic based on the Taiwan Stock Exchange (TWSE) tick size rules to help traders visualize potential returns across different price levels.

✨ Key Features :

  🎯 Smart Tick Price Control : Equipped with + and - buttons to adjust the buy price.

  📊 Multi-Dimensional Profit Matrix : Generates a matrix showing the potential profit/loss for the ±8 Ticks surrounding your buy price.

  🔄 Profit Zone Shifting : Features "Profit +5 Ticks" and "Loss -5 Ticks" buttons to shift the observation window.

  🧮 Precision Fee & Tax Calculation:

  Commission: Calculates fees using the standard Price * 1000 * 0.001425 * Discount formula.

  Transaction Tax: Supports both "Standard (0.3%)" and "Day Trading (0.15%)" tax rates.

  Pro-rata Costing: Automatically calculates the cost basis for the specific number of lots being sold if it differs from the number of lots purchased.

  🖥️ Professional Terminal UI:

  Wide-Screen Layout: Optimized for 1200px width to ensure all financial data columns (ROI, Net Profit) are clearly displayed without truncation.

  Trading Colors: Adheres to the Taiwan market convention (Red for gains, Green for losses) on a sleek dark background.

📖 How to Use

  1.Set Buy Price: Use the + or - buttons to align the price with your entry point.

  2.Input Quantities: Enter the number of lots (1,000 shares per lot) for both buying and selling.

  3.Adjust Fees: Set your broker's commission discount (e.g., enter 0.28 for a 72% discount).

  4.Select Mode: Choose between "Standard" or "Day Trading" to adjust the tax rate.

  5. Analyze: Click "Run Multi-Dimensional Analysis".

  ● The Total Purchase Cost (including fees) will appear immediately below the button.

  ● The table will display the profit/loss for 17 different price points (±8 Ticks).

  ● Use the Shift Buttons to move the view up or down to find your target exit price.

  
