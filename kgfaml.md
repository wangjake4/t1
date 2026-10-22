代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gthwyhallr.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtxqocwnvm.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtiblteshs.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gtmxgswgtg.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtyauzqolu.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtdediirtj.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtynryhkxi.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gthepjpssz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvxlbsduq.html

[T55] Scala：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtrrcrjfox.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtustxrvmp.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtipxafyrt.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtxpjgujmu.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtpphphtla.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtcsntwmhl.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gtaswoezbq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gtzcuztqnk.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtwovbzdgj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtrxxhcrhc.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfylgloox.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gtncuivnzn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvzgivnsi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtzapemlan.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthuzqqxkz.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gtastjumeo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtzrlglcwk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxhelxqs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gthgreukkm.html

[U03] Py：加载 .env 配置
来源：http://dali.chenjidiqi.icu/Article/details/gthmfsgpep.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gttbhnugky.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtuekgcdvq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gthqkhwmfq.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gtebsdzwle.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtmteueabj.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gtrbxhhvge.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtkeegdymu.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtqhmfkugm.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gtnfmdkuyx.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtiupfkezy.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gtjozstjkd.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gtogeiguwp.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtzxagwnex.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsjluqfn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gthgzmtxbz.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtbxoazivr.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtsevuntit.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gtipdgrwjg.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gtublmginu.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gtccdkjxtf.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gttckvdhxt.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gtoemdmxpp.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtamklrwpl.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gtvzyjykgi.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gtwtdbsitp.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtobxwdjcy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gtxoracjyw.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtbnebyumm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhbzoiru.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtvowqonew.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtaniwjirh.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gtmjloncjh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gtedcnuplx.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gtbeiafghz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gtqoawumxq.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuydoqmt.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtuttouazy.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gtjegwrnxu.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gtpcjbfrws.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtowvigisl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gtiaubgspo.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gtqywmdklx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtdzxczdvo.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gtruqwjcbw.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gthnauhkup.html

[U26] Py：并发下载
来源：http://dali.yongpay.top/Article/details/gtdshhzpop.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtcymfopok.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtwchckesh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gtxtxpotqm.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gtwaneiurw.html

UserId = int
来源：http://dali.zhoulong.xyz/Article/details/gtvnkpawcc.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gtywfjdedv.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gtqapqtrsn.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gtblgnffii.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysvgzyeh.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gtaolonbgx.html

python -m pytest -q
来源：http://dali.yanxiufei.cn/Article/details/gtpfutveys.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gthvyttngm.html

ruff format . && ruff check --fix .
来源：http://dali.ivvv.top/Article/details/gtpktcggot.html

[U33] Py：打包发布
来源：http://dali.hfpthk.cn/Article/details/gtlwcqigme.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtoinwyiqk.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfauijmn.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gtcvctkdiv.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gtrxgdaepn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gzhubu.top/Article/details/gtgokuphmi.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gtcnyhwldi.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gtfmyrajnt.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gtssvrxwtk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.0kj1m.cn/Article/details/gtnopevyab.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyizltvh.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gtwwnuzjdl.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gtzdnltzuw.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangtech.top/Article/details/gtddxxcbap.html

[U40] Py：打印到标准错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwvpnvnj.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gttoenochh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtzkjhewqy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cdnleiting.top/Article/details/gteddedkhb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxinkj.top/Article/details/gtyrmewnhq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtwnnflwtt.html

[U43] PHP：声明命名空间
来源：http://dali.aibaodan.cn/Article/details/gtiyfbvvoy.html

namespace App\Http;
来源：http://dali.zhiwuduotai.top/Article/details/gtnausdcqg.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gtmuihquzz.html

declare(strict_types=1);
来源：http://dali.fengsongda.top/Article/details/gthyekulfr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gtnitjclja.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxvkgqdhj.html

[U46] PHP：可空类型
来源：http://dali.zhongyouzk.top/Article/details/gtlslnzefj.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gtqkqlykem.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gtjvrpblfs.html

int|string $id
来源：http://dali.xinyue.icu/Article/details/gtnsefqnap.html

[U48] PHP：纯枚举
来源：http://dali.zhoulong.xyz/Article/details/gtfidnlldq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxuanxn.top/Article/details/gtuzwhvxjp.html

[U49] PHP：只读属性
来源：http://dali.ybcxt.top/Article/details/gtjgfmzabq.html

public readonly string $name
来源：http://dali.mhx1999.top/Article/details/gtfuotymnb.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258888.top/Article/details/gtgzqbwbqs.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtrhfvdwdk.html

[U51] PHP：数组解构
来源：http://dali.yonumen.top/Article/details/gtnngxkgmz.html

[$a, $b] = $arr;
来源：http://dali.jqgfzy.top/Article/details/gtkyidywsq.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtltohkwes.html

