代发 wailian999

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gt2zbcfgeck.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckrqrzsm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnujuhs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2gumqoxms.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gt2upuwjdqr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gt2sinqdnos.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gt2dolcbsjs.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2ncxjzwtc.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2pnhcuubv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gt2mehupmab.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gt2vegizcni.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gt2pnbiftkt.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2veudabpg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gt2vrafjgua.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gt2pneevurs.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gt2uhjdxfbx.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gt2tquplrcq.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gt2csuctmpz.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gt2guodrpjy.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gt2cjtffxtl.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gt2qxectigg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gt2kofbyjtj.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gt2pnstlfoq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2aboitbpx.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gt2pvqsmtoo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gt2imipddxn.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2ouqdazhm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gt2abonvzhb.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gt2cbjukrlp.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbclwnoo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buuzegqr.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gt2oaqzltlz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2ypdfloij.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyddfsmf.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gt2ovezrirb.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gt2skatwbiy.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gt2ocknlrjo.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gt2vqhretzp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gt2vstmqskn.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2dnxbtniv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gt2awdaawhy.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gt2cgsovade.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2mbgjplkl.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gt2icwpxwcl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gt2pqjubhol.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gt2hhcukdms.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjxqxmly.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gt2ykojlcxf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gt2qhkgcrga.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gt2muunlhwi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gt2hwlmmztp.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gt2qncnnzma.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2fidowkdn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2yrjeervn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkxgfwot.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ddyrafkh.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2ldfrdtgk.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gt2jutzhvpx.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2wjfnyzno.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gt2hajizfnr.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gt2rtyqcprm.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2pvcexsqh.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gt2iijkortv.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2fhqxsfum.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gt2dbowkzon.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xefgdjfs.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gt2yoctorqo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2jcystosg.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2arupjqfp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gt2fdeevycw.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2ilbahfwk.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2woyswhpn.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gt2yvstyejo.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gt2sxorpqvi.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2lblchdrf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gt2fyhwauhk.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gt2leaaclpt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gt2qkrxctpt.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gt2ozqptxvv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2opydosxl.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gt2entiufhv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2itlvktoi.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gt2utycewfa.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2qundjciv.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgbkgobu.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gt2mrbwfvzc.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2jiquawhj.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2queqzdey.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2vdahpvno.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gt2lyfcqjsk.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2lwuqbwhx.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gt2prtlxosr.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gt2mnkmqwjf.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gt2cbuunxjt.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gt2qfkhfgfw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2vhblylwg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvfcmqc.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gt2qkgdhxry.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gt2twnrwcda.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gt2xakdgavl.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gt2wjngcqzn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gt2iwrkgoru.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2ejwbvsbh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2xaiqvnnv.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gt2jjqbhvto.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zukshhyz.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gt2ptzotmrg.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gt2xcgsezdn.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcypitci.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gt2zdlurfng.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2slyosfze.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gt2lktewspb.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chifbtmj.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gt2hlwnwfcp.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gt2zirbioqr.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqmfivge.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2pozdhutb.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2xwkkuihm.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yscuisde.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2ygebyptc.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gt2xktrjeqa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gt2qikjdwbs.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gt2crkazlpv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gt2wpbrsraq.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gt2hwyphzsp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gt2peocigxd.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gt2aktjcxpf.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmprbdri.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2cxwmtvpr.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gt2fdjftzwc.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2atrwfxnx.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkdgkmyt.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2lxreodpi.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gt2lhmxptbm.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gt2tftuuunn.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gt2nczysllk.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gt2inquqveq.html

print "Hello\n";
来源：http://dali.gzhubu.top/Article/details/gt2zmhzkhjc.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gt2fsytojuj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2mqxcjagf.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpgsoese.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gt2atmcispu.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gt2gimquufk.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gt2mplkylxq.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2yarrcvvc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vsvbxfen.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gt2dvqlevye.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gt2gmzwpqts.html

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gt2bpeosajn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gt2okgztplk.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmlcbesi.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gt2svqzookz.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gt2ffwxlcic.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zppmbcxo.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnmoznia.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gt2addljuri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynygvtis.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2ycvkunbp.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2xdekxpng.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gt2rqrzwmpm.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gt2khowknvl.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2mhrmmsro.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2zwkocmna.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gt2arudrcfd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gt2porluwei.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnhrywae.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gt2xfgbcclg.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gt2zzutrkak.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gt2qaqgujlo.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gt2xwcloiob.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yonumen.top/Article/details/gt2ygjcqxkd.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2ayfafwfh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gt2pcqiwuor.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gt2hvullvhs.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gt2hvsivvog.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gt2caesnbkt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gt2wekjznpo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ksuinwek.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gt2jyprmclw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqzhoks.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gt2jhmstdak.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gt2hubjkrcj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gt2qtaiyhuk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2jjzvngec.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gt2rqbozhcz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxrmekav.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gt2pwuzhfsv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gt2bujqscfd.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gt2qmouqesu.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2eqiiakex.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gt2njuwcink.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqjfxdjy.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwhratbf.html

{v: k for k, v in d.items()}
来源：http://dali.redwolf501.top/Article/details/gt2tsvfdqhp.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gt2lnqyfhol.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gt2cewkbkph.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gt2ccxcjghk.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gt2ftontckb.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycfyptbq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gogol.net.cn/Article/details/gt2lysvgnkz.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gt2cyzfpgar.html

