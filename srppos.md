代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvvuknkc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtgnfdcoax.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gttxajfqfg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gtyxowdniq.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtuuyafovr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffanaywx.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gtvomsncia.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtzatlqibb.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtomaemcyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtlimlmjfp.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gtksvlmufz.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gttqvzkyqi.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtfnjhxrlc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtxjnddmbe.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtihhizrkj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gthotmrtxo.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtjcyzjnai.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrurfzaji.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtijnbajkj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtmramylmd.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtxehcndbi.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtafbecpoe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtinnsookm.html

[S50] C++：格式化数字
来源：http://dali.sxryk.cn/Article/details/gtjzyontza.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtvlcphxjh.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtncftaehf.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtrknlhreq.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtirfuyrpk.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtjphjonhk.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtjmifxoxo.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtjpscnmmq.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtqtoxfatk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtewaqgxex.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gtbaqnosbt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtjkvoshtl.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtqpidnvwa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gttyyqpxes.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtvetdztnv.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gtqaatrrqh.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhyypiut.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gtsxxxhqqj.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtvlmqbguf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtadvqqyyg.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gtyqvxswup.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gttltwdjcg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvectysad.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gtirnqddtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtuldjudoe.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtentquagk.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gttyjfumss.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtwfuiegen.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtppglfwoq.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtcxuveobu.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtaedvgolc.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gtnkcmwssm.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gtkgmiqgdq.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjhajaek.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gticjjkrcs.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtcsutnrmd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtuuuxghaq.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtrexglakw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtumilhehp.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtuvzuwjbm.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gtawoabtge.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtiekgsuxm.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gtxkotketi.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtdbnctvrf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtuxfbbysd.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtrafsmmlk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtxswjpqjf.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtszqqrzho.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtbnfcqpvi.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gthympzjfi.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtghikapgq.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtaqndenss.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtepzpdysj.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtzetikjli.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtfarzlizq.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtybrvomgp.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gttcsiumen.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gtazfnrhaq.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtdiftopan.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtogrblfhc.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagblqsmr.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkdnadlf.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtzeyhjzol.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtlcuihilv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gtruolmgtd.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gtskczxyvl.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtlfxjxnty.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtsuoebbtn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtzbvegovh.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gtgvsawomn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gtrfyoyqgg.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gtuyobdqnu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtyhpnosne.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gttnelyswo.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtoacouquz.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gtrojnozvg.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtgvuaumpb.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtsnekigup.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gtbscabvxa.html

[T28] Swift：枚举
来源：http://dali.guannengcc.top/Article/details/gtutwilxoo.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gtghuqtthh.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gtwxioacxj.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gtpthiegjs.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtatlolsgj.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gtrzrotmot.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gtcvuuiovu.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtjsapfkjh.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycrqjwkc.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkrfvneu.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gthuicqwta.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtmylyxtwh.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtwyodadxa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gtiemotbob.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtrdjifwzy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gtdnkhlxna.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gtfwihsmzc.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gteymxktqm.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtnzdfjfce.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gtvddykmds.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtlnfuxocz.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtcbwrhewo.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtdjeztgof.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gteiachjzn.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtwrfumgue.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtxvicdkfw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtxmewqlno.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtsfogcioa.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gtjmtoogvq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtiaevfmlt.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtkaysquuf.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtpjziirss.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtdygjkeau.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gttedakgqo.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtxfdbygrl.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtbqznvqxb.html

[T46] Perl：哈希操作
来源：http://dali.yanxiufei.cn/Article/details/gtohswzjlh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zdqjudy.top/Article/details/gtjazaxdfj.html

[T47] Perl：正则捕获
来源：http://dali.sysykeji.top/Article/details/gtigxcamdi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtygxpywux.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtiqtrhnzl.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gtlbwgftzp.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtjocvumkg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtsvcoiend.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtcsdfqpkt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiydlndcj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtnxvsveor.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtgvwxokjj.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtvdmigsvr.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtlansowrq.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtdwjhcucf.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtvkwppipe.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtfibpkhsu.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtzotwllie.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjgqjdkt.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtrbhvabff.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtglavexly.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gtcfiiauwn.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtjuecsgvi.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtiygfhbcx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gtkzifixhg.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gtisgvyrhg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtreotheak.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtfzccozzs.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtnuvhsspf.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gtnvnafnzl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gtwsmgtzov.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtoorxpotg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtzvopomia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gteiizuqkt.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtolxmcwna.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yueranfly.top/Article/details/gtiqmywsfl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtlfxvxspl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gtxfbdvaeb.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtrahgnazk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gtpxqramzn.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtodkhqhzg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtkacvnmwy.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtjukoowem.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtlpvfoaxh.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gtpsclqykv.html

{**a, **b}
来源：http://dali.316326.xyz/Article/details/gtihypirug.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gtfvrtghjy.html

{v: k for k, v in d.items()}
来源：http://dali.wangshuangyany.cn/Article/details/gtsloaxjdz.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtslmbziom.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwfvonzc.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtfsoavoxg.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gtykibrvmt.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtrgcyomza.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangshuangyany.cn/Article/details/gtizwpzcap.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtkrmworhw.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gtpwbqbwle.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtafzsocvf.html

