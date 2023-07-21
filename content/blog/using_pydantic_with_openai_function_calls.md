---
title: "Using_pydantic_with_openai_function_calls"
date: 2023-07-22T00:09:55+02:00
draft: true
---

# Draft
    
```python
from pydantic import BaseModel, Field
from typing import List, Optional, Union, Dict, Any, Literal, Tuple

class NPC(BaseModel):
    phisical_description: Field(
        ...,
        description="A description of the NPC's phisical appearance",
    )
```

end
