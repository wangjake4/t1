代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ribqksqb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zicbnvvp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzowlxhd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fssgwwzy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgdhznr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsisnhs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2epohrkij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbexbmnt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oispqlhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2attpytjs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yttcfsqy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpwezjw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnelgep.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyzbxet.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjegmuu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrwrmwv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbxvhws.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcuxwfc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaikdqd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqlbbvl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mirrzegh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eazkhntb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sitnjomq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwpeucp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyorwml.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdokupn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2olvweiou.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhuesge.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmdevqm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2abvfbdxf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqyoxei.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qjthvpoo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zumhkbax.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbxoxlg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujconahr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfanmefl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcehxvx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzifgtr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjukumd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdszdiz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aecixfoa.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjdvdsi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lnymhnpg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qccobeej.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rycdqmci.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2npkhfgda.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjstzhwk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2quwdnzgl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rovbxkzz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ilovrsmj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjyhpkr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpneuzw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rocxkfrj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qamgmtnn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vikkweuh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jeheuomv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsixzmkd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rllijtse.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thuyrscj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2klrqspge.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bojlrydn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sftwugrt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spkjviww.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjaqjxz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmhzqxn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qybhjuxp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ognudxdc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzkuagh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnssyuvm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gutqqcdk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2itdjhfpe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuaxdvm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqbaehj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2smnmuirw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yezvmxkz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhtvlqs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoslywo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hpssttmo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjygkhdj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmrgzor.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkstucf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bdckyouu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvpxbst.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrcpzei.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2edvzrqvu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjigjyb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcqkhbw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eahsozqg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qihequsk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlbekgx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mszyhygs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhofwsu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2voottvbp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpanppj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhcvrey.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zvagespz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fjadxknx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvczvms.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvakimo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzxrmee.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gchvcdor.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxalabk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfyusaf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmatfug.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pjujhmsv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkfzlhi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sospikho.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fadxxlmw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvzhmpc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddknjkat.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjfsesh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjhayqb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2forapguc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwmblaw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcrangq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jaewjvzw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwlpnfb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pseaiwzy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vblipuzc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsoabpr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mssccwoh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiuyqit.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgeayfb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfazlei.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjliqog.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxefeap.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2arnpbbdd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2skpgrirh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyslwem.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwtqvhj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzayany.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2izwmnfqo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iieuuofq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2utmjmttu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxyxwgq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcubahq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdsczap.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2piptdzci.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2capcswvp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnglbst.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtryytc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaunork.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kalktwsb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kdztjxxx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzxjsva.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqusfwnz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoieqxc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhmiaqb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiwxbhk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvujpgk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2andlznqf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2phgohggv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qqceabpi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2akpzgrdm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2czsmtmdu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoaclyu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hselsies.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkubjsq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hivuifdh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjloxju.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvyaizk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxedkrh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhvdixn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgmjlgc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlradyod.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrienmw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nakogbrr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2atvbqbud.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2efkzfmej.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vnozopld.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxijewm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ssywwxby.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vagenxzn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuyogdg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cecukdvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lawsjjpz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wewildao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoihbgd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxrcqmp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lavpcfih.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmycinc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxojyju.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciperqqo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbfapey.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxjiypz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xppdslyj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oecsodlm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmdjjk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srvkgpgc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgwswqj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2liqvdput.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2otymikje.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nilxlwfv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmuyrnr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtatyqrf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdnsief.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbceyvz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuvjntq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxorhso.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrhfwdw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxigrrew.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzcblvc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyljbjb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prxdnhrj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jucbcriq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqufete.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdwetti.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwvhquk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dgadjbjm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzawpfs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lozpnmvs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnmwkmw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlosqaux.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfwsstk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydynzyjc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmclwhi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdphacna.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fxamorbi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmylyih.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcapbyq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2htppnvpl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qajcnndw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rewinwhb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fyghrvhi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvlunyt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyrqqge.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhfppeb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kptbluyi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfurvkc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kgechcrm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdzycpx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmbisut.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2twafysxc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrviybm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jddngbck.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjewwdi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2raykshpe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxbhiji.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtynxwmq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaohadl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpujoxl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjurfou.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdrqbur.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyzuzoh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nnraohoc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhtrvqi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpkjjbi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoziakw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eojxeiim.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2usfwymhz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwhqytj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsexenc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrgmovi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvglppm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbdvtdq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhmssro.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgmbdfk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2guiibzhi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2augyyiuo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2llbqxuvw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcznjsi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfssprv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmjcnrj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaybnjr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnepvmt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtuhtli.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxdlcxs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpvrhrj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2usodlajk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cthnjtme.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsjhgna.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxxjiln.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2phnovbsd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ruykktmu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uogeqjzk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eefufbao.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffobruvq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzwfrrs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpjabiz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaspbzot.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qinrkoma.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdudkpvi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2akngtgik.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rinmphis.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2znweanqh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhmggzc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jrslqibx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lceeczch.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cslegums.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zpztegrv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2acwpwwdw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zytmgzkx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtptmpxo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvijxqn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxskros.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2brdtvexu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhntylp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfussnk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfukdozn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2inwqdvko.html


<!-- 参考信息 -->