代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uamrxngv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2crxpxkig.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxxpakx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2soqojfhn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kayftuga.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rptvlnqj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwgdlfr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dewhreyu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqjeuhk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvnhgvo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2exmsbdpk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ccunhgpx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ypurwgra.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vghwuqch.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2miqplbej.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2imcimvwx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dibzhcpo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvpdmfa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnexdug.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kroiqvwk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcbfghs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaikpmq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wldkskjt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2emjganjo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiiahtn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzivwyx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2sclocvui.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2icwmmqew.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtbcqop.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqjqsav.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hrczircn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrkwgep.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiiadyn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kttolzkt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2flzwrxug.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eblvwecw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hntplton.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsdhzzm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wshylexn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vahckngc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpvorno.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2airtkbpi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgeftzy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2syvejimz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zacfyjgj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2avaujdbn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjprpsmq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuhjaam.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czlstmsu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sidpdurd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjyitzw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbhdfop.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyihagkn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gkowpcxc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jaskdzgz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzgqndo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoiwemn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnjsory.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ontoxgro.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2drpihtzf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kapbsgny.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gndurgmf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgdrjru.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mqawqbml.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2olzarmqs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxmommt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcrqvsm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvrauaf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpjfbxz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqozyqpn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgguzuur.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfergyqu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tajstzzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgenotjq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfyeltm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcfkdqv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtegfha.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2albfwpim.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2itshnioa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eztobqtl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqroubu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2iufrxntz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bckoqcty.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2egliehri.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mehvudhq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yjezxesb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jifihqeq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2suflhhfu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtzqlzw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgrklfj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpwndqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grlmjwsb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hchwizam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkacxqgh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qljcwoee.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiksmbm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwhbkwm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgedpsbm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2obxtcxxq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iehdvvrr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpwfgpn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmofmxo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvlpkog.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tukhuhjf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpdliqk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2erngbrvz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2henqybjp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyljpgv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lumpcsgw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2frwfqnkc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ziomwghr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qysowzrs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aotdfyzf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbsbxlx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aifvnafg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmyzzbz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2igzihezt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgaevcf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pibobxph.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwulxecj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfofwui.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2quccoida.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ietwuzsl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2abxqyxcx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iyowznyo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdxliyz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utghvtwd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvqyfmy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtojmea.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkfyhzi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gyednftb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2reykusut.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kclmqhsd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cazvccbb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbelyub.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyujpbz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrktqwq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dycrfzga.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxtpqem.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2risdvqff.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvmgvaq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjazije.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvshluf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjeokwo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2whiiweaj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2paogepki.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqwhhaj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vbonktrn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxljerv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oscsocwn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsmsmct.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nsetipuu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdarejtm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lhevsubi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rqycziuy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hekshbut.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2scxhdlog.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qrviuveo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oixqmljq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2istqmlye.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrpwwod.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwphtck.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhveirpc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jregolal.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2klhvaovw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2iekrfbxx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nowjqugb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhxgxsg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmooluuq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyyuyzy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nowzopdv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwqmtgr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzueosbv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2aecfuwnm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfvbsvq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlvqjzu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gyythrcm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbaokjf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxscjic.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjrdvhy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yqboqrde.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mjngrrty.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzplwzni.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2guczuxxl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eiirudul.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqbhxqj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2seszskdz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxkailn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbmhxoe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlewsto.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjwioin.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaayrqi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okonbfvd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2flinfumg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owkbyeve.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzrzbcf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlinkdx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2injqnddr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvcrwlz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kentpbnx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxgslgp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bijfhcrr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ligubkki.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nfujdaky.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gznahhwe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rptjuvpx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxshulb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fontwaio.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iznhuste.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hyccoomy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2stxgekdo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhxtbaq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrvbzso.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqldtznm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiusjhe.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjchtdj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzzaay.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvaistt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ckssakdj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2utrnjtre.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuboclu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdmvkuv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxgrniq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmpjsyz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gbupznjj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuryfan.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2futykbso.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2idjvfulq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmjugzt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2khqkdfrn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhbkeij.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjqhgkk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2juchtmyo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmktimw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqenxob.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmclfjo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uushmnuf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyglnwl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2edqlcvzt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2evnnivhk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2juczioeq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wynslqjv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfazsjy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vljkljlu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uetaehao.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lucqawcy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gggucaip.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpscghk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vusnvawn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsfripg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nbakprvk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2elpuxeik.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrxtwfw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwazvpi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbwsihd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wlirlzwh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbtbaob.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgckxnp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2phjsvoob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecswekmv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkabapj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbciuzxo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtopzio.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xqesviho.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toedgqye.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqomocu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxhcogo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxskgfd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhjftih.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yuypjcko.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfixemm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2slnozcnc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbdsfyy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsksjmk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbuaigu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvniqyu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hvipytyz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpabobq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkguirko.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ajypmufz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bjihjhya.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfqahie.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdxinnu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njaknytl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2klxuwhaj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fculxjqo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2edikaafp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjankbgu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2toujdxrg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxgoekc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqawubij.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2txitdpwq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbfolew.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aevaqnlj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhurkduy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pivaasab.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imjfzedy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtggzma.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eexvwbgs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2giqapsyb.html


<!-- 参考信息 -->