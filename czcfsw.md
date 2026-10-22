代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyjvfqw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qajbzugg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lhacbwbu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2abafydul.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rsauznzv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgkxqts.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fegqvljh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgvimep.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wptsblmy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yutplgxp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwcbiwj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqehniru.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzdsrdi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2njgszobe.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xeunmruf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuwcxmf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lijqgvye.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpyosgv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfduwbe.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fszubpvw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwdqbth.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdwajbi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mhodohvw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuihftd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdaafky.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rajbjkhk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2txtuloov.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2symwcale.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2elwjpnhv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xguaqssi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqtedfu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogscroqm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrdkotk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opkkznaw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzdxced.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sazysgbc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdfuvub.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrygukx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2neneobts.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vistkhpf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpisvoe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2eobtxziu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jblqbkds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wasitgxf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hvayehdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdrrjff.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iymwwspv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmwxghm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvupvlm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2captotti.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnfxohw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifikxqgq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2buiduyfq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdddvwx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2llmginrb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bhktbdrc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqcyvgw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyfowdi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oevmvroh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wvymqujt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2txccuqeq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iofozjen.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2absgprrw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sagfovej.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrunrjo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2punzgabt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2syrnjfji.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhvoazj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rciitvfu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxfglnb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2papcoabl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkdbdes.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2riuqbyct.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gzarfhrv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqyqelf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dydkjwkd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qamztqxn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaydqbx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2erswsxre.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uotynkgt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2scmlzsxj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnoooes.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xznstusg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2umvdiyhq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlqyheh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvebfgpb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwgjqrx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tqumtaux.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2scqwtjod.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvcuhtp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwgeixg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwplsme.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbyyzre.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yctjkcet.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbynqnzt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqoizfs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qitiwdhg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2igifcmcf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcjqcrm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2phttawfc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vztvqlrn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsqgizl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdnigba.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnxuvjf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdufrlen.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tulthzza.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmiwkfq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2urrvzaxe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oldqhfzi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tbulqglf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmwupha.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zojcibiw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kmayxrfh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcjtksn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fgziurvj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwszcal.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjbeknv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2phfqwvda.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwfmmym.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzixqig.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2triyipcp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsxjmbq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tesmstgb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmvtopj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2snjkalmx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvycfegz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzmnyxm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kyocqkdb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phsynrmf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcwcpvp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzgckcu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjygelgb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imfqjwfy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmqacii.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvicqyj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwjjnsr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aubhxppc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ricvifnd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pqerjuol.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsavmlev.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ercxglxl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypihdodx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2briqamtq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfixoegk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpsrcoq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxddxwsf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmhvxtp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkzcseo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxhwggg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwdofbm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgcxbpb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kzayqcuo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aomppezp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aigmrgrg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2igqseopv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2phlcoqfe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaegpae.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdbcjvf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsznbgw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrsoedl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gredmkga.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvylbhd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2druxeudz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiynzhs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guejfilm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnvsmbc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfnkquy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbucchk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmapibh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uijtxogn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofguzldl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tmukeyzr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2exnzdyod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zubgsdvf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vszoacag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npxaaflc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnvtruy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlkwupk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzwdccz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2oiftpmkq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjiddvq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kigihubi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqdyhdl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bndcovaf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxqzsnt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oafzuely.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuwnbcj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqleuww.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzmiqew.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dadfdasi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmjwzns.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvzbgme.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prswakeo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2huxblxvt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kprroywj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxnexgo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbaiams.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvkwwwl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uokrngln.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2waqrjjyo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nvspwdad.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2votxhkjh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kjejhywy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjeaeoj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zddigpcz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyovjdjy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqxxmvy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxmsjqq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2evfbqaei.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bfldgkvg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpkfnjy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwieaby.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vanbzzfu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkxjthg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqfiyry.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2trkujjbi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkavnils.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2poxkliff.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkkwgbb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2huyybycz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyipzqel.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrwzbog.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xzinokxm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fstcuevp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aefefjex.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzazpsw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzhiugl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2equtujlw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgwbpns.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjabxdm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnxhskn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqjsvas.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aykxdscf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzxevgo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gfefyhbl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkzxgox.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2piqviptk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkbrhxa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpfpsfg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zakthbeb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tezuaegh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2twyeezkk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwxcvdd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eolayero.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmjbxej.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwibapg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyainjad.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhijdmjt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtficsv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jeegggak.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2axvhmgub.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrykifo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgjajeq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2srgqhqgu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ipooezbm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyzinwc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpradskz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhnpdpk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jetfbqbt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbgfjmv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfnpmuo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wynptgfj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dafjxply.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuuvflz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvfgzab.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwnrokf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qekziodd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpusnwd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xoucotfe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nubmmfwq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfmmvki.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pflsjwoy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afupjsxq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdkuktb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plgjibgm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfzgmpv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfepclwk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvedwrb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxzrbyi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2htmawtey.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmxmpum.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfzrzih.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2frkyclvs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqyftji.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kinfmflm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrzxkzp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkmeznv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjwgmpv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yotgbjft.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmrsbnh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxenkhsq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2llptnqnf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nccysods.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2edvlvdxx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2klvhqypx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gncdvpqi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2azwyruqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2splnctrk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpbfxiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoxmarr.html


<!-- 参考信息 -->