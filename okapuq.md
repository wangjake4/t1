代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gttmnusydp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwneygqax.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawjbfeuv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtcgzzgfgj.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtmpgtpltu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gtbzdyahvr.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtixfccaue.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gtjapagbzv.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtzndfszzu.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtcecmmsgi.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gtosugmnpw.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gtogsqjexd.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtftxyalbp.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtwolpgdqc.html

[T40] Lua：元表
来源：http://dali.dianchejie.cn/Article/details/gtfugxkvca.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gtbhdomoit.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtkqmgeooh.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gtcguggpgx.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtzmgsqawh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtkcuwvece.html

[T43] Perl：字符串插值
来源：http://dali.birdmap.top/Article/details/gteinxjvjj.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtrbzvzrpw.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gtuwhgjwmy.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtpxkagqte.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtnisfzfto.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtpqpdnmpm.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gtbnlrkzir.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtemiqmmvx.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnhzsukj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtifsbejte.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtmasrhwte.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtpdzmjtra.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gtqbjalnco.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtwkqnzrvk.html

[T50] Perl：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtystbruou.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhoxwczo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gtxeplwuix.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtymoeqbta.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtmofcjoqh.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtimtwpmrp.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtmxcadriu.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtpnkmroyu.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gtwbhjufwx.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtwnlhclte.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gthufvmczm.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gthjsbtuaq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gtnxizddsq.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gtztiolhwn.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtfwfelewd.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtkvqqaihb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtxdtueewj.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gteaquoblv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtkssenjdr.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gtkqwzohtw.html

