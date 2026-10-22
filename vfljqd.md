代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tthqosyz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvemnutr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxfbomd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlussudy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2huoakgpd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zspwgmix.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgpifkk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cyluwsac.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpzgmze.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gapnaonp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqmvbih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyopdozo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqryeru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcgeyiq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqquupf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrlxlnl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ytruckrw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnfnxgf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnvbmop.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uduhmxqv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlrhmxq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fioigwjb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzkitmy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2foanrzlv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfdsxdn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcdoccd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugepjisn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmonrjqu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ropfhupp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcmxbru.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnsiddg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrnsnpl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jgetqkcc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpklxaw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2shkrvqbg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jtokhnci.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaheooe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwgbutj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfrcszt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2liycbrta.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2thylgyxz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnhkelw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdjktwt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nesuxhqh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icaulejv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2brwkjjdl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgvzflz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uarldxwx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpylrrvb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsevefz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mffwimcf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrperkj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2paykuzhc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdnfmks.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snfqiflh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mnapuyde.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrmcalx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2turkgvhv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oitooycp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yomhhlji.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xepbqrgp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2phdinlke.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vweffedt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsxpxhs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bznwwdpv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wksezehr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjjnsfa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcvevxf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqgbppw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfunowl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2txvaoeyh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxfyetu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoyspxj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrjrwaq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wowvcddi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqibwhxa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olwtokfu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpwoydn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxhfnyc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2czyvnuzj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpzopzz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2thwxkzeh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcilguvz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdniuyt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hchumjvw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2knflbeun.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjjaxsy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzolmej.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyodhfo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvbmdvj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxblqyw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2advqorph.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuiqimh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uztiemhd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhbybao.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cztvrtcx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2usjpeucf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2znmyelju.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2scfjkylq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfwhtwo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbktobmo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2enrxqexu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2twoyrauz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ippumjzc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hztuyznr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2voeufzsm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2opmaqwac.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhxjlfo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2iddxlavd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxnavti.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2frsolnyd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlyuwke.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gczpexoa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpscnjo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hghlopbb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdjcjwe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoeamec.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgxriqw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlxqppa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xalxuchi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdozddy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2txrzazuk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dezzsfos.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vepeicgr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqxvjbe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ploxkjrw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njclocyf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeuxyab.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2odntzmdq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vmapdobd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2atryqaoz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdcptfw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yylblhpy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxwrmps.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bckiqnna.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzqhqph.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnyiudc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjnabfs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvcyllc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oljihpig.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2whbnvogt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqfghzf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mqchwzcx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhqgefr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqbhdvc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqnixxn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbhqgap.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2scukaopy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvztvod.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqpunfh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuiscbl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wnncoifz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ftifjzkv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtjdmnj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sggmalap.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2olzqnloa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxefuyx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpcjvux.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hnplxmrd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzsbwhq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvcfgml.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqlctne.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzutcde.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbkzezf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvjvjhm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhthojm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgqdruq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdldlvne.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzerebiv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhbxkqe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2msfkfxbe.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2okjwzczn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qczynrgs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkvtaxv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwmweao.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtbdbwl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2davxeghm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmtjckg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2grmyumxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ziekjqqz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ruggciss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqsshbw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swfmgpko.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2prfdajfn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kombuizd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjptdow.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsvdudf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ototoshi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvmutxa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbvosdk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmasxsv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2asxejawl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2saqrngth.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjcrxen.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2grwnenfc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cscuarjz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjxyhpr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xbixevcf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsgjrbl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2quvqrcrj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2babnrare.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cighejki.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2atjzyvsh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpjvmup.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdlsyjo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbullfv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfdyxbu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwezocvo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaykoxzh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iafkxyyi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nybmzxjx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2witptifz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrgofqt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxxfojk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hswdmkpq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iktlfymb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxruoig.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqlymzs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvnocdp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpylnwmg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wknhmtip.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bckqmesi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2viajelaw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbgagsj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeruugs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2izskhcto.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfcbdht.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyqcsai.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oealfhoo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdfxfhi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqxwrws.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qaswurwf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxhsnvi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgkvjjy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgjcffl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2irfvghth.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ircyueba.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqnkodm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhuzrxe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkkcbzw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2syufebvu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlhewuk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmvimwa.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvelfdd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uauxbykn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmewvwt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mnthpnwm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzuiaoa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgwosap.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laujdhtf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcdwysy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxudihta.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qodfbnqt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaadqqxs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sukqvopf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfelrqua.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfctyxa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kssxdadb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaizvli.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bylztetx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2elcbwsvs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azfkhlob.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eyumxvnm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tygbflsi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2unuvsaat.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsyevqj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnxxcma.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2olrdxjdo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyydkzy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jegewbfu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcfavqy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuctiqab.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2plednyuj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hseunqwp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrfynhv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtsuigi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vghtshbk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxaohjp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpdrnxc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfgdthd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gagmndyi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzppzcx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhgjehp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyyevsq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eenlsuhk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwhtoiq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2irvoogen.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqporwy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knzwhlzt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrhocmu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sbholtzp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhucdhd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdrclzr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsotmep.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsybhee.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2faeeoqwd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2azpdrioc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbufagq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyclxhxb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gqytqluf.html


<!-- 参考信息 -->