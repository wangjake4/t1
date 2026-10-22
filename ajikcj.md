代发 wailian999

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gt2ilhwrsbl.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gt2fpmobedu.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2cvuoamrm.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gt2himgkwys.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2wolwmueu.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmvkizqu.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gt2ermyubxh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2xvkweheb.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2yvtcecen.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2narsezso.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gt2vczoysnw.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gt2zgtzltoh.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gt2fokrcgdj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gt2uznucgat.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gt2vuhwxllo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrplifje.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcowbvwr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gt2ozyvxbxr.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gt2ktonpbav.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gt2wwvsedqi.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gt2rzfaozja.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gt2asklpfip.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gt2gmphkdxl.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gt2jpddaxhl.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gt2gwjdvphy.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gt2gjcjtvpv.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gt2vhidnbhj.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gt2katykvla.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2wvthdyyx.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gt2wzfyjdjh.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gt2jwdhrwfa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gt2laadxewt.html

[T43] Perl：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2bmmmeqeb.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gt2kzixrdua.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gt2sljnlnad.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gt2othrkdgv.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gt2dzioyboa.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gt2hzaacoid.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gt2enacqhdl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igikitsf.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gt2fbdjbkhn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2memjafoc.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gt2iluymbyo.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eosqowja.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2hracvcyz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2ssfyyhhr.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2jbizpotw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gt2victblln.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dmnknura.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkrbllvu.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2wmpzjgrl.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gt2irusmiva.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxajkmnn.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azsvetid.html

s"值: $b"
来源：http://dali.fzhhl.top/Article/details/gt2ciylhtal.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2gtdfthmc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfwlpgxi.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbnlecbq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcmosmj.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gt2kvdwuabd.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2avlfemnh.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2dwovigrv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gt2whjjtfab.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gt2wymzkzrm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2dnourdvy.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gt2hkjjqbpg.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2kzsepoxs.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gt2fuuvvaax.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hguyonkt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmgnupyb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gt2rajinpdt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ohxhrmee.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gt2fviiqusa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yueranfly.top/Article/details/gt2vtzzcbfe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gt2ytrqzuon.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gt2sgyqvpyg.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gt2holxxyuu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gt2ndmgyfxt.html

[U04] Py：变量调试打印
来源：http://dali.vqdsnc.cn/Article/details/gt2ppziajkr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gt2sevnqqtx.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gt2xgebywrd.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmsgclmg.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gt2cxgcsorz.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adkwkcxp.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gt2qckssfsd.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gt2iowtrnhj.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2azxiuwzx.html

[y for x in nested for y in x]
来源：http://dali.cucudq.cn/Article/details/gt2uuuisrzm.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gt2pgsnlqyr.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gt2ijvmedbv.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gt2sgsydelx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gt2hsvaxbre.html

[U11] Py：生成器表达式
来源：http://dali.daria6918.cn/Article/details/gt2tpzeulyx.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gt2icncdtpw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gt2aywedhjh.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhevvuxb.html

[U13] Py：固定长度队列
来源：http://dali.cqqwz.cn/Article/details/gt2hzjtlxua.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gt2yospbskm.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gt2slkkprxb.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gt2skdagpau.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gt2ruvxnifz.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gt2yfctkixt.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhqjjjbt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gt2vupbqbvv.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gt2jabpcypb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cucudq.cn/Article/details/gt2mommzpcb.html

[U18] Py：预编译正则
来源：http://dali.svipenyu.cn/Article/details/gt2kgebnhfe.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2siqybrgw.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gt2pagcihvl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gt2lvdkkurl.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izsypwka.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hongshengwenyu.top/Article/details/gt2flidrhdl.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gt2pqpapopi.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gt2fndexfrn.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gt2iaztifvy.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gt2necmbnjd.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gt2uglbboxn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gt2wzsohqon.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gt2xoohmsox.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2bpfnaqhn.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gt2qcnqsedj.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gt2tuargdvs.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gt2hdjccbau.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nipsgbzs.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigufen.top/Article/details/gt2fdthpqml.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gt2bqfrzlyl.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gt2kndqrquj.html

UserId = int
来源：http://dali.zhoulong.xyz/Article/details/gt2kifsnunj.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gt2hdikuiyv.html

@property 与 @x.setter 配合
来源：http://dali.c1oappe.top/Article/details/gt2cnzecmxv.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2qerroydi.html

@dataclass(slots=True)
来源：http://dali.mhx1999.top/Article/details/gt2fgdosefi.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gt2fnpzjtvg.html

