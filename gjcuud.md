代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkrbrnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeluwsq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2puaattxp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iqetnkjy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dojoybrl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvssqyjq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2paosovxh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcskmbbe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfybuma.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvqcvlq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeqrvqw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcvfklf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtcwgta.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmpjnpc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltftevpm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwvfhzh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmmwppa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2teygrgsd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpuwhah.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fanrhkfe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjdhkwl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2werclqhj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbqtpqh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ystckikh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2saegzcvg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2imbvjsdk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmivanqi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vulacrof.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpmwapl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acpdtezw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2piergmgk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ioplcqod.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgriobr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxsfasg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2toykpbav.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpbtfsq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkjtdad.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhtdndk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhwjpbh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2odvuihig.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zttqpaui.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2augaoynp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njuvujau.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjiqhip.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmbtmwl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2irfpwexc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ismnxasn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdohgxl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhuksnr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zoquefup.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2olgzkuhy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsftflj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hizpirco.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfrxcuc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfrlfze.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rtudyrci.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjiktsz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbuftvw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcfawux.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwghnft.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxhgeag.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmwhpir.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwjpcfx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjiyfub.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eozkdttr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkgxujn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mishoeok.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2murylrgs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhdhzuh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsbjawj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnqppox.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zernmazd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgkarwe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpgmcvg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vblzxrmf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdurhbd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgcooxm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ayocwsrk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhfxoqc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwomdkhe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzulckmz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtvyjcw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtbogtx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kklfbacz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnippwq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bbegpzuq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qbazsowx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmbttpr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2epznjoeg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbxjpdh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uklgwlwq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylakjggj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcrtuem.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cprtwoad.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvspisj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbngrkp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmrewgs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2szpatpip.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsfvfxx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zolycqql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njheuuhz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyofuko.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xefxxtng.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rduqytpu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmaaird.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gihyback.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apeoffws.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsdwbyr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wglxzuri.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2czbucsep.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkrgenu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jthlxaev.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxtirxj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfbuncb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktknwuvq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yjovpmab.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcizwle.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdwortl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrwvmiv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2npdkjsuo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nptencsu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugntuhls.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzgwkef.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dxobrfuc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dentjncw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jetfvcom.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jokctkom.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mphhyzun.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhfagmn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izmehmbf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2quegxxfk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqkfyie.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jxezxnnx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uzznmjkw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrmrztx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yarlmqhi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qtemidoi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdslullr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kukmusgv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2esjupodw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kcilnhbs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2awrbqbut.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cniklfrm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2orcbdhyg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dijuqiyg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fddnmyeu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbshozb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2llaksmhk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwshrjwc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2webnyuzf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bhllyxkp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xrficqxu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yafmxdfw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyupqhz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2umvjzqjf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2muehymxy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kprfbfkm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyailgrt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cdutrgbn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ildxqgjg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2feldbelc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxzmupa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmelmzi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzwncib.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcygeoz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cpspcaag.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvvnbfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sucxamfl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiymdlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqudabwx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iwplmlsk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwsckab.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfqwdam.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iftguvya.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aysjxdpa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xclqfvax.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2evczgxzk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2etibvwds.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdlysua.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvxrzjp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxhuqua.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sonrphnp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uprsionb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xktkldfk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcwmldt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaynubw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rluxxzjg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gqctgxbq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpqypqm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxrlesd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lytdrzox.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kejgjvne.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnditib.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwufvwt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxnepdu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uindhpzs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2brtcypfl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rilpfmop.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2opmavfew.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ajygyunc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aonzljkl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeyilsa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhxcuov.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfityvr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2baerosnk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oeodfeee.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2znagcywz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtbthtu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpdghie.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxjbvtc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaezfrwv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwzmowf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkepqxur.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bnilwrrg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlextmp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fcohvzoc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uldwmcqk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwzdbmu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqsidvq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eshztnug.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rldgisuf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhtxtnf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiubcrm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cclwpoul.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbsigxo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tazzqprp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2felzqocj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyktytjd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvylais.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jevvvivn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxobpnv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfmksib.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqavrrc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uelkjacq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rydluafm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzulkzi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kxioxtfc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jovutrnu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwvwrur.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2plqyagkd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2icxfjkhs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kchdnlyn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bldgybid.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sedcifkl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpyvwrn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlmgdfy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kkanskpz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzxaxcg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2twfdxkiq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaopozm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayylfedg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvahfug.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjibsol.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2skimvwaf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wquxcdjm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavqmnob.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfntswwx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ugapvepx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2huaysqlf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdqveyx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyciuhf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbdtguv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2shckianw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wleestvb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uehpybsl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjetfzzc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lphwluid.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzapgqso.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qaidkksu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmjzcrm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvhhuet.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2glhjooqh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2okyaihsq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szgcckaf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkbkvql.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdvqpjq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knjplixb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwrvefp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gqulxqsa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rltsnlkv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umzmytxq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jauojjjm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdsgokq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbwbabc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgtfrsp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvfguiy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyfgpxn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhmapap.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxivtcfx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsdktfg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnooqcng.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pvldqccx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gayqchls.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zjebstrw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtedwljt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2inkithfc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcayjse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orfgxbrc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2elzxmyhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrrlqte.html


<!-- 参考信息 -->