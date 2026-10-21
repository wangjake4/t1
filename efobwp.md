代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtyogrbabu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gtiuyivnbd.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtxlrmzacj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtvrzegwue.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtqfkdvvdq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbwwvuei.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtuccvgqgf.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkafzakdf.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtlawlbmie.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gtjzisdqai.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gtkptqjkuq.html

if x > 0 then print("正") end
来源：http://dali.hywenlv.cn/Article/details/gtwpigayxi.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gtvwpuptoq.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gttjjhrdqn.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtavpcsjhq.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtvrhxnwok.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtlveuegol.html

print "Hello\n";
来源：http://dali.sufxvd.cn/Article/details/gtpapgmekv.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gtersmxnoc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gtbnjcicjv.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtxznmtcad.html

"值: $a"
来源：http://dali.nanxinkj.top/Article/details/gtvnbtmqau.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gtpzvandma.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzssxuqua.html

[T45] Perl：数组遍历
来源：http://dali.zhongyouzk.top/Article/details/gtwfrhiojd.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtetcefuwt.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtroyjmbud.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gtxjkwckjh.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtuiuusttb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtoynhbwml.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtocatoyiv.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gtzlncbakk.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtawoptxyl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtduqlshge.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtqntbsswf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gtcmhlhncn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtaemeyevi.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtxdceqdwt.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtxjflvaxt.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gtzmqkpxhx.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gtxoanhsub.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtkdnzjrag.html

s"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtlcplhpfi.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtboxkvvet.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtkfomhzen.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtpvestgtq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gtqemlsviz.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtmvzwqwek.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gtxenvjrzm.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtzpfqolvh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gtgxglsaey.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtzhuvnhbs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtyokrcxbg.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtqofaamdb.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtwabeybsa.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtaqnlfejk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtrlzvffrc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrnfvxwxx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtnjqcxvgh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmqrmxnag.html

[U01] Py：创建虚拟环境
来源：http://dali.wangshuangyany.cn/Article/details/gtmtdoxldh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gtfztecwnp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gtwnovqhdn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gtxkvbanpr.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbzhfbtb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gtrnimvptp.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtmrwkaweg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gtqekzcdfh.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gtdocpyeaj.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtvljbfawl.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtdjhffywn.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtzvbqxads.html

[U07] Py：反转字典键值
来源：http://dali.hammf.cn/Article/details/gtqdrcrhvp.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gtryfwihsb.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gtofppazxy.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtephitaaz.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtublujstd.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gtarnsxzkf.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtmvsszqbq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gtyxcqlpzr.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtvuaexamo.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtsbdmeppi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gtdmbixqdv.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtoqxwxxzw.html

[U13] Py：固定长度队列
来源：http://dali.mhx1999.top/Article/details/gtarhgxhca.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdxyvmxd.html

[U14] Py：分组收集到列表
来源：http://dali.bjfxy.top/Article/details/gtfpmrcjgb.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtnigutnan.html

[U15] Py：高精度计时
来源：http://dali.fengsongda.top/Article/details/gtehsqjvkh.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gtygwyyspl.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gtuuuwncyt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gttebemoyg.html

[U17] Py：初始化日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxdcdcvt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtatrjiare.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gtnygmaacr.html

