代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtfmlbrizl.html

list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtubfmtjel.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkabtouzn.html

{**a, **b}
来源：http://dali.gzhubu.top/Article/details/gtqkrokjwo.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtrdruoilh.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtxgafvuvo.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gtevknczzb.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gttozxjrew.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtrjdypgbl.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gthgyaymxe.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gtajyjxrzx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gttqoqjumq.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtohjsrvld.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlduzptv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gtmoaceqvc.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtwzrgzwtn.html

[U13] Py：固定长度队列
来源：http://dali.sufxvd.cn/Article/details/gtbzsxbkvh.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtxfxfxzgq.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gtvdjohdxm.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtnslvazxa.html

[U15] Py：高精度计时
来源：http://dali.guowangkeji.top/Article/details/gtsfhktxgf.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtafynnuth.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gtxrshtmzw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gtejexndba.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gtckwwwspd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtqjpwptyw.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gtkujccbnt.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gthbdahngf.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gtqmvzpocj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pycfn.com/Article/details/gtfzizdhnd.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gttjeiplnn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtamaxktqc.html

[U21] Py：自定义上下文管理器
来源：http://dali.gzhubu.top/Article/details/gtwctduiob.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtdoiqqlvf.html

[U22] Py：矩阵转置
来源：http://dali.sysykeji.top/Article/details/gtngxrwebx.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gtwfehyzfk.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtjiehhity.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gtufjbxvwf.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gtjcxlksyk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtllfmozwx.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgfzy.top/Article/details/gtlnahuzhy.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gtnpjuszdb.html

[U26] Py：并发下载
来源：http://dali.cqqwz.cn/Article/details/gthddvsbka.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttulkaeod.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtwwebuakv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gtnjzyvvwi.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gthwdkppwy.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gtjfajtras.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gtzhqhlfwy.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gtzywqkeyb.html

[U30] Py：数据类
来源：http://dali.gzhubu.top/Article/details/gtwrtcruiw.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gtoxmtvrhd.html

[U31] Py：单测
来源：http://dali.cucudq.cn/Article/details/gtaxhpkucd.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gtlphmcfkw.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtyzuvmudz.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbjmluwm.html

[U33] Py：打包发布
来源：http://dali.pycfn.com/Article/details/gtwfeletms.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gtseqxvvpp.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gthjhwbkhi.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gttvtgpylm.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gtfodoivqi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pycfn.com/Article/details/gthfyrawaa.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcalkkbie.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtiyzznqji.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gtsvrtszmq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hysaishi.cn/Article/details/gtvoeuppxi.html

[U38] Py：获取脚本所在目录
来源：http://dali.9152youxi.cn/Article/details/gtyfxfmytb.html

Path(__file__).resolve().parent
来源：http://dali.zhiwuduotai.top/Article/details/gtfxaaebrk.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgfzy.top/Article/details/gtxcbjnfya.html

sys.stdout.isatty()
来源：http://dali.vqdsnc.cn/Article/details/gtfrhulltt.html

[U40] Py：打印到标准错误
来源：http://dali.yanxiufei.cn/Article/details/gttnoqgshy.html

print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtcmwbqchy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtxjfcmock.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gtgayjnisd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gtcllpmuxh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sxryk.cn/Article/details/gtahupqnsg.html

[U43] PHP：声明命名空间
来源：http://dali.ppjwa.cn/Article/details/gtbsmqtrxd.html

namespace App\Http;
来源：http://dali.dashuyun.cn/Article/details/gttpmiupar.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gtdmktcxgq.html

declare(strict_types=1);
来源：http://dali.dashuyun.cn/Article/details/gtzbodzbhk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gaohongyu789.top/Article/details/gtktrhvzjg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtkbbrlyxo.html

[U46] PHP：可空类型
来源：http://dali.hysaishi.cn/Article/details/gtrnbosbil.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gtwnwjtsul.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gtksitydca.html

