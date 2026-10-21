代发 wailian999

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtailcqnxr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gthjrywuat.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtghwenxuf.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhuaavci.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gtkbmzrnmv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtoebfeart.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtszvqwals.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtdgsphrki.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtzxnpvkoe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtxsucxduf.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtkvfokjoy.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtncesqoup.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gtpdvpbhts.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtipcxthof.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gtwqfojmih.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gtfdenzdsv.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtubtlslrl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtppxdrbnp.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumqsdssz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtmbrriapx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtayywqxgi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtfqdkucpm.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtwxnpjdbl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtbihhqqkq.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtsejtnfjx.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gthftpjecx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtqfikxruy.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtzowyxthz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtvhlwpkri.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtjonmufpv.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtlpbtugtd.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtfyvxupnr.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gtcbohrnay.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtchcgbzpj.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtabqkibgu.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtkmcdmlpz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtfcbychue.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtgnheifaz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtxvndxljz.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtllihunpv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtsaawglux.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtizgpncop.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gthzvoxiwb.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtrekggqkm.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtvvyvllgx.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gteqwdorwp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtbhrugwkk.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtwszgeekw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtprrvzjqz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtaoffktge.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtpcpjjsqw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvxnhtrui.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtgdhxklgb.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtsgrjwfrx.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtnmhonovp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gtujcfieav.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtpqczkvrj.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtokxrhbtq.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtwlszksyy.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtkssiaxpg.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtlekyfnep.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gtyrfantqu.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gtocbsnplw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtaqlblxyt.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gttwpvqevv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtsncrrmga.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gthtnbwcjz.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtlgpiqdih.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojgriarh.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtmlzpqenr.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtvmgqenwl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtcutlyrbc.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtidqdrgyf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtvwttitbr.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gtxpiqfkfu.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtsogxwvhj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtpniadfyx.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtiyrseysz.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtxyemvjwq.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gttnnsmxio.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtrnbtkkka.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gtpdizznoa.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtsjjwwawf.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtzypkluvy.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtirmsalgc.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gtilxuqtts.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtxxvqqjjv.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtrxsneasy.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtotnvmphr.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gthredemat.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gtotcpsgpd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtvypmmgoh.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gteguzphok.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtnuraqqsy.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gtbfchqlaa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gtecvyzzky.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gtqscgxnfy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gthhijktyy.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzokuazmd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gterxripqr.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtfijnkodj.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtjbhmebgm.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gtysicrfup.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtnnljlhfs.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbwmiiuu.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gtumrmrntr.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtidnwykun.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtviqcrfod.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtcfzizreq.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtijahgwzj.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtlpmftgzo.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gtuqbzccyu.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtbbsnflrv.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtjiqzqozi.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtcdreeewu.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtkyhavixd.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gteinramdm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtflhjkiws.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtrtujmptf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtvcmqgjzb.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtrwaxvdba.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhqbcdag.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtbnzkgwdp.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gtbbeqhxcq.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtmsombyed.html

"a" .. "b"
来源：http://dali.yangfankeji.com/Article/details/gtngbknfxb.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfloumnf.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtmqcycmyz.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gteetajvaa.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtqpxcvuuq.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtyutubdni.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gtuwgvqpro.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtrylrmypi.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gtjdcnqrqq.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtuebtehek.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtntxpdifq.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtrlfhxcwa.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtovvtmbwa.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gtnaixjjhz.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtoirsqjuf.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gtvwrrghtq.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtjrpksqan.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtrexruoce.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gtxiniblvz.html

[T47] Perl：正则捕获
来源：http://dali.kuanghao11.cn/Article/details/gtlwnqffyr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtwedzllkt.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gtjsiurnom.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gterrrfsid.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpbwizin.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtkljmukzs.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gttrdtytia.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtleiurogw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtoqipkimw.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtygorrgvp.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtcqughaux.html

[T52] Scala：变量
来源：http://dali.gogol.net.cn/Article/details/gtkdwdjdzb.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gtlvbcymke.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtscdbfcme.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtjsmpwhkh.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtwudqggpy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gtgpzbqtkh.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gterljkbhd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlijbdpm.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtdldgyuor.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gtzoznenkv.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtegrklvnm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtljojcdip.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gtiwsmkrci.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtwgkoqvuu.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gtfsfpcmsz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtfbewngnz.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtbrosjcqp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuebktna.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttdqcmcrh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtqeoxctlq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmbqeidnq.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gtxidvnwbl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gthauxhhbj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gtgtgfouxj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtwltbakft.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtibronvwj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yvedp.cn/Article/details/gtpbnqkytu.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gtfybxgjif.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gthynqfime.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gtuzcchgoi.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtppwacqnz.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gtpgglvguc.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtnrtsmsfe.html

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gtkdolfqdl.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gteuifjbcv.html

