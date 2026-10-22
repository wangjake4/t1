代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgaafld.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmhwltq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pspsazfb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gvamlleq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeuqicg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucipxiav.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vostssjs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjvsvyk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqrtels.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yojypcbn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ggccyklw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2omlwegiz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2knecqxcf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwwvzkk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oflykzdk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fatjaqmm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzhtwxa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwcorrg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsvqvta.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyupreb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaefqlu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeiaqqv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbzelcg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlvqbsn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2soolgfyk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqotxtdf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtaxeji.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2icqspugd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfpdwet.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lqybnlxh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhoqiop.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2scntcdcz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ougjzdku.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsfbphr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfojoha.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlwfhqz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2auyloxkl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2piafcymt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhjvyba.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdigkpl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlkadzu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gciylcdv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tisvphlq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyqoyke.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2afnwlvtm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcjsyvu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2elmihvqv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vtymojkv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2retpbwqt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2scmpfgno.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zvehksed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhiqcfc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrfknwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiyljcn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azjxjpac.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iojniihi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntsrxqm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qtenecep.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnigknc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkdgzat.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjekgdxi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zuumsinp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oeprtkey.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vytdiper.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcepic.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2swlovbfi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fmflnchu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kacgxlbi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pructqtp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yqluvigb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymucndid.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vryhzfqt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ocddtlub.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfdodcr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfoomrx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrvfnhd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnfgquk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnldmrga.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2olhmwgwf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxahzjb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcbfovt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uugfjlgl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uozerrhw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2waforvit.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2utsumkku.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2buxxwrbw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2exavytgm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhqmkkr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdxgmkn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rylwwxwc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsbcdpd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwojthkz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ituslene.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzvhynp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2khsfmcjt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sruvqjav.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejytdnjl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ieotfxix.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2eltjnqus.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjcckzj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbsjyvj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxteqmeo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieytgnlc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tpihsaqo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkpypkx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkeyzsy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xugauutg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvytqfy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnmfmsg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfhzhhv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwzuvbs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqesyzsa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpdgorg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxejsuwv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaxtujl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2umasqgaj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhavgzb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2emeloifj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcbflve.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mtasvkce.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdfoiuc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdffgeu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2trmjcddq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dffsnjej.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzigqpv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqafpqe.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwcqnjy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrivoxy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2oahaemgx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrhjcxt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtenpyv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tepgogxn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2enqxnyge.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrlewtr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmqlltv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqryaxo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbesngb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiycrpw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2abjyiavu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yznqekpz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwtirof.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yamphzgq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpyevrp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeluohv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2myphcczy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2llxanexj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wzickopx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfruueof.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2myleofgy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfvnarq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ljszdowa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zohruwkl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iisevrwx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsgeakq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khzkkrqr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxwvnkg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbdyaof.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqsgqju.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhcxqhb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmzlwhc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzucauq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2klshhnzl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xugggkgl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzennas.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfxqfas.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dadihrvv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2orekjsgu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yftocbor.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2smztpdjj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzpwcql.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyjendq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sijztwfy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdylcasx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dywjvaub.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2djfxjdkc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yngprhdy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxnioac.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoemrii.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2flmusocz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlbuejj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtwkvga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcgtvrt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuxrckj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vapegqde.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pheexadj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzskxkp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eevntxny.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2baesxdsd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrsqcgs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxvddap.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2imzueidq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnnvdmg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtlvnny.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ygumbmxw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ggurkddt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvonhkom.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpwgppj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2evyerryh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zptvmdxl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iixpmecw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnddnoy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2epqawikj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xiscezju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtyqpgv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2orzorisg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxzuyzs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhyvuqr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcwofyr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nriecjgn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ympwfvnh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2asibfeoq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmaiota.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nclulgtd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkrgecq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxfrcuk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2itlqldfm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2slyetojq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smdewkpi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2swqnyrll.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbppczwj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2akcvyxei.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrauvmya.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwbyxvq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsjpjzp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2glhavqnm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfervix.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2exanitxm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wydbsyps.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smnzexgi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2macaqyam.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsglohg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvmcilo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkaqqnl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcblrho.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoxgvkn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bihlylwa.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xupzoiyi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2juqepbdn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwjdnzg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jigricde.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2godgqipb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjlbqni.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mebgtfjg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvzjhuc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdilpwv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrfmhpu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upzeexfh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfrgdsw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnsvzib.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jegxszuc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jesgikuw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmjswdz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwzhwbh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smicmgmv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqmlchy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2otpmbraj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfppgfr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eanjfywf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgstvfj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iahktmgv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2liemqksq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnoqzpe.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qeriivrk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnzvtpt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbnkpes.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cljigobo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlkpmxr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkaiing.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yftypexd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpmbopb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcufogeb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnlhcrm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dsemuzwg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcqqhyv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiizlvx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chktryim.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzvpccj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axnyruuc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmypvpm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2briykgeg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmsyjmu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfgqfkg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzoelgm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyqnzxd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbvxmat.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkngrsc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcqtcpm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyokkobs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwllyym.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aulaecuq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfopteg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qufkpqsu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsdsvcr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxqhjkz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhukbf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoufghx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvceraw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iadbimbm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xisizxpd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrlqfbg.html


<!-- 参考信息 -->