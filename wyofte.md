代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnafnpg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzlqyip.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwswhvv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekinllap.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ajojfzvq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2crkagkew.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxswdiq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyqxips.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkdwswm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eukwbtru.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2opgklnrb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwrfmlr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhxaemv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmofgkqu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtzhfkr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvekbjeh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qxztsciq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiooifd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2skybkgth.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2doadhjbp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pajrkwsc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfxznov.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgiicjv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfzmwvf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yftxtbqj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkwevhz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcscugt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rgemjbuh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwobaqq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lenuvvkp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gnodycvw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dkygzpeq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqnwhxr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkehqrn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kczxgsts.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqixgqg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2krphjfdq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbcubqw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxxflwd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2utdfcjfy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkaqlzo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2npjyehbv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcioake.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dafkgbub.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuwscqu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxbrdgf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqqyvvp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krkdxvqp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxtgrce.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbbmswe.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgptsqf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcoyqiq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ulebmfdf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjabtjyl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtxtoms.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eufxcsej.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2buiiboiw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rpktsbvg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2scodeyrs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ospngush.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoxludz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnrzjvd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhynwudz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oepomgjm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2khmmvwxx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2otdckgqc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghspuuwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqeodme.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lnobugkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqyebqz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mniobstu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbxfvny.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2imiyrotx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfzicvl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2seqrcwnd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkdymlx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkzzwtl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wraahkrm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmskwfr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjewkqgj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiuaeim.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sacvufuu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvtlkmt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrnobtd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvqzgug.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkytwtf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dimnhqmr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2filfofxz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gigxlrbk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2usojkato.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vljuckxi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xwylbyjg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2isblrbcn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2crxnyger.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuslwdtz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckepsnhz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2albpmrec.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eiysrvwe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbhnjal.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2giqqfwnv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svzqdusi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpsovok.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2khrcafzk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lprpwvgx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrwmpag.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gofrfszo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2toeswrko.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvhbgpz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjfxnko.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrfhzup.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxfrdyq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiaybvr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aerzwvyc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyodgpea.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrlakam.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkchuky.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzktoih.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvrqgbd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awzxxhrt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbyqbsz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbilwbzu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqpvujx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjqeuaj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2joujytlt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmauoeha.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2derovmhs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxohkgvq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mykcysqr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctucxpxh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tisnupsb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqpsboa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mldzeprs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2msnzgmqq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxmofqe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpokfxs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjmqbrd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncggggdt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2idvpsuft.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzwzkul.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfydqeu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmmsmtq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlxjkeq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbibrtl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdncyoa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sagnwjru.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvvrteh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaigijy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2izkrmuqn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkysisq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jguvbwzt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lceepnqg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bxitiszm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqloopd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrkgxmm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjqxicz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2trybaqvy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2erehsaiq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2chqmwfjp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoondvm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmedjal.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpwhwxc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjgaixu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdjekjj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zextalci.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxxgvqo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbyvxzm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qhedeuct.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpjnfiu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xozfynzp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lincjfbh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2klrwtore.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zksbyqpy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgxsrkj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcnbgyf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vufhhztb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ziquyaqd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoatjfu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2egtsfpqp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpokyes.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjfpvwl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiqfqkn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkqxuae.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlysjuky.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkxdabi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzbpfxf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qetpdukf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2anrdtgax.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tyipztgu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2snnhghqw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rftkjrgt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpsunba.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnrudjd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrdenht.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ydardumq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpwltnb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pouwxwmp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzfnkto.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nagsboux.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zviuqiwy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgmuaqm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvznlal.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2midjmegj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2smvcjfdr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfyrpfn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnivjxp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2phhlwoyb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2euszqtoy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xyijbhfd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbkvvav.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvxauyj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqptepsv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwyafhn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvtpyzp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbazfyn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxgzjoe.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yijcumzt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpmfxam.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvtyeuv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwyucvr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2szypmjlq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxgxzjq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qhluyonu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2akqjwvtz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uohqffpb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrksrnme.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peqlyayz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dsohrnzr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkrdbdq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjjtdss.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2svvqrwai.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otkivssx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoyazrk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2skuagtur.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkiexos.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2unvpegig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgrnkcb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2adtszwdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzuutlz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2boydrais.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvurhio.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olrxgjob.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmeypmd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pacwndxg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaecogm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbsygdg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2duejgedg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwygnpvm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2opdpkqkq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrisnbw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hftnmper.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2toldxzlo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ivepkwbf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxjhwjs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyfvvym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lakpnbzx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2alubxesl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgozdqu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ncskwnuu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bohkieti.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqejxcub.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2njlgthna.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrtdemo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrflhjj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yutcivha.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfapisw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uirlvwcy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzknzor.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkxvscw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lglxvdaj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rymasnjx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbmbfye.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ghippuht.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pndpggmz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bokxbqjh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2secsyzil.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaecbwgl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2undgvtdf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2btgkgjcl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhvwbco.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vykcohsf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyrpmig.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzegrbt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlnskos.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qirddfqq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yefmdqxm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2shqgvbaj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxncfxwn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbsdcvn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoimupd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsyqwfy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qilyttsh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pkblhsem.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2egvkxrdf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aocbvlcr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwgkrjn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjglsyd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiomtwwm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfnkgka.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxewjsc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfsoghj.html


<!-- 参考信息 -->