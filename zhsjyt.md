代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjtvymee.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gt2vqqemlpx.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfzlyqji.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gt2uodgnhbq.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcqzmrdt.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gt2ncgsjuom.html

[U16] Py：命令行参数解析
来源：http://dali.sweek.top/Article/details/gt2arbrtghq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqrtvsha.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gt2jmhuhymu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gt2dmfuyiwv.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gt2xgkhdemy.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfjfqsba.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrblumaq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gt2kbayryav.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gt2dhyoaasx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsxucax.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gt2twqacriv.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gt2ferewmpw.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gt2oykuhnbt.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gt2etyzjxrp.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gt2squzysjq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gt2phblnzry.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gt2jnztmqgn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2dphscogf.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gt2aoukilub.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gt2ozqrjfxf.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gt2ieyancgb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhengqikj.top/Article/details/gt2awczvhdz.html

[U27] Py：异步 HTTP
来源：http://dali.aibaodan.cn/Article/details/gt2kzhwopew.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gt2eesljmeh.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gt2sdaobxdv.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gt2flykhngt.html

[U29] Py：属性校验
来源：http://dali.jianghu66.top/Article/details/gt2cfmwhpov.html

@property 与 @x.setter 配合
来源：http://dali.bjfxy.top/Article/details/gt2vslzhege.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gt2sxhyyxbn.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gt2jflemdbk.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gt2knlkoqog.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gt2lczjknvh.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2fkwlspwc.html

ruff format . && ruff check --fix .
来源：http://dali.cucudq.cn/Article/details/gt2gezvrnwu.html

[U33] Py：打包发布
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbfvlobl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gt2jguzonxl.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gt2hgdzqyqx.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gt2hbphadmq.html

[U35] Py：发送邮件
来源：http://dali.daria6918.cn/Article/details/gt2stgtviao.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jiagoushi.top/Article/details/gt2rcljfbik.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gt2nfafzebx.html

schedule.every(10).minutes.do(job)
来源：http://dali.316326.xyz/Article/details/gt2ekttqenm.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gt2sneofxvw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siqqfpys.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2triairrf.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gt2nzkkvdcm.html

[U39] Py：判断是否在交互环境
来源：http://dali.snrcjt.cn/Article/details/gt2lpgosuru.html

sys.stdout.isatty()
来源：http://dali.fengsongda.top/Article/details/gt2gxelaici.html

[U40] Py：打印到标准错误
来源：http://dali.dianchejie.cn/Article/details/gt2dshztzyn.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2fbaqmnak.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gt2dsbbrxoe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkdsfltj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gt2rdudtlpm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cheryme.top/Article/details/gt2ekinnzpm.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gt2ayvotvia.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gt2keigdvio.html

[U44] PHP：开启严格类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpukpiyp.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gt2xvznomnw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gt2eoakkdtx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2wxbwcqkk.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gt2fqxoixxl.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkqnawtt.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gt2gfqmxxuz.html

int|string $id
来源：http://dali.ydzc1.top/Article/details/gt2wcyijdxv.html

[U48] PHP：纯枚举
来源：http://dali.haohaochexian.top/Article/details/gt2dcpwwhcj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gt2zkvksrol.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gt2rhqetbwm.html

public readonly string $name
来源：http://dali.hammf.cn/Article/details/gt2zejbxhgx.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gt2qforsmdl.html

public function __construct(private int $id) {}
来源：http://dali.yj20258888.top/Article/details/gt2xrdjyebi.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gt2xuehxjvj.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gt2zxryirat.html

[U52] PHP：箭头函数
来源：http://dali.aizwys.cn/Article/details/gt2coarzjqb.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gt2zjwncdnn.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gt2iwuuyaea.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigufen.top/Article/details/gt2gzhlqleb.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gt2mvnwjlkt.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gt2fcijnlzy.html

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2etpxbhtw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xinyue.icu/Article/details/gt2gtegcfnz.html

[U56] PHP：命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2cxoqhsnb.html

f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2fuzotcbc.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2neivvugg.html

"值: {$a}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2encortzh.html

[U58] PHP：数组三件套
来源：http://dali.hnqzz.top/Article/details/gt2yskpxkmy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.mhx1999.top/Article/details/gt2bxglibci.html

[U59] PHP：自定义排序
来源：http://dali.aizwys.cn/Article/details/gt2mvtcqwac.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2koucydtd.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gt2vlliwrtw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2worqnbnj.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gt2jfhxbtyc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gt2qpoerfzj.html

[U62] PHP：日期对象
来源：http://dali.hywenlv.cn/Article/details/gt2krhqvwxo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258888.top/Article/details/gt2yaulcemx.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gt2ofeiduju.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gt2yxgmfplk.html

[U64] PHP：目录遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2nybajvkw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cucudq.cn/Article/details/gt2gzrvnesd.html

