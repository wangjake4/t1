代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxlasrw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2igeeddwv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtnfxvw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2laqcshjg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2phqmdjqk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2srkauuwb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dylugfil.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxqgmqc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaykety.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmgxjqs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wufhqxbj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyhwoqp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqowlwz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xwybczec.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2grxbdctf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdwkhqd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbwfxhl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuxeldr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgiyoux.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ockipgme.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzdrjov.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hzczhkrm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzceybyr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzvznln.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdliytn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2axjbcbhc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kszbmkpk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qokiqrnl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmugqnc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2emheiooz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqfmkyw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2njavnprw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2khwscvht.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sikuizwo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gltrxrrd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmlfckb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrpktav.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2byjiccrd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qqccmjlu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqvsxlr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyxsaoi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tawbeyoc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dgflnotk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyzxbcb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiagnjc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2smfrwocd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2opnwezgr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajisqjml.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqpkgjl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nolpxvfn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2odyerjkz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkegnaqq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpxlnws.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cygpdklx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2heuzracx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdushio.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enqdzufh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2devrnzgh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdgupaj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyigdae.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sacrtsbd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gmejordx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2apwvzwgo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwydxnr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qfityekh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2agoacbod.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2umzoijsy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgudszx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjhkbuf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2twvsmtbq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rmphsymd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sctobizd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ccphlrmp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cavzverp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ekorsmqg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lravhkup.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnkyqyo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etgjijyq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mshyllqx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnjjxnp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtlnksp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoigwag.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2egrwscio.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtdxvwy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2amkgstoy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdvlofz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaxflla.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zslpxegp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aqefdtlm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2atilvvzb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhnpaed.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vldbujjy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uolgppdk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2btsogpxv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csyibxth.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvngfub.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gmonrumd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlguwkn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcobxsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyzkumg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hlflvltr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtqyvbj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dizyvfen.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ultqvrpv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2luynoavh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrxyxle.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2atiqxeln.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpvyihr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdtvbnx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2enmtlpnn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2epfxdaxb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yylrfdat.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvexchb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvhkozz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjnnvee.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujniowto.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwfbhae.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2getjmyrq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjwjbsg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kijvcdcn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2azvtouuc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaqguwj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2azsqthsv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2icqxjaxg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuakmpz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgygmtjo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyraoaet.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsqxzwd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaaweim.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnavirxk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sismyusd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjjovqj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzrkcio.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyhhlwu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjdasdr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrzrhov.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwihjwy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzinjmxc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxxgynx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysemksmj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieptodbi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2spsrbaxm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epcwqubf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyekdkx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsdjmrs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2brbgsqms.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2glctjfib.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpwqkvp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmwotrw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qebmbkrw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfebraaf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxepbhf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsinoyt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2otpnuwui.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryupngku.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmvoixi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uewvzvqb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfdictn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aasbqkye.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2koctstxm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdebwfq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuysbfa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qwviwleb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trcqxdpv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rforynll.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2idwuiowk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jetejmtk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otzykckp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xibzyiiy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2npjqpdtl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uapbxbix.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2josqywdz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2frfbhldo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvljapn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jipbbpsd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlxlxtg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2glcukmen.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvvuefp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkwfhvq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtsxcxa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhnjchl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2joocjnxl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuavxrb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvmnjpa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2njufswoe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sboftrqt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2snitjjer.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvxiwzw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2leuownhs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ifltuaoj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbsdkux.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkoanya.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvxnqun.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iapsqomx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpblyzn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ougaggwq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2snfrwqxb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfdbohp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtedwol.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtdzfyw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gckwbwuo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqimjbr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krfzmkic.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zouqobjn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rztyusrp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrefgpt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jiczxdtw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdgzirp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hybrizom.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxokgwv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahserqys.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxtzhaa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmsfzit.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crumcfdo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnacjbze.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ercrwapn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mcczexrg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrgjzjo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoqnavc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2egiewdub.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgzelvd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmfwebn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzyyesz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzwumfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aeszfyrd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwltakcd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sxthidtu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vwozpqop.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wvojtiua.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsosmkf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wjucjdlu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqiryzp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwjlaar.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzndnmb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqsubbf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2krnrgtoc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrrpodh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnjqhdr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzflzes.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtoelqj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2avanntdp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlhmajl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dipxlxxi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2prmcfeex.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmqrtrg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pejlabpj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsgrxry.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgjnqfv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrahsryx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgcuzdc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwhbwfa.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qwglmcla.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2msmiukui.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuocerv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjznjunk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghifgjpz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2agggqpuq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lypopsvf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2voavfqrv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxmbmsi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kastjwxo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwhecko.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jkppsfix.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2chvbetad.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wibvqomh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqfdllc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cldslzhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtohtoiy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfupgfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuypjgv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzkihjs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhncdlz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piihedcq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtndatmd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2phuhzect.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvezwrj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcwntio.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvfmjoh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vaicliid.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zsukduok.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajomdcgy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyohahj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlssjms.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvmpndq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdfswnp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2asauyykn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtnuvxk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnupzens.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xojqqcwi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsmnnfd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gougqsll.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwyqktt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyqefdb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrgbota.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuorlnjf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clljvloi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oplpewuw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gatehrfs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzpuwld.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcnsoir.html


<!-- 参考信息 -->