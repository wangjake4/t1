代发 wailian999

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2czzyradg.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2biqtzhdb.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlzpflkb.html

[T54] Scala：集合映射
来源：http://dali.birdmap.top/Article/details/gt2iofyfntt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzpknntj.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2nnjrtxmk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ngbliyut.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gt2tvkxiyyy.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2yjkqacsk.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gt2rcxvritr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gt2svwgohbq.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqopjitf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtqdxrdk.html

[T59] Scala：循环
来源：http://dali.nanxinkj.top/Article/details/gt2oyhvtnfk.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gt2nnlnmaqw.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gt2qpezpqlb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gt2mfinqzob.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbfbiekc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gt2kuvfudsb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lzwrqnbp.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gt2emvdfrgf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynakdgnm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gt2syeipyst.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gt2ysumzgam.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gt2gpzgwudp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbhfqvdw.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gt2mpyvkrmh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2feexcfil.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gt2edbbzaxm.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwidttkv.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gt2iilbbdaj.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gt2rikkqjmz.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gt2cpixsrmr.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujkylkop.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gt2vrztvbqo.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gt2jaflafbu.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gt2hmdmxfyq.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gt2fofghjes.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udkznjqp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gt2wcxbhmex.html

[U11] Py：生成器表达式
来源：http://dali.jqgfzy.top/Article/details/gt2ktitcdii.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onucxjcl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2czhfvtxm.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fedxbmac.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gt2lzetvxda.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gt2rtjidwjt.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2cmhlvhjq.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gt2oztqwyof.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gt2wtttlcuy.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gt2jmtdiqhs.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gt2wzglarqb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gt2dwsncyeb.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gt2sgyhaqog.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gt2nrhvsjcp.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gt2yotmstqh.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2zisfrere.html

[U19] Py：正则替换带回调
来源：http://dali.9152youxi.cn/Article/details/gt2igsfxjbc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgfzy.top/Article/details/gt2donygzis.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gt2urxpdalu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zdqjudy.top/Article/details/gt2nrzfagiw.html

[U21] Py：自定义上下文管理器
来源：http://dali.hfpthk.cn/Article/details/gt2qdxubwob.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gt2mrhixltt.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2ciaqlefe.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gt2ctzspdwf.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gt2fjqheaqk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gt2qstqilzg.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gt2psflelul.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2kfrmhefz.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gt2inntvxyg.html

csv.DictReader(f)
来源：http://dali.zdqjudy.top/Article/details/gt2kvntimmw.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gt2hkwgwsln.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gt2qaktwfmv.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gt2uxbpihxx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gt2ytnnwwan.html

[U28] Py：类型别名
来源：http://dali.ybcxt.top/Article/details/gt2fckzebqt.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gt2dzphvlmb.html

[U29] Py：属性校验
来源：http://dali.yj202588.top/Article/details/gt2yyotuatj.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gt2letwbxva.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2msoknjjo.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gt2bdnknetr.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2hcbhudaa.html

python -m pytest -q
来源：http://dali.mhx1999.top/Article/details/gt2hwvftknz.html

[U32] Py：代码格式化
来源：http://dali.yuxming.cn/Article/details/gt2dilsqbwe.html

ruff format . && ruff check --fix .
来源：http://dali.nwbrower.top/Article/details/gt2panoicrm.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gt2tvcxchhf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gt2abybltik.html

[U34] Py：判断编码
来源：http://dali.xinyue.icu/Article/details/gt2qzfornqs.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gt2bsnlwtez.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gt2ihcinrmp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gt2zgqumizf.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gt2njyvxdzz.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gt2bofvgeoa.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gt2mdjebfjb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gt2sebrxjyb.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gacxezfb.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gt2oqbifhav.html

[U39] Py：判断是否在交互环境
来源：http://dali.yanxiufei.cn/Article/details/gt2zrwewzrs.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gt2uihigquf.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gt2klfnnfqp.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gt2wtoyzwti.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gt2lhheumvx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gt2nishjnbf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gt2crhcxkwk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpzgnbvj.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnszvvov.html

namespace App\Http;
来源：http://dali.hysaishi.cn/Article/details/gt2oelivlsx.html

[U44] PHP：开启严格类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdcrdtah.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gt2tyrcnnwt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fzhhl.top/Article/details/gt2jfumoxfw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2fzfmplaj.html

[U46] PHP：可空类型
来源：http://dali.jianghu66.top/Article/details/gt2qprqavog.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2omxrrxtb.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gt2xereusfw.html

int|string $id
来源：http://dali.zycfv.cn/Article/details/gt2irpdewjm.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gt2xbcqxmvy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gt2zzngpxjz.html

[U49] PHP：只读属性
来源：http://dali.jlsjyb.cn/Article/details/gt2ysonjzid.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gt2adxrzqai.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gt2cycomghw.html

