代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnpmogd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxddcpfh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjusnwcz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2irtxzncz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzfxhdj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2briuwrdn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvprhcz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lpahrpzq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmmssfi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbzdrlt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hkegqjhg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjednoyn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpiswul.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmxmlwp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocujzdew.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2epouwdvy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yempdaap.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxovjjc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpkcdtg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djaxseno.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkqzuxh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2agbiliwv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrrtlcy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpbuljr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbcmmod.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucudencv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqtkamh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvwxnzo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2msbuebpm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jajegkud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2efoiremj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ejirlttv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsycevp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhxstkc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2utpmonag.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoeadth.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfryhcb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2imdbjnqh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjktnlj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czartgfn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bsundabc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfnrdvj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwydeft.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2okypojfh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flkzokyi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2drmyvbez.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwjwat.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzamyzn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlhclrt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2comvoemz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiejpiu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgvijdr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnhetqd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2malctpws.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qllxpfvz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efcaeses.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfvcalw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2krepmkhx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vsknhort.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2henvrucw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdoxnkt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdwfhmh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjoabhm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2imidbsrj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2osczlinj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmhgqle.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yenrvtjh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmbkili.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tychcgmt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eqolbcli.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsqbemk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zpitzakf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qvydanbk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2thtkiccw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkykdtk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2teeibsba.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rpixrdml.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdemeoh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdbwiah.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmgauol.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbrugal.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgogqwu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnnskkm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2slujtuxv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2guqsvrsk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qilgoovv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urxqboiq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xvypurvh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2etmygfbw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjqcyfp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqbmdpr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ldekdfkw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcjorol.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrtatwq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lbocqqwf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyfkshg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqndkkl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpwgboo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkearup.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lafpkjki.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwgbxsw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqsxyxr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvlhmud.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmlkhpu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bjagwmtl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubefiisz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gouefkko.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkwjfds.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wtchvugs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmictnj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbkblil.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwyknrv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfjzbvd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2udlmcvfc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2znadnbmz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpnfuct.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzibkhg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jsppscip.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkhoglc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcekpcp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wihcfbjz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvxdpbn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuvivyd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aquyxoru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgszszgm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2buiyyzri.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiuaegp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmrqffp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kaovnhic.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eapcmmyz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yehptfbe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxbgzdo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jubkcqhj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrffwxxg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmmwglu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrxjawp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lquhckzf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgoxtyw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ylislxlc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvtdph.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkvjmcp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hiioyzkh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gylepfwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkovlsd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjgyxtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olqcsbiq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unptaiqv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lssehthe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyomejmd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqgvbef.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpfbfik.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfarcblg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhatczp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ficknpdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzywqsh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgdlatw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcxznhf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tcswedar.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzjnlex.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtphdmt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwotyxc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fscebcxs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2scbngjul.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxtuufa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsfkwrx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdamtar.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkszufe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sugjherf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwardoga.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2byeeasvo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xahgctkh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drkwzmkw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnqabpx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcpxvyb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmurmeio.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvvwxhk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgilhje.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzewaruq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzjplkz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ourbdhyw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwjlahu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhzlewy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggboitws.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgvamab.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2flasmwyl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2defysqoc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqspiyql.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vwejbgdv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2upgihfzv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qggqurcu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2umalkich.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuzrqum.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sofqarve.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2muwkgspb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iouxqmxa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ezorhvih.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2aawpkfla.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbdcleh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbqhxrm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxmvldf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cukgouco.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwnyifv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpzgbtr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vllfqoae.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyziknh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sltxcmkl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxxmqiq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyyxdmb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjcqast.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vuurhzre.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgmsjpy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnsyknc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2josfjohy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klvazsot.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpvnsue.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmijlld.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hrljxciu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdujlgt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxufdae.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdppskyh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gejyfxgd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgsjphm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qacbjdse.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnabgamu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxygvuk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwcaicl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlpvaqa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ccswjjnt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqqbwia.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwfksvz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ezprzhyl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnndfraw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efxqhwhh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eefxjorh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yslckeud.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwhxfyi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eokkakul.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbrnkhq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uljdslmx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvrdqif.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnkqyca.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2caqdsslr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhppupq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moocdvbb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmjlgoo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riodceca.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xphnzqut.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtlooic.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddclcdjv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swisegmw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2erylmxrj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhwdqps.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxolnusi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nayfulea.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ggossaxn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwcotfv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjjnucg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2crtzdflc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2skueyazr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lwahrvad.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yroskgtz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uslfgqkh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2usqrrccl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2efefpfzy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnpjuqm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlyutvu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pedfwekz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvvqrzz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkimbbrw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbepsbi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyclcgi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeslwdm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uamujeio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whsgdzdp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jncpkcvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elnpjkqb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rneqkdxu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtexfodp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjlkwsp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fwipfrcb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zryifanb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yszxbgph.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rltctiql.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwfjtyt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmzbozm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2etjnnbzx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2diovlhwt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nigalumt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bklrjbse.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtfvydx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gfblxmtu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsywzpg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ituugaqa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kafzbjof.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtynttg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bogkqrgd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zordtglb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfampbe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfubozp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfmikaf.html


<!-- 参考信息 -->