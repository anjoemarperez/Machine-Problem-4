# Machine-Problem-4

h = input ('Please enter the initial height (m): ');
v = input ('Please enter the magnitude of the velocity (m/s): ');
a = input ('Please enter the angle (deg): ');
x = input ('Please enter the x-component of the acceleration: ');
y = input ('Please enter the y-component of the acceleration: ');

    
if y == 0
    error ('y-component of the acceleration or the gravity can not be equal to zero');
else
    t = 0:0.1:10
    X = v.*cosd(a).*t + x.*(t).^2./2;
    Y = v.*sind(a).*t + y.*(t).^2./2 + h;
end

tmax = (v.*sind(a))./(-y);
ymax = v.*sind(a).*tmax + (y.*(tmax).^2)./2;
total = ymax + h + 10;
plot(X,Y,'--r','linewidth',2)
ylim([0 total])
grid on;
xlabel 'x-axis'; ylabel 'y-axis';
