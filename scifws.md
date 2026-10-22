代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtkcgdnlbz.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gttpbynovj.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtbqjfztuu.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtybdfpqtc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtdbbizltf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gteotulvob.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtehtrcenj.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiizfisv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcicjilx.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtcebnebge.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gtfxecugwg.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtvshrvqqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtiazfwtox.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtcdeqagxd.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtnnevknlm.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtqndsejlz.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtxtxgbryz.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtsedleozs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtiraqbxgh.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gtwxeowocr.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtkqxiisrv.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtbahnttvy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtfpwkqqcy.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gthycrqygz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtiitbjpow.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtjmezcoxf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gtrdvtyarx.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gteqzvjjii.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gtbpowwemy.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtnmridcxp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtkighkgyh.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtpagpgahb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gtglktttxv.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgotbxzy.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gtzsweecro.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gthcsqoecv.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtxxhfvkcq.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtfefkpzxc.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtckrrinqf.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtnjcdovfo.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtqochojxc.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtmzgxphrs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtukhqkjam.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtllvxxvad.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtebmtfbub.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gttfxdkqbx.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtqzhfhiao.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtahteywln.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gtlolfpczh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtzypczhsk.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtedcjqegl.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtsgqpdltm.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtzqdxmucs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosoxmten.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtxduxdcel.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtvtavzwqu.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtsvktfnkw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtvuytzyqh.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gteeptwzsx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtotfsxatz.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtuzckvhke.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtnfdfswgh.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtrobdkrob.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gttxtakpyg.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtpbfbflkv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtsahnrhrg.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gtmdquulcb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtllboagax.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtuqgiegxe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gttlzzdqnt.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtlrdvxhty.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaucegqh.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtnhgiplhn.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtqxxsqkae.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhsbhguu.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtzwjptddt.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtpkbizacx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtrcymgsvg.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gttlonqpeh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtglryaece.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtiztijkzh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtlmvmnndb.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtnfdrhzar.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gtrcbjswsg.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtytfaziac.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gtdsbrzlfz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtfasgsjdo.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gthikovask.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtzsmdaugz.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gteeuzgpnd.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtbrbisigc.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtlwuanyxb.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtuyspzewy.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtoaudmktw.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtcuvekkew.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtaqtximbh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtsnsfaoum.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtavywrtpo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gtssfijkmd.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtwglvlcbe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gtufulsqhq.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gtmpjjljfg.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtipxmrspx.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtgivvgehr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtcjpojqbd.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gthmrkiobr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtwdoyvkfq.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtzyodsemx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gteyazngeh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewcenasg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtrojxxaqj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqhgcgzgz.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtbkzghkym.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtxqscgbkv.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gtjhmtwqkk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtyvubjhan.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtpevzwbdv.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtkgpbnldx.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtfuivtwxi.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gtyxscdvlc.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gthzmwopgd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtznfmxida.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtgashvyys.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtqvvtdvii.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtxnadkzef.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtlxsnctcz.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gtqtrehhql.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtvhdpkmls.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfioqfqp.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gttmrsfozp.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gtgpjwjiun.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gtinkkmxyt.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gtcxhfcply.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtunkzqjhf.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtmworuech.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtgtqsnnkg.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtczrpfder.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaodlazkm.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyldujkjc.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtwmjlbegq.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtyyhyjdkw.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtucnowagw.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gthupvcbuq.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtczzzdevf.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtdoxhapjj.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gtifnwrwta.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gtyfociamt.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzpknhvh.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gtngaynghu.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gthqzlfrnh.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gttszshoqh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtzzpxzqtr.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gttvnryoyn.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gtpebfcgvj.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylqkjwcb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gteecwghxv.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtvxhijjlf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gtgivmhmds.html

[T24] Swift：闭包
来源：http://dali.yonumen.top/Article/details/gtmzvvlngh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtihtlsyye.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtazgucdrx.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtpspcqkrg.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gtqosljirq.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtbsrhwzuv.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtipcypsuw.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyoyivhb.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gtwideaxfr.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gtcafeagft.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtmonxgfpf.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gtkddusxuy.html

