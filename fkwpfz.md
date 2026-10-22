代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gttphdpmbm.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gtsfggtnre.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtgzqprcvg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gttpinhroz.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gthmqgxhfo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtgreskwvm.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtnjujjijb.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gtlotqfqmg.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtqtywmhbc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtupcgbzxp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtqxrezeje.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gthqvozsro.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtmyaswghy.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhymeojr.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtfxpkofns.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gtbtruagix.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gtsaluexnh.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtaunebife.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtncovheel.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtesbjcegn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gtoicmferl.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtkryjajjq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtziagmptq.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gtrelyzonv.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtbhqiwfzn.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtmifrhjvp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtidcickfr.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gtghpndnbv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwybptqk.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gtawflxycz.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtsrjvxyuy.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gtgancmnhx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtbblkjwdu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzowkoulo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtsdeoucri.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyfbhctum.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gtlhefvhzk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtzdsrhnhh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gtzklchflr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtffuqdiro.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gthsqqzykj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gtpgharmqu.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gtunccgjsr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtysypqzdx.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtmlaxgdoe.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtexnmdkax.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtufwodvfy.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gttuxduvqx.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbxysaza.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwdehjjh.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gtnopkmrez.html

[y for x in nested for y in x]
来源：http://dali.xuetiantiany.cn/Article/details/gtwoukajwq.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gtiipgdchh.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtlcuotiaz.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gtlxacjsdx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gtopnginim.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtozqrstey.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gtvvuibcmw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gtxxgjrtyz.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtwyhlxhkd.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtusslittt.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gtlvhnixmh.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gtetnobodc.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtfoqewfmq.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtdxeymgwy.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gtqupfkwnx.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gthjcstvqt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gtbfgwhszi.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gtlrsowucy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gtpybrfvpi.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtlhyahtbp.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gttthlsryw.html

[U19] Py：正则替换带回调
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaculwvw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtqpgqokjc.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gtyjojbtdb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gtatjwwyni.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gtcbrmsnpz.html

@contextlib.contextmanager
来源：http://dali.hnqzz.top/Article/details/gtgmoshksu.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gtcwnnamci.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gtxkejvlep.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gtoouqyfyt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtdzgifeoc.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gtjctpghpz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtguopoybh.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gtjuvwaadw.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gtbybbsrdp.html

[U26] Py：并发下载
来源：http://dali.nanxuanxn.top/Article/details/gtotbnmfki.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gtjntezldj.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfjzwdpp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gtczzissxd.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtskcmfi.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtbwqpesjq.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gteehpbnvz.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtnyrszcas.html

[U30] Py：数据类
来源：http://dali.andypj.xyz/Article/details/gtwuwtyyak.html

@dataclass(slots=True)
来源：http://dali.9152youxi.cn/Article/details/gtvakpcqqr.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtikwsukdz.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfhvcagz.html

[U32] Py：代码格式化
来源：http://dali.jinqigufen.top/Article/details/gtgqimlglx.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtplucswng.html

[U33] Py：打包发布
来源：http://dali.nwbrower.top/Article/details/gtxeopqkgw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gtywbwlref.html

[U34] Py：判断编码
来源：http://dali.daxiang520.top/Article/details/gtauqavjpb.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gtjlgvhoxh.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvykdabqe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhongyouzk.top/Article/details/gttxfnwykb.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gtxyrboxci.html

schedule.every(10).minutes.do(job)
来源：http://dali.vqdsnc.cn/Article/details/gtorpnbisb.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gtumwtqgph.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gtxuhjglrs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhixingplan.top/Article/details/gtdcimbqag.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gthhprybmn.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gttxzviacj.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gtoqoiqxao.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gttpldhhhk.html

print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gttviyveca.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zdqjudy.top/Article/details/gtvkxeqltz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gtzkmxqkof.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gtjevqjwnp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gtemevnlxx.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gttqwoqdxn.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gtgmsuhymu.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gtdnbsesbw.html

