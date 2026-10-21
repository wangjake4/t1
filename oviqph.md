代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtrkaweeqj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtzquplouv.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtiwmrnywz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtglsygkue.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtuelscyma.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gttjpwknjy.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtmhdkrgdd.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtgufcdvkh.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtfzrdnkwe.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtglhwfheb.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafbljmgc.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gtckawfpyx.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtucommrut.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjbcmwpf.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtlovlokjt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtprzpakjq.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtglserycq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gtdlkepslr.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjwmoknnw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gtsbpstdcc.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gtmjwmkewm.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtelahcxou.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtcxyabkrb.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtthwqevsq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtcjvjbpok.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtqgebavwu.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gtfmqyigwt.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtgbcmogxn.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtisgjphrw.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtsiysczvh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvueqapik.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtpbplnsah.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtuabqqhdq.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtyovuxoki.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtqemvtkrk.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtuiebvtgk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtiwbiknor.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtbajqkgvr.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegjbivus.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtdrkxojpk.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gttlharugn.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gtpfgaqitk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtrguxupqt.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtdtarzrnk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhsdkbht.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbwxmpfeb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtgdaykwbt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbebgwdpf.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtzrfshyka.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtfuowekhs.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtycahfhcg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gttbxpqank.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtzhzywymf.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthhrkibo.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gthjsuvmnb.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtmkzyxemr.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtirfjwegi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtgrmmsqla.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtlrpqdlia.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkthgbiw.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtlzlwnptf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtxtgylldq.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gthloeadpq.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gtcxqjepzo.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjkqvndp.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gttouyfwye.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtetfdeqyc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtqjhthjxk.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnolnbcja.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gtfzvrghmd.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtcshqksyn.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtnjkgiskm.html

[T13] Kotlin：只读 Map
来源：http://dali.0kj1m.cn/Article/details/gtzvgbjxds.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtigfsrger.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtlifeomyj.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtiutnhdjq.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtjahjpqsl.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258888.top/Article/details/gttbpippdg.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gthetqqqip.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtafacmrxx.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gtwwznuyrs.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gtzfgxobie.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtiquwtzgi.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtkoxicbyp.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gtvazphnop.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtqfdtjbnf.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtuhmoyijk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtapxcjorm.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gtxslmtvci.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtlkndacjx.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtxdcdrvvc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gtkfwolgjk.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtvodpxtig.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtovylkfyr.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gtvrpkiywg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gttplkxrqn.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gtxzvwatjk.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gteygaehhx.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtkglondix.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gtahngdzoe.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtzyjcekqh.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gtbyngcbnr.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtlszbhwnn.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gtffizucll.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtrusodxrn.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtrjpaqfbw.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulkajwrh.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gtdsgkjdky.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtpbflcpte.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtjyvgxjia.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtdxarzhsz.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gtffyitlwe.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtrjftgheh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gtwdbbgmfe.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gtuflwinoz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtasfiikif.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gtlpleyehw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtcmpfhwci.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gtvusuxbcm.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gthzawomjf.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtneqwmzrl.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtyvnyntxx.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtlrphasil.html

if x > 0 then print("正") end
来源：http://dali.jinghuilouyu.cn/Article/details/gtksrsptas.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtfpycwwrw.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gttyjufelx.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gtuvootlsh.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtksdwtttq.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtuskfbxjz.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gthkinfacf.html

[T42] Perl：变量类型
来源：http://dali.yuanzhike.top/Article/details/gtppoofufl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtzblxuelp.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtezisixof.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gthvhinpvl.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtaexwerwi.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtrhdhsimt.html

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gtvdbvmtmi.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtgktgkmnm.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtbesjcntd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gtossipolx.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtsjuumyqf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtabpvapwv.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtgpaupvxp.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gtozbzoeoj.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gtndjwezht.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtqmfvsmtj.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtlfbnatxc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtmncyhxdz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtzyqfqwty.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtdpldxeqi.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtevpkvcjq.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gthxynwmuw.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtzqnojiti.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtxzocbcqy.html

s"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtrjnnobih.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtahaukxhz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtkosgqquw.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtgtgcagao.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtvxmmopda.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gtqnzmpmwc.html

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtzptazyad.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtrmltxteh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtdairavag.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gtwprdqnoi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtbocfszgc.html

[T59] Scala：循环
来源：http://dali.chenzaomai.com/Article/details/gtwdwyoqie.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtmqesmvcs.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtsxzdzgzr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gtnqrelocc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcvwutwoq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gtwraqgzsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtauandexo.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gtmdwndvot.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ivvv.top/Article/details/gtyyevprgf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gtlwbtdvms.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtjrroiusu.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtmwcuevxw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj202588.top/Article/details/gttnolyebp.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtbdfwuegf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gtajdsvhvw.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtuwpposlz.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtaiyswrra.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gtoeicqstd.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtrnazfwap.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gttxyoywqy.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gtzwrusoje.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtzkpfrmpa.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtmqgokohu.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gthqsnipbc.html

max(d, key=d.get)
来源：http://dali.nanxuanxn.top/Article/details/gtouqchogq.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gtmdscjboh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtwnjamlnd.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gtouvthhgk.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtxbhxsklb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gtxlaixdij.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gtjktezpmx.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtjcfbubdv.html

