代发 wailian999

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gt2qayfqafc.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2onuofmaj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeqpevln.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2pamjuiuh.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2bvidwlvb.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gt2sdknwxry.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2dwguodpa.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2cjvhgvnb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2darezibu.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gt2gppcyptv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gt2wiqbirvd.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flqfefuq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gt2bbtvjbir.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gt2ucyfdevr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gt2rgpskfso.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gt2lqgsjwwg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gt2jajkoipq.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcjaotyv.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzgcxahm.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gt2suypyuoy.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gt2mkfskpop.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gt2wyzuhgqc.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uutmkupr.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajqyjfhf.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gt2endyrohx.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxaatzeq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2armjjtth.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gt2qvsuxzvj.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gt2cksrdsrw.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gt2sklmhmkw.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gt2yxkuyizb.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzdionym.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2gbwkxooa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gt2sbgdvuiz.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gt2clgnvits.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmanmxgc.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gt2szwqvpzx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcswqphy.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gt2mrjwkixh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gt2sgdyfexq.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gt2uqimxcaa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2geyctrdx.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gt2uyztfapj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2yogqsrri.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gt2gpbkgkmu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2yyonrqwe.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gt2mtfxtizw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2dqifzetl.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gt2rnfegfvh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylzmiqen.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gt2tpjxlpkl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uddouiln.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2noczlewh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gt2eosskvcr.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gt2mqjunron.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gt2zpjhhrau.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gt2lgulvlvd.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gt2bskyubtu.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gt2drbnubwz.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nusfzgbg.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gt2txqivvrz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gt2gdeznosv.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2wgwzowlx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gt2wxtoaovn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2gwfhwhoc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebdjrcfb.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2kgoegpyn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gt2ipithrsr.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gt2vbfkrcxr.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gt2drhngomw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gt2hefpveqc.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gt2vihfibjr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2ftaouzkr.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2nussswxw.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gt2axoekoin.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gt2rpjaludx.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2vfhgpjkk.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gt2tmhuybzc.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2kpscftpw.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gt2xffnrexp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gt2tyopvsvi.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gt2ogsbirlu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2czvedhby.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gt2fbgznizo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gt2wntqvjam.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gt2asonxfzj.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gt2emobycep.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gt2enyxvrbz.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gt2cnngnlsz.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2hggtczqa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gt2hzstmpxe.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2vngpwpii.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2dcuivjci.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ciixmfbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gt2sghomiwj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2whushozk.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2zfphedse.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2bozbhvbp.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2cgbdtqmg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2kefdabqd.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gt2yduornkd.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gt2iozrphfv.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnrauiry.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2slagkyvm.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2ogwptgln.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whzttpxf.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2ngyjbtde.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oahyzvwy.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2cliysdts.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvvowtrn.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gt2rthypxuq.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aykopdvd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2crsibotd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gt2nyopuvrv.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rylbhspq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gt2ycllcoex.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gt2fvcumfdu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gt2bjrsiylg.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gt2mgngaikk.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2kdagrigp.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2nnpvqgib.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gt2dcrrwjwq.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdrzbumo.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulalecjg.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2uwfaukoo.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gt2yeevgspv.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2vofrrekt.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2jtqdkghe.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gt2ggankzso.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gt2hpjqcoee.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2qstqjhjc.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gt2uysultxf.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gt2jehktdwz.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gt2owmasumg.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gt2zowkgaev.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gt2qjdxygli.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gt2rclqhrhm.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gt2tagpjjyd.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gt2oceqkxia.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gt2nqxhijbg.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gt2usmnqmst.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2sgupklwx.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gt2ibtynnmk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehfidhrx.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gt2gzyssqpm.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gt2skgvnjjy.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gt2degrwail.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gt2nulaygsd.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjqatxtb.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gt2vqrxkrzz.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2vqdcribr.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gt2jdfsazua.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2ewkxhibm.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gt2mxruhjju.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gt2rndadlrb.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gt2jkldkgjx.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gt2ouyxpsuo.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2hfishfui.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gt2ofnrfqzk.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gt2leyyyqaq.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gt2uxmscsez.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gt2hrbowdws.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gt2ujvrmijf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.feifeiyinyue.top/Article/details/gt2asllnutc.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gt2ewhualjw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gt2mjmmgvag.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gt2uwypqsha.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gt2nzooczya.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcgpmaap.html

"a" .. "b"
来源：http://dali.havefunace.top/Article/details/gt2ttyfouqw.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gt2nhvybqmu.html

