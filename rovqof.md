代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtprigmdnd.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtfabfcsnh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtixplcjol.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtbraxubak.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtofggbkgr.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtcfhstrtd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhivdbut.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gtihcghbjx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtbxjwavkm.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycdxknig.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwzdwtss.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gttmdkpvxa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gtbogpqsfs.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthiffswvx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtxechuukp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtywfgvbgv.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gtrkwyprkq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gtkbkcvtqt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtujdmpquw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtwotbffjh.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtjjspfees.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtcftzmtzo.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gtfhlmcofm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gtvchkyqud.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtttedojpl.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtgnfceuys.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtxfkjdwfz.html

{**a, **b}
来源：http://dali.dianchejie.cn/Article/details/gtgtyeimgp.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gtyryntrwt.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gtexwtqvtl.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gtsuhnurwg.html

[y for x in nested for y in x]
来源：http://dali.hnqzz.top/Article/details/gtlihzziar.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gtsnwndmhi.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtsvjqkalv.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gtbbkffrda.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gtgpsnjoum.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gtenugohvh.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gtxplxeefc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtoomvjfxx.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gthqjreszf.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gtdpsmezpp.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gtgfjkjxtt.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gthxoijnpx.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gtvfdripbx.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtdknewdwv.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gtpumnommz.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gtirmemyyg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.haohaochexian.top/Article/details/gtrveeapjr.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrhvgbra.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtmezgxfpx.html

[U18] Py：预编译正则
来源：http://dali.c1oappe.top/Article/details/gtlbxttwvj.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtmdbsfxtc.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtmxfzjhzc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gtoucfsbsh.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gttatvifnw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtosbosfes.html

[U21] Py：自定义上下文管理器
来源：http://dali.daria6918.cn/Article/details/gtoxfgppqy.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gtfaxvepzg.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gtnxfqgeqk.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gtrtqeyvmw.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gtkmzrddvr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gtmtgtkmkc.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gtxdklhjin.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtucrrthvn.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gtcshavxce.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gtbiotajlb.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gtuuuupaia.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtvmqojmtk.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gtdhcoimwp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gtaiemhxxf.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gtsldrmuhl.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gtwjkkpxdt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtdtlvaukd.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaygalnu.html

[U30] Py：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtjatsejoq.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gtiuixssxt.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gtprbeeale.html

python -m pytest -q
来源：http://dali.haohaochexian.top/Article/details/gthssjiqzv.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gtzqyjkefb.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gtbkteqvjw.html

[U33] Py：打包发布
来源：http://dali.cheryme.top/Article/details/gtvnzlzpja.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnqzz.top/Article/details/gtgresschs.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gtbzcuvlqd.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gtjsjwhzld.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gtjtusigzh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvxqsbvn.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gteuvrnhgc.html

schedule.every(10).minutes.do(job)
来源：http://dali.havefunace.top/Article/details/gtquqoprjl.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gtefqbtjsx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhengqikj.top/Article/details/gtkjkamysf.html

[U38] Py：获取脚本所在目录
来源：http://dali.0kj1m.cn/Article/details/gtekdhxhqj.html

Path(__file__).resolve().parent
来源：http://dali.yanxiufei.cn/Article/details/gtruqqbnmn.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtcuvertyr.html

sys.stdout.isatty()
来源：http://dali.zhengqikj.top/Article/details/gtkepenukt.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtyzjozsxs.html

print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gteycedqfd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtccquaonm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gtxcgdpzir.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.guowangkeji.top/Article/details/gtrfthwvym.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gtlqvtnixp.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gtmjboxlpg.html

namespace App\Http;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagbuyvve.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigfzy.top/Article/details/gtnkjeosmt.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gtzpraqpjv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gtbdvdbaeg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrymzhbpz.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbaiizuy.html

?string $name = null
来源：http://dali.hnqzz.top/Article/details/gtqgyvsowh.html

[U47] PHP：联合类型
来源：http://dali.0kj1m.cn/Article/details/gtgqmkljzm.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtzwcciixd.html

[U48] PHP：纯枚举
来源：http://dali.tian-w.cn/Article/details/gtunqjhmeh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigufen.top/Article/details/gtabucxckf.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gtjgzounmf.html

public readonly string $name
来源：http://dali.jiagoushi.top/Article/details/gtxnsozmhz.html

[U50] PHP：构造器属性提升
来源：http://dali.hfpthk.cn/Article/details/gtixksavld.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gtsntmhmkm.html

[U51] PHP：数组解构
来源：http://dali.aibaodan.cn/Article/details/gtvigcoqxp.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gtgdhlchte.html

[U52] PHP：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtsurttjwa.html

