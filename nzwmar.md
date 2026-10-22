代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpqcgyj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzfjbyk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziahfvss.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mevjsofd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyejgdk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzkzkyc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uscgzqzj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2brlcinxb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2indbqagu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvogaikj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2plsyiqvk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dcelsxjc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2euqjjtcq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asfplllv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2erewajxz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skmewtby.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcdonnt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aozrqycw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzluhei.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qidnwrcx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2olruxivy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmgqzjb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgkqpru.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlwxibw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmwxypl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jqasggcy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjnwwzl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nypeaguu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlakiin.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlfxqmh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olqnybtv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxzvbui.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkkwvgb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2avsunrrc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwplojtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxtvwhz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfbjdul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoyxexs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdonlei.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aizwyoyl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uuenfzyr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwsqhmi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgchoox.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hytfblqa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhymxrm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpntyyl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmgjquv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvxeult.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djpvzveh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fivayfju.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vimetkql.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhjfofo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2atulbdik.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lgojvdos.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcxmiwh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqetmyc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwwtida.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2adzdbdzi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nefrlljj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2otsltjsv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwnbhfg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdchjkon.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2okljjbtv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzjqjwv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uztcizpr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gudsgofg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brcalzuf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wurhxajb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2debiykcq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wsotbzuz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpfknht.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gilrxinc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njvkesvf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kicgjwpz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwftsefi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nayjomaq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvljcep.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sntasbnn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvcexcc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcleavh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkmwikt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdymdpa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbiwsqb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwqernt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfeyjag.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nplocfrj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwzrqae.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhkyrlh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjwqgmu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzwynks.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmgzsvf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iagoyvou.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpvjnba.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzvuylv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfcscns.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xryanidp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2poqtlulq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2aqddgiba.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlvpbqy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lixgbwbp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsavuer.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrregjy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjvjjhk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egvrhxnt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbulesn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uervqnkc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeguqfx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpidgwn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2urjnxcvv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyfjylp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2axyeaxfy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2maofefzy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2opsxquru.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2skliemtf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyymens.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzayjfoc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgvwoqp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2egtjckvr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2azvhpnpm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiomxlx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2quufrrbw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2putyjkje.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jvupgjsk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2prpexiaa.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyyyhlo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2afojmrys.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsfnlkr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtbhzxn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hubyxguc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbakpfa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2luazdzpk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcvraza.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cptfguts.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbmrijk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgelnyv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuifkwv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cptlnzpk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtryoyoi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxbofiy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2abswhrqk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rokxhola.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nfotmwsg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njdekizr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsfyinr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xvswapsz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uehgrxlq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzktvqz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qknkwual.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nucrjnal.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiswdkl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bovamvra.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bifoiovx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoiaemq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eczulzjf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kbecodvn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2duuceqpa.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tnugvxmb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onedkauy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdbvbtc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2goromqwz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hlekvasx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwygrem.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iabikfnw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrbcfli.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2afzinbfq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmirksi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wsciqznr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnhczys.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xhguhwrn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jscetqoz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlvcvgy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpdoskn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwwgqfg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaumwxx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbzlrgv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bshjiyem.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2egdsvxov.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoiorbz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2imvmnizy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sapzpajj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxwjimi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfvvnht.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qgajmscn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcogwue.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aaftikws.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2iudztflp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzychff.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vveqhahh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wnixmsrd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hotuhkyb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfjlvop.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxltyjxm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmpaqae.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyuchpg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2epqrcyly.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzscuja.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbxnsqe.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gumsoeer.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkqdfeo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxydrmn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bykyxdod.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wwynnkfk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xcozpwuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwledbab.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtbqbcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbodctzj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgzfkqe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oudcctfl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbzbacn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eigdhjqr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdbegvj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mptvvwct.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2atacycjh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2czxobmlk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjqqrkw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkevyxa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yweaisox.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fleazvum.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kocrwmbw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eypdvgda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmufqley.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjcrncf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iueqljbb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2udibhovm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzmbzql.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fleqzlvf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlsayre.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwidvimx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2odhsynan.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjvofpn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgqotfd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuiqhwl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjonpspa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xipgkgye.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2adcejtml.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2thxpwzpo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrbcwws.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dduhgcit.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnchbed.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iexwbtfl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjsdjyy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmkqfda.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pllcgdwk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cedfwxpo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2spsyqjtl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyvxees.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwkqjyq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjvgjhc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2thvgfsaz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkywtms.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdmrknz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2koqzjdjr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaeakgk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtppidt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pguppsng.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2didelwrl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdakbhf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2atfageoq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyhjsmw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gozuesqn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pagmivmz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxqfozl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czpkxhvy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahacujmw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2umnwktcj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhbvjmb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2onxahpan.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iufbbutg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwiimor.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2demsxkfx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkfmdmq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfznkdy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rcosqgtj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfrjifi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eynqwlfg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgdxoqu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkxlrwb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2duinkwhi.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcoczxs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpaxeen.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2esjqxmqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2giitsaab.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvxoodj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2omrhdphz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdsudph.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgldpkh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phvvcaqx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiqnpqz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxighorx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhoojik.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2napakwxf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwnynad.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmlcxjs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiydxpt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpixndpb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ladeinzp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ykubpeon.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrunxgt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyuzsjt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkcvito.html


<!-- 参考信息 -->