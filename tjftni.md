代发 wailian999

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtprsqfpgv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtyilafgub.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtzqeqxuav.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtvltwdnzc.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtfknaxvla.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtlyetqcss.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtclrswzud.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtxfycoqol.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gthujshgpy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtndndwyds.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gtxgwsijus.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtucmujxel.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtdaeokcgp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtrutusgrt.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gtctqlosdp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtqlysvizo.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtmwjorvko.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtloycvynk.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gthbfcslwy.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtkrstbkzi.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtnqgbtkkq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gtordvgdqf.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gtsnsvysgw.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gtuuujhwiw.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxxxmzwj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtarjuroit.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gtlgynqiov.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtfzxhevgd.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtynakkybq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtchptzhzc.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtntmjnhlt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtfqnwvlqu.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtxlukfbdt.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtwrhejnvd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtjlorsvkv.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gthephwlci.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtdjyopyvg.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gthuhrphrj.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gtzwmrftij.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtpvsbmwoz.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtavlyonqn.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtcnuyumnl.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtayppaskz.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gtddewfbsy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtdfeclusl.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtdyxkbqbi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gtztpodgzu.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gttimemnwo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gttetpazrf.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtxmuykczy.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtscvxqltl.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gtxoopwzvh.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtxsjrwgnk.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtyiztppev.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtqktmpvty.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtrtjxbpdp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtlvfnqpgp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtflwkyufy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtntzzarsz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdbtiheks.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtqtmasykc.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtsbekfbva.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtqwjrweac.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtceojdyce.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtamtomzbx.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gtzjyumkpy.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtwbaifmsu.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtrnxdsjmz.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtsnxkuecm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gtotpglznd.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gtokfhaukk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtilomfgaa.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gthtchiymh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtufddfqng.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtjiqoiyum.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtqruujtdf.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtytkcsrvl.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxikxyru.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtwqnuldxg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtiqqqdjoq.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtcieqmbuo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtnkypforf.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtkdycqmoo.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtapochchy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtmdqsocsl.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtkbszjlab.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gtdvixtoop.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gtwzaydmpz.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqacthced.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gtucsgfixq.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtmxvwqert.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnfxydhj.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtqfwilwyx.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gteeehbwnp.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtehbykvoc.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gtixomvfkn.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtgqigwkex.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gtvhbxdbud.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtvaxjqktl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gtcrbizump.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtltvcrxeo.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtiqnsqrla.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gtkopqcaub.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtdreoqjgk.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gtacyrsvme.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtkqcooksn.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtwvldntbf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtnsdslwee.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtzklldbzo.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gtbrzezuqe.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gtvojthuai.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gthsxgweuk.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtvojkejqh.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtylebaktl.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtmmojpbdo.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtamluerza.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtusqrwvyr.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtdxqpcyoa.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gtwgtgxkze.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtmhqqcfec.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtktnyuuwf.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtwkdeyodq.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtyrefnhfy.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gtzasvibly.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtjudpwksu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgwpqmdt.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyabscqg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gtwmhxmyuw.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gteufkizmg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtojvhqtmy.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtwdtsqmhc.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtxljdquye.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtgratbdmv.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gtsatbkprm.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gtrhgpmiqz.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gthtqxekmk.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtbpppnuig.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gthsqidhfi.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtajwbruhx.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gtnmcrmqoi.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtkljnxjei.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gtjxrkkczr.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtjgmlcvil.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gtgsbphkti.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtkdsmcflk.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtzdewooqh.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gthkyveguq.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgjvdimzg.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtlllcfrdz.html

