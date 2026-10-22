代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqyahrii.html

deque(maxlen=10)
来源：http://dali.sxryk.cn/Article/details/gt2wektwunc.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxotnmtd.html

defaultdict(list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhsiychy.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gt2qnapomkr.html

t = time.perf_counter()
来源：http://dali.cashguo.top/Article/details/gt2hzxvxygs.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gt2azhtfyyy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gt2vrnthmax.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gt2jxkuhupd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btgtiqxr.html

[U18] Py：预编译正则
来源：http://dali.tianlin.xyz/Article/details/gt2oujlbmwd.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2pvezzttb.html

[U19] Py：正则替换带回调
来源：http://dali.ybcxt.top/Article/details/gt2plkyhdbw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gt2rszzallr.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gt2hnrjlvqs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gt2nxaaytdb.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gt2ddycorqq.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gt2zsurukjh.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gt2ifgzpcmv.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gt2rjyooloi.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gt2xsvntccf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gt2tauevxwi.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gt2bonkmluw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2daytgonq.html

[U25] Py：CSV 按字典读
来源：http://dali.gzhubu.top/Article/details/gt2cjmhwhzd.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gt2dwjktncy.html

[U26] Py：并发下载
来源：http://dali.havefunace.top/Article/details/gt2yqgtibau.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gt2rfdbxdqt.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gt2bfgxsjeg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yiwzengj.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gt2gtobgywl.html

UserId = int
来源：http://dali.hnqzz.top/Article/details/gt2xwangqvi.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gt2uhxifmkj.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gt2lgaxspeo.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gt2fsepgxii.html

@dataclass(slots=True)
来源：http://dali.yonumen.top/Article/details/gt2paymjeup.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gt2mlqorldx.html

python -m pytest -q
来源：http://dali.xuanzx.com/Article/details/gt2mvdnritz.html

[U32] Py：代码格式化
来源：http://dali.gotoacloud.top/Article/details/gt2zttwubxj.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gt2itrktxgg.html

[U33] Py：打包发布
来源：http://dali.quarkkingdee.top/Article/details/gt2uaukfffn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gt2smrvugpr.html

[U34] Py：判断编码
来源：http://dali.dianchejie.cn/Article/details/gt2yqshpdsj.html

chardet.detect(raw)
来源：http://dali.zhengqikj.top/Article/details/gt2vjiboreg.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gt2nyduzdkn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gt2gldlqfth.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2eexthunj.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gt2kioyoagk.html

[U37] Py：读写 Excel
来源：http://dali.yj202588.top/Article/details/gt2qgbrvagg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gt2ftzfaghc.html

[U38] Py：获取脚本所在目录
来源：http://dali.svipenyu.cn/Article/details/gt2memixpbk.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gt2hveybfyr.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gt2zpnfwhca.html

sys.stdout.isatty()
来源：http://dali.mhx1999.top/Article/details/gt2ugyxlzos.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gt2oktrhaht.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2iincnxba.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yorbhpoz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpuiklff.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gt2plbvhnxi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gt2qfrjuhlx.html

[U43] PHP：声明命名空间
来源：http://dali.chenzaomai.com/Article/details/gt2yvlqkxrz.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxhgoajw.html

[U44] PHP：开启严格类型
来源：http://dali.c1oappe.top/Article/details/gt2nswwnipn.html

declare(strict_types=1);
来源：http://dali.tanke756.top/Article/details/gt2rdyuqfpy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xinyue.icu/Article/details/gt2upvduyxf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2uyjduetm.html

[U46] PHP：可空类型
来源：http://dali.yangfankeji.com/Article/details/gt2rihpgess.html

?string $name = null
来源：http://dali.kuanghao11.cn/Article/details/gt2cbnwxqmf.html

[U47] PHP：联合类型
来源：http://dali.dashuyun.cn/Article/details/gt2vzkddora.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gt2bqfqnbhx.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gt2bpiaoqvf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gt2naxzysts.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gt2pklegrrq.html

public readonly string $name
来源：http://dali.vqdsnc.cn/Article/details/gt2unlnifrq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yclmhmxv.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gt2fjipdaff.html

[U51] PHP：数组解构
来源：http://dali.yanxiufei.cn/Article/details/gt2nqwckptp.html

[$a, $b] = $arr;
来源：http://dali.tianlin.xyz/Article/details/gt2avdluppv.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gt2ixxgcwzi.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gt2xuiydcvf.html

[U53] PHP：空合并运算符
来源：http://dali.gotoacloud.top/Article/details/gt2tcwubkjt.html

$v = $a ?? $b ?? "default";
来源：http://dali.feifeiyinyue.top/Article/details/gt2pehrhcbn.html

[U54] PHP：空安全调用
来源：http://dali.aibaodan.cn/Article/details/gt2lcvrqvfe.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtgbhctb.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gt2aepmhoys.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gzhubu.top/Article/details/gt2emqnhsai.html

[U56] PHP：命名参数
来源：http://dali.guannengcc.top/Article/details/gt2drhshmdi.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2abwzijok.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gt2dzxurjff.html

"值: {$a}"
来源：http://dali.sweek.top/Article/details/gt2oktyogbo.html

[U58] PHP：数组三件套
来源：http://dali.cqqwz.cn/Article/details/gt2hkwogfko.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2hcdndmuy.html

[U59] PHP：自定义排序
来源：http://dali.jiagoushi.top/Article/details/gt2vfompjfw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2denitezg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gt2geewnasm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cdnleiting.top/Article/details/gt2cnwambuo.html

[U61] PHP：正则
来源：http://dali.pycfn.com/Article/details/gt2lhvlqbfs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gt2dhhsrvtf.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gt2mfqqsurp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.birdmap.top/Article/details/gt2irdqnamj.html

[U63] PHP：文件读写
来源：http://dali.meibo888.top/Article/details/gt2vdlxtlaa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gt2sxckpwlv.html

[U64] PHP：目录遍历
来源：http://dali.aizwys.cn/Article/details/gt2gammstnv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ybcxt.top/Article/details/gt2adrplihj.html

[U65] PHP：会话
来源：http://dali.yongpay.top/Article/details/gt2gpwiyoqg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2nshwhkan.html

[U66] PHP：设置 Cookie
来源：http://dali.vqdsnc.cn/Article/details/gt2vlgwiqcr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gt2ouhltccf.html

[U67] PHP：处理文件上传
来源：http://dali.yuxming.cn/Article/details/gt2lcsrbvii.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gt2hrnzcfbj.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxiwmjfx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhixingplan.top/Article/details/gt2qvehlgfj.html

[U69] PHP：PDO 预处理
来源：http://dali.hysaishi.cn/Article/details/gt2lwvxlclw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrsfadbj.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gt2fmlvmvgk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tian-w.cn/Article/details/gt2hhieicad.html

[U71] PHP：抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijuyftmv.html

throw new RuntimeException("失败", 500);
来源：http://dali.jlsjyb.cn/Article/details/gt2efetbnxx.html

[U72] PHP：写错误日志
来源：http://dali.fengsongda.top/Article/details/gt2gdzutpof.html

error_log("失败: " . $e->getMessage());
来源：http://dali.andypj.xyz/Article/details/gt2bhccsjec.html

[U73] PHP：读取 ini 配置
来源：http://dali.yueranfly.top/Article/details/gt2omoxakek.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gt2juhoehbd.html

[U74] PHP：读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvypunna.html

getenv("APP_ENV") ?: "production"
来源：http://dali.havefunace.top/Article/details/gt2xgxyeucs.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gt2zznllnju.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gt2xwoaqhli.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gt2atravgwh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gt2opdedpzh.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gt2ebhkegad.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gt2iesqtqjz.html

[U78] PHP：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gt2savtuhpv.html

composer require --dev phpunit/phpunit
来源：http://dali.hfpthk.cn/Article/details/gt2rcxbmmjs.html

[U79] PHP：静态分析
来源：http://dali.wangdashe.top/Article/details/gt2dzkfcbbi.html

composer require --dev phpstan/phpstan
来源：http://dali.0kj1m.cn/Article/details/gt2rdxieean.html

[U80] PHP：代码规范修复
来源：http://dali.yueranfly.top/Article/details/gt2xtelsrug.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guannengcc.top/Article/details/gt2nxhsmvzc.html

[U81] JS：初始化项目
来源：http://dali.meibo888.top/Article/details/gt2edxgvzqe.html

npm init -y;  npm i express
来源：http://dali.zhongyouzk.top/Article/details/gt2toyrdqwf.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gt2bgcglorw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gt2eojqsajc.html

[U83] JS：ES Module 导入导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnrzphnh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2xqvbljfr.html

[U84] JS：CommonJS 写法
来源：http://dali.aibaodan.cn/Article/details/gt2luxssklt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gt2yjywzvol.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gt2uiaeckkj.html

a?.b?.c
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxfoqefc.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gt2ggdwrmib.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gt2mukaneny.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwujbpgr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cycxjevy.html

[U88] JS：对象展开合并
来源：http://dali.jianghu66.top/Article/details/gt2euyidsuz.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gt2lhdeuwcm.html

[U89] JS：数组去重
来源：http://dali.sufxvd.cn/Article/details/gt2uhmdjzaw.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2grlyzfyh.html

[U90] JS：数字数组排序
来源：http://dali.gogol.net.cn/Article/details/gt2vdhtsdcz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcudkrwp.html

[U91] JS：对象键值遍历
来源：http://dali.wangdashe.top/Article/details/gt2hcbshlre.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daxiang520.top/Article/details/gt2npkumhto.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gt2ztiqlqvt.html

structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2tsnwpdoa.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2grldxvto.html

`共 ${n} 条`
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfuaixic.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gt2dcanlatd.html

const double = x => x * 2;
来源：http://dali.sweek.top/Article/details/gt2lwuuanks.html

[U95] JS：Promise 包装
来源：http://dali.quarkkingdee.top/Article/details/gt2eefaykom.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gt2jdqfdaef.html

[U96] JS：async/await 与异常
来源：http://dali.yuxming.cn/Article/details/gt2dzzedpzg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2kveucfdh.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbpwoovw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2dylhamgy.html

[U98] JS：fetch 带 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2uluwmvps.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuanzhike.top/Article/details/gt2pujgcrkl.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gt2pwcihwnj.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gt2hspthuqk.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gt2zsfrkpqg.html

document.querySelector(".item")
来源：http://dali.gzhubu.top/Article/details/gt2xcewdozm.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gt2eoyoeupg.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gt2ywjfmwcc.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gt2unsgihfx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gt2lchotgzc.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gt2hynefnwi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjkffiwl.html

[U104] JS：防抖
来源：http://dali.havefunace.top/Article/details/gt2jivqjjjx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2dnncndke.html

[U105] JS：节流
来源：http://dali.yueranfly.top/Article/details/gt2ysuzgnmi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gt2umvurifc.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gt2hdyvmrya.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gt2oppvevqm.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2fwhezfft.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gt2wxzczvks.html

[U108] JS：随机整数
来源：http://dali.ppjwa.cn/Article/details/gt2iazrlcpz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhoulong.xyz/Article/details/gt2xlkjfpvr.html

[U109] JS：数组分组
来源：http://dali.yangfankeji.com/Article/details/gt2tjvjbyok.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2zvvirhgs.html

[U110] JS：数组分块
来源：http://dali.guowangkeji.top/Article/details/gt2iaqpftqe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gt2eliiugqu.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gt2faorzmuu.html

new Map(Object.entries(obj))
来源：http://dali.smart0.xyz/Article/details/gt2pbmhxwtx.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gt2mywkdptz.html

"7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2fbplwrqb.html

[U113] JS：正则替换全部
来源：http://dali.gaohongyu789.top/Article/details/gt2zpryfjml.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2rydsxzyt.html

[U114] JS：JSON 深比较
来源：http://dali.316326.xyz/Article/details/gt2bzpfsuqj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2bnvscjcy.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2atpuhdsb.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbuvrhyh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pengpengdd.cyou/Article/details/gt2iladvcca.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gt2bvooeibg.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gt2gdfpczgd.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gt2rqocnjon.html

[U118] JS：开发服务器
来源：http://dali.jqgfzy.top/Article/details/gt2btzdnvfr.html

npm i -D vite;  npx vite
来源：http://dali.hywenlv.cn/Article/details/gt2esxqhpkn.html

[U119] JS：生产构建
来源：http://dali.nanxinkj.top/Article/details/gt2jbfgxbhy.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gt2tyrmbumd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gt2dypknqec.html

import.meta.env.VITE_API_URL
来源：http://dali.aibaodan.cn/Article/details/gt2pufzcqyy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2tfjwvorc.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gt2sceaaxst.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2sprrqtsh.html

按语言统计（条）：
来源：http://dali.wangdashe.top/Article/details/gt2hnxfdzdw.html

Python ......... 252
来源：http://dali.cdnleiting.top/Article/details/gt2oobkdogz.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gt2yrrpakuz.html

JavaScript ..... 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbxyvmax.html

TypeScript ..... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2thhbhytu.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2oszsyjji.html

Go ............. 212
来源：http://dali.zhixingplan.top/Article/details/gt2svjmawvu.html

Ruby ........... 212
来源：http://dali.fengsongda.top/Article/details/gt2cqpxtwoi.html

C# ............. 212
来源：http://dali.xuanzx.com/Article/details/gt2fatskcej.html

C .............. 30
来源：http://dali.birdmap.top/Article/details/gt2zxszmtih.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdfiuepj.html

SQL ............ 90
来源：http://dali.yj202588.top/Article/details/gt2fzlrxedr.html

Bash ........... 80
来源：http://dali.yj20258.top/Article/details/gt2tknmveue.html

Kotlin ......... 15
来源：http://dali.jlsjyb.cn/Article/details/gt2ukwykkae.html

Swift .......... 15
来源：http://dali.zycfv.cn/Article/details/gt2blwfyhrg.html

Lua ............ 10
来源：http://dali.jyoumei.cn/Article/details/gt2mlessrda.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2chqjtrug.html

Scala .......... 10
来源：http://dali.hnqzz.top/Article/details/gt2uhjmwgse.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2mdqoiytl.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gt2apckgqjb.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xybvxdwl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gt2swooezle.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gt2qhsnjxkr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjmftgjg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gt2pnpnwper.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxejdpty.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivogizkl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2svxasacu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gt2oakitmwp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2fnsvtivh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gt2euaduyui.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2mhpghloc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2hofimncz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjpsqirw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gt2lbypbpol.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenlongwang.top/Article/details/gt2zzxgpxra.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2tkdikxka.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gt2lnkqiybb.html

R Bash 专题                             80
来源：http://dali.dianchejie.cn/Article/details/gt2dgdfgmcn.html

S C / C++ 专题                          60
来源：http://dali.jqgfzy.top/Article/details/gt2jzveoelw.html

T 其他语言补充                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2tyhdimmu.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gt2qiejlzpc.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2njsdafvu.html

合计                                  2106 条
来源：http://dali.nwbrower.top/Article/details/gt2zcibdyqz.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2xiqpnrkj.html

使用提醒
来源：http://dali.cucudq.cn/Article/details/gt2qrurzpbk.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2twtfauuh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gt2pyfbstvp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gt2nbubvqmx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjjobvjc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hammf.cn/Article/details/gt2ufzcudxv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gt2ljxomquo.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gt2knydwbhy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2eqzuxigl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gotoacloud.top/Article/details/gt2mxxuelqc.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gt2kvywnzfd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2htyexcpn.html

【收录内容】
来源：http://dali.haohaochexian.top/Article/details/gt2qitmhzlr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgufenzy.top/Article/details/gt2iwmjxvwc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gt2zdnukmon.html

SQL · Bash · C · C++
来源：http://dali.cashguo.top/Article/details/gt2humtnsfx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenzaomai.com/Article/details/gt2tefwvocw.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gt2yozfuxpu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gt2gmnxwznc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuxming.cn/Article/details/gt2dhqlvzsd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gt2aylrcyjd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.c1oappe.top/Article/details/gt2xjuuxlly.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tian-w.cn/Article/details/gt2zbvqfjtm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fzhhl.top/Article/details/gt2pvjfsrab.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tian-w.cn/Article/details/gt2mlbelali.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258888.top/Article/details/gt2halaizgv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yangfankeji.com/Article/details/gt2rbafdmsx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekispeyt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.birdmap.top/Article/details/gt2wmmmrtig.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tianlin.xyz/Article/details/gt2utijhqcd.html

【文件统计】
来源：http://dali.jqgfzy.top/Article/details/gt2fjcxrzxw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cdnleiting.top/Article/details/gt2qtfywcot.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2jujpslmx.html

目  录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekssqzys.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkvidxvf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gt2ifckuhua.html


<!-- 参考信息 -->