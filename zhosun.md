代发 wailian999

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gtbyarqnhh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtexpjlora.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gtcsqfwfui.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtesbzxtcu.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtouoezliu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtcefvisvg.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtfrfaxrrd.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtricdxodl.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtnoroicrz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtfybkezfl.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtuxklwpkm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtyavczftz.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtljzwsysu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gtebvwkcax.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtyuwuhtud.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gtrxyxvejl.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtpsufrjct.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtzarueimy.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtmnswwhjm.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtdtjfsccj.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtuzpvkcwt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtslygqtox.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtzakowdcq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtibpohzgb.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtfjbwjtxi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtvfluubgr.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtcpjckvqx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtvaacxbcj.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtrybcszyy.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtlpwzqoua.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyuydleb.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gtdwxpekpz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtynjhjhkb.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtezwhwcml.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtbdlhmmdx.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtcovdkucj.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtqqmsvlqn.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gtuzfctqol.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtodqjpqbc.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtaalukoje.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtkssgkapc.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtrnwnrfxo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtqmlflnpn.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtjyazrzuv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtnmuypktd.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtbnkhnnvc.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtzvyqzteg.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtujtyntzr.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtmwykgrdp.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtcgzsaomn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtttvakjfy.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gthkjqlszv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtmrbeuqvo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgyjmwoka.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtyfpcbjqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjofmrmxl.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtzujqvunf.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtchiddfcu.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtpdmytonm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtxvjlcorw.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtksqoijlp.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtajxfgbzx.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gttutdncxu.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtdiisdnhe.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtzyryewhq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtyffhzogv.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gtpvamscqp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtooxqwhzd.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtjiyeclnq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gteaxfdicv.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtchmjkdmy.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaebtlvqy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtunzbtczz.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtfvtmonii.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gteoehbsgv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gthcotsmdn.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gtuulyvndu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtqpllhicd.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcucijfs.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtwfzljzvw.html

[T13] Kotlin：只读 Map
来源：http://dali.0kj1m.cn/Article/details/gtxwjqesuv.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfmjftnh.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtxroxfnbi.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtzztvpaet.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gtlhanxdpj.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtrovvytzc.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gterjilpsc.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtcpkqngom.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtbyetprqa.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtdxmtvljs.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtjvbegzjs.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtnzfrfzmo.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtidcwpzha.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtylyjgcsk.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtxwbdiqxg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gtymvlkxuk.html

[T21] Swift：遍历
来源：http://dali.yj20258888.top/Article/details/gtdhcbqfhl.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtkskokbri.html

[T22] Swift：字典
来源：http://dali.chenjidiqi.icu/Article/details/gtirlmmqnf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gtxrwcduva.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtamvietcn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gtnciswgbl.html

[T24] Swift：闭包
来源：http://dali.yongpay.top/Article/details/gtajwwbxml.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtempnhobo.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtdfhhdldo.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gtezwhgfeh.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gtknxvblmo.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtumlzgumh.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gtkkcgmzpt.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtvnkrchli.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gthnjvernt.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtkktloaqt.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtzmqfvtoc.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gteyppmuum.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtioaejytm.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gtcpmncdop.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gthqzogeku.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtfgzmkvfu.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtofnfpusf.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtdmnawley.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtrgxrkdpx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gtsexgxcld.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gthglrsibm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtrilgzatn.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixppatqk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtdfmeztdz.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtdzmxvcbq.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtehkstwtr.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtmkavsyrs.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gtwayyfiwz.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gtaehyzwuq.html

if x > 0 then print("正") end
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbxbyhui.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtxnbakhjg.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gthatlpzxz.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtkniclpqd.html

setmetatable({}, { __index = base })
来源：http://dali.quarkkingdee.top/Article/details/gtaygkkehl.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtufhrtwey.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtomcsdnge.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtpltewsdc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gtwkrdggcz.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtpjwyljno.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gtiqcomcsc.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtsnjbesss.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gtbatxmdui.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtlisxgjol.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gteaddkqya.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtppluygwx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtnskwrots.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gtintnbhby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gtvrvkhoqx.html

[T48] Perl：正则替换
来源：http://dali.yj20258.top/Article/details/gtuptltpdb.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gtisgckrae.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gtylfdoucr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtmpfvulmy.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtwueavhvi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gtyvmwcuzj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtysxlxlby.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtzdkgcnga.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtojczabdc.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtrdhwwhuu.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtornkwrnr.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtmhnwndfx.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtgvuztzdl.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtnutotloa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltqorxdi.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gthudwdphc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gtywkvwxli.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtvmhpjrlt.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gthajbamag.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtazixuxgj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtunatbwwu.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gtemfaunlv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yangfankeji.com/Article/details/gtopodkbtp.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gtpnzmxgtm.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtdofjttbt.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtotvjharr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gtxqflytrd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthvfkjyit.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gthaezdnyb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtomkqqfth.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gteghshhqz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnjtwyyv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtjfyxqpfe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtyeobckpo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtnjwapzly.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aizwys.cn/Article/details/gtkkcyrisl.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtjmcwjteo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtdhmnayqd.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gthzvlinmc.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtfbwttpej.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtcxapyckt.html

