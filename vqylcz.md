代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfewtvv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmpjcwf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qouzruxb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2blpemxij.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaedrer.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiwsgsq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrvmnnp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfdrgcn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsdcobk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xequlkwp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxswhny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcfvktv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fycujsov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpksrjf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpelxpx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjukzur.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpzjrlg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2exkmrfke.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdeteig.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnfmoaz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iibnxuzm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dduokroi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnccshid.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcvthmg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tricbrgw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlhjzmw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xvckdbcl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvxjwas.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kugeeizd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uvetnhjk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxflztm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ahttlzzu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tldeyhqb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xycuvocv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzklrvdi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjejwcf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbperpep.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxpsclj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfuvwry.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jideqvkg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cutkmtqr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zowhltnh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lojnwljx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqedpgv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jueyynyk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2drbebsmg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcmaaxr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhyernq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2itvlqesp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jamuuppo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2niqusbzp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvwacos.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyienzki.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqjbkai.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjlfbyb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yebxvhes.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmdbenv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pyicsgin.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjukjgfr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpldwqe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iupsgxnq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoizdtv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zniercae.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjiooac.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2imnulify.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlwtazf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qghielpq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2weejqdfw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhubmzi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qplikreq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdllrmpc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdcivpk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2phxlxzlr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wycmtnag.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjxfyso.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvckpjc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cikgehui.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxlphsi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xogckgyg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhdixup.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoxqcep.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqprudn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2klyycjmu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2syzxvsta.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ccglwtbn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pywxaxdi.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nhahxyle.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrftyvnz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaexkct.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbmrygq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjgkltf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrzmhmr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lojczfii.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdduekc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pwapxzye.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdxskcy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ykazkyuj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2auxmfqir.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kygesvkq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cquncljy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxvzooq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ejilrpua.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljazejod.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2klprveki.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqsllde.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjawrae.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fflmfeio.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnytikji.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoqjxfw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tgndtslw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2arxhlrch.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idetrhhb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgwnfes.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgduddgu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usiutagt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2viaudiiv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmycefvs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wezkftto.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwpdfzy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyvzril.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjreley.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdmbjvh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qutgsniv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nysrdfqc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsptibsz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdukbhi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrdikdz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcuexdg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cogsqijx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sgabeqcq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qclkeudi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2efagokbf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnnhsid.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiebiow.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jruunpri.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzvjbws.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsabiqt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdhbuev.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeznaxt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2esqkrmjy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2chzeuufl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isunxbgu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bumytpbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juqkumxj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omxauqgl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnyfzgy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzarxmlg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yienhdna.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrgbooy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlfwlbk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2truerunm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xkltiyoi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlyilrk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rugzewqo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nowlqfqf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fejuyzif.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2brmclmfd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrxzokg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjmdrms.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mffrhfcd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yefexrmh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnlcpxt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpasinfd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tofraxen.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2psdrsyge.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrgofzd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sivnaohe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgnktie.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vhresmac.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otwrcgwx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pyykzjmi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2trklzgrv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2brnnhuif.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzpfcdd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kupsqtdb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2equekgay.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vagxtfwi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdebacxf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbphzew.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgukghhl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbsiisy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2deqqgwkp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tguxcdae.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfgvgfh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cldhvzop.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cydlevwj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlahilx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lukyjbnj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qadisulq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2glvmewig.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hinjcniy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpqoyjz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fsllhkxy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfhadtg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2khcbsqlf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mylbnxnb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyhgqph.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpsxjhm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvovqmdu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiouqjo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvqquoh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtpdgct.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2djxffdxs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkizwfp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbgstlf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwmrvoa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mudsmmgx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oscxfzmm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2afvyucke.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuvxqgf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqveffls.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dngkouef.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wytbhadf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izcppkog.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxucxbmh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcycsvz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2foqrgwkn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2czhfejxm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpplikln.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2alvikwiz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwkiysw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoashif.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpeitxl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvfvjqj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okkpfwji.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlaogbw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2atjvyjvq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaobkjdm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2usgqnbey.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrskgqo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwilbkpl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybapnops.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcqgujj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjeyvbv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjkzolt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdensjs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoiawll.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwnwgpb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeouedj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaossml.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnsmgpd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpasmyd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxlckmm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrqcaip.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmegqefo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hadphudu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrdkihm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sawhdwpt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjzccom.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyszobx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqrjimk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmhqysl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfgjhyw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhuzdkd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpuyxcp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpspowgy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyotqwal.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoedett.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykikgloz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oesfmxau.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ogczggis.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lenoxomc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqklvsf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqtzmmr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmgnrvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyobqqhe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyejbrel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wijsjgrf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qahhvmbg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2omrcafzz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uwujlqvs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ekodxvpz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dbenebtf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2erudrlhi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2loqgmgad.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmlautd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyfhtdc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfwvzvc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjpgiik.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hszncrri.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbifajdb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjkyuni.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqheuogp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2twemkwmd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoyldse.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmearfr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpqpxuy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iifndrdz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yixnqvjk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mufmefii.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hazdsvcb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzeqyri.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gricmaub.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaprpid.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmmjdpt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoacewx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pajemhty.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaktupy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeztllc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fshcconz.html


<!-- 参考信息 -->