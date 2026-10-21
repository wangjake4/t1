代发 wailian999

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtnjvdyihx.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gtglpapbsy.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfemwbnr.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gteooukikd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtizocnuwn.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gtxcnonkil.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gtgkegtxuh.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gtlauuqavk.html

case class User(name: String, age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwssjjlhx.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtsqztqyri.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gtvxgjnzdn.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gttmhiugbe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtzpiuzifb.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjjbxqhn.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtzgxjmrdf.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtpehnypek.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gtzepnbhjp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthiemvtxn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtwklgrled.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttzxduoqb.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gtzojjpumm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gtkumsojjc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhixingplan.top/Article/details/gtjlzyzmpo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtgpliqooc.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtgqjoyfan.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gtlvgdaszo.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtgvnmmrlc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gtcxaswmdw.html

[U05] Py：列表去重且保序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutfbjrps.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtiknbvdsz.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gtyushierw.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gtrdlghidq.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtwvmcavbz.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gtrktogtgw.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gtllkbwkif.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtwrphzoxl.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gtrtpuqbdj.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gtokgrvwzi.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gteddjjjoc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtadphguml.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gtqvtnwpvj.html

(x * 2 for x in arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtvycsmlkk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhixingplan.top/Article/details/gtktwznepf.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtfhpsfdaw.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gtyssqyfum.html

deque(maxlen=10)
来源：http://dali.yangfankeji.com/Article/details/gtjwnflayf.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gtbczhvbaz.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtsjikyhrm.html

[U15] Py：高精度计时
来源：http://dali.tian-w.cn/Article/details/gtgrymbvbq.html

t = time.perf_counter()
来源：http://dali.kuanghao11.cn/Article/details/gtbexflasi.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiocbzhrp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.haohaochexian.top/Article/details/gtowgbqugu.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtsarqwfvb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sxryk.cn/Article/details/gtkvhuayvz.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvndtmtf.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtoyuwsawq.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gtwvsobzbo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtrjiwkluq.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gtmbvmdkpp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtqodbenit.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuetiantiany.cn/Article/details/gtprerstne.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gtlwbodpbc.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gtvmrjyiyp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gtsdoromyj.html

[U23] Py：分块读取大文件
来源：http://dali.gzhubu.top/Article/details/gtvtrzzehs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtfvottdrc.html

[U24] Py：路径操作
来源：http://dali.nanxuanxn.top/Article/details/gteplhisdc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtjihuflwp.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gtzowfmovq.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gtbxnydtab.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gtfvvlnzys.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtotlpejut.html

[U27] Py：异步 HTTP
来源：http://dali.guowangkeji.top/Article/details/gtjirjqayj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tianlin.xyz/Article/details/gtxzovwcqy.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gtajvuhkce.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gtyaxczhhq.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gtlkifiona.html

@property 与 @x.setter 配合
来源：http://dali.shzxlz.cn/Article/details/gtafhhtpif.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gtnagnckjx.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gtycnefgum.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gtnokjvuwc.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gtyajzhazc.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gtwijpdoaw.html

ruff format . && ruff check --fix .
来源：http://dali.yanxiufei.cn/Article/details/gtrfcuzhcp.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gtzusreyrm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gtccpatjfj.html

[U34] Py：判断编码
来源：http://dali.daxiang520.top/Article/details/gtziycujay.html

chardet.detect(raw)
来源：http://dali.sufxvd.cn/Article/details/gtvywcapqn.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtuotucxfb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtxgvmkqmq.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtbvqgii.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gtisfpvvhc.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gtsxjjpboo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gtbhkjzeoq.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gtdhbpyxur.html

Path(__file__).resolve().parent
来源：http://dali.nanxuanxn.top/Article/details/gtwxzmhhtt.html

[U39] Py：判断是否在交互环境
来源：http://dali.jianghu66.top/Article/details/gtlnixklhd.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gthhnqwshl.html

[U40] Py：打印到标准错误
来源：http://dali.sweek.top/Article/details/gterqyyplq.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtevuxuyzr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxuanxn.top/Article/details/gtbktsnunv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gtucsieeri.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gtkxyuxjke.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtwsnfvvxx.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258.top/Article/details/gtmxfxckmb.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gtypdfilqv.html

[U44] PHP：开启严格类型
来源：http://dali.cdnleiting.top/Article/details/gtzybgtjqt.html

declare(strict_types=1);
来源：http://dali.ppjwa.cn/Article/details/gtgdvehqnh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gtrnejexxf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gthcqkqqec.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gtwbtzbsbe.html

?string $name = null
来源：http://dali.chenjidiqi.icu/Article/details/gtgzhsimgl.html

[U47] PHP：联合类型
来源：http://dali.xylfe.cn/Article/details/gtjvixtjcp.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtscuoudah.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gtxolyomcv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.iojbl.cn/Article/details/gtfzsskgya.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gtntxzgbeo.html

public readonly string $name
来源：http://dali.smart0.xyz/Article/details/gtdxsgvcar.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gtjshskgtd.html

public function __construct(private int $id) {}
来源：http://dali.chenzaomai.com/Article/details/gtuaeqmuzo.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gtpjhqrqxz.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gtkrfyprnf.html

[U52] PHP：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gthmnxfndr.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gttbyrpmdg.html

[U53] PHP：空合并运算符
来源：http://dali.chenjidiqi.icu/Article/details/gttlgjguwy.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gtgteifigd.html

[U54] PHP：空安全调用
来源：http://dali.yanxiufei.cn/Article/details/gtotugseia.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gtixaqesxn.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gthefgowzz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gzhubu.top/Article/details/gtifsqmojt.html

[U56] PHP：命名参数
来源：http://dali.c1oappe.top/Article/details/gtvkqkconm.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gttfatnsca.html

[U57] PHP：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gthrxrcoub.html

"值: {$a}"
来源：http://dali.zhixingplan.top/Article/details/gtnivqtyyh.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gtvjtqtvaq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtxfiklsam.html

[U59] PHP：自定义排序
来源：http://dali.sweek.top/Article/details/gtmesnryef.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtlpbqvkex.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gtpyutuuny.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sxryk.cn/Article/details/gtqrypwjwj.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gtxywxryfo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtfasiaedr.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gtofvyprfe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gtwtxcrinb.html

[U63] PHP：文件读写
来源：http://dali.vqdsnc.cn/Article/details/gtcyirmywt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gtnyzkbcyc.html

[U64] PHP：目录遍历
来源：http://dali.0kj1m.cn/Article/details/gtzuuokgkl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwnmwrju.html

[U65] PHP：会话
来源：http://dali.ppjwa.cn/Article/details/gtpynhchhv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtzyifsswy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gtzcxwiero.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gtksplrzqp.html

[U67] PHP：处理文件上传
来源：http://dali.tian-w.cn/Article/details/gtbomufqxa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocijjpez.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gtkpotmtct.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtllygqxww.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbzarvrw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpbutyuk.html

[U70] PHP：PDO 事务
来源：http://dali.hysaishi.cn/Article/details/gtvxjqjmmd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dashuyun.cn/Article/details/gttcjtltso.html

[U71] PHP：抛出异常
来源：http://dali.yvedp.cn/Article/details/gtftdgafip.html

throw new RuntimeException("失败", 500);
来源：http://dali.hysaishi.cn/Article/details/gtdyviywtl.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gtepsoiaju.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daxiang520.top/Article/details/gttuopdgvd.html

[U73] PHP：读取 ini 配置
来源：http://dali.bjfxy.top/Article/details/gtufzkluyf.html

parse_ini_file("config.ini", true)
来源：http://dali.nwbrower.top/Article/details/gtkazjkdpf.html

[U74] PHP：读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvdldnok.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cdnleiting.top/Article/details/gtvalyxmbl.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtmaljgylv.html

composer require psr/container
来源：http://dali.cashguo.top/Article/details/gteesgysde.html

[U76] PHP：简单路由
来源：http://dali.zhongyouzk.top/Article/details/gtvuvtsfpz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yanxiufei.cn/Article/details/gtfnvintde.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gtexganpsk.html

composer require twig/twig
来源：http://dali.zhengqikj.top/Article/details/gtinnfxbsf.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtvkyktrvk.html

composer require --dev phpunit/phpunit
来源：http://dali.birdmap.top/Article/details/gtrtwjfhcf.html

[U79] PHP：静态分析
来源：http://dali.bjfxy.top/Article/details/gthsuqayhs.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gtvbtbdmab.html

[U80] PHP：代码规范修复
来源：http://dali.quarkkingdee.top/Article/details/gtjgbthspc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnqkxnce.html

[U81] JS：初始化项目
来源：http://dali.cdnleiting.top/Article/details/gttvheciqz.html

npm init -y;  npm i express
来源：http://dali.yuanzhike.top/Article/details/gthrotiiue.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gtrmrqmzwj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenlongwang.top/Article/details/gtntsrrvtn.html

[U83] JS：ES Module 导入导出
来源：http://dali.yongpay.top/Article/details/gtlizmpicz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtphoitiyy.html

[U84] JS：CommonJS 写法
来源：http://dali.daria6918.cn/Article/details/gtweemejsk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gtxvzrfxeg.html

[U85] JS：可选链
来源：http://dali.nwbrower.top/Article/details/gtomghgylu.html

a?.b?.c
来源：http://dali.sweek.top/Article/details/gtnsfjfhze.html

[U86] JS：空值合并
来源：http://dali.nanxuanxn.top/Article/details/gthlgxwoib.html

a ?? b
来源：http://dali.nwbrower.top/Article/details/gticupnacq.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gtzrsuqjqz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gtcdqndcin.html

[U88] JS：对象展开合并
来源：http://dali.9152youxi.cn/Article/details/gtgxktcwty.html

{ ...a, ...b }
来源：http://dali.ehwqpu.com/Article/details/gtsptrtdhl.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gtozygegho.html

[...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtmdeontrw.html

[U90] JS：数字数组排序
来源：http://dali.jyoumei.cn/Article/details/gtfmlaapnq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtysogodzx.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gtualvltrt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdfqxcjv.html

[U92] JS：深拷贝
来源：http://dali.iojbl.cn/Article/details/gtbnvezeci.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtufguyadm.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtyncuzumd.html

`共 ${n} 条`
来源：http://dali.chenjidiqi.icu/Article/details/gtzuhczwef.html

[U94] JS：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gtzygbsimv.html

const double = x => x * 2;
来源：http://dali.redwolf501.top/Article/details/gtygfpwbsi.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gtvzlektcb.html

new Promise((resolve, reject) => {})
来源：http://dali.gogol.net.cn/Article/details/gtfoqxghpx.html

[U96] JS：async/await 与异常
来源：http://dali.yuxming.cn/Article/details/gtzfcueqtk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtrsnptxii.html

[U97] JS：并发请求
来源：http://dali.316326.xyz/Article/details/gtxjldvjqz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtzoyhgqky.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gtarcrxnxi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj202588.top/Article/details/gtfknkzvgi.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gtotcecknm.html

el.addEventListener("click", e => {})
来源：http://dali.snrcjt.cn/Article/details/gtabwzhbeo.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtxsksofzs.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtzvnnhuph.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtenifmwjw.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gtaegzvppv.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gthrhwxsjk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.andypj.xyz/Article/details/gtryahvdax.html

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gtdmgcncxh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gtfixjfisw.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gtixhubctk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtggbzgxwn.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gthimcqrke.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.haohaochexian.top/Article/details/gtpmjruueb.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtancxrksf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxinkj.top/Article/details/gttxokasjd.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtmghfxgez.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtdqpnlctx.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gtypshkzpe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.svipenyu.cn/Article/details/gtvaissdis.html

[U109] JS：数组分组
来源：http://dali.dianchejie.cn/Article/details/gtxqoltxpm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gthhikzegd.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gtapiqmbea.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gtlxzoaclv.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtbqzjcamy.html

new Map(Object.entries(obj))
来源：http://dali.haohaochexian.top/Article/details/gtbzomlbcn.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gtcorjivwv.html

"7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtgvvetpbu.html

[U113] JS：正则替换全部
来源：http://dali.kuanghao11.cn/Article/details/gtthgjysac.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtcnkmrflq.html

[U114] JS：JSON 深比较
来源：http://dali.kuanghao11.cn/Article/details/gtmowiraed.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtpejagowg.html

[U115] JS：生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtpvyawyif.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtpijrgzlo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gtddbolewi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gtgizyaemk.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gttyjwmgcp.html

npm i -D vitest;  npx vitest
来源：http://dali.snrcjt.cn/Article/details/gtdtuwehih.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gthsaxltmi.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtxzdyyfck.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gtykhpmsoe.html

npx vite build
来源：http://dali.hfpthk.cn/Article/details/gtyjjxzyat.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gtqhnfsbep.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtekczecbq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttfsfigww.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gtthgcqmzq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvfzmjziz.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gtizzqsmif.html

Python ......... 252
来源：http://dali.ydzc1.top/Article/details/gtwyzgjzlj.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gtqpmfpamr.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gtuhzxojfv.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gtbeqqujjj.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtnaenkceb.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gtcilsvusw.html

Ruby ........... 212
来源：http://dali.jianghu66.top/Article/details/gtqgejgvfh.html

C# ............. 212
来源：http://dali.c1oappe.top/Article/details/gtrvwltcab.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtsnkhypwo.html

C++ ............ 30
来源：http://dali.yongpay.top/Article/details/gtkggnvrun.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtxqnuzygn.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtzbjiblof.html

Kotlin ......... 15
来源：http://dali.ydzc1.top/Article/details/gtepdocoyh.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtjkvmysfq.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gtrgmtfslr.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gttddssanr.html

Scala .......... 10
来源：http://dali.smart0.xyz/Article/details/gtcfcbquvs.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtsgnboqvb.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyyoyuby.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gtohqayhov.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtzwbvphla.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtryroaslq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtiquawiip.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtcwngonrd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gtyrnrejxq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gtjrbtkhnb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtxvjrmhay.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtfazwwswv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtopegskmy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtwjyfncti.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtczvoveyw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjonvpzq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtocjuniuc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtosrnshmm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gaohongyu789.top/Article/details/gtmzmbvgcu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtsruxbvcu.html


<!-- 参考信息 -->