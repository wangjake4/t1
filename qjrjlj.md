代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmuzvnq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwttkiox.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yztiqgwm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkshbpwk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwakmrqi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfrmgfg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vamprfwn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbswfrm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnihwifd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vynhigfy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ilygcwwl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aytkejgz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkoujnp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgtkqri.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkhjjfo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2orrkwbmq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwkzaek.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkgedif.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpofopl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrqreve.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxsokay.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnuqgwi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2djzashjy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiskoxq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hznabdoz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhyazdv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eolkeevv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfosiis.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuatgju.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjntkna.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhteqka.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2syodjswy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zaccwyru.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2plsikpse.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqtqoip.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mosmlees.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nszlbxvs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrmcgbl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmoljbu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfjayhe.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gquirjad.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2okxmzytb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqecfrt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpandqbh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wdixilwy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mliwiuis.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcevecm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eleinrks.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrwlfai.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwdbaff.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2epvdfqmu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrxllhg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfbqlgp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2agljiyet.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2getsrcia.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tfphpvuu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvmpwus.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgajtjl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2osyheyhj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwzudnl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tyscxmoh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2utktadtj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gciditwn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxeziaw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dngwtoun.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsczputc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2umuakogz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyrearn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2brjqnqzn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zaedyyrk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tueusecp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2idyxetfk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tppizugb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2msbuqsxj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hreixabc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxegnhh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2btrmanfa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxrryfq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lojfhspv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eewkvdfm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2olriqjxy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwzuplh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mioryjok.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzujuihw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2huxbjqeg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsryrzo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2phobxamh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkgrcwk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2agbustvg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdvilbh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykhvsje.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoydsxf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvftdzu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvgsncd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksilnmhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyyieoh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhlglqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thrayrip.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pfouiwkm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsodmug.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqbjqbj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxuogqv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2shoiblxa.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvapcid.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2khukhupn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kirqsypa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtdpgkk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjwnjnz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atgaejkh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izbsgens.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzzirsl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuuxzxo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2trscqurq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rolziytc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gajxjvpc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdudwfro.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oprdsjcl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zumrnmsm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2okjfgdaw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzoxvac.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvqfywl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odyxhtjb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2afmbxbzh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vneqqvga.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxelfis.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gickscmw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpoajoa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvgkhoe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwvgtmy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wleawnsh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsjqmqh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tehijyly.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrqecyq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmogcuv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsgopfw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsuezok.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgbhjxd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzxwexq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rukkognl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fneliiff.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jddboari.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsygryi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzddkgzc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2auqpstjz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyghyqi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaqwaco.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjrfgcq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnpntpx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2amxfqlpy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqtucjb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vspqaalw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ynldbpgw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgmarlp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrclvie.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aexzygtd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uyslhrpy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiozrqf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2feriafef.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sniwoxxf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzmpvmw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2belvsxvz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dftlngbd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlzcazc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uifizthf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upshrvhq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeaolpm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqgywmc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2laqwqbyz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hymteiof.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlengay.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jojxohdg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeycrtk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eskaztve.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaacftp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bxynzvvp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rslrviry.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpjfwuc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqqkbeo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmsjill.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lyykdqdj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbjtchy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrkvlvu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwphpqk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2idezuoxi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqinnhd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jorwvnja.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hswhpyfj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jusrdtpj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wohqxeyh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsquuyg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhcigqm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiavywd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwhgynp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oujvpfjr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gspvdbye.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2afysvdyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfavujh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2digkbqgb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igwimgte.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2siadbtwx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vmakxuor.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2knoacdod.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnkotbf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwkxtlm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmzjpvo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqmayeg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuytict.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zwavzrsy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2berwecpt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkhbmkp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2psboaskx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxpptrc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjmdjou.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dtatqfev.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhvxdbr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iitosred.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2imiqosll.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2endtntpm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwqjevf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2plckqzjd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dnakfiza.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaaeueu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wllnzzcj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zlphjkcx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fynipshi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2horpckyy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpjzbev.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrhmlob.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gguaxkdi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xstrwvap.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnldksfi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uepxipid.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuqdppx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqsmlsf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsdpozn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eciqvcnw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqvdald.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcctqvme.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qyicztad.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxgturm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gzihwxdp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmlxdoy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdtcmkg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ufntdggc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfywtsy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrtiqcs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwuhisw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2slavifrf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tviuiljm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpjhzys.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqebshhi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxaaytu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2poycnels.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxuqikb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pghjejtp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnzxofg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rearcjgh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2prlxxdvn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgdiwxg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiktopt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzehova.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gcesabzf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxwhhff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlublpwa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ikonkinw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqvmgig.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjufrvrv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2brsuojei.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mccjisql.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nouhjjqq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrzxjxo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkepqxpf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dezfnhzz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oelgnioa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxmnrpw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cobjzubb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgnoggc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gewljkdq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhqrbti.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gttcwzaz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjuhybc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xpemprwx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoivyxla.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgpxjcz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2weazbprq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhcuxxm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgrsumv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mirqowhj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvofwfbb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlewsurf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2obofovoz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlkxtka.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnuorns.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2utamvwmk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhpnnaa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hshxahie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnhhexf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtplghys.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tniqwmnz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqolaqr.html


<!-- 参考信息 -->