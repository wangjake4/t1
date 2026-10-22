代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuptvwb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yxomcskx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gzejrevy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wkekwwbr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwetfis.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjzpisx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgobfgs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkunwfj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvarpxj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cziuhzdp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkjesnl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkicrhe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzerdiro.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2trptalik.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhdgkbf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eggqowwz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mskwmgfl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzcqxym.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2luaebqes.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nvauidtn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcuijfc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjqygaa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zenjliet.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrlbcbe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwmhypi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrseidi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2svjavnfg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2awecfsxl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qentloil.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtmmghd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2htrhcyep.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtkicyh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkvakpc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjumsndx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2covyszqi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qolnkltg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzgavte.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2axesnwte.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wglukpsx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmsklhg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cldkgseq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjvfxod.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rormghww.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zninsswo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anjwnaqp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwtmoeq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qfljyekk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yxayteim.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgpaufy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fewvjpoo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiwspia.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wiliuemj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtuxkjn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uictrrbm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbdwgxw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cadthcgi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kcixmwub.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfihkpun.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnjymur.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuqmugw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rifbqley.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgzxjbh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2swbevpre.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoolksp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvkycfz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoqktru.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwwmjbp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlttjgx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atieqgqx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgntphi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqicqyqt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhajsdw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pftummrs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrfyqrq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwgaaou.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cedyhvdc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2scklpxye.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2trgfgjcn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiwswhw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2onrobsjp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhjtbdv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sqggjxnw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atojdzyr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxshcwg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2niugddyv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iftorbiu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfrdgtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bubogmpn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2drxolioi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upsibtpw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxgkekb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eteqtzjb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2earapboc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlxsctb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2swbnrwya.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpdargd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpdgkgs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjwxvnm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xflocsrn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2thtvtpym.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmiwrqv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmkdqpn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ognkxgtl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysywwrlc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqkbjkt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqqmwxc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwcbxxe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2opeyrnfz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfafdpfi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bldujhnh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2duhgqant.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpihonn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2arzntlsa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnepeiem.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhmlrgs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgvurdi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpxfrdm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbdpqpy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmnppng.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ljilnsmc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jujivvos.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vquwusoo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvkxlik.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdxzfkv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2attgcoow.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbriierc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhwlisp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtecbio.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfmqxnz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzoayrs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqhodwt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmbujaf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpqhwri.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnogoffu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqsyjhr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wtypgtoy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsxdelp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdvnwju.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiromfw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qrapafiy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdohbtsu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sddsebwm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgxposp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2odkdkiym.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bszeoyek.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyrplso.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjieolr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cyasurqe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ektiefpb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lwclivlj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2htowfzsx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwghubt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2apxzwntu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2crwasefq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxmpjyu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upzrnypx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zupcndnf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hruvudib.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huczlzbl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2awjqwyws.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kicaoiyd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2joxjluwh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtuyopy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zjofjifc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzeawxx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmvsyyx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqxtzwp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jttmreef.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxiofit.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xumnnmae.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2unntetgp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzhzdfd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfxtwuh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzirtvm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdvmdse.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nnknbwfc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxsludu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kekovefh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqtvnxr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itfciocy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkvipgs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pfajebcz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2orcmspkh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kwszkerf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xnssaryw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxbuwxl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2toxtrnie.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfsbxyw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2osksbrbq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pttsvifp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrxkuid.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2spkqaoni.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jkywcpsu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aueuvbqf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etvteril.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrjmvsc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcfhohh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwaugak.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxkezxq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rfozaxtm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2prbngbst.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpggiotb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grgemzjg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhiqwtk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkpheps.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwtbsdb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gveqtnfu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2owmycwyb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwqjgrl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gionujfa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgjdedg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdbtxxv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2laanjzof.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxzaoov.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlqpyih.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxqimeg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqkercr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jekdnyns.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ouioklnh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbpwflw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hkykxrry.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lijkzwhb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynluhvbu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2toqxfnmv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2azmhjtit.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkwufev.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pymjeqcq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhtdjbe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxqkfxf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2txbqxmbb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfanmavc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2utdsphmu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbfbvrl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlooytg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2naaakzwf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qleylfxo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbwaguw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gwivlxmr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhourrd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqmqqyi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wuibrwwn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvdzvum.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrgnupb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmljswbd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2omlihjkn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyznhoh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrgxvim.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dulfiqii.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kgppgjxr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2phkdswaj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pjimqrmd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlgbxee.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjlhhvt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rbneivmp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyekodu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqoqncm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2brqjvlvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuifgig.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkribexl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gplwhovx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slcnyjal.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfpbpha.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuemoag.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgevpjyd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuvhipd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhxaljo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qescztmo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhddswy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsefrgeo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymazhfua.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mheeiyvb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpwbimk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2egmumplv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xnudqgzs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tajaqrji.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vslcwksy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gomgivoj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oliyafxn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yewwheoi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twpxegsk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2emolqeig.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2djwrlgcz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrovjfw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrioeyg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2npdspdlo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbnkpco.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfqsyht.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oygfesfg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfagqllk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kalykcol.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2enkfrybp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnealuy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwkayfx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kujpzjub.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2meqrwzwp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrtcxlf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdopfnb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xfywoeyw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tylcwudd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgttndd.html


<!-- 参考信息 -->