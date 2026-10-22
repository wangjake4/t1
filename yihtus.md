代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihaofhlv.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gt2uswalsqc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gt2nequmpvx.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gt2xyzbgvec.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gt2mqupmowp.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2rfgolydo.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2rjsdgasp.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gt2cbxulyeo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwhoxakc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ntoowofs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj202588.top/Article/details/gt2shcssard.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sqnvhzmo.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gt2edjwluco.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuxming.cn/Article/details/gt2xpowffvu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwjfgrjn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gt2cqxmphgd.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gt2zmmdevom.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gt2fqukbady.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gt2zlruheuz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxuanxn.top/Article/details/gt2rlgaqiee.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gt2ddzpxzyk.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2kgglnrvp.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwccrxwh.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gt2xtcsigsi.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gt2yyjlrqoj.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gt2ymlqlous.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gt2xxqljmwp.html

[y for x in nested for y in x]
来源：http://dali.haohaochexian.top/Article/details/gt2kparllud.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gt2jgcoefto.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gt2euuioytl.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gt2ltokdduw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gt2oowquvar.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gt2roytlwag.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gt2zlzevpgh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.9152youxi.cn/Article/details/gt2xwgbyijm.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gt2vtbitvru.html

[U13] Py：固定长度队列
来源：http://dali.sufxvd.cn/Article/details/gt2gfrzlyzx.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gt2zpdujtdk.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gt2kmrffska.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gt2hfhyvfdu.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gt2yrcvuguv.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gt2tkhryfgq.html

[U16] Py：命令行参数解析
来源：http://dali.dashuyun.cn/Article/details/gt2dtwcebgw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gt2luyifrrj.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gt2qretxgzj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgggcwxf.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gt2chcfsqpm.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gt2oqiccxtw.html

[U19] Py：正则替换带回调
来源：http://dali.gzhubu.top/Article/details/gt2zrndkfve.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gt2lcgepkif.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigfzy.top/Article/details/gt2dggvqoua.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gt2vgorpjbn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gt2olxaczkg.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gt2hchvfavs.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gt2txurspkv.html

list(zip(*m))
来源：http://dali.yvedp.cn/Article/details/gt2pkgvgbns.html

[U23] Py：分块读取大文件
来源：http://dali.xylfe.cn/Article/details/gt2cijuwuwf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlzlfjeb.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gt2ustxgaql.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2rqpdosyy.html

[U25] Py：CSV 按字典读
来源：http://dali.yanxiufei.cn/Article/details/gt2lebjemyb.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpiolubl.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gt2xstjgewd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgxrcoyr.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjdloinw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gt2cbtoqfej.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gt2twirbjis.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ungtdtge.html

[U29] Py：属性校验
来源：http://dali.yj20258.top/Article/details/gt2yhjfwfcm.html

@property 与 @x.setter 配合
来源：http://dali.shuidangran.top/Article/details/gt2eyvtsmhu.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwkeuzol.html

@dataclass(slots=True)
来源：http://dali.hfpthk.cn/Article/details/gt2meexxbew.html

[U31] Py：单测
来源：http://dali.shzxlz.cn/Article/details/gt2tewpycam.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gt2zdhjjiyo.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixobwijg.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkflmfgj.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gt2kmlwxdun.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxuanxn.top/Article/details/gt2wglkrvcj.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gt2tkiqddwa.html

chardet.detect(raw)
来源：http://dali.hongshengwenyu.top/Article/details/gt2adbfxupc.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gt2svthddbr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dianchejie.cn/Article/details/gt2sydavrhg.html

[U36] Py：定时任务
来源：http://dali.smart0.xyz/Article/details/gt2kgvbnmru.html

schedule.every(10).minutes.do(job)
来源：http://dali.ybcxt.top/Article/details/gt2rcgecpjb.html

[U37] Py：读写 Excel
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkbihorh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gt2xwhzptfa.html

