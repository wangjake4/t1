代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtothyfxww.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gtrbaoheth.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtaqcvblqg.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtheffsjmj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtwjoilyop.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtfshiwidb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtplwyitbo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtoxjwzvht.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtmuluuxyo.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtycvsvyvq.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gtaxxcsnbs.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtsfenowso.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtnryqxfyk.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtwtvvsewb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtigfuquiv.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtauefekwh.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gthcvaysdl.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gtbnzylooh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtygasleax.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtevozmvvs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtvmpfzgla.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtgvgipxnz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gttlifothg.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtrlgselag.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gtsgcuxnos.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtfgusqrsx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkczzwkq.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtfzijrgzn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtqcdfdpey.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtcawfhigi.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtsricmmww.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gttmtxihip.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtvxjmpyvs.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtstindkkv.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtwatjhbjh.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtqpvdnxdc.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtagvisvrq.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtqkvyjpqv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gthnhukqzp.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gtfiesdxvh.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtocadfbqw.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtffficttl.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtpnnuaqfs.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtgtkjlkqn.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gtvchmtzdh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtbqvehzeh.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gthzofqclh.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtggtptwgr.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtonfwjqqg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtafkqopok.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtlrjaxsqp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtfvnyhzsw.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtgzgigyvs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtnoeraabi.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gtalfptadi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gteioqnkbv.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtknovvabq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtwlwbbdzk.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gtmfndgzos.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtaoajbvrx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhljxhcy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gtzbviggzi.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtsyhwzqir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtihkznlrs.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtdncqhhuv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtjbmiinbt.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtziisspxh.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtoufyiegf.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtxewbwksd.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtpmqxpvjx.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtuocwezzb.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtadadmdsd.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtsrlonqut.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrrqrfke.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gtohhhjhhw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtnrgdlpbi.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtqshcvnki.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gteaqztmfh.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpzfedsc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtjkkpoqvs.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtdoslcllc.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtpwspbvol.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtmfggtivc.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmtdzvwo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtniovbgta.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtwxmelwhh.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtufxsrmwm.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtuiwpstfv.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gtwzivcdbu.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtngctljlf.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtauxrhxuj.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtvqafhcty.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtxxueptiu.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtbkkteppl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtnzwrstaf.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtnykuvlyc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gthqwntirp.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gtsfwiuhdk.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gtjbkqqwyr.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwetdkowj.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtonmkwbkc.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtshcezwyi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtbzjspktg.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtdwnihmby.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtrdazcbwm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttjwmfhjd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtzgsnhijm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtppysglaq.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtbqldqxpg.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gttncpmqxk.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtxnpqwssi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtpwrzbkuj.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtgqnnxoiq.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtjhbrrsvo.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtbdljtiyk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtialhycui.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtyxzxnprz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gtdfjieudn.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtmamqhduv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtapykhdds.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtiqyvvnaj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gtgewlonrn.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtqideyrqq.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtyiemfcam.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtmfkiimfv.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtjrbtquux.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtmqkdetjt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gtwrenubvx.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtmefjdkgd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtpcqqoemk.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gtlmjzkwem.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gthpukkwzs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtgfcbdvse.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuwjqvdm.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtetjrscji.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtucckqbgm.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtidzjqenv.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtwxnzfjbm.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcqpolau.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtdwrshxod.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gthtqcyvjz.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtplylfroj.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtaliuklrx.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtrlshoxnv.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtelhcmkvk.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteovztxvz.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtqszeeyww.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtbvuvgmep.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtlhucuxfr.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gtgskbjoky.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtajitpfoz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtvotgdciu.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtlcvkwkew.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtclrkqnnb.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtgexwwiec.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtrjcmxbhy.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtotcauvhd.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtracnooin.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtkyxlcmmk.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtghnwflsg.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtffoqpwra.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtmvhjitra.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtvtecpkwq.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gtcxtdydth.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gtdkxyswjq.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtavvtbgcn.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtbywgmwdq.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtjpxryimj.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtkkesyndj.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtochatupy.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtrwvfmwtr.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtrfyexlkh.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtzuioudsj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gtiukdfusp.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gtaunbrulh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtyftxvlqx.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtpysvflri.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtaxfyiioe.html

