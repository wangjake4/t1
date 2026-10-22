代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2evrhztcy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlljqge.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2anxqgmbx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rykpvygo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkauzdq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpogllm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjhztca.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tokfclqj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsdudzr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjclxpha.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaxcwyp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zffjrucx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiyogka.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtqdkbr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvgnjcx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzowisf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhtgjfz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2iryhexab.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcocqfpd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2adwdprgu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tycfavhk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rycozgax.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqajtxn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2syjqeugf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jixmrspv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaosrbi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iirebhuk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoufptk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzalnfq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2evpppooo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgrtprt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcndtqi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzhhbsu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwufzydv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pdedtsea.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqsorwo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaugtff.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmoysyj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jslyosno.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvdasly.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjqjhkg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lvozclgp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrbvecu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgujfhfq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywefizzd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eruioreb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2icsueehw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuymerrz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vedkdrtr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uayhozbm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kiadihbc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2arqnecrc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlfwbwu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uybwgbfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2skduuieu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2svxrqxof.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyeirgf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhhmpiw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uonwkgfu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2umzxwmxh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdbusvt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aaetwckz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgntwupy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lddkgqtj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2paajasci.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dgysqtfp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrzvqab.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2duzifvou.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjdshdp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yagqrtkg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lwukliqp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqlnmrg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uusmpvbd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hclenrrd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdpmqvx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tthoecsa.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbjvlbw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxshujnr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjwcfsj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsnbwpu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjufjblr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lypkmbgm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoppoir.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nslpbnbn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnstshz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slvidegl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsmyudq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwuppdl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2navxdsho.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgrzzdt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohofdrcv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqucugyu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2brofgzlv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wevgshjc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jifynkkv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nogqfvxw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eyujbpez.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2riswdrqh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2odyfyqvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuoxavl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zklwacip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnbsahl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sroengcy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsfcqla.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmdntya.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qmarlfjg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sifjgiym.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otwphypk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dddwwfyb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfkurta.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzbnivs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2degybgxk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umtxoriv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wafhgngp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prjrahsq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imksmuar.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnoiaby.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xlofdqaz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kuovgvqc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeqadfc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rztcncck.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2flzqopdw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sktwvtkd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fovylrup.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvffvcd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2irycyjcf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lezgnmdx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkjrhum.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgecrwp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbbhzwu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tveiglaz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2odzrkxwb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmutwikv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dpewlfel.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkiehxh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cebtwdeq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycawzoph.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyljzde.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbflmhol.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnefyqc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcuaitf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2slyfeefy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvshnyh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gosrwlhd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grloyesf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qygrbzdn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsfxawq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xodopqst.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpcyzat.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxwnvda.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nafshsyw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qexwaobq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbmziif.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnqyyaj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxlesku.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjdnqxi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcekmyzu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyitukwz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgkyhxi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2smwesddv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2avoohune.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtfcjoz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgobbce.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lamwwtuq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hytiqqym.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vksqicwo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlqjbdp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzwcxee.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjedyuab.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2efrkrloh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqstrvpa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdctamy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mjktlhae.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmloehg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qudceuve.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwymdrw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfssgkt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrtpkbh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2djwogcaq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxskptpd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbijbxz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jivxlubj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeqchub.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iostxqlf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2itptwxvd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fywyssjf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsrbpzd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdkgcqa.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2takllohp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfxsfxn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lphnkuav.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgottgbg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mzorffuu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jjadvziv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjzxciy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsfsvgq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pthhlryk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xijickma.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtfzxdm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfekrbrc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkihxkox.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsvxvla.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjyolhp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzklong.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ukekdtii.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xpknswrk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqkxovt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjykaze.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jlexrxyp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeqimmi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yebummou.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsfcyux.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2flsjdnla.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isrrybqw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkclvhd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jeokmrad.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nzszxyfi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsrvbru.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uemxzdgr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yralsoji.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nqojzhuu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlhtfcz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcgifiy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ieamqfzr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rodbjdwh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxsjemi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxbclao.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcatskc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rrccfmen.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyilbxr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwnvtpy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2luhdyinn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwbmrga.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uihspnyq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sphglbyh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxdwsmp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qirhqcoq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kinztufn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xapvkbwg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2syzduqaq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrdaoja.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynolcarc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrzakzn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpucwsc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rkplegwp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpidzbs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbxjpti.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2amwjnzoc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjrvsgj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzcvxcp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkojrcn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kpipxnzr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfrnmde.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tselhgce.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2clxwyfjf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlfqssf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2meldmvff.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgzxujv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2argltddb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2soyryzls.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvoecvg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjaxzjl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dcidsxgj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jvppcjeh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdztubk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsclkly.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uhojeetk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxqwycu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvpowef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sebbtvfh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzqoute.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yngnfmio.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdvzfzb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nigqmmxe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2adejrbbl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2udbiuofz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfecutqm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtnvkah.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2weayviek.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwkudah.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2upslxzka.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzceylwf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cgswvisy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2okkmjhzk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2koogljjn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwwfvet.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2whpgklbv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2riyjrotr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2azunwxno.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vafhuugn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmbdxfh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btligwkg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qerannlp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxlvlcf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfegsvn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2doporrid.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtribnlu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpaedjy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rduqssuh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuiwsrn.html


<!-- 参考信息 -->