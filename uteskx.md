代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kciemsdy.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gt2gxgryerk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2ahleseca.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gt2ajbcjpgg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2itbijnyg.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gt2abswrtuz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gt2llotsbxf.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gt2qmluqkpf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2cnfiagud.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2rwqplibm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gt2flpdtimu.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gt2bhdzhbhs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gt2fsrjqvgx.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2azuibjcn.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gt2tdijadpe.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbmyzhma.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gt2zgtbqkgh.html

[S27] C：定义常量
来源：http://dali.jqgfzy.top/Article/details/gt2punbrkpe.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2zfqmbjmv.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gt2ucfwhcsw.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gt2ehstahof.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gt2jwgnheuw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gt2unvbulze.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gt2rwsqotju.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gt2hxhthrgu.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gt2paacxqdl.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2igmpvojw.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2bkbaakzz.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gt2iixzgygh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gt2xlhirkfk.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gt2grqpzryq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gt2thquyuso.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gt2bswtihfc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gt2nczkoomt.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gt2nnaewjrw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2iemveqth.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gt2wevmxyex.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2ibvopysj.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gt2gutemuso.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2gdtyvlus.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2sbxpqrwc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2finhxhfx.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gt2pghkeqjn.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2lkhqkfxi.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gt2rgjdjmax.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gt2jxejrusw.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2jenobepa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcynmwcu.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gt2iffneocl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gt2ibbnqkan.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agwmwwvy.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gt2kzdptrql.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gt2xpbaotev.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gt2ahccdoyj.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gt2uiqfamon.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gt2bzvveqlp.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gt2cbvtfhzo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gt2ttoiiclz.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gt2iwalbgpj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2rsjrsrjx.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gt2jqrocdgv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gt2kofzksfu.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2ghizpjcb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2mvojlwlh.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2digfotag.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2verjhunp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gt2xnllangn.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gt2yiuwavca.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2bjmmyysf.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gt2awpkdetd.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gt2jvvhjffw.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjphgbbq.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cijxokxc.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2mnaipixr.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gt2xbcghqnv.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gt2gcbwwxcx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2lourfmpf.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2gnwnplpz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gt2gycmyvqy.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gt2okujixgo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gt2mistcvnn.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2zhaztyfg.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2tpmqribg.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gt2sxngoecf.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2guokkpiy.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gt2kptqbyzt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gt2ilhnshdb.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2eyruvgsf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2airvfsqv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xavxrxlw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2vueqrasa.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jsbrkvqk.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gt2yfeafjgv.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2hqhltbtu.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gt2tadsbhda.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2szjsyubt.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gt2mwlyacbm.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2btbozycu.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gt2hkfuhkkg.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gt2encatgsp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cttfhybu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gt2fqygqzrf.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecpgvkop.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2supqgaok.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2qaopbomh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gt2nyzahzlf.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2gwesxrjd.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2wggtfycz.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcemzhlk.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqkeopsy.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwtfavwd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gt2nhgwwwel.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjmolhin.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gt2nhpgfddv.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gt2mfqtxutt.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2bqnfanvz.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsjcnigr.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2wdcstntz.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2qmrrssld.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gt2ulwptqjt.html

[T15] Kotlin：接口
来源：http://dali.jqgfzy.top/Article/details/gt2kxmgvdxi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzautbrz.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfxzidtf.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2vxadndqf.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gt2zvgspkzo.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gt2gardcyyo.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2smvbgcir.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gt2ooovsdzi.html

[T19] Swift：可选绑定
来源：http://dali.shzxlz.cn/Article/details/gt2hsiizmiq.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gt2pzjfnzcu.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gt2eiuiroln.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gt2xmmbgadz.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2jhhptmzi.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gt2uuzdbgln.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efbuyydt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gt2phqqirld.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gt2unvwsbyv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gt2ihytosot.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gt2ejufhhng.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2ewbzfnet.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2kdraqesh.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2zxqzygdf.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gt2eutcfczb.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2pgrdcwtj.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2owtngfjh.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gt2kgkvwgud.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2syafnizs.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2durzepcn.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gt2qqrnagxl.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2rnjeionu.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gt2spbceanz.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gt2kbcqghve.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2pwtmpkeo.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2avisqaap.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gt2lqvgyjru.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2enjrgbjt.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2solsquwc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gt2wcklmcgr.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gt2waascetc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gt2giwgyhkn.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gt2wukrpenp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qojtgtuf.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gt2xawuplga.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvowmdpw.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cohsjahn.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gt2paptiiow.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gt2lysoazes.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gt2xqfacvba.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gt2pqzlkqun.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gt2qldoazlo.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gt2scppjexh.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gt2dmmkeyto.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2qlbrhnrd.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gt2ueqgzdlm.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gt2lzhbwstb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gt2fdpgfdyx.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2plgsvrqk.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gt2loulkrhq.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gt2hzfwnpry.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gt2trkqwudx.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gt2ynukvkna.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gt2zorapqgh.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gt2nibtmsoe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gt2obwztqgg.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gt2mohrqbsv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gt2hndspfwc.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gt2aqjvzrop.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gt2blxjsogr.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2pswmkgfj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2rdpbxrvk.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ximaucvg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gt2rztcymhr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gt2ffvcgufr.html

