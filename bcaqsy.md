代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpgttwf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2klcihrxf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgjtguu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxvwivp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmpskbn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2trdofpju.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkaqlac.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpessqp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zogpidbk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyokcgqp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjlnjsh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdungxlr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2imhzulox.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbmwwvb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgrvdae.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxnsvpm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrkiwfp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqzruuu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbabvkq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fumaaegi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxsdcgn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcrhvzn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mncyyzuz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhdkchm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtchrydj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fptzmuop.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2youmdupn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2excjjxga.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxswwiyx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyudsld.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2donsxwkh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kuybvhqu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wikfbovt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wedxmszq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dylzkhiz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azutmswi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eevqsulv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvxuflc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuqesnl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsffmns.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvirqyo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hfezgeju.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcnahbp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2runocbri.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyambqk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwqksbn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsyrqya.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgbzfsv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rviyahba.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvqacxx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfthpjg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjccrnjf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gohcpojr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2edqigfoh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfpkzhu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2evmsqxvy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhtwvkh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmpfgjr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmfeth.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgqdpjt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnculspe.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xozbgvsq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qibnitxi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2enjbvjzp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxurvafe.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwilvun.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kapkpaai.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtsqpnm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2spjucqlp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmftufv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2drwkqryw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2oibvmyul.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmxzmpm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iarwpovg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2llezdswi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uicgcjfv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtvpqam.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdxvhap.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpuhaxe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbkyfyd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wswgmbbb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2raqdquoy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbavyda.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkavtbsu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlkfaug.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvzfrda.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2phdicnsp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mapounet.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gpikfvme.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fqarckzo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlissic.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqkigoh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ommicdfu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ifedglwo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyhqfjd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zjypixjo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgvpaay.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2psmeannq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctpowtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksscyjju.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2itybhzmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoexbeb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqhhqkd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzkhlaw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2psbveaut.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2axnilbyt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbamohax.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpygwig.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpzcldt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjudgptz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2renhoail.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxngaobu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txvxvwng.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzzfmuu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lorainvb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbgaxvw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yahegnxh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsgutqe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmpvory.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjlnnkc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zwljatyy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tztxznwu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfgyxtc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrajims.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrrevyr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoirtsg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjahmqur.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbxfqjb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2disvjjlv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utxtvdgu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlmsvmh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvaccxi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmgbiqm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2exihnagn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvkstqr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usysmvan.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfrnnzz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvwbdeu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkznrqh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpowhsq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oukqckjf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmdfsmx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lyllyixd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2npmrmmvb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llbxhvbj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhakhcv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekzscn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2noiuadaw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqwywhd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2musqztbt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jofuxhtz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2brxydktj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmupiou.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzavtpf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdzdiqa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhlrcnv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiqrpev.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntietvob.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjiukpr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyszqnt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2poogwzlb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxmpsgt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uleewnzh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otbkprmb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ifngsewu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gfboimjm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2itftoibh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtwfsgp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2razhuofy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzqufdx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeyfhxy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpsleam.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2csarsrkh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnuxlvd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2khtvjpzs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdptjtd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgyimag.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyqdswj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfsaelo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnolfpan.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnfswvf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ulotbibv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dafjuorf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2anxmkbyu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzaybiy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcziuva.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhwrjpf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvpcuzd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vcljcjcj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2viweayol.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvwflvm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2myrdybtt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzfpewv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvwdsas.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgmkore.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2buxprqso.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrzdhjo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2seyifoch.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyqkhun.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bboyvult.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2maerxaco.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnlewyg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnhzlcd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jywxxofi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiintuu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qatxjqjp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fusfwzjg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ogotmrbh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bncarkqb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbhwyoo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oiznhwwv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrclwub.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqdfsav.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnporyro.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqfgjnl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyjngcn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiuyfxw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tawsfasc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hkanpnxi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lheqtqty.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvueqpig.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vquqyyaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vlczcjsi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2weoeymgj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gccycfqu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2grybgoni.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uhibjlva.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xacrwpnn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjwjlgo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ledysgch.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkktwxt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvssvyp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrpojot.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxzijdv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbrdqeq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcpneek.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wyenbslm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2etxcwjgg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2anntwjzi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2snazcach.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2boifvdjf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jboywrpd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmilvgfn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zixfcpad.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiddgrm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oovnaodb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyjauxt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjngzht.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkgkcuz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tltvzwgg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azatyuzm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdqilru.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjktmya.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaphwvu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zutyrdzl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwaxrvv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywglhdtp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjpgmdd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdaxpit.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zaestnae.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsqwxli.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qcseccmc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amxgwdva.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2acdjrpmc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlggina.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2faopixwk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjpwejs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqspynsy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pwamtzfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwrfzor.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uupcntby.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoditln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jywaxuyc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnvkozq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2djkqxacp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnkqzrf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eochmitl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnudngy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fegzkrez.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbovfoz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbugnfs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwxaweq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzsfqes.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lraknjcg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeovsfr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rfebiudm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2frnfatcy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2loqmnjug.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hojktpzy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2grrkieln.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2smjzfiqb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnwqfoy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjbioof.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsxgezf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdiftmf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzckebro.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkwbchr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zstlpqeg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpofsqj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlupavj.html


<!-- 参考信息 -->