[U38] Py：获取脚本所在目录
来源：http://dali.aibaodan.cn/Article/details/gt2anwequww.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gt2hqfkhtsq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocqpiskw.html

sys.stdout.isatty()
来源：http://dali.zycfv.cn/Article/details/gt2gikeofof.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gt2emwejwus.html

print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2wrgfhxmi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2idzgswnb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.redwolf501.top/Article/details/gt2amuwwigl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnxiangtu.top/Article/details/gt2adlirqvm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gt2tfkpzeno.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gt2eesjdcdd.html

namespace App\Http;
来源：http://dali.jyoumei.cn/Article/details/gt2runkgsmo.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gt2mcahklfr.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gt2omtvkrqa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gt2qncfojhi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2sysjelja.html

[U46] PHP：可空类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2igxsbvpt.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gt2iajkpccm.html

[U47] PHP：联合类型
来源：http://dali.daria6918.cn/Article/details/gt2jcdadpyf.html

int|string $id
来源：http://dali.chenzaomai.com/Article/details/gt2vkmnhcdc.html

[U48] PHP：纯枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2xbuhrrzp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gt2lsdryfgq.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gt2mlszuqmw.html

public readonly string $name
来源：http://dali.hfpthk.cn/Article/details/gt2swuahnfn.html

[U50] PHP：构造器属性提升
来源：http://dali.shangyingyoupin.top/Article/details/gt2enpsihsi.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gt2smizilwa.html

[U51] PHP：数组解构
来源：http://dali.sysykeji.top/Article/details/gt2ksazbsyb.html

[$a, $b] = $arr;
来源：http://dali.jqgufenzy.top/Article/details/gt2nynytdif.html

[U52] PHP：箭头函数
来源：http://dali.c1oappe.top/Article/details/gt2mtgzerzg.html

$double = fn($x) => $x * 2;
来源：http://dali.9152youxi.cn/Article/details/gt2phyxtjgs.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gt2mrszbypw.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gt2xfscujsb.html

[U54] PHP：空安全调用
来源：http://dali.guannengcc.top/Article/details/gt2pbsbzqgm.html

$obj?->method()
来源：http://dali.cucudq.cn/Article/details/gt2ucujllfn.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2gotfkvqi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gt2egvncsyq.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gt2xtbvfoeq.html

f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2xlzlsgdk.html

[U57] PHP：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2hqhybnpk.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gt2akjinxgl.html

[U58] PHP：数组三件套
来源：http://dali.chenlongwang.top/Article/details/gt2hkdfadxb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuxming.cn/Article/details/gt2wwlgbjjt.html

[U59] PHP：自定义排序
来源：http://dali.9152youxi.cn/Article/details/gt2tihrpkdh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnhvlgsb.html

[U60] PHP：JSON 编解码
来源：http://dali.gotoacloud.top/Article/details/gt2hjhymrdg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xziqi.cn/Article/details/gt2vgwnebqu.html

[U61] PHP：正则
来源：http://dali.zhengqikj.top/Article/details/gt2ednetzaj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqmjelqm.html

[U62] PHP：日期对象
来源：http://dali.sweek.top/Article/details/gt2hiuywzni.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gt2bboswzhg.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gt2gclnsiiw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gt2epchmuim.html

[U64] PHP：目录遍历
来源：http://dali.jyoumei.cn/Article/details/gt2qkarnewz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.316326.xyz/Article/details/gt2xbphdwcv.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gt2opxslgrv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2icgiciro.html

[U66] PHP：设置 Cookie
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohvqmhoa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gt2gnxmlgpr.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gt2qixgsken.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gt2unmsfqmg.html

[U68] PHP：PDO 连接
来源：http://dali.aibaodan.cn/Article/details/gt2safaauly.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cdnleiting.top/Article/details/gt2bmbnrllw.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gt2xzpifcep.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gt2puivpfuy.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiixfihj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yonumen.top/Article/details/gt2gybwyvme.html

[U71] PHP：抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2vyukuhjh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2elfimimi.html

