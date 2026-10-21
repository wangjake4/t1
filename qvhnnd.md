代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirrpvibl.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtjsxuanup.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtoypthxog.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gtmdhtjvln.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gtswfvuydp.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtaowbxvfo.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtqdsetvdv.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gtkcyhiekb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtrmsacpny.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbvjuksxm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtxfctwdpl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtppryskbo.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtuoubjjue.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sysykeji.top/Article/details/gtcmfolvmx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gtomalpwwq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gthjktonan.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigfzy.top/Article/details/gtlfarrdfb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gtuwowcavt.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtuyrhykei.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtonsdgfxe.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gtzlgvumjg.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtbapnlaqo.html

[U06] Py：合并两个字典
来源：http://dali.yuanzhike.top/Article/details/gtypnslfgi.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpjmpqcl.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtcuidwwqu.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gtysrtkaic.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtpjebatwv.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gthrdjwtvx.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtxukqphcn.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gtctvzdtrd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gtduspeudo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtehjfrtrq.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtdabuejtk.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtqklehscj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gtpaxzgdde.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gtnkrtkaol.html

[U13] Py：固定长度队列
来源：http://dali.zhiwuduotai.top/Article/details/gtjdaydmlx.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtoorsdgki.html

[U14] Py：分组收集到列表
来源：http://dali.cashguo.top/Article/details/gtgyrsuukc.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gtmlqctgvk.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtnowuxzjf.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gtdmyoscjv.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gtdsernozr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gtkkfhblkp.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtvwouxfol.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtqngbgvvy.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtiephibfz.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gtmgtgtctf.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gtsasqucjr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gtvkvqcdzo.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gtjwyndele.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gtwgbfgrox.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjmfxzld.html

@contextlib.contextmanager
来源：http://dali.yuanzhike.top/Article/details/gtxirnvted.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gtwhtuxikp.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gtacopowvs.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtbxbolmxk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtomrttsho.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gtuxnjrqcq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtaaxsbhoj.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtbnqsdwep.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gttbehigbt.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gtnamxmupp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtazibezim.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtlqcwilwk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gtdulzhjdc.html

[U28] Py：类型别名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwxzqhmn.html

UserId = int
来源：http://dali.tianlin.xyz/Article/details/gtzhbytlww.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gtbuuqmoeg.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtpwonybbb.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtwlijqykn.html

@dataclass(slots=True)
来源：http://dali.shuidangran.top/Article/details/gtcxaqezoh.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwixrhvb.html

python -m pytest -q
来源：http://dali.hysaishi.cn/Article/details/gtznddqvoo.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gtdgnwuflz.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtgjfhjgwp.html

[U33] Py：打包发布
来源：http://dali.jqgufenzy.top/Article/details/gtbkhcafyi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jlsjyb.cn/Article/details/gtshgzyxgl.html

[U34] Py：判断编码
来源：http://dali.wangshuangyany.cn/Article/details/gttkgkolxi.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtxgyjpi.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gtnykwopjg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gtkweheqed.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gtbwmemtfz.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtlqayylvc.html

[U37] Py：读写 Excel
来源：http://dali.fengsongda.top/Article/details/gtjzeqmqac.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xziqi.cn/Article/details/gtmnqakjlz.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtevhooxnt.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gtnkmeczln.html

[U39] Py：判断是否在交互环境
来源：http://dali.smart0.xyz/Article/details/gtfumzpumr.html

sys.stdout.isatty()
来源：http://dali.xuetiantiany.cn/Article/details/gtguwlrsxe.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gtfjuvrner.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtufxkibjq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtutyuvpyr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnxiangtu.top/Article/details/gtdnpmsijo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zdqjudy.top/Article/details/gtnudpyevv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gtansnohfh.html

[U43] PHP：声明命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtifecxxxp.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gtdazgufeh.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gtyxrfagdj.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gtrcaoeaym.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnxiangtu.top/Article/details/gtgrwdtrei.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtvtakcyab.html

[U46] PHP：可空类型
来源：http://dali.cqqwz.cn/Article/details/gtaaffwizv.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gtrlcybdgq.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gtbjmsfnwc.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gttskanjpn.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtglvhecai.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpipmspol.html

[U49] PHP：只读属性
来源：http://dali.shzxlz.cn/Article/details/gttitjwliq.html

public readonly string $name
来源：http://dali.jiagoushi.top/Article/details/gttdtndyww.html

[U50] PHP：构造器属性提升
来源：http://dali.hywenlv.cn/Article/details/gtihaacauc.html

public function __construct(private int $id) {}
来源：http://dali.ppjwa.cn/Article/details/gtntrigcro.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtegednduv.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtlbprvyuj.html

[U52] PHP：箭头函数
来源：http://dali.sufxvd.cn/Article/details/gtiskjdbnc.html

$double = fn($x) => $x * 2;
来源：http://dali.aizwys.cn/Article/details/gthznxjmij.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gteczyujlx.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpflorjtp.html

[U54] PHP：空安全调用
来源：http://dali.yangfankeji.com/Article/details/gtpmdtteqa.html

