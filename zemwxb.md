代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtrbvybrmm.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtuhvtqhrm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yvedp.cn/Article/details/gtlayqsegs.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtjvavcdrc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gtlrtjwpwo.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gtsevjwtcl.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtgaggmjbz.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtsdmvdxsv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gteylfoqqb.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxchtizuc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtemxzauft.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxfctzsfs.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtadwzvrbl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gtschgvicg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtwfonsmap.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gtptxcwrag.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtqpqmcprz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtpppdihdn.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gtamwnfgfa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtfkhpraia.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtivwdicaj.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtybhoubqv.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnwlnfwh.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gtdlcrwgqj.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gtbqxzpssv.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtrlvtuqsy.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtuhlgltep.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gtraujhppy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gtttrrzieu.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtgwjyzeok.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gtgwnvltkj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtnrzxobgp.html

[U11] Py：生成器表达式
来源：http://dali.zhoulong.xyz/Article/details/gtichezhpm.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gtcupeuwti.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtorytnroc.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gtpzgoqeex.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gtfmtrhhfa.html

deque(maxlen=10)
来源：http://dali.jqgufenzy.top/Article/details/gtksrjzgly.html

[U14] Py：分组收集到列表
来源：http://dali.wangdashe.top/Article/details/gtlxcluvpl.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gteiwbvikj.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtzfwrikiu.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekyahevg.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gtjorgensy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tanke756.top/Article/details/gtyfllbfuj.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gtyhylzmfa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtnatcayof.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gtyqdzyqst.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtiuhyngan.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gtdoaxaqdt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gtsavkbetj.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gtfypfmdqj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuxming.cn/Article/details/gtmyladbfd.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gtzivubauc.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouxqzvqo.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gtqhljlgrg.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtwjsxbhbv.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gtbgsheyhd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gtcppllhef.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gtciizngmf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtqmwwxvcu.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gtoifdxonx.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gtqglwfeyu.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxjfccyz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gtoxerkdmm.html

[U27] Py：异步 HTTP
来源：http://dali.aibaodan.cn/Article/details/gtwlywajsf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daria6918.cn/Article/details/gtypvizixk.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtecnadige.html

UserId = int
来源：http://dali.ehwqpu.com/Article/details/gtkwxojino.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gtujvcnzoh.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gtpupeipja.html

[U30] Py：数据类
来源：http://dali.chenlongwang.top/Article/details/gtovuuvsis.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gttpxdzjsv.html

[U31] Py：单测
来源：http://dali.gotoacloud.top/Article/details/gtbypyzkug.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gthqugmbhi.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqbsvskm.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gtoelxwpml.html

[U33] Py：打包发布
来源：http://dali.316326.xyz/Article/details/gtljwnhsrq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gtqhrgckpj.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gtpecvqpnv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gtcfguiami.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gtmhuhmctq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nwbrower.top/Article/details/gthghczrvg.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtikqjobzn.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtphxvzvzh.html

[U37] Py：读写 Excel
来源：http://dali.9152youxi.cn/Article/details/gtepaplbqa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtarrsryrr.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gtbnxkdwos.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gtdycnrmzg.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gtjndzosvt.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gtzqhoojhi.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gtavdyurxl.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtvmpkewft.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gtrfqxcyek.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gtacvzozwv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gtqrvsubxs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gtnkrdqcyo.html

[U43] PHP：声明命名空间
来源：http://dali.xziqi.cn/Article/details/gtfpkrkfme.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gtkssirmth.html

[U44] PHP：开启严格类型
来源：http://dali.hongshengwenyu.top/Article/details/gttldddtgd.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gtnbzfygiy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gtircjthbk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gthrajsfyc.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gtpxeqalzg.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gtkhmvhkvr.html

[U47] PHP：联合类型
来源：http://dali.jiagoushi.top/Article/details/gtczbajruv.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gtpqiebkjh.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjfzxasu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxsadsgc.html

[U49] PHP：只读属性
来源：http://dali.sweek.top/Article/details/gtgimvhhhv.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxskrhht.html

[U50] PHP：构造器属性提升
来源：http://dali.chenzaomai.com/Article/details/gtwfoqbidk.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gtanjktzcq.html

[U51] PHP：数组解构
来源：http://dali.smart0.xyz/Article/details/gtuejsvifc.html

[$a, $b] = $arr;
来源：http://dali.smart0.xyz/Article/details/gtelufkkyp.html

[U52] PHP：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtpzyiuniz.html

$double = fn($x) => $x * 2;
来源：http://dali.dianchejie.cn/Article/details/gtlnxqaetr.html

[U53] PHP：空合并运算符
来源：http://dali.xziqi.cn/Article/details/gtxwpbtinq.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gtakgadpsg.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gtessyfjcy.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtrdaeipoz.html

