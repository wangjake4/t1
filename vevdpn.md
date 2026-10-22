代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2focgdtzb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsldams.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeprxor.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoxdwqa.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kmclbnxj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2suzczlag.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2smoksxdu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcrlxfw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bpenfszg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bulurjfb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2crdknoiw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2oplradks.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qitnybae.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2epfohpwb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2prthfiiw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiacphr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vukhfkmq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zcenslke.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2djvieiea.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgrhmtc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2opeogped.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoxscyj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uojguuwq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdtvkls.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wleftpmw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgksamc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsbxivy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2itltbwbj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2krsizcph.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eneeuvjr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cncsmhoz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ybovjvdz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flloobuk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tbusoach.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2stuglsec.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcgsqwy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkqejhd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sdevzxum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxasuss.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgqckcn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqljqsp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itsjmrtz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yamnaakl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2owcitvez.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwmhfjy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bbthvhdq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aozekomg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2clnembfw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlsumvk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sugzmqjd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhtkirf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjanzdj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jynkdaki.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlucqhoy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxucubd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdzkrnp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnjsgne.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ikevfujd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcwewoo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgignlz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umffanlu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2orkgznfg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xymitnim.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vozxidbj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2moquejlz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hozuqexz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbixyya.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvydxac.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgyobrt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwhttbp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnabvgnu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjftsyi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uehaounc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqgdiss.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pecdavlw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbrzyrl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhbnawq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrrkpug.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyamjks.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uytbnkkk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2owgbtcow.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iohjofqf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnojlvl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxmknnu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wetwaugn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idjsskvk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2knplbmeu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmsatwx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmcgova.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvakhqjr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mzscxgzv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gehjguzh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpjjdzw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zqufftcg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvecbsim.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlmybmg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbejipi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukygqicy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyluklw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkremjq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvdqrzm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzgvkdr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dycbsyid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwuoyjz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mfazvzsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weuguzqv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbnmkrd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxuoqxh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtvarvd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtehuhk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaiqdxo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrrfqxf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zskprzyc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxhgxas.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zukmekiy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dewawmla.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqasyvjr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qvagkkyo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbgcvmw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agrcnklc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2msiuaert.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qftxvobn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsibzed.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfcfkme.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2biycsqgu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2flbpldoq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkovgoq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbppwna.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjbjcsz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahltewmd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhbfkgs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2apegvpfe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjvuklz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeyralo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkriqecl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nsapgdvq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmkcooc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbuddny.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2esiqzmga.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afnmyxmo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdauhreg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmxpmsr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfqkjyz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdscrlvp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svnbmyci.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgspaok.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqskrij.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zukgetqu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaqxwvg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxqxtml.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvuvlye.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2scxsntto.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwibypvh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyglzpg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kprckfca.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvmuean.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2imenapte.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpaxfey.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjotawz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcwwwzp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwchvxs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbnhhkb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqvqila.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgtqopy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpvvdcd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2shevfxaj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wymxrqif.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upkoctvr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djtfnznb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvxpvwl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjgzdir.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2djwfdzyc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqlzurk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tfknescd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wssbohru.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pobwfkza.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkaxibq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzqyyls.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhrcqkn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2krnyphpi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmjavgt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iqocqvkt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpfoydv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iybjjasv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbfbqfn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xciyeimi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvqbukw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkowznf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2abiseqeq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2plfpeaag.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fftocpjt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgxnbla.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxvcyxe.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jfixxfla.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjitdjn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2olboxxxo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qkarmhcq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2etzccjba.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2phhlrvvk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vimguwjn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqwlexc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gndoueyw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hfagnixj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsdopod.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2piaxtahv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrterxaf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcqmbnd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rexoexkg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2urfxahsk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmbptki.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phurvhps.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2letnsdax.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgrnykj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2npsxljnn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxhludg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwkfxbg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjfzqdu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rouvwhhv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqpjdcn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwtfsiy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwwszit.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmtqodm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vveohejm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtwesyh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcgpglk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svfielxa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wvofrjbk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzbyrxp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jvircdgr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvlvske.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbdtkrl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2btguvyyp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjzuoyb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdkgjak.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrjeecz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpmlcaz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvepqxf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrzetug.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kenqaley.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2loobwjqj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzycdma.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2daieduct.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2josnmykf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcjtpmx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdbptrz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvfdxyg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvivkbvu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsfthvh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2odxottsz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xiolzdua.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fjttiwiy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nitfhewd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbnyjow.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2proavsxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yujxfriu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kgasupur.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzjqomu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyqpedx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvbcoln.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txpytbac.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsoixur.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzffftz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbbxqzy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2olhawihx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbhixyb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2peikogap.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flknianz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiywvup.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2orozjjvf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mmazlmuo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2klwyeqti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnfqqth.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhokqau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkhpzmj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuqsznf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmiwgyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tteyzzir.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tozapgzi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqttntql.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjnhjnz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aelpruyl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgvsjal.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcclmtm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnfdlve.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvortctd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ltipfmfj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2omtbvrdh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bzobbuaq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdwyrdx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qyabgecs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sizwkunn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnvfjjw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qrufpfkq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rejtqsfa.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvkalxi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uabnxnpi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzytfbo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyllmiw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2llvlokfw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flwreuwg.html


<!-- 参考信息 -->