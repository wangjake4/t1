代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elhayqur.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjiwaab.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlnklek.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgtulgg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpykfcqz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2akvxpxva.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvxsoah.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyzvhhm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwroirn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fanqcorl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2anoeegel.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvxkyqz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sasfshyn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwmxamo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfgxuag.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcbulhv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rojmyuvh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2suntrsnf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2suzngmwo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pbissxhs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2focgvkcq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkznxbid.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rccnmmmr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlvsnuv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2esabiuxe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkypefd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kuytidmg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csjdbdbp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rfybdiai.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zabnubql.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpqqnjz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuxbmxc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdqqdqo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sczynxav.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qiduqvvd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhepoka.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlrnycl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2buxvnsgh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toxcbdlz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwhjvuz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2srrhdini.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyrrlyo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pawjoxch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbcytas.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjuukbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmkuzvh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qzspvcpv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpeunul.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pwavgfiy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2boryvikb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gklizwmp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2epklpwnm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiaeeio.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bboqejnz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nznbzbkf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqrwhnc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeymswg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnalsbh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wguvrcpz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dweyoyzg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qatxnhja.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeghpla.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdhnled.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbiokyq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ublheohs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoubfxz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iezrmjal.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vukesbpv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gptahbrl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2asepxegm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqpcnsd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbabyzz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqmfaby.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmkqsqy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcvkipz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2agdhqwcu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoeazvp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtjaxys.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjalrel.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akhpjxhr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbtjcic.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgkrsus.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jedvonqd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyyqwpj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnfihtz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvkimuj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxetokpf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxmzbbs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2innisora.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2savokwfo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjwawpb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sojugtjm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyycrcvp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hourgomd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zidrjezt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoppbkwq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqkxcfv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhqwewh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2duwrdrzs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiqaqsf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqotzqcc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhywkdu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rayswvvt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfgdbtw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcztqzko.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jgntmzlw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjgtmxk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpbkitv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbisjhyb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vtywuafb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkdvzho.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkjbzsb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpzfvwu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtrcbau.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxdovlz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2grmszzwl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2woltsllx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2usdtjnfe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lovbjaho.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkokkqi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nybxgcjb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2idhsswrr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2isopsrke.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaxescc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsoceuf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbtbrvg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeosryb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdlieyy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oarddveq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbxjnnk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kectlnyl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nihpnhgx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2duynjppu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2whmzysdy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkotcyr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjndaqu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwkeenm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcumwle.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqsllaz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xiynepop.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcjwrga.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcjosah.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bhemgocp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwycvlr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptipojjq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mluihitl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjrrvlc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2giebgrrf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sujwfuoj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nydafjan.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhjvdds.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2skybqsnd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2esharsli.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhnggnm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxfxhby.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bwynxpge.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsvmdkf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jksbjvor.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaebvyz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbkupmv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2juhetjrg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2grbypewt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xomqnycq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvupnhi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cnouuods.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbamwxp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2knbzzitj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fexlbemi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhagpwc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmmavvt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwoejac.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxwzgiw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bqymalzt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2weilobjp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yomgoduj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kcknyqwf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vpktrgsx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtpraso.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxjqqdr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rebpyvnt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaexqtd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiyhvky.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhfsqmx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nhswygqn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jigbgoby.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jauzuunm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfzleab.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpksqss.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zmalyvfm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nczcpszv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oniadmrp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hpewaqin.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmeclfm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bptqazcb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jssywhlo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nxztffza.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hsifbfka.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qgebxznd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsgbhim.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfmydyz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpahrexh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paaqnsjj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rflhozwm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qccaqzdb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcbzeyt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsfqvjv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlosqgg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2aroddyjh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2opiggmze.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dttszbls.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqufaim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvrakvq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjdasth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrlecqy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2geimtizd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xtavluns.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzebhgt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2imlqtybn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2afridnyt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fofncosq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzsqjlc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2avjutfyn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryerzygi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2shifeuhn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqccein.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnbtnsf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqtpehp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cukaoxnv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxvmurw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxerola.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhmduiv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sktqmjos.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhrvtxs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvtewjr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsejvfaq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kiajwine.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrasikw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qctzxpgh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtocsghg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbzfyaq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oossnpzt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pxctjwzb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqvnoed.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gughotxz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsygjgv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpiondt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2koenewut.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kabkqdti.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxanrzle.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuvjxez.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzdpswk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuftoymi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lifizjfr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zommvloh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcziyovu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmxyigw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlydvwz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhzydsa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcyqwpj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzkdwta.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cplrdmcg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqonmbfz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzisegzo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhvkuip.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxtfqix.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bfemzpui.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfphecrf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdhvriz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bebgudzy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcbnoui.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmitsafz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2foohilpi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2igbqpbln.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkmwsto.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zutvnkao.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnrbiat.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjlmaol.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2igkvmsrv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bolvgkch.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2diubgkbg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cseeddap.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlrwmvk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlwpzdz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoffhhf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xorhwhxj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kayfrcdc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dngjggga.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpejjlgq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzrwasg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrdrrtb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtiotqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rffoqovk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gwexinlr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2afxzjgzd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdygwjf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvkfucl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2scgcqxlm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2guvpkvzg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2szfgdkmq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbuckhb.html


<!-- 参考信息 -->