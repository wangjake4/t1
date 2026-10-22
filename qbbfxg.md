代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2efsqbyyb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iznjiime.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjoueqa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbxbafa.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2afltkhfc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsaoqes.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqqvdku.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqfpjbb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrorvrv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbchzyh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoadhjj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvrzgwv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uswsgzif.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjalflxb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpurppq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmczaqpk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zywxmozl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2geqkterr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhxqznt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zdubgwup.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhjstgi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfmkfsz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvhlohs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hncsfgyl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fralbelf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnwbwrs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2frvavosh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzadued.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbccvke.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wexoxogf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrpgfwx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2chvqtfwt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdttsyij.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2byeawsuc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikladwdw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2isktkcoa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvjvhnp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhzhbqv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2puqrdykf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vglmdkxm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhwnxyl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2isjqousc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iagcbkkm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuigjtb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdqxuva.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwelilj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2auqnmxft.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2naanyzux.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xumamqrj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkihptu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnxuefr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vebnqoup.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmcwpko.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiekyft.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2idfyjmca.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbkypuz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfgndzp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqzqbja.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbezfjn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xiftgeaz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feepqntk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2prfjacvy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdsblyl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bumaefjl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lryxvieh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2daoruuba.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xzurlitz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qklmbajm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2womvtodq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfldcul.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcmkedi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgtteyf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2glysytvc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2szqvszcz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxawwre.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hitcnoes.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxkinau.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmyviyj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kierhrbn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjookhs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxkldqc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrkdpju.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpcyrtz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2harasvqy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ldirhqru.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yndkamva.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iajcnkhm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkpznlu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhhghuh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjklnqox.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gkonlxqb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtjkdzp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxefjif.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2noxpjrzo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncocfcim.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmcpstd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvoyqlq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wctynwcj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbubqxyl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kopuzltu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2clcwbvsk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wddoizzs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqliopng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svyvdqnk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2piovwspx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktixjjhg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gvipiwto.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkckorr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hauznbpe.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdmhmwa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgksqoe.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2scytjdom.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2urjhtcup.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcoyxjx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpauxzw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmocsqku.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhheiej.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2appzmmik.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvoqggf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbeptxs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzlbwii.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxjtfsu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpowvvi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyugvex.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2enfloiwl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2otgieqpv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtaxwrq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2inpjzbgc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjsqqoj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzxiqzx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfrnktb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgykvzgt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wbypbkuk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyychrmk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnmcxmv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yahwhefk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ywupxhjx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kokhjazm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ogirmmcc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkylaffh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeyjomt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsiapjw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hotxxcxi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cgekukkd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaiuiyl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbizkox.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zcilmftw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dukzjzmk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqezuet.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qojvzcuc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apwzuvtw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2msmizzwl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2swlxyynz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmqwikq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiimtwrs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2heuwnrjg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsszbsh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhejaivv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kznpqybd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sathjvbm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcukbdn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqxstfe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uscepvgc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkvmsyx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vopwlods.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqhewgp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yfroqpeg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbfnfyd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsdibhl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rstpgrwp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzfvtbh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhgjmis.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotftghg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2anasmqva.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvzczke.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kheendzh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdwghnl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgesjzn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcnsyao.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbdcxyo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuuqnna.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2znkfczek.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkdzkvm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdfqtmg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evthgtsf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2iycmnniw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxrtjmk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qddttcka.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lttpwfkn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqaqdon.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eukgudbt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hiypkkxt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmqizgr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qfunpryf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrbruko.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xaofagzl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjghnjm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2snkbtkut.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cusmecwk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mxntzolx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwjlnhb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzwrxug.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcmrzsv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzesnscz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2duozjedg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdridkpq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2veghodxs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyycxotv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeiuvfi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zhphxzax.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afrwddtb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fhklbuof.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwvsvtp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnoqusp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxjxnxj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxvqxva.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2amrroyrr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmprfzhk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkskmfzx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtovkis.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhwplvj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyaneom.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2brllqyzw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ezspobfz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdyehth.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmlrben.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtsfemu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjopcts.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmghytl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xiceyjwv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ngancfwo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ssouyucn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmxeqnk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mktdfhfa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbcdysm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2domwmveu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcpmvhi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2okdtqntj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uppysqxa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrkfbvb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hmixdtlt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2scbdcvfz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlzoeps.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2natgcscn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtlmaae.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdyxyor.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkzbhbr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoyzfbi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfmhmmt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eocjxupk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeocsvj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyxvfec.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrpnjzk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiotjzx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bsarmtly.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzrckty.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoyxikp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmsomhd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuhcjjz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdtfbbc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zddezulm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqvjxax.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqwrewn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ctknqrjj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yuosvcmz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqkpovh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuegxvj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gywneacv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcondawx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fblrlpze.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qidytdxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idbvaafj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nicfqdyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iebylbak.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yafkxkww.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvmavrn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlwwtmj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2egvgajdd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zekfivjy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjxnlih.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2visjejiv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cajzplni.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2takbziaq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2takwmaok.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbbdwbe.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgghlcqs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkkkfeu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iitrfrls.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sazrcjpd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwlgctr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzohdziu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkxhvet.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vfejeufj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqgfuyd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxqdepf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhejfao.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwyaclj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2huructgx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oypisbzs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igkrjiwo.html


<!-- 参考信息 -->