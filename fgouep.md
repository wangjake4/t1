代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtpogyvtsp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtcgnvdkwy.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gtsptatymy.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gthbwluzkp.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmcvybar.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxhfozrj.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gthjiizvjg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtqglrnxvq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtgnwqabgc.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtrsqmiwts.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtadikdlye.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gttbqefygv.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gthqwbzgek.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtnyyhveyg.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtutrgunhg.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gthsanvdps.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gtdyedxzvo.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gttjrakmyt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttedudmil.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gtubnpsmdy.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtnheeksti.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtvgejafvu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gthqpeixfu.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtcndldntf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtdmunvvid.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gtaqetmprq.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtxivprikc.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtpusauyob.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtuflzpkcp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsgcccdqy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtwjwlbbar.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgqjtsvia.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gtqhkswjyc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtrdxtihan.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtkavpaldh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtexqhjboi.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gtyprhkhay.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtyoixratj.html

[U04] Py：变量调试打印
来源：http://dali.guowangkeji.top/Article/details/gtgjtnwiei.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmldcvrk.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gtewientpi.html

list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtylfoikbr.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gtccszcqqb.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtocdljdbt.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gtloqsnsga.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtkwxtbbad.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gtjwhzhcwz.html

[y for x in nested for y in x]
来源：http://dali.ehwqpu.com/Article/details/gthytskpoh.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gtxhmykmww.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gtzzcobanc.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gtzcirqkdo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtmqtnrjom.html

[U11] Py：生成器表达式
来源：http://dali.shuidangran.top/Article/details/gtytlkawyn.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtukgjfpsv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gtwnernwkp.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gthvmdekik.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtvzesshei.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtmutxrowb.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gtuwluengf.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gtwxjrifkj.html

[U15] Py：高精度计时
来源：http://dali.tian-w.cn/Article/details/gttwwkpooa.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtbinxxgbs.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gtcvrfzyvn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprkrwjsu.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtdrkegygc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gtscgxnqdp.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gtnjcvajaw.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gttkmlwgas.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnprmvna.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gtbcmrkxub.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gtyobsrwxs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizzsgnrz.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gtryfyoqae.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gtjxxfadbo.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gtgglplfsd.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gtdlezdbxe.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtjrnhupan.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtftobjypj.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gtdxgeprrr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtaztkheuu.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtlxjejige.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gttjnegfhe.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gtvwvibfvo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dashuyun.cn/Article/details/gtzpodpvow.html

[U27] Py：异步 HTTP
来源：http://dali.zhiwuduotai.top/Article/details/gtsmcvnnfo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.mhx1999.top/Article/details/gtjmlbjolc.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gtgsqeqjmh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gtytokpdql.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gtmpnzrboa.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gtrhzifxiw.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtlzbwxpmb.html