$double = fn($x) => $x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtshzqhrus.html

[U53] PHP：空合并运算符
来源：http://dali.tianlin.xyz/Article/details/gttsvnzusk.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnxiangtu.top/Article/details/gtbbrxgujt.html

[U54] PHP：空安全调用
来源：http://dali.yuanzhike.top/Article/details/gtndcclxzl.html

$obj?->method()
来源：http://dali.jinqigfzy.top/Article/details/gtszwnrgzh.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gtwdkvgnez.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpabovhw.html

[U56] PHP：命名参数
来源：http://dali.chenlongwang.top/Article/details/gtaquluuza.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtjwnhnfbn.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtouyzoihc.html

"值: {$a}"
来源：http://dali.gogol.net.cn/Article/details/gtlmsycdmq.html

[U58] PHP：数组三件套
来源：http://dali.gogol.net.cn/Article/details/gtxclztalu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cucudq.cn/Article/details/gtjgnoqizc.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtadnthtth.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtpsyiiwtn.html

[U60] PHP：JSON 编解码
来源：http://dali.pengpengdd.cyou/Article/details/gtaushiiou.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtfwqpqtfx.html

[U61] PHP：正则
来源：http://dali.gogol.net.cn/Article/details/gtersznsus.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtqvvgypkb.html

[U62] PHP：日期对象
来源：http://dali.dashuyun.cn/Article/details/gtjehsgtwh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gaohongyu789.top/Article/details/gtualtuggy.html

[U63] PHP：文件读写
来源：http://dali.zdqjudy.top/Article/details/gtninhwnst.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.havefunace.top/Article/details/gtxtagsggz.html

[U64] PHP：目录遍历
来源：http://dali.jiagoushi.top/Article/details/gtsbqfvxkq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtoodncfic.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gtjlpxiozt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtcfulufsm.html

[U66] PHP：设置 Cookie
来源：http://dali.tian-w.cn/Article/details/gtcbwcobol.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258.top/Article/details/gttwscqkor.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gtuoncxwbr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgfzy.top/Article/details/gtgphuiymj.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gtnscfkkmr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj20258.top/Article/details/gteijhsusf.html

[U69] PHP：PDO 预处理
来源：http://dali.xuetiantiany.cn/Article/details/gtdcggsijy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gtfhobygph.html

[U70] PHP：PDO 事务
来源：http://dali.bjfxy.top/Article/details/gtusabuwrb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gtrzjpipji.html

[U71] PHP：抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtpbuguuby.html

throw new RuntimeException("失败", 500);
来源：http://dali.c1oappe.top/Article/details/gtoocartoc.html

[U72] PHP：写错误日志
来源：http://dali.cdnleiting.top/Article/details/gtwpbzimen.html

error_log("失败: " . $e->getMessage());
来源：http://dali.snrcjt.cn/Article/details/gtlvidhcjn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsylwldrj.html

parse_ini_file("config.ini", true)
来源：http://dali.feifeiyinyue.top/Article/details/gtrwwtukii.html

[U74] PHP：读取环境变量
来源：http://dali.sxryk.cn/Article/details/gthddmxyum.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cashguo.top/Article/details/gtxmfwqihv.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gtusuzimvl.html

composer require psr/container
来源：http://dali.havefunace.top/Article/details/gtbtkqorfd.html

[U76] PHP：简单路由
来源：http://dali.zdqjudy.top/Article/details/gtjcviksui.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gtqkokvkyw.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gtpdeugqtn.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gtkgzntxkz.html

[U78] PHP：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtrwvymgab.html

composer require --dev phpunit/phpunit
来源：http://dali.hnxiangtu.top/Article/details/gtavxqmwpb.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzirtqxn.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gtqyzpmwmq.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtqrtxadtm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigufen.top/Article/details/gtizztnibx.html

[U81] JS：初始化项目
来源：http://dali.quarkkingdee.top/Article/details/gtkbtsbxus.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gtchzvtiyc.html

[U82] JS：package.json 脚本
来源：http://dali.tanke756.top/Article/details/gtgjsbehbt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtdcrxhyjx.html

[U83] JS：ES Module 导入导出
来源：http://dali.xylfe.cn/Article/details/gtuycbztfa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtnpvfsjdn.html

[U84] JS：CommonJS 写法
来源：http://dali.cucudq.cn/Article/details/gtfaayrohj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpmwpago.html

[U85] JS：可选链
来源：http://dali.yonumen.top/Article/details/gtaqjhegkb.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gtehahcwbp.html

[U86] JS：空值合并
来源：http://dali.gogol.net.cn/Article/details/gtywiuyguc.html