$double = fn($x) => $x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtkvcwzyyi.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gtpwlxngdx.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtuvjkeghz.html

[U54] PHP：空安全调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhalnvtj.html

$obj?->method()
来源：http://dali.0kj1m.cn/Article/details/gttumyqrco.html

[U55] PHP：match 表达式
来源：http://dali.chenlongwang.top/Article/details/gtvnzkwcvx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtoyrvcjhn.html

[U56] PHP：命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtlpzyfiik.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtfkygnqwq.html

[U57] PHP：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtvrtwkyht.html

"值: {$a}"
来源：http://dali.tianlin.xyz/Article/details/gticuovirk.html

[U58] PHP：数组三件套
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaklxubo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtykyhgymw.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtaascctug.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtsolcktqa.html

[U60] PHP：JSON 编解码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzllpxpg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zdqjudy.top/Article/details/gthvdepuoi.html

[U61] PHP：正则
来源：http://dali.snrcjt.cn/Article/details/gtslevzusw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtnoxdvzqt.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gtqvflvnkg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258888.top/Article/details/gtnmvmydxm.html

[U63] PHP：文件读写
来源：http://dali.shzxlz.cn/Article/details/gtpverzbqz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gtypphibzt.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtiesgevan.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fzhhl.top/Article/details/gtwiazrlvz.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gteudjxfzf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtbchnydgx.html

[U66] PHP：设置 Cookie
来源：http://dali.meibo888.top/Article/details/gtabkxzovb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gaohongyu789.top/Article/details/gtpkvjrfcb.html

[U67] PHP：处理文件上传
来源：http://dali.jinghuilouyu.cn/Article/details/gthxsttaqz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gtluzmtuni.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gthheftrru.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gogol.net.cn/Article/details/gtbluvclmg.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gtpgdtlzpo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gturikarje.html

[U70] PHP：PDO 事务
来源：http://dali.redwolf501.top/Article/details/gtqpelodyw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gtcfewrfbz.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gtekyyhmdu.html

throw new RuntimeException("失败", 500);
来源：http://dali.xylfe.cn/Article/details/gtnprgcxdu.html

[U72] PHP：写错误日志
来源：http://dali.yj20258888.top/Article/details/gtqdifuoip.html

error_log("失败: " . $e->getMessage());
来源：http://dali.havefunace.top/Article/details/gtdwczorno.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gtulwhynqf.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtcxjrbips.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gtcqqlvhfk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gtdasywfez.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtdogyngov.html

composer require psr/container
来源：http://dali.sweek.top/Article/details/gtvsbfhucb.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gtkhlioslf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gtmftlinkt.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gthagkvynj.html

composer require twig/twig
来源：http://dali.sxryk.cn/Article/details/gtmegzdser.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtsnoxcqfe.html

composer require --dev phpunit/phpunit
来源：http://dali.chenlongwang.top/Article/details/gtzrfvifue.html

[U79] PHP：静态分析
来源：http://dali.svipenyu.cn/Article/details/gtscgybjch.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gtofawkucu.html

[U80] PHP：代码规范修复
来源：http://dali.yangfankeji.com/Article/details/gtqywdobcn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.316326.xyz/Article/details/gtecvhkkmd.html

[U81] JS：初始化项目
来源：http://dali.sufxvd.cn/Article/details/gtwedoqzhv.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gtjaqydsca.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigufen.top/Article/details/gtrnjzzxfs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jlsjyb.cn/Article/details/gtiezzhhyp.html

[U83] JS：ES Module 导入导出
来源：http://dali.ppjwa.cn/Article/details/gtvasngcck.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtgfmmaimt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhixingplan.top/Article/details/gtfdydzjmn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yonumen.top/Article/details/gtechkzvdc.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gtbhcajgch.html

a?.b?.c
来源：http://dali.daxiang520.top/Article/details/gtnhjuirtu.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtzrdzzsza.html

a ?? b
来源：http://dali.yangfankeji.com/Article/details/gtroabfkfr.html

[U87] JS：解构默认值
来源：http://dali.daria6918.cn/Article/details/gtoqrudctb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gtxogkbfkg.html

[U88] JS：对象展开合并
来源：http://dali.ydzc1.top/Article/details/gtzmoupvkj.html

{ ...a, ...b }
来源：http://dali.zhengqikj.top/Article/details/gtrsthtpop.html

[U89] JS：数组去重
来源：http://dali.gotoacloud.top/Article/details/gtbbtnghtx.html

