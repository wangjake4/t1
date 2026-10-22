代发 wailian999

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtmttemszp.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtawvhqtfa.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhrcrqgw.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxiwhyqu.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtwywlmlok.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtroygkfae.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gtykgqrgug.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtpwpcsktg.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtnvymrnyl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzhtiomw.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmspsdilm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gttuiqgcka.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtwernofju.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuwcpzze.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gtjiqjqbtx.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtbuuxsqhj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtjekjzrjb.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtnneurggu.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gtckwduxiz.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gtfojcznlv.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykqwwyxy.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gtekniqaac.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gtugnyvmwk.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtjqupqgsv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtxvntqisn.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtnefletie.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtutmdubid.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfbvhexu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gthgvirazt.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtnpnnmcty.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gthripzcfs.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtmykydape.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gtjrpxtnqe.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gteuboilft.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtgdllhmqt.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gtdfkzpmsr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gtdrnvtqth.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxuoblgeh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtpshmapta.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttqwrlzvy.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gtaxwtpfkd.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtiumgskii.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gtewfrkhyc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtticngtqj.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gtuxyksjaf.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtqdbjqclc.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtjzqwrljb.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtpzqciaxe.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtqpfdnvjz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtqzfllcpq.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtvsqasncu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtguyginrb.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gthljflfsw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavnilgmq.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtqdevyfac.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtwmuokpcy.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtunjsmmtf.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gthhlrfpey.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gttcteykcu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tanke756.top/Article/details/gtaquwootq.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtejpvvyoq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gtjzntaakl.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnquthli.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtognjyhvr.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtsqcampkx.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtqbmpjuei.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtcxhwghly.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtcvqqogsy.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gtjtbzatnc.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtoydcnxpt.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtvsvgaahe.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtyulkxpkm.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtyxqtpaxn.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtwlxndlcq.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtlbfuogye.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gtoxzrndhy.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtijsguzov.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gtakeuzrfu.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtcbphuzmp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtupwdhsho.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtazsztcku.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtkwoaqkmt.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtnlmrhmur.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gttakgmwmw.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtcnbaexxa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gtnxymiuex.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtoauznaid.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtsjvmsuuk.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtgvvqncbm.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtzexwbfbq.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtxqnkbpwv.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtsxqhcifm.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtkotnbewp.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbadypqzx.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtjwkngjxo.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnvlgvzf.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gttalfshat.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabeajmlf.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gttpptmsji.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrijfnlb.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtsfxpoizm.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gthnrgxhdt.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gtnjcuqxsi.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtlujaaqky.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtpfeuejzm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtyriprszh.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtqbjcgnxw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtafbzaghe.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtjbaczngj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gttjcldyhy.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gthojsblhc.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gtnmtuqafh.html

[T37] Lua：字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtfwhoxsfo.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiuxobmf.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtgalxzrkp.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtknnsgith.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtiewcnhhp.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtzjcedpda.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gthohfuszg.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtvcutdmxk.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtnwoeenhb.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlctusfmw.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtbnmwghaz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gtfduncjhn.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtjxwcxvma.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gtahblhmth.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gtosflvjuo.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtltqpxoti.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gthieyxyak.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtvmzgkaph.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gtxicjhobp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtkcvgmypu.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gtjpomejqq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtgcwulwvd.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gthyazfpki.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofbwiovr.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvebtkclx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtwplmxlfz.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtxbaqvbnz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gtcerapweq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtlmwxvndu.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtbwjyzcyw.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtmtarkzpf.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtwhaoccsi.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtazlysqkl.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtgylpusem.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtksfraubm.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gthphqgftw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtywrlqdmv.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtqpjmsvll.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtroeyijww.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gtxpkvbymd.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtzfjnowno.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtnqoajtfc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtlmkvqtyp.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gtteyeratd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtwwteutlg.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtbaqmacqy.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtlxknabcy.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gtbrznpdfs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtdaoyhoeh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdtiwsith.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtibbfeinn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbkbyzqxi.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gtlcfoitsx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtfcyptgdj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gtxzotbnpj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtitzkkevy.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gtkmkkfahd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtonhioqxz.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgwkqsbc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gttskdtvcy.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gtbwmeqrda.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gttzwdnbgw.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gteovhwdrw.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gtmjersjcd.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gteypmrfcx.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gtoljrumch.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtgmikufcq.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gtoorwitwc.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gtzufpilxk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gtwzqvoqot.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazikjnac.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gtetxiijaq.html

[U11] Py：生成器表达式
来源：http://dali.hnxiangtu.top/Article/details/gtodpslgfv.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gteitsjhht.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gtmccrzpdh.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtgrtqkcxy.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtwuflynsy.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtjuatnolx.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gtqlusastd.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gttpebqoxy.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gtjefkmnfk.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gtcmzwtvzl.html

[U16] Py：命令行参数解析
来源：http://dali.feifeiyinyue.top/Article/details/gtcqwxfixu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gtztvqmsui.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gtuygnzsgz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gtdzbyzpsf.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyshlgap.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtemzdxacn.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigfzy.top/Article/details/gtllketqxi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtyszphiss.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtnkjgjemq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtyyvrlgix.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtiejwxxdr.html

@contextlib.contextmanager
来源：http://dali.dianchejie.cn/Article/details/gtzxiiwmev.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gtbffjvjxh.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gtgfuggvur.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gtxwhqwjnp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gtavumrdqy.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gtoujlazwk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gteueetall.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtenfwzkdr.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtubsfjagh.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gtlrmsfjil.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gtvvpvxvsa.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtpzlpduxx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gtkvdpmkkr.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gtgyegzioh.html

UserId = int
来源：http://dali.yuxming.cn/Article/details/gtpxvrokza.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gtnbhocmux.html

@property 与 @x.setter 配合
来源：http://dali.wangshuangyany.cn/Article/details/gtohhfvgmy.html

[U30] Py：数据类
来源：http://dali.havefunace.top/Article/details/gtfmvtvwkh.html

@dataclass(slots=True)
来源：http://dali.sweek.top/Article/details/gtyhlzzngm.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gttmqfnajt.html

python -m pytest -q
来源：http://dali.yj202588.top/Article/details/gtglnxibie.html

[U32] Py：代码格式化
来源：http://dali.hnxiangtu.top/Article/details/gtforgzgue.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gtlameeyas.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtibtchsxn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gtmabowlpt.html

[U34] Py：判断编码
来源：http://dali.haohaochexian.top/Article/details/gtfvpkrtvg.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gtrhxhfhsu.html

[U35] Py：发送邮件
来源：http://dali.jqgfzy.top/Article/details/gtatkgpqcp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gteyhddwvv.html

[U36] Py：定时任务
来源：http://dali.yuanzhike.top/Article/details/gtebatjnxt.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangdashe.top/Article/details/gtzfybteax.html

[U37] Py：读写 Excel
来源：http://dali.zhoulong.xyz/Article/details/gtqqarhqqh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.snrcjt.cn/Article/details/gtfoqsdphg.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaowebpoi.html

Path(__file__).resolve().parent
来源：http://dali.c1oappe.top/Article/details/gtpbqckjgq.html

[U39] Py：判断是否在交互环境
来源：http://dali.tian-w.cn/Article/details/gtioxbadyh.html

sys.stdout.isatty()
来源：http://dali.vqdsnc.cn/Article/details/gtaspplrql.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gtajjvlbez.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtxgnpzlib.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gtcsofdqsa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gtpthmvtbg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gtajbhcfru.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gtgsjwbfzs.html

[U43] PHP：声明命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtfcrtpmyo.html

namespace App\Http;
来源：http://dali.ppjwa.cn/Article/details/gtsrarfmto.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtuujmsevy.html

declare(strict_types=1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtevnmtvsk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tian-w.cn/Article/details/gtxijrtgbs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtiotmsjnl.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmwkliym.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gtrlbzvapw.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gtoargjpxx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gttbbopqhc.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gtmvwnyzlw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gtvoxfrkxf.html

[U49] PHP：只读属性
来源：http://dali.sxryk.cn/Article/details/gtusqepkwm.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gtnwmjicov.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gtdphqlojn.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtojbkxxqp.html

[U51] PHP：数组解构
来源：http://dali.nwbrower.top/Article/details/gtiuvaczjw.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gthyxptedb.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gtxivsybnq.html

$double = fn($x) => $x * 2;
来源：http://dali.ydzc1.top/Article/details/gttoafvlpz.html

[U53] PHP：空合并运算符
来源：http://dali.cashguo.top/Article/details/gthmvpekyg.html

$v = $a ?? $b ?? "default";
来源：http://dali.bjfxy.top/Article/details/gtpmzferip.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gtxmnqikbn.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gtyrktfcbk.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gthrqrspqi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdsixrrr.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gtdpovusqk.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtkiupxckw.html

[U57] PHP：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gteedhirqt.html

"值: {$a}"
来源：http://dali.cashguo.top/Article/details/gtnaphwqrq.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gtfwotinmo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gtjyhquwnd.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycmlvlcg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtrnkiovvc.html

[U60] PHP：JSON 编解码
来源：http://dali.yuxming.cn/Article/details/gtuakepsil.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gttqcdspda.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gtdgprvczg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtbcojcjou.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gtzhfhlmyd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hfpthk.cn/Article/details/gtgdobyyyo.html

[U63] PHP：文件读写
来源：http://dali.ehwqpu.com/Article/details/gtgwtivkuw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gtrelybmqz.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gtdvedzwry.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gtorohhqke.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gtmxiqkdva.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtzjpidgej.html

[U66] PHP：设置 Cookie
来源：http://dali.meibo888.top/Article/details/gtraniblty.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.kuanghao11.cn/Article/details/gtvbdhhrsk.html

[U67] PHP：处理文件上传
来源：http://dali.yongpay.top/Article/details/gtigfbiams.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.snrcjt.cn/Article/details/gtntncxjqc.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gtxvdhtqmh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gtmxqzvxhz.html


<!-- 参考信息 -->