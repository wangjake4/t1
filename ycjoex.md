代发 wailian999

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2fvjzyess.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gt2izieswvx.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gt2hlojalmq.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjbuzsxo.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gt2evdtotnl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2ljsxwwsc.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvvdnlhp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gt2eucfkngh.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gt2aupjdnpz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2bjfodngl.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2elxaaczh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gt2zhtymgyv.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gt2jlqyvajc.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gt2jmddyyqe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2jfhtovlr.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gt2nuokaxeh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2tdvxrhlo.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gt2hdueheye.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gt2dxfvbnxk.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gt2vbchowqu.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gt2nkrstper.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gt2rqlpqfbb.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gt2ytkxqijo.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gt2rwyhsmve.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gt2qxosjrff.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gt2tuvmnknp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2uvesuwiz.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2latttagj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gt2qqsbwuyl.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gt2kmlzfsws.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2simkdmui.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gt2ppsyuxsb.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gt2lpanohiu.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gt2tymuneeg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gt2nxegigbf.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gt2wczjwaas.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gt2rrcclgxr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2kwwtengr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gt2byksjdve.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2aehkytjo.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2yzwytqhz.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2dvgyqhtw.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2bluetbgy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gt2belkvwgg.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2twjcgbnv.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2mppnhkrh.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gt2iprkdfhi.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gt2brjxeiyc.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrdhhtet.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gt2dduewziz.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gt2qgczfvcw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2ofcxphks.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2qwmsmxkj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gt2rrewcnro.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2gmhahgcc.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gt2dmgqrdsm.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gt2mgvkynvq.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gt2rlhydpnx.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gt2proyqvjr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gt2wvcptmia.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gt2qefiaaau.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2qzgqspqt.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gt2amhbxiid.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2dkivkrsw.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrvufpcb.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gt2mtmtazje.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gt2wijxkqyv.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2fqbtvyor.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gt2utnwpidc.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gt2tgdwljxe.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2vsclnomp.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2lpwbmjwj.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gt2uyjajizw.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gt2zsazgntl.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2zugwmrgc.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gt2grpyjmch.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gt2clndbrla.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gt2zduxczwq.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gt2jmfbefyp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gt2qewwfyzw.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gt2ymgmlaod.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gt2lbbspkcd.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwyxobco.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gt2xdocwvcg.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gt2jxofnvoi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iogaezjc.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xufrkkwi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxiidxpa.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gt2ruabjtht.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gt2pxxdewdc.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gt2uxymqezr.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2robzfwfj.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gt2fddnmegd.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gt2lxdzfhsf.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2zfqbkbdg.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gt2cbhlqbkv.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2xmqqoawu.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gt2ethmfozb.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gt2asstnnop.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gt2bcibhebt.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcrkdbln.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2nieafwdg.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gt2rtxnhdum.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcvulfoa.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gt2voboufsl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gt2lgnrwmre.html

[T34] Lua：遍历表
来源：http://dali.c1oappe.top/Article/details/gt2begixxcr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gt2cadcbzdd.html

[T35] Lua：字典表
来源：http://dali.chenlongwang.top/Article/details/gt2jpbhtrts.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gt2fpwrjtkw.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gt2qxgbmjxp.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gt2ljgfkwsx.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2ijiyeyup.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gt2xdefrqeh.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gt2jzxecpgh.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdioqncu.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2chtkdiha.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gt2ynuqlfar.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gt2ykqxwdpo.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gt2pvxjzcmb.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2vmqlzgtl.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gt2akoqituq.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gt2ljkfknam.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gt2abgrgrik.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2uusppzjj.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gt2tlulkvta.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gt2gsmuxaqi.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvhxjrbn.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2xupcllwo.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqmdazow.html

[T46] Perl：哈希操作
来源：http://dali.c1oappe.top/Article/details/gt2qrkjygkv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gt2fmmnalua.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gt2fixbuzhk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gt2dleduzgw.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gt2dqjgqcjo.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gt2vrkdyelf.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gt2vszitzvu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2yzmicuxj.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2hkqfsiir.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gt2oabhghgh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2dtcqcxqe.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2ttfxyshw.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2abnqmdvx.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gt2okuybctx.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2vybjfgcc.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2xmtzkegd.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgachejc.html

[T54] Scala：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsrtrrjy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gt2pomjyfdm.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2vvpenwlz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.svipenyu.cn/Article/details/gt2belfdkwn.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehfmfztf.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrrfwkys.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2mioqhtrn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gt2edelrboi.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gt2ouakziwt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gt2sqfxadzx.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2vokfmkoi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2qihwqhhf.html

[T60] Scala：折叠
来源：http://dali.nwbrower.top/Article/details/gt2wnsjnjhm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopugmoq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2haklghbr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2fwfylnsw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2zhkbdpfe.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gt2malsftis.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gt2bjeahatv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gt2bbyvygay.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exuwvlig.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdpumyox.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dublcirs.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gt2fcsvphin.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gt2kulnswlm.html

[U05] Py：列表去重且保序
来源：http://dali.cucudq.cn/Article/details/gt2ixbgtbyl.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2grlmqejp.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gt2zbimpytw.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gt2djbtipcm.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gt2eluikeop.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wklvjbzm.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gt2emeifzpu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2boztaohq.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gt2koiwblcs.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gt2fkrgknjs.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gt2jmsvrwfv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gt2rnqbayuf.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gt2ghfzojqy.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2qzkccgsp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gt2wbzcertn.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2htyrqljl.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gt2cpeogtck.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gt2zqaxeaqu.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gt2juqcwxsp.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gt2kigyrajq.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poqybdpt.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyvreumv.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gt2pyqfrhsn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gt2hrjlijgv.html

