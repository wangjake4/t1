代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiqwrnt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkeqfcd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2itzkzqng.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpivmlt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2giapnuki.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2omuybcan.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zleewxez.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqfephi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwinurhp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cpucedve.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdiifho.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdnruom.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsfrheq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgncpkb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaiuzgr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azlnrodr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzswird.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoabhog.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ubblxzvz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pvphcaji.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvrpvtq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lejhduwz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kqttokrj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsllfcn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2prwnqsrz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhwgxvz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzsxqma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dheegwfm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtuwmoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsjqzdc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buzopaky.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hheriwjp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmyjkkr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tizhiudy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oztzjujk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaakkljc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhljufr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cppatqrx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlxzxlp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yupwekbt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdwbimx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ytomylsy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2djzjwnxe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uukdjbvo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2htivdurb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bluiwnvk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqvdspz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqbmtvk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyqjhza.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfscjfg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvecsia.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wumxzntv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qezbrikg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2icdlaift.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2skybroau.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnjgazj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiofckx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2htfafagu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgivssqy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbespde.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwpozki.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ombtvapl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mweyngju.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlyblke.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwbysyf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfqlekt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2urpnzcru.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwssddh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtllnwly.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjvkdlf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2epwppkrm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmfbltp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvkffkm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxlvpfs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvdpohc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jprzhbec.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2prnqwidh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zitfvhrx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2plmfcedm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lyocwzgz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksydkdbc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2amqigroo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zesjxpqo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lozfncpy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nolelkiv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzptvzet.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrkydzi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeconniz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlalgya.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgrrywn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwddslu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwwjwap.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrnqcsm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcdptwr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2byjmdcvn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvkvrbg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2frbmdlvr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkqohrw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2btorfggs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzqcrfx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2aebvzdvr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsvdcor.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdpcuec.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhnsild.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2odovceov.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cghftrct.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ydftmzua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xewsequm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iajmmtdp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zokxhfrl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wevwutjw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxsklwv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bobjlkku.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnvmdvj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eycpwdjm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2upelhqxm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmqaaii.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljudkbfs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsuqzwk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lobvcbwa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qliioghl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qftbvjhu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcsdwrw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isydttxp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2erlcxrhr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2thjqljyu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eidhdymh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubspgedw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bygsomex.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prztotfz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrspekde.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvtjdgt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwnfikv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjwktil.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahufspnj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqmgfoh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsatajn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjkmrcl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhboxei.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ycecdtut.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yshyxlrw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwfswbp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dscgdmvd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bqovtlgk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sogrvajt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zdukviqv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcmcvcj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pkegznxd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enlsopcq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2szsaxrbd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuqemtk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sdagangp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeyyycs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbfvurn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2znpatauz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2blupypxv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2paeeaybf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjldmcu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkyhmni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wckhadqo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2chheqpqc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdxikmo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltprfewh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rewxxfmg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2morwoeom.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xldiwcio.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qczhwccg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pftwquok.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cuykdvmy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zjythhyu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqgriod.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pflfimxf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrulani.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2psdppcet.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2azuvqhbd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoxcznj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vedkbbkg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqspexd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqleaut.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdmkchc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbfhdkf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqiozfu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoyqsfy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjehrjzf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2blzidcru.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrzvhyf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkmlika.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfpllmp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdacclo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckamfugh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzbhleo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdujmroj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2irldjibx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nawgarrn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlhzeck.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2awweykka.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uuszqrqe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hamhhdkf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efjwapqf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsesogz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qunpheqf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcclmxgf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjewvvj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eueiofsh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lybqwxdr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdbiedp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hawhcemk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2izxzcafv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbzaoxd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2raagsfwm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpyarrg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ongqcqma.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvpssxd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtfhbst.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhmcisw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqybtoj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lifezett.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsppiuz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2chgqlcah.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tapgbfic.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbjyeib.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqecqipi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqqtepu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvpwjeh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pedqlubv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnfyaih.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzsfesl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwmmaid.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzspaic.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvgvjwp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avcpmvaj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2purajrug.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpcigew.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2edojgzzc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsknjbf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuyiyyy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2skghhuxc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpspmjmb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qobahiqv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2otourfro.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqddaadr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcnzfbi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sngonrnn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnccfrmd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2scvvhulv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfljtin.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjymewy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrtdcdm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuyxxlw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdppbqx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxrekwe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqkgxqy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2glpgnque.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfavgtd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhwxfty.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrqrqve.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmpdkwa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkfngeg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoiyhxb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpuvnkc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njtbtddz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gndpnjhp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2palcpqmf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whdhowcy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ivokvfum.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaewcex.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kygcwwmb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cnojvcxw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cohepkim.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2taafhmsb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjmcuyy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcboxpy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilomeobt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnuuucs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhycccw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqkxnos.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2urumimrz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlomfcy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoxhnmg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2osmcusua.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2umqzvndu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxonywmf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhsrshv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoysbiu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhshhxs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsflose.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzwylrc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpskcox.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuunupi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzistqfz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wgauakar.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxjmsrv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nskesyim.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2trhpaudp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzcbhta.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2luubnbwk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzecmdu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeuhsfh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyslnzh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoxrpzm.html


<!-- 参考信息 -->