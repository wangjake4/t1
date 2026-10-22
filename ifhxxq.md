代发 wailian999

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtwxwtdoko.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphwfkujn.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtrbcuntpv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtpnlxztto.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtfqycrkyh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtojizjtfo.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtotssouqm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtvtfinory.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtshbczgfc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gtnadiqbpl.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtdismzxuv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtukpupmpm.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtvyjivrtc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtfxxardbb.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtjdaabwkf.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtfjobxrfj.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gticetrzkz.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtuvffqdpl.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtmntmxcog.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtjgfdtavo.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtzmsjrstq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gtqnuyyrqt.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtgsqlctkb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtyfyxhkop.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtuztvzgyi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtwkhtsqlk.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtamiqapvy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtsuyfttlr.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gteyhsvqio.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtdnspyuqn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtwbyjsciw.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtdbobgbxl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtvbgujmuf.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtayhryaja.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtzexaxnmx.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtqynmzwrr.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtbimycvea.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtfiwavnqj.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtyyuufqsv.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtzxdcciud.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gtyqagwmya.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtgdxtnkwh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gtxlvqdifs.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gtquojrhfv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtbliycdda.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtzcyjgdmz.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtnjnagtkh.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtkfgjaeqe.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrnzluho.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gtyydanqkp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtzkblygze.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtuttpzeap.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtedkfekrl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsvmpxvsu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtwuozrwac.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgbcrmkqe.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtxbankzrz.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtuhrhfouo.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtlyskmomt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtdzqdhhyc.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtgplqboxy.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtazovks.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtzcbrhnrz.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtkhhlptin.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtocixwtse.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtqgcfvzbm.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtctiryguv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtxaratgzx.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtulvhjzbn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gtasrebatg.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtddpgzimi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtivedehrs.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdcqqcal.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gtaqqdqhzu.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtnxgsddfd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtvgongzie.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gthpaurhgk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gtumfauqny.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtcxuzrxle.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtzkhevwvh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtchizqlpz.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtyryrtgma.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtbhzuspgc.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeprifqv.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtdgbrjquz.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtxiiemdah.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtcfdefblp.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gthznxizpg.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gtgpthxmws.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gtaofqfqgj.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtrkigduqf.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gtbkvkvcen.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gtpcyttvyi.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gtetprrezk.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrspgihe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtyavftwlc.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gtyxsufnhm.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtbizdlqco.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gtomlassdi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gtcpptfgbn.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtpvbxhtjc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gtukhjpoyv.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gtrdskpbxg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtvxylzwiq.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gturyzfgxa.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gtwsfrwgsy.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbymewwte.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gtxrsrrrsi.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtpyungmyd.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtipfaqhbe.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtbqiceraq.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gtkculobzc.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gtpmmpovlx.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gtiukmafiz.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtsopudcgm.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtynmnherl.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtyvazxydh.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtiizyrwif.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfvcfnyn.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtyrzijtsq.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gthdwmiqcm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigsfdvgq.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtkqysvjhv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gtwlvlrxle.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gtjjbniher.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gtaqforrun.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtsafhzwgb.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gttnnvazdu.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtoquzrkso.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtlvwfvjtx.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtuclxqysk.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gtunsdcfod.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtakxgwuqj.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gthnmlcehi.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gtqvuewmmw.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtehmkhdmn.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gtwpuhiiit.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gtnfckooyb.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtyyftfzhw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtgidgtqti.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtyrkznzxh.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gthrjbqdlv.html

[T44] Perl：条件
来源：http://dali.wangdashe.top/Article/details/gtuedyuksw.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtmtzpmlcj.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtcytctiik.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gthnpddbba.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjgssuda.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gtxjzmufsr.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioabqjph.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtmmsdfckw.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwqggmux.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gtmdmiappl.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtypgnvhfc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtvujdqabz.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtxcertvuq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gtblmssesz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtddrkvevj.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtxptrhcxb.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtixqchnxr.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gtfnlqhacz.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtkotwcpnd.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtacqsbvgq.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtqjjxvjdx.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gtfuhuhyzk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gtahouzusd.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gtvgldcenz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gtmhwqkjsg.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gtmixcnrba.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtqpeagnlq.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtgwpjoqqy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtimkdbfqa.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gtunrzzsgk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gttamtynyd.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gtrpxsmsdz.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtptguvmeb.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtmnwkmlfm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxxuoptb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcvefkkbb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtdmgbfimt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvgraphqb.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtrjjuwcwb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gtlieykpay.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gttlucqvtt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtflrfjtcg.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvmmdzzi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtaalwksiz.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtuvvcywyv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtxhikmxaz.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gttopnfhus.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtcqltelxs.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gtynpuysej.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtdxxtsbvy.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtkxqldped.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtmpibjtui.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gteaactsrp.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gttnyyajpx.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtagcivgnv.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmtwamcd.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtilwniyfu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zdqjudy.top/Article/details/gtpczuqnsq.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gtioltpiga.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtkwxxrqzs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gtuwgpfqrb.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gtxoljwhyq.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtsikkjewg.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gtwhonvqse.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gtrazkozhu.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gtskkeehcr.html

