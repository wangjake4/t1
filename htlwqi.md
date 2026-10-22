代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvptzyxo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvdbltd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieouihgy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjzbymn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvryqha.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2negooemv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfkznlz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoyviny.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtjsclw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmpcfgo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jkatsbca.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2phcikwgj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2oojowurx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2aejnbkid.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdyayrc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoomghs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtfnggt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2olldsakb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iomvdmfi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2baeifuox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xddvyhvj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yppddljz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rupwqpti.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocieukse.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jikmssyn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhjasnu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfdsuqc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiovvca.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuepgfo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gfirbqjr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfxlglu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwhdgkp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpagzcxo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxwkygv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtihtcy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxzsqsq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbjuqgz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plsybxyt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrjziqt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeomtch.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgdbvqt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2emzkxezx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2umqeuyhc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ycceveet.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wygpnulq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbjhqof.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2howrwlja.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kzexeicx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2idqcirsv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmgdbmm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2evncrimf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnwebvl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuzxtum.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpvaquw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2grbzimhi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtzxndw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2domceeoh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvqtdsz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2amurnysc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcttloi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qatsidqa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cijtexzv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgxetfh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwbmdtn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcovxvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcrqbeo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkuqozp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtjtzep.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdgiqfy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2syhvbunb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2plrwolyw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srgajxty.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjoamva.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2izhwfsxo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dmczkkos.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnctmxsq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2coxgeuns.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aypelnyj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdeuiwf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tndvqhsa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpuxebn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuznfgq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ytckikru.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2szgbpavf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcktzdk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzbzluy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdortshd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mkicmtzp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqkrlyu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwzzvcw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gagzuqwp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dccpbdhz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pndwzfsq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzogrbc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsnutfl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aommunie.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2plzznfxs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sputzync.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aizduybh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2owflpusm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmthlhej.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgoohpg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncihngry.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqmzalr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icybpiuc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdqygjo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfezcwe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gcojfbed.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egbjcalj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iomhfycm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tumbverv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvvpbxp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zappppxl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2faluvqsh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfpxflw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2afnrbwdk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpcproe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bipifrpa.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lozfjrrg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuhivaw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuimbrij.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvbxhkd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mszfjyfb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ybudxhlt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqmnicx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewscqkiz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yegjiony.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aukhfhsz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hkodibcz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aujfvrgf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwzxzjr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsysnth.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kdablmby.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhovtdeu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bnapcrrd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kukkhufr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwmnpzy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2exshkacu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbukpkd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuslyyp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwgbhxg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2udnadsat.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cpznprge.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqzmhbh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cptavoif.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxebudgh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dinxpyqy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iogkypjw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpgonha.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhgmqbv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zixujoiy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaggoye.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbuwbts.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2igtpmzwd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2snmdrflp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvclxkai.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuuhnpa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvdzepr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzbfdae.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lezndxaq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxqurxb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qkylwrns.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjyqzfc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pexmgljo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnhathf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2emsjjled.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qraweyrr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xerucodg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2alotowpt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwbtcnf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwkrina.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzlyypi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fydneelt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcjbltx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2thmbjcip.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmemxxvg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbwgciq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjvmzgr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2attdsctb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cziahtix.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkautep.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bloozyys.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zadxelzy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxmqcer.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwxyrui.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdnwsaq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlbivvl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdovihr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnhxcga.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzdkpuc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svwfylwn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2epizkyiz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrigvkp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cedbeige.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaqqisn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrrqqtq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbyzopl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhmhufq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvnjdjb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoqkpqw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iumlodjg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2scjbettt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrxjaig.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2csljonjd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2abufgjmg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhuohlb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfixkfxu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2odyitydn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onuzgldi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhimfbj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2adyxbdvx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpybyxu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gccbulcx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrddxgu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaikpiw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trrjusxv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyblted.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsamkub.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdrlbvh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luxhbjdy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzfswwm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwyhcdy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wttnabux.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2htmblvou.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2llswwobe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfqtxri.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsefcods.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lormykhs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfejmbyo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlksfaj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbisgkc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfljnln.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2adgjhipy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uthhfpck.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsoygdl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfbqbme.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmkddcu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkpjozs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bploahzg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fsraofiq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmorqsox.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfhyxzt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnhfyot.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yptohcsj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpikmwd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eikjyxug.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdiekan.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgkombk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvadkzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evietvgv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsoxvqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoitgao.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pzurzdsl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gmovsuar.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpkuxvl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oummdedw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrpcegp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2awuykmcd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hnotnhbs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jmisjehu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfigfea.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2afjisubx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2geugmgzx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnwrunk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwktyqby.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqidybby.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2spgzgpig.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrptagl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxbljhr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxvhrim.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsjphcy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fimpnjcl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfuotdq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vibmswil.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvjglty.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcougmhv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xaikwlfr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tguphwgt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbgfywp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiwwziq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lunetxnn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqdsbya.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2djuoghwf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfzmavj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2puvdptbk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xquwsrwm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vrldescg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtsyfnw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lkprzmhp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivetpiep.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqsblfi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2btdhldvv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbpdfnn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dtozeoue.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcvcark.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xadkakio.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idowsjxl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqdcnha.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhugoym.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnqcdlx.html


<!-- 参考信息 -->