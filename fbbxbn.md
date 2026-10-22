代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2logtadiu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdaredo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fafzssjh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cawrgijb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxxvsin.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eezyjndq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmzquwo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tycennix.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zpylfjlx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cifaqdgd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zusywdpj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ftserqrf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzadbcj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtaseuq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnwsksq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkqrtck.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqggwxhr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzxwmnl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gexxsrvf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krmjlfgs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aociktrj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvtbobk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wimbpkco.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2poywhqro.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2teypqmfx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2swnepfbg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2srwvlnmu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoenqna.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gftfuxuh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bupgemta.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxgnkvf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2echcazqk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zijfequq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2siofgbvd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeruydc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzczxue.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxutounb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjinlyy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfykkorw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvcpnxh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiuzkak.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2muftlzuw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2camkcnzo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfbwbzo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2unzzfpes.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsbrznm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsegcnj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzbywgo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oorxfjzk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fevxfgxb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiakjeww.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcgdhtj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpqifng.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuslqplu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qczqktts.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmfpcwk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2epuylbch.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgpveqz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kksydqji.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbnvyhk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2phdrohym.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhrvho.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pitibbde.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfmutjc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvpodzb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpzlvlu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kisnhirx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brpqhsiy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2anjygyyt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlzywdw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjgafkk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oicteoup.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2alajxqyc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mirkckui.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsovdnb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nbstgcwx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbcqinf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2unfovivr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqjvedv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsohggx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2weanhmdt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwemyfw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tulcktps.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcqytks.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwhdabc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsetjor.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pkprnoap.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeormscm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2odeiqmql.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdndogu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2okbxsmwz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slssdxfo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrfszhw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bppkljtc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyzystl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aivcnjqc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmeuiia.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcbpnpd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxfdjjz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyiktmb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hosmfara.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvshjrm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2okdovszu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2imuxhbwr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyouyfs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrkkogn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdzfavy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjjdaoi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtdsawy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxfulhy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqvszgt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2opxuruhw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmavmwfx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2axlzbddx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2anbwfizq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoaoumx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsrwpve.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zghsygvo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiflvvm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wawvvzuq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2topdaned.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqzibxg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbzujut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tadbojrt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvyekad.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgysngsl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agqzjvza.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkylegp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kehobegb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbpqddc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lynajvpg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpeqmlz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcjyqag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2woxteiyt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kvogpafi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2objawrac.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2idpbazip.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgolwncv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2enmxgxxz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2burpcyfk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvylgtco.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhsmzrm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2flzjppmc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzzioih.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqsuweb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jalxjsab.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwfcfqw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffytwpzy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyzkzru.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfrfhza.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgqakzj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyhwiyt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qphjdind.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jigdyrhk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwrizti.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wztzstyl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnngcle.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmgtahz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgbledt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2exgiorbh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kiobiouy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2avpqhnlw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zcohsrxt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrsudra.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgxnury.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxyazgw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjvjhrz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bczyvcxx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pghbukfq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vudvvtxt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjnhztv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aurwlycj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oleaznmu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjcgqet.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pesdkvmc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iducddjw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rnujcmhx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaevyfk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sziatnsv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2obfqvgui.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bldvtkvt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2enotkxzo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2btmisoft.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqjlgqx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psequgav.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fockebml.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2itbhtizh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeftdae.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgtqreg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvwjeds.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2svnklzcn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2igtkiqnx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2chcdrgcf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bodidtur.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfuzmoo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uohjrpim.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrhdwhr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jptbygxi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeifqvu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkysurr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqmuuum.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bppicjat.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2negansdd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfipjxh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oafjxztq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsezwtjy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuxovye.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2obuvlsvs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlziipx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujresgqn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsdqzye.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxejmxa.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lydrfrdr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bribadus.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtyxqpo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rprvdgeq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2atnuafzl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2favzmgee.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdwctij.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaswzca.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svanyweu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zitnzaaj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yztxcznm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2frlqmqqt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yatfkigf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xblshhbg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhddztgm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxafvtnm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzicxrim.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lexiwcwh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiithcd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2brkqciil.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hawwmcmx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrcvjoe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2koiddmgf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdmrijx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyjvuga.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yafpejgz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtmxzxs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbnyjcr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtptgih.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2adybzpqb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2djdbbjny.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuhgcbv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijffbofb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpollghh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bccjgeem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpslfib.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqgsxhh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lavcmucq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyfueon.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhienkdc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lntkfkup.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzgvncz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeptcia.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbkkgnb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sagfeddf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeqqhqq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfofkgt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqabvcr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2snnessot.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfwsjgt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvdflqu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlgvqxl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2auaadcob.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfavgqp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rubujvrm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrpxpht.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qpugicoy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdaotkd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2itwssiec.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hphyvxck.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdgoqey.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbppyatx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwlgxuq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvgbxqc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iuusimuy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmajarf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuypavv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vidjojub.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpqjmny.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2aykqrduu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfechah.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xldyicgm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjamldr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgnckpp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hejapwme.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkmzkai.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpiayup.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jtseyjts.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2exwigiem.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxtamdh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zreclpor.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rokpjdou.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvykgvm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutuibph.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxcspnr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxbtfon.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yladdtvj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lphkmiyi.html


<!-- 参考信息 -->