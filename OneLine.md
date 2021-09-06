The single line Matlab codes applied to time series T with period length L includes:   
T, -T, abs(T), -abs(T), diff(T), -diff(T), abs(diff(T)), -abs(diff(T)),  
movmean(T,w), -movmean(T,w), movstd(T,w), -movstd(T,w), movmax(T,w), -movmax(T,w), movmin(T,w), -movmin(T,w), where w is search from [max(2, L-100), max(2, L-50), L, L+50, L+100].  
The auc result of 1Line in table Ⅵ is obtained by running all single line codes above and then picking the best result.
