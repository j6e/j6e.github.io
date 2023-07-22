---
title: "Using Pydantic with OpenAI function calls"
date: 2023-07-22T00:09:55+02:00
toc: false
draft: true
tags: ['openai', 'pydantic', 'llm']
---

## Draft

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
    
```python
from pydantic import BaseModel, Field
from typing import List, Optional, Union, Dict, Any, Literal, Tuple

class NPC(BaseModel):
    phisical_description: Field(
        ...,
        description="A description of the NPC's phisical appearance",
    )
```

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

end
