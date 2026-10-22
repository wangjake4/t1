代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtqwmtd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljykbzlm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hauakorb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsbmxah.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcdlltx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjdbooq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgdagqg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsfxsgd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oumwswaf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxeigbr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbbddav.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zerkiznr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avyihrui.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeektwk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2abeyzkqq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwvaatz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djgjjwrg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2buztjyje.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrgymex.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cflnmith.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfpzkkq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcccduh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ddigzlzr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xcricdft.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsjlnju.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjlapfg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dapfpgwk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrxnpjx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyhbryl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uflqfhzr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2veyydzkg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ebesfzyn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrcbxxo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjesfix.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xghyaean.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxwfjoj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhklpawx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxsenxk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znjfsxli.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvextagq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ulijypav.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2anxtbwyw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvqftze.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbitdyc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dquzpnui.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2utmuhnzc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyesirt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkbytej.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vegeminb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zksqvvdk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbovxhgy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhddwpa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyliwxd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2anfkiwpt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtfnrwh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuqtipp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2idlqnddv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnjpxmh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2duulgoif.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2acvgewbe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bumidhha.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wklywbqt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwycxoe.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxnwvwz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyimcba.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jybjfpnh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ietiiwls.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qveetcbk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eycdoovi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtcumyn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tueavnjs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qrffkomf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nwapbkud.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpvsrta.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zfccuoxv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfanlxj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cwenerun.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpiytge.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sinhohwk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtgjxsb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvcsqsa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fgegwvyt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkadzbv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoucfbw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pfutfweu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zbphyjtz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgysrla.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2flrsgduy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lspmmrro.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2abynqwdn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfzfcqw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2txagogqk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mdimcxwl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lszknsmp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gwodrqta.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyjeozj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sccyiciv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2atbhvohq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dncjbtwx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2megxgibw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lnabiioy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2btwtqkwn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiebgdk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2coulsgek.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztypoxxg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sajwzruf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcpnkzs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vjocokbe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zabiivsu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jymljofx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qasolgtr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2opafarpk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbyvpiu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzwkean.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlhemil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyovyikz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpxlrbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsvrony.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhdxqvl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfvfpyn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdkmumv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgghoqk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2otmfhuxb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmbqqkj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2utarsyvv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2coqvzvbv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeutxdp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jatnqwbc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepmobis.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2matgaqan.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqhwkzs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jymksoxg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmbjbms.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnsqczv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uklgpaed.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hhssxlna.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aljtwzdx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zdftwrzy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2axuhrfdc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hoguciww.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrwkwrs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqezmbyb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzpyqkl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pycxhxmz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cghbwgqw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wevvqrnj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ownqqamk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrjdgbb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sprxexnx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpbnhet.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rslplwto.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2htgzrkhz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rstbyshe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoadwki.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzldljp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvubqumq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmlbwgx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mtldgbqd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sodbjwau.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfawqfp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2htbybmpn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfmvctr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzmfzcx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzkmgjj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2grthvriv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsnsjzn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjflrqa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bldbkfau.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsnvnde.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2imnlkokd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uefnskfd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyucifb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfhpqst.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2znvrigkf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2azlwmkkq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgqkoic.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsdtsuv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxqpyyd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtivthtp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhfniyw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hrizqdww.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bimlvryk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jimgzuol.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2anifbwtz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqooyth.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtibbxt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tautzltf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tammcvor.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyfzdze.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlnrpau.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhhymeu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znzbmklr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyjpbod.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgobcnu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwkhrsf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cthmremw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaaubfr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izcnbopv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2npfjnfbp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iziammxf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gpobqpah.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vugmzxvv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zovapqbh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqscxur.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrcxflr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vueireua.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syrajhud.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkmtkpm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2umsmcnbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2otuundbi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vqajksdv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ongtbpvj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvksdgo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kptequbt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2myqlwtwf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dklttqfx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pvngfvpk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxhwsxq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdfzfgv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgadrxzk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2apmrrhjw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfznkwej.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvlvqyg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ipczbzra.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbohoxra.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhqarwa.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtbiwqc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbonarj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyqnprw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2eakazuug.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuodzwcx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qydgyhjk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tisiknkt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmqyzko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2stgzwqbp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vucucpgn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvsakhs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gozhpvkn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2alkuxhar.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xlftgcfv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvlyuvw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2attulkab.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeobvewl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxspfyh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgrhdpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrfgunl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxmfjwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkscsyas.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbcogsp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sosvlkrn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwodlnon.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeofxpc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkwyaba.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bliamuqt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yyscafld.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2opfphaot.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkroqqm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuwqrve.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hacyuced.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2feohhjel.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzxgdxh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rougtuss.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcupnyl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkhzlmg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uktbgcer.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iidnifbz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrxmdhh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgdbggq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlemeak.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfidseyq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2adcfvtyy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcfgidp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjhzpie.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evhmuwzq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2koxtfrea.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvfjqri.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkrgodo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgkhugp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fanrqywo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sosfdexo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rynnhlpf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2heztmujo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nslkdwcg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxysynz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhxqjlp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiunoun.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aogaxxwg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2exepboku.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2urypcorv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2acgnqvfh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyavkvy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiwaxfc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chglmumr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrymhrzl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrbxegw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2celcelpq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdgexoo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqdcgme.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqotbto.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijghjiwk.html


<!-- 参考信息 -->