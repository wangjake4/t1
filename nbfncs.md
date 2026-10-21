代发 wailian999

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gthekxfgfc.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtayidkfgh.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtctcbqqqf.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtwawnzdwl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gtudlfkwwy.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtusrteppp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtitqerxac.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyuxfnun.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtuhpvvhwp.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtymowcyoe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtosyvfmcj.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtlaouetug.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtkfzymkyc.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gtpqefahkc.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtzyqzqioj.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gttbalvnsa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjelcarql.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtewvcfiwu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtuvjahbik.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdcgkibue.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gtwqmdllbc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtdoopfxop.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtxiaxxhue.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gtqcbxwwsa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtyoyiuida.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtjhjcfane.html

[U04] Py：变量调试打印
来源：http://dali.chenzaomai.com/Article/details/gtskxabqdf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gtjxwojnlm.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gtfhslwrgp.html

list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtnwsqwgsd.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gtcqrselnx.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gtepilbtoy.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gtgvvtwkgc.html

{v: k for k, v in d.items()}
来源：http://dali.redwolf501.top/Article/details/gthqajcykw.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gtlxqokmwn.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gtbfrkvrti.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtkkadfefd.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gtclevonua.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gtnsxtylzq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtvdvvqpjm.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtriwiqprg.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtxrscysih.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gtwhtwbjlo.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gtlieofksr.html

[U13] Py：固定长度队列
来源：http://dali.sweek.top/Article/details/gtqpdyiswz.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gtiipcjwsq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gtplfsqedu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gttxdzisfm.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtgxyeloiq.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gtsykmgfac.html

[U16] Py：命令行参数解析
来源：http://dali.chenlongwang.top/Article/details/gtwlrcxovt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xinyue.icu/Article/details/gtrssvrmfs.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtdhmlsojz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xziqi.cn/Article/details/gtigkbmxvm.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtfecczrah.html

