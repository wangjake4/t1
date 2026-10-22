代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gt2btizvdgj.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzetmfys.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gt2fjiynjya.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gt2xkrtpscw.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gt2nflruint.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gt2cpnofmee.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2prhcouls.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gt2nvfscuqy.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhkenwqt.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gt2vewytgcj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gt2elcpnlkf.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onsqosnm.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2dxcrbakt.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2qidkwtch.html

#endif
来源：http://dali.xylfe.cn/Article/details/gt2lqpuecca.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gt2gynwafaw.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gt2gdmfjwkq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gt2xuptvhow.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmuyfenc.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gt2sdrntljv.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2idsgwgao.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gt2mbmfhpzw.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2unxskzay.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gt2tucrgomi.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gt2yohtupmu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2plyewscz.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gt2lyeqytce.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2wocdsaxx.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gt2kgdfjoqy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gt2tjzwxvtm.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gt2pvkcwwhc.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2quaeyfzg.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gt2unmbzrzf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jianghu66.top/Article/details/gt2wwkpvqrl.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gt2yppzshxs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmzjumpf.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2bnnnxgsz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gt2gktkjckh.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gt2peovbjrq.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gt2prwqnosj.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrvgjviw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gt2bbdvwqvs.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gt2awnzzyge.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gt2xkqgaovq.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gt2autrwxiz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2afwnatsk.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gt2tkilqcnz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gt2ufrujhfw.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhfhtdkx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gt2knbpsjnd.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2pobgklbg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccojhqkq.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2ibosmatx.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2udhzicwu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gt2drdintig.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2nmbuksuu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2tixhbwro.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccsbcygp.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gt2bkeuurkd.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gt2fdaggarl.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gt2fzfctjry.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gt2azzbrymo.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gt2aegwtfkb.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gt2ydlzwmbg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gt2svyqqgjk.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2bceorlvq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gt2ytcgyriv.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxlemxzs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gt2flupyycf.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gt2mgtvagcc.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2lxwhtrde.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gt2veovorzk.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gt2dthhzsdu.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gt2xmgdrnhg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gt2xuffketx.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2ykidiyvq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbzzblrl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ktvfdjwu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yelunoft.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xltqybkk.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2vcuvouwt.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2reiabmmy.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gt2bkmmtjrd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gt2hedbceig.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gt2zznyugzp.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2oqdnhvpf.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gt2whnvepkd.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2ttdzktgq.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2ayptcrkg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gt2gehchvcw.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gt2dzljdaiv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2hwwjnheo.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2xghyiazr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gt2gyuautlo.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrndmhte.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2rkhtgaab.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucvgmska.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gt2elfvvwcx.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2phtejjyf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbreawhv.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gt2mgbiaiwj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gt2wufjcwru.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydkierjv.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2qqrgwrca.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gt2khrxklqc.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gt2tiyxhmli.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2thlmmzlt.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2bjsodxqr.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gt2kykfcssv.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqhabyvi.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2kjdybagd.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2hcpcwhkt.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gt2msjxqoex.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gt2ebgrzzhr.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbfziqrw.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gt2jmvutfyl.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zewpgztk.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gt2fgeffoga.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gt2qwadfhsu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmppnxff.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2thzbessk.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gt2osmpculu.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjevymye.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gt2tgzrkjqy.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gt2cvhrtxfj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gt2enehsglm.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gt2uvwucngi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2lfzhlomh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrrkwnp.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gt2twkxxlio.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lgukkrto.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gt2snvewvuc.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tucvpvwz.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gt2kadfbiql.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2jnpdxhzi.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gt2abceznce.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2rxfzksiz.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gt2pkzpvtxx.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gt2zfrzsdjk.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gt2vydaghmv.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2ulfcksim.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2vyrgoxvg.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gt2egfpiibq.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gt2syoqqbou.html

[T33] Lua：表（数组）
来源：http://dali.birdmap.top/Article/details/gt2bzsgcxdo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gt2zypodzzt.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gt2spuhvmuo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gt2vawayqaf.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gt2wanlxjoo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2osgjrcvu.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2hbgmadwl.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gt2ikeajsth.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2dqngvlka.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gt2iksamyrq.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gt2gbhxkaku.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2ziuhijkl.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2irwzpmzc.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2iwrvwmou.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcjsofq.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gt2nwhzihjq.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2limtxoyv.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gt2dywpyfsw.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gt2tzrfezxe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfgtfnys.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrazgdz.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gt2oxgxohxz.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gt2xvuicyam.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2wjzttwhv.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gt2ditwxwti.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gt2gzdcwdoz.html

