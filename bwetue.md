代发 wailian999

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtyfteewav.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtfosfhrvq.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtllkahoyt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gtfshittgd.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtyivxcrvw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtrjatmowv.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtwwfwvjyy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtpowmehxt.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtnamixree.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gterfpzves.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtmoccsaps.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgogwndg.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtguwfaeeo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtyqttseov.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtchlqwzuk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gtkazxwlfv.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdyzkyfi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gtgvuwgiud.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtfevldayn.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gtxbsiutnp.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtspqeavdg.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gtswovfmfu.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtjctkeeub.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtyhfpsefj.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtbohbntjq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjgbhqlm.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtrouynnhm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtvyawbiue.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtsehfvwqn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtlfyojcpv.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtnjpaqhuq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakvgzqqs.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gttkithlnu.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtxmfjpqlu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomtmljfb.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtuyincojm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gttlqbnmyo.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtcjrqmzao.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtgkffgfvh.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gtgqxxntbs.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gtiuspqlgy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtnlnosxgb.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtfafjbbby.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtfdhhvbpy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtxbghedsw.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtbfkduixt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtjbudexef.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtigkduphr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtfywtbivf.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gtvghjzfle.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtuibtwlwa.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtzzmvvbbd.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gttaedbnye.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gtksbeuoof.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtvdognmpd.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtcieipakr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtiwqnxsmf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdflzoowd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtzndsocpn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtibexbbkn.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtapplorgf.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtdtvxodji.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtfkcnyqah.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtqhgthzms.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtowjhceds.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtpuduxjbk.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gtgmooxiln.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gtevrbekac.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gthenxawal.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gtqioxlscp.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtjlfapdiq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtwqpbgkfk.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtkxiwisym.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtegqounro.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtostcnlqs.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinvemgrp.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtnimsozpa.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtjyghvnna.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtndlmsrnv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtnonmfatd.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gtwawblqzi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtcroivvki.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtjjxssdpg.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtosudyyof.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtwkjbqybr.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gtlmbfyzya.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gthtiorngq.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtunlzmxbs.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gthwqecmgi.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtqigdqcrb.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtaixfcoxt.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtkbazdhpj.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gtmsdnglzt.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtevuwwusu.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gtppxclubx.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtvcwjvdkp.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtnxymomoa.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtlcothfuv.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gtiegbgkix.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtnbzobkid.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtirejbsnj.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gthrdfwdiy.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtvrsmzlxh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrsckcbc.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtunfhoqzn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtyodxvsdp.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtizpjqhne.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdhiiqwq.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtwpflhjjp.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtjxjldypv.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtxlpzrojk.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gtfnflljmu.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gtkoahevik.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtyengpnhh.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gtofyrgafh.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtzpkopwkl.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gterlkcqil.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gtdisyriqn.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtjhwnwvll.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gtslgpxsuk.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtefcdmtyb.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtxlzejfpy.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtlarzeiuh.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtieoionsn.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtkxrocjni.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtkiomjyxk.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gtfttijvqt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtweqgneuo.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtpunktieb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gtowatnadv.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtsycrlbuc.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gtgxaeqejc.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtaekxiggz.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtegwspsfl.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtyladvrcw.html

if x > 0 then print("正") end
来源：http://dali.yuxming.cn/Article/details/gtodzaxidw.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtuhmsfooq.html

string.find(s, "%d+")
来源：http://dali.birdmap.top/Article/details/gtadyqmzuq.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gtghtvotbl.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtjdrugrgu.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtgvyfervq.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtjqswbxyg.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtqjcvekly.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrooqqavn.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtddjitzgs.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtzbyizmva.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gtabfognhq.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtjbtgcasw.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gteljbdqzk.html

for my $x (@arr) { print $x; }
来源：http://dali.tian-w.cn/Article/details/gtmpdwqsjx.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtdzswzahq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtclibnhrm.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtziwvinjo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gtzaswyisw.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbhntlug.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtaqbfulbq.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtwcvuouje.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtcrdwfzuw.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtrgxsdpqg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gtxyhvynac.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtghcfuvod.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtgrbydbum.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtpghhgrdm.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtojgvofqo.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtzvqllncj.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gtrdtgjtto.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtkvgfkulz.html

[T54] Scala：集合映射
来源：http://dali.c1oappe.top/Article/details/gtjbbixktw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gtzcenxscu.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtbqhrthjn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gtihgbifeg.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtymyichda.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtouiwhvft.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtgldhjmkr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gtsvdqyozy.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gtlhdfwmne.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gtuhbaxocj.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gtvwlgzsnx.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gtuvcuntva.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gthtkrqkky.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtmygmeqgn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbaktqigp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtgiorlttv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwsfaric.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtjlhdmuft.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtxasxermz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtuzfjvptd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtiluaonig.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtesvfebbr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cqqwz.cn/Article/details/gtkwyhscwa.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtalhruzat.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtgrgeknjt.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtvulonhbk.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtllzkiudt.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gtevhpbglg.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzcmbgub.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gtknmsjhyk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gtfjmewugk.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtcnqoqjnv.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gtcuzvyiuj.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtfuczydbb.html