for (i <- 1 to 10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtjbfueldv.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gtmtriftyo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtttcvmghu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamibejei.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtzoihysan.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxhxebrdg.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtuagtlcfn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtecxdakaw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtozquvfqb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gtcbdmqvyl.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtzqmijcaq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yvedp.cn/Article/details/gttazkqeyh.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gtkmgyokas.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtsgzarrsm.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtgjwjfwxs.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gttzhvqxrb.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtskpeoqae.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gtiwrfqppx.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtjavsliiz.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gtyvjndwbb.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gtbpbjdszl.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gtedzcholu.html

[U09] Py：字典取最大值的键
来源：http://dali.guannengcc.top/Article/details/gtozycooyf.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtuhjrfnvn.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gtbbxwvtwz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gtimrkfzhi.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtjqjrrxpv.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtpptvkpmp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gttnxjdbbo.html

Counter(arr).most_common(3)
来源：http://dali.jinqigfzy.top/Article/details/gtjyaylzia.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtfkryxfvm.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthebcdqvc.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gtttsmabju.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gtgnmowqtp.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gtbdleilsv.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gtpprqxauj.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteijgsywz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtrguuxceu.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuipclec.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtgewailqx.html

[U18] Py：预编译正则
来源：http://dali.feifeiyinyue.top/Article/details/gtkyyjzkaz.html

pat = re.compile(r"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrhdlayo.html

[U19] Py：正则替换带回调
来源：http://dali.xziqi.cn/Article/details/gtktmyfldx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pycfn.com/Article/details/gtrwtupfqi.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gtjobwptnd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtaamgqkaj.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gtsgqtmgmh.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gtsmqamfmz.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gtwqfrequf.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtseyjibad.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gtgvmvfrso.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtrpmvdfml.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gtzwjkpvbg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtrsmncpsh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhengqikj.top/Article/details/gtgnlillwt.html

csv.DictReader(f)
来源：http://dali.ybcxt.top/Article/details/gtguqagura.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyztijapz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gtnxcudtjg.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimnfpmyn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gthoueubpo.html

[U28] Py：类型别名
来源：http://dali.gogol.net.cn/Article/details/gtojochzni.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gtfijkclco.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtndovraer.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gtilnsygnf.html

[U30] Py：数据类
来源：http://dali.jyoumei.cn/Article/details/gtwanhyvrd.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gtzmloumlk.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gtynrorqjc.html

python -m pytest -q
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygrxkqhs.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gttsliggsi.html

ruff format . && ruff check --fix .
来源：http://dali.tian-w.cn/Article/details/gtuugftbcq.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gtwxpvpxhf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sxryk.cn/Article/details/gtvmksvest.html

[U34] Py：判断编码
来源：http://dali.0kj1m.cn/Article/details/gtgluydyvz.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gtstnoyfmz.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gtgyvyvimi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj202588.top/Article/details/gtbmmfjxlb.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcwablkn.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtideqxkum.html

[U37] Py：读写 Excel
来源：http://dali.tanke756.top/Article/details/gtonautkte.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gtocwfrrfe.html

[U38] Py：获取脚本所在目录
来源：http://dali.hysaishi.cn/Article/details/gtaowshsid.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gtewleorhk.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gtewmoctuq.html

sys.stdout.isatty()
来源：http://dali.sxryk.cn/Article/details/gtdztontnm.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gtnxpilwfn.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtjriswbrf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gtgbkuvpfh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtluaxgzub.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtdajngari.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvmksepb.html

[U43] PHP：声明命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtzwlerzno.html

namespace App\Http;
来源：http://dali.zycfv.cn/Article/details/gtiqtdqzxs.html

[U44] PHP：开启严格类型
来源：http://dali.redwolf501.top/Article/details/gtqamtuxey.html

declare(strict_types=1);
来源：http://dali.ydzc1.top/Article/details/gtwqslddlo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gtcvpuciqs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtafkzzgmh.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gtbumnxkjg.html

?string $name = null
来源：http://dali.cashguo.top/Article/details/gtegsclnyd.html

[U47] PHP：联合类型
来源：http://dali.sysykeji.top/Article/details/gtgmbxztmq.html

int|string $id
来源：http://dali.jqgfzy.top/Article/details/gtrzdhhbtq.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gthdhcrvdi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfecdipvo.html

[U49] PHP：只读属性
来源：http://dali.316326.xyz/Article/details/gtqkewunpd.html

public readonly string $name
来源：http://dali.hammf.cn/Article/details/gtmkpnooku.html

[U50] PHP：构造器属性提升
来源：http://dali.wangshuangyany.cn/Article/details/gtbrrnadfu.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gtafillqwy.html

[U51] PHP：数组解构
来源：http://dali.yonumen.top/Article/details/gttnzsjnsb.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgcmylfc.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhfxjdnf.html

$double = fn($x) => $x * 2;
来源：http://dali.ehwqpu.com/Article/details/gtekpbdqwn.html

[U53] PHP：空合并运算符
来源：http://dali.yangfankeji.com/Article/details/gtozclbult.html

$v = $a ?? $b ?? "default";
来源：http://dali.andypj.xyz/Article/details/gtkstqpzkb.html

[U54] PHP：空安全调用
来源：http://dali.nanxuanxn.top/Article/details/gtilsrajuc.html

$obj?->method()
来源：http://dali.fzhhl.top/Article/details/gtrufqtzwb.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gtslfrudvp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtjokzrnbg.html

[U56] PHP：命名参数
来源：http://dali.jqgfzy.top/Article/details/gtiarqvvtq.html

f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtrlxejcst.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtudvsmfxi.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtblitdlcf.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gtyefgebgc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.snrcjt.cn/Article/details/gtslmwtelj.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gtpjjiwhxw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtiahdxzob.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtfqktkeoz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.0kj1m.cn/Article/details/gtntqokumu.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtpcvzxlbd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtruysxwdf.html

[U62] PHP：日期对象
来源：http://dali.yangfankeji.com/Article/details/gtnewwwomj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.c1oappe.top/Article/details/gtfnvnmesn.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gtifmontln.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cdnleiting.top/Article/details/gtslrebfxr.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gtamaklzbc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtlhwwcwtb.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gtbxbvqazd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gteayezeha.html

[U66] PHP：设置 Cookie
来源：http://dali.smart0.xyz/Article/details/gtovxzinun.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtvbpnpide.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtjtukbvrc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ppjwa.cn/Article/details/gtltuspydj.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gttnqydaor.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenzaomai.com/Article/details/gtlmmqzbsu.html

[U69] PHP：PDO 预处理
来源：http://dali.c1oappe.top/Article/details/gtnubpdkkr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ivvv.top/Article/details/gtfskvimbj.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfghpnrg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangshuangyany.cn/Article/details/gtyxfbnpgd.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gttchrmlst.html

throw new RuntimeException("失败", 500);
来源：http://dali.tian-w.cn/Article/details/gtlckgyzsi.html

[U72] PHP：写错误日志
来源：http://dali.shzxlz.cn/Article/details/gtitbbprrd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.havefunace.top/Article/details/gttgkmzxlk.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gtnuatsgns.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gtcxprqifs.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gthpjpoxms.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangdashe.top/Article/details/gtwfurfgda.html

[U75] PHP：依赖注入
来源：http://dali.gotoacloud.top/Article/details/gtithaeqhr.html

composer require psr/container
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosyyakgp.html

[U76] PHP：简单路由
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnnmzodv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258888.top/Article/details/gtsuanvjlt.html

[U77] PHP：模板渲染
来源：http://dali.zycfv.cn/Article/details/gtlxewrosw.html

composer require twig/twig
来源：http://dali.gotoacloud.top/Article/details/gtdwfswtjk.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyggxpum.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gtsyynawwm.html

[U79] PHP：静态分析
来源：http://dali.hfpthk.cn/Article/details/gtfomiaaig.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gtyyxgnrwg.html

[U80] PHP：代码规范修复
来源：http://dali.cqqwz.cn/Article/details/gtnlymcopx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhongyouzk.top/Article/details/gtfzwkarbd.html

[U81] JS：初始化项目
来源：http://dali.shangyingyoupin.top/Article/details/gtbalnsbjn.html

npm init -y;  npm i express
来源：http://dali.xinyue.icu/Article/details/gtvryzzkjr.html

[U82] JS：package.json 脚本
来源：http://dali.hnxiangtu.top/Article/details/gtxblpbcns.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hammf.cn/Article/details/gtjunnnsul.html

[U83] JS：ES Module 导入导出
来源：http://dali.c1oappe.top/Article/details/gtmnhnucpc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtoloqhfql.html

[U84] JS：CommonJS 写法
来源：http://dali.yangfankeji.com/Article/details/gtwnhhbikj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yongpay.top/Article/details/gtbxzfskld.html

[U85] JS：可选链
来源：http://dali.jinqigufen.top/Article/details/gtinnqycla.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtcmqmsdot.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gtkmvjfktr.html

a ?? b
来源：http://dali.yuxming.cn/Article/details/gtarnowqyz.html

[U87] JS：解构默认值
来源：http://dali.yongpay.top/Article/details/gtyiyudbjs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gtysprgvut.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gtpqoeyblp.html

{ ...a, ...b }
来源：http://dali.tianlin.xyz/Article/details/gtsccrlrhf.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsurjfxoa.html

[...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtjxpsksfn.html

[U90] JS：数字数组排序
来源：http://dali.ivvv.top/Article/details/gtibmttmkb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtihvyvelc.html

[U91] JS：对象键值遍历
来源：http://dali.iojbl.cn/Article/details/gtkjmcgfzi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hywenlv.cn/Article/details/gtazfjordn.html

[U92] JS：深拷贝
来源：http://dali.zdqjudy.top/Article/details/gtdcahfxdx.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtribdlnpz.html

[U93] JS：模板字符串
来源：http://dali.yuxming.cn/Article/details/gttkcusqjf.html

`共 ${n} 条`
来源：http://dali.ivvv.top/Article/details/gttyggfbbn.html

[U94] JS：箭头函数
来源：http://dali.yuxming.cn/Article/details/gtxecbbcqj.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtterodtuk.html

[U95] JS：Promise 包装
来源：http://dali.jlsjyb.cn/Article/details/gtacknbeuw.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gtixumtrii.html

[U96] JS：async/await 与异常
来源：http://dali.tanke756.top/Article/details/gtzvywvjws.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtlvksarro.html

[U97] JS：并发请求
来源：http://dali.svipenyu.cn/Article/details/gtzwygcnkk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtzdswidig.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gtzwvvhils.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gtejnjxpdu.html

[U99] JS：事件监听
来源：http://dali.gzhubu.top/Article/details/gtzzxsxdhh.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gttfuqttll.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtbwombjzw.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gtwvqikfom.html

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gtrblueojl.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gtdvzdkxxs.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gtnqgrjoub.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.316326.xyz/Article/details/gtvjnnqrup.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gttwpptbrv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gthmwzwfsx.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gthlrkguyh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gttlsgbuob.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gtjlniidwv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gtrwbuhozy.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtywuledla.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.kuanghao11.cn/Article/details/gtthctpcdu.html

[U107] JS：数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtsymceisx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gthxblqdst.html

[U108] JS：随机整数
来源：http://dali.0kj1m.cn/Article/details/gtlxpbverl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gotoacloud.top/Article/details/gtlafueeqk.html

[U109] JS：数组分组
来源：http://dali.dashuyun.cn/Article/details/gtfgkfuubi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtimgjsass.html

[U110] JS：数组分块
来源：http://dali.hnqzz.top/Article/details/gtgepktujx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gtgiijkmnx.html

[U111] JS：对象转 Map
来源：http://dali.pengpengdd.cyou/Article/details/gtzxrdtfno.html

new Map(Object.entries(obj))
来源：http://dali.zdqjudy.top/Article/details/gteqcwreqh.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gttwefhjkj.html

"7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtptqrncrh.html

[U113] JS：正则替换全部
来源：http://dali.yuxming.cn/Article/details/gtsiymbccs.html

s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtwrvdzaab.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gtqwvqzbcf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtfrexlpqa.html

[U115] JS：生成 UUID
来源：http://dali.ivvv.top/Article/details/gtaezqpgch.html

crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtdqdwnbpm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswbdlvtd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtysxyidbc.html

[U117] JS：单元测试
来源：http://dali.c1oappe.top/Article/details/gtrxcocdjd.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gtxvakuvyy.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gtlirbxyrz.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gtgkcfttng.html

[U119] JS：生产构建
来源：http://dali.316326.xyz/Article/details/gtooewwtdx.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtvjvggthu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangshuangyany.cn/Article/details/gtuqfpskea.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gtwvcjnisj.html


<!-- 参考信息 -->