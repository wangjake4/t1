代发 wailian999

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtgdgcdcxg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtwmbyhoty.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtewhnawol.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gtmwcemwhv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtpfeqfwce.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtlqofmnuq.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtzdadhqjg.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gthsdvhgth.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gtkdyycnqc.html

[T53] Scala：字符串插值
来源：http://dali.yj20258.top/Article/details/gtxdqcxnnl.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmqmbase.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtgcwxsbwc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gtohusrany.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtczcgfasw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtkjtglwaa.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtjdosxewb.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtxwadkcad.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtumwrztud.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gtudxyrwgy.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gtlrqyrpzf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtoxhoujog.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtwuhrdfur.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtzqmjzrzh.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtfjdtrnoh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gtvupbfizh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtilajrhzj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtogjjqecy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdenpntcd.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gtjskcgqqr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtsmrvvbgg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzofwvftx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gtwfihonwn.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtpsdqlhwu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gtnlnbmwab.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtndcaawul.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtgkkffihb.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtwnoqkaxz.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gthbcgftmr.html

[U06] Py：合并两个字典
来源：http://dali.snrcjt.cn/Article/details/gtltpgzjns.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gtpmsmeudj.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gtkabxnkvm.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtvwvjxugd.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gtvgzlbmtg.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtfyeuiuka.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtorhsglpm.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtzynqjbee.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gttoxaqswi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gtupcproyf.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gtodeyfpum.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gtgdgqtltc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtnnvolsjw.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtaeirotsv.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gtloqhfpkc.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gtfahsycyo.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gtmuyuundi.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gtwagyppjm.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtfckmvnus.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gtlapfldxb.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtpnqcecez.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkmglfph.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gtjcgouftd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gtxosltgkt.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtcvniprrw.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtoqdoutps.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtfbyksbsq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gteuevfuje.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gttsfexskr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangdashe.top/Article/details/gtkpwkncxg.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gtsbcysuoc.html

@contextlib.contextmanager
来源：http://dali.yuanzhike.top/Article/details/gtyadlibfr.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gthqxcjpxr.html

list(zip(*m))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlaednwz.html

[U23] Py：分块读取大文件
来源：http://dali.yangfankeji.com/Article/details/gtutnkpduv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtqzqnqnja.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gthowyqfnz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtmsxzemfj.html

[U25] Py：CSV 按字典读
来源：http://dali.svipenyu.cn/Article/details/gtcdxnucli.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gtjbygtujo.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpjljoro.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfbiebiq.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gttdyaidjv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guannengcc.top/Article/details/gtvydppepi.html

[U28] Py：类型别名
来源：http://dali.hnqzz.top/Article/details/gtqbevsrdd.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtimcalcpg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtbwszrkve.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gtctbepuhd.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtrhfdedeq.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gtygfhsout.html

[U31] Py：单测
来源：http://dali.yj202588.top/Article/details/gtguyewgrf.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gtjtapkmwz.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gttntvgvfv.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gtpwfxpccn.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gtwkhmtoml.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gtpbxxavmm.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtiujnubvo.html

chardet.detect(raw)
来源：http://dali.ydzc1.top/Article/details/gtydbaazfu.html

[U35] Py：发送邮件
来源：http://dali.jqgufenzy.top/Article/details/gthvcbjksx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gtbftbngux.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gthcaazwqm.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gtghpmpjwt.html

[U37] Py：读写 Excel
来源：http://dali.wangshuangyany.cn/Article/details/gtictohexf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gtlooobgbw.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gtxdzlwbwr.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gtcqcrlwxe.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsvnpuou.html

sys.stdout.isatty()
来源：http://dali.sweek.top/Article/details/gtvzghyxma.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gtpuxpahsu.html

print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtntbrwdxu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gtezkqfjkl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gtceuomuso.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gtlkcfxnwk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhvjujno.html

[U43] PHP：声明命名空间
来源：http://dali.yangfankeji.com/Article/details/gtzwlhuura.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gtkvkptfvw.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gtxckcglcg.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtxdpxpzdq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gtbqhbfiyf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtndtyrrfb.html

[U46] PHP：可空类型
来源：http://dali.cucudq.cn/Article/details/gtthhzalac.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtdtvgyosj.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gtwoolyunh.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtkwqewain.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gtsalxxkgl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gtgoshjppj.html

[U49] PHP：只读属性
来源：http://dali.zycfv.cn/Article/details/gtdwnbeemj.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthlcrsnu.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtsvvilajz.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gtadfbkgjs.html

[U51] PHP：数组解构
来源：http://dali.zhiwuduotai.top/Article/details/gtpafyzpxp.html

[$a, $b] = $arr;
来源：http://dali.yuxming.cn/Article/details/gtcjlwjajc.html

