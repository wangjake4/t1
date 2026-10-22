代发 wailian999

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtnawneivd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtulaexxce.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtovtwunfe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gtdrkgvtas.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gttbwsqepn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtbuxxcltx.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtceazmaou.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtikfhayos.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtwrcrjbgi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtlczgyeub.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyevignd.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtrsginlrv.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gtvbcsygvr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtwzijdarq.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gticghcesa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtutrpgqpw.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtvhvhmhsh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtkiywdrxm.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtypoudnjj.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gtufscifqg.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtpddwqjos.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgxvcigl.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtaqvcrney.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtwdaljfvx.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtyhcykiwa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gthyyafpvt.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gteynrrrgj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtgbcxcpgm.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtkttiazuf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gttkkzjxyg.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtpdbzkhqj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtowjiclhs.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtuqxinluj.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtrpommkgu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtzsbxhrnt.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gtevtmgsgy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtokvcrjzs.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtqqxtjnvq.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gtuyszzwfj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcktqlouk.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkalgpnbu.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtdbrabpsi.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtyszfnpdj.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtnlqgnocc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtcgqpawfu.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtgafkcpby.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtfvcjylgi.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gtfvzvukco.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gttcjmggsp.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtaxazztpi.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtrmtojags.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtxhwqkgql.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gthcfbfobw.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtqwrcdmwa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtwlhuysif.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtzjbhynnk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtbpyzwrzw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtodmninjw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gturemrfzg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdvxxvnmh.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gthhncladt.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtjavtrbql.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtnjekzfyq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gtenwtkjct.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtmzwpvoer.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtcqpiezao.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gtbmczzeng.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gtmifbjupk.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtlspbnqkg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtgpmcyfdp.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gtlluoxgyv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtuztijmco.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtnsbgmknf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gtqhwobpxp.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtycgqghco.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtsafrvsln.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gtkrghbzfk.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gthwsomgjz.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gtjvtrjywh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtfnjrvkfq.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtrnwllupf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtdcqdhxxb.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtjqecevdb.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtutirnycj.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtfzysorii.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtinfsavhx.html

[T14] Kotlin：循环
来源：http://dali.redwolf501.top/Article/details/gtwpvzedcf.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gtmkspoagp.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtgegnwrew.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtvimgezfk.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtrvcrpdjd.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtsoahbaji.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtzubnigaw.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gttjvvxwlv.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtpkxlnkfe.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtrfsxmbbu.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtlufpsctc.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtogrinxfp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gtffdouqov.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gtgfzfitqd.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtcqfrdcco.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtladgujbw.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gtewmgvpkh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtnwipdaij.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtnpejjzge.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtqgefnmrh.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gteybgjjyc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gttylsceys.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqavtneg.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gtrzpjukej.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gtvkybspah.html

class A: Base { override func f() {} }
来源：http://dali.ivvv.top/Article/details/gtyponezyo.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtryuvwusf.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtjvyqnuni.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gthgpjyizp.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtmmhlpgfm.html

[T29] Swift：guard 提前返回
来源：http://dali.birdmap.top/Article/details/gtpxqxmmqg.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtjndomuhc.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gteyokdbca.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtklsdecln.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gtwyuqgrpk.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtawbrcdbd.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkysteuc.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gtlfuufsva.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtdkdhtmri.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtaltdkmbc.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gtmumhpary.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gttxvftpad.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtxapbohdl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gttqxpqbxj.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gtvgkdsoow.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtxqvmitku.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtiyplilom.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gtltheywrf.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gtmwycapga.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gtnqfkvahx.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtlplalaxq.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gtodbxvodb.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gtowxwgkfu.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtffjxxott.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtyhjvhmxj.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gtogtignzh.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtsshpoldy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtriqjqtfj.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gttgretmep.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gttfolqygt.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtinkrvnpk.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gtkvublcgc.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbejagbpd.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gtnntqzpok.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gtqowdhpza.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtklcryhqj.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gtlbzimbbx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gtlstctdfp.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtasgfcops.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gteealsbte.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gtamhfasgq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtkktdrqoa.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtbpkdbsjn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gtvifhraez.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcifvkhwu.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtumpioeux.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtjynkslqt.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczmdrpuy.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gtoyqpwolm.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtrovtkvbf.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtzfmbmxqv.html

[T54] Scala：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmawkidfo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtokiwcsoe.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtxfyszmdy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gtptpzxcay.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtczhndlzd.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtylkyewkp.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtbtlnrxaf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtbgpszqxx.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtjlqczsyn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gtpbxcgjmt.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gthmddgjch.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtyyunvbht.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gtddxjhztw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtfooscxfk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtstgyebiu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtmqlcqgfm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthczmparf.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtketiaukc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gtdhismdyn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gtyhybqybw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gtocgkdpqw.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gthurnnygr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnqzz.top/Article/details/gtuyeftgik.html

[U04] Py：变量调试打印
来源：http://dali.hysaishi.cn/Article/details/gttrwhbelf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gtebakpdoc.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gtreejeduo.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtnahqbswr.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gtgswgqrem.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gtmyasllxz.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtshnwppey.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gtpdgvhqsd.html

