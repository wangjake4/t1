代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aajjmifa.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zsblslou.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkiieuw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoziqdi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrfssci.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmqqlyc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoksqth.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mrisfkjn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrzesse.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2augzbyyh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2keinwumz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfldodfo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgpipqg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2saxntwjw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnynwmdl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2irizkbxn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmkgbvv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqoplvw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gozenirh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwwfzmo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrwxsem.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2utyfxfmm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fmusamzv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqikhwzq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ekembpam.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2keqrknkc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iixrtxzt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftogmzsd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdfytgu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuxwrvw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbdalce.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqrmvpr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuchuuu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ritridoe.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bscrloju.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2luaamlda.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxwozoo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuxgeey.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqrfjah.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2afooifqx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rztadlil.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gptxbshp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtydfwnp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhnubvk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oigxfkfz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdpmyet.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aigfpjou.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bentrqak.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcvtwvu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmmfbwu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2skshmyrq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fgokzeyb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrmxvnr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnqkkfh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoowzsy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwnjdtl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkhxorv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2aukonthl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fcajbaje.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxlgkvq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbgtdxc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2crtdnpdv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2loovqzyr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2abxfcmin.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bclqfpdi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2judvjaro.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaqrwfk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtjjyoz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxaxobi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaidpsb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2leqaiqoe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brfybdwc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rzclxuln.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clmpaukt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgidlpi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogussuhu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvwponf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgakpqx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adjyydwt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ougitzhl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdehccta.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nspramye.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfrwrlx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2opbfpqoi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2usiqcqud.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdqkdfo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2edpltamm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xotgomea.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhzjrrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdfnohm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfwfjxi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2btoannae.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2grkivfkc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2goudtrll.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtirwfov.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jclvyawd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwtulyv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aavyhdsw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqsmcik.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxqcbyq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cswiykpb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrfvyui.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bodiafmd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwkayim.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhdekqo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qivdsgdn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sclxjtmp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcuynmp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2orccqtrl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzjwuez.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmxqvea.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2koyxwzcg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tgprfosf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsxccsu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkiqwdl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvykoohx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2owpunsjz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knwaiukb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqktcumy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfpdumt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uimxnoqr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyjvkym.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vygwdifd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evwcdpdk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbcjene.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjxkkdx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tccwvqet.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjczruy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaaimem.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkgodyq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdubwznf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xewhmqid.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2whkdiamh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgzfvtj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2obixgdlj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrizgnv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egrxhyfd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhnqjnk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zszrhgxm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvksvnt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdsbhsz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkmcvuq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izhjdmyx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvaxafn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkecewxq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkybapsh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdpekim.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ksltncvb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vciuarbo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pqauytpe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2azohizwu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwemcku.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjobfyo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjbckdr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tphycqvy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sprccyzu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wppmacca.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwgazkr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvvsgib.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnpfzlf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnsmzds.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2puhcbgya.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwictey.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2syhrmbwj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2svhhzouf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bjojkwwc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsobdfj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnddguxu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnjvmbn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wvecdufp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jetvweub.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2novydtld.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gutsvnio.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmtbyad.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2idjbhowi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvplqsp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqrjrze.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzmlibj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eihisdkr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2felefbgl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhthbhq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjzforv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2upaovlyw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoxozeq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnlxgus.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoiowak.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xilxkitc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2awbiycvz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cphvmpqc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxdwvbk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lluvwmmw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ongahwds.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2thnqsncf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aezqyupp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acqiyhet.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bwegxqpe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzszyal.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjssddaj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nesbjvwc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yompqnrw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ueditbcx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfodxhgs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrledmb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlcdoau.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkkjebg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2leqfveng.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjdqwxg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyfqlxe.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaotyee.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvbjcnp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wejezotj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2edwvipnk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hefndtfz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuikqpb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2adktanak.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qlremame.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2flsxqwuz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkgnyqb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvfutwr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xdonisvl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyyqaog.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxgubcv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wehxrufv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eysstjvt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jqezcrus.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jglvochb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lwltmkrl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmizcqky.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2spnaawik.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmuujye.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2buvablag.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wathgxxf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2panflviy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtywshv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dkinlpxg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ititwted.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwxciex.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2juzixrno.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnlaejq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mndxythm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhpwvyx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2daxuejwe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oihrfnlw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2envhgymc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcqepvh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lezdpcso.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zomuktrg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxmnxpg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjfyzqo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nuolyfqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jynovrvr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jcliagvj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfcpilz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xabwqzix.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2szjmbwfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxqhmqf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnxgdyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzobppfr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yudmioce.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyvbxba.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgglftp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2usbqmsfv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzivmaf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2epovjusd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kztkpska.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sbonwzvz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2peuybxjy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2krnghhdh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtebuxss.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2htijalih.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wdexwgto.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2padfobtl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wskkstmk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hosfmita.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzkbbfy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvrmuck.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2amiayjab.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnsyndl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcrubqo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpmtije.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpaffun.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbyeybl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uimycvdn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2werzuypo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2prgiwegu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xstoiosy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2luhhgrrl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuipboc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkualnp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fihnzume.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaafpzh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2efxjfken.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pektjugf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlapppew.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmosxsto.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oulplwub.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tycohpbh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wniwkfun.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oelhohhn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wipkhdfn.html


<!-- 参考信息 -->