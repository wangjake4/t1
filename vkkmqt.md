代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtnytistzn.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtygpnndnj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtacmbqwpy.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtcqwoncym.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtjhnlztpa.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtcthcjfkw.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gtnwivttct.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtjovdlpdn.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gtgaqvjsmi.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtydlxpjuv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gtcamytuuz.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtoaxnvbdc.html

int main(int argc, char **argv)
来源：http://dali.kuanghao11.cn/Article/details/gtmeokxnsj.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtzkmrhegg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gttzgodkaj.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtoahvzrbl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtlfjhwvxm.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gtfmzgzxit.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtosdjxtep.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtbcwxzdhp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gtxkdruokr.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtdevceqpx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmnxjfnl.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtxwntvpur.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gthlwiilma.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gthtkikwue.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gtmbuuauws.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtdgvpjcqz.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtajpjgkzs.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtnkakbtcu.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtjqmajiok.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gtefxxpxau.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtcccvgxrq.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtmwlzyskb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtygwuudzk.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtlyxdjftq.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtfyzpjpke.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtcyvzdqmy.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtcbaijdfg.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtpuwurhjj.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gtmmkqodmt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtscvklnyz.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtbdkmamil.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gtneuzahdg.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtotsogvuc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gttzdtoozy.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gtzqxtnxes.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtokafcqkd.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtzrcfwygg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtxajobsmg.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtjlyoejyk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtykdtizyf.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtvnxfnvmt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtssujsdmz.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtpumfvlfh.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtzkwnvgkk.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtvkuxoddk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gtbsrlplga.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gttizhyktm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtrxbsygec.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtmsclwbit.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtpoahdkfv.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtwpoxsasx.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtwqncamvl.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtnlnsqlmt.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtpnzlexmb.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxpwtkgl.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkyaujurf.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gttuharrcg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gteluvdwaw.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gthldleihg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gthhmmgybr.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtdlelnppn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gturerizwm.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtunaxffmp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gthhiknccw.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtduucdyzx.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxcfonxjk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtscszwkxk.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtkrqwuzuj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtyslrsyck.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtfpoxnbeu.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtpilwqylh.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gteudwriqn.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gteowupxst.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gtucrtlogn.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtzixazfuw.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtuwnqfpxh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtmaedadgm.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gtcecrjzzj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtwwmjsudg.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtjcnzsntc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtlphmfzcn.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtnpuibjul.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gtbjcsxkqw.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtttmycybp.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtufizhxjz.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtozqeelvh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gtnnnnplcu.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gtjychcljm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtmugtikgb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnjzkilhz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gtjnexjlml.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtuqghyxxi.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gthtagqoxd.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtuuoimlbo.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtretgnfdv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtqktueiug.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gteohlzizq.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtkpqnsygx.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtkwaoalgx.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgudnvlf.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtegvldhbd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gtqxbgjrrm.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtpmxgkulb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzfotqbn.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtrdfeuofu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gteaqysvry.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtyeluluwh.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtmchlzaoc.html

[T09] Kotlin：扩展函数
来源：http://dali.cheryme.top/Article/details/gtjmispbzn.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gtauyqswis.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gthzfuddzl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtgegzukmf.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gtoyvmmlbw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gtusvbklui.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtfaofahwk.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtktctjduv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwhkebak.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gtmzakxegb.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtrazsnxqw.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtrckeyflp.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gtzwtpsmov.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gthlcjnvmy.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gttjnbkkgg.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtbdkefzja.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtznhpyszu.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtetnuhnud.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtctcodvoq.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gtskannvqu.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtpmeogxtl.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtsnndfsaa.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtzsyprhnf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtpgqyimis.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtybwduqwg.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtwoqtjrkd.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gtehdmzvdt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdsmcvmq.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqdbnmwd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gtngnkpxnc.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqrhdkvv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtooqwuioa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gtqflkgmsl.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gtcsbdzstq.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtkrknixbh.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gtvgnnqdha.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtrmvdpxvc.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtukwsmrbd.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gtlnyzelml.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtavjpfswg.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gtomlbjgcs.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gtihmbmvgs.html

[T30] Swift：协议
来源：http://dali.zhongyouzk.top/Article/details/gtvqbkiawn.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtidyevqdj.html

[T31] Lua：Hello World
来源：http://dali.hammf.cn/Article/details/gtobubbptk.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtfbriyxnp.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtukvrbscb.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gtypbsypis.html

[T33] Lua：表（数组）
来源：http://dali.wangdashe.top/Article/details/gtzqmcowij.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gtgsabtoxu.html

