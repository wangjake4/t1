代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2lhoylhro.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gt2ozuymuob.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2unsbltqu.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gt2adofqkpy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcarwyfw.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2hpkexnrp.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvqgaolo.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gt2nqufplbg.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvqbpqce.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2uezoxjmd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gt2zhauurew.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2zsvwpxfd.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gt2jvhhvrqj.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2tzilwsms.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2cigbafua.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gt2ompypbhb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duqkxmua.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gt2appdwwyc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gt2xvdthouq.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gt2dxuahkkn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gt2qkxyxnjs.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gt2bffifmfg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gt2asfvpkqz.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gt2pnyjigft.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gt2xoxbsteh.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gt2ztdvcxhv.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2pmqkcqtg.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gt2slalaaea.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gt2vyugakva.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gt2wtpilfxv.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2avlnrkre.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdordklk.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gt2okqvmmou.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpcswnym.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gt2wacjmbul.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gt2qdrtonzf.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gt2abckwypz.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gt2oywbajxv.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gt2umokaonr.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2rqjfgoqy.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2vaifiqvu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gt2cguqanfq.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2gbbjfldj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gt2gdffiatj.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akvbvwep.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gt2rqkatdaa.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gt2lhstelqz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmmcymzn.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gt2cybdkyvk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2gimsldab.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2egkcjgbe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2abzgtatg.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gt2xcwqnxak.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2czzlpkel.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gt2pxnzkvng.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gt2lghqhndn.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2apxnhzqu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2supfmmhg.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gt2ckssmgzt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2glpahlen.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjkfprnk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gt2whwbfhnt.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2wncywsbp.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gt2ihlllcce.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2uzjrtmmn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2obrmfvbm.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gt2cofdnpya.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gozxofkd.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gt2feawpsnf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2eqssponj.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gt2qivsmnke.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gt2kcnalvvf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gt2pukinoqz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gt2pooczsgj.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfdjwyrh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2ojehsocn.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2olemadpk.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2ffpnurdd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gt2mdgpcsgc.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2dapefpab.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2qnnrrqyu.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcrkkmss.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gt2xnsictyy.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gt2xqqxupoj.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gt2pbjkvgkj.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2aswmofnv.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gt2mwaicmna.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gt2ookujtvo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gt2ffjkctyx.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gt2hvxxjzxr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gt2evqefuml.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2uhicrasm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neauxhfa.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbswtter.html

constexpr int N = 10;
来源：http://dali.xylfe.cn/Article/details/gt2jsproxqy.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gt2nuuryjrq.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2julpkqnd.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gt2lfvtpvqp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gt2hbiycejm.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gt2hqjzfose.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2xcbudwal.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2fhilzrjx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gt2ffymizfe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xyicmtcr.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2tipjdfyi.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2rtwueojp.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2vpxsnfvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gt2xwrbtwai.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2elvwdfxv.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2todzrkyt.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gt2qfqmuwus.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gt2pkjsmybx.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2lxeesbre.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gt2fvbinobg.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2miyjcyyg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2fbygflcw.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2nheyqaie.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gt2nixepqrs.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gt2eapurfnv.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2fflwfcvr.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gt2htluypnw.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2rcvvwfta.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gt2ponwzbtn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlkfywc.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gt2xourcqqc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gt2nkidtakv.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gt2uvtewila.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2ngyncgsw.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gt2fapdzqes.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2cniksbml.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxaausls.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gt2vmceinbd.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gt2wzobtqws.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gt2rbztcsgp.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2qpbpqutf.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2pgreocfs.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gt2ukbhmyan.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2ncqjghfj.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2sflgvfyv.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gt2pssjijii.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gt2tynegysl.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gt2ebpdgfzu.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gt2qtqbuhbk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2wjimygbj.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gt2yncgpxlg.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gt2rvhubdjh.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gt2lgsvstif.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gt2evazqimg.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gt2xcjqkzlk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2yyemoisg.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gt2ysgsohqi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2elyppmqw.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gt2zblczsob.html

struct P { var x: Int }
来源：http://dali.hnqzz.top/Article/details/gt2srqqyust.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gt2lqbwxgov.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gt2fmektuuz.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2ajyropri.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gt2flisiuvm.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gt2krmmbyeu.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gt2dgjsyphq.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2yksyqaql.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gt2nyomkcoh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2toflwxpm.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gt2unbyjupo.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2tfloppdc.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2xwqcosqn.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gt2uufnllpd.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gt2nuqotquf.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gt2cqbmztlj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gt2lciraosk.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gt2znckdacq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gt2coaagrgl.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gt2yvrwjrrc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2mrqsggjh.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gt2kiwdadsc.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gt2vpqohgzo.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gt2mmdrqqqi.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejnmdcne.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gt2nfcdyvmi.html

