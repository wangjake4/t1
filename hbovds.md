代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emhqvjuk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbaezll.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpoxuzi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lgseiukn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2beprewfz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjyydwr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoszjxv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uzksggfh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2teferepq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2czaaufqf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yawaolrc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yerpggha.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hilnjvbm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjwzowa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tlydjchm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwhkaue.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oefuzgbu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhkvfgz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hutrsvgm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2viovlate.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoeomov.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afuilkom.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmzpnhj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqmoeoc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpsbuux.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grzxdpzs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bidihnyw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrjmzzj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yemfwjzz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmazopb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2csspxwtl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtatjtvn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlhxyeu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwclufa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpvimvb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzlsggr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvptqqiu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoxwlha.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiyystk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpzazpx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvmmbcw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2olcmqgaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2etptrpjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czxvlcfz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhntcrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiqsejx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtwdahy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2umppgqtr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwuaaaz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qwalgkhm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhxyick.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmwzbnw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2casqbycn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fapmrspo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbtuqga.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtqelnp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkugoar.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrljwsd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awzcdfzj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqmiwjz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yoprtpgu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jliotncx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbxduxk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pulvftcy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2efmapzjd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cktdjysr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uvurmzdc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2moynnddw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nimfzrcx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzrlfzz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2upnqyvog.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgcljxw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gzorecft.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyugvqk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxbovxd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiszwdo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhpghfg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oauvwqgd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpieezg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djlrpmyh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqpudnf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2anscvvpx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjtzirh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wryayjar.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkxaqwp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2optyylbq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmhthic.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2crmjvfor.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oftzzozy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcffhzhn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nebbldea.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wckhefdu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxlhofj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtgbert.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgnugrs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aougjykw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbwcrdb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewugmqse.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2azspidxa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdvhftc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brpedgdb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfdavpe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgigyhq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhvkrcw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zowlumxb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqwyoyz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2txpgzuhs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhomyhs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqbmlfp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdoecuq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxnikih.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dssmdjda.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfspqjgo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qggtohsi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whqzqvhe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sogawssi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtjdbpb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzvfumd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnstsot.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrjwayg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdkxdjk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2frfutfgx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhackvn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2opfstasg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knhabkif.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fyigqnju.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2urcplpbd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sackkuny.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqyeiqe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaegbbv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lozaupfs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgqjgkq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2klkzcwmp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2apprkcby.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dykhwpao.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjhesai.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gfposqyr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zstmcvyx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnrjnyi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvihyla.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xskqdwwm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2syqirxot.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyifeqo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2somzduox.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtzeqyo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzekqctg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiibcmx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvkpthl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vzovychv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hznhjmtv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpyljgp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaxuxyq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaxctmm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mngritsy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hupiovwx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsubkel.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrplvrz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqebdoog.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaqrhoh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2onithmdr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjiftwc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2efhboprb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nobrbhks.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrfbrrc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnmiqpr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxyxtnt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2phfbdawz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdapulq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkqvyvq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrvlwmj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hltgrqoz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uprtfdgc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mighjpet.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wklyysfn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbcoxuz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tkayzzhe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wplmpzgb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjzdygg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfqaioa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwkczrq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqfdpkp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjuonhp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2isrvxhlo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnyacbk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2csqrcrjj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcvrzgs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iibjyhpr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrogcbr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkoxtiy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wsemdvdo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfvqrbb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ulssdqlp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2marwjndd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxpoumj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqjxrce.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hotfdwbh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgndfal.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpqcziq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvlwwks.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iogujneb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbseplw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ackuhwft.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2opfnrvgi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dcafgwsc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdgtftp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmhekcd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsodooae.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2znyngpfo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hewvlejk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnisbsa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kgutcghm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojegipgq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkhoruh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyltkhyh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rrktvbju.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcwmppt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbrgwtg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqxueox.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pswastho.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaoigaa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2elzytfun.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wbshhalq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2czuhrrtk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtaxjjf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdurkcq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jbboygcp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxikwlr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsgldnn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2oulztdxo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjofqbf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsynfga.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwhqype.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmmcdiu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjktrwr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdktzpzm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnxvzqw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkdxpud.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkauxtmg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yohqdrgr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuoezcb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhxjlvt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fkirugph.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgljkmc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wrspilgv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdytvimr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjwgkfi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hceoxjhl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqvytck.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuilkph.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiljwcn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukndopdz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzdbzrn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwadndwm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbhxpvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsbeveo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxnthgy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2becylcdc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nzczmger.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2akcpjiuf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xaklpuix.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxidzci.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfwpmxa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdnukin.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbubpqb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwjsqbp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2inthmghx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfsjdik.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zygrlusy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrlxjng.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lsanppwe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kriecarp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ttptrkiw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xelmgejz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opjvcyok.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpmrkwp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfnmxbn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ravpdlqs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlbcekt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwfadbd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmjzziz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eixzwlgd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acroylyk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eimdabzs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yasoknop.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlzyeaa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsxcqpe.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbknmiz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ospyrahj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eindjxzc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vizubxzi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fupnkluw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmjbpdk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfyonog.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaavizuq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmftikzi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtiwhng.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzzwohy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kscrscvp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfzrlid.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gowhlrsi.html


<!-- 参考信息 -->