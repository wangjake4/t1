代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtqlcfijvh.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gthlkxcpnp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gteboxuwkw.html

[T58] Scala：函数定义
来源：http://dali.daria6918.cn/Article/details/gtltabmhvh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gtvjullinj.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gtxnhhsfyl.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtkcupssut.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gtibcsbvid.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtcguftskb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtomhzdpap.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gthqwmbrrn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gturwerpvh.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtdlwcxtxm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gtbcytlwzx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtdyilqgtp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gthnyaibya.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gtvjsazqtw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gtdhqdltrk.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gteumbprzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtkwsrgkqi.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtfrrdnket.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtorsvmlbq.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtjjnkcxrb.html

{**a, **b}
来源：http://dali.gzhubu.top/Article/details/gtnvowotto.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gtvywmwtaz.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gtzmpjwhed.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gthopuvqhp.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtmwdgqcau.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gtgxtdntuq.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gtornrqzkb.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gtdeuznnnw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gtulkvbpah.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gtoaimjoph.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gtbjxupche.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gtcemwazqn.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutuuguam.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gthjzzprvh.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtlqjtqzyu.html

[U14] Py：分组收集到列表
来源：http://dali.svipenyu.cn/Article/details/gtvbfgluwk.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtolghouwp.html

[U15] Py：高精度计时
来源：http://dali.iojbl.cn/Article/details/gtjzgjsnva.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtnmihzjke.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtihfywtuk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtrfzgtxvq.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtjapyqkas.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gtgloosckx.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtkdiedgid.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gthozddvir.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gtgeqjihfi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnxiangtu.top/Article/details/gttzcohftk.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gtkpfiadjj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtozuailoa.html

[U21] Py：自定义上下文管理器
来源：http://dali.sweek.top/Article/details/gtqtrmlnhn.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtdhotmjts.html

[U22] Py：矩阵转置
来源：http://dali.havefunace.top/Article/details/gtktyshjom.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtpkfegdqg.html

[U23] Py：分块读取大文件
来源：http://dali.chenlongwang.top/Article/details/gtubqarprw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cashguo.top/Article/details/gterflvdfw.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gtsfzlkkyd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtggfhigzs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhongyouzk.top/Article/details/gthqxrtsxx.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gtpacbbhkb.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gtwgclupqs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dashuyun.cn/Article/details/gtamwcmnzu.html

[U27] Py：异步 HTTP
来源：http://dali.zycfv.cn/Article/details/gtfvbvpanv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyoljnau.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gtzyaqdygc.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gtnclagqkx.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gtknmjrgpq.html

@property 与 @x.setter 配合
来源：http://dali.vqdsnc.cn/Article/details/gtljnsstag.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gttbhjgfbn.html

