r = 5; % reward per step
y = 0.8; % discount rate
steps = 1000; % time steps

G = NaN(steps,1); % prep

for t = 1:steps
    if t>1
        G(t) = r + G(t-1)*y;
    else
        G(1) = r;
    end
end

plot(G);
xlabel('Timesteps');
title('Gt');
