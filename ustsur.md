代发 wailian999

val a = 1;  var b = 2
来源：http://dali.tianlin.xyz/Article/details/gtqhzlguna.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gturcqjfym.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtmsbwopen.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtsvqczryt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gtoldjukmy.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtejijrrko.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtiaggyiyo.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gtsvbntzri.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtvwxnnfcf.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtgfqmvctm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gthszbxkgh.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtmrsfunce.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtgbccicix.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtgagpdfxt.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtqallwlfl.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtdvxciebt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtvwibkqbh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtippfekqi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtjzppgsfk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrfyoitgs.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gtjzgisvao.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gzhubu.top/Article/details/gtytvxrrzf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtvvdsmkwk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtfckkssjz.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gttgnadxfs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtldiwfcjc.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtzajvpvii.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gtdrznunjf.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gtjfwnnxrt.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtvtvlhonz.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gtsdxyeepm.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtjtldukkj.html

[U07] Py：反转字典键值
来源：http://dali.yueranfly.top/Article/details/gtrdunqker.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gtxaudevqr.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gtwoozfowf.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gtqfrydhlc.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gtwzzpxtlp.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gtthnwcxpu.html

[U10] Py：按值排序字典
来源：http://dali.yonumen.top/Article/details/gtvyoqgufy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gtcxlgdjtl.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtveticdku.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gtgusysjkl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtzymzmafe.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtppgbsjyd.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gtvhhdfjwc.html

deque(maxlen=10)
来源：http://dali.0kj1m.cn/Article/details/gtlhgvlcdw.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gtfnoeflon.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtomrkfnsy.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtvcxgnhvn.html

t = time.perf_counter()
来源：http://dali.hammf.cn/Article/details/gtqyfussla.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtkakwmkga.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gteggkjael.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtlojdkkuv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gtbwvogygh.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gtgznyybxc.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtirnlmunu.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtyvpaqcig.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwmiiylm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gtownmstcl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtjwknsznu.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gtwmretzne.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gteoxefgxm.html

[U22] Py：矩阵转置
来源：http://dali.havefunace.top/Article/details/gtqvmhxmdy.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gtbpraxogf.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gtpkwuycbo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxtcszrn.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gtspovmtza.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtdouosxmp.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gtukytmmky.html

csv.DictReader(f)
来源：http://dali.gaohongyu789.top/Article/details/gteilxftwx.html

[U26] Py：并发下载
来源：http://dali.redwolf501.top/Article/details/gtlzuihanb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuetiantiany.cn/Article/details/gttbfhjkgr.html

[U27] Py：异步 HTTP
来源：http://dali.nanxuanxn.top/Article/details/gtojguxnky.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gteharjjqd.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtluwttlzf.html

UserId = int
来源：http://dali.yongpay.top/Article/details/gtupqbwxlx.html

[U29] Py：属性校验
来源：http://dali.sweek.top/Article/details/gtndsvwvoa.html

@property 与 @x.setter 配合
来源：http://dali.dianchejie.cn/Article/details/gthhovjjfs.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gtwvroltin.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gtpcwgxnkx.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gtbcmsezco.html

python -m pytest -q
来源：http://dali.jqgufenzy.top/Article/details/gtvxlrupht.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqnjbfhi.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gtneekdpvi.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtpviowyhf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigufen.top/Article/details/gtgoqvkkvb.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gtwslhfqsr.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtqzbhhcom.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtmgopipaq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gtanjuuohn.html

[U36] Py：定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtjwtnynks.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gtdcqdpirp.html

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gtfsdsrmar.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppbxtyvv.html

[U38] Py：获取脚本所在目录
来源：http://dali.hfpthk.cn/Article/details/gtxsjnrgql.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gtptiemvek.html

[U39] Py：判断是否在交互环境
来源：http://dali.redwolf501.top/Article/details/gtlqbmwdmp.html

sys.stdout.isatty()
来源：http://dali.hammf.cn/Article/details/gttbgcowkb.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gtbvgskgzg.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtphoeghoa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtzhnouxko.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yongpay.top/Article/details/gtevtnnxxx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gtwgeaykkl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gtfgzprrkk.html

[U43] PHP：声明命名空间
来源：http://dali.0kj1m.cn/Article/details/gtyjjvkkix.html

namespace App\Http;
来源：http://dali.xziqi.cn/Article/details/gtmosarfgn.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizmgmcwp.html

declare(strict_types=1);
来源：http://dali.daxiang520.top/Article/details/gtynzghydx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtajawjnac.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtqufxhlpj.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gtpxsjofne.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gtsbwuuyoz.html

[U47] PHP：联合类型
来源：http://dali.nanxinkj.top/Article/details/gtiaxpblld.html

int|string $id
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfdbybld.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gtvjtlylme.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.vqdsnc.cn/Article/details/gtauxdhkds.html

[U49] PHP：只读属性
来源：http://dali.tianlin.xyz/Article/details/gtzhvwqzry.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gttiqzakzy.html

