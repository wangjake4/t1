代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rcymcubm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhshopc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vohvfezq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwguvdi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vvljlbht.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwqrztw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqwixps.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfcdplb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiqkepd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrcasiq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xupfeefc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdhspwx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hypaxpln.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2flsrswwm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrknamb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2laelofhd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dybgxivi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtvmnxe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuhhyuy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ochfkrjq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfopgtsc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kujcyaxl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogneqqky.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdghbqzm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfecbpxt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpktyvfk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2munltumd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuyiufk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opzqgzzu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2otglbwef.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiqpchq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjqxncr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dklrdbdz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rexlboqx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xapayaix.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kugrprgp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeuqzhx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgzhrid.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeygjsm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtfqyul.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjrkqol.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyoqcqn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2apbklmvo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nracjaug.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrzwxjn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhukpoq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wovfqxgn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeflrpr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2oovxnxlj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rivfodsb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gakbgbij.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shfvhkyu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhhtlmt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ioydfedf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxbrhky.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hikfxfgz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcztlwjg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2smzcciqh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zuredshc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aeggvrdd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyldgfga.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qozyxivs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2auzzjpyw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhmfpfc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpzunkj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuoojvo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rihlbnzi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oywwpssj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzjejzz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qosbgliu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hugpuymz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzcflnm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lekfyqbj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2advfgqsb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gajkudde.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vqecxdef.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzgcpjk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlfxjvh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdxfwqu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbqsnmf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxaletx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxavibu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxccunq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hesuvrgf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gscxakrt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghihfhcx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdilgmr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhysojok.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiqizxz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2peswymvb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qocsovxw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmkjuyr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2caqszaxe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zflmgyhr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pggteifg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2epumuyff.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jdshhozj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpsbiza.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2whfdksvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpntpsf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2odhelkuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgikqjil.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdkwklt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2obpvgpzb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tflenkuw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrexxtl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqakrpht.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkeslvt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ordoryjb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfjykhe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzzaxeb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnqfqgz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjktfbmu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvjefkx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfurusk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtncetok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2reajinfm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khoomgsr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2thywaxsa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkglekhd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxyzbza.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwjczyy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrzkkxy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzozgij.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2npryvwzr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhxqmds.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zshvossh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzivrakd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2twefpwsw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kafhbzch.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iaujrmxt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2utsopksc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdazyodm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqrehgp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnvqsgl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpsjdqc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxccvna.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2maetbswe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbjvaqy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbcsfjx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhnxmhe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2imkmbclh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqpveue.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xstdwgjk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlaayac.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtghbwai.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiwumfp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jgczmjvk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxksnnse.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsryohs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ennnwqpk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfvgbji.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcutyerp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xslmrdhl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjqxbai.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wucamnpj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsbxyfd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxbtatd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2scpubphq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kfetxdbg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qokblaif.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fohnqsvl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqlasng.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoioktx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpolxkw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzlkmpw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lznfyfcq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrcnnfu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxgicgv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtdqdzu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueisxobu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjwmmvz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaxdhwu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlaeynp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uubakfag.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2npjrbfvl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2okfdoynr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zphvpodf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2trprbffw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzlpjyo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2djbtqzma.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2msybsqka.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbarsku.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2higaoezy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpujsvo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrjjnhi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2veyrdjad.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwwugxq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2idcdzmte.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nvstglkp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdgtjne.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxgndyu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wpybwoeo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtokxij.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2udlotfin.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfhyqmo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbddmjt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2arfhjhcg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnqlrah.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfhmnxk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwylxnsj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcuriov.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iurnjvea.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxwbwag.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2omfvdmlb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxbbadk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqkzgbx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmsssqe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtcooxn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2clbvjxxt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiwjeqr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xttnksfw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jaikngmt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qicaazrs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiwgkph.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbcotvq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vzalfeib.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaibyjx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xztgtadj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfdwneg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2undauyud.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnaqfkl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrikhqs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdyjdue.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgulaci.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwrzoaw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzxwqod.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mijsevtu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rshkaboc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwixenfq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2onjnvrve.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxgjcby.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2czqyadmi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mavmwzxh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrwdmtj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cccrkbyd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnhtamv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wunhnyjp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2twjiwfbf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpixojm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oxphwwlq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pungplev.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrkulut.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqlgqaa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfwssdj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2maobfgui.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2katuejru.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpoqemv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuhednz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlonuao.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2owqtogxc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbmfwyk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qjluezgy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cijogpke.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krkcuxxj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vouhcaol.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtjmftp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqvmwdp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeqjccn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ndywxazk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fbswmmas.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2szysixof.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqicqrj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwbmclp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nglsxrnz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2peelhqvy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcmruxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcexikju.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2blklkyno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bixarcxq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aztrpsic.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jssznfkb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zssqxmnm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fluwnyjm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kopjflvt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmfdomv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgauybix.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkaoqon.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpechkgy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2boqrruwp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eriivrtg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ndowayfq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzqaeke.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gobquymv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnjkikt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rucdhhzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbgedga.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hdodpica.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhknzzz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hczezgnr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcamgzj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omvthexf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sitqyplb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnbewhi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbenradm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gerexgtt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrarkom.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqzqmjh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlinedro.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbbavbk.html


<!-- 参考信息 -->