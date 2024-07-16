# Extract Questions from Paper

The `extract_questions_answers.ipynb` should be run in a human-in-the-loop fashion to extract questions and answer text from an exam paper. It is **required** that all papers must be aligned before feeding through the notebook. Remove redundanct cover sheets and blank pages at the end. Only include the question and answer pages.

## TODO
1. For each paper type, run the extract question parts model call only once, it is not required to do this by paper if the papers are aligned.
2. Add on the fly costing to compute how expensive OCR is for a given page/ paper.
3. Refactor the code which text is extracted and assigned to question parts. 
4. Break the notebook into different scripts to create a workflow. Extraction of sections needs to be run once per paper type/ paper reference - make this an independent script.
5. Add Exception Handling, make functions into a library etc.