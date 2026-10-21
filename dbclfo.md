代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxfdohjb.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtblojcufz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtbqtryulg.html

[T60] Scala：折叠
来源：http://dali.yueranfly.top/Article/details/gtcpnpouxk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtgrwwzfhu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxwwkfmtd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtwbayagqu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmuaradms.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtikjuncwm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkatnddw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gtzklvtamd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtxwbwxvye.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gtqxtjmxod.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gtnvvazywk.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtejwtpwzm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gtsypkmrwe.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gtsaoewyuf.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtbaqelwnk.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtwsjmxcfz.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gtnfxywqui.html

[U07] Py：反转字典键值
来源：http://dali.meibo888.top/Article/details/gtmmllcxcn.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gtsrelorms.html

[U08] Py：展平二维列表
来源：http://dali.cucudq.cn/Article/details/gtdwxsorhr.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gtrwzgbzjr.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gtvahjxjei.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gtmvulukrr.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtjykjxanl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gtsbenjzrz.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtmolnmwjk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gtmafxicsm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtnrqgbmza.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtdupevcrv.html

[U13] Py：固定长度队列
来源：http://dali.hfpthk.cn/Article/details/gtusbfktnt.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyfcwoyq.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gtldxonncy.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtexenpitz.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtqudocivm.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gtzyjwezpi.html

[U16] Py：命令行参数解析
来源：http://dali.redwolf501.top/Article/details/gtgjimbzca.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hysaishi.cn/Article/details/gtyedchzam.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtjdooosrf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtcrlqtvev.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtkwdazsmd.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtillcjgqa.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gtptdwdslb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhiwuduotai.top/Article/details/gtyxejqcfo.html

[U20] Py：缓存函数结果
来源：http://dali.tianlin.xyz/Article/details/gtafgimshy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.birdmap.top/Article/details/gtympcdqlu.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtxjubpjbc.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gtvnlrenwc.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjhsyvwi.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gtqfjomcsb.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gttrovmtpc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gtshisnygy.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gtghzslirk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtakmamvfx.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gtrolsonen.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtnrhehtjx.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gtpzdicgyo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gtfvhekvjt.html

[U27] Py：异步 HTTP
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbglbzdc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gteuxzmcoo.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gtzeekwdpj.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtlfxfcikc.html

[U29] Py：属性校验
来源：http://dali.wangdashe.top/Article/details/gttyobtzaw.html

@property 与 @x.setter 配合
来源：http://dali.nanxuanxn.top/Article/details/gtzxfasslp.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gtvvhzgotb.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gtbudvkeon.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gtsxsxfgld.html

python -m pytest -q
来源：http://dali.shangyingyoupin.top/Article/details/gtirybfjyx.html

[U32] Py：代码格式化
来源：http://dali.zdqjudy.top/Article/details/gtaedredlw.html

ruff format . && ruff check --fix .
来源：http://dali.guannengcc.top/Article/details/gtjccklpwm.html

[U33] Py：打包发布
来源：http://dali.zycfv.cn/Article/details/gtvksmkger.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gteujysqqz.html

[U34] Py：判断编码
来源：http://dali.gzhubu.top/Article/details/gtbafybeib.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtfggorkys.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gtmgnsyekr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gtztrcummf.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gtdemarpir.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtwrkefquw.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gttyrxnidx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xylfe.cn/Article/details/gtqipjtkbk.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gtmtqaplap.html

Path(__file__).resolve().parent
来源：http://dali.chenlongwang.top/Article/details/gtmzpakfxb.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gttonxrbjy.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gtjvqaqmol.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gtcsfcdpdi.html

print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtmzpwrwvf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jianghu66.top/Article/details/gtuluioaqc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.smart0.xyz/Article/details/gtvyvgyfff.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yueranfly.top/Article/details/gtihskkbqq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gtevqeqjvh.html

[U43] PHP：声明命名空间
来源：http://dali.tanke756.top/Article/details/gtokyiinxt.html

