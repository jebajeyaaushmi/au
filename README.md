# tb to display hello world
https://edaplayground.com/x/mzi_
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



