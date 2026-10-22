代发 wailian999

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gt2wxuxeqgv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2qwssohsq.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gt2mblsbesm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gt2rizdtemb.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2hktjftfi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2ezylakdj.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gt2olmbhhga.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2iklgoxqg.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2brdaalph.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gt2lujjskka.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2skdcwcii.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2fuanyair.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzyvrgzq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gt2basnszfh.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gt2lmmdvsfw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2pbvjwpit.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2vipkueyb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gt2lbfjcuji.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gt2vhdidjcn.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gt2esojdshw.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gt2wcjywyov.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2fpkqnnxc.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2etsyemkq.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmlaezgw.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gt2erxvbott.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gt2xzuatvkv.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gt2qgymwgav.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gt2ndkidkpj.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2uuttabxr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gt2ixnauswg.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2larjsdyx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gt2pizczgdd.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gt2fqqjlogz.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gt2zwnzegkv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gt2xllhpgcc.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gt2wzjoadnz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2okclueoi.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2orwkjikm.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2szbbpotg.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtrpnmbw.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gt2twdsmdht.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gt2stdhixqr.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gt2pexbwxqa.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gt2zgdnsqhg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gt2gnkyebdl.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gt2obdfzctd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2zmnyklfw.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gt2hykuatyz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gt2wbjsaril.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gt2ivuhjwjf.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2pqibywpi.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gt2cagpwwjb.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2scehfuxt.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gt2mehrvdeg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gt2xskuwzcz.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gt2ngbjacpd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2klovhlmu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cdacmbqt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkueuokc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jtatvhdx.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2iqxyzgjk.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2nvpqdvwg.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gt2pnugmjbs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gt2wvfffvct.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2taphwvbe.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2dbspfzqi.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gt2htlxnrsq.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gt2ywehlgfd.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gt2rhtepkhp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gt2oyslrnww.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2xhfyzwhf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2govmsfcy.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2qehzlbbo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2xfjpiptl.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2yisuzxmu.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2byrgsfuq.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gt2oxtrfsmc.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yaylqouh.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdyalaaf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gt2tckvzohw.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gt2kxoqepze.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gt2sywxbfvf.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gt2cgtmylqp.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2eoiqlcna.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gt2lgffcqun.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gt2gejordml.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gt2wldisguu.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfiutdai.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gt2hgrqutpl.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gt2uuglgpyk.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2yywpymiz.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kovzwurm.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gt2sgywjtls.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnbeuwnc.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2fwjzpnev.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gt2uhyifuut.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbnvazjj.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdyhuvyf.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gt2clfsnloz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2crslmsnn.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gt2ozctmtak.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gt2sofweqcd.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gt2tvsvfowx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gt2cgkuruxg.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gt2gxuibzeu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2irwnbvnh.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gt2jkzdkqaw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2weumenvi.html

[T25] Swift：结构体
来源：http://dali.ivvv.top/Article/details/gt2njsthppo.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtpgpujm.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gt2alhmkvmy.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gt2bcyifnpg.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gt2obkjjjlb.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsiilkhx.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2edlzznbc.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gt2mlayoinx.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2xbewtmfz.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gt2sxmzzgvn.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gt2lvfgnvrg.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgfzy.top/Article/details/gt2qarzqeht.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edssiafr.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2jyahitff.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gt2xyawflym.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gt2kdhevsoz.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2enigfjhl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gt2itmuwcts.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ryrzvnzi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gt2nuvphoxl.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gt2lkyftuda.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zijhfbbu.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aovpnoah.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euomdjpy.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uitykjps.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gt2aphggfuv.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gt2uqimejgu.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gt2esylutwm.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2jcoonuqg.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gt2gzzamrgv.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gt2pzawolru.html

setmetatable({}, { __index = base })
来源：http://dali.jiagoushi.top/Article/details/gt2guzmhoxh.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2msrlyscv.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gt2bkyiyzfa.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2cphkjzxo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gt2dcdahbjv.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2hvzojvic.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wscoqbex.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2rqtqyqey.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gt2fbvmskwi.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gt2gdwouijk.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gt2yacehqod.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gt2aqdijcjo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gt2wltjqmcz.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gt2jgguxgtz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blufzgae.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2gckucuqr.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gt2pfgufzpv.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gt2wrgsjdve.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2oqqwpnuv.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2gfnfrkif.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gt2eklnbuyq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ysvazgrq.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2miyxdmvt.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2cnswdemh.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gt2syjjfakb.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gt2fnrhjkzt.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2vobvwpiu.html

s"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2bzdqhksm.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2xxsxzyjz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2yfjiswtr.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gt2uveydatd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gt2agxbhoni.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gt2demumzqq.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2zgjomuov.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2tufwogdf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.haohaochexian.top/Article/details/gt2gncniuzi.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gt2qcliznrt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2gregmovy.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gt2bdgwqiwb.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gt2jirjyccl.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gt2qzuseihi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gt2neuskqws.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rwkbwqpw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2djmwykoa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2lueqthpc.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gt2wtaxmxll.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gt2rcvorjvm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gt2ntaegwph.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gt2mllqdrnf.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gt2veambemn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gt2lxbghais.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gt2xhtqkria.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkqqoqlf.html

