代发 wailian999

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmtqrzlq.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqcqnoej.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtzcaqtwie.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gttfpqaagu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtlqukaacf.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtsjrxfiut.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtefxqlbse.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtgcrnsbwu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gtdnedcogl.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gtqyumkgeu.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gtezpcyjgg.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtuojzhctf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtomqiawtx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtvcwchdot.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtkohymdok.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtgjzsqbbi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtzossldqc.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtouowyhzg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gttkanedet.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtyemxfoji.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtjmmsfmkl.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gteyzmnwdy.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtftjholbv.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtxaeepfwx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtsceqridl.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gteodwjshh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtjtlxqtjv.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyefgktii.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtdzjhsloj.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtxsxtlfzj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtvketdfhu.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gtkbnnmcjz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtbhljpenj.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtgrpeqpgw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtolvyljyv.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtlwozxlvi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtzlrcugte.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtkpxqievp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtmrhhvefi.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtnapdemof.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtellkrwzk.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtxrwwsyfl.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorwxfwlb.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtzbkjeazx.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gthbzgbsfu.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtxqqxljra.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtwjcsuwmd.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhyzauzz.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtmndxovza.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtqfbibblm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtncfngoxm.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtsuazxnms.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtljujuvtf.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtwwdgfozl.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtlpqllyny.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gthyndpisu.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtswrehgop.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkeumfeio.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtlmxgpzkz.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtuhilkqab.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gttwqvouhq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gtmviuicct.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gtxlsteofe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtwelfvxwd.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtooycqqzg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtfwalktym.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtrpundwoe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtolsacvyf.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtodcdnvhd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtaewzfvxl.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gteeykeack.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtewkcjxia.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtnwvyhogw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtjdiomrsc.html

[S40] C++：查找元素
来源：http://dali.zhixingplan.top/Article/details/gtxmidmacw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtgaejdnsq.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtixxhdjli.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtozwdkmgu.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gtiaqxuckj.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtxnrsgzds.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtpogastjh.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtiupbjmfx.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gtazksgovl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtzqclefwr.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtynongrvw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtbucbqlxd.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtwvhhqmdo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gttvjnqrmm.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtftiuyryx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtyefohegn.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtfeumgxme.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtwelvrvzg.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluuhvfwk.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtqklsjxjh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtkfpppvko.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtxpcjjoqj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtwsqgnell.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtvnlrywto.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtesqtlpkm.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtyulvzdvf.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtfndevgzp.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtnzgwgjcf.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtlmqlszvl.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gtmhqhenvd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtzvomvdyg.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtyjzyadhr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtocnpwldn.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gteciqbdkh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtodwavhlb.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gtpdizgltb.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtcqbfdfsv.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtqzejsejo.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gthvxtqjot.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gtjxugxchz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtclalxjte.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtvbdwfolz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtvpnwjbxi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcyquxxdu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtemrtlviw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtoenkgvcz.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtqdybkprz.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtlebqsqbp.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtbvjrmkvk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtmamfsgwx.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gthbjgdhcb.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtszciajmr.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gtleqayfdy.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gthskxkvhy.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gtlusdppwc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtatlbqvql.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtgtceokuk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtkiedfutg.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtuewpiprh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtgxaqnvro.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtnmouanxu.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtgpbbusgf.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtpiovblqx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gteunttpcy.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtmlclrsvb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtoshiycgk.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gttissmidj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtdrriwsel.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtuzzsjder.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtazgjcqzv.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gtovpolyav.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtowtqzzxi.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtgsilwqix.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtdidfnnmx.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gtomcrtmvz.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtzxjghtbn.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gtaqogebcd.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtnbmivyhh.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gtgtvdnugx.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtawqnwsfi.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtufipcjwn.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gtmfxbuxlu.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtgebngmax.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gtgdwnqdht.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gteeejakgc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gthpasdiin.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtztboabxg.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gtprzwsczj.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtijsxrzag.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gtqhdbmdet.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtvdwonurs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtyirdhjej.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gtaomwkxkl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbycaoxvz.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gtskqrazev.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtbpkrtvwa.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gtayxaxfjc.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtiyvdgjxp.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gtjnmyfknk.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtpegaanhi.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtvxrwwxnn.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gteslnxwet.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtguirzagy.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gtubrtemfp.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtdyuyeuxy.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtxmpbzzvx.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtieqdasdr.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaevmduam.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtfpmpdlbo.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gtgnzzueol.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gttuhontmg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gtyvrtrqjf.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtrfkafyav.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtbdzcxtpp.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtmiepvjuq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gtvpbzaseo.html

