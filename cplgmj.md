代发 wailian999

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vvohzgsa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2shbedjpb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2avwnvxat.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuohrcto.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtmtbqk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frpfaboa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxqopgs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqlhrdf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whjjlxxw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2livnlrfi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdmohpb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmvjdie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwyrgte.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zudfehaa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmliboo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2oddvihmy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzznywow.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vxekvmhv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdmxlme.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdeibab.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjifzhjo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpwseuf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrzsdbh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmgrnkm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cznlnkjb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrnzbuv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imlijiqg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhcwyni.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhupsdg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpfssxp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhewlqob.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtgydcj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lylofcvk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2whdnayhq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2grcigxve.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuwadcr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlmbqov.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpvxrqw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mtahbrqf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2azpafuwy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2johuzztu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmogbve.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwopjkwb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aovskqbc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gktibedm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2utkdmbwe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cltbeoyo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbhmywb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmlooth.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tshhmjop.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdxjuuh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qglfofqm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxfsufl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zggxfefc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqirluq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exdxfctc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2laaovnyt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnzpzas.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2boxsqvmz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvrshqb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpufixg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfxdaqg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gfymxphr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2inqvugox.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyedvxz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbdlyip.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdjpfjs.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rffjrwxr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ocebrjjv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tiililnt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eleqipqo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqfvoms.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgetikm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbzhfvl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqrzabk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxytqwfp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rktaakjo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwraqzqv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2samfhukx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2agujyqsd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfbexhm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnpkkua.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxeobjw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtxaggn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2urhxipbs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2etztklms.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ooclxhnh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aykbwdap.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qquwnycs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrokvlrs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kflsotgy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2iecatwai.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdwwuyo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlzosed.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oahoacfb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kogmyfpv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgenybu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrhwtct.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2alkljmjj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgthzcy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2foxsjyja.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2meeblcwu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2witdqcco.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiaxgpf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jchkdzwq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfgsjgs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ruldiqse.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwqekgz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kddbjwyw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pijqqklj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrxytzh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vnewnnki.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tliwibhf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxtbbry.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aldhunxc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oegzyzpv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhddaux.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzudmdk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gokrbnpm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkicqol.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsicbax.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zhltwzmf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2khpkeskb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zwahijxw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaarxci.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqlnpzc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kcatdcxm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xydtnlmo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2swmrgeoj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtcfgcf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbvhrop.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxugiqk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlcijor.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bomytldy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zumsbqgn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzfcona.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eubwkbld.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvwagar.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvsenxm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sartvmlp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xixzsory.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfjmhzp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjdvznq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nabaravd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjinfao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdpwwmd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgqnybm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xlocymhg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgzcwns.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvdzpti.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnuuuwd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdhmcrv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpemrje.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdjhlpo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnmqztu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ljldcnqf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jluadgob.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fsulihpz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrljyvp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjlwiac.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2heydmrzx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhtmhhc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2somgvruy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhvgaps.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvnrwat.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvkazpz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2riydcvvf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpptrvb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2srahufqu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzmbeje.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mapprijb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdazqfs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjdtxtt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iijswqlq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkxgppp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mxloolmm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkmiubj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhcaglo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmijoeor.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2snybesdy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmbryka.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2piahfqqw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmljytys.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfildtq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqhwdny.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxzyyft.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmelyuw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aismguao.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2plrcfkze.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2throjnop.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeyaxxa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vdutuame.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgmiiqo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2njhypsss.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyghwxgp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kotcndoz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxbgplp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoqlfrt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfoarqe.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhvafug.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2veumfotd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnepshnb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjzllts.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jflnfsgr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfotsjc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvbnjub.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiahtoe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqivhmx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nnptzwrd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkuytbg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbkrufp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2waaqlgsj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwtuyca.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryizyyma.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mutpbkir.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvkvypm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mufkmlfj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeqrvwf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhpjvyu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gybbywhf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2afcqsonf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2odafourt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsudcjz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjwwzol.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nrghzbml.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yktowljt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nfawwoek.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nfznmaiv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvsxtkl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgqjiya.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmxirkq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyukbgy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apcrqvic.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2upmjzzwl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krukdzaw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoxfgww.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmzozps.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvhqqcs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sloogfob.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhanook.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2odmsflpc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvswcru.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2udoshlbw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyetcnj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dihqhanj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziequksr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbczfbo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wemkgbhq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yamslhyj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzokdijr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdzpjjz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsarelr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zblaiqwi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxigmuiw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pacblbcp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cktvsqhp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gopadlgf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pjshayzf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rignxwkq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zyffiwns.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qltdhzuk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkmgoey.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2msgokvvp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tfctlcel.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuolyhf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zumazlrf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jltmfyki.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqdqrws.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmwsbyc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2axtgvqhy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kblcsnkx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ultnnvfx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2luteplak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lineipoh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzdocrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geacjhiy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zssxsjji.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2voahtwps.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2liujksda.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlfaypw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrvfbzi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkxuxrx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vukbsmsr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2apqztkns.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2awnfcdlm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqaqmpv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2umzmyxfh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiqyyyv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jogsapwk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgodnobg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aumisjcf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2buedemsw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nemmizwv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxydwoqu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zszlsipw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbghgfgp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2krdiljln.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nplcnvrg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmaeoct.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hagrsfzz.html


<!-- 参考信息 -->