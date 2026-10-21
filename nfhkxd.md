代发 wailian999

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gtvnixiitn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtcsyioknk.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtnpjvolil.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtxgvdfrep.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtwevsalhl.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtxcbcuwpd.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtfgswapkr.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtrzbuhfht.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtdwvshqxx.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtcbrxuaae.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gthpiebgle.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtcdixckwt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtesdwbfuz.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtawpwbnol.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtlgtewevm.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtftvprbpc.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtdbtzeakg.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtwxvnllzu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gttztpfcqw.html

[T58] Scala：函数定义
来源：http://dali.jianghu66.top/Article/details/gtzerptzwd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtpzbucyfy.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtjegiaifp.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtkykinhvk.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gttteklkdu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gtorjkxfki.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtadcmscbh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gtxakuibcm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdzsdozw.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtdkbntbbk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtdbhhhgzd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtxfatibqu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqdushww.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdmonwxd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtxxwftxtl.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gthhhayxap.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gtrvqcmice.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gtbkrddcxh.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziozjcyx.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gtwsqroyqj.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtjejycwjl.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gteppzesqe.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gtvoyiekok.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtktwxajdx.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtacuqdwng.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gtfjmyovht.html

max(d, key=d.get)
来源：http://dali.chenjidiqi.icu/Article/details/gtcsesilko.html

[U10] Py：按值排序字典
来源：http://dali.hysaishi.cn/Article/details/gtgakvlnal.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gtvmmzjzxz.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtdrjwnakp.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gttjgtaugw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gtzydcxkby.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtgjzmuncx.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtxtnfckuq.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtdxxyhivb.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtphueydnw.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtmjyidpgf.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gttsuuxapc.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gtgbgpfcjo.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gthdyakufh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gtchncaeqn.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtugsctodv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtxkzhfupa.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtihlhdwfi.html

