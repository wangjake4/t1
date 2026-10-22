代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxcvpdt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxfcthy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqxwzcv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bsazdeda.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnlpakq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhybhyf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbeqknl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbgjevb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2buomttps.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkaqolq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpnlplo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iynecnme.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irqvlkhv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vszvusuo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2omscfrpe.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sulqljtu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2esboqqeh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgxhyxc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdrugwh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eukrokdd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wngtqtxz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wasbmjcs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2eremydez.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfigole.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zhunppxe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhhpdtj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vflpzgcs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjxlzuy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtnvlto.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvlnnif.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfmxwif.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2svervylz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wiakcvqk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdrlsea.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xiktpkra.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydlvadd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2myhydepa.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcblyog.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdqoujy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2olqalnck.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrfwdye.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2stjwcntw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnkjwvp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pfplblzi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlzjata.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hehvxkli.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnuxxnr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhnirrt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeldqsk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzfvyue.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2toerwrws.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmigwsb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xedaqege.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjraumtv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2idrxhqba.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fueeondr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rziqvnwe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtusdtfh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xicifeyo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kzztodvg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhrfjsc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtrgedd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idmxydep.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxxicti.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqpmdbd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxfmash.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iytaadyt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxdjmnf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fekacuqj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzrdonj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpxlynq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2upuxghxw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xgojqklv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfjvkaj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyiqymm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gohcglxf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtybjygn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjbpuzl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaayxld.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmzisbj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwveksv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vvupxpot.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyqjoxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phfumwdv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtysnwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmfhuac.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmatzuz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmouvpa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2trcvmard.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtstbwk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dytaduqo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgwdczu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bplsbbfg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rynkruff.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpcurch.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkatlzx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enczydsq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqiaxst.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gutjsbya.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stinbhsf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkryqpq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvahiys.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tnobkqgh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ozibkhcu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gexplaiv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoaauwu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrpnnrc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhgyzne.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbcoreh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzsnehf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aotffgus.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zagrhfjr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lskzgwbe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmlxtcn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glensspu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2twpdujlh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urkvwqsx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2czepozki.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avwxyvkc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acmanopu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjynkigt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2snkbbcxo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2arpszazr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaukqnk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pusamelb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lidhmews.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nizeetvl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vowhczrw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmptrsn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjflvek.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyqaizp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsmjnhu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcneyel.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdnmzqv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjljwhq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzaovsi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjhndik.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2snihyruk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mavlgfhw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jegxgtrx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbpzlrs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfpjntu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsgeegp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2heokwimu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqwoioh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iafrkfsh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kgngobtg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2embkufem.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsywntk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2arldkztq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzfskid.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzabomvk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pagjjpag.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hntlotub.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obynovhb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yqivienc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kyekrqnl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2igshxwkk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vihfcwkb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2leujaurd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzakrmgy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2izybpund.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hinkpqbh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyxizqq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dokjxwsd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gchmarvb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2djwyxmyr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wsynsxjz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjrmxtu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2icyilfhu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2slclqroz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfbrmlo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdjvslg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rpysauds.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjctoopn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rihxfful.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bmltqhfq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nswhowlv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rbecvxhg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aoatbgdl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuyfcpe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2peisuxch.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ughmltmp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdqgbzq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yotbzsnl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wswolsvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jsarnmca.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlonlsa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzwmqkd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhtmcap.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwghnnso.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2htpbafzh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rwllxydp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxpkyou.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhspytr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yojgjxxg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qsymviff.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpercrn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snujlygs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdycbxx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjfnpme.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaxrikw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkcozzn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tfujlyib.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgueesn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqthjauf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kyubyjmj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbmcrjw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlqbluz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hikfzuai.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxvunhe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2elcfrwrl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2neroiuss.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvehluqn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsxcexn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zotidjbb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iljrusfg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2thkrezqx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ettgwdkz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sdatiiad.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdnswfr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxdjgsq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rakebsrm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqpepzj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gdefkogw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2asulrawp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khjpccvp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgkyhbe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bobnulgw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2feudjydr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qtubafvn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbxwrnt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2siswhvqu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2baoysjsg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aaimuezx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dljlcogk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnobsot.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2riqsqcsc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzafxtle.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbacces.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjwgvmp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqrhnnw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkjcktz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrwzxvf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbrzxiu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ofidhbpm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfmjgyr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fcavobqm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xldwgurs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqeayvz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2azcfpqpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbraima.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2whzertql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpsedhg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twlwkwqo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoymedw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqdynjb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkksone.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsmsrai.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbcndyu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vekozuqv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoakmgq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntokoelm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zyackwdj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzvsahz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2osfvnvsh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sclgnxjj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2korfrulo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2badrmqfb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vsejuosh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zswqzfxa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ouajsbzw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ltziofqt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pktxxqkm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsszsja.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzahkoz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ansoomqm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdketre.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuanjjfe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtzcgbh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnidghw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uacytfuu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtigfuk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gqttjrqn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqkcogi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxetzjk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jadncohk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmqrura.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbjbefc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2miskcqyn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2idkfxlqe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlljels.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwieevic.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpogiin.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhumxmjx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cnydlbbq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2popvjmfh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgbnedv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpurvfm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzbjcbp.html


<!-- 参考信息 -->