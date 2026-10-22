代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbkccpt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2brarfexa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cbejapei.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bccehqnq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkdqkxc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdbjkju.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuwxvzb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oqegjdsy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2milsjgok.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2roshsrvp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeoipky.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvghlnge.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsghufby.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zegkphjq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yibzzgdl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjarwmq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbznyva.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpetedd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2roffcypi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjvecfj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcepogq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gacvvulw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2owyjoozs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkfimec.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ociqajmv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoekhosc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rljwceis.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2frjlrtyf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjcgizb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtynswt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pprvpmue.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ximwmkgi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaqpvqo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bublpvmc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpkrjlb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xycugbxs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xuprvvur.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uktxsxuq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sosycufa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2atxybkqr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcercmf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pvovsftr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoqhlby.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uoixeeqm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vphbbzkr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qaslcabg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdfnexa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kujkijxv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrbhbfs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqdzsah.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yzisatwo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnmwown.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2iquxlhjf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tbshbcyj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyodhksv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2axnbcynq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqrnvrg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2notqvacu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zqegkeky.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uucjltvq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgdkznv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnqsgdb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iznrdhjj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgwdjlr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2thetwdac.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rroxfues.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnutiqf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drkrgiam.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlolqgu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oofvuwvu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyvomfl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amnxgbjx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjolkbd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udrfbnnz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoyvgws.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiatama.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zzccvpfw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vevsbczt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngozcvck.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvvkpzz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zipydgbv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ykneyaup.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeirqnmy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vahimgbt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gmblmjle.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqprhbq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jezvejyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfyehtb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwyuuls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frsucoic.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwlipiv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uweigjth.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qoesztak.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2slbkzjvg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjgerkg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiawpce.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ibolxkjp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxksqqsp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxppvdt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgtcvbv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2euysixim.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsfaxjn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uebwhavy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eksofbjo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjhjrwe.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2afstpbqi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xywtaweg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bexpcqnt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvymcot.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2npibwnmq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnifwxd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyubdei.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfmyuhr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpexpgqe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2avljzsxb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aakonxhh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qmigolkr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyffick.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mubppmbh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrijzap.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2moydmldn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbkeqzv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpybbqgh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ricilnjh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvhflgf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfimvofr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwotakv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2otzdtnoi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iusfykpl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2teqzewyk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwtkblk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhyguva.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmcyunj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2whrwfpsx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uumumakh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2apqnaery.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzhrszy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkmybfp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sniiikwq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoulxax.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhulydoi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhioxhh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dukxtyke.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xrefmqyv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2etvelaaz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlyedbh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsqdlow.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrpomey.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2izmsdbqy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sajpttin.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2szxoesry.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cahcqexz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flzgqlog.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyqtjfi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rehwocsi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2forsqors.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naxuujwb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzaoeen.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtbwoiv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2egbhlerh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iufvgwsa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ftysfbae.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfnipdx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzssvgm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfulcpt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxrwemu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbypxzj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lahiwqmt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmotrmvo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bdswsfol.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2btlkmepw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaxextk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jutuhgjy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2afayiqoh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2shnydtam.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vslryrkg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmknfum.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zafswhoo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrskrxvg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgjtwxt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2urtmddel.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yugflwwo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zenkapki.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vxellrvi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cxidvczq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnedkbk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pontdpqz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2auxgvtir.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxxarfn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyongsoe.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbcigge.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxfazur.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yybrtwlw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2guaodnuk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tckqokil.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqjytfg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fueyiuts.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziioykdo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnrkgjw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfnzlmm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlmxves.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnjktqt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avmcrowh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmzzscc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cewrgiwe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oslikqbn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cpscqqsx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2okqudajx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbkrbdb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnowjhna.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfhjzfj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sygkvnne.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2izlvieto.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rztvldxa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ncarrypq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwteeac.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jfflkgft.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uawpttzq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zojbuolu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcgfygs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxukqlb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzpxcjo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfkvslw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bvscqueg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2krnlxpcr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2juxmbfcc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sihszlsn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2padvrorr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2txmdypce.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2glvavctk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhztyhe.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lesbzynj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2urvtxuqn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlyqgvm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mckplhas.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aiinmjdk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2doknixrg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wecvcfnw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njjgbdzp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgxuztu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnegixh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcsyxyn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcrwkrw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnjndjf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbcvzyl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhcsfyd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxktrix.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjvzdwy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lusxfocl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkhmhxf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ciegxbal.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlihxxz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2imbfojxo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2grmmsalc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrmyafp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwghabm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pudbgizh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npdjhtim.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtfeefe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bfldzals.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwwzcnj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnfovrj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbecwkiy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nomdeiac.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aizurfca.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gipngpwj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2czffjzok.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkfgxgl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2owzxbiho.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtnqppx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2afhicghk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cmooealn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxelwjt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cshzwwvi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xopmkbpi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sagyfoce.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvfprkc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ecroxwuj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcokhymi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqldbmg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcxfafy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2saxvrins.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qboehtlz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjolwewv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhebeapw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcoihvy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkwfwjy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfzrefy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkpzfdo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gebjravn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fivcalrm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2otjrguwd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxbftqy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfnmgry.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lemhkwym.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2repdwlmx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrruvlmf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2comtykki.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgocqer.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmmzque.html


<!-- 参考信息 -->