[U17] Py：初始化日志
来源：http://dali.tianlin.xyz/Article/details/gt2omjcnnrw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gt2pgzuauli.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gt2biajtgnp.html

pat = re.compile(r"\d+")
来源：http://dali.yj202588.top/Article/details/gt2nkjfxlah.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gt2rwgnjosv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gt2xcuhotpe.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gt2nyrkmjlr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gt2xvsnrqxe.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gt2feaymhkr.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gt2dbrvtqwv.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gt2boiacloe.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gt2xigmvlgc.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gt2focmuiwn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gt2liheddtv.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gt2ardxoggw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmmejxxy.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuxjqtmh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywsiwlv.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gt2ugjypgqf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gt2lddxxaox.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gt2nsszpjah.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gotoacloud.top/Article/details/gt2zoaqmvjs.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gt2uzicqmrp.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gt2zsglklpb.html

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gt2zxjmvtpm.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gt2evhniqmz.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gt2eksccdgh.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gt2wtxzgszr.html

[U31] Py：单测
来源：http://dali.tianlin.xyz/Article/details/gt2mdyhcemf.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gt2fraxvxjn.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gt2ypxdogsr.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gt2ypqacfxu.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gt2ogosqzye.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gt2mhpeexwj.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gt2llwokrvu.html

chardet.detect(raw)
来源：http://dali.birdmap.top/Article/details/gt2hggouqss.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gt2zcxywauc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cashguo.top/Article/details/gt2hpgsspkb.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdxkzubw.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258.top/Article/details/gt2umosloqa.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gt2syugsney.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gt2abksufum.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258.top/Article/details/gt2gtoasbch.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gt2yefhbkyv.html

[U39] Py：判断是否在交互环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shdwsbfp.html

sys.stdout.isatty()
来源：http://dali.aibaodan.cn/Article/details/gt2lkgsecdh.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gt2pzmcmjcv.html

print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2imromxwc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixlxvenx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yonumen.top/Article/details/gt2cokhegkq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gt2naxhbeml.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gt2cuzkvkls.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gt2sojiehbx.html

namespace App\Http;
来源：http://dali.zhoulong.xyz/Article/details/gt2zqfanbsx.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258.top/Article/details/gt2xfyihsub.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gt2glddhziq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fengsongda.top/Article/details/gt2ckchqamg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2unggcrak.html

[U46] PHP：可空类型
来源：http://dali.ivvv.top/Article/details/gt2vacjbqrp.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gt2hfiudmdu.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2akzsjblw.html

int|string $id
来源：http://dali.gotoacloud.top/Article/details/gt2taqazbam.html

[U48] PHP：纯枚举
来源：http://dali.havefunace.top/Article/details/gt2wmkjzksg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkenpysx.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gt2kewhlpum.html

public readonly string $name
来源：http://dali.hywenlv.cn/Article/details/gt2hhckzkyt.html

[U50] PHP：构造器属性提升
来源：http://dali.hammf.cn/Article/details/gt2dorkhjip.html

public function __construct(private int $id) {}
来源：http://dali.dashuyun.cn/Article/details/gt2rtpfzlrf.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gt2erxblxfr.html

[$a, $b] = $arr;
来源：http://dali.ehwqpu.com/Article/details/gt2bcrnqpge.html

[U52] PHP：箭头函数
来源：http://dali.yongpay.top/Article/details/gt2jgesufgj.html

$double = fn($x) => $x * 2;
来源：http://dali.gogol.net.cn/Article/details/gt2umhvxzyv.html

[U53] PHP：空合并运算符
来源：http://dali.zdqjudy.top/Article/details/gt2eeonodne.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gt2bsqotsdw.html

[U54] PHP：空安全调用
来源：http://dali.gotoacloud.top/Article/details/gt2ftwiclkl.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gt2znvhhvro.html

[U55] PHP：match 表达式
来源：http://dali.hywenlv.cn/Article/details/gt2cmkucmyg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gt2cfjsqzbm.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gt2kmaakbtv.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gt2nztlzecr.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2vnhjhneu.html

"值: {$a}"
来源：http://dali.hammf.cn/Article/details/gt2xelqfqhx.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gt2wazjayta.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gt2podnsyhe.html

[U59] PHP：自定义排序
来源：http://dali.bjfxy.top/Article/details/gt2krcqjguj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gt2berevztr.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gt2bqaephiq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.iojbl.cn/Article/details/gt2emaptiqd.html

[U61] PHP：正则
来源：http://dali.xziqi.cn/Article/details/gt2gludgaec.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2veqwxljy.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyfymrjf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daria6918.cn/Article/details/gt2lfsxmgof.html

[U63] PHP：文件读写
来源：http://dali.vqdsnc.cn/Article/details/gt2poulsuea.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aerfvkrs.html

[U64] PHP：目录遍历
来源：http://dali.shzxlz.cn/Article/details/gt2jlqaiihp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gt2rdisvrph.html

[U65] PHP：会话
来源：http://dali.xylfe.cn/Article/details/gt2faraiqho.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2kbgcvtfi.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gt2cvulqzci.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2remikykt.html

[U67] PHP：处理文件上传
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcspeghy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zdqjudy.top/Article/details/gt2dzpuutzl.html

[U68] PHP：PDO 连接
来源：http://dali.sufxvd.cn/Article/details/gt2unfjgdfy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.9152youxi.cn/Article/details/gt2gpzfuodb.html


<!-- 参考信息 -->