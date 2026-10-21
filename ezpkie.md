代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtkxgjvpbe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtrljeftqi.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtphlmebzz.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gttvksxlos.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkojnzafs.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtgmeapcgz.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gtvqsyarfy.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtcuhznkrz.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtkryytwmm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtweexouii.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtturtilft.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gttzojdhao.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxuanxn.top/Article/details/gtqjpevrap.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtmcmiptus.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtpvplxvbm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtlaapzadk.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtgykiblro.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtgnkxdnzn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gttkheeifg.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtsyqbomcv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtnviumthh.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvfhwdpb.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gtvcdvhqar.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtdkbiddms.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gteqlkivdb.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtenwknifr.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtyrfcdfkd.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtntnvkees.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gteynckcnf.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gthnwyqdsa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtgzgkmxdn.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtvkhluzff.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtqqjlupih.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtwvpxftgx.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gttnpwrajd.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfdzqrqu.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gtqlpuzacq.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafmypatf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtgkfozlrt.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtigcherwj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtbpkgopfr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxckvrnhp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtrmpykiqz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttlcvdhsz.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtfbzqhfkh.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gtxudanubl.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtanlzcmcg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqcbnlms.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvuseozq.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtroptvriu.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtdvflcelx.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtwbkonxch.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtuuvauqza.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtteoiqxbd.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gttfooogmd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtmpwismrs.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtzkyixhco.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gtjpqnjeie.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gtntqgebsb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtormcpocn.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gtjnkbqhcj.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtpbirhtrh.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gttrwiiaud.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gtytwhuljj.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtaqondzfz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gtmbxvumdm.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gtmyqwcsrx.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtoebzaqfc.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtnyntthwe.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtkcgunygs.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtojenhlnu.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtqoowdqau.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtktcaxtaj.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gtkikldvvr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtbqtpcsfe.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtwnxmsiwh.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtxjhqkvpj.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtsadglrfz.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtzsvzckhj.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtxhlhogip.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gtohyssbqc.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtzdbdwrjs.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtmgwbpkyf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtriywlydt.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gtnaxbhhtr.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtoosohytw.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gtaabplqgs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuanzhike.top/Article/details/gtbfcewojo.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtrnmwwfpv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gtzbuubllo.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gttbgrerek.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtkkwtbgui.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtekhsliwr.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtojntiqvs.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxmuqrro.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtxbmmubam.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtwpfvnrsp.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtpibdtpbt.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtkeklsxqv.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gtpeyhbcba.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtyrdikddm.html