[U52] PHP：箭头函数
来源：http://dali.yongpay.top/Article/details/gtnaavvzjf.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtcojoezyl.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtspwfgckm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gtiekotiyc.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtheixiihp.html

$obj?->method()
来源：http://dali.hfpthk.cn/Article/details/gtmaxmkupn.html

[U55] PHP：match 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtlyxjuatj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtsbnklcay.html

[U56] PHP：命名参数
来源：http://dali.tianlin.xyz/Article/details/gtuvbeffrh.html

f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtliibzpbo.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gtzeeiioir.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gtrawoghei.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtpbdkuhqu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiasrzxgm.html

[U59] PHP：自定义排序
来源：http://dali.yj20258888.top/Article/details/gtzwdwjltg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtbloviyld.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gtqdjapnhf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cdnleiting.top/Article/details/gtqzcunyyh.html

[U61] PHP：正则
来源：http://dali.xuanzx.com/Article/details/gtockcjoow.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtwxpveqcx.html

[U62] PHP：日期对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqggzevv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtpdxxmfon.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gtzbdqpvky.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yongpay.top/Article/details/gtmzoyamod.html

[U64] PHP：目录遍历
来源：http://dali.xinyue.icu/Article/details/gtwvkcbhwa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gtjlzvulxn.html

[U65] PHP：会话
来源：http://dali.shuidangran.top/Article/details/gtjmtbvzrm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtevbdrkwt.html

[U66] PHP：设置 Cookie
来源：http://dali.pengpengdd.cyou/Article/details/gtuwuhqgvm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xylfe.cn/Article/details/gtzndtuwdn.html

[U67] PHP：处理文件上传
来源：http://dali.zhoulong.xyz/Article/details/gteytqqmmn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shangyingyoupin.top/Article/details/gtuowmpezc.html

[U68] PHP：PDO 连接
来源：http://dali.svipenyu.cn/Article/details/gtfsvrflpb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtskfnzbta.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoubeziq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nwbrower.top/Article/details/gtztizosuf.html

[U70] PHP：PDO 事务
来源：http://dali.jiagoushi.top/Article/details/gttbpnrsjp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yanxiufei.cn/Article/details/gtophpxwyt.html

[U71] PHP：抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtuxikibwi.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gtfzxwetjh.html

[U72] PHP：写错误日志
来源：http://dali.hnqzz.top/Article/details/gtkinlanzt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gtoxdrlwvw.html

[U73] PHP：读取 ini 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtlkpuxfgu.html

parse_ini_file("config.ini", true)
来源：http://dali.vqdsnc.cn/Article/details/gttgxxkagv.html

[U74] PHP：读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtxofrhouv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphczbuml.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gtbcrqtwqg.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqsbeoiw.html

[U76] PHP：简单路由
来源：http://dali.feifeiyinyue.top/Article/details/gtptcveahr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jyoumei.cn/Article/details/gtmtbrlqqw.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gtpsrwixrr.html

composer require twig/twig
来源：http://dali.yanxiufei.cn/Article/details/gtsarkxuwh.html

[U78] PHP：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gthnhgaqjl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gtzhckpjnq.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gtvetjfety.html

composer require --dev phpstan/phpstan
来源：http://dali.xziqi.cn/Article/details/gtssvcsftl.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtmwdnyild.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aibaodan.cn/Article/details/gttdapkhra.html

[U81] JS：初始化项目
来源：http://dali.zhixingplan.top/Article/details/gtfgsnxvgt.html

npm init -y;  npm i express
来源：http://dali.hnqzz.top/Article/details/gttekjajgr.html

[U82] JS：package.json 脚本
来源：http://dali.svipenyu.cn/Article/details/gtyulqlack.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jlsjyb.cn/Article/details/gtibsrtoiu.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgufenzy.top/Article/details/gtzcbcxvgb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtcanxzvga.html

[U84] JS：CommonJS 写法
来源：http://dali.yuanzhike.top/Article/details/gtdljgrjoa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gttrqyuscc.html

[U85] JS：可选链
来源：http://dali.tianlin.xyz/Article/details/gtlrczpvrz.html

a?.b?.c
来源：http://dali.ydzc1.top/Article/details/gtlhadmghq.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gtblzsdxzp.html

a ?? b
来源：http://dali.shangyingyoupin.top/Article/details/gtqfblyyde.html

[U87] JS：解构默认值
来源：http://dali.cqqwz.cn/Article/details/gtmwpadejy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gtdtqzlvuy.html

[U88] JS：对象展开合并
来源：http://dali.wangshuangyany.cn/Article/details/gtgfklbcxh.html

{ ...a, ...b }
来源：http://dali.ydzc1.top/Article/details/gthhepgits.html

[U89] JS：数组去重
来源：http://dali.gzhubu.top/Article/details/gtpbwurbqs.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtiadolppx.html

[U90] JS：数字数组排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduubpvvz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakfxtsgq.html

