# jobhunt

A personal job-search agent. It reads public ATS APIs every morning, throws away
the ~99% that don't fit you, scores what's left against your resume, drafts an
application kit for the best few, and emails you a digest.

**It never submits an application.** It finds, filters, ranks and drafts. You
read the digest, edit the cover note, and press submit yourself.

```
2000 postings  →  40 candidates  →  5 in your inbox
   fetch          regex/location      LLM screen
                  /freshness gate     + draft
                  (free, no LLM)
```

