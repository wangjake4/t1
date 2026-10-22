代发 wailian999

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gt2ytwzocyo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gt2rtaawsmc.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gt2qkyzmpxg.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2mfwzztdy.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gt2nbolkeie.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gt2kffvdehx.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2ibjzfqld.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqgubagl.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2qcgzetqs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gt2mkbjebgu.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnfwdwjd.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gt2lmabqsmg.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2gjtmldjn.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gt2vzxdgxux.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2wpvqrhek.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gt2urlryjpd.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2cainsxac.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2qkbkdfqh.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahovylfh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gt2skahwfuo.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gt2dxsgqons.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gt2uzptklly.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2veaqtpyz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gt2tyvzduvb.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gt2pztvqqpj.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2tphtenlb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gt2czbxxeyy.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gt2acjrytng.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2jfipzorf.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gt2gaywfxkp.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gt2tpdwckoa.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2omrimnjd.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gt2xowkdgyx.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gt2lrtkvfuc.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gt2wqlmalco.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2ufnpvvvj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gt2bnzkciqv.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdixzlrk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2taljrvdo.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gt2xmnuiimy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2budruvtq.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gt2zvduwvli.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2hofzlspm.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfhjcyqk.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gt2hweuxzih.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gt2pogtgqwk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gt2puaraouu.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2mawxzlds.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2qoatskdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwdrcmb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2fmdzhkdi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qgzvmbbl.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2wtavyhve.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jklovimd.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2jedjihfd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwzvoal.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gt2fdwlqorn.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2xfejobkg.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gt2wzomzzwk.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcegdjfn.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gt2vbxhivkz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gt2zwnnykto.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2tzhdrrfe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2fxfoajbp.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2pvwkghha.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2dzjrwzon.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gt2sylvirug.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhipumog.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gt2kcbcwhxk.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2zaizxzsv.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gt2nzfylcyi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gt2davsfnts.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gt2vicebchl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gt2yiivusom.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2dhsjecup.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2iffhxmra.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gt2ixhbxukw.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpitgnkz.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gt2ugcbavco.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gt2dvhwleko.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gt2sihcupfy.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gt2oovesyad.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2rxutmwye.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkwohwyr.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gt2hccyuaqn.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2makcgeha.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugdsyuyt.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gt2sspghscr.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gt2ujvrbtqm.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sggixeqb.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gt2sdfxubzn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gt2oxbsenhn.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2bnbeiyip.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gt2bavdgnpf.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gt2fsbquuoi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gt2jozjljcd.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnbbmuqd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gt2yhcgksqm.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqfqfapm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2cqbmfaas.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2atxdkkia.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gt2jluosffh.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gt2ttxrxhpm.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ookywzyf.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2fiumczqr.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gt2thhrsryw.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2njxrdhxg.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gt2fstklerh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2uoduzdzr.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gt2ukzjlboi.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gt2kqijkowf.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gt2pfgpbjow.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2echsetfx.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2feheaxqu.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gt2atwflcxz.html

local a = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxyxiops.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zinbskzp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gt2dscpyveh.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gt2kmvlptni.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gt2nizwvwcm.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gt2jhmmndbb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2yqjslalx.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irysgval.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqmejohy.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxhegmut.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2vaolnwqf.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gt2bgscmpad.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gt2vgmynikb.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gt2bjomwedi.html

string.find(s, "%d+")
来源：http://dali.daria6918.cn/Article/details/gt2exuerasu.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozenddth.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gt2yjnmynjm.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2fwcrlqzp.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmiyhvoj.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gt2uxethays.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2xczlthko.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uuwkorjn.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gt2dznsucse.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gt2feipomjf.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gt2curoadnr.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gt2rimycnxb.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gt2xuhtuflp.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gt2jarhehts.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gt2gyoejqvu.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gt2zecxgyao.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gt2upwtpeyc.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gt2lqctdoed.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gt2bsdlkclm.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gt2iltfdbvw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2keaxwakm.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2qvlxpeps.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.meibo888.top/Article/details/gt2exipnfvs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gt2hfmipfic.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2eybvaxpa.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2wikpbafw.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2vimatlsi.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gt2yjvrrhqq.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gt2borlldry.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2maractfn.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2fnmfaene.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gt2jmbnfgrm.html

[T55] Scala：集合过滤
来源：http://dali.ivvv.top/Article/details/gt2nedkwiuq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gt2cpigqmpx.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gt2fhjrcner.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2edkgvdwn.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2colbkjea.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gt2rxjuhikp.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gt2gqpfpdjq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gt2ujeezust.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gt2teozimsw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2lshqulup.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gt2qencznzn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gt2upjaptnp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2gwfkvjsh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2kwgosrrt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2uzvrsugk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gt2ltjhoqax.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gt2bgxhguas.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gt2amnpeiec.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gt2midmbchm.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gt2steejlhc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gt2lnqkbehh.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gt2sgqwdyxr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2pzmujzwi.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gt2pvxlyfeb.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2erlllxql.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gt2gqlafzcm.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gt2iipqflbu.html

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gt2icmwmjls.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gt2itspppjc.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gt2eiygbbde.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzavtlh.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gt2hfsqmkce.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gt2woodquuu.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gt2jidljifb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ppjwa.cn/Article/details/gt2qczryuat.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gt2mtzjxruc.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gt2hfxyuzrr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gt2dwdponbn.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2gjmzenge.html

