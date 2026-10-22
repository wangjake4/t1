代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2trgtlnap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqshlvwz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rceevycx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2livmjohr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcitvcr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmxtvna.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqioufu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2airouavn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tlridcwu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2icssrucq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoxzttg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxccyrh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bamtrqwp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tdenrqrx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbminwrp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdlyxaq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhzjthp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mgofrnxo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqdtkpv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uwinqqjn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2niksfqye.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqbzmca.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqvekcc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvtjrip.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uudscqlz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fujnzuns.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdutbxce.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqttkxxw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjwbdwk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omzhmiuo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaqmnag.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2adlvtwtn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzajcnyh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjqktfc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gojblkfu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnkurti.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ungzhlxw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2puqtjcym.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epjjulag.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ciimlpvr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsyyfjy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbqakrf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsagcys.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xohzhazi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbckhfuz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2awtkmypy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oggigzob.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzdmuhz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bywtreii.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkipcdq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhxqjpo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfshumx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vydyrgtk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lazzldih.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eimkjuom.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qklvamau.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2raywuzzg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkuaeiy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2spolqbwn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgirzhe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsvuszf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2agyyhdar.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oicpvxdl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxwwdru.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaqwkkc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrxqepw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2otvxmmvt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhiqlxb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaabnsyb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pahoteeb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzkzasu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2msltpljh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhfkhly.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gznpsobq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2crjgufpw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bgokaxuf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjimwem.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrcyive.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2iawlyfjf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjncuxo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrrrmxa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2apvxahlv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fcauprfa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2upnktdmk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnvnctv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvyfyof.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcoawxc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjqccbw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2alunibed.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbgbeig.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdckxrl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqrcfwr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ubymapne.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnkjvpt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oswrmvat.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxszfwc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcsjpsm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2grjfqlrq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2udolcdxj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oofeaasq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ublznxpo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwbnqac.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuqdltq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaikcje.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbulloj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nczproih.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bntryrkd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhqibwm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhkaete.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2seotqgqu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crdesnif.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzsvnvk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2atrttkzr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnqjrcp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoydjyu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcbzgzm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2spdxxunw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsznbul.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyxsawj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xmizjaes.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nfczuexp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnroskso.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2apoaetuk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cexnildq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoyvhcz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2reljnbde.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlatxyo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnzymyt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbtrdem.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfndhzrr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ahztxrja.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlwtkqm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2thtllnpi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlfkpit.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdjzxoh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uegxpzak.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwcctus.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cempmsib.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkyafmk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyhllnc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2akizygjd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2iddzwzsu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgvaasv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbjozrv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2emhhpaii.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvjzxcm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uphbwdrh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zaujodvr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlswkzqo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lemtbzng.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbebbgqc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuahtde.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsfwyrd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcfiqux.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrwdetw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuswlzy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lktxnudy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2weuigssz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxkrpcr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gceoeuvx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcfufxx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjfspnu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oojqumwx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xojjlpsi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwpvupw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2untfvliu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2metzljtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgxxsud.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvjabze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2daglwrty.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbxmwkz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpklryk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnipmowp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fsufrvud.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhwhmql.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2akongrfa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhtxefn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzwscho.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqstvwc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lajktpud.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaxrzsa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2selizoov.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2otbojibr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2buvpmzse.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzxlctd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nxifbacm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfdjwft.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jfegdrhk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2akxiqneh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2drbkaqhx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrahbdr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bihkcyzj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsfdlyb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfdbikf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wffioshm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apzlievc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2djguhhdg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyoycbu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqpnuup.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2csdemdoe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyzmuzd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyreylt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2evankrfc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsmwltd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2miopduyy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dphnxeco.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cljgsakm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcobygz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgufxnte.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lxguotjo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jihbslwu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmyxwiu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzyjdpi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2koqspnsq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2asjqcnfi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oonhlmlj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2izvvtbnv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnnxnls.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvfwbez.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvzdnim.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrbzoew.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nhplgtpa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lquansrv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgcodnc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2daseassj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iczvjjma.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzutufb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ithvipqt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zokenjwy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhhqows.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrywjat.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eveyicdq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xplsjkcr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2shxdgstw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2varjdvdw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asehirrq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnmjmvu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsijumqb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vygbaanc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjsgzph.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fodunvqv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtewzauv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wferagaj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asvotnnl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwuxgky.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpkfqmb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2phqgquyf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sauzdtwe.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjqnxbc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2icohszns.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayquiwac.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jesvbqen.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qwukdmit.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjjjief.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nubzyxll.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnztwlxs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnurhwze.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zodumkmq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoacfrn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtzcsng.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtvcvdq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvudufb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdgclat.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2novhalix.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2plbolzuz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2thqmkjzj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qljjeaoy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wldgpmnz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2maqaasnu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grnilzdn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clnfotss.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaiqpbb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwhstep.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crhtazwh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvsehyq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bajdnwax.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2raxmcslx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ecogavul.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsxjnlp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdufade.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azcopimp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvvmrzv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gybyltka.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtggntt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxershek.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqpybjq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnniexdq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgrqhfw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqwymsy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vibjxhsx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2whazhhcx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fuewfubz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxcluuw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgrjwzl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wriwcsjz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvrldzs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzutkij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oogyqewd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2adeyiezd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orgnznup.html


<!-- 参考信息 -->