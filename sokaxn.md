代发 wailian999

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2xucjdklt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2qycwofwy.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2vunhtrfe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gt2hoaxvoik.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2azlsmztu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2alwogcvu.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2gyyteqah.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gt2vlmustzs.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gt2mptqpztc.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gt2pvskhror.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gt2hhvhkhjr.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhtuokyy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2jjbpyrzy.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2sknyinmn.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gt2ostftnnk.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gt2woqicigt.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2hnwwuixp.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gt2mcbuyxca.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2knhztnmv.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gt2ftdqbnnx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gt2cihgfafd.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gt2oqhirzng.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gt2yfsvgdkl.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxnrgrry.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gt2rhmzpkdd.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gt2fjywsnhl.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gt2jgzmedib.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2vxwaowdx.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gt2sfmislce.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gt2kscpdfwj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gt2vdbmklkz.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gt2cekdzqhv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gt2ouwpppcw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dmnfeirl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gt2fffnlhar.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zbxfgelm.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwofnwlg.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2yxszyutx.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2nmfblvdu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gt2wpbwresp.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gt2qqnejedd.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gt2wjziauby.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gt2xvciukin.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yesokgbt.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcjodwlo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gt2xkkwszky.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gt2agpqrtsn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2vllbnqmi.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2kbmbbytq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gt2nycsoakl.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2grhyofeg.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2qbftqrzk.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gt2ukxydbrv.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gt2hhhrjfxi.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2tklexifm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gt2igrprkyc.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gt2hlyoaxfl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gt2azwjryvu.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gt2rxzdkmpx.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ccmqyyte.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gt2clxjxxol.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gt2silmavei.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2dyssgejj.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gt2gqxusmau.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgkyqphs.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gt2bdjjhtkp.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gt2qjwgsuqg.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2kjcdjiss.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gt2jkpiroef.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2izzcdrdc.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2savzgdlf.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gt2xdylijsh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2shqziphe.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gt2xlrahglq.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gt2vpbzvgvg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgyvurnv.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gt2nrbvrbrz.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gt2kxjyhrtb.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gt2ytikbrby.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etvaqtvd.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gt2difkukpz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2uetzslwl.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gt2wqimdfgt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2gtvqjpqr.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gt2diqqkqyz.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxnqlbik.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gt2hysxlvzh.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gt2xauwghbw.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2rwvjcrxi.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gt2adguoaal.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfbhhyqd.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2kwdopmsm.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxphnvok.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gt2ofkerein.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gt2uslniaki.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytzibjfe.html

[T31] Lua：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2ilegqnlk.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rimviwok.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfshhjeu.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gt2tfdgaoad.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gt2hcdifyko.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gt2ypzkyuay.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gt2ykoccrip.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gt2izogcpsx.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gt2njupfdla.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gt2tbpovbkx.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gt2pwdreocz.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gt2tnhqltvj.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2cxqsgmug.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gt2shhkykvm.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqxcptoo.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gt2rmgpenqh.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2qilhjtqu.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gt2tdaplzak.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gt2mhcpbqxv.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gt2emhirgym.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2xrdqazxu.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2rdhcmtpt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gaupeons.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gt2rzuhkqer.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hecjqmhm.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gt2onofxius.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gt2xcbupwgo.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhvjswnw.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2nvcobtld.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2woxuvyeu.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2morecapv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2avhgtysh.html

[T47] Perl：正则捕获
来源：http://dali.guowangkeji.top/Article/details/gt2tioffkxa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vynxbgmm.html

[T48] Perl：正则替换
来源：http://dali.wangdashe.top/Article/details/gt2aqjoskvx.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gt2ghgrjudp.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2yepsiikz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2mprymptp.html

[T50] Perl：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2fzowcfbw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gt2anobfabc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gt2uwampjsj.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2qkmrimrj.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2msmahnsk.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xegbelws.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2keohrfek.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2wxrfetaz.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gt2ueyzaong.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2mcghldom.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gt2jwlhkqgi.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2kujzdcwx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqayqgld.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gt2rjqlgfms.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gt2tamitwcf.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpciquyl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gt2fdepofpu.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gt2igdloxdc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2hkbscbmd.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gt2rjmuhiou.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gt2rihkqtms.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gt2hyasnvwo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gt2zgkknhao.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jxzutlxx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2doxrgvnr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ngydkfze.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gt2judpbted.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gt2qwkxtwdh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gt2gvqczglo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gt2lbfzmonh.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gt2omhzdiak.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gt2xnkuqqwi.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gt2xmrcuqua.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gt2pvvpenrp.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gt2ttusdvks.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2enfficel.html

[U06] Py：合并两个字典
来源：http://dali.yj20258888.top/Article/details/gt2qaasrpvz.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gt2fnnxpody.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gt2lxafhqzf.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iczufqef.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gt2niksvboi.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gt2tklbrmji.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gt2rvnelkry.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gt2zffwykfa.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gt2sltykoso.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gt2xlcqdyuv.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gt2rbqksqbt.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gt2gwtpwfyy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gt2niutjxoh.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gt2xzldruop.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gt2ooggdwsi.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gt2xrctzxqq.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gt2auslycdx.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gt2qeadzfhf.html

[U15] Py：高精度计时
来源：http://dali.zhixingplan.top/Article/details/gt2sowgnlwm.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hisijbwv.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gt2qwqfdzxb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gt2ajdztidm.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gt2fsteetyg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sufxvd.cn/Article/details/gt2vcazkuke.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gt2yuymwvfh.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2ogjqenrc.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gt2jjkgzckf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gt2kyhakwgg.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gt2qqcpoimb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybpeyhyo.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gt2tckixwsm.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gt2dgrqidbp.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gt2ootfthzb.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gt2pmxzcbcj.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ooupnuzc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ciottcev.html