namespace App\Http;
来源：http://dali.sufxvd.cn/Article/details/gthaztapzw.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gtcfdbmwvn.html

declare(strict_types=1);
来源：http://dali.shangyingyoupin.top/Article/details/gtnmpotruf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.vqdsnc.cn/Article/details/gtqkvesmnj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtgktcstma.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gttafsfurr.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gtynnjqvdz.html

[U47] PHP：联合类型
来源：http://dali.c1oappe.top/Article/details/gttxhcksub.html

int|string $id
来源：http://dali.aizwys.cn/Article/details/gtrxzrqtjh.html

[U48] PHP：纯枚举
来源：http://dali.guowangkeji.top/Article/details/gtcxslprqe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgufenzy.top/Article/details/gtnvmsfwlr.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtjjmavvih.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gtxmmjgjxt.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gtfmwkrwur.html

public function __construct(private int $id) {}
来源：http://dali.yonumen.top/Article/details/gtqdgvtrsj.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gtpgkfiwfh.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gtuivfaywq.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmdpwryff.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gtivzohdat.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gtzwjwzcaf.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gttlfwpxnf.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gthguaogad.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gtrqryjumh.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gtxzhdlkrf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtyjuctpnk.html

[U56] PHP：命名参数
来源：http://dali.xylfe.cn/Article/details/gtetnigiqh.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtxmptqpyv.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtfemvunbo.html

"值: {$a}"
来源：http://dali.redwolf501.top/Article/details/gtswerdsdx.html

[U58] PHP：数组三件套
来源：http://dali.cucudq.cn/Article/details/gtxkqyipxx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shzxlz.cn/Article/details/gtyrtwnweh.html

[U59] PHP：自定义排序
来源：http://dali.jiagoushi.top/Article/details/gtdycawlza.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnbyabxj.html

[U60] PHP：JSON 编解码
来源：http://dali.hnqzz.top/Article/details/gtkuakxpfg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gtzolcpnel.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gttqauqzim.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtrsngyxgr.html

[U62] PHP：日期对象
来源：http://dali.cashguo.top/Article/details/gtmrxsfjpr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gtzxgrayzb.html

[U63] PHP：文件读写
来源：http://dali.gogol.net.cn/Article/details/gtrbsjdqav.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ybcxt.top/Article/details/gtvyrfdvwb.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gtqwsxroyc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xziqi.cn/Article/details/gtjqdspkek.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtuknoxila.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjswiizbs.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gtwqbylinq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zycfv.cn/Article/details/gtweemqxpt.html

[U67] PHP：处理文件上传
来源：http://dali.guowangkeji.top/Article/details/gtojgcitlc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gtotfwtxwb.html

[U68] PHP：PDO 连接
来源：http://dali.daxiang520.top/Article/details/gtcebscvoo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gtalanxaja.html

[U69] PHP：PDO 预处理
来源：http://dali.shangyingyoupin.top/Article/details/gtpgyxvohe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.9152youxi.cn/Article/details/gtsujngqff.html

[U70] PHP：PDO 事务
来源：http://dali.wangdashe.top/Article/details/gtilgizwou.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gtjhenmvjo.html

[U71] PHP：抛出异常
来源：http://dali.yueranfly.top/Article/details/gtmxxydchi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtzjtvoypg.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gtsdaqplsv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yangfankeji.com/Article/details/gtyzoikmsh.html

[U73] PHP：读取 ini 配置
来源：http://dali.quarkkingdee.top/Article/details/gtvllpkvhm.html

parse_ini_file("config.ini", true)
来源：http://dali.tanke756.top/Article/details/gtxookddkd.html

[U74] PHP：读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtioiusgqv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gtlhirkhrd.html

[U75] PHP：依赖注入
来源：http://dali.9152youxi.cn/Article/details/gtqvbdbjcx.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gtwksasjsw.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkwxsnxt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hywenlv.cn/Article/details/gtkhhallfj.html

[U77] PHP：模板渲染
来源：http://dali.ydzc1.top/Article/details/gtzkxunqyy.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gtkicremxo.html