[...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtgdixjoef.html

[U90] JS：数字数组排序
来源：http://dali.dianchejie.cn/Article/details/gtpsijefvo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtybhzljnn.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlctfuyp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.svipenyu.cn/Article/details/gtvwqjkuyd.html

[U92] JS：深拷贝
来源：http://dali.yuxming.cn/Article/details/gtedcuskqb.html

structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtsnnfhmjl.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gtemhcychh.html

`共 ${n} 条`
来源：http://dali.zhixingplan.top/Article/details/gtxhzxhvgd.html

[U94] JS：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gtsfahkrxj.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gttjshygxy.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gtiyiavacv.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvpsrwgk.html

[U96] JS：async/await 与异常
来源：http://dali.zhengqikj.top/Article/details/gtxxgilujo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtmnotugwc.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gtipmukicu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtqnnwfvwu.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gtylcbucqh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvaymkiw.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtvvyjkkzx.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gtonkqyyfm.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gtwtrqxxfe.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gtqyawvmut.html

[U101] JS：classList 操作
来源：http://dali.yvedp.cn/Article/details/gtmiblcyjn.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gtznztkcel.html

[U102] JS：本地存储
来源：http://dali.jinqigufen.top/Article/details/gtybpsxjuh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtcpvdredu.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gtvktwzibv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.haohaochexian.top/Article/details/gtmfopmecs.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gtrrdhtsoe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtqdvgltaw.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gtpakjkzky.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtxpzpavvg.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtsdilpnzr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gtqietdenx.html

[U107] JS：数字千分位
来源：http://dali.aizwys.cn/Article/details/gtyyebyrwt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gtjblmbgtw.html

[U108] JS：随机整数
来源：http://dali.sxryk.cn/Article/details/gtnzcxbnht.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaagrtkfq.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gtfhxfkwbn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtzwdapjpf.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwwvvcgm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangdashe.top/Article/details/gtftlqksxb.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtsixdeyax.html

new Map(Object.entries(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gtxswqawrv.html

[U112] JS：字符串补位
来源：http://dali.kuanghao11.cn/Article/details/gtxdkycwur.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtuqxedzks.html

[U113] JS：正则替换全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfidciuk.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtfhjnyqil.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gtrqrqpagf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtumkjckvr.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtkobfuwes.html

crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtsshbqtsk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtdlsgmqiq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfqqirpcl.html

[U117] JS：单元测试
来源：http://dali.xinyue.icu/Article/details/gtdxmxaeel.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gtjvrmdviz.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gtavoospia.html

npm i -D vite;  npx vite
来源：http://dali.aizwys.cn/Article/details/gthhokvohn.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gtqmfhftfv.html

npx vite build
来源：http://dali.ivvv.top/Article/details/gtoizoxeii.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtyajytlxf.html

import.meta.env.VITE_API_URL
来源：http://dali.hammf.cn/Article/details/gtpeultdth.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfftcqalf.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gtwwmbxpjy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxmrvyaat.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gtgmhguspa.html

Python ......... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtdiuqwoij.html

PHP ............ 252
来源：http://dali.ppjwa.cn/Article/details/gtomjdumnm.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtxtdnnuie.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gtrfytiart.html

Java ........... 212
来源：http://dali.sysykeji.top/Article/details/gtccmaeaaf.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gtfulcybdb.html

Ruby ........... 212
来源：http://dali.xinyue.icu/Article/details/gtdsiguppn.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gtlhhbovaj.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcanfjqem.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gtwvhufxee.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtdfwxxdlx.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gtgfsprupm.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtpfwmocja.html

Swift .......... 15
来源：http://dali.gotoacloud.top/Article/details/gtrrynxyrt.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gtudvulnnc.html

Perl ........... 10
来源：http://dali.hnqzz.top/Article/details/gtwtcqozrz.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gtyvciajab.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtjzghoubj.html

合计 ........... 2106 条
来源：http://dali.shuidangran.top/Article/details/gtuwoftpxq.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gtuvduyxea.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gtxoorazkk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gttygfvkkd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gticzcyvuw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjiazoop.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gtnbahkzio.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gtjwwasnia.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtdeoqtobd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtjyryjuvj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gthlludjce.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtrvygedmd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtohzidson.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtplomjrgv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtrbgqoslu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtqfjtzbwg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gaohongyu789.top/Article/details/gtjuasnrin.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtzbgncqvq.html

Q SQL 专题                              90
来源：http://dali.shangyingyoupin.top/Article/details/gthdyfqtan.html

R Bash 专题                             80
来源：http://dali.shzxlz.cn/Article/details/gtirousubr.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gtqeqaakdj.html

T 其他语言补充                          60
来源：http://dali.yueranfly.top/Article/details/gthgwetjvm.html


<!-- 参考信息 -->