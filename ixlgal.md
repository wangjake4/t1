代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjouufmh.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gt2yemsopyl.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gt2kvarcown.html

defaultdict(list)
来源：http://dali.hfpthk.cn/Article/details/gt2pvthcmla.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gt2fkuxivhr.html

t = time.perf_counter()
来源：http://dali.fengsongda.top/Article/details/gt2icwiwqug.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gt2tamkktof.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gt2kwfkqqco.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gt2zdehblmu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gt2ppdbqbmd.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gt2puzaebku.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2zlpwvzea.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gt2uqbuwuel.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mcwzknww.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gt2iufrjiwe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnqzz.top/Article/details/gt2mnqmtqym.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gt2nyxxvrgi.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gt2mcsvejbb.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gt2gxjyaslk.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gt2hqxtdxbe.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gt2fvlvgcuw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2boiwbjhc.html

[U24] Py：路径操作
来源：http://dali.dianchejie.cn/Article/details/gt2feemyeun.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvjsmckj.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gt2nkfxxxuj.html

csv.DictReader(f)
来源：http://dali.hammf.cn/Article/details/gt2nwfohpru.html

[U26] Py：并发下载
来源：http://dali.xuanzx.com/Article/details/gt2rixzfgde.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gt2yalivqtz.html

[U27] Py：异步 HTTP
来源：http://dali.hongshengwenyu.top/Article/details/gt2auettaqs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fzhhl.top/Article/details/gt2fompremj.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gt2adiyeopb.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gt2oeipojfm.html

[U29] Py：属性校验
来源：http://dali.guannengcc.top/Article/details/gt2tkhcbqmb.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gt2opibysjq.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gt2eunjlvxi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2neasubny.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gt2xbaatqre.html

python -m pytest -q
来源：http://dali.chenlongwang.top/Article/details/gt2rfkjsadl.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gt2cqurgvlx.html

ruff format . && ruff check --fix .
来源：http://dali.sweek.top/Article/details/gt2umvdjzky.html

[U33] Py：打包发布
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2degtmbvm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gt2fujeuakq.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntnvplfm.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhvbvecc.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gt2sgwhbgmv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.c1oappe.top/Article/details/gt2omoytnel.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2ijtqbzcc.html

schedule.every(10).minutes.do(job)
来源：http://dali.yongpay.top/Article/details/gt2qhmardea.html

[U37] Py：读写 Excel
来源：http://dali.jqgfzy.top/Article/details/gt2ptczapmg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigufen.top/Article/details/gt2qdjglpkn.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjpqvybv.html

Path(__file__).resolve().parent
来源：http://dali.snrcjt.cn/Article/details/gt2kazmwitf.html

[U39] Py：判断是否在交互环境
来源：http://dali.haohaochexian.top/Article/details/gt2laoqeyqh.html

sys.stdout.isatty()
来源：http://dali.wangdashe.top/Article/details/gt2unzsjnbv.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gt2sddnfhrv.html

print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gt2lgueiwrf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jyoumei.cn/Article/details/gt2elnzqena.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzmuqath.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gt2peijwpiy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhengqikj.top/Article/details/gt2mlnzwezf.html

[U43] PHP：声明命名空间
来源：http://dali.zdqjudy.top/Article/details/gt2fsqgpqql.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gt2cvfvodui.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gt2aqcheznc.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gt2hhheikpi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuxming.cn/Article/details/gt2jcwwxmbg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfhpnnuu.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gt2egvsiizd.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gt2nswqahsf.html

[U47] PHP：联合类型
来源：http://dali.jiagoushi.top/Article/details/gt2hjhaauge.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gt2mfuyyppy.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2huofthvs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gt2woefbydy.html

[U49] PHP：只读属性
来源：http://dali.yj202588.top/Article/details/gt2qpeftbzp.html

public readonly string $name
来源：http://dali.smart0.xyz/Article/details/gt2eglyqhqh.html

[U50] PHP：构造器属性提升
来源：http://dali.cdnleiting.top/Article/details/gt2wrwbhdro.html

public function __construct(private int $id) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xbheaasy.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gt2hjmlynfx.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gt2pxasxsiy.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gt2xkmmiimb.html