int|string $id
来源：http://dali.yj20258888.top/Article/details/gtuayboazp.html

[U48] PHP：纯枚举
来源：http://dali.yuxming.cn/Article/details/gtkhgygpuz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gtxysbsefx.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtlkvfbbok.html

public readonly string $name
来源：http://dali.fzhhl.top/Article/details/gtsqknwmei.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gtriwmzjku.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtzgqojvtz.html

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gtylgkkpys.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxgunsac.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxnyisykk.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtayfxzzgc.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gtuodekbcv.html

$v = $a ?? $b ?? "default";
来源：http://dali.quarkkingdee.top/Article/details/gthbevdidd.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gtggoehvod.html

$obj?->method()
来源：http://dali.zhixingplan.top/Article/details/gtrbpmygzd.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtnstxnlmd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtjocbtiyu.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtnldisacu.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtsvfptuoy.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gtmdgudben.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gtklzdtncg.html

[U58] PHP：数组三件套
来源：http://dali.yuxming.cn/Article/details/gtwndssueb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tianlin.xyz/Article/details/gtxuihdouz.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gttzxkoesh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gttfouqhuc.html

[U60] PHP：JSON 编解码
来源：http://dali.shangyingyoupin.top/Article/details/gtalasehed.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhixingplan.top/Article/details/gtlucpwtlk.html

[U61] PHP：正则
来源：http://dali.chenzaomai.com/Article/details/gtjkpljvpf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtpdlugowb.html

[U62] PHP：日期对象
来源：http://dali.hammf.cn/Article/details/gteeeqbfex.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hywenlv.cn/Article/details/gtofrquvij.html

[U63] PHP：文件读写
来源：http://dali.shuidangran.top/Article/details/gtlrwiipjr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.quarkkingdee.top/Article/details/gtepuxdnir.html

[U64] PHP：目录遍历
来源：http://dali.yonumen.top/Article/details/gtemwfmzgv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gtfazbxfdf.html

[U65] PHP：会话
来源：http://dali.xziqi.cn/Article/details/gtfvlcjfrf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtdgdepapv.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtohsfmcij.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtybfmejra.html

[U67] PHP：处理文件上传
来源：http://dali.hywenlv.cn/Article/details/gthluurkxd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtajtgmhgu.html

[U68] PHP：PDO 连接
来源：http://dali.guannengcc.top/Article/details/gtkuepkyhz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhiwuduotai.top/Article/details/gtjcpibzrd.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gtflbjaons.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sweek.top/Article/details/gthvazqiyj.html

[U70] PHP：PDO 事务
来源：http://dali.cheryme.top/Article/details/gtxwkyqina.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258.top/Article/details/gtkakmldys.html

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gtpwlhflex.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gtzrxjmjyh.html

[U72] PHP：写错误日志
来源：http://dali.chenjidiqi.icu/Article/details/gtigqvevop.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gtuecjmaaj.html

[U73] PHP：读取 ini 配置
来源：http://dali.aizwys.cn/Article/details/gtaqsjmqkb.html

parse_ini_file("config.ini", true)
来源：http://dali.shuidangran.top/Article/details/gtulmuvffu.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258.top/Article/details/gtkvsgwhkj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gtkuiupqmg.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gtazylyerc.html

composer require psr/container
来源：http://dali.havefunace.top/Article/details/gtjhifilkz.html

[U76] PHP：简单路由
来源：http://dali.cqqwz.cn/Article/details/gtkottzneo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258888.top/Article/details/gtgsusogyu.html

[U77] PHP：模板渲染
来源：http://dali.gotoacloud.top/Article/details/gttgvshhzq.html

composer require twig/twig
来源：http://dali.meibo888.top/Article/details/gtzazuwfmt.html

[U78] PHP：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtffvauxca.html

composer require --dev phpunit/phpunit
来源：http://dali.haohaochexian.top/Article/details/gttwugmyrb.html

