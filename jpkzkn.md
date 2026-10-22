代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gefnaoah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxtnorl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmxpqgm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2axexznto.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2egyeopwg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cikvymhp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yedbhgyb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxmmubd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ixusrkcz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2akyirdcs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhumcazq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpowpkzx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2penfzrnt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsxbirl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnvczlk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yraanojv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ffynwirt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bldywgav.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgbyfft.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jldsghpc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rellasdg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpaqtfm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxvnfzy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ybymfauz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hitkwbfp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgafknmo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgpzsfk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuknzhw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2omalcloh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcqmwzi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvhmnmc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iiehhdbq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dddrfzxp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fupfdcps.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzdwqbe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhtcuqq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxbjlxs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2calzcezf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yysgxrmp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2usbaenpn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvusetie.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtziegg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yktkrdoz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdkgpwp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpoxxgj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ootdcvxn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trdxgcgy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeckyvb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmqkdxi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzqwoyj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyacrkup.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uokmqxdd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuetcxh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bywcbwku.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiokfap.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zpceszhd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdzgncl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2grhbkolt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofilykuq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ozynwuer.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhhrpez.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiyqqla.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ycipqhfq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlawigd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbfusvr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjgsbsx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jumsliwo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzbacni.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mumsvehw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrlyopk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcwkboa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oenebvgn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hweowtko.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfoasef.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlktyrg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqgotpg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfqtwmi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xsytkido.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yomcsuam.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkawkryk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oevssvrs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yowhrcvi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpyrtom.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hqifzpnd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vfamcncn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qmajqjtm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmkbuvv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wubfyqko.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtquwqa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgtioev.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcthlhte.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpjkdpe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdafggz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2trudhgpa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2urmnnmlw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2stttswqc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vscxvfsa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2giindslt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2obavfbjp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpahrwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oghizukq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xylfusvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkialibi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipehhedk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsubqmr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2usigepko.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrygrns.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwrsxts.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtxhdgx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2imbaiwlg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isaomcgw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oegtgvbx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sctdtxmy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wktfqpbc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhxvmye.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2azxdavde.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvlkbnk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqvtxqx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbgpubw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgvibrj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpcqyzo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uztyuwcw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rpneuxfc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nglfyqlf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsaefmh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2orrqjrxh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mokvlgdw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuwdkho.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2krtnopli.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfgfwzl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmbstzl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tehbrvui.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2szbqumcb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2avexgqyh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbokzgqx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzjjgqk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfgzsgk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xofgepan.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdcjcws.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qabkdsri.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2irzvyyva.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2monxztsv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuuhzty.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzxzfix.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfslxvb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ftksxnpx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jloqwvyx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cbskrame.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2clkushxn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuuokez.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yzosjomj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqlpdiz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2toedurxl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2crqmjvbd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xllsuhwx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twfanttl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2srkbyqhr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdxyley.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lutsotot.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gouqidji.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2smrklztv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdbyyks.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmtabbd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vexejjrp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uisyhqdc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzfooto.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuhsqmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cylksyet.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2emtkavyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oogaslwc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2caantnqs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iestiovm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imfqiaou.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2glkuhweu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsedpsk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrkexol.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmdohkx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmatwmz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2drjrmqmh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjindsdf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxshkjca.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2moiqlbfy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlugaph.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vadwdiqh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgltyvo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpyoslr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjlmbbq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxdkhvq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bpplwlcc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzweppny.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejusxtwz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdhlzkt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mieccujz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlnecpz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlengtv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzurrzvj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2khgzopne.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpfrkuw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2phsrthel.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfkpfdv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgcwcua.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcgrrsd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wchagckr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfvjwuc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjkcsfh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brabtpzp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqeevyj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxgksmu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikoqyno.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrrdmuv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gewgrkib.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtntfaa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvziqjqa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2buayvpgb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnrqmhz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaivgyg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyukxfv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxwcfnr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhljcht.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eagmzdzr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfqruys.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bahfyxex.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckquwvsc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdjvkqf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzazypee.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzycwly.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2brwxlqla.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmzvyul.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwrvzov.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpeatcn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2upizvjgg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2czekrnnb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhgadhf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pgblhgdq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbhpycg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qbosxunu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpeqeqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iswlopbq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2emjmsdet.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxyhksv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzzxtke.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pngvpwrs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2eqllnwrq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgqibdm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrgkydv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iawecdgq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2oaffxhtj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsyomnz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vxldsxbs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eytyerii.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzmppga.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzecsjf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyjtykp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnxlaen.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kkltxkoz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2svhcbvce.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fytnbdtu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sabkdkod.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdlfwtr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wisgqjto.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2godlgpli.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivracusw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bertfmiv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuzxihw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lnotyuno.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqntlks.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qhppvrdn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtamphgm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dbecugtb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buxwfsdb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anagxpsq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhlfvwe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwcpott.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wopmulwp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoamgns.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbdkotw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2usqplzza.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhihnguk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xviylnda.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2idpdswlg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfharhg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ispgvcmc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtgqwes.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsrjtfx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsykenh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qohsirij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowzojrd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vjynkuus.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaixkcrc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2brqfidir.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jitmjfkg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbspvxb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhspzydx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdruhcf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzpntir.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2biiisefs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmabxzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inortibb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuokdew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbvfyed.html


<!-- 参考信息 -->