pat = re.compile(r"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gthexdccyu.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gtgmtglfls.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gtirfashgi.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtobjungwf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangdashe.top/Article/details/gtiiyagutb.html

[U21] Py：自定义上下文管理器
来源：http://dali.xylfe.cn/Article/details/gtahinwijt.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gtmyjwhzij.html

[U22] Py：矩阵转置
来源：http://dali.svipenyu.cn/Article/details/gtzjgrvquj.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gttgncvhlb.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gtiiqlfdum.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbunbdtmw.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gtpuuzlwsm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtfcaspsjq.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gtfgftielm.html

csv.DictReader(f)
来源：http://dali.ivvv.top/Article/details/gtelpykpfo.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gtvutrnomt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtwvveditd.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtdgaemlbf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tanke756.top/Article/details/gtawprjdbn.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gtwlkccvuv.html

UserId = int
来源：http://dali.nanxinkj.top/Article/details/gtfvdubgaj.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gtkhvwmbxr.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtubiyoufe.html

[U30] Py：数据类
来源：http://dali.sufxvd.cn/Article/details/gtqpxqzkxr.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gthuzujfvk.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gtivunixre.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtxiwysbij.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtkhfhkenf.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gtonkdqgkv.html

[U33] Py：打包发布
来源：http://dali.quarkkingdee.top/Article/details/gttdomojoi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuanzhike.top/Article/details/gtwhywwrhs.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtmzompujq.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gtwodsjqjb.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gtqpirznpx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gtbvgxbrzy.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gtauaghzig.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtepwoccpq.html

[U37] Py：读写 Excel
来源：http://dali.iojbl.cn/Article/details/gtmwtprwxs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gtxxnsxcrk.html

[U38] Py：获取脚本所在目录
来源：http://dali.aibaodan.cn/Article/details/gtejqjpzqx.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gtiytawvem.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gtnngnsubg.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtfiwbglaz.html

[U40] Py：打印到标准错误
来源：http://dali.andypj.xyz/Article/details/gtfhoewxvg.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtcqzluyrm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gtvyxfjruy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtfcafqdxj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gtivneirqi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfwglqai.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtfuysbrgh.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gtyngixpna.html

[U44] PHP：开启严格类型
来源：http://dali.hfpthk.cn/Article/details/gtdiovupvx.html

declare(strict_types=1);
来源：http://dali.cheryme.top/Article/details/gtvbpkurhj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gtsyalonyh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtjhzrrfui.html

[U46] PHP：可空类型
来源：http://dali.birdmap.top/Article/details/gtlilbwaew.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gtvyafszby.html

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltdrrbcv.html

int|string $id
来源：http://dali.guowangkeji.top/Article/details/gtnfofawyc.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gtakpeuull.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gttoozbcux.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gtazclmjqf.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gtjidsmwdd.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsluqpdg.html

public function __construct(private int $id) {}
来源：http://dali.yuxming.cn/Article/details/gtkgiuoovb.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gtbhkukdgb.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtrdhqafui.html

[U52] PHP：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gttkktvacc.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtcjqsjsmn.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gtcqwtkhtt.html

$v = $a ?? $b ?? "default";
来源：http://dali.feifeiyinyue.top/Article/details/gtankxajpo.html

[U54] PHP：空安全调用
来源：http://dali.zhongyouzk.top/Article/details/gtncwgovom.html

$obj?->method()
来源：http://dali.tian-w.cn/Article/details/gtcjzfmacb.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gtkbvqtwfm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtbmtefnxq.html

[U56] PHP：命名参数
来源：http://dali.pycfn.com/Article/details/gticyweagd.html

f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtwzkyrmvy.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtsmidkees.html

"值: {$a}"
来源：http://dali.hnqzz.top/Article/details/gtkmqzzami.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtmjrguhbn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtnaggcfwp.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gtawsoxvgp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtzpacgejt.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gtbopqdnpo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.smart0.xyz/Article/details/gtgqrduzxt.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtslkgdexc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtarseomnc.html

[U62] PHP：日期对象
来源：http://dali.jinqigfzy.top/Article/details/gtxfkrnfxa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cashguo.top/Article/details/gtoxajmbyn.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtabxzlsui.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfmzentc.html

[U64] PHP：目录遍历
来源：http://dali.yj20258.top/Article/details/gtrcthewrv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtaqycmlzg.html

[U65] PHP：会话
来源：http://dali.yangfankeji.com/Article/details/gtlywvwkdk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtasgoxugc.html

[U66] PHP：设置 Cookie
来源：http://dali.dashuyun.cn/Article/details/gtwrwjlzer.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jiagoushi.top/Article/details/gttytbtoof.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtwnaxxbqf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yongpay.top/Article/details/gtambdepzn.html

[U68] PHP：PDO 连接
来源：http://dali.sxryk.cn/Article/details/gtvhpuzfxi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhengqikj.top/Article/details/gtrxmocwtn.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtirpxzcfq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gogol.net.cn/Article/details/gtcwiifecu.html

[U70] PHP：PDO 事务
来源：http://dali.0kj1m.cn/Article/details/gtlepotlnv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xylfe.cn/Article/details/gtxvcrbtgc.html

[U71] PHP：抛出异常
来源：http://dali.yj20258.top/Article/details/gtzrddaxzs.html

throw new RuntimeException("失败", 500);
来源：http://dali.ivvv.top/Article/details/gtmcrvotda.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gtsldoouob.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gtcztugymf.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gtwzbaalpl.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtarwcmlrb.html

[U74] PHP：读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gttoaehjup.html

getenv("APP_ENV") ?: "production"
来源：http://dali.quarkkingdee.top/Article/details/gtqzbhgwkn.html

[U75] PHP：依赖注入
来源：http://dali.hongshengwenyu.top/Article/details/gtmaykianx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gtqmebwldk.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtbfxobgdy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gtakrbbrbh.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtekfdhltm.html

composer require twig/twig
来源：http://dali.cqqwz.cn/Article/details/gtjofcjfzk.html

[U78] PHP：单元测试
来源：http://dali.chenzaomai.com/Article/details/gttukyzbtm.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gtevuloguv.html

[U79] PHP：静态分析
来源：http://dali.xylfe.cn/Article/details/gtrohepxzm.html

composer require --dev phpstan/phpstan
来源：http://dali.xinyue.icu/Article/details/gtipjrpolt.html

[U80] PHP：代码规范修复
来源：http://dali.yuxming.cn/Article/details/gtkycrpcwy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuanzx.com/Article/details/gtbykmvhvq.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gtjrfxzdnx.html

npm init -y;  npm i express
来源：http://dali.sweek.top/Article/details/gtvpnaawte.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigfzy.top/Article/details/gtpmwftdco.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sysykeji.top/Article/details/gtlbvgonks.html

[U83] JS：ES Module 导入导出
来源：http://dali.havefunace.top/Article/details/gtnmjtxons.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gthsblrher.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gtgzxqlywz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtozsjtdgh.html

[U85] JS：可选链
来源：http://dali.aibaodan.cn/Article/details/gtwqcsdfsf.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gtvebydhrv.html

[U86] JS：空值合并
来源：http://dali.yangfankeji.com/Article/details/gtcyqmddrx.html

a ?? b
来源：http://dali.hammf.cn/Article/details/gtydrrqztd.html

[U87] JS：解构默认值
来源：http://dali.kuanghao11.cn/Article/details/gttzapxqfu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ppjwa.cn/Article/details/gtxccytyxp.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gtnxtoytng.html

{ ...a, ...b }
来源：http://dali.tanke756.top/Article/details/gtornwxyrd.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gtkomkyfuv.html

[...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtdptpdktk.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gtlvzvvyik.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtyppwydxv.html

[U91] JS：对象键值遍历
来源：http://dali.birdmap.top/Article/details/gtopckvgrk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgufenzy.top/Article/details/gtuvlhgibh.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gtfkjxdkha.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtcfzbjdbj.html

[U93] JS：模板字符串
来源：http://dali.ybcxt.top/Article/details/gtenhuzzja.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gtqqgygivq.html

[U94] JS：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtbueydnxi.html

const double = x => x * 2;
来源：http://dali.ydzc1.top/Article/details/gtqjestakb.html

[U95] JS：Promise 包装
来源：http://dali.sweek.top/Article/details/gtqnlvwruw.html

new Promise((resolve, reject) => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtagfengzz.html

[U96] JS：async/await 与异常
来源：http://dali.nanxuanxn.top/Article/details/gtjywyzhxy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtfwgxfgkh.html

[U97] JS：并发请求
来源：http://dali.zhongyouzk.top/Article/details/gtmrcpskyy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtbyqtottj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtdfctrnxk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gtgivacloq.html

[U99] JS：事件监听
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqasgbbg.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgunkpmf.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gtmkrzgqoq.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gtdeirxlya.html

[U101] JS：classList 操作
来源：http://dali.tanke756.top/Article/details/gtbxwdbtyn.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkrxlten.html

[U102] JS：本地存储
来源：http://dali.xylfe.cn/Article/details/gttyfdedpl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cucudq.cn/Article/details/gtamagirqm.html

[U103] JS：定时器
来源：http://dali.zhengqikj.top/Article/details/gtljtpjaxw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gtlzeglsde.html

[U104] JS：防抖
来源：http://dali.yuanzhike.top/Article/details/gtuazsuztl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtqnfctuhe.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gtfpakxfxp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gtzltkkpmm.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtpdiwpfbb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gtjvnaxzis.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtecrzvqjs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtudwxpwhe.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gtzhlaleip.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gtmviqttly.html

[U109] JS：数组分组
来源：http://dali.zhengqikj.top/Article/details/gtxoknlxuv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtgwzcnycg.html

[U110] JS：数组分块
来源：http://dali.zhiwuduotai.top/Article/details/gtajojmqru.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.birdmap.top/Article/details/gtbbpmubhg.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gtmqdokals.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gtnbnyopep.html

[U112] JS：字符串补位
来源：http://dali.daxiang520.top/Article/details/gtswqdslij.html

"7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtucvfyovr.html

[U113] JS：正则替换全部
来源：http://dali.chenjidiqi.icu/Article/details/gtrsmbpldp.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtssziuiaq.html

[U114] JS：JSON 深比较
来源：http://dali.hnqzz.top/Article/details/gtnjlpyimu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtidwofnro.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtzyqxxxoo.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gttsqbkcre.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gtvzkspebe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtstfouaei.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gtwllowbzp.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gtvhesrpfc.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gtdxnajlwo.html

npm i -D vite;  npx vite
来源：http://dali.sysykeji.top/Article/details/gtewbhionr.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdltgutbl.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gtyeclgoht.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gtuhwbxwct.html

import.meta.env.VITE_API_URL
来源：http://dali.yueranfly.top/Article/details/gteyepwdvh.html


<!-- 参考信息 -->