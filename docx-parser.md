# docx parser (client-only, no libs)
- .txt: FileReader.readAsText, split on blank lines
- .docx: ArrayBuffer -> find word/document.xml in zip -> DecompressionStream('deflate-raw') -> string split on '<w:p' for paras and '<w:t' for text (avoid complex regex)
- Preview 300 chars + word count before Import
- On fail: "Could not parse .docx, Save As .txt and retry"
