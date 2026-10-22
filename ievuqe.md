代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjxoime.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcijntne.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfnqryv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcmbcjh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cwljfbdn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ledskhoa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdjlxot.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnqaitl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wasorzbz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oznvzlyi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kysrbcmx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmwumfq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2azvdjxuo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2felrrmqa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2irjfxely.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2urmykgbj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2siusjide.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnixply.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnrtzcz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjghgge.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnzhqvs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpusujq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtogewb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvdvunu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2khotlbqp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jifdjquw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gltavyxd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tldvdmsb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmnzyml.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2piikjoze.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdakuif.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2viteoowg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zniegydf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjlcovt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ginjotsf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2trcolxst.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nczehkpa.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kyckkcho.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctifwnrv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmrrcvr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aynhlnrg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzztcpyz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhvannz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaploxu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbbftjb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdzxgmk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dzatdbrs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbfxkfg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nuawiefv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmtkgpe.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bclpnoqe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bddxvvch.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbzjbhn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnilckd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqdyzqu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdeevwe.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2evncvpei.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcfuztf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfttfvfu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2najliwtj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gewnlqsm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2awglllmq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mcohdeif.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2endmvajn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvomqcc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cleflozk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tcadfxly.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2trbwaaqz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdfjngl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gguovzul.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuievwhh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqeionw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2asrsdlne.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2otsncpmz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fphecrxa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdwajoo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2esvywqqz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvwqghx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ydogwrsc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqjbjqf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uuubjwlk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdrnepx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2peainigg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkowbcj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2voxwdoxb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqipheb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrtfucx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlacpap.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xylsnelh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swcqpmuq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2emtxugbw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrretef.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgcixmp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nbigxjro.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoxhwge.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrazgdi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhonurnz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwceaoe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nalimcfm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdltavq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnvhkzu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dewghiht.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uztpeiwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pspbcfrg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2inoonyht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfqndfp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkcbeva.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yibqkhwj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtoolai.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mncsgish.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2splhwmtn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsbuadk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ijypqvpu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvmbbnb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfocgyu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjabsen.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxzmtdl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtrmcow.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgvvjae.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqgibfb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwjqoyr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2guednvbq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gkslkyam.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyjzsob.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2biebvbma.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbquilg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rffdfmmt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhfdbxe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2erhdkwpi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2egarsnwt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxtwucv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxkwdaw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdllooj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlvuidk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ydghctaz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gurpwego.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvejooe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qavkhihq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2etsiykrq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2haoejlzx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcammyu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzqrdfc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2spnonoot.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrbrgbn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwosaua.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrfmnws.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2skfasqfu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtmjwag.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grauetgu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfnkbvs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyhfamq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdbbipz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjihvuz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsythece.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlclqvls.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukniqutc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmmwexx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyecava.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afugszda.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpkslxq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvknktds.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fluywwkp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2izhnrmqh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmihnjj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqymbdp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fwviqykp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpolmzh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaerafq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdmiutp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvcjmmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vduoxxrb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxksflrb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwueqoo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2doxciohl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnxyidb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmfjzbe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoijnlr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zyywnxxi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kuohkekm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdecmbx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2udtcbrtq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2poopziap.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2csmbxujv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bedhgibm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uppsqint.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvohktg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvbvpln.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrryqrs.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzpwyww.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbtrdqy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiqqsxm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2conlkuao.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpsxiby.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gvybilfw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xymiwjdc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjozbnoi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzqptzf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wilghnxw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yugezyqv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vznlzzea.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrjurby.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2adwdbvnz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqtlwqx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hodfhgqm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dniwcwpx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlyqrqd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsdsgkv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcluaydh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyueajg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjcdzwi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obpiqnox.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhswlnu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nrisggrf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jspjvaav.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbtlrvs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2llqgujig.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2emjcbtqf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhivggjg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yngyvqok.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2acyydadv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlpnlvw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oxebqpld.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2izbtaodp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwvccfj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2shlrwsdp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyxgopd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qcioyqkq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfuuksf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlyzldl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2omfezmse.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gwntrgwd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsmtqxx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wykbyjjb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abmiogdg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdoafff.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2soizacuq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbqiqnn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2agdyedyv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvzlcgu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jyinedvk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbpxifm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gocpjppv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2utsjvzgm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2auqouzik.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeydmgd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgfteit.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2muzswubs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wkagzsds.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjeqadn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvfncvg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvwtiim.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2shdtsnsf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdrxdtw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ywubzahs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhijafq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2osyeqofv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fswmjxfv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qikbrmkx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyjydch.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzuagid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tethdppa.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzurgxod.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmmzeac.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzpqvvs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbxpdtq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtzccnp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnbhfni.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmvcxuy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxpzrgh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jobmjews.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgjlxvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhdbpqi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpufjpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bduhsbjd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kldaexbt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ljadfpry.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaiczav.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuiqzbv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnmojhi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jejgcjgt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nivtgtqw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbvfnsy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2txukwhvj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkgfhvd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfdkiya.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqejrpx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nmugljvt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkpvecq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lapdvybu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2letldcqq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gicfakgu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2clujfljt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqtxlrs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2utyubvmt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxjrdzc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dscpcipj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcimqnuu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xalcdbnp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hifvgbhb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reamnfhl.html


<!-- 参考信息 -->