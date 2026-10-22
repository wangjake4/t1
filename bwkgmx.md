代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gt2swavtkxb.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2bjvgcxeg.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2viksfvfe.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gt2ztuiuymf.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gt2yfaooxlq.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2wpruzhrp.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnvtwogd.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gt2fcfujrdq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gt2llhtvlom.html

[T55] Scala：集合过滤
来源：http://dali.nwbrower.top/Article/details/gt2kjztlntg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebwpbyjk.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gt2edvbvbly.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2ynhpoemh.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwrajjxr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gt2zgdkypsk.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gt2joctqbfv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2eyixcgul.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gt2lrwffabl.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gt2emfqlqwq.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gt2vsgtixcw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwhbfrsf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2nogatxsg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2qoearbeu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nimzljye.html

[U01] Py：创建虚拟环境
来源：http://dali.xziqi.cn/Article/details/gt2ycnqmngh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gt2fugaadkk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gt2dyowhuzv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2illkketi.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigfzy.top/Article/details/gt2ziogjtae.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gt2rmszmnma.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gt2fbvclqcr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gt2cfnulnxo.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gt2fsclxtku.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2vuidcekj.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gt2drwljprc.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gt2rqupabfs.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gt2iwfqnmah.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigufen.top/Article/details/gt2ijdbictf.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gt2iimhzcoq.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gt2eplszqll.html

[U09] Py：字典取最大值的键
来源：http://dali.cdnleiting.top/Article/details/gt2avwrhkzy.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gt2kppbnsux.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gt2xfjxchxc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2yohyfuyj.html

[U11] Py：生成器表达式
来源：http://dali.jiagoushi.top/Article/details/gt2ltikzcil.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ypmgzxmz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqviezdi.html

Counter(arr).most_common(3)
来源：http://dali.jiagoushi.top/Article/details/gt2xowpuiiu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtquiika.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gt2jqvvekmz.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gt2ytceprop.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gt2awdeijcp.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gt2qvkdkpin.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnbiajyx.html

[U16] Py：命令行参数解析
来源：http://dali.aibaodan.cn/Article/details/gt2wngqfikl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gt2wwsuiqon.html

[U17] Py：初始化日志
来源：http://dali.jqgfzy.top/Article/details/gt2octtfyry.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gt2dsnuiorl.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrddarvy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdqykyn.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gt2yrjcyalt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gt2hgxrlexl.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gt2ojhqrfej.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gt2ppzawsdf.html

[U21] Py：自定义上下文管理器
来源：http://dali.gogol.net.cn/Article/details/gt2sgbpgcto.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gt2ckkmzpms.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gt2wmxoknpz.html

list(zip(*m))
来源：http://dali.nwbrower.top/Article/details/gt2gmpumvfi.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gt2omitdbvo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gt2akjakqat.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gt2lkkutzpj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gt2epyupzsy.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gt2wmknwxgx.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2katqsoxv.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gt2wgtxhmzg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gt2llngrtgr.html

[U27] Py：异步 HTTP
来源：http://dali.jqgufenzy.top/Article/details/gt2zfhkiaoq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gt2nvdfoxix.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gt2geuqpnap.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrhkytev.html

[U29] Py：属性校验
来源：http://dali.vqdsnc.cn/Article/details/gt2ymiuhigf.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gt2ngdrhche.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gt2rifanquq.html

@dataclass(slots=True)
来源：http://dali.birdmap.top/Article/details/gt2ivufwneo.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2iwfjvrup.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufugwldz.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gt2iwzdfnnu.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gt2icdqaupo.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gt2zghdfggo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gt2ydeurplb.html

[U34] Py：判断编码
来源：http://dali.gzhubu.top/Article/details/gt2qlytxwof.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gt2oxzukfas.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhyufwbd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gt2dqprcevh.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gt2frjytdjp.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gt2spxnqbzz.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gt2wiqdphie.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.meibo888.top/Article/details/gt2cownxcvo.html

[U38] Py：获取脚本所在目录
来源：http://dali.shuidangran.top/Article/details/gt2xkewohvt.html

Path(__file__).resolve().parent
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzowjqpt.html

[U39] Py：判断是否在交互环境
来源：http://dali.yangfankeji.com/Article/details/gt2dtbmqfit.html

sys.stdout.isatty()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fowgilnz.html

[U40] Py：打印到标准错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgavvyza.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gt2kfxiobkl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gt2nkvqdgzb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gt2vjggpkaw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gt2wafxvork.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gt2iciittbz.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gchhxdyq.html

namespace App\Http;
来源：http://dali.jinqigfzy.top/Article/details/gt2fmfzqxgv.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gt2xpvnsrpv.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gt2huwqnrcy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkybcskn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lebhkdar.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gt2hikbfnql.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gt2osiikwgl.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gt2kuggrisg.html

int|string $id
来源：http://dali.hysaishi.cn/Article/details/gt2xapvszrj.html

