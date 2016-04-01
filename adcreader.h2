#ifndef ADCREADER
#define ADCREADER

#include <QThread>
 
class ADCreader : public QThread
{
public:
	ADCreader();
	void quit();
	void run();
	int get_samples();
	bool read_enable();
	
	int ret;
	int fd;
	int sysfs_fd;
	bool running; 
	int no_tty;
	int inp;
	int outp;
	int buff[100];


};

#endif
