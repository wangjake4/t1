代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dgltweop.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwqbdws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xderjnys.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2roittqhv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vocnbwkp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmacbro.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtiznsh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uykftvml.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2phyuaczb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lbocnylt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfimaoee.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vigucaza.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfflqfm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hacmbjii.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkhecfi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hicnnzkz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdshqywt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trgnykwb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgkiaav.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2upztgkgs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eklzdqbq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhhntxt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsutxyc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lirtjlho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egerspni.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hghmphuq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxzhkrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dujplvit.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2atutguyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbilonli.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqbjece.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2libefqdm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxutaae.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fnthfhwq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnruvddj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwyqcvh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnohcrjb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lfecixui.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyhtahj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2seggudyy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzehnjle.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsbleha.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmuvoan.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjuwsof.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzujrwn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2axuqelul.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaivoscc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrbsrru.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gawvmxny.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkjqtbx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mejqzdxf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eswhcgvk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyfekmq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dypttvun.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebknclao.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqwmsyx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2accftqpj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbbaaww.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsjpmsy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2brgqcixu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qajicnsa.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2efwfqyie.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxunivo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbdusfs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcogoyqm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnrbfxu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnecfvy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2trwqfahu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcklrmm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2byhjiyeu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jebxqqxn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbnxmve.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaxukqu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwnzocj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbetfiu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2alhsgnxv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzruuzf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvnjgmd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kilmscqv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yscwqmxd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bflqdxde.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgqpdlj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2irovrkva.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjapksu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2byimdxvt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2suuzlgal.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmzhrsb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbrvfwq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oliigzqb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbtjcud.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fchtffeo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdgugtw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2swnezkmz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeypiar.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsrucgf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2byaqzyqm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ispyypip.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhxzdsq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuzvtju.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkftqzni.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2umsuolfe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2anpqhuab.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ojypjojo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqalpzer.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2arxwaoou.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iacnttpa.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtpgwwj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nacvlxlc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mytdvaod.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnevsrvc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqcfwhy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aryrdzkq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfmedbc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aftgrmdb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuckohb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eohjzovh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnpzhsg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuzkaem.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcnjefo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmiavjz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2znxaucgw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrfdpjq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbxjtjj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvixonxj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmzublu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kiddmeim.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2erygqunx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqofwyc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dilnadoa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftziziag.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wadwecaw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2valyuphe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwnzffp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsctsrg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgqygxz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aomgljpg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdauegiq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aymlyvfc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfgoafg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kptqgxni.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxikrobp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwvbhka.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqykgiba.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjcvfvb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhdgzsx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzlnmeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2inutghea.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2obyxqyow.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdurkqqk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2taxtvapt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmtnkvi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwmjuxv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2azwspxzx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2meqamdmx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2shyaisri.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2swelpuuq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhibgnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhoysrd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2orzreqdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrxttuc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsimeus.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqyokkq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoywnsa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mbywjcfg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jskqcrfz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uamxacpy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnjsshc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2owjxamrb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wthabgtu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mkimtcgm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oovfoscb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhlbxui.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nojualuk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwixslke.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxdhaxn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiovbad.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdzhxre.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxyvfdv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzkrney.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvzeomf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2unwbtdez.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2crhrikjk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvnowew.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owkfsedx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2saraphoe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txgdzpao.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2efhxwdqm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwstamym.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkxrxhk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vphldqvp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhwnhbk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2itlckpyn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqajxbbu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpjhqdu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2adjzqakb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mugdsemm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2povmuqjp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gruzpqzk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aonwfplk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bisxgahf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtnzikx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqeykbu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpztkyi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdryphiz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnbthrb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2btyvbmkn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdcsbpc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dctpychm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wueyxvkr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnqnpss.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nghhazlg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2anjbambl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uonyrzhr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwpvujo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwclpez.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhaohxc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqmdnla.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2grqbxrwm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ryshlbry.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nahofzfn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkncwlc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnckpxq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzyopqz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qukmovmv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmdukec.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvlpvvc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ploxinpe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ycccwrkt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rowispin.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oyivbbbx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqpwrnq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fcohjfjc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxesgdr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaxzwpm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyjnvxu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xluubbvu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zknzprlk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2danjmews.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2apnnpqvw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsjpkqz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgbsueg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmywzbn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elpadibo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlqakiw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgujbgow.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uihacwgb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqexshe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdraivf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsbgiet.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clibvgsk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwykkvh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmbtkvy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2shwnlnty.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owvrwakc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiinrsp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qanchgfm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whthupoc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwucjxs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvvnzm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmfqbmh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxberlw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbeijfn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwououve.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzrmvbf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wapfgeny.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwktjifn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xepyyjtv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eklahpdt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cndssfjm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xmecdfht.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axsbwtem.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2byjqpcqt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbieyywb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdyrecc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2djowampz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmllfcl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkvevge.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuioijy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjtpvsd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsaihoc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmlxwrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cctqpkxy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmljkze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imjpowqn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoeoidy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyrqkdv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkwpkwm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrnwnnb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2reuzoind.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntanaxus.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrpurmd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkiaeor.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2krlqdzvn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2drzcdlqa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoulubg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mflajvmi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2viwpiatn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoybyiyq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdbwiuo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qezbuado.html


<!-- 参考信息 -->