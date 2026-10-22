代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxvgjin.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdxbjka.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzinznbx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqjjzep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iugcuocl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfmghrq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2umgiybsp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xonienma.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lutpexso.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjwdaay.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nvijnark.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2humfrpen.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdkaljv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsfhaxp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rstrnhzc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2krklgbre.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjismxe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bviqaxgm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrqyqjd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pozuhwfk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zoelplkj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfegvsb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnphlhe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sddwegvm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhhuacn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmcered.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlnhfyl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnonzwj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epdwofhm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkotutt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2igdrisci.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmuppxc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkhdvca.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2arxheeac.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwhzsjn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuuksjm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2muyllmwr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2utcpwltc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgpsqpi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xogatxuj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhjdgza.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvqsqol.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vohjrudd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2oemcscyk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkwelvx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhkstfs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xssflcnq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdckqycf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kywtmqcw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdegrich.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzojnab.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruewhlyf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiszvgp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lylvxiuc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqzzaoz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbhpomn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiyilxu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2stccshzt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2saudwfjf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkngtia.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wugjmary.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbleohi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xixdbzuh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvwehif.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2avwixvph.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2amipxyou.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqsoclt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2krablmpp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyznlgho.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2adxvcups.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xcluhpys.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nvamtufp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnegzjtf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2morjjlun.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zrykghxo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jjinsjnv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uykhrhhw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2imypozpz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzpbbqe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2khbmgcse.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzkcfmz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jopwkwyk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtdhmln.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wljhtuiv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvhnabw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxdkycs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2egbpgkmo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hfadlgmg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgnnsel.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hosdiwco.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xszumhva.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmpdznk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuocthj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nywavcfb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2voalwafw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axqdysyj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2efcbacvt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnshcitu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyqkjwm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqkhuim.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2prhvbwgb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyswjhf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wurxtvzp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjogdhq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmuzzel.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqlccdg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxgxqqi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrpzbiz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bxophjai.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ablmwzng.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnklvdmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtijspih.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtkiblw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geflvosl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmgunmd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rusyvwvu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dzakllrd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qufkagrk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjckbki.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anqqwseh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwaiknj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvskavq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsecbit.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwnrymp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2znxkxzcf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2arsaicdt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnboyni.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njdqmifx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2furhqayv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hproxola.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vucbclxa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2keaweqjm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyzsjlv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2obhnpzht.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ttprptrd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vaikbatq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfgrzyw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaiqulh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fimgzthk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdywfoza.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfvqput.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orpsiytq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcptqll.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2htublwer.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhhxdgi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyunqib.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmdrycp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obantpws.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yamgmsip.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2benvtqsw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcnfbtf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uksnreuq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuzkjgy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeggipv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fabwrlrk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgjzzwv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wntwfmgv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbhvcal.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfhjldh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsiufzu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfxdhyg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxtlpox.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgnyylt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlihqqpr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvgjwrt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvpjpob.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrmdxdj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxlphpg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umeymmzd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qczootbu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zodlvlae.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2foscedwj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcazqzwo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zcunibqv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrvgcjn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdudvjcf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uisojjxi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpypryzb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfakath.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skriltig.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yngaaupo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2khmygdyo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjecyje.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2acqgyayi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2izrcyuye.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2utapzixg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwwcwvc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pkilkngr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkpdchy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aglicpkb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmkdgdy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqjhczl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinyaplt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhheqyb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjwrxaq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxsfqci.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2igjxdpgx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjkrmbk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnllcni.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rioghjpn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqburdc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hlloofov.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxfsufp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrydvghx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oiffudnf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpnxwep.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2apeuzsod.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkhqlak.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqwerep.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tkevazrn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzjxwtm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeehchf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrhgmwn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2flghbubv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdirioui.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdqrmbk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkwishi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eihhdfgh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zneasydq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2keprhhwk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ekowendy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyiwdgq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbosjil.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2grtkfvsv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2luatmpaj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqycflh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbzpzpf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkwnmyv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2haoojsyk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2avkzxrgz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mibrmhoo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsnwzer.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqdflnm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tppkrtyv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qujavzbh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeokhor.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wqznemaw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgldwddt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sydrfuys.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ppluejzw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhkijie.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiovypqu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2iofutcfm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2anwfrqjb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zicjlwym.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbrrssw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbbdfya.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpksmlk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpnoegb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rcslpvra.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tytmmxle.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2aspgafcm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2asqmwjuq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrngjtud.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enlezlqt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yejhbolv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2trarhrbr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cifomzqp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcvezrw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dthkrhec.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlewyqpl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpdbkef.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bcylruzf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqhdkzu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmwjcgy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxjyxlj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mulubytz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrayjas.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqplxou.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwidzyj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2osccmcht.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2akalgmwj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2adogetlg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ctflihzs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwogsdp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnzoglp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eazocmps.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkwbfxi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwzjoqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkwpezh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lezinyjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzzztwr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpxtcms.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yypmqild.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwytafxl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tesbmouj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjsxhzr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gispondx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2chkdugvm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkkypjc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yisfjznz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2voanirfc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2azleoaap.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyjdfbx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cijnoaol.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqvfylt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhylcly.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rblkyhte.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrdxttu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaxyhlb.html


<!-- 参考信息 -->