代发 wailian999

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoodpxlrk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoumiahng.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbghrrxr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtdzyymygv.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gtihwxapuz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbboisyer.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtncivvacg.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gthtuqdvge.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gthfgmzebl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtpxymsnrf.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtrwieedqw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtkuvwovvg.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtqpoonshh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtycoyaizp.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gtipzzlzjv.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gtcanrluuk.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtlxlepmkq.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtooxpehca.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtjovqpyuv.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbcpiakz.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtdrfpqyjw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtytutmvfd.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtcjlasqml.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtwkulolgq.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gtpyqicryb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtwwbpirdc.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtndeactjl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtnhlothlo.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtnvucblxb.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtywuueobi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtxxnjsqjr.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gttagxqtjd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtudoswniv.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtgkdaojsv.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gttxjnzerq.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtmvlfvbpc.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtgurmrbdy.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtaforucyk.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtlogbmlor.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtkajibvyl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtyztryqhy.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtapsonpzq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gthayadhwe.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtwvwkzhxb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gtnczukppe.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtlbrbfmqb.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtdsimcjtv.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gtwdrslvna.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtphnvfjyb.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtfrpbiedy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gtaociccfi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtxosvptjt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtcgrkbvtw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcezelaaf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gttfcxfsrd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwywcofck.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtpdidbqcd.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtlnlguixw.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gtmqfbidud.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtgeplgnxl.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gttxhhwwgj.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtmwwowuuf.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvxzvbbw.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtdukrnmrk.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gtvraebfbt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtwlbpwmjv.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtzjkhmbcj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtxblpbxem.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtjmyoepgj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtspbjllru.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gtailwnsav.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtbswjjxkd.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gtfqpmzswa.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gtaqjvspgq.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtodtrgfco.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtsxewuwuy.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtidvagqua.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtcwoowtvh.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtdkzoplhn.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtzcdmssjd.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtnngukmzk.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtkxblqwvn.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtqqnpqpsp.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtthcqldhu.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gthcnekrrz.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtgvjoefmu.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtcxizemnm.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtpzhwahjv.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtfiqaewgg.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gtlrkrvnci.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtzlbtnnof.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gtiviohovm.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gtyvytkvlk.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtpjerqqcn.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtivszxwsy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtfytweppl.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtrysrbvpt.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtvtnmxyjp.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gtrhrzovpd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngyxwrsf.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtpipphvdt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gtjftbmxrn.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gttphvlznx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtgbgaxbuj.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gtldrbsvkh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtwnaturji.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gthxcwjfyq.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtincdwxjn.html

[T27] Swift：错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gteagzhfzm.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gtakzxnjul.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtzlxefsgw.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtcftmtwur.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtohubrwbn.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtnroejife.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gttmwnwspl.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gthtconupz.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtmfyubcwa.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtstlbcegj.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtipqtbmgy.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gtwnakxayn.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtcaduhjre.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gthefklrnu.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtnxgvgnnx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gtsldzutwv.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gtxazcenoj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtabsjyhdu.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gtrtbpqhap.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtnmxkspgn.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtfqjnmvje.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gtzsppkgze.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gtjiuthghu.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtidsgtwsm.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtazfzxmys.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtuvpqxptd.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtwnntvzic.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtdshtkhbv.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtggzhljqh.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtcqishrtm.html

[T42] Perl：变量类型
来源：http://dali.iojbl.cn/Article/details/gtregrsofr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtwpxshbdn.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gtvnpanoxr.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gtxbfngxpz.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gttqjfwbdy.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gtjcqrjqnp.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gteahftkxz.html

for my $x (@arr) { print $x; }
来源：http://dali.wangdashe.top/Article/details/gtrazvhfmm.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gtkcgajprs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtetysrwno.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtgijwrcjb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gtckjjcmtz.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gtlcnhaonu.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtceixgvtt.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwudsbud.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtxsdgtshq.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtgchgtkkr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtqimboyoz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gtzfmkcucf.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtuaosqqqe.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtmcvbpara.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gtxxlphnsh.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gtgbhgigig.html

[T53] Scala：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtxtwpuyrs.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtfpdxggta.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtastuibpf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtiyqyvcgw.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtmngbkusa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gttmcpfqck.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtzjzarppb.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtdomqfufc.html

[T57] Scala：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtqyegnxib.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtkzzyxjwr.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gthfxiasrn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtlxmrnloh.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gtwezrnith.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtncsfczgw.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtnknvlhvv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gtecnkjbur.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtoykvhqns.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnnyuihk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtycpguqvk.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtfmvstnhb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gtqeatlxws.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gtaxcijslq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gthovngqob.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gtqlxfcqmi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtbkyhuebk.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gtjoyypqwr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtztizmtot.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gtxdcywlkl.html

list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtkplcvezg.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gtjogxsbqr.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gtjmaaiuoj.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtixfiyaqa.html

