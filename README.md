# JAVASCRIPT

```javascript


// Create a variable to hold your NFT's
let nftCollection = [];

// This function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT(name, eyeColor, shirtType, bling) {
  const nft = {
    name,
    eyeColor,
    shirtType,
    bling
  };
  nftCollection.push(nft);
}

// Create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs() {
  nftCollection.forEach((nft) => {
    console.log(Name: ${nft.name});
    console.log(Eye Color: ${nft.eyeColor});
    console.log(Shirt Type: ${nft.shirtType});
    console.log(Bling: ${nft.bling});
    console.log('---'); // separator
  });
}

// Print the total number of NFTs we have minted to the console
function getTotalSupply() {
  console.log(Total NFTs: ${nftCollection.length});
}

// Call your functions below this line
mintNFT('Nicole', 'Black', 'T-Shirt', 'Gold');
mintNFT('Prince', 'Green', 'Hoodie', 'Silver');
mintNFT('Yfriel', 'Brown', 'Jacket', 'Diamond');
mintNFT('Barbie', 'Pink', 'Dress', 'Gold');

listNFTs();
getTotalSupply();

```