public function __construct(private int $id) {}
来源：http://dali.chenlongwang.top/Article/details/gt2beadqhfq.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gt2fhgbunst.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gt2yewbltpw.html

[U52] PHP：箭头函数
来源：http://dali.yj20258.top/Article/details/gt2ylktiisc.html

$double = fn($x) => $x * 2;
来源：http://dali.gzhubu.top/Article/details/gt2dpolxhqy.html

[U53] PHP：空合并运算符
来源：http://dali.jqgfzy.top/Article/details/gt2fltvfsib.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gt2awcujcdm.html

[U54] PHP：空安全调用
来源：http://dali.dashuyun.cn/Article/details/gt2yhgutiho.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gt2cztgjrqm.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2thrwgzvc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gt2dzagzumh.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bccfwklt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivabquc.html

[U57] PHP：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2khhlnsfa.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gt2bqtchgri.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gt2ncmcliti.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gt2vzlsdbzo.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egftngda.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2vwynwmih.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gt2cifmsjny.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangdashe.top/Article/details/gt2andkgtkr.html

[U61] PHP：正则
来源：http://dali.yuxming.cn/Article/details/gt2ehlflsoh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2cgtngetz.html

[U62] PHP：日期对象
来源：http://dali.xuanzx.com/Article/details/gt2udpzhswz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gt2saxhnwfl.html

[U63] PHP：文件读写
来源：http://dali.andypj.xyz/Article/details/gt2tnvflsxo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhongyouzk.top/Article/details/gt2vlkhfngg.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gt2jdfvmpik.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gt2snavkaan.html

[U65] PHP：会话
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkgpxjey.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2jbidlccn.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gt2wmpnqrvb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxinkj.top/Article/details/gt2psxxzcxd.html

[U67] PHP：处理文件上传
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgiavpjf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgpkunug.html

[U68] PHP：PDO 连接
来源：http://dali.shzxlz.cn/Article/details/gt2njidvcrn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yangfankeji.com/Article/details/gt2neovksba.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gt2vaafrnju.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nwbrower.top/Article/details/gt2cbpzexgk.html

[U70] PHP：PDO 事务
来源：http://dali.shzxlz.cn/Article/details/gt2zaiphnnm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gt2zsgqpzts.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2cwxgipue.html

throw new RuntimeException("失败", 500);
来源：http://dali.bjfxy.top/Article/details/gt2yyttlvze.html

[U72] PHP：写错误日志
来源：http://dali.hnqzz.top/Article/details/gt2wojeolvw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gt2aedffkcz.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gt2fmwfxdil.html

parse_ini_file("config.ini", true)
来源：http://dali.shuidangran.top/Article/details/gt2jvvudhwe.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2ecmvumio.html

getenv("APP_ENV") ?: "production"
来源：http://dali.redwolf501.top/Article/details/gt2vjorxjrd.html

[U75] PHP：依赖注入
来源：http://dali.xinyue.icu/Article/details/gt2bazcnafh.html

composer require psr/container
来源：http://dali.yongpay.top/Article/details/gt2hlpgtzon.html

[U76] PHP：简单路由
来源：http://dali.yanxiufei.cn/Article/details/gt2hinowjup.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.mhx1999.top/Article/details/gt2jtrlhyin.html

[U77] PHP：模板渲染
来源：http://dali.shzxlz.cn/Article/details/gt2jlzegftr.html

composer require twig/twig
来源：http://dali.yvedp.cn/Article/details/gt2sfgzsfry.html

[U78] PHP：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjblycoy.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gt2dkdrdvsj.html

[U79] PHP：静态分析
来源：http://dali.tian-w.cn/Article/details/gt2rthstbbw.html

composer require --dev phpstan/phpstan
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdttgrmd.html

[U80] PHP：代码规范修复
来源：http://dali.wangdashe.top/Article/details/gt2mpgkwjhw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hysaishi.cn/Article/details/gt2zvpzrbil.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gt2awhrmerx.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gt2wpbsvzlh.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plilaigt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gncuyixn.html

[U83] JS：ES Module 导入导出
来源：http://dali.316326.xyz/Article/details/gt2jihvhzqp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gt2gzudxfjv.html

[U84] JS：CommonJS 写法
来源：http://dali.hnqzz.top/Article/details/gt2ypfatkjv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yonumen.top/Article/details/gt2xfnikkie.html

[U85] JS：可选链
来源：http://dali.xinyue.icu/Article/details/gt2sdzqevwz.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gt2tzubdbib.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gt2weneqeps.html

a ?? b
来源：http://dali.zdqjudy.top/Article/details/gt2udpwucmd.html

[U87] JS：解构默认值
来源：http://dali.gotoacloud.top/Article/details/gt2dbyfbhhw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gt2tsmmyjov.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gt2nndleter.html

{ ...a, ...b }
来源：http://dali.birdmap.top/Article/details/gt2llreuorq.html

