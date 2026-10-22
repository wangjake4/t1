代发 wailian999

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtxbopepeh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtcpdviber.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtklvuniyw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtkgamkvyf.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtvupecldy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtjrormtyn.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gtvzyvypqd.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtyvsdnjby.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtrsrqdeul.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtigxgyoei.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gtlkfdjvvi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtysphlpih.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtiptjetpz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtjstcyuct.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gtgjmmsjbh.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gtetvthucn.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtqxjssvik.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gtdfwmqbku.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtcpfysmtc.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtbxsksydc.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtvuqsvqwg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtjxehdkuc.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtkileexxb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtdnngkfzg.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtslrfvera.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtxyrdeylg.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtwaanbdwq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gtvbyixven.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtifpbcsmq.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtavibceqh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtylhhjjtr.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gtbojevhkq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgwdrydp.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtvibmculg.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gtdcdsicux.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gtxqiovlee.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmruvajfo.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gttyutkbfd.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjgguvhl.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtutrvgojy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtclhwwatw.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gtszttijez.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtygtcwhnc.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtcfywxkil.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtrzcfgsqj.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtlgpcncdg.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtqamcngrg.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtznfpyxfr.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtrhxuokho.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtmdvzhiwo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhongyouzk.top/Article/details/gturehthlw.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtnqoadjlq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtaizefyqr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvtqpdggs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtngnaieml.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtewnbjlyc.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtovlkcqye.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtivgvbzql.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtuyblfwwf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gthitksvsr.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gtaisasizz.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtkfzeryhw.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtntpshins.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtasosbgrw.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtymrazpzh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gtylpgteni.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtllheuskr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gteornwpfh.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gthptawsky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtjqfefpgt.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gtyltadbdp.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtbaljjfke.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtwlrsplaz.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gtsbzdouyc.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtmoaptpmj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtodjuehpw.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnxlmhqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtappbnylf.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtvscuhfto.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtjnmgljdc.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyfhgzhd.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gtzbcwgkhf.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtivpsiocu.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtmizuhujv.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gthkexppat.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtsvqtdmbs.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtrkgnprdm.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtryfiaavw.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtdvoxbkdv.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtordvvvwe.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtpknaqxyu.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gtvxvuomyw.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gtfrhauzbu.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtaleogtpq.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtzxwdgqlg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcvekcwj.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtnmodfddf.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtswutftkz.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtkgsqtlde.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gtolaooxwt.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtocueetgi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpabebzyy.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtodtikyht.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrnsdfwt.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtoutkdlog.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtdreppfma.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtpnnrynsi.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gtoomflnnm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtkgltthlr.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gtxawptkek.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtpjeeefih.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtutcxqnsc.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gtvnfufdpo.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtlzuimfaf.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gtwzjzcixo.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtumhdikwt.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtvgqegwnp.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtkqaxwqxv.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtdlrzjyvb.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gtqeahtnih.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gtqfmcksqq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gteitvnbdj.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtfbbbsbwd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gtxflkbhkb.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gtsithwkph.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtixzenzbr.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtwkppeiil.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyimobwl.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gtsdayjrxm.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtkmwzhqvi.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtlizdmzgb.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gtfjduuwxd.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtidhwzsxe.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtrfcoftci.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gtikrjjufs.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtawvczaic.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gtbmjirvyg.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gtvafqqfue.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtmftmypsd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtbnbhpjry.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtamujsqqg.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gtkcwqyqar.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gtrugkiabr.html

if ($a > 0) { print "正"; }
来源：http://dali.aibaodan.cn/Article/details/gtrrcqsgnu.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtdbrsrlpm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gtfyofchru.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtoedkfzug.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gtvbuzgayh.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtzcnutmtn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gtlucqorij.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gtsahjiopf.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtnoybpbno.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtccssltwq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlyxhjzhv.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtmaweokds.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shuidangran.top/Article/details/gtxhzvbmhw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gtfdmjlkzg.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtahwghppl.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtbmlftboh.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gtfzfvocgc.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjekuoum.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtzbsgurzo.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtvytutzuu.html

[T54] Scala：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtkpigomen.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtezbmmiag.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtvqpxsquf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gtawsikequ.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gthchvfwlr.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gthfvoikoc.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gttszdwtux.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gtmoicdrql.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gtpzhxvrao.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcrozfdk.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtmgfcxcxa.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gthoxvrxho.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtidpshrdd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gtzjkltqmu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjblwilzb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqubtmerw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjffmsnqj.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtkkngefgh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gterqjqssr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gtsupztozs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtuivmxvoz.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigfzy.top/Article/details/gtlwblnezr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtailvokbw.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtlmvgbhvo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtbhpmhvjp.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gttunvoskr.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtgutuqrhe.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gthbcljuyl.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gtsffhtrqf.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gtlytsdstj.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvjruztd.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gtbngbyzhl.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtcplfdwxc.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gtuzvrxrhy.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gtzvcnfcyi.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gtwxgvqnqi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhiwuduotai.top/Article/details/gtbuvtqgwj.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gtwpslzoel.html