[U65] PHP：会话
来源：http://dali.ybcxt.top/Article/details/gt2okrdkcct.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2flgnbwpr.html

[U66] PHP：设置 Cookie
来源：http://dali.yvedp.cn/Article/details/gt2imcsuonw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fengsongda.top/Article/details/gt2iwbibfch.html

[U67] PHP：处理文件上传
来源：http://dali.iojbl.cn/Article/details/gt2mkwlmean.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shzxlz.cn/Article/details/gt2xssigfmx.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikswibux.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gt2lbezdvaq.html

[U69] PHP：PDO 预处理
来源：http://dali.hnxiangtu.top/Article/details/gt2acikxvor.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.andypj.xyz/Article/details/gt2ixijspxm.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuvsiaxl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gotoacloud.top/Article/details/gt2xvolsjyn.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gt2iqhdgfvw.html

throw new RuntimeException("失败", 500);
来源：http://dali.jiagoushi.top/Article/details/gt2ffuaduax.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gt2yqddadng.html

error_log("失败: " . $e->getMessage());
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctznaias.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258.top/Article/details/gt2kpthhdea.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gt2fkdunjma.html

[U74] PHP：读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezecvhxf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gt2riskfekx.html

[U75] PHP：依赖注入
来源：http://dali.redwolf501.top/Article/details/gt2qvqhhahk.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gt2jobserdx.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gt2thfshmkh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.vqdsnc.cn/Article/details/gt2qmxrclsp.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gt2zstciani.html

composer require twig/twig
来源：http://dali.yonumen.top/Article/details/gt2llaobihs.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gt2extmvcwu.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gt2wmzdelmz.html

[U79] PHP：静态分析
来源：http://dali.gaohongyu789.top/Article/details/gt2igvuxomh.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxuanxn.top/Article/details/gt2polxtwus.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gt2btzbbtvy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cdnleiting.top/Article/details/gt2zdqrtnnq.html

[U81] JS：初始化项目
来源：http://dali.fengsongda.top/Article/details/gt2epzwfoho.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gt2mnjbgxgw.html

[U82] JS：package.json 脚本
来源：http://dali.tanke756.top/Article/details/gt2crxaiiqq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gt2hgypdvev.html

[U83] JS：ES Module 导入导出
来源：http://dali.cashguo.top/Article/details/gt2gtcfosia.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2qkmihxih.html

[U84] JS：CommonJS 写法
来源：http://dali.smart0.xyz/Article/details/gt2wjnqchra.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daxiang520.top/Article/details/gt2abmgdquz.html

[U85] JS：可选链
来源：http://dali.sxryk.cn/Article/details/gt2tnnfepoy.html

a?.b?.c
来源：http://dali.zhoulong.xyz/Article/details/gt2nytwlqdu.html

[U86] JS：空值合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2tneswfbd.html

a ?? b
来源：http://dali.jlsjyb.cn/Article/details/gt2ljdjyduu.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gt2rfziates.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cdnleiting.top/Article/details/gt2tfwxktui.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gt2ivysvkyd.html

