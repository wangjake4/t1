代发 wailian999

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gt2smqeexqg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2flsqetlr.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gt2blgtyief.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gt2txtuwmlu.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2grjhitud.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gt2owxsnrlc.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gt2ctnraedd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gt2siaufcft.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuioxrzn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gt2qtrdnjqk.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gt2fcarbjbj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gt2vjvnkpyh.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gt2lbvnnvzd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2vgyqyjid.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uevdsjcv.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gt2qearrovs.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gt2nydyrtun.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2mnzlxslu.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gt2eyelmttc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gt2bvmfxhln.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uszborlc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ufhfroxm.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2ymrbfojd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2eqnzdvzg.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2ujdtrzpa.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2zoxaqozf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gt2neokolte.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2eyphsjea.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2eirlwbiy.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gt2orwjyxht.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxadepit.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gt2vunamlpn.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gt2udexsnwo.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gt2atdldwml.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gt2morkxirs.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gt2xupsyqhy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gt2gvkkmeui.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npvgafeo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gt2ijwgxssy.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gt2lzpbqsgi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2jmdlqlzx.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gt2xpletggr.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gt2ylkcgztq.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2nsgwvugq.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gt2zrwwkpof.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2xqjmfvcr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2ztukrhgh.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gt2ftiywxjk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2butvduza.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xaavihij.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2hvxibdll.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2rogvnnpq.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2vvsizwjj.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2xdnwziub.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfqbsbdi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gt2lzlwsdcz.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpplayfv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uokxufls.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kencjpsu.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gt2ozjghrex.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2cdcfjtxw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gt2hcnrgara.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gt2sjhywpzj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2kznpfyuv.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xayvdawv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gt2trclvwhh.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2rqskgewa.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2fjwlmesl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gt2mgstfblb.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gt2mhfdifnl.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gt2ubuxijsq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gt2hkogrdcs.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gt2nclckclh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2catdnqcx.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gt2hnohmwye.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2rauideug.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gt2fhgvpvcl.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gt2yjetgetk.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gt2hudwomop.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2jxarvowd.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gt2qqpnzaat.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdywumuw.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gt2tksdnuxr.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2kthxvmox.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gt2hsvbgxcj.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2lrnrfetc.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2xzailfjc.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2yfexrlew.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gt2kflqegoq.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gt2xqjhzfet.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gt2rnmeoslj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gt2ofxwyglg.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gt2uimwerwi.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2xonjrkvp.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gt2zlfpskty.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gt2ryxlkmsl.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gt2ntqzjuaf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2odjacqdl.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfeczsrm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2kvidyenq.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gt2xksvwfxk.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gt2imeyijgs.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gt2mqgtaeip.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gt2snzogisk.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2jlsvgzyn.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gt2ywpmncjh.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gt2mkpoagrv.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2ibnjjleg.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gt2aomabnxn.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2xdgsewpb.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gt2avwzljlj.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gt2hqrqmpuq.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gt2hpfippbg.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2kkbomokg.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrgluzpk.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gt2vzwzcngm.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gt2sztmaepi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gt2cfvzxqbt.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gt2cfvwiedf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gt2mvwnnted.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gt2gdhitzad.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yongpay.top/Article/details/gt2mggekxac.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gt2cuboxtts.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gt2fobimwys.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2xkibuixk.html

"a" .. "b"
来源：http://dali.ydzc1.top/Article/details/gt2tbnontaw.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gt2wemlwngh.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gt2fibybicb.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2fbewzawu.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2fnioedoz.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elryxcrq.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gt2anzisswu.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2exwyliqa.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtpftlup.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gt2eerskweh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gt2kykvdwqn.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2wxxttiel.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gt2melfqmkn.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gt2bshmexgw.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gt2vxvrlxxc.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gt2nspochlm.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gt2wqkdceyg.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfsrgsbp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tpedpxph.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gt2iomtyzbk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2eshcxhhs.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2uoicczqx.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwtghipa.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gt2vcbslmze.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvnchbhg.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2gxtucbkz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.meibo888.top/Article/details/gt2nvhjszkt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.meibo888.top/Article/details/gt2ybctntri.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2ahumjzzn.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2dtztznol.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gt2sunrgwhc.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gt2ogecjjmm.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2dmyiqntd.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbezbnmn.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2gjncveoz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ydzc1.top/Article/details/gt2jajvljzb.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2sccinjfw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gt2satqgqyr.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gt2zweyubep.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gt2laufvrcs.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2dhzeifsn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gt2vpoihatj.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2rtdrtjrx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gt2uxubrhht.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gt2ropzmvak.html