$double = fn($x) => $x * 2;
来源：http://dali.ybcxt.top/Article/details/gt2bcpattdd.html

[U53] PHP：空合并运算符
来源：http://dali.sysykeji.top/Article/details/gt2clezsatt.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gt2ycyszvrc.html

[U54] PHP：空安全调用
来源：http://dali.tian-w.cn/Article/details/gt2ixxrdwvi.html

$obj?->method()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbpukvtv.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gt2ukmlhyii.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sweek.top/Article/details/gt2tuozgjtq.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gt2mnqibsbw.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ucgdtmsj.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2oitalgke.html

"值: {$a}"
来源：http://dali.quarkkingdee.top/Article/details/gt2bowvpyxu.html

[U58] PHP：数组三件套
来源：http://dali.sysykeji.top/Article/details/gt2cymgdtwm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2xpgpzcuq.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gt2faubpogy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gt2hdavcwzf.html

[U60] PHP：JSON 编解码
来源：http://dali.tianlin.xyz/Article/details/gt2czbwpbnn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gt2klcaguhc.html

[U61] PHP：正则
来源：http://dali.fengsongda.top/Article/details/gt2igjcbwek.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gt2qwqfthkc.html

[U62] PHP：日期对象
来源：http://dali.yj20258888.top/Article/details/gt2nsucscop.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shuidangran.top/Article/details/gt2xgrqzwel.html

[U63] PHP：文件读写
来源：http://dali.gogol.net.cn/Article/details/gt2zqlyqweu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cheryme.top/Article/details/gt2mzrumbin.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2urvxaifh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gotoacloud.top/Article/details/gt2pmspnwif.html

[U65] PHP：会话
来源：http://dali.xuanzx.com/Article/details/gt2vgnsejeb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2sfctcuyb.html

[U66] PHP：设置 Cookie
来源：http://dali.tianlin.xyz/Article/details/gt2gpsblqgg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnqzz.top/Article/details/gt2ygnadflk.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gt2vruafoww.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.0kj1m.cn/Article/details/gt2deayytaz.html

[U68] PHP：PDO 连接
来源：http://dali.cashguo.top/Article/details/gt2fdeubunv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hfpthk.cn/Article/details/gt2jgwwblkh.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gt2woitblpt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.meibo888.top/Article/details/gt2skerpqui.html

[U70] PHP：PDO 事务
来源：http://dali.aibaodan.cn/Article/details/gt2qezotgwy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gt2rzzpmsbe.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gt2yaklhxuc.html

throw new RuntimeException("失败", 500);
来源：http://dali.smart0.xyz/Article/details/gt2bxmrqksy.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gt2zecuxxrb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pengpengdd.cyou/Article/details/gt2bopcrhbs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2xbswnnjy.html

parse_ini_file("config.ini", true)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctpgtnpj.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2ljsleaez.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gt2hmoiuajn.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gt2ywfduhti.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gt2awidwkyi.html

[U76] PHP：简单路由
来源：http://dali.cucudq.cn/Article/details/gt2rlirmyje.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hywenlv.cn/Article/details/gt2aepqkkhc.html

[U77] PHP：模板渲染
来源：http://dali.hammf.cn/Article/details/gt2ddppvrnb.html

composer require twig/twig
来源：http://dali.shuidangran.top/Article/details/gt2xgfrwrbs.html

[U78] PHP：单元测试
来源：http://dali.hysaishi.cn/Article/details/gt2txlbimnc.html

composer require --dev phpunit/phpunit
来源：http://dali.xinyue.icu/Article/details/gt2nolpvlwb.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evmesxyz.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gt2zunwmgas.html

[U80] PHP：代码规范修复
来源：http://dali.jianghu66.top/Article/details/gt2cgzihcvk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yueranfly.top/Article/details/gt2ilspgidn.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uihqvwoi.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gt2gqopchkc.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gt2fjtzceve.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shzxlz.cn/Article/details/gt2xvdnzgrz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvjnkvik.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gt2ptgvbjfv.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258888.top/Article/details/gt2lwejijsz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daxiang520.top/Article/details/gt2gouelanz.html