[U05] Py：列表去重且保序
来源：http://dali.yj202588.top/Article/details/gt2fhsabryg.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2dnytfwfp.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gt2phfkwaec.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gt2pfobmpzo.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gt2nopakqdp.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gt2zzpprvpf.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gt2injzcuhr.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gt2ftfhgprg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhongyouzk.top/Article/details/gt2nxezikxk.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofzykqjw.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gt2lyfshbqj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gt2maghebjb.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gt2wlbysthq.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gt2ptriammd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gt2gwhpxxab.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gt2tupsamle.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gt2sbwlssxs.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gt2aycascpd.html

[U14] Py：分组收集到列表
来源：http://dali.cashguo.top/Article/details/gt2lilpqzfi.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gt2hpcxetga.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gt2sinfobbd.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gt2lzajlbzh.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqxtzauo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gt2hkmrirbr.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gt2sexptkty.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gt2dtnofbhk.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gt2vfoscnbg.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhhbqqzy.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gt2enwylmly.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shuidangran.top/Article/details/gt2ydqrnyai.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gt2dugoalvm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258.top/Article/details/gt2gklfkcjq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gt2nmmxngrg.html

@contextlib.contextmanager
来源：http://dali.jyoumei.cn/Article/details/gt2ygounzpk.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gt2ppjjvdpj.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gt2xcszekyu.html

[U23] Py：分块读取大文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfxsbfla.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gt2ggxcfqix.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gt2rfiuwjav.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2bdgvlecy.html

[U25] Py：CSV 按字典读
来源：http://dali.yuxming.cn/Article/details/gt2ucxajwcx.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gt2nsqzvscu.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gt2dablkymo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yonumen.top/Article/details/gt2qorhbmne.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gt2htfeljag.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.mhx1999.top/Article/details/gt2rsvwanur.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gt2pbajddqn.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gt2gmftkecy.html

[U29] Py：属性校验
来源：http://dali.quarkkingdee.top/Article/details/gt2viikroji.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyprdwnw.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znoadzjn.html

@dataclass(slots=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2sgkamggq.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gt2jhquxqng.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gt2gehbwpuy.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gt2hpizedtn.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gt2lizrhfos.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gt2nxsqchbd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gt2zufikahj.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gt2spwfrbla.html

chardet.detect(raw)
来源：http://dali.jqgfzy.top/Article/details/gt2fvuwnqks.html

[U35] Py：发送邮件
来源：http://dali.yj202588.top/Article/details/gt2neemjwxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tian-w.cn/Article/details/gt2izacptve.html

[U36] Py：定时任务
来源：http://dali.havefunace.top/Article/details/gt2knvkqijl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbbdbmmb.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gt2vijmzzrl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxuanxn.top/Article/details/gt2usmtdkmv.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgufenzy.top/Article/details/gt2omveoivw.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gt2dngcyvuw.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugdwfqeu.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nykhbhfm.html

[U40] Py：打印到标准错误
来源：http://dali.vqdsnc.cn/Article/details/gt2ydipuzvi.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2suugmhwz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guowangkeji.top/Article/details/gt2zjikpqut.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gt2xgasdghr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gt2hylpqany.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gt2jkenberl.html

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmcfcrdp.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gt2hmowvrpj.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gt2xzgcvdrn.html

declare(strict_types=1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2toykwzru.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gt2otieubre.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2rspexpbb.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gt2ehjbjchc.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gt2bzburxoe.html

[U47] PHP：联合类型
来源：http://dali.cucudq.cn/Article/details/gt2clnzchvc.html

int|string $id
来源：http://dali.guannengcc.top/Article/details/gt2ksmqcrdk.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gt2dbrmkbvm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tianlin.xyz/Article/details/gt2klaguoxt.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2wttaqtab.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gt2opxqucwm.html

[U50] PHP：构造器属性提升
来源：http://dali.0kj1m.cn/Article/details/gt2zvthhqgb.html

public function __construct(private int $id) {}
来源：http://dali.yj20258888.top/Article/details/gt2favjejfq.html

[U51] PHP：数组解构
来源：http://dali.yanxiufei.cn/Article/details/gt2jygwljrq.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utsgyaoj.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gt2udxzqfui.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2axbojzjt.html

[U53] PHP：空合并运算符
来源：http://dali.zhixingplan.top/Article/details/gt2yynsnjrb.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj202588.top/Article/details/gt2pjhfwydl.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgrzowhk.html

$obj?->method()
来源：http://dali.hnqzz.top/Article/details/gt2naifozxj.html

[U55] PHP：match 表达式
来源：http://dali.cqqwz.cn/Article/details/gt2pamckaew.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2giclshrr.html

[U56] PHP：命名参数
来源：http://dali.aizwys.cn/Article/details/gt2urdfwwzv.html

f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2tjdqutsc.html

[U57] PHP：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2tmykdvqb.html

"值: {$a}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2mydtginb.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gt2iysgmwlm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.redwolf501.top/Article/details/gt2oilntofh.html


<!-- 参考信息 -->