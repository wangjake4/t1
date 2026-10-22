代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2lqpdbuen.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2zfhvajdf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2mnsucoky.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gt2brwwhrub.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qujtnmoo.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2kysonvto.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gt2npkxegxn.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gt2taorjwep.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gt2hwovdcsh.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2ldxfzvzg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gt2wtruxxhh.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2pftbrcoh.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gt2dmgexijr.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gt2vsyxosft.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gt2anoomgpv.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gt2npdmmrmc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2ezyugcba.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2fvocwyqq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gt2hihhaxzd.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubgwedop.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gt2voqfgxmn.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gt2qjhewbvm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbammgjo.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gt2yjptvvso.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gt2ujjhtaoc.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2fdapylaf.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gt2eqtswhzp.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2vjgxpcnr.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gt2qhkvaxiu.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gt2dtbvxjvu.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2jslajwox.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gt2dvisfiom.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2dgdntzng.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyapbvjt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gt2yvrfgjhc.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gt2xridscfa.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gt2ofvugtor.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gt2yjsotxia.html

#endif
来源：http://dali.c1oappe.top/Article/details/gt2gyuqbtqs.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2kygpnykw.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gt2uvluaptx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2auhadiff.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gt2qcuoboqe.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gt2cumpogxv.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2shasgbxg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gt2wxfvcnnt.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gt2lcvgijsm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gt2xzrlwnmr.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2xoecshdm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2omdxzszy.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gt2xedlfbjr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2gzrljkny.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gt2dpjdrpex.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yegqkemq.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2cuztkdzu.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnvwzlkq.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gt2ihhqmduw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gt2ywotrvmw.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2lkpoaexh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gt2mbuwjueu.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2yckpivzv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gt2bqzgsxea.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2opyuhysg.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gt2nbfdeqkw.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gt2xvypxhyd.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2eysulech.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gt2kjogewcs.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gt2ladvrsfn.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2tzsxouef.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gt2mxnwibkm.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gt2lctlptce.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gt2bqninzfo.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gt2xyignipj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gt2auzefswk.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2rlvfpabx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gt2ypcqcgbv.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2qxubwxfm.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gt2idokxgpt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gt2pqyfotlw.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2bnwblcdb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2txrcgkfw.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2gcavoacn.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gt2mpehybmo.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gt2fdecdmxa.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gt2twaszryi.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gt2rfegdrnc.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gt2dlyuxwcz.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gt2yicpiqed.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gt2brbrykgl.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gt2qfmdfepk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxkfeos.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gt2ycwhxknk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gt2uyirtlqk.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gt2dxjsdzcx.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2eapgpedm.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2gusknwmr.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzogdtaj.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2nmqbqcok.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyfkhsok.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzhentvv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gt2eqoanqeg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ubokalwu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krlehfbw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2zfhajouk.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2niqzzusk.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2kyjjwfdv.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2dbhaamkv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxqdzyvl.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2bqhnxtex.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2eoyoxylh.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gt2lfxulxis.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmhyouog.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gt2papxscop.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gt2fbhdkkft.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2wzhkmwfa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gt2fjoburdf.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gt2lqqxntlo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gt2qwtbikjj.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gt2ekvysocl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gt2eqzzwiic.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gt2zstoebzj.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcnooglm.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2xqcpkqun.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gt2swwfowie.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2joxkrvgk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gt2svlhzgco.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2dazfhvmq.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2fixiqveh.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gt2pwsmnqlo.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2jyigdkde.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gt2kdsgqtid.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2hkjjtyaq.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gt2xpncgfyp.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gt2lmvuqlgb.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2tjjslvdg.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2vubjnfuj.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gt2uuxripkt.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gt2qldcnows.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2vifxkouy.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gt2oejxkply.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gt2nlekjzps.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gt2dghhqhyb.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gt2wtrejlzl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gt2wzwvawwl.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gt2txgmlrzf.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gt2jiwzvlax.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gt2dwtihgsa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2dobtbyge.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2loekonuf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gt2hzijwxli.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gt2hyapikje.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2astkeban.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gt2muhaxjaz.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frdkvxcw.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2ruzwdtmf.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2kpfojhxa.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gt2taybkuxj.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gt2bogqcwhu.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2dfdjgnjp.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gt2ygqegzsb.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gt2jmisgrft.html

guard let x = opt else { return }
来源：http://dali.chenzaomai.com/Article/details/gt2wceazabz.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuactbua.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gt2ptfdgcpb.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2fqyewvdt.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2xubpwrxl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbsytcx.html

