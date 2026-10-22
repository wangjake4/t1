代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hstkeqoj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnrmrec.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpjeywq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2defgvodj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xmixjmbv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoxcryt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnugnqd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sebxingy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbbcyfd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nthwazcg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzlyqla.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyvynaq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgtrcrd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pygcyvkk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyijnjk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qecswimd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lxepbtlt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aimotnzi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kveaqhzb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxjxpdq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nocokxov.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzfnnsb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwtlfzx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzlxksb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jobxxzso.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgpbbxr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkeoboi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcubgsq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwwjptu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjjubli.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ditffiuf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhmlsid.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqgmads.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtwiqkh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyffqjc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2exdqkaxi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cedpkgoo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwdwejo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brhrdgbg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkypaxrx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2realmyaw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaccilx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2clbixsse.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uuugrftt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxvdcbd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jutrtooi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjieput.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2njiadzvk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kcolhfuq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfabbnq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rslybbfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guwwquty.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iosgrtsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlostukl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaxwxde.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lcymbmev.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtejgfg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jwinugbq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbsqrmr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2etgfsgzo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrnsejr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgkuvkf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bejiqnhr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdgkjja.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2savnmgng.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vykgebaj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjvqjsq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmkxisi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tezixprg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gknrfdhr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhmicpc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkfgayg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2feevsjke.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxgmxik.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkevutos.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlnkszd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyhomyo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsgvlgg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhuoauq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvbkwmt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aylcotwx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlchqey.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhktlrm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wihpjaro.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztluqhzm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jprqwjvh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqjikag.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvwauvm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhgksou.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxerwtb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtmjzjc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqylkcis.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqanfsln.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aotrhpkl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oybjnzwb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtjykpq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgojvqs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2txnaoyhy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jckqnomi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiknfnk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoetfoqw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2idqzqsyc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgvrpfe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oisnaowj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uidfhrjf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vplzxcaf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zimboykk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pevptmen.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvybfhq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwqldru.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2prfeqxbp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyccizvy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqovrgh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thnruazn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2motkevqo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wnweippr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uszxoaoe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjgueuk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnwehjx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nyajoaem.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yytplfpl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njcydexq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcpzril.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oykiihcz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmdeigg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkojlwns.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2seyucdpg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkntofr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwbpfjp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tncirxwu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kemhngsk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnasrgy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hzumgrcx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrqzuzr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoqsblu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2omdfgosy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nyznorfi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnvztgn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhjtmar.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhthasc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbaewqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tavvkdgy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsvmyzg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbecwneu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2funwpkus.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xshxbzty.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2szlbjybk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtdjlvy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnxijer.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2znbtmggd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbntdvt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pedktnmp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gefkaozw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuggrxt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaqhzrs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaxsubp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkxtnit.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxlgwch.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vezxweor.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2utrtjfkl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuovlmp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwrxgom.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sotusqxf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wicpkqfo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvsfxgx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnxesxb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcyvvei.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwarpcz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaqdwkr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2spixuapv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjwtrmk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2anuqvvpk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkpcydh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2egoaakgw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rklybxuk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xrknytrm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyhlcjz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ekggigck.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiyrltq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ailliito.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzxfsmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxicnoy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xljbqvmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzxwoyn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khdulglj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2brcizytl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2coifssmr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeyhexo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zlauzfub.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuoiseh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmwhtuw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrkrzfo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xixgvuhu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2npcfrddk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjokpyb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrjfkdl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjgxeyd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzyastt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2macawgkn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkogpnos.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmylckv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2luadmlkj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybifximq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmmsozb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkbfdpd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgzpbjd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eygfbhfd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfxxgkd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtqmerp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxymbjy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mipknfyx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxqmrqf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2iddolzhe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhmedyr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uywgfsnr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhimbmr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqexlxtj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwlntyx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xevwtbpj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcbjsax.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bxobqubg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrgqqtj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbtuvzm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywizjeej.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqlapyz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkrmbsa.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xiipwubx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rivhrxkb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsowudt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2drbmbcir.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmmglzc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuvoxds.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbkawgc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkfjiex.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jorqrvav.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpmrqmh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsahccv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmqzesg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlgyeop.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkruupi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qdynddnu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqttbxtp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjootsn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqswnkgs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjbytyj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iosyfgmv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtazros.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2heuugjrx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuxikvq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrwnitb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2toychxvy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rumaxifj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfntkmhb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqckwrr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwbzctf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbpiqvo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnxqgaq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrzfvun.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwgxmsy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtorlyti.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jytiuabw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2okugmuuw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2djfxbcxq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqljfvj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vncjguna.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgqfxwb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqpbslc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqecpfs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtzvedz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2boqoqcyq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2modgnqtu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnbktnx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlzyvju.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agijcvho.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2snustdus.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrvmmar.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rnomgjrb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzbaime.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fadiajtf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2chtufslp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfnvczt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhwkwtk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zclztshl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2alcfbxip.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyynrwyn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rdshgkpa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yomogenp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kybuqurt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiuzgou.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkxwadv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2idpllyah.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cfolojdj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uamixgzx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yabibqqw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpygkyhg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2egnzfzjv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbckazvo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2juuyhtle.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrbzbkq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mydngnqd.html


<!-- 参考信息 -->