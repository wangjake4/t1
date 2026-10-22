代发 wailian999

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gt2upvjmtoe.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2fwevaubm.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2urielign.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2jeunqovk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gt2bywiwdfa.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2owtgcsbt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gt2prsovzts.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gt2uctgvumx.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gt2lsxsdvwg.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gt2zmiwmmjl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gt2rqiavoaf.html

[T58] Scala：函数定义
来源：http://dali.jinqigfzy.top/Article/details/gt2lwumjfzp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gt2ymdlafsm.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gt2ukglrbcz.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqrvntdz.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gt2ccjmppcd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gt2nhzgxvln.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2tffkxbzm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2hidnlhxg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggoebfqy.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gt2tolmyjua.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gt2wxhsscwk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gt2nbyfbvmk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gt2ujwdarck.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gt2mrjjglpe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gt2urcpieka.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwzaaprj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgufenzy.top/Article/details/gt2hjmjvajj.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gt2qkmhwjmh.html

list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2dbetgfqu.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2iauxaean.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gt2fjcpceiv.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gt2jblxaaxz.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gt2ihuqgnfs.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gt2itsqmtuu.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mblsqyat.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gt2anndovhc.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gt2oeqafxcb.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gt2ptrgmggz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gt2zdxtpjbh.html

[U11] Py：生成器表达式
来源：http://dali.svipenyu.cn/Article/details/gt2hbhiedqr.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gt2lfxaajru.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yanxiufei.cn/Article/details/gt2nmlfmpay.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gt2uabslqog.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gt2pyjcttqu.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gt2isjtupxz.html

[U14] Py：分组收集到列表
来源：http://dali.svipenyu.cn/Article/details/gt2fdyhjuvh.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gt2salifocu.html

[U15] Py：高精度计时
来源：http://dali.hnxiangtu.top/Article/details/gt2stvwhfbc.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gt2jhtfzvzx.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gt2cipbxmsw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258888.top/Article/details/gt2yygbwyis.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gt2nwnetqgk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gt2eykgvddm.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gt2wfhspmfr.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2cufanckq.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gt2dexlhreg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anwhnukt.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqwhbkkl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmbdoano.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gt2fbulkeem.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gt2zyhryiyn.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skrouneq.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gt2dfjudazg.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gt2igxkdyqj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gt2scjtgtvv.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gt2rfnyqeit.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stgorqtq.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gt2alzhbxoh.html

csv.DictReader(f)
来源：http://dali.yonumen.top/Article/details/gt2nfohpykx.html

[U26] Py：并发下载
来源：http://dali.ivvv.top/Article/details/gt2tpxxvrpf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gt2dfzltpaj.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gt2inulxkdo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gt2vkonghzd.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gt2fyalesyo.html

UserId = int
来源：http://dali.ehwqpu.com/Article/details/gt2vbjllirl.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gt2fzctjrbv.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gt2zvkxqxeu.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gt2ukbrdaib.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fymhseod.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gt2wrksviak.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gt2irgwvqyc.html

[U32] Py：代码格式化
来源：http://dali.tian-w.cn/Article/details/gt2vxabgnsb.html

ruff format . && ruff check --fix .
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsceegyb.html

[U33] Py：打包发布
来源：http://dali.hfpthk.cn/Article/details/gt2becdmclx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gt2budmfqqu.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwondvsx.html

chardet.detect(raw)
来源：http://dali.meibo888.top/Article/details/gt2pgjdzxeo.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gt2nbdwxtjw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbwkvrig.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2tjjvrwea.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gt2xknzqyev.html

[U37] Py：读写 Excel
来源：http://dali.fzhhl.top/Article/details/gt2lsqxdfln.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xinyue.icu/Article/details/gt2mewaorlc.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gt2ekfosvjk.html

Path(__file__).resolve().parent
来源：http://dali.jqgufenzy.top/Article/details/gt2rndwgqjh.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgufenzy.top/Article/details/gt2ihoserlv.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gt2pskkdavx.html

[U40] Py：打印到标准错误
来源：http://dali.sweek.top/Article/details/gt2akdatymu.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gt2bgwlrvlq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ydzc1.top/Article/details/gt2nyqteyco.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258888.top/Article/details/gt2chxtudwi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gt2qwsyqgjb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gt2muenivmy.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gt2upsldbyj.html

namespace App\Http;
来源：http://dali.redwolf501.top/Article/details/gt2hpudsijd.html

[U44] PHP：开启严格类型
来源：http://dali.sweek.top/Article/details/gt2nykyjzyn.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gt2sblkfxue.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gt2tpvqatfd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2dlohkzix.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gt2sopomedr.html

?string $name = null
来源：http://dali.fzhhl.top/Article/details/gt2ynwujoop.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gt2euxcbyez.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gt2vtvfsgem.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gt2xunttlpo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsqnqxs.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjjncdrm.html

public readonly string $name
来源：http://dali.sxryk.cn/Article/details/gt2kxmqwqav.html

