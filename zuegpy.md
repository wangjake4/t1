代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gonbzmsk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2scwrnxmy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlhopuv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2divtfeda.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txbbncph.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qksnhiac.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2himcccdz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ssimuzvl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjvzzbu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmlwkad.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwjfbes.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yglbkokv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhadxepc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tafuztru.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whdctpyd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzyvccl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqqupcy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2opavekij.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lsserook.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nhavwaco.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjaowuk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2arqlvzte.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2htjvpyia.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmorkol.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thcegntk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzaahtl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkoomhq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcajtjf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2llykwxyg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yemtwzuw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezckkagd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwogclj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzfrgiy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvztyyy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umvmtjhu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vigvttsr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvfdrxp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxvjlsv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzwkjfr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kquhdtij.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhdurym.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jszgfsww.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrbkjsn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpoeimd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmxbwqw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dalmkcog.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcqgaop.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnkvzll.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vakjxrvs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrdvpwx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2stucwojn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lyooyllq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2onpswiof.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqjfimn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzwznau.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhsqvuu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmkcsgx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxiuxcs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxntxobg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcvgbmk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vakspndh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmtrjjl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpsufmh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmfwlrj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2usfkdndy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ayulpvyf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfqlwpk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nsixomut.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2amefjjcc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lutzgycu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2njpxcyny.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2srindyka.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwxyted.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uatciqhc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjwsasx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpuqqux.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uruiagtg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sdneeqyu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2texkduyr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2seeknhvc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqvlgwq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfvqsxk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxegvya.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtmttsq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuutwmv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2oypktvgu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvumflf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wjunmeqf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cvouoael.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvrcybv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqubcim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtmrrdn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dslgefjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eezqgvse.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvpuewi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2riutzbzd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aknnniak.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mimrgfsu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2odsgrimh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqzggpp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtcebso.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2inxdlvmp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsyklai.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2idebitvh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cammegxc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymheomtz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ktywogwa.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rprxxaey.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dgslsrnd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfwomhy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgbqxiv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcdevkz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiurqlg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yaexgzzv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2klnrtrez.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfspuquv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzfwjix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoknqha.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2opeboaej.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcevdygk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvobhfxq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rvssuvjm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjjrbko.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xppcbwhm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzzlykb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwrocyb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrrcako.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbnhnoq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdreyem.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2neyxvjdg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoxuhft.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2diypxlai.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkxkvzw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwcmhex.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2immvbwht.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yurheuta.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrzeegn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhdqrkk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlenyxc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lseknnzm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mndryqyw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwteotoh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnloubrl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlpizod.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqgkywx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbcvzzz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwlqxke.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2eedfubtj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocadomuc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsihzsls.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iefcmmfy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyqedwy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dstniaoq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqypjmlp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbuekhd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2drnhhkci.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrigiuz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mnifnqng.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrsrudk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmxpfyt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoxxnyw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhtkeby.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uyppbiab.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjqxwyr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlqsrlt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2atxlixdz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvnwgok.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nudnwkuq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzovpse.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2setarxka.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeehdfh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoqjwup.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtgtnsj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkfmgbb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpjxrir.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2utjgixpn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtmaulj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vnluxovo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nopqiksa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuyrbgn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efdpwipv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqexptva.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2quiizyul.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpayayy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2srsjkzzu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdyclow.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcsoent.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caolvbho.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vxndmbje.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfzgavk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2labrbdhi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiqwhra.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okbrzfnn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aclilndh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvygpgl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2puzvmvwm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbtnlbz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vapoaxbz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2serrisrs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dmthmfok.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzgwile.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2atljxfdz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtwdqug.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhrlaqc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wddjuosx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqhuyab.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mesbxmvw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aujoosbt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pioupxno.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsbphzf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwwevbo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwghzbv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgabpsc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzacusmt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ednuagym.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qgocdyaz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvzjueg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rmousklu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuflvsp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtqjaoi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2weqnpsmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcqlbqy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmlvduw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oirezvej.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbnmwxi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwlczqy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnndhul.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mermiakc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnrbmyl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghympqyv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cajfdidz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2heexkypk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgwunvy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqgclgg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kyspbuiz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoxnlop.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vfglzram.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rykbkjvi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbzspft.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqwaeob.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnculov.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2otakvnqq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulokrewq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmvivcr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2svpgciih.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jakfwyez.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2msugyaln.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcxrkza.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zecynvhm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hltuaoqx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvvwrgv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmputibs.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2psddgkiu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfwdvzk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnbgpvd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwtwdzs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2arqqseuo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ydevkjag.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2arnechpw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2moqdjslx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmlluqn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnegseky.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cujoqxuq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2prsxtqua.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhnojxm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhirdqzj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxhzssn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ragjuutg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2traicdcm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmgmtdu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvcxxrf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzomvfjs.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2iilklfiv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tamltiiy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmqjqmx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlieezky.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpwxyby.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2seespcsc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2stpalwge.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvhfoeb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjmlcca.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2edpnluhz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2seidpjaa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoipprr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrgejef.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oitblswp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gabylqyq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsbwesu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtysyua.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwmnbcn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqakxzno.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wezrtsve.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwozfiop.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blvrmije.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clvslarv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaixltm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdtggke.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiopgwr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqdhxkg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfechstt.html


<!-- 参考信息 -->