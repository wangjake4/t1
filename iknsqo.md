代发 wailian999

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gttqxqvegl.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gtstszjdbl.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gtnieglzpk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtjazanpsy.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtbwnhmujx.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gthcdpuctk.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtbbdhkikk.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkmxfdwiu.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtdnohwoep.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gtbwbnppmt.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtthhpxnfh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtdmavqfab.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtbckrnyss.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtqgqoayrk.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtgayzonha.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gtjifydqnw.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtmlfhyeeo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtaxokzxdg.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtqpmrzfxj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gtnxnlehwz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtkqefblan.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gticnfqcnt.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtwpcmjjrt.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtndvqtbpw.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtbgeilpqb.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtofqbkkzd.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gttmuvvcoh.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtvwkzwkkc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gthjikilev.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtxgkdwjcl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gtjtwzchov.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gtgljalclv.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgomyhad.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekfzxinr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccqufhnc.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gtjaxjjhvd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gtnnqpbeil.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtlhzqawct.html

for (i <- 1 to 10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtgmucbzoa.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gtxpydrlof.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhnxoite.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgdkcsyty.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtkoeghefn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkownmtdh.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtmizhaoox.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gtxdjbsdxn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtounukwbf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gtyjxqqrzb.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtmpdmmvfu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtljgehnqu.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gthwiwbkyt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtaklfhsnf.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gtmhedupho.html

list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtlsueegic.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtzulbumtq.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gttopdmxef.html

[U07] Py：反转字典键值
来源：http://dali.hywenlv.cn/Article/details/gttkfmpqul.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gtlgkwzcud.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtsyvspxhf.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtkihattpr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhoulong.xyz/Article/details/gtfgdrfgit.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gtleygparm.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gtlvefnnyk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gtmnowsddq.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtwebtjrkg.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtsdwbgyfy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwwsprsb.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gtwxwdkgap.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gtoobxozta.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqmtvgaj.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gtlyagxlxt.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtwbjxfnoo.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gtvbxmdrno.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gtjnlclcak.html

[U16] Py：命令行参数解析
来源：http://dali.hfpthk.cn/Article/details/gtulqiskia.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyidbntb.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gtktlnrbjt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtycalsqns.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpylheyfw.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gtzhfhotyu.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtdpzdtuso.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbizoogo.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gtwxwnerok.html

@functools.lru_cache(maxsize=None)
来源：http://dali.svipenyu.cn/Article/details/gtncecymfy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gtpoifsgnf.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtlzfdngor.html

[U22] Py：矩阵转置
来源：http://dali.gogol.net.cn/Article/details/gtzgbnshnw.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gtogqvuqdv.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gtdxqoqkcl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtloibsapo.html

[U24] Py：路径操作
来源：http://dali.snrcjt.cn/Article/details/gtyykcyixm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtsfjwjrye.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gtccqhoats.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gtpyimbxgl.html

[U26] Py：并发下载
来源：http://dali.wangshuangyany.cn/Article/details/gthhhjkbik.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fengsongda.top/Article/details/gttfnibsjz.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtoviybtpe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtivcworql.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gtapvatuaj.html

UserId = int
来源：http://dali.zycfv.cn/Article/details/gtgkdolhyi.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gtdhvwksws.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtorgsewbf.html

[U30] Py：数据类
来源：http://dali.jiagoushi.top/Article/details/gtipdqgzhx.html

@dataclass(slots=True)
来源：http://dali.ydzc1.top/Article/details/gtiynbeuvd.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtonihnavh.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtwfrielnn.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gtxgaanone.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtahacihls.html

[U33] Py：打包发布
来源：http://dali.zycfv.cn/Article/details/gtadlvswdc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.mhx1999.top/Article/details/gtqtyuyyiy.html

[U34] Py：判断编码
来源：http://dali.ehwqpu.com/Article/details/gtzdwzmwck.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtiovzisrh.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gtrtywqpty.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gtbaeuaqsv.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjjyvmox.html

schedule.every(10).minutes.do(job)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdottvrz.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gtnvwpcpwr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gtjbhhctym.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtllfugzev.html

Path(__file__).resolve().parent
来源：http://dali.yj20258.top/Article/details/gtdekdipqp.html

[U39] Py：判断是否在交互环境
来源：http://dali.hywenlv.cn/Article/details/gtuwwmpzov.html

sys.stdout.isatty()
来源：http://dali.aibaodan.cn/Article/details/gtvofieinn.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gtqacohcku.html

print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gttiohmcoi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzklokmi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjtgjzed.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yongpay.top/Article/details/gtgbkscexz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkxkcyrq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtxfeexocy.html

namespace App\Http;
来源：http://dali.yuxming.cn/Article/details/gtdnlfqvyx.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gtawapudlb.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gtxsbgbwud.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gtosvyinrb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtwxgmfnwo.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gtdhhxmhhq.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gtvsxyfvvy.html

[U47] PHP：联合类型
来源：http://dali.jyoumei.cn/Article/details/gtgvyqfnft.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gtqutzqzao.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjvopfmg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gtzplyalnj.html

[U49] PHP：只读属性
来源：http://dali.jqgfzy.top/Article/details/gtsbrxpeqt.html

public readonly string $name
来源：http://dali.hywenlv.cn/Article/details/gtlsxuvvef.html

[U50] PHP：构造器属性提升
来源：http://dali.birdmap.top/Article/details/gtztmozmbd.html

public function __construct(private int $id) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdgykdbg.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gtajecgnvx.html

[$a, $b] = $arr;
来源：http://dali.jyoumei.cn/Article/details/gtfwtiqhtb.html

[U52] PHP：箭头函数
来源：http://dali.yongpay.top/Article/details/gtfldpsnrc.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtgmmxgetk.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtzpniiwiz.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gtvzhlzshk.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gtlhdydaun.html

$obj?->method()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttunikaxf.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gthgegpbml.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtgakwliky.html

[U56] PHP：命名参数
来源：http://dali.smart0.xyz/Article/details/gtxcmpudoj.html

f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtwppbdcjb.html

[U57] PHP：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtbozmplhl.html

"值: {$a}"
来源：http://dali.quarkkingdee.top/Article/details/gtamgmunib.html

[U58] PHP：数组三件套
来源：http://dali.shuidangran.top/Article/details/gtgpfkbxhs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtnlxmmftg.html

[U59] PHP：自定义排序
来源：http://dali.shuidangran.top/Article/details/gtvaeqfsjm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtfwaastsq.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gtioclibbd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gtjvrktuxw.html

[U61] PHP：正则
来源：http://dali.gogol.net.cn/Article/details/gthucewhla.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtxomzfiny.html

[U62] PHP：日期对象
来源：http://dali.jlsjyb.cn/Article/details/gtyjllfmbk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daxiang520.top/Article/details/gtuacikpcc.html

[U63] PHP：文件读写
来源：http://dali.wangdashe.top/Article/details/gtzwutrjgy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.haohaochexian.top/Article/details/gtedanchff.html

[U64] PHP：目录遍历
来源：http://dali.hfpthk.cn/Article/details/gtenitlrfd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gtxtrmxniq.html

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gtrseoctgx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yongpay.top/Article/details/gtgaqjbopd.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzwtnumo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yangfankeji.com/Article/details/gtfjobjjnz.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gtjjqyexkc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnxiangtu.top/Article/details/gtiekxeduf.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gthgmxyvek.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gtlxsfcvzy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhoulong.xyz/Article/details/gtbtnlvatv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gtgwrdiuzx.html

[U70] PHP：PDO 事务
来源：http://dali.sweek.top/Article/details/gtnmmmpwbg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gtcgaelvcw.html

[U71] PHP：抛出异常
来源：http://dali.daxiang520.top/Article/details/gtdakimgur.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gtpnsnkwph.html

[U72] PHP：写错误日志
来源：http://dali.andypj.xyz/Article/details/gtschwqqqn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hongshengwenyu.top/Article/details/gtrlmhmybc.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gtrrnrltvk.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gtcbmsfkpq.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtzsigejbh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ybcxt.top/Article/details/gtapaaebsp.html

[U75] PHP：依赖注入
来源：http://dali.pengpengdd.cyou/Article/details/gtroeblahd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gtsmidprrj.html

[U76] PHP：简单路由
来源：http://dali.snrcjt.cn/Article/details/gtffeqnybp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.havefunace.top/Article/details/gtbuhmvfin.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gtgfsbtjhp.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gtmcjdlsse.html

[U78] PHP：单元测试
来源：http://dali.chenzaomai.com/Article/details/gtihteaqkw.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gtlslawbku.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gtkmdrgomk.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258.top/Article/details/gtagwrdpzi.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdlfwaad.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zdqjudy.top/Article/details/gtiffzjdqd.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtzaovrznf.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtdnwgrmwd.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gtcdqdvjxt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shzxlz.cn/Article/details/gtckisxvmr.html

[U83] JS：ES Module 导入导出
来源：http://dali.pycfn.com/Article/details/gtukxdxmbf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtvrpxsxdd.html

[U84] JS：CommonJS 写法
来源：http://dali.0kj1m.cn/Article/details/gtvlkfydsq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pycfn.com/Article/details/gtdlerxbtq.html

[U85] JS：可选链
来源：http://dali.zhongyouzk.top/Article/details/gtzvlviwvv.html

a?.b?.c
来源：http://dali.meibo888.top/Article/details/gtznssbrnc.html

[U86] JS：空值合并
来源：http://dali.gogol.net.cn/Article/details/gtrydfcnvg.html

a ?? b
来源：http://dali.pycfn.com/Article/details/gthcepfial.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gtqwlqysai.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gtesqyxpcu.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gtfwyfxcsh.html

{ ...a, ...b }
来源：http://dali.snrcjt.cn/Article/details/gtccecdrbv.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gticnekntj.html

[...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtkelxxasf.html

[U90] JS：数字数组排序
来源：http://dali.jqgufenzy.top/Article/details/gthknxwjls.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gttgmhuqay.html

[U91] JS：对象键值遍历
来源：http://dali.yangfankeji.com/Article/details/gtdnwnmixg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gtrukkrozb.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzljekocc.html

structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtojsmrorf.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gtgyukvjgy.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gtfdjklqei.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gttlwkvbbm.html

const double = x => x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtfewrai.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gtkbvriwls.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gtlaxxdoiw.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gtspghqrty.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtztteivmz.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gtfesnyrjh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtadaxjjrh.html

[U98] JS：fetch 带 JSON
来源：http://dali.aibaodan.cn/Article/details/gtdtgtwedy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnqzz.top/Article/details/gttcdssjfa.html

[U99] JS：事件监听
来源：http://dali.yuxming.cn/Article/details/gtevxgukxv.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gtnxskguer.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gtozjwxygi.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gtokklrtdl.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gtqweuivbk.html

el.classList.toggle("active")
来源：http://dali.hywenlv.cn/Article/details/gtjmcubxrh.html

[U102] JS：本地存储
来源：http://dali.fzhhl.top/Article/details/gtbewpqysd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj202588.top/Article/details/gtumqzomdj.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gtzdfsuvcx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtuqdalxpl.html

[U104] JS：防抖
来源：http://dali.jyoumei.cn/Article/details/gttoxbnqya.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gthnkchrmk.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gtsjzzqnks.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtzdtegwas.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtzltwfhfe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gtnyyomixa.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gtojenxzij.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtmjonmchd.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gtcntrmamn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gtjjcltfea.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gtqacuwpsq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtpoqxuoch.html

[U110] JS：数组分块
来源：http://dali.chenzaomai.com/Article/details/gtcomnpaey.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gtjokhzeyb.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtmxbtvbjn.html

new Map(Object.entries(obj))
来源：http://dali.cdnleiting.top/Article/details/gtestthfeu.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtpcpctodp.html

"7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtkbotrshp.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gtabmghedj.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtvhjzqaaq.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gtchtejvdb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjkjefpv.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtrsnkoaeo.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqamfaqyx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.316326.xyz/Article/details/gtzetleeon.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtulzsplso.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gtrwfdrfvq.html

npm i -D vitest;  npx vitest
来源：http://dali.pengpengdd.cyou/Article/details/gtadnambfz.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gtecmyhzpi.html

npm i -D vite;  npx vite
来源：http://dali.yvedp.cn/Article/details/gtinkmkmob.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gtjhybhmwb.html

npx vite build
来源：http://dali.sysykeji.top/Article/details/gtjkkauiku.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gtxijzgntd.html

import.meta.env.VITE_API_URL
来源：http://dali.gzhubu.top/Article/details/gttkiyossz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtodynzxhh.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtzfcjujee.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlgnlpdda.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gtdhfryqtl.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtpesmvine.html

PHP ............ 252
来源：http://dali.gaohongyu789.top/Article/details/gtpiulmzfc.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gtdrrakgyn.html

TypeScript ..... 212
来源：http://dali.sxryk.cn/Article/details/gtnzbaqbky.html

Java ........... 212
来源：http://dali.tanke756.top/Article/details/gtgfpwsljn.html

Go ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhnjpjxg.html

Ruby ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtntkelgmm.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gtikfdmdfi.html

C .............. 30
来源：http://dali.jiagoushi.top/Article/details/gtnakscery.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtrjvgkdnn.html

SQL ............ 90
来源：http://dali.haohaochexian.top/Article/details/gtyweiopjc.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtnfvrsmhr.html


<!-- 参考信息 -->