[U48] PHP：纯枚举
来源：http://dali.yuxming.cn/Article/details/gt2dwblmbiy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gijnqlcl.html

[U49] PHP：只读属性
来源：http://dali.zhixingplan.top/Article/details/gt2iutwdcpd.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljfyigym.html

[U50] PHP：构造器属性提升
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upiprghb.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gt2vhwwozsh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2urwkitzd.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gt2ifdcqvbb.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysehsluv.html

$double = fn($x) => $x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knsxozqi.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gt2qfzqeebo.html

$v = $a ?? $b ?? "default";
来源：http://dali.svipenyu.cn/Article/details/gt2zntuzfpk.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gt2ictlcspb.html

$obj?->method()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzjykuhv.html

[U55] PHP：match 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2hxstajmr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gt2eydmhbpo.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gt2rvnljntk.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzvihkju.html

[U57] PHP：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2ckfpybol.html

"值: {$a}"
来源：http://dali.yuanzhike.top/Article/details/gt2neqgswsq.html

[U58] PHP：数组三件套
来源：http://dali.hnxiangtu.top/Article/details/gt2rogdsmje.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gt2puxfefnd.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gt2bybtwuzl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2gwngadit.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gt2rvjxyafa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.andypj.xyz/Article/details/gt2evbqaqrw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfbuzqi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2mdelzdmz.html

[U62] PHP：日期对象
来源：http://dali.jlsjyb.cn/Article/details/gt2yjnduemq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cheryme.top/Article/details/gt2xruzuxgc.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gt2kuxxdggl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gt2oeovexnq.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gt2wfyjprvy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gt2igyjdldv.html

[U65] PHP：会话
来源：http://dali.dashuyun.cn/Article/details/gt2rkiaaxng.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2qpuszwlt.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gt2nmhfljbm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gt2wersysqn.html

[U67] PHP：处理文件上传
来源：http://dali.xuanzx.com/Article/details/gt2lzlsjkpy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daria6918.cn/Article/details/gt2iseokksn.html

[U68] PHP：PDO 连接
来源：http://dali.daxiang520.top/Article/details/gt2wlvvbcfa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhixingplan.top/Article/details/gt2tnfhxsbp.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gt2gsnxqyba.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuxming.cn/Article/details/gt2vmdaudcl.html

[U70] PHP：PDO 事务
来源：http://dali.cdnleiting.top/Article/details/gt2ypwyksbo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gt2hwkbbugd.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gt2zbtqtvwj.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gt2qwvjqqjz.html

[U72] PHP：写错误日志
来源：http://dali.ydzc1.top/Article/details/gt2hflospjd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gt2jkqdxjuv.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kugosglk.html

parse_ini_file("config.ini", true)
来源：http://dali.c1oappe.top/Article/details/gt2pzedxujb.html

[U74] PHP：读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lylcdiue.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yvedp.cn/Article/details/gt2onjsbtyl.html

[U75] PHP：依赖注入
来源：http://dali.yuxming.cn/Article/details/gt2gyuwetif.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2khpoflxy.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvuveqkm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gt2zzywqxuv.html

[U77] PHP：模板渲染
来源：http://dali.yuanzhike.top/Article/details/gt2ckcbyzal.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gt2hmrtauky.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gt2dbwctcdm.html

composer require --dev phpunit/phpunit
来源：http://dali.chenzaomai.com/Article/details/gt2fknbvfrv.html

[U79] PHP：静态分析
来源：http://dali.vqdsnc.cn/Article/details/gt2ybusthuw.html

composer require --dev phpstan/phpstan
来源：http://dali.kuanghao11.cn/Article/details/gt2xpjmiutn.html

[U80] PHP：代码规范修复
来源：http://dali.tanke756.top/Article/details/gt2lmczjwnh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenzaomai.com/Article/details/gt2hbbafqse.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gt2hbbcgjte.html

npm init -y;  npm i express
来源：http://dali.yonumen.top/Article/details/gt2mxazoxmh.html

[U82] JS：package.json 脚本
来源：http://dali.jiagoushi.top/Article/details/gt2hlsteehw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhongyouzk.top/Article/details/gt2cuktctsr.html

[U83] JS：ES Module 导入导出
来源：http://dali.snrcjt.cn/Article/details/gt2fngnvafr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.havefunace.top/Article/details/gt2ktwkprwc.html

[U84] JS：CommonJS 写法
来源：http://dali.ppjwa.cn/Article/details/gt2cciwjjdb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gt2dhcaonyf.html

[U85] JS：可选链
来源：http://dali.zhoulong.xyz/Article/details/gt2emyyviax.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gt2uctdjndc.html

[U86] JS：空值合并
来源：http://dali.snrcjt.cn/Article/details/gt2ktqfilwd.html

a ?? b
来源：http://dali.316326.xyz/Article/details/gt2pnpbpqnh.html

