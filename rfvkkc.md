代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2diqekdfl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvjqvbx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlugxmo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vugttyut.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzrhknf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltvvmlb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcjyrut.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oklrhitm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qulnwvhf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2abncbaqz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2splcspej.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rryfmkbu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjkwbqn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyakexa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzokbzmf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnebhkw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bemedyss.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyvivrr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcuimhb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aerbbdct.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrowcsk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwwwydx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvwggtm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2reepdbqa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmcmxex.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vmubdnzb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mptzuiki.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmfayyw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwedvzy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcuhnjr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnaxkxe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgktcqio.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xudmdaai.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbawnki.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhpzkzu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdxmnnm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyexdkn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lclgsivh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gckjixpi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiduotwr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnsniqg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uruiaiqx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ojheojkv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2znxfyfpu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2unqzczoj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rizwvpbs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuwewue.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fahjlcgf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcjswhg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2eypcppdv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzcdztx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2humzvuit.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxnbpbv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qhirsabu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrsbwpw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjcglns.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omiwjork.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaornky.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvsqtdi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tprsoygc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2afqekkhn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzkypza.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmnqnyl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gugqdnaz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tacrqsqr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeybwjd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwhmopj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2unqrygir.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hisdqbhq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaplocx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwqlzek.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2spksafjp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqbazkv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rciqdaop.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhnraug.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irjjhrrx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2steebczy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmksitl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2unvubjak.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mopasafc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wmimlotr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfycyjbl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rsumansl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zidofrij.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bffqlmxn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kbffitvo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzlmljj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ithbxakz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdgprjd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yoijvjrv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olqohoqn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hbazlzbf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwmtbcl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkqudub.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtjrprl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2giuyyngr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdsbeis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxmhimg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiojaji.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bnldllbm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpgoxwv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2durkmclv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmigkwe.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kywhzvmo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ynforrfi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2occlgznv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpnpnez.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzuagzc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdftvzmd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaxtxmm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzdjarq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svsaxvcc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2utkttwxn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsvlvwf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zypjmhft.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2talkimnd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ayperzmm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ztciufdv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xurtavud.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rwblepio.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qswvrouo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wffxxjwo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgvknts.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiphoqqr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwfvkxz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxhovqb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzqxojy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wimcohqd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpvmfvl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yimjzawc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aacrtrri.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pupsntit.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sshkhpdv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xabewtjo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2doqczcen.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbzorxo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jojbgtov.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2liiyqteu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omtaxgrj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sizhsxrg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwbumsg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkwncqo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeclmjv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqebzxww.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avfchxzj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2arenmcpl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ellrrtsv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlopljcz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aigrsxnm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkgdvjt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwnhtpa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlkarey.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjciuiie.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyokzmp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2miepcsux.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpcwqtw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwetmap.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwnjfoi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pytuuouc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uebruvsq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgmczco.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuowhyg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpkpvbz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqdtfvf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2posczysy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wbttsxcj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfwttic.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhfwqxf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcoafvq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqtbteb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jicqslfx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvkvphz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvibegrk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyvntkg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hddjgfez.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxiswvp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpvztlb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsbrcxc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yitnluya.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nyijobcm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2orglnymn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mjruwbmr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aaumetjt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvdtmlk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtnovvm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrabfnz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzazlvco.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irvukvgr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgmhsyg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqaqknw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkeoujl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yygyqjva.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2stpsilyn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yaykhasq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2suixfjzn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2porfqmbv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaivolt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvippas.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vusuzlsb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2okgkjvwm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oypjtrni.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkbqzsa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vixmoxqf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzaoeih.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2taurhmlq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtmeoyy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2stkoslkg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwehpsl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcrbmoy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nisfklnb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njcxuyoz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hihcbvxl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdputfa.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhgdba.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nceinfqa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoueyrh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2izwsobgu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2womkquty.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fxciitol.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnnvtph.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bzthfbec.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2txsoiqkk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2atazlimw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2edhjihqu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsjqdyo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iocvorcj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cpumhvrp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjylepy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yccdpyip.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2alttohoo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2azqunknu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2okrvnwlq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xuegporp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhgiidu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2epcgjrtx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvcshxb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2slgkiroe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wggksbpm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkrglhd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhditofb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvfrbln.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrdebjh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfndmvs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfqkpsy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcryblys.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfdkpoz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvtlluc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsiuttx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjwyhdl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqlfjvj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agnhrdlz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvkdubb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtbbvff.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzrwfdr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqidboc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpalgwv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjtclzp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkvcrpq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2viluntbv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sddoxdkq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2waocurtg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xhztgsgb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lvippslc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnbmohj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sllrohos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tztoiork.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bidjenjc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ezddcjzy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvaqrio.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvextto.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkofainj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjybbsmm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbflpmd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2slnmigre.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2snqvyzrx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnfswci.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmukohq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2llhyxqgj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxzdkyw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olsxeqwf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uqesnbee.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2klhundlp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wivhaoss.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cueornrl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nzozbanf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xdueldwq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfavnwdf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwnggvu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkoaima.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmnxcbp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhercllr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnvzhos.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2akrbjshy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mqadzhin.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qanpzqhj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuzhagy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2irewnwqd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhjnzth.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzrynxf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeetmla.html


<!-- 参考信息 -->