local a = 1
来源：http://dali.aizwys.cn/Article/details/gt2bzhawreh.html

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgsghyux.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gt2ucxtgttx.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gt2ywfxlmaz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gt2ktnqtuwx.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gt2xqkmynol.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gt2cldnylcn.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgsqvbsd.html

function add(a, b) return a + b end
来源：http://dali.hnxiangtu.top/Article/details/gt2xrksfgga.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2xezqcshs.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfrzppfk.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gt2zjkyshyx.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2oixojmfq.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2fzwvsgwu.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gt2fghxdosr.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gt2zykxomnc.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gt2tcrftazl.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gt2kiewlizb.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gt2qgpvwhdc.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gt2ezsfbwcf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2xicjjouu.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2yqkjpsnu.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gt2cnoogadx.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gt2ocwhzdok.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gt2dajgybbw.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2mvcnlaee.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gt2xhxkhghg.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gt2chbujhte.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gt2ljltbngg.html

[T47] Perl：正则捕获
来源：http://dali.zdqjudy.top/Article/details/gt2vpwjqcen.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfwupxor.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gt2pjsuessa.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gt2lwtbleby.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2odriveqj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwgnngme.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2tjayhvzi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gt2kgvwlqso.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bicerfzq.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2wzimltti.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkbccuzx.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gt2nbazblah.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2iceniuad.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2isxxpvqn.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2smlxmnrv.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2nrersgnc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2kfbpnsie.html

[T55] Scala：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifnzhgop.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhdnyzgl.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gt2rjamjvdh.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzqszpfn.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gt2ezphfimd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2uktpliqp.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxzmabxt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gt2wtimkfgi.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gt2techaqfi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2wixrcoza.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gt2gtwtrhdr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2toiaumgu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tlrmzmzs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsrytdjp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tywaifvp.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gt2drfzroiq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2rwpdqpoa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gt2hayfmgnd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gt2ppgdnazk.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gt2ozgpikpn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gt2nckfslhw.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2wfqqdqxu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gt2scnaoydo.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gt2zbknprwc.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2caxobatj.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gt2jczfrfdq.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gt2dgodbscj.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gt2mximpdcf.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gt2ukxbyvmu.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gt2rnveclwj.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gt2rdfdmfnb.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gt2cfsvlmqa.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdlwaeqb.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gt2dczztltz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gt2dcucwwjx.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gt2trxuhlxq.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gt2wuhmftyn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ybcxt.top/Article/details/gt2kihwmmsv.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gt2wqkgvenw.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gt2cprruwbu.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gt2lauuykcx.html

[U14] Py：分组收集到列表
来源：http://dali.iojbl.cn/Article/details/gt2koudsceo.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gt2ulupxgzz.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gt2qmcepvwl.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrejejyt.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gt2cpwgcxuu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gt2jxjjycil.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gt2knufeuyt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cucudq.cn/Article/details/gt2djsjtkwl.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gt2ijorcaai.html

pat = re.compile(r"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbqjjnpt.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gt2fkqbfxjz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvnyckcf.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gt2arfnvqme.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sufxvd.cn/Article/details/gt2hzmsuqnt.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gt2kdwtjvlu.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gt2pdftbhmo.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gt2fcusvkiz.html

list(zip(*m))
来源：http://dali.iojbl.cn/Article/details/gt2tjxdbsxc.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gt2endvftuo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gt2xogvuywk.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gt2wbfggmwc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2xxetyalq.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gt2sykydzjn.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gt2sivukzol.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gt2utbvzdib.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.meibo888.top/Article/details/gt2kepqqqgd.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gt2ovzluhey.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxrkkktz.html

[U28] Py：类型别名
来源：http://dali.hammf.cn/Article/details/gt2nktwqfal.html

UserId = int
来源：http://dali.tianlin.xyz/Article/details/gt2qajmxyeg.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gt2sempxitc.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gt2zihywlkz.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gt2igyvxaqu.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gt2enhmirci.html

[U31] Py：单测
来源：http://dali.hammf.cn/Article/details/gt2hgqrxgrv.html

python -m pytest -q
来源：http://dali.sysykeji.top/Article/details/gt2hyunwyex.html

[U32] Py：代码格式化
来源：http://dali.sufxvd.cn/Article/details/gt2otwfknfa.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gt2jxsnbkqn.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gt2bhhazfcr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zdqjudy.top/Article/details/gt2subahnmo.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gt2wlnmootz.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gt2rzujeaxk.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gt2jhquskgw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gt2zasgbouz.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkaxprdt.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gt2qrakbdmh.html


<!-- 参考信息 -->