$obj?->method()
来源：http://dali.bjfxy.top/Article/details/gtaiixridg.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gtcjpwqavg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.meibo888.top/Article/details/gtmjvolaqr.html

[U56] PHP：命名参数
来源：http://dali.tianlin.xyz/Article/details/gtgglqdiwy.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtapuswqox.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtoshbmmiz.html

"值: {$a}"
来源：http://dali.hfpthk.cn/Article/details/gttgshaepj.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gtagkmkosc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtnpfdncpq.html

[U59] PHP：自定义排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmahbdba.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtqsupnsie.html

[U60] PHP：JSON 编解码
来源：http://dali.hnqzz.top/Article/details/gtovsiyxqx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqecpmqyv.html

[U61] PHP：正则
来源：http://dali.sweek.top/Article/details/gtlgxlwito.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtdawwndkm.html

[U62] PHP：日期对象
来源：http://dali.havefunace.top/Article/details/gtwjtmddzz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pengpengdd.cyou/Article/details/gtxkgrplzz.html

[U63] PHP：文件读写
来源：http://dali.feifeiyinyue.top/Article/details/gthlyemgkp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dashuyun.cn/Article/details/gtrwhzjhuu.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gtercxdjzg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.kuanghao11.cn/Article/details/gtppxdrbat.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gtbjuqltjp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtfpkynawf.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gtsvsuxtkc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jianghu66.top/Article/details/gtfibppizd.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtvwbnfren.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxuanxn.top/Article/details/gtubspmllr.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtokeanthn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.0kj1m.cn/Article/details/gtcretakzc.html

[U69] PHP：PDO 预处理
来源：http://dali.sweek.top/Article/details/gtgtighjzr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jianghu66.top/Article/details/gtqomqmvzi.html

[U70] PHP：PDO 事务
来源：http://dali.aibaodan.cn/Article/details/gtcujnylnn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gtdulpwknv.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gtgfdafumy.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtqqubpqem.html

[U72] PHP：写错误日志
来源：http://dali.birdmap.top/Article/details/gthqzusjlk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xylfe.cn/Article/details/gtoqtpwuke.html

[U73] PHP：读取 ini 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtjhfzswjl.html

parse_ini_file("config.ini", true)
来源：http://dali.9152youxi.cn/Article/details/gtvqghrveh.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtdspurgnc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangshuangyany.cn/Article/details/gtgdzogpxc.html

[U75] PHP：依赖注入
来源：http://dali.ywan-chungtsiang.top/Article/details/gteykwsczo.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gtawropjvo.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangtech.top/Article/details/gtyplirpsr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.redwolf501.top/Article/details/gtqcnujowo.html

[U77] PHP：模板渲染
来源：http://dali.jinqigfzy.top/Article/details/gterqwmpmk.html

composer require twig/twig
来源：http://dali.quarkkingdee.top/Article/details/gtxmrrtnhc.html

[U78] PHP：单元测试
来源：http://dali.gotoacloud.top/Article/details/gtabsviirl.html

composer require --dev phpunit/phpunit
来源：http://dali.quarkkingdee.top/Article/details/gtsiqqlgvf.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gthfenctcl.html

composer require --dev phpstan/phpstan
来源：http://dali.hnxiangtu.top/Article/details/gtyuhyuhhs.html

[U80] PHP：代码规范修复
来源：http://dali.hnxiangtu.top/Article/details/gtehdyokwm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgghwxfzf.html

[U81] JS：初始化项目
来源：http://dali.gotoacloud.top/Article/details/gtbohdpety.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gtpeoleyzw.html

[U82] JS：package.json 脚本
来源：http://dali.zhixingplan.top/Article/details/gtwzlhlgga.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gttnogdgct.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gtgjszfxny.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gthvawafvy.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gtbcfohqon.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guannengcc.top/Article/details/gtgevhnjfb.html

[U85] JS：可选链
来源：http://dali.yj202588.top/Article/details/gtjqwhmozl.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtvzcypkbh.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtajvnwhjf.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gtjjkkbmcq.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtzwyexsch.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gtvzxhsmcg.html

[U88] JS：对象展开合并
来源：http://dali.jqgufenzy.top/Article/details/gtfklxqbqa.html

{ ...a, ...b }
来源：http://dali.sweek.top/Article/details/gtdlvujfah.html

[U89] JS：数组去重
来源：http://dali.gotoacloud.top/Article/details/gtdetvnhkc.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gttkcjtmgd.html

[U90] JS：数字数组排序
来源：http://dali.chenlongwang.top/Article/details/gtkwlxddsq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtnvcstnyx.html

[U91] JS：对象键值遍历
来源：http://dali.aizwys.cn/Article/details/gtzorxpvjl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gtehbrjlhk.html

[U92] JS：深拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtkppgezhv.html

structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtyezvtlro.html

[U93] JS：模板字符串
来源：http://dali.yuanzhike.top/Article/details/gtvlutybpb.html