a ?? b
来源：http://dali.zdqjudy.top/Article/details/gtyegjqvzj.html

[U87] JS：解构默认值
来源：http://dali.gogol.net.cn/Article/details/gtdrppnqrj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhixingplan.top/Article/details/gtbyncldwb.html

[U88] JS：对象展开合并
来源：http://dali.jianghu66.top/Article/details/gtkmkdxegg.html

{ ...a, ...b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgswftqq.html

[U89] JS：数组去重
来源：http://dali.yj20258888.top/Article/details/gtqxivlixs.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtnwrhnvdx.html

[U90] JS：数字数组排序
来源：http://dali.sufxvd.cn/Article/details/gthhtssjrh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtqpshpeio.html

[U91] JS：对象键值遍历
来源：http://dali.xuanzx.com/Article/details/gtvmuxovty.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gtrqznkzkh.html

[U92] JS：深拷贝
来源：http://dali.cucudq.cn/Article/details/gtcdykhvle.html

structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtycmdixgc.html

[U93] JS：模板字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmhvxmrq.html

`共 ${n} 条`
来源：http://dali.snrcjt.cn/Article/details/gtsgcrwloc.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gteubpqvqc.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtcfnqhfoo.html

[U95] JS：Promise 包装
来源：http://dali.zhengqikj.top/Article/details/gtqoxexjcy.html

new Promise((resolve, reject) => {})
来源：http://dali.shuidangran.top/Article/details/gtplisbuyg.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gtvvjqptox.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtnaaykhsg.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gtsswxodif.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtowwvbkwv.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gtyxxamumw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gtxpytvouw.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gtszmowpvm.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gtgxzmcgin.html

[U100] JS：DOM 查询
来源：http://dali.jianghu66.top/Article/details/gtgmbvvdcj.html

document.querySelector(".item")
来源：http://dali.yueranfly.top/Article/details/gtwcincmtz.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gttdrbjaqi.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gtycvzcllk.html

[U102] JS：本地存储
来源：http://dali.dianchejie.cn/Article/details/gtytsqchxa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gteuwzcxou.html

[U103] JS：定时器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntbuhcke.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.bjfxy.top/Article/details/gtxabzbeeh.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gtmntoggkh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtrgzxxqxz.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtgvgbuobn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gtehqypuod.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtnvkmcnhs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gtnqoedeep.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gtmrxkvqrb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtdowyvzsc.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtosiwgkth.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daria6918.cn/Article/details/gtevikrgmr.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhdiwlpq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtgagleiii.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gtbaveytyh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258888.top/Article/details/gtipbqffyz.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtwcthdymt.html

new Map(Object.entries(obj))
来源：http://dali.xylfe.cn/Article/details/gtcuyuxptv.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gtsnspypwf.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtkmvjjcrd.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtomlkutuc.html

s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtvrzlitje.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gtgpqzzjws.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtevbvcjpj.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gtucxavmno.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtfapmpumj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxuanxn.top/Article/details/gtimljdgvk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gthgfpbfjn.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtvtltbyuu.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gtvautbdwv.html

[U118] JS：开发服务器
来源：http://dali.c1oappe.top/Article/details/gtdpxgvnic.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtdmxhikww.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gtxoapumfa.html

npx vite build
来源：http://dali.feifeiyinyue.top/Article/details/gtnrdnrctc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gtbyzxfwlr.html

import.meta.env.VITE_API_URL
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppwnnmcf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbztgkwgw.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gtcbvbeswl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfqcajarh.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gthqtkymly.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gtbgpkpmjl.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gtqpglcihh.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtyaawvrbi.html

TypeScript ..... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtmohdqlfi.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gtkuiucfrg.html

Go ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtecawfmhx.html

Ruby ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtzhfpmhko.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gtwbncqvhq.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gtgazvmhwk.html

C++ ............ 30
来源：http://dali.yj20258.top/Article/details/gtnmdhylha.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gtxpqpzasp.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gtvrobfpwp.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtvtcfns.html

Swift .......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtkanyokdu.html

Lua ............ 10
来源：http://dali.redwolf501.top/Article/details/gtuyyfujmf.html

Perl ........... 10
来源：http://dali.nwbrower.top/Article/details/gtwgudsxvy.html

Scala .......... 10
来源：http://dali.chenzaomai.com/Article/details/gtneibnslf.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhfzqmyu.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gtmpsatrpb.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gtwhwtbgep.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gtawgmfmnw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkbgylql.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrriipbw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gthcunyayc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ydzc1.top/Article/details/gtvqmgtpcg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gtusfdctgo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtsetdrzyi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtwkmvsrvo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gttxejlouh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gtqsuthbqp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtjopusaie.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtftjpdgqe.html


<!-- 参考信息 -->