[U50] PHP：构造器属性提升
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyrkxecn.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gtqzuaesje.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gtteohzfmk.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gtslkmexoi.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtkqknbgmo.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtgjfvspkj.html

[U53] PHP：空合并运算符
来源：http://dali.yangfankeji.com/Article/details/gtfhnygzfi.html

$v = $a ?? $b ?? "default";
来源：http://dali.yvedp.cn/Article/details/gtwfdtuxac.html

[U54] PHP：空安全调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfxtxruy.html

$obj?->method()
来源：http://dali.jqgufenzy.top/Article/details/gtambdapkc.html

[U55] PHP：match 表达式
来源：http://dali.sufxvd.cn/Article/details/gtufcxjqfs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtogwmraed.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpohjkat.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtelkgrryo.html

[U57] PHP：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtttswjmhq.html

"值: {$a}"
来源：http://dali.nwbrower.top/Article/details/gtiesahsfx.html

[U58] PHP：数组三件套
来源：http://dali.hysaishi.cn/Article/details/gtxdnnpbdi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gtyatuqguc.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gtrsdowkmv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtdyocgrlp.html

[U60] PHP：JSON 编解码
来源：http://dali.yj202588.top/Article/details/gtpaddqbkl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gtzckoldql.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtproawkyi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtpsqhrkzg.html

[U62] PHP：日期对象
来源：http://dali.yuanzhike.top/Article/details/gtpvkbprkt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gtrbvnfspv.html

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gtgehwxpkn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gteabljhlj.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gtkwzuqmzu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtzbzarfhb.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gtzvlagdpe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yongpay.top/Article/details/gtlkkygwjp.html

[U66] PHP：设置 Cookie
来源：http://dali.yuanzhike.top/Article/details/gtmwfoorar.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gtpnuaywqe.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gtnmhnglzp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258888.top/Article/details/gtesabcyui.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtmobybrca.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.havefunace.top/Article/details/gtrxirznye.html

[U69] PHP：PDO 预处理
来源：http://dali.fzhhl.top/Article/details/gtiwpkhleq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gtwpfiqngl.html

[U70] PHP：PDO 事务
来源：http://dali.zhengqikj.top/Article/details/gtfeljjaaq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258.top/Article/details/gtutgoziwl.html

[U71] PHP：抛出异常
来源：http://dali.redwolf501.top/Article/details/gttdeysvyz.html

throw new RuntimeException("失败", 500);
来源：http://dali.c1oappe.top/Article/details/gtewbjdkjs.html

[U72] PHP：写错误日志
来源：http://dali.fzhhl.top/Article/details/gtzdmuwokw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yueranfly.top/Article/details/gtdfihpjkt.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gtldsuxvci.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangtech.top/Article/details/gthhblzgka.html

[U74] PHP：读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgfgleyw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jianghu66.top/Article/details/gtjvvaqyhs.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gtqycijdhw.html

composer require psr/container
来源：http://dali.aibaodan.cn/Article/details/gtkyvnvpmj.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gtpwtbgpui.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gtwtpfiimz.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gttkdrnjwe.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gtdyxesyqx.html

[U78] PHP：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtjldpgugw.html

composer require --dev phpunit/phpunit
来源：http://dali.hywenlv.cn/Article/details/gthabnwzzl.html

[U79] PHP：静态分析
来源：http://dali.vqdsnc.cn/Article/details/gtmwmurqhv.html

composer require --dev phpstan/phpstan
来源：http://dali.nwbrower.top/Article/details/gtcbasladx.html

[U80] PHP：代码规范修复
来源：http://dali.dashuyun.cn/Article/details/gtwvikqrae.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ybcxt.top/Article/details/gtaqfudkaj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gtikcudxsv.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gtygqompqm.html

[U82] JS：package.json 脚本
来源：http://dali.zhoulong.xyz/Article/details/gttbdjotqm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gtjufhgmmg.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gtqqwsojhh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtmfftboiz.html

[U84] JS：CommonJS 写法
来源：http://dali.pycfn.com/Article/details/gtlszcnswc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gtwexafdug.html

[U85] JS：可选链
来源：http://dali.nanxuanxn.top/Article/details/gtemrbtrvh.html

a?.b?.c
来源：http://dali.yvedp.cn/Article/details/gtgkrlbzrg.html

[U86] JS：空值合并
来源：http://dali.yj202588.top/Article/details/gtkpcdcavz.html

a ?? b
来源：http://dali.zhoulong.xyz/Article/details/gtapqzmwfe.html

[U87] JS：解构默认值
来源：http://dali.yangfankeji.com/Article/details/gtpcnipujz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cucudq.cn/Article/details/gtguwidasj.html

[U88] JS：对象展开合并
来源：http://dali.smart0.xyz/Article/details/gtknjspqgc.html

{ ...a, ...b }
来源：http://dali.feifeiyinyue.top/Article/details/gtynbbvjal.html

[U89] JS：数组去重
来源：http://dali.shuidangran.top/Article/details/gtytunvflo.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtpnbwbfob.html

