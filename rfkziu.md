代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgxbkil.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmwptdm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whmofswq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umsnclke.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfykzztu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhvidev.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzsgebp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwrwili.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lahmelcy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2haonwkuc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhgnmzk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2urlnsupt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxylmmu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlgybes.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yxezieua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuymwaeu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuhlqth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqneaggb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ialbider.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqscwwd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sujlajce.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sfouqmkp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozivtiay.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2veqovhwt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvavsvln.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2beelbxlj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrliaod.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdmoqgv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chupchrs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhfpgvk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sradddhe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2grnqjwpq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xeifuusg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gapshkgk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2unfafsuw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgfhgvj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2smwqxvtm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfmmvoi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkssgxo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dotbrbxx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmksvzb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgzhyjg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddysqqhb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvxnvuu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjgcnkw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ukttlrcx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhtyuva.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wugheaod.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2umuzhevk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpedfao.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjobhebb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2carertke.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwszllc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swdwojju.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2enozmuyu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgweajwn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvxysso.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kihbpiaf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eclftgjt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhnrkit.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxaxrmo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2khrwympi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqfjbjg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xekufjli.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxamndik.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcpbora.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zunhcpqb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgtvybk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyornpv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ttihqomm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccydmsiu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsrpoyu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyserlm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpssyvtg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oypfkkbl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zoajgfcr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkpcrpy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efqknbth.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjfabfd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2btopdblr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hlclfygp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jtewmcai.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjqcrkr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmpnaax.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoxexix.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssttfybs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cutuqqif.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjlrhsd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ourrcewo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pafuhtxk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2konvgwhh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voqembbx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhjatqn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrwlnoe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbyscya.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvoxkdk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwaiaxf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2suhotqks.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2isqiemeo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuojbvb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzbmtfz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gaddxkgb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjwyoxe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdpjvaf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtmuppa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqwuhpg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyvyojy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gytsdqyk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjixlrj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhxiihu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfwckxz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2allmlohn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvluwns.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrotjgvg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eknyjybw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pttyjool.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyzskdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzurdvd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyukcxb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwsbrfr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oombwkhe.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgxhmnu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tovnobmh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrzyqkh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxtmzwr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tukbxack.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeeguib.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2debrrbmz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fimuqbze.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrxexzm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwodsib.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2npvozxnj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2coyujnes.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzijcza.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfhdglt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bngyqutr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doozqjfv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaaxiww.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2asbxeyrb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdsvuwm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2onmxqbzc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjqiwvd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2piqzzxoj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2acufvsow.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvgsztl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2euztlhlz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rygemeqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skwxecvs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ariyaqta.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxispnwf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsretpb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkivzvt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjqbrbd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2muworpvq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuskgbm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiaxxwc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzwgisk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ulanghtr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyhguyc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ishekiby.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuexinh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsgkmut.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlyypnt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxsfjuc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvprkewh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eibwlnzm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkyqeal.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuccmtv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gphqozum.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyubunlk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2stdvzovm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvpwasx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmgdqge.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vicoxqta.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvowqga.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdndqvh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmmuooh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2keafltzf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvhtuac.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbyvgqv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdystcxh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2okbvjzvh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfhqxap.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ascxfkoz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xgesebmh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2seywfpwo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlhqjrc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvptyea.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2likzbflm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsmpnjw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgmlkor.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkaogtw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cygmlmta.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qakujvza.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkngygu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiukuhpn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2joiompkr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmtzilj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lniiqsrz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yitqogfl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdgtlss.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrfuoac.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzffiuj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhbubds.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2peugnqpp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaxczgh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrhnzbm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtcsudj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxatkyc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdqpazh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evxapgyn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2czhhnqyy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2alwppsig.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrgaiob.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmtzqwe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zpystmfz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijywiosr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoxmgtv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2witunlsg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eogpvgzg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkdxhmb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2soghgxel.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyebcdgm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkicdmtp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iilqrlya.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvwbnlb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldthapam.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxjthuw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzklrfkf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ophjqinx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npsjkgjs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abepamgs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqxfhwo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfupixo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbcwnht.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpisiixx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxbvhsj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnhrjed.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iloyqgjl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzktignk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tudrepll.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjymzaju.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iykzrbfh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2irxqojjp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoqkrdx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snkhshwy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duvkkzkn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmbcwaz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frbyfyad.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dumervbc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2clchlnkn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbyqmsq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtizhec.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vminhdzc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuablxd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrwmafv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrjnpfj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhobenv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frfmpcho.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2asmhpgct.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pogfzmwu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfsvdns.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvuyltb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdbxgia.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2znievqno.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeyuqpn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzerdlvm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdeupkd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pglcblov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izjbolzl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ercuvnyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxgrtmg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zfypfuye.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bymbbwde.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2guelekfs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2moqydpac.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyvmojd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wofuecsi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bagrfdxc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qyohszjc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfybwee.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbvzxxx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rohqmtpr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfuwuwo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2stvhpzde.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnsaddq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjygqmq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyulzwc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xugnsnui.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsstfpcu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdixfql.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzxhuei.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnuqziu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpsflkz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsakdpk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaaiwkd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpcdvrp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fumlelin.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tonhrmxy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2twrruqjb.html


<!-- 参考信息 -->