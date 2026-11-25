# Architecture

Gmail inbox -> Gmail client -> PDF reader / OCR -> AI extractor -> validator -> dedupe -> CSV writer.

Documents that fail validation or are not invoices or purchase orders go to the review queue. Gmail changes happen only after the result is safely recorded.
