代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yoewvdgj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkdfjva.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgzxraa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpogzljk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbwusbj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgihjcch.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywatozig.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2junozzmp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoyuukt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzewvqu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsajdgp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wfybgxif.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtckkegq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhblxch.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nvooddls.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2obdllpbh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjlmzct.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pewreovs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hipexknr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwhkcsq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxyiisa.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwddcgc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcektjek.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcdoras.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiofdyt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqoivsy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oolatphi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxnrbqa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfuqpgq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2twzvpjxb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dttnmbsx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyeinum.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpisdto.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoybfsq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2behyekvr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpjrlkn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdqcgqn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfoeuyo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjxjzdg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnnuvsz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2osqapjhu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2njetkdbm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nukokjue.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsjhsab.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaaklps.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqajfzok.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzxghjn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzghzkqu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2auiqtbtk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdijewg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tdciaqdq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yztpjxpl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuxxcyt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kzndogfw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbdsxkt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkomiet.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsxovqe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyfwnhy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjscbhe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yvecyuqh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zalibthi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmedgqo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqrqfdg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzipuwu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxffvak.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpschbbd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2egnmyqql.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaujfod.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eutmksnq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wblythqu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmmjheh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdzfhoz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2espfnohp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnfljms.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnhkici.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2elzsngbg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sudymjua.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2htkdjjya.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkhxvzf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjehvkqk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2slpllahb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyjhvmd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2taaommms.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzbeqwm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lssfkfqp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cojewvzu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ylidhjcv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsfsqje.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vrazudlq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bigkqhkd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yahcinya.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzfotem.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aypqmuiz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqztvzc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmbqhlh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cesniasg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jbplgpoy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyghitw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgioxwrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhkftzt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eggwautn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcevsrty.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsclmmt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jawgysry.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiolrvh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjarilj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrsxdfh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zntgrsze.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrwsqkq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbrsjjy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkidwlwj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hthyjyls.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2olsiswmr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uduhnwqm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoobarm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mglkpjow.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlfkyrj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsotafe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2phlwghlf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sxckpqqh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mimdqiqy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rjutamtj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aajbudkg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxzgkkh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jwalpfjg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrslpqg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyzxsjl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cniracgq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2scnvowtk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msijozst.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqhqrcc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iblopdcd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oqioyebe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwctdve.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmcqqof.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jolmjzid.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsxqyoe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbmkbqd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnbtimd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2srlwlyrg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrqproo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eqniieqk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czggiufy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlfcgal.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwbhcob.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcmrohu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmuelrv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwytdit.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvhxmwo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zsffydxh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdwxgzy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iznsufaf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfzxcoh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqeokrd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwfwapj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fpofgfgh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egqoukbu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eybjfslv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxulxiy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ziscmrge.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxvixqk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnsozky.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzqzuxz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htdtwsia.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcvxzzz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdihqdrx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnqfggs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdorepr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoksawlc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uuravkgq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pujvlzfo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkurpoc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2niuovdta.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoaxxxa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmkvsjc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tkluuyby.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yashcnpq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uznaigko.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnlukwh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2buhklmnr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fppkyohe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmbstsk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oddsqzcs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fohsmjwm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vaceduma.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxbpcog.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhzsiqx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fytpyycf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgdkywa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2krjwecda.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyspxkl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luilpcpz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbyljox.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pblrcfcz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aiifbhxl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmmclcg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2epzzfixk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjrlrkt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnmdggx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxteizz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cddffoeg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhwhvxm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mieolxhh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcmcota.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ycllxuzt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwlmkwh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbaorql.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfzmylp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjokosd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2arzfyurw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uuftlvvz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgkqqqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwviffa.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnervgm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evxmxwaf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qexmxgei.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mquggoor.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzjizmm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjewwyo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqqmihs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rswycbos.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfgulxj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vixdvbyi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iqouugbn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2olipbbka.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tckplbhk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcunpjx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcyfynn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lmowqqtv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsvxrab.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvbyfge.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfknvnp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvbrarb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cyftxcxg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytezgpuf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkvqimk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yqglvmol.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vkneazaw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxyokun.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iasuycbv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pvczeswd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmoxros.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emrzhzgn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rccwbvgb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2praqwdey.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwjvfrf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pcocgqdd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsxjpcy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqkxzyx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtudduj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrkoary.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ethbjndc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbwnwdo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zecwgvao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2unwtrpzh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iowewrtj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sosbynrn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oggimwaw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmqvocg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xahezkwk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkpnemw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaovzyj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puslufoo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jnujtvwz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2surbavcu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ffysznwy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmpflyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpfepqg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vomyupmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpnygxu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfxzvxh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiqotck.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2essuiiux.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcnrwms.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvnvvjs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2utypsess.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bakfojwm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gldwsytx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2prkcqwvs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2csdxgoyr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2roxivomv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2raszqdwc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xrklqvol.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmynrrh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2puyaeuld.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdlzpsv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlmqhmn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2resepcmo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvnxvrz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2eopklqkg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uppgvdiy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlkkzup.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2luasikql.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgjrspe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hahhmotb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfjjkng.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxyjldp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nmawqsug.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzdnipg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pnobqwss.html


<!-- 参考信息 -->