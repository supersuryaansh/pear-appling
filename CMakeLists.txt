cmake_minimum_required(VERSION 3.25)

find_package(cmake-pear REQUIRED PATHS node_modules/cmake-pear)

project(pear_appling C)

add_pear_appling(
  pear_appling
  KEY "m9og4cqyqmq7bn47b1fchj79bxcte47ronmdgnhjsamfnodapj3o"
  NAME "Holesail"
  VERSION 1.0.0
  AUTHOR "supersu"
  DESCRIPTION "P2P Network tunneling"
)
