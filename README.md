<h1>MyToken Smart Contract</h1>

<p>MyToken is a simple ERC-20 like token implemented in Solidity. This smart contract includes basic functionalities such as minting and burning tokens.</p>

<h2>Features</h2>
<ul>
    <li><strong>Public Variables:</strong>
        <ul>
            <li><code>name</code>: The name of the token (Blunt).</li>
            <li><code>symbol</code>: The abbreviation of the token (BT).</li>
            <li><code>totalSupply</code>: The total supply of tokens in existence.</li>
        </ul>
    </li>
    <li><strong>Mapping:</strong>
        <ul>
            <li><code>balances</code>: A mapping from addresses to their respective balances.</li>
        </ul>
    </li>
    <li><strong>Functions:</strong>
        <ul>
            <li><code>mint(address _address, uint256 _value)</code>: Mints <code>_value</code> amount of tokens to the <code>_address</code> address, increasing the total supply and the balance of the specified address.</li>
            <li><code>burn(address _address, uint256 _value)</code>: Burns <code>_value</code> amount of tokens from the <code>_address</code> address, decreasing the total supply and the balance of the specified address. Ensures the address has sufficient balance to burn.</li>
        </ul>
    </li>
</ul>

<h2>Usage</h2>
<h3>Deploying the Contract</h3>
<ol>
    <li>Open the Remix IDE or any other Solidity-compatible IDE.</li>
    <li>Copy and paste the contract code into a new Solidity file.</li>
    <li>Compile the contract using the Solidity compiler version 0.8.18.</li>
    <li>Deploy the contract to an Ethereum network (e.g., Ethereum mainnet, testnet, or local blockchain).</li>
</ol>
<h2>Requirements</h2>
<ul>
    <li>Solidity <code>^0.8.18</code></li>
    <li>Ethereum development environment (such as Truffle or Hardhat)</li>
</ul>

<h2>Authors</h2>

Nitil Jakhar
<br>nitiljakhar1904jacs@gmail.com</br>
