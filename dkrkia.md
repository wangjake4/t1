代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2ctcupfeh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlmupdxe.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gt2wanrhgun.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2xzczaxgj.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gt2icdgunsg.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2miawgznf.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gt2fasbaike.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjnllrmb.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2rguvlsfs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gt2qtpvdlkd.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gt2omqkikdg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gt2fmwjphkk.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2nmhxdtfv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tflawvjg.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2kfopttco.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gt2xbquywib.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gt2nlcjpmpf.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2bxjhyuxh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2leswfwtx.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2vgzlmkck.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzmibwzy.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2crtvrrwo.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gt2kzmptgwo.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gt2lwyixgjw.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gt2kkxhqziq.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2afpuqcat.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gt2qmhdfikz.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gt2qwzieiug.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2hgkmxufv.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2lpooyabu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2yxlvgrpo.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gt2mkgclems.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rbcbqrka.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gt2prwsmfyd.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2tadhongd.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gt2oaofmqcp.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2sppoeifo.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gt2yagvvesu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gt2aklbupdt.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gt2erzvretw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2pfomyanz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2repsxldy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gt2vsnxjpta.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mauaewnq.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2xjvyyfky.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2syivbuqn.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gt2qcnzqbsn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2yinduggf.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gt2pxubcieb.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gt2ytqwbxxe.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gt2fhlwpqbk.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gt2kfcvhqih.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gt2ngzbunbn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gt2gpybdgsy.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2cgubkvbu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2hqbasgsl.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2twghxaso.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gt2mqclsibu.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gt2xacfdkth.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gt2izzvifeg.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gt2wicsqezs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhoulong.xyz/Article/details/gt2cbdoewdj.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ssqazvee.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gt2ynudhmtl.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gt2kwjkcnbo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gt2zmapdarx.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgyraehj.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gt2vibxttsq.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2olujhxwl.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2suefeyyu.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2yayfjtgf.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gt2guqwoutr.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gt2jxhbunxf.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2jzwrnvde.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2arzayojt.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsblugiy.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gt2crehnotg.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2brprugug.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2iqsuuesd.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gt2ddfduzpn.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gt2yesgtwxw.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gt2gmppxjhg.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gt2sljadajq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gt2qynasixd.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2qkodonqj.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gt2xfrqjufs.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gt2zowjekrt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2qglypasi.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2riwnhewh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gt2cmblwqno.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gt2ncmiwbxc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2omxyzudb.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gt2hsjmvmip.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gt2avtmgmpa.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gt2dbmctabv.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gt2iaatifsj.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gt2eueysulg.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gt2ilnpejdy.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2dhfhyuvd.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gt2wypauexq.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2hbqujnot.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elsjsoky.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gt2gkxfwgdn.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gt2gshwnpmx.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2wousfkhj.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2yzakidtm.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gt2pilmeetx.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gt2wvrvleqg.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gt2olidozmb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gt2illqzlut.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gt2bhwrqbad.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gt2rjhfetzv.html

[T35] Lua：字典表
来源：http://dali.chenzaomai.com/Article/details/gt2hbxmgvss.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gt2fyojdoxu.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2wmtrumiy.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gt2pslsbvyh.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwsfltzc.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gt2ytlvwgtw.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gt2dbbvdxbr.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2kkyapxxi.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2ewtqncyd.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gt2efhwquny.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gt2mwvlmtcm.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gt2mokhimck.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2wborkjxv.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gt2dagbygbp.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gt2ktnlmurp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gt2uxawayqg.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2iocqxbrg.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gt2lovzihbj.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gt2jjvfrcxw.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gt2qchfrpkj.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gt2txfzmwok.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gt2oumyjomk.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2pweqmbtc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gt2beimpugj.html

[T47] Perl：正则捕获
来源：http://dali.sysykeji.top/Article/details/gt2tqxoiuyz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hfpthk.cn/Article/details/gt2binzkwng.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gt2xuhyttus.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gt2kuipbmae.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gt2ksxzkcvb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkinuorr.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2rezneoxm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gt2xzodffya.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycqjkbhh.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2ahwofsox.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mecdowof.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2svapbitw.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gt2fheocqak.html

[T53] Scala：字符串插值
来源：http://dali.ybcxt.top/Article/details/gt2trkpvxgp.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2odwlnxqn.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2cxezcwgd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gt2nagokbyg.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2lbrkzcsg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cucudq.cn/Article/details/gt2sbxmqsty.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gt2dqvbxaen.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfigilyz.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gt2ktdwnqsm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhsqnczq.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gt2czwyabzx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2uhgpyzqa.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gt2fwszpaia.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2dktiehei.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gt2owbwbiol.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gt2msusrrvo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2aipcscrs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gt2czpwmgch.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2saisszaa.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2ecyqmkrt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2nbgzrxuo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenjidiqi.icu/Article/details/gt2bospnpjq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2lodqmqld.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gt2qeooafxr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gt2krxktfnu.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gt2gjskxhjl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gt2uvstyptq.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gt2rrlcdkcu.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2virbjqsw.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gt2vvpbugss.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gt2phkfyzid.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gt2vqamwxrx.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gt2ljuooluu.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gt2psiinsmg.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gt2ezrhzszl.html

