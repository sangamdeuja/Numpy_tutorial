{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Difference in normalization constant in Sample and Population"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "We use sample statistics to infer the population statistics. While sampling there is always the bias introduced because most of the time the sampling mean is away from population mean. So, while calculating variance, the varaince of population is always greater than the sample variance.In other word the sample variance is always underestimated. In order to compensate that, n-1 normalization is used for sample variance correction also known as Bessel's correction."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Review of Covariance Function"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Covariance is the measure of the directional relatioship between the two variables. Covariance of two variables x,y is calculated by the formula: Cov(x,y) = SUM [(xi - xm) * (yi - ym)] / (n - 1)\n",
    "\n",
    "OR\n",
    "\n",
    "Covariance is calcualted by multipling the standard deviation of both to the the correaltion matrix of these two variables."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.3"
  },
  "toc": {
   "base_numbering": 1,
   "nav_menu": {},
   "number_sections": true,
   "sideBar": true,
   "skip_h1_title": false,
   "title_cell": "Table of Contents",
   "title_sidebar": "Contents",
   "toc_cell": false,
   "toc_position": {},
   "toc_section_display": true,
   "toc_window_display": false
  },
  "varInspector": {
   "cols": {
    "lenName": 16,
    "lenType": 16,
    "lenVar": 40
   },
   "kernels_config": {
    "python": {
     "delete_cmd_postfix": "",
     "delete_cmd_prefix": "del ",
     "library": "var_list.py",
     "varRefreshCmd": "print(var_dic_list())"
    },
    "r": {
     "delete_cmd_postfix": ") ",
     "delete_cmd_prefix": "rm(",
     "library": "var_list.r",
     "varRefreshCmd": "cat(var_dic_list()) "
    }
   },
   "types_to_exclude": [
    "module",
    "function",
    "builtin_function_or_method",
    "instance",
    "_Feature"
   ],
   "window_display": false
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
