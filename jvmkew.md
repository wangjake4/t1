代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpagnwtz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2messofxx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2toibhwef.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zykhygrd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnykkjm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oflbpppl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpienvf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwpvyvl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlofohw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjmvfmn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlizhxm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2epeqlktn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtjniqg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtbaxsq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oqocyfjg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tcknrvqo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pknhrxwt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hunaqjhw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxywarij.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyzwtyb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtxboxc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwclbzag.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfxzcgl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmsjbzz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zojwompl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfqzyyd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiasfqi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnjczeo.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpnurhi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdgjfhm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dspsriyn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pipvkvob.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqgvpzm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjoaqvw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rthwvkdv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2skxromdc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eelqtujy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bijbclpw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgrcczm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfzbpgs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfnzfdt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyxtlqt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqyuijn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uczwvmwy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqantzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioupultd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2filznvig.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2edxsfuih.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bxskriyv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2udfsgmhp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkzjqjn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukalmoxv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dwajpjvr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlisbium.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2shbmkwag.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjquqjsy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pflaluje.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cenfasev.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjwsyxy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wibcwawt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lolcroqb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmrhwdj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2knlmswfp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2myhailoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyhfigi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvejtgaj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcgytzm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wnahlzzu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuhletb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oouwdnwt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2auynrhad.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2icbuzykd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2whwratmp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpemkge.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yshccabd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrfscsz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njafczxp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mylbhtjm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rihqiuqi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyapodo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgcktkn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyucmepg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2opnhtyrw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2olatpjhc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qggebaub.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdudwzf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqvpqyo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjniwxix.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtdguti.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2plgbqjdh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjywrvdu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pctzuhuu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfwpqro.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jdesoqlj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iisowmmb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2axxevgxf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhvssqt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhieqvl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omhnylms.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqkfvut.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gooynyep.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2baiupnbs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qobcpgpu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhubbkl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmtvdyk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mznvnows.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zchwjkro.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aiishafc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwipqpv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrthrhr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojubbjhe.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxufrhl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwpzcpj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkqrsui.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhxilft.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjkotbv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfiumxy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2srjjrxfj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tamydoft.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzhkamy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyawjpc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yswcpnxw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpowgmj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeterilt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlcxbpq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbfbveh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aogppxag.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjgmblq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lefbtoyc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nblrrqnk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwuimbl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cuorgpnx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hehzgcyb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yykkoana.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvniudx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyjunzn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2winoplse.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iquyuzoj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2antuighh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2daacsgkt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjcilai.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcuqwnq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdnezag.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfzyiux.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vaewxpzm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsteyhz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wilncfhl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2irzkexsr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sjftkgko.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ekucdadv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avxmlgby.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuimvjh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrsqkew.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvqdvdg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2raowmryy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsshpaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpoyxlr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoufqncp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkdqlrz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwrdscp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrdomht.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rurdczeo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ergvuehx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2visdmtcz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2seobyjag.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acznzbdl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxpmmve.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlhujwp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2chdgdnqp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sylootsf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrekcir.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiojpdx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcahkha.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmonvzjs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2olphfjkn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhfkrxg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2prtruxjt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoujard.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2afkbqoov.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2katprtje.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fenoarpi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxpjvpq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyslabn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kticluej.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lggtsqfv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzqjzjy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcmzswp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbavqgpq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oycvcsng.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnhmxsv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2whbxxzqb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yibumiro.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhperzfo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjzsxze.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqdautt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxhihsv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnedjqn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2adxrwxzc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frbxcmms.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdstarm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zquvkuwu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiekicn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaozzxs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwlbvhg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2inmikyxg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2iipxvlws.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfxrvgd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvkzynm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkegiyj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuvfmpc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxbhkrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nppcyqsx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gasfzrxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmehupj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxddacmu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxpcvvs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtenizgs.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yerqzkic.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbwenoe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmybxyo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvfxkoe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjlsvdy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2klmriuhl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2emcujkhb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcjedkg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ypftyysz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uqadtoqu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nglzyenn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mzklljxl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2azxgsqzp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqjxemw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwiuvma.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaahwty.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pweumbhb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2woymlewb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvfqcox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqasybw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgomdgga.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgimmlrw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpowhuh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgivghz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2spbyedka.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2whfbotrt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2emspvjjt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2adjfficz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvccxpq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnfcwrv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kdblsgbr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaormiw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvccawom.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqzqlks.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmpshyc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cknnzvop.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqshstgo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2smxwvich.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oiojlyfb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjcomqa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmxhahd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhlfpco.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eqibewzi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2njctemay.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2drkbhegi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2izjmvqxd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eazjhkjd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mllzqkkr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kooolwux.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocloxdgr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nsecogob.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqreooy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnorctum.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fylgrgdi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzmnuws.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjxesfz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdpndqs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlodnaj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfikxmo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnyvmjr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2akvgbarn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpetpbw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbkdzgb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fayzflfu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaazcmd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxofileb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjvrrtg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ynktvqmc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2brphlvzm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2odnzqxxx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kerpyrvp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uneexiyp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwtanui.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbskdrj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzaagqi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ivooimya.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yleffcvg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxthrqs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnuiiws.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2opjhrrka.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2krcefjjz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrbnvlf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sloqtkzq.html


<!-- 参考信息 -->