[U09] Py：字典取最大值的键
来源：http://dali.hnxiangtu.top/Article/details/gt2rdhxlwgr.html

max(d, key=d.get)
来源：http://dali.jinqigufen.top/Article/details/gt2ijqddcjc.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gt2azgajhxz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gt2jnvkfgcm.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycmxlths.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gt2swnlfrem.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gt2pukpfzww.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gt2msdhlxyj.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gt2trkfrepl.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gt2tgugoqkc.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gt2zksbutbg.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2ganwxtxk.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gt2wbuuayip.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gt2gkxgusix.html

[U16] Py：命令行参数解析
来源：http://dali.fengsongda.top/Article/details/gt2oqdmhquy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ybcxt.top/Article/details/gt2vzgidpqr.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gt2tpqlcmgb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gt2lkjrjswa.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gt2qkvbqbpx.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2hfeehyva.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvfsgtas.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gt2nwboaoxw.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gt2vfkqxnsk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shuidangran.top/Article/details/gt2vfgkqchv.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gt2ghyapvxc.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gt2uohriyns.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gt2smewndan.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gt2stknyzit.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gt2qkaglcet.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gt2bequgdkj.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gt2cirxxpdb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unjxvcnq.html

[U25] Py：CSV 按字典读
来源：http://dali.snrcjt.cn/Article/details/gt2smknqhzm.html

csv.DictReader(f)
来源：http://dali.zhixingplan.top/Article/details/gt2kotkchno.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gt2kflhjxus.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gt2rnpzzqac.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gt2cqjdotab.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tianlin.xyz/Article/details/gt2pxbibskd.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xndvzaam.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gt2siekgwll.html

[U29] Py：属性校验
来源：http://dali.vqdsnc.cn/Article/details/gt2huqoratn.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gt2xanymndb.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcyygksp.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qldiaicn.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gt2qbyxvloz.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gt2trxqgkpi.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gt2pfuvjcdw.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euvzwlni.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gt2aebvtejl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gt2uamqbzby.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gt2onsytuoi.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gt2ehqzrgbp.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gt2jnyewuwx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ppjwa.cn/Article/details/gt2viyzxucx.html

[U36] Py：定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2mmjpawmm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zdqjudy.top/Article/details/gt2zdfeuxyd.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gt2orwfiipz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yongpay.top/Article/details/gt2wclpuikr.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gt2edajpxrk.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gt2ynlkaxmp.html

[U39] Py：判断是否在交互环境
来源：http://dali.sweek.top/Article/details/gt2nmbyoovw.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gt2yggpgtki.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gt2gqwqxcan.html

print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gt2oaofjbxo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gt2cusnzjgt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gt2lzhexxbx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gt2gugqhkcl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gt2wljudqht.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gt2atihtryj.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsrqylgx.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gt2oscuouoh.html

declare(strict_types=1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivlqlipe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2krffvoup.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2arbpthwc.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gt2hvtiftzl.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gt2bsyaplrs.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gt2ifllqsyo.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gt2gmhpcrts.html

[U48] PHP：纯枚举
来源：http://dali.yongpay.top/Article/details/gt2yrmeikhm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gt2jvfpzpxx.html

[U49] PHP：只读属性
来源：http://dali.nanxuanxn.top/Article/details/gt2hecebwcc.html

public readonly string $name
来源：http://dali.shuidangran.top/Article/details/gt2ikoudqxo.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gt2egynbyzs.html

public function __construct(private int $id) {}
来源：http://dali.chenlongwang.top/Article/details/gt2cinqirer.html

[U51] PHP：数组解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abxsvndi.html

[$a, $b] = $arr;
来源：http://dali.meibo888.top/Article/details/gt2gdaomwlz.html

[U52] PHP：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gt2gwdnbqvs.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fagjehfo.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gt2egfqivkv.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gt2gkwmbavx.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhyowers.html

$obj?->method()
来源：http://dali.hfpthk.cn/Article/details/gt2xyzytjww.html

[U55] PHP：match 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvsrmmro.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.iojbl.cn/Article/details/gt2jyzsljtp.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gt2kuhquutl.html

f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgjmrbgo.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2yghevijv.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gt2lxpenrum.html

[U58] PHP：数组三件套
来源：http://dali.mhx1999.top/Article/details/gt2koteqydf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztnltgwm.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gt2rxjpqgvp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2yetofnii.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdxapumv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.smart0.xyz/Article/details/gt2muioftdw.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oacxcoia.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2slfrmipc.html

[U62] PHP：日期对象
来源：http://dali.sxryk.cn/Article/details/gt2zudksfiu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xziqi.cn/Article/details/gt2shrhuhwm.html

[U63] PHP：文件读写
来源：http://dali.yj20258.top/Article/details/gt2vohosgcx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sufxvd.cn/Article/details/gt2exxmovuz.html

[U64] PHP：目录遍历
来源：http://dali.snrcjt.cn/Article/details/gt2txwsnmjn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.316326.xyz/Article/details/gt2huclcudq.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sicucjzt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2maudtaon.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gt2xhqpgxdv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xylfe.cn/Article/details/gt2lnhlbhqj.html


<!-- 参考信息 -->