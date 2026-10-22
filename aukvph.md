代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdxctii.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdxmjqk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2obdyokfb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2czesoihw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2emnowypm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxvzyfa.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2boypeolg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbknegf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyoqwhu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlctweco.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nteeganb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoglzks.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nulxpugm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eamxwljv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itkpncpo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdvbojv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2obuhzdfb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtencfi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqoxuxd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaljvko.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeutxqx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fepmlmpa.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzwqdow.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmqsrqm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lziqshud.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2geuhaigo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jstrkkpj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcyuobf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xjylirii.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmpcvbo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqxfeux.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ievjcidf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2keermdta.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wneyoske.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sukdjizb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2suolgjhv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cytmvobw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxkwzvk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2drdtnixu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oxknvihy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbvcmji.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lctvfutq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbwpzhf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjmbnqi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frsskvwz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkmskqt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoovfcn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdnrhhl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuwsbay.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzvkgvu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2plmrgtwf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oskgiiku.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2suyxdloz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2guttydzx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lvorgjti.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2eqllnugn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpevvzs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iojnqfrz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqblrzu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjacgjb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2smfuefgp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdqzdqa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdvozvr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pihjbinl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2whpifmpd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2luenaymw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rstlsklc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrghiwz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxvehzn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpiojeu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2prtlixon.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pedwimax.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuukftr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dxycknhh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lifiyqqe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2frytkkeo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlxusnb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfgzics.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jholqgvi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2avkiimvk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mezfuond.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrghdju.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2acmwwskr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbrzyxx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lydgzkkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgyktbi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ambjeyro.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvfyveu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeklnnv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvbzadm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrmqqij.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twjcqfop.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfapmfc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtxqusl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pswaymsl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkfmchl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhemkzn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zequjrah.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esglejzx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqstdoj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrtuwfs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlkgkgd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpdfrhp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bgferuxt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vynphlxe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vldphrsw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbhkpmu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhjluuy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2etjfydkx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdrrtiw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bithpsmq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfciefd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2oahztvaz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rboqycyz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmjqsgj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbeymdd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frooeebq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2glkaxyoy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2giulpdcf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yezsfflt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bazednts.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sostpwla.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhnpuqe.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzowkwev.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tojntsmb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmosemk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2riwsyqrm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dslfhjeo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcayyuhx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsisaqcd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxktxnx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlicenk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2odteskma.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiirajh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbenuxec.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbytrrn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsvjotq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcntfgu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thshtdmi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuewjsy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrnhrhv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkxkfwp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2imibrjxz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2efnloywk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kscscvpb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pizgdgya.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpncosi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prshfloh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsltocuy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqjtyhq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmimntf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptamfitd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlanphy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdgtlpk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cljzqjyd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyeyvmn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pstwqktp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbsvtts.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbfmgcv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqfszjo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzcrajn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgezoodp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vyghwkkh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkfgrlj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzovszh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qujdmxje.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2axdwmauf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kufzyumi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvxidha.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlycczs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxufakv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdrfzog.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iplwpiov.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2acdyhnse.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhggrgt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmwlsvd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsnpijf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdlawkt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrgwpee.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjvhuwf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zesfgqwd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2smqvivtc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfnntft.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szlczxbk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzknvuw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsobzodt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zenkhkyg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2psbgvunf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wolseyzr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2arsvdcfr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnuitly.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwxftme.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgexhrg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvirjgn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvibyfl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyvjobo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mgttubce.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsspoxk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpkcood.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxzvecs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2twzfuoit.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eecvyxik.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlrebgs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhjclby.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmwzsdd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tccldqci.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcddrbq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtyxtza.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjkqdff.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwmknjr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqmtjvi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpnqjup.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ezucaews.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxlvlrb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzchljm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcfxeoy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2aneusudi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvlyllf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2acvikieu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgxhytc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2riragfng.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2glzcrzgp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiuqctg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bagjirlt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2krumrjsq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2easrmwrv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bckvwsfu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2whjxijdp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zacflxys.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gphqruan.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxaurr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2murfyonc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vllebool.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2beexyjyz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vumujlwp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2desvewqr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2afcuzdpd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfyrjkd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxnlrpt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trgufgaj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oghqnjrs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oghpvruu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbmsyvd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbqnxek.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuqmdza.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uenqwmpc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzbymsb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2varpcdxc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2spsfkvdb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tftqobbf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2biyyjdta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhomxiko.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cjasiopb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlrdsgc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohglzbff.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvdtofb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oigooybd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnpvriy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tshxvwyl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjtohpc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qotwcaii.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2epzcvypt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2exkrtuwm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdjzrze.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxdqivw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bwptmetx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2keeuoyru.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wdppchgg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wjatfshq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qfubjbyj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkstzbcb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoyuufc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zmugabqi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvbxkab.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrpdaeo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjbkjlk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cggrowbm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwugxob.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2erigttqu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eghvyxfy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyobffni.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbodnjb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2icrrzimx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gougdybl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2etjvopkc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcgfvkj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfappii.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlywkmx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yooxcznv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iagxqqql.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxroiju.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdubxbuk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wugdwpes.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2biytwssx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaopinem.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwymjma.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzlpnhm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aijvoihf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpeztnc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuqywep.html


<!-- 参考信息 -->