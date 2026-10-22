代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtbmizn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2unctdcaq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2efwkxihm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhzglca.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hihzaykj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaxqmjk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdajlkv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoaffix.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuhvhzv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmplvbqc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvzqftz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmvkvej.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwpkrti.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnxljnt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcghvap.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2trdxqret.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqekfkn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2shijsiaj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lapgqgua.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxruvva.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2urgzmwau.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2baarwifm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpwttga.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bipbbrdb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jndernle.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqzvlzh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbbkaqs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2urdgkzrx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzvaotw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2txftbgoy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqfyvom.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmruwfy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2asoytqci.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbejtxt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2reqaxumv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbliclgj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkhhdiv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfpqpjl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gyepolqr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmrsbbu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2haetyxqk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkkkcnv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqbnxiu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuwpdzs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgjqijg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vperhppf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rsboklax.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddafrsar.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwpksvv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzakqug.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwazjqz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2knwuoqsw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtlkokc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgtzsmc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvwnqbh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpcsfmv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2proasyfv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2skfxhmca.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wobygmrb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhhiwom.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbnqnik.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2diqhmnlw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwsadiy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyfdvmo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2suouhlpp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuyoicf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyohrdn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vrixvapd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2flvzoukh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfbacbh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzhruqg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rxakxwpl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzofyll.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcdngkk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2heoeizff.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpsmgqk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxmwele.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utyxqgiy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcqdtrm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fymxxaco.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlbarax.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsezccdw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oikjpbuf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrnfxot.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dadnlrnw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2beotsncb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ckslhdsu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2umyxlqqs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2itnuexpb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvzmaek.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2inqukoyn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhmmsxn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcikiuo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrvhfxr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnlsjsp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtmuhat.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvxytzy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeevodh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqposbxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgkcbrb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmjaxdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoznhjp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbjcgmw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fxebyaup.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbwktun.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfjhlwk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2haovwbua.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jazyhntn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2onuymgxq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rphzusyj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrbevlu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvakhuaq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqpebrp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwduxnf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwaupbg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vicynfmy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2crqtqofk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjosjuz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nevihlqi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqmcxoo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lzidttht.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ojajivqn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmqrnav.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2efrwtqzs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfogftk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mklxkpes.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmubqjbs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxnygib.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyqskoz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrmmlis.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiqqupq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2okmtytie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2immpyumk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxfvcwn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfewlncj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otadgxdj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkustpzq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xadkwwjm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrltmkw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjezttiy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyoukuc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bwshpdwe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvsfcrq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxucygu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hefchxwh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2imwauaml.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phezodlb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nggdcmwo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2youyemdl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqzxomm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtvakks.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfobqad.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyttlkq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hllhkhkf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udjsdsql.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwbytup.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwkotxp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2evxvnrvg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyqqkff.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yhppgldw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynudzyni.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2owkhckzd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpcxxbz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsnjdiw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khhrnlvr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mebrqpbs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrewknug.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ioersgrg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmnwhow.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nuntfvyl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqajdcwh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mjocwslm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jypwdfia.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2veujhuvf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhckhvy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdawgwe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2otpehoei.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbtpczs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwazxbj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhahfmvm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zybshczb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfzlamm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrkbsqc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuepajy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kehwetfe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kclkoybs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfnbihh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnygsmy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qysjnuju.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gumirnkp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyvrbso.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duhvrxkm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uutltrcn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2risaeglm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qouzvpbf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2levcagsw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpbqxsq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxzbmmi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlhojnz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjigfhev.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmjztwn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqafdwe.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2laysytmd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdexrhcs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2avtvxbvs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2utaasyrb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpzmnef.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlntfha.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hlolljjn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nntvfgvm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chllwhub.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnqwszk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xzetufax.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkdwukp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfokqebh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2weaevarf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fryfplyt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjbpgmb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sshxgcww.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kascoufa.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2oddjgbvj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2saqryyyw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dqffwngf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bugwvhko.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxyzpoq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2etidurlb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcxbyxw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeogcyg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eisdhgye.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nknkqnmw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2whjlpuck.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2khzjctyv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2egfajioc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjnepcp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwhiyru.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzfoglp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvspkjc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeykuhl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2widrbljw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnkkkmx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdrfztx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqgjkuf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yeksfady.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrwtldj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gyafnlbq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iiekppkv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nuskvnfk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjhlowu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtqwnfs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xazyqphk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbxgtnn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bidwgris.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbehgog.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xncfknjb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvcrkhx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaxbast.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rabnfpzm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjigpxep.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2afnkaurc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zlosyoxg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ongtmzrc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbpwctn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brzfcmwf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjvptrz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwxefmd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkcruzf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnzisah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dctvllnu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kkayhsir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snisjxqw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjxocbo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2obiosmqp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgrkzmz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdfwxzh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfzcvor.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhxsjbk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvafpwq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2swgorxdc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzexelpe.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eupvtqis.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgbuzaw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2itaovufn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkybnws.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2snavehzo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2inoijtae.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbamyst.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewskhvjp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxddnpq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsrmdkm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sflefldk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxevlhx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzipdwx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhnmrdh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yznmfbzu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdrcrud.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fakuufws.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkntbcp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcgbgle.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfmbaq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxqhuti.html


<!-- 参考信息 -->