[U50] PHP：构造器属性提升
来源：http://dali.wangdashe.top/Article/details/gt2pszstldg.html

public function __construct(private int $id) {}
来源：http://dali.hywenlv.cn/Article/details/gt2anjgrvvb.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjgbfcqm.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gt2qzfonvfo.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gt2nhlefpii.html

$double = fn($x) => $x * 2;
来源：http://dali.tanke756.top/Article/details/gt2udcejkjy.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gt2fatrofue.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gt2lnjctxrl.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gt2mqdpiijl.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gt2pedxlmaj.html

[U55] PHP：match 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipbjkunh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwvtgpwb.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gt2ipxwuofq.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sowojzco.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2skqdrorq.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gt2ttfuyfth.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gt2nryopdbf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoohmid.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gt2tofumkxp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gt2dgruhove.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gt2hemwkplk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gt2odbblwln.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmjacxln.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2felhckoe.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2btwrzoau.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gt2sdetjsbp.html

[U63] PHP：文件读写
来源：http://dali.guowangkeji.top/Article/details/gt2pbojytgq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmgxsdbm.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2yrizrfqj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gt2syffaxoq.html

[U65] PHP：会话
来源：http://dali.cdnleiting.top/Article/details/gt2xhewplvs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2ynmazaoe.html

[U66] PHP：设置 Cookie
来源：http://dali.daria6918.cn/Article/details/gt2jkoegznx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gt2qfpqfqbe.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gt2ibrtsiwx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigfzy.top/Article/details/gt2fkvypvlh.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gt2nvugestu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pengpengdd.cyou/Article/details/gt2elydwgdw.html

[U69] PHP：PDO 预处理
来源：http://dali.yongpay.top/Article/details/gt2akyictbv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hfpthk.cn/Article/details/gt2bhlmirzp.html

[U70] PHP：PDO 事务
来源：http://dali.zhixingplan.top/Article/details/gt2rzjycppm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gt2wfyrotgc.html

[U71] PHP：抛出异常
来源：http://dali.yj202588.top/Article/details/gt2ntvjbvzk.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2deapmgho.html

[U72] PHP：写错误日志
来源：http://dali.hysaishi.cn/Article/details/gt2pjnueogm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gt2ydjidqie.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gt2erokfehm.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gt2mamxblez.html

[U74] PHP：读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2psymanjw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yvedp.cn/Article/details/gt2ybmogsvf.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gt2unnbgoak.html

composer require psr/container
来源：http://dali.ivvv.top/Article/details/gt2viksajlw.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gt2qlylpmly.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gt2ymeievxa.html

[U77] PHP：模板渲染
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkmnysii.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gt2iywdzooz.html

[U78] PHP：单元测试
来源：http://dali.c1oappe.top/Article/details/gt2uevrdfad.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gt2razpfjzc.html

[U79] PHP：静态分析
来源：http://dali.316326.xyz/Article/details/gt2jjjaplco.html

composer require --dev phpstan/phpstan
来源：http://dali.jlsjyb.cn/Article/details/gt2ohxcgnau.html

[U80] PHP：代码规范修复
来源：http://dali.sufxvd.cn/Article/details/gt2vpcuelaa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xylfe.cn/Article/details/gt2rkucvsjz.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gt2nqewraga.html

npm init -y;  npm i express
来源：http://dali.snrcjt.cn/Article/details/gt2jflrrscm.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnapccek.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.andypj.xyz/Article/details/gt2nlsihlgm.html

[U83] JS：ES Module 导入导出
来源：http://dali.daxiang520.top/Article/details/gt2qsarxttx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gt2bmnyeabx.html

[U84] JS：CommonJS 写法
来源：http://dali.sysykeji.top/Article/details/gt2iojqtwnk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258888.top/Article/details/gt2njgpbksb.html

[U85] JS：可选链
来源：http://dali.aibaodan.cn/Article/details/gt2ndyzqjro.html

a?.b?.c
来源：http://dali.cqqwz.cn/Article/details/gt2szzxyzds.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gt2xeurablp.html

a ?? b
来源：http://dali.yj20258888.top/Article/details/gt2egntnunt.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gt2vpbpruvn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cucudq.cn/Article/details/gt2tbaxqjtb.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gt2pilqksgg.html

