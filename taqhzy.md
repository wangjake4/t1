代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtfedqtfcd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtmlmgijnf.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gtmsolelqc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtczjsyghi.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtsxiqiiqf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtshexwjyr.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtsahsgtto.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gtfbotbwxu.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtmduyfope.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtaxheixcl.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gttzocehpe.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gthwuzkkgs.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtvugtwnpb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtezjqgkul.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gtvlpjphae.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtlkroancp.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtjmlymbup.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtugkzdewk.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtntzjaftu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtfsftiulq.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtjdvwmlel.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gtkldcjcyn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtxqisxsup.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gttvugmhjk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gthhxwucqm.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtefcmyjia.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtuamycdro.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtcggpmzyc.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gtbdaqqzea.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtjzktrsbe.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtkwazeacu.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtnfkwtsht.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gttsxawyxb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gtzrdjvdzr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gtplhkzppa.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gtaowahfoa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtqhzpuczk.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gthpvvctya.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtirkyunvb.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtrfzhfbjf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtxlzudpuq.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtpxijmnoo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtxswoeexf.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtsbaxzwmb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtidrwchht.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvrycfswi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtaqhtuudp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmfhvxoom.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtsjcboqbk.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtjbcgovhx.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gthknkgyjw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gtpbbrpset.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtjkhygepo.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtdwdprkig.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtdebzixgc.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtgdexszgj.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtvklhikiy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtaztpcddu.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtkhnetfqe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtumnnmacb.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtfuutgkoe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gtrvfuudwp.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtpaswyrtg.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyaxjodi.html

[T09] Kotlin：扩展函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiguevbv.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gttraofsob.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtecqrmimm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtqhxegmqm.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gtneceltty.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtgxjlvoin.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtozvzdvfi.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtkgdcykhk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtwxbtywjd.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfkhnpgnv.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtchyxsfzr.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtifubihno.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gthbvqcopr.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtrrzrfyeq.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtcotwvyek.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtcpcddgsk.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbykhjmfg.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gtgdqbgfbe.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtaoptrcew.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtqfxxctsz.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtntgbzdob.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtnyqdzlod.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gtmjtjxwbu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtbertggyo.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtqlzoacjj.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbccrfmfn.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtbzblwtjj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtfuoefhkz.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtgoskbfqw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gtquoqsztm.html

[T24] Swift：闭包
来源：http://dali.daxiang520.top/Article/details/gtpthdzrfv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtkrpdlqmp.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtrhfqblgu.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gtczlqdzvt.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtwusdoyns.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtuprndlmw.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtkywtaxtz.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gthsbuxncx.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtkaekfjvi.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gttqvidcoc.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gtmnaohsmz.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtuxxvgdpw.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gtdajkpxea.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtzindddot.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gtkhqftajl.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtakhvmyuq.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtmljsucdw.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gtiamqlwyn.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtclqaytss.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gtggibnyos.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtbdhfhvaz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtigwhtbmq.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtpoavhhqm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yongpay.top/Article/details/gtgalklarp.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtnswfssgw.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gtzxtriazm.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtqpuymnmi.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtzcexdoxz.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtnituoyjb.html

if x > 0 then print("正") end
来源：http://dali.dianchejie.cn/Article/details/gtznnblhiy.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtyyvoalco.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gtjxhgfrjk.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gtwbltaaqt.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gtwdjpgbel.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtgwisuggn.html

print "Hello\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtqmyrbrnw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtipzrqgkm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtedhojaqv.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gtjxoxeyhy.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gtwzfqwtkq.html

[T44] Perl：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtklcqdvpy.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtmsatyahr.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtqjkoncvr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoadisjr.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtpvppefqb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gtefddrpkf.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtcajeferp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gtaxspmvuv.html

[T48] Perl：正则替换
来源：http://dali.shuidangran.top/Article/details/gtccgniycw.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtqaeqbzqf.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtamiccato.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtaikfmlwv.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gttbxmjqkt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtzqapsweu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbgybxhc.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gthpvmzirx.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjdveyxr.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gttxtdwvhh.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gtjfyhcval.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpxaxasm.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtmhqmeofn.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtntueygnu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmzpwlvkf.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtqofwyupw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwonkbbtc.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtgsrozged.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtlnffxzzs.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtmooalssl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gtjenvrzha.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gtpwihwvid.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaqpfdnq.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtqtxshzuh.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtellkvnbh.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gtdrtqysac.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gtmqciacnm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtebeuspuv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtkqzfwcuk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoghjtenw.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gtiqivvfrp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gttzxifrrv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtvjolnqul.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gtieouxxog.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gtiovmrofv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.snrcjt.cn/Article/details/gtseubpvmo.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtedzabjgc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gtkjukriyp.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtvgojasvi.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtixmeyckj.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gtfhuyaukc.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gtethsljla.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcpnbmqq.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gtigzwtdal.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtlxjbgfai.html

[y for x in nested for y in x]
来源：http://dali.cashguo.top/Article/details/gttrfdojac.html

[U09] Py：字典取最大值的键
来源：http://dali.guannengcc.top/Article/details/gtlxthyzwm.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtvprjfclr.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtfifymtem.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gtzeslhpad.html

