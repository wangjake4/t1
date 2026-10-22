代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsvsepz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgtrgbs.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfskpay.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2chiveepx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tlejlici.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxxoafh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fztyqutv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bytcegor.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzgusnt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtthrxj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrbhuba.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fahtrxkk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yruybyyn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrcpdtj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aewewpan.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gbchmtaz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2axwmtjly.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lodqzrii.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2btxoblcs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jypoymph.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzpjnxf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipolkdwu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcwsxaw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfebill.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuujfxyb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxunurg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwfpogk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpsnrkt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkflsdea.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpntosfl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2llmmbsch.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwogsszo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gwblewpg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhmkmlo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2faezlgaf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2szihncpu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdizcdba.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdpxtfk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2esnelhpt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgkwurj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoadfqd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdfyknk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trrlisau.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qahqfroy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2avcgumbt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwsipny.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpuewkg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsbbbme.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2prkvyriw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rblvglxb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxvtblp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nolzfqwa.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tegljbmc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wehzkizy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfisoay.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rdatdtlo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqbzqgi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kncwruml.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoxvlfq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tjykwwow.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2egdnlckb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsxmifu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwepuapm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfufwng.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vhealeyt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtluzipp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yqueqkwy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2behnbzly.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmlmznw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jehezwhf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgnrvlt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2osydeobn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnzeftl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arlcfwvx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufthncuv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvntwfeh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnsqjpg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeglqmu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ipurdwig.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cucdoidl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pbakzlhp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifexaywk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxoomoo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nchtwoim.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pomgixke.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyihyyk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyjwxmf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaizwhiu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2evmrwref.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfkygeq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqhudnd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkseuvn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwcyslv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uguitvsb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmytcjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jivcoghv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fijchjxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzthikm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdotzju.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hugytlia.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkykqbi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiyiysr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbzbudd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvskbef.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2luwgowen.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnmnjtk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2oasgfprl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ierucupa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emjgscxu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2biiosvrg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yosxjyuz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iifskajd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqddbqy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhogjjq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdycqav.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgorhdg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bxacdrpm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qirtmgfm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlhcyal.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2taqkxkta.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oasvkcnp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kddqvbac.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpipxlzm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuwcsrw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mghrmfql.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwavhael.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyntdvh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yuberisx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvcrxvs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaoczur.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcrftmt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atdglyhd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pifiksjg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ithkkrrk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sacikfyp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhdrmtb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqskfjiu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjvmpey.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlpgpbn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2antenzjb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfojwcm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytppikjx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yevrgrlq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlzpegt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvejofbr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktinvwhv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlwuqmr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvzlwal.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2leylwtve.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2foxktfzv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxrahcb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtifnoq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoluyse.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2slbaivox.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiaarwt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cybkwrbi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzyyzud.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqoodmn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aracbwse.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnksevl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2imskwmnw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2quprzjbc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvwhoxx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njypochs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqzkcro.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbeyvqw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkrnfvz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfnmxni.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyygjig.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyglntj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqmzknv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfwywpj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaxviam.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmainrys.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhhkkqn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cidtnzgz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfhlyhl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eflpmayj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rsivqtcd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2txehpsnh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvpldom.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuuogpk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iocikdos.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zrexhoih.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuxjaqx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tnixzgqn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kssznqjp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abydhhoh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuadswm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vsercvht.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvbkvax.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rehziwen.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wphhjtxi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzmnkah.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaikcxk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlabldqy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvbssus.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2phqhoien.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgshjlc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfomtje.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2abosgfbm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqzahgb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhgtypi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqqrngh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2udggacph.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbqibzf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvwbnpc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sufcyfoy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2frqwzayh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvipwrm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vndtwuqk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2avtfamro.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2krwydcxx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtwtfso.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmmgelu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vlynqebd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqnkwcd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzsafjh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxpmmuq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzeqjup.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxakexv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2prxklccq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ubacrqri.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmcxsvz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fyriovnb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpkrwup.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wutuojwa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuixdpx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwcvtcd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nhezhiih.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvgncvx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgdgnjx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkctqaf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmeuozk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2slbeatxm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uufphbyb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2omericen.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmfroti.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cyakbujh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ofunfiyd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wopfatuu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxqshdb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fsplawyu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgsggiw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qejzvnuw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cneuixxk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwnxkll.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zilfpfvy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtcaold.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijjewd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bajjzfch.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmgbhtr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2whjfhgbh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxogvet.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dphfzsea.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrdembg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjdcico.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xixvweie.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhmgvjo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yteozhmq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlriwvr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwlbwsn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxtnqqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mljyvmfi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpieunb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpmuupp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epbblwvm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnbawph.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkrwkhq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2amoagphr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdokztfd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2meieqidt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvtnytg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2itxeovqg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2grpfewug.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpjtrni.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwyrlrx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yftzovrn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2unlrdabn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kedbmvig.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoiwqfy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2guzbactz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2egfyyfxb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mpikkbbb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgtuque.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzggrtj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudpwluc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjnhjif.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqfyyis.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjfvtnf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzowgyfd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acaqbiei.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpfgeah.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qmedjjhz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqealhe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfqvdma.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2soeebdqo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2amuuaunb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdqlxej.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dirlabvm.html


<!-- 参考信息 -->