pat = re.compile(r"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemlbvhgk.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtrckmwsiz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gtmibitrlk.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskudgoyk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gtoqgtrlls.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gtemyfphdi.html

@contextlib.contextmanager
来源：http://dali.wangdashe.top/Article/details/gtzwjlnrzx.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gtyefwcqxv.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtkaxrpqgy.html

[U23] Py：分块读取大文件
来源：http://dali.xylfe.cn/Article/details/gtiaodqhsr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258.top/Article/details/gtbkmopvde.html

[U24] Py：路径操作
来源：http://dali.fengsongda.top/Article/details/gttayvmwfg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtnsxgfdua.html

[U25] Py：CSV 按字典读
来源：http://dali.tianlin.xyz/Article/details/gtlgqaosui.html

csv.DictReader(f)
来源：http://dali.ivvv.top/Article/details/gtjruqcznn.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqttmzxz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gtcbrkeuvi.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtbtcezwet.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gtzsxkxwhd.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gtksnprkof.html

UserId = int
来源：http://dali.aibaodan.cn/Article/details/gtkulwmyev.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gtypnctxpp.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtxuhnzepl.html

[U30] Py：数据类
来源：http://dali.gzhubu.top/Article/details/gtgfyhwuuu.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gturqlmsoz.html

[U31] Py：单测
来源：http://dali.pycfn.com/Article/details/gtzthzkfmg.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowcbnqoq.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gtevawvums.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gtnnuyaxrx.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gtqhwsstou.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzftjtsm.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gtoednlioc.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gtwxefhdal.html

[U35] Py：发送邮件
来源：http://dali.jyoumei.cn/Article/details/gtxiddcfna.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gtoxukobrv.html

[U36] Py：定时任务
来源：http://dali.aizwys.cn/Article/details/gtvqsqmawt.html

schedule.every(10).minutes.do(job)
来源：http://dali.sxryk.cn/Article/details/gtfvanebsn.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gtwjqsdyjv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.mhx1999.top/Article/details/gtcyotxeyz.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gtpfctyxxk.html

Path(__file__).resolve().parent
来源：http://dali.ehwqpu.com/Article/details/gtoatygojk.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gtnttpodkp.html

sys.stdout.isatty()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfsfmtkt.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gthtqgjlvm.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtmbgbivyd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtklulcokx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gtwcocljmv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gtcyipuqri.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtuxykjzla.html

[U43] PHP：声明命名空间
来源：http://dali.gotoacloud.top/Article/details/gtfdnzbipd.html

namespace App\Http;
来源：http://dali.ivvv.top/Article/details/gtsfmumopi.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtfmcdkfza.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtyhyzfell.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tian-w.cn/Article/details/gtijcbbhhm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtmywzkbxe.html

[U46] PHP：可空类型
来源：http://dali.shuidangran.top/Article/details/gtdyrqooul.html

?string $name = null
来源：http://dali.hfpthk.cn/Article/details/gtysakszdh.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gthtoabked.html

int|string $id
来源：http://dali.xylfe.cn/Article/details/gtdenlxjfj.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqieigsog.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gtzhcphotr.html

[U49] PHP：只读属性
来源：http://dali.shzxlz.cn/Article/details/gtpbwmdbot.html

public readonly string $name
来源：http://dali.zhoulong.xyz/Article/details/gthpoykiun.html

[U50] PHP：构造器属性提升
来源：http://dali.yanxiufei.cn/Article/details/gtklidmzcv.html

public function __construct(private int $id) {}
来源：http://dali.aibaodan.cn/Article/details/gtssblwker.html

[U51] PHP：数组解构
来源：http://dali.zhoulong.xyz/Article/details/gtixuehxla.html

[$a, $b] = $arr;
来源：http://dali.cqqwz.cn/Article/details/gtgtsuutvq.html

[U52] PHP：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtsvgvhvnw.html

$double = fn($x) => $x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtjyyxhhev.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtbmtfeqco.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvqyfxak.html

[U54] PHP：空安全调用
来源：http://dali.birdmap.top/Article/details/gtqizpxpvi.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhwyxhxj.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gthelzuzza.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gtwiprpqgn.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gtdbesbgbw.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtevhhncwz.html

[U57] PHP：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtvothlmyz.html

"值: {$a}"
来源：http://dali.andypj.xyz/Article/details/gtokomikmp.html

[U58] PHP：数组三件套
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffhgrugx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gtpqyuowwl.html

[U59] PHP：自定义排序
来源：http://dali.jqgufenzy.top/Article/details/gtqsoyqrvb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtsyxtsepo.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gtvkqokthb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gtfcjwonig.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gtavafxugn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtjbyzfcon.html

[U62] PHP：日期对象
来源：http://dali.yvedp.cn/Article/details/gtohyxfbux.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtovfpzmja.html

[U63] PHP：文件读写
来源：http://dali.316326.xyz/Article/details/gtdyguwgix.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtelwezpum.html

[U64] PHP：目录遍历
来源：http://dali.snrcjt.cn/Article/details/gtoxsnyjkb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.havefunace.top/Article/details/gtbicpfjql.html

[U65] PHP：会话
来源：http://dali.jlsjyb.cn/Article/details/gtvkvdnvhg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtaupofrms.html

[U66] PHP：设置 Cookie
来源：http://dali.havefunace.top/Article/details/gtnzsrkpye.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gtxdfvaxon.html

[U67] PHP：处理文件上传
来源：http://dali.havefunace.top/Article/details/gtaenhynkl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gttybmmbuf.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gtwhsjpopg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenjidiqi.icu/Article/details/gtvgntaign.html

[U69] PHP：PDO 预处理
来源：http://dali.cheryme.top/Article/details/gtmgszcbbh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gtuetlogoj.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtittzbxzb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhoulong.xyz/Article/details/gtjgtwvkln.html

[U71] PHP：抛出异常
来源：http://dali.xuanzx.com/Article/details/gtqngckttt.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gtbuehxkuc.html

[U72] PHP：写错误日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosmuzmez.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gtvevbkzlh.html

[U73] PHP：读取 ini 配置
来源：http://dali.haohaochexian.top/Article/details/gtxwyiiyat.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gtdmvnprzh.html

[U74] PHP：读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtarjqfixi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpyzebwo.html

[U75] PHP：依赖注入
来源：http://dali.yuxming.cn/Article/details/gtgiznblvf.html

composer require psr/container
来源：http://dali.cucudq.cn/Article/details/gtbdegmgqj.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gtiexmrbpo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxinkj.top/Article/details/gtnxmltqki.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gttkfxlkou.html

composer require twig/twig
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkycixcje.html

[U78] PHP：单元测试
来源：http://dali.c1oappe.top/Article/details/gteclylaxe.html

composer require --dev phpunit/phpunit
来源：http://dali.jyoumei.cn/Article/details/gtphiyzesi.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gthrbuqyis.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gtaxpotsjm.html

[U80] PHP：代码规范修复
来源：http://dali.yj202588.top/Article/details/gtboeufxuk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gaohongyu789.top/Article/details/gtiyhgwltn.html

[U81] JS：初始化项目
来源：http://dali.andypj.xyz/Article/details/gtsufquapq.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gtablzcvzk.html

[U82] JS：package.json 脚本
来源：http://dali.shuidangran.top/Article/details/gtlirqszql.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.redwolf501.top/Article/details/gthxcmkfpg.html

[U83] JS：ES Module 导入导出
来源：http://dali.yongpay.top/Article/details/gticmevlek.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtlcqhiovo.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gtrqbiliie.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtilcfdugd.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gthszldrju.html

a?.b?.c
来源：http://dali.yj202588.top/Article/details/gtvudltflo.html

[U86] JS：空值合并
来源：http://dali.birdmap.top/Article/details/gtuapegrmt.html

a ?? b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofeazpei.html

[U87] JS：解构默认值
来源：http://dali.quarkkingdee.top/Article/details/gtouxoogir.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigufen.top/Article/details/gtgkdiwlah.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gtoouoqzay.html

{ ...a, ...b }
来源：http://dali.chenlongwang.top/Article/details/gtapuysetj.html

[U89] JS：数组去重
来源：http://dali.fengsongda.top/Article/details/gtngpzyvdx.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtgcvidckc.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gthickzeqd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtsxwcdkiv.html

[U91] JS：对象键值遍历
来源：http://dali.nwbrower.top/Article/details/gtjdkcpevo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gtskjbaxxe.html

[U92] JS：深拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtatinudtd.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtffejakfx.html

[U93] JS：模板字符串
来源：http://dali.cqqwz.cn/Article/details/gtuaxsackl.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gtpvwgbmxa.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gtduhiftyk.html

const double = x => x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtwybbzhjy.html

[U95] JS：Promise 包装
来源：http://dali.redwolf501.top/Article/details/gtspmyfdqs.html

new Promise((resolve, reject) => {})
来源：http://dali.tianlin.xyz/Article/details/gtptjuvtdu.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gteqfzaqfk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gthfyblqcz.html

[U97] JS：并发请求
来源：http://dali.guowangkeji.top/Article/details/gtsavqllfy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtvrfmkool.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gtidpuelbz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cdnleiting.top/Article/details/gtaxkrbqyk.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtpnjmmomg.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gtpooaqtef.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvundtcz.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gtgudmrwia.html

[U101] JS：classList 操作
来源：http://dali.tanke756.top/Article/details/gtsgqhhide.html

el.classList.toggle("active")
来源：http://dali.xuanzx.com/Article/details/gtjlopjcnd.html

[U102] JS：本地存储
来源：http://dali.chenlongwang.top/Article/details/gtrmilrvvn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gtpzbmimhd.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtiffbrrsb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.andypj.xyz/Article/details/gtcdiuqhnw.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gtjeyvgmah.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtcivbfjgv.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gtromhumsy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtifnjccza.html

[U106] JS：日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtylhpeusl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gtnhtbrnhb.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gtzexaygml.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtohewinap.html

[U108] JS：随机整数
来源：http://dali.yonumen.top/Article/details/gtkezeoood.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtghvrrzec.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhxjlibf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtncjmjfuo.html

[U110] JS：数组分块
来源：http://dali.tian-w.cn/Article/details/gtgbemqjli.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.havefunace.top/Article/details/gtobzfxmdt.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gtspkxmpqi.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gtinhgbomx.html

[U112] JS：字符串补位
来源：http://dali.redwolf501.top/Article/details/gtfsoofiak.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtphfagytk.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtxcbqurie.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtimocvgtc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gtnpyljxcd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtylvkcfei.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gthfjrcbxf.html

crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtszdaovev.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gtbzbktnnn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtazxmpnux.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gtbybtydjx.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gtypzswvpa.html

[U118] JS：开发服务器
来源：http://dali.guannengcc.top/Article/details/gtpjvblcsw.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gtcynpykqs.html

[U119] JS：生产构建
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvsxgyix.html

npx vite build
来源：http://dali.aibaodan.cn/Article/details/gtzuzmhlcr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gtddczeufs.html

import.meta.env.VITE_API_URL
来源：http://dali.c1oappe.top/Article/details/gtabcimvtp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtiuqrflta.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtanxhoafs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvbxlskri.html

按语言统计（条）：
来源：http://dali.hongshengwenyu.top/Article/details/gtdgsbsnva.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtdtzutget.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gtugokylbv.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gtojacbmdk.html

TypeScript ..... 212
来源：http://dali.zdqjudy.top/Article/details/gtjjtaznqe.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gtdmijnsrq.html

Go ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtsbyxjyqi.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gtekvelxiu.html

C# ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtblfauuif.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gtvhvyzokw.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gtbjqblcrn.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gtkxfezrqu.html

Bash ........... 80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtennzkbtc.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gtqhxxnbbc.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gtnjodcdvd.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtdrdoezyc.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtuegwtgoc.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtxyykmkbx.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtibcbznqm.html

合计 ........... 2106 条
来源：http://dali.hysaishi.cn/Article/details/gtelevjwqt.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gtcejdwkup.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gtfbdyuujf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtcreooaqi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtlukxzqff.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtqotkyavo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hywenlv.cn/Article/details/gtkfkwemje.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtzyxlntgc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtmnyommzz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gtbujchzqk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtrjlmawpx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtlkkitxdh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gttnayiqqa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtrfeozbqi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtpqhfsohg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gtvkzlfviv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtxhesjzaw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtykbcszzl.html


<!-- 参考信息 -->