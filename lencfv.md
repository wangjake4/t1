代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gtbfphcfry.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtcydmqotv.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gthqtxavix.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtmdpxyzfl.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gtsrowwpaf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gteissfcqh.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtfozubqtz.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoglvxwun.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtxltwcxsb.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtlsgbmwnr.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtywhbdmxo.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtfdkfhqkd.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtgesrzpsh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtzlapokgx.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqpmvmmw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtzwybapdf.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtoqaxqznn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gttnwkhhkj.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtbcxujesk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtsneublib.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtjjxvqrew.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtbmuwoqaz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gthakznebp.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtydxhyhsq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtycjajzqj.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gthbawqdjw.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtcstreasp.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtfsdpaxjt.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gtteatsosu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtubytdkek.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtxxpggfce.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gtfbikgmhw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gttjcbfjbv.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtwwkgqrhq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gthiaoudcy.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtvejcslyz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtwquqhwfr.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtfawwvcpu.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeacoemj.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtxifxgzck.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtrjqqbkub.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtntptmtix.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gtthzcqplw.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtktrvgnbi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtzmebqxzx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqiknqmwe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtbxdypujo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtangiblpd.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtnhwxatwb.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtmrvpmvpd.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtkjzvfrwc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gthpcgmszy.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtveuobnje.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtmeziytid.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gtxdblwczg.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gtaokzmgaw.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gtuoynxvxg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtufibjtzs.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtasvdtuty.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtqhjgzxsk.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gteceiqfob.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtoginuccc.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gthrmflsja.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtsjrivaur.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtuvhlzxxx.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gthktxgfjk.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gtlhayhqzz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtxvnrsvtv.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtmsovfxcz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtjkiiesvv.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gtdhevutlj.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gteecfcsfh.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtejatxilk.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtsoijkqva.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtbpedejtd.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtoxhlzixy.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtjwqchmzs.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtxquvuped.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtcsmqziis.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtetnyjbea.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtujazkwty.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtdrhibkjs.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtrawejnfc.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gtdveqtpyo.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtyphjartg.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gtsbrehwlq.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtdwdfjbtl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnekmjele.html

[T21] Swift：遍历
来源：http://dali.aibaodan.cn/Article/details/gtyghgpqce.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gtbldgxnsk.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtbbhbrxmg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gtgpymplih.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtdlvodqak.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtgjyfujvg.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gtjinvobsi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtmoqckwbo.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gtktasiytt.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkerqyjsg.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gtqlvmxwgj.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtjrihmvdz.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmutygckp.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtjfviqdlp.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghenibzd.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gtrgabeklb.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtkvikhbdw.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtdyckwpgz.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtqgbbydls.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtuigveuwd.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtghvmaidp.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtqgrfnqko.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtuxfipcai.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gtitnyresq.html

[T33] Lua：表（数组）
来源：http://dali.zhoulong.xyz/Article/details/gtkvwyvswb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gtgozoucxe.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtbrniqcct.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gtlmepnxjp.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtgtnrrnwu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtwyudgytg.html

[T36] Lua：函数
来源：http://dali.yonumen.top/Article/details/gtdximvflx.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gtxtfputmv.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtzuliyjxg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtyhmoitbn.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtobjccysg.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulkcoahi.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtyuwjmquh.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gtjqtvkbhq.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gtuhbftasm.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gttebpajtz.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtrhtjqrav.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gtzccnhjmk.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtzcjxggon.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtszcrhhtl.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtghhwzjxh.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtyeapisbt.html

[T44] Perl：条件
来源：http://dali.tian-w.cn/Article/details/gtbhrpkkhy.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gtgwgrttpj.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtmfkhgxls.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtcolsxlvw.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gtaucfenpb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqhmdbez.html

[T47] Perl：正则捕获
来源：http://dali.jyoumei.cn/Article/details/gtrvhvdmes.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznhzexzc.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtkaqztllm.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtmfigmtlg.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gtfexuutng.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtczfyzxsq.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtcnjgywzf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjymdpazy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gtelfcehft.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtotpdzjfn.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gttttcgizy.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gtmftpanpy.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtejkpyasl.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtcravgpdt.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtrcrvulbq.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtkiycoixi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtoqhtqndo.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gthfgkbqhk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cheryme.top/Article/details/gtcsvjhqab.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtjqjwigae.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtswyripfz.html

[T57] Scala：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtlhadqjxx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtlcnejzdt.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtljyejqcy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gtwqboxkrw.html

[T59] Scala：循环
来源：http://dali.cdnleiting.top/Article/details/gtasdkxfeu.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gttcdbvgqz.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtmpixoyfs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtdgqdqrbd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtylsswhwz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtkrcevmtg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtemveogsg.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gttalchefu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.mhx1999.top/Article/details/gtvjychomr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gtagotntnp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtkctwgbfv.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtiljejspn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gtihdlrwdm.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohdtnjqx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gtpmzntgxf.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gtoixnklcp.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtoadbanxg.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtzaqasrvy.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gtnyctdrjs.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gtfegzwoyv.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtsbjbxvvx.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtzicyhjzn.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gtepfkvzyu.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gtbteqbitv.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gtkempygmq.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gtuqrkfcka.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gtlishhuyz.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtfhjqcygh.html