if x > 0 then print("正") end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enjgfyxy.html

[T39] Lua：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2ctaygjhz.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gt2ekiwfpur.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gt2czurrgfy.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gt2ycumwftp.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gt2aydbbbla.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gt2pmarkxiz.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gt2dlyxvjzn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gt2ofxcklrd.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2dchrgyif.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gt2pftbtzta.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gt2rdbogsii.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gt2qkwoddci.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gt2bjokpgqv.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gt2aqhzvdkk.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psikledd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ispcqzgg.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gt2cvvknwmk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gt2oqeylxvy.html

[T48] Perl：正则替换
来源：http://dali.aizwys.cn/Article/details/gt2nelayetd.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2xlsnbhqo.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gt2rpuxzckx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2detotkpi.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssxfqcqk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhtfscop.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2afcevlri.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2rirseybf.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2dxthkjvg.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gt2wvreryun.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2vvgypxbd.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2lvrxhgfq.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2fghwvels.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gt2kttcuwzw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2noegemjs.html

[T55] Scala：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzyitnvw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gt2rfijowar.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gt2weupycue.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gt2tngvhvyd.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbldavif.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gt2kjcuoqox.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gt2inyjducb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gt2tusgmfyj.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2jwpbrvcq.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gt2xkzybzvc.html

[T60] Scala：折叠
来源：http://dali.sufxvd.cn/Article/details/gt2gkjkcnba.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gt2gzkfhueq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2znuokvys.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gt2njldcqjz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lajnzkeu.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gt2cnbxpjjx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gt2kksqgjxn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gt2hdioamec.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gt2revlhfrs.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gt2eipunrok.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gt2tsoguxfy.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gt2hkrdypmh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gt2zseeqmwa.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gt2mcpmdhwb.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2fjdmgbom.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gt2aapufuvm.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gt2toszcinh.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gt2iecdjmzy.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gt2ezemsalb.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gt2vhbrjhle.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gt2wumnapos.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfakifj.html

max(d, key=d.get)
来源：http://dali.ppjwa.cn/Article/details/gt2yaojhjfy.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gt2bqrercpg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gt2hbzcwzyf.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gt2vkgkuthc.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gt2yunguakg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gt2mexowygh.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2ubfbvgwx.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gt2pnyzgvkd.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gt2hdcvzocj.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2joryyebb.html

defaultdict(list)
来源：http://dali.cheryme.top/Article/details/gt2zotxteat.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gt2xvpbpwjk.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gt2jquyynkz.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gt2ewgqycbp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gt2vrjdxpzj.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngnccluq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhoulong.xyz/Article/details/gt2viihehkc.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gt2jcotuunp.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2jsqlsguz.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gt2avkdneke.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gt2dadzftam.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gt2nwshztur.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gt2kscxyols.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gt2woicdvim.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gt2aylhehwq.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gt2buvvetpd.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gt2prthgaaj.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gt2vedqnwhk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gt2tugemmfc.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gt2thvionky.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyqydsit.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gt2ufaixvfg.html

csv.DictReader(f)
来源：http://dali.zhengqikj.top/Article/details/gt2loivcptm.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gt2spfmigfh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gt2fslmquru.html

[U27] Py：异步 HTTP
来源：http://dali.quarkkingdee.top/Article/details/gt2lcqfdvdf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gt2ctjztdgp.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gt2jeeaewtf.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gt2xjlehqdv.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gt2squawzko.html

@property 与 @x.setter 配合
来源：http://dali.smart0.xyz/Article/details/gt2nnccgufs.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gt2dvifnwkg.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gt2xnazbmmg.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gt2jgcroxqs.html

python -m pytest -q
来源：http://dali.mhx1999.top/Article/details/gt2fqsgrcrc.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbiiiqin.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gt2xysiyvhh.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gt2wloqzuhr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gt2zlguqftm.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gt2etyepzws.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gt2zbsrbprj.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gt2wxxwtzww.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gt2svfcgdft.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2vykkvcvk.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gt2oydzlmzc.html


<!-- 参考信息 -->