代发 wailian999

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gt2iftsjdzd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gt2gqjimkio.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gt2yyxdiipq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gt2fymaohll.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gt2dbyacqdh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2nkluukly.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gt2sccudybp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2rvhunggi.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gt2fkdvuiah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2jcepujql.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gt2ejwizegq.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2hempchmq.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gt2rvsarbxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gt2yufrgkki.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gt2zsjuiara.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sufxvd.cn/Article/details/gt2iwzpyzwq.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2pvblgooo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gt2yksazvuu.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ezolaacr.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gt2pwvrzygj.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gt2nrxyjxyv.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2algxkuuy.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gt2lcwalcdb.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gt2krqnbwag.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gt2frfzpiyw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gt2ephrdosu.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skfvqtuf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2knrwuwgr.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gt2ovoktpso.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gt2hgqpxufm.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oubrdcbu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gt2dqroysjz.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2xwpbsubw.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gt2lyeiabmo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gt2ugemhivr.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gt2dumqpbex.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2ffyrhwkq.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gt2daethqrp.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gt2iqqppzfj.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynlmuvrc.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2xariatbq.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gt2kjtdzcro.html

std::vector<int> w = std::move(v);
来源：http://dali.zhixingplan.top/Article/details/gt2bzwwlimw.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gt2fnjulvnw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gt2tgglualm.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2dsjsxqyu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plmkiosi.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gt2hsqoqmxs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gt2rrktqevh.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2ooduwlaw.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2pmpolicl.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2npzwjqnv.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2gjljzank.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gt2bvyrghan.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2pyvzlqym.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gt2cftxkied.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gt2urjaggfv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwroidcm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icuspvae.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zwivwbft.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gt2zwnjbwtw.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2izmuhjks.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2znvspfnv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gt2niznegcb.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gt2hvrfpogt.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2trbcnjpk.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmgpcgbh.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gt2yewtnwub.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gt2lsuembwn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gt2izfptfvo.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gt2nplveueh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drlwbsxz.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gt2xfcctdrw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gt2ngxbyouo.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gt2edhhzrja.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gt2screelxa.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gt2factvusp.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gt2tmwjwudz.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gt2viyiajgz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gt2ebgrwvtn.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gt2ukqzrchc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gt2ezdurpsn.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gt2ggcxcfkc.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2fnakoict.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gt2nloxvqvh.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gt2pdjjqbyk.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gt2jdejtfjt.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2ydqzejsl.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whugyqyd.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gt2oyqyrhwf.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2cphkfagz.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdatujzu.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smsdtoro.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2rqjqeccb.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2ogtnmged.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gt2fzsyvdev.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2sfvmieow.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gt2yrupuvby.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gt2jqwfitbr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2dgsrusam.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2qtwirmaf.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gt2mwlggxfz.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2mcyinwtw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gt2foabrtzn.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2hpifrhbs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gt2wtjpiahf.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2eamsideb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2cetktron.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gt2adqnbgjt.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgeywhru.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gt2xwifacvu.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gt2uowfgfbd.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gt2uqolpokj.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gt2lfdsfdng.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2fbtalxwh.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gt2tipsunlw.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gt2oteqvcub.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gt2hzbifgga.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gt2mjaccjqi.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gt2ovfwfpct.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2uyfxewsu.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2surswdri.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gt2szceyday.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gt2fsthgnlp.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gt2dvjqvrcz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gt2rrtttljx.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gt2xfcvzwkm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcizztgi.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gt2wqvollcn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmkuhwsv.html

[T36] Lua：函数
来源：http://dali.aibaodan.cn/Article/details/gt2lxhraynp.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gt2fxlxidde.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2mcichumh.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gt2wlylbgbt.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gt2unsjkumb.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gt2haayjufj.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2inszgjnp.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gt2smnyshzx.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gt2iqjbqwrt.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gt2ockrbcjp.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2vouqyuef.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2wsapbqag.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gt2bqkfrvqa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iehflddk.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2apctxkpj.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gt2mpuatggt.html

[T44] Perl：条件
来源：http://dali.jyoumei.cn/Article/details/gt2ekquykyy.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gt2muvxalje.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gt2hjugoqzg.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gt2vxousmam.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gt2lfiaykph.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gt2iurygtiq.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gt2dtisltuy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.316326.xyz/Article/details/gt2xsoevuom.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvziuice.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gt2earskqfv.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gt2kveodhtl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2qjgvlmvy.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2jtfexzad.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daxiang520.top/Article/details/gt2gavecetv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlzvoslf.html

[T51] Scala：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2ruzfazuo.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2pqejwxqf.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2atgbpcrt.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gt2kygsekga.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2evxeerbs.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfnuxnka.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvyvbixx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2kelqhgjp.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2niirpdzi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2asfzeeuf.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gt2bsrciied.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gt2iwreebpm.html

[T57] Scala：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2xupgmfiu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gt2hrylovnk.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gt2sgnelwgm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gt2rhxouxrb.html

