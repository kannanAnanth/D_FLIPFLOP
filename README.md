# D_FLIPFLOP
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/4f3e1d9d-e0c3-464e-b0e4-e47946c813bd)
# Truth Table
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/42d38f79-9cc3-4b09-a46f-e0c1241dee57)
# Program
```
module dff(d,clk,rst,Q);
input d,clk,rst;
output reg Q;
always @(posedge clk)
begin
if(rst==1)
Q=1'b0;
else
Q=d;
end
endmodule
```
# Output
![WhatsApp Image 2024-05-12 at 18 10 41_c02cfe39](https://github.com/kannanAnanth/D_FLIPFLOP/assets/160721190/70b12e4c-c743-459f-b326-712a7f880d03)

# Result
DFlip Flop Output has verified
