proj1
=====

proj1 for EE652
<<<<<<< HEAD

Please put this folder under contiki/examples/ 

/***************************************
 * function to change TX power level
 ***************************************/

core/dev/cc2420.h
/**
 * \param power Between 1 and 31.
 */
void cc2420_set_txpower(uint8_t power);
int cc2420_get_txpower(void);
#define CC2420_TXPOWER_MAX  31
#define CC2420_TXPOWER_MIN   0

/****************************************
 * function to read RSSI
 ****************************************/
core/dev/cc2420.h
extern signed char cc2420_last_rssi;
 
http://sourceforge.net/p/contiki/mailman/contiki-developers/thread/AD05DBDAC33146FABCDC58C57F310598@koko/
=======
>>>>>>> refs/remotes/origin/master