[U89] JS：数组去重
来源：http://dali.zycfv.cn/Article/details/gt2ukkapvck.html

[...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gt2xiodalvs.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gt2fjapwwgv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2wylnvaoy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gphkitxs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.haohaochexian.top/Article/details/gt2kimjsbau.html

[U92] JS：深拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2ywfmbwgp.html

structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2wkpzbviz.html

[U93] JS：模板字符串
来源：http://dali.zycfv.cn/Article/details/gt2pdgfonhs.html

`共 ${n} 条`
来源：http://dali.smart0.xyz/Article/details/gt2fdjtraqm.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gt2pzzvwzwf.html

const double = x => x * 2;
来源：http://dali.tanke756.top/Article/details/gt2usohkwqh.html

[U95] JS：Promise 包装
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqgyobgc.html

new Promise((resolve, reject) => {})
来源：http://dali.chenlongwang.top/Article/details/gt2lrlvppon.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gt2sczwpohg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2qtmofjov.html

[U97] JS：并发请求
来源：http://dali.ydzc1.top/Article/details/gt2ujgkiykz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2manwewrf.html

[U98] JS：fetch 带 JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2glhkcthr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwhzulgp.html

[U99] JS：事件监听
来源：http://dali.hywenlv.cn/Article/details/gt2cpyyuvwt.html

el.addEventListener("click", e => {})
来源：http://dali.daxiang520.top/Article/details/gt2bpqmfele.html

[U100] JS：DOM 查询
来源：http://dali.bjfxy.top/Article/details/gt2owwxnjub.html

document.querySelector(".item")
来源：http://dali.nanxuanxn.top/Article/details/gt2lanjjcai.html

[U101] JS：classList 操作
来源：http://dali.0kj1m.cn/Article/details/gt2doynugbg.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gt2cozykkao.html

[U102] JS：本地存储
来源：http://dali.smart0.xyz/Article/details/gt2ovymjsly.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gt2qbqldmio.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gt2unujqbmi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.haohaochexian.top/Article/details/gt2ibktlzmb.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjqjkdyf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2bxnrqiqr.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gt2ppzfvumm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gt2vhmohlsr.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2uisguuqc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gt2yciwldqa.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqmjhpdf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gt2hfdeeaco.html

[U108] JS：随机整数
来源：http://dali.9152youxi.cn/Article/details/gt2npexfgmg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gt2dtbjhbvj.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gt2jooxrzri.html

Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gt2wmuxuhpu.html

[U110] JS：数组分块
来源：http://dali.ppjwa.cn/Article/details/gt2pojjoacr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gt2ntombpuu.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gt2ejdlsgle.html

new Map(Object.entries(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2notffymh.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gt2ujiejnzk.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2gvkahlnh.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gt2qmeycfez.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2btbuidvm.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gt2tujvsqnw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2ljcltshs.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2vpvvpnzb.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2lvhyajpy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gt2porjgpwy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2axvdfrbk.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gt2vsqtvcuo.html

npm i -D vitest;  npx vitest
来源：http://dali.tian-w.cn/Article/details/gt2ydmpkplx.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gt2okddnbyp.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gt2htnjchlb.html

[U119] JS：生产构建
来源：http://dali.ehwqpu.com/Article/details/gt2yyjjzlyg.html

npx vite build
来源：http://dali.c1oappe.top/Article/details/gt2uidqyeas.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.c1oappe.top/Article/details/gt2uqwgvtlv.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gt2hnqctriq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sbwodsns.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gt2yflctreb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2pdanxngr.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gt2mvulgyah.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gt2spknrhqn.html

PHP ............ 252
来源：http://dali.sufxvd.cn/Article/details/gt2awqtvfat.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzfcmypq.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gt2gyawuejw.html

Java ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsueceqb.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gt2fbnplqxn.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgulicpd.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gt2khyaisvh.html

C .............. 30
来源：http://dali.wangdashe.top/Article/details/gt2meaaemmi.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gt2cxocppup.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gt2vjwhkawu.html

Bash ........... 80
来源：http://dali.jqgfzy.top/Article/details/gt2kfbldsev.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gt2mdocwfko.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gt2emgkzuwj.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gt2wqunmocu.html

Perl ........... 10
来源：http://dali.gaohongyu789.top/Article/details/gt2nsdcybdv.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gt2lglipszx.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2afzmhjmv.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2dghiwlgm.html

按章节统计：
来源：http://dali.yongpay.top/Article/details/gt2bjjaatbi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gt2mwcvfoeu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2nphainmt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gt2jsegbygl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhengqikj.top/Article/details/gt2sutqvdyh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gt2ypcbintb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmryzjus.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gt2cigikilo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gt2gxobmmrl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2otipfyyn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2qvwobame.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2nudegygg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2lsawqacz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2tdojsjmb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gt2obetxfmt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xinyue.icu/Article/details/gt2stjjshth.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2ijhcbtbg.html


<!-- 参考信息 -->