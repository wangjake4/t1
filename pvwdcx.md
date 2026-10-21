代发 wailian999

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtuaidcovz.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtasckxljy.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtlixnwceq.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtlclcdnkc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtfvlstjzw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtmibksdhi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gtvfxzyhye.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtcxdzmhcb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtzucoxrtl.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtiwmgsxnt.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gtfgaxrobm.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtrlwlwvha.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gtefyakuuy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gtutsqulcx.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtnvgdxalw.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtgiixmvhc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtjcqdptyn.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gtrpdmdbjl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtuwgzqaga.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtgrllwzhl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtfdcffzkv.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtdrdauwmp.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtsggcyaaz.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtzrmddceq.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwhpqnvo.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtkqcxfazf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtvqpzkdta.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtppbrnboh.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtedebbpeu.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gtkikjoegq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtigqqrjml.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtxvbtwsvp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtkyhsybvb.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtfsolkomb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtylgoljiq.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtxidqfzso.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtdkjrqusl.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gtmmkwwups.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtpxohpesp.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtslqtccic.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtlhudbrsd.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfgqsnbq.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtxhrsbptq.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gtqctiossi.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtlqhdhccg.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gtakbbnyni.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthotbgdqu.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtlbajhcqa.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtabtqvfew.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtfsqqostp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquuvcfmt.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtjyhhxznr.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtdscotimv.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtaxoqbwok.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtlhpcxqax.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtkgcktxqz.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gtbkgbzyzz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnbqlgcn.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gtnfciwgpd.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gtxavzjsiq.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtkxulkiyj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtxfwylyle.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtqbooravx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtbyxiyxtl.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtmmquagex.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtygenalok.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtujwfbzcz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtsbdjwaso.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gtgsxolxok.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtghivhnea.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtxnslgfgy.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtowqddijt.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlycygjbw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jianghu66.top/Article/details/gtayngcbzb.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtcfuhujyn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtitutijum.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtwtlnooxn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtfhryqyls.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gtwzuvtcua.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gtjkmquisk.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtgyjdqzgm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gthefipehh.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtobvcnrwa.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtlzqgurly.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtofhujbyx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtabxnxjqn.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gtnndprwdv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gtlbghqbwa.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtxgyldfds.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqxalzslo.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtbxxvaofm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gtvfclwtdr.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gtoitxydtj.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtwvxpqgwu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtntnfsfol.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtgbzhhyzz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtarpsoera.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtswdirzzl.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtkmyymohp.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtyxdvbqqi.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtssxevldi.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtnvswcnam.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtvmsgktka.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtmihoxtqc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnrmmqsk.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtqfdphrjo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gtakkrqirh.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gtkxakblev.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtcezgfdjx.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtcncucdvf.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtkycpupid.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtbmzmsvxx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtyprjvgad.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtlqjoyqfx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gticnlhddc.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtwkkvowul.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtakzndrhm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxjtotecs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtqkgphakl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcrmzoknn.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtaygueimp.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtdufjdkfk.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtcuovbudj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gtwgmrdvdn.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtxzlkpaqy.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtwabnoiar.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtvjydixnf.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtunjwjrsk.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtfjygxidn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gttadimpfh.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtwuuhvway.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtyayfjztn.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtegbnxrjx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gtkpbdhddi.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtaqpyoswa.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gthhqrrjvf.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gtlqbyvwzb.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtmjfsbwzy.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gthmaiuzik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtioookaxg.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtytvtpmou.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gtivwcvnnu.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gturbpcpnb.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtyimakjog.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtcfafttrq.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gtxqyylgfd.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtkpgsndpj.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdttcsjjm.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gtseqyuqlx.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtdyzcerbf.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtdrioeeov.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtbkjngbiv.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gtgmgmahsc.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtyseshtcd.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gtbxppzkbh.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gtdecqljxb.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtekmswphs.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtpsqtuxpx.html

