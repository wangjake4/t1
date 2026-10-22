代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2drkikfhj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2urroztqn.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gt2btnuqrxs.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gt2ddrgqeic.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gt2gbezvant.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gt2pvatnujj.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gt2rhhblugh.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfmfmhzk.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gt2uetfncmz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gt2mquqveew.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjnfhtbs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rlvhlsgy.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gt2jmjqwjlu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gt2agpdaibh.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsrrkfdu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gt2gyupcwik.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gt2usnajnnr.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlggkkuf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gt2gewnnusc.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2rtytoevb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2mszvoiwp.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gt2qjawibxx.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gt2tsimuzdd.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gt2ooyfzlep.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gt2kcpzarzk.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gt2qyytspew.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gt2aawnqidx.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gt2ayutezde.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gt2idbavcht.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gt2dqkkasbr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gt2iowjfjab.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gt2wgrylcyw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gt2cdzwtsev.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gt2ivpszxiv.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gt2pyigjhsw.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2qapsntwq.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2lxcznjbw.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irlaover.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gt2giilhhze.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gt2nlnjbqbw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbbjmnbc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2dchhzsms.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gt2rcpmevbg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2lfwieuyc.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2ntgpegrz.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfsoxnzo.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2ntllighj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gt2rhjhxoym.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnblqrxc.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2ihbqybvo.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gt2fdzugiwp.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gt2xyoveevp.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwgtdhuq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gt2dddeqgml.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2ltuvwloz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2ajhuavqi.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2enkhtdyb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2biwkdwhj.html

[T08] Kotlin：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gt2dckxpuih.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2eawkqniv.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gt2kauyiqow.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2armeoqgu.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2dmlnurfs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gt2zxvppyck.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2ueibeorn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gt2bmelnavg.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2fytxryvi.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2lgfaogyf.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gt2griyduih.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2tffsgqck.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gt2lkqzrpuj.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2cykivmvr.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gt2pxpnumgc.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gt2wrgpwylm.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2wbzlhqsq.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2vsycohls.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gt2dgabnibp.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gt2zisbwleg.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2jluqnhth.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2ijouhgrv.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gt2ohrtgqza.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gt2snaulhsf.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yniexnnw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gt2xatiyfaq.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gt2gqjjxwdf.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gt2bpxbgeqp.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gt2nbbjncuv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gt2arxnbiod.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2mwtkpghq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gt2tvkojdqo.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gt2ownnmatx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2hgzulbja.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gt2vsafngan.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gt2rwmqbbny.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gt2gsmtgxsd.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gt2nbbfyomu.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2chefpwyx.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gt2xfjmceop.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gt2gvrpriwe.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvleioyc.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gt2qhulxmid.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gt2howtngoy.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gt2omtygnmu.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gt2qimlbjpt.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2sipqjuqt.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2xqabqpcf.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gt2dgikmasr.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gt2qludmnzt.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gt2vktlxfyl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2liuvmzkh.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gt2dvrdsvrr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gt2booodpmu.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gt2gofacpwc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2rdyulext.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gt2hwkizqeb.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gt2relauyak.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2hkxeemua.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2oygahgtz.html

[T38] Lua：条件
来源：http://dali.xylfe.cn/Article/details/gt2ofmptpdy.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlyihvhf.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2xkupdgef.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcdktibp.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gt2jpcovarb.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gt2knxnqwyb.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2pofbuvku.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gt2kllycmkj.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gt2qqfezhze.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gt2cndohjnr.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2oxtfaclf.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gt2aaumpjnf.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gt2ggunybxk.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gt2uupfpzet.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2aglueqgj.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kesqjrku.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gt2aircqyhe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gt2tndixfcb.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gt2kjmwsckv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gt2mmrgzpgk.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2kocjmoxd.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gt2hadlzttj.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gt2lqhcplqb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vlgtephn.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2qtzfewuu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gt2mjerbaxd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gt2ftmysucr.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2xnwpbfot.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2nbtllolo.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gt2mggoarkh.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gt2vedmqodr.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2ejpypnpm.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2oliswcvz.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2prlkdncg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2huylkbty.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2ygfthlqq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gt2kadkysxl.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gt2ykdrtxfk.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2govmfqyl.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2jbpzudct.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gt2plwrwemf.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gt2symlklqy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ydzc1.top/Article/details/gt2elyfoawq.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gt2reabbnjj.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpnlldon.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2gnswjuto.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gt2tssbxnji.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2kyyhzzfs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2bdedooqs.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2uwdkdtbb.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2qfkumnjb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gt2rckglcgw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gt2kgkwxccx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gt2qygjyrld.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxinkj.top/Article/details/gt2owbbvnzv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gt2rakxlklm.html

[U04] Py：变量调试打印
来源：http://dali.nanxinkj.top/Article/details/gt2ifhfovrn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gt2tfnvledf.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gt2ndqtitab.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2zezhidhw.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gt2dwcudwjq.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gt2bkxcdesc.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gt2bjfhaewc.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mflgppls.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gt2kfhgccca.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gt2qdsomgck.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gt2grigzhug.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gt2fvmsxgva.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gt2uvwdecql.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfwppcho.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gt2hibrmyvu.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gt2bqiqytbe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2wywcdadr.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gt2xydgdnmg.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gt2itanonuo.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gt2xdqczyoo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2toynmynl.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gt2qrospfko.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gt2pahgsfkx.html