[U85] JS：可选链
来源：http://dali.hywenlv.cn/Article/details/gt2jzyseoxc.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gt2mnfbxpqh.html

[U86] JS：空值合并
来源：http://dali.yj202588.top/Article/details/gt2pybhlbwk.html

a ?? b
来源：http://dali.zdqjudy.top/Article/details/gt2irmyyytq.html

[U87] JS：解构默认值
来源：http://dali.hammf.cn/Article/details/gt2ysobjmkz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gt2rcqufuny.html

[U88] JS：对象展开合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcghdfqq.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gt2hzdqganb.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nslaemzw.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkycndzz.html

[U90] JS：数字数组排序
来源：http://dali.jinqigufen.top/Article/details/gt2luvqiijr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2cpamxdaz.html

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gt2bygzntps.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgfzy.top/Article/details/gt2qkphmriq.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2omnvkyma.html

structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2mndawkrv.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gt2zmnxrhxj.html

`共 ${n} 条`
来源：http://dali.andypj.xyz/Article/details/gt2omnyxbno.html

[U94] JS：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gt2hkwhzjzx.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gt2mduxhazz.html

[U95] JS：Promise 包装
来源：http://dali.daria6918.cn/Article/details/gt2kxccdkpp.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxuanxn.top/Article/details/gt2fftspkxp.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gt2nxuojqfd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2gjunsslv.html

[U97] JS：并发请求
来源：http://dali.c1oappe.top/Article/details/gt2msuhusse.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqnrymyd.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2gvsrvoxp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nwbrower.top/Article/details/gt2lkwxqzki.html

[U99] JS：事件监听
来源：http://dali.zdqjudy.top/Article/details/gt2kxzcetyd.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gt2lapevphk.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gt2kfggfivx.html

document.querySelector(".item")
来源：http://dali.guowangkeji.top/Article/details/gt2crfnhuqh.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2jwdhjrho.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gt2xicewkel.html

[U102] JS：本地存储
来源：http://dali.iojbl.cn/Article/details/gt2tnyhnvqm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jiagoushi.top/Article/details/gt2okhfwdcl.html

[U103] JS：定时器
来源：http://dali.fzhhl.top/Article/details/gt2madkdwbn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fzhhl.top/Article/details/gt2pcqmvvve.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gt2dfzcflqf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2mfdcvxle.html

[U105] JS：节流
来源：http://dali.redwolf501.top/Article/details/gt2lfdwfsyi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gt2zpbfipct.html

[U106] JS：日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2pkxqkjwu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gt2qhcjfaqu.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gt2ljvwsjku.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guannengcc.top/Article/details/gt2hgqrlbkb.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odjyzlpd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ivvv.top/Article/details/gt2qpxyepuq.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gt2lngjuhdh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gt2mbpzxwww.html

[U110] JS：数组分块
来源：http://dali.jinqigufen.top/Article/details/gt2inujnzvs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ehwqpu.com/Article/details/gt2ikctetug.html

[U111] JS：对象转 Map
来源：http://dali.snrcjt.cn/Article/details/gt2qzpldqvy.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gt2siodcuax.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gt2fixwnbxq.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2kvsbrdfu.html

[U113] JS：正则替换全部
来源：http://dali.iojbl.cn/Article/details/gt2abejdhxq.html

s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mekepnoo.html

[U114] JS：JSON 深比较
来源：http://dali.aizwys.cn/Article/details/gt2bzfiarwl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gt2ffwyhryn.html

[U115] JS：生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bildorkp.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2kywhycyh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.snrcjt.cn/Article/details/gt2bmcbytjx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gt2lfgpxpwl.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gt2dpgfzybj.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gt2lejcmxjm.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gt2pugpbuxf.html

npm i -D vite;  npx vite
来源：http://dali.svipenyu.cn/Article/details/gt2uieczfax.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkevqwpp.html

npx vite build
来源：http://dali.xziqi.cn/Article/details/gt2dbfvdcqh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pycfn.com/Article/details/gt2psduzgcq.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigufen.top/Article/details/gt2dmpiynxr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2cqslggoq.html

统计汇总
来源：http://dali.dianchejie.cn/Article/details/gt2fidmpbzc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2shxcykna.html