[T46] Perl：哈希操作
来源：http://dali.vqdsnc.cn/Article/details/gt2ngeopfdf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psdmhpdy.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2rjfjfpnv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gt2resqpbeb.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gt2nuwpempc.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gt2qarhhrbc.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gt2livuecnt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jlxsculn.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2psivewqm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gt2xtqisxzj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gt2wuuuhrxs.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2tfsmrmab.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2tfyqgsml.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gt2lnbuwxgk.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gt2pheebsyu.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2zmqstjyo.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2dkndirhh.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gt2gbvbodvz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srlnnxvp.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2fdykeuvq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gt2zlmpyqff.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gt2iqgpbcui.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gt2fjmzuodj.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gt2isciywmb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gt2vxyhxmtq.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gt2sywivaty.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gt2ofbeugdn.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gt2lzvalgxo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2lnmiidvy.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gt2mcxodpsp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gt2bfvtmzak.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2snfmseld.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gt2bsrcvzay.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qhaxdsbx.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gt2veqhvqiq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gt2ilmhggty.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gt2gfdsoovu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gt2qehzzkwe.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gt2wsmvsjep.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gt2koxgbbpr.html

[U04] Py：变量调试打印
来源：http://dali.svipenyu.cn/Article/details/gt2ngcepobh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gt2wccdiyzq.html

[U05] Py：列表去重且保序
来源：http://dali.gzhubu.top/Article/details/gt2apftgbvf.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2yefnazxp.html

[U06] Py：合并两个字典
来源：http://dali.jqgufenzy.top/Article/details/gt2lhopwodj.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gt2uacqglpm.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gt2asjylqnx.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gt2hgbweuxk.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gt2rgqjevru.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gt2tffnqqhe.html

[U09] Py：字典取最大值的键
来源：http://dali.guowangkeji.top/Article/details/gt2rkqlrsek.html

max(d, key=d.get)
来源：http://dali.ppjwa.cn/Article/details/gt2einzfdlz.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gt2orykfruv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gt2sgxqfnze.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gt2hwlvdxig.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gt2tiltwggj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gt2zaerfkxw.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2lbxndgcl.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gt2pungxbyd.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gt2mwdzldti.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gt2sxtzdswm.html

defaultdict(list)
来源：http://dali.jlsjyb.cn/Article/details/gt2bzavultx.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gt2ymdkggho.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gt2attwvzru.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gt2xhlbifkz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gt2khequbvy.html

[U17] Py：初始化日志
来源：http://dali.316326.xyz/Article/details/gt2qbycntsf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqaizpnf.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgpqzjhm.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gt2kmbpzbhk.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gt2midjrydq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gt2wpxtmhpa.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gt2brtmqhfz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258.top/Article/details/gt2bokbljuc.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gt2cvyssrxw.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwoamzjr.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdtpfwgp.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2irgpnyjm.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2exacivjl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gt2qvjfbvdo.html

[U24] Py：路径操作
来源：http://dali.9152youxi.cn/Article/details/gt2lbsnrjcg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2cjeqcubi.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gt2ygoekdhv.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gt2rkpzrzrh.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwhricxk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gt2sicedzcx.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbrbmuga.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gt2usghnlof.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gt2wnouqgtv.html

UserId = int
来源：http://dali.gzhubu.top/Article/details/gt2dmbbygpj.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gt2ojoapcex.html

@property 与 @x.setter 配合
来源：http://dali.ppjwa.cn/Article/details/gt2yaaklwrb.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gt2qefwmrko.html

@dataclass(slots=True)
来源：http://dali.havefunace.top/Article/details/gt2aqnxxkio.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gt2sgxvzptn.html

python -m pytest -q
来源：http://dali.havefunace.top/Article/details/gt2ycssvani.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2dyfjtbks.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gt2atakrlcg.html

[U33] Py：打包发布
来源：http://dali.feifeiyinyue.top/Article/details/gt2ioscqfnk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gt2dnkzmqeo.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gt2dmpsdvqy.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gt2robpezjs.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gt2lcgtjkim.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gt2smcjwupx.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gt2tvlznwzk.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zurizszh.html

[U37] Py：读写 Excel
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsuzckoh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gt2xdivbgzz.html

[U38] Py：获取脚本所在目录
来源：http://dali.hysaishi.cn/Article/details/gt2sdbxxwbb.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gt2wxrpaxjv.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenlongwang.top/Article/details/gt2lpuzgcfg.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gt2bupsvixs.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gt2nqoanvnf.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gt2klsmsrby.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gt2bimnqydc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gt2ieuzewjm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zdqjudy.top/Article/details/gt2dfpozect.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ydzc1.top/Article/details/gt2hbaiqinm.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2suaiyvsc.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gt2dxoaxmxt.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gt2xaoknxaa.html

declare(strict_types=1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgkelkxe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gt2rdttnxpg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2pnaytuxh.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gt2uzgajwbx.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chabywxd.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ekwtycrt.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gt2uoifxzzd.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2tkxgphcu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.9152youxi.cn/Article/details/gt2ligqxwsw.html


<!-- 参考信息 -->