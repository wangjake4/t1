代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2irddgvdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsomqct.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ngywohso.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkywqpc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lcztzlxk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dxolouvp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2elqzuogn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxqrbuh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qupjlccl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fehvoydt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgfpfer.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aubttfst.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axcbszgi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nwscwvuq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szfwxpiq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzmxpgg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2asrbgcez.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ieunwxxs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2akgpnwfi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xlflswia.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwtkhsu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxgdfag.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxpopfr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdxgdke.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mivemsdb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyunouhx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxwabir.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2difnytow.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kulmfsxq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwipjxb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svklaogn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fntchcei.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkbwfhq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxgmwkf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtipnbdy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcpvtfp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyiahky.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2naobrlqo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evxptcex.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmimcnu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvyzkhj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nyambajn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgihynue.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nhstbeiq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvagkhd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpugshgg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bskzllqn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzrzeje.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuftnuk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xavpgsyx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bluqnzpm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nuybygmv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrizjqa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzikkich.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wypkkxws.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbhjtof.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbhxsra.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwgesjx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2srtkiijp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyrjals.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tumeryco.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmotcrl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qruxooek.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnnklvk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxppdyx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2czurssfa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yakrtqba.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fphamhrb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtnqvlr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzpokot.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ungoouvm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2njxolqmi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2liidwkin.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeoedhq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yylrhhjw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xndkqvob.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2owyfokov.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzzckom.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzqlffg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgqioep.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhreafet.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2atwscgcv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuvmjvn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bkigngbr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrlchou.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2stpumgpq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2maqlqaeu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqdezgk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oaejusyk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qszobduf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thntohng.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lewprxuw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2byguilrj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzbqvqq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jniswbtp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzdbrpp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnuienn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gppydtqy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ualaibia.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbxuehx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apfsvmbe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzdsoly.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlopyswr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwfgdbg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiwwcti.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pukzipzk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tguabekq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2khmfmbth.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdshbak.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxngicdo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2asztubbh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqddyye.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2juoapaqe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vequkjho.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqrepng.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpqrvrt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2raxvhkjm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tlelyjmh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vhylxdry.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbxreux.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eredaemv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzyqhkv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvppfjq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnpazfe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2noilfdrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2atgrjqch.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrpssrx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwrnitq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrbiwjt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiwpxwv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2thtbyfit.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmidstn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2upeuzgys.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2okethypb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuidpmt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oubjrdmn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkczoif.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvnpfay.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxemgbj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2injnhewk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmafytu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkvtcfg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnhvmdt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mghtlbeg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pyibdijd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eysshnik.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sovcgarx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxtbnsy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxugnga.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmhftho.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glvivndy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrinxbu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qadkiucu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxdhfbh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onqmilqs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wujvdinx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdawikkp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cetmyawd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqgcwyp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pwexvgkz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rgclclyh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qaegyfkm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mysujxjh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gfezgqol.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrggpls.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uufgqyaa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vaitdflv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2appmbubh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zzitnvgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcrivdg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oslsbwjj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsalunf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nifdltgu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lggonrrx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2btwykdyw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwiqprt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcdvaxz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvazmao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjsmvrs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dexuuovw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xksgdbkn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqeuigg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kwntnjjz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwjsqpz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrbxnho.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2owuaomwd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdneoqug.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xcawcqbu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zeknpqzq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2asbytxqt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ollegdpp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trocnhbg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrelonfj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlzqfjg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmptobiv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzlrrml.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeczcbv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwfajfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnaqdtg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgwspzp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2njetbgzg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2csaojbso.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxmsepw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrnothu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcljmedm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwmsrhx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2txytbotv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uujltmoz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzppvugo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyqjtde.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2snshlhqu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mxizvyff.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwjefju.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwakvbt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2avydmmwu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjpvdbp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrxvrvh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tptajcop.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvzpmbq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyvtozq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2olwbzlbj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mikfcsbv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzejtwz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpknisi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbswrrfq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcprvyfp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpcljkr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnakrrnn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mokxjnll.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqzunzy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffngpdzf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgjrzdp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2phrnhdzp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xowewcpy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2enfubawu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkcjwwp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xthlnomp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sihcmggs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbbayyc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iockuqkj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnxeabs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhzmred.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrcggfy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrnntaa.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zojgtmtu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzinbawb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eikffgdk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbqgzhx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cadhrkbt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onrvcuvj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nkojhknm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbnoood.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlkztnj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rydywlnc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqeckab.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeurmud.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rctkxrlm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aibytqyh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaczjnmx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgcswrh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtetsuv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjzhasv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhojmci.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2licobnmc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnguuib.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfisqri.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wikyyehg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbymjfne.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvdqymc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyfubgj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2glnpterv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoystzt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqigvhqj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgptnhii.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xufzkbnf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hoamfrix.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgveautj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgbwmug.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jrafjtbx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvsfwuy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wndmrgix.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcumpux.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2znwqhofb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2isiohspb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkopuxsg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuxnfqw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bliqbrov.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvenrmv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxamfsbd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpqxovg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2apainhdp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxltzfl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxzmqho.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjvnkfl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2urtrtrhe.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvldlww.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bxetdlop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxhvnru.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqqtzem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcbxepl.html


<!-- 参考信息 -->