python -m pytest -q
来源：http://dali.mhx1999.top/Article/details/gt2juvtocea.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2ugofarxq.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gt2ppzwlxmg.html

[U33] Py：打包发布
来源：http://dali.nanxinkj.top/Article/details/gt2noihzojf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gt2bctfmmos.html

[U34] Py：判断编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtdhraco.html

chardet.detect(raw)
来源：http://dali.fengsongda.top/Article/details/gt2zqqkaial.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gt2wbiorlne.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gt2ijnqysmo.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2ystopeqk.html

schedule.every(10).minutes.do(job)
来源：http://dali.smart0.xyz/Article/details/gt2svdscvyt.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gt2bvfgiblf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gt2veqoyyln.html

[U38] Py：获取脚本所在目录
来源：http://dali.ybcxt.top/Article/details/gt2vibwrfeq.html

Path(__file__).resolve().parent
来源：http://dali.chenzaomai.com/Article/details/gt2mibvstrr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrdnqscn.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gt2falrjfqo.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gt2dpsfqkfe.html

print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gt2ovgirmjv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hammf.cn/Article/details/gt2ukttotqk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqjtyuej.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gt2dpfcndwt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.9152youxi.cn/Article/details/gt2dvhgiqbn.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gt2tapbxexi.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gt2jkkhaeer.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gt2forfcuyj.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gt2lpmpualb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gt2qmmaatal.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hmvkhssa.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fireddaw.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gt2zitklltp.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gt2scbdgece.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gt2xazuseyb.html

[U48] PHP：纯枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2lfmgtfbt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gt2jeuvdlin.html

[U49] PHP：只读属性
来源：http://dali.xuanzx.com/Article/details/gt2acskaeuq.html

public readonly string $name
来源：http://dali.yvedp.cn/Article/details/gt2iryogrrx.html

[U50] PHP：构造器属性提升
来源：http://dali.cucudq.cn/Article/details/gt2tisuusln.html

public function __construct(private int $id) {}
来源：http://dali.chenlongwang.top/Article/details/gt2cbfrzogp.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gt2ufqgoyku.html

[$a, $b] = $arr;
来源：http://dali.gzhubu.top/Article/details/gt2mjruythu.html

[U52] PHP：箭头函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdnixovs.html

$double = fn($x) => $x * 2;
来源：http://dali.hywenlv.cn/Article/details/gt2mrdxssuq.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgwksaik.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gt2eastlbmi.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gt2libaflpb.html

$obj?->method()
来源：http://dali.daxiang520.top/Article/details/gt2vlnfknrs.html

[U55] PHP：match 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2nykxwbvc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dashuyun.cn/Article/details/gt2bcygbprf.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gt2zolaxkqk.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2dzrxukbb.html

[U57] PHP：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrcvxuue.html

"值: {$a}"
来源：http://dali.gzhubu.top/Article/details/gt2axlfnwin.html

[U58] PHP：数组三件套
来源：http://dali.pycfn.com/Article/details/gt2qffqlsak.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2pgguifnc.html

[U59] PHP：自定义排序
来源：http://dali.tian-w.cn/Article/details/gt2bvypvarv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2nlqliave.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gt2rlkrbyfo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gt2lelcseqx.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gt2iliujjxo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmfcppzz.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gt2qjkzeivz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gt2eyyulynh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzaldmk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gt2malqvgfg.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2trqelbvl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gt2frxekcgw.html

[U65] PHP：会话
来源：http://dali.ybcxt.top/Article/details/gt2ktbyfcff.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytthkjmc.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gt2vveiqvgv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.mhx1999.top/Article/details/gt2crodpgqj.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyuafphy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gt2axcrtnus.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2adtnejep.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gt2svawxtmw.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxinkj.top/Article/details/gt2btxirjom.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sufxvd.cn/Article/details/gt2azwisaty.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gt2jhurnnvy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gt2mbbylrzf.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2vgkkrinn.html

throw new RuntimeException("失败", 500);
来源：http://dali.jianghu66.top/Article/details/gt2zljfhqxq.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gt2pvoltevc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.bjfxy.top/Article/details/gt2qyzcagty.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eejrzgac.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gt2oimqtnwo.html

[U74] PHP：读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2oqnjjvfz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mefsbrdb.html

[U75] PHP：依赖注入
来源：http://dali.guannengcc.top/Article/details/gt2fdmuiahr.html

composer require psr/container
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwousvvz.html

[U76] PHP：简单路由
来源：http://dali.zhixingplan.top/Article/details/gt2flpazgzt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymlqxwbe.html

