
===============

CREATE TABLE IF NOT EXISTS `employee` (
  `id_employee` int(3) unsigned NOT NULL AUTO_INCREMENT,
  `emp_name` varchar(10) DEFAULT NULL,
  `designation` varchar(9) DEFAULT NULL,
  `date_joined` date DEFAULT NULL,
  `salary` decimal(7,2) DEFAULT NULL,
  `id_dept` int(2) DEFAULT NULL,
  PRIMARY KEY (`id_employee`)
) ENGINE=InnoDB  DEFAULT CHARSET=utf8 AUTO_INCREMENT=11 ;
 
--
-- ინფორმაციის განახლება ცხრილში `employee`
--
 
INSERT INTO `employee` (`id_employee`, `emp_name`, `designation`, `date_joined`, `salary`, `id_dept`) VALUES
(1, 'SMITH', 'CLERK', '2010-12-17', 2500.00, 20),
(2, 'ALLEN', 'SALESMAN', '2005-02-20', 3500.00, 30),
(3, 'WARD', 'SALESMAN', '2009-02-22', 3550.00, 30),
(4, 'JONES', 'MANAGER', '2010-04-02', 3975.00, 20),
(5, 'MARTIN', 'SALESMAN', '2011-09-28', 3300.00, 30),
(6, 'BLAKE', 'MANAGER', '2008-05-01', 3800.00, 30),
(7, 'CLARK', 'MANAGER', '2008-06-09', 3850.00, 10),
(8, 'TURNER', 'SALESMAN', '2007-09-08', 3600.00, 30),
(9, 'ADAMS', 'CLERK', '2011-01-12', 2400.00, 20),
(10, 'JAMES', 'CLERK', '2009-12-03', 2600.00, 30);