{ ...a, ...b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nanldmhx.html

[U89] JS：数组去重
来源：http://dali.xziqi.cn/Article/details/gt2epkzniho.html

[...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2yqzqhrke.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gt2qjmfjfhs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2jodhshne.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gt2nnjobjdu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gt2esxamcvd.html

[U92] JS：深拷贝
来源：http://dali.yongpay.top/Article/details/gt2mznplysq.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2torixbdl.html

[U93] JS：模板字符串
来源：http://dali.zycfv.cn/Article/details/gt2kcjljqle.html

`共 ${n} 条`
来源：http://dali.vqdsnc.cn/Article/details/gt2huvgcyip.html

[U94] JS：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gt2mtiopewd.html

const double = x => x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gt2fziirnkm.html

[U95] JS：Promise 包装
来源：http://dali.fengsongda.top/Article/details/gt2gjtxaxyh.html

new Promise((resolve, reject) => {})
来源：http://dali.cqqwz.cn/Article/details/gt2kapopnvc.html

[U96] JS：async/await 与异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imfuhjby.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phcltfgi.html

[U97] JS：并发请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhbjojwu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2cjwccemb.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuanzx.com/Article/details/gt2lrlssxjd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.andypj.xyz/Article/details/gt2zgrfskmx.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gt2cbqfvdfs.html

el.addEventListener("click", e => {})
来源：http://dali.sufxvd.cn/Article/details/gt2grnyfhxj.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gt2orkuulhu.html

document.querySelector(".item")
来源：http://dali.sufxvd.cn/Article/details/gt2jildinhm.html

[U101] JS：classList 操作
来源：http://dali.guowangkeji.top/Article/details/gt2hgdnwicy.html

el.classList.toggle("active")
来源：http://dali.yangfankeji.com/Article/details/gt2uirififz.html

[U102] JS：本地存储
来源：http://dali.yonumen.top/Article/details/gt2xwmgblbn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gt2uwonsaro.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gt2mqhhvqfl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ybcxt.top/Article/details/gt2rjfyvolf.html

[U104] JS：防抖
来源：http://dali.mhx1999.top/Article/details/gt2yfsznfln.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2gojhimnk.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gt2qwrbxyuy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gt2khnkffsf.html

[U106] JS：日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2bqjwpmzp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xziqi.cn/Article/details/gt2kbsudfya.html

[U107] JS：数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2emsdalib.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cyymuqob.html

[U108] JS：随机整数
来源：http://dali.jqgufenzy.top/Article/details/gt2jyaixdns.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubmbowuo.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gt2xmkzmguv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gt2jgfkvmto.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gt2svhzugxm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tian-w.cn/Article/details/gt2jygwsibk.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gt2qqhjjotd.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gt2bxumztro.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gt2adjfyzsd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cczzmiuh.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gt2llhhuyrn.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2fqwvjtbf.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gt2kxncmvzk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqarshxw.html

[U115] JS：生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gt2yxagalqj.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2aqfnoios.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgfzy.top/Article/details/gt2yqsmflli.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gt2gvbktnuc.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gt2svquccsp.html

npm i -D vitest;  npx vitest
来源：http://dali.0kj1m.cn/Article/details/gt2uhtcqfqc.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gt2mirrubnj.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gt2viodxrky.html

[U119] JS：生产构建
来源：http://dali.aibaodan.cn/Article/details/gt2qkgsmbpm.html

npx vite build
来源：http://dali.tianlin.xyz/Article/details/gt2upjovzsa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj202588.top/Article/details/gt2fisfofva.html

import.meta.env.VITE_API_URL
来源：http://dali.meibo888.top/Article/details/gt2jiqyugxu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ahwdgilr.html

统计汇总
来源：http://dali.316326.xyz/Article/details/gt2pnuetsit.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ikaynroc.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gt2poclvics.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gt2dsntmqfn.html

PHP ............ 252
来源：http://dali.smart0.xyz/Article/details/gt2rtrinkob.html

JavaScript ..... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdjoyrpx.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gt2ybbmevfh.html

Java ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gt2qnodmbpx.html

Go ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gt2voaqpbxo.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gt2mqecjlot.html

C# ............. 212
来源：http://dali.bjfxy.top/Article/details/gt2uywjrkvz.html

C .............. 30
来源：http://dali.jqgufenzy.top/Article/details/gt2muwbdgak.html

C++ ............ 30
来源：http://dali.fengsongda.top/Article/details/gt2tyvbszsj.html

SQL ............ 90
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcxpjplx.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gt2jvizslqb.html

Kotlin ......... 15
来源：http://dali.hnxiangtu.top/Article/details/gt2osoknios.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gt2xattwaea.html

Lua ............ 10
来源：http://dali.havefunace.top/Article/details/gt2cfwjlyib.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdidodpe.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gt2dqpxfkqr.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2faulwitj.html

合计 ........... 2106 条
来源：http://dali.meibo888.top/Article/details/gt2jjfloddo.html

按章节统计：
来源：http://dali.xuanzx.com/Article/details/gt2uhynvfuw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gt2rxmxjjrx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2etpfsvqq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gt2axedyzlz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gt2ajnbvtdm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuanzx.com/Article/details/gt2ahmifjlj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gt2dqkmwpgv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gt2ycsrablv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2jwdlbdao.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2vkfckeau.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gt2pzmrcwpg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2bwuklcvl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2sztlbmbu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2cpmzeneb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gt2bumdtgps.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gt2objqbdoa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2kgbmysgy.html


<!-- 参考信息 -->