[U87] JS：解构默认值
来源：http://dali.sufxvd.cn/Article/details/gt2gwdeugps.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhyxbqkp.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gt2hmkahxmb.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfiimcga.html

[U89] JS：数组去重
来源：http://dali.yueranfly.top/Article/details/gt2amipftgx.html

[...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2aceudofb.html

[U90] JS：数字数组排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpnkikez.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2cjgflpzi.html

[U91] JS：对象键值遍历
来源：http://dali.tanke756.top/Article/details/gt2mjlkbeyf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jlsjyb.cn/Article/details/gt2xfqgmhjq.html

[U92] JS：深拷贝
来源：http://dali.quarkkingdee.top/Article/details/gt2wvvulzbs.html

structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2angefnxr.html

[U93] JS：模板字符串
来源：http://dali.wangdashe.top/Article/details/gt2fgcgqeet.html

`共 ${n} 条`
来源：http://dali.ivvv.top/Article/details/gt2unyniqth.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2seyslhca.html

const double = x => x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihxnliai.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnssfrxa.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2jqbkzjgr.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gt2ckreyzkd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bizpvsud.html

[U97] JS：并发请求
来源：http://dali.cashguo.top/Article/details/gt2dfmrwuaw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2jmjoioxg.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2byxztfdr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigufen.top/Article/details/gt2lspcxxco.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gt2icbutsak.html

el.addEventListener("click", e => {})
来源：http://dali.cdnleiting.top/Article/details/gt2lbgaerrw.html

[U100] JS：DOM 查询
来源：http://dali.sysykeji.top/Article/details/gt2cefdrcqb.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gt2ovrnkrru.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gt2xxupgdjb.html

el.classList.toggle("active")
来源：http://dali.aizwys.cn/Article/details/gt2qhmkamwk.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gt2bybwwkuo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnqzz.top/Article/details/gt2rlijrkwg.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gt2vilfkhyh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gt2azfqxuss.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gt2hzbtvwxm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2kfbvyqiz.html

[U105] JS：节流
来源：http://dali.hfpthk.cn/Article/details/gt2ucccqzuw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gt2nuqhgouq.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2esaxssti.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guannengcc.top/Article/details/gt2wdkfqlbw.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gt2jucwwagh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekbhwjfg.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gt2kdpgxqhb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gt2xbnqniuc.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2igckxpxq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2ljzmqftu.html

[U110] JS：数组分块
来源：http://dali.chenzaomai.com/Article/details/gt2kmmlzdml.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gt2svavdfwg.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gt2wnwxjxxy.html

new Map(Object.entries(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xupdewzu.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gt2ebbtcmxu.html

"7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2sthoibsl.html

[U113] JS：正则替换全部
来源：http://dali.guannengcc.top/Article/details/gt2ppzgfxcv.html

s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2gowcjxwm.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gt2fmsazuvb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gt2mbeauhig.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2iyqybcyh.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2oyvswbxf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gt2cjmcfazh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gt2ugzbsrgc.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gt2qkdspkse.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gt2hnlxbqaq.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gt2oulrxzjk.html

npm i -D vite;  npx vite
来源：http://dali.ybcxt.top/Article/details/gt2ocduhrjy.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gt2praqellu.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gt2mfuxmgqx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gt2emkzjgrj.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gt2zsxaytby.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2obwrfdju.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gt2jampqkbw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ebskxncw.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqkzisou.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gt2lojessoi.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gt2xingbdqu.html

JavaScript ..... 252
来源：http://dali.yueranfly.top/Article/details/gt2gycklkqu.html

TypeScript ..... 212
来源：http://dali.jyoumei.cn/Article/details/gt2yhwylivz.html

Java ........... 212
来源：http://dali.andypj.xyz/Article/details/gt2cromkbcb.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gt2ieeayhtn.html

Ruby ........... 212
来源：http://dali.snrcjt.cn/Article/details/gt2jyevzexq.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2jzobzufk.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gt2rrjjfefr.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gt2vsgqzexf.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gt2fjgoraga.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gt2faizuwzs.html

Kotlin ......... 15
来源：http://dali.smart0.xyz/Article/details/gt2hkrfaead.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gt2xzmrbcqp.html

Lua ............ 10
来源：http://dali.meibo888.top/Article/details/gt2mqldcybn.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gt2dewgerpu.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joclzhjt.html

------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2eakjhexl.html

合计 ........... 2106 条
来源：http://dali.hywenlv.cn/Article/details/gt2nwdlgjsf.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gt2jovqzxji.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gt2slvhldsx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gt2elwvofem.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2mjoncqzm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gt2ogyfjvfv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gt2rcqfbrcf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gt2xlmdjvzo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dprgspqg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gt2tsduvzlb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxegsjrb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gt2rfhsjgnf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gt2ahcfreoy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2pmcsyjru.html


<!-- 参考信息 -->