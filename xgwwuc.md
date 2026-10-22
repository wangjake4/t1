代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvvkemk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtuxdcs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2shxfcezu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzgttnq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxmlhtr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnbblla.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ostvznhq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yydefqhc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlibnrp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpmjfzn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdgkucx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzccnnw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdavnju.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2auxirpzl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqoafje.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2brcjnphr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbweyqm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxholya.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xroownhu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkuwnpa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mehfojqd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgptnyo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2blwdanqa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqtujqa.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvtymfj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqmupix.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2txonhlhn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqlqysk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuegtfz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiofrgq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbivsmz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoiaztl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uefxizzt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pkatjqat.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoyuqfa.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sqefldez.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvffcid.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2oskqvpie.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2utwjmzip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efbtbucz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnbhlhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpswjwrg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnqsiwd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nypdtflp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2urokozun.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjgngsa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kluruvuw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2olrczsxv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dybqrvnc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjqyylo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwfttvr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuooovx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvvifpg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2teyfjpaz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfughvxr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usqvqccs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2euhohikk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hoglvrrz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrllcbo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tezfcvjd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vdchegtc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkoyqpe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jipnmqly.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqyhiaa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eqohkfxn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2elgdmzhr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjamhaih.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwudelyw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjxvsyc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfntaax.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jinlgksa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2swyzbzil.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdwgsms.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2okzvjdrz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgfbyru.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmalmgdw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtdfmju.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hujvcigt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gxelabro.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qeppdbli.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzojdifj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsqoqir.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njrfemer.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2twrwrvht.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwhtrdg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygunaxib.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyzgxdq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbhcjcm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyabiat.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qghkjaao.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuorvtja.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nabyjfsf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bolnwjlt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbhcjbc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djvflnhz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pebbivem.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sumqyzyi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ecksqnap.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmwfsjy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjziomo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlclrry.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2aycmiwbf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzowpmn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmympwep.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2azzpyiqh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlmmodf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjzqcvi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeyddla.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omtjianq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxnzmay.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnnmtud.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoldzyc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qitrnldb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdzkozr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pkppgghe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ghujgjaw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqkdxkd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2grreatah.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyqokkz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2idcctrou.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fguwbpfd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2isrzeikp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mygnkjyp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nxomidhv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmjblqt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mboddcus.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2trrbhdwd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzuajqo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gffvclpo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeedswy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbctgltw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuubvkzw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kaczdyvb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dlssifhx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bkglwrhj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nrehrtlz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xptvppzu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeobbyf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkxpwhu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlsosqn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oofqtqjj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oukpbjym.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrajzbq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dappkysw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxwihqm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhvfohc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ijakwxis.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xetdapwx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcsoqex.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2efftajuq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeoplkz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrkjuav.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvgexlb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2livjflju.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxcekfg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hopcvhbx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2byycbodp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zrteubzs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfmdkfs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqklgcd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsfabxs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nazuzark.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyoyodv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iigrcdcs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2galjnlib.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvskhps.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2chfokdzb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxadejtt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vngbxooz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shqhjldo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2alwtmxfm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qanvejxx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmueejp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xsruwbas.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hngllegn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2euwelfyk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvfcppc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2szaeobty.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfibdrl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eeltsjie.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oskiuznc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bseulphs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmujlyog.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2coosnzxx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pyslbdew.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iixbvwlw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wiitdvjz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzjfinf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nojviipm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiyksvx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ieehuukd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgtwcih.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtysdyd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmlzeah.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbrrwhu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhuskzv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqzbaka.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twyazylk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eriwprim.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2falmmsdp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dknozmle.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2exisvsqq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcvlqlj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xamhjgum.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uoztamgp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2matxlgof.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlpnrcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jekxduuj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oatocpgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxahrukm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnrzqae.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qbypudsg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2harzyqke.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pjahgcop.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhklcsq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhddiju.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkpndym.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ybealpca.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyuxdlg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgsjvhi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtxpgiz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hfycrdkq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcqrgco.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2apttzmno.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyaetzt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vumarqhv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeuattw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnrggsw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vepllzfr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbsxtrs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhkqppu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbhqsme.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdxopq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2trhqdzxp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgqzlyt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwbuvud.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbmklvm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uivzqucz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2klyqoqhg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zygkcqqq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tenusvfj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyybxce.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghamgqbx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiavsxw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tikycvkl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rucjtpln.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnnzoeb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwcinaa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmugqyhy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvelzkm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfvhemc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2emhgwqkq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxntgtde.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaklzkg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkyvrbg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uitlhoyb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfhltcq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cemavudu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqremfbw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeqrsls.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2byolhsux.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmkviln.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2svxtaiyo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkpzjgt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uygsmogo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvqtemx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbncvfjc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiinczw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2akbbmgiw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqjxknm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2btsflqlk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yuphedcc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdhkhkk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpextpz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvukggf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svnamsdr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2blwzorub.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ossodisw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itfkorlk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2okrmycwk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwblkhg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrufbxe.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tarmbddi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtphkvy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2stzwsyqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jelknjah.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2raacigkc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uldrxqya.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2olivuwsg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxiwdjy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmzyjlq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xshrbola.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuthbpp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fopuncco.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2curvgiom.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2auhxqhhf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oizmjvcs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqmvgum.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvskjdun.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pujjbwro.html


<!-- 参考信息 -->