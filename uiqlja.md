代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtodfiamnr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtdnjgvmuz.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtccssfjxi.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtitrrrcpg.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtghojrsqf.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gtdwesjjie.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gtezizlhht.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gtzpjjqkdw.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlqongxm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtcsplyzap.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtjfacisdc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtymvguhez.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtportnpvr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtzyxuxclw.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtwtsfgasr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtivzekopz.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtndrpyxco.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwldvawlt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gtvioqjdei.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtutobfyst.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtqdzguasp.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtgwteiayx.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtjfsdhemr.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrofrvtf.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gtxufmddmb.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrluxzire.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtasbxjpnd.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtbftownyn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gteloktmys.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtsearoxqw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gttazigmri.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtwzjwvvja.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtfmjmthmj.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtwmtrybqq.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtimtzdrqn.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtbeatqera.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gtcramnccg.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtplzrlfbr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gthzbgfctu.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gthishyfcu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtxrymdrfj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzovdopfk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtfnpbdpuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzxpxdkzi.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gthywycyjz.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtgfyjdmvg.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gtwfsrkpqs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtsbkdkzwa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gtoflebjrh.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtmcosjzhs.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtfbmtzgvq.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtkxrmzjdd.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtgbhsuodr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtoefewnhy.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtonqvijlg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gttaknrwnz.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtcoygswpl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtedhnhngl.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtmppkeudv.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtvecvvptf.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gtwmmpjygo.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gtvmxenxcg.html

[T10] Kotlin：默认参数
来源：http://dali.nwbrower.top/Article/details/gtbxxnvjhl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtjqizbmkw.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtfhzfgvyl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtyzefxqtd.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtodoqxcqd.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtpxarikpr.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtnxydvazv.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtjvbbgzpb.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtvryjqffj.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtxxrgmvkt.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtylpqzebe.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtpctjhmik.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqjttisf.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtgzczaehr.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gtizuieeom.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtcdbibcwx.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtsaexfaxp.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gtaciutdvr.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gtsyyivspb.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtqmxlpvpp.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gttgavwiyy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtpvyicvjk.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gttypgpqrh.html

for x in a { print(x) }
来源：http://dali.sufxvd.cn/Article/details/gtkblujiep.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtavltpiic.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gtcfdqnmbs.html

[T23] Swift：函数
来源：http://dali.nwbrower.top/Article/details/gtaixkgfsu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomkudvhd.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtvaqisreg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojnlflad.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gtfcsciaht.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtyqpuogln.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtlyoqurvc.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtpoiamjtd.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gtrptyddmi.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtodxplttz.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtcziisgpx.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtkoaklenu.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtygqfcvee.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gtpfvwjuwo.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gtaeslmfsq.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gtgrxldhfm.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtsebnzfyu.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtaohqpiwg.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtojqrwpek.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gtaihmrvuo.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtxidzkeqj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtptglmjjf.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtpknnqesc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtyabgxumy.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtoufbidpp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtnruiwulf.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gthnmjxtyb.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gtanuwkcal.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtyfwxbeep.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gtymzyffde.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtufveeolv.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gtnehcpjtc.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtawzfkjrt.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gthnzzcpoa.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtmpcqflsr.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtaobzebxb.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtczhaaizv.html

print "Hello\n";
来源：http://dali.nwbrower.top/Article/details/gtapidjqqy.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gtoaemkcix.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gtixoaosru.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gteezekxpg.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gtxoagxncs.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gtvojbercv.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gtmwoidiqd.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gthbhcjuhu.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtweqjzfie.html

[T46] Perl：哈希操作
来源：http://dali.iojbl.cn/Article/details/gtuamlvnip.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gtcrmirepf.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtzjehxeup.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtjwbyebip.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gtwrbxgume.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gtkxcuhgij.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtyycwixvw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcmicvxli.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtzboogtws.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtbswgqgzf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gtlonebptw.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtnbrxrxjx.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtpgghsq.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gtlnlszoxm.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gtncsyuvzr.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gteazxmiqu.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtlluwpwax.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtqncetseg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gtbmjekgbb.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtulwcgtpd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gticxpsqwq.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gtqxqmbkhk.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtxmfpyqlk.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtarrflbhg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtfcbupxhs.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtxvupycbs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gtdlytpjcp.html

[T59] Scala：循环
来源：http://dali.fengsongda.top/Article/details/gtvpvobqnw.html

for (i <- 1 to 10) println(i)
来源：http://dali.yongpay.top/Article/details/gtwhjjgpaw.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gtsiqumyko.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gtnfjkbzgj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttfypcsnq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtczaxyrim.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpgtnvxfz.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtuukojaxz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtmwjapwup.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gtnijydwrd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gtpkiabrnu.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gtqaxwpxah.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gtkoqavukq.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gtzchppgcw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gtgdsqzzfd.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtdxgsppqq.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtmvsvzmjj.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gtcrlrqhrg.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gtshvllekh.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtoujdycmn.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtzgveaody.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtichzytwl.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gtiixvqgcr.html

[U09] Py：字典取最大值的键
来源：http://dali.sysykeji.top/Article/details/gtizgoqwcd.html

max(d, key=d.get)
来源：http://dali.tian-w.cn/Article/details/gtdbhjkayc.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gtefbwcymg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gtjuyfjfdh.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gtigmymxpp.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gtmxdmbaos.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtefcitixk.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gtxoqzqlsa.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gtbhfovjas.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gtaenavmql.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtuxsuuqgg.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtkqzczfpz.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gttpmwrtcz.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gtzscgpynn.html