[T51] Scala：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2yshrgnyb.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2agtsuxfk.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gt2encjwbhg.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2mwxnoagp.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efzvegre.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2jowxjshb.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gt2xboaqtux.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2kbkjrezc.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsvpaasp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fctdjmev.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gt2lirptgrl.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqefpjty.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2inapkryc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2btvrisgl.html

[T58] Scala：函数定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjpxfcrq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2wkomhnly.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gt2yrspwdvd.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjqgdxzk.html

[T60] Scala：折叠
来源：http://dali.meibo888.top/Article/details/gt2eyiyztyg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwzmarrq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2yxchdtup.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2asrdsrmq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zcsoqamg.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gt2wtnrhaad.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gt2aryttemb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gt2kpmbebdf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gt2hnibxnky.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gt2alwxvkpz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gt2ftlptoza.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2elyhmeth.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhgwfwdh.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gt2lphuezfk.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2eueezyph.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gt2ejylndie.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gt2ugokpkbw.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gt2ruxkuadn.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gt2qnnsjwrf.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gt2ehsrrkep.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gt2rrxgojou.html

[U09] Py：字典取最大值的键
来源：http://dali.chenjidiqi.icu/Article/details/gt2smryjkuh.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gt2lblnwixy.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gt2ajdvqynb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2atlbbani.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gt2pfwmsqqq.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gt2tppuehnp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gt2gjtlspll.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqzvlste.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gt2pietyucw.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gt2mevzjypo.html

[U14] Py：分组收集到列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxdkykfh.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gt2llzhgbih.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gt2zubbswuv.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gt2ppzrkiyh.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gt2sdpabxqr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2onmxlkvi.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gt2eolptnxp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gotoacloud.top/Article/details/gt2yayutefz.html

[U18] Py：预编译正则
来源：http://dali.dianchejie.cn/Article/details/gt2zbqncujt.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2ypzguwpj.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gt2gwzxhfss.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gt2bnkollnl.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gt2pgtixaca.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gt2ypvxinbv.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofjfiygl.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaoydwxs.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gt2eytfbpow.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gt2wtwcpknn.html

[U23] Py：分块读取大文件
来源：http://dali.jqgufenzy.top/Article/details/gt2beamlrkp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gt2okbnvlok.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gt2ntotbmvl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2ifzoveij.html

[U25] Py：CSV 按字典读
来源：http://dali.guowangkeji.top/Article/details/gt2nznoteno.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gt2jrvbnxpj.html

[U26] Py：并发下载
来源：http://dali.fzhhl.top/Article/details/gt2sigylgqo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gt2hwdnwcot.html

[U27] Py：异步 HTTP
来源：http://dali.9152youxi.cn/Article/details/gt2qjylngjd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cheryme.top/Article/details/gt2zntahybd.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gt2nqldzgob.html

UserId = int
来源：http://dali.sweek.top/Article/details/gt2hpxypjbk.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gt2warjvpnj.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gt2oolvpyqd.html

[U30] Py：数据类
来源：http://dali.xziqi.cn/Article/details/gt2iqccqfrv.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gt2abzwpkml.html

[U31] Py：单测
来源：http://dali.0kj1m.cn/Article/details/gt2ymvqlsnz.html

python -m pytest -q
来源：http://dali.wangdashe.top/Article/details/gt2cinpcbdc.html

[U32] Py：代码格式化
来源：http://dali.gogol.net.cn/Article/details/gt2lsjwhriw.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gt2dghbsifh.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gt2lwhlxdbn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gt2aoicijeq.html

[U34] Py：判断编码
来源：http://dali.cashguo.top/Article/details/gt2heudaxmp.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gt2tfvfwzfa.html

[U35] Py：发送邮件
来源：http://dali.sxryk.cn/Article/details/gt2wzpgdqsh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.smart0.xyz/Article/details/gt2rneagudt.html

[U36] Py：定时任务
来源：http://dali.yangfankeji.com/Article/details/gt2cnjdbugj.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gt2irrzlrwv.html

[U37] Py：读写 Excel
来源：http://dali.wangdashe.top/Article/details/gt2btwqonjm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gt2qvhpzqlv.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gt2zgucaqvf.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gt2xcobtzdu.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gt2appmtmiw.html

sys.stdout.isatty()
来源：http://dali.cheryme.top/Article/details/gt2kprvndxe.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgpgjqfk.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2xaozlkxo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vffgcjql.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqqdbchi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gt2ihypzzcd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sysykeji.top/Article/details/gt2ytgjpymq.html


<!-- 参考信息 -->