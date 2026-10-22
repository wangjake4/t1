代发 wailian999

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2xfrrwwfp.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2mgpnmaae.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2cwiblpto.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gt2uggwmsev.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gt2nnizjavi.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2kixggswq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gt2mzsdjvwu.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gt2efzargbt.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2islqfmka.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gt2jwwqhlci.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gt2jwcurpwn.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gt2jiphjuux.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idwefxic.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gt2iscbhldt.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2aufdqxbz.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gt2bgahqzur.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gt2kybzflzo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2guupybhx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gt2lzhztwiy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jwhfxcps.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gt2zgnprmet.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gt2spunugva.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gt2ureyxemp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2tntfxcrg.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258.top/Article/details/gt2bungwzvn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gt2henaatsh.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gt2utvfvzhj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zdqjudy.top/Article/details/gt2fnizuohg.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gt2fgxehcby.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2iwgfhcdc.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gt2edjutreq.html

{**a, **b}
来源：http://dali.9152youxi.cn/Article/details/gt2tvcgphri.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gt2xaiwbefp.html

{v: k for k, v in d.items()}
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqugoopm.html

[U08] Py：展平二维列表
来源：http://dali.birdmap.top/Article/details/gt2bkyoovwa.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gt2bbvafajj.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gt2miyyqynh.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gt2epfvuzrq.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gt2ccvrgabn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aizwys.cn/Article/details/gt2nwlpwrgy.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gt2tqyniait.html

(x * 2 for x in arr)
来源：http://dali.gogol.net.cn/Article/details/gt2vybqecjp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gt2hjiynztf.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gt2miiteenc.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gt2tekejime.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gt2bclnevvv.html

[U14] Py：分组收集到列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtbckguq.html

defaultdict(list)
来源：http://dali.sysykeji.top/Article/details/gt2vdtyhtlt.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gt2nvqglzjv.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gt2fpgccshf.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gt2quuonnbq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258.top/Article/details/gt2dxlqwpet.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gt2ffdhmpun.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gt2vngrwime.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gt2ngujdfcs.html

