代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mojmubuw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fujrocjk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2llyegrtc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpkdceu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2svlsitdl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2znnpolri.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2reriltdo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fujbwcfy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjguwgp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiybyih.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwktigfx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2afvlzqws.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdbxnnq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmpihtb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flkpdzvv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jymztpfv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbrjnvf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrwlsid.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2irgefire.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cifjnasw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfxhsnk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcxjvlc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbpjddu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpdymro.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oksmgetj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nghytids.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bduquzfg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jcypoxsq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oqisgfuf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaypqme.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydohzczv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcckswik.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rogjsyos.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlkthul.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ligvggze.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jflrzosm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isiipcde.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrryufg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eakzeidz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ooitvkjz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmacqcdc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxagwxsv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2umnijmap.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fezuxhum.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zgivcwoy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fevlbekv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrfqhrw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmbhmrv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdoslft.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2thjducpf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xyciqoku.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqqavif.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnpzali.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhjpeap.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xalfmxzf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzfnout.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yteoprcw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pihauwgn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2folyupaw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kocqaoph.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wywmgnkt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzsxxlv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2keyrmgrg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzhytem.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuqyxvn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcffyyp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2thjjzout.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pjurwlan.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yobhfvfz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxrjdek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2chztgnod.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tckeupbr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mixlzmvs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsgxdjr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiccjhnf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxutrtp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2esialzws.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gziairrc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uepbjupv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtnosdb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhndpjh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlmijno.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjqsmyj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bmflzcii.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pjctlmsc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbepykh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxxlxpj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymsrwx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnsebus.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2spzzwfrm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbbksrg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwbnnnr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rizqfehx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuwiund.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqqkjhs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwnmyro.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjmdbow.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqshuaq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiotrmcx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xospeleu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2osjudmyo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xcscpdvv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlzsbpf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ylatpvqv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyyiqzm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzetiimy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2exkpgbel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbefpoz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqbbren.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2effjsaxp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2locfkymo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qsshnyfo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrwrwaq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzmrroy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yavvtpav.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofswjznb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmohrzm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqheqhwy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2goqrzrwe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyinnjq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwmgdzc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aktrtafq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eequkvvr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjarcsze.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iprtjwpx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2npmnriul.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2inzswgfu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdytmyvt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzhncli.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ikujodak.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2prijfeop.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kacaspqa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsnasvn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpcuezv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2etyqdbtd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsuppjf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vqllbvql.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzabmqfd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njyiedpn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hhptqzwl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuobhyrv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqxdyhw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmxsfvv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaomnjmc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdriyyn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoktssu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rlywxioc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxgrxeu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbthnra.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vabhqoqx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edryptzo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2htjlxtew.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spjcylct.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgledwh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ondblaip.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yycyewun.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uygulymw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qilbxfio.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrunaiyl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuvpqik.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdncalcw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvkfzfi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcisvdmx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkeosuf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaagrkt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aondbyys.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzstexh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuucjbb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qazibvhu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fowyxtop.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2twyedguh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgclevk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvcjryv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uydgsmxh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2narznxrf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdxaboo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eimkdemx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fplfddis.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npycbawz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcfdccp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcgivvv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eseibgvr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2puhwmoek.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oytgqhyj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdzkckx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2piodwqel.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2njhltyut.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwchzsak.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyggpdzu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oczyikzh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsslmgr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdnzrhx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwxsugf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxusbss.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnrsshs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2drdatfdc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oiynfbpn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbgxkxo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmzcdjd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfregxdh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdlrkdq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mseyzjsr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qscvgmks.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnlzbfm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmnpila.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvufjdi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfklqwi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhgceej.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agouolvv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnffqon.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wycrwyrk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoydbel.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhwswtl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2txrnivhe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxinewav.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vkowxoiw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgkqsvw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zylzawjb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxictza.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2klcygiws.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qswyzxnj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhyyidk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2exqfanmz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2azuoflco.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkcsvjh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cnimdlpc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpwivuv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2smcghbmq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rddljtoo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrhrozz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fyecifxj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wthwrefq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgplwfx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzspbie.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdtfgze.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rffbosls.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjkgofh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iezjjror.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vavucbix.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvnvejp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbjhgsu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2krmwufpo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewfphti.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrfegri.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvwwljd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvckquf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxywbdq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2almiliyp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2upevmnbc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qkffbptb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmioema.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrbvrth.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqtzsvp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlkrdsh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vgumcbtx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xecylhxf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilykegfy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnafjxr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlbvhjr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqrfrzy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrkxfql.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzlcxfk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfdfxbc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlchemns.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzynfqa.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsutulp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxryifq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fktdflsz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2porqzywk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zimmxkke.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eximvnbk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2exdfpovr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxcvzob.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2apmhoquy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqeqttn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpagrgnt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnohnsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkgsrms.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2btxycafk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxswawt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkogyme.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vxldgvns.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zajnbjcu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2udwfhgem.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfekulj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tresirdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmlahnk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwxybeu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vobhnyds.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2erivpepx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lltwcthc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnjvzur.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfpgoag.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvzdcci.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nowrmuuy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ncihzjmm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqhvstf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2efovrdyw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2szzqvehq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmciphf.html


<!-- 参考信息 -->