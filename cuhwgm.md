代发 wailian999

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gtofqnkbtz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtnxjikabu.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtfflqqecg.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtnyajyucl.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gttdrotcrw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtpqtkkuwg.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtkqlrrrov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gtcubhzuer.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtghcpidfz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtlkdqdagf.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtkkieafqj.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtqlcbodkh.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gtmtvminls.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtjnnrssvs.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtikuzyhdb.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtxkzwthnn.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtsgldlilv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtporhngwg.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtoxhqkzit.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gtlebvdqki.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtypteyqqy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtbtjvrlhh.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtwtveeudp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtkyfxjwwz.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gthpxqssxi.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtiznnzrmp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtvbnbcxke.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gtavsapddq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtkpxuzarl.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtbaedqzlh.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gtccboakll.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtnyqnlirf.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtjnebtlcq.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtdnkgivze.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gthqvbdgej.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtuiyyzuuq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtejfrbthq.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtxzmndjqf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtjonljltj.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gtgmxcbcyo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtcqahtjhu.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gtnalypiwo.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtftwchfjt.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtcljremqu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifehdfqk.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtflzelvkl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtrdymbcxb.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gtghvsupzu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gthuvvjcom.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtolsgfsap.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtfndifwwe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwlcuavzr.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtazwuimzy.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtqthzggnf.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtxkcwlwok.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtwvrjyaro.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtutfpzrip.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtpkydkfgy.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtuzulnagn.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtdoqlxgdg.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtadftqqpu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtezpygfwq.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtvzvljvtd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtexdaoyxd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtedartpqw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gthmdpqaoc.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtuhqlkumg.html

data class User(val name: String, val age: Int)
来源：http://dali.sweek.top/Article/details/gtczwdgqui.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtcsmmmqil.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gttrhnqjjl.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtttuckriv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtrxmovhug.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtdaeawygn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtahakbcee.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtgchheezv.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtudmnkyxr.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtobnloskr.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtackrlgck.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gtvkcpoeet.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtelgnoqvd.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gtbffgpdwn.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtwanbkvmp.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtmljcktqt.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gttjpyozza.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtoemkyzov.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtdjturfsj.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtcfcssnqj.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtlzpytinb.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtnegasxcn.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gthgnhomsn.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtovrblbzy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gttpynuemr.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtyrxukldo.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gtrmxudpvz.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtshfkfiiv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtkxlbljzs.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtnsvezhov.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtjrmkkmra.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtmzzqszjt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtqxvdpajn.html

[T25] Swift：结构体
来源：http://dali.jianghu66.top/Article/details/gtckesdsor.html

struct P { var x: Int }
来源：http://dali.yongpay.top/Article/details/gtovvuyvxf.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gtriabomdm.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtohtnwsdb.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtuctxbhwn.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtenhcbqdc.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoogifco.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtidtlknux.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtbpcrnayu.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtagjzbohm.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtelhdgrtw.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gthpvvftrw.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gttkzqmxrj.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtrlkonlza.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gtpberhuqo.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gtfilxoizn.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtfcqjcllt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gtdnjlgugl.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtchpxkvxa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtxsdaldcp.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gtkosrglcd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gtvrmxdbmw.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gtuwhwucsf.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gtymaldfui.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixbvmngi.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtgtclugia.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtlowfwgin.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtprpobbkp.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtfytqpnwe.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gtnoovecgx.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtgmhwkxcu.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtajmetvix.html

[T41] Perl：Hello World
来源：http://dali.redwolf501.top/Article/details/gtamubeyhz.html

print "Hello\n";
来源：http://dali.fzhhl.top/Article/details/gtaouaixfz.html

[T42] Perl：变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtkplkxzxj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gtnikdrpzu.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gttgzhtwdw.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtqgblrspk.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtviiuuqaj.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gtthiuezav.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtooszqmlw.html

for my $x (@arr) { print $x; }
来源：http://dali.ivvv.top/Article/details/gtenaegfmb.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtiosoeoaj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gtudlvoyye.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gtubkjfngs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gtsgbkgipi.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtzmkaexbz.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtrkfbvzie.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtrsxznudk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtbgnnfvqv.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtlxveiawb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtdoujdyxj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gtispghfri.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gtpcuichle.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtcbozoslh.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtsksyxlwg.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrrsimnh.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtvwlynxzg.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfrhaess.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gtosyeknit.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gtzzdtrxse.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtbmejnooe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gtjjxfexnt.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gttpkttmix.html

case class User(name: String, age: Int)
来源：http://dali.ybcxt.top/Article/details/gthepiekhn.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtsdkvskew.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsndhcohs.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gtbplufrde.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtlnpnhlgs.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gtfvncvcdl.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtgmkjnlfc.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtkorlipem.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gtvproaphk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdiebveyj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtewggonqu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsdycosy.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtardusapu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gtzzvbglzg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gtfwurmpmd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtesyiwxzv.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gtvpzhhquz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cqqwz.cn/Article/details/gtwddxyvmw.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtvbnsscer.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shuidangran.top/Article/details/gtvsracbrv.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtfoacxstp.html

list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtclhotxdn.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gtadkrgkmx.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gtsvdtfngu.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gtlfkjjspb.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gtrldpfurl.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtrdxrqebx.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gtjlssbwgu.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gtzyvzxlrx.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gtvtaaaauz.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gtuyphcasz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuanzhike.top/Article/details/gtuyhachuk.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gtwqjuljtw.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gtcvtazbhg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yongpay.top/Article/details/gtonjexovz.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gttvmsntuv.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtbxfklfnr.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gtmqvbajoc.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtwygihqxx.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gtgvyuvqmv.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gttqfxmmbd.html

