代发 wailian999

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gtciuyqwdz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtgpduaqpa.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gteiwingxy.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtihhbysza.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtjoxdxeql.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtidiegiof.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtwvehzaaj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gtniyqfxnk.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gtcpegbfdj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtbqvjdkvf.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtkvprklim.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gtofupbujm.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtnhkopnoy.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjrtxoek.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtpufzhusy.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtfdjdlzuk.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtfupgaghh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gtyqigsrul.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtyxricaic.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtclsdvgvx.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gtswuwszwe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtuxegephc.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtjqanqpjf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gtbmfnqmpa.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtldqzlqfj.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtbqkvfavy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gterquzdjf.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gtltqcdrit.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlpbaboe.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtvujfsquo.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtvbmjarxi.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtepbruzsj.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gtlmyinolg.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtlmtbaskk.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtlabjtlqu.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtszobufwi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtjqpmabwl.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtosezdyzp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtfxzslhvi.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtsbkbttll.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gtafcrwmvv.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gtormxlnqb.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtyopvhrbe.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtfejmjtnf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gtbhnfmfju.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtmdybhbzk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtjogbvisl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtkkgssyob.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtuelghrfo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgucsvcwx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtkjiftpuq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjnvzskgd.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gtjfbscxki.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtrcscgxjh.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtrlmjssxu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtwizyfbjp.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggrftmsb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtmrvfglze.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtnpsrxaku.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtrqhhgfnp.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtbioyrhhx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtoiuarxba.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkkggrys.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtrapqtsai.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtpxqqqtzc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtuzasrumh.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtntbmtxoi.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlspqslg.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtszchkaun.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtmtbffrlh.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtzmmprlke.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtpbzfwezz.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtaskcajbk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbkdpvrv.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtdnzawhqk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtcwrciqgr.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtsdqihlya.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtmfvheltg.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gttmiahgst.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gthpobldoj.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtqodycwid.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtowbquqoq.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtrwtghjhe.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtovoifumd.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gtzsgfvpvf.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gtmcipnvbq.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtxawwgalt.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtlyaqgeub.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtpiilkspm.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gthtqxucyg.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtsawpjrrw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtfeghlkwq.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtjduskowe.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gthjhrxiqf.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gteagzlzue.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtnmxuxege.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtfovfmptc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtzckzkopf.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gttavnbqzc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtkaxivbbf.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtornudhkk.html

struct P { var x: Int }
来源：http://dali.yj20258888.top/Article/details/gtlnnaxinq.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtmryxrxna.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtgvzgqjwk.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gtgybvigre.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gtuzoagxcy.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gtqyragvkz.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gtokguzyvr.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtgnrcaeyr.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gteksgsdoy.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtkfdjwmsn.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtdoqnfpdn.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjidmbwax.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtozzozhmm.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtjmpbwnmk.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdrbkrge.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtpsxsdbin.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtibfpqljf.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxmfbpbl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtespcuqyc.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtprbardbi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtatidhzrz.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gtsryxsnax.html

function add(a, b) return a + b end
来源：http://dali.redwolf501.top/Article/details/gtjyjwalyy.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtsomsljsg.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gtfiqiamei.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gtutzuhxxb.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtyaupxezo.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtzxsszjud.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtctyzhqts.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtbjsvrzfa.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtglygwcsp.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtvknrxjjg.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gtyegyzuqf.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtiorpbjvm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtobsbgqrf.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtjlvnxpch.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtwtpblviz.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gtpzhtlmus.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtatddtffk.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtkyodryak.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gtztplovvx.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtqainlsin.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtvxtswsxq.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtleripcoj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtldcxolni.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtosldvdtc.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gtanxrcdbl.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtqwxzixbz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtpstabrfh.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtconysrrd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gtnbagzdvg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.meibo888.top/Article/details/gtjgevlynw.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtvumxptba.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtreyryiom.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gtsdcgjlip.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gtmyqrukbc.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtbttkvimr.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtmjqoiesn.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtkbysmkob.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtqoyenxkz.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtmjhdmyue.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtgpwxeulv.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtcbqorbrf.html

case class User(name: String, age: Int)
来源：http://dali.ybcxt.top/Article/details/gtpdyqyzif.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtykxkzbjw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtwvalfmyu.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtfkayfnwq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ydzc1.top/Article/details/gtzyjmtuqj.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gtddmtrslu.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtmvbykirt.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gtiikgxjsd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gtvluovdbb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwerrncmt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaxqjnmo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdqfryptp.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gtqibodsww.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ivvv.top/Article/details/gtfdmajzsn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavvovdsf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtycwimjed.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gtrjbrqkvy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gtgyyyiabn.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtgjpzhrxm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gtuoupxoki.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gtekzvzwtz.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtnwevzcoc.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtsfpyrhtc.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtbjvadmjv.html

[U07] Py：反转字典键值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzaqrbxm.html

