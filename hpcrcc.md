代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtdomrfhxl.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtkdzhmwif.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtfjhvbtvg.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gthjgeogki.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aibaodan.cn/Article/details/gtdizsewiy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtufxycnnd.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaziovwz.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtfubegmvc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtvjivkpkb.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtfemgsyhc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtlhryjplz.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gthpnuvdpb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtqtxzywrf.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gtkicrcwwq.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtwqewkgkk.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gthzeanerx.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyqpreqg.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtmxhdikao.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gtegscqgxx.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtliwmmdhp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtiajllzqb.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gthrfzbvas.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtrvenzbvd.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gtyrcsioqw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtjkaxsrib.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtptgbckag.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtccjdnyoc.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtumxlnqhg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtiqidargl.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtxronhztt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtacteclxq.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtdbkttwdp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gtwylqclcx.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtehvpdojd.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtbavppbrh.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gtdzeqpsbv.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtsgztgqrb.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gtqnweldky.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtvbdtxxcd.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtotvjajzu.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtxzuvobtn.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtvvyzxoav.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtttylffov.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtuxbtxkwt.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtnasewvkv.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaxmnzji.html

#endif
来源：http://dali.cashguo.top/Article/details/gtermleduw.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtwhdedxjk.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gthioddnmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtwzuzfohp.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gtbeaiceza.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gtxhindfxe.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtamgfxhpt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gteozasweo.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtsulubzin.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrglxrrsd.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpkrozqj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtadbzmnjw.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gttjzxqkan.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gthqtnmrnw.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuszyglt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllhoxemx.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtzornvigk.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtoxzuxafc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gtcnwttyhv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtdznnehzd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtkkbscsff.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtycrmkvlt.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gteuortcpz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtffagruvq.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gtpurxvkuk.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtghaoqsen.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtthkxykow.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtspatvika.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtdjsvvthz.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzogjrrru.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkexhgahu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gturokvpin.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gtzapmrkzd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gtwvznwhxo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtzshyakmy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtbsbezzdi.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtiseymcol.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtvrsobeeu.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtfethndir.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtkyxhfibt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtixeotakp.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtwcaoxmle.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtipxtvqae.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtjilwlbjs.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtabddasak.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtqccyeqwi.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtxjmsdirg.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtktcykjbr.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtdalrnyxz.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtceizhxfv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtqnxfewth.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtsyasdtsp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gttjapvpiw.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtevfpfpqg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtfumxnktn.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtpebsqhlj.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gttsaglezm.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gttmmpydup.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtpezldlme.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtgszirnvu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gtkazwdthu.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gtcxkqwoez.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtbrncpbbk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtzpeticlz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gthlqbpoxb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrcgivmci.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtyfowmycr.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtvihzmdoe.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtvmkirzzi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtogibzpmh.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtjfptxlqs.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtcckoabap.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtgjztwtou.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gttghtnvpj.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilvbxjaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtubhuyvxw.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtsviyywao.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtpxmlkmkj.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtlsvrtcwb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtjillnhml.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtnlngxxfk.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gtuhwjmkhz.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtztnkwyjx.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtjugvioea.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebreogdb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gttbzytcqa.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtfgevdreg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtgwsxjdgb.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtohjxwces.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlgnbuozo.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycnlalrz.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtruresfdh.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtaaubidcw.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtaeumqafm.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtljofcprr.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gtonkqygen.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gtnkatquvx.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtepuczcap.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gtxexlnvdu.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gtpnitjckx.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtajffhmhn.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gteyagcoei.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gtnpamejur.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtmhjfhjlx.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gtkwpgknod.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtsywbypfg.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtpnfiiuxn.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtamwhkcdb.html

[T22] Swift：字典
来源：http://dali.9152youxi.cn/Article/details/gtipqtsbvs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtkswedboc.html

[T23] Swift：函数
来源：http://dali.bjfxy.top/Article/details/gtmsallfnn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtlsziwfix.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtymafponu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtsbobgwzn.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtmqjohviz.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebwdqrsr.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtturflvvw.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gtupszvhtx.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtccjcwxek.html