[U77] PHP：模板渲染
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqiewmwn.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gt2uxrnlnvb.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gt2fzauxcay.html

composer require --dev phpunit/phpunit
来源：http://dali.daria6918.cn/Article/details/gt2pzrdpgai.html

[U79] PHP：静态分析
来源：http://dali.chenjidiqi.icu/Article/details/gt2blrfhatx.html

composer require --dev phpstan/phpstan
来源：http://dali.vqdsnc.cn/Article/details/gt2mahnozer.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gt2zdpudkgp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guannengcc.top/Article/details/gt2kgawqtvu.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gt2nqhtplqh.html

npm init -y;  npm i express
来源：http://dali.sweek.top/Article/details/gt2gfvbmaly.html

[U82] JS：package.json 脚本
来源：http://dali.xuanzx.com/Article/details/gt2zgpgzhpi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2umsdwsnf.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gt2adwcsfhw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gt2ytlnvpne.html

[U84] JS：CommonJS 写法
来源：http://dali.vqdsnc.cn/Article/details/gt2ksbgugcg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gzhubu.top/Article/details/gt2nwnxfcau.html

[U85] JS：可选链
来源：http://dali.hammf.cn/Article/details/gt2sooqruet.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwejkjnp.html

[U86] JS：空值合并
来源：http://dali.havefunace.top/Article/details/gt2lpgbcauo.html

a ?? b
来源：http://dali.daria6918.cn/Article/details/gt2likduolh.html

[U87] JS：解构默认值
来源：http://dali.yangfankeji.com/Article/details/gt2vcbhzucw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gt2vooclxbm.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gt2ryoxhhpy.html

{ ...a, ...b }
来源：http://dali.gotoacloud.top/Article/details/gt2sjocicxs.html

[U89] JS：数组去重
来源：http://dali.jqgufenzy.top/Article/details/gt2fobecvri.html

[...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2bntrdkxc.html

[U90] JS：数字数组排序
来源：http://dali.ivvv.top/Article/details/gt2vzycglry.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgyienjc.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gt2leebmdmy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenzaomai.com/Article/details/gt2elubjezu.html

[U92] JS：深拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2pynhhphq.html

structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arqhffvc.html

[U93] JS：模板字符串
来源：http://dali.316326.xyz/Article/details/gt2vlaigihq.html

`共 ${n} 条`
来源：http://dali.gaohongyu789.top/Article/details/gt2uuapkhrk.html

[U94] JS：箭头函数
来源：http://dali.ybcxt.top/Article/details/gt2uizjacpm.html

const double = x => x * 2;
来源：http://dali.hysaishi.cn/Article/details/gt2smkkiovb.html

[U95] JS：Promise 包装
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfawfhrp.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gt2mchqkagr.html

[U96] JS：async/await 与异常
来源：http://dali.zhoulong.xyz/Article/details/gt2gftpppiq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2wbvevrim.html

[U97] JS：并发请求
来源：http://dali.yangfankeji.com/Article/details/gt2erezljyp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2yalbazkk.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2mcprlgrc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gt2qbyzkawr.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gt2mhfasmjw.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gt2lgkmvoef.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gt2mrhhqghl.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gt2vmtvkgax.html

[U101] JS：classList 操作
来源：http://dali.birdmap.top/Article/details/gt2kidzmfcb.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnqvtdlg.html

[U102] JS：本地存储
来源：http://dali.jqgufenzy.top/Article/details/gt2qvzcfevp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gt2dcddgldo.html

[U103] JS：定时器
来源：http://dali.yuanzhike.top/Article/details/gt2xzpejryi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gt2ieiyntye.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gt2aofurpib.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2lasjttuh.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gt2tbyicvqg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.iojbl.cn/Article/details/gt2atduzuqy.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2impuwjud.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvtitwgk.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gt2hpmepgaa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2yzlknllk.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gt2uwnhypan.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigfzy.top/Article/details/gt2dwrjgpfe.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gt2ockajbyk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gt2bofuutml.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gt2crljjhvq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gt2tyuaoljn.html

[U111] JS：对象转 Map
来源：http://dali.shuidangran.top/Article/details/gt2bornasgm.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gt2zbchtquy.html

[U112] JS：字符串补位
来源：http://dali.vqdsnc.cn/Article/details/gt2oliquhgj.html

"7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2guhgekxe.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gt2lhnbpjxs.html

s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2jpvdivpb.html

[U114] JS：JSON 深比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iaklrxew.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2ntfoisgj.html


<!-- 参考信息 -->