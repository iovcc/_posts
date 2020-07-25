---
title: "Lançando Layout e Site"
categories:
  - Welcome
tags:
  - welcome
  - site
  - layout
  - jekyll
  - markup
excerpt: Este post é apenas um teste e um exemplo de como deve ser um post básico.
---

É possível usar todos os recursos do tema e outros que poderão ser inseridos conforme demanda dos participantes e autores do site.

```Verilog
// simulation part
module sim;

        reg RST=1;
        reg SET=0;
        reg D=1'bx; // dont care, to track the final state
        reg CLK=0;
        reg RUN=1;

        initial while(RUN) #1 CLK =!CLK;

        initial 
        begin
                #10 RST = 0;
                #10 SET = 1;
                #10 SET = 0;
                #10 RUN = 0;
        end

        wire Q;
        
        lalala lalala0(CLK,RST,SET,D,Q);

endmodule
```