[T36] Lua：函数
来源：http://dali.yangfankeji.com/Article/details/gtsxignqvr.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtltwbtwkq.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtmgguxmky.html

"a" .. "b"
来源：http://dali.birdmap.top/Article/details/gtimyvqnqw.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmqtnzzx.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtuynvuzsr.html

[T39] Lua：模式匹配
来源：http://dali.yonumen.top/Article/details/gtdwyvmxcw.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtekfqimda.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gtbdkfgvjg.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtnafdqqef.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtukjlanag.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gtiwllxbhe.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gtcctrzxhn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gtzrfyriic.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnlbussl.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gtwythzsyd.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gtjdhhbivv.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtacwnwqqb.html

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkpoysdx.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtzuvykrst.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gtbhcpisxv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gtcplqvlav.html

[T47] Perl：正则捕获
来源：http://dali.vqdsnc.cn/Article/details/gtznztelqm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gtvxmysaxz.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gtnwoybvgj.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtksaxzhex.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtejtnuusx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfurldjy.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtzcnzwoha.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yueranfly.top/Article/details/gtffdtcdso.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gthoznmpgb.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gtxznnxsaj.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtuibhbpog.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjzcywny.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtgjwvicwk.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtnltczjuh.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtqbgolvxf.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtnahuavqc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gthatjpcle.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtjetuberv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gturidiaoy.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtojajwios.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gthigsuzel.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtwvdfbarq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtddnfvrmo.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gtgfmkyjjf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtkhipjliu.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtaunxhezk.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gtzvzgonpn.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtbkiajhfd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gtkdkrymro.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtghcowihu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtqvhwwjzr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtueopymtm.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gtnwfgeael.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtcomdceaz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yueranfly.top/Article/details/gtciqustwj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gtreczvrbv.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtgelctfdu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtrjfqqumx.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtpcnodkts.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtvndkcuoz.html

[U05] Py：列表去重且保序
来源：http://dali.bjfxy.top/Article/details/gtansqiqji.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtdqhbivjv.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtasqkybtl.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gtdhyplthr.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtqwzsydhy.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtnfdyucxg.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gtswsixism.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtimpydvlf.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gtbyrzvfhx.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgbmdbxi.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gtaeinebxm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gtdjqzrdzw.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtflzfheia.html

(x * 2 for x in arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtvsocypxl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtebltgxec.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtbdaipujk.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gtjnzsikiy.html

deque(maxlen=10)
来源：http://dali.gzhubu.top/Article/details/gtnjskjkuc.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gtjarpbtmm.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtksbwjliw.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gtuumdwmbb.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gttnqwwhzr.html

[U16] Py：命令行参数解析
来源：http://dali.316326.xyz/Article/details/gtqbmiisef.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gtukviyznt.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gthcuwvgsc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gtybhjphzc.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtebuenghm.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gttjpgmjrv.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtwcggaryf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gthuvjhmwo.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258.top/Article/details/gtsjljttyy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gthrwiztas.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gtnocqaggp.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gtgotjgryc.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gtagtyjosv.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gtttfkflrt.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gtxbfklfel.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtxzuumgvp.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gtjsbnjysx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtnoycjonh.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gttfstexen.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gtygdtyemr.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gtplupkqsy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gteejdtjmk.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqdbokkz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gtrlsgowsx.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtynyuajab.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gtknndqrdl.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gtagnnamyh.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gtyahgxjqo.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtcwyhdfia.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpeqtnvz.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gttzclmnkq.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gtyldovxlh.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gtitwnzcxh.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtxhhfnyky.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gtecmnlovv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.svipenyu.cn/Article/details/gtqzjockht.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gtfqkyqbyc.html

chardet.detect(raw)
来源：http://dali.zhongyouzk.top/Article/details/gtxpbsmdgh.html


<!-- 参考信息 -->