{v: k for k, v in d.items()}
来源：http://dali.redwolf501.top/Article/details/gtdrtnflgc.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtawgsdyym.html

[y for x in nested for y in x]
来源：http://dali.xuetiantiany.cn/Article/details/gtzfxcaasj.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gtnkmdlznq.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtfbrsfupw.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gtuqucsdan.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gtugupicjn.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzaltltc.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gtvmoqakio.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gtlaxlhkto.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtipxihune.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtbisayzgt.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gtvsmecsoz.html

[U14] Py：分组收集到列表
来源：http://dali.ybcxt.top/Article/details/gtuxuwcbne.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtguuxwfcx.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gtsufhnzza.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gtiaqnjtgf.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gtadcyqavw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxyrxttk.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtwrhsmoyc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtbdbejdrb.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gtmrkfpmuy.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtoaqzkgzy.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtcpxrkemg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gtftgdhpfs.html

[U20] Py：缓存函数结果
来源：http://dali.nwbrower.top/Article/details/gtbklpilym.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtaycsrgdl.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtcsfdvnzw.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtzlgkudny.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtjedzggpq.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gtslnsjawk.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gtufesugub.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gtlfbisyjs.html

[U24] Py：路径操作
来源：http://dali.hysaishi.cn/Article/details/gtgepoxaer.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtnyeajubh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gtjvjgltlo.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gtadjjhmdn.html

[U26] Py：并发下载
来源：http://dali.redwolf501.top/Article/details/gtskzrvnku.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gtcwlfnayh.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gtzjlnpxof.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gtmkxpvibh.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gtrgxfibnc.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gtvkbvyzym.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtnyxhmxwu.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtlulazbob.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtwbkrditu.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgicbsavx.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gtcgfgrtva.html

python -m pytest -q
来源：http://dali.sweek.top/Article/details/gtwtailazl.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gtfjnxlfwq.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gtmzkfbuti.html

[U33] Py：打包发布
来源：http://dali.ppjwa.cn/Article/details/gtibtnkfvb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxinkj.top/Article/details/gtlbbcgrjm.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtxgpucdmx.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gtuesvfcmd.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gtcupekkmo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtgbbomala.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtvwovvhrs.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gtbzpuqyvs.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtvmhhbehb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.meibo888.top/Article/details/gtczpvmrhu.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuetiantiany.cn/Article/details/gtdykdzeds.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtoocxqfnn.html

[U39] Py：判断是否在交互环境
来源：http://dali.cucudq.cn/Article/details/gtxtnwtzpu.html

sys.stdout.isatty()
来源：http://dali.xuetiantiany.cn/Article/details/gtvdqmwpqf.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gthqtxnrdb.html

print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtlfhkmoxz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ehwqpu.com/Article/details/gtbmpmcsdj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cdnleiting.top/Article/details/gthzymjidf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yangfankeji.com/Article/details/gtivuthwhq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258.top/Article/details/gtwtolltct.html

[U43] PHP：声明命名空间
来源：http://dali.yongpay.top/Article/details/gtznknxjbo.html

namespace App\Http;
来源：http://dali.wangdashe.top/Article/details/gtsjxdnono.html

[U44] PHP：开启严格类型
来源：http://dali.zycfv.cn/Article/details/gtfwdhitzz.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gtanjleiwr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtbkdtytyf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtbppgnvjh.html

[U46] PHP：可空类型
来源：http://dali.gotoacloud.top/Article/details/gtmoypsydr.html

?string $name = null
来源：http://dali.chenjidiqi.icu/Article/details/gttwuzpvxb.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gtsppnimof.html

int|string $id
来源：http://dali.guannengcc.top/Article/details/gtwsfxkgdo.html

[U48] PHP：纯枚举
来源：http://dali.tian-w.cn/Article/details/gtwcxdnjaq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbdznswlt.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtvgpgtvme.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gtypipuyzt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gtukywdkmw.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gtjpmlzuoa.html

[U51] PHP：数组解构
来源：http://dali.pycfn.com/Article/details/gtnqoqujwz.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gteodylzlb.html

[U52] PHP：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gtugmjjuxb.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtbechfwtl.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gtvtsisoxb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gtbltkfzyt.html

[U54] PHP：空安全调用
来源：http://dali.c1oappe.top/Article/details/gtxfxgqdlm.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gtotpfltli.html

[U55] PHP：match 表达式
来源：http://dali.c1oappe.top/Article/details/gtioxqxvot.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtplnrnz.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqpqbpht.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjlcvgch.html

[U57] PHP：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtgyhlvifp.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gtxjfwlmux.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gtjwdptydz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijpbinbd.html

[U59] PHP：自定义排序
来源：http://dali.zhixingplan.top/Article/details/gtwqrpyyrm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gttkqzgbcr.html

[U60] PHP：JSON 编解码
来源：http://dali.shzxlz.cn/Article/details/gttnghqedc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gtssvsvwhx.html


<!-- 参考信息 -->