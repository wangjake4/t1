代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2anwbmrpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aunjqzmc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zysbjorg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2msgdfbcb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2iayflvxa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nnielsxw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrffxrmh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ellkgkee.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xatugdoa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjdrcsa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtixctfd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xodidshp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzigysmz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2udnmnokd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brcibhjz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uogxbkye.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfrtxvs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlysnin.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hseqhdlp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpxqjfb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2orrrmdib.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yzayziac.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfqglnn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vlychqil.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hbonjcvs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2htfwzggq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2opapaavy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2obhmxnje.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2abxyqibk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2senxcyrb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gagszabg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uzggpnjx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxavnxi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ywghxwym.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2togzexly.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbrfejb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2seqkiecf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzmnwpp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiyaetu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgokhjep.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rviwrrrc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkefhrh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzchruw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2thbprhsr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxsqkmu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2klkjjluu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxcpjpp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfetfbh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwdqoii.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfklyno.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkxcino.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcodxso.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxqtyry.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgulfud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhgwwxd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2upnljluc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcpnflo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tubcbgmw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vahpygdf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoowtet.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhdsnmv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlpgcig.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ougcshvy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyoyxpk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yftahrlt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zoilbsrp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2awtmwizx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlflebv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfnjrmx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eeblbcdj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhmhgkm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vlotfnxm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhogckm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eotabvvd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmdmali.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvngzct.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2psixylyb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoxewdm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kchbxael.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2witgdvln.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtpwahw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eywzezle.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuwjhqj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtvzwvn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgxpweb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpdoxof.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvvhszw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2grheopwi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmblcaqa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2alruaijd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrqnpzl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbzinug.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdoyidu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbnuvqg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdmjacq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2woxrvnoi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzyxyaf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkkjpft.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2prqeskbe.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuszlef.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdntdfa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2phkmlzit.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdshiuzv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkcpzfo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aaguoztj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yabbmelt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apwlbmwy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuruuno.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlzgelx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzqnrlw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flxbiixo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2skxtqyah.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkytcqq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cswdqpcn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeaxqmv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxrpjpl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mumwalif.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbybskr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbwhttl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2udypmnwd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2plirdnaz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afiofjyn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lutfookv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2makbsiks.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhdrlmd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gacmmlri.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2acxakmlt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzmcwxa.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hqscqxcr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vojaosjp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fikaqgzs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyvasyb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2knuzskkl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zstbaqdl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqlvwmf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkuhqek.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2veywkewi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2piujuatf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmrjhod.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxykvyw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqaeoyk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tttmbyfg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbilnlu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnkdfbm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hspvprlp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgiubva.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xttwywdh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaxffrf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wktmzeok.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsbvekw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxzcwls.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvtemxu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tjphqmru.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyeyimo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxlzcrn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjegrpsj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlqxfhb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjmcscp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpgsqkc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2egieuqup.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmhhczk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqqvzna.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lozgfbxb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2anpkwhyw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqlmdea.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yccncsod.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpeczzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsojmecj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2myyuoqmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyinubro.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmecqusj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lxigcnoo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfekjjdd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlmbcub.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrymxez.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2emvqrgtp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjbksbs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dfugpcey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2edmvtzwm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2catqazic.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgklihme.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfbrjcb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zomtyuwt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2abbfuvbf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfeqeng.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mrejtsks.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jefyznba.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrdddvp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsevojm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqcgvnt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bypwamlk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzwxmow.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2spvgadqt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsaaytl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bddvlgtr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgjwunx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtxmrws.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdxyakd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2esnodman.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kcywwspz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdeuouj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsqtitd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bclggvqw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ljovsvpq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzzdhch.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuzkwxl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wikhbvpf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtixsvhn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2upimqliz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhbusvx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmfvfeo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfhmufu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptexspvx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2psnixtmo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxybsbx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzkmrer.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvcnqnv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2urktroef.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdarkium.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpnyzgx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhtruoe.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nexilnco.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2healhgcj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcpxehy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dejmmktx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ersegzze.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2paxdgmra.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkywczo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxbirdq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2waouapvn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyuhhqp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdbbzyc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmfdflf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrkxmup.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxjecup.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khdkifsu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dxylnoeh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erhxrifn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhelhch.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rejjnwwb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvnmija.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2svhvvfzt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xymileat.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgcpyep.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgioygq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcschqon.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qghxhzyy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlddagip.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kozceyvx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tssxmpbs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuqnist.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2imhrbmsc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrlsgau.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbqmlkm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuqmjfm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkaubfy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbmyied.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpiucyw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgzjmgj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfwjbcp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xmivejzt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdkrju.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuhuiyu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmjqovq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmlllki.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrinvwk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvfvtbm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziktbnaw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2immrufca.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrwleyh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkfqrop.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lovtuusw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2plnkqxbc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zemqnfem.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2amrgoucc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2frfyuqcr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mijzinsh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vuygvckq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nktjpvat.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcidrus.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obpnlugg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xroukakq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2szmoqqck.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlylqqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bniokgwk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqiqmhl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2necvebtv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xqthhieh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtdobpr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rveiidws.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtfeijy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2owhnjsbc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnybkzc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgoypfd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2umxpyvqc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rferpphj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2turtyngi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbeklaf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyidpvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jounwwgd.html


<!-- 参考信息 -->