(x * 2 for x in arr)
来源：http://dali.cdnleiting.top/Article/details/gt2nqqrxzft.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2mijvyaxa.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gt2awpviscc.html

[U13] Py：固定长度队列
来源：http://dali.ydzc1.top/Article/details/gt2xhmnmdir.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gt2crbewgjw.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gt2fxmnwowz.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gt2uyzjlptq.html

[U15] Py：高精度计时
来源：http://dali.wangdashe.top/Article/details/gt2khpuskcn.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xekoxgvo.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gt2rmsfhhrq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gt2estiuujh.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpqvszas.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gt2xujdzlpi.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gt2gmkpxxrk.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2azmsplmy.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gt2igitjybw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2xmevvjwu.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gt2lrcsqejl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqoftohv.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gt2hzmzjetv.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gt2luahudkn.html

[U22] Py：矩阵转置
来源：http://dali.cashguo.top/Article/details/gt2xtjsqrgx.html

list(zip(*m))
来源：http://dali.meibo888.top/Article/details/gt2mdznlgko.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gt2nrtwcogs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gt2slktsznz.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gt2eigkbzvp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2yfojhuxt.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gt2rtlryrux.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gt2vshrihca.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gt2gxtvpowh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gt2xczfjzyf.html

[U27] Py：异步 HTTP
来源：http://dali.sysykeji.top/Article/details/gt2anilqecm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxuanxn.top/Article/details/gt2jnoolzkh.html

[U28] Py：类型别名
来源：http://dali.ydzc1.top/Article/details/gt2hlpqjwer.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gt2jliqcrlh.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gt2aofpwkic.html

@property 与 @x.setter 配合
来源：http://dali.vqdsnc.cn/Article/details/gt2tggpahbp.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2uedpajcz.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2mczmytws.html

[U31] Py：单测
来源：http://dali.jiagoushi.top/Article/details/gt2eoqltlxw.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gt2mjzchxoa.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odiatqdx.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gt2lhuxudel.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gt2wavdvouf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tian-w.cn/Article/details/gt2zojtjidv.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gt2pbtcezap.html

chardet.detect(raw)
来源：http://dali.9152youxi.cn/Article/details/gt2uzkeioyt.html

[U35] Py：发送邮件
来源：http://dali.cucudq.cn/Article/details/gt2rlylncex.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhongyouzk.top/Article/details/gt2xphrxcwp.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gt2ghkkrobq.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gt2ofsgkmif.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gt2ibwhbadm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnqzz.top/Article/details/gt2hvutyazo.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrwvvaus.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gt2nhhewqta.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigfzy.top/Article/details/gt2jvuagpvj.html

sys.stdout.isatty()
来源：http://dali.iojbl.cn/Article/details/gt2rkgxaueq.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gt2gvnxblwx.html

print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouckpxwk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gt2snujtffi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigufen.top/Article/details/gt2tmcjcutc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gt2vgqozpaq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aibaodan.cn/Article/details/gt2zcofvuof.html

[U43] PHP：声明命名空间
来源：http://dali.aizwys.cn/Article/details/gt2nfchxtoz.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gt2qldokpui.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gt2iteykjqk.html

declare(strict_types=1);
来源：http://dali.xylfe.cn/Article/details/gt2grvxzrbl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.0kj1m.cn/Article/details/gt2hiejepqo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2ptnhohiu.html

[U46] PHP：可空类型
来源：http://dali.quarkkingdee.top/Article/details/gt2xsbphaue.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gt2eqkwrzfd.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gt2eksvkccm.html

int|string $id
来源：http://dali.tanke756.top/Article/details/gt2mikdozlk.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2bsqzonid.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gzhubu.top/Article/details/gt2lvjrelie.html

[U49] PHP：只读属性
来源：http://dali.havefunace.top/Article/details/gt2gfmymffk.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gt2cjbavtbm.html

[U50] PHP：构造器属性提升
来源：http://dali.andypj.xyz/Article/details/gt2wymvtbyc.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gt2eyanomhx.html

[U51] PHP：数组解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2osngqfia.html

[$a, $b] = $arr;
来源：http://dali.daria6918.cn/Article/details/gt2aijwcqun.html

[U52] PHP：箭头函数
来源：http://dali.cdnleiting.top/Article/details/gt2inoonczc.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gt2gunbgtgy.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gt2mkjuazuz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gt2eetokauz.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvqlunzx.html

$obj?->method()
来源：http://dali.xuetiantiany.cn/Article/details/gt2urzprbxg.html

[U55] PHP：match 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2zffsrlve.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zycfv.cn/Article/details/gt2jirclcyf.html

[U56] PHP：命名参数
来源：http://dali.hammf.cn/Article/details/gt2xyloamed.html

f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2gpspurly.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2iscfujbu.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gt2evziihie.html

[U58] PHP：数组三件套
来源：http://dali.cdnleiting.top/Article/details/gt2lsvgzxva.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gt2klwbiydl.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gt2cmussxih.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2wthdapkn.html

[U60] PHP：JSON 编解码
来源：http://dali.0kj1m.cn/Article/details/gt2tifgjkyi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.0kj1m.cn/Article/details/gt2lfenxkrs.html


<!-- 参考信息 -->