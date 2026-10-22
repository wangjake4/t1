代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kujikspv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2veviivas.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dgownmxh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtprmog.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ivapiupk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kijduijr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lapcaxwv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaovuag.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pwujqobk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkuamqj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rvygiumb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qklidada.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2frormxzr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2doaaneef.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgplmqps.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpbgxoz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uycaveij.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcvfrfg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjyedet.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqxheil.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfsrpjb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmzogik.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlmmqcc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dalnkohz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfnpfhz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qoomfzzs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzjbvha.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jviumvdp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihouyzmk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jomudzwx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2etzxtkhz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2brwszbgf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlbxqat.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzcoqcp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaavpei.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nywfjlln.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzchuicw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pubefvmn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gjytiuvp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2prhbjrjd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpcdwiu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mylawymt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxqrssr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpchohb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oqipvvtn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hogkgznp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kzamibbm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iimvaerw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2opsowpuf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2oglnjhrh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzafppi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnmyvax.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrvpwvy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfwafkw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vwygjvdt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uamterze.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqonohg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oleyeito.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdoekjh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gilunxdp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjefnhvg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbjdjim.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ohawwmfz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vvskzaka.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmizephz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwoyufx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqalgun.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpreqtk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmmckrh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bzllesna.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgerxukm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gbclsdli.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2opdzmxpi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrrhqlo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsdzoqk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoejbcg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2shdgiobs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcfbdvi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmbzwew.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aontvxnu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmhasrw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2debdpcpp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqvymmj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jptwctrn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2agrsacgi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrgkivl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfngecnb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrfnxvb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oepnpyvf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgcjgob.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcvbyps.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2idzzekqt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jsevqvst.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxnmkhw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fydvfezl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2axbcalsv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkqfmhz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tadxxulq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgatlrkg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnfhlpc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cowjeuzg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmkqqxn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdbtmiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyyypvp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dinpyies.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtvbtdo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tayzmdmz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2acdoozph.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fiplbcnu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2euhiqwrp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2edwbbism.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiyojqg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lejkvbep.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvzyqqa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyjlhhn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvzcmce.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txznpqae.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpdtyvd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxopzxs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cneefvdh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vywfkzav.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2swpzpfpq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiqbrvv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdpsmef.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiicwzt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnvojsu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iebikmad.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2glogwrpk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfyoxqe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbepaqwn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgukzci.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifehfort.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2krynobqb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnblerg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkmrzcy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsilodn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyiijqw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcslazb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2duoydsbh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgmagmz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgtomkz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlchkktx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjszisc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fiearuiy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lguzmgew.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tupzfgij.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvqooyy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcnkkcv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svbcydeb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjjwhtm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuonbxzx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oncgetvg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2turfisqn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mafbfebq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rykcoypo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iacvuutf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xixtqolg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2smkhwnpz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsfrlyw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoioqba.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpolqfrn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2diaednky.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vedvwzfr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yavlpfoy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2crfapnqp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwlakoj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sevuaawh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udagqhmm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwvyhaj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dijkkgnh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrktsjjn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmmgblh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doukfgsw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvhssxu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mftkvyfh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2elmapafr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2smnzklta.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2evpwdhvg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2puhizoke.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qooijkns.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2etghxdua.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yuungfkt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vypyyzgo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpnbsdd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjdvlit.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ixewnuwb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vqehoilh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2adumaiyd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfvrxci.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2byxwomib.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdkyeno.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hicribnc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnsvysj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xelaaywq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcocssf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rutyznty.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jepghsoo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhldrvk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpibjfj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2stmbafic.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xujrwenw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2amqdtopc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyrwmdk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdqerjv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yakmrwzx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2etegyzml.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2inetguif.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qidsuofl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tycihjas.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pefbhqad.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tohpbchr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2piimvzjo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bxptezyc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2exgyakpk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zamoqgwj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuvjvcm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbqqlpn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afqemkxj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhpcuso.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mpykcfvd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnawrea.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgyvudh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxjbodm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2czwiyrbu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sipddneu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mglxarbp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2avanbzmt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rpltbtlm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdgpfzk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2emguissn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pdicbyha.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwitpca.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmmrtxe.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2olshxezu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2iszijhzo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxdshif.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmxcfyr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2laetmkwc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsawspwa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwatare.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzaknmv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhmvxpb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuahyjj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvraaquf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vgccrpam.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdsnkej.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apcfakrx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2edvnayhz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2quuotxwq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgbvqmv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rbimbdrx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeitwct.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnasdvb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdibldk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwzibob.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lmazhnsv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nrddorjo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmbadgr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2feolwniu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsmdmiy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bajhpepd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxqucmm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzqetiz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iglchrnk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2blachcym.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2huequwgn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmpjuzm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfuethx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqopfal.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xggtkvnv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tclfprds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyystiq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2acbkdhkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzabkfc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vppjnrze.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2budedsux.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eegenfxt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hwivwrgu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ropviiiw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwqfrmj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufktaqkn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgckmtu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbnfmxr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzifpro.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2buomjaxu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxotounb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgpxpcl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpdqlgt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hovkdhet.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zicioafk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2naozlvuv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yalcttbq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkfrkmm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nygrrzum.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrzqoig.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfoiltw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhytfzk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmjkinv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmaqlvx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxlaqcs.html


<!-- 参考信息 -->