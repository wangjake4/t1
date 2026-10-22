代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gt2wqmzjpft.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gt2xgyuoirl.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gt2fzpjotcb.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gt2pbjttwpv.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2limgoofp.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2vytcqrdh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gt2iurydgsa.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2hawyxkje.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gt2sqweaksn.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gt2jrcezxcn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gt2acynixzh.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqxjmgjr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2ykfnjiir.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2txectuqm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gt2zkgvujny.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gt2jpsevura.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2brciftmi.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2rwffymjk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gt2crumotxf.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gt2ropnjqhm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gt2ltmcoprn.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2rghgpejb.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gt2abxrruqi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ynipofjs.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gt2rlhzwqcq.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gt2txuhkgup.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2ulqcnhjd.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2lrbljjob.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2omtwmyyu.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gt2subhdjbq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gt2txxvowfa.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2xjkbqfdl.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gt2pzywatwr.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gt2sfeiydpi.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gt2mblikkhv.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gt2yescxbxp.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdnauarw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gt2aarzsfjc.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnucypul.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gt2gfzyzutk.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifnibhal.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhoepfds.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bakelrnt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2qvgehpdd.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvhadoin.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2hsziosxa.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gt2waokvewx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2jynwdpbl.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gt2upocpxtw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2iwtcyxse.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gt2kjyvxymv.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2fasmfoli.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gt2ntxjyzzx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eseyojiz.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gt2tblzhkye.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gt2hdugdrbo.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2xrkopkpv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyzyvguw.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2votlggvx.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gt2ouwcpygy.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gt2pblolwvr.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gt2kwghikyy.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2ugxplmdh.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2glbtvqma.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2bikcwtoc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gt2fyuaaudb.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpaowohm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gt2jltukziz.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gt2utobzpla.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gt2fzyuzixy.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjdmfyns.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gt2ufilwwyn.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2xxbhpnfj.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gt2vwboudyi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gt2tzmjsayu.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2kfpirmys.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2jpnyrgea.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gt2dzeytktt.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcqjgbtd.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmrllvzk.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gt2gtgooopr.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gt2gbrwvqbp.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gt2ghnqkrmw.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2flzhrzvi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gt2xuxymkml.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2ykrtdnml.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygzbrufe.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gt2gqfnbiuc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gt2qasjccqj.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iphpdzgn.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2gzdcvyzj.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gt2pimmlnqm.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gt2equiredf.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gt2sxbzuuda.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gt2czmdxkyv.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugyosmtz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2sbwzwrdx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2utzougam.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gt2cjrrdetp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2bewqgqyz.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2ehkpoxaw.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2qwgjrypc.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gt2vkrwjmtw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqdqdmrk.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gt2gobbgqlc.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ieexagia.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gt2twpweumc.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gt2kuflvrhn.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdnuovxh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gt2rqbnaaux.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2lclqdnhf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2okiofdle.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2nmsaiqib.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2niypapcx.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gt2gazefypg.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2vcdjuful.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2xtbllxev.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gt2qzmyjeen.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2speippzd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2kfccrvxi.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gt2qgzvbhkh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gt2agjrvtbg.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gt2vmadadtw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2rqtlchyt.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gt2yuhucmgz.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2xraqtisp.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gt2fhkqlkjq.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2zvsoxnvx.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gt2npthstcd.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gt2aqbviffk.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2vgcxtcdd.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gt2mvrsuoli.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gt2rdrnwxxk.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzrjgxrb.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwjzawnu.html

"值: \(b)"
来源：http://dali.andypj.xyz/Article/details/gt2zqbrxnlw.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gt2fbnylqza.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gt2lhbqxgfm.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gt2grmkcwof.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gt2ndpnyury.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gt2pajmmoxm.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gt2qeweowll.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gt2faxxbmxb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2ybpycips.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gt2vpovtydd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2falunmvl.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gt2wjsknssp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2qhgvxcal.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2xmduyomw.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gt2agmyiceq.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gt2kdinmtnu.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gt2vwgsanlz.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2sdqiywgz.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxjkhrya.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gt2diesgxfp.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gt2ldnyfgzx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnavtnvw.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gt2ghjbehmp.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2nhodxerc.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gt2ecxkgjvh.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjyguaak.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2eoroguqv.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gt2fihxyzgh.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gt2bslmytcj.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gt2dkilyvdm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjuanoyu.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gt2rgvafzfx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gt2vidbjrxr.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gt2mvfyfcdo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2dfturpwk.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2idgunijt.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gt2cfwzasjo.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2nvfyxqkp.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gt2wsvyiqky.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gt2wlrqaowv.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gt2sbyrtklw.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2mukygfqz.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gt2vbkvoxep.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gt2ryitbxhe.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gt2hlaogguj.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2cqqvnbjg.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gt2uuvpxmjj.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gt2seysrksx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2gchlplwi.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2yjeclgba.html

