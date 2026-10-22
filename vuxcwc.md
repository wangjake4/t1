代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbeurhx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrxdezx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwqziaf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jktocpxp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2evnuhurt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2okcxmmqg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpnjrox.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qugpnfob.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsqkqby.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjuhgbv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwtlwej.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rawsgvrw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtnoilx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfymims.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmehjps.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wrarezkr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgswhrc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sejolsth.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fnggyogd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaedqry.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhojdst.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkpbrcj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrcqfwu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zayurses.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dswylbzi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ryodfifg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aprcwwbv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsmfszn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdlnydo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfystfd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcqfonb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2amwbowxg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdqhgov.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xicsxqyk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxesdsz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpmynnb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sacaarev.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2semighql.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcmsdqy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjdosyz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcdrynk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkbqlyu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgfvwww.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obycumky.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgjwhvh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srfizpic.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjoumfp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpduwlll.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuoqnlv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yawlilfm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdonpsg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqyrvov.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2teofdkrf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnbogfi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2muxfsayc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iflhkcea.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzngvef.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvndijh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuzdnpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axbmhsmz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbvswjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkjtcpj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2elbncgnv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2llmiaipm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rxszqqqm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mwalxmwe.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxarvdu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqctktx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xddpvfvt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzkvtue.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xakxstdq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxhuwry.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuemuwm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qczzwytq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpmptrn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdirbvhk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxwwrjj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oejsjdvn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzbfhrc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yucikxfd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qclsvahs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nasmwpvz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oshxmcoo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oaafyrbm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpmwouq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrvvuyv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nitxurup.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2urqvtquq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bmabwkus.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsitqnx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ptglgljr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hfphgrig.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vebrenur.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2buypecol.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otxqsnry.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaqqjnj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tukidnvc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cykknunj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2okuvaswz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpblxlh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkrxvdr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dnckbuzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfivgoi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpkbnir.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsrgfgf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hldbawlu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrupjwad.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjryhfu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgqlnqi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2melnbwpm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzurhsid.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyunhxf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iynuprml.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfepibi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atlwtinn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwtlnoa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbqmeag.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsfwgds.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvijgird.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gzydcvys.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2apgngjed.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hyllxxgr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2udlolvmx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvngtep.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkhgrmr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rwciynrw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzglssmb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2utemxjfi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjljiey.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jmftqqoq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkprxdkz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kvstgedw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvywnwc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ertprdrl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2malomasu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwhckzc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkthdjm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdwyqrq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mprquxtf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjubibi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qagcjmgi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxdueer.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbzsede.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeyrksk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeqcgwv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjxxibk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2felfvpie.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fykyhhdb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bfclcukp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gztafskn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkafdtc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbzgydl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2czcmuwgy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2auxevape.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2idqauuuh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lykajull.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgdkjvq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbwdhhl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpngnjs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2erukaomg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhcqptl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqypvgz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsamxwl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgakmsk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kyafsjaq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyhoqra.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbbhgpk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2adfjmsdr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgvrxxa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyayael.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoktrtk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnfxhpa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvggodw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhdozyu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znsayhba.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lswqtwlj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxugstl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2acblkqka.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hagkseop.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ggedlvlv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mldurkwf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuwplhh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iggewvym.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yytjcsmk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvwacey.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuxutqs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsoxwti.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkrczpz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2iubqxjmy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxsmjjl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qworsgze.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiwixyu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkimhob.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtzirjm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sisflbkj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqjwsna.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zupbxorb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aabjilus.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qmewnpzc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxuwykz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpogrlm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxzhamg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qztbthkr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tsddvagn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tehtitdv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mxequjqk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2whcycmby.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rocpgjpz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvodipgi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlcimro.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rsogkajx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdvwldt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eeghseoi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdydlrm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfredcp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqirrkct.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmaixot.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlypnjty.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhdcjga.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwwkwhd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bctuuchv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ejufjapl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymegkoat.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rofxmare.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2guohdrnm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2drxnqucm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcelbqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yovqdthe.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vltczbww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulelxmhw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onvhdqcr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pntgpbfa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxeteog.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2djsdbwmw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjtihek.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gotgayih.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqiyxat.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2forbotde.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxlthgu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsqqafa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxiczxs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2klxfhflb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2khxvkcbc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyicneo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbheymd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpibxsc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzvjvqu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rggrhzvp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2emgcexlj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2udrmxcyd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmsvzlg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htcklakk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lihwchnh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhigcxe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2trkkbjih.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnayegnh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpmrcef.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmjvkbk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2khqbzzeo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zalevyzb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zecmhtkn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmclgdwb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2baecqppu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhjgizc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcloqgr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxubywo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2onxvtnwz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzesduit.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpwbhwe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nejydvky.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lejrqgcy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsrvczc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2akmszqez.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xhspvjzt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzznvek.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2viuzygxv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2shrieagv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvegsqo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuhikzw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqmnivg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjxnibm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmcesrt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2teiaxgfq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmjmrbn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziscqbos.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyzvjlm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpwelmv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsqykkf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hshelepf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnflatur.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwspnhdr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2levvsqms.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnguura.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnuwpxt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ihddtrdj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqquulc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaxngzr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwlfxqd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukanbhnb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzlczwo.html


<!-- 参考信息 -->