按语言统计（条）：
来源：http://dali.cucudq.cn/Article/details/gt2xbxqivzj.html

Python ......... 252
来源：http://dali.jyoumei.cn/Article/details/gt2mezdrsuy.html

PHP ............ 252
来源：http://dali.dashuyun.cn/Article/details/gt2ixtruwel.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gt2gqavneka.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2jcltczix.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2jelfyrsi.html

Go ............. 212
来源：http://dali.yvedp.cn/Article/details/gt2xsttkfec.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhenrjaf.html

C# ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gt2yvtsnwxc.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gt2rxfsvonw.html

C++ ............ 30
来源：http://dali.yonumen.top/Article/details/gt2gktbybvf.html

SQL ............ 90
来源：http://dali.sufxvd.cn/Article/details/gt2mlnijhns.html

Bash ........... 80
来源：http://dali.chenlongwang.top/Article/details/gt2rsjntrel.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gt2mrvyydve.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gt2mwpzmmab.html

Lua ............ 10
来源：http://dali.chenzaomai.com/Article/details/gt2eorwlqaa.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gt2wzqukiav.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gt2mpplmwjb.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2ttbuecks.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcfmbihg.html

按章节统计：
来源：http://dali.c1oappe.top/Article/details/gt2szmqynzu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gt2ostavzmv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mswgulqa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2fdfyoiiz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipijofxo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ydzc1.top/Article/details/gt2fuhuywtf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gt2bgsjwqep.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gt2eiszbimc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btjdndob.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2atdhmjqg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gt2vqsxzsaw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2tiqglxed.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2loxesrrl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2ulpaazgb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gt2gqsxdcwe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gt2aglqnufw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2hbqqyvuc.html

Q SQL 专题                              90
来源：http://dali.hnxiangtu.top/Article/details/gt2qbttyvib.html

R Bash 专题                             80
来源：http://dali.xuanzx.com/Article/details/gt2zvrbqpfk.html

S C / C++ 专题                          60
来源：http://dali.wangshuangyany.cn/Article/details/gt2snxcstey.html

T 其他语言补充                          60
来源：http://dali.shzxlz.cn/Article/details/gt2lizrlzav.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gt2jpczbock.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2xsrpcvsa.html

合计                                  2106 条
来源：http://dali.zycfv.cn/Article/details/gt2gvcyqhkh.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdeypyzy.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekxsusei.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gt2jbbcmszb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fzhhl.top/Article/details/gt2vhlaonvb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gt2nnrzbubv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jlsjyb.cn/Article/details/gt2fwebxija.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.316326.xyz/Article/details/gt2ijpecmga.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnqzz.top/Article/details/gt2aiikqhqb.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfufjtan.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2bsdbhekq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxrgjqgq.html

Common Programming Examples Cheat Book
来源：http://dali.xylfe.cn/Article/details/gt2doxsdjxi.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2uewthvog.html

【收录内容】
来源：http://dali.aizwys.cn/Article/details/gt2pemrankm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gt2gxtulrqj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.bjfxy.top/Article/details/gt2nmwfyblz.html

SQL · Bash · C · C++
来源：http://dali.cqqwz.cn/Article/details/gt2mjtzwbss.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gt2nygqmqri.html

【使用说明】
来源：http://dali.zhiwuduotai.top/Article/details/gt2tijotwqs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buwsdorm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gt2gznbmzgy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.mhx1999.top/Article/details/gt2kvohyfrr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tanke756.top/Article/details/gt2iwmlwhiv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hysaishi.cn/Article/details/gt2dssqmnsi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gt2fvfnulbt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gt2zzjtickp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yonumen.top/Article/details/gt2uwxmolgq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpmedqoi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.quarkkingdee.top/Article/details/gt2okbuxvcv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gt2bdcinbsn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gaohongyu789.top/Article/details/gt2cvgjnitb.html

【文件统计】
来源：http://dali.shuidangran.top/Article/details/gt2hdobnnzs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jianghu66.top/Article/details/gt2bqghpegp.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2nfwgnnts.html

目  录
来源：http://dali.ybcxt.top/Article/details/gt2zijwcfcp.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2belsikyx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2pmxorlsh.html


<!-- 参考信息 -->