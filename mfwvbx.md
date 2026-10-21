代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gtswzvgxkp.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtcehltoiu.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtdjoefmar.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtovhbaxgu.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtxvntvcsv.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gtrvdrspwa.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gtzwobfouc.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gtsbrqpnts.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gtoacxwjnu.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gtzdoyigaz.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gtcqegvviw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gtjzxjdgtw.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfspleeb.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtmjxnnwqi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtlqoqxrph.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gtfzndvvey.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtntygaagl.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbqyqmog.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtlraeoqeh.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gtbxojhfxb.html

[U15] Py：高精度计时
来源：http://dali.wangdashe.top/Article/details/gtwvvqdbwt.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtphnuibdu.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gteivhyhds.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtwlvsvhfa.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtpggbgjnv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gtthwvhqtk.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpanqscoh.html

pat = re.compile(r"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtzpgtfgtu.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtibdfdqlz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtkbufobrr.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtwndvxeoo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gtygxtvtwg.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtnmrjzubq.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gttnskpzzd.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gtirsfbipd.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gttgtcfhlk.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gtuubxgipu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gthpvceint.html

[U24] Py：路径操作
来源：http://dali.316326.xyz/Article/details/gtyjuiudlt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtnrerbjdz.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gtthpglklr.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gtnijrvafg.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gttvunrfot.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtikaxsuxm.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtcmzixuju.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gtvzeukdmc.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gthmemelan.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyculefoi.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtaxusgprf.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gtzywbokcy.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruukmaeu.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtabiknink.html

[U31] Py：单测
来源：http://dali.tianlin.xyz/Article/details/gttaxgzdfe.html

python -m pytest -q
来源：http://dali.jqgufenzy.top/Article/details/gtlwftlerj.html

[U32] Py：代码格式化
来源：http://dali.wangdashe.top/Article/details/gtnyjpiuea.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gtehibcthy.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtwobmdrdq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbryykysd.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gtqdhmpain.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtqxkatsdf.html

[U35] Py：发送邮件
来源：http://dali.nanxinkj.top/Article/details/gtkcusrkqp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gtvuhryppm.html

[U36] Py：定时任务
来源：http://dali.bjfxy.top/Article/details/gtsoklcdiq.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtoutygupe.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtztktpiga.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gtlrvrxkoh.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gttnlsyvzf.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gtlfxpquxv.html

[U39] Py：判断是否在交互环境
来源：http://dali.bjfxy.top/Article/details/gtazyijsit.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gtwqakbnwn.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtrcvjzfpg.html

print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtqzywopex.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hysaishi.cn/Article/details/gtdihomtqa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gtkijurrju.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nwbrower.top/Article/details/gttuqxptfi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gtsdwsjgwx.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtjvopupni.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gtipihpspj.html

[U44] PHP：开启严格类型
来源：http://dali.jlsjyb.cn/Article/details/gtzxotdsru.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtwfjkyqlm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ybcxt.top/Article/details/gtwaqqrgqh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtnraiczlh.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gtjlkkqkic.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllioutby.html

[U47] PHP：联合类型
来源：http://dali.nanxinkj.top/Article/details/gtojugggfx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gttzkpbdtj.html

[U48] PHP：纯枚举
来源：http://dali.0kj1m.cn/Article/details/gtxhzkgbyr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gtybxnhodu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gtpzzipefn.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gtggdvaykk.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gtmacougkv.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gtnxmiqnhy.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtdepjxltf.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gtyugkfune.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtarbmnpgv.html

$double = fn($x) => $x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gtoolouryk.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtesfqlwjh.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbbvqnen.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gtvpzxaymc.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gtqwpyqcli.html

[U55] PHP：match 表达式
来源：http://dali.jinqigufen.top/Article/details/gtfyuxvtyc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gtsarwlljp.html

[U56] PHP：命名参数
来源：http://dali.yj202588.top/Article/details/gttfscloop.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtdqihjjor.html

[U57] PHP：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtbagyfhsa.html

"值: {$a}"
来源：http://dali.jinqigufen.top/Article/details/gtiksxlneb.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gtcrvuzvng.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sxryk.cn/Article/details/gtlsxhzrkr.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gtxlqqygfu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtasgapoxd.html

[U60] PHP：JSON 编解码
来源：http://dali.jiagoushi.top/Article/details/gtflziwvjr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.haohaochexian.top/Article/details/gtmwmmqcot.html

[U61] PHP：正则
来源：http://dali.hysaishi.cn/Article/details/gtwrtyjxdg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtrnqyrepo.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gtcqbqcfrs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gtrmsdftbu.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gttktdtglm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gzhubu.top/Article/details/gtgekcmbhx.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gtqrygkmxd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgufenzy.top/Article/details/gtkkjktouc.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gttltuizyk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258.top/Article/details/gtoclkrnkj.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtviwnzdol.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gtqswfrtup.html

[U67] PHP：处理文件上传
来源：http://dali.jinghuilouyu.cn/Article/details/gttolpvndb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.havefunace.top/Article/details/gtzpkqxfxe.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtpuojvtiz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gtwdmxvqlp.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gttyjanfbd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprzncutv.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gtbjaabzuk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxinkj.top/Article/details/gtscxbruao.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrlbragj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtoqkkceab.html

[U72] PHP：写错误日志
来源：http://dali.hnqzz.top/Article/details/gtobystobo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtgnhfdqio.html

[U73] PHP：读取 ini 配置
来源：http://dali.jqgufenzy.top/Article/details/gtfmjzfuwa.html

parse_ini_file("config.ini", true)
来源：http://dali.zhiwuduotai.top/Article/details/gtndwfmevq.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtjkordqpv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fzhhl.top/Article/details/gtpwaoupzj.html

[U75] PHP：依赖注入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpnfovaf.html

composer require psr/container
来源：http://dali.xylfe.cn/Article/details/gtuwestpzs.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyidazwi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhongyouzk.top/Article/details/gtqvqfwflt.html

[U77] PHP：模板渲染
来源：http://dali.jinghuilouyu.cn/Article/details/gttosrhfay.html

composer require twig/twig
来源：http://dali.zhiwuduotai.top/Article/details/gtqakadisd.html

[U78] PHP：单元测试
来源：http://dali.sufxvd.cn/Article/details/gtbunopzaz.html

composer require --dev phpunit/phpunit
来源：http://dali.svipenyu.cn/Article/details/gtvkuggcgw.html

[U79] PHP：静态分析
来源：http://dali.gogol.net.cn/Article/details/gtphgxxamx.html

composer require --dev phpstan/phpstan
来源：http://dali.jinqigfzy.top/Article/details/gtssbbysgo.html

[U80] PHP：代码规范修复
来源：http://dali.yvedp.cn/Article/details/gtxamqnfem.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.bjfxy.top/Article/details/gtemmxsypc.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gttallzqwb.html

npm init -y;  npm i express
来源：http://dali.zhongyouzk.top/Article/details/gtnobpkieo.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gtohfvodet.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxhjfjcj.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuxming.cn/Article/details/gtdtkjtsor.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtejqwtyle.html

[U84] JS：CommonJS 写法
来源：http://dali.sysykeji.top/Article/details/gtlibirjxh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gttabiiprg.html

[U85] JS：可选链
来源：http://dali.fengsongda.top/Article/details/gtpjecrnwg.html

a?.b?.c
来源：http://dali.dashuyun.cn/Article/details/gtgncnzhwm.html

[U86] JS：空值合并
来源：http://dali.yanxiufei.cn/Article/details/gtmqtfrlwj.html

a ?? b
来源：http://dali.ehwqpu.com/Article/details/gtzzgkkwms.html

[U87] JS：解构默认值
来源：http://dali.vqdsnc.cn/Article/details/gtdutkghzw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tianlin.xyz/Article/details/gtnkvekdtk.html

[U88] JS：对象展开合并
来源：http://dali.zhiwuduotai.top/Article/details/gtltjfgrjw.html

{ ...a, ...b }
来源：http://dali.hnxiangtu.top/Article/details/gtjikzkyma.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtwplgdmpg.html

[...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtisfplpik.html

[U90] JS：数字数组排序
来源：http://dali.aizwys.cn/Article/details/gttdakhmai.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtooilldba.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gtmdxdpowe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gtrdfolaqe.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhfsemac.html

structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtgqoodgji.html

[U93] JS：模板字符串
来源：http://dali.aizwys.cn/Article/details/gtyzfhwspc.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gtldjqtjjb.html

[U94] JS：箭头函数
来源：http://dali.jianghu66.top/Article/details/gthtlpggnm.html

const double = x => x * 2;
来源：http://dali.jinqigufen.top/Article/details/gttdturkuq.html

[U95] JS：Promise 包装
来源：http://dali.fengsongda.top/Article/details/gtcswcrvqo.html

new Promise((resolve, reject) => {})
来源：http://dali.sweek.top/Article/details/gtfwqlkbjv.html

[U96] JS：async/await 与异常
来源：http://dali.nanxuanxn.top/Article/details/gtrpqevbog.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtarrekvmr.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtvwcjwoxg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtrgwyzixj.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtmumzbxmv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinqigufen.top/Article/details/gtkaqsiali.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gtovklhjhj.html

el.addEventListener("click", e => {})
来源：http://dali.yangfankeji.com/Article/details/gthknmkqbk.html

[U100] JS：DOM 查询
来源：http://dali.andypj.xyz/Article/details/gtuknykgqu.html

document.querySelector(".item")
来源：http://dali.ivvv.top/Article/details/gtjeqknlgy.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gtfjhuowzj.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gtyahqctrj.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gteljtwcoo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.9152youxi.cn/Article/details/gtxgfhofky.html

[U103] JS：定时器
来源：http://dali.zhiwuduotai.top/Article/details/gtrcwxdnhq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.feifeiyinyue.top/Article/details/gtyolvvbzz.html

[U104] JS：防抖
来源：http://dali.ybcxt.top/Article/details/gtzuhlscfv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtnjnpcfhn.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gthwtmqarh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gogol.net.cn/Article/details/gttzxbiwpd.html

[U106] JS：日期格式化
来源：http://dali.zdqjudy.top/Article/details/gttqvbguob.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtilswhklz.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gthvejfyvp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gthgldwrbr.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gttewyxptd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.feifeiyinyue.top/Article/details/gtggterehr.html

[U109] JS：数组分组
来源：http://dali.jianghu66.top/Article/details/gtaanxoczv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtfimnqqqq.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gtdfbpstct.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.andypj.xyz/Article/details/gtytnfwxzj.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtsgzdlgim.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtmuynilaf.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gtaitunjva.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gttcqxsqoi.html

[U113] JS：正则替换全部
来源：http://dali.yvedp.cn/Article/details/gtnsgolwzc.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtlagqbunk.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gtaykeoats.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtrshkkndc.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtaugcvszn.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtbbryyrwp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shangyingyoupin.top/Article/details/gtdizgxcxq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hywenlv.cn/Article/details/gtflmhxrfu.html

[U117] JS：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtyboxtcbo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhoulong.xyz/Article/details/gtpdyfxqgc.html

[U118] JS：开发服务器
来源：http://dali.cdnleiting.top/Article/details/gtysmradhj.html

npm i -D vite;  npx vite
来源：http://dali.yanxiufei.cn/Article/details/gtltmgkujo.html

[U119] JS：生产构建
来源：http://dali.nanxuanxn.top/Article/details/gtbgfcrbod.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gttztybjvl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeoblinx.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gtusbsgufv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gterbuhhdl.html

统计汇总
来源：http://dali.sweek.top/Article/details/gtbxasycmf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlnvcdbze.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtzfkdgbxi.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gtnabhqxad.html

PHP ............ 252
来源：http://dali.ehwqpu.com/Article/details/gttmimwfyd.html

JavaScript ..... 252
来源：http://dali.xziqi.cn/Article/details/gtfbkunjtz.html

TypeScript ..... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtudxopjkv.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gteasirknk.html

Go ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtcgwlznfk.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtotwpfhmz.html

C# ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gthmpfwxvv.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtzlucxfep.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gtvndslqey.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtyzvlmbqi.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gttoprlwng.html

Kotlin ......... 15
来源：http://dali.xziqi.cn/Article/details/gtcvwriatm.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gttdiyxbto.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gtzfkqbmsp.html

Perl ........... 10
来源：http://dali.c1oappe.top/Article/details/gtxsbflzsr.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gtpqaltdtm.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gttnzgykun.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gtxwhrsswb.html

按章节统计：
来源：http://dali.ybcxt.top/Article/details/gteacybdyr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtgnadoinu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtqzutonrl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtecaocnwo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqkrwuxf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.smart0.xyz/Article/details/gtzwkufman.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtzkcgnpaq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtkobqgykd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gtkrxmwgps.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtiyergybs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gtjuirxogc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtoazpvudq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gthramegkc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtcfeazvgx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtcseuehrb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gtaqdjdmqz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtuuxhcigo.html

Q SQL 专题                              90
来源：http://dali.yonumen.top/Article/details/gtvpcluoco.html

R Bash 专题                             80
来源：http://dali.jinyuanbaomall.cn/Article/details/gteweieasj.html

S C / C++ 专题                          60
来源：http://dali.zhiwuduotai.top/Article/details/gtsijixefn.html

T 其他语言补充                          60
来源：http://dali.0kj1m.cn/Article/details/gtvgwuzkrr.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gtvzdpjbnh.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtawanxqbb.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gttqetspni.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtaonkeumh.html

使用提醒
来源：http://dali.dashuyun.cn/Article/details/gtezbrfgod.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtszwosnpg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gtcayrihsr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pycfn.com/Article/details/gtcsfyhqqn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pengpengdd.cyou/Article/details/gtvrzdsfxy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shangyingyoupin.top/Article/details/gtntcxjryl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gzhubu.top/Article/details/gtpgnoitwq.html

—— 文件结束 ——
来源：http://dali.zhoulong.xyz/Article/details/gtnafnjmlw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtoxhawzda.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtuwguizxi.html

Common Programming Examples Cheat Book
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotpsgcoj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdyubrpig.html

【收录内容】
来源：http://dali.feifeiyinyue.top/Article/details/gtocdvnayi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nwbrower.top/Article/details/gttlttzdmh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gtcexaaggp.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gtimpcyomm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinghuilouyu.cn/Article/details/gtctxnmdgc.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gtfyhtnupa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cashguo.top/Article/details/gtwkuvjyqx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sweek.top/Article/details/gtasabrdad.html


<!-- 参考信息 -->