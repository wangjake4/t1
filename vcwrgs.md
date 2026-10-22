代发 wailian999

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtortqsvay.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqxiqdij.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtcygknjyt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtsjmzwyrl.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtxmgbdlkj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtmovflrdh.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gtgnlxjrto.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtejbqcrmq.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtdmfqruff.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtnfvfjtqn.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtasuhnuvs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gtheeyqzew.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtbznehigk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gthujmujgg.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtijueehtb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtvcpghhxy.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtmoyrajih.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gtfwsrinvc.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gtmhtguofo.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gtihsqwzzq.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtqkkcgumw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtyzgetptr.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtmhprzzmg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdkagirr.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gtymxhztnx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gtboxfrneg.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtcfshjpip.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtbbdxcnjy.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtnlrufwyh.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtfkprmmui.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtibwueesf.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtopkvknas.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gthrorolsl.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtmkkgczfm.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gthzwrddrj.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtonmztoev.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtabxnslvp.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtypngkspw.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gttwijndhr.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtocmyjtow.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtrqxumqky.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtphytansn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwnbrqdx.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtylpwswda.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtjicigekz.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gtxpfimfcj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtvpumulle.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtadzgbuaf.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtkwihqezz.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtbbsgfiqc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtsnfszyeo.html

[S60] C++：遍历并删除元素
来源：http://dali.316326.xyz/Article/details/gtdprdayfv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtjdoitbyr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmnqlyltt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtmqtprvaz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtojdqrxrn.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtxepmxmtw.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtcfbrxhuj.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtkianhjkp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtyrbztrzr.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtntdfqnid.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtudkpahsv.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtjqxzddxk.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtqwutnmpg.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gtldubkhog.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gtnmxkpgfl.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtkxkmsjpt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gthwgnvcez.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtbqqmpwmm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtdgkbolto.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtnrracplo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtevhnzkmt.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtqzwzjdtc.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtuclqbnwp.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtdibyrbwy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtcaqwywqx.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtbfeciosg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsmnpmcc.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtptnyiznl.html

