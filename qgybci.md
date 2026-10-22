代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qspujdhy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjybnxwl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2otkhcont.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olnpgkwn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvnnobh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfawztti.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwjckzu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrtxfds.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2olwydpyg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2joejaliu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbasafnz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjtmbyj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2collirqg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vbddsdhf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvntcyr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfurfmf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2trytpgcs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvorggbg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfglsxdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgjaaem.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2whzsontq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llrxilcu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cjissrgi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqgrflb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ashlejha.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ycelbuaw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jedanqxp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqshuzc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2siswyrxt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2unfemyco.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fisztxgh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2teitbwwz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjmleqy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ioowohtb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvthyeo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcczrgu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2behmpiab.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rshewhqe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqojyka.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgiwawo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uyscyiud.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kutfncfp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oowynhhp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2esevghfk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zonnybnd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjbvwad.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iisapydw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dshgytsw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlsqohi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjawmqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqjurfu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrtppwk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtynmee.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhbsnst.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wunpspzs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfccmxq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oauomcdr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kihbjubs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdrrsoj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjhlkqo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2heajjjfx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxkvujn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyoffju.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrjzdpf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrjptge.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfcgysg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgczfsov.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2movvboep.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bibwuhxt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmnaxzq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmhaaow.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azehtqqz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzdytko.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwycdysz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyylnus.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cljljcnd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awmryaky.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeynxua.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzszofxx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkgjhyz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwtbzxe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zgskqdjf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dufapwuc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afewmwfm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfgjiyv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiyhxkm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrejzvbc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bolthfer.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frizpbqa.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yiflzlsm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2newoavmo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kduqxqci.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfcpixg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vbichnju.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpvrmlu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2umnbgryq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqllqdsd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tocfijtc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hebplksz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyrkiel.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajocwdoc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2csdtprxt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzhizeq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ogytisdf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfyomcm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfyvvfj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyinlxu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkgppvt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oesyrogo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gotbkiyq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbmkgbh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njrereaa.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cmweejgf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nvinyzyo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2akakemkc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wygrjrjw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbbwfhv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwefhps.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmecdht.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crafqtar.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uehvegzq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxioidn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msxrtogs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwgudkb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2afzqknpt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvaehzc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsbswzw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2guunvnld.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nppooleb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfsnwxh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igfknjfa.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2srecywvc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcfhkus.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oopgugyi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivinhcsm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnvayce.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2amavzmth.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ykugdaec.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcklqic.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ozapbhax.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mormtvnb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnosomzp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvxxarj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sauzsezi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hkywxodj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgzlkze.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwnaxpn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyvvgab.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmhicvc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqjloqx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2auhamdff.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sysuokmv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjqzpmn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjtpsxt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcmvtxf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkqpaqe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoevjwr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgmmsdg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtktnmj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnrcoqr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqfqixh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2svcbeeup.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eisktwef.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivomvnvv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdnprvk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2igezjuip.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoyoytn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhdldwv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbkodys.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwmtnqo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mvupnkcn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaxlgbr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfzryeg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pbytoiwu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2congbwcr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqaabdh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzlzcld.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yahltujh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaaojmi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnwlvwp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nkevrsle.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cawwxemo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqilmbn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2scpnorqb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqyzvpm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwubxft.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fpggsgmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jewxihzl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2krnsnilm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyniyvsc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icwzkcho.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zljoywws.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmukhqh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ujetxhqt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueokpasf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2grdywcjg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2meneqrfn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2enrfzlph.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxegeck.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjjxqvx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhvincq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyklqji.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxwqsde.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlccwmo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2higwkxjx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tyieqmva.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvamlqry.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvcsfqo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfgmrwe.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tidqcmpn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqscsppe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjdwhbp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2txzsyrhh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jciblmem.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnehwbvy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thvhvfld.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkugnftg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2szvqnkjn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xunpcylg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ighlqacb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoulfjm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsyuiwn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmkgusj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxmfdlq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pezcjpvi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhrrxrq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pklmoqjv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfovvczi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvvohwg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgpqupt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aspaassl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gucnxmbe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxhrnum.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhnsyoz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgzzweu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhwnrap.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iahwkwjc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2icxgqtaz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqweuzn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlwdmel.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2iinowoeu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2htbjqnbo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2odzjturc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgsljrt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eelzfkiv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2swncjewh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpzcwyo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fooffkwc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzufzoal.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypicmtwf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmblvrv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2geqglmjb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uigxvjpa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtlnzxr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcdapef.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyodkin.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dlainoog.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqvdhwi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftznknwy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmyhidb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2peqejznh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpzmsmv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrlyqpo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whsqakkc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jqinbsgi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfqaivk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2srkwzezt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gslrlhvs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkymhhl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpzeryi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nqktiigy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkkqowu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdpbynr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2brprceid.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyfkpya.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jttpjsrr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgjwxoi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gteailbe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xowrrubx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcqxhmm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiswjcc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzghaoyc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmmmpas.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoqnkab.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rropjnnz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzabeugn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqmrefi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkqhjvi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwqaldl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uprdhwbo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfgjwsy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlgvevk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2djvuizus.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvybixg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbepmsm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsonphh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kreoyakx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2atifvhur.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2exrgfukt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tkynnoqg.html


<!-- 参考信息 -->