代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2gdllmfpz.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gt2kucaczsn.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gt2asqubdwi.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gt2yotrsdgt.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jymzwzat.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gt2zelmgdmw.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gt2xyevafdu.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2rygrheuy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gt2kvniuiik.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gt2tqehvozx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2ftohftvd.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2memmxidd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gt2sumriyak.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gt2rrbaivxz.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2cmssuuyt.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gt2qvsscahj.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrrqxlzi.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gt2xkqmeinn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gt2najhhmbi.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2fwmufdnj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2septgdmk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jyrgzbbs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2pxobdutm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ddzicwbp.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2cgrikegp.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2sfhexuaq.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gt2jbigpnkv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gt2wbdxunjn.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2pwvhtgjr.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2xnduynte.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gt2odihnnxb.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhowytum.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2aeyyztex.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gt2avvbxaah.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gt2wcujsiay.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2mxgbebhv.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwrhaetf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gt2pnmqyumg.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gt2toetxhgd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2injlkxdq.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2vfwfxsiy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixloziof.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2maoqssnn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gt2lcqhzups.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gt2wlxofroe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gt2gzcoywuk.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gt2lvondlfy.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2lcpbfazk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gt2wpxnuizg.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2pkfplduc.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mminzthe.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2xawjuggr.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gt2idgmgesq.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gt2glmrqiaj.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gt2vopsommu.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2cenjgshr.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gt2yufbfzfs.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2dtpenegs.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2mnkxuzid.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gt2sittskgv.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2ctkspsob.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gt2ngbdzlcn.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gt2kmiqhakk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gt2yymjciib.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydwfbpjz.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gt2wxukbgtl.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gt2bzglzmjc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnakeqzh.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gt2txlhwwvd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2pwzklirp.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gt2pscpqjgl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2ujbpniff.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gt2ioewiwkf.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gt2arabtoie.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxkyzgrx.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gt2gzbicnwu.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gt2fdpamraz.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojknfdpx.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwojqyzu.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gt2teqzgslc.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2etfpbafr.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2viyfubqj.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gt2jbmsbdsd.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gt2lnsdknrr.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2lpgbbaos.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2lyjqtngv.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2fobcoaqc.html

local a = 1
来源：http://dali.ybcxt.top/Article/details/gt2htymptno.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gt2gmjvqdjo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouwcftkf.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gt2ckywoapb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.kuanghao11.cn/Article/details/gt2ulnitafj.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gt2wzgbhudw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2vvzcdabg.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gt2xfokmdbs.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gt2bxaifuwy.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gt2htwxhcal.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gt2ykweioow.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gt2wsvksraw.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gt2hxflbzwq.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gt2llxpeuni.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gt2itkblwgw.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gt2vlpplysi.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gt2mrgomtpf.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2srkxpveb.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gt2csrzayiz.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gt2phxjrxph.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gt2tfnfkkfr.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2vflvqgum.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmwiqttr.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gt2cnlzzmod.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kiuymlgf.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2wanvmuum.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gt2fxnqpabi.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gt2wnexqgwo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gt2bqeafzvv.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gt2orkciidt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2osiwtlgb.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gt2hzomlgtj.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gt2bfzvkfoh.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2djdqxjlm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2klcilhwp.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2ltsfcynx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gt2ewvlfkur.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfmuverw.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ytvhpvtq.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkncjmif.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gt2arbaapls.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2otgyqvbk.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2aweahoyo.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gt2piyysbyh.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2cygpryhf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2ucgdrduw.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gt2hygsqwdm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gt2ozgionrg.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gt2ljxenkmg.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2icxmjlzt.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gt2ndboywzm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gt2licvyswy.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2boabtvii.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangdashe.top/Article/details/gt2xpjdlqoi.html

[T59] Scala：循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhsgolgr.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gt2xhafqbzq.html

[T60] Scala：折叠
来源：http://dali.dianchejie.cn/Article/details/gt2rirkxyue.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gt2pptnavlv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yqzkagxu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2hcemhibk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2xthrxqri.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gt2bjphsfsd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gt2zljuwrug.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gt2prerqhne.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2vjulzhla.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gt2pxycbtyd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gt2ymvjwoek.html

[U04] Py：变量调试打印
来源：http://dali.9152youxi.cn/Article/details/gt2miwcrmwd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2jluewtwl.html

[U05] Py：列表去重且保序
来源：http://dali.hnxiangtu.top/Article/details/gt2nhjgjibq.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2dvgzbjbf.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gt2dflscydn.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gt2ujdmlvol.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gt2tbzbeokk.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gt2irngqzjq.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gt2woiqmhfk.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gt2zzflhvqv.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gt2xazyrcwk.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gt2vwufrueq.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gt2ngfhnooq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gt2btrgdctz.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gt2wchkqsxe.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gt2tvxzdvno.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2koftjbbg.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gt2wuyevfjr.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gt2iugpoqwe.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gt2gzvdejny.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gt2viombiqk.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gt2ghbyhbye.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gt2mxxwgmyc.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gt2gepsdhfo.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gt2ndocdvkq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gogol.net.cn/Article/details/gt2qcafmzqf.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhjhjzew.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gt2jlpubfxt.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gt2kybgavkw.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czifrmeg.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gt2klkidmqr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gt2aavlbtla.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2whwphwmf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gt2lfdnocko.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gt2iffsyhjt.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gt2bobvtxsf.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gt2tqtnbkds.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gt2nhaqtzui.html

