# tb to display hello world

class hello;
  
  function void display();
    $display("HELLO WORLD");
  endfunction
  
endclass

module top();  
  hello h;
  initial
    begin
   
  h = new();   
  h.display();
    end
  
endmodule

