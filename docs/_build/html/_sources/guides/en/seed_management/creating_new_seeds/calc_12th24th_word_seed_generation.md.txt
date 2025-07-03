# Calc 12th/24th Word Seed Generation

This seed creation method allows you to generate a cryptographically secure seed phrase by entering 11 words (for 12-word seed) or 23 words (for 24-word seed) manually, then calculating the final word with proper checksum validation. The final word (12th or 24th) incorporates additional entropy and ensures the seed phrase meets BIP39 standards.

## Complete Process with All Screenshots

1. **Navigate**: Main Menu → **Tools** → **"Calc 12th/24th word"**

![Tools menu selection](images/ToolsOptionSelectView_sm_cn_en.png){w=250px align=center}

![Dice method selection](images/SeedGenerateCalcMethodView_sm_cn_en.png){w=250px align=center}

2. **Choose Length**: Select **12 words** or **24 words**

![Final word calculation seed length](images/SeedMnemonicLengthCalcView_sm_cn_en.png){w=250px align=center}

3. **Enter Existing Words**: Use the on-screen keyboard with intelligent word suggestions:
   - **Key A**: Move up in the suggestions list
   - **Key C**: Move down in the suggestions list  
   - **Key B**: Select the highlighted suggested word

![On-screen keyboard with word suggestions](images/WordEntry_sm_cn_en.png){w=250px align=center}

![Entering existing seed words](images/ToolsCalcFinalWordEnterSeedView_sm_cn_en.png){w=250px align=center}

## Entropy Methods for Final Word Calculation

The system provides three different entropy sources to calculate the final word, ensuring cryptographic security:

![Final seed word](images/ToolsCalcFinalWordFinalizePromptView_sm_cn_en.png){w=250px align=center}

**🪙 Coin Flip Entropy Method**

- Flip a physical coin exactly 7 times
- For each flip, select **1 for Heads** or **0 for Tails** by pressing the **Joystick**
- This method provides 7 bits of entropy for the final word calculation

![Coin flip entropy interface](images/ToolsCalcFinalWordCoinFlipsView_sm_cn_en.png){w=250px align=center}

- The system displays your binary string and calculates the checksum

![Coin flip result display](images/ToolsCalcFinalWordCoinFlipResultView_sm_cn_en.png){w=250px align=center}

**📝 Word Selection Entropy Method**

- Choose any word from the BIP39 wordlist as your entropy source
- The selected word provides the entropy bits needed for final word calculation

![Word selection entropy method](images/ToolsCalcFinalWordEntropyView_sm_cn_en.png){w=250px align=center}

![Word selection entropy method](images/ToolsCalcFinalWordEntropyResultView_sm_cn_en.png){w=250px align=center}

**🔢 Finalize with Zeros Method**

- Uses a simple 7-bit string of zeros plus the calculated 4-bit checksum
- This is the simplest method but still produces a valid final word

![Zeros method selection](images/ToolsCalcFinalWordZerosMethodView_sm_cn_en.png){w=250px align=center}

## Final Word Display and Completion

**Final Word Display**

- Shows the calculated final word with full derivation details
- Displays the entropy source used and checksum calculation

![Final word calculation screen](images/ToolsCalcFinalWordShowFinalWordView_sm_cn_en.png){w=250px align=center}

**Completion Screen**

- Review the complete seed phrase with the calculated final word
- Your seed is now ready for backup and use

![Final word calculation completion](images/ToolsCalcFinalWordDoneView_sm_cn_en.png){w=250px align=center}

> **📚 Technical Note**: The final word in any BIP39 seed contains both entropy bits and checksum bits. The checksum ensures the seed phrase is mathematically valid and helps detect transcription errors.