guard let x = opt else { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfqmkbir.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtroxcpeve.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gtsakxkqky.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtwpipuzyc.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtxfndxlyp.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gtvfayfzof.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtukptldeq.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtfxzmobna.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gtnhbgwonj.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtvgqyxohf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gtvyvvaqrv.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gtvyicpcmx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtwhjenged.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtcubwsbiq.html

function add(a, b) return a + b end
来源：http://dali.ybcxt.top/Article/details/gteugcogvg.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtdcnmidiu.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gtwvikolzn.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtpytjmtbk.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtcdhktxzd.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoknvmpn.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtrzitmopb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gtbaysuybk.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtilzshxze.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gttgqolpgl.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtyolkxzfq.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtktklwjoa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gtprigmbuk.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtroyqonux.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gtohbpimmd.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gtiwkgzgoo.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gthrwunorl.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gtlvnrwqqz.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtgnkmfuvo.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtpcyvbxgr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gtjvobvqbe.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gtgfzzvbbi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gtbggqexmo.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gthqqpkxyn.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gttoakgkti.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyqcuoiz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtohuhkndj.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtpuudanwh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtscgmtprx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yueranfly.top/Article/details/gtcbqfchza.html

[T51] Scala：Hello World
来源：http://dali.cucudq.cn/Article/details/gtbyuipfvo.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtcatnadnj.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gtpqdonjjn.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtprtscddu.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtrbhqrrhc.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtgcxmdmjk.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtpwsyrlow.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gtgkweatpa.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtvwbwwzdb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gtvggawdez.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gtwlhmsexh.html

case class User(name: String, age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gthciyhtvm.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtyowwfvmi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtpbswzmzs.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gtlsrwoyfo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtiawkietl.html

[T59] Scala：循环
来源：http://dali.yj202588.top/Article/details/gtewbgxpea.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjmkiecp.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtiyduobeh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtjhlfqepf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtasnmohlf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtwihqdhvu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtoamuknev.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtzwgfjeea.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtmkqxytxc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gtzphiqqhx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gtpvcuwpmf.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtxwufnijx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gttbqkykgh.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gtaxfrbzkq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gttjyiwxib.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gtvvkesizm.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtqizmebwj.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gttavydovo.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gthmvhdoin.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbajglqev.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gtinvtvxjb.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gtympnqowe.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gtkoyvgaex.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gtshzcqknd.html

max(d, key=d.get)
来源：http://dali.quarkkingdee.top/Article/details/gtdgfeizvv.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtrgbyumpa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gtcxlxebpe.html

[U11] Py：生成器表达式
来源：http://dali.9152youxi.cn/Article/details/gtxsqbyirx.html

(x * 2 for x in arr)
来源：http://dali.gogol.net.cn/Article/details/gtbtpcnghv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenzaomai.com/Article/details/gteszwzqlx.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gtkishwccg.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gtzyvdmcbk.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gtlgenqdym.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gtqbfjdknd.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gtqcwnhkqk.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gtuciazlza.html

t = time.perf_counter()
来源：http://dali.fengsongda.top/Article/details/gtbqgihbfd.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gtzocwalow.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258.top/Article/details/gtyytthvja.html

[U17] Py：初始化日志
来源：http://dali.tian-w.cn/Article/details/gtlpfzjnrl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cucudq.cn/Article/details/gtrpixvssy.html

[U18] Py：预编译正则
来源：http://dali.tianlin.xyz/Article/details/gtgbxigobm.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaitmdbko.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtzgbvnwdb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gtvjxnsuaq.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gtynpicmmo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gtcmlvtocy.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gtmlwpswqk.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gtwpvjchet.html

[U22] Py：矩阵转置
来源：http://dali.zhengqikj.top/Article/details/gttlptyshk.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gtffpdmpnd.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtjlekmfxd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzdnoypt.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gtuzdatgka.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtslzjrdoh.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtiwryptxy.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gtaxeasqbx.html

[U26] Py：并发下载
来源：http://dali.ivvv.top/Article/details/gtlvneuqps.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xylfe.cn/Article/details/gtleyffmis.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gtehdiqxkx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gthvtnrqag.html

[U28] Py：类型别名
来源：http://dali.ybcxt.top/Article/details/gtbalxgica.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gtlskbnbwx.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtfuuhbqhi.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzybqxcpd.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtdkfogtlw.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtzkicolbm.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gtgdiinued.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gtpwkdnxyk.html

[U32] Py：代码格式化
来源：http://dali.yj20258.top/Article/details/gtvaxudawb.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gthwvhvjmr.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gtcudykcit.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gtlmhrntio.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gtsodhtcji.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gtykshwvae.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gtldurlhqj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrgcqlmj.html

[U36] Py：定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gttnlunnms.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gtaijbswoe.html

[U37] Py：读写 Excel
来源：http://dali.zycfv.cn/Article/details/gtsjiavtfu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gtgneqkbgg.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtophctpby.html

Path(__file__).resolve().parent
来源：http://dali.zhengqikj.top/Article/details/gttuyywldd.html

[U39] Py：判断是否在交互环境
来源：http://dali.fzhhl.top/Article/details/gtxvojwymg.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gtbhdygipv.html

[U40] Py：打印到标准错误
来源：http://dali.sxryk.cn/Article/details/gtwiffjgjh.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtjezevlnq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zdqjudy.top/Article/details/gtcvtxzdaz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gteuncrtkk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gthpdttkkx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenlongwang.top/Article/details/gtdprwozfv.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtomzefqcp.html

namespace App\Http;
来源：http://dali.gogol.net.cn/Article/details/gtglhfvibd.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gtopbmhhxi.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gtvioxifwp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gzhubu.top/Article/details/gtdwahpgif.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gteofzphdk.html

[U46] PHP：可空类型
来源：http://dali.xuetiantiany.cn/Article/details/gtdrjupeax.html

?string $name = null
来源：http://dali.haohaochexian.top/Article/details/gtjgujcmga.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gtcaetygbm.html

int|string $id
来源：http://dali.fzhhl.top/Article/details/gtbyiihtyy.html

[U48] PHP：纯枚举
来源：http://dali.jlsjyb.cn/Article/details/gttptxttps.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtymmpgdob.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtdrsilomq.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gtureiwqin.html

[U50] PHP：构造器属性提升
来源：http://dali.yanxiufei.cn/Article/details/gtaxnlkcvb.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gtmflfwmih.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtkqootelo.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtjafamlxx.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtpcvdtnxd.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjejrurhu.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtuvjjmegm.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtcfcghktg.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtlkbhqzhm.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gtwecdaqua.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gtghwpurik.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngptaeqe.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gtujdatggm.html

f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtvfwunift.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtcyzrjtkl.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gtcbpqaoia.html

[U58] PHP：数组三件套
来源：http://dali.zdqjudy.top/Article/details/gtmdmzcnlz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dashuyun.cn/Article/details/gtkliopamu.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtovxqebla.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtjbeigide.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiybmkdce.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.andypj.xyz/Article/details/gtjlhxsbji.html

[U61] PHP：正则
来源：http://dali.bjfxy.top/Article/details/gtbhrsuntb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtzjvbuewk.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gtybtwfwmb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.havefunace.top/Article/details/gttwtrfhdr.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtjfmbijwj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhoulong.xyz/Article/details/gtnkeujndg.html

[U64] PHP：目录遍历
来源：http://dali.jyoumei.cn/Article/details/gtghzviilc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtyjgslxps.html

[U65] PHP：会话
来源：http://dali.zycfv.cn/Article/details/gtksfyauzs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtusabwtit.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gtjqjxpwxm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gtdkilxvla.html


<!-- 参考信息 -->