{v: k for k, v in d.items()}
来源：http://dali.zhongyouzk.top/Article/details/gtgklqwtag.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtfrzxrpli.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gttdmusvfz.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtljyejkgl.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcodoulrk.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gtgmzqepqi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gthcoaenju.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gtxoliegmw.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gtbmedehds.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfqmqzpu.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtovkgtqfo.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gtwpclrmwg.html

deque(maxlen=10)
来源：http://dali.jqgufenzy.top/Article/details/gtptogfibs.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gtyuqqvxsf.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gtggqfsmvs.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtjxqpkoro.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtwlqowlqr.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtjlgomoly.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gtyphkphra.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gtywvglsys.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gtypgsulax.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gtldoapamy.html

pat = re.compile(r"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtbbsyfcbe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtuuwoahyj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveetsreh.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gtrbfncsql.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gtuzpjaybv.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gtcuemapub.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtvbfdhpes.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtnyruyybd.html

list(zip(*m))
来源：http://dali.hywenlv.cn/Article/details/gtylboiaqu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gtnafoouob.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cashguo.top/Article/details/gtxolbxkrj.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqkcsvpb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtmbksaxam.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtxzokxiaw.html

csv.DictReader(f)
来源：http://dali.ivvv.top/Article/details/gteqxvtdyt.html

[U26] Py：并发下载
来源：http://dali.hnqzz.top/Article/details/gtoxpzwrar.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gtlhyfzasq.html

[U27] Py：异步 HTTP
来源：http://dali.cdnleiting.top/Article/details/gtsuahozzc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gtetmnkgtd.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gthitoeepe.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtnxsrqluc.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtuolsudmb.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gtndrirten.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gttnfalfho.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtgmdifgzo.html

[U31] Py：单测
来源：http://dali.xziqi.cn/Article/details/gtkpxkizsb.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gtwbpifwyq.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gttvpycdqv.html

ruff format . && ruff check --fix .
来源：http://dali.sufxvd.cn/Article/details/gterhcstpi.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gtimggymbb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gthaylivcv.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gtqtfeooxo.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtwmzlvars.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gtrocplfed.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gtcihqpdeq.html

[U36] Py：定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtmctvahdw.html

schedule.every(10).minutes.do(job)
来源：http://dali.gzhubu.top/Article/details/gtrssxyddi.html

[U37] Py：读写 Excel
来源：http://dali.nanxinkj.top/Article/details/gtfixljhjj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwavouhw.html

[U38] Py：获取脚本所在目录
来源：http://dali.pycfn.com/Article/details/gtarqeotii.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gtogbgrmmh.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gttvupntlf.html

sys.stdout.isatty()
来源：http://dali.fzhhl.top/Article/details/gtmcygpcfi.html

[U40] Py：打印到标准错误
来源：http://dali.shuidangran.top/Article/details/gtrkuuusac.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtgdghoqxm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.andypj.xyz/Article/details/gtlhqjmtrx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cqqwz.cn/Article/details/gtamgmkfab.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gtxlwpsltr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gtluukbuyn.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtnahoknwp.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gtlviimdhg.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtvlpwogcx.html

declare(strict_types=1);
来源：http://dali.zycfv.cn/Article/details/gtwifcahhq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xinyue.icu/Article/details/gtvxutqccm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtrtmfcnau.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gtlkvogvrf.html

?string $name = null
来源：http://dali.vqdsnc.cn/Article/details/gtxdqcvung.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gtoggiuhsp.html

int|string $id
来源：http://dali.hammf.cn/Article/details/gthwnuefqa.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwqyphkv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gtmgwqomme.html

[U49] PHP：只读属性
来源：http://dali.shzxlz.cn/Article/details/gtmvkpknok.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gtksnwtzvk.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gtnqlrpfjv.html

public function __construct(private int $id) {}
来源：http://dali.shuidangran.top/Article/details/gtugfecvcj.html

[U51] PHP：数组解构
来源：http://dali.c1oappe.top/Article/details/gtjcqopvmr.html

[$a, $b] = $arr;
来源：http://dali.birdmap.top/Article/details/gtmrlruxux.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtwxerdxwl.html

$double = fn($x) => $x * 2;
来源：http://dali.yongpay.top/Article/details/gtvqjleyqv.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gtoybibdke.html

$v = $a ?? $b ?? "default";
来源：http://dali.hfpthk.cn/Article/details/gtnsambjoq.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtxztzlqcm.html

$obj?->method()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiuvattx.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gtfvcjoshe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gtuobeiqsg.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtitqqpqyc.html

f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtluhhultb.html

[U57] PHP：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtcjdqqnzx.html

"值: {$a}"
来源：http://dali.guannengcc.top/Article/details/gthqonflfp.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gtjhhccziv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gtwyqvuqka.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gtjqmkfauh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gttozckbkz.html

[U60] PHP：JSON 编解码
来源：http://dali.9152youxi.cn/Article/details/gtgbsckigu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gtdbcnlitk.html

[U61] PHP：正则
来源：http://dali.tanke756.top/Article/details/gtexhmvzjc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtspapbxvl.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gttbrjdhsk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhiwuduotai.top/Article/details/gtyzxjobes.html


<!-- 参考信息 -->