[U11] Py：生成器表达式
来源：http://dali.cashguo.top/Article/details/gtjmfxyjka.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtzatejpyq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtkoxgqqhl.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtznmtnvkt.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gtbbyhpdqz.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoewgrjz.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gtdswfhqmc.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gtkpyknbmn.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtdbfgvyse.html

t = time.perf_counter()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzpmsaaj.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gtvgnrbgby.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gttrefyfae.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtdvadspux.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gtmorvecvr.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gtthkdxzvq.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtwldjzwec.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258888.top/Article/details/gtmhekxzsz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtybgslarr.html

[U20] Py：缓存函数结果
来源：http://dali.dianchejie.cn/Article/details/gtsmspvjfl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtozxgiwfd.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gtvnnegact.html

@contextlib.contextmanager
来源：http://dali.jyoumei.cn/Article/details/gtybjulaxc.html

[U22] Py：矩阵转置
来源：http://dali.sufxvd.cn/Article/details/gtkdvrambv.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gtvqunlpvt.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gtvsxrjdtu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gttzurypgd.html

[U24] Py：路径操作
来源：http://dali.nanxinkj.top/Article/details/gtjkaolhdf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtxoxstijq.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtcxtynrlu.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gtenixxujr.html

[U26] Py：并发下载
来源：http://dali.jianghu66.top/Article/details/gtadohphza.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gtmxgeuotd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gtiwszoubj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gtweasnhob.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtbnlssooa.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtnadywzva.html

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gtbnaanqhe.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gtybujjvyh.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtnkenvnnt.html

@dataclass(slots=True)
来源：http://dali.cdnleiting.top/Article/details/gtttlpwhww.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gteagoughn.html

python -m pytest -q
来源：http://dali.gogol.net.cn/Article/details/gteflxdfsu.html

[U32] Py：代码格式化
来源：http://dali.gogol.net.cn/Article/details/gtloxqmtvs.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtrrdfkbtl.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gtbqcpingc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gtxuwazurs.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtwlolxrrb.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gtawexwowr.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gtfpxcjymn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.vqdsnc.cn/Article/details/gtafflkjpp.html

[U36] Py：定时任务
来源：http://dali.daxiang520.top/Article/details/gtrjbrtmju.html

schedule.every(10).minutes.do(job)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwedqhqyc.html

[U37] Py：读写 Excel
来源：http://dali.zhongyouzk.top/Article/details/gtzejmjbfd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guowangkeji.top/Article/details/gtikzdfdor.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gtwtucqihj.html

Path(__file__).resolve().parent
来源：http://dali.hfpthk.cn/Article/details/gteadvdlfm.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gtejmikirv.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gtavzrnpvs.html

[U40] Py：打印到标准错误
来源：http://dali.pycfn.com/Article/details/gtepzcrehp.html

print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gthpdaxocz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgfzy.top/Article/details/gtzdmljkta.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daria6918.cn/Article/details/gtlnuvldgo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gtudjpwoor.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sysykeji.top/Article/details/gtdiokatdb.html

[U43] PHP：声明命名空间
来源：http://dali.zdqjudy.top/Article/details/gtuprijyqe.html

namespace App\Http;
来源：http://dali.jiagoushi.top/Article/details/gtbqyhehhn.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtawvenyju.html

declare(strict_types=1);
来源：http://dali.tian-w.cn/Article/details/gtepmifels.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgfzy.top/Article/details/gtbjjkyjbg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwfwhupzf.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gtuuhvfgsd.html

?string $name = null
来源：http://dali.dianchejie.cn/Article/details/gtpbqmopqz.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcslnnhl.html

int|string $id
来源：http://dali.cqqwz.cn/Article/details/gtavwusdjw.html

[U48] PHP：纯枚举
来源：http://dali.yvedp.cn/Article/details/gtgvbrciad.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gtwahmjmoh.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtljzkttbk.html

public readonly string $name
来源：http://dali.guannengcc.top/Article/details/gtqntopvtk.html

[U50] PHP：构造器属性提升
来源：http://dali.bjfxy.top/Article/details/gtoqbhaixx.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtoehjwktc.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gtkvfhnkwa.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gtrslftlys.html

[U52] PHP：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtbaqgfhlt.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgsfmtow.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gttgvlhmad.html

$v = $a ?? $b ?? "default";
来源：http://dali.cucudq.cn/Article/details/gtoyyydjnx.html

[U54] PHP：空安全调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlutrycbu.html

$obj?->method()
来源：http://dali.zhongyouzk.top/Article/details/gtlppygewl.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gtsjrfmvlf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zycfv.cn/Article/details/gtzpviggoq.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyesehpsk.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtiackbili.html

[U57] PHP：字符串插值
来源：http://dali.cashguo.top/Article/details/gtvltvjzwn.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gttbahdjjg.html

[U58] PHP：数组三件套
来源：http://dali.hysaishi.cn/Article/details/gtqanimrau.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtribnahhb.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gtapbhjvga.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaytgolv.html

[U60] PHP：JSON 编解码
来源：http://dali.dianchejie.cn/Article/details/gtiovaujsk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtymabolit.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtojlecsgp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtwpcixcen.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gtdbczutta.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gtrddepszx.html

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gtenvtvxsp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gtzlinihwu.html

[U64] PHP：目录遍历
来源：http://dali.xuanzx.com/Article/details/gtdtzljivr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gtfgaovkge.html


<!-- 参考信息 -->