代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxfrmqa.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdljijuu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjhuqwe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfkuamj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgrybyh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkkhenq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfchbag.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2alegrmkk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmosupie.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqzowkq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsrgund.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsgveel.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eildrrfh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxphzwg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dzngjpaw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwcbwgt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyhymbw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzneoptw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mgafvyax.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2swqffbkt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xurefyek.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dihznafe.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrufyah.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxphyden.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxalwjyy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2klucnqzy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjpklvf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2axfyemeg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uigntzzr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlfjxew.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2utoinqtg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkklvwcl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlghxkh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjnobym.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2phugclet.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mgccmcqc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2firhbwjz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfoqout.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwrhmuo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lldajswa.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnypool.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dqammdhu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ytivrmyz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnhupgq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxzatkr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmdolhf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtbabic.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvijxre.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsabsjb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzierfaj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yduzxduf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aejdyugb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2trecsdot.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dyehmlzz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyiibzv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpdvvah.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbcyhsp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmlimdi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgshqhke.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mstdujib.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2esfxttkq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rniaabju.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jegkdchk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2doajwlaj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gckwbzkl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wngxdjqj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqyobdh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tccodtsk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gksvrkpf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pesuvwev.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydphsizs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcajpain.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2invccrkr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2woxyosdn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwifthh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itecqlmv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzxxyzj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgxgzpi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvgyiwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2assffhiz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2igmybpgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieasbgub.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdxpgyx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqvloxu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2axmjxjyd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2catvdgsc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfdsvri.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxanoxu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbqjfjt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2utwuvzmo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeorcrah.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoxciut.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjvofee.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrngakm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qapmurns.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hilglboz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2prfjkrtt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdqoxxu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ierjkpam.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoqdhpf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sppavexu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcidkzv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxqestr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hfycpnwm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiznaje.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sghhpulg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgztehow.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wajvskxt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cneqluzo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmbmcnj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2anjqstvg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2chtksjcf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtesxlg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcpzplj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhqgoqy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tafemcmw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oidvrwkz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhccakb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amiijqkd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2okqmthok.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2swbjbffa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dekqpcki.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nimylgit.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2whsszrms.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tibshrzl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrauwti.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjklqbfx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcvydvq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfknamq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tprzxkvo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysusjhqo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwufmkkv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uttvvbiu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxgupps.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otwttatu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqclleg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoydkter.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2raurfjmh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2srzbdcnt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2idkvfkzf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvriewc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2isvktebb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzapcwq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkykmuz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmdwphu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kemeqrva.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhnmhmw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2htfbkock.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqeruip.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2axpyovcs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbapans.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsbrxww.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lrghqvev.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoqsvnz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdscfzu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2igyzaeev.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2htutblvf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dulsnqor.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwcmakn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2venthbvf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2peznyuff.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkkggzh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjkgbpu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwcwvld.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjdvzxc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odhjvnhi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2flhivgse.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlbcuhx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkdcbga.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2npjnesqx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqhdvmj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxylncje.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkjorxa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2snyqdwdz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ljketndy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcwrelp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlwdceq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjtxthf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lapbqvia.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnyyywh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxajipdh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2asfniimx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfrwpbi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzrboem.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtylprj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2guziaavn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adjghppo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2myxgfuaz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcmwwyv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdynsfpk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akjgqrmu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxjvncp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxjyddq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klljcqtm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpjxfls.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcdepmw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jxojwxki.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxyeysq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2byqmugnk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kwifbacj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2udpqntuc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rawnrwdx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdzpedq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2epyknlhn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kywtpfvr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyctcmc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bufxtnkr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrfwjkv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zltnueeg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npzkmmbh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nfztdpdd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2attvvfda.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlwcvis.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dyztouhn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocafxivr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdlzufc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqxvrow.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlngrosh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2juckdvmx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2myainivf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2avacigpb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnhxvzx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvacyayj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2laengfoz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhkixnz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2moovcjkj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2truswmrc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhxupbh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuspqhi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2opwdmmtm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xncjcjwx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcsztzw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxnujrs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2alxdegxr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aernsqou.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjojcscj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dedmtdhd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2weobgmku.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2womxgkms.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sipwnonf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbhpoik.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2syxkwxgn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkeulqn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vslofpxe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgbxtet.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2guksdwld.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2njgkxoxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhwpimj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zehcmsqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkbjjph.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyawduy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wacdurzu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avkzvmzz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmghlyr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyqcojs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlyfihk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieswpoze.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bscnvfdl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fefowfti.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgatmgo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvmoiva.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdnisak.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tkebjzhn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gwclxwpu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2evnqkozn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kaygctpw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqtohsf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vahzeubp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyzrxnq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rajyhlbz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhtyosg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbluwev.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiavbpw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpykfcy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lywhujym.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puxwfjdk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxjzqgj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjefadk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkgrkih.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xukxxdbk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2onbszsch.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2akdocavg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiswzet.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwfcwck.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaldnyon.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmwgiqt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2krkkrnjs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrqsujn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2esuvaase.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbtkkid.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdpvjyq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2josqysok.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiunutr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfefdvv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrslavip.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pveixnbj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmccpkj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsmvqdd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bylnlaxo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uydaakjr.html


<!-- 参考信息 -->