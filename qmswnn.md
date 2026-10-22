代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2clxaxqcz.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2cjzviskd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xevrtjhh.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gt2cztlwife.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gt2lkeluihm.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gt2aukaatux.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gt2xcfkkbbn.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2zbsorbok.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gt2egunhaeb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2alriayfe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gt2iwhptgdp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2uqdxrsoq.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gt2fkodslla.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxinkj.top/Article/details/gt2hcakunbj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gt2wpuyvnkf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.iojbl.cn/Article/details/gt2uofbttgw.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gt2hdrghbhl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gt2wjlvkwzm.html

[U04] Py：变量调试打印
来源：http://dali.mhx1999.top/Article/details/gt2cuyvsybl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gt2wywluejb.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gt2xvetrevi.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2xulugrvx.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gt2ghxpbtdl.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gt2wdegecbb.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gt2afychxvf.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gt2pcmtbuij.html

[U08] Py：展平二维列表
来源：http://dali.cheryme.top/Article/details/gt2dqdiybeb.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gt2pgzzzrxw.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gt2nwryzhwg.html

max(d, key=d.get)
来源：http://dali.cqqwz.cn/Article/details/gt2mlumwodu.html

[U10] Py：按值排序字典
来源：http://dali.zhoulong.xyz/Article/details/gt2rrtiawyr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2sjkuuzry.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gt2lzjilcos.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2zfnqwgyo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gt2prggsckn.html

