代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgatzuw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2unoozipa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nibtyotj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfyxyng.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ldztnsat.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjenfda.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhcylmv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2veovbzvd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xynjybla.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbihqfqn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmfbgvd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeafiymb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfmapct.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrecacp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2glyirmaz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iijrcans.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzemmpo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuakxqnf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mgavdymt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xppdydjk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbifids.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yguhdpql.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlrtmne.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uofqcvic.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2edfyvtlo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfkxfal.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gbidpjrj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yqogrroq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrptjygr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kkekalnx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnefawho.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeedxej.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvuskrc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgufrjea.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eleyucyf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdrkaaa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2phjyknlv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nukfanlx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiymrexg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvztiql.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ontunuiu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wghechog.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2avshmwmw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuzsakl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yepdokse.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jenjghur.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcucnba.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpwpfuf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jpruigum.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwrvuvx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmjfyhx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlxrccx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kuakbajo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqmhnes.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2owmrheip.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kajwucdv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zjacnavy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiliakux.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zendhkdd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmzhfbg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwaxywo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiutbbk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpujacv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqgzncz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxclgty.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwxljom.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiepene.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mustawcb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uswrgjla.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yzesjwbi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2erawbety.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bukfidms.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awqnmvnz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2prbyadad.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lvipfvbw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnkpqie.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbpfota.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmpzuhh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayojwpcd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxxczvx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bsevmsuj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wompdfpu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuqcgfu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zplbcffh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2erhcadan.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsyujce.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtskuux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yznkoptk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqqeede.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtxixlx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sciuisiw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaomdif.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tuncixsc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnaxale.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmqfoap.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbaoigk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2iidabpuz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hultoqls.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cckyojvl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfifwctk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oxabvnvy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrvdyuv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpwxyux.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmfcohj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpfdjid.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jktunons.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akgbqniz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mettdxhj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2udhhltkh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkazvqjq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2toevejri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jddxyzoo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dygtwrrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mggvdjqs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmnhqkk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmwhtfp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnsqaji.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzmvubb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwrhdfg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhrnnsq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkmywll.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwqtidb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mligmnrp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2szvprirf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkckgxc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvuufyn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djweusjz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nopqthmh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxxnhmw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2npethmgj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqhxfri.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2efjgahar.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2voahfkhg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2clnqslsm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkrjfsn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ngolwsdp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gipuxiqc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuvhpdd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2huwcdiri.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgonfyf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfzvctu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcyfmft.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cahehygs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkdavkg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sygripxb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2auivvkut.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvakbgyh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oygkoanv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awvzxlwx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etulhuog.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2selyiwfm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tltocdld.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lplcgyni.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkmiodj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fmawttne.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eiibwvml.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuuefqs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqntwsku.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2smveervq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpugiby.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpeuqav.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iizgqkal.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ochpnxid.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2acdwyqym.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nckixyba.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zshchbbt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrsiddq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdlzxij.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkftxwbs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjkyijv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsoxgot.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2enrrgxbv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiyqnqo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvrzfdl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbewygh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqipodod.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkpksvu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cevtglgt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxtjzkk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vobggofm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmevxza.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2elcbteeu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqjxdws.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pwycpygm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhiupdn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnltqni.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtlnexu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuhflef.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ashvwwnx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dlenisuk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2osbdqtbd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fifzbhdb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqedwoe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ebseeopz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2howcmiyh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhknisi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2elyjplhl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpybokl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lstfhvgd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxmqrui.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2extdstqh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxgcbne.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrksthpo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wirxzbpo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpolebi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2abilxhjd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xymatxyq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmlsrgt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2epufgair.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwkbsob.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tqodvxbj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnpefcz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtjfzql.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyxwovb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcabxrbn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xysfybzn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yxucmznm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpjdsnf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jervfggi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2odkhrhmb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrzmohq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2aezbfxuq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnnsyjj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rshvagki.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzhfgef.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qankglsz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbworzx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxubltq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxhdvka.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nhechtoq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pylxdldx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hphuycgd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlnvztz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bugyhmog.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zkerrdhf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuylavd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxfytxy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzgntdg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaasduc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgvdfes.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtujvfq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhifvze.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wufqpzit.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsadvvw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rcweveze.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjwbipw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmghkgeo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2slodltks.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqwjkdb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxfrdvu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nrixjfnd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hluowjet.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgnfqvi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqwuolb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhcdcfu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2praeiihb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2myyyefrz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqeksll.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xuotbssz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqymhts.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiqnmnf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2izwqekxq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jphiyhfw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqffszr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfhtjun.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2unkljjzt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgomhmgf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnknyen.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlgqyyk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owklvwoy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fctedeuv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lomeppey.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpygrtu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xwggkzmt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eubeifdu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jankcycw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkwfwle.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtjrsse.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvljuch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsllzao.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hckuejod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyldarih.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmknfoa.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqwihlz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwgvpyx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyrnklh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrenpfn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2knkhjsnk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgudeko.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qcloelza.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhwssju.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmwkajv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aigeletc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpfqowp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uokeqgrq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2emxrgact.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnughnwa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zwackzuz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfphpyci.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iecfowdw.html


<!-- 参考信息 -->