[U72] PHP：写错误日志
来源：http://dali.yj20258888.top/Article/details/gt2vqoxewxh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yongpay.top/Article/details/gt2kfcihnvm.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gt2odimbgox.html

parse_ini_file("config.ini", true)
来源：http://dali.xuanzx.com/Article/details/gt2aaemirld.html

[U74] PHP：读取环境变量
来源：http://dali.cucudq.cn/Article/details/gt2kgjvacge.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuxming.cn/Article/details/gt2ffxqzsdd.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gt2nwedprrn.html

composer require psr/container
来源：http://dali.yanxiufei.cn/Article/details/gt2xeryodod.html

[U76] PHP：简单路由
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzhicyvv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gt2bcwrrqrt.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gt2qrbsolzd.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gt2tbqmttnz.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2znaivcdt.html

composer require --dev phpunit/phpunit
来源：http://dali.hammf.cn/Article/details/gt2xamvbtmq.html

[U79] PHP：静态分析
来源：http://dali.yangfankeji.com/Article/details/gt2vuwnhmdz.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gt2fsdlixht.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcpckteo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhengqikj.top/Article/details/gt2cnnzipax.html

[U81] JS：初始化项目
来源：http://dali.yongpay.top/Article/details/gt2cdadhlee.html

npm init -y;  npm i express
来源：http://dali.daria6918.cn/Article/details/gt2zfnphmvd.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gt2zjqjgyyb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ybcxt.top/Article/details/gt2xxctxnnu.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gt2fkikilbf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gt2eiwmhjiw.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gt2lcvvgooh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jianghu66.top/Article/details/gt2fbjcnsec.html

[U85] JS：可选链
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmwdkqde.html

a?.b?.c
来源：http://dali.chenjidiqi.icu/Article/details/gt2sipjerdl.html

[U86] JS：空值合并
来源：http://dali.yj202588.top/Article/details/gt2ycstunve.html

a ?? b
来源：http://dali.jlsjyb.cn/Article/details/gt2uexxocby.html

[U87] JS：解构默认值
来源：http://dali.daria6918.cn/Article/details/gt2pysglpex.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gt2oqpfgfmx.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gt2zfmdbwsd.html