declare(strict_types=1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthndlkfip.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gtqrwnplql.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtvvdawuud.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gtviopargv.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gtbxyyammf.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gtxteurqkf.html

int|string $id
来源：http://dali.smart0.xyz/Article/details/gtsodveoqh.html

[U48] PHP：纯枚举
来源：http://dali.tanke756.top/Article/details/gtxahwppiz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gtwdqzlhbo.html

[U49] PHP：只读属性
来源：http://dali.yonumen.top/Article/details/gtmdbtqqlk.html

public readonly string $name
来源：http://dali.cashguo.top/Article/details/gtgoawvscw.html

[U50] PHP：构造器属性提升
来源：http://dali.cucudq.cn/Article/details/gtdepsdukz.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gtmaqowzue.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gtytxljtvt.html

[$a, $b] = $arr;
来源：http://dali.bjfxy.top/Article/details/gtmbswccmo.html

[U52] PHP：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gtqlnfwmry.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gtlzcnjbnk.html

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gttcxhsgpw.html

$v = $a ?? $b ?? "default";
来源：http://dali.316326.xyz/Article/details/gtpsfabfld.html

[U54] PHP：空安全调用
来源：http://dali.shangyingyoupin.top/Article/details/gtqpfvqmok.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gthweoywja.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gtcrgbdzga.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yueranfly.top/Article/details/gtppatlwcn.html

[U56] PHP：命名参数
来源：http://dali.zhixingplan.top/Article/details/gtvvunpdqp.html

f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtonuvtljc.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gthenhdofg.html

"值: {$a}"
来源：http://dali.zhoulong.xyz/Article/details/gtfxvezwic.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gtwebooycw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gtpcegxfgg.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtbshktrmx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtpbifvmvu.html

[U60] PHP：JSON 编解码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpevhhyem.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gthbbacoew.html

[U61] PHP：正则
来源：http://dali.chenjidiqi.icu/Article/details/gtzaozchfg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtbbdfoymi.html

[U62] PHP：日期对象
来源：http://dali.ydzc1.top/Article/details/gtcfpocpaa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gtqjiecowi.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gtsmycaorm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gtdqnvqece.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gtfepnnqpe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gtvmoaqngt.html

[U65] PHP：会话
来源：http://dali.daria6918.cn/Article/details/gtvuqkfevb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtwrvgkwix.html

[U66] PHP：设置 Cookie
来源：http://dali.gzhubu.top/Article/details/gtagnurmke.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtbcbzeaap.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtwaxuolhu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hammf.cn/Article/details/gtzzlyhxbg.html

[U68] PHP：PDO 连接
来源：http://dali.nanxinkj.top/Article/details/gtcqydhctj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hywenlv.cn/Article/details/gtyswjduqo.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gtobbxwlgz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtdobsluqa.html

[U70] PHP：PDO 事务
来源：http://dali.jiagoushi.top/Article/details/gttrovxrym.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gtcqxopzwx.html

[U71] PHP：抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtmnqgunmc.html

throw new RuntimeException("失败", 500);
来源：http://dali.316326.xyz/Article/details/gtwcgflspq.html

[U72] PHP：写错误日志
来源：http://dali.hysaishi.cn/Article/details/gtswqiwqya.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gtdzukpcpz.html

[U73] PHP：读取 ini 配置
来源：http://dali.snrcjt.cn/Article/details/gtjcrfcffq.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gtmhnbesyu.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtlnphpbke.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gtjliodaud.html

[U75] PHP：依赖注入
来源：http://dali.tianlin.xyz/Article/details/gtepjkdegu.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gtxqkrbbch.html

[U76] PHP：简单路由
来源：http://dali.chenzaomai.com/Article/details/gtquyqnzil.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jiagoushi.top/Article/details/gtbedvboor.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtfheeebgx.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gtjigmvqqk.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgteffaio.html

composer require --dev phpunit/phpunit
来源：http://dali.dianchejie.cn/Article/details/gtfhemrqcb.html

[U79] PHP：静态分析
来源：http://dali.redwolf501.top/Article/details/gtsivzsgoe.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gtyefdjrgb.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxsdjaug.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtcnjaxckg.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gtjgdscdlm.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gtinihkwjq.html

[U82] JS：package.json 脚本
来源：http://dali.jqgfzy.top/Article/details/gtrmmuiwgr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gtdjtsnbsr.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenjidiqi.icu/Article/details/gtvobkfsxi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtnxlwtwiz.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gthgowmisj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gtpmctnrhx.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gtwwnwedrd.html

a?.b?.c
来源：http://dali.nanxinkj.top/Article/details/gtkzonofwk.html

[U86] JS：空值合并
来源：http://dali.xinyue.icu/Article/details/gthikahvqd.html

a ?? b
来源：http://dali.aibaodan.cn/Article/details/gtdtsauoul.html

[U87] JS：解构默认值
来源：http://dali.redwolf501.top/Article/details/gtiqrilgnn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gtexuzfnap.html

[U88] JS：对象展开合并
来源：http://dali.gotoacloud.top/Article/details/gttfqnoida.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtjuqbhnei.html

[U89] JS：数组去重
来源：http://dali.ydzc1.top/Article/details/gtcsmknvka.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtgkumgkqh.html

[U90] JS：数字数组排序
来源：http://dali.zhixingplan.top/Article/details/gtlrlhnfkc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtbejskjtt.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gthbruagml.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnxiangtu.top/Article/details/gtxeerwhmn.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtffpuqbry.html

structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtneuahnpj.html

[U93] JS：模板字符串
来源：http://dali.snrcjt.cn/Article/details/gtiwqvzdvj.html

`共 ${n} 条`
来源：http://dali.jinqigfzy.top/Article/details/gtnyznxoef.html

[U94] JS：箭头函数
来源：http://dali.yj20258.top/Article/details/gtcfuggzej.html

const double = x => x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gthmnhjzzw.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gtqsetxqgj.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtvktdhnyp.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258.top/Article/details/gthigcxenr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gttqxsugnc.html

[U97] JS：并发请求
来源：http://dali.9152youxi.cn/Article/details/gthomnikiz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtfurzdzlo.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtptrlzsiv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.kuanghao11.cn/Article/details/gtilawwngz.html

[U99] JS：事件监听
来源：http://dali.yanxiufei.cn/Article/details/gtymwawbcd.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gtarxybqyf.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gtfyzffrhx.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gtmqyrrfzl.html

[U101] JS：classList 操作
来源：http://dali.jinqigufen.top/Article/details/gtcqssscsh.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gtqtzlxiqd.html

[U102] JS：本地存储
来源：http://dali.jinqigufen.top/Article/details/gtuphtnhji.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gtbquugfwj.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gtpxjyelbi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtdvlmvdqi.html

[U104] JS：防抖
来源：http://dali.xziqi.cn/Article/details/gtkkegazmh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtjixasvnj.html

[U105] JS：节流
来源：http://dali.jyoumei.cn/Article/details/gtwoieybjb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xziqi.cn/Article/details/gtgxrexrea.html

[U106] JS：日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtpkdqmzdn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdkgohax.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtzdyisfpv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtsekxfowf.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtmfudtpyt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gtxxnlrzmc.html

[U109] JS：数组分组
来源：http://dali.yongpay.top/Article/details/gtulmhbrnh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtoyhsdmso.html

[U110] JS：数组分块
来源：http://dali.cashguo.top/Article/details/gtwgcocmzf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gttmiykevu.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gthycwmtie.html

new Map(Object.entries(obj))
来源：http://dali.ydzc1.top/Article/details/gtbisryulv.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gttwqufbee.html

"7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtbhdjwmhz.html

[U113] JS：正则替换全部
来源：http://dali.nwbrower.top/Article/details/gtxdrwgdol.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtkpjysrju.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gtukymgslk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtgbqffmuw.html

[U115] JS：生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgzcyikh.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtenfxmsew.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gtcytgnrqr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hywenlv.cn/Article/details/gtipvvpugh.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxjjlqqm.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gtiklixvgd.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gtyaxpvajm.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwpqxvvk.html

[U119] JS：生产构建
来源：http://dali.jinqigufen.top/Article/details/gtuxfjxzmc.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gtwgvteosn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gthothlkiy.html

import.meta.env.VITE_API_URL
来源：http://dali.bjfxy.top/Article/details/gtrpohllzl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtldyuxsvp.html

统计汇总
来源：http://dali.jianghu66.top/Article/details/gtwpnbtscj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqpktlkva.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiixaalx.html

Python ......... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvxgioym.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtcsiuoajf.html

JavaScript ..... 252
来源：http://dali.chenlongwang.top/Article/details/gtnzdshjwo.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gtritlfnrl.html

Java ........... 212
来源：http://dali.smart0.xyz/Article/details/gtvjfpwrze.html

Go ............. 212
来源：http://dali.316326.xyz/Article/details/gttmqypplb.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtfulceegg.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtntqzzreo.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtyxnjeetd.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtllbgfggy.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtgurcfruc.html

Bash ........... 80
来源：http://dali.zycfv.cn/Article/details/gtxlhbhhui.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyfiqgzs.html

Swift .......... 15
来源：http://dali.jianghu66.top/Article/details/gtnwxykrkz.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gtvrrcykgc.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtgsrluvou.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gtthaslyqc.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtwiyuudui.html

合计 ........... 2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtsjyrbcow.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gtbzpxyqbe.html


<!-- 参考信息 -->