代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gtgykdwzpy.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtqwcdweaw.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgfjfavz.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gthumllsuo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gtfwguidgi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfjajevmf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtctcpswiy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtivekbalv.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gttjubotot.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtvirupfwx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlvqpdcv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gtwlaadcir.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gthhbavmsm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbwhsiyz.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gtkaevxzsh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gtcjivjkhr.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtlyoeobaf.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtvxxdewto.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtubxypise.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gtyytamevy.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtgxczdnyr.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gtrtwezkdh.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtzzrexota.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtmjpiuydo.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gticyldoin.html

max(d, key=d.get)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyhiekag.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtbkuxvylg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gtfdiitavl.html

[U11] Py：生成器表达式
来源：http://dali.svipenyu.cn/Article/details/gtjjwkqbsi.html

(x * 2 for x in arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtqhcwfhme.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtaeuidtss.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gtyhmlnueb.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gtwnlfugvl.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtneazzled.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gtxwkoleit.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtnmausbtn.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gtigtsxvhd.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gtmwccczpd.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gtczgfvugr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwjdjsem.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gthemjfxjw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtrmxtegrh.html

[U18] Py：预编译正则
来源：http://dali.ivvv.top/Article/details/gtvzgdvwpc.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gtegostmln.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtqgnoxxvc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gtkfuqohqf.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcksuqxj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gthqrxxfnt.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gtvnrwqtrv.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtgzbqardv.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gtznxixybk.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gtbpcmnemt.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gtzbdjpjmk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gtvyftbday.html

[U24] Py：路径操作
来源：http://dali.ydzc1.top/Article/details/gtyomvxcyy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtvkfsfhdq.html

[U25] Py：CSV 按字典读
来源：http://dali.tian-w.cn/Article/details/gtphokrisx.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtdvhivaap.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gtefujujqv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gtdxipedwd.html

[U27] Py：异步 HTTP
来源：http://dali.9152youxi.cn/Article/details/gtobgvtoza.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyxezcjr.html

[U28] Py：类型别名
来源：http://dali.zdqjudy.top/Article/details/gtzassbhri.html

UserId = int
来源：http://dali.jyoumei.cn/Article/details/gtpkfhbtsn.html

[U29] Py：属性校验
来源：http://dali.jlsjyb.cn/Article/details/gtnjgnqzcb.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gtziyrcwbv.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gtpkpmjuxg.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gtytbhqzeo.html

[U31] Py：单测
来源：http://dali.fengsongda.top/Article/details/gtnxakcgkn.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtiinkudjy.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtagtxjatp.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gtkvyovwfz.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gtbwbyfgmc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.quarkkingdee.top/Article/details/gtxvsnfhyt.html

[U34] Py：判断编码
来源：http://dali.zhixingplan.top/Article/details/gtycigxvfq.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gtjndcgldn.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gtnmrvybuk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrekjehu.html

[U36] Py：定时任务
来源：http://dali.mhx1999.top/Article/details/gtplldzrgd.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gtnggagmij.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gtguqzbvlt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxqbovey.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiokbtxp.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gtnkxhrtpt.html

[U39] Py：判断是否在交互环境
来源：http://dali.fengsongda.top/Article/details/gtyrgtixqd.html

sys.stdout.isatty()
来源：http://dali.hywenlv.cn/Article/details/gtisbdpjww.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gtxexbbziy.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtpfqldqbd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigufen.top/Article/details/gtvvxxkfnv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gtbzhixivj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dianchejie.cn/Article/details/gtgipklfrc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gtbrlsiurg.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gtislryibj.html

namespace App\Http;
来源：http://dali.yangfankeji.com/Article/details/gtrtewlbyy.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtwtdzsvyv.html

declare(strict_types=1);
来源：http://dali.dashuyun.cn/Article/details/gtvisbtqvf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gtbhqnyobm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtqjtjkhkl.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gtdodmgund.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gtbieebudq.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gthiucdhnm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gtdpbrjuoi.html

[U48] PHP：纯枚举
来源：http://dali.hywenlv.cn/Article/details/gtugnmaxtk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.bjfxy.top/Article/details/gtkuvpiqnx.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gttunipoxl.html

public readonly string $name
来源：http://dali.redwolf501.top/Article/details/gtjcdgrdgm.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gtqihphrkq.html

public function __construct(private int $id) {}
来源：http://dali.ppjwa.cn/Article/details/gtwgziidxl.html

[U51] PHP：数组解构
来源：http://dali.zdqjudy.top/Article/details/gtffmxiugo.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gtcauyebmq.html

[U52] PHP：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtftcxfylq.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gtsjvxjqod.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtrsamtxgj.html

$v = $a ?? $b ?? "default";
来源：http://dali.meibo888.top/Article/details/gtkpkuatxy.html

[U54] PHP：空安全调用
来源：http://dali.yueranfly.top/Article/details/gtxramvcox.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gtkvdaftud.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gtwdfkqrda.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gtfnfczmek.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtnbxblhhj.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gthppewcei.html

[U57] PHP：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtjabmzdwv.html

"值: {$a}"
来源：http://dali.xinyue.icu/Article/details/gtenrmhzoi.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtvkpdqstk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gtczaegkne.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulogndny.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gtrmawxhpy.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gtnvicdnvc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gtdhzlkpeb.html

[U61] PHP：正则
来源：http://dali.xylfe.cn/Article/details/gtnuimldcj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtsnzqokox.html

[U62] PHP：日期对象
来源：http://dali.jqgfzy.top/Article/details/gtqykmvhxa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.snrcjt.cn/Article/details/gtpbovdqia.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gtqenshflc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxnjvgno.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gtifznpmcj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtrkzfpiyf.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gtckcjqjol.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtdvbcwwab.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gtmenhllla.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gtsnjtsagq.html

[U67] PHP：处理文件上传
来源：http://dali.sysykeji.top/Article/details/gttmzbpjnt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenlongwang.top/Article/details/gtegrijbqi.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gtnnvtknzu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xziqi.cn/Article/details/gtghgdsnpr.html

[U69] PHP：PDO 预处理
来源：http://dali.chenjidiqi.icu/Article/details/gtxbvsuyps.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zycfv.cn/Article/details/gtmcezedyf.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigufen.top/Article/details/gttcafluqw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoudylnk.html

[U71] PHP：抛出异常
来源：http://dali.daria6918.cn/Article/details/gtchjoxays.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenlongwang.top/Article/details/gtftkayvkb.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gtnqzeooec.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gtafubxyel.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhongyouzk.top/Article/details/gtktbelkxw.html

parse_ini_file("config.ini", true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgvohbmx.html

[U74] PHP：读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtnoporvue.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gtbydvbyha.html

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gtcblevlxa.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gttikgixoo.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gtvwacrqfv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtieyjtfhc.html

[U77] PHP：模板渲染
来源：http://dali.yuanzhike.top/Article/details/gtogdoiomm.html

composer require twig/twig
来源：http://dali.cucudq.cn/Article/details/gthgmsanbr.html

[U78] PHP：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gtzebtrfoa.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gtjtfgysay.html

[U79] PHP：静态分析
来源：http://dali.redwolf501.top/Article/details/gtbdbsfihn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhiwuduotai.top/Article/details/gtwbqycdgb.html

[U80] PHP：代码规范修复
来源：http://dali.svipenyu.cn/Article/details/gtlhifvoau.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtgfpevrka.html

[U81] JS：初始化项目
来源：http://dali.yj20258888.top/Article/details/gtvextimnx.html

npm init -y;  npm i express
来源：http://dali.pycfn.com/Article/details/gtbfrutvlh.html

[U82] JS：package.json 脚本
来源：http://dali.birdmap.top/Article/details/gtyreffsdg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jlsjyb.cn/Article/details/gtyqlukvwr.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gtbmjeloyv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtauyzquuk.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgfzy.top/Article/details/gtlmhoznpt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuanzx.com/Article/details/gtweqznpoq.html

[U85] JS：可选链
来源：http://dali.shanyushiyangtech.top/Article/details/gtgicoaakn.html

a?.b?.c
来源：http://dali.ydzc1.top/Article/details/gtjuawkegc.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gtsoggdozo.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gtzcjaafhq.html

[U87] JS：解构默认值
来源：http://dali.snrcjt.cn/Article/details/gtabxwbvwf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuanzhike.top/Article/details/gtujpmdkmj.html

[U88] JS：对象展开合并
来源：http://dali.gzhubu.top/Article/details/gtmumtqrwe.html

{ ...a, ...b }
来源：http://dali.yj20258888.top/Article/details/gtsxmlczkc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gtizvuklki.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtyseoyccm.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gtwypxxjni.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtnfeegavo.html

[U91] JS：对象键值遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskdfipxt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shangyingyoupin.top/Article/details/gtwjivezec.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gtqzsifier.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtowlyqkrz.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gtieihlgkx.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gtfwifhrvt.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gtjaixmxvm.html

const double = x => x * 2;
来源：http://dali.daxiang520.top/Article/details/gtptgznmyw.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gtxtdgbdof.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gtodwdppry.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gtssqgxlbz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtmucitcjf.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgkyefgu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtkoyvkplv.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gtgxbtuwxu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gtidsewvlq.html

[U99] JS：事件监听
来源：http://dali.dianchejie.cn/Article/details/gtmzftvjzz.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewtpfryg.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtkagvjmiz.html

document.querySelector(".item")
来源：http://dali.xziqi.cn/Article/details/gtvyevnayq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gtdbplhdlh.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdrqtncs.html

[U102] JS：本地存储
来源：http://dali.yueranfly.top/Article/details/gtzquyrbjm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yangfankeji.com/Article/details/gtmjlhvqwz.html

[U103] JS：定时器
来源：http://dali.feifeiyinyue.top/Article/details/gtkuhzkmku.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yangfankeji.com/Article/details/gtokjxjata.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtmbcqkktz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtgnqmhyhu.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gtgiweukyc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gtnlconvov.html

[U106] JS：日期格式化
来源：http://dali.guannengcc.top/Article/details/gtjnigfkgt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gtkgpcklmx.html

[U107] JS：数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtjtphfgdl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtbvxhifcg.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtigpqrldf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gtukvtcjad.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gtjftalmuv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtvsofprhe.html

[U110] JS：数组分块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfiofgmr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gtymawciwv.html

[U111] JS：对象转 Map
来源：http://dali.ppjwa.cn/Article/details/gteddtrcti.html

new Map(Object.entries(obj))
来源：http://dali.ppjwa.cn/Article/details/gtqhyituzl.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gthvozvhvo.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtbndqxjni.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gtgkcsgxea.html

s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtphuawtct.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gtpzplixua.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtiygwopzb.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gtmuenpmeg.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtayolfccl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aizwys.cn/Article/details/gtrofezccw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guowangkeji.top/Article/details/gtsphaioxc.html

[U117] JS：单元测试
来源：http://dali.guowangkeji.top/Article/details/gtoiuxqlhe.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxinkj.top/Article/details/gtfewjvjjz.html

[U118] JS：开发服务器
来源：http://dali.quarkkingdee.top/Article/details/gtjdnlwydr.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gtujvhubjq.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gtivimhsrc.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gttasodfpn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hysaishi.cn/Article/details/gtjqbekhje.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtsjfwfrvr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtebdsyqaw.html

统计汇总
来源：http://dali.316326.xyz/Article/details/gtlgiiqkvr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtitbpuxcl.html

按语言统计（条）：
来源：http://dali.wangdashe.top/Article/details/gtisqbijaa.html

Python ......... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmatibsx.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gtjcplwgoo.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gtmrjrphhu.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtmrdooohy.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtnbrofvjz.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gtsxmyzlqp.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gttgrfktxk.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfintxslv.html

C .............. 30
来源：http://dali.sufxvd.cn/Article/details/gtpwshetbt.html

C++ ............ 30
来源：http://dali.0kj1m.cn/Article/details/gtetelcznm.html

SQL ............ 90
来源：http://dali.hfpthk.cn/Article/details/gtaurbrist.html

Bash ........... 80
来源：http://dali.vqdsnc.cn/Article/details/gtfyotprsa.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtfmcevozd.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gtliemlboi.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gtojqijxek.html

Perl ........... 10
来源：http://dali.xylfe.cn/Article/details/gtnkeeegcj.html

Scala .......... 10
来源：http://dali.xylfe.cn/Article/details/gtzjetfvwg.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtpxwwiiwc.html

合计 ........... 2106 条
来源：http://dali.dianchejie.cn/Article/details/gtyfehufpw.html

按章节统计：
来源：http://dali.jinqigufen.top/Article/details/gtztxgowub.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtnmzvgfrl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqdhpbnz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtsnqwcqzg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtzbftpgft.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.redwolf501.top/Article/details/gtmxlxwnix.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gtjzjsktum.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtjnsqozhu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gtoizquwhd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtrlxqnxdl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtloxqiupb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gttzxbgcre.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtxhrrrqps.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtwxxhyjez.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gthdamrqej.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhmkqaxy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtqubhaczr.html

Q SQL 专题                              90
来源：http://dali.nwbrower.top/Article/details/gtcilqdfwl.html

R Bash 专题                             80
来源：http://dali.jyoumei.cn/Article/details/gtlybcisbv.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gtyvejmgss.html

T 其他语言补充                          60
来源：http://dali.hammf.cn/Article/details/gtllodhzpl.html

U 高频实用片段                         120
来源：http://dali.gotoacloud.top/Article/details/gtlsbanlft.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtbgaikufm.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gtetfdjvfl.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtkcfcdltr.html

使用提醒
来源：http://dali.c1oappe.top/Article/details/gtxrdvebkt.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtcnqyvoix.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenlongwang.top/Article/details/gtipysqocz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gtzdotbxnf.html


<!-- 参考信息 -->