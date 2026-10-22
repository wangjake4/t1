代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sygportf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzmvwue.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bugggjxe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmomcav.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mufzgelp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tevxpmdh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcaxooh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wzckjxbm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iqexrrwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvipwdt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhqlsfe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqradkwo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iicaornd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhdqtik.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jomhgqfv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2chsoylvr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcociyu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyfsxgw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dssothxf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtcpfdw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfrotmx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2psehqdln.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvkxtfy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtixhbe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtxnzdr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bxblhlqd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjzwfmg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjktjsdd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnddjbr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlxhvxf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtdvylq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cufkpzzj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vslpmklf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2faxeootk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2njlkhzzj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2evxlkanj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2scdskmsy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zekwdzng.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eesbtqwg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrtilip.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcikicqm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hghbwigp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hegkjvns.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bifcfztp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdigvvb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxqbwov.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzcsgab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2drjzpchx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wyudvimp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgnknbj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zknbmwbp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2opdpzivl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzgryab.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hjajzmrl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2soeccjrx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2maudiqfg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lnecjjzc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryerynhv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyhcijw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgxnrwq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvfxxbw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnaimqi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2abchslsb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgbpwkj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdqmuoh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkwvedu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wbutfune.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnndfrx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2milnrgoa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrfnbmw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxssxqt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2auqvirpb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okfoxkus.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxesntx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbidbab.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sumhynst.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqmajyl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqlffxx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kygatazx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lturwlqw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dajilzxy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2siugwtex.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqrfgny.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkrkxvh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjygvxx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnzfjdt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvycfjv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2axpnzrwm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2odjpbqrk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buyrioju.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmjykij.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkkvtpx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gybfjamj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbtpftm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xonedikp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twawmzdt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wpapcjup.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfwjodr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yjocrjxh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpghrupn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cawfxvse.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnzfthe.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzgtazf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2swgwfiwc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkwxgfg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxtsijt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnparmv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uukwfczh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxdqhlq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyxktpc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2shunwgqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jymkaank.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqimtvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjblpork.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnaurcj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hyashptw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2igymxvpa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgbcqzs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jocirxjc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxtuceh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2skampaxi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqawpps.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2whynsoac.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2elwjkixc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjvghgr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmhqenb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clupznwz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ertfjzcr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2egxacizh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiwzonv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yddcrkwy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2djugounm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vaouyzda.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrpytoi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqjksel.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2teegcntc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jegeklcw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxlsubj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcgoija.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2azfrjawp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fkozazms.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnimlhi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmffolc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2amjhacfa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhwchxg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsxjdob.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsietie.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iazeqbyv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgeotur.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvznuek.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isyaompd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkcxifa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgipahf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dedoraqj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lxijomkb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkkpwtv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzhzkjv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nymezrmq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgftgtxj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqekvum.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnhtxjd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcwnnln.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vejvrjnh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjipljew.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bufdmufw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2drztttjl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvpsyrc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2afelhuuv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqcwndd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2umqopiqf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzfrvab.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxxgvwx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcxjrqq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyugkva.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdgpcfs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdnurse.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khuudnnp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdokrvd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzpgxor.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mllluoku.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iucuulhs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qzphfusr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlpkavp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2caihayhz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iaczvaet.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfiovnc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2asqevuhn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqsvtlk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zinnxpag.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxfzdck.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgjkwwv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iiysugat.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2msyaozwk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwydury.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oonulvlb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkjncxq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyvvgwp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oqywcmcs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2crmagywq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzlbfwe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmsyrzf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfstwlh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwzrhde.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zeelmefo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xdosjwxv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2clwmkbpe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qumrocch.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yxftzclw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wndwbpfp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2muqioblk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkhxpmt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkjthdj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdjidty.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gplakspi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfvkoxh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqakosyy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvqsvxz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mptnhkkw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuvvzpc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gruvyedd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yjizcasu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2otcnbklq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiyfwbb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sampyyyr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbupqwp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxjkizp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdzkkpp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkedhsi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkxwrye.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2srqgieav.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hlharvrk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbrutyd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hivipudg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2heiefili.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzmvlob.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2brekyprg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlzbxvy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2knqvngmr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaigjwj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdmczls.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmgvxlt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnpqrej.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uogxotdw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgoifyc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsqlnxr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmupdip.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvzhoup.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzqfuxf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtdwlat.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zpprrnjh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsjpupj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbmbhdc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdtcvkm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vhppjpyb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwpkngh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2aumhtppp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmtxxus.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvksiqt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnjxyik.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyqwxun.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvgerqc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxvlfjz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkywqaqm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bxebwgml.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2stdbtqgd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwgiazt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsngdqco.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgzhupj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsqmwao.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiakovr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrrjgth.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaxlijl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qztvzvum.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfgclmx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bydifadb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqmnrcm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsbavyu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2psfejoye.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzcyklq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjhfvds.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tewgzsoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsjoest.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dzocyuij.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuvovfl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpneaaz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jjldpmwb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcojamc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyxocha.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovawhspl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aimwgwin.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbjskon.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzcbdmi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2upxewyty.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxzibpj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqqnilx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mdecbxto.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtddvif.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eovbuqte.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqlaabb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bhooborf.html


<!-- 参考信息 -->