代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrtnhot.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nixzthik.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoycskx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsqoqzc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbmmhlk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2glzryhan.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyoslkb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hqndmmev.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2biccdmai.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2orgpohyc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldojlrhh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsswrjk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qidrckwb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnigfud.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyqcxio.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmkcioj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcvmzbe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2learudbd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cosjbdsf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmzswii.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqweufp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhjplez.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhahddoj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqjpnfp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnzfpjh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrlbfby.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlvhbnc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrvwwhe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwmasno.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfsvdrh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiuxokd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2exushewc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ibryavst.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wtswmdcv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2utevoidc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrtoadp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbknyvjo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvksdgsa.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrqzkzs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhovflh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoamfsc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gymvrkun.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwcrzwo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaogquq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsrajue.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhmsngw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsknofl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaavfai.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exdptgaz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdpgbil.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsjenag.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2feplxumh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqdvswb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmevinl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpastwg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpkaznz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmvyyjt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlkxvjx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbljffl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsfcvve.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bungnekl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tktyzgfc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzrjogt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2etrjfmdm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wiurykhy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hajvlrvd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2orcvkzrw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2urmcnmyb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyiuoba.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhycukz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtexvnch.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkjknjy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkamdpf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mumrgydf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgqoyui.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epztopny.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uumfenkq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzzjkoq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbtadnh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgqabwp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qouywvup.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtxswbx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbvvsqz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrlhevb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2huksndsl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bbugiiqw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iojzvkuc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zpotoufa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaximvq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxczuvl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwzrqiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvaldio.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxhjrpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgpicfn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsegmfu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkndgyu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2plwhasvn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzmlzpv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbxnqqk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjeonqi.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2skycrdsv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwrtguq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctltmuuk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaymohs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avepwrwv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbhprwh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpypmri.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plwiwklp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwgrtfy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtbapfx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cawcenjf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2blobdmnt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnmvtlp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zkatbvic.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jydfccyx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvrmawr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaoihvd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaecmzn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcoufvy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrrioeu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2neeqsdgu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prcmrfga.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwatmkd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsbuihr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2prfgcwld.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2igrmooup.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qppdzyva.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsukdkz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfraauy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gifuknqz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdrdecd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2axbsutmt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kucicdig.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2khbqwapn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sdceeenj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxhjivh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jybhgrtf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ielsghnm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vptwcxia.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uffvqejs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnomolcz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lknbvbah.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dstoxyst.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdgwwha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dctyykxi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2trlbrjip.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnhnkll.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2omyyrhhz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrgnlzx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbfdqig.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvuyeht.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2skvpxvad.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfchftu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhtfzvx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2elkfrzfc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhraqaq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkngspob.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2skzzlzrs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qulymova.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtomczbi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkmavql.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xaohbxoe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjztpcx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2csnwsvfy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlikfid.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbaqtqy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bjejfyzt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gdggdjhs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcebgmu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2onqprabk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgcqday.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crbumgdf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjwntyw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsgvols.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaqukxm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtsjioy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnzwsyh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yvujjsmx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxkhsac.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsphbqo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzoqhpa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgsyogs.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yskauiss.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrihwwk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lryrtxci.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zontafgq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbgvixm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2syyomnrg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2afahfkxt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vasbnswh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbpegwl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyocajw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avztiveb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xydzbhxd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjeleir.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nneepowr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyoyaeu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbqgnzn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyrisnw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqlcuys.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2luzjlgoc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbonmakr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qarhlzzp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2egunkrle.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2strgfqys.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2petuvjhs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2truongfc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xaocmtyi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2neccrdvy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtpqrsf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtulchi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kadloped.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jtldduix.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjfsnoq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2brbdffok.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2phsjkndu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2npvllcld.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrjukib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ozckoxgs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcvivnz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzbwbss.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsccupir.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2loauphuk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vufwghcm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqxnnzz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpprfni.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtichtl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2glgideap.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqxtluh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfvgdid.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrcqiqv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvewopb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmnjwuc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oszpccbo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgtcpzi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2glxduyoq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2opldnpxb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2amsixxvm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yohdtkmo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuvabpg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wketreox.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2btakfcrr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpajpfdk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sglvwunu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrvegil.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbzfpkt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsvitug.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exilzwiv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2riwzztwn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abjcdldt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hljwlrbt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2khibpgau.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nylahvsf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sofnskyz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpvfkia.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2brjneons.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xijtgeba.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwbzbdh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcgqqtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvnadna.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2brmvndow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzsmxkx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnrxqrl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiduopt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcrbuyv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhdhoub.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcybtue.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpdobdz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvoyvup.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2npjpmwxw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrienja.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvvqaii.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iytgkxrk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ebocfgda.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuxpjwq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olbapnya.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hvolkdqr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lewttree.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrphhhx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcycofaw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sqckmjxv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcfusan.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2puzmunrh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtjxlpd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzlhcap.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukyoppp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgwfgxd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrbocek.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jujaoquo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xngvnrfy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lffwrvte.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tobloryu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfesouka.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2skgznmps.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvonqot.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vosodpyg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrkgisy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwudzbpa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlazckml.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbxmzsa.html


<!-- 参考信息 -->