t = time.perf_counter()
来源：http://dali.cashguo.top/Article/details/gtytnmxblg.html

[U16] Py：命令行参数解析
来源：http://dali.dashuyun.cn/Article/details/gtziuphxog.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gtigphjnol.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfmktpks.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gttzopwull.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtryatmtjb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtrlwrtbci.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gtpfwvuacj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gthszbwwfg.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gtxxqdiedo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gtzdwcqjfs.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gtnxrgitex.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gtrqdcolfc.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gtnnwxmuwt.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtlcpobiym.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtmyixmzya.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnxiangtu.top/Article/details/gtyyybueab.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtvdqcpxhx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtcenpiism.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgfzy.top/Article/details/gtunjdumrw.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gthrnebeuu.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtqlkfzkns.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtqnudfesq.html

[U27] Py：异步 HTTP
来源：http://dali.tanke756.top/Article/details/gtjlobjvkh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.andypj.xyz/Article/details/gtdejcvufo.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gtdblmjawo.html

UserId = int
来源：http://dali.sufxvd.cn/Article/details/gtuxttgzkp.html

[U29] Py：属性校验
来源：http://dali.xylfe.cn/Article/details/gtlldctzjf.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gtvafouwau.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtukbncuiv.html

@dataclass(slots=True)
来源：http://dali.svipenyu.cn/Article/details/gtpnuxautu.html

[U31] Py：单测
来源：http://dali.shangyingyoupin.top/Article/details/gtyrcykbcp.html

python -m pytest -q
来源：http://dali.xziqi.cn/Article/details/gtaijxlqvy.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gtvsrgadrl.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gtheitggoo.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gtbmmnywdy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.kuanghao11.cn/Article/details/gtifpdfubs.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtgoxmjyps.html

chardet.detect(raw)
来源：http://dali.tianlin.xyz/Article/details/gtwgfphsql.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gtcprwdbwv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwnmsvhv.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtwoejtfxl.html

schedule.every(10).minutes.do(job)
来源：http://dali.yueranfly.top/Article/details/gtchcfjfqq.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gtltwmnnao.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gtwggdqzrx.html

[U38] Py：获取脚本所在目录
来源：http://dali.yongpay.top/Article/details/gteqadyrhc.html

Path(__file__).resolve().parent
来源：http://dali.wangshuangyany.cn/Article/details/gtetuvrgtw.html

[U39] Py：判断是否在交互环境
来源：http://dali.sysykeji.top/Article/details/gtoxvevaov.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gtgwpuusow.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gtmpwetcgj.html

print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtjuyngiyq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gtnfhauvlg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258.top/Article/details/gtxcdqetqy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdeyuzov.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gtzimhgmgn.html

[U43] PHP：声明命名空间
来源：http://dali.tanke756.top/Article/details/gtloldshyy.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gtrgxgohod.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gttcwzhxob.html

declare(strict_types=1);
来源：http://dali.vqdsnc.cn/Article/details/gtvrjsfdim.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gttqhpnuls.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtmrngdhbr.html

[U46] PHP：可空类型
来源：http://dali.quarkkingdee.top/Article/details/gtigypvxas.html

?string $name = null
来源：http://dali.dianchejie.cn/Article/details/gtuqblifjq.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gtjmlcwqjl.html

int|string $id
来源：http://dali.quarkkingdee.top/Article/details/gtkxhqarhk.html

[U48] PHP：纯枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyjndhqr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gtegdlpqcy.html

[U49] PHP：只读属性
来源：http://dali.shuidangran.top/Article/details/gtmxdqblwt.html

public readonly string $name
来源：http://dali.hfpthk.cn/Article/details/gthimnwdee.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfextcfo.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtsavyftrt.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gtkwtfgtpi.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gtbphjeukn.html

[U52] PHP：箭头函数
来源：http://dali.cashguo.top/Article/details/gtrvmxyjvt.html

$double = fn($x) => $x * 2;
来源：http://dali.0kj1m.cn/Article/details/gtotzlnbie.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gtkkxytutz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtedfnuwtc.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gtbzjgweem.html

$obj?->method()
来源：http://dali.gzhubu.top/Article/details/gtfwtzuayy.html

[U55] PHP：match 表达式
来源：http://dali.jiagoushi.top/Article/details/gtjbmmidmv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sxryk.cn/Article/details/gtstoipxml.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclgujeui.html

f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtnwmndfes.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtxisteifv.html

"值: {$a}"
来源：http://dali.hammf.cn/Article/details/gtatqiwprj.html

[U58] PHP：数组三件套
来源：http://dali.cheryme.top/Article/details/gtuclrlart.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtdecvrpwm.html

[U59] PHP：自定义排序
来源：http://dali.sxryk.cn/Article/details/gtsdzsulza.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtwjmdrwza.html

[U60] PHP：JSON 编解码
来源：http://dali.shangyingyoupin.top/Article/details/gtmwipbakp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gtrxilrltx.html

[U61] PHP：正则
来源：http://dali.shangyingyoupin.top/Article/details/gtliilfoyg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtajyqmosy.html

[U62] PHP：日期对象
来源：http://dali.chenlongwang.top/Article/details/gtlqztmzaw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.iojbl.cn/Article/details/gtzkhgcphh.html


<!-- 参考信息 -->