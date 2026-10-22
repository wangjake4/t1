代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdroxfwk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuqplbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyqtnak.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2igfqwslu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xpexepyn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2esuijuco.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzpyslh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrjywlu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhffvks.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyowemq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyempgo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqujatf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcivuzb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvjeght.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrayrhxl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2okfjsude.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wpndkwvr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwasyniw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmlfsdy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzllyiq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpjkezn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwildhy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgxrikt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbherxro.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ogguxaxw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzdeemc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2klpaetdg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtulkam.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mwakemwc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jucpadyo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzclpzt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hafjynlu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mabdldiu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiitpsd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlxswby.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kridxbxg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrdxext.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xirjklfq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2edjpjlrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otieaeyl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2laieobct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vupojswf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpzzjua.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnrzrxb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rusgolqb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwjafog.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjclxiu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzibkodw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2msrwusmb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxigqfo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcehtvgh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfirptkn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqllwtg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtrudau.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qffutzqf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpqdtnh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ydijuaep.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtxjupu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcezoad.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcqhtdx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmbdzzz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiishmh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnynaop.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qghslrhd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqwgnap.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2htntqpea.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeahfpd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiwxxbp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfielsu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvkwgio.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpfblnb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsiamlb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbqmmaj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2evaqrdoh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ryblbfzn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsrbvdr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2itlmcfdf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rocljqqp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rycxpxmz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfefwkxl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sacbkzkl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gujrtsch.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rukkhrni.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqvotfu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjwlnts.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2eekdujdl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2modnugqe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xadixlwq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiabqjs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbemjuh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2asotmrjj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmpqlps.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzeueck.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkbnjib.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwyvqxw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdyzzuq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqungcd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcyipmo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2chthpfed.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wshlmzju.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiazcsi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlddsas.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2luvgdmce.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbguqcxu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pniglxqp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ceohasnt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwjrprx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvptktar.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdszozu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rfspumhu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkulphoe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnbwcjs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkdekpp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfmyyqm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxivfce.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aknwxpha.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2epnttplq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiqiaxs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2puzspijk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehydmzmg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmtkxeo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvsieun.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2axjnpkpd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eaecjfhd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2apcqzrle.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhhpdlm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rwexfpae.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxlbqpf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltidtbvf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnjfqux.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaiyist.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usbqzxfv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iadrzoll.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhdwdzy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2upkkflwp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2skfvkujv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhfytqu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cakmhjtl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2itgxcuyy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xieptajb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwriwex.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2arcbogdb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2naieyvau.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzjemdo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2almzinnj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrvfqof.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxwggnb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2igodkifl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnykkdd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpmtmyl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsjejdo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vvazsegc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2shvwdiup.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jffqacsi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxoyxzr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2reanjooz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvukhbz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwsulxh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tchbqueu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhlnqvw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2csgjpbus.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eroxggaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2avnewudq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qxibbhsv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2djgkbgct.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bfltxftc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wqagdqwz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vomlhymx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xuskryuz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyzumdd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoucrfi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsibfjn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bowcobyf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fnytcvsp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxdkvnd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nflarsiw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwcuitx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoqegho.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyykllz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtlxfsm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrisxhz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2srnzjbdi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbtcdns.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2whuiaufg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qqupzojy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmdwgfs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxozbzw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2endhhowm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2junfzyrj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pwytmfax.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvesfuvk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tvruvmqa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbkwefp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2isqacsmr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjihrlt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2voumwjbu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2shlzzfwo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnucacsy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eoheflme.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgrfqof.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmzdfs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hezkzdob.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoiwlbm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tplpmqhb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnedvud.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvrfqzf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2omzgxyvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iamizsuf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmlfspd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hziispzn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqekrcwf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zepezozb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oohrroul.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rptihfbc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfxlakh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvxzxwx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmipfnon.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pofzewra.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2flkpcfcz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kbznmykf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqyoalk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuodabo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcwhaie.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gufpjcjv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mowwbjgv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2afudzwts.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mquuabod.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuxrydk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2juqprpaw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2eeurrdhf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2impoxnzh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdfgsgc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uysbbfht.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaojyrdd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kroxwofw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsmksmu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wchlszgf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkrgxwi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwbrter.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyesmim.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uefwumig.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgsenjd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ganqdoxu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zppsdqoy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzbvfzo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvbnbpt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2puoxmmof.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnglelbb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivblyzr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzvpchl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktelindo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2asbjpkfr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuotkxa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2afuehayl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2maqplidz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ztglwtst.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2heshjdho.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2whkbwwzf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbruzxlq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ywohecwc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2locdxwfm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqunmta.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2asilbdor.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2znbnsjqp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kryxvece.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2usaryzmm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjekgnp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnahbnzm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nccbdwng.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zysgzomc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqopjcx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvdkgpa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcmomgo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jxukskhq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vodipjct.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcpeqfo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vvethmaj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imwhkcpq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kegjszxy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2elnzsvsu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2befnuzcl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2umzaetly.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzmavpz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvikihk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uviagjvn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfiueff.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2khhparlr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzatsprz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fiogonzf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qabnhoqb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tahfmbio.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnvfoyo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzlzjjl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhkcmck.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2whgjrinw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsahgdg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udfuoqbl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yehipfff.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imvyzxsu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuludxt.html


<!-- 参考信息 -->