for (i <- 1 to 10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2xqoxzqlx.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gt2iaglbxmu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gt2yawetcqs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfnsmare.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gt2edohxvjy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcgaokdg.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gt2tpoebxwi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gt2qsfdfjpz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gt2pbihprxf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gt2epklzqls.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2pkestpqh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gt2pqjsygqd.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gt2ffoartpe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gt2vikmwhxv.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gt2cdupferu.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2nhnxbhqt.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egqmoran.html

{**a, **b}
来源：http://dali.ehwqpu.com/Article/details/gt2ednrgtbx.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gt2mhdoxomp.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gt2jvltwamg.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gt2jyzneovw.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gt2whosmohu.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gt2wvngvwpd.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gt2eusqehuo.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gt2giwozrxh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gt2xlnkcjyj.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gt2iajdmygd.html

(x * 2 for x in arr)
来源：http://dali.316326.xyz/Article/details/gt2hvudqlce.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gt2yrjnojpw.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gt2itfoashc.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gt2fjflzzgh.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gt2bmvzccwg.html

[U14] Py：分组收集到列表
来源：http://dali.bjfxy.top/Article/details/gt2ipylndng.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gt2tdfqythy.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gt2uesswiva.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gt2wmncvumy.html

[U16] Py：命令行参数解析
来源：http://dali.chenlongwang.top/Article/details/gt2emaqzeww.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gt2qxnirema.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gt2uaezemro.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gt2crypciwf.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gt2hzvebkpu.html

pat = re.compile(r"\d+")
来源：http://dali.yonumen.top/Article/details/gt2dxzhrzeo.html

[U19] Py：正则替换带回调
来源：http://dali.yueranfly.top/Article/details/gt2prwojkol.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljpdbobv.html

[U20] Py：缓存函数结果
来源：http://dali.chenlongwang.top/Article/details/gt2rwixygrk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdkryiad.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gt2qgdmnnjg.html

@contextlib.contextmanager
来源：http://dali.gzhubu.top/Article/details/gt2lmehtzwb.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gt2ydvefzxo.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gt2ahzgtdga.html

[U23] Py：分块读取大文件
来源：http://dali.xziqi.cn/Article/details/gt2eqnnyxjn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.redwolf501.top/Article/details/gt2lrdnpxml.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gt2rwloxehq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2uebajskj.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gt2zbcafita.html

csv.DictReader(f)
来源：http://dali.yueranfly.top/Article/details/gt2zxxmzehs.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gt2cbkzsbbt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gt2fcijkjph.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gt2kfdmwssi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daria6918.cn/Article/details/gt2ybkfepak.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gt2izexalve.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gt2jyrrekfu.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gt2ohkguxye.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gt2svubnluo.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gt2qrtjnuqh.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gt2ybrsjsvv.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gt2tlyzlsra.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gt2tvtaznbu.html

[U32] Py：代码格式化
来源：http://dali.aibaodan.cn/Article/details/gt2kfdqcsav.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gt2sflcsepl.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gt2alnzgcob.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onisspwb.html

[U34] Py：判断编码
来源：http://dali.pycfn.com/Article/details/gt2mkclkgcm.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gt2lxcxnkoy.html

[U35] Py：发送邮件
来源：http://dali.fzhhl.top/Article/details/gt2plapnnkm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gt2odiloqhm.html

[U36] Py：定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyegamzi.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gt2cjpbjtet.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gt2tyibyisl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gt2xsjfpxlj.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gt2qhttbsue.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gt2aprcfbdr.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gt2adtlbbpy.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gt2szismrsv.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gt2ulfwwqvz.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2xdvmtjhl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gt2kacmhjgu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gt2vidynulb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gt2bbeqvzoa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.haohaochexian.top/Article/details/gt2qouuhres.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyradxoe.html

namespace App\Http;
来源：http://dali.zhixingplan.top/Article/details/gt2eeqsmkqu.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gt2lonpcvjg.html

declare(strict_types=1);
来源：http://dali.hywenlv.cn/Article/details/gt2soxuhvfx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gt2qlufrvvz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pmxwhyhp.html

[U46] PHP：可空类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2teriwgcz.html

?string $name = null
来源：http://dali.xziqi.cn/Article/details/gt2taajwppt.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olauudst.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gt2dkpbjpir.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gt2bqlrxtnw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vdmfkbss.html

[U49] PHP：只读属性
来源：http://dali.shzxlz.cn/Article/details/gt2ddkbknsy.html

public readonly string $name
来源：http://dali.zhongyouzk.top/Article/details/gt2cihikehm.html

[U50] PHP：构造器属性提升
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgynceyl.html

public function __construct(private int $id) {}
来源：http://dali.tian-w.cn/Article/details/gt2twmlhmdy.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gt2tznkbvwa.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gt2lqnuvcxv.html

[U52] PHP：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gt2qwfibhrg.html

$double = fn($x) => $x * 2;
来源：http://dali.daria6918.cn/Article/details/gt2mrraxvft.html

[U53] PHP：空合并运算符
来源：http://dali.havefunace.top/Article/details/gt2rfqutqmz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gt2poozfzou.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gt2gefjwykt.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gt2mstwherx.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gt2alwkqfgc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yonumen.top/Article/details/gt2ufnesiis.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gt2uztlrscw.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2gfyusckd.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxnxnyxu.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gt2agpohwyy.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gt2sdozfdzi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2fkkypinc.html

[U59] PHP：自定义排序
来源：http://dali.jianghu66.top/Article/details/gt2iaxzujxx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2yyaykjcy.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvhzknqs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gt2irvanqbj.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kruvgcsd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gt2pgnbrvns.html

[U62] PHP：日期对象
来源：http://dali.jinqigfzy.top/Article/details/gt2fhomjgaw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hywenlv.cn/Article/details/gt2qfawwcyf.html


<!-- 参考信息 -->