代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gyigtldy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqxvzko.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpjfarf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oehxfami.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hyugjsms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyzdecv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phumrojy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqufuxg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpdsgmg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wufarsnx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2spgbpxks.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjvyffh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlkxybq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2utqtrmul.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzjnxii.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmoqxog.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eossmcsq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wpulwlal.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwxkedk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vwspuzjy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtjoynw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zlssbija.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxnviqy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdtuvio.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcrcyss.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2evmpjveu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzibtnq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkekwrj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyqruyh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnbimax.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfclqgxu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsdedzl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kscywoup.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kykpbbhz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jowbhnaq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sblwoylj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ailalfzv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2apeefnju.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2flaszuet.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ualjsyun.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfhvduu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2obdojknw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyjrdfg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iaetjejz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcmczzc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwoewok.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmgcdnp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aqssikgm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxwuzqc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqmjwms.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2npbrjhsr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzuigyu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqkrufe.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2swjvbjbm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdcxzag.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtwpuiq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jftjlldr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhrgtle.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdzijmg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zwecftrk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oytiffnm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpvlquj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxnxynt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lecygdpr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcfttnz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kckrllmg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgrsqpf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tojfqgbo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2scajztzd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdqngvb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbpklif.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhejakm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fnomsgxi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msapawlh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxydebpq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2atxjckey.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vapswsvb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiykpxl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsfavtt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrhzyam.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmgkgin.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wozcqpzc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2easwkoqz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xljdzxci.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yxggtkiv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wynigqhf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrclzfr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvaetlt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2olgxeiqn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2coehacma.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqnxnix.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeysloqz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emgykmgz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dikeeqnv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlwboqg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuqbhpo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vbavnoia.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jswgrauw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2shscudpm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgscdwa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqyvtpz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jroigaad.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvqzdfq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfpzuwz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jruhjvzk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejmehoy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkjuddw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwbkesz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhvunpo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lftbqmki.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpznkos.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nekayztl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jattzzqj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iainqhke.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hslvglah.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ayngwwjt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gihmouye.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2szpteorb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2husfbvcd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2axzmvrnb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfvlmwc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxdmqer.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyzahjg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2igyvhwai.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ameneshs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2avfduejf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2huppfycg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vztivdzx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcijhez.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2icudatcr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndafndza.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpubyyx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2etfrbodd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcrejor.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2arcxvqxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrhcajy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsavsbr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzjxehf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzefczs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlngjpe.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbccndh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeulogc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ymezjtyb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaytbkx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2drksdxoh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zzesjzle.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxoiuyo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2efmkjqez.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfakgemp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuayrpt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uspppgwd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgytdayh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvykphtn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oioaalxg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lufwitzp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziayoele.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iefmastc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2knzmwtmi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyfavqk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eclffpyj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxrcnab.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2feveniso.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsuxbvh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjfuufy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2slvregsk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fchaeryu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2trvyognh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiyuiro.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2poltqanl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyaaooo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2omqdkaln.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2owltyirf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wkygfmak.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewljrobb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvdxbmz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2duckdtuc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2apzlvaab.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2arsfnyic.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2agylmgde.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2umluezdt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypworsuy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhnfqzz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2djbhyphu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyadnfh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rzehjgqt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzveksgd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxqvtvw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjzgdnw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcpmjwk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2quottzqw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2drccjuer.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnrtgyo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmvvnfi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2onoajwfe.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hsivlwcg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fswqyacp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jezfctuu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvmthnj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwcgsae.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eaffdyso.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnujylyx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kabyorkx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bduonmvj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzssdaj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsnpxgo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmuyvka.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jieodlow.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibelwhmy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lupqkrfg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2adleqgkk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuwtwkd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuhedab.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdborzp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbglqem.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gouajxyq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2erobsenf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2thkrcwsy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fthcyjpv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhfvoxu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2saasetud.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cflrmzrx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2idfvohit.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkjcyyy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apptvyxk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvhzryi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkslbce.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2exddpdrg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhkmkny.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lilzwjum.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlxaquj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyakzoo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wevrinru.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpotipgj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwrjtlc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxgbklq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2axzoxfcn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbgqslj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdavgfw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuryhql.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvaxuvq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vbefvaga.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bkycknta.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcflilqw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzzhphh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjxlqyt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjeqqzj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbzoxfm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2snhgnzve.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgrkkxf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtjprip.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuonesa.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2obyqykns.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsistpwx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdcysdr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2szptweuf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hoefaagh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqmzcwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmlclcw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fttbzwpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gocencem.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaavxmv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjhijyy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2otttbgoc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyvzhue.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzrxxtu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnlponw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yanuhzqa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzetzxv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2biqcpzsr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrtjzwf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwgudxs.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2riyuemho.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcncavhb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yplqqrmo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2avzcpcoc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvupawsd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dkljkvgm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2igpnxzji.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vceshxfz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbaxoui.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2odmcmeqa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzgivqi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mdirszeu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkodidt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oeykmaok.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdezcdrt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2juzcczvg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuizlzf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwgveco.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dihzbjos.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvbjabn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oumnbpqc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cflzcdkx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayohpudg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjwjcot.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zumajkzu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcukxhi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whvoepor.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qtonwbew.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2myqloffp.html


<!-- 参考信息 -->