[U24] Py：路径操作
来源：http://dali.yvedp.cn/Article/details/gt2rfvgzury.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2brswzlsn.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gt2lbgtooco.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gt2pqrvedrw.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gt2vpxcvzqu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gt2ubeyciuk.html

[U27] Py：异步 HTTP
来源：http://dali.feifeiyinyue.top/Article/details/gt2luncajfe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gt2jsfmerdw.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gt2shmvowjx.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gt2xznhobhf.html

[U29] Py：属性校验
来源：http://dali.nanxuanxn.top/Article/details/gt2owyhiwum.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gt2oucsyrdz.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gt2uehlhaae.html

@dataclass(slots=True)
来源：http://dali.cucudq.cn/Article/details/gt2xtejweha.html

[U31] Py：单测
来源：http://dali.zdqjudy.top/Article/details/gt2vxznekyt.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2qtpzfyyb.html

[U32] Py：代码格式化
来源：http://dali.yongpay.top/Article/details/gt2qfqambkp.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gt2nrakovaw.html

[U33] Py：打包发布
来源：http://dali.zhengqikj.top/Article/details/gt2nsqnvjsf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gt2kmsrwttr.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gt2qwothmiy.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gt2grwhgaui.html

[U35] Py：发送邮件
来源：http://dali.cucudq.cn/Article/details/gt2umaxkmzf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gt2aiuuxejs.html

[U36] Py：定时任务
来源：http://dali.svipenyu.cn/Article/details/gt2pzddttyi.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gt2whhyogxe.html

[U37] Py：读写 Excel
来源：http://dali.xziqi.cn/Article/details/gt2vvijtcfr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gt2tzlbtssd.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gt2osnqffbr.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gt2jtmfmnty.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gt2nxaiopjp.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gt2xhprgviu.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flzropjt.html

print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gt2zzinnbmj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigufen.top/Article/details/gt2csunfetj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gt2krhorqxu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gt2jftfxkxs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gt2rlaczkyi.html

[U43] PHP：声明命名空间
来源：http://dali.zycfv.cn/Article/details/gt2kgkzjbkk.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gt2zyajpgbu.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gt2xvnccslm.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gt2waexobyz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gt2gwnrvadd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2ukhmynzp.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gt2ucwyvcmd.html

?string $name = null
来源：http://dali.ydzc1.top/Article/details/gt2tbmorheo.html

[U47] PHP：联合类型
来源：http://dali.ehwqpu.com/Article/details/gt2amyynkbz.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkohrihj.html

[U48] PHP：纯枚举
来源：http://dali.sysykeji.top/Article/details/gt2ncvgsefd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gt2jnjinkhe.html

[U49] PHP：只读属性
来源：http://dali.chenzaomai.com/Article/details/gt2fhgmvdmz.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gt2vpsilwcq.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gt2iewjahim.html

public function __construct(private int $id) {}
来源：http://dali.tanke756.top/Article/details/gt2qcvlzxzk.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gt2wsxdmvxt.html

[$a, $b] = $arr;
来源：http://dali.redwolf501.top/Article/details/gt2smoyfbyz.html

[U52] PHP：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gt2giravtbf.html

$double = fn($x) => $x * 2;
来源：http://dali.snrcjt.cn/Article/details/gt2tznmjeta.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gt2cwfabdsi.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gt2arxjagzp.html

[U54] PHP：空安全调用
来源：http://dali.sufxvd.cn/Article/details/gt2wvvatwaf.html

$obj?->method()
来源：http://dali.yuxming.cn/Article/details/gt2iawahdhv.html

[U55] PHP：match 表达式
来源：http://dali.hammf.cn/Article/details/gt2hjkwobwk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gt2hypjpdrg.html

[U56] PHP：命名参数
来源：http://dali.sufxvd.cn/Article/details/gt2ylutzdui.html

f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2ztuitfvk.html

[U57] PHP：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2tjqrsptk.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gt2rtgipdpi.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gt2qphvnzrb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2wcrvbzzb.html

[U59] PHP：自定义排序
来源：http://dali.tianlin.xyz/Article/details/gt2dbjeokpa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2ajruuwad.html

[U60] PHP：JSON 编解码
来源：http://dali.fengsongda.top/Article/details/gt2wysbfoby.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2aaqbthck.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gt2bwynqcnu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2jfqxmyfh.html

[U62] PHP：日期对象
来源：http://dali.snrcjt.cn/Article/details/gt2achuvzbi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gt2gpdyuyyv.html

[U63] PHP：文件读写
来源：http://dali.ehwqpu.com/Article/details/gt2xcobcvch.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpjizwpn.html

[U64] PHP：目录遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2gagzvbwd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tanke756.top/Article/details/gt2jqkixeah.html

[U65] PHP：会话
来源：http://dali.9152youxi.cn/Article/details/gt2cristipe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2guxbocob.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gt2avwmqvso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gt2etuaynbi.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gt2itxmdexk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.quarkkingdee.top/Article/details/gt2wppofwev.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gt2mefbjxak.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj20258.top/Article/details/gt2lteotvci.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gt2qruprclv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gt2wlqoraho.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gt2gfwfuqse.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwfxdwbd.html


<!-- 参考信息 -->