(x * 2 for x in arr)
来源：http://dali.0kj1m.cn/Article/details/gtqgmnxiwt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gtrcruiogp.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtzpjqojgw.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gtdpavrcdx.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gthppiaqzx.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gtjfbczlfe.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtmsfieuzj.html

[U15] Py：高精度计时
来源：http://dali.c1oappe.top/Article/details/gthlblfzuh.html

t = time.perf_counter()
来源：http://dali.mhx1999.top/Article/details/gtzjsgttqo.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtmghuzbwa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gtjvscgbtr.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gtkfvqpnmi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gtkietpmdn.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcgzyapt.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gtgtnhzrrv.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gtfsrzuxaz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gtmsxepmjt.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzrsnjcl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.svipenyu.cn/Article/details/gtsubzyzww.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtiugxhkdw.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gteovchshe.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gtzeeepyrz.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gtlhdqaglc.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtkdwcmvnt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yanxiufei.cn/Article/details/gtasytnkwe.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gtvweqgwls.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikfhdjfw.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtcsarjebz.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtcrxrwxsr.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gtnyperbjq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gtcxqnqdex.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gtdsriuhhc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gtnygitalo.html

[U28] Py：类型别名
来源：http://dali.feifeiyinyue.top/Article/details/gtorextffr.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gttwnpnrcg.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtfgnmvuch.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gtrgwrztbv.html

[U30] Py：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtrnalssqb.html

@dataclass(slots=True)
来源：http://dali.birdmap.top/Article/details/gtbfokgmdt.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gtvmcbyhps.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtlaegnsjh.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gtpzrjbgyy.html

ruff format . && ruff check --fix .
来源：http://dali.aizwys.cn/Article/details/gtbswjkgsf.html

[U33] Py：打包发布
来源：http://dali.316326.xyz/Article/details/gtlmkxzdbh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.havefunace.top/Article/details/gtfucmhlpl.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gtmaegmfop.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjylvdxuc.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gtrxcqqauc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gtxnmyaqpg.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtqlaxlrmc.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gtckhawish.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gtmerzpzad.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.bjfxy.top/Article/details/gtphxinuwt.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gtzzyhiidv.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gtkuxutvzn.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gtcrjptngw.html

sys.stdout.isatty()
来源：http://dali.dianchejie.cn/Article/details/gtkbqahclq.html

[U40] Py：打印到标准错误
来源：http://dali.daria6918.cn/Article/details/gtxozkspws.html

print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtfkghzuaf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtdjqzzmvx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatkbvpse.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gtzvgxjatz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gtvvsbhqfr.html

[U43] PHP：声明命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreltjogj.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyyhsvam.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gtfyofqtkp.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gtajsmdwpq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtqmnfcnfm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtmgqkowug.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gtsyujnvwp.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gtanvvsyot.html

[U47] PHP：联合类型
来源：http://dali.zdqjudy.top/Article/details/gthwvpudue.html

int|string $id
来源：http://dali.ppjwa.cn/Article/details/gtefwdywhn.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gtfmbsyqap.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.c1oappe.top/Article/details/gthdqrkuik.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtmjdswfoz.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciabvscv.html

[U50] PHP：构造器属性提升
来源：http://dali.guannengcc.top/Article/details/gtpnpbvnvi.html

public function __construct(private int $id) {}
来源：http://dali.bjfxy.top/Article/details/gtkksrrwbd.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gtuglqblhn.html

[$a, $b] = $arr;
来源：http://dali.pycfn.com/Article/details/gtotxhgwxq.html

[U52] PHP：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gtuqqtcxxa.html

$double = fn($x) => $x * 2;
来源：http://dali.316326.xyz/Article/details/gtoffdagfi.html

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gtafxojdfa.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenjidiqi.icu/Article/details/gthqspmdsb.html

[U54] PHP：空安全调用
来源：http://dali.9152youxi.cn/Article/details/gtuucujmvf.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gtuhaegppb.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gtvdswyxuu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gtmrimrfwq.html

[U56] PHP：命名参数
来源：http://dali.daria6918.cn/Article/details/gtccmypaqo.html

f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gttxwxmrzs.html

[U57] PHP：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtdcyytpby.html

"值: {$a}"
来源：http://dali.zhixingplan.top/Article/details/gtcgxkzckf.html

[U58] PHP：数组三件套
来源：http://dali.jinqigfzy.top/Article/details/gttvacaqxs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ydzc1.top/Article/details/gtvvjkfznu.html

[U59] PHP：自定义排序
来源：http://dali.yj202588.top/Article/details/gtrgzfmuac.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtqvvehiwc.html

[U60] PHP：JSON 编解码
来源：http://dali.wangshuangyany.cn/Article/details/gtpzgqsuqd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cashguo.top/Article/details/gtjibaggne.html


<!-- 参考信息 -->