Counter(arr).most_common(3)
来源：http://dali.jinqigufen.top/Article/details/gtlmdtynlk.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gtqzvorsje.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gtahxcmxgl.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gtwfllyvig.html

defaultdict(list)
来源：http://dali.316326.xyz/Article/details/gtjbfeucqr.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gtvufbonvd.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gtrlidmqfm.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gtjvggeuig.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cheryme.top/Article/details/gtnpunrkyn.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtrkyrjmta.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hfpthk.cn/Article/details/gteukpxplx.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gtheuhbdfj.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrrbgwfn.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gtdbsfmjav.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtzlgproyw.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gtpiczveeo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gtipanidnu.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gtcetlcetv.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gtcnsjosui.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtfltyirir.html

list(zip(*m))
来源：http://dali.jiagoushi.top/Article/details/gtqbkniwdg.html

[U23] Py：分块读取大文件
来源：http://dali.cucudq.cn/Article/details/gtwxcydqtr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gtvdfjmhay.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gtsfobkbgl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gtwjewxrkm.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtnescvvrn.html

csv.DictReader(f)
来源：http://dali.jinqigfzy.top/Article/details/gtehcffslh.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gtydmlmdcg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtsojcqcdi.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gtjevtjvns.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gtrcdcwcre.html

[U28] Py：类型别名
来源：http://dali.wangshuangyany.cn/Article/details/gtjocftnfg.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtghftdggl.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gtrfzktvxp.html

@property 与 @x.setter 配合
来源：http://dali.xinyue.icu/Article/details/gtvldwgfmw.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtvsnvmjnm.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtgpuqhtfx.html

[U31] Py：单测
来源：http://dali.xinyue.icu/Article/details/gttftjaagh.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gtubzevqij.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtdechsl.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gtpdljwbld.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gtxnzgebrw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.quarkkingdee.top/Article/details/gtzxayqfet.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtsryhlvww.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gtmeczlxvz.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gtcjljshdi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gtusxgnfbj.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtfdmlysgv.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gtymgvzyut.html

[U37] Py：读写 Excel
来源：http://dali.wangshuangyany.cn/Article/details/gtwtrzswyf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtebuxeedm.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gtfuagrmzg.html

Path(__file__).resolve().parent
来源：http://dali.jlsjyb.cn/Article/details/gtlnjvsnqu.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gtfmclhuxp.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gtckodpimt.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258888.top/Article/details/gttsczodbd.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gttpneoouk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gtmwtaaibk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aibaodan.cn/Article/details/gtihinqxvk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cucudq.cn/Article/details/gtavpqdmsg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gtwqzhvgwx.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gtbqfsiorp.html

namespace App\Http;
来源：http://dali.chenzaomai.com/Article/details/gtyotuyxdj.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gtmsaelqql.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gtdomvixup.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgfzy.top/Article/details/gtussqbvil.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtlsahdwzg.html

[U46] PHP：可空类型
来源：http://dali.bjfxy.top/Article/details/gtetvukegn.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gtlygjrnpg.html

[U47] PHP：联合类型
来源：http://dali.mhx1999.top/Article/details/gtbihtcdbf.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gtthizoryr.html

[U48] PHP：纯枚举
来源：http://dali.xziqi.cn/Article/details/gtswsbzhcz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgfzy.top/Article/details/gttxkpczav.html

[U49] PHP：只读属性
来源：http://dali.tianlin.xyz/Article/details/gtgxfhaqex.html

public readonly string $name
来源：http://dali.cheryme.top/Article/details/gtrnitbtyr.html

[U50] PHP：构造器属性提升
来源：http://dali.zdqjudy.top/Article/details/gtbpojksxu.html

public function __construct(private int $id) {}
来源：http://dali.aibaodan.cn/Article/details/gtaknqdyev.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gtgegwiaek.html

[$a, $b] = $arr;
来源：http://dali.havefunace.top/Article/details/gtiyftcrmo.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gtoeesvnju.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gtgsfjjocn.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gtphboplle.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgfzy.top/Article/details/gttgqutqng.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuxacmwo.html

$obj?->method()
来源：http://dali.jianghu66.top/Article/details/gtxcotcdfm.html

[U55] PHP：match 表达式
来源：http://dali.daria6918.cn/Article/details/gtkfxraezf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gtrexujaxn.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtwiqwlokc.html

f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtsquypwpv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtrnsobvdi.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gtflwcqare.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gtgodacgpw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gthrregxog.html

[U59] PHP：自定义排序
来源：http://dali.ivvv.top/Article/details/gthsfakzcm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gttcffykpm.html

[U60] PHP：JSON 编解码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnutzygc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jlsjyb.cn/Article/details/gtlgpxnamo.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gtzipwkuud.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtcvovckpu.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gtfotzdwur.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhiwuduotai.top/Article/details/gtvsqsjplx.html

[U63] PHP：文件读写
来源：http://dali.ydzc1.top/Article/details/gtpgilziws.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aibaodan.cn/Article/details/gtljkydeys.html

[U64] PHP：目录遍历
来源：http://dali.cheryme.top/Article/details/gttkbuwfwa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sxryk.cn/Article/details/gtjjktraih.html


<!-- 参考信息 -->