max(d, key=d.get)
来源：http://dali.jinqigufen.top/Article/details/gtsqecjnli.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gttxqujuil.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtjrollzii.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtlecyxmjt.html

(x * 2 for x in arr)
来源：http://dali.ehwqpu.com/Article/details/gtzaldtgph.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtltjqszyf.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gtrxafecsc.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtwazmdwrk.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gtmrnsnrxm.html

[U14] Py：分组收集到列表
来源：http://dali.guowangkeji.top/Article/details/gtanowjyyy.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gtgzbnjirg.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gtclepakmb.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gtonojiqqq.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gtdcueuqyh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gtniozuidw.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gttkmsavqb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gotoacloud.top/Article/details/gtiggmrrnf.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtxzaxqbtl.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtpzotixry.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gtuxfnpxtv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtscgzvhlb.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gtpgxuiztp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtmnghvbnm.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gtvoxbuuhr.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gtlgjbxfwo.html

[U22] Py：矩阵转置
来源：http://dali.pycfn.com/Article/details/gtrhfcofbg.html

list(zip(*m))
来源：http://dali.fzhhl.top/Article/details/gtzmebasiy.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gtetfpoxfj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cucudq.cn/Article/details/gtygsfvjcb.html

[U24] Py：路径操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfwvsnmu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtouhllyuc.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gtmiyntolm.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gtvtvgpxvm.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gtiqiyncwn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gteqygsczt.html

[U27] Py：异步 HTTP
来源：http://dali.smart0.xyz/Article/details/gttbyrwcnt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.feifeiyinyue.top/Article/details/gtdkqsmpve.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtpmfyehus.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gtydxbyswv.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gtnbhvxpbl.html

@property 与 @x.setter 配合
来源：http://dali.yangfankeji.com/Article/details/gteldgrrui.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtqbiggmtg.html

@dataclass(slots=True)
来源：http://dali.daria6918.cn/Article/details/gthvzdkugn.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gtfxngnpxc.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtkmhipbxj.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkjqbagdb.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtyfqmwura.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gtcahdfoyd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gtcsbqxxmx.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gtisrlqnaj.html

chardet.detect(raw)
来源：http://dali.daxiang520.top/Article/details/gtlniigbls.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gtmahsllot.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gtekvvprdc.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gttktbqpzc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtgauxhszr.html

[U37] Py：读写 Excel
来源：http://dali.ybcxt.top/Article/details/gtybbpndcq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhengqikj.top/Article/details/gtcffsgsjx.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gtrpckctpj.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gtlxdgwdeu.html

[U39] Py：判断是否在交互环境
来源：http://dali.nwbrower.top/Article/details/gtltlwofuw.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gtpjkqlmlp.html

[U40] Py：打印到标准错误
来源：http://dali.xylfe.cn/Article/details/gtiiojkick.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtsodykfvh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fengsongda.top/Article/details/gtgvdbjxje.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tian-w.cn/Article/details/gtkczofjeb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtaxzpfafz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gtijqpderz.html

[U43] PHP：声明命名空间
来源：http://dali.fzhhl.top/Article/details/gtqchryyum.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gtexkvrohx.html

[U44] PHP：开启严格类型
来源：http://dali.pengpengdd.cyou/Article/details/gtnavubbuk.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gteyccpngv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hammf.cn/Article/details/gtlsbexilj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtlndxtojf.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gtgddfvuws.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gtnrwqxprj.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gteuikykuj.html

int|string $id
来源：http://dali.ydzc1.top/Article/details/gtxaebcqcf.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gtgnyklnjg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.bjfxy.top/Article/details/gtrrffxlai.html

[U49] PHP：只读属性
来源：http://dali.zhoulong.xyz/Article/details/gtwciqbkjh.html

public readonly string $name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkupuumf.html

[U50] PHP：构造器属性提升
来源：http://dali.dianchejie.cn/Article/details/gteqjumbbg.html

public function __construct(private int $id) {}
来源：http://dali.xuanzx.com/Article/details/gtaupubolp.html

[U51] PHP：数组解构
来源：http://dali.jlsjyb.cn/Article/details/gtsfvhmefd.html

[$a, $b] = $arr;
来源：http://dali.jqgufenzy.top/Article/details/gttlhmtnvo.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjytdczl.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gtnasxvudo.html

[U53] PHP：空合并运算符
来源：http://dali.xinyue.icu/Article/details/gtamzoiuzm.html

$v = $a ?? $b ?? "default";
来源：http://dali.yanxiufei.cn/Article/details/gtphdlxbam.html

[U54] PHP：空安全调用
来源：http://dali.haohaochexian.top/Article/details/gtdvdlbeaf.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gtyrywtsox.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gttavnghem.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gtowdzoaoe.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gtevljrsln.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtnrnoubwu.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtmzqkltvq.html

"值: {$a}"
来源：http://dali.iojbl.cn/Article/details/gtgelagxlg.html

[U58] PHP：数组三件套
来源：http://dali.xuanzx.com/Article/details/gtnuouycdh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gtrobueyux.html


<!-- 参考信息 -->