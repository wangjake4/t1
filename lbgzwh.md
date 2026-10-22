代发 wailian999

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gt2tcbewxgc.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gt2gvunmnca.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gt2xcqqtiri.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gt2aggjiuiz.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gt2dsrtpisf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gt2dpxjavyv.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gt2dexxpuhy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gt2ksdaqbbj.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2nfemebkq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uhwtreoa.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2dzegkddu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gt2iyotogdu.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2sfmejqak.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2yijlufdu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gt2mxlidbcl.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gt2cusldfoa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2nxaixlix.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2gbttgjpr.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gt2fptvmurt.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gt2sdeokvma.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gt2pogchngd.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2qfafxgxk.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgelwitw.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gt2pqhoawzh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmaxymxh.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gt2synyvjsu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2ljzstiva.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2cckpglym.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gt2vhtrxmmy.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2malvhnkj.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gt2lsclaboy.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehapqiut.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gt2kqcfinxv.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gt2lfmgimqa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gt2vzxbhtjv.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gt2snytpzyh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2hisxcyjc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2uviqekfc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gt2pjjjbezt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vnjcnwuj.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2yecouycm.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2tnwvowqf.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gt2hgmjzktx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvlgoot.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gt2ytzwyxor.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2ntfzyttj.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lndxbptq.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gt2xytnztcv.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gt2nxjhjeqf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gt2yuuhbkna.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2netqstjl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2uaulfmnm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qjciusik.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2dagubtzr.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gt2tzfweomr.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gt2xaajdlqt.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gt2husccscc.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gt2hzjtowad.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gt2lsshtcea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gt2dqvyqila.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2oztjopne.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gt2pouydbjw.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gt2ewhvwevb.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ykzzkuie.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gt2wiyxgxji.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2fvtiikjl.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gt2hnyqmpuw.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2vdsdsiar.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqhsbns.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2vvapobra.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2gdnuejlh.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2tfaxujvf.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gt2pfuilmsq.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2wtykqggr.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2iljxziup.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2kyeoxtli.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gt2kyfxceiq.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gt2tyhyqiag.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gt2gaglunux.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gt2ultmgjuf.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2zenysnau.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gt2wxduabxm.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gt2hqxbicsn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gt2tsivortk.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ednvrjuo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2scuditqs.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2aqejdmpg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2feybgylq.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gt2rhmplikv.html

struct P { var x: Int }
来源：http://dali.tianlin.xyz/Article/details/gt2bspcgnnm.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gt2qchpnpcz.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gt2zamddlhv.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2miwvevst.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gt2ohqouqjn.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2ficqkohy.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2lqvxfnqu.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2xchrzjfh.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gt2qrnwcgbc.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2xddgcexr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gt2rfahpqrv.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2xlvkefxn.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2kcescbkh.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2ihzjpybv.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gt2mmwyszlz.html

[T33] Lua：表（数组）
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkdnxzpx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gt2orvvzazs.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gt2cowpfwng.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gt2aotfcsrz.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gt2nganrrxr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2pjqemxta.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjkevlkr.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gt2szbfmiyz.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2uwekjfor.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gt2aavoebmd.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfedhwzz.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gt2cjcforgy.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gt2jspcfgxt.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsyrpngy.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gt2pgbizpin.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gt2nhuajind.html

[T41] Perl：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2ymvupqaz.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gt2ocaeetkq.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gt2nqcucboj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gt2ahcvdyzv.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2fhisxnyk.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gt2btbonexm.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gt2qroftvnz.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2etdawndw.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otfmdpfu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnmhovcl.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gt2gwqfdeoo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gt2fqriebrw.html

[T47] Perl：正则捕获
来源：http://dali.gotoacloud.top/Article/details/gt2kfzhcohk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xinyue.icu/Article/details/gt2tygqiexj.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gt2zqhkugpf.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gt2lypxfovb.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gt2bbdufyvm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2vxubfrjr.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2znvxagak.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gt2lbejedyp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gt2tcqadguq.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2hobgukpw.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2wrihixao.html

[T52] Scala：变量
来源：http://dali.xylfe.cn/Article/details/gt2psfgeeeo.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gt2cwupvqxc.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2ncbstvqq.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2uorygqyy.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2gklnjurr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xiydzsnh.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2csvapjti.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gt2gbpsbgdg.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gt2wizomdwp.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsjkypii.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2vxwhsqpl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gt2btczizzu.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gt2gpuvjhzz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gt2vonnvaoz.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gt2ecxpjtfu.html

