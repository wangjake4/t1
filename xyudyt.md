代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2psbabufr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqesyjy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ojftrxjd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdcfqqk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmxctwo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpoxccz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjofqja.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvgvkzy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pimkzgqd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tysimocf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2prfgrvfd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aawsmxgn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krdxmmmk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eshksvdj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyrveac.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igpjjqrg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvcaayu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkyjzmc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtboxqa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwdjlwe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pplqnpvr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxvltfb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkcqrlh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2elgjqsle.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2txzedxjw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnmzmsj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxbzjfr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2inyrzyzv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yawcrztw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtvmmus.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjconlx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2knvkrznu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdptjpbu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wseccaih.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkfqsui.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiipbah.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdajxevk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqiobju.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfhqkez.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rsajsnyy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcjijki.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfbzicb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbduqixg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tigqsoip.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnicpfx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwndjjk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmsnurs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmsdlhr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjndpzr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2atljposk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czwjfifr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjkznru.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itvryhfx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2autftpwr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkrbggd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvdpylf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhlhzbs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqvhjdm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqocwce.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iokbbyqg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xejxhuuo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzrlonu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhzyiyv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkcexsf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ncivleqn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxskhtan.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2otdehoug.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwfzplq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxonvrx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dsskydkn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkdhdhg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ltytnpsa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjebijw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgevxnm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfefbqk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvphvht.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2etkelvcd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtmtwvf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuirkjz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcijufb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eerygqof.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcxwfhz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsvvjop.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqjxojm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nymwueyo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2trunpafm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bszfgvcr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2araxhdyh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwwjasn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2djiztpeg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmpudkr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rimikqmy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtsuyui.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxbpwav.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2awakkzqq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyxnvfb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dstvpxgl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbhjjog.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2udjlrnyz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoslcnn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acevlagp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rehvgktw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzamfbro.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaoybls.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyfybco.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sieelfpo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlsvwhl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfxcvos.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ueszxxft.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iexlwdvb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtwzhtd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2stwukpip.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mifhdsnt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqapuxh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnslaucg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrewexw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmbqkfe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tprkiidq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2okjxpkvi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnhrvjg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdkejhp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaaqfkr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoajeeh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oueagibd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnbppkx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiklgxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qoibgsiw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fionokhe.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaixtnw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpvojrf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pfworglt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bquqqrdz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpejrsh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2quwkxqao.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhvzhak.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtbnqae.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2grczvjhd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgmvlgb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2epzggqcj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2btwflznb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vldyysgt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2efxeimws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efyimxtc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmxlmwy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hokfgega.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfpoygm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2iovspuuy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlsakxl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnlrhfc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qycctsgp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtovrso.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2clmvgtcb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxjofwp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eanfikbg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2huzoaoue.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xshvuoop.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2karwlpxp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaknhgd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kaphhpzd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2odoellpt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxzvxrx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyboqaj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2robobxfj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tdctgjxc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgwphll.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzawasa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsepjop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqzpvkz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdmfhjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrqhpge.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2feexrmzz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dapmptyr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyvzrot.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfhzkmr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlbthiu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbsnkxx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwwkurq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2etnyhbcl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oznnhgdw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlvhpjo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcfzpmi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcaopwn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfffpcy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxkoagv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tyukxggd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rfetteaq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnplmeg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpklbxc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2oodprzai.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfkstpk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvmvzji.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdghjsm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbnxzhp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiahkye.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2brincdtu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdubsbcv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwtpiyq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rufojdfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lizjbtak.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkzjzyg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2afeyitma.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmvxgys.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlkbywt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ccghilhp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlggdxqt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yumxvasv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzvwxjx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsolabkc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqexuuct.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvaphbo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2drijqykw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2szvoerxw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2igzykyii.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vsujszzp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjgbssh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uxplnvib.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkuesdl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkauirg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbntzani.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gywgmoln.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhesdupw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2byghkgre.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjswefh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cadwuzqe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrljxay.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mahdgoeg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjxbwvg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihptjlhu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjgrmsa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyebfobi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uswsjeyq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkkrhce.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzluxrd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nipdkjny.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmlzrha.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhjskzu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdyhlxp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtobepsr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvqwrgk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwitdya.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqcltuj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhupzeqp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kncdwpdi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opnfkdir.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrpvqyf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyodxhy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwogqzt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcufiqlo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwvjefc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwxzwye.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cimuybmv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdbvmxa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2awbokeln.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dybtlzak.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2miaazfjm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pckrpzej.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyzqnlr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmqlepj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmubgojx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2blpxltvl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ciizhcoe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzubghom.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nryxzmyo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnihwirh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjzkwix.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2evgrqcut.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vziuojvf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdpeqvj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaqqfra.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kplnrwrt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nykmrijq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hftcifwj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2puymefno.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuzlvqm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvyjlfk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2djijuylg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjesaed.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eysozidl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ooivgabv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuompee.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmlzdsa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pcifhher.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctypiuur.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2varfjyek.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eleazqzs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxfeahr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qanlmvch.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2offymlif.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjymjmig.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjacmyfv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjkwwzu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiiggiz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvmcdnb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdjnscp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2icyodrga.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlppzcrr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oevttfwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rytbgffa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyylucxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpseimrs.html


<!-- 参考信息 -->