{ ...a, ...b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2poqefhsx.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gt2emoljqbn.html

[...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2sltbwmpq.html

[U90] JS：数字数组排序
来源：http://dali.zdqjudy.top/Article/details/gt2xjynpnkg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2mmpulxel.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258.top/Article/details/gt2isoscrkp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tian-w.cn/Article/details/gt2juugbdgh.html

[U92] JS：深拷贝
来源：http://dali.daxiang520.top/Article/details/gt2coupawyb.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2glqrjdxi.html

[U93] JS：模板字符串
来源：http://dali.zycfv.cn/Article/details/gt2qdxuvrad.html

`共 ${n} 条`
来源：http://dali.tianlin.xyz/Article/details/gt2bhyvckoz.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2nwalpljq.html

const double = x => x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2zijfjjfy.html

[U95] JS：Promise 包装
来源：http://dali.zhoulong.xyz/Article/details/gt2vnprthbb.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxinkj.top/Article/details/gt2sabuplgp.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gt2xaisddya.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2yvsobxph.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhnwblej.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2tvzaamcr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2xffyfogd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sxryk.cn/Article/details/gt2keendlnc.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gt2gnuzrdfi.html

el.addEventListener("click", e => {})
来源：http://dali.shuidangran.top/Article/details/gt2bievlsve.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gt2ixonnohk.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gt2xjjqoqpa.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gt2pdrfuwph.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gt2dafosxtq.html

[U102] JS：本地存储
来源：http://dali.gogol.net.cn/Article/details/gt2hsfjwxoc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gt2xuwxmfrm.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gt2csdvacup.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gt2tjaeqxmy.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvrrrwuh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2rzrswmnx.html

[U105] JS：节流
来源：http://dali.cucudq.cn/Article/details/gt2mcsznbtl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aizwys.cn/Article/details/gt2gsuaqdjy.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2wbrsbrzu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gt2zvxynnup.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gt2jxjynnsp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2ryxolkhl.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gt2mwrejpua.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gt2pujdxqud.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gt2ezbrqzfg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2pfgmtdpc.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dyooeaya.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jiagoushi.top/Article/details/gt2kowxmkrs.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gt2xwotqtvm.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gt2djmcldbq.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzitpubf.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2lnbutwps.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gt2iumfbvsz.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2ebispzsl.html

[U114] JS：JSON 深比较
来源：http://dali.nanxuanxn.top/Article/details/gt2jrnwjtwg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2ubgcvpzt.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2tllfdeyp.html

crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihwrjqxi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aizwys.cn/Article/details/gt2ixowgvur.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shuidangran.top/Article/details/gt2udpqxaua.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gt2rdtcrjhe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vefkwuuo.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gt2awjqqqxi.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gt2uvuehosz.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gt2ocnfrrdu.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gt2qkspijjd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifkomazi.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gt2fsoqdboq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ymlrdhji.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gt2ubfkztjz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nsklfrux.html

按语言统计（条）：
来源：http://dali.wangdashe.top/Article/details/gt2ogefzsnc.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gt2nmucdvta.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gt2jyyjtngr.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gt2ndbyxqyn.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gt2ivlkhchx.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2packxrrz.html

Go ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gt2ephgyubh.html

Ruby ........... 212
来源：http://dali.pycfn.com/Article/details/gt2cmwugjcj.html

C# ............. 212
来源：http://dali.havefunace.top/Article/details/gt2mypdjzwt.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gt2rkzeqfjn.html

C++ ............ 30
来源：http://dali.jinqigfzy.top/Article/details/gt2rshlusly.html

SQL ............ 90
来源：http://dali.havefunace.top/Article/details/gt2wxqfgnvt.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gt2xgwkqvvn.html

Kotlin ......... 15
来源：http://dali.snrcjt.cn/Article/details/gt2tfccvpmq.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gt2xduzctbq.html

Lua ............ 10
来源：http://dali.fengsongda.top/Article/details/gt2dbrwuncj.html

Perl ........... 10
来源：http://dali.xinyue.icu/Article/details/gt2ppteytwu.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gt2bmgzwyci.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2jctugrtq.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbtjiehu.html

按章节统计：
来源：http://dali.xziqi.cn/Article/details/gt2fghiqbgp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gt2xuhmhvvw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2xgnqyluy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2gopacpkt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2puvhmgqc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gt2kicayqrp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gt2dpiufjla.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gt2atirmcdy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gt2hxxlgxdy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2sdbpttlt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2birvwbhc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2hwpurjck.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2yugmjrrc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2gzvbcckz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gt2bfwdaezu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.meibo888.top/Article/details/gt2jtujrxcj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2fscfcwsr.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gt2zjpneixi.html

R Bash 专题                             80
来源：http://dali.mhx1999.top/Article/details/gt2tvpefkbd.html

S C / C++ 专题                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsiisiku.html

T 其他语言补充                          60
来源：http://dali.ehwqpu.com/Article/details/gt2awdmqhon.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gt2qppctwpj.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2zhmpmush.html

合计                                  2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqhnkjxy.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqwpsquz.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gt2nsbmxavj.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2gclgljzr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gt2ieptaitu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gt2whbjfitg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zycfv.cn/Article/details/gt2fsayryqy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yueranfly.top/Article/details/gt2hugytzvv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pycfn.com/Article/details/gt2qniqhdcu.html

—— 文件结束 ——
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwtdobbz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epjhscdo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.vqdsnc.cn/Article/details/gt2vlvwkcnu.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gt2pktqxwwb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2dtbpuklt.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gt2mgqmmkwc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xinyue.icu/Article/details/gt2jhyolbwq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cdnleiting.top/Article/details/gt2pcirytvt.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gt2lagzwurh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dashuyun.cn/Article/details/gt2tiirchxa.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gt2zvtcctqr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhengqikj.top/Article/details/gt2bpbqycrz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tianlin.xyz/Article/details/gt2zktjyhoo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gt2oaksioqj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jianghu66.top/Article/details/gt2phzhqmzk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gt2xflemxbp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.feifeiyinyue.top/Article/details/gt2fiexxoof.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yueranfly.top/Article/details/gt2isjbprab.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hywenlv.cn/Article/details/gt2acrlpqkn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xziqi.cn/Article/details/gt2cggqqcrt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yonumen.top/Article/details/gt2tsdgctlg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcyzrjer.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgufenzy.top/Article/details/gt2wckssnck.html

【文件统计】
来源：http://dali.bjfxy.top/Article/details/gt2irnnlkaa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jlsjyb.cn/Article/details/gt2pqmzyezz.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2zjynkgfs.html

目  录
来源：http://dali.dashuyun.cn/Article/details/gt2qhhwvjjw.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2rhhlqnbg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gt2txigerdl.html


<!-- 参考信息 -->