{**a, **b}
来源：http://dali.ehwqpu.com/Article/details/gtlgepsznx.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gtgsbraemd.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtchsfmbyw.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gtwioskgty.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtaewgkiev.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gtwtkurvee.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtmpihxmrt.html

[U10] Py：按值排序字典
来源：http://dali.c1oappe.top/Article/details/gtdbomzwrr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gtcoghpzsr.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtdzefccog.html

(x * 2 for x in arr)
来源：http://dali.hfpthk.cn/Article/details/gtlxxqkmhg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cashguo.top/Article/details/gtvwpwcqup.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gtkxelmbzq.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtdpdsyvbk.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtimcyclxw.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtkklwnero.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gtflsjotqd.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gtaggbotiz.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gtzpdcdpvc.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gtktfkswsl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gtishgpxjs.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtdktgwruy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gtnjtuvvmx.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gthdnxoufc.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gtknluythu.html

[U19] Py：正则替换带回调
来源：http://dali.nwbrower.top/Article/details/gtkjbcjncd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtwykjxdxt.html

[U20] Py：缓存函数结果
来源：http://dali.chenlongwang.top/Article/details/gtyvgbrsck.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gtujkwnhqj.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gturcqvhmi.html

@contextlib.contextmanager
来源：http://dali.svipenyu.cn/Article/details/gtwlhjuxhr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gtoplvxvml.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gtrtldtcbc.html

[U23] Py：分块读取大文件
来源：http://dali.gzhubu.top/Article/details/gtmbabruzq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gtgdmmipvc.html

[U24] Py：路径操作
来源：http://dali.feifeiyinyue.top/Article/details/gtrifqfphv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtediitljk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gtzyoioswe.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gtnjuzdzpa.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gtykgtxyts.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuanzhike.top/Article/details/gtwvvzeqjv.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtssthjcaf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgfzy.top/Article/details/gtxckyxlky.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gtlyzjlegg.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtruluvovj.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gthzivxfah.html

@property 与 @x.setter 配合
来源：http://dali.hnxiangtu.top/Article/details/gtqxhwfmrx.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gtrkdxkahk.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtivytyhcy.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gthzvwaxxd.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtgyxqtrit.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gtatpjkirm.html

ruff format . && ruff check --fix .
来源：http://dali.zhixingplan.top/Article/details/gtqvspkzys.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gtjexyjfwg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtmqbwtqca.html

[U34] Py：判断编码
来源：http://dali.hysaishi.cn/Article/details/gttkvkhtpc.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gtmmyxlvin.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gtmygmwgof.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gtrmhqrdqp.html

[U36] Py：定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtknkbtenm.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gtndhpjlmz.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gtubbpjyer.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjhmbqjq.html

[U38] Py：获取脚本所在目录
来源：http://dali.hammf.cn/Article/details/gthrqlqaft.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gtapdexrkr.html

[U39] Py：判断是否在交互环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvmclboi.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gtsqztvytn.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gtexhmbaec.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtoxnpnlsi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jyoumei.cn/Article/details/gtnzsrjhik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgfzy.top/Article/details/gttmptcybz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigfzy.top/Article/details/gtfvmugcka.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuxming.cn/Article/details/gttoelcxrp.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvovpnkb.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gtbymjujjd.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gtzbkmtszd.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtlngxbbhs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gtzrunxkgz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmoyzizeq.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gtsktpeoek.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gtkxugiurm.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gtuaojpsjg.html

int|string $id
来源：http://dali.hywenlv.cn/Article/details/gtuykqfapp.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gtymsavtiw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.svipenyu.cn/Article/details/gtubqmkvij.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtmzncqhuu.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gttcwohzbh.html

[U50] PHP：构造器属性提升
来源：http://dali.meibo888.top/Article/details/gtfsuhjfwn.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdjutemzd.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gthsidzfap.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gtgpqbnvua.html

[U52] PHP：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtdssrukld.html

$double = fn($x) => $x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtbjdxnkpx.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtvzufpgsv.html

$v = $a ?? $b ?? "default";
来源：http://dali.aizwys.cn/Article/details/gtjmnedejs.html

[U54] PHP：空安全调用
来源：http://dali.hammf.cn/Article/details/gtbqxhnwva.html

$obj?->method()
来源：http://dali.jinqigfzy.top/Article/details/gtpquzhzvc.html

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gtjatnmkin.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtfxexpnrz.html

[U56] PHP：命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtlzmpubfk.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtevtpkgis.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtllpcwcon.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gtxyeosgyw.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gtnfetlgto.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbmbzpmxu.html

[U59] PHP：自定义排序
来源：http://dali.daxiang520.top/Article/details/gtxhpeypei.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtuwacypxa.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gtewxxhcii.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gotoacloud.top/Article/details/gtafrwfrkx.html


<!-- 参考信息 -->