pat = re.compile(r"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2pqwwfjnv.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gt2xhesujet.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gt2bpyxsjxm.html

[U20] Py：缓存函数结果
来源：http://dali.chenzaomai.com/Article/details/gt2btuggaud.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gt2niupddzy.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gt2fozsnozj.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ieaszrqw.html

[U22] Py：矩阵转置
来源：http://dali.hysaishi.cn/Article/details/gt2dhmuqfxo.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yawjknqn.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gt2ylojgaoo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gt2tdvowepi.html

[U24] Py：路径操作
来源：http://dali.vqdsnc.cn/Article/details/gt2grwpixjt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2pabaaxlu.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gt2sscnfuwi.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gt2pdqspneb.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gt2nzjmdabd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gt2izejbowi.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gt2gxxexrwm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gt2ruebfsms.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gt2dvxolkcd.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gt2pqdzvqqs.html

[U29] Py：属性校验
来源：http://dali.zdqjudy.top/Article/details/gt2vajxauqh.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gt2pkgxehcp.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gt2lcgrwjfm.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gt2xaylsfld.html

[U31] Py：单测
来源：http://dali.gogol.net.cn/Article/details/gt2pyhhxday.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2ohpsmawp.html

[U32] Py：代码格式化
来源：http://dali.yonumen.top/Article/details/gt2tserlotu.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gt2rbfipqib.html

[U33] Py：打包发布
来源：http://dali.tanke756.top/Article/details/gt2ipkulept.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gt2hxrrcrex.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gt2uiqszzwf.html

chardet.detect(raw)
来源：http://dali.cheryme.top/Article/details/gt2cbnqylox.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gt2jqoabkip.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gt2debbqhyk.html

[U36] Py：定时任务
来源：http://dali.bjfxy.top/Article/details/gt2qpcinttp.html

schedule.every(10).minutes.do(job)
来源：http://dali.ydzc1.top/Article/details/gt2enfxclwu.html

[U37] Py：读写 Excel
来源：http://dali.bjfxy.top/Article/details/gt2ixrnvsov.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fiwussvl.html

[U38] Py：获取脚本所在目录
来源：http://dali.yanxiufei.cn/Article/details/gt2httmukss.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gt2eqlytmec.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gt2jlvhsvqv.html

sys.stdout.isatty()
来源：http://dali.tian-w.cn/Article/details/gt2jbgfbgmt.html

[U40] Py：打印到标准错误
来源：http://dali.hywenlv.cn/Article/details/gt2gmqboyxi.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2vfgtrskg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zdqjudy.top/Article/details/gt2segownai.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuombbmy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gt2urhptyyb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gt2hceblgne.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gt2pglaafwl.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gt2kwnpixta.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gt2cwhfsmco.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xusxfefi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gt2tihipgcf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2pkqcndki.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gt2mecnkuqs.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjsyrlzg.html

[U47] PHP：联合类型
来源：http://dali.haohaochexian.top/Article/details/gt2pwzikqqm.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gt2mzmoihhq.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gt2vxiuapob.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hysaishi.cn/Article/details/gt2vfzwzefn.html

[U49] PHP：只读属性
来源：http://dali.hywenlv.cn/Article/details/gt2kotognrn.html

public readonly string $name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipyjggaw.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gt2tbzkwnkh.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gt2glnitctv.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gt2kpanxczm.html

[$a, $b] = $arr;
来源：http://dali.9152youxi.cn/Article/details/gt2eqtjbxmi.html

[U52] PHP：箭头函数
来源：http://dali.daria6918.cn/Article/details/gt2oqbmavgw.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2bnldjqdj.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258.top/Article/details/gt2fyodydam.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gt2rinxnauf.html

[U54] PHP：空安全调用
来源：http://dali.meibo888.top/Article/details/gt2tobejrts.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2encafrcq.html

[U55] PHP：match 表达式
来源：http://dali.sxryk.cn/Article/details/gt2evuwwvlt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.havefunace.top/Article/details/gt2lsfefabc.html

[U56] PHP：命名参数
来源：http://dali.tianlin.xyz/Article/details/gt2ytlfscqw.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2ktlkexdv.html

[U57] PHP：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2atzhyjvc.html

"值: {$a}"
来源：http://dali.bjfxy.top/Article/details/gt2gumfpiwz.html

[U58] PHP：数组三件套
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2canxhchl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cheryme.top/Article/details/gt2rvvcdlhn.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrtaftef.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2zosppxew.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlbyzepw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aizwys.cn/Article/details/gt2ezjvnfuq.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gt2zqsmcmvp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2hrtgljpl.html

[U62] PHP：日期对象
来源：http://dali.zdqjudy.top/Article/details/gt2ffmxpwxx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdghtgiu.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gt2ytjddide.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gt2dhmxliyw.html

[U64] PHP：目录遍历
来源：http://dali.yuxming.cn/Article/details/gt2vvauvsya.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sufxvd.cn/Article/details/gt2csartcmq.html

[U65] PHP：会话
来源：http://dali.c1oappe.top/Article/details/gt2tvyqqfqg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2eyzcdhyi.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gt2mgrvgxzg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gt2znfreccj.html

[U67] PHP：处理文件上传
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfunoddl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cdnleiting.top/Article/details/gt2ruqvqdqj.html

[U68] PHP：PDO 连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uucbxkzz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djmripxe.html

[U69] PHP：PDO 预处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2slleykmd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uynwgkwj.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gt2gwvefyqx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqffmjbt.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2nqurmdid.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gt2qwyybakd.html

[U72] PHP：写错误日志
来源：http://dali.xuanzx.com/Article/details/gt2dzzdctas.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sxryk.cn/Article/details/gt2jaeyvfvr.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gt2ppsblhxa.html

parse_ini_file("config.ini", true)
来源：http://dali.yanxiufei.cn/Article/details/gt2qlxklznu.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2uieynjpd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangdashe.top/Article/details/gt2ntazitmf.html

[U75] PHP：依赖注入
来源：http://dali.tianlin.xyz/Article/details/gt2tbcjaove.html

composer require psr/container
来源：http://dali.aibaodan.cn/Article/details/gt2vecdvcqo.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gt2lesuaneh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpvcyte.html

[U77] PHP：模板渲染
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amudzuuu.html

composer require twig/twig
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtnevhtv.html

[U78] PHP：单元测试
来源：http://dali.zhixingplan.top/Article/details/gt2fpldfzgk.html

composer require --dev phpunit/phpunit
来源：http://dali.shzxlz.cn/Article/details/gt2ovubmzyn.html

[U79] PHP：静态分析
来源：http://dali.svipenyu.cn/Article/details/gt2uxyaxikl.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gt2rvuknebp.html

[U80] PHP：代码规范修复
来源：http://dali.quarkkingdee.top/Article/details/gt2kuthpafi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.redwolf501.top/Article/details/gt2cdpzmfvn.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gt2tijhfafw.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gt2bqxcbeil.html

[U82] JS：package.json 脚本
来源：http://dali.shzxlz.cn/Article/details/gt2vpdbiqqe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gt2jiqmbppk.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgfzy.top/Article/details/gt2drhxdoej.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2ihjyuxru.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gt2kooeeebl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sysykeji.top/Article/details/gt2apolkmcq.html

[U85] JS：可选链
来源：http://dali.yuxming.cn/Article/details/gt2zvribrjd.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzuwzklm.html

[U86] JS：空值合并
来源：http://dali.zhengqikj.top/Article/details/gt2jgovwlbc.html

a ?? b
来源：http://dali.cashguo.top/Article/details/gt2kiafkzzy.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkjfqfli.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenlongwang.top/Article/details/gt2orvpswbr.html

[U88] JS：对象展开合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2nihlgnur.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gt2cwpojrum.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdqfcpxk.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2vokbovuc.html

[U90] JS：数字数组排序
来源：http://dali.zhoulong.xyz/Article/details/gt2ptgubbdt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2yiebtith.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gt2vamzuurd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cashguo.top/Article/details/gt2zupnloog.html

[U92] JS：深拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2kpynbdqb.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2zgfsfcik.html

[U93] JS：模板字符串
来源：http://dali.yj20258.top/Article/details/gt2zaedgsfj.html

`共 ${n} 条`
来源：http://dali.vqdsnc.cn/Article/details/gt2vzmapuhi.html

[U94] JS：箭头函数
来源：http://dali.xziqi.cn/Article/details/gt2nxqxdmhi.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gt2vfhnaono.html

[U95] JS：Promise 包装
来源：http://dali.jlsjyb.cn/Article/details/gt2skzprfaj.html

new Promise((resolve, reject) => {})
来源：http://dali.sysykeji.top/Article/details/gt2aqqgnqqb.html

[U96] JS：async/await 与异常
来源：http://dali.havefunace.top/Article/details/gt2ahzkdhcq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2itjrlzqp.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gt2lhgxazjj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnolnrxy.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gt2xweabggc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhgijwfk.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gt2ykhlxctq.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gt2opbzcnyl.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gt2xydetlnz.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gt2geewfpic.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gt2huyyadnd.html

el.classList.toggle("active")
来源：http://dali.yanxiufei.cn/Article/details/gt2fjbxwqlv.html

[U102] JS：本地存储
来源：http://dali.sxryk.cn/Article/details/gt2kfjgjgrv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gt2abtgihqo.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gt2rxkqrjur.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gt2dxnyrxsz.html

[U104] JS：防抖
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqyjjord.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2hnshvvyr.html

[U105] JS：节流
来源：http://dali.tianlin.xyz/Article/details/gt2mczfelwa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhixingplan.top/Article/details/gt2rsjktbjf.html

[U106] JS：日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2gxxbrybp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nidcgwyo.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gt2dmrdsfth.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2gqekblvw.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gt2orlioigi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gt2rtrutrij.html

[U109] JS：数组分组
来源：http://dali.redwolf501.top/Article/details/gt2iiclbqps.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgruouvx.html

[U110] JS：数组分块
来源：http://dali.mhx1999.top/Article/details/gt2lqnptrfc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xinyue.icu/Article/details/gt2upslxkci.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gt2evexbfnh.html

new Map(Object.entries(obj))
来源：http://dali.yueranfly.top/Article/details/gt2bcnjmofc.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gt2nqmaatcv.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2negdpbye.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gt2kbxrqhpa.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2orolpmtp.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gt2mtgvgkeb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2pkmmxvhp.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gt2dtvkwqfw.html

crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2dphffgmk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daria6918.cn/Article/details/gt2fqkzlhpj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2gzhvppxy.html

[U117] JS：单元测试
来源：http://dali.ivvv.top/Article/details/gt2npigbcgb.html

npm i -D vitest;  npx vitest
来源：http://dali.kuanghao11.cn/Article/details/gt2kxheffbo.html

[U118] JS：开发服务器
来源：http://dali.shzxlz.cn/Article/details/gt2teoxjils.html

npm i -D vite;  npx vite
来源：http://dali.gzhubu.top/Article/details/gt2takginrh.html

[U119] JS：生产构建
来源：http://dali.zhoulong.xyz/Article/details/gt2ejloznnc.html

npx vite build
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrbqsapb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gt2qjzwbkfc.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gt2ycviwujh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ietmhauz.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gt2cczyaxyk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2fsmyuofp.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gt2kiqgyzex.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2wfoejdej.html

PHP ............ 252
来源：http://dali.birdmap.top/Article/details/gt2ckduwimd.html

JavaScript ..... 252
来源：http://dali.bjfxy.top/Article/details/gt2wfealxez.html

TypeScript ..... 212
来源：http://dali.sufxvd.cn/Article/details/gt2asjaitvc.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2iydetwfc.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gt2fyzeltso.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2bjdutlkx.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gt2suljgrvn.html

C .............. 30
来源：http://dali.xziqi.cn/Article/details/gt2babcidva.html

C++ ............ 30
来源：http://dali.sweek.top/Article/details/gt2ufuwlftl.html

SQL ............ 90
来源：http://dali.yj202588.top/Article/details/gt2cybzkbbr.html

Bash ........... 80
来源：http://dali.aizwys.cn/Article/details/gt2eguvfbsj.html

Kotlin ......... 15
来源：http://dali.316326.xyz/Article/details/gt2zplvczkb.html

Swift .......... 15
来源：http://dali.svipenyu.cn/Article/details/gt2khlbtivv.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjqpvumh.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gt2ooinxrpa.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gt2onvivwfa.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2drkxqnyc.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gt2zytwmndu.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gt2ghmivaoq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gt2ucxkgclk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2pxgzredw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gt2exgdkaco.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gt2pvgeiswn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.havefunace.top/Article/details/gt2isbxxzif.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gt2prcefomh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gt2ufmwisyt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2mrpkqmga.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oybvcnzc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2xoosuhzj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szncjibc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gt2ixfyavmf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2ppdqkhwb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gt2ulcsnnbe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ivvv.top/Article/details/gt2bspbghch.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2gapciymj.html


<!-- 参考信息 -->