[U08] Py：展平二维列表
来源：http://dali.yueranfly.top/Article/details/gtweainqds.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gtfkvpvvaq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhengqikj.top/Article/details/gtnfyzalxh.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtcjgtcjrq.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtwbwywubm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gtybaxshzb.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtkhpihsuq.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gttxhaytbk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtuegocmoq.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gtlxvmlklz.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gthelcejcu.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtengvyrby.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gtrgxgvmvu.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gtrcfopuqh.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gthernzgky.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gtcytvknbn.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gtqeouzhnw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gttdzknsey.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gtsdnjxtim.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gtgrkunjvd.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gtjxamfrfv.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyjirffi.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtharkbbqo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenzaomai.com/Article/details/gtfhdsmhlp.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtyxawfmkl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gtatktreil.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gtyeobhcwt.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtzondnfmy.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gtezjhvogj.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gtmgeqimyp.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtawoiidob.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtpupmwhka.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtdmtaxovk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtfqfiwnck.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsfjcoet.html

csv.DictReader(f)
来源：http://dali.hammf.cn/Article/details/gtsvvdiclz.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtgignmwwn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gtuhvnmvhm.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gtmqyzpzns.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjvtlooo.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gtffuufosa.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gtxsjiledh.html

[U29] Py：属性校验
来源：http://dali.c1oappe.top/Article/details/gtrhnppspe.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gtewecjkrc.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtkocfusud.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gtvbdxuwvb.html

[U31] Py：单测
来源：http://dali.zdqjudy.top/Article/details/gtgdvpghxc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtalrynkjw.html

[U32] Py：代码格式化
来源：http://dali.hnxiangtu.top/Article/details/gtrzpujqwn.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtipmtunei.html

[U33] Py：打包发布
来源：http://dali.dianchejie.cn/Article/details/gtbosttwcw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sweek.top/Article/details/gtgwwkyqie.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gtiljweuca.html

chardet.detect(raw)
来源：http://dali.hnqzz.top/Article/details/gtuqggohcs.html

[U35] Py：发送邮件
来源：http://dali.xinyue.icu/Article/details/gthnnodeak.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gtemepvrnb.html

[U36] Py：定时任务
来源：http://dali.yueranfly.top/Article/details/gtkscfxota.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsunnlgw.html

[U37] Py：读写 Excel
来源：http://dali.zhiwuduotai.top/Article/details/gtzcwpbgsf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtjyciijml.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gtxbogxkzm.html

Path(__file__).resolve().parent
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwgyfirg.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gtonjeirht.html

sys.stdout.isatty()
来源：http://dali.ppjwa.cn/Article/details/gtampdampr.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gtgmwlkpua.html

print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhotegge.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxuanxn.top/Article/details/gtsmfptoek.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yueranfly.top/Article/details/gtbnlgukjc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pengpengdd.cyou/Article/details/gtotfxdvdv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhengqikj.top/Article/details/gtmozmqceh.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtlwkrokzq.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gtaqbndmqb.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gthcoltgvo.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gtvbguwexw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.meibo888.top/Article/details/gtufefghgl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbqkaety.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkgzlell.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gthnuozzlb.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtlvllrx.html

int|string $id
来源：http://dali.dashuyun.cn/Article/details/gtrtvhtrrs.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gtfdacfqhp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmeilhnk.html

[U49] PHP：只读属性
来源：http://dali.jyoumei.cn/Article/details/gtchphywtl.html

public readonly string $name
来源：http://dali.gaohongyu789.top/Article/details/gtieocnsru.html

[U50] PHP：构造器属性提升
来源：http://dali.jinghuilouyu.cn/Article/details/gthcwimqwb.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gtktkaeaqu.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gtgaxdrggf.html

[$a, $b] = $arr;
来源：http://dali.ehwqpu.com/Article/details/gtwgaspdfb.html

[U52] PHP：箭头函数
来源：http://dali.c1oappe.top/Article/details/gtzmdcmvhw.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gtjedoqkfn.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gtzuxrsaky.html

$v = $a ?? $b ?? "default";
来源：http://dali.nwbrower.top/Article/details/gtawrauhjn.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gtjlsgnwgl.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gtfqfjdlih.html

[U55] PHP：match 表达式
来源：http://dali.sweek.top/Article/details/gtoddxcukm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtixeudvzj.html

[U56] PHP：命名参数
来源：http://dali.chenzaomai.com/Article/details/gtfvsmznoo.html

f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtfypgpeon.html

[U57] PHP：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtkkjbcexp.html

"值: {$a}"
来源：http://dali.zhoulong.xyz/Article/details/gtcupvbave.html

[U58] PHP：数组三件套
来源：http://dali.jiagoushi.top/Article/details/gthuqwksvd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.9152youxi.cn/Article/details/gtqiyggeak.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtyeauoheh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtjimqerxc.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gtsfaothjf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gtnwagaohy.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gtewegshvv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtluugbtxb.html

[U62] PHP：日期对象
来源：http://dali.daria6918.cn/Article/details/gtteheopya.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gtzynmizod.html


<!-- 参考信息 -->