[U90] JS：数字数组排序
来源：http://dali.zdqjudy.top/Article/details/gtzafnygmm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtpwuuzerw.html

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gtetykdvwj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guowangkeji.top/Article/details/gtywraevxm.html

[U92] JS：深拷贝
来源：http://dali.yuxming.cn/Article/details/gtjyjqcxku.html

structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtvicfdvnt.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtqxdvgjrx.html

`共 ${n} 条`
来源：http://dali.yanxiufei.cn/Article/details/gtejcgpvok.html

[U94] JS：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtnpscwjgq.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gterkkrqwt.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gttvjltere.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtekknhvat.html

[U96] JS：async/await 与异常
来源：http://dali.c1oappe.top/Article/details/gtmxjlylbj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbqxmbpd.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gtrtbrmduc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtqwiubmqv.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gtwkglmdbl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.svipenyu.cn/Article/details/gtxjmfmeit.html

[U99] JS：事件监听
来源：http://dali.chenzaomai.com/Article/details/gtzduxsdxz.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gtpwrtduqf.html

[U100] JS：DOM 查询
来源：http://dali.kuanghao11.cn/Article/details/gthmokahsm.html

document.querySelector(".item")
来源：http://dali.andypj.xyz/Article/details/gtbmiebodl.html

[U101] JS：classList 操作
来源：http://dali.xylfe.cn/Article/details/gttawpufkv.html

el.classList.toggle("active")
来源：http://dali.redwolf501.top/Article/details/gtnxzolwea.html

[U102] JS：本地存储
来源：http://dali.yueranfly.top/Article/details/gtxxruwtdd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gtmziasjwj.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gtzwboaxkj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gtbapzedbq.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gtnrjafokp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtsxsllafr.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gtgklzcvdu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gtvigptanb.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gtbmlvmijs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gtfvxuxgru.html

[U107] JS：数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtkymuezap.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtgjyfqovr.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzwjqkzo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hongshengwenyu.top/Article/details/gtaijkabmz.html

[U109] JS：数组分组
来源：http://dali.cdnleiting.top/Article/details/gtsdtuwgpj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtnmvregia.html

[U110] JS：数组分块
来源：http://dali.chenzaomai.com/Article/details/gtheiymrxh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pycfn.com/Article/details/gthwfjzqqw.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtcotpkjwf.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtlrljbfqe.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gtgtmrumlg.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtzmmvvmdl.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gtkhiccbni.html

s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtuymidsce.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gtnfwnefbl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtdhcjyeau.html

[U115] JS：生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtqjyxfjcc.html

crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtgqfjaerm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gtyfiomvgu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtrdlcnjca.html

[U117] JS：单元测试
来源：http://dali.xinyue.icu/Article/details/gteveczktw.html

npm i -D vitest;  npx vitest
来源：http://dali.quarkkingdee.top/Article/details/gtqmwemqcl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gtfzieagfv.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtigusyitq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gthfqycpwz.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpiyxpcn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gtctecyhsh.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gtruxkzkhu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxtjidbex.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtdzifegia.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwjpjdddl.html

按语言统计（条）：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzslgdiok.html

Python ......... 252
来源：http://dali.ydzc1.top/Article/details/gttxjoosdl.html

PHP ............ 252
来源：http://dali.xuetiantiany.cn/Article/details/gtfaokhdun.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gtvnalluiw.html

TypeScript ..... 212
来源：http://dali.hywenlv.cn/Article/details/gtzprmdjep.html

Java ........... 212
来源：http://dali.chenlongwang.top/Article/details/gtxkboatzm.html

Go ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtiddoxkfr.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gtfmnsldto.html

C# ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtnuimyfrx.html

C .............. 30
来源：http://dali.kuanghao11.cn/Article/details/gtfwhhlyfk.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gtwhefqaul.html

SQL ............ 90
来源：http://dali.vqdsnc.cn/Article/details/gtxsstbwfz.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflmxdidd.html

Kotlin ......... 15
来源：http://dali.9152youxi.cn/Article/details/gttryhfzhh.html

Swift .......... 15
来源：http://dali.zhongyouzk.top/Article/details/gthgvnzmci.html

Lua ............ 10
来源：http://dali.daria6918.cn/Article/details/gtxzizavva.html

Perl ........... 10
来源：http://dali.yongpay.top/Article/details/gtgihaspxu.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gttkgeobwm.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtqxrbbfln.html

合计 ........... 2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkgywhmz.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqvmtjcw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtfjqjceep.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtvhyctgjb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtwluwvryk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtzlvivwef.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cdnleiting.top/Article/details/gtcvvzecvi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtnovhyfdv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtsdlxaobg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtukcpxwnt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtdanlwepo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gtmhrlivkp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtdnabxnpe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtzxneqxpk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtpxfaiwne.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtdvqplyll.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nwbrower.top/Article/details/gtsbqwvhzs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtkzvnfrda.html


<!-- 参考信息 -->