`共 ${n} 条`
来源：http://dali.fengsongda.top/Article/details/gtkwutlmyu.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gtuhmpxjfh.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtdoqqooau.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gtoxtmdoof.html

new Promise((resolve, reject) => {})
来源：http://dali.shangyingyoupin.top/Article/details/gtcqzwpvnl.html

[U96] JS：async/await 与异常
来源：http://dali.xuanzx.com/Article/details/gtxhcezaxj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtkfintfnz.html

[U97] JS：并发请求
来源：http://dali.c1oappe.top/Article/details/gtwkphfctr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gteseyovxf.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gtdjypdtfg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sysykeji.top/Article/details/gttabmicgj.html

[U99] JS：事件监听
来源：http://dali.cqqwz.cn/Article/details/gthlhprfck.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gtivmgtmmc.html

[U100] JS：DOM 查询
来源：http://dali.yj20258888.top/Article/details/gtorjgpquv.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gtrvyjgwbw.html

[U101] JS：classList 操作
来源：http://dali.sysykeji.top/Article/details/gtmhopfhgd.html

el.classList.toggle("active")
来源：http://dali.yangfankeji.com/Article/details/gtbaywooli.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gtvotwrjmr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgufenzy.top/Article/details/gtdklqiqkl.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gtzsyjfoyy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gtxvcyrkki.html

[U104] JS：防抖
来源：http://dali.c1oappe.top/Article/details/gtfxozerxs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtrmcxzbad.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gtylujqezz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gtaniptygg.html

[U106] JS：日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtdvxgfiry.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtjonmgncy.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtpbajvyts.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtkzqkskva.html

[U108] JS：随机整数
来源：http://dali.xziqi.cn/Article/details/gtgfikovqo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gogol.net.cn/Article/details/gthyfgruix.html

[U109] JS：数组分组
来源：http://dali.316326.xyz/Article/details/gtwzixlocu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtexieyhse.html

[U110] JS：数组分块
来源：http://dali.guannengcc.top/Article/details/gtoyllvvxi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gtcgkafrrt.html

[U111] JS：对象转 Map
来源：http://dali.hammf.cn/Article/details/gtetnawvhq.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gtzmezlrdp.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gtkwcaehyz.html

"7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtlvhewqys.html

[U113] JS：正则替换全部
来源：http://dali.haohaochexian.top/Article/details/gtburgpvmg.html

s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtrgvkbwph.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtvolrpicx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtbpyeixtz.html

[U115] JS：生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtzglgwmhp.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtxchzbqsa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gtwtlmyhxh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.9152youxi.cn/Article/details/gtbfjmqian.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gtpikpfaow.html

npm i -D vitest;  npx vitest
来源：http://dali.ehwqpu.com/Article/details/gttqvicsdk.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gtinaetikz.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gtjwowkzbu.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtvudwuqby.html

npx vite build
来源：http://dali.hnxiangtu.top/Article/details/gtryovueht.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gtaqpibcom.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gttebxjfdb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdzrehatf.html

统计汇总
来源：http://dali.guowangkeji.top/Article/details/gtqdytxubk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcuneboqk.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gtckuqyzaq.html

Python ......... 252
来源：http://dali.vqdsnc.cn/Article/details/gtgrwgkbqe.html

PHP ............ 252
来源：http://dali.dashuyun.cn/Article/details/gtrtsbvoqy.html

JavaScript ..... 252
来源：http://dali.hnxiangtu.top/Article/details/gtychatiac.html

TypeScript ..... 212
来源：http://dali.jyoumei.cn/Article/details/gtzehuaiwz.html

Java ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtbpudrgzn.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtmewnnzhp.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gtcrncbkkl.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtjthdrnnq.html

C .............. 30
来源：http://dali.wangshuangyany.cn/Article/details/gtclaobwrj.html

C++ ............ 30
来源：http://dali.yonumen.top/Article/details/gtirfwkvof.html

SQL ............ 90
来源：http://dali.hongshengwenyu.top/Article/details/gtzfftwesv.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gtsjayxicz.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gtykiqvfuv.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtncnyryaf.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gtmnsrmloj.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtzcfawqfu.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtlmncjwcw.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtwiqqsdmt.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gtrlcbcyef.html

按章节统计：
来源：http://dali.sufxvd.cn/Article/details/gtdyvismyd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtarubassy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtrqpbgvmn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtbmnclehl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gtvclldaho.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhengqikj.top/Article/details/gtcthsizsn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtolhjcmcq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtmllygitz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtaoqshzyu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtrcypwumv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtoffdcvsp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtzlmwkkbc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtrttsdskd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtbtzqpqna.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gtnugdjvag.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dianchejie.cn/Article/details/gtlhvgeiei.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtvwhrbrzl.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gteddfdaax.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gtvtmjbtkv.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gtrnuopcof.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gtcnxhszoq.html

U 高频实用片段                         120
来源：http://dali.kuanghao11.cn/Article/details/gtbgbqlwuw.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtpzrofweq.html

合计                                  2106 条
来源：http://dali.hysaishi.cn/Article/details/gtkugikski.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtoegeptbr.html


<!-- 参考信息 -->