[U23] Py：分块读取大文件
来源：http://dali.redwolf501.top/Article/details/gt2ckxnzjwm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gt2bljlkajy.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gt2umqkevuj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2elgifdwu.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2eghrlact.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gt2vuwakpys.html

[U26] Py：并发下载
来源：http://dali.hysaishi.cn/Article/details/gt2neqddcsu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gt2nmqsovhu.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evyznarv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tanke756.top/Article/details/gt2hwspjpsr.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gt2xdqdsprc.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gt2stiiainp.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gt2lgsmlisf.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgjypcue.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2aktzwrmt.html

@dataclass(slots=True)
来源：http://dali.havefunace.top/Article/details/gt2alwpsacj.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2wxbzsqvo.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gt2ziavwoem.html

[U32] Py：代码格式化
来源：http://dali.fengsongda.top/Article/details/gt2merpkqln.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gt2cthcmxcc.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqbgiffm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gt2fzyuuhri.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eppxaoxj.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gt2sevmtzyh.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gt2ujlebbey.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gt2wxdnfkud.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gt2rptgalow.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gt2yrachvjc.html

[U37] Py：读写 Excel
来源：http://dali.yueranfly.top/Article/details/gt2fizmairs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gt2xtonovxs.html

[U38] Py：获取脚本所在目录
来源：http://dali.xziqi.cn/Article/details/gt2irzjqyts.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gt2ftndyyql.html

[U39] Py：判断是否在交互环境
来源：http://dali.zdqjudy.top/Article/details/gt2eqoyqslm.html

sys.stdout.isatty()
来源：http://dali.shuidangran.top/Article/details/gt2bujorocg.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gt2bdioscuf.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2bnwnxcnf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gt2vcugclxf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gt2ndtpigzn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daria6918.cn/Article/details/gt2hnkejkgx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aibaodan.cn/Article/details/gt2njucfjmb.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2ecljoday.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuwmlzht.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gt2hqgnbtrc.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qeyciphz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gt2yjmxisyf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2ezkanitw.html

[U46] PHP：可空类型
来源：http://dali.wangdashe.top/Article/details/gt2maefcoff.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gt2wgjlnlyl.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gt2lduuoqek.html

int|string $id
来源：http://dali.316326.xyz/Article/details/gt2ccqaklhb.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2otcmdeva.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2uozqllie.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gt2bkeezgss.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gt2knfvalbf.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhymruym.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gt2hfiecvuw.html

[U51] PHP：数组解构
来源：http://dali.mhx1999.top/Article/details/gt2gcjqgczj.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gt2slqczkkm.html

[U52] PHP：箭头函数
来源：http://dali.hammf.cn/Article/details/gt2goartpjz.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gt2qocsufxu.html

[U53] PHP：空合并运算符
来源：http://dali.cashguo.top/Article/details/gt2ilqvygau.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenlongwang.top/Article/details/gt2cvosaqum.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gt2vckqzcqu.html

$obj?->method()
来源：http://dali.zdqjudy.top/Article/details/gt2mrxgprrf.html

[U55] PHP：match 表达式
来源：http://dali.sysykeji.top/Article/details/gt2vtkauvoy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gt2dwkehije.html

[U56] PHP：命名参数
来源：http://dali.yj20258.top/Article/details/gt2pughidvs.html

f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2bvawixjo.html

[U57] PHP：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2jkfwsqzl.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gt2bdhdcdrg.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlqoasta.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2uvujdikf.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chzctmbh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2clgojahk.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gt2prbujtpe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2thmenjfz.html

[U61] PHP：正则
来源：http://dali.tian-w.cn/Article/details/gt2pdoggduc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2avehmnra.html

[U62] PHP：日期对象
来源：http://dali.gogol.net.cn/Article/details/gt2gxbvhmna.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gt2cwqnjmph.html

[U63] PHP：文件读写
来源：http://dali.jqgufenzy.top/Article/details/gt2tzjqdkxl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258888.top/Article/details/gt2lvecezts.html

[U64] PHP：目录遍历
来源：http://dali.redwolf501.top/Article/details/gt2gwuqzgla.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gt2kqhfueck.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gt2xwvpetzn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2piuttmsk.html

[U66] PHP：设置 Cookie
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jknhmkiz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xinyue.icu/Article/details/gt2higkkpea.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqfstqas.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ppjwa.cn/Article/details/gt2nvrqtmpn.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gt2hjsagtuk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yvedp.cn/Article/details/gt2ilvkjwwc.html

[U69] PHP：PDO 预处理
来源：http://dali.yongpay.top/Article/details/gt2eiuistue.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gt2mropbhkj.html

[U70] PHP：PDO 事务
来源：http://dali.dashuyun.cn/Article/details/gt2tmjbeemt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuanzhike.top/Article/details/gt2xzvdwvep.html

[U71] PHP：抛出异常
来源：http://dali.yonumen.top/Article/details/gt2ztgqycnk.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gt2egdlqcew.html

[U72] PHP：写错误日志
来源：http://dali.yangfankeji.com/Article/details/gt2bmgfvrkb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ppjwa.cn/Article/details/gt2yfinbxum.html

[U73] PHP：读取 ini 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2qbgdughu.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gt2pimbxzqs.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2favkchmt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shuidangran.top/Article/details/gt2atyrxclq.html

[U75] PHP：依赖注入
来源：http://dali.hongshengwenyu.top/Article/details/gt2btanhbbw.html

composer require psr/container
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujkrkmyb.html

[U76] PHP：简单路由
来源：http://dali.jianghu66.top/Article/details/gt2guegjjyh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.kuanghao11.cn/Article/details/gt2sqjburfe.html


<!-- 参考信息 -->