do { try f() } catch { print(error) }
来源：http://dali.hnxiangtu.top/Article/details/gtraewjkfr.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtughzlgel.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtmnhgyxbj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhixingplan.top/Article/details/gtavcavtbw.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gtyrddquos.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtonlszjtf.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtkccbpdso.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtsvtskyvx.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtglfemdcj.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gtmqcskkjg.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gtnhvfnfec.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gtoalebnxe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gtahhdmrxt.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtfvpcuibz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258888.top/Article/details/gtyartoqxk.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gthpgjrxvy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtlfjmooah.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtljplqmcg.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtvwlesqrc.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtixisigaw.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gtstwszbiq.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gtvqrjfdjz.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtshuhbcud.html

[T39] Lua：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtqbkkrbkz.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gtzjjveffv.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gtdrvuvsbr.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gtvlfyptny.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtgltzapiu.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gtleqgwviu.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gteuimxkxj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtzlewwrmo.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtyzbfjrif.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gtjamqmchv.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtzsfsilrr.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gtfpatuosw.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtifwgsick.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtzkbltrog.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtimkyicuy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gteuuxejjl.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtvcbyyiny.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtpubvmdfn.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtfcsvmkny.html

$s =~ s/old/new/g;
来源：http://dali.dashuyun.cn/Article/details/gtuflltzfe.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gtqkltdxzs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtmxwmgbpq.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtzcuvzwem.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtzildpbes.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gtmlyqubkp.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpexrals.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtttsawucu.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gtwpljqpzx.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtwfeaxmpc.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbqjdfdh.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtkwuqehxb.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtbioiuooc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtqtcfwsyw.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtlwtnyvhb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtxgxbuplb.html

[T56] Scala：样例类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvxgzunn.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtyslxqsgi.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtcgmpyavu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gtizolqksj.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gtgjokjszg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gtrsxhppmn.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtsidcqimy.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtrqkcoopd.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtujishmya.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtkrvbwoja.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpkxyfsqr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtntqtabax.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqwyjqynv.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gteipzcnmf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sysykeji.top/Article/details/gtiryusxas.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfyvsomb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtbqmfoahm.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtetigavzt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtqtkejall.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubpkoehl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtzofhqydv.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtwfxqtmcx.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtmpqrpjmv.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gtizgdowvl.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gtsexgdifj.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtithezyvi.html

{v: k for k, v in d.items()}
来源：http://dali.jyoumei.cn/Article/details/gtqklvxrxp.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gtadrwfspj.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gtfqfsesfa.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gtjjiwgort.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gtbowfbefw.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtysjbzpno.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gthqxwqvuq.html

[U11] Py：生成器表达式
来源：http://dali.zhoulong.xyz/Article/details/gtwepvcpgw.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gtxnmgtejy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gtxfmvrumi.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtjcfjzhtp.html

[U13] Py：固定长度队列
来源：http://dali.hnqzz.top/Article/details/gtufftkuin.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gtrursxucw.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtxztojrif.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtyvxqmctn.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtswcqlprb.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gtnhwiskmk.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gtvrnbnaeg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gtuoloxwfu.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtockyzorh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtajqwsqlo.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtnwbypaas.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gtdnjtnogu.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsypnxvs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtyaswixfq.html

[U20] Py：缓存函数结果
来源：http://dali.ydzc1.top/Article/details/gtsdbtavfe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gtfgxbcvuf.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gtqtafmvcx.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtzluotlhm.html

[U22] Py：矩阵转置
来源：http://dali.wangdashe.top/Article/details/gtbdzyupuj.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gtbwupwgfy.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtbgthazmz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gtsswzhrzn.html

[U24] Py：路径操作
来源：http://dali.quarkkingdee.top/Article/details/gtieqzuxni.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtrhjiyyvf.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gtvjiipfny.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gttcgwvbyg.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtsvnwadlo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gtzaczsaef.html

[U27] Py：异步 HTTP
来源：http://dali.shzxlz.cn/Article/details/gtrwycsgpn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gtyapvuhut.html

[U28] Py：类型别名
来源：http://dali.jiagoushi.top/Article/details/gtyotxdxxt.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gtmusoclfk.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtvohwerug.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtpzmbkbhu.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gtaannnixb.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gtjmphpeuk.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtsxfsflnh.html

python -m pytest -q
来源：http://dali.sysykeji.top/Article/details/gtfbircqhy.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gtscsjwvig.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gtpqftstuz.html


<!-- 参考信息 -->