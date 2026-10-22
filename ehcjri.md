代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bpounsvp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlndtde.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvadhtz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2szidmwbu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2odzkqlhh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfqrsub.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2duljobze.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vfreuffn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojydwxxu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2awamygzd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgoyhjf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zunhsnki.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvvurcl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwscurjl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgqwtwo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnswijc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpwztcx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyuciya.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zngzghfx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzshtxp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvijjhav.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyjowhi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvtoevp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtpqpul.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikctgtrh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzureik.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2punmdyyd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdkwnzz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgekjut.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfubjqzr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpqoyze.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmjnayx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjssppk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uubgotbg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpypfboz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eowjhpjr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iiufewbn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgxyclr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2owytweft.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqpmscb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rscrpuna.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpdepjm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrtgffl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoauqsv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgahtxmu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bsklujlx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwfcfvx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyxktpr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkauxheq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ldznrfyx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2otuonoff.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wungyhkv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlirirbt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fatxhgbt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2skunzflh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwqolen.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxfbuty.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbcmsfl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlsafbr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zftsvzgx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2meqhtslj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcauxnh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzzaxjt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqpxoae.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2edwlopku.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulscodry.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxdqngv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2orciyefo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2caxgqhyr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xewopolh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkqcfcp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qimkfuyc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaflgfv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcfuzww.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iporyazq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efbjsywj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnmqufg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zakmaole.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnnykkl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2plmuwlxp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuyeprn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sgweqaii.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmkmzpf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqztbko.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjgeuqa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2anjkfvvy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2saosqxzu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2poztbtbz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rufllpav.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsqxowx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxctqris.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jeavyiwz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfbbkmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzjrcod.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmkbrpk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2byevibrr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2trezijfk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzcrtzr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzuuzwa.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nynuysia.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2njqslchv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdhgoxb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbipdwux.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsouhff.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tucbocso.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iajtvztl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsirlfd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gscibsjh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pukxztkf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpagvau.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqwiymr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gthpkpqd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkweoiy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwlsswd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuosgen.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xycgnsas.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2djxgyneb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvtubew.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymddgfai.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hynlxdcj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2voyzdreu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wouuaocm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoycbmc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mpixgvuj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksykbeed.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjpqtqy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flbzmycb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvidxdvg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ratqqxsx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpkwlgy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2npsbaomi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2udbqctrl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuyedvd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2apsuasbd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2soromwjd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sxulwhcc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqremyon.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdflaso.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgfvizb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rniobgra.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncebrgbu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ighhbkky.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afstjvxi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlibgaf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2smxwsisy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwkxtlm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmclnsz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwarvik.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vleghson.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2klhrgdxx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqycjslg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkhdtcq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2clgsbuee.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwhavmj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtfrhzv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxohsdk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgthajr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2klgbsyen.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhimlorl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwdwbeg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inwmffco.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2peoanblt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mweffefl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeuixws.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2opnzamwc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2neoemxxd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kozotrsw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjgqlmr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcmkdkk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qpswdijz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcycanw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtfwqwl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhemidtv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uygdxisa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsmprsb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoklmih.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uazfamxw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2olptfqnd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2evpjahzg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nfofigpy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rspldpdv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkfrrev.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msbltjlk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izedpcgy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bujpwkxm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2olpbrkax.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxntqoy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzhxirx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ircgwaud.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qfictabw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmbuumk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyilamei.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jszavbpl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlfdhwb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okefnlpy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqyezzn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqnbwce.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sppegmsc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jotmhptz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2awsnubdz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfnucct.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2egccnyxw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wyohlmff.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qknqmbiu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgueqfu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxrkibz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctebivnm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtwzjjv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxegolx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wpstphvk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wijwjvmf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kzprdnio.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yghhhzic.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqbtmvl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2njeasvaj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsmxttu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cuosgguc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2skkrysmb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fuicrqca.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lebfxqec.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvzfaqf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odpplvya.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fafhrwdu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqszjvl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wsktxgrx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gkujaocl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmyspum.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyuugkf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pskgcaok.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rutfubli.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbnmgbr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqkqytj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcjcirz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2flyyswqn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqxqkkq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwukjmh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dlugwkoi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2azsznrgu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfcdnuf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2herqjrjo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdxmlhw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vwevxenl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yisiddgm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsygxro.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2borsfidf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2poxbiojg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eydumbbw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zheijyme.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxymoeaz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpletcr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiiexbc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoughji.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnnmcdw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfobnpy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lihllecu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uqagsjrr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zyabmgiq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nijblugc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2flllhdsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbfxkqp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mggvyhjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egzplnpp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nopcqbdx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvotujz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2honqjfyy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbmguzh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfysbnab.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2olrrekzr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2auajwcqa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sovyiefm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2urnjsgcb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jomygqdn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eebhcglb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edvwpdqe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjrdahw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbvnstx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfozebm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iwslgcgv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iraxfufs.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nwysajoa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjfwaoq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uylykgqj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpplkdpt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reabraxv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlswzlj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mblklaqg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvojjkvf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaurrnu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbupbiv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmtkpvs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpwupei.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2klsrrmtn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlswrsk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwfyqms.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkqqfga.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2swokkmpe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbfjnql.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeurzgv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fekslelh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjbkztg.html


<!-- 参考信息 -->