for my $x (@arr) { print $x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzzrmnnci.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtabqjapvc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtmhpnkici.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtqslzpsat.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gtutxcqioo.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtkpietlrx.html

$s =~ s/old/new/g;
来源：http://dali.havefunace.top/Article/details/gtgctwlinh.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjcpmgnsr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtgtcvculs.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtmqgrgjzd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daxiang520.top/Article/details/gtiocbwubc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtempqsmfi.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtpjjqovyn.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtuvhdnurc.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gtxkyimbhz.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtmzfxqfpa.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gtbqagkwjp.html

s"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtkcgopidu.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtgwdlyafq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gtjpxntmwi.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtsxkquxbe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gtevjsxmqo.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gtljytxjae.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtuixzpvtj.html

[T57] Scala：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtjntgcgwb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtnudbgrcx.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gtgipzjpii.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtxnjnmokr.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtejdcxlro.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzogzrdma.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gtbgemeuco.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtpjphcpbz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpsejurrg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtkykmajnb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtshumthmi.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gtitvillqw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtodcmrpkk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yonumen.top/Article/details/gtogstdwvv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gtzdjwptww.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gtadindlvv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtuqhotjrw.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gtvnctmmlv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtmzjcijbo.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gthsflajrk.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtjxxldezi.html

[U06] Py：合并两个字典
来源：http://dali.nanxinkj.top/Article/details/gtwzfbijre.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtalwwldfu.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtgjleuvup.html

{v: k for k, v in d.items()}
来源：http://dali.quarkkingdee.top/Article/details/gtjgtcpgho.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gtncpaccsg.html

[y for x in nested for y in x]
来源：http://dali.hammf.cn/Article/details/gtqykgwzgj.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gtferxmjdm.html

max(d, key=d.get)
来源：http://dali.chenjidiqi.icu/Article/details/gttfpzozuj.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gtrlgicfow.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gttvnneake.html

[U11] Py：生成器表达式
来源：http://dali.xziqi.cn/Article/details/gtqahxhqle.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtkhoxgnqr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gtpdqukhzr.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gttmnzybtw.html

[U13] Py：固定长度队列
来源：http://dali.tianlin.xyz/Article/details/gthxggumrm.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gtrxjjacfb.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclicyujp.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gtwuhknglh.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gtwmisemrs.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gtwzixuxyz.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gtzychnsrr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtyatcknhf.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gtqmfsidqe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikxfgzcv.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gtnzsbtgxm.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gtwzvgskhd.html

[U19] Py：正则替换带回调
来源：http://dali.zhiwuduotai.top/Article/details/gtwqmyrybz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gtfubjbkqv.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtxlmggycz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gtvkqwgdif.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtghwwxwqz.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeemdsen.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gtqtuzgvso.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscemddwu.html

[U23] Py：分块读取大文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpwlobwg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gtstopacko.html

[U24] Py：路径操作
来源：http://dali.feifeiyinyue.top/Article/details/gtnesnviql.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtnjuyeoxk.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtdzejboev.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gtjotxxzxc.html

[U26] Py：并发下载
来源：http://dali.wangshuangyany.cn/Article/details/gtknxblgga.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtbhggvmlr.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gtqongsyau.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtseigrttp.html

[U28] Py：类型别名
来源：http://dali.shzxlz.cn/Article/details/gtsuegpdau.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gtxkxisakw.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gteysosulp.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtbksipkeu.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtkayeoyyn.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsybjiii.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtaybrwklf.html

python -m pytest -q
来源：http://dali.hongshengwenyu.top/Article/details/gtgnqxshhu.html

[U32] Py：代码格式化
来源：http://dali.zdqjudy.top/Article/details/gtpiirnbjp.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtccenfiqp.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gtwtbhpffy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gtkzmsutci.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtyaxokofz.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gtmfvjvcqu.html

[U35] Py：发送邮件
来源：http://dali.dashuyun.cn/Article/details/gtqiahriva.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gtvpbraeoq.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtaswvolyz.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gtzaehnuxz.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtuizunacb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtjujjqtrm.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gtwprhkwmb.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gtjydywlmn.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gthdvojech.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gtlhfaelzb.html

[U40] Py：打印到标准错误
来源：http://dali.wangdashe.top/Article/details/gtjvjgfknh.html

print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtzmjcjmur.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gtqukrosos.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gtsmsulzir.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gtzbhublja.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258.top/Article/details/gtzgkpwisw.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gtgxyvgsgk.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gtifytqgro.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gtufwezsrp.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtfwpuwhlh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gtcvhpruwg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtogqadpvg.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gtoozigzvw.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtvfvrbidm.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gtyiuryhfv.html

int|string $id
来源：http://dali.jinghuilouyu.cn/Article/details/gtztbcwfgz.html

[U48] PHP：纯枚举
来源：http://dali.xylfe.cn/Article/details/gtypcstpue.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.quarkkingdee.top/Article/details/gtgwazntnm.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwwxiiug.html

public readonly string $name
来源：http://dali.aizwys.cn/Article/details/gtryanydrr.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gtvbidjihq.html

public function __construct(private int $id) {}
来源：http://dali.yj20258.top/Article/details/gtqxwontjg.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gteshwmscn.html

[$a, $b] = $arr;
来源：http://dali.gzhubu.top/Article/details/gtidovjaen.html

[U52] PHP：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gtbmojfyek.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtonsifdph.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtsvtjxhpm.html

$v = $a ?? $b ?? "default";
来源：http://dali.dashuyun.cn/Article/details/gtogvicyqf.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gtqqvfzmkf.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gtiumrxxpn.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gtwlxcazhz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtgcxcslav.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gtyrmdomae.html

f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtnunsfntt.html

[U57] PHP：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtityfzgqj.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtvynxhxvw.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gtswetqxdo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tianlin.xyz/Article/details/gtcrqitzph.html


<!-- 参考信息 -->