[U78] PHP：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtsdisrgwy.html

composer require --dev phpunit/phpunit
来源：http://dali.jiagoushi.top/Article/details/gtemssgayv.html

[U79] PHP：静态分析
来源：http://dali.havefunace.top/Article/details/gtllqjupek.html

composer require --dev phpstan/phpstan
来源：http://dali.dashuyun.cn/Article/details/gtnbpuvhkf.html

[U80] PHP：代码规范修复
来源：http://dali.snrcjt.cn/Article/details/gtszmjijxl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shzxlz.cn/Article/details/gtzwretexg.html

[U81] JS：初始化项目
来源：http://dali.zycfv.cn/Article/details/gttevwmlvc.html

npm init -y;  npm i express
来源：http://dali.zhongyouzk.top/Article/details/gtacccnvwd.html

[U82] JS：package.json 脚本
来源：http://dali.hnxiangtu.top/Article/details/gtdafwvvnf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuanzhike.top/Article/details/gttkpttasu.html

[U83] JS：ES Module 导入导出
来源：http://dali.hfpthk.cn/Article/details/gtubfiltzc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtslqjjryq.html

[U84] JS：CommonJS 写法
来源：http://dali.ivvv.top/Article/details/gtfeshqybu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgfzy.top/Article/details/gteymmkvch.html

[U85] JS：可选链
来源：http://dali.yonumen.top/Article/details/gtobamzzqd.html

a?.b?.c
来源：http://dali.hammf.cn/Article/details/gthqbypoen.html

[U86] JS：空值合并
来源：http://dali.sxryk.cn/Article/details/gtdahhgdse.html

a ?? b
来源：http://dali.ppjwa.cn/Article/details/gttqwiieeq.html

[U87] JS：解构默认值
来源：http://dali.hnqzz.top/Article/details/gtbiyltrxw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ybcxt.top/Article/details/gtgvnjjrvu.html

[U88] JS：对象展开合并
来源：http://dali.fengsongda.top/Article/details/gtbzcndivi.html

{ ...a, ...b }
来源：http://dali.yueranfly.top/Article/details/gtchgkgqfw.html

[U89] JS：数组去重
来源：http://dali.nanxuanxn.top/Article/details/gtjhqjxcpa.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtitxveuvh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gtgcgvdafs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtlxuqsyxz.html

[U91] JS：对象键值遍历
来源：http://dali.jqgufenzy.top/Article/details/gtbflekggc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtlsmadouj.html

[U92] JS：深拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtruznwfqf.html

structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtjcmlcdbd.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gthpkozsag.html

`共 ${n} 条`
来源：http://dali.shangyingyoupin.top/Article/details/gtqimpoyev.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gtumglyzdo.html

const double = x => x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtaheotyhi.html

[U95] JS：Promise 包装
来源：http://dali.hongshengwenyu.top/Article/details/gthdntkzsc.html

new Promise((resolve, reject) => {})
来源：http://dali.yongpay.top/Article/details/gtqwirelfc.html

[U96] JS：async/await 与异常
来源：http://dali.ivvv.top/Article/details/gtzbqhevgh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gttainphyj.html

[U97] JS：并发请求
来源：http://dali.chenjidiqi.icu/Article/details/gtlvwtcrfn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtidfovqrj.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtorhgubbn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zdqjudy.top/Article/details/gtlffzdumr.html

[U99] JS：事件监听
来源：http://dali.yanxiufei.cn/Article/details/gthwninpne.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gtdfwpaugk.html

[U100] JS：DOM 查询
来源：http://dali.pycfn.com/Article/details/gtusbfcdia.html

document.querySelector(".item")
来源：http://dali.pengpengdd.cyou/Article/details/gtcvgiakbv.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gtvswipfth.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gthngvdiin.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gtaoeusdzo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gtlxnmiasp.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gttdaubgxc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.bjfxy.top/Article/details/gthsqdzopr.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gtzmzxpszl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtyxwhthqn.html

