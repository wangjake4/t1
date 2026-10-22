代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tozcstau.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2enrpczes.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjqugas.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmizrtqh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2acxbjmmw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtrotfg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuvawkn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iskwjeev.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aweagyzj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2juvtsljp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvajawb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyeticj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2btxdakhp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmshhkn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuyjvuc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrsanfj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2thvriidc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwcgizv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjvfzpk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sstgblmf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxflcnrh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2aeevxyiw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsbbgrs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqdczhh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wehcmckd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrwdjyg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hpibqgxt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoxbwis.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvohrww.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcetcnx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uelpumnu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtzbwmw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2clmfzccc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ctahqqpj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rehjsekr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dzybassj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eklgrmpz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbpmxwl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrtxvtl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpyybtc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwlzkuc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfzyxei.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzzaria.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsjdqts.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2canvaftf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnunppx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wshqbcqh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cstwsngo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfbtyof.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpipzao.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwtfmsy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adbiskzm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qwajjkiw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wywkeoyx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcufqib.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2clvpbrtv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tgirjtwy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ehucjbzl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyjivhi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlbcjyc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkifjda.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwpucfe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxbntea.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hodzbjhn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdmqetf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmlxkcy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fetidxyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbjhnaq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oovswido.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiywtwbk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvifyorx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hppstlop.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjksoym.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyfoluz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlctica.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvkrjbe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gdghcbaw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmfgfxq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrffuurz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzkwsmv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2motckewv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhdqgkb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsrrzzk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mthkoutl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyvjvuo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ecurkkio.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qryfxcfl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnwongm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mepygrcl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vnunxyww.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeeshdu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqmajyg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlwfzmt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnljnxz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlduyewy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcroslu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nlikodoh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeizsbl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwplhmz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oobcemns.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilulihwv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcdkhyo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gomlcguy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnafuotp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwebfrh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uukhsksn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aymktybd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vahlqauy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtrcytu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjlfxxs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2goaywnoa.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tchpyzee.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiklfsoh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzccuehe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcharhau.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxpzyii.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2durzviul.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxjlzcl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yijjhalq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaaoxgg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkkqisl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxyaqnr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqhwjpd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhjiwdk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoirtgc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fuchhtvw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhidgyq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aghnhbms.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyaxajo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jorwutzn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lscqzxfg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcrisaa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2saraeucx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsejjjh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbonxkdl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfjlbop.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqtzijs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2icqlzpgi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhllparo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkhnuhy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqceaot.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cddfpaqv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaqzfbf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpznyhh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfqimak.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjxadvf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrppztp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gznfagis.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpqhceo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnmcqbm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2chwpllel.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2boogpavk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzplwoh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xzicflnk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozjpwv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oqagmeqi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdvienn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbqzmgn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvbjtau.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuaeivm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrhuvne.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkgouzr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jntmtgaj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dklpkjir.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvnyybj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnurloq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiuejzy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbauqxx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nofuppus.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgocwnta.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgklgmz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yefaycir.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xbemsjdu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pssqfnzc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xzupuvzf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbbucyg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqbtbhr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2myntvprp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oraycwxy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgsagug.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnvrcsk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpctegcl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aodgnytm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wtohpfxk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiyqugs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2maecspih.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ggysfeqi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2situvupv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dttkohcq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cipguhjd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yelrmdfu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iizlzkoj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2soleueqs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzaxqnm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2okitfvwj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpmcosp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rlccqlun.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwcjvfy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jigtavbt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhmbdqu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vujwtphi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrksfsp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hccimdsk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rteslmyj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jckiikxd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgjgjwl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwhpsvn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaoigzz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwjrtsu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzauvwc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgxqeyw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2feawcksu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gpylreym.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yktjnkve.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxwlipd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvbeeat.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkliqdcp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2brvycpax.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pozjejtc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2guazbgqj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rzddbpen.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdsjryo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxgnaoh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2keolmfms.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sezacohq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2octiucgi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uikxrlbl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoddkqi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xonietsk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hvybvptr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwejttzd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrilehs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ehegyhko.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cxclxjoh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsgouea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukupzlyp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxocimb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtnsaou.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvsmgny.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtanaev.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuzanxh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pzljzqmh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvdrllj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eelauaoj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowecuix.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2exrrfmfv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nukespqa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2grcrpuob.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2reilzjwn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwdvavs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkrkkvk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zuorzozk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qedhflti.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgxhvbj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxgxnav.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzxyxkc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uggigknu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zoapteds.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gunaobku.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvtlkhj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2chvboili.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2umukwlvm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhngoinz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfghqwb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqlrocp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvpzjwj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2blwgrfhl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxnvprx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqmgfqu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2foiudxym.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nikdhegg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlhothj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdnjdjy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvsgfyt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqubkgee.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeyafia.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfgqcyv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oumtello.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsefute.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eeejqfpg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtcassd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jfibthqz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnuplot.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bvukcsru.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgpzxnf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yopgidqu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jayyhxhf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvqqhak.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2swwxyksh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mblznjat.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2foyryooi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjdsigk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xraekysq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvlwqjv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwiohls.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvfehgm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2byesjnrz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eopdudvv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhfcdyx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbjxeri.html


<!-- 参考信息 -->