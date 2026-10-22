代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dorscxvq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zipkxjnt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2quqikoex.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqentij.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfalkhkg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gsamgtgp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyfxpkh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bopjsrif.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idjqtrbx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2slumbgdd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lkopnghe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpfmvey.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2puxrshkk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sguveozi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgrmced.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sahksifq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kilrzgfm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nlykehvs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fosoowbo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsjgdil.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnfhjvk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjbtpvo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyvkyjs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ogozbspn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bufcuhkr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzquklgz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gbokejko.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2twhcvwfw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2khdvfcms.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryywukow.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ritsbgzn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsennhy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmnupqr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcxptwq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzcuhti.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nltzmglp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvjuwcs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzohwnh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uciyeyoa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dchkfwoi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2chrqupgn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgnzkho.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkblrhbs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqkmkrd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcbtptj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2odgtvxer.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oabgicie.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mopmulnm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qiglasgi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lafvokky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubslmrot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvgbwna.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cmznwkny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhckyvhy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ereutydx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpgbhnj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpltbbc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lnegwogt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkwufrg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aftgrfih.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvzinwa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2spvbfqyt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtahvhhq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfcumcg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jefvsgrf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2owvcahxy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzthirjd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eiugsemu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmwjrkx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjxvkmu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2stvbacww.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2txidgtvx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgwsqxi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dypxoroy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jnomciul.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2opigslao.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzokqcj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rochdgwa.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwhggtu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gygtjqho.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfeeyfn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykomhftu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhrhyyj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rssfgifg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qewvskyi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvhhvip.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvbegba.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuudfvbm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrqqjtb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2reisrcjg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqwychz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwebjqeg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qocsxnjz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoqgxbd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zftjgnya.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfogmge.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgytqam.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfomhbq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xidyjjdl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiopglo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agxtbspf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2elgktmhn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjkvoof.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xezievue.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uldqbmew.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2trqenjbe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjhgytd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2efydhgfs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqkvgvs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdqzzok.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrsxhsq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcbgujg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfhrnvx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2biwlcpgx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fucosens.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwifiytn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2phvtnowi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsrtiub.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuwauvo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2okvvpzco.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyceruqx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuiiqqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqxscih.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcvgrzc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tupbzhwa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bftbuggs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iodfxwjj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lemftxhg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhdqsrg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rihsfwts.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2naopklcl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvucqro.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgibnzby.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2swhbdxbr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjohczw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiggnhc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfhjrlk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmqhxyk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2adzpxkvy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vddaaoln.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oblciqwq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lymviprg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ursbrujz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ravhrlsf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiddsuf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2squgidow.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2svxdqyfs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzjzsoa.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvkqllo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2snmlkbof.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsjgsho.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsglrmcz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzxdhcx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdhxmsg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzsoudo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xllmyqiu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2idtbxdkj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2leyimcti.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaqsmci.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmrupfh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmhhjsz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lofrlzmc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuhovcg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiksmtg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iuutawya.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kembnbhx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igxmeivl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbkgnqc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqjbzyz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2huetbaxx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmgzgip.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfozgnd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2meksztiw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duodetgi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uslugsvb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pebuobfb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xonfyteb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2egvivswv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2exgwspsn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pakhagmb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnfkvvn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqloipzt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbbvuof.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dksxqdoj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbfcien.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazqeoc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmosrnp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2akroztwc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsjihfb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zngmnmlc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2isaupyfu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbvvwlf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vadxzhcz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kehdmsnd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szdoeuod.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gipcxllb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjkpnhr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlnybqw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dywcizrf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgxtjqm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnwnuck.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2frivdcvk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlmdydy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqsethg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcowdkd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gcombked.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fumsqaqo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tflctsab.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2einehfsp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fncwpbfu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpuonjt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnpainn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyedvls.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2giqgfhwp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiymelo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mndimfsk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeusssy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2puxdefbl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdnbdlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ienkacsu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmkftuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvodryxd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlmatgn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uyozobto.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tirpleji.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuksrko.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2urryqbuu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuayvgz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjxluwm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjcyxjn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uulwuzty.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2adencuup.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwygsor.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fatxdmuw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xokqunxs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmgfncz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iohizxia.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2faqhwvzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfkyyox.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xggdgeti.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxgmtzw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hddlweuz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zshatbvp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqitjnvy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrlkrsz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2chegbugf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxsmjjz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeusjmx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeamuikw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuanfzo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvixbmlb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdiyajp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhnynfr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gglvzepp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dolntxqr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtwzuhx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzuylgx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2utiuibgy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2diblrztg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpnfufe.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdauznv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvazzkn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2luwoxesl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmjbzmo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoltzja.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2euilthkq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rokectqw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyjjyba.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcsmcbc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpdcemd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktywdpci.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2imlggzpt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzyuqsw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2umsbylmd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjgqziu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ghixifrf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgoykmt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sazopzrp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgyzzqw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxdmrpg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsrhoqx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxflyphm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwibspvh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dotwjmhx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvbxhzz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgibsrf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqqfjqs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjkoxsz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2crfsrjgk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuxqdvk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvnwwiv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkszakf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbhmzke.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnrvxtz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwloanr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdesjiyc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kdplzews.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xolnxuvd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbbewkb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kupmcgeg.html


<!-- 参考信息 -->