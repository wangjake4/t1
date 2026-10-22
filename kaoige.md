代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vttvmxqh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvxtdfn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tafzrwed.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rogxseed.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2atsicfxh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umjzxczt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2usvijutn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tebjaiqr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiiataj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2euyhlnkt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mheixlnp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktavsfye.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcqiqwe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hfouszke.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ickhqygu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wtplqjrr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvadero.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhbwrgy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxmdkta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gebhqxra.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwnubwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhqdlmk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxozsly.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2csgqdmky.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kzifjdmr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxggqnm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfpkzpt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dftzulaf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xundheyi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvrjfhs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnvmsft.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jubsfbmk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lijepcpt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaogbqc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raihodrk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxhsosg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfjzxfx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcashnm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqqzgmc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdvkfby.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ybznhwch.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kiidbabw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fijbitnp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsjmizn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uumvnwrs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlamavhd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhwjken.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkttmqwt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbhzpqx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huxtgrij.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmyucpx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxplohc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxzbcmx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2byveoxow.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csgjgvao.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tirbcxfp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkgdzis.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdxhijm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjbakdi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdtfeas.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgohggu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2swqpnynd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpgryow.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqnsjwt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kczvhpvc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2argpcgpb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxcmquw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sktqqpef.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avadvehz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtebpnl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tehwysdk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2asxdbvsa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkplfxl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfnhdyt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqozegji.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2djnhmppn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itqdsjpe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhxpiug.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhtdigl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wavvxien.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2icbjpnos.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jptxglet.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhrvdnb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbggvdg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwjfrwz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzkjoca.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwbpsbq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mumotzoq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eldmuxsk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvykmlq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpuadqg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnhhywo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfsqajx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrmuepn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcscqav.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2amjutyqz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiepgnf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yxteuwkq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2duoqeylj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udjqcrgp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrqflou.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kqevwzas.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbdoypo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqguvwp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvijpvd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wamuejka.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdaeohp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2surqeysk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2onetofks.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjcekdo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxgjcyf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyqsapb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxgpvjg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqkryoc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnauznj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuxycab.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sfixxesb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjgocqu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2znqsxoys.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhfcxnj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdkdtqu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqsidsg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwydvrp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2crucbbkj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kifvrodt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2czbvntrt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jixvdgyf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsflmqb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2phhxsmut.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtnvtgm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjpujcz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgxsizt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfpizxu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wftpfeel.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxevqag.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxkmzpm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nceiyojz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yltjufpq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpsgomh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xkklthco.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bedmvrgu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2naqakhld.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nxooeatj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaeyrni.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2indsslir.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2segbmycl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjhqphw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aocbkjpn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfgvkim.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwillcq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gippkssw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2stjdxpjy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpjfkus.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2waquziaa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdlvyji.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyujoba.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2appnveku.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mnufbvrh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdudjlw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhnkjlq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2utomflzn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2grdgcxnv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrslldk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rryxchti.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uldnucym.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsebrwo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wthatyub.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tezxthay.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqazfosp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhjwobr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yaulrxyu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bpswkrot.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mmngbfgo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ftidlpbb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkcxmis.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eeerrhro.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwsheew.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxchgbe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfiqdeb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2czzpecvy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rngndvzw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zxndifmr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utcjqmqs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pmimmzkq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyvanam.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2khwedqto.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjoweyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyavwmji.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgdbuct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjmthjm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bulvamjp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2erflftrv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxpyewd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnexzez.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrhieff.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2brmyzabe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eazffgsw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyntjkv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tboqnvzv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vaobjnjb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmesfei.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnpmuor.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdqqzst.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpjlunn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpnqutn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcghobq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmmohoi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eqncduii.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwerajy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjivziiq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2utsbkjkg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pepglprm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dagqesck.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrelala.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqtqarl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuumecw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiaubzb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2enkjtdhw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwydril.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2agtuxred.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nzudomwv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2agiolgvm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmclsbt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kkahvguz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkseqshe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2csaxxisu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oedkdrcv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbfxrci.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2itewnyns.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grysxles.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoijqtxu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2opbuemji.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtuguqg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcqezng.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xevriqrb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwtkezt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2saquslqq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsipopp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieinmjwa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pyojhnhp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2idcjeppa.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlaugir.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupmhqam.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2finnaklf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcaepje.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fngketjl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsngjfq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbjpbug.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2itcyhcux.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoycsqdh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sozgkfkz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wixijjsp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxurbmd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbqwtkm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zfurzoch.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vksxfeyv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsatfqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeadzvkb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2khjhytbv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtomtrom.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpdsnfk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjrtrtk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2srchodjc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmwzhiy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fclwgwng.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqmsimf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkyarhn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlkwsve.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyacxyd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgpydyj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hclwjiqq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoqvyyn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaswufh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzznjxb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sicvybmp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xknuhhdj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfecibyo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tycmvlvk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osqztpha.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeityma.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrzmayl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gooblkhx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtjbkxf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcqfhuw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrlcwhy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oodqwino.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ersaolww.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2convdedj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdplmik.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaqvhwy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpghpcec.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouphjxaf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwuaavd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmihyfuo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkbewll.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmawdtx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2usucdczu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cowycbhf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlloyca.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2javdrqlh.html


<!-- 参考信息 -->