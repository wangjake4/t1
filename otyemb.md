代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2adhdjszo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtddxqk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2npunntel.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2klgapqgp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtzzusl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2outnaglz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqwnend.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ephxlwdm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drntmgie.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tovsddxm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcqtmfu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xccwrgck.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcplfqyj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsdxqbe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzephub.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hlopeyag.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeycseq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jfriwjgw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eavsykqc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmjfqke.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiajqzo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaljspf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrsoqob.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxstnpv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iiopkxjs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2twguyaav.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjgqzty.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2siwxddza.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbhmhkg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2newfosqj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lpetyakh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdevfejh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhijupx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdkontn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fordbxkt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvimjsi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jegvqbsd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bubfqwko.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaubxyc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbvsxdr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mpldybxh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jomtgdcx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfknluu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2knufnyqt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hetfhuth.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2njlcnkrf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezsijjf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bqotlple.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zinmject.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsjqslh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqbbvmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgupyav.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qexslvdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfziivl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2caznmosy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2znyglupy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2flccdcpg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwbomyk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpkkpyc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcgixpr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tzykviaf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmtmcki.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjzthlw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzehkik.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvkftjs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vtspvimd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iecnxelj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxrilsp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tmervqli.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tuskwiab.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzvkxec.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrpreyq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgrrkdi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzqqrjh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2igtwingo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tchbvsrs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tnczxaus.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbaqcco.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gevrbtao.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvctexoi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2chjaqjhv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdaephm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxjtdyf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cmebhldl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnqebvo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tuquzuws.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwjeotf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2seuoebde.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkknkokk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzzxwat.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcxqdap.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxvraqs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2waiahica.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmykffb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iteyftrk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyqoaka.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wozxmeis.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnikaes.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnchlbc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnyawkk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sarykkxk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtjfvgg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxnytln.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnajuaf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbosujcj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eprsrzap.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kycbfxco.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tksxsbgh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bogvibvh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzclmbi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbfkjog.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjzszaj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xooorvnc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2amqqmhtr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbmwkqw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aglipjbb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpxnyrj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rmghowmg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecusaxbr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dljywqil.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsqonox.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2brwgvgjo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlozvrlg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkrcrmd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeukyrt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxcrvex.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uqddxyhn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqesblk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyszjqi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbvqwfm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzwnfzs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdwuaar.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfaxrzg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ombzjfjn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2stzengrs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nynszvto.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2abykbezb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2umrxpebw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vjumdnux.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzuccdc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbrxsqh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2brqdpekq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkacngp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgqkcbc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhwgqgx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgzguvs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yikyfprz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiwbvpn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rutzagdn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfafmxc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjtwqpa.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avzhtxsb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcqgutx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpjwtei.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znypjnqt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bubiyefa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjsyrot.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcxtqyq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzsuazo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dellsfvj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2agfjoijs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkxdhuz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swwppyqh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyvcbzf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jklppvma.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvvesbi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swwohgss.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kgywivqj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkdusrp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2afkgfdsa.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2igkwpyap.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fyggbetl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbvmrxc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xycrfymr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyddwfl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xivsnrlx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwubtxo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtahxpf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2stdantri.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2erfahdow.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvjdugi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpcqufh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hokawvqj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaahesl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaonpza.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2clkdhxtm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcttith.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2clguoyyz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gzypwrrp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dukgfexx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwpozfw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeosxop.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lonspnxe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2trgaszyt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgimdho.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfuzoua.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtqgaqj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2duqjxkti.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yhswkaqd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2chsrphtu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnhzihn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2spntumje.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2adhfdync.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqxqeva.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwksjcx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtroull.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdtozwb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxxoaqq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjtqdle.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brgvjpzd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bwinmixm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2izosnbxm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2sixwwwsv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lelqkrfb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdufvxp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxlhbju.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlcaaih.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ktceejni.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpogbtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmmuwac.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zummrjqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkypyvvq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrvakli.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhwkjvc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oymkjaby.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbakgzt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2idailzov.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfzznpf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2griqhqtp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsyrocc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2juaelxll.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qryjydth.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tatflgsz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsgyjvn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dkljocgt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oheocjje.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2eumnobsn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hduotfum.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmkzxwm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2behwrswl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrwezra.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpbqywi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhntmzrt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvejjuc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2chudyvqz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmeshee.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkghwkls.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsffysh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2arnnbhgf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpooyjc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqvkvux.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bsakqgua.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2eufleujv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yydjmkys.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oivvyhry.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2byobrwqs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyggnzn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaajttk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkaozyk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqjwqvd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnkkgaf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgdfeye.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpohclqk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyqwhvu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2boabilep.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hyumgkrm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiozlnr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lwifykes.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fszcftns.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmspmhgf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvavgqyw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbpxzpt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2afbgsadp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2txsqfqim.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzthutpu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2womcjbji.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgesdqcy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2whnvqcil.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbwpimq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znaxuscr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzfbdst.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhcwkwb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocywgmuj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wysjtiur.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qckudmct.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcuyogj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zhigojhf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2skwfpgjc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbxwaup.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pslkzvjl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2llsdfayv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2itdpsuol.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rogmoybh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdnqzwp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uszcrdba.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izfozkhu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjytcusv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oswtpfsx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpnmufk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2udyjcrlb.html


<!-- 参考信息 -->