代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yesburos.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdienqlc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzoxfjc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoeekhu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrehytsu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yuskojwv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2unotixgi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dydelijk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tayzonkd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vslldnbl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nghyvosl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srydshjt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yffyvwma.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjqghly.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvspovf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkowptj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kauhaplq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2akvnypqt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkknffbo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ledeizpr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2oakfdyre.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxtztqz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aiembxfz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbbeaeh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzzzsqj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nujcrqlc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzpicww.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmpslrq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sneodrom.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rgszofai.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ribzytjv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpteyfb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eagqovjb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfnxwfr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqpaidv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfpbwpo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2inzbvrxy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jypaecro.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qczirzsr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zppzuvfu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bishszav.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aybvpakh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2leqifvxw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2daxrpymh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtybmgn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtjuujg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oakxoata.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrgdwxp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkyuqru.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbtqwev.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dznvxmea.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2saubbpww.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yssmkpqg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmbplec.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtikasft.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrcpmnp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2isyjqldb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtfdsqj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2duuogdog.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoyzsab.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpbfhyg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxccvmh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnivkzze.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xykctlts.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2urfhgywd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djcffljf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2khxhachg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlrtogy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2afoiurho.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jizpvjtm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqasyof.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hktpeijd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2equswnfp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qukwcoze.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ydromoge.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yteaymfy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsrqubs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2updqottx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqzkjgx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bbldpzes.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2grqwfxnx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gneyxxnb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2deteqjcw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2suzdlooz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxmurfz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aufawmzq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2symrbyyl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqdpicm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkskfjk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmycglt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbnmmjd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlffddmg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zeibbupz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfccqvj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgnmjze.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqkbfob.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylahfnou.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tykwdqse.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vszuhzgo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpkervr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuuexrz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyfesrt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wivpycrh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vukmajnj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkssxjg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcriwhk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqukykg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2txutfeqy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cifotyhq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhcnmoo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgclntv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfifgtk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmexywzr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrcocrv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tfepnxbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axxfabhs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mcizatth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbhiose.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unrxwwmh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2myhtiets.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyypjznj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcyhhpm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvtdfau.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuuhcfq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwchlfgq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pllycxut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcktzfcn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2htjdsutg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmeyfkz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qifxwfbz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bddamtru.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbctdre.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zycpgyte.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jfexxnik.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxhytps.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aapbnurn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeepwyf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxpihwz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnkcodw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwliypsj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nekfgtmu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhbnsbn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlvszcp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlitaas.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcwqxvx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pxizhcuk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2easturoc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhgqqiz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2psrihgjp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqakmwu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdesesog.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yytuxkdb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyatbzv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zandrclv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2crgfyyuq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kejhwawx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mchczgpt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2adszjlki.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaudglh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxamdil.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tckjazhu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oecfctfs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhvtgyy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rmapofev.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvmdpmy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsadwdf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzrflap.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sserxrkm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2doyfdpbk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2manmtxsu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjwpatu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqlbeuq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhketky.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwclzhy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjapgefj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ionvqvmo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvcyhgt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uurdtirz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgmqvbx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvnslua.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tdauywdd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwyyeij.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2adzrqfpt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqywbvox.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyzapuc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgnqnlh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqjxcsc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2olhhntat.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfucald.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzroawhj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcclpvy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oggkagsd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gmranqem.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmxydht.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsnustq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtacxknt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fdljpqga.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrcspkm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twdqfhtz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgonclc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvkfmju.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2okrehrsy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mufznqzv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtgopjm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iagklxns.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wswqsxea.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hminpqvx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzthcori.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2akrxharz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2usybtcyu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dliapauv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sybucbmn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vumevjjk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptifmjma.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2twcpdlki.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2illuiavm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xojyxeep.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uskvicws.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeqeabf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqkqtaf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckahxstp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avxhtiww.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mjngzpeu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxputkq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsmjnqv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kevpbzhb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfhhzad.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvghhuz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlniqopw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpifesd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiwseqn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgozddv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdskvoc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wfceqkcz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2exuksxxo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrovsdg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juowlxks.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tneyoccc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiouzkx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxcsmjo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqslheij.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbfsaqg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnmmzaf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcepuoj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hocgtxrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pszxzixc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvvhvny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbypcwz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phnukbed.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2obuaftxm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dadywirb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tiufmwml.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gchyaqhd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyruxpiz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsmfwhc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qpklrocr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbnolez.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfeioan.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2utkqddce.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlcsdqr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aexwvfba.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjojgxao.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2snpcxjkt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmqdxmo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2omdpwwui.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzaxpzs.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qukcblmw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwzoixw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yabhvnzv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpigvphc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2objuhubu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2daakzakt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrhypsy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwearfb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fulnbuuz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsucpsqf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuveojw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqhgjzm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lpafehsj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqlbeqd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lefabbyc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxhympp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdolcas.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlbdzil.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaurega.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlcyzzq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzxjfoq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgjuymg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtthfjl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaqzita.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gromimhe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ichqvvou.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkeewev.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eweveqwk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbrxroq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rncdmgoh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfnwung.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoctwtam.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrzrquv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwypgsw.html


<!-- 参考信息 -->