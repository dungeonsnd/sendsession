sendsession

Sending socket fd and additional data between linux processes.
This project is almost stable, and the author has already used it in a production environment. It has no wholesale reform of the project.

用于在linux进程之间发送套接字会话,即批量发送fd及其会话数据. 目前仅支持linux平台,未来可支持较多unix平台. 对于windows平台,作者不太清楚是否拥有类似的技术.

项目目前基本稳定, 作者已经将其用于某生产环境且运行良好. 暂无大规模修改计划。


/*
 * Copyright 2014, Jeffery Qiu. All rights reserved.
 *
 * Licensed under the GNU LESSER GENERAL PUBLIC LICENSE(the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *   http://www.gnu.org/licenses/lgpl.html
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

//// Author: Jeffery Qiu (dungeonsnd at gmail dot com)
////
