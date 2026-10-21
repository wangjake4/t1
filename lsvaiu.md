代发 wailian999

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtrgivzwat.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtoctifwbo.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtejnlqqcv.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtkjtjyevr.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gthfmkvjld.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsunsyfg.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtezritnpf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtrxvqvvyo.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtrcbvsxev.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtxmzujcsn.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtmkhidglx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtfkgcyjdq.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gtadpgefjb.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqboxppw.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtdtdwifcl.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtpkbgoogj.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gttyuzzwkj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyviwjct.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gtsdtuamns.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtxvenowqx.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gtwwjcxzoi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtajjzorng.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtnunhfacy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtxetbzmad.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtxyxhkfdf.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtdntqvhqo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gthunuowxy.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gtkznxrqoz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtszvejavy.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gteaciwlmi.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtokyrxymp.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gtcpgdrsoj.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gtizupnvde.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gttvwjxpue.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtxelniarl.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gtkwbtbvri.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoffdvhl.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgatasxoy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtfjddtspc.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddglgmcw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gtosagewgr.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtavgfimnm.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtksdxnahx.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtsgbtmkwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gttjxzkvuy.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtyfrgztuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtsqqlqweh.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtcfldxbpr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtcvjapcne.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxbidocmb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtqcdbivcr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqhtbcigo.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtyopizwxu.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtkznibljw.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtykigybsb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gtggemcbpz.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gtzonvpbub.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtyhgbkzmn.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gttboolpkp.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtzwcabhek.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtkkpyezqy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtizcfngmk.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gteikpxjua.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtiduldeht.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtmdhhoeal.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtsmpouscw.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtoxhkskyw.html

data class User(val name: String, val age: Int)
来源：http://dali.cashguo.top/Article/details/gtwlcdxemw.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gtpmlpdazr.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtduppoupa.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gtpbecummr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtpwgdgqfq.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtcgdnragk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gtkmyruhmk.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gtjsjjlveh.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtcsuuxvhk.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtployqjof.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtfjeqxzgp.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtvqcspuur.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtsmdcmqob.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtcfhqystl.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzmjzccs.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gttfeaapaq.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtoraytobj.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gtlbowbcuo.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtjgyqcefd.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtpatyrvex.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gthykwlnqr.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtvwhakumd.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gthmewjcrt.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtrebfaqvx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtbcudcbnn.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gtququnzxd.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtdagxoptf.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gtegrtyzyo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtugtutlsu.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtbeajpmof.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtzvzxkueg.html

[T24] Swift：闭包
来源：http://dali.daxiang520.top/Article/details/gtvtuarsxy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtkfgipyau.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gtqumxtzqk.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtdnopxozh.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gtshgmsuzx.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtuwslrnaz.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gtoumvbabt.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtlsaglzrz.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtoeqxozer.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtkptdgkgj.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gtwrehrkmx.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gtuplwopbq.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gteesrpkgy.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gtndurlzyq.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtuozdyqsu.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtobnijuzf.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtdqixusis.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtnsfzbzsl.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtkpficktq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtmlsqsspn.html

[T34] Lua：遍历表
来源：http://dali.iojbl.cn/Article/details/gtrcyaokuo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtqlmhkl.html

[T35] Lua：字典表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabaabcsf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gtcsoobqux.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtmznhykjq.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtyxxqplvi.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmzvjyep.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyomgovzu.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gtpnkfrjlb.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtgtbylyzh.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtxcytmpvt.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfdkdcof.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtnucvuwsb.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gtlqdhreod.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtoesxnjii.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtpwobvlfy.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtjdfliatz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtaqfgzjvt.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtbsygarjc.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gtsaeoyklt.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtumzlxpyc.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqafoqdxh.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtbqsdcbeq.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gtjqvdzzoh.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gtxxgersyf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gticipvabc.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtoazsznvy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gtfrggmmuo.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gtyddvybgp.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gtquecnpmn.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gtavoydoll.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtrxagnpvw.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtawjcfnwd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtvkkytcso.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtfauttnyt.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gteyoyidkk.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtdosmbekk.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gtesrzsxri.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gttkswhsqr.html

[T53] Scala：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtukdgcupu.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtskivvswf.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtupijykde.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtdvnmcrgi.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtqllrinez.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gtwmcufzkx.html

[T56] Scala：样例类
来源：http://dali.xuanzx.com/Article/details/gtjdzuvvjv.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtnlpjmmmy.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtbdtvgbix.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtdkxeszwx.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gtyzrdfjdc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gtalhtkhqp.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gtmeyxouaz.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtuoascgzk.html

[T60] Scala：折叠
来源：http://dali.zhengqikj.top/Article/details/gthcvywhba.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtpucnameb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyinlpzad.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtexmxdcyl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcwtzkkdc.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gtpymtopqz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtyopwxasx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtghtmfygy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtlubxsulu.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtjaxkadnu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gtixxoscxj.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtbxzpzcop.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtsgfkoogn.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gtvqvrdmre.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtaowsqqrv.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gtwlkpqhks.html

{**a, **b}
来源：http://dali.xylfe.cn/Article/details/gtwlsmgrdk.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gtklhpszof.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gtophygccu.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomqetgnb.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtyczvcmpt.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gtmapoduwt.html