[U13] Py：固定长度队列
来源：http://dali.sufxvd.cn/Article/details/gt2zqkaxzkb.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gt2zfdcgtlw.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gt2dkdlqqhm.html

defaultdict(list)
来源：http://dali.ydzc1.top/Article/details/gt2jypzozdb.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gt2lwhqbbnn.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gt2ihigfqqd.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gt2nzibgnle.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yanxiufei.cn/Article/details/gt2bodxlset.html

[U17] Py：初始化日志
来源：http://dali.sufxvd.cn/Article/details/gt2nejxiyur.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exqtxdbr.html

[U18] Py：预编译正则
来源：http://dali.tianlin.xyz/Article/details/gt2mtrhgaiv.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2bvjnztxk.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gt2ionlchxd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxmvkdkb.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gt2xvzleyhe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gt2pldfwvhv.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gt2fguejnyf.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gt2awhdrmlj.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fngmvhvq.html

list(zip(*m))
来源：http://dali.yangfankeji.com/Article/details/gt2eviuyjwm.html

[U23] Py：分块读取大文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abxhycfm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gt2idjgbkan.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gt2unkhgyuz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gt2meojdqen.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gt2gplmfomq.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gt2hhnnjadz.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gt2zcbwlimr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2vkxioeki.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gt2enwnvecy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gt2gezstjwk.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gt2ujsqdgvo.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gt2aetpjwwa.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gt2injnkknp.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gt2wkqchjuy.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gt2tjydarzv.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gt2toawshru.html

[U31] Py：单测
来源：http://dali.daria6918.cn/Article/details/gt2koyvmico.html

python -m pytest -q
来源：http://dali.jiagoushi.top/Article/details/gt2vppfhrvg.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2unpxwsgx.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gt2jkqprqnr.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gt2gjvarrjb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gt2ghycopzj.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gt2tbfrzfda.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gt2ixbdduoq.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gt2iozzrtey.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jyoumei.cn/Article/details/gt2uvljbljp.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gt2sngrvjrm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfehlfwc.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gt2nhypbqsf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gt2xosdufnv.html

[U38] Py：获取脚本所在目录
来源：http://dali.gaohongyu789.top/Article/details/gt2hplutfhn.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gt2stxrknmt.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gt2twormasl.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gt2mfqhkaui.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gt2mhjfazww.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2ylyfyjcn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gt2imtufftf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gt2gkdufatu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gt2vwtvkvwt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gt2dodpdymx.html

[U43] PHP：声明命名空间
来源：http://dali.zhengqikj.top/Article/details/gt2eemzzpsw.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gt2cswxvizt.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gt2kzlktclv.html

declare(strict_types=1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqpqjfdd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xziqi.cn/Article/details/gt2qzjqljti.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2mlvctkfm.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gt2aapienug.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gt2lwokgerc.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2aiwwdxku.html

int|string $id
来源：http://dali.hysaishi.cn/Article/details/gt2exbitook.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gt2osqvfvbf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fengsongda.top/Article/details/gt2hipchial.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uucexhtw.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gt2btmlowco.html

[U50] PHP：构造器属性提升
来源：http://dali.hysaishi.cn/Article/details/gt2sjeqdxmz.html

public function __construct(private int $id) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rnbkgbxp.html

[U51] PHP：数组解构
来源：http://dali.sysykeji.top/Article/details/gt2blwxujlj.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yznplioi.html

[U52] PHP：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gt2bcdcnjvs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnwwantr.html

[U53] PHP：空合并运算符
来源：http://dali.yangfankeji.com/Article/details/gt2pugaguwr.html

$v = $a ?? $b ?? "default";
来源：http://dali.smart0.xyz/Article/details/gt2dkoqusjh.html

[U54] PHP：空安全调用
来源：http://dali.chenzaomai.com/Article/details/gt2cevujtpq.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gt2betrpnhi.html

[U55] PHP：match 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2kqofvjwg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gt2mwmhxzhi.html

[U56] PHP：命名参数
来源：http://dali.iojbl.cn/Article/details/gt2donkgece.html

f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2uibvuxqz.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2hckcmjqr.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gt2qqbrxqtk.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gt2oygxckfq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2mtnvtrqc.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ooubbntb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gt2ymuotvxy.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gt2apgrhxft.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gt2qpjikqph.html

[U61] PHP：正则
来源：http://dali.jinqigufen.top/Article/details/gt2jeyhbbrs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2axwcqiqs.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gt2qvpqheer.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258888.top/Article/details/gt2svfvikhe.html


<!-- 参考信息 -->