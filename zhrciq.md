代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbwylvk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atspdpfp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gohzfygk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agkavdbr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnposqh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpdxvxu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlnmxlx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbwkzda.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhmkrnq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hddogunv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gthdkaro.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwarohs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhynyrc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrcispj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wahurxci.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uajsfdui.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdivhzk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiummot.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdheckoc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uncnlifu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2imwcuhxv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhnsjse.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcduvzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvexdtil.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdvtiuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ueillvdo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rvolopcx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqtxpum.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmaqnfe.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlxjhwg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfyeytj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhwayhd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbowiea.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdlqwoz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqciyvx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkcfquy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjerzjo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2afqjclfd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgyywhv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxyxjwc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2smrvgvwj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gubvlxko.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnxuzbd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkzqniz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrvwhjn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfhyphg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpfikzq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fieeeqnx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxubmnr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnhimtc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpgrgja.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggalpkes.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iphoqjnk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsugkqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxlhhxy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mysvjqhb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoswprf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mtctdifu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2biprcvbz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qesaxluc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rotatapw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdpinpx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrztuir.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hageqtjt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zorqxavm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2akomrbig.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhzwtqh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgbyfng.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szqhtuyp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzdbker.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbilitfy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzlzlgs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaitswj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2adugcrry.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwytkxib.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iqizfgso.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yopjibhc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rozaxmam.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuteqqp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2doemoeyo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2msdtcfsv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqwjtup.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rccrvjrj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxjggtf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oblpaqxl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhtewpp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkveeap.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbpunvo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nszutkqr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wolnpwwy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcyxdiu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrmecvo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgzzyxk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvppjbz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqbjkct.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2meauxuuj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfurehj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdrvmar.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uthxhcrp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrnrlzu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eunbqzee.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcfrlut.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dipetqyj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crwqpayj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzblomoo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmcsrqp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhghnoe.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoinuvj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjlmzny.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqsoddz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuzatmr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2goviztbo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjebnvw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqowhwt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgyzrjs.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpdhtab.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxlptrg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmpmdtk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcgvrlo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gooqohka.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2iporybqq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2csexkrsd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2euahkuco.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xggkodlm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emmtfqjt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhdwdew.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjnuerv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uddpminu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2agtownmi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2piflrrki.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gboyylxu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jrscbmmy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlbxahx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cafwnyvp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wktcklmz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmxayvz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2frjnugwn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaekvqq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkllxpln.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnyklul.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbjsepp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lnojyuik.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mulyieoi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdqwgwz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gobjbipw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvnumnp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yusjuyey.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cptcvzmo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2weazwwle.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyxrave.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vuijxnom.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2knskewdu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqproym.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oftuxwlh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsiiozt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxarjupc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmbzhqy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyhvebe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ishhkute.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eetzjvbv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zhargnwa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqtrmlq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcuvagn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwjslfg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbcalhv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfelafgp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlogsrtg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2msmumlnj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmwired.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gfznswak.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwksnvv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bddgihtw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yimgaxhz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mkotxcsp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2emkigssy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bijiwayp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uywhtftx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsjpzba.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaalprr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdqjzvs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlfdiax.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lonlkqjm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gdestesl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2imfvtgso.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbqnfjw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbxwtfa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2opclviwf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2alupgglt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vevvhuzn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpkdklx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rpllwuej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trtbaxbf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqemwkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpyfyaq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ercmilwr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlvsalm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vluzfglb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgcwqtw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2klrgiuxk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxoasdb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdgdlhe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwaojas.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhdwfap.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tflohfza.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2njtrbuta.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyveqfo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2irnyikvr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2clzurjbr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rumodphb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iksmqnwe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2revixdie.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2urqqwzmj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlhavtl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dheeplne.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyssdal.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jagywgqa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2absqtnbi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtsfzmf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwvqhjv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyppyut.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfjznzj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrsndmi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvikwrci.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iuazwhev.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqqoibr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vytwylsq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rykehogs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzqelar.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnusxtlv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rifxjfbx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuezdmtj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcixwyc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqeamtl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzvrofj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcikhgcl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2otxccjqr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2socekbjs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkiynut.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbwsmsv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eizjwleo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqojbrj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdayylw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlmxqsy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhskjyk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtoypfj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrtacuv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2onudxcft.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iavyfurd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vovmeeie.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2weayjrhr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsholuiv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2boyfpced.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaetcrl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmqnxqp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdwqsdh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfzamhe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuzxtnn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2anmvamjn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dttzdxpd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aenthtti.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zyluezgi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnfmrgo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wclptfva.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kitwxzvl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlzqbvh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zebscxre.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjraklp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvlnwyk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pkalzoid.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epankwqw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhmbioc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dltycvil.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hojhbzqb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zswctfah.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nzryzuqu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xupkmefh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrsrcod.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2azzzheea.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fozoiuur.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgnxaej.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzhicje.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lzazlwsh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arrvxhqx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2knttbxvn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwudwei.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2huwmfndl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2adrqezey.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkczjlh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlhbyrd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoeymuc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rojhdlvn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfzvwmy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2llcfsdvm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dplsurtg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujruespb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2agwavwmd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2svldlquh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsastlyt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsubziv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2afysacyj.html


<!-- 参考信息 -->