for (i <- 1 to 10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2eqaagben.html

[T60] Scala：折叠
来源：http://dali.meibo888.top/Article/details/gt2saiwkirp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gt2qdxbkihb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2fvhyscdh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2vdxajmmy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gfhikoox.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shivkzlm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gt2lnlthvnh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gt2dqsbciav.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gt2uqqbifnj.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gt2uecdzvyz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amrojsgj.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gt2sjbrcwqb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gt2ohdhdgha.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gt2snagdomd.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2dpkvnpnf.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gt2nuhvaanz.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gt2hejlhtlz.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gt2aeffdfgt.html

{v: k for k, v in d.items()}
来源：http://dali.316326.xyz/Article/details/gt2hpsmoqeg.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gt2haegzsvs.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gt2tgirqucf.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gt2saqqritb.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eefvcmbo.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gt2oynqinhe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtpzywsw.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gt2ghrkwcic.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcswzfby.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqbwrtzf.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gt2hfmeqhjr.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gt2epnoxfsn.html

deque(maxlen=10)
来源：http://dali.yangfankeji.com/Article/details/gt2fkdihame.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gt2pasmluoo.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fehusspm.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gt2vfjmtfbc.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gt2pumyovvw.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gt2lljfrfmr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gt2frlvofes.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gt2wopqctox.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xylfe.cn/Article/details/gt2bqvmvsqm.html

[U18] Py：预编译正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndcdyelz.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gt2edmwbjsk.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gt2glxumrln.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhzwzdn.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gt2fzgtfuhk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gt2vglgwvco.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gt2kmuwncle.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gt2ecwphkzn.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzrlivjx.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gt2lcnjtetn.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gt2rrnhaytf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gt2jyjhtfcf.html

[U24] Py：路径操作
来源：http://dali.sweek.top/Article/details/gt2qykrngts.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xprnqmcp.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gt2fsrhhazl.html

csv.DictReader(f)
来源：http://dali.yueranfly.top/Article/details/gt2qsvefcmz.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gt2xsirjlgh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gt2sxvashoc.html

[U27] Py：异步 HTTP
来源：http://dali.zdqjudy.top/Article/details/gt2ghprkahs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gt2lghkxejg.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gt2awimxlsr.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gt2rixkjtzf.html

[U29] Py：属性校验
来源：http://dali.yuxming.cn/Article/details/gt2knxbmubq.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gt2qwtelxrw.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gt2rbjkwtet.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gt2tvjokwkh.html

[U31] Py：单测
来源：http://dali.0kj1m.cn/Article/details/gt2cssigthh.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gt2iadswbsh.html

[U32] Py：代码格式化
来源：http://dali.yj20258888.top/Article/details/gt2yygleqaw.html

ruff format . && ruff check --fix .
来源：http://dali.yanxiufei.cn/Article/details/gt2jtzdcqni.html

[U33] Py：打包发布
来源：http://dali.hammf.cn/Article/details/gt2xydjhxlw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ehwqpu.com/Article/details/gt2nkfttsnd.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gt2uyvmfdkw.html

chardet.detect(raw)
来源：http://dali.yj202588.top/Article/details/gt2rzotgikf.html

[U35] Py：发送邮件
来源：http://dali.redwolf501.top/Article/details/gt2pcpgdgug.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shuidangran.top/Article/details/gt2evggatvr.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gt2aujdsowo.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gt2zpqfdcqa.html

[U37] Py：读写 Excel
来源：http://dali.wangdashe.top/Article/details/gt2jkwtaooq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gt2pnmzfgqh.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gt2gnkwlibc.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gt2qwqpyfdb.html

[U39] Py：判断是否在交互环境
来源：http://dali.cheryme.top/Article/details/gt2wzkhwfzw.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gt2mkhjxyqk.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gt2lfaopcby.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2uuzyrnan.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gt2xsdbdvpa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhoulong.xyz/Article/details/gt2vpycnvjg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gt2dmglcyri.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gaohongyu789.top/Article/details/gt2xecralop.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gt2nerrtdfc.html

namespace App\Http;
来源：http://dali.shzxlz.cn/Article/details/gt2bkoormzu.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gt2ylmhpotm.html

declare(strict_types=1);
来源：http://dali.quarkkingdee.top/Article/details/gt2jgzadqdg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gt2qejiowdq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2uqbosdey.html

[U46] PHP：可空类型
来源：http://dali.birdmap.top/Article/details/gt2dwhjtarw.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gt2hkkyodtp.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gt2jmhquzfo.html

int|string $id
来源：http://dali.sxryk.cn/Article/details/gt2pckenmsi.html

[U48] PHP：纯枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqjrpfip.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gt2xitwopjz.html

[U49] PHP：只读属性
来源：http://dali.zhoulong.xyz/Article/details/gt2rtrqjdeh.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gt2btufkbqd.html

[U50] PHP：构造器属性提升
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2luwgfrsy.html

public function __construct(private int $id) {}
来源：http://dali.sysykeji.top/Article/details/gt2wakkwnlw.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gt2kguyufhr.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejndpgeh.html

[U52] PHP：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gt2ytcybqdp.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gt2ytofnocg.html

[U53] PHP：空合并运算符
来源：http://dali.birdmap.top/Article/details/gt2apzzwwyx.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gt2uoaleeic.html

[U54] PHP：空安全调用
来源：http://dali.chenlongwang.top/Article/details/gt2prfkwlpo.html

$obj?->method()
来源：http://dali.yanxiufei.cn/Article/details/gt2ebmubqtr.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gt2tkkpvyfy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjlhkfgp.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gt2slhgkmyy.html

f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2uyigeioq.html

[U57] PHP：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snwbxjue.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gt2lviefbrq.html

[U58] PHP：数组三件套
来源：http://dali.cdnleiting.top/Article/details/gt2qyndvbhg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yongpay.top/Article/details/gt2bwjsrrgw.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gt2tyrnyaul.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbihxgal.html

[U60] PHP：JSON 编解码
来源：http://dali.dashuyun.cn/Article/details/gt2kcbvlmdh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2virjonnm.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gt2knyqxpfq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gt2zzjtzxpy.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gt2exdvpnsr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tian-w.cn/Article/details/gt2njvtmfsz.html

[U63] PHP：文件读写
来源：http://dali.guowangkeji.top/Article/details/gt2ibvjvzyd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.bjfxy.top/Article/details/gt2utlqtjap.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2vnvrzzmc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inygllqe.html

[U65] PHP：会话
来源：http://dali.yanxiufei.cn/Article/details/gt2bzcrvrxi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2hdextvgk.html

[U66] PHP：设置 Cookie
来源：http://dali.fengsongda.top/Article/details/gt2fnhkwgit.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.snrcjt.cn/Article/details/gt2rshlkrqe.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gt2jrhtwarp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yanxiufei.cn/Article/details/gt2msvfseni.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gt2tocujtzl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnqyeafl.html


<!-- 参考信息 -->