# SampleRealEstateTokenizationCosmos
An example Rust code to tokenize a real estate property in Cosmos.
This code defines a TokenizeRealEstateMsg struct that represents the message sent to the contract to tokenize a real estate property. It also defines a RealEstateToken struct that represents the actual tokenized real estate. The tokenize_real_estate function takes in the message and creates a new RealEstateToken, then stores it in the contract's storage using the sender's address as the key. If the real estate has already been tokenized, the function returns an error.

The function returns a TokenizeRealEstateResponse struct that contains the newly created RealEstateToken. The function also adds some attributes to the response that can be used to track the transaction, such as the owner, name, description, and price of the tokenized real estate.