[U105] JS：节流
来源：http://dali.fengsongda.top/Article/details/gthcciegms.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cdnleiting.top/Article/details/gtsbjvyeot.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gtwrhtdzbi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gtvaojyibe.html

[U107] JS：数字千分位
来源：http://dali.fengsongda.top/Article/details/gtamvvatuq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtyfenuwuk.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqixyvkch.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nwbrower.top/Article/details/gtttfqvfto.html

[U109] JS：数组分组
来源：http://dali.hysaishi.cn/Article/details/gthamnvtry.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtrvhjtzzn.html

[U110] JS：数组分块
来源：http://dali.tian-w.cn/Article/details/gtwwkqtfrc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xziqi.cn/Article/details/gtrqffsrcl.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gtiuxxfkhh.html

new Map(Object.entries(obj))
来源：http://dali.bjfxy.top/Article/details/gtcfyukvtz.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gtaicttpwk.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtvpdhctzq.html

[U113] JS：正则替换全部
来源：http://dali.cdnleiting.top/Article/details/gtbklvshek.html

s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtzaglvwfj.html

[U114] JS：JSON 深比较
来源：http://dali.fzhhl.top/Article/details/gttjdnczva.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyipdbqs.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtunkhkegz.html

crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtfptbbdks.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxinkj.top/Article/details/gtbyulnnop.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtnmpfezap.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtmmmxwqut.html

npm i -D vitest;  npx vitest
来源：http://dali.zhixingplan.top/Article/details/gtrvhtwgaz.html

[U118] JS：开发服务器
来源：http://dali.kuanghao11.cn/Article/details/gtieuiwvaz.html

npm i -D vite;  npx vite
来源：http://dali.sxryk.cn/Article/details/gtffbclsfm.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gtebgvvmol.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gtndergbgv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtbuwwvixv.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtyqhilnqs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkhboywxs.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gtqkmcxlay.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpuapnntn.html

按语言统计（条）：
来源：http://dali.hongshengwenyu.top/Article/details/gtaknxavnd.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gtrqmkkmez.html

PHP ............ 252
来源：http://dali.jqgfzy.top/Article/details/gtsnuksaat.html

JavaScript ..... 252
来源：http://dali.fengsongda.top/Article/details/gtosnbmywt.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gttwqbgavz.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtuyibwtsx.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gtftwnlwkf.html

Ruby ........... 212
来源：http://dali.nwbrower.top/Article/details/gtpwcnvxza.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsoskqdd.html

C .............. 30
来源：http://dali.chenjidiqi.icu/Article/details/gtqphegucd.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gtjvjxfjpt.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gtnlkxticc.html

Bash ........... 80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelsqgtob.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtjbujtbxu.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtakvbdssn.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwotoezij.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtmbouimgp.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gtkugfpxqr.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtggbzaahs.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdlexrqb.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gthwtqxivl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtfipymokk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtsadnlrxz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtptfluivn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtdkfsmtxt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gtchltryaz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtklfozzff.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtorjintvq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gtwbltiehj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtkndogb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtrnvdwsyq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtfcoityzw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtujyeowvy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtmlhtxkfh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gtjzosujsx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fengsongda.top/Article/details/gttkhryuba.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtjwofqahr.html

Q SQL 专题                              90
来源：http://dali.yuxming.cn/Article/details/gtrvppkpnb.html

R Bash 专题                             80
来源：http://dali.hammf.cn/Article/details/gtlqcyybji.html

S C / C++ 专题                          60
来源：http://dali.nwbrower.top/Article/details/gtsjqrantv.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gtsripiupm.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gtnnpqwmev.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtgleskkda.html

合计                                  2106 条
来源：http://dali.hnxiangtu.top/Article/details/gtspszdjbv.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtispvhhzg.html

使用提醒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnsxburm.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtpjdqvilw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pengpengdd.cyou/Article/details/gtazasoyrg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cashguo.top/Article/details/gtwgmsllha.html


<!-- 参考信息 -->