#include<iostream>
#include <cmath>


int main()

{
	double* g = new double [10];
	double* t = new double [50];
	double r1 = 0;
	double r2 = 0;
	for (int i = 0; i < 10; i++)
	{	
		std::cin >> g[i];
		r1 += g[i];
	}

	for (int i = 0; i < 50; i ++)
	{
		std:: cin >> t[i];
		r2 += t[i];
	}

	double mid_g = r1 / 10;
	double mid_t = r2 / 50;
	double* g_pog = new double [10];
	double rr = 0;

	for (int i = 0; i < 10; i ++)
	{
		g_pog[i] = 1\g[i];
		rr += g_pog[i];
	}

	double pog_prib_g = rr/10;
	
	double* t_d = new double [50];
	for (int i = 0; i < 50; i ++)
	{
		t_d[i] = t[i] - mid_t;
	}

	double* t_d2 = new double [50];
	for (int i = 0; i < 50; i ++)
	{		
		t_d2 = pow (t_d[i], 2);
	}
	 

	for (int i = 0; i < 50; i ++)
	{		
		std:: cout << t[i] << “ “ << t_d[i] << “ “ << t_d2[i] << std::endl;
	}
	
	std::cout << std::endl;
	for (int i = 0; i < 10; i ++)
	{
		std:: cout << g[i] << “ “ << g_pog[i] << std::endl;
	}

	std::cout << pog_prib_g;
	return 0;
}