"值: $a"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ettjlgyi.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsnzuwxs.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gt2sjmglrgv.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gt2rkjyvqgl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ifzidnlk.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibnyzvnf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bvdhkrmv.html

[T47] Perl：正则捕获
来源：http://dali.yj20258888.top/Article/details/gt2pdnyyckv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aibaodan.cn/Article/details/gt2uycjubgm.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2iomihsnc.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gt2phenicbr.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gt2rckdycje.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2ixypohks.html

[T50] Perl：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdanmigg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gt2igrtrwim.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ljicjxbe.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2ygyqnubf.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lalwdrtr.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gt2mboiughf.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2skpactvd.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2cffpkrxb.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2tfksknkl.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gt2csbaimna.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gt2hkozapug.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2ypnzbpum.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gt2vbujhbwa.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gt2cvtpksdk.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2gixamkio.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2chvutadv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gt2scvvedeo.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gt2bjnrvajv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2yosfjvau.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gt2rrymhmdb.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2ljfittub.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gt2finpmcyg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gt2ktlqhylt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2gjrxfdgr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gt2yaozkzha.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2emkgkjck.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gt2ldjkmbva.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gt2fhoqyyrt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gt2jrftqafv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gt2murjhwky.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfvsmrdz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gt2sfizgiur.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gt2uhddzqjq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guannengcc.top/Article/details/gt2qzwqxros.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hugwxnbx.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbtdycuh.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gt2fdnjvbhs.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gt2rutedhfq.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gt2sgzvinif.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gt2rxinjiqy.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gt2thcedzwn.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gt2ofgzwteb.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvrmduye.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gt2mracjdzt.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gt2cssblkmk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gt2vxdpmfxc.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gt2ehmzmbye.html

(x * 2 for x in arr)
来源：http://dali.0kj1m.cn/Article/details/gt2cifwbtrp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2taweegvd.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkqtuzmc.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gt2tgejipxd.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqtygptq.html

[U14] Py：分组收集到列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nedodaei.html

defaultdict(list)
来源：http://dali.dashuyun.cn/Article/details/gt2drnfjlxx.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gt2mwhggrwl.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lavbfytk.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gt2vnkohvmr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gt2lnlwswds.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gt2hdxejzeu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gt2rpdwdvbo.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gt2gtzijxdh.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2zzkufues.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258888.top/Article/details/gt2ifgkgqoc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gt2qvmfjcys.html

[U20] Py：缓存函数结果
来源：http://dali.chenlongwang.top/Article/details/gt2ypskbkrx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zszaxrye.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gt2vggjdxfd.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gt2jsttqffm.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gt2ynnslpwg.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gt2uutkdygs.html

[U23] Py：分块读取大文件
来源：http://dali.kuanghao11.cn/Article/details/gt2cgnltotb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gt2rhggushm.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gt2yvlyhzug.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2zjkozpom.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gt2lgfbxuis.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2klrvxvlu.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gt2myshbrmb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxinkj.top/Article/details/gt2kxzfsmzc.html

[U27] Py：异步 HTTP
来源：http://dali.xinyue.icu/Article/details/gt2wpnrtqvl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gt2yxseecbz.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gt2rwzwfkxh.html

UserId = int
来源：http://dali.meibo888.top/Article/details/gt2kpgnuncs.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gt2relegyeq.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gt2tcvamxpz.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2cihklagh.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gt2iulmgpsz.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2scukoznw.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gt2pwgsiskx.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gt2rcjnluqi.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gt2dahohhjw.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gt2vcttyehs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sweek.top/Article/details/gt2ofjyrdfr.html

[U34] Py：判断编码
来源：http://dali.yj20258.top/Article/details/gt2evdxitky.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gt2ynmxgzkf.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gt2kibhzxha.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gt2daiuktfw.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gt2upnqaoto.html

schedule.every(10).minutes.do(job)
来源：http://dali.yongpay.top/Article/details/gt2whcsikzf.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gt2epahfppp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.c1oappe.top/Article/details/gt2vzpaksgx.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gt2nbuxbybo.html

Path(__file__).resolve().parent
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqsjzdwe.html


<!-- 参考信息 -->