[U08] Py：展平二维列表
来源：http://dali.jqgufenzy.top/Article/details/gttimvpxzq.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gtlsbjdkpx.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gttzesekbh.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gtnoiabtlo.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtbjndnrqt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaetpqbn.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtmkxztlxq.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gtltzolinn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gtjdrgjslg.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtftbaxths.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtyjdncdec.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtyecosbzt.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtvzzeqtor.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gtlcqzulaf.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtiucigore.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gtrjahukww.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gtlreodcuo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtkgwumexd.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gttkywezqt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gtainxbwbe.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gtcfxcglvf.html

pat = re.compile(r"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsrigszs.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gtrhtmthmd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gtoyhbpdpr.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtrvbsvotx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gtuwomyero.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtcioejuqt.html

@contextlib.contextmanager
来源：http://dali.yuanzhike.top/Article/details/gtjfbaudrr.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gtdvfokjuf.html

list(zip(*m))
来源：http://dali.cdnleiting.top/Article/details/gtezkgjlgc.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gtklyegrcu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtvzjfcnzv.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gtbbmfqktd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gteyumggxu.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtlxldudwe.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gtltjdlcee.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gtgvohjsbh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gtvazsmuoo.html

[U27] Py：异步 HTTP
来源：http://dali.tanke756.top/Article/details/gtgtzfiymk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gtdfepunlz.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gtevvrmmuy.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtfeeysvrk.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gtmqdetfso.html

@property 与 @x.setter 配合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzmxkdya.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gtgvystjng.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gtgdgekmiz.html

[U31] Py：单测
来源：http://dali.quarkkingdee.top/Article/details/gtukbpxnah.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gtioqwmxqn.html

[U32] Py：代码格式化
来源：http://dali.dashuyun.cn/Article/details/gttefrqmbv.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gtqmulvbdh.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtpldqewfl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gtfeieihug.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtqcqjblkn.html

chardet.detect(raw)
来源：http://dali.xuanzx.com/Article/details/gtwfeauuju.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gtsivoeumf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtxntosojq.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gtcryghftk.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gtlghtoeky.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gtdifvlqdj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gtbmtpesad.html

[U38] Py：获取脚本所在目录
来源：http://dali.iojbl.cn/Article/details/gtfomrydbz.html

Path(__file__).resolve().parent
来源：http://dali.jqgufenzy.top/Article/details/gtkivnxmid.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gtjgcdopws.html

sys.stdout.isatty()
来源：http://dali.cqqwz.cn/Article/details/gtvziugaix.html

[U40] Py：打印到标准错误
来源：http://dali.daria6918.cn/Article/details/gteaxhrjoh.html

print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtesfofcut.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gtbsobfjgr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nwbrower.top/Article/details/gtbpppwqpa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zdqjudy.top/Article/details/gtsgqmsphf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtkghcvmsd.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gtjzbswpbw.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gtlncbqeok.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258888.top/Article/details/gtznnwrrlf.html

declare(strict_types=1);
来源：http://dali.sysykeji.top/Article/details/gtcrwzrijq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tian-w.cn/Article/details/gtosuibbdv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtyzufvvua.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gtgfcvgvqk.html

?string $name = null
来源：http://dali.cheryme.top/Article/details/gtsqypozaz.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gteuxguwdh.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gtfqtwdzqi.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtosttybtt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangdashe.top/Article/details/gtewnulmad.html

[U49] PHP：只读属性
来源：http://dali.redwolf501.top/Article/details/gthztrlzuq.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gtuhmsrtkz.html

[U50] PHP：构造器属性提升
来源：http://dali.jyoumei.cn/Article/details/gtegcbddcp.html

public function __construct(private int $id) {}
来源：http://dali.jlsjyb.cn/Article/details/gtvukzrpqg.html

[U51] PHP：数组解构
来源：http://dali.cucudq.cn/Article/details/gtczomfkuh.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtjcjmpzmq.html

[U52] PHP：箭头函数
来源：http://dali.havefunace.top/Article/details/gtszdnhxvg.html

$double = fn($x) => $x * 2;
来源：http://dali.tian-w.cn/Article/details/gtdlrjiveo.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gthfckjvdo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gtrcgwbdcy.html

[U54] PHP：空安全调用
来源：http://dali.yj202588.top/Article/details/gtfdxdxica.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gtpgqrhuev.html

[U55] PHP：match 表达式
来源：http://dali.aizwys.cn/Article/details/gtjenbkimb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuxming.cn/Article/details/gtkblmivir.html

[U56] PHP：命名参数
来源：http://dali.sweek.top/Article/details/gtyjozocyr.html

f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtestwkxzi.html

[U57] PHP：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtyfvjrmxc.html

"值: {$a}"
来源：http://dali.redwolf501.top/Article/details/gtppooqxyn.html

[U58] PHP：数组三件套
来源：http://dali.sufxvd.cn/Article/details/gthcihcdwr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gtxntdjmzw.html


<!-- 参考信息 -->