# assn5_help
http://www.cs.ecu.edu/karl/2530/fall18/Assn/Assn5/assn5.html




#include <cstdio>
using namespace std;

struct Edge
{
	int v1;
	int v2;
	int weight;
	
	Egde()
	{
		v1=0;
		v2=0;
		weight=0;
	}
};

const int maxSizeE = 100;

struct Graph
{
	int numV;
	int numE;
	int arrayE[maxSizeE];
	int physicalSize;
	
	Graph(int nv)
	{
		numV = nv;
		numE = 0;
		arrayE[maxSizeE];
		
void insertEdge(int u, int v, int w, Graph*g)
{
	int k= g->numE;
	
	g->arrayE[k].u = u;
	g->arrayE[k].v = v;
	g->arrayE[k].w = w;
	g->numE++;
}

void readGraph(Graph* p)
{

}

int main()
{
  return 0;
}