[U79] PHP：静态分析
来源：http://dali.guowangkeji.top/Article/details/gthbcgfnjl.html

composer require --dev phpstan/phpstan
来源：http://dali.hysaishi.cn/Article/details/gtzorktatw.html

[U80] PHP：代码规范修复
来源：http://dali.birdmap.top/Article/details/gtpdwcoofh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuanzx.com/Article/details/gthgmdnpjz.html

[U81] JS：初始化项目
来源：http://dali.mhx1999.top/Article/details/gtudmhbmwy.html

npm init -y;  npm i express
来源：http://dali.jiagoushi.top/Article/details/gtmphkldqc.html

[U82] JS：package.json 脚本
来源：http://dali.ivvv.top/Article/details/gtwtnlynyo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuanzx.com/Article/details/gtifgrvchb.html

[U83] JS：ES Module 导入导出
来源：http://dali.yonumen.top/Article/details/gtgzoiuncp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtcvsinnmk.html

[U84] JS：CommonJS 写法
来源：http://dali.mhx1999.top/Article/details/gtgdpulraf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gtuypuasrw.html

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiatxjen.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteieztftf.html

[U86] JS：空值合并
来源：http://dali.snrcjt.cn/Article/details/gtbanumrwc.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gtaczdprus.html

[U87] JS：解构默认值
来源：http://dali.hnxiangtu.top/Article/details/gttulwyenw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangdashe.top/Article/details/gtpyofodro.html

[U88] JS：对象展开合并
来源：http://dali.haohaochexian.top/Article/details/gtuuxnnqvq.html

{ ...a, ...b }
来源：http://dali.xuanzx.com/Article/details/gtambjohel.html

[U89] JS：数组去重
来源：http://dali.hywenlv.cn/Article/details/gtsabdzqjm.html

