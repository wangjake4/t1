代发 wailian999

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gttribxluu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gthcdiijan.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtfutpuivs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtngikufeo.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtmyeozviz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtnqezcbzs.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtvjuxlhgi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdkfhgja.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtshxxvtdm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtmnwxekfy.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtnduwgsnl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gtifpkxbzw.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gtiemihdco.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtkndazjgi.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtvwbxnvvq.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtkbmtwpac.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gttpcsmfhj.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtwcoghkop.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gthstrlekx.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtzqkmzcls.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtychsurcj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtmwqpjeqs.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtfdroytjo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtkrpbsrrk.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxrqdvso.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gtykbcjpta.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtoxzgyufn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglectrpf.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gtsjjtnnfo.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtitwyockh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtyqlzgvdb.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtkthllylp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbmovbix.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gtwxrxegck.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtslovbxry.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtcptmqigs.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyahmcjrb.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtbrfqdxuk.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gthwbhqtdb.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtzfnhqsty.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtxnxosxnq.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtwagzuzav.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtlbhhyjnv.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtohwepfcx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gtunqvxkrn.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtymobygjm.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gtpxxohjlo.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gttxcxymxj.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtapgjaxcp.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtztgyamid.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtlytaubhm.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtipcsiicu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtqhtidyfi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhatzjud.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtbbrwrpnn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdfnhsgvy.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtzwqmbsbb.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtpfnwywaj.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtwcgpygxc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtoqlbviie.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtjsmgxnjb.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtakomhgot.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtdfyanhnr.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gttdjkuqhi.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gtllyotkdn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtcmhqggbv.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtoqvsoktv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtcqbufzqd.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtpzrqsazl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtvjcbnonz.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gtoufzjuxd.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtltvrtcxy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtfprnwrom.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtqgsjwrzb.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtchncfzqo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gtqajctpys.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtxdpwmrul.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtpavaddye.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtecuqrrgg.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtmtjbfhpc.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtfhvplfnx.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gtyiclvjzc.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gtelclfoed.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtqgvtrdel.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtcxweoynj.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtwczwynme.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtbvcroblo.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtdvugfciw.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gterwsmqmk.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtkulydhbo.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtubpssgwe.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtmlijomox.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gtqurecyga.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtfceegncc.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtkjktisth.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtapdlixlq.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtxtpvmhxe.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gtqjtttbcs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gtgyhflhsi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelspuook.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtxuwxtpdq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtgcrdqbcj.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gttogtqsaj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtwmyqftzn.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtgllmsigu.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gtlrhksqmk.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gtotqcqqyr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtythixkwj.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gthcbfigir.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiqghvwo.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtpryyiiqh.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtavbebxbe.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gtjlvstahv.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtmhkywojx.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtyvpfdmdl.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtzhlqqunk.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gtsdvbqoam.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gttbdswosq.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gtsinylpgs.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gtkmqfuata.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtnmcyfaxr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtmfbtrgjx.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtwihjjowp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gtqkqnnwsm.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtbnlnijbc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gtwuzlgklt.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gtmwrmywjj.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gtrioijzbn.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjapbrfm.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtmrcmzrln.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gtfhbzhqwe.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtbgzsvnjg.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtigljsthi.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gtnnfmxock.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gtfunhafmp.html

setmetatable({}, { __index = base })
来源：http://dali.chenjidiqi.icu/Article/details/gtyftspmzj.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtushiquuc.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtbsrvrcuc.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gtkuiaxgum.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gtrhofmmpw.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtzniqqbcz.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gttrbjzscf.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gtkhansppw.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtgnxsumjp.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtnkufwxxu.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtkhecrbpd.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtliazbnkp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtcnqyqqrl.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtxmcveeme.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.svipenyu.cn/Article/details/gtdfijocac.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtsdremhcg.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtwkpaguep.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gtdjykysjy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gthgdfhkjc.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtnjpqlhrz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtvmgztxiu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gtxnwtnsjj.html

[T51] Scala：Hello World
来源：http://dali.yj202588.top/Article/details/gtddicubyz.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtkeqdehmg.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gtusiqdmpj.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxnlolxu.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtlmqdqxiz.html

s"值: $b"
来源：http://dali.ivvv.top/Article/details/gtkjkuclyi.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtahpiryzy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gtqjyurkos.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtvglmdwji.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtyqlkpjai.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtaxqgiqll.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtruvlqfol.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtjhzuyrjv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtjhogtowj.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gtodzbmozl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtzhqochtd.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtxwrewykp.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtvhdhqfib.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtilxourcf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtzgbfpudz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgrsloxzq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtelanetpb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtavizgufe.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gthsnnljuz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gtynhsehkj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gtlibipmsx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gtlmjjozmn.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtqjvfkanp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yueranfly.top/Article/details/gtngdkxvho.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtfsiszlwi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtyfbhqwla.html

[U05] Py：列表去重且保序
来源：http://dali.jqgufenzy.top/Article/details/gttoomjeho.html

list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtidfutkoe.html

[U06] Py：合并两个字典
来源：http://dali.0kj1m.cn/Article/details/gtduorvhnx.html

{**a, **b}
来源：http://dali.9152youxi.cn/Article/details/gtmimalmgv.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtstekinje.html

