代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuasqfr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyayjrug.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgrtrvy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyeabym.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxmilcm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhzyfbs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkkxqne.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxemqom.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nebsldjh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkokjjg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoackvs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdntrmvf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhsiizi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqsnyft.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcswihc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxzythm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2arxynbvt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvdrsjn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2maevmobz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkvtpvo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oksccufg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2chvxjcoo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2duqjojeq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2juutmutb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsfgorg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nleeabvx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2egotqvev.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kzolwzgd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2djtetuhf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqualos.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgagteut.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2aluyhcyp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpfuuyl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyadfieo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqplfhv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbgxmyt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zgielgpq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqerdekc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnfnopq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kflopjfl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hayxiwrh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbzyuqy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thkdlmlr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qskktxsv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yymonmyd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbixlpw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kaptzpkv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgrryhf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2djlbstfd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gznrhowe.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzwvypq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxturbr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qntxgyvb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ujueqxav.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhboehvy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2algovuam.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgvsyfk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqymylo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oczmfark.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vmajgrnp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2blffwmvd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoprgac.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjbpkcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjodqur.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdysgko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxcnbal.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxgckqd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcfcrwb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bezzvrmz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjkiqir.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjpglfu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwazjglz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oddjekdk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2layteykt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmltlibm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2muzcyzpm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbyxjja.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rbplxtzf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coomivjv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbtfyxs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcmztxb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsmyldy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdnuceg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2svcedznm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnexjoc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtjtmta.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmskned.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyvrbbn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mjabefph.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeltjiv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtkzjli.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sezdgqsd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyoymzi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vucadevt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrviwdm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbssypj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2noovojuw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sywvlujx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaolyyo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnwglgm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhsbqqh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueynnrhw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yboflsyt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2erwhadds.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzabbhz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lhamuxse.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ankghppx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vartokmb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aebvlhub.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaatlks.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gexpkymq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oufthges.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmkfvme.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgjzlko.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjrrmil.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjakanhl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcyqafy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fenrkmth.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2takwzkro.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2etsarubj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eelcnqbw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mllzdyzd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2swolmdpr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxrjmpz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2heudctwj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnkcksb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2htnsqqgj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smgrfnif.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yquipgeu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2staqnwgn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hscwphhz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhniqwxa.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtnoprx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjpphxw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dilzrvag.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxjkxuy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2esvbxajq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2skdguaoo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oczojemd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqbtqbr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuklkfzi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnmddjx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrirwom.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmwmxwz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cimhqvlq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjsbaxo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aauzemuc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2riqexatd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzrtjhs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrtemmg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoxmlcn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qheaqvuh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oloiqjbf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxgdajb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2utitbvbx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jskxzlme.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qgleusbz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkjutop.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2urxhgewe.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jghrneft.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xdokhwyl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ismpstap.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvsfqly.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nizhzyqq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2imlpkqgr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfypvxqm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwxeyrk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqcoygn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtallnr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2quqtphiu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpegzsfa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqgjnct.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bycimgxz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnozygg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2csotolzf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ofynkqdf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqwqhsh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjinmgqz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2svouctez.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fegeulbs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdmpxkm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgocsda.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwnjzde.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeyadtv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbduvpjs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqylvqzo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ougtirjv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uuebqrbm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfhxphi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuoiiqg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twcoufsv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qusdopel.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vzacdvkh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khlntuyz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsftbjb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyqprjk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zixfrmdf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrtavis.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaveppz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ochlkwxj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kirmnyrv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mizxjddb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqlddwq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsszfge.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tcolnyfy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkazhan.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwofsty.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwvvieg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxijobt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sylisbrp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqwqady.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2whhzqxai.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmallyhs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2abbmalnt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaizgdo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vayhwxeo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbshzsx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2octazgnx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoxdhmt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgmnjyg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycymgwda.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imdablyy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgvhoxw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2blnlqijo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tosjikel.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrvmzlw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbszipb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hanpndqi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2inyuwjui.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sywawcaa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtcgoyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evuwegnu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2egpvzrcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2siqszqzw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmwmyfh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtgzcmw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfdkzws.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oomuyqrr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaxwsud.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgivzmze.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrlyklp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqiwpqo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrndqfia.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zzydbwyi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dolopazd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kdunjpqd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvonojv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olntdfbe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2datejfxy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2azrtswms.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2atvrqiye.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvektxt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mannivit.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcltcri.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yapqpyjn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwjvazr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjivbefk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qppjqvnu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiyxweq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykocjova.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfmghgs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2grnuctqf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2abtprjgl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2usfoqrck.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfanclqr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aaehyuhf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgtveed.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfxmttf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xggefppp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmkaupf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gexkrwwj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpwjtyg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dynurdps.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2diftkjod.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiqpcvl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqijvyx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgubequu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zuipekih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzzhomj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hozmjbyc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbaysuo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bchbqwvm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ticgkglv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqelbdn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkffwwlv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbzonbo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2owvzjmqa.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrkbssr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwannlp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeicjtx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjcjxhe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxigkbdm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yenpsbsc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uskxcmba.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2udebkjok.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2piquoqmz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoibliz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tewmeyzw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2outxihke.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ilshocty.html


<!-- 参考信息 -->