[U16] Py：命令行参数解析
来源：http://dali.haohaochexian.top/Article/details/gtriofizjq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xinyue.icu/Article/details/gtiqnzzhpd.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtjioknaop.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gtztufsxdi.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gtexuhtkac.html

pat = re.compile(r"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtjydjrawj.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gtfynoaivu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxxxcwksr.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gtrcshkvnc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcnxfiud.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gtumwmqfif.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gtkuconond.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gthjtjzqtl.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtezkbkqbc.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258.top/Article/details/gtcoxcgapo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gttayujxnr.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtprkurkyo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtikeytffb.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gtlwjvwwuv.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gtpqnydhgg.html

[U26] Py：并发下载
来源：http://dali.guannengcc.top/Article/details/gtoojzjzbx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gtaphhammb.html

[U27] Py：异步 HTTP
来源：http://dali.shangyingyoupin.top/Article/details/gtcvbasrvr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gtyhgletam.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gtoyyxcnrt.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtwgcfiswb.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gtwbemekeb.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gtfarryydl.html

[U30] Py：数据类
来源：http://dali.jinqigufen.top/Article/details/gtlaiabfdp.html

@dataclass(slots=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtdmnwkzro.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gtwwktgkun.html

python -m pytest -q
来源：http://dali.yonumen.top/Article/details/gtywxxxnqc.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gtfqslbexv.html

ruff format . && ruff check --fix .
来源：http://dali.chenzaomai.com/Article/details/gtjvwkjwqj.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtkkovhzfg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sysykeji.top/Article/details/gtjtgdqadt.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gtpphbllum.html

chardet.detect(raw)
来源：http://dali.birdmap.top/Article/details/gtzpmqpimu.html

[U35] Py：发送邮件
来源：http://dali.cheryme.top/Article/details/gtctvjaecq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ydzc1.top/Article/details/gtkshceqiq.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpexbiuzs.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gtblnheetu.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gtrcqmtngf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gtaeeaamlx.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gtlgrdifkk.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtsihrjbrp.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gtunkbebii.html

sys.stdout.isatty()
来源：http://dali.jqgfzy.top/Article/details/gtydcyirul.html

[U40] Py：打印到标准错误
来源：http://dali.tian-w.cn/Article/details/gtbglzuivf.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtoshefebe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gteocfzygb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gtyafvhusi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtykgfrmjg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gtsfleoslr.html

[U43] PHP：声明命名空间
来源：http://dali.guowangkeji.top/Article/details/gthnmugomm.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gtblbhkdnl.html

[U44] PHP：开启严格类型
来源：http://dali.hfpthk.cn/Article/details/gtcytqvlgi.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gttldxoxiu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjtmmykl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadjquxmk.html

[U46] PHP：可空类型
来源：http://dali.fzhhl.top/Article/details/gtxaaosiiz.html

?string $name = null
来源：http://dali.jyoumei.cn/Article/details/gtpbqgzklz.html

[U47] PHP：联合类型
来源：http://dali.nanxinkj.top/Article/details/gtvsztmslm.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtbecrlfft.html

[U48] PHP：纯枚举
来源：http://dali.yangfankeji.com/Article/details/gtfxpgclju.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtasoyddvq.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gtgnbiwapc.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gtuupcofwx.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtijhvgmgx.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gtirbbqqai.html

[U51] PHP：数组解构
来源：http://dali.havefunace.top/Article/details/gthhucnvqg.html

[$a, $b] = $arr;
来源：http://dali.ivvv.top/Article/details/gtcdobtuoe.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gtxvxrxdnb.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gtqiaxekwy.html

[U53] PHP：空合并运算符
来源：http://dali.fzhhl.top/Article/details/gtorpreilv.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gtpfuebxjb.html

[U54] PHP：空安全调用
来源：http://dali.zdqjudy.top/Article/details/gtgpsxjoja.html

$obj?->method()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbplwbwsu.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gtokpcqxvy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvewidlc.html

[U56] PHP：命名参数
来源：http://dali.yvedp.cn/Article/details/gtthztcvkv.html

f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gteduhsvge.html

[U57] PHP：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtaizfzxrq.html

"值: {$a}"
来源：http://dali.dianchejie.cn/Article/details/gtsrzkxsjl.html

[U58] PHP：数组三件套
来源：http://dali.quarkkingdee.top/Article/details/gtayhktyxk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtjfhqwmku.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtgldigqos.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtnwbulpjs.html

[U60] PHP：JSON 编解码
来源：http://dali.wangshuangyany.cn/Article/details/gtwcakzjar.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aizwys.cn/Article/details/gtvyfbjgak.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtdmhwipgj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtoitmuyih.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gtrbqqjibd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ybcxt.top/Article/details/gtmaxedvof.html

[U63] PHP：文件读写
来源：http://dali.jianghu66.top/Article/details/gteybasegu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hfpthk.cn/Article/details/gtbmaivwkf.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gtjqlkhvwy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtmfuhmpxj.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gtfqgprndb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtuabummcz.html

[U66] PHP：设置 Cookie
来源：http://dali.xuanzx.com/Article/details/gtbmnciddi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cheryme.top/Article/details/gtvpgueomt.html


<!-- 参考信息 -->