@dataclass(slots=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvpjzgfh.html

[U31] Py：单测
来源：http://dali.sweek.top/Article/details/gttlrenejn.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gtobxtxqlg.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtgtqmttgk.html

ruff format . && ruff check --fix .
来源：http://dali.hysaishi.cn/Article/details/gtwckfslzi.html

[U33] Py：打包发布
来源：http://dali.ppjwa.cn/Article/details/gtotpaduma.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gtuujfarxk.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gtysfcgnqz.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gtxtojvrht.html

[U35] Py：发送邮件
来源：http://dali.c1oappe.top/Article/details/gtolsqzvuc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gteffxbfic.html

[U36] Py：定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtpsuyrcqs.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gtuzypijmm.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gtrkfdceof.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.mhx1999.top/Article/details/gtkbhqzwxo.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmtjodyg.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gtsrhwpjzp.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenzaomai.com/Article/details/gtjzhllqbf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtpevilkrm.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gttkqbzorl.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtaydofhug.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuxming.cn/Article/details/gtoostzwex.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gtwhdgnzmr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtgemmmily.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuetiantiany.cn/Article/details/gtcarxgwmk.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtxnhmseyf.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtxogernft.html

[U44] PHP：开启严格类型
来源：http://dali.snrcjt.cn/Article/details/gtssczhdvu.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtrfugjvif.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gtpzsrdeam.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtbgytorrk.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gtrfirfzbn.html

?string $name = null
来源：http://dali.0kj1m.cn/Article/details/gtkbtustng.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gtygphneud.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gtaqskjkzw.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyssnsijb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yonumen.top/Article/details/gtzztqxrbg.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gtzgrmjevu.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gtzbasfhyv.html

[U50] PHP：构造器属性提升
来源：http://dali.xuetiantiany.cn/Article/details/gtrxnfbbbc.html

public function __construct(private int $id) {}
来源：http://dali.pycfn.com/Article/details/gtfiejwqlx.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gtqnqghgds.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gthdscggnv.html

[U52] PHP：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gtjtemhdqe.html

$double = fn($x) => $x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtakqrsans.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gtevjxphgn.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gtvfweqygc.html

[U54] PHP：空安全调用
来源：http://dali.svipenyu.cn/Article/details/gtydyithxq.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gthcycowhp.html

[U55] PHP：match 表达式
来源：http://dali.nanxinkj.top/Article/details/gtqjnrtyul.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtnakmvrvw.html

[U56] PHP：命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtflvhzihq.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtsomyscka.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuggxjaz.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gtbobfqjch.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gtkufewjkt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhongyouzk.top/Article/details/gthikcimql.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtvuzfytwf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gtgohxnjyo.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gtzbsvasyl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gtgosuyfxp.html

[U61] PHP：正则
来源：http://dali.zhengqikj.top/Article/details/gtmmvqxhda.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtdvmlqzst.html

[U62] PHP：日期对象
来源：http://dali.xuanzx.com/Article/details/gtnfhqjcgu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtmbdjpcjx.html

[U63] PHP：文件读写
来源：http://dali.shangyingyoupin.top/Article/details/gtqmvzvvzp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yanxiufei.cn/Article/details/gtywiykjqo.html

[U64] PHP：目录遍历
来源：http://dali.hnxiangtu.top/Article/details/gtiuoiukar.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dianchejie.cn/Article/details/gtziarjado.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gtgovmhxpw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtvywzowov.html

[U66] PHP：设置 Cookie
来源：http://dali.ydzc1.top/Article/details/gtwnhanqmt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gtbiryfxfb.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gtsdgyuzkl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangshuangyany.cn/Article/details/gthahxndzg.html

[U68] PHP：PDO 连接
来源：http://dali.316326.xyz/Article/details/gtcjekgabd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtkfzrsphp.html

[U69] PHP：PDO 预处理
来源：http://dali.ivvv.top/Article/details/gtutgzzdrx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gogol.net.cn/Article/details/gtjwvgwjst.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gtslidnfsk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sufxvd.cn/Article/details/gtmwmlnmae.html

[U71] PHP：抛出异常
来源：http://dali.sxryk.cn/Article/details/gtogpmlxwb.html

throw new RuntimeException("失败", 500);
来源：http://dali.shzxlz.cn/Article/details/gtvqrvaolu.html

[U72] PHP：写错误日志
来源：http://dali.cashguo.top/Article/details/gtztfyizzf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gtvpeshaty.html

[U73] PHP：读取 ini 配置
来源：http://dali.xziqi.cn/Article/details/gtbiusiiuc.html

parse_ini_file("config.ini", true)
来源：http://dali.gogol.net.cn/Article/details/gtlxqqnoro.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtfodtrpls.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cucudq.cn/Article/details/gttgwitsky.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gtqpiifwdc.html

composer require psr/container
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvjurztw.html

[U76] PHP：简单路由
来源：http://dali.andypj.xyz/Article/details/gtgcbrwljm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gtdghhqeka.html

[U77] PHP：模板渲染
来源：http://dali.pengpengdd.cyou/Article/details/gtanmhskzf.html

composer require twig/twig
来源：http://dali.daria6918.cn/Article/details/gtmsymxzoa.html

[U78] PHP：单元测试
来源：http://dali.jiagoushi.top/Article/details/gtcwrauuyn.html

composer require --dev phpunit/phpunit
来源：http://dali.gzhubu.top/Article/details/gtwnqbjxfw.html

[U79] PHP：静态分析
来源：http://dali.nanxuanxn.top/Article/details/gtcowofnei.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gtrjtcoppv.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gtijetqjsw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yonumen.top/Article/details/gthmmhcgvu.html

[U81] JS：初始化项目
来源：http://dali.chenlongwang.top/Article/details/gtbtldmxqw.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gteelwphvg.html

[U82] JS：package.json 脚本
来源：http://dali.xuetiantiany.cn/Article/details/gtlrottesh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gtaydjkzjd.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gtawztrgan.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtogppdmdr.html

[U84] JS：CommonJS 写法
来源：http://dali.hnqzz.top/Article/details/gtzsbzbotl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtpydhyxet.html

[U85] JS：可选链
来源：http://dali.shuidangran.top/Article/details/gtjzpopsml.html

a?.b?.c
来源：http://dali.wangshuangyany.cn/Article/details/gtzaeerguh.html

[U86] JS：空值合并
来源：http://dali.jinqigufen.top/Article/details/gtebvvtsql.html

a ?? b
来源：http://dali.0kj1m.cn/Article/details/gtlpoiairf.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gtiupwxanq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nwbrower.top/Article/details/gtzayzrjws.html

[U88] JS：对象展开合并
来源：http://dali.jqgfzy.top/Article/details/gtzozvxugh.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gtfxyhoqep.html

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gtyitngbxx.html

[...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gthaqesjnc.html

[U90] JS：数字数组排序
来源：http://dali.jqgfzy.top/Article/details/gtgtowjbor.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtxcxwxeqd.html

[U91] JS：对象键值遍历
来源：http://dali.nwbrower.top/Article/details/gtanoewhaa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daria6918.cn/Article/details/gtbajvwowi.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtvuopdurn.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtzjoidhrh.html

[U93] JS：模板字符串
来源：http://dali.yanxiufei.cn/Article/details/gtfaiydpiu.html

`共 ${n} 条`
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwdocpmi.html

[U94] JS：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtfeonmrkv.html

const double = x => x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtvcwkhqfn.html

[U95] JS：Promise 包装
来源：http://dali.mhx1999.top/Article/details/gtiqprqvnp.html

new Promise((resolve, reject) => {})
来源：http://dali.cheryme.top/Article/details/gtgtabypqv.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gtcrdfzjcs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtttmpnvzb.html

[U97] JS：并发请求
来源：http://dali.redwolf501.top/Article/details/gtrlaytpwx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtayvtbszd.html

[U98] JS：fetch 带 JSON
来源：http://dali.tanke756.top/Article/details/gtmujrgbor.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.9152youxi.cn/Article/details/gtpifysmal.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gtfdruxeyi.html

el.addEventListener("click", e => {})
来源：http://dali.yj202588.top/Article/details/gtvuexdanx.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gtnfbqeflm.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gttipimluw.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gttodbnewi.html

el.classList.toggle("active")
来源：http://dali.kuanghao11.cn/Article/details/gtybpwlwlh.html

[U102] JS：本地存储
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbhzswaf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gtuenosbqm.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gtygdvbkvb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gtskvthkkr.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gtndtnnqpo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtolmzqsob.html

[U105] JS：节流
来源：http://dali.hfpthk.cn/Article/details/gtzjgiilar.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gtjmovsusm.html

[U106] JS：日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtdqakysaq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.bjfxy.top/Article/details/gtnrfgydqi.html

[U107] JS：数字千分位
来源：http://dali.yj202588.top/Article/details/gtvtfymuxs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtonmhpwjr.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gtkkondegx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.feifeiyinyue.top/Article/details/gtdfvseqal.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gtxqqpemhm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcnqwzlw.html

[U110] JS：数组分块
来源：http://dali.aizwys.cn/Article/details/gtqwqhhyhk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gtxahtqysz.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtwifpviae.html

new Map(Object.entries(obj))
来源：http://dali.cdnleiting.top/Article/details/gtqgwmvlkj.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gtacriejhr.html

"7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtwahqbfpz.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmpspfeb.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtciwvagyp.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gtjxxvwyam.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtmytvgizk.html

[U115] JS：生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtlxqxelif.html

crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtfloklnop.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtyjlzuodw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtwtkzgxcw.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtdnhkqrxm.html

npm i -D vitest;  npx vitest
来源：http://dali.jlsjyb.cn/Article/details/gttujlzwda.html

[U118] JS：开发服务器
来源：http://dali.hywenlv.cn/Article/details/gtzggrhict.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhkeqsju.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gtjrodrfsb.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gtqaepoyiq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtfikgyyws.html

import.meta.env.VITE_API_URL
来源：http://dali.tanke756.top/Article/details/gtcxofnpqx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyieiseio.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtwsvztgoz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtboqwalpc.html

按语言统计（条）：
来源：http://dali.yonumen.top/Article/details/gtqldujipt.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtaoiplhvl.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtwfdayzgi.html

JavaScript ..... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmeoiaey.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gtkuaomvfn.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtrvtdldcy.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtfbuadsec.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtcdxisctj.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtlbttqfgf.html

C .............. 30
来源：http://dali.aizwys.cn/Article/details/gtickxbncl.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gtlnsdpifx.html

SQL ............ 90
来源：http://dali.yuanzhike.top/Article/details/gttfnefcqt.html

Bash ........... 80
来源：http://dali.nwbrower.top/Article/details/gtrxfgnpag.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gtiwwaiqyb.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtxrjmzzyy.html

Lua ............ 10
来源：http://dali.ydzc1.top/Article/details/gtdeouzplt.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gtwtoklfef.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gtmtsukgfj.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtnkqmxtjf.html

合计 ........... 2106 条
来源：http://dali.nwbrower.top/Article/details/gtjrguaqcj.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gtpspympxo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtektlwetv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtsoaddike.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtsftyqkct.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtgmrdehnc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhoulong.xyz/Article/details/gtlbmwsfsf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtkghbzeht.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtdsvzoxcu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgabjpuo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtzmufwqaf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtgpirzsbv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtbhvafzys.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtshzuptvz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtyatuoydg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gterefvdwi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuanzx.com/Article/details/gthfxjgkuf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtecznzvvm.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gtnhqhzwsp.html

R Bash 专题                             80
来源：http://dali.hywenlv.cn/Article/details/gtwquakpbn.html

S C / C++ 专题                          60
来源：http://dali.hongshengwenyu.top/Article/details/gtzduqsoit.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gtowbipmdt.html

U 高频实用片段                         120
来源：http://dali.cdnleiting.top/Article/details/gtfdieiznw.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtceoufqtz.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gthuyfgalb.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfuxklur.html


<!-- 参考信息 -->