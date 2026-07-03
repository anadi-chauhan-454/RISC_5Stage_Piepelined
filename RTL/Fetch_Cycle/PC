module pc#(parameter int WIDTH=32 )(
input logic clk,
input logic rst_n,
input logic [WIDTH-1:0] pc_next,
output  logic [WIDTH-1:0] pc
);

always_ff @(posedge clk or negedge rst_n)
begin
if(!rst_n) begin
pc <= '0;
end
else begin
pc <= pc_next;
end
end

endmodule