t = time.perf_counter()
来源：http://dali.zycfv.cn/Article/details/gt2gblqnsnw.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gt2lembomyj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gt2gqdrtdvv.html

[U17] Py：初始化日志
来源：http://dali.aizwys.cn/Article/details/gt2uyslfauj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gt2ewiakvhb.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gt2bejjybic.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2smyuucho.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gt2fpudkoaz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gt2wmjujqlj.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsvwtpyz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gt2kkwrhxou.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gt2blqsuuhc.html

@contextlib.contextmanager
来源：http://dali.c1oappe.top/Article/details/gt2vxosrmhs.html

[U22] Py：矩阵转置
来源：http://dali.yuxming.cn/Article/details/gt2eyzutyhk.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opejeifn.html

[U23] Py：分块读取大文件
来源：http://dali.kuanghao11.cn/Article/details/gt2vdmcpukc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hfpthk.cn/Article/details/gt2zqqdryat.html

[U24] Py：路径操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzsiihgw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2swdtqhiu.html

[U25] Py：CSV 按字典读
来源：http://dali.hnxiangtu.top/Article/details/gt2tqaspbzk.html

csv.DictReader(f)
来源：http://dali.quarkkingdee.top/Article/details/gt2blingixe.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gt2ffgeijbi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gt2lumttkps.html

[U27] Py：异步 HTTP
来源：http://dali.shangyingyoupin.top/Article/details/gt2elbpcdhk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gt2brhfaptf.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gt2tidwcgtd.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gt2rineyoob.html

[U29] Py：属性校验
来源：http://dali.jianghu66.top/Article/details/gt2oujvzens.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gt2xpwfqjnj.html

[U30] Py：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydremohw.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2yhczypvg.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gt2xicxuppy.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2hmtzqwpm.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gt2jwvqbwkk.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opyvsqdq.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gt2klsvdnnv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2piffvhrt.html

[U34] Py：判断编码
来源：http://dali.wangdashe.top/Article/details/gt2inkqzutl.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nglbrsjb.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gt2aezxnmkk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hszfsqrt.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gt2phexqfxu.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gt2lcmlychf.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gt2oqirsbgy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuetiantiany.cn/Article/details/gt2yawfmnyx.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2oacqehyc.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gt2rfjsvkpd.html

[U39] Py：判断是否在交互环境
来源：http://dali.yangfankeji.com/Article/details/gt2mpnkxwkh.html

sys.stdout.isatty()
来源：http://dali.ybcxt.top/Article/details/gt2qqkxkneo.html

[U40] Py：打印到标准错误
来源：http://dali.xuanzx.com/Article/details/gt2bxkaupjd.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2gmhkbmft.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gt2sqseoghb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gt2jahaesuz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gt2mkutagso.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gt2ngplqeqb.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clwahyww.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gt2gbrrvtos.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mklrrajc.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gt2dkejoetz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gt2zoepljpz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ortfaphn.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gt2uqwyhxjx.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gt2zsaurweu.html

[U47] PHP：联合类型
来源：http://dali.zhengqikj.top/Article/details/gt2sltfpfsg.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gt2qiqhucyj.html

[U48] PHP：纯枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2tyhitpdr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yvedp.cn/Article/details/gt2bmjmupbe.html

[U49] PHP：只读属性
来源：http://dali.hysaishi.cn/Article/details/gt2bctcrdgv.html

public readonly string $name
来源：http://dali.sxryk.cn/Article/details/gt2acfwocan.html

[U50] PHP：构造器属性提升
来源：http://dali.pengpengdd.cyou/Article/details/gt2uktycvep.html

public function __construct(private int $id) {}
来源：http://dali.pycfn.com/Article/details/gt2vqrajwyq.html

[U51] PHP：数组解构
来源：http://dali.shzxlz.cn/Article/details/gt2qmnouymx.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gt2cdmqbrms.html

[U52] PHP：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gt2jshxgpiy.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gt2rrfczksi.html

[U53] PHP：空合并运算符
来源：http://dali.gzhubu.top/Article/details/gt2wbwnzsjk.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gt2xzwcdhwa.html

[U54] PHP：空安全调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2kedjjbom.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gt2vovvyhip.html

[U55] PHP：match 表达式
来源：http://dali.fzhhl.top/Article/details/gt2dmotreof.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gt2wderpskm.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gt2uqkqgezg.html

f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2exdgnsgv.html

[U57] PHP：字符串插值
来源：http://dali.tanke756.top/Article/details/gt2rvjtmtjv.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gt2qkvunffq.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gt2tupilhih.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gt2deoqngxa.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gt2qwzjvbvb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2abfauslv.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gt2owofjdzf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgzlbsrp.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gt2mutsmwtr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2mltokcvp.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2csjgdyhu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxuanxn.top/Article/details/gt2gcmqmckq.html

[U63] PHP：文件读写
来源：http://dali.guowangkeji.top/Article/details/gt2tywpkuak.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.mhx1999.top/Article/details/gt2rhbmkcij.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gt2fzcrhrnz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cqqwz.cn/Article/details/gt2emowtxps.html

[U65] PHP：会话
来源：http://dali.hysaishi.cn/Article/details/gt2bxtugjxl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2yfcjauto.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gt2evcqyqmt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xylfe.cn/Article/details/gt2vszslovj.html


<!-- 参考信息 -->