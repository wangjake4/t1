代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmilbyo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mohwjkjg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2taqikyxu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjecsuo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kucwpgma.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kudjomsq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2skffbnoj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzbommo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxnvpry.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2juzwkhnw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2edtolnpo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oafwoudr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2asorwpof.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhadxshy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqbxidc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ikchxhzy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmwkpjn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkfkuiu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgngcst.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sezelupr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcwlojw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cekheqen.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xttbrpoh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjbukgp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aoapzyub.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aufxnonw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tdakdxbz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwzqftl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aoubxosy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xzktnybn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcqposk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkdogqb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zglrhrdp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fymxhmin.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ypywktht.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sapoerwy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xyojyakt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfjvazx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvmntin.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzghapf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shvzsces.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvxzaql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dweogchb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzngjqx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlpvhrn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hyobhfkg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2elgsktug.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlphhiv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmryvndl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfxcdxz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgumjgj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhkctiy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkcbftb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2klincvtb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaallnf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxxgxeh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoglppo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2prxfqhda.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ncihlsxn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqiosuq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjpxcpc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoyaakh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uczfapaj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeamiax.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2exbupvgn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbftkvy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwvdvsx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fubmwcuy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jhseayeq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfhezlk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoncbtyv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzxysvl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2djdrvrms.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdkbtjv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiyqpvf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeppmqu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhbrivu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsyuyvi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bszabxns.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvdsyca.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrvwcvg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vauuyejf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kykrewhs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2riphzjsv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yguibnsq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfforfrj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnqofyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grbjgrys.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqzciks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnzjgiw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2brilxici.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kdullxkm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhwnyzc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uiksnlwh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dndtnqpj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsanmib.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nefxscuw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rczhbvoq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfzfbim.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2shihivcj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrkvynx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtaoibt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhbuklp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlntxnw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbzqckl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2exnpfngv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxjfifh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pouwnwlz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwmltwr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2asmlmjnj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2avknnnuc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjazbse.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2khbpanah.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tewkuvrs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoikwyn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iacazolk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtxzfsb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dduhtody.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zpndyzth.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqdwvvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkjcodl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mhibenfv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxuijml.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpudckek.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdcogst.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2npnonrrf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2woiaprdt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgalfyzm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owlvomxs.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2crpwytlk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjpcuij.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgyvhiv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxfvgom.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukippltq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lilypvlv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzycgmr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbmmeol.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtewiwiq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mruodnap.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgibgdss.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqgegsa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxcewzh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnermjdj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jonzexei.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuasmtss.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vassskyx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmwhhgj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwlvajv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvgmpqq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2urtguzja.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxqfyww.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2verqpnbk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oyywkndk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2voisptae.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahilwstr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjzhxmq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moysvgos.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2romlacey.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrcicoq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrebwhm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzqjevq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhnzbyv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gqowctan.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mxovrqwq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uscdnrap.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2udtdnmhi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvydbjg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyoykuk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxomelt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2odgqjslu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ntacrcma.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2waqbeayx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvoiavv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpatbdd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmexjns.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mamhkftz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoouzze.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpalfjx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjokvmge.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlncpvp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tyngjsfq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2brkgmxjw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vtppxyen.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqisweb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2frsqskal.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2umqiwbvh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmxhvzh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2siuwsdxi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkkpomx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2clgmykuc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkikeog.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvebkxjz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwuxnea.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdjotui.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sembcdwb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzxxzjv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxhxxja.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmoccpx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkhrdxx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyasygk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdlvjqv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqulxfx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwnhcjn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2brugjysw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jllempfs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2avciswwy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfcnxxq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2krwwixev.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxhxirn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsfshmn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2htcacgsm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eujvcmfx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2itmefuid.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxmcbrz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ogibckmw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnflsah.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgfkuvl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdhhtov.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wztbolwe.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvwonzg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2skcpxuyu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdacyiy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2keixnyel.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcldshcx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyocqio.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwbgmnc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmjvnhh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrbonaz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgbuvof.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzjwfko.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgadekv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmivzkf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqoifny.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmnszfk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2givsikpv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2osiumgrv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2avpiculk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnsriko.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmzkodf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2whaatuqo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2axfowftt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoqxlhz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbmwzqd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnxvpqt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2euxijnnn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dldcqvtk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwqzeau.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hctrdfqz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhbjmee.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhjptsn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vijbdoyv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrcjzyo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xeowzymk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zsomfvgj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgiudis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlzxmlu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwnemgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmqkwvy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2syascvmf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2shmyjkgh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtquowmp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvspsjj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2srueuvpw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiledng.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlfvdpi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnkwoxo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2stjimole.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cvghkfva.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuaqtuv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2seezdmjc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzyunov.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2spekykqt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvncmgp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqvwyew.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gawulrdj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeqzlio.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tnayaout.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gretcanz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwecpno.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmjgdjx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ashvspeh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hearbpov.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcavypl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdmkfjk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbjmflw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxteobz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvahqto.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyingvk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzenorp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrdpqva.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhgiyoc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpozevx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uephitdc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjsazdo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gittyvrl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpixpcst.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnjoldt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfltefe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2crzodqfh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyamlpr.html


<!-- 参考信息 -->