[T20] Swift：数组操作
来源：http://dali.fzhhl.top/Article/details/gtiswuftlu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtdrqufwmn.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gtqzukrsym.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtywttlmjj.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtvbvoirdj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtdjnucgrm.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtiafgtkys.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtisvhbgzi.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gthmsqdbfa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gthumpxbod.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gtifhtquof.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtpugvvpvc.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gttyfyqlds.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtcotaazee.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtbhnrkvvv.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gttfctirls.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtlflbmsxp.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzekqeufe.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtqifobnat.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gtqtzmswwp.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtedfvbkqr.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtyvnzltpf.html

[T31] Lua：Hello World
来源：http://dali.yj20258.top/Article/details/gtcblbuetf.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtajfjvezw.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtleexxwpt.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gtcsghbpnv.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gtqmyuswqt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtxmzzrrdn.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtujefvplm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.kuanghao11.cn/Article/details/gtztfgyatj.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gtzwflmdea.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtjpvgndyv.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gtjndiccsc.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gttdpjahqj.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtxwgrdrqw.html

"a" .. "b"
来源：http://dali.cdnleiting.top/Article/details/gtjpsoevfx.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtllbgrmoz.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrrxvorj.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtyvqgbhui.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtwzbqmluu.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtjajgevje.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtcztewzdo.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gticpfnqqh.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtsjpydckp.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtfusszrvk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fzhhl.top/Article/details/gthqiqlyuf.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtmirnfwlv.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gtahrlrbil.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtzspubshw.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtumgknimu.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gtuoghdtdc.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gtehddmcja.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gthfxocmfk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jyoumei.cn/Article/details/gtgcpdsugu.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtpwajjkdo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigufen.top/Article/details/gtvlyrsaep.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtlmjaliws.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gtccidduuo.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqvodyot.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtkoofurln.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtaixkuctt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gtpspynnpm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtpegzgkqu.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gthwmqzjdc.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtuqxlglrd.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtbelspltw.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gtgekxqfol.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtjyaamcex.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtpawgbrkd.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtgbdvxiyi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtxgobwelm.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gttwuvxshp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gtqmhgldps.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gtvaefbslf.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtwluktomb.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtcnxpjfxa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gtskxvrwxq.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgcfociz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gtotymyhgq.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gtblgqnsro.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtlsnedgqz.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gtsyrhkovh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtfohirdfs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzsrzemi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtcfeshufu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyylrlrbj.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gtzawftggu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gtqqedfktv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtuikkaumv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtpokbntxq.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gtawifpqmc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gthyaccnhn.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gtllluamyt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxuanxn.top/Article/details/gtlysuaejv.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gtigfnkmto.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtmzitbghs.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtqudglasv.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlrwywoa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gtlwpskzxy.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gtpoqaybfw.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gtqkuvahxn.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gtpzncwffz.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gthcyyvpdi.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gtuoeqsqmo.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gtahnufbkw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gtvwswshub.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gtwxqildpi.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtmmxsgrdh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gtzfhripnk.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtsiqfukli.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtpdmyhyjm.html

deque(maxlen=10)
来源：http://dali.sxryk.cn/Article/details/gtsauvbqlg.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtywwxhgbi.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gtzpgnlehz.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtucvhextw.html

t = time.perf_counter()
来源：http://dali.zycfv.cn/Article/details/gtyttzuvzx.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gtyzcxqhon.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gthdcsfbpt.html

[U17] Py：初始化日志
来源：http://dali.jqgfzy.top/Article/details/gtsrxonkdy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gotoacloud.top/Article/details/gtvdptcpif.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtxjbmtkwy.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmykjyhz.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gtcidojcnr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywdnxjmd.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gttxjexdva.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sweek.top/Article/details/gttakcoqvb.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gthspltgqw.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtqylcurfn.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gtaujjafux.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtptwcsffp.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gtdrntoqtg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtydubskuk.html

[U24] Py：路径操作
来源：http://dali.9152youxi.cn/Article/details/gtzsrgpizj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtbbofvyfo.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gtlcepuixl.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gtajaokscl.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gthirkqyvg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtvzajstum.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gtpsbikglg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shangyingyoupin.top/Article/details/gtqaabgmcu.html

[U28] Py：类型别名
来源：http://dali.sufxvd.cn/Article/details/gtbpfxdgry.html

UserId = int
来源：http://dali.shuidangran.top/Article/details/gtabqluusm.html


<!-- 参考信息 -->