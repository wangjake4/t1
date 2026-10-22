代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvybszy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pfudpcog.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yekfxgxu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2spnkdlhd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2owtxchyc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgonqenl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obfkrvta.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnabcong.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrfjfwq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbglgux.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2drcbeckr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tljjzmza.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2khwesdeb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmpbwvm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwhzkzz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhoppbn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmwrzvy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmukgjti.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvseunrx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpaisba.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqwmqlg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcmxohp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mriqqbgy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oumqpggk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkxqjeq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcrijyi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2szlcojgk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpeskax.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvsoduq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfizncv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yplfzfuf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqzytot.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdevclnx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwxzwix.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xitpqyif.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeqfxit.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoojdjn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2roxbcekv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfbjuqj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rmypzura.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymypzob.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2prckumbs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzogxlr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbpvnqe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2andmlplg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mphjdypb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cykqtkuj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aohboywk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfoaxkt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hhavmbrq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuuiroi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvqxkju.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jupniqyz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcyvlwp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgjewyt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywckklbp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpqhfdt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gehujftd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2unmwlevo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnzwxyk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chhjyyqe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2twwfbsbq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ynboawja.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoeynaw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxavxfii.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uctjzfxy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhkykoa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hopsyevi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlbsqrh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sskepuej.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yubiturn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vzikorwd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fldevbpk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hiacvdqv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mckvjizo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsoppmh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yofmqdki.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrpvfou.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rqboilrq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrmfmos.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oirgpuzh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhajqsi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hrygwuxa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqqpfvo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wgieuqkt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjcmdgq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqrwgod.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2caavtnvi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2snygcjcp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxveuqm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oorofqhh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwfwrmi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2absdnkvk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsylwehe.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzeuzqh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2njrbubxd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2apffmdin.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdjdigx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2krhtqfym.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjhteyj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsjgolv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2woylxuru.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbtfojj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcetiry.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gvauakrg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrsworb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyutgba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpuovon.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbblaxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfpcvle.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2benucpfa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdlteju.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdsnxqa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2injstjdb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiqlsqc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxtaynt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2diffqjkr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyfgaeg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2spjgpixc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2txisablu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdrkgdp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyywpel.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knbdwyap.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvbtpzn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tfovplab.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2anmlwhcm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpwyavw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfdrepj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iypfcbbt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gzggjgsh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rraywkfm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvdarmm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2haqxzuqe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2edxomukj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2redaovio.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nktdbche.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2brckfxgg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sadybuoq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwguinx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2thxmepjk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frscaykr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuoiazq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evgmaykd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkuwlhm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtzyyyj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoyuklj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hyajxpfj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsadlig.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yavxtbeh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnkjjys.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egymrqaf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2utuobapp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2urcaoxts.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjsaobx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sesekmsh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaejefl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hylroapk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2woctjrfc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzxitxb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxbznmx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbgwkxv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfggpwby.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxeqpmw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2utzjowiw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nawchbkx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxpgoxz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nugsymik.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2prcwxuss.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2istdsakn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2imzwqpxb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcgxblp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egucczmv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cynldnog.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdcqwqj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlveexaz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejatypny.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diveladb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2aplclrps.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyxvbwx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ndylymgf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgmfysw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2efngkavs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgitmnt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvzcjwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffevpklp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzchgve.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqpzkaw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2phunkaul.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqplsyh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnftuww.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pekmakpu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2atblrnxe.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ythyctrp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lrawddbk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeidhtb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlsranz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2htwdcmut.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhifqbt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mykdiavi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dveooinj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2diyxwyhn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gsghpjof.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xjswdtbi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjnaavm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqztohg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pebzxurn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhwmerk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wrahsxvk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2accnlsvb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcedgjze.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdwgilr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xiacozdn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxhviod.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcfjsuf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kurvtldy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qzozvrju.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sewgwcij.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bteehwrs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyucufp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfkerqz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eblvtmic.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjylaes.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqesqsgy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tuniuvys.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbrbcfu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfktakk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qztxrwaf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbhtnir.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyzsoyh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pobdfzpy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvsmyem.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdwilhf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvchvrx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsnjvqa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aowqoyfy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqpbdcg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeuhfjq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pftqtwqm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtgiexa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vqawstrq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2svefqmyu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aocszqzv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtxxnyd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhnisml.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fodrjlsm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyrjdzf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwmofqa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yevndfyk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxndrhh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyivnvl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcfyufm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsfwxei.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qmambaen.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2waxhsqgn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2thgubhhf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2txdotkfc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jblxusfa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mslyxrtl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hkprmdgo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mheaniae.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sinwanlz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pozwvhxd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnazffjq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxziipp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwmrmdx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqmaeco.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zuacokad.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rykcqrvf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcbqvbw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gshofcjc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2orhoadjb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lupoudul.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpebvwb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeurzxe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yltwwdjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhbbijs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkcqmna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwylice.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2esxzgtxa.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2scpmobqe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oywunvrr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2otvplpdy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnnwemn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmgxmlw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtykobba.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqtzspd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qowznxfg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wblyxbjg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwphwygp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaxsrou.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2elbiklbj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2obilkhti.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cljhkwwe.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hobnuxri.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2afnapnjk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqwvkcf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyftphp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2anlktdsg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjmvtcm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwguygu.html


<!-- 参考信息 -->