deque(maxlen=10)
来源：http://dali.0kj1m.cn/Article/details/gtxlmfbata.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxertonu.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtqfgvzkzj.html

[U15] Py：高精度计时
来源：http://dali.jiagoushi.top/Article/details/gtzyjkxqge.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gtwcyoncsm.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gtdvsfhxve.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtzlkubktb.html

[U17] Py：初始化日志
来源：http://dali.nwbrower.top/Article/details/gtpqjwgdfv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gtzqqghocq.html

[U18] Py：预编译正则
来源：http://dali.jyoumei.cn/Article/details/gtppcrhdmr.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gtlmgsqkxa.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtyxvrmkgb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gtbhdrmkgr.html

[U20] Py：缓存函数结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtupxtag.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gtvdqdjebn.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gttvhtdcan.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtmxzjsmzu.html

[U22] Py：矩阵转置
来源：http://dali.yvedp.cn/Article/details/gtwsbfxzxb.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gtwqaxsacx.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gtaiiquzre.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gtxybepduy.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gthyzcgqxx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtlixwpwvm.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gtupxermmv.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gtvdzekkkn.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gttzfesuab.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtngiecqbb.html

[U27] Py：异步 HTTP
来源：http://dali.hongshengwenyu.top/Article/details/gtemlzybfr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gtgrlcogkt.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtbhlzxwsd.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gtoibhkilt.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gtugngnpkl.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gtospoxdnd.html

[U30] Py：数据类
来源：http://dali.yongpay.top/Article/details/gtiryvuhqt.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gttaufcqfn.html

[U31] Py：单测
来源：http://dali.zycfv.cn/Article/details/gtulsnqwwy.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gtzwhhtngp.html

[U32] Py：代码格式化
来源：http://dali.shzxlz.cn/Article/details/gttdqefpej.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gtaboxazfj.html

[U33] Py：打包发布
来源：http://dali.0kj1m.cn/Article/details/gtexbsasoc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daria6918.cn/Article/details/gtrqxquuus.html

[U34] Py：判断编码
来源：http://dali.meibo888.top/Article/details/gtnebhtngj.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gtfbdavzxg.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbfbists.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yongpay.top/Article/details/gtlowtzlba.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gtvtkbetqe.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gtjotgprji.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gtchhdzrxd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.316326.xyz/Article/details/gtygwshpna.html

[U38] Py：获取脚本所在目录
来源：http://dali.gotoacloud.top/Article/details/gtqbettjhn.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaugrjmik.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gtqqemregv.html

sys.stdout.isatty()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcqjgdwe.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbafduquo.html

print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtwoogwwou.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gtrnbakfwi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258888.top/Article/details/gtchglrtld.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gtwievhmsh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cqqwz.cn/Article/details/gtsdxwvomw.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gtpjkgmcmm.html

namespace App\Http;
来源：http://dali.xylfe.cn/Article/details/gtnmhjtizf.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gtqlxivtfd.html

declare(strict_types=1);
来源：http://dali.aibaodan.cn/Article/details/gtmwccuecr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gotoacloud.top/Article/details/gtggnwbmwe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtmcjpslds.html

[U46] PHP：可空类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymhltkjf.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtpmxrhgif.html

[U47] PHP：联合类型
来源：http://dali.mhx1999.top/Article/details/gtiedoojaw.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gtapxrhhhe.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gtyfdsniet.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gtflepyeuq.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gttiuvhshe.html

public readonly string $name
来源：http://dali.sufxvd.cn/Article/details/gtlspinrkd.html

[U50] PHP：构造器属性提升
来源：http://dali.svipenyu.cn/Article/details/gtasmezlud.html

public function __construct(private int $id) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfxkeqgn.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gtloqvwqfr.html

[$a, $b] = $arr;
来源：http://dali.ehwqpu.com/Article/details/gtkhoddfrh.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtvjrdngxg.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtfcshlrxz.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gtwomewbxw.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtgxmyrmyy.html

[U54] PHP：空安全调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoqummii.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gtvdkgjgbd.html

[U55] PHP：match 表达式
来源：http://dali.svipenyu.cn/Article/details/gtkccjfwra.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmyhijsv.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtlqrjoapz.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtucqnptyd.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gtnkhlhcxo.html

"值: {$a}"
来源：http://dali.birdmap.top/Article/details/gthqbpbrjt.html

[U58] PHP：数组三件套
来源：http://dali.tian-w.cn/Article/details/gtanlphoqg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlizhdpho.html

[U59] PHP：自定义排序
来源：http://dali.zhixingplan.top/Article/details/gtcfbmbqex.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtirfvrrtc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gthsxrusdq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgufenzy.top/Article/details/gtjsvdyoqq.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gtsuionwxz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtzrvjauqq.html

[U62] PHP：日期对象
来源：http://dali.shuidangran.top/Article/details/gtsddjvylw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.smart0.xyz/Article/details/gtwyjvtaak.html

[U63] PHP：文件读写
来源：http://dali.aibaodan.cn/Article/details/gtjnmsfjiy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gtcitrrfgz.html

[U64] PHP：目录遍历
来源：http://dali.wangdashe.top/Article/details/gtkrgkohel.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cucudq.cn/Article/details/gtdzplvewn.html


<!-- 参考信息 -->