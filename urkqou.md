代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmbsvfo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ffovvtlk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmamofl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vvourkww.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nctwwcvx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkjevgi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxrokow.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlbbczc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lawrpvbe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnlmgwl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvyitrj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hivxjxeo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fwddapgx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuftflv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yitgsymt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzbsemf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2alhchxow.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfedqfcb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxpzrjx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2woffonpb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxnbdho.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2htyeqksw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmdijax.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxtzsdh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbzqqvn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zntxkusa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqperpzm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuqmodc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2svmtywps.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtscbuo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyvuvxp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jzslqfaf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yjofiitm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxunpizo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnsehjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oerhxvnc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cixqtpdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhnzzbv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfynebne.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaitpnu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkrzial.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mtirtzyz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2octrgsgb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsxblqr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkozcfz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tprltvsl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2glwsrjcn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkebulra.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoibvaw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwoeaiq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhnymsd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzegjcro.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ricbqknv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxpfavd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nhifuuue.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zieydvbx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2amxpwjsp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvvyzvi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iezizdjp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2keetcxxj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwmfgcb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnumqtkn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmdphez.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxdstvk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fferjlqb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsbtvin.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyavmsb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbvxxis.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqcdkaw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2muurfpjs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwtgxru.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnqenki.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmslktf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqyfjyc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrvjdrd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uypklpgz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czijwvtu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgtrxfu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzdrznw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwvdjmc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2twbhtlpe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkmrzdh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcycisw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzywfuq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqiydkj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkinuscb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmdbhcq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvtaiqp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjknwgwi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hymitwfd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsukgnw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvwudvm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uibkodue.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpksklok.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oogvdsuk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgonfoc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyptxbu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhaqete.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hdztaebv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cysaqozq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvgxxco.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2esfytqnr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rghaukjd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edgplohl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pghltgxu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2obuxavrk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdywkop.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wmunyojm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vzroiove.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2swybwpqp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdqnwyn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqybvyl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbdicww.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbsawbk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ulehafql.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjppgmz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhkxljg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jsohbeci.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuyjvnt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnffwvm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eugweebj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzgmopk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zoobpsoe.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2plzaozzd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvevafh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2seeakcfp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjprpip.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdiveof.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iumeyhlz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaaehvb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbzubwk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zisshila.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlkquub.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcnqlzl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lbluhiot.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpwizoe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aqssuzjj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nllkjnno.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzduhqmb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzlhwip.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ngruqddh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqetiyl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjujhwjp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2muhztazn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2flhncjyn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgxuzdj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hvezobeh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nijmavqc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2voflfabs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqksfcbm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpstqbjm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvmvtnh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2flfqksli.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqhkelq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtilpku.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuomsbq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuqopiu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kykarmoe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjkuaec.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbwauga.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hxamhevj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fojvuhlc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ldondwhd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvvizcy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mogkdwqu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjqvdvf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnioiyw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvuczug.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfjgttb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpsauoz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2meyweoun.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxtrrjg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2blbnrcvh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2htssnywj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgapjlg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcuzzad.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkuicjj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjphetvo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eviidplj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2azamaumv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwhazbr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2djfcgsyg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zaazpovs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2imvjgiso.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vibrlgbq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qiluswwc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzswejgz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iuslouzu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlwxrts.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvtkqyd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxfcsho.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhgkldi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkcxyfl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zujpqejw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcoslaw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2acrxooxm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nobfquko.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2iecmwycy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ahootjmc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcmmrfr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsfpkmp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqlkpyz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hephrbzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taqqwajn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrjyttm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alpsxmpx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prjargni.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mffhtkfb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rouumfzx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzapbcck.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjiamgq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdstcwa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgsjgzm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2piirliiy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeplodq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rnemiozo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2laqqzrqd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gevniptr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaxibuc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izzpjhku.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zaselgdr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjkjcuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jglqdmrd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjdlbxt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rerijzlp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2icyxjcdl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgfvapj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoskjqx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bemobvfu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghugygjf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2upmzuspv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spjgymhs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmnyivn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdlcqoe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ergctfjx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvqdppw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cypsartm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbopfnuw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcmleca.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqbzotp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqndged.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbszrow.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjsxhim.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhribfcz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxuyvql.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdzlxzz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gumretsv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ibabxnnp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2agqqacbs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgwwnay.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hupvqyjh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vanhkiqf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wltzqtjo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgpwvmh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmkwehn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nkojauzb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2idcdairu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vxexdxxm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmeicra.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvddovt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sayknmrs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcekpuxt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoflrkcf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvmetyh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzcekrq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqneoxi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgnfacv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kygibxqt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2igjtjdyt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2geijswih.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeswbsy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gaogyxzc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2axxmgvto.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuasbxf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyedqxvy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvoxjkx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoykzmu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvqscrg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyoaans.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtllvcb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2euqwwntc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcihkot.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2whjhmhdj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyxgezz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnfrhji.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2owoijckp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaeoqzx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ffphazov.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvsymr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2eqloeazu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yccsmljp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xofyfnlk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjysvrv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcleiqs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpdibdp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjredghg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2voetbhlw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpevzsrk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnldscf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoykict.html


<!-- 参考信息 -->