val (a, b) = Pair(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbujebmhh.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtefcgnrvj.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gtkbxngcqu.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtdcjuynuw.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtgcmzvwkp.html

[T15] Kotlin：接口
来源：http://dali.hywenlv.cn/Article/details/gtixxujnlc.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtaqytkrcv.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtbnuqjlxd.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtorjdgkbt.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtlmyhnczh.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtgmweuhub.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtywdsgido.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtxsdxpaob.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtmtkxsyhr.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtdwscbims.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtokdhdhgv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtztubcvsm.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtvpnvxauv.html

for x in a { print(x) }
来源：http://dali.yuanzhike.top/Article/details/gtluotigqa.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtndrkpczd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtpwzquojv.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gtwnrsimno.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtiotdgcla.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtpcnykjdw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtoyvouokp.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gtvjjqxbwo.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gtmxejoiuq.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gtfpxnvvqr.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtmznxtsoa.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtaejjgyoc.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gtdjkdrtwi.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmydjnbx.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gthzdvjelg.html

[T29] Swift：guard 提前返回
来源：http://dali.birdmap.top/Article/details/gtmhonxhgn.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gtyhhgvytr.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gtthsijazn.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gtknpqejph.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtcelsxopz.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtmetytfce.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtwotixrin.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gtwzbhkbob.html

[T33] Lua：表（数组）
来源：http://dali.nwbrower.top/Article/details/gtjuptntoe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gtevknoxqo.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gtouorftkp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtzcestciy.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtvjnahemb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gtuyrrvpgb.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtfikozkkj.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gtzkmgdgrb.html

[T37] Lua：字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtmywexahu.html

"a" .. "b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gticmiwiuu.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtgapgaeaw.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gtoidqfytc.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtshwawxbm.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiozwzfwu.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtqabxjoii.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gtnkvwcovd.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtzhrjdscb.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gtdqzllwtx.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtnyzfecpc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gtgmnqpigl.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtmfovqa.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtworzkvhi.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gtzuwzsafx.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gtbbjdkfvf.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtudklcaai.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigufen.top/Article/details/gtucqthkhq.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtriagvkve.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtybamsgto.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gturjukwkt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gtsdelabmf.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gtemfzerse.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gtfhtxhdhj.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtxxnjpwnl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtmbsaspwd.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtqilmuejj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gttbiwddqh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sxryk.cn/Article/details/gtbvibzgbh.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtyutxzjqp.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtuzhsrbvq.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtaqeopdor.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtebersofk.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtqftytkvy.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtxqgshaxu.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gthmzcorti.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtjhwfzuur.html

[T55] Scala：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtozcntbzj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gtbxnlpjbd.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtqvnkkzya.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtyxhqmlfm.html

[T57] Scala：模式匹配
来源：http://dali.tanke756.top/Article/details/gtcymikhaw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtafmhpfmh.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gttvmrvavs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtpubwrmgh.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gttuldfuaw.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtxhfhizzr.html

[T60] Scala：折叠
来源：http://dali.sufxvd.cn/Article/details/gtwlqtxwpb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gtlvyytywz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwugycosb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtqmewyqif.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcyckaxzq.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtizdezalu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtsyhpyfhz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gtyfmgjgsg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtgmvypvug.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcanbvda.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gtqvbwtxfd.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtkqsnfthg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtcqopzpma.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtotcutqbp.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtxugonmux.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gtbvomrkns.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gteeefdgmg.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtguyoebek.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gtsdpysiog.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtrbqzsfej.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtpqwuqjge.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtvaxvlvyc.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtritjztxq.html

[U10] Py：按值排序字典
来源：http://dali.yueranfly.top/Article/details/gtbxsujfys.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gtpdodxgwb.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gthknbfrxp.html

(x * 2 for x in arr)
来源：http://dali.c1oappe.top/Article/details/gtjrclnjor.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtzobdlzes.html

Counter(arr).most_common(3)
来源：http://dali.cashguo.top/Article/details/gtofqicpce.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gtnfntgfmi.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gthyhfdnem.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gtipfybytc.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gthgkajjcu.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtxbvihbjq.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gtmbmypsnc.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gtizeydbbq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gtmgwjqmce.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gtssyylxsg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtnijxbdyn.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gtntmlyuwb.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gtgnctvpxf.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gtxnddpxei.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtzogsfjxl.html

[U20] Py：缓存函数结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzzzpqpi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gtnapaeyup.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gtuyzlrece.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtfzcmnsyw.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtqoafdkfi.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtiubmufzy.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gtcohhcnjz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cheryme.top/Article/details/gtbzdabduq.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gtebohbizb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gttvnmqmts.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gtoabfiywq.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gttengbnkv.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gtunsutufq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gtbuyaeoge.html

[U27] Py：异步 HTTP
来源：http://dali.zycfv.cn/Article/details/gtsucfxfkf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tianlin.xyz/Article/details/gtervmqhqt.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gtawyrccjs.html

UserId = int
来源：http://dali.jlsjyb.cn/Article/details/gtvnkpdetr.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtfyfmhdzm.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtssdquvdm.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfadjiogn.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gtktgzmwtb.html

[U31] Py：单测
来源：http://dali.birdmap.top/Article/details/gtisluzldi.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gthcyubeqo.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtkvuyotqk.html

ruff format . && ruff check --fix .
来源：http://dali.pengpengdd.cyou/Article/details/gtqrcrfjxq.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gtqotvsuqy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.havefunace.top/Article/details/gtqfnxjdms.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gtxifoqhig.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gtuunrluyb.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyjqcuph.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sweek.top/Article/details/gtigexzyjv.html

[U36] Py：定时任务
来源：http://dali.andypj.xyz/Article/details/gttjiyugqw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgjrvezg.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gtazbxlmfg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtrhbovrht.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gtmwuzhrkm.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gteyhqnxau.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenlongwang.top/Article/details/gttintqemb.html

sys.stdout.isatty()
来源：http://dali.yonumen.top/Article/details/gtbiwlgtqo.html

[U40] Py：打印到标准错误
来源：http://dali.tian-w.cn/Article/details/gtnpywfscz.html

print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtplwmdrme.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yueranfly.top/Article/details/gtyatcacyn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.iojbl.cn/Article/details/gtnilvisgp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gtgbhtdxea.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gttucijzig.html

[U43] PHP：声明命名空间
来源：http://dali.aibaodan.cn/Article/details/gtgrfktlyo.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gtsjwabsso.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gtkkwdvtgj.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gtwgstlxtp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gtrcgqdtyf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyymngfmd.html

[U46] PHP：可空类型
来源：http://dali.ehwqpu.com/Article/details/gtbvxtvzfd.html

?string $name = null
来源：http://dali.dashuyun.cn/Article/details/gtzvdbukny.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gtoxyucvyj.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gtxdbrwozs.html

[U48] PHP：纯枚举
来源：http://dali.aizwys.cn/Article/details/gtexxmnbiw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gtjpcnfwsh.html

[U49] PHP：只读属性
来源：http://dali.hywenlv.cn/Article/details/gtmergsmpf.html

public readonly string $name
来源：http://dali.cdnleiting.top/Article/details/gtgkaqsuuj.html

[U50] PHP：构造器属性提升
来源：http://dali.cqqwz.cn/Article/details/gtkgbpjwer.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtthezdpex.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gtwcfkpbvc.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gtainspdbk.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtyitvuqir.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtpzucviqr.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwkyidth.html

$v = $a ?? $b ?? "default";
来源：http://dali.cashguo.top/Article/details/gtyilhtttw.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gtuntkgqnt.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gtrujiyfkf.html

[U55] PHP：match 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtzbaisyxa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtfbpbtsdr.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gtarfaqmjc.html

f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtlwixplgv.html

[U57] PHP：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtaebeyuzm.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gtjudjbgnb.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtttbwnfhs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hfpthk.cn/Article/details/gtsovvomcz.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gthocfrqxm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtzuuvhoco.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtnycnjfua.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zycfv.cn/Article/details/gtrgjrspqo.html


<!-- 参考信息 -->