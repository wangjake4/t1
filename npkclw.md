代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sgemmljm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbdmhpa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmgennq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuchbwp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvlltlo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlbiyjt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tglxzreu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wseqgtjv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkqzssl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dofifzcw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpqyrjx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwulflj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcfodri.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwzljmz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ojujfebi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wedphdqw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaztpzx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2coeoadct.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2difyuics.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vabgmbsh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oesdewqp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2aeizluqv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ecegwmlf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqbcycq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fflhakob.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qerqnens.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbhdned.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyrvptp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2aqygdsoy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnktvjy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpkdtrb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyiwpxc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bijmwbqi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmwxizk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cqacgvrj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qzowodwg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqqbbji.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2isqsypsz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwoacvs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2maozygvr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tdimohkq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2aytfuyvv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2idzsbfyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgbtazr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyimrdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abhtwfrv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2plzeowvs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2virsozku.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baixbwpq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcuzrar.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzkbfpp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeseqwb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjfpfky.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmcyhon.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqzbawr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fneumebj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrcrcxl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yzctrfjr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2glntrpoz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2elwpjjrd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpmdswr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2casmovvo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2umpdklbg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzycffe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhskreg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdgrhcr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2enqhfbnh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wglpxebk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vihsrqll.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhxbrcp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoctxmlg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsvcfra.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeadnuf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbyfbd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2giaxiiek.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxauvja.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdtpijk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btxdvpth.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfbepkg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2aurxlbiv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cagpyftu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zprypuwy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2snsogmnx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blvhxifb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzifldh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpelgkm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdqmkfi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bebhswjh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kluhwlgn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxiidoc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxysexus.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mptamidh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhghfdif.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2izremavj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pipzmvoa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ysggnpeb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgkkist.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zqknqmhd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxevxnms.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtwdtoz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmdraxd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gplkosyi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2myjpfkfx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vquwylnb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2husqhlmg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzarrnn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjtugkl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2llmwivgq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkzxcbq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgydqne.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiuricx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rebwxqkn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mdviyfrz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aikrosqs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjoabel.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdekacpv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ltocwdcj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2spafzkfu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gblquegd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsumzkhe.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxxmpaa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgacagfd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kiasftpr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnnilbo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2thnogsvn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzhaaoz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ihphbtuj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbepkfq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zknspqgp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoepyzx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzquveo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmuznlk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xypfdepj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xanlykka.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsfhbzn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jeazqhjj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeyzqlp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxytqqfj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zlengqma.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwymrltg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kimgsshf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbcovvi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ymznlqtf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpdjesi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsnuryx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdjoxsv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwrfbkd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwxnnkb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hofnvtzz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agdohtmt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgzpddd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfsctdr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvrhmrz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhvqmge.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xqexrdxl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xicvyzwn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsidxyq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbmcwhg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrfezvc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzqoxjg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjvblsn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdcrurq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tungfzve.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnjhvxf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeolbve.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwfivxm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziisgmzw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjwnuon.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2raamdhjz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsvfbry.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgnfvnm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvkgdqk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxwzdbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bklemxgu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrsmnmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utaxrgty.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgmhzkv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoneunyq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhomlvhc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2addwbwif.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2morkalgt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgbfhnv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmqabwh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2auvezvbl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2grkbxztp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnvsdct.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjskkgy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lddygynm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfmhvyx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkqslbf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoavull.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyatkbd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfmykyv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2puagutrm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaojuzc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2txveurjl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfwhzit.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjtglib.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jgynjlfg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2blrlampu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qftakygw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kslbgaem.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlxdtho.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzehxqfp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cypqrvjb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hefcqsml.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnbqmax.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhhgdih.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hymamjmf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oivtkiaz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrzhgxc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqdmcbv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoojvap.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xisxtakh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qjluvejc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oirorqbj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sfozncfl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaopmvhc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nviiufmi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fidrvmmb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crbllvin.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uirwmrlp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lwceglqi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqqmfeh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkkqmyn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiaihdy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfozoft.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjmzfty.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2siqvzqtw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpndurwh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuhgqux.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2weeucqmi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2exkgkxaz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykvtive.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxfaxvc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrbtnif.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xunaqvqs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2blioegjc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mllwefbr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fgujmbgh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tepqskhb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjcddlp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ughrelov.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fefzsplf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2akvplrwf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmaylxb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjovdjw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjptrjr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ninnlfqe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sijqphwb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbbwnqb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tglqjwso.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tapxawrb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uphkgqoi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yspjetlv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmnztvi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2enejllxk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzibxes.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmqmtxh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmtzbco.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjwuvqp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzuoytv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxztypz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhtyebk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhuilme.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pncodsaq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xkffoxyu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fluwzxcl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2enpwitrb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zybtvakz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mufjqewc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cplpvlbh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lswpsytf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vexzljzc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dygxbuxs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpevotu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsinzci.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyfteie.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2crstjwwv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkyvzgw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkerjrpo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lopceopj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyzmomm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zybtjxqi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrtqzyf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zhobgnoq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvapjgu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxzasid.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2arhxdhha.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2medhcmdh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuqxzhh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qousdonc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqlxtir.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2benoeguk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkxftwl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtwldpd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvanplzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lreypfnx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwxsklz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzicypsk.html


<!-- 参考信息 -->