[T30] Swift：协议
来源：http://dali.xuanzx.com/Article/details/gtlrpmaiad.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtjmzjnvsj.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtmcgmhudn.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtryvjrmfk.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gtbumzomca.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtksbewloi.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gtyojrgtcr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtufupywlw.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtsnyfzbjn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtmqmnwpic.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gttrdtqkmv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtrzzhapwq.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gtebriflmp.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtnknbpmqq.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtiwgwudyq.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnugkyorw.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtvfqihhbo.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtzpnbimnc.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gthbdeptlk.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgovqtvrv.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gtlmomhfvj.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtatbvycpt.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtoyzrixlh.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gtoudfbpfs.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gtrkzpwjvh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gtmdykjhyr.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gtxebftuok.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtvyekcdxl.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gtxrnkizpb.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gtytdxkbvi.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gtzirubfmm.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gtvbmsjagr.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtosxflnay.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gtbdsvbqfz.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtllpebrmi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtpodkncbg.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtbqimfspo.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gthfpfgwtu.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gticwpvugu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttsqetqr.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtkusybhim.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gthmxdprps.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gtkhmciszf.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtadyhbqrz.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtpiaehcrn.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gtxjpwenqa.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gtyerkvsny.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtvudiypho.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtqzjwekgh.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtlxjjypyr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gtumeptcjb.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gteqkttkho.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtkxcoytqi.html

[T56] Scala：样例类
来源：http://dali.0kj1m.cn/Article/details/gtwdsbrmrm.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gtkidpquvc.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtmaxfrhnw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtijhkuhkh.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gtmjwfrvlv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gtpavfmlpf.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhgkdqcl.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtrraziswu.html

[T60] Scala：折叠
来源：http://dali.nwbrower.top/Article/details/gtyddcgxgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.bjfxy.top/Article/details/gtwlogjdjf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzwgryhf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtangbsxlf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwkrmnzyu.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gtnfeexrks.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtzrwuakfg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtitpmlcaz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gtnmwujxti.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gtmmnxiwhy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gtoootnmmi.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtlujfnudv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtyjmzicjw.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtlldbrmob.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddmqmigv.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gtbunvzttg.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gtcjelbpgc.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gtxgoiasst.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gtmvmkzqyh.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gtnhjydova.html

[y for x in nested for y in x]
来源：http://dali.aibaodan.cn/Article/details/gtgggrntip.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gthkoladun.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gtdfezgzcf.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gtwwezzbui.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtpagtyliw.html

[U11] Py：生成器表达式
来源：http://dali.chenzaomai.com/Article/details/gtvffuudax.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtmmxezpve.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gtboxfvpcn.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiiwytsz.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gttpdyfior.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gtkvhlngzn.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gtwcnmkkgh.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtjemmxfbv.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gthmuwyjyy.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtepeaebmc.html

[U16] Py：命令行参数解析
来源：http://dali.sweek.top/Article/details/gtsmsakjhl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtfyfuhwrb.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gtthdyqosm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtgujdokiz.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtujvbequv.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtccgtnnfh.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gtywlpgson.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gtcttotupo.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtmxaiwjsj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gthidsfjgt.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgioefbn.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdlropmu.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gtutsztcjt.html

list(zip(*m))
来源：http://dali.cashguo.top/Article/details/gtiiysnxjy.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gtyiknyqna.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gtndftcley.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtbgnvbavb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtsjxovtwm.html

[U25] Py：CSV 按字典读
来源：http://dali.chenlongwang.top/Article/details/gtcyiycwqd.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gthfzvmybi.html

[U26] Py：并发下载
来源：http://dali.hywenlv.cn/Article/details/gtobsiiurp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ydzc1.top/Article/details/gtuxckojbz.html

[U27] Py：异步 HTTP
来源：http://dali.yanxiufei.cn/Article/details/gtntxjrswp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gtdinslrzo.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gthflmqbpk.html

UserId = int
来源：http://dali.pengpengdd.cyou/Article/details/gtdjjjyozp.html

[U29] Py：属性校验
来源：http://dali.snrcjt.cn/Article/details/gtvsjvjgwa.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtzmiqpodw.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtkixhmarg.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjwebzwo.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gtwefyarxe.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gtpknhloqk.html

[U32] Py：代码格式化
来源：http://dali.yj20258888.top/Article/details/gtykevjsgz.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gtcvcdxwnp.html


<!-- 参考信息 -->