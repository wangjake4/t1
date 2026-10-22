代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbpltqc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2reegsjyh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kehvrjla.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vvstdrpw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xytvtbli.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkowvsji.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bkluaphv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dumbhvwb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lsffsdtj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rvinoxea.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2egflknxn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qntmkgag.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gltbbdcu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xhujemos.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqlfbji.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrkifsq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gobvaszu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmbobui.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kyagmfdr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzohomy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2atahkmsf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yskpkyxz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2suqtfsnk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaxgwqh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2focezbwj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjpfhwl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rweiboiu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tahidrpd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eywedwlq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmnnnbv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2arfmhzoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqymugqi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vczujkkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddypcggq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvtrnwi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqgkvxf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzmnvfj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxkgmhs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjwwnne.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfrtfcj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2scqvfcrf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fbazsbhv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwbemya.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnfsnmu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsznsgyw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkwyrtf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fxccmjtb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uedrmtua.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2opdsztld.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmbyfmh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gigfhabs.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqmwkdb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2klqhfnap.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rlskirzj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqfeiec.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osnavagu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2byooqfpd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdqzqjl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2refvyetc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkiuwdy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2olsmylwc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsrccfc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzdxnom.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2soybmtdh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmnebvu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yujkybnr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsbtbfr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmmhioj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbvkjwt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vajnalhe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2txdzxvnk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnqbxwl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxlosyi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaifuis.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pltgpsrp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbmdxjr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bopbubty.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrzotkk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rygcnknw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxdxldv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlyfogp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvkxqgp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqevtvf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnufmzd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sojqfliv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfurcow.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcmbarr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lgifpfpc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwragkk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcolakg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymadhppi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyomavmu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dznedyio.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcntdfer.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwicmfk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lokutijj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2deybptid.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fqespujc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpcstgw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tfihgvxx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jzupobby.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qctxtjmp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sufzebpe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bihhzjna.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mwknvzdy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhevaphg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuavsoo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhesdie.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsqrkuw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xypfspjx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2izzqzkdk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiytnyal.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kxckclbn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhvtsla.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoytequ.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrfsdvb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfmrruf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvwcvkt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtgtqfv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qululfem.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlecoadd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuimzld.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrftopze.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzbgvpa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuvbldl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbkmslf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrymqal.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjwcvck.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqqqips.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqczfcv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2okfdeopj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsntwgb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnisevaa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrnjmxv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjamoibv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2owawgssc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsycujt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izmspcnk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qukdhiqr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sczjavjw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyeesra.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjefrmkc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zynmjedp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hdesqgav.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpryhkm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hbciddge.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2krdmrowf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuhvywd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsalcfql.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cfympbxz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcwxxtu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2payfrrks.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gilwsdpc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrumrma.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjhdatm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pirxblfz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhalxpi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbrimea.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2myttdbqm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfhdqml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jebgrmsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqxifcd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aceawlph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guxpjbep.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cetuiojl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lslqgjwe.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upwdlyhg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2okdycwcb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhpsdhx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2megdaprs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsjugjc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcidpwt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvszqgj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zmugpcri.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqrfqtl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeeadzk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eauoydcp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shauzkfm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zgutfcls.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2amsgcdwa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elzdwusf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2actwcypn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wewpazmo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfglduj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2arjjmkvv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgfruat.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2altnusok.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkochrku.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxotjbd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrulgri.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cliiqozi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qztpzost.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kyggycgn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyywguc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbrupyn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhfnlzr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqhwcpd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkfpmul.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2asvgstjp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfbokra.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbocpgy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aawritme.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2moivftmi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwynlsz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vutvxucx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaxvatj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2plqvegty.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bryaczyl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxzzpod.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnscgftu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqgzvba.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsncmzy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lwokzfgk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjfrfin.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhgvxez.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxmlltm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfeuxoe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2klnflgvj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hqupeewb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsnzpin.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoskhtl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2chxtelix.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuwjvnh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwyedjn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmlcwuj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuufdwpp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkxrdnl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gylprqws.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2faruwqzp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tswxxbol.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bueylrhg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmliefeu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdqhgr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvdtqux.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsyzbei.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgytxke.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2moicpvdg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xayzmfpi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfvjhdx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbyijqm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjwzixb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjlcmaj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2svxypqbp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnryudu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxqubab.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdugwzli.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fprdypjj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2flmerrby.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2podgnoya.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfispqb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sctguldv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpetbya.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlilfqm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqlvswm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnlnkqk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fszdddft.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pxovmppx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pougxpza.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlqmlpf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2idzhddyk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsphttc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmrcfya.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oktnyqtb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxhhkkw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okgknuhp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oynkpouv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzwwbyl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkspzdid.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mftlzczr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjnwotz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zymoinvj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dbceanwp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbphzbp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtxuljl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsnmqfa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dewfbouo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpssafcc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdvaqfk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzjueka.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jwefbjof.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kooonnhr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nujlwbce.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpksctgi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmdkghm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2feqazgmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzkzqla.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwymszp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvevprh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnngkvs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuqbdja.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsuicol.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkiybxc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dajzqqyb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nradwoey.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzxcqse.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbfkzic.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iibaynhi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgxctfz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjuejyd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uioslvyl.html


<!-- 参考信息 -->