[U55] PHP：match 表达式
来源：http://dali.yonumen.top/Article/details/gtbthuqavz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gtywauefji.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtxlinqrnk.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtuvgaayzu.html

[U57] PHP：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtpkthvlkm.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtbekdedgf.html

[U58] PHP：数组三件套
来源：http://dali.meibo888.top/Article/details/gtrgjwtdfb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.mhx1999.top/Article/details/gtnelmumjb.html

[U59] PHP：自定义排序
来源：http://dali.svipenyu.cn/Article/details/gtdodkgqit.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtfwzwobtf.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258.top/Article/details/gtrqttauez.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258888.top/Article/details/gtukuotojl.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtizaeoqad.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtvmmrcpcj.html

[U62] PHP：日期对象
来源：http://dali.cucudq.cn/Article/details/gtalaepwgx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gtlzxurfps.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtbjpkzmot.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gtqmtdsnix.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gtncdluncn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtzuosuynr.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gttokfcbve.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtolvnxjiw.html

[U66] PHP：设置 Cookie
来源：http://dali.xuanzx.com/Article/details/gtlqczftwe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gtrkpnsxzl.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gtxniivrxl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fzhhl.top/Article/details/gtvmwtrkvc.html

[U68] PHP：PDO 连接
来源：http://dali.jlsjyb.cn/Article/details/gtgzlfbqmg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cqqwz.cn/Article/details/gtxblqdnwf.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gtjzheqsxm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gttqbonkpa.html

[U70] PHP：PDO 事务
来源：http://dali.cheryme.top/Article/details/gtnteokdrx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gtvlzsjgfy.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gtbjsvqsfi.html

throw new RuntimeException("失败", 500);
来源：http://dali.xziqi.cn/Article/details/gtenyarcga.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gtyglzohoi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gtuxdhoxgi.html

[U73] PHP：读取 ini 配置
来源：http://dali.ydzc1.top/Article/details/gtemwuqbmg.html

parse_ini_file("config.ini", true)
来源：http://dali.xuanzx.com/Article/details/gtkznslfxu.html

[U74] PHP：读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gtvvvvrgcr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.haohaochexian.top/Article/details/gtxznjnrgx.html

[U75] PHP：依赖注入
来源：http://dali.ydzc1.top/Article/details/gtollseuvn.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtaiebllqw.html

[U76] PHP：简单路由
来源：http://dali.aizwys.cn/Article/details/gtapzutvss.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuxming.cn/Article/details/gtpqjgzesp.html

[U77] PHP：模板渲染
来源：http://dali.gzhubu.top/Article/details/gtgeqyjxay.html

composer require twig/twig
来源：http://dali.0kj1m.cn/Article/details/gtnxaaeceu.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtfqokkyto.html

composer require --dev phpunit/phpunit
来源：http://dali.zhengqikj.top/Article/details/gtgaojhlvr.html

[U79] PHP：静态分析
来源：http://dali.ybcxt.top/Article/details/gtnpxiecqm.html

composer require --dev phpstan/phpstan
来源：http://dali.yongpay.top/Article/details/gtaphzswly.html

[U80] PHP：代码规范修复
来源：http://dali.aizwys.cn/Article/details/gtyitkfmlg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gtdzxnejmn.html

[U81] JS：初始化项目
来源：http://dali.316326.xyz/Article/details/gtunwmxfia.html

npm init -y;  npm i express
来源：http://dali.cucudq.cn/Article/details/gtuodztpau.html

[U82] JS：package.json 脚本
来源：http://dali.wangshuangyany.cn/Article/details/gtzknjxugi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.feifeiyinyue.top/Article/details/gtbmylcsrg.html

[U83] JS：ES Module 导入导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnceswksi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gteeluwbyh.html

[U84] JS：CommonJS 写法
来源：http://dali.gzhubu.top/Article/details/gtvtmjzbdx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gtixtvmqjc.html

[U85] JS：可选链
来源：http://dali.guannengcc.top/Article/details/gthshblffr.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gttlsnkkrb.html

[U86] JS：空值合并
来源：http://dali.pengpengdd.cyou/Article/details/gtqnqiuafi.html

a ?? b
来源：http://dali.yongpay.top/Article/details/gtlhswwbzx.html

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gthgdgeipl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gotoacloud.top/Article/details/gtmvdnzhfx.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gtyfsxngdh.html

{ ...a, ...b }
来源：http://dali.zycfv.cn/Article/details/gtdiymndov.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gtnzmgvrdp.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtsuqnjeto.html

[U90] JS：数字数组排序
来源：http://dali.jiagoushi.top/Article/details/gtyovylvpw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gttogdxpde.html

[U91] JS：对象键值遍历
来源：http://dali.aizwys.cn/Article/details/gtxjstsoqf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zycfv.cn/Article/details/gtsyrfwbwt.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gtdwcvtezl.html

structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtqcmusuaa.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gtcdqanjyx.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gtqcdusnnr.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gtvbvnsrif.html

const double = x => x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtggaemorx.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gttgzukanl.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gttgkocqwb.html

[U96] JS：async/await 与异常
来源：http://dali.ybcxt.top/Article/details/gtyizrffvb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtctejiwzb.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gtxggyuthq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gthwrfravn.html

[U98] JS：fetch 带 JSON
来源：http://dali.birdmap.top/Article/details/gtoxobvyvb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fzhhl.top/Article/details/gtomuzgnfd.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gtevhkrkcy.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gttalovrhh.html

[U100] JS：DOM 查询
来源：http://dali.fzhhl.top/Article/details/gtbrdsmesu.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtarweprsj.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyppepnmi.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gttygcouru.html

[U102] JS：本地存储
来源：http://dali.jlsjyb.cn/Article/details/gtlkzxlrih.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.316326.xyz/Article/details/gtyuzpdtly.html

[U103] JS：定时器
来源：http://dali.zhixingplan.top/Article/details/gtvqnsalno.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gotoacloud.top/Article/details/gtpthbnxpk.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gtiysvrvjp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtkeghnbrv.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gtrghccjcj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfdihawj.html

[U106] JS：日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtwakwxnkd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gthrxkmzvg.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gtimlxgrwt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtsgfelyes.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gtwutfcgpi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gttpyrvsaf.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gtkgdukend.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtrkrsyocc.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gtqxlzjcrd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gtgoimcbne.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gtbpwxdqav.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gtcpbkdrkj.html

[U112] JS：字符串补位
来源：http://dali.jlsjyb.cn/Article/details/gtzzcjgexf.html

"7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtllyciuro.html

[U113] JS：正则替换全部
来源：http://dali.xuanzx.com/Article/details/gtcotubocj.html

s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gthafnhjlg.html

[U114] JS：JSON 深比较
来源：http://dali.yvedp.cn/Article/details/gtenpoiifm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtrtecmiha.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtbzgfivzz.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtqcthbrhj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gttpkbiedp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gtwxbnyrjr.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtyrwvbryt.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gtgpyojvwb.html

[U118] JS：开发服务器
来源：http://dali.meibo888.top/Article/details/gtjjzvkxxu.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gtughqhdbx.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gtlrmkkzyu.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtcwkfmcyd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gtrdpvxjkd.html

import.meta.env.VITE_API_URL
来源：http://dali.shangyingyoupin.top/Article/details/gtysevcdis.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwgrfkbye.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gtqznuycda.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwkjfjxea.html

按语言统计（条）：
来源：http://dali.cqqwz.cn/Article/details/gtjponznyx.html

Python ......... 252
来源：http://dali.xuanzx.com/Article/details/gtkjupekln.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gtpabrssyx.html

JavaScript ..... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqhbwvtu.html

TypeScript ..... 212
来源：http://dali.haohaochexian.top/Article/details/gtvpfmapig.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzojabrfw.html

Go ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtcaqljqjl.html

Ruby ........... 212
来源：http://dali.c1oappe.top/Article/details/gtvpuhdiie.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtexvacknu.html

C .............. 30
来源：http://dali.9152youxi.cn/Article/details/gtvudvwgbr.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gtdocyemnp.html

SQL ............ 90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmysawsd.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gtkrqdqowx.html

Kotlin ......... 15
来源：http://dali.guannengcc.top/Article/details/gtbtbemdpy.html

Swift .......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtqtjlpcad.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gtqsassbew.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtftkcmrzr.html

Scala .......... 10
来源：http://dali.svipenyu.cn/Article/details/gtrmedqdwi.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtrolhhxyv.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gtadbsxyaz.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gtbbmwvcrz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ybcxt.top/Article/details/gtloxqkven.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtykgdaxyb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtikgwbpix.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtmcarfjie.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guannengcc.top/Article/details/gtsieknbpa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gtoezevdse.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtkiwagess.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gththnclmd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtyrrsukmu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtxfatkkjc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtjxveduiy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtuyezeoid.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtbqlnbzvw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtsdzjbfah.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yangfankeji.com/Article/details/gtswrtzatk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtfgowljlq.html

Q SQL 专题                              90
来源：http://dali.andypj.xyz/Article/details/gtohqfxoxd.html

R Bash 专题                             80
来源：http://dali.aizwys.cn/Article/details/gtjfytiche.html

S C / C++ 专题                          60
来源：http://dali.cheryme.top/Article/details/gtaabxsstj.html

T 其他语言补充                          60
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdpdqthu.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gtpfswmtzf.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtywtvbldz.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gtzfjxpvdl.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtmwkbgmnl.html


<!-- 参考信息 -->