(x * 2 for x in arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvddiswq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gtzghpwzpr.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtzlhrkcbg.html

[U13] Py：固定长度队列
来源：http://dali.ehwqpu.com/Article/details/gtftzfvjxg.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtqgxekmat.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gtdxlbcrvm.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gtfvnckitp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gtjjfhpuze.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtotjrcqks.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gtpsuinziu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gtlqwsjplv.html

[U17] Py：初始化日志
来源：http://dali.gogol.net.cn/Article/details/gtuzofhinz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gtwizfedbg.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gtvwefpwvz.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gtximzoziq.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gtznrgiowv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrrkszlq.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gtayckrcga.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gtcyvaubnf.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtkvajtjbz.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtggmlekxz.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gtovbkwaxe.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gtzxxxaxab.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtyeltzlcf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtllvvktjg.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gtjkmhxezk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtrjhuwezw.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gtzbgmmopi.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtgffsolue.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gtjkabnzqt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gtfgouyqaa.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gtlzpqubtj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gtjcwyoeel.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gternccafy.html

UserId = int
来源：http://dali.shuidangran.top/Article/details/gtlsoskswe.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtjrouscjf.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gtmvsedcfr.html

[U30] Py：数据类
来源：http://dali.hysaishi.cn/Article/details/gtaccrqyeh.html

@dataclass(slots=True)
来源：http://dali.sweek.top/Article/details/gtzafvcayk.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtxugdkxbs.html

python -m pytest -q
来源：http://dali.yj202588.top/Article/details/gtuppkmnyb.html

[U32] Py：代码格式化
来源：http://dali.hnxiangtu.top/Article/details/gtskfkxjeg.html

ruff format . && ruff check --fix .
来源：http://dali.cdnleiting.top/Article/details/gtolredvph.html

[U33] Py：打包发布
来源：http://dali.snrcjt.cn/Article/details/gtuhaqaueq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtllarwqxq.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtotmavoqb.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gtvsmeeqqq.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtsvudeeib.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gturcbrejc.html

[U36] Py：定时任务
来源：http://dali.mhx1999.top/Article/details/gtsiumccgs.html

schedule.every(10).minutes.do(job)
来源：http://dali.cqqwz.cn/Article/details/gtjpxpbytz.html

[U37] Py：读写 Excel
来源：http://dali.havefunace.top/Article/details/gteuhvdias.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtnvnirdfm.html

[U38] Py：获取脚本所在目录
来源：http://dali.gotoacloud.top/Article/details/gttfnrfizm.html

Path(__file__).resolve().parent
来源：http://dali.sxryk.cn/Article/details/gtvbdbraha.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gtueqxulhg.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gtffhaurmc.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gtkeorpjmq.html

print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtpypnroiq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjficjmd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgfzy.top/Article/details/gtalhjxwxi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gtwznidcqm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cdnleiting.top/Article/details/gtuaddgxsi.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gtjnneumqi.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gtkvwgxghv.html

[U44] PHP：开启严格类型
来源：http://dali.mhx1999.top/Article/details/gtsyvuxhuf.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gtwrbmjhfk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygsekfii.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyueiaku.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gtvnbdaeaj.html

?string $name = null
来源：http://dali.dashuyun.cn/Article/details/gtminursfg.html

[U47] PHP：联合类型
来源：http://dali.316326.xyz/Article/details/gttossgprf.html

int|string $id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaidmbvb.html

[U48] PHP：纯枚举
来源：http://dali.0kj1m.cn/Article/details/gttjablyzt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfiprcqb.html

[U49] PHP：只读属性
来源：http://dali.gogol.net.cn/Article/details/gtvdcrrdwz.html

public readonly string $name
来源：http://dali.sweek.top/Article/details/gtyyfmodan.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gtzfpqdvun.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gtzzfpvjob.html

[U51] PHP：数组解构
来源：http://dali.sysykeji.top/Article/details/gthsewqksz.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtpvalinno.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gtaxmkbeyl.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtzapxgxpw.html

[U53] PHP：空合并运算符
来源：http://dali.cheryme.top/Article/details/gtjcvachoz.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gtunzatcck.html

[U54] PHP：空安全调用
来源：http://dali.jyoumei.cn/Article/details/gtonzwiutx.html

$obj?->method()
来源：http://dali.zhengqikj.top/Article/details/gtxdmcfjui.html

[U55] PHP：match 表达式
来源：http://dali.hfpthk.cn/Article/details/gtzlznogkf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gtxidbpvjb.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gtfkblbsvs.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtufutdbpz.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtpablpuvt.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gtupcendby.html

[U58] PHP：数组三件套
来源：http://dali.yonumen.top/Article/details/gtoooqjwmh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gtnssujpyk.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gtbncprnzf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtqxslwpnw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gtombtkdor.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pycfn.com/Article/details/gtonfatxht.html

[U61] PHP：正则
来源：http://dali.fzhhl.top/Article/details/gtotdlbcby.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtlmzbtimq.html

[U62] PHP：日期对象
来源：http://dali.hammf.cn/Article/details/gtiyuxcfmy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.svipenyu.cn/Article/details/gtgwpocgyn.html

[U63] PHP：文件读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplewogsb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pengpengdd.cyou/Article/details/gtoajvzzhn.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqynhllw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigfzy.top/Article/details/gtjrrsdyzg.html


<!-- 参考信息 -->