{ ...a, ...b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2falwtohj.html

[U89] JS：数组去重
来源：http://dali.dashuyun.cn/Article/details/gt2tdpsjsjd.html

[...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2fzphqgga.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gt2ilrstmhe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxmdwwen.html

[U91] JS：对象键值遍历
来源：http://dali.yongpay.top/Article/details/gt2uxlvjytk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjkktbgh.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2tdgrziov.html

structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2emolpqor.html

[U93] JS：模板字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2onckzzba.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gt2dsrtqybe.html

[U94] JS：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gt2epvsnkcn.html

const double = x => x * 2;
来源：http://dali.sxryk.cn/Article/details/gt2jmgpqalt.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqkurjcm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxfrtvyj.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gt2sdloecff.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2ydpllzxx.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gt2idefthhv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xeoenanu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gt2crdmkbcr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gt2vbpthqrz.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gt2gjbjhvwr.html

el.addEventListener("click", e => {})
来源：http://dali.ybcxt.top/Article/details/gt2zndyavne.html

[U100] JS：DOM 查询
来源：http://dali.jianghu66.top/Article/details/gt2khintxvh.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gt2rktnzaji.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gt2xfzsemsd.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gt2mczrhhco.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlhkjibn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.kuanghao11.cn/Article/details/gt2xwzykmfs.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gt2mpvmwhvc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijvtsxfc.html

[U104] JS：防抖
来源：http://dali.ehwqpu.com/Article/details/gt2ynaunmck.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2ntixyiak.html

[U105] JS：节流
来源：http://dali.yueranfly.top/Article/details/gt2kjrirnzi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gogol.net.cn/Article/details/gt2xypagwlb.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2tvkwreem.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gt2viitfksp.html

[U107] JS：数字千分位
来源：http://dali.svipenyu.cn/Article/details/gt2lguamlfe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gt2hloutmwl.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obzmknrr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gt2orknasqv.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gt2stklutgt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2pfyofcae.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gt2ndrdybqp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gt2ezbmrxsv.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gt2fvexoriv.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gt2drjsxcvj.html

[U112] JS：字符串补位
来源：http://dali.pycfn.com/Article/details/gt2ypwcidte.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2etrmcxaq.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gt2jtxzfubm.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2ueytssec.html

[U114] JS：JSON 深比较
来源：http://dali.gaohongyu789.top/Article/details/gt2qgtphlss.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gt2cvxsacku.html

[U115] JS：生成 UUID
来源：http://dali.fengsongda.top/Article/details/gt2tiknkwff.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2yoblazhk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ybcxt.top/Article/details/gt2haeqseom.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gt2cqkkkxvy.html

[U117] JS：单元测试
来源：http://dali.gzhubu.top/Article/details/gt2tltycuss.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gt2ddnqtwaj.html

[U118] JS：开发服务器
来源：http://dali.aibaodan.cn/Article/details/gt2iwfzzpnk.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gt2hfupsxjb.html

[U119] JS：生产构建
来源：http://dali.cucudq.cn/Article/details/gt2ekawjfnl.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekwdjsta.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gt2lazlpmsk.html

import.meta.env.VITE_API_URL
来源：http://dali.jianghu66.top/Article/details/gt2fxpdezax.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2dpmrpkmt.html

统计汇总
来源：http://dali.iojbl.cn/Article/details/gt2kbxabbbz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dqrfgvyl.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gt2exbfweoh.html

Python ......... 252
来源：http://dali.hnxiangtu.top/Article/details/gt2ifqeywfz.html

PHP ............ 252
来源：http://dali.ivvv.top/Article/details/gt2madsirdu.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gt2tttexcue.html

TypeScript ..... 212
来源：http://dali.cheryme.top/Article/details/gt2xmxxeuhl.html

Java ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2zsupjlwb.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2djgqidrs.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gt2flkpycdg.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gt2radoprrn.html

C .............. 30
来源：http://dali.daria6918.cn/Article/details/gt2xladyzdx.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gt2bykqtsnb.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gt2zmyqsxwv.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gt2lpvzktoi.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gt2mjkgualp.html

Swift .......... 15
来源：http://dali.tanke756.top/Article/details/gt2giqqlymt.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gt2zgzfvseo.html

Perl ........... 10
来源：http://dali.tanke756.top/Article/details/gt2xwfrnlxw.html

Scala .......... 10
来源：http://dali.chenlongwang.top/Article/details/gt2xntiifvv.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2keyresqp.html

合计 ........... 2106 条
来源：http://dali.snrcjt.cn/Article/details/gt2yhavecmx.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gt2dzohqqbq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwiyydec.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mepgdxpn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2eootfgde.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2kfxdofan.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jianghu66.top/Article/details/gt2zajwtfep.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2feekljwt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2sxbdsoqg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gt2oopvrkve.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2ewhcmvmx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlbuamsh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gt2igzzxmfc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2wipwttbl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2lslzfpxi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gt2azxuolkp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gt2sokvqknv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhygwois.html

Q SQL 专题                              90
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmvnmprj.html

R Bash 专题                             80
来源：http://dali.yangfankeji.com/Article/details/gt2zcxejzvm.html

S C / C++ 专题                          60
来源：http://dali.cashguo.top/Article/details/gt2uylzatmx.html

T 其他语言补充                          60
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlkcynaw.html

U 高频实用片段                         120
来源：http://dali.shuidangran.top/Article/details/gt2ocrvacuj.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2avayebhx.html

合计                                  2106 条
来源：http://dali.jyoumei.cn/Article/details/gt2gcrwsxiv.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gt2bikshijo.html


<!-- 参考信息 -->