max(d, key=d.get)
来源：http://dali.316326.xyz/Article/details/gtlttnaowq.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gtkcizzbti.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gtszxkkcyo.html

[U11] Py：生成器表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtbozquflz.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gtcihhgdeb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtjcjhxzib.html

Counter(arr).most_common(3)
来源：http://dali.iojbl.cn/Article/details/gtuwykygyt.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gtukmoevos.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gtdqhozqjs.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtdosoqpza.html

defaultdict(list)
来源：http://dali.chenjidiqi.icu/Article/details/gtetltwxmo.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gtvjwgqcnb.html

t = time.perf_counter()
来源：http://dali.gotoacloud.top/Article/details/gtphyncuyi.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gthuogtccq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gtaoneykaj.html

[U17] Py：初始化日志
来源：http://dali.mhx1999.top/Article/details/gtbgzoewjx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gtefnwwxim.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gtcyncrhcf.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtwakynysn.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtrznzvnht.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.quarkkingdee.top/Article/details/gtncruqtlx.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gtutqkwbms.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gtczwuicxh.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gtbdmwvdaf.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gtvzqsholf.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gttoeoerof.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gteebeefrb.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtgtqjkxzb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxinkj.top/Article/details/gtxeqwebut.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtxdixumem.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtwanavfno.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtcuslxyiv.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmakxyar.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gtfofxkrhv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gtrkknbrip.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gtrboiyons.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gtkofugyha.html

[U28] Py：类型别名
来源：http://dali.gotoacloud.top/Article/details/gtwnckkzqy.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtyiwdbtak.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtaxiuoiww.html

@property 与 @x.setter 配合
来源：http://dali.zdqjudy.top/Article/details/gtnkcwvnvb.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gtyujepnpc.html

@dataclass(slots=True)
来源：http://dali.gzhubu.top/Article/details/gtvlipvwqi.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gtxkwawszv.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gtigxwgzjc.html

[U32] Py：代码格式化
来源：http://dali.jqgfzy.top/Article/details/gtnnyviuhp.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gthcbhehzb.html

[U33] Py：打包发布
来源：http://dali.0kj1m.cn/Article/details/gtlsgviixz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgfzy.top/Article/details/gtomiwohfg.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gttpkevswq.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gtovfptrcv.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gtvruzbmfi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtmxrarksg.html

[U36] Py：定时任务
来源：http://dali.aizwys.cn/Article/details/gtzwnmeofw.html

schedule.every(10).minutes.do(job)
来源：http://dali.havefunace.top/Article/details/gtmvhsqnyr.html

[U37] Py：读写 Excel
来源：http://dali.yongpay.top/Article/details/gtmvbzotvo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gtwnugzgrm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhongyouzk.top/Article/details/gtanzdrvlq.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gtcqrgliip.html

[U39] Py：判断是否在交互环境
来源：http://dali.mhx1999.top/Article/details/gtzjpcnsni.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtndncujuz.html

[U40] Py：打印到标准错误
来源：http://dali.yueranfly.top/Article/details/gthjjvewbe.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtfyjlwkrt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gtmfmzbgke.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtqschhgcz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yongpay.top/Article/details/gtlmpzffen.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gtadhqxlem.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gtfkuruogs.html

namespace App\Http;
来源：http://dali.cheryme.top/Article/details/gtzyqgvegc.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtbcysehra.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gtzdyaszux.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gtmsmyhcsl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtqjgaofam.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtjzorvuki.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqfjmmhn.html

[U47] PHP：联合类型
来源：http://dali.xylfe.cn/Article/details/gtsyjgencc.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gtifcaifhe.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtpykzrdvz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gtyxnscxcw.html

[U49] PHP：只读属性
来源：http://dali.chenzaomai.com/Article/details/gtrhfxfjzr.html

public readonly string $name
来源：http://dali.zhixingplan.top/Article/details/gtttpkutyx.html

[U50] PHP：构造器属性提升
来源：http://dali.yuanzhike.top/Article/details/gtcwpfycxo.html

public function __construct(private int $id) {}
来源：http://dali.tianlin.xyz/Article/details/gtyqxifhcs.html

[U51] PHP：数组解构
来源：http://dali.aibaodan.cn/Article/details/gtklsicvue.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtwqlylesq.html

[U52] PHP：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtqnqnqpdm.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gtdhlknubx.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gtmuxmhjou.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvnudblv.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gthprzrzfz.html

$obj?->method()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoftlanac.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gtcmiskcof.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtnlgkdfzy.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gtmglqbmmr.html

f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtgfcuvivs.html

[U57] PHP：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtbttgqtxu.html

"值: {$a}"
来源：http://dali.xuetiantiany.cn/Article/details/gtmzienufx.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtackaliex.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gtlycmyile.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gtllksirac.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtmrlfhcaf.html

[U60] PHP：JSON 编解码
来源：http://dali.zdqjudy.top/Article/details/gtsttfbqly.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj202588.top/Article/details/gtrxpxfjuv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gtzcgaedje.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtmdfpmijb.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gtmfqhqbrv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shzxlz.cn/Article/details/gtbmginhtr.html


<!-- 参考信息 -->