@dataclass(slots=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtejhzjpqx.html

[U31] Py：单测
来源：http://dali.fzhhl.top/Article/details/gtdlrrppiv.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtsqepkhci.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gtscmucdde.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtffdykygc.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gtlumooafc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gtiwoobkra.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gtvaqaofyt.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gtrhhpfvpm.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gtnkdtxyfh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gtrdenouio.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gtmebofprp.html

schedule.every(10).minutes.do(job)
来源：http://dali.pycfn.com/Article/details/gtvkefvwos.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gtvcwmgvxw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.mhx1999.top/Article/details/gtzplhpqso.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gtvvogbvjo.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gtsztgulsy.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gtktjvigys.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gtztrnwcfj.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gtcuunocgk.html

print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtxaoxphkt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ehwqpu.com/Article/details/gtyndldabf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrhfpdoi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gtiwxxsvwu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.9152youxi.cn/Article/details/gtjmtrmvpp.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzbbjkzq.html

namespace App\Http;
来源：http://dali.shzxlz.cn/Article/details/gtnhsacjpg.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtndvdferl.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gtpaqrjfea.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gtauchpwfo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtydyxlyrl.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtbzfvybpw.html

?string $name = null
来源：http://dali.shanyushiyangtech.top/Article/details/gtvehmchbf.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gtxihaepgh.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gtsapvvxzl.html

[U48] PHP：纯枚举
来源：http://dali.gaohongyu789.top/Article/details/gteqlxqula.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gzhubu.top/Article/details/gtdiihevar.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtxryktddo.html

public readonly string $name
来源：http://dali.tianlin.xyz/Article/details/gtgvcisnzb.html

[U50] PHP：构造器属性提升
来源：http://dali.birdmap.top/Article/details/gtrhmgwyhg.html

public function __construct(private int $id) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttkzyxsay.html

[U51] PHP：数组解构
来源：http://dali.hnxiangtu.top/Article/details/gtpqrpajhj.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtwbcukdie.html

[U52] PHP：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtrbngjlcm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gtfarwpyiu.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gtxtknenyx.html

$v = $a ?? $b ?? "default";
来源：http://dali.tianlin.xyz/Article/details/gtevpxxyjj.html

[U54] PHP：空安全调用
来源：http://dali.jianghu66.top/Article/details/gtoowszbcp.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gtwjiejesg.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gtcemkfepv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtqsfvccuz.html

[U56] PHP：命名参数
来源：http://dali.gotoacloud.top/Article/details/gtobkjbcao.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtvhjviikb.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtyyuwmsvh.html

"值: {$a}"
来源：http://dali.yj20258888.top/Article/details/gtillfgyui.html

[U58] PHP：数组三件套
来源：http://dali.hnxiangtu.top/Article/details/gtjsboizlr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdaahalc.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gthugfhncs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gtwkudvhxb.html

[U60] PHP：JSON 编解码
来源：http://dali.jyoumei.cn/Article/details/gtiizkhkhz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gtvoirsbid.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gtveujbjhl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtvlhthilu.html

[U62] PHP：日期对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvdkglma.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gtntjwawsw.html

[U63] PHP：文件读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghrczbhe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shuidangran.top/Article/details/gtsvhwsyft.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gtdisdzhqo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hammf.cn/Article/details/gtdmqiqqcr.html

[U65] PHP：会话
来源：http://dali.xuanzx.com/Article/details/gtzuqxobpz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtpwfcfyia.html

[U66] PHP：设置 Cookie
来源：http://dali.gogol.net.cn/Article/details/gthfnsathk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtvfrjaane.html

[U67] PHP：处理文件上传
来源：http://dali.xylfe.cn/Article/details/gtmeimsziw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sxryk.cn/Article/details/gtqvgfxbzs.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gticojihnc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gtbhoxcyrr.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtawgohghp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shzxlz.cn/Article/details/gtinxmvkec.html

[U70] PHP：PDO 事务
来源：http://dali.wangshuangyany.cn/Article/details/gtkobxcefu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrdsevbp.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtxbillyly.html

throw new RuntimeException("失败", 500);
来源：http://dali.shzxlz.cn/Article/details/gtbzeipamj.html

[U72] PHP：写错误日志
来源：http://dali.cashguo.top/Article/details/gtgdlseksr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangshuangyany.cn/Article/details/gtaauxhmit.html

[U73] PHP：读取 ini 配置
来源：http://dali.guannengcc.top/Article/details/gtqttlvunf.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gtuekynjeq.html

[U74] PHP：读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtfrzzpuqu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.haohaochexian.top/Article/details/gtgqzhduyp.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtxvdimkgg.html

composer require psr/container
来源：http://dali.zhengqikj.top/Article/details/gtlusdygve.html

[U76] PHP：简单路由
来源：http://dali.jiagoushi.top/Article/details/gtjverlihd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ybcxt.top/Article/details/gtyjehritj.html

[U77] PHP：模板渲染
来源：http://dali.gotoacloud.top/Article/details/gtuonakywh.html

composer require twig/twig
来源：http://dali.meibo888.top/Article/details/gtbwmcfvfh.html

[U78] PHP：单元测试
来源：http://dali.316326.xyz/Article/details/gtqugniqnq.html

composer require --dev phpunit/phpunit
来源：http://dali.bjfxy.top/Article/details/gtrnhwinob.html

[U79] PHP：静态分析
来源：http://dali.yuanzhike.top/Article/details/gtlvodrqpz.html

composer require --dev phpstan/phpstan
来源：http://dali.haohaochexian.top/Article/details/gtxahxydhe.html

[U80] PHP：代码规范修复
来源：http://dali.jqgfzy.top/Article/details/gtretizbya.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gtkrvaoxfg.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gthxxwpznw.html

npm init -y;  npm i express
来源：http://dali.zhixingplan.top/Article/details/gteovrdieg.html

[U82] JS：package.json 脚本
来源：http://dali.chenjidiqi.icu/Article/details/gtkzcniedk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daria6918.cn/Article/details/gtobvtqrjv.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gtjpkzxvlk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtsppvkczr.html

[U84] JS：CommonJS 写法
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgkrotan.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hfpthk.cn/Article/details/gtrbfrzozm.html

[U85] JS：可选链
来源：http://dali.iojbl.cn/Article/details/gtselavtac.html

a?.b?.c
来源：http://dali.quarkkingdee.top/Article/details/gtsrxdnhsj.html

[U86] JS：空值合并
来源：http://dali.c1oappe.top/Article/details/gtepnlzkhp.html

a ?? b
来源：http://dali.gzhubu.top/Article/details/gtmyqywdaz.html

[U87] JS：解构默认值
来源：http://dali.jlsjyb.cn/Article/details/gtsovdvlsc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dianchejie.cn/Article/details/gtkpozymcl.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gtoifonhrm.html

{ ...a, ...b }
来源：http://dali.hywenlv.cn/Article/details/gtfmebjgpu.html

[U89] JS：数组去重
来源：http://dali.chenlongwang.top/Article/details/gtyuzyvyab.html

[...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwffnrilm.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gtrszsromd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtakahiycl.html

[U91] JS：对象键值遍历
来源：http://dali.yongpay.top/Article/details/gtmndzpkng.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xylfe.cn/Article/details/gtylbzdtzo.html

[U92] JS：深拷贝
来源：http://dali.c1oappe.top/Article/details/gtplzdldaw.html

structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gttsfusqbm.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gtdspmvhup.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gtfoqewxlm.html

[U94] JS：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtvkobwgbn.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gtvfxbdmqv.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtshqcyltr.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gthwvhthnl.html

[U96] JS：async/await 与异常
来源：http://dali.guannengcc.top/Article/details/gtxtomjlew.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtapfyqmmz.html

[U97] JS：并发请求
来源：http://dali.aibaodan.cn/Article/details/gttpfuixsl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gttubclrql.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gtryqredgo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daria6918.cn/Article/details/gtrxbilqhi.html

[U99] JS：事件监听
来源：http://dali.chenzaomai.com/Article/details/gtakbkdlcd.html

el.addEventListener("click", e => {})
来源：http://dali.yvedp.cn/Article/details/gtuqiizgpd.html

[U100] JS：DOM 查询
来源：http://dali.yangfankeji.com/Article/details/gtxnoprjen.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gtifdtyazi.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaxptftn.html

el.classList.toggle("active")
来源：http://dali.wangshuangyany.cn/Article/details/gtcpzrkdzj.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gtnqbtegps.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrdkeukk.html

[U103] JS：定时器
来源：http://dali.aizwys.cn/Article/details/gtnukdqldk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmczxfqpf.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gtzbpthcqz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtrtylljyu.html

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gttiavzkui.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zycfv.cn/Article/details/gtnncidfba.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gthpoevqwp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gzhubu.top/Article/details/gtzmtxkvyz.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gtihxvcqpg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtvvzqenhg.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gtiyslknvn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gturciibxs.html

[U109] JS：数组分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvqsoybn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtufyethnr.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gtedngjvqc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258888.top/Article/details/gttktywpeb.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gtaszucult.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtcfzobrop.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gtfvzgpsgu.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtdqhkkcsg.html

[U113] JS：正则替换全部
来源：http://dali.chenzaomai.com/Article/details/gtzrvwfqhm.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtfnhhcjbt.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gtyuthkdmy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtdaflpjdv.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtzaudffwe.html

crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtsbiieatl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gtxmlnjarn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yangfankeji.com/Article/details/gtlglbbcfk.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gthbwmdfvv.html

npm i -D vitest;  npx vitest
来源：http://dali.jlsjyb.cn/Article/details/gthqqrnqof.html

[U118] JS：开发服务器
来源：http://dali.andypj.xyz/Article/details/gtqcijfyox.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gtngzkycce.html

[U119] JS：生产构建
来源：http://dali.dianchejie.cn/Article/details/gtskeqaunt.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gtckmbtitx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yongpay.top/Article/details/gthcludyth.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtfwjonmuw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvayxumzn.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtqbtpeeky.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtppxanlwc.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtbtxylkoi.html

Python ......... 252
来源：http://dali.daxiang520.top/Article/details/gtxefjihov.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gtotigvsur.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gtzaoikexd.html

TypeScript ..... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneajpyhu.html

Java ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtynhvrtwh.html

Go ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtedyrosje.html

Ruby ........... 212
来源：http://dali.smart0.xyz/Article/details/gttkbodskw.html

C# ............. 212
来源：http://dali.fengsongda.top/Article/details/gtgdbbiokt.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtzmhydhmt.html

C++ ............ 30
来源：http://dali.xylfe.cn/Article/details/gtautfrmlv.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gttimepoqd.html

Bash ........... 80
来源：http://dali.shuidangran.top/Article/details/gttmhwybdz.html

Kotlin ......... 15
来源：http://dali.jinqigufen.top/Article/details/gtgqwpycsl.html

Swift .......... 15
来源：http://dali.iojbl.cn/Article/details/gtuberwifc.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsjrdxdy.html

Perl ........... 10
来源：http://dali.hysaishi.cn/Article/details/gtjrnfxtri.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gtuwnfsyne.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtqidjkiwz.html

合计 ........... 2106 条
来源：http://dali.smart0.xyz/Article/details/gtsilagxju.html

按章节统计：
来源：http://dali.zhixingplan.top/Article/details/gtbhxfjkha.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtvfxzmwbj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtrsqebnht.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtbbeigcow.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtnkrlmfsp.html


<!-- 参考信息 -->