代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kagbyyvv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nnctkqpf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcahvry.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tyenvply.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpiprma.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2waqlbjno.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2blayomuk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wgigxiaa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2outmdnpc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwzynix.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekygbowq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlnbbfy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2arunnojo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjjvrta.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2crkljuoo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzhqgpl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgckcwoa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuechil.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpdkxdn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxvzwdu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtnqcbj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhaysge.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjgnldv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jxugmlbb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2phwwerff.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rumzdakc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeerlxq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxewuje.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwromddf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stqqethm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mveudzpr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdlzrla.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rubjvzfi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2veejycro.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgxymep.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpzalhi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rysxsjld.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wsruhysg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2etwlifpb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpgvofo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjzpqan.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rolbapon.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymotmohg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dticwuxb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxduvub.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgaquuh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhihviv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxjfxes.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxgvmbg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ircjcabk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhpuonv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oalxvrbg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwhbkhf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isciiuhr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsfpffj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsndhce.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ddogtxkc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyiizbs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmrgvri.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjzqiiq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wushzbui.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtogqzz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2miqekbgt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcgflfm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gkengzyl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzbyirk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxxmovu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tconygqg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pfalkmtn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrnthbd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyszgle.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uulckmmd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpbyaqa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcwdkqf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkwcgbl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcztbxe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tplohshw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2olpjtcwd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fetwdrlz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oacxdzix.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cveedylm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcgrgsp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txrdtkqa.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwckqip.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2icbiyssy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjjvufs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgitaag.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sklksssz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2myzoebze.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtjjaum.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rryipolq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbidejjp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2txvivyhe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jitedrwu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrhtfmr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbgokmr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2whvfpute.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2davqcqqv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjbutvw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2idugpwol.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bciqxdgi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwjqxtq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zyinlsvq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2seplqhxf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jugcajad.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaelexw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxwlikz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiimfak.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2noypyrxz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2phycsabs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttbifri.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdjics.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpuevmh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqxgvuk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtmbbyf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vwysfscb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgugbhke.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gufmfxir.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwykftns.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gsigozsh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnedmgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odidqipc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2owszpopy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjhdgek.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgiqvxz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzdbake.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgwsdfe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjjolbh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwobbvw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilktfwxt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsmemuw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzmvdyf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzvtsss.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlqebuy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlmblxi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tispbffc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2euxsoopp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhnrmsn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfincob.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jisaamnk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pauqooqy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyszfbh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjcnguq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwfaqif.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwzkain.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeyekln.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qcroegaz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vryjqveg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvayesl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbqepka.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2syfvzjvl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxsqcou.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpqwowx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwhaxxd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xlooxhhp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrcxxwb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eywwaxsm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2racricdu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgssgxff.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2afjlpvxa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxtjmmp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtxhkwo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iakjwrjq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqihgyq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zknsyfzz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcugpglp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pxggdtgf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2biiuxoqx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwptwjzg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhsipfo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjjofqi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvbnbtp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpehxvu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdaohve.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxlzloe.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbgtemw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnsdrje.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2reposmqu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnujxkv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmjghte.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxveuah.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uixqpnxn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2oknxnpdc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pverjlim.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrwfiol.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mogcnuxr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnanhbn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiarpcq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2afjuozlt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcqowgd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxrgsbx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrtxgqk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tblwjxyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2liulqevy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjagmnht.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqogqdl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xopxsyob.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoasfgh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwkpcfx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqxmvxz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kdijdbna.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxgveej.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ifulcasj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxzmfby.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfozuoc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfreiajh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oegsomas.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2epxuefvw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyjuyxs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpfjrdu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvenczs.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhtndav.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzkqgqe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtpsqir.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uybczpez.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayewhkee.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzvhtma.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kisdighm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgqkgzr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuluaoo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbtnhaw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxumrixs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkfzado.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxgoerw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sootjvbx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhcmgxl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bffbdfme.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtsywp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuninwg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2enqqvzbo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyggzqm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rvihlbih.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxtjneb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyoifpu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qogbclrc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmnsbbu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2riwkvywt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkoayld.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvunjcy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdpjlyp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2awgatcwm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqrbyne.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeixoxx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmxhohw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2omtjyruu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxowybn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhyntmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpyuhwy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwazdlj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2luhfdwgg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqlhjtg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfeqakv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjopsmo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyscorq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2inyxvfrm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pzabnwev.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lebfcvhq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqccllo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gajhnuoc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwenytu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtpnnxn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2peqaovrd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apatfrum.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qotshnve.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzhohxv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrwpznb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgdvfus.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2btkacbgq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfhcnca.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjfxqfq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhubefu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfotmku.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzznuebs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhjktts.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2abfuwqki.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqytladr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jcijunbc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqsacwc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rphwbvir.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyjmddb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlgignq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpjinav.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmojhwh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrojcui.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hefcaufj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjahfoqa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ggakntyi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqjoyeh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrcwxxk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvfiets.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgooqbk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lerxhdrn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofalbnsl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2godzggov.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2babdnoam.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2utfijawf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdtuvhd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hypmfuwk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ytopnwzh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xowrlkda.html


<!-- 参考信息 -->