Counter(arr).most_common(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2lwqscxrv.html

[U13] Py：固定长度队列
来源：http://dali.sxryk.cn/Article/details/gt2dwaxctaw.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gt2ibqiblcn.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gt2aqycyxkg.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gt2lsveohll.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gt2zhwwthzg.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gt2qnlwqjkt.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gt2hoeychxg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdueuqtf.html

[U17] Py：初始化日志
来源：http://dali.meibo888.top/Article/details/gt2woqthapl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gt2knznqwzx.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snfkwagn.html

pat = re.compile(r"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2lxcfwhkr.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gt2zzkhttvz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cashguo.top/Article/details/gt2amjmhtvu.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gt2sesudnzz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gt2hlzrhoio.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gt2sjmvuylc.html

@contextlib.contextmanager
来源：http://dali.zhongyouzk.top/Article/details/gt2ubkobyzf.html

[U22] Py：矩阵转置
来源：http://dali.birdmap.top/Article/details/gt2mkimjind.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gt2cfmxqjom.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gt2bvewgket.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gt2lllnrhgt.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gt2fyhrtlwp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2gnanaqzo.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtjwzouv.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gt2ssnsuxox.html

[U26] Py：并发下载
来源：http://dali.nanxuanxn.top/Article/details/gt2gteygqcr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcweaook.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmyyfxvl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gt2wzyjxgas.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gt2mwtqkbfq.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gt2xhpdfxjn.html

[U29] Py：属性校验
来源：http://dali.hammf.cn/Article/details/gt2icrouzwp.html

@property 与 @x.setter 配合
来源：http://dali.havefunace.top/Article/details/gt2htqfkweg.html

[U30] Py：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdqvnywn.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gt2xezunyuj.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gt2kwkctmbj.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouijhzcw.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gt2vzmncilv.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gt2nzfoxkvt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kteitrvf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.0kj1m.cn/Article/details/gt2zizatvdc.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgkkfpzk.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gt2cqalcsyz.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqgzbkrw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jakkkfgp.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gt2vmyuiaae.html

schedule.every(10).minutes.do(job)
来源：http://dali.ydzc1.top/Article/details/gt2emsrshgt.html

[U37] Py：读写 Excel
来源：http://dali.gogol.net.cn/Article/details/gt2bbmkzpte.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuxming.cn/Article/details/gt2iddfeasm.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gt2mekbbpev.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veqqkxrz.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gt2jhwkwpeh.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gt2fndixesc.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigufen.top/Article/details/gt2cvdufvbm.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2bvtjvubr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pycfn.com/Article/details/gt2iypkhzjt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gt2qcjyrndo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.guannengcc.top/Article/details/gt2wxcrwdss.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gt2xebuoodr.html

[U43] PHP：声明命名空间
来源：http://dali.yueranfly.top/Article/details/gt2xvrziqky.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gt2ggntopyo.html

[U44] PHP：开启严格类型
来源：http://dali.cqqwz.cn/Article/details/gt2izphrxsm.html

declare(strict_types=1);
来源：http://dali.yj202588.top/Article/details/gt2tvyjrdee.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sxryk.cn/Article/details/gt2oziyouel.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2bbnlhnpa.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gt2ejeiqmth.html

?string $name = null
来源：http://dali.ppjwa.cn/Article/details/gt2kwmvvoou.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gt2jhltaabb.html

int|string $id
来源：http://dali.guannengcc.top/Article/details/gt2bycgpego.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gt2tukdyutb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2figfoaph.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gt2nlphhutq.html

public readonly string $name
来源：http://dali.ivvv.top/Article/details/gt2qkozrlue.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmxherqf.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gt2zbgqppgf.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gt2gvxzqfvg.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gt2aebalkoq.html

[U52] PHP：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gt2hlxmvxpt.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gt2oiumrryc.html

[U53] PHP：空合并运算符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtlqucho.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gt2kypygmnc.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gt2fhuobanv.html

$obj?->method()
来源：http://dali.zhengqikj.top/Article/details/gt2udstezzj.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdrlpfqb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gt2cxgecwon.html

[U56] PHP：命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2unliqmub.html

f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2siulrdvy.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2orjyyfnu.html

"值: {$a}"
来源：http://dali.yuanzhike.top/Article/details/gt2kgvakygi.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gt2yptlkspj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpoabctg.html

[U59] PHP：自定义排序
来源：http://dali.wangdashe.top/Article/details/gt2exubfqhy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gt2mcwcuqar.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gt2jgenetjh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sweek.top/Article/details/gt2tncnavpq.html

[U61] PHP：正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zadobraf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jubgexjf.html

[U62] PHP：日期对象
来源：http://dali.xinyue.icu/Article/details/gt2vxpayqat.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gogol.net.cn/Article/details/gt2tbaerozb.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjizgwgn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gt2wmdxjaps.html

[U64] PHP：目录遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2gusmdhef.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yueranfly.top/Article/details/gt2xwjxnsdf.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gt2ycrqabux.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2brgzvxhp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhoulong.xyz/Article/details/gt2jnhbwbmo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xinyue.icu/Article/details/gt2odxzlmmi.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gt2zcfrtbzz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.smart0.xyz/Article/details/gt2jeethbgl.html

[U68] PHP：PDO 连接
来源：http://dali.jlsjyb.cn/Article/details/gt2ahfxanwy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gt2vhbxnsut.html

[U69] PHP：PDO 预处理
来源：http://dali.hysaishi.cn/Article/details/gt2vugmgfvp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryrzylac.html

[U70] PHP：PDO 事务
来源：http://dali.yanxiufei.cn/Article/details/gt2zxxdfbxr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yangfankeji.com/Article/details/gt2jenzclrj.html

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2ynrecwpu.html

throw new RuntimeException("失败", 500);
来源：http://dali.cucudq.cn/Article/details/gt2jfnissur.html

[U72] PHP：写错误日志
来源：http://dali.shuidangran.top/Article/details/gt2nnmhdwel.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpggbjhw.html

[U73] PHP：读取 ini 配置
来源：http://dali.jiagoushi.top/Article/details/gt2nhrscprm.html

parse_ini_file("config.ini", true)
来源：http://dali.wangdashe.top/Article/details/gt2vyfxjqgc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2liuwimjz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhixingplan.top/Article/details/gt2irwbyhpq.html

[U75] PHP：依赖注入
来源：http://dali.ydzc1.top/Article/details/gt2bgvwnocp.html

composer require psr/container
来源：http://dali.jianghu66.top/Article/details/gt2qtybxxwy.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gt2wrmnoowf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guannengcc.top/Article/details/gt2zzhhfmgh.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gt2zywsovjc.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gt2jmbytikh.html

[U78] PHP：单元测试
来源：http://dali.xuanzx.com/Article/details/gt2bctxhsnx.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gt2vzrjparo.html

[U79] PHP：静态分析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkewwbgk.html

composer require --dev phpstan/phpstan
来源：http://dali.316326.xyz/Article/details/gt2ipkazfud.html

[U80] PHP：代码规范修复
来源：http://dali.c1oappe.top/Article/details/gt2wulgsjcx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yueranfly.top/Article/details/gt2yskommgy.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gt2sfzpgeki.html

npm init -y;  npm i express
来源：http://dali.yuxming.cn/Article/details/gt2bouqxzab.html

[U82] JS：package.json 脚本
来源：http://dali.xuanzx.com/Article/details/gt2gfnsaimo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfwqcbzs.html

[U83] JS：ES Module 导入导出
来源：http://dali.dianchejie.cn/Article/details/gt2qnizvzgn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gt2tyatlyyk.html

[U84] JS：CommonJS 写法
来源：http://dali.gogol.net.cn/Article/details/gt2qnuygjxb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ydzc1.top/Article/details/gt2gtneqlky.html

[U85] JS：可选链
来源：http://dali.cashguo.top/Article/details/gt2zjgsaqfb.html

a?.b?.c
来源：http://dali.yuanzhike.top/Article/details/gt2aychxvox.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgwmmdpy.html

a ?? b
来源：http://dali.chenjidiqi.icu/Article/details/gt2lckkmojm.html

[U87] JS：解构默认值
来源：http://dali.hnxiangtu.top/Article/details/gt2fqwxmxlw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gt2mlkeovil.html

[U88] JS：对象展开合并
来源：http://dali.zycfv.cn/Article/details/gt2izcnwgax.html

{ ...a, ...b }
来源：http://dali.sxryk.cn/Article/details/gt2xvmymsov.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gt2ucciabyx.html

[...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2qspctqjr.html

[U90] JS：数字数组排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktdlhgyk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2soifiptf.html

[U91] JS：对象键值遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2dssbfcxq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sufxvd.cn/Article/details/gt2itqdvqrk.html

[U92] JS：深拷贝
来源：http://dali.yonumen.top/Article/details/gt2iovhpvhy.html

structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywzwteyp.html

[U93] JS：模板字符串
来源：http://dali.shzxlz.cn/Article/details/gt2vrsjvcsp.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gt2souxoyoz.html

[U94] JS：箭头函数
来源：http://dali.jianghu66.top/Article/details/gt2ffoqcjcc.html

const double = x => x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gt2hyvrcadd.html

[U95] JS：Promise 包装
来源：http://dali.meibo888.top/Article/details/gt2vypjvyzc.html

new Promise((resolve, reject) => {})
来源：http://dali.xylfe.cn/Article/details/gt2upcyhaka.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gt2pzepdboc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbpwffez.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gt2snmutlaz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2mxusccrs.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2yazhashy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.c1oappe.top/Article/details/gt2mgetmubi.html

[U99] JS：事件监听
来源：http://dali.xuanzx.com/Article/details/gt2frilbpto.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gt2fhlnmilx.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gt2uprudqke.html

document.querySelector(".item")
来源：http://dali.kuanghao11.cn/Article/details/gt2nmrtjsuk.html

[U101] JS：classList 操作
来源：http://dali.cashguo.top/Article/details/gt2csnubvso.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gt2lgjmjlnr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhyxocx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ppjwa.cn/Article/details/gt2ewonnbve.html

[U103] JS：定时器
来源：http://dali.bjfxy.top/Article/details/gt2wveyngit.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gt2uujotpow.html

[U104] JS：防抖
来源：http://dali.sweek.top/Article/details/gt2wquseocw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2ibdxvllv.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gt2joewlnfl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuanzhike.top/Article/details/gt2qbxbqkbz.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2iouawyzh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhongyouzk.top/Article/details/gt2ngxcwjdt.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gt2michvzop.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gt2qmszvpzz.html

[U108] JS：随机整数
来源：http://dali.nanxinkj.top/Article/details/gt2jyblfynh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuetiantiany.cn/Article/details/gt2crswjcyo.html

[U109] JS：数组分组
来源：http://dali.chenlongwang.top/Article/details/gt2brubzruv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gt2suwmmnjt.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gt2xtsdguqr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jlsjyb.cn/Article/details/gt2rlcyxhrl.html

[U111] JS：对象转 Map
来源：http://dali.ehwqpu.com/Article/details/gt2dgbjrfhq.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2vjmgrmwv.html

[U112] JS：字符串补位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trduukbi.html

"7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2rlfvvgjo.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gt2tfxpmdtk.html

s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2wpoqtneh.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gt2yxwaspvw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gt2uyzbiijo.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gt2gxajtvfu.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlwlyovt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xylfe.cn/Article/details/gt2wsmoxfkk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gt2wnuynhju.html

[U117] JS：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gt2xeeoopfu.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gt2mwmskhvl.html

[U118] JS：开发服务器
来源：http://dali.hysaishi.cn/Article/details/gt2rdmcizck.html

npm i -D vite;  npx vite
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpqxnpjh.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gt2cikidvfj.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gt2qeryumot.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.snrcjt.cn/Article/details/gt2ovanmmso.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigufen.top/Article/details/gt2snqhhwbp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ryxopqux.html

统计汇总
来源：http://dali.andypj.xyz/Article/details/gt2pxssqxlg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ohjfgdou.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gt2biqgmbpf.html

Python ......... 252
来源：http://dali.chenzaomai.com/Article/details/gt2mrenuiwu.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gt2tdxwvuvq.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gt2dlxndfys.html

TypeScript ..... 212
来源：http://dali.tianlin.xyz/Article/details/gt2hnwtwxqz.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gt2xlcqrvhw.html

Go ............. 212
来源：http://dali.zdqjudy.top/Article/details/gt2tltytrij.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gt2qcxiufkc.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gt2veibtsqm.html

C .............. 30
来源：http://dali.cdnleiting.top/Article/details/gt2lhiryaoj.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2makijzqn.html

SQL ............ 90
来源：http://dali.xinyue.icu/Article/details/gt2wstbkalc.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gt2qwexdnqx.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gt2uzgvuwez.html

Swift .......... 15
来源：http://dali.yj20258.top/Article/details/gt2lkngudtu.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eoytyllg.html

Perl ........... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oaalaobx.html

Scala .......... 10
来源：http://dali.chenlongwang.top/Article/details/gt2egkxolov.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2nrljzaxw.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoteetrd.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gt2ovaywoyd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gt2qzokbzja.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2gyyrrbho.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2ygznpyuv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gt2hnutkshl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gt2xqffuqtu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gt2dfhzwgok.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gt2ioqtdoxw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gt2ksdqybfy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2ypxnzdnq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gt2fpihhfwv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2sangefwf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gt2ieyfmptr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gt2ulthljia.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gt2japiacjh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.iojbl.cn/Article/details/gt2ohpjpasp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2xejbyabc.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gt2alwzprar.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gt2sbltipgb.html

S C / C++ 专题                          60
来源：http://dali.nanxuanxn.top/Article/details/gt2cscigaiu.html

T 其他语言补充                          60
来源：http://dali.hammf.cn/Article/details/gt2mezmseat.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gt2delvfmfa.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2ogfkcqxs.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzlrrxsh.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2tfgsqqor.html


<!-- 参考信息 -->