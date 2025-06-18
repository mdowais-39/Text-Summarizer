# TEXT SUMMARIZER

## Test Cases Study

1. **Short simple text**:  
   Output is good — 3 sentence summary.

2. **Long complex text**:  
   Output is good — 3 sentence summary.

3. **Text with multiple perspectives**:  
   Output is good — 3 sentence summary, but can be improved.  
   The whole idea of the text is not covered properly. Summary could use better phrasing rather than copying input text.

4. **Text with list or bullet points**:  
   Not able to summarize — just returns the full input.

5. **Empty or very short input**:  
   Displays "text is too short to summarize" — as required.

6. **Text with no clear main idea**:  
   Output is as required.

7. **Text with heavy jargon or technical terms**:  
   Output can be improved.

8. **Text with non-English words or code-switching**:  
   Not able to generate a summary — returns only the English parts, unable to interpret non-English content.

9. **Very long input**:  
   Output is good.

10. **Coherence and fluency**:  
   Output is good, but needs better restructuring for clarity.

11. **Avoid hallucination**:  
   Output is as preferred — good.

12. **Handling redundant information**:  
   Output is as preferred — good.

13. **Preserving key details**:  
   Output is as preferred — good.

14. **Text with typos or grammatical errors**:  
   Not able to generate the desired output.  
   Does not restructure words as needed, simply echoes the input text.

15. **Text with special characters or formatting**:  
   Output is as preferred — good.