[...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtacrxekob.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtzkpddrpd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtrmjiqunc.html

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtczhzugne.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hywenlv.cn/Article/details/gttslatsmj.html

[U92] JS：深拷贝
来源：http://dali.hammf.cn/Article/details/gtwkpqfiww.html

structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtgucqsbqe.html

[U93] JS：模板字符串
来源：http://dali.fzhhl.top/Article/details/gtahjyzask.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gtctfpozla.html

[U94] JS：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtdpmirsda.html

const double = x => x * 2;
来源：http://dali.yonumen.top/Article/details/gtypvetcyc.html

[U95] JS：Promise 包装
来源：http://dali.gotoacloud.top/Article/details/gttpvgvwek.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gttnxjudjm.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gtbguyqmeo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtumnwijzv.html

[U97] JS：并发请求
来源：http://dali.wangshuangyany.cn/Article/details/gtgubozjpk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtshozmqeq.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gtpktuowhp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.meibo888.top/Article/details/gtmuhwhmaz.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gtlrxzoomi.html

el.addEventListener("click", e => {})
来源：http://dali.shzxlz.cn/Article/details/gtmkpytxcu.html

[U100] JS：DOM 查询
来源：http://dali.nwbrower.top/Article/details/gtjsrgvlyb.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gtpwmsiyuj.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gtarjloqyv.html

el.classList.toggle("active")
来源：http://dali.svipenyu.cn/Article/details/gttgnqyfbx.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gtigzckakp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtyvhgugzl.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gtrmkjpcqr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gtkpoqqbpd.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtelwydeqa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gttxjgbjlt.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gtfvhhjzru.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtbuyvxawy.html

[U106] JS：日期格式化
来源：http://dali.316326.xyz/Article/details/gtfopliqvk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gthjqhujpu.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gtwbetqcbc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtckyrpoeh.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gtybdklgha.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gtjvcnxjjc.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gtumufzvww.html

Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtgdwyspbe.html

[U110] JS：数组分块
来源：http://dali.yangfankeji.com/Article/details/gtaxomugzg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tian-w.cn/Article/details/gtloaujrst.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gtlxqnzdja.html

new Map(Object.entries(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtjgirvbst.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gtyyynabtl.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtyjkouovz.html

[U113] JS：正则替换全部
来源：http://dali.snrcjt.cn/Article/details/gtjgbdensf.html

s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtxhbwfnjg.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258888.top/Article/details/gtgqmbbsmq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtdtrmnelz.html

[U115] JS：生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtvsqaxizv.html

crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznvrshbe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gtfgbiymgf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gtjsbcpida.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtibjvwaov.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gtafkqalcl.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gtelhobqrg.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gtrhnvuzqk.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gtzucehyzx.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gtfdetxkvk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gtmwmmccyb.html

import.meta.env.VITE_API_URL
来源：http://dali.aizwys.cn/Article/details/gtoeigioum.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthwupqmxg.html

统计汇总
来源：http://dali.yj20258888.top/Article/details/gtudayjrql.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpwkomrmn.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtnuvztwzv.html

Python ......... 252
来源：http://dali.9152youxi.cn/Article/details/gtjrvweeyo.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtkckccaqg.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gtodqjntgi.html

TypeScript ..... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtykmzcpum.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtotaeitpx.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtftogpmow.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gthknlygdh.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gtyqyikqfr.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gtsyugdare.html

C++ ............ 30
来源：http://dali.andypj.xyz/Article/details/gtiemtyyaj.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtggnmzvvs.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gtlwellbrz.html

Kotlin ......... 15
来源：http://dali.jinqigufen.top/Article/details/gtsmusefaq.html

Swift .......... 15
来源：http://dali.yueranfly.top/Article/details/gtsbbfmrcy.html

Lua ............ 10
来源：http://dali.xylfe.cn/Article/details/gtobkbmlgh.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gtzjrbjika.html

Scala .......... 10
来源：http://dali.kuanghao11.cn/Article/details/gtxknfolfh.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtogddsyvp.html

合计 ........... 2106 条
来源：http://dali.jinqigfzy.top/Article/details/gtjbfyypwo.html

按章节统计：
来源：http://dali.yvedp.cn/Article/details/gtngbqfaff.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtbpmeiyxk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gttnsedzrr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjmkgbfb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtwqdsowbi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhongyouzk.top/Article/details/gtjucaphpv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtzpuksdol.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtlioozaeq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtmzslmgxr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtnzpzpfan.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtvxhaenin.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtpqdcarwj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtsvctzusv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtdqnsrshh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvgowipt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.mhx1999.top/Article/details/gtvruqkfma.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtzxnhciye.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gtvxxckrnl.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gttpyqtuld.html

S C / C++ 专题                          60
来源：http://dali.gotoacloud.top/Article/details/gtrxelzpgj.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gtjjawahoy.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gtavkndbjj.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtijbpncjz.html

合计                                  2106 条
来源：http://dali.aibaodan.cn/Article/details/gtvgofyhxx.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtuzvfbklp.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gtojetpymr.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtqpfydlzo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hysaishi.cn/Article/details/gtxsbwtogf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gtlngyzcvg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cqqwz.cn/Article/details/gtsxzrkger.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gtbltrcxbz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.meibo888.top/Article/details/gtqwgglykz.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gtxrpcumlg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmoiuryar.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.haohaochexian.top/Article/details/gtlanydmes.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gtcqfaijkg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtulggpinn.html

【收录内容】
来源：http://dali.hongshengwenyu.top/Article/details/gtztcrhioh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jyoumei.cn/Article/details/gtcnajvrvd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aizwys.cn/Article/details/gtptuxgpbo.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gtankxbudb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gotoacloud.top/Article/details/gtaqbgtuoz.html

【使用说明】
来源：http://dali.hfpthk.cn/Article/details/gtbsqnylez.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.wangdashe.top/Article/details/gtvqvqzjwg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cdnleiting.top/Article/details/gtrkxychld.html


<!-- 参考信息 -->