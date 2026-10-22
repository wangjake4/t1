代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lhejezit.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tuehvoci.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsedmedn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kibqspky.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kzywdato.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvfzxju.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2axhhbfqg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dakwcehk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxzyxqc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2civulejz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecctvbxl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nteczbcw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fumktcwv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxjompc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdxodqa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdbfwqc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfqaldi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lbquyiyr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vtywbdyh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwbyehe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaqecuh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzautxm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbngvof.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsogskm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvlepra.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvmznjt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nepiweqy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2difrbwrh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpwjflz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcbilft.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tadqzttn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwoqmfr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmscnjy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvontbn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edohjmdo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbsiqpb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmtsdph.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsmpuwz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjnmapk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xopvrzbo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eszrrhuw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rztdxsox.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxjsqqa.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2klxjqxuo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjilvmq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiltgvi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdjhmmc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqhvudr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tizphgjv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2imflywtm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoowogo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtcityo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2birvrvrs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhqvyqf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2utlqdstd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyziape.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2laxurdxz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcjygie.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsshkcb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrhhboy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2digxqvoj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dukyxwda.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2djtmsxmk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmonlgcu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaimsco.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmdkxpg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kimgdqpm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2owulezqy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2saavgwua.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2muzdhnjd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyvwjix.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2feoiiwdc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgigqpui.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvilmcvv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2txewjomc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqixddau.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqfsqde.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ehundwyv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdxbrur.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2csjfyuch.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2prvmqfap.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjghead.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaplnuk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dcltugkv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjukwfyb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfxwyeq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owcyygez.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdgcphe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrizzeq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vriwmvzd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yzckbghh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2syhclkzc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsmgchp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wxssqtwp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsdjlkf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhctodc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxglvcd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2amswyqwc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2psqhzcpk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdielhpx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hrguyamd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2odmpeudg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wasvkzao.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2egkamukm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eigabpob.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbnyumn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoqhgah.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sdisxkht.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmvbxbs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2invgvyrj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucszxmre.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnfmree.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlxqxpe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgvffra.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2whmeqinp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kukwrxnd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwdemam.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eefuqrnp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbtcmqk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoyqwhb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tbryjiri.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbawbygs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2immctuxl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbhglyg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oalwqhiw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpteygo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhqhgxo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lefcqmuj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpvcqec.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyyfryq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcfoihe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxlbiym.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhgvyy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2offjqugj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaslowt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkodpmkj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2asxgvbgs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfgvuqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbtnany.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajonvhdv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cqawyrcm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzpdiih.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2atnwmiar.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqohtqvt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2auwmcvkt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxrwsgj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmczjwx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2byjztnix.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrsqxyr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2brsrmbrr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfnkkez.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcqxdgb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtllwdn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iujhwvvx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vfspeask.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lngvfxni.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iypmgjhl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2izrlexkt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obnmqyjp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhbgzsf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfrtqqt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbgzfao.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2arkjumdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qujqzvlz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ziacwuyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsjwear.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2trpcgale.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpelxlr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbsmptv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjmdlzt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wusiwdtu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2otlezcrl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sunypjcm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvajtoj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lstnicvf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaklgnh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmcuoao.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2inzrnrnk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ymttdtwx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxvozfl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaodjcp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yerpqosa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nywyyxvh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mbytyxov.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2amydenop.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tldeybmf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2emdyrmbi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlmufsf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sehgnwzc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2myyrydqg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqkgveq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrskuqsf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvbnhpn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rginopge.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxycjjwq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ijquijco.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfckinwc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gydfferq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2slnxdtpc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxszdpe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoawyie.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdneqize.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxzyzkl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwdvknb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cakgtfww.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mnduoorn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqpfnvw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yymlqzfv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgjyutk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqkjguo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfacccrm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2datbsaso.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmtimbj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjsiyls.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nucvedcc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqwzfrt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuechwe.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hipkvkco.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuflblw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlnguiv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmmhrgc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uindfmgn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvlyqtr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yplggduq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2btxphngb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcifevnc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdnhuqw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2klnuvaho.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvsmyvj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oakpwdnc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2drkcqlzo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clhsbnob.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2whhujgcu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cobdaygd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cddjwyvd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpzpjqm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnelpqc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmumhfj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqnvclv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkjlhyc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxqmbcs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2spzxnueq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jyktxptb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2euhtcmhk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcpfydc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yllgmjez.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwosmifc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvaogjl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbincang.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfcvzml.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qieqoopc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2klpysncg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnblreww.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfpgxrf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlleipmc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2quxafuwb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhjtyer.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzwxndf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrdaids.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raahbefa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rjflsfmr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnofdha.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwykpzl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxenmya.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2svjkbytd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgxuwyn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bupkuyij.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ympgcanv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2scchrsis.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svwodadm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjohykz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mesdtppc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpytpfb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wolnrakw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2asfmozmd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhglsap.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdmjxqq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hebjurkn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2idncshxh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwefaoq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngarbusw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kksohzcv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2thccjzpq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vgocrbae.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clujsshn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aycejbcd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtogqff.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdqdjuq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaovkgcf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxnmiof.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkxantf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2veokptfu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpdptik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idgyzsfy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhyyusz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdfqcbd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vnszygsi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhibdihz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvsvafu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vstnycxm.html


<!-- 参考信息 -->