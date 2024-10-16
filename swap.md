# Swap

The swap page in Volex Finance allows users to exchange one token for another, specifically compressed tokens on the Solana blockchain. Below is an in-depth explanation of each element shown on the swap interface based on the image you provided:

### 1. Swap Interface

   The swap interface is designed to facilitate token exchanges between two different compressed tokens on Solana. The UI is clean and simple, ensuring a smooth experience for both beginner and experienced users.

### 2. From/To Fields

- **"From" Field**: This is where the user specifies the amount of the token they wish to swap from. The displayed token is the current token that the user holds or wants to trade. In the case the balance is shown as `0.000000000`, that indicates the user has no tokens available for swapping.  
- **"To" Field**: This field shows the token that the user wants to receive after the swap. The system automatically calculates the equivalent amount of tokens the user will receive based on the swap ratio.

### 3. Token Selector

- Both "From" and "To" fields have a token selector. This allows the user to select different tokens they want to swap or receive. By clicking on this field, users can choose from a list of supported tokens.

### 4. Swap Arrow (⇅)

- This double-sided arrow icon between the "From" and "To" fields allows users to **reverse the swap direction**. By clicking the arrow, the user can instantly switch which token they are sending ("From") and which they are receiving ("To"), making the swapping process flexible and quick.

### 5. Slippage Tolerance Settings

- **Set Slippage**: On the top right of the interface, users can manually set their preferred **slippage tolerance**. Slippage refers to the difference between the expected price of a token and the actual price at the time of the transaction. This occurs due to price changes during high volatility or low liquidity.  
- **Slippage Display**: Below the swap fields, the current slippage tolerance is shown as **1%**, meaning the user is willing to tolerate a 1% price difference during the swap. Users can adjust this value based on their risk tolerance and market conditions.

### 6. Balance Display

- The page also displays the user’s **balance** for the selected "From" token at the top. If the balance is **0.000000000**, that means the user does not have enough tokens to initiate a swap. The system also alerts the user in a red text.

### 7. Swap Button

- The **Swap** button at the bottom initiates the swap transaction. When clicked, it will prompt the user to confirm the swap based on the current exchange rates, slippage tolerance, and fees.
- In the current state, the button is **disabled** (gray) due to the insufficient balance. The button becomes active once a valid amount of tokens is available for swapping and all the necessary conditions (like slippage) are met.

---

## How It Works

1. **Selecting Tokens**: Users select the token they want to swap from (e.g., "GGM...S4") and the token they wish to receive.
2. **Input Amount**: Users input the desired amount in the "From" field. The interface will automatically calculate how much of the "To" token will be received based on current market rates.
3. **Adjust Slippage**: If the user expects market volatility, they can adjust the slippage tolerance to avoid failed transactions.
4. **Swap Execution**: Once everything is set (sufficient balance, selected tokens, slippage), the user can click the "Swap" button to confirm the transaction. After confirmation, the swap is processed on the Solana blockchain, and the user receives the new token.

---

### Features and Benefits

- **Real-Time Price Data**: The swap interface pulls in real-time price data from liquidity pools and DEXs on Solana, ensuring users always receive up-to-date rates when trading compressed tokens.
- **Low Fees and Fast Transactions**: Thanks to the underlying zkCompression technology, swapping tokens on Volex Finance is cheaper and faster compared to traditional token exchanges, reducing both on-chain costs and transaction times.
- **Customizable Slippage Tolerance**: Allowing users to customize their slippage tolerance gives them more control over the price they are willing to accept, especially during periods of high market volatility.
- **User-Friendly Design**: The simple, intuitive interface is designed to make token swaps straightforward, even for users new to DeFi or compressed tokens.

In summary, the **Swap page** on Volex Finance is a powerful tool that lets users trade compressed tokens with minimal friction, ensuring fast transactions, low fees, and a high degree of customization.
