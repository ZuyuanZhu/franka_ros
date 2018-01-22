# CHANGELOG

## 0.2.0 - UNRELEASED

  * Added missing run-time dependencies to `franka_description` and `franka_control`
  * Added epsilon to grasp action
  * Added `m_ee`, `F_x_Cee`, `I_ee`, `m_total`, `F_x_Ctotal` and `I_total`
    to the robot state
  * Use O_T_EE_d in examples
  * Fix includes for Eigen3 in `franka_example_controllers`

## 0.1.2 - 2017-10-10

  * Fixed out-of-workspace build

## 0.1.1 - 2017-10-09

  * Integrated `franka_description` as subdirectory
  * Fixed dependencies on libfranka
  * Fixed RViz config file paths
  * Added missing `test_depend` to `franka_hw`
  * Added missing CMake install rules

## 0.1.0 - 2017-09-15

  * Initial release