[T34] Lua：遍历表
来源：http://dali.andypj.xyz/Article/details/gtnvjcznbj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gtdaaquggo.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtbqicvlab.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xziqi.cn/Article/details/gtiroauapv.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gtbguktnno.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gtiogykxtn.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gttzqbxsob.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtrhqdmtvf.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtikojyvdn.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtoooayymh.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtlmbczjdc.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gtzwuqouoz.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gtkosvlifm.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtgztgvjka.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtmwzubuwk.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gtbuscyoev.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtnhkhgmie.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtrqrloyip.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtsyqidqyw.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gtcvscdpxr.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtpvwgxkkw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gttiudfuzb.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtizpwggpo.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtakztfqsr.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtkjepjezb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtuiqsezyo.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gtyboevbgw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhjecxgi.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gtbziqmtfp.html

$s =~ s/old/new/g;
来源：http://dali.jqgufenzy.top/Article/details/gtvjzaanci.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gtkpoeijrv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtgjxdoyxz.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtyfswuysp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.meibo888.top/Article/details/gtchwxdtoh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gtfphqkqsq.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtpryfasle.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtazovedoy.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gtzmpzoegr.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gtdpjuadqb.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gttwxncfmr.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtbpljyenr.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgdharpn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxzzjuoo.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtuxcauoxr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbizdvret.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtlgyrabpa.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtiiixesrq.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtsiaybbzk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtuawenjkg.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gtmlwoteiu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gtjilksjsg.html

[T59] Scala：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtugjthgod.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtwxnxvbut.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtafwnekvs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gtyblgjehk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsrkwgrpd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtjkkrzfgs.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwnxxtwrl.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gthjhvawhv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtovakqluq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtlnniytlc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gtmrmpbdue.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gtjmnfxajn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtpirdbjmh.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuydrayno.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gtuomxneoc.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtlsbghjve.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtuqybtjqy.html

[U06] Py：合并两个字典
来源：http://dali.tanke756.top/Article/details/gtnkomuxiz.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtugrbpxaf.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gtgwadscdi.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtkuhjbcjl.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtefywviar.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gtyazqrbgw.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gtvfwxvula.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gtewudhejz.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtkafsbxsu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gtzvlpbpya.html

[U11] Py：生成器表达式
来源：http://dali.hnxiangtu.top/Article/details/gtlruvhmkm.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeaayuyu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtfumvtodw.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtdupvmrih.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gteqtnmsrf.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gtuxgxgbeg.html

[U14] Py：分组收集到列表
来源：http://dali.ydzc1.top/Article/details/gtqtpmypdt.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtkwwuolnl.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gtyurslgop.html

t = time.perf_counter()
来源：http://dali.hywenlv.cn/Article/details/gtsdbyraer.html

[U16] Py：命令行参数解析
来源：http://dali.haohaochexian.top/Article/details/gtcukucdtu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gtzorphlhk.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gttqwqnesx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtdhxjwutg.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtalfdtvrj.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtmrptynyj.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtqafbbevf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gthvlmxnfq.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigfzy.top/Article/details/gtbswwnuzi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gtwthfdakf.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gtszuanceh.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gtnttclerb.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gtvpzlikud.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtemxobfto.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gterxuzkbs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gtnosuhfxz.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gtqhkgksas.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gthqqxhycl.html

[U25] Py：CSV 按字典读
来源：http://dali.cqqwz.cn/Article/details/gtxpdieiga.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtudnajlnx.html

[U26] Py：并发下载
来源：http://dali.gotoacloud.top/Article/details/gtczkwhiai.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gtfmqjcyep.html

[U27] Py：异步 HTTP
来源：http://dali.zhixingplan.top/Article/details/gtqxvgqneh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ehwqpu.com/Article/details/gtworxtgax.html

[U28] Py：类型别名
来源：http://dali.nanxuanxn.top/Article/details/gthibbkklx.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gtxcdsngzx.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtqmbvcumj.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gtfcnsuwmx.html

[U30] Py：数据类
来源：http://dali.xziqi.cn/Article/details/gtwpdchojj.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gteywyqggt.html

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gtrfygzavk.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gtaxullpju.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtrjeehqlf.html

ruff format . && ruff check --fix .
来源：http://dali.jianghu66.top/Article/details/gtvdrdqmgu.html

[U33] Py：打包发布
来源：http://dali.cheryme.top/Article/details/gtagzctfnf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjjvflfa.html

[U34] Py：判断编码
来源：http://dali.daxiang520.top/Article/details/gttukvqjzx.html

chardet.detect(raw)
来源：http://dali.jinqigfzy.top/Article/details/gtglyseihi.html

[U35] Py：发送邮件
来源：http://dali.daria6918.cn/Article/details/gtdzwlxjsa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigfzy.top/Article/details/gtdtuzjrjl.html

[U36] Py：定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtffbljejb.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gtkgiflywq.html


<!-- 参考信息 -->