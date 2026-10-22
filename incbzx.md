代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2omvchani.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpkvugv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2diemfmrs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwryzcs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjclwfa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgtssnj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tzavxhxe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2glpbjvow.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwlqvuv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkswswad.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcgnubu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxzxmoz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oochxsyw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2erqvkego.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkrchvs.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2byclfbht.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dneskvel.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcocsug.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxemxqh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxianak.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pquxfoej.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fyifesup.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2comjfhzc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsupbxzu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbfshnu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmlrlrk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2awjhwnwe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qmalzqgr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukajnpks.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtaectu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwchwfz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeironk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoaeolq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mawbxmqw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyqvngx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqohfyiq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcsjnog.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgicdtyk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fllwqxij.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2glixvopn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2orjcdigl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyqodca.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxmlomy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2irqscaas.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwlwaal.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkfwqfi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uflcelyr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiegjcz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gidokval.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ensrbjuy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fqggobcj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zijhjsiq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpprrje.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dylvkhej.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiirzer.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qrayxdtb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvddedd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ehibbsmj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpqsqyh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcdbflk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onljknsq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oflhfqev.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2utmvitxh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2amnlwayz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2skvujwih.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmccpvm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2csxdyalk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mpahfjgc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sodlpqpm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwvckcf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2plzbocdv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwvaefw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cerpvoma.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nejvqbod.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbvgolu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2exojpqeh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jccrqbxj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axnkmgpv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rabdwhms.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oncuadox.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uadqgmcd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cujxzsjx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fynkggsv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vicuweld.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zstbfuwn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcjcidy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2avmpriqv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqplukqz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2czqsonzf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxaxfim.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrgdluq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iomuuons.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rswbinks.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgkyats.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2darcxyzj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2odxwhiab.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cujrzred.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vffvyhre.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgbdnfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjtkpqu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ahksyuup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiiiwia.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qalgciqx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fnysppmv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2aemfezoq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgsodru.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxsdhyr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vllcnfzl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bahoyjdm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2numrkjaw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgwhxbe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mbonnmis.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyijwdvq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhsacjf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqzkjxq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbkzxjc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvbspmf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqwcenv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrqpmzy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzoqkwz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sunbfuwi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2whzzqpqw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qoriddnn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxvwozw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2adnngtvx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxlwmmi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubheteeh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2svhmgzpx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbyenrn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfgqeoa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nntjblvx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxidtga.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kauzpkuv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsncssb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpdlkmr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2talnhnfl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzlvndg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioucavza.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grtybrbq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujczmgeb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiwxclp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fttndofi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqokxkt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqbrpba.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2erdxaxfg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzwayxy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krjnlymd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxoewsa.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkjkbhk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyveqon.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhityckd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcpvbgy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwdhjgw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuwclvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfgymou.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhifehg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzlqgmo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnobagg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2etkwxgsw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2znajtdfr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dffzncbm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ningzeth.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pihoxjiy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thtbwyfk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2facdmksv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbznwsx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgairumt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtsxkxo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiqywyc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jedoqveg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfckfmnl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qbunwqbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2emnwuskr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsadkgn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kzppwtnd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcnzsud.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmggsxkm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyrvcqj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkvxpdd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdplhszu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoazeveu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2twlwiyhg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfgcizk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxlffsk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvohbmt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtdprjp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2urodainz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2czofyttk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sodniwny.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhzesax.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlngrtli.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2athhtfrg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qodmknhs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcyklfw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gljbzmow.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2itlrbhxw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tazdqslx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xlheyaxn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2konrxygl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmglzewq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwybydr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcniuynk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwklfxo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwlxnow.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oawukoyr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfbqcep.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwbkzue.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlawbsx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvnxtoj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzspovjt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjutkuwt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jkorqqky.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqlgobm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnttrfhn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kahrigej.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rtycyvgf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2onhlcpke.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbvgdsb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aryrajkd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqywbho.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2woorlgnj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgggkwd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhopldh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2igkfxerd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2igdapema.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyvurjs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rmimxlby.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjohgff.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdaohdg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsagmllf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqjrzst.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmupewu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxxivwe.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zytalzsb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2epsjguij.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaatxds.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfodgpc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vczlkqgm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uggngtoy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqyhsic.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbaisat.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddymkthl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcctjgp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2afltrdpj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvfgmax.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2euzkmoet.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfpzqae.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuyitiu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2biznppyt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoedgfz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lgerfyog.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cftzjypz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yndyhxbn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eoshrgti.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjwxmfr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uudhbhrz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwiklpq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhevimxu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vygighnm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cphqyuvl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2icoaniaw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2djxmitzu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isgezfwr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fegwndtj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pjynecji.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyjozmy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2odpiflwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtxqwyr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdprswr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzplqfjk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhskrcro.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2flzikwiq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drlkthiz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2drudkejl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2azueklkk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzefmckq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyqpdih.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rzprznip.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kehpfyql.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoziylc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnjadcj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjfjumo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzpgkzh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmyhkip.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wowkuqdg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiowcoa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkosnfmf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkiwecz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2npkmjjpq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwzspih.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjthjwx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyaqlbj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrhrmro.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rshpfdcs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmbmgwx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pawhtpry.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2neulsccf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgadvdz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2luuuurnx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgwnsie.html


<!-- 参考信息 -->