if x > 0 then print("正") end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oofurxgb.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2jixevryf.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gt2tkzsvxab.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gt2uaevelun.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gt2efxsoqkl.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2gghdvrzw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zubzletj.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gt2xgqgxzvt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gt2odzpflad.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2aukbtiqh.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gt2xaoiozda.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gt2gprtrmre.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gt2xrgrtbxb.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2rktjgktv.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cbnmrobx.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gt2rwuwyvzm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gt2rqgahzxp.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gt2sukorikx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gt2loefrnns.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gt2mdrozzdg.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gt2dstznjzd.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gt2dtvpmybz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2brugzmvd.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2liybraug.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shuidangran.top/Article/details/gt2xupsdnqj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2npcrxitr.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2nfwodtrm.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2slfbpxor.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gt2yxmdhjfy.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2zpyrkywv.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nojsuapf.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2irivdhpm.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2femzsuex.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2dbcyrqzk.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2szsggluz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gt2omxlmsdq.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gt2cvxyelng.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2vzuxkdlv.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gt2ckjgxtax.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gt2ifponlkd.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcwjudzz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gt2gcjwqncz.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gt2nkmkeswo.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gt2ynuiylgq.html

[T60] Scala：折叠
来源：http://dali.jinqigfzy.top/Article/details/gt2laskdjim.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gt2rhedreke.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fcrczmqz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gt2unhkylfc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2auwlvapz.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2jylchedz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gt2xxofucyu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gt2accbjdhg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gt2bycpgtsn.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gt2gdqvqkgp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gt2akrpbzkl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqvnjnc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gt2fkqxvhdu.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gt2qzobemrc.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2nulngnsr.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gt2bopvqpjp.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gt2mgtnwfet.html

[U07] Py：反转字典键值
来源：http://dali.sxryk.cn/Article/details/gt2lacxtonv.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlufwsyn.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2qegzrzdh.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gt2qrunfhsb.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gt2dytmtgsc.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gt2fuxtqfjc.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gt2ilbqjttn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gt2wangbdga.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gt2qzggtaqc.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gt2rehncixu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gt2ihcjsrzi.html

Counter(arr).most_common(3)
来源：http://dali.iojbl.cn/Article/details/gt2nujptmjt.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gt2uvstmoes.html

deque(maxlen=10)
来源：http://dali.xylfe.cn/Article/details/gt2dramupor.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwcpskwo.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gt2kzkogwdf.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gt2vzqcufyi.html

t = time.perf_counter()
来源：http://dali.nanxinkj.top/Article/details/gt2rdgjumyp.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gt2orrfqibf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gt2mgpdsbxm.html

[U17] Py：初始化日志
来源：http://dali.bjfxy.top/Article/details/gt2wrblltme.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skbsjfdp.html

[U18] Py：预编译正则
来源：http://dali.svipenyu.cn/Article/details/gt2jodenpyc.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2sbpvnrvw.html

[U19] Py：正则替换带回调
来源：http://dali.yangfankeji.com/Article/details/gt2nikklyul.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gt2aftmewmc.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gt2owcwclbk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shzxlz.cn/Article/details/gt2xyxfqekj.html

[U21] Py：自定义上下文管理器
来源：http://dali.yonumen.top/Article/details/gt2dmcozemm.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gt2mkcvdjgz.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gt2luxksvxl.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gt2wzbbngqj.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gt2vhwomjjb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyfarmzr.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gt2cjujjkog.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2vmuysesq.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgufenzy.top/Article/details/gt2xnjekfhh.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gt2fwytulna.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gt2lktxwfqa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ehwqpu.com/Article/details/gt2fwtngalz.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gt2ftdejtjo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hulezddn.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gt2lmsfwdig.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gt2wwumpaet.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gt2ujbcowlh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2docdxove.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2odlctsva.html

@dataclass(slots=True)
来源：http://dali.jiagoushi.top/Article/details/gt2pwdmloeb.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gt2vcquuzot.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gt2dimmpwns.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gt2twpzylxs.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gt2ygobwrhv.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gt2wpgcllmq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gt2ndjecebx.html

[U34] Py：判断编码
来源：http://dali.guowangkeji.top/Article/details/gt2pjcnjkix.html

chardet.detect(raw)
来源：http://dali.cqqwz.cn/Article/details/gt2zkxjsamp.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gt2uvgncsqg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gt2tasjxuud.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gt2vdzbzzne.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gt2jznfoctw.html

[U37] Py：读写 Excel
来源：http://dali.zycfv.cn/Article/details/gt2hntgxwhs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258888.top/Article/details/gt2xxixvlne.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2jposdyrl.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gt2tatyzctd.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gt2laqwgnus.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gt2pwwsfcqc.html

[U40] Py：打印到标准错误
来源：http://dali.yanxiufei.cn/Article/details/gt2stajojgp.html

print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2qhguyupj.html


<!-- 参考信息 -->