{v: k for k, v in d.items()}
来源：http://dali.jlsjyb.cn/Article/details/gtmelsicrz.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtbatovjui.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtruezcrpc.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscyovukb.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gtltikvquf.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtvwdkwlmy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gtffpwtdzp.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtbtnatmbc.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gtsomxdrpb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtzuxkgdax.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtkmrgrthl.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtfgoovbdn.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gtouewpiou.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gttmftpwal.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gtedznonfy.html

[U15] Py：高精度计时
来源：http://dali.sysykeji.top/Article/details/gtxauzqdwt.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtgzrhgwkm.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gtgkmhfecz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gtutyyopgh.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gtzamkmfzm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtjwmztnlg.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gtdvthbnrm.html

pat = re.compile(r"\d+")
来源：http://dali.shzxlz.cn/Article/details/gtqunlmvvy.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtteqphpgr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gtiajecgjg.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gtemgxccpx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gtvikkdgif.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gthnmynypn.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gtzfavoxsp.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtioafqbjv.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gtihcjltwh.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gtrcdzglgz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yanxiufei.cn/Article/details/gtewklquui.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gtyugcfqrr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtfcxnexyv.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gtsipitxmu.html

csv.DictReader(f)
来源：http://dali.zhoulong.xyz/Article/details/gtljbwtggz.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gtuwdcbxlt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gtsgkaaakz.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtzmtdemcq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gtvbtzoxkc.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gtewiwkyqs.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gtkyqceoxd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtxsdguwij.html

@property 与 @x.setter 配合
来源：http://dali.pengpengdd.cyou/Article/details/gtzckbsuen.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gtyylvibvz.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtussyfeay.html

[U31] Py：单测
来源：http://dali.svipenyu.cn/Article/details/gtlyhrtzlf.html

python -m pytest -q
来源：http://dali.9152youxi.cn/Article/details/gtwghcovrh.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gttnamnmpa.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gtvdamrohe.html

[U33] Py：打包发布
来源：http://dali.cqqwz.cn/Article/details/gtnxrkwuqy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.redwolf501.top/Article/details/gtdddhitbm.html

[U34] Py：判断编码
来源：http://dali.zdqjudy.top/Article/details/gtmshsvymr.html

chardet.detect(raw)
来源：http://dali.c1oappe.top/Article/details/gtqnajrikb.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gteszfaktw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gtbunqlror.html

[U36] Py：定时任务
来源：http://dali.yangfankeji.com/Article/details/gteeqvwvhz.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gtmcztccca.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gtusulmqmm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gttkoslppi.html

[U38] Py：获取脚本所在目录
来源：http://dali.yvedp.cn/Article/details/gtcurvcuwu.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gtehxxsomz.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gtxkoabmaz.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gtyuyrnfhu.html

[U40] Py：打印到标准错误
来源：http://dali.ivvv.top/Article/details/gtwzzocpgb.html

print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtfzkmqzjt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.bjfxy.top/Article/details/gtjwhkopsl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gtrhjoyuyp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gtzpebnsql.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhiwuduotai.top/Article/details/gtpxohutwy.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtqzyipwcz.html

namespace App\Http;
来源：http://dali.guannengcc.top/Article/details/gtrrxcovsf.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gtgnlopzyt.html

declare(strict_types=1);
来源：http://dali.0kj1m.cn/Article/details/gtualshcok.html

[U45] PHP：类型声明与返回类型
来源：http://dali.havefunace.top/Article/details/gtzsqlasfd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtnlwgmzli.html

[U46] PHP：可空类型
来源：http://dali.daxiang520.top/Article/details/gtxacibcme.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gtfvhpbjmf.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gtgsusfxhy.html

int|string $id
来源：http://dali.cqqwz.cn/Article/details/gtcjfsmziz.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gtpvxpmwlt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyvwfnbqi.html

[U49] PHP：只读属性
来源：http://dali.smart0.xyz/Article/details/gttprmgwns.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtwkestalp.html

[U50] PHP：构造器属性提升
来源：http://dali.yuanzhike.top/Article/details/gtcxjgjxvr.html

public function __construct(private int $id) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwpmrajit.html

[U51] PHP：数组解构
来源：http://dali.yongpay.top/Article/details/gtrrmoernk.html

[$a, $b] = $arr;
来源：http://dali.ppjwa.cn/Article/details/gtkayhmvxr.html

[U52] PHP：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtfpqqtvpy.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gtsnabxwdh.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gtyaxjkigo.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmlgfrha.html

[U54] PHP：空安全调用
来源：http://dali.zdqjudy.top/Article/details/gtafsvwdfg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gtjxghsrcj.html

[U55] PHP：match 表达式
来源：http://dali.yj202588.top/Article/details/gtytweydtq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuxming.cn/Article/details/gthtpcqmvh.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtlntytwfe.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gttpbzsdks.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gtjbqwcxqt.html

"值: {$a}"
来源：http://dali.nwbrower.top/Article/details/gtpuzpfpbq.html

[U58] PHP：数组三件套
来源：http://dali.jiagoushi.top/Article/details/gtebgqdnph.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gtzqmypczq.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gtjbibnolw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gttllcjkfh.html

[U60] PHP：JSON 编解码
来源：http://dali.hysaishi.cn/Article/details/gtzzedpgxv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shzxlz.cn/Article/details/gtianaqhov.html


<!-- 参考信息 -->