代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtlgcep.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjdggal.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpeusfb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eqonhdyr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uueuljkt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxvfged.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwiqync.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gzatbjjx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yyenthew.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2chkbonhd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fcibrgqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnknphg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pdexagmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tncdydpa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujudaqcu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhuvnos.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2widcrpho.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvmdftf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuudbvko.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fctvxqyj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfmhtax.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qdycdfyz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgotsjpg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiwmxgu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpjgtbb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkoqwup.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhmxtlb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2umbtalst.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwctuaii.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2elcgzeqo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwgjrru.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2waelstbn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrsdskt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbhgxou.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyccrlvj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouywrako.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gygrocdn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmghplzq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnhywka.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdciqioq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkivllw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2phalynhz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbrwlcc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwcrecd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpubavu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ncczqtmb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqmmool.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyajrrs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpopjaoq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bztxbzxs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2quvazhyw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyfvbtn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhosawiv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2psuoppqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2penrvgbi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwifnet.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jczuqwkn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyiioco.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxplvzy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzufyrr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiudkfqj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtnvprp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nauemrfv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwprqjs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnugtrf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcukvsl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2orljdzlj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfxeigb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsukuwfl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dejbsdkm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqddosl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxyzsgy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zchaiiqe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbvksrh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhxzlsa.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2unsfqpfv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2livcsmsj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzwkoqu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfrijxj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdveslch.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjkajya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgklerxk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2huhtccdj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zboostcr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qimuzvro.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwpkfcl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hjduxeri.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrkxrtq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrpuwjg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2osqgvicp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hcreznyq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2choxldlw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2chikjktz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2faawuqkd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cksnlxzz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqmponc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rudwhtyq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaxusem.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvydxed.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2htysdzze.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhcjayd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcrtocc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsraygn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2snurclqn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eldknepd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiavopor.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rebozhmm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuaqrtd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvyoykc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2paajxeme.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyksqwl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrkktkl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okhvtdue.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seofxikr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chwrybqq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zudjgexd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaplxssu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwkxthz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqqztpy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rgggnvsf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjnqdnp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbsnrvn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vfltmubb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2plutmpne.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azmsjvda.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrvcpez.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bocjwejr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhfliod.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qldavcul.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xihtvqdr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuicjgs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2evjavmeu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgytriwg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mygevjfc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdvhlga.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxavghzk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhuccwd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mfclorhh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2plrhulvi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqxfdds.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2orcuyyxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzlguof.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdqqrqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crboyimd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdtpwrl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cchmuxon.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrnwcav.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kwobzluh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cokggoum.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuizbdvv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaypgnz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwykzws.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fazvbhvt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfsouur.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbmgmck.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpasmxz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dioyvcla.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqqnlrd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxyymua.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciroezej.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfkzqls.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoeocou.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvsjptu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmstgtde.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpbeopi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnmiwny.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnopkzy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2angmdmul.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qpziofkd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cijmaxim.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqrccib.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kehzgdkz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzetzmb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtpcrlz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2duruykps.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvukgyk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxtamrn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnyepnm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwwwnue.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2teqmqkkz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvmtbte.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbyqhqd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2raiwjobc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzfyebt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2encitgcc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2djpqlcgd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcyonss.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbrktbe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skiznixg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwavgpy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnoqnzx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjukvqzk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fecahyvq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lugiqveh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqcypwl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjacbojk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uwblgfke.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqatobg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2obrbuzgy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2eadcypwk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2loowoxvh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2upbiirxp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sbretncn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxalbci.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rajozeli.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uubezrct.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzrjfsf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwznnum.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqabbvdu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpkviwm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjquzvz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qipscuzo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxqstla.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bglhzosq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hojfviwy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmecbbu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjzqfda.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fozjustx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2srblcfle.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2abfdmtqr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2largnieg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxpsiat.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xumvmuth.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbrwxev.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hqycugdf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2niwkvsfj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cuphiyxs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmzzsgx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqolcklw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsndcuuf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ildyplis.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgudzedh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2azwpkrsl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glsfuegj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaaukgg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akqjqtjp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbvbeho.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbtzqag.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bggpwrhb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2arjwqthj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mftezwsz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eabpdeyk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxggjib.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbnnvfe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutrajtz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eaquhcvt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sudneuyk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgidgdm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2baptuark.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhlryvr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgphebg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jijuukro.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxkxfei.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtgnrvg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdghwolv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ledwssnr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2loqjxzuo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgtrbpu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdapwbwm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bbypfllr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2brdrtyvn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2phqzxudx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2totqrkxk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zpauhond.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nihxunhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzfadcw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzxoovt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgovrta.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qnksbnub.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyfsfwt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wodwealb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iinaqbyp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcdujnj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghymjokk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pauiliga.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwemmyk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjntpqh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdalhdq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpqufoa.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2udlzjvyj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmuunvm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyefanni.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eabjndyn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qejlpyfw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jvokqxwl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wogwtbnm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xotvwtir.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlmylqc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuanqhf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2auguwlot.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkjunwn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yslkguof.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqopqnlw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfafeug.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjmxxnd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvlnkac.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxrduji.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmshhik.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqlskth.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcfldbd.html


<!-- 参考信息 -->