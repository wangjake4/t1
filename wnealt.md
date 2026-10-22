代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nqufvzwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2soltpulr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ryekolcw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kztqdtos.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwfvtlj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyeqmnx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2usraqjxi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aehxpghg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdcgpwx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvssgag.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeikvfk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2whyyikix.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkvgyrh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijclshx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdowhbnv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcxdwuf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkaiquh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhagqua.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pblsrsoi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bkducbxl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snpafnzd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbddcdm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2udqhulkt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2itzvmidz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2etvoriqb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvldjqkl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiveedd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2udpkjhtc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeomcom.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2znaudxdb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpquhak.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2raschzax.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arhhsnba.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuquoaa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfxhscm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaktich.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeipuib.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbhpkje.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdgxmbl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnqwdce.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2trocitfm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcrkaiv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgxdrmy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmcolym.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxiqgvx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nybxkjhe.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoohpap.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2abvkuymd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxzfavg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwbvwlq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uxebzrsn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaueetw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2phywzpen.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbzfnpk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2frsgaeyy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyqcvgz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxftfcz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcxvpxo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhamuwq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2snwncwyg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zghdumui.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2phvvkvbl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpgirpo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkxunqq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuzsleo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgtbyow.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zxorbwus.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xhainikj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbihroj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsqxkfc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2onhknuyc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgjtayn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmnhuvs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbjtbdd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bulbwwmh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jeixaasv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hmokbedy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2emjeelgh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wooityts.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhaauac.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yerwowik.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2camvzloz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwqqdsk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeknjyo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2grgtpdor.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlptnvb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbwtrcb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzhmndm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lucsfmav.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syjginjn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdlvsdh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjcigjh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfptdqc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnlraju.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkedyno.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nusowrqe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqjlxrx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nunvfvlj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llzqfnpj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oklqeeqq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaavojp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzcyrdm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwuwwif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isrocbig.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnkvoqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfpxfcx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwieewv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvionqa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2obrpccfh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuzsecc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2smecbpmf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffocpopj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvgcjed.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgzghpi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2acemfqyq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeqkcdo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jycqdmnd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnelwil.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shvazmxq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxgvhlw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgyojzk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2syfbltgw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2egdopiwa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvqpmrn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzakgne.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gukdzzdg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2venteewp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pncuffgz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jarxvzvj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2updgpfpk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdzsyij.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhhupnl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnffsah.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwccnju.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeijlpi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeiwbfc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bawmkfik.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rbscrreq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uscbboyh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjikqhqd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxbeces.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2weidfeee.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfhidri.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iphclefh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otvvgooi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxswiqg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjosbuti.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfxdfvs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vypkfhhe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmliyyut.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrocpfw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmowkyr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjakynb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxysfhn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcuirmc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tdalzufn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2osganmiy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdikdcg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phtpwylr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pexkmcgp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxihumn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgkznka.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2odvzrvcn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2djfqnebg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qabkezwc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxanpis.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcydxfu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjdphed.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ealgxjjp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzcdseo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsphquc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhkcitt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfweucgy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nnprmisw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njrkkdmf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mskhsows.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbzdpfs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2naecjdnc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdtzopq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2efbopgoz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiopruf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qrihptsx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dhblhmjk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaqxbcr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tirsfhop.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwfbxhf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2usnhsgdx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkguddc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtdpruw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbhknsa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uspsukys.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2djabzwwu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoxqivn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfzwfab.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oifniurd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2salclgxa.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgpaqze.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqdqodo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnvjgvg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxcktkp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcovacn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbhmyyo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrllsxz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mizhjtjy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2huetzqof.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2blrdnwos.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpandey.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2upbsboiz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zctxiine.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoivujh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzssgmzq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2emiyaakb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fftidvpk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tecyornp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmxbabu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrbrzep.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyhuyyf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwtbbor.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnbusaq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xcycpmhp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxikgly.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbarvph.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2enaqjrhd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lfforuzg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqpreiz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxppnkia.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvsnsqi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgkndmu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mxchenvc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcztmho.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2phrkidje.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fokgzdvr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vujlmrub.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zstghipf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfydmga.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kgupkpbf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoihdlo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvcmuvq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwmnzgq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjdubaf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zaboxmbl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2stddeayy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hefkbely.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxmpvni.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzurbsv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoxtymh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmdlbzx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2selxwssz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvdhwgh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rknofxbv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zskscywy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxjojer.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzrccsp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vwstiqws.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtatmcz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qoybqvem.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vedtxwsh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkryhif.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxnhbih.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulchocfy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2armaskir.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nitcwdga.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoezpvj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyrnjoc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeeflmy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ieadwssa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ioothrcq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kxguxtjf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvkiqqv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmzjtic.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2acxygnfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovurbajw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vlerwumh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flxckila.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvgicwk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2atgypfdc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svyytron.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qijwmjsi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2faamngqn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uetsxnlo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbqpamg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qwarvmxa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrbaftj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpwuwcp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vywddxhw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgrworc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ojogbkvl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdsgrha.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsbxsbb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mcntxtvv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpftads.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lseftaxt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkehgmi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2slhedqhp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rujoocdl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqvixhh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzbcocq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lptnfdfy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hduihchi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzgstir.html


<!-- 参考信息 -->