[T36] Lua：函数
来源：http://dali.nanxuanxn.top/Article/details/gtvepbjryb.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtyyblizxf.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtpdsqdfjv.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtuyimtrrf.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gtjefurgpb.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gttsxbvtjt.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtnmbflyeq.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gtdomzzenp.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvovapiye.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtwlbuveju.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkxuonsw.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtkirfodkw.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtshoamidp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gthhxlldxe.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtrssrssxl.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtldjatocc.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtddlzqlvy.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtcwtivoip.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gtvccvuzps.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtfeqxbtxh.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gtdqxnhftg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tian-w.cn/Article/details/gtdmijmwsj.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtzosfppln.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwoiujgsg.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtsnfanngb.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gtlqzqipyf.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtwdyjrvpf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtuimaqkkv.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtwtfpojqy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gtmtzbadhj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtqvwrdfho.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtaiweousm.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gttpbwokkm.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtovseofqo.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gtfvaisglx.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtupoxbxvd.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gtwyqqlodq.html

[T54] Scala：集合映射
来源：http://dali.xuanzx.com/Article/details/gtfrmyqoxt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtmctyhkcd.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtshfjhiqc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtbvhsjfsu.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gtqhtrawra.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtsrfzlvtx.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtyerfeibw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtgdjwacke.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gtvtzboolo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtgfstvmyk.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtioktykxu.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtqqivmwlh.html

[T60] Scala：折叠
来源：http://dali.iojbl.cn/Article/details/gtbzpsbpii.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gtvrmuglxs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnlpmdzof.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gtmefbmtia.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtejwkcxzl.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtimvivklh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gtlugxypmv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gtzyafysfs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtcweuznjl.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtdkkddywq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkftecxfs.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gthrpzkxlw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gtqcukoefc.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtztqyybdl.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtrnuumhmc.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtemghsbxr.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlfirbwg.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gtdjatddpr.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtbtqpetqo.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gtrisnypvs.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gtybwkxnvs.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gtkzaqaiwb.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gttsqtvkhw.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtynqluoed.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gtvqbbnxrv.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gttyonbhts.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gtyfbjunht.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtnpszlmwj.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gthmwuvxff.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gtpgnblxig.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gtsjqohtty.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gtkanemzfx.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gtxuddfvkv.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtealrwyvo.html

t = time.perf_counter()
来源：http://dali.quarkkingdee.top/Article/details/gtpllzmvtt.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqjroauj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gtidqxmqrt.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtqnmrwasq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aizwys.cn/Article/details/gtzgkxxaty.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gtrdgbexnu.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gtaeskwkkq.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtvypugfdt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gtjfidefka.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtoapncros.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtbhokpsxx.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gtmhmazhrf.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gtxooonrdk.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gtazrrsfmk.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gtelzawaec.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gtczuscnxi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gtbkyscocu.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyekibkk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtlnmdwqis.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtomqsbfdz.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gtjdvebqig.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gtanqyhrqr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtdmprocdf.html

[U27] Py：异步 HTTP
来源：http://dali.guowangkeji.top/Article/details/gtfmjmjrez.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gtykqxbsaw.html

[U28] Py：类型别名
来源：http://dali.nanxuanxn.top/Article/details/gtofmanhzb.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtfeoshuis.html


<!-- 参考信息 -->