[U91] JS：对象键值遍历
来源：http://dali.daxiang520.top/Article/details/gtykoebfhq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ppjwa.cn/Article/details/gtqkaxbzeb.html

[U92] JS：深拷贝
来源：http://dali.chenzaomai.com/Article/details/gtvyrtputk.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtvrfdoekd.html

[U93] JS：模板字符串
来源：http://dali.ehwqpu.com/Article/details/gtgmcbikpk.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtgygcrzqy.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtzapdlnfx.html

const double = x => x * 2;
来源：http://dali.redwolf501.top/Article/details/gtvcsiveze.html

[U95] JS：Promise 包装
来源：http://dali.zhengqikj.top/Article/details/gtoahybblq.html

new Promise((resolve, reject) => {})
来源：http://dali.havefunace.top/Article/details/gtomzxuxxx.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gtzjjjbopu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtsuqmdebe.html

[U97] JS：并发请求
来源：http://dali.ivvv.top/Article/details/gtocayriyz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtoktnukpz.html

[U98] JS：fetch 带 JSON
来源：http://dali.svipenyu.cn/Article/details/gtnwrfltnp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xziqi.cn/Article/details/gtqmkfzbas.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gthmftxvms.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gtnrgwghyr.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gtaksphhkz.html

document.querySelector(".item")
来源：http://dali.havefunace.top/Article/details/gtehynzjbj.html

[U101] JS：classList 操作
来源：http://dali.wangdashe.top/Article/details/gtfpzavcxs.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gtyvsuvzhn.html

[U102] JS：本地存储
来源：http://dali.jlsjyb.cn/Article/details/gtuimdjtfa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gtsxkcquez.html

[U103] JS：定时器
来源：http://dali.tanke756.top/Article/details/gthaadxsrr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzojudgvu.html

[U104] JS：防抖
来源：http://dali.zhoulong.xyz/Article/details/gtsyqhevue.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtjcaqktvu.html

[U105] JS：节流
来源：http://dali.yanxiufei.cn/Article/details/gttlkqepbv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gtcngmxcqs.html

[U106] JS：日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtjmzqedjf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtwshxnlkn.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtmwsunxqb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtrakrivuj.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gtjswkyczj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtlkjibwyq.html

[U109] JS：数组分组
来源：http://dali.shuidangran.top/Article/details/gtzynsebxe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtwzqxqmmt.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gtyfrqpgra.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ydzc1.top/Article/details/gtjanvjlhw.html

[U111] JS：对象转 Map
来源：http://dali.shuidangran.top/Article/details/gtupqnsond.html

new Map(Object.entries(obj))
来源：http://dali.havefunace.top/Article/details/gtsyzvsbfu.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gtkfbkjlzf.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtuytzdpyd.html

[U113] JS：正则替换全部
来源：http://dali.hammf.cn/Article/details/gttvzumwwq.html

s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gteaanhwom.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gtyrnlgrsu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtvoanjcbi.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtqvltumsz.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtgooxngyr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gtybxuqvcx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gtscnqwqog.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gttmmccpkf.html

npm i -D vitest;  npx vitest
来源：http://dali.chenzaomai.com/Article/details/gtwapgyred.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gtsasmnhqn.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtchfpreoi.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gtpcgyrqwa.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gtpduffsxu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.iojbl.cn/Article/details/gtoansddim.html

import.meta.env.VITE_API_URL
来源：http://dali.yueranfly.top/Article/details/gtawrxvliw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxqobgrdg.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gtwkjaktiu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdzctklb.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gtjpbavrzp.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gtngychrvb.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gtlytqbelc.html

JavaScript ..... 252
来源：http://dali.zhixingplan.top/Article/details/gtufcotxtd.html

TypeScript ..... 212
来源：http://dali.vqdsnc.cn/Article/details/gtaekowgwk.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtttnpqkyw.html

Go ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrohxsqym.html

Ruby ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtugysuyts.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtnrraytey.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gtbpynkbvb.html

C++ ............ 30
来源：http://dali.xinyue.icu/Article/details/gtoazxeppi.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtxdbclxuy.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtpymkjlvm.html

Kotlin ......... 15
来源：http://dali.316326.xyz/Article/details/gtxolnydse.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gtzfwhzbms.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtztcemgjp.html

Perl ........... 10
来源：http://dali.quarkkingdee.top/Article/details/gtfxwsvtwv.html

Scala .......... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtdddyqawl.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtxlhgzyaq.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gtxzlwdfcq.html

按章节统计：
来源：http://dali.zycfv.cn/Article/details/gtfndtztbb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gthgtevazs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfjinefa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtjkeupzxd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtjcvmfssx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gtlffpnvyi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gtvntkidfa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtwettkrpc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtruvcylsu.html


<!-- 参考信息 -->