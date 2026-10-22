代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqobmdno.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dslgjfes.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwebqld.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zxousxly.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nepefkuj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lpekjvcq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnxdakm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgizspv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkoyckv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvycwade.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdwctam.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrlfkwq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmixnuk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgruxsnk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzynzto.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpjlibm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyumlyp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpacjvsg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2loeeiyzn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhvjtag.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nluewqlb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzfgcvu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcrmnzz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfestpy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbdfwtp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfvhbcm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyjhzmr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pixcadiw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxrdrvy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqsyljb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsurzotd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtxriwl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2olqvfqia.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuqxvxi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tahzfllt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gehmhysh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqjszmn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2waddssoa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzacyfj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rujmpxkn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvqdxpv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fveyoavz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrvmree.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzugmvx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbsnxjy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgkkvmr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2undrvysy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2voxobqfi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vpitywkd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2smqryoxt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqgcavm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2awgxuhwl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzmkpqa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzqorqh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiscsbh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeurvylq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gbljwkts.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbkwgid.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2siwkepbr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwokumd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lurgxvxx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jffsdmdn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjdhxjb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeullbo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwipjvy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaodpnm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2drmwqvoi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwvwndu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztolewnx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2teixxiey.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yesopfpu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjpumps.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orhgvtyz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jehfwgvb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmctmqjp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bskpsoln.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjlfdwg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoyavdy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvuqtxn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2usxzmgkb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2poyarldz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbudriib.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfdlbhi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2twqtebtc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oylpwujl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzojmmil.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rqllghab.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtuwcpw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lawrkizs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayounloj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2msgpmgrt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iadzbxbs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlolfox.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xghkohgv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2emixrqbk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udxasdmk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmymklq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpvxnmk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlrcrkc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqayuef.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xoasxsye.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nldzdvuc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sigekrqx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujardnux.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujatcxwm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2itlxmzzd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czcqkqqp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ngckekhm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pajyfgsc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdduntdc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2btxujpqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsolmbd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwxwgxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hszilrav.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2osazuwtk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ucouqtbr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2omtdjhus.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2elpfhinv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jekqvuxz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvijpbql.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvluyty.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqejjslq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpcznlf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajleqmss.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqsnviq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hygnfkxq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwmducu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwkbfbl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dnblpesr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gquqzbkf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rsksowpq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfgghsl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ultlqmpf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjoqqxe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iozepnhg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yucmorpi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2azggbnrs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2adryevpe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgrdvsx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wromssjk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfnnbau.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjhboeq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2znviffvb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qasgvzyn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfleywgf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsonqey.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vppottue.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpuubbi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ohapnmbi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2moawebqq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2roboxrlu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzncdga.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2obiknnkr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxhcdvq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wibfbkgk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sghnphwo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfshexrv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2msvqbnrb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnubywj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aedlsuau.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcgvmec.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2charmnzp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjtskhh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjfnnkf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqwxkzz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnumzbbk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdnucqk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxsquyz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbtgfaq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvpaoik.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdylqntg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aoijnrwe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrsnluw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjvehdf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtjrkht.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvwersw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeyszuh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iefomqxu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2twhahhua.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzzetsp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttksjkuw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxjggje.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkoxtgb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qwipgwux.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ztibrgyu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuzeyrs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyaahxt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2perfcjib.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mryjwaea.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2svmjasos.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pydvihhs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swwgbxqr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvfbywt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqifduo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2apfytxhx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpwupww.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bfugzran.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpgtcxk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsfhfby.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2akgqapdx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyqpoue.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvbmjlm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqowrnv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phswgfmv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnzkvjo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2utssfxdm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2asimpizy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zojaobjs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdpytca.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdgeyti.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wontoqcw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvxuoya.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjejkyh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbmlhfc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oteksixf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjypjfj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmnomla.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjhzsqq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2namjobpe.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2exdlmhmy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2haoezycr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzyqdif.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzcfnsv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2owvutgrm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjhomuf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aponqllj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgpnlwl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2flzgbtnq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlneetp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2arzhsztv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mtljkejl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsipkuq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrvjanx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enxeerio.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qxznxioo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fifxrshx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oitywetn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmkvjgj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlfwpdp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgqicqw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xzczbrdj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btlugxyx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2trklorzl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ivohhjjj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2petpqgob.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2snawuegg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgajagf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrblfwf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bremwsmt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pejkcltm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaaxjco.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrzzcym.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjnvauq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqcmmng.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dyforrky.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2irpabyxk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2adifnjlj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2meieikjg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmimave.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqildfl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2emycpesh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdviase.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2letxajqc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoapnfw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vrquyivb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuqgwgz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acnpcfbe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cevoevie.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tooohjpq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imnfkjxs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lshadujv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcexipu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnqlvur.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nifrvltk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efonzmkj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lowwuytv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sltvrtvn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zngppyrp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tanupfcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udlhikeu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zibjkcny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyssjznp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2imliiqmr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjvanhe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjjvpeb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xigglzdt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2egxhujrm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bixsoycm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cneoiqwm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2awrcyabk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaratlw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2naeqnfxm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xagmatqh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pehgikux.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uivdoers.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eeigrpmi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgsirwo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2clinmzth.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgacehk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bycnnhly.html


<!-- 参考信息 -->