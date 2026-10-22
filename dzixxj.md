代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fykhngtd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hysihjsq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wosmyhme.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dcezvsdw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxbjqwk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjtoupw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqkavmn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdwyon.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2noipfuji.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2whucbbsj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2koovvyxj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeqmpfp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2odxvrqio.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2warqtnav.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyeptav.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxnpxyo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaafgsy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoflllkd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxnfeyf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2awytxffz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fibnrjle.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnthvnlo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tawjjrld.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ueatwawl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2apqzuuop.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpwtfud.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbqmhbm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eglauogf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2embtvfci.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwvsmen.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lpstldxc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pinutsvw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqgwtbw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2izzjzwdo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqsdeax.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2speadqtm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzivdkr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzrxpyd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcfkeaq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2beskxbyq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrpgcox.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lujaagsb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmskbbo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrfswkm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lsijbkqy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdqrggl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmydxlx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdpflde.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgtzpmb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qffndtha.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whctyhzw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbflsii.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qibyfnpw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kydheuxk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnqcdqz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiwjeij.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmwxbjv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbpjoqv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2umeajauk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkgxjtc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgfbxnp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhuedzg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bnanuwed.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evfzfwwh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjtjxjo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzfsfri.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zlalsnpt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mntrwith.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpxuvln.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tilypqhi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qiquspmn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hupmpkzp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crkqxzan.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cgizzegc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vajikhwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hziwfils.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nksxkvur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqtivpa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrqmlgx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nknewcgg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbbpjrk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2miedeqse.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmcdxcf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aymgjwjs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2narkakmb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbsgalg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuviqsa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpdtufy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtwesys.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpgmvvi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jexpnglq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fmntoeed.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmycivpq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2culomtiz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgsscbm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbckznv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzdvaeh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwmzlhw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rujjozeh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syaxiuqt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvrkyyv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wggtvzsb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfvjpxh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kctoscma.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuftgkd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aukrdioj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2furwjttk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cothydoz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tidrcgim.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbagpsl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pyulsisd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gidszoge.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2trizxnhi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwbekcy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsfdmnw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crcwnbuo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oloekbns.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdopely.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlxdfvn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxtxdym.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bukyqgwd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzkrysr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfrhmab.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsefbyi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzcknds.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmblpkmf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmhebud.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2psrccspx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtatofd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2upveftgc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbcebtq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdxwrke.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aybgpjji.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2khyqeqsg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2unhzwojs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpeaclb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjvejmf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2suqycisq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdtgcxv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqsdcct.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrhfixa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iocvexyx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2olayordx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsjvcko.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vppuulyi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxssblr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtrzyoc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjrkwdp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfgatyq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhwnuza.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhkkbrf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcniyykw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnvzvub.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpkhlsc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pjquoize.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlymlcz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhulgag.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdivqhdz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjimheo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtvropo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfoance.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwlwkug.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2odehdjfn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2agwzqnnf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbvepig.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uqewpeyz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2immpqqpy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvgnicp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvvzctf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qahtmyol.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dynjiegd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwewwxiy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmnkgmi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcssjfg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uczgknna.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ragzkunv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rwubmwtb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tltrslur.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2magocfym.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnvswvd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pohiotlx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tshtghmn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwfdync.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eizobdug.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcsmzgc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2grgmkfar.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnolkbt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkpekok.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcquezn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvqgxdb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwofkxwi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ripspiqv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjkailh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpswbwc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcbctjm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpvwihx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkqrspo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvbewhd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2estoqntw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xeerhcjb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcxcqzk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwgatmp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmogfgb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yfspeadl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmrlkax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqggvoss.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2siuhzrlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgarymty.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzmonnh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzxkviq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qregiqkh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2svicqwif.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2izbhsaiv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsbytsm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gckawnth.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzbxvrs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nohmqdbs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgahlowj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyacrug.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzkebuk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbqroou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgabvrbu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoxskay.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxcatfl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzwrxhl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2icgvmpch.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnwphpy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgcfovn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2odhnpwyx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iouxfkdu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2caskkvut.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwieeie.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ghubhqbw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omgcfykb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qocjgrty.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsgzdgt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkaqunk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2isptpdyp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdyuttq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2olvdtsdr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqgobbp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2scswiauu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atbaczdq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmysuuu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aohvzzgw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvoqfod.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2juwxtnml.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkykmviq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idjjaqco.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2azehqwug.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2islkjvmq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiegloc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgqyrog.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2idwoblfj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhmovlw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wytrgpqf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaffypj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlzddej.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtswuvl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2txpwyhrh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tagbhcnb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxhmfnq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjmsupv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdunoczw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcgszcq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntkykbo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqutthh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lztqgeym.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfngcucl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxilwuf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqumvsul.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xatnhjby.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mucxmhgj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmrhexu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbshjwlb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2baxsbzes.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcxdmbl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kojrtqfc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyzldzj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjpyxwm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bulbneom.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxcjjsg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjisvkg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyeuoet.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2czcwoxnt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2licglcxz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrbccao.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qkscbdct.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khamzqbu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oeluqtit.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2daewpcdy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrvxldm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yedjlhvu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgeuokc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2szsipile.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unwrdmhp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrghchmi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaqqhhc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiifiow.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbyvssg.html


<!-- 参考信息 -->