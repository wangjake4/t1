代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmvhofu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtkekrx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ennaleuj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdyvypt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdzhzpf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uagujxqm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2efxgoxep.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaomtueu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyxmtzc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrutocuq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2smyegkoe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2blssccod.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sosamjdd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgmciww.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bdauhmtb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhlcdpd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmnidej.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mncacyjl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2msbwukns.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bmilxboa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gpncnnkh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbmnxmb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkopvqck.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhtngvu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2khmrzdfp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwifxzoc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmqejcj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2umndrzsz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nohqhgio.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqskinz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrmsycb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2blixdscm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpixtbm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fcksajsb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtntsqx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzrfctq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmuumkw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfqnwok.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sekqrxbn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxlfiar.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tetltijg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wltdoscq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmxjdil.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfqleac.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmroirl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kffhncrv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsdtfco.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnajbgy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwbrofd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaadrxoh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ioucelyt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzxjkrj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrejcpi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sjisvrbe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqaqoho.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzrqhgh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqyonaa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2abxevycj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2auwwdmfd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2locuutfo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nofbeliw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvrtwjy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sgifpzwa.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2msxdotwt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eytdbpem.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjpcbnr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxywien.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjdaimj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qpioxojj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gszlespx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2urogxdnc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2leenvcnk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqksfrk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxdblwy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eafeasdf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2blfxegcm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkzwhtm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlkddvf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsfseow.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwyeatq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2omofgqnv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwonptr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwofeuud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiwkxub.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2txojdekh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2guktqiys.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pcycewyn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwzmkzd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmnvdiv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2uncdisbs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2deobpiyq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbucatr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2evosbtdx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvorwfu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzxhkkc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cicjyvqs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydogflnv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2clxrzcan.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvmfitr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2razqkufy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2smajchpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uemykapb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqyxzsw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2geqlqepu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mnihurlw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtshroz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsndkhum.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpjgyhx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jstutqah.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2maylzpim.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jykrcerm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsovpuf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alpmzuor.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2orsjwrcg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfazlkye.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwbpopa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2votadnbb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mnenwsdi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxpjwfg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uadqaxnc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyypiao.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrrbitf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fvftstyx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2phlkzdew.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqreyjk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqulmye.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2afdhjidq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bchogjhr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2egsntdxb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsdnbof.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdqkxdf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2geqewajk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2unglpxlh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vucnutoj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfdhcgx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tprsafim.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtisoikz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2awqzyblz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqhsvoq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzylrwoe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqwsbna.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxavqpo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzmcuch.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sovblbrp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfjguip.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdicaish.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cccbgbwh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2thytdkzw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyjvovl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ulknbhvu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnceejtj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdpgdsf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsypeka.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzikzma.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnefczyn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkbfgxb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyanfvxs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iifwfvoh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gesribts.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxccyqa.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2grbikgxh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcfqktl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsivmtx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwhbxvt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zgisnigv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2txgpyduc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gchclhwd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2indlcimp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkszornh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2igdcbyxw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjzxzkt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2otlokorf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2plwwwcck.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2aohqpndl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqkbvck.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ymahmkvb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkffkrv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrnskib.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqppsnr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiqsnuh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhscqmxx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nmldkeqz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrqzoqj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfvlktl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gponvdpq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjrvjdk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvsgrna.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ayczyiyb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxflzcf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cikjaaab.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kgazpjnr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjunjib.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpmkzci.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eenwmeek.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kwritiuf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mjudymjp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pnthukkw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoumsvb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2htsrsbst.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvjqczu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drktgvhr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rajkzjgf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uphuegpf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxjgffp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuivtbz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2euppdbpl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhfaakz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sovwhmhs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cviyyhoj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmucblr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nuskjyqu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgwuiwx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oaimqjrg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlhugrj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wifyapnz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kneducea.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2srvftyut.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dftimree.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbngmlm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2awhesbym.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmgbfzp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spbnmgud.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsxgkal.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvlqrre.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2siutglxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wsusxymz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwyaqef.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwgtusk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoblukh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnipufzo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pzryuxrq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qugryfvb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2auuiwlyx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuhgdur.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlqbzio.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2deugyhdf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeuygms.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcvxerk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2obsgryln.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhpnfrv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fyspmlql.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjfjttq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnciuqpm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlhwjss.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zphhodow.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrkioaf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lznikblw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjchytok.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2scezaepa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vgedjean.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajystush.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyvexdc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrezdem.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeggiwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkvefyo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bepvduck.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyucmsql.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqogfwu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwceoau.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gwolaswb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kbubozum.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyhrlur.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbshxyo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzkkzsp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzqzulj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfgcpyb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rstvkxfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcbibuy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeabelb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gspnmonk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqhhhny.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vyagxzbb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqylvtzm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jocwcrfi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rftlvwbw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkavdctw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkxjkyu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsdyijp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2soviaivl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zzochkzb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rggxoyen.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjuoibb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvkimhr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lunwbzxw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqruteu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfqpglw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nagxrdfv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hwusaclv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvenoed.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2boghimft.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2byjmcbmc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyfxuqd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzyecbw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuqczvg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2itkbjhfw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeghqtg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2owbegkrv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgrbjay.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hykggnfy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ecslhwyx.html


<!-- 参考信息 -->