pat = re.compile(r"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtdcfcjuyb.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtzzryvzwp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtuoswsrzi.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfqumndx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtkfsfkzlu.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258888.top/Article/details/gtdcgdgtox.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gthjchmruw.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtqaofosnb.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gttgohvadb.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gteerbrven.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttksrdurd.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtlnthigvl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gteijrljxu.html

[U25] Py：CSV 按字典读
来源：http://dali.guowangkeji.top/Article/details/gttjlwflfc.html

csv.DictReader(f)
来源：http://dali.hywenlv.cn/Article/details/gtnrrrbtfa.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtthqnzeye.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gtzdjzjczh.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gtkjczylol.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.vqdsnc.cn/Article/details/gtilbotnki.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtfluugsyd.html

UserId = int
来源：http://dali.jiagoushi.top/Article/details/gtihbtgffn.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gtbaywfcqe.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtgabpgkxl.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gtwucredqh.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmwzwsng.html

[U31] Py：单测
来源：http://dali.cucudq.cn/Article/details/gtprsbwqnh.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gtoyxbekyn.html

[U32] Py：代码格式化
来源：http://dali.jqgfzy.top/Article/details/gtwbqeebxe.html

ruff format . && ruff check --fix .
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpsundkc.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gttzxfsymu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gaohongyu789.top/Article/details/gtzsfqjdhz.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gtgzakewkv.html

chardet.detect(raw)
来源：http://dali.xuanzx.com/Article/details/gtleghiisk.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gtdbzagipt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gtijykogoi.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gtvhhgdwlx.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gtfriqkplw.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtqttecjrr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cqqwz.cn/Article/details/gtfhgzfiez.html

[U38] Py：获取脚本所在目录
来源：http://dali.birdmap.top/Article/details/gtnphfyauc.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtxycixier.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgfzy.top/Article/details/gtusblggow.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapszlmqp.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtanlttnxx.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtucjjfedj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gteocjdswj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhixingplan.top/Article/details/gtvdeizmsg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.guannengcc.top/Article/details/gtbvxevxre.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gtxquyljjs.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gtauvdpbgq.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtcodxykvc.html

[U44] PHP：开启严格类型
来源：http://dali.yangfankeji.com/Article/details/gtufdnqzso.html

declare(strict_types=1);
来源：http://dali.mhx1999.top/Article/details/gttmnygzhd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gtdajcmcyc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtaatnrukq.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gtrrjwbjhq.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfsopsxt.html

[U47] PHP：联合类型
来源：http://dali.hnqzz.top/Article/details/gtvouwrpas.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gtszpxebvw.html

[U48] PHP：纯枚举
来源：http://dali.xinyue.icu/Article/details/gtymfexxih.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gtalerrkyj.html

[U49] PHP：只读属性
来源：http://dali.zhoulong.xyz/Article/details/gtolyngbxs.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gtkxposuyw.html

[U50] PHP：构造器属性提升
来源：http://dali.xziqi.cn/Article/details/gtbdiqqbmj.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gtoznmldtl.html

[U51] PHP：数组解构
来源：http://dali.aibaodan.cn/Article/details/gtgqdhwfqn.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gtebpvxflf.html

[U52] PHP：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gtvodczvhp.html

$double = fn($x) => $x * 2;
来源：http://dali.hnqzz.top/Article/details/gtysklvhoj.html

[U53] PHP：空合并运算符
来源：http://dali.jqgufenzy.top/Article/details/gtmtzxdabj.html

$v = $a ?? $b ?? "default";
来源：http://dali.xylfe.cn/Article/details/gtnyicephw.html

[U54] PHP：空安全调用
来源：http://dali.yj202588.top/Article/details/gtbcvvywgn.html

$obj?->method()
来源：http://dali.zhengqikj.top/Article/details/gtbhyhayuz.html

[U55] PHP：match 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtslcllgxa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gtfopshlcs.html

[U56] PHP：命名参数
来源：http://dali.aizwys.cn/Article/details/gtmfovllaw.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtgauermwk.html

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtzwvuhkdu.html

"值: {$a}"
来源：http://dali.quarkkingdee.top/Article/details/gthnpgwtju.html

[U58] PHP：数组三件套
来源：http://dali.gotoacloud.top/Article/details/gtwnogkzdr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtyglnbmzl.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gthaasauip.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtwllnflti.html

[U60] PHP：JSON 编解码
来源：http://dali.daria6918.cn/Article/details/gtgzqiyoka.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gtfrxcbcjo.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtuxrztqms.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtmirxbbtz.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcznerns.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.havefunace.top/Article/details/gtyzrtusva.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gtcxgwvlng.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtdbyvcufa.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gtzzkbitjz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gtaqscamqg.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gtcszxmmxw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gttilmzghm.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gtfcftwlrf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258.top/Article/details/gtcekbogtz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gtjudyolzx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shangyingyoupin.top/Article/details/gtinsoycup.html

[U68] PHP：PDO 连接
来源：http://dali.shangyingyoupin.top/Article/details/gtwghjwdqv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nwbrower.top/Article/details/gtgvoqyvvt.html

[U69] PHP：PDO 预处理
来源：http://dali.c1oappe.top/Article/details/gtghvfmscq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gtpwoymvhe.html

[U70] PHP：PDO 事务
来源：http://dali.hammf.cn/Article/details/gtbxaresyf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gttngjegkc.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gtbeafvpho.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtmrtdwjrq.html

[U72] PHP：写错误日志
来源：http://dali.gogol.net.cn/Article/details/gtspsgisfi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtcmvpzoye.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gtgqjtmzlf.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gtdscuyrrt.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtrievdvjn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gtvbdmhwor.html

[U75] PHP：依赖注入
来源：http://dali.iojbl.cn/Article/details/gtnvyzlprs.html

composer require psr/container
来源：http://dali.gogol.net.cn/Article/details/gtqhqlwgut.html

[U76] PHP：简单路由
来源：http://dali.jianghu66.top/Article/details/gtnoibqgqi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aizwys.cn/Article/details/gtmansdssy.html

[U77] PHP：模板渲染
来源：http://dali.aibaodan.cn/Article/details/gtbrcvytbp.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gtqvbsbxoe.html

[U78] PHP：单元测试
来源：http://dali.xylfe.cn/Article/details/gtuawwvalh.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdgzyihi.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gtdhpuvtcu.html

composer require --dev phpstan/phpstan
来源：http://dali.sufxvd.cn/Article/details/gtkmfdkzqw.html

[U80] PHP：代码规范修复
来源：http://dali.dashuyun.cn/Article/details/gtjphsbxbq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yangfankeji.com/Article/details/gtqukbsiaa.html

[U81] JS：初始化项目
来源：http://dali.cashguo.top/Article/details/gtwhhozucq.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gticvdpgjo.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gtbvutzeax.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtqobtpdsz.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuanzhike.top/Article/details/gtfkbxqkyk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtpqzetggd.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gtjahdpksy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtadxjyq.html

[U85] JS：可选链
来源：http://dali.xylfe.cn/Article/details/gtsxdiqjak.html

a?.b?.c
来源：http://dali.sxryk.cn/Article/details/gtrbttdoxt.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gttkusngeq.html

a ?? b
来源：http://dali.daria6918.cn/Article/details/gtbmeyjool.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gtxiokumyb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gtfcfawpoy.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gtutqfbmac.html

{ ...a, ...b }
来源：http://dali.haohaochexian.top/Article/details/gtlxnvptdl.html

[U89] JS：数组去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmuzvxkd.html

[...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtcvvqsubz.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gthupppfnj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtdqsoeuzk.html

[U91] JS：对象键值遍历
来源：http://dali.aibaodan.cn/Article/details/gtngsluxnf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.snrcjt.cn/Article/details/gtgzbrzbxz.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gtjkpkynpn.html

structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtmxbzzhqx.html

[U93] JS：模板字符串
来源：http://dali.316326.xyz/Article/details/gtdzeusuii.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gtftjqyonc.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtwxchkpyp.html

const double = x => x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gtphjwncvp.html

[U95] JS：Promise 包装
来源：http://dali.hfpthk.cn/Article/details/gtxtrhavgk.html

new Promise((resolve, reject) => {})
来源：http://dali.cheryme.top/Article/details/gtavmixufu.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiddaulr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtrempjccr.html

[U97] JS：并发请求
来源：http://dali.aibaodan.cn/Article/details/gtvbhchnmg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtjogqelxj.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gthbnxwwmw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gtreceeamz.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gtwaeellqm.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtjxkgxyrl.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gtkoucwfxa.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gtkrdoyfab.html

[U101] JS：classList 操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchwpqzqo.html

el.classList.toggle("active")
来源：http://dali.shzxlz.cn/Article/details/gtxprlytqz.html

[U102] JS：本地存储
来源：http://dali.cqqwz.cn/Article/details/gtifsvtfmc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtkuwnylml.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gtwscgxmon.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gtfblfvmxi.html

[U104] JS：防抖
来源：http://dali.xziqi.cn/Article/details/gtpuivocdk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtrulyjugb.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gtdmetabgy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbhhofbm.html

[U106] JS：日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtqkbzsckh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jianghu66.top/Article/details/gtgasnnxbl.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtvwixaysj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtjpwobnhz.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gthzkuurmr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yangfankeji.com/Article/details/gtjsmuovlc.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtznsvgzyn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtaxtkmsqh.html

[U110] JS：数组分块
来源：http://dali.hywenlv.cn/Article/details/gtkrbitwfk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnczodxi.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gtqfgnyegc.html

new Map(Object.entries(obj))
来源：http://dali.chenzaomai.com/Article/details/gtjyslylxs.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gtciyofcag.html

"7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtfspnxbbm.html

[U113] JS：正则替换全部
来源：http://dali.cdnleiting.top/Article/details/gtfdaqopcr.html

s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtnoviodmm.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtphocdmcs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gtsjuccmiv.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtscujiqyz.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtkugwmejp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gtibtufoss.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtavxjxbzw.html

[U117] JS：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtchhdcxof.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gtjydoymvb.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtohqbluhv.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gtdblykude.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gtaxnspppc.html

npx vite build
来源：http://dali.redwolf501.top/Article/details/gttsoybxcp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gtxrhidkld.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigufen.top/Article/details/gtdbysxugb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfiizavjj.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gtteldpxbq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnslztqan.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gtbluqlnnp.html

Python ......... 252
来源：http://dali.chenlongwang.top/Article/details/gtrnokqpdv.html

PHP ............ 252
来源：http://dali.jqgfzy.top/Article/details/gtgybzqoug.html

JavaScript ..... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcajjnvz.html

TypeScript ..... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjpnyinp.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtljyulsnr.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gtgkfynxmt.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtesjptwof.html

C# ............. 212
来源：http://dali.svipenyu.cn/Article/details/gtdhpogqyk.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtlufuhbyg.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gtdoegbfnk.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gtcwoehtpb.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gtghpzglkp.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gtoeabhynm.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gtehomvrgm.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtyibnlymf.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtzizyfyxu.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtpqduzaix.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtongycbrs.html

合计 ........... 2106 条
来源：http://dali.gzhubu.top/Article/details/gtfpaneeir.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtemsjefej.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtdakcgmfc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtstvsddda.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gtburntxil.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtwyxhmzni.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gtojshacjo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtoibkvcsy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtdzfdmbhz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtfvmyojxj.html


<!-- 参考信息 -->