[U15] Py：高精度计时
来源：http://dali.hnxiangtu.top/Article/details/gtuientsyd.html

t = time.perf_counter()
来源：http://dali.hammf.cn/Article/details/gtafpygsbw.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtvalkhuqz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gthghfgwwy.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gthnueovrd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gtqaboqfri.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gtgtppupww.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtbeocaiyt.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gtzbtdlavv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gtkiystipy.html

[U20] Py：缓存函数结果
来源：http://dali.dashuyun.cn/Article/details/gtuuvkdoqy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gtrkbnxkuy.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gtyjxegiig.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gtbahkuepv.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gtcoaqypcy.html

list(zip(*m))
来源：http://dali.jinqigufen.top/Article/details/gtrcerfgby.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gtniwvwzvw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gtwvhjmrbk.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtyfmvliuo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtfbdfoljl.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfmzadcn.html

csv.DictReader(f)
来源：http://dali.andypj.xyz/Article/details/gtlgyfndqq.html

[U26] Py：并发下载
来源：http://dali.havefunace.top/Article/details/gtvcpkwgvy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtdzqvtlxs.html

[U27] Py：异步 HTTP
来源：http://dali.tanke756.top/Article/details/gtbmxozpbb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfemjysmb.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtpihxppkz.html

UserId = int
来源：http://dali.0kj1m.cn/Article/details/gthvqefrkc.html

[U29] Py：属性校验
来源：http://dali.guannengcc.top/Article/details/gtoqvengru.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gtfglfxufz.html

[U30] Py：数据类
来源：http://dali.yangfankeji.com/Article/details/gtdmtrnlrq.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtqvrbfvzi.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gtjaukodzf.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gtrlqefrgp.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gtpxerinlb.html

ruff format . && ruff check --fix .
来源：http://dali.wangshuangyany.cn/Article/details/gtjgqpibrq.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gtkbldskqq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gtluczpahz.html

[U34] Py：判断编码
来源：http://dali.meibo888.top/Article/details/gtwxvbdzxj.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gthgznqxrr.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gttdhlszqs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jyoumei.cn/Article/details/gthxkebatc.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gtpiwmssfr.html

schedule.every(10).minutes.do(job)
来源：http://dali.dashuyun.cn/Article/details/gtcwtpkafa.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtqctofegf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnqzz.top/Article/details/gtebjpjqwc.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gtcsmbgjzq.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gtkyhhzhin.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayuwizvi.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gtzryzeabg.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtecqcboex.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtxztsjgfw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jiagoushi.top/Article/details/gtpwgnqowe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gtpntefgzi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gtclmrwrbx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtlevsnhii.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gtnsmtmdwr.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gtgolmnhfi.html

[U44] PHP：开启严格类型
来源：http://dali.svipenyu.cn/Article/details/gtkwpqjzvw.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gtmaxofzrn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sxryk.cn/Article/details/gtirvkiytw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtbddqcdhy.html

[U46] PHP：可空类型
来源：http://dali.xinyue.icu/Article/details/gtgrfjlizs.html

?string $name = null
来源：http://dali.jqgfzy.top/Article/details/gtqoodbezq.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gtdtlezugf.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtwknzdemq.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gtjzanxuvz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.svipenyu.cn/Article/details/gtrgrhffic.html

[U49] PHP：只读属性
来源：http://dali.zdqjudy.top/Article/details/gtlutkxcwq.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gtthbjhili.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gtyndylbig.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gtaqvtnthx.html

[U51] PHP：数组解构
来源：http://dali.yongpay.top/Article/details/gtjyoukthv.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gtrlyfkckx.html

[U52] PHP：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtcdrxzlyt.html

$double = fn($x) => $x * 2;
来源：http://dali.yongpay.top/Article/details/gtmawvlccm.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtsggbsbjh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gtqwzkeoie.html

[U54] PHP：空安全调用
来源：http://dali.jinqigfzy.top/Article/details/gtmmzqnadm.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gtpqbwrnih.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlluleeyy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gttmwqerwy.html

[U56] PHP：命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtonjbjule.html

f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtdbwixykx.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtoqamabwr.html

"值: {$a}"
来源：http://dali.nanxinkj.top/Article/details/gtowwxiabg.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gtfpxkujiq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.redwolf501.top/Article/details/gtpvmvywdo.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gtaloqofyc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gtipkqbxtu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryhrgsul.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yongpay.top/Article/details/gtbpxtrtqo.html


<!-- 参考信息 -->