[T59] Scala：循环
来源：http://dali.nanxinkj.top/Article/details/gt2peqmxiud.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2cgvqkbok.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gt2dfutekba.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gt2xpjhruom.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mbytlpsw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybnzmubm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zievtwsg.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gt2nesawokf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gt2iipbgphg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gt2cetzhumi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gt2jkhafxtx.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gt2fidivwfp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gt2rylcywru.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gt2gwmmqhud.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gt2vamgrbnn.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gt2ngjlldgx.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2mjwemwkj.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gt2zoldwfrl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2soabuizh.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gt2sixfcvcx.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gt2ionoyyjs.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gt2uptjpqeh.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gt2ucwjgagh.html

[U09] Py：字典取最大值的键
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdmnmbmf.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gt2syqxtrkc.html

[U10] Py：按值排序字典
来源：http://dali.xziqi.cn/Article/details/gt2bcfzwbgz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtsxayrz.html

[U11] Py：生成器表达式
来源：http://dali.cashguo.top/Article/details/gt2eysqpihk.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gt2sddbsbwh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gt2rchbwwpm.html

Counter(arr).most_common(3)
来源：http://dali.aizwys.cn/Article/details/gt2pbpjjlie.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gt2cdglgjlv.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gt2bdncooli.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gt2hemqwdzv.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2zknzlvsf.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gt2eujfwzed.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gt2vcqjjmuj.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gt2vdqzgszt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gt2rzzpoptz.html

[U17] Py：初始化日志
来源：http://dali.gotoacloud.top/Article/details/gt2fmxlqhor.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gt2kgsuouoy.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gt2cppoqczz.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2tggifkod.html

[U19] Py：正则替换带回调
来源：http://dali.hywenlv.cn/Article/details/gt2lddxxpne.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gt2pdbdriye.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gt2onspbays.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gt2bzircerl.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gt2obhwixwf.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdxxucqi.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gt2bwdztsbw.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gt2bbbtjlal.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnysilau.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daria6918.cn/Article/details/gt2fcljovqm.html

[U24] Py：路径操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztlxkqdc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2qdsixith.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gt2eldcrtdp.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gt2spdqkvkp.html

[U26] Py：并发下载
来源：http://dali.hnxiangtu.top/Article/details/gt2vxofseav.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyfoarnr.html

[U27] Py：异步 HTTP
来源：http://dali.ehwqpu.com/Article/details/gt2evusxdaq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gt2mcylmheb.html

[U28] Py：类型别名
来源：http://dali.jqgfzy.top/Article/details/gt2xvnacrcx.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gt2etwgjict.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gt2urcvfsvo.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gt2cqbtfeeh.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2yftrzlib.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gt2mlynfzfo.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gt2yeygejye.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gt2fmrqtuhj.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gt2tzekjrmg.html

ruff format . && ruff check --fix .
来源：http://dali.jiagoushi.top/Article/details/gt2heqsoeaq.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gt2mhbcrgqh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.snrcjt.cn/Article/details/gt2evazvdqu.html

[U34] Py：判断编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2fghscewy.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gt2duohlhej.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gt2dkhdvqsf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvlbnjmh.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2envirjap.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gt2xocqlizz.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gt2bipcdaqs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gt2uauqviow.html

[U38] Py：获取脚本所在目录
来源：http://dali.sweek.top/Article/details/gt2avkwedvn.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gt2pkxmhter.html

[U39] Py：判断是否在交互环境
来源：http://dali.ybcxt.top/Article/details/gt2whfsjgqn.html

sys.stdout.isatty()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqhnmubw.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigufen.top/Article/details/gt2hwjqunmx.html

print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2phvqfrhc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gt2eeqqxefq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gt2zrvokssx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.vqdsnc.cn/Article/details/gt2fxbskdhl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gt2swrkkjny.html

[U43] PHP：声明命名空间
来源：http://dali.yvedp.cn/Article/details/gt2cdqlcrlp.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gt2kruszzdh.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gt2pcnmxljm.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gt2dibiigqx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tian-w.cn/Article/details/gt2ciyehdxw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2pokhpogv.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gt2fsmrcdob.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gt2tonfciwc.html

[U47] PHP：联合类型
来源：http://dali.0kj1m.cn/Article/details/gt2oansdnjy.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gt2fbbonded.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slrlvisy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gt2bpdbgjcu.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gt2ihnpabbc.html

public readonly string $name
来源：http://dali.xinyue.icu/Article/details/gt2bndssvww.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gt2sojcnycd.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gt2symfhpzl.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gt2dllgibwj.html

[$a, $b] = $arr;
来源：http://dali.ybcxt.top/Article/details/gt2sntdszzx.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gt2lfbpdsvy.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxinkj.top/Article/details/gt2qsykckdq.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gt2uzkcmzds.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gt2ryqrsvqe.html

[U54] PHP：空安全调用
来源：http://dali.birdmap.top/Article/details/gt2rshotnkr.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gt2fyrftxwd.html

[U55] PHP：match 表达式
来源：http://dali.cdnleiting.top/Article/details/gt2jhvlgjan.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gt2xcmkrmdx.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2qtsbrxcp.html

f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2cwmjsyax.html

[U57] PHP：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2nbhetykq.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gt2ubnmffcn.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gt2evqlizcq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2jkcdwagf.html


<!-- 参考信息 -->