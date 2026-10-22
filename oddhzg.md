代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfvezfp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhccjpa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrtvdss.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdelodfc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djkbwruc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhqjedi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjhdtgl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpamoig.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjsqdpm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxnecen.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tdstunnr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwtunwe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xawbtpil.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2poieklrg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjcyjy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gurkivzl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbguixs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxptqtb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aziunipu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jicqhbzz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aedbctaq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brvskvmx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glimuzcu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmvguhk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvauaug.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvtdpzw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpykycti.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqmvdq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrsjloe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeebcea.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpphvaib.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrwubos.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbbjkwv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2njxcfatx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2paghdvnq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2psppouno.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfwhyma.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2loqkjeor.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhyrlnb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpozwqx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynslqyyb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqrwwfg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrznbxi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpanwos.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2balplcbz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqopdcce.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2quqaqlvm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qqowoaos.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqwnali.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhrsjrq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvzynvu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iazfbmfv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuhtlov.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2saystxbz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdqmzwy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmndrgw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbwvngq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2apmbeoad.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwykmkw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbazyofk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxtwwag.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsysitj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeqinqe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoyvhtq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fldpgapd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2irxojevt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2odzvizlj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2adjandsf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pewswtlg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoftuzo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aqddsocz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfqstna.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnchclcs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjitquo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyxnzfa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdabgkc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzitnsv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlivekf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ctglpqwa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgahzol.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjkxtob.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aykpymap.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzerxdjj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkinapl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2avdtmuwx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kwafeajz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfejzsc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwrsmtv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpoakyb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqyhjhq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwdyddp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2honifvxa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kheskabc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iztcqekn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrzhrkz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeidzwzz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsxesip.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxtoxgn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qeslngzz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2untfxwlg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhbtrli.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdimbxn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnadugrp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2faybtjwg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpqdear.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvutlpw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otymbxgw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xukusmcr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zxncxpwj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jnklkwyz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2crhqtjpo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2grdoomdq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mqstdjnw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdneqyhw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvkhiky.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgqqszy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzoemsf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2funrefia.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjrsmcz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovepkltt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2abmiczge.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfdgkua.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2emljeroa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcincyp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsnkbur.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnyxowp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2chwtgevm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjuejiw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kgshgksa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqqumuu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzvpkiu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2crtnblfb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2knfpxzob.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2psezxukt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txyatfkp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2juczxvdz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mljpkwjh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzenllh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqulduz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsetehq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxhofvd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kftewddy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgluzcj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qblxysww.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fedkqmlk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcvsrqk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmnvwqy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxacvivd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrwgwjg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chzyhzuw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hijjgpda.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjyawqb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qibkciyg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2owveuztv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpzwefq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2myvmcrxp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2smjzcpji.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2eedsftzy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kamffbdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odrgfgko.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2obqfdbpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdzufxl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqpimnr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2skysjzrv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmfbsoi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpmjust.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjaykln.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pybtgnxk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyghsgl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvaaxta.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrvdosi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oywkyzfk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grbimyba.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeopcdd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpvbjsi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2poetnuls.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtlgigz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdtzjvf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuokwjf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uuefubvb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pexrirmr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bgssotux.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lynojrgu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhhpmwg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qorhoxdj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrtfcsa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xejppnmc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqabwmuj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoijldv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrepcdw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2djsajvzc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bitufgbk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqftefwf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmifxvc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2heaelzbo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxblprl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzplkqnc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2whcxjydj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvcuwlk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwnvndh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmmxpam.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbexlkd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmmjdbe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoapfmr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvabtkae.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbzowgf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwckttnr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ysezrhnk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzahblow.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuoccmm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtaefpt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yoldspkj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gigljcji.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjcrwag.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2konztpvo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtsyhqw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2damlmemi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tibqwylv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2llzpeqkq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2asymmezb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdikenkb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfnmfli.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjnefjl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2aimxitwk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdyesit.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2laofcrde.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjwcowh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ervztvwk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvkqiga.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrhycnm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2njncifwb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwobcjs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sllxdcat.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmccook.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gciitnes.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naoznfzs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ewguvbsb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmztlnh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmrppxy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnmwded.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbicfdv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyqdfsy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xlidhgej.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsngvrg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkpxiny.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rmebguep.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yddlofbd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqmwmqa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bathbzma.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ublebafw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhbqeyz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfetmxq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtabwxn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwaqwql.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwgqqbh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdndnywu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnwvowx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zeroaesp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fstraqhm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtlwybl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fevumojt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrjfyis.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdewuxc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wipsndyh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqshikbw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvphpzd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfijpdti.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2czndefzd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkdtznh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zztqzrsn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbxrevg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkpngol.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbvsoex.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvtgban.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuxuyhw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rbriqeev.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlulbuxx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgoovdu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqqymld.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dotbzkam.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2livzspix.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydynlglp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2brddpaae.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvkqdmk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiebhwgw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqzmhsd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlmhuvl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wynfudmi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yigvkqxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlerwegt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2imlqqbrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kepxwuhb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhwluxp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsudwvuv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otmgpuqf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzxtoeb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzwqghy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfthoady.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iglbxcuw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uafnxgvf.html


<!-- 参考信息 -->