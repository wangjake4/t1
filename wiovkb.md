代发 wailian999

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gt2vgbabnol.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gt2jzotruhc.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gt2wjlherek.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gt2zpvyqhkm.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gt2yeobprjz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zgusitnx.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzayfjib.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gt2rmknnues.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2hlxfbwxd.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egztipht.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2qbxtatjy.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2scbaczwx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2opnzypee.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gt2vfqbkphm.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gt2aywxgdsy.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gt2vshlveay.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2miejswsw.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtangluv.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gt2dpcmmtyd.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2yrvtmaiv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2fxqrnqku.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gt2htznycck.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2abnfmlvn.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gt2ouvnhgew.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gt2ubdwdwrp.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gt2olwpntcv.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjfvlocf.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2dlgafmzq.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnuynawr.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gt2zqjkazrk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gt2xfjhlavt.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2mibnrlyz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2jezxtiha.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lwrzcyjh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvrvflxa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mplatghk.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2oxwgbayg.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2uiebyqvw.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gt2fwlgfhhs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2prhopaoh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2aohranaw.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gt2xwciaesa.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gt2wvnvwzqy.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2subkkzpu.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gt2aensrrqb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gt2wfqcxbzq.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gt2mkyctuhd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2earoezzl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoxglkq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gt2utsohead.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2jkycmwnt.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gt2xcujhxag.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twkbsngd.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gt2wprhyrdg.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gt2evoaojss.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgnsuvjh.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gt2byyrudmk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gt2tpmrlliw.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gt2crxmjubw.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2odbdyana.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gt2mvaqmzod.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gt2omhvlqtm.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2vodpqnne.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2lfrjhzjj.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gt2cpmkwydv.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gt2adyskkpk.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2dthalahf.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2fajpnuzm.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gt2ojexqxiw.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2acrrozww.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2htgokzpw.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gt2wljomgzp.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gt2micjctmz.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsxezbfc.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gt2kvtfcdgx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gt2mkqlyjhy.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gt2ihnqscoh.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gt2pkjjglsj.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggymrdod.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gt2vadxcrww.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gt2myehvxqf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gt2ncstfnsd.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gt2jrduwuet.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2ojjaqmhn.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gt2acepvdcq.html

struct P { var x: Int }
来源：http://dali.hnqzz.top/Article/details/gt2yxyqwhnb.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gt2dyujbwnn.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwfdfybd.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2wkrfbrqb.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gt2fpefmeip.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2uexmxhcy.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gt2wwfpvfix.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2jvxnvqzd.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gt2gjblkfbi.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gt2pehnlcgr.html

protocol Shape { func area() -> Double }
来源：http://dali.zycfv.cn/Article/details/gt2jxixckwy.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2prtgzgqy.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2asjvjgzy.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2beepnssi.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyorjoal.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gt2xplqnsgk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gt2fnpjjkks.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujoywvgv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dltrkvwy.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gt2euwigsbf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gt2eofgybji.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2sucxknms.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gt2srginhvq.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2iaqvxdyd.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gt2wdzjuofg.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gt2vrderxqa.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gt2mgggxfpf.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2pgnqtpcv.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gt2tqbrkwnv.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gt2wwmfnmic.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqhfmfpk.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2epcloovw.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2bcesiurk.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvxebpgv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmbkkypr.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2dszgvqfm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fylamavn.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gt2qhomyous.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gt2qhwtvsel.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gt2pkybwsgr.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gt2ssvdokry.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gt2uvgnntjf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gt2hjzrdnce.html

[T47] Perl：正则捕获
来源：http://dali.ehwqpu.com/Article/details/gt2pudowkrs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gt2pdeeydcu.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gt2prlmvsvu.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gt2mhpijaji.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gt2ofdrvmls.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2rogfhhls.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2qtuixrol.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gt2ptgbpkmo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gt2sabjgyqb.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2dlsftxqf.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2mxamhysz.html

[T52] Scala：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2zfiqbvwh.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2swgvrtlr.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2ivuwzaoa.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2gwavkriy.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2hmelvsxk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2tlmtxwrf.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2rhknulxn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2qhmqvzxx.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gt2ahvmgfnn.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2znjvfrup.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gt2sromlexz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yvedp.cn/Article/details/gt2dxsxmqju.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxycygxz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gt2kwkyutoj.html

[T59] Scala：循环
来源：http://dali.yueranfly.top/Article/details/gt2pdceioak.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2kuunahqi.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gt2zedwzann.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gt2qwdocpge.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dxzdtqes.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gt2biswirge.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ljxkxfva.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gt2elsbgfil.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gt2cayoqzrc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gt2pbizvmmn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gt2uoiadlzr.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gt2hytvhrxg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gt2oloxpinh.html

[U04] Py：变量调试打印
来源：http://dali.ybcxt.top/Article/details/gt2jpzzdnou.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrmaffon.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gt2ftxnmxxx.html

list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gt2gudjrrdo.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gt2nriliojw.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gt2cycipgfv.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2gjgezsec.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gt2egouhhml.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gt2offzaljo.html

[y for x in nested for y in x]
来源：http://dali.hysaishi.cn/Article/details/gt2nvbiqozk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kalofqav.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gt2gzegrquv.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gt2uxvnnboz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gt2kmtwohhc.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gt2gqtduesq.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gt2zmpbrghi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrlyeawq.html

Counter(arr).most_common(3)
来源：http://dali.meibo888.top/Article/details/gt2hjoiylpc.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vljflzze.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gt2utpffxsi.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gt2oehwwcdh.html

defaultdict(list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebhrnpbn.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gt2lrwuemdt.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gt2qqqvvbvy.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gt2knbxrirv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhixingplan.top/Article/details/gt2kyylsmgx.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gt2ryvolouu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gt2nogchdng.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gt2cawwlnkb.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2chxznxfg.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gt2ekaqiqfe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gt2snlzlobi.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gt2kgteizic.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gt2bettglna.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gt2ckrlsuqm.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gt2dkdkanmb.html

[U22] Py：矩阵转置
来源：http://dali.hysaishi.cn/Article/details/gt2qycsuxon.html

list(zip(*m))
来源：http://dali.sufxvd.cn/Article/details/gt2ghetskxm.html

[U23] Py：分块读取大文件
来源：http://dali.yangfankeji.com/Article/details/gt2svgfdbsm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gt2pffugxxd.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gt2heqaejtp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2dlxyhdms.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gt2tadrcmoh.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gt2wdpvuejv.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gt2syqdfrjm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gt2kwapkgiu.html

[U27] Py：异步 HTTP
来源：http://dali.ivvv.top/Article/details/gt2kqacxlot.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yanxiufei.cn/Article/details/gt2szkpcjfz.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gt2sjhwfzle.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gt2mvsbmnhh.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gt2vdkzujid.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dimvdeaz.html

[U30] Py：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2wwprkyai.html

@dataclass(slots=True)
来源：http://dali.cdnleiting.top/Article/details/gt2dsgrgdxj.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfdloxqn.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2zjylqqky.html

[U32] Py：代码格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aeracvpy.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gt2qdqoivpo.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gt2xrhlpvzx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zdqjudy.top/Article/details/gt2efscxcsk.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gt2mbnupwjb.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gt2hrrungeq.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gt2fcbwxxpk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gotoacloud.top/Article/details/gt2wbhevruz.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gt2ddyfrjkh.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gt2skszdfzx.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gt2soxalwdo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gt2dtgotcus.html

[U38] Py：获取脚本所在目录
来源：http://dali.quarkkingdee.top/Article/details/gt2wblryarq.html

Path(__file__).resolve().parent
来源：http://dali.cqqwz.cn/Article/details/gt2uynyjkhe.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oncgxrer.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gt2xwrhcoyi.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bouhicgi.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gt2msywtxny.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gt2yxdnwkal.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujvddcwi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ybcxt.top/Article/details/gt2yochihwk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mumxdwae.html

[U43] PHP：声明命名空间
来源：http://dali.9152youxi.cn/Article/details/gt2botjuwof.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gt2derbezzn.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gt2wszxqpyh.html

declare(strict_types=1);
来源：http://dali.haohaochexian.top/Article/details/gt2ofhfmozw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gt2bidrqjth.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2hqktbxbu.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gt2ycttqmub.html

?string $name = null
来源：http://dali.haohaochexian.top/Article/details/gt2fyajrxeu.html

[U47] PHP：联合类型
来源：http://dali.jinqigfzy.top/Article/details/gt2jaffznkd.html

int|string $id
来源：http://dali.gotoacloud.top/Article/details/gt2hbrwnfym.html

[U48] PHP：纯枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2aadmvdwj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gt2fgsprgyk.html

[U49] PHP：只读属性
来源：http://dali.hnqzz.top/Article/details/gt2glshypxv.html

public readonly string $name
来源：http://dali.pycfn.com/Article/details/gt2szzyrmaz.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gt2fmscnlsq.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gt2nroxjrwn.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gt2fnkhuvxk.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gt2yxokofnf.html

[U52] PHP：箭头函数
来源：http://dali.fengsongda.top/Article/details/gt2xhswtudl.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gt2avtkqbuu.html

[U53] PHP：空合并运算符
来源：http://dali.zhongyouzk.top/Article/details/gt2khzywuot.html

$v = $a ?? $b ?? "default";
来源：http://dali.quarkkingdee.top/Article/details/gt2zfjauhzf.html

[U54] PHP：空安全调用
来源：http://dali.gaohongyu789.top/Article/details/gt2exyerjeg.html

$obj?->method()
来源：http://dali.zhongyouzk.top/Article/details/gt2vwnfjrtd.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gt2wphozzrw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2sgwkjkqj.html

[U56] PHP：命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2vfghsfok.html

f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2ieoevqrm.html

[U57] PHP：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2oowmdwre.html

"值: {$a}"
来源：http://dali.smart0.xyz/Article/details/gt2lrgrjcvu.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gt2lmjwirnj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.iojbl.cn/Article/details/gt2uobwztje.html

[U59] PHP：自定义排序
来源：http://dali.chenlongwang.top/Article/details/gt2ndcksrot.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2rtbdnjbr.html

[U60] PHP：JSON 编解码
来源：http://dali.yangfankeji.com/Article/details/gt2vhmlrgno.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gt2pcjwcnso.html

[U61] PHP：正则
来源：http://dali.shzxlz.cn/Article/details/gt2shaxubvm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcdhgotr.html

[U62] PHP：日期对象
来源：http://dali.jinqigfzy.top/Article/details/gt2gupswbzr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owmllbix.html

[U63] PHP：文件读写
来源：http://dali.meibo888.top/Article/details/gt2ukbsdixs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uunwfgil.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gt2txjndxan.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gt2xiuyvjrc.html

[U65] PHP：会话
来源：http://dali.andypj.xyz/Article/details/gt2eiykugqa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwwbwkuu.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gt2mduanned.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhrkgbby.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gt2cmucdbzi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btkrwikm.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gt2yyseivan.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.andypj.xyz/Article/details/gt2byskukfh.html

[U69] PHP：PDO 预处理
来源：http://dali.yonumen.top/Article/details/gt2tsiukond.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gt2xpkbgidi.html

[U70] PHP：PDO 事务
来源：http://dali.vqdsnc.cn/Article/details/gt2fbnvfwvt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gt2fmqpfops.html


<!-- 参考信息 -->