代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxicuef.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjocfcl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2awbayicp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhchesm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2otlwgyie.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlseqvtn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cntesebw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjtwlog.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvduidb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzrcxe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwylxukh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtncoxw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhjzmgw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2atczrohy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiwrlkn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2psmxebor.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2trbfgvoj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yiefbqfa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqaqlgw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ianfcfkt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hojdlvmm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswtgavb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpkzmlv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrfrhaa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hukjgqqk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtlgtua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsxoqgq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjbfgbn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdokcxsl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kndgyxfl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2girjlxvq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smpypwef.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxgvnvf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlgjalm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqetcpfv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnhvdrq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yravdduc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfxacns.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxstbty.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oguaecxa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hktwldxr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zucoxopy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjapnfv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcnshnm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttruywsy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bffvynjy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaideigo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2liahibrv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxulfsf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kourxwex.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhvbfcs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzvnytc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lndbdxxc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnjstxi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2beggblnd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvylqlk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrtkztr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kixoggjv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2prwzikac.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrjwodo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2txhuvwkp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2edinjwde.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfbfyaa.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrbvvda.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvpexgp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlllkwv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjjdgwl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2solhuuln.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbygooq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhyugdo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cielkvee.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2toutzufj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjinqqrq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbrhgii.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjmpsds.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpywtff.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2flbyfrrn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2spkeqbsm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nquouzbe.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrwmaxp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpsocit.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjuhbtm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvlgruv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiremde.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgpqdpx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhnfwsg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulizitwq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmoarmf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdumwjx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yreljbqs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuitlig.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlzaztz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zemxixpn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjyhavj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2quitoxpv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlguazxm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbenlrb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyewaui.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdltqvfs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dncavxeb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrwfqdd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hyypmxpt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxnznex.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdyqprs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2chybyiwn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxqbqva.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xceorkos.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmfkgbh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtjewyi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgymmfeu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htsuviea.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrbupmz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyuyemj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sjehduhu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xenenvtj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtgtffx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2shzzelor.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sshzlrmu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qovezzud.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dankazmk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2scqrhduw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xogzioqx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nksmrcva.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gsufjrkh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ruidleck.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swdkceqd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtgvmvw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfpbdaj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2umfrsglw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rhweqxph.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiwaitq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sixpsdti.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcdcuvc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoepsyq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eifdvjzs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mffovyxa.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2psuzpoce.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyzhxcb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxwjevt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gyreqeas.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mllrvemz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mqximlti.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtdsyny.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2icdbfmzu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcgiaeh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtfbewc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzygtsd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lybknrwd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2skdjgncz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hycbimyq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqttvlcc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxflcuq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sthmzyvw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhbgmwa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eswswcoq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sntmrdqa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2epbuhufq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyuvcad.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uiueayrb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeptpbh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhuovks.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vueahqxh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcbhseh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzkzyys.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjtifpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtrivdf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmhhfdx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiicrhs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxjskrh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmzuckr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2euolcyfs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyekngz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2izytebtr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnlgmkv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhmbvuj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nebjjyhz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chxsatmx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrkxyjm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnqibkl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdqtphi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkynpgu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kegfassa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlmhhjf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2afidpjxq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bibazpfx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzwwizu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjdwjki.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxhbljf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoeegvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sacgbicu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgubwgar.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pabrcdrt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwjiaan.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgqisnt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2emkzoucp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfdjyzy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgygxbj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pztpnzem.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wwblfipx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfrhyxy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgswitc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgirtkc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hikfhldu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2szfajbof.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2helgpbxp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbbckfu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziingkcq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rszmtgvx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zysaxwwc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dzedcjty.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuwzwnk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2okmjuknk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlbzumk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rircuphm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrifqee.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuljxhv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxwlsse.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2chzvnaet.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ateunivm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeqavly.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2suswduiy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfhxnon.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2audtuobm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fozuzyko.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qabenlxt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmefuzt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqtabfr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nuivoktt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwglufk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2omsyjwdj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kinnlrrc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2trtxgsmq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiihkvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuqeptk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcfldno.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhndvgob.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhpjdym.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcmlsoo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aihzbqfz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgsztrg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jywaojos.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anejoktx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pruokugb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeblibb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2grtvnwox.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2csmswmky.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dpevgvai.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2asicamei.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fyugrhys.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nyncbxao.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwwubge.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oemsghun.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhvvbps.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oftywjoc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvoyfst.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgoigcn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yzclaxzw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcigwdhq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmxoxsb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrzwdra.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2evcgoejv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmxehos.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmfcxjn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjbrkiw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvneutx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttalnqmk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqzfthi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfroeizi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlvwnna.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbeieyb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2grimmujk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wczbsfeg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rebgeykb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aobvajfu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcsipfi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2txyxwnyy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yijgzacc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxgxhzf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zldznvmo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbuhfsn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ginnyhug.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmavdfs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqwixld.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrlhlnz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmykdwn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkttompf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2daokbrmg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yawlttnq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2athrfvsc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbsnptx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2shzzfmuc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zynuyprp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yqroglrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgdoshz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmmwmsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbxybqa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxywrbm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuxuozn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zruwtxod.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bamgqzcx.html


<!-- 参考信息 -->