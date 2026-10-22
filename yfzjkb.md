代发 wailian999

[U15] Py：高精度计时
来源：http://dali.ybcxt.top/Article/details/gtrgrdzxzj.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gtbcpmozxg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gtvtictren.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gtvizxmzcu.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gtkbpmtaon.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gtrtselwnn.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gtsiyyhjra.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gtxkwzqgkr.html

[U19] Py：正则替换带回调
来源：http://dali.zhoulong.xyz/Article/details/gtlhdzwsql.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cdnleiting.top/Article/details/gtcrvmiqge.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gttvrctxin.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gtxfidbdvl.html

[U21] Py：自定义上下文管理器
来源：http://dali.gaohongyu789.top/Article/details/gtdjopyjhu.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gtbdquuyga.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gtaeegyjnr.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gthezwvluf.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gtmjewfbox.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtndkzxapx.html

[U24] Py：路径操作
来源：http://dali.hnxiangtu.top/Article/details/gthunwofbm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtkhuniiup.html

[U25] Py：CSV 按字典读
来源：http://dali.ydzc1.top/Article/details/gtzopnwqax.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtgvfegxih.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gttiivqzhq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtcrljbqmq.html

[U27] Py：异步 HTTP
来源：http://dali.svipenyu.cn/Article/details/gtnbiesclj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gtlfvtsuwh.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangtech.top/Article/details/gteluziyqf.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gtimjyohqa.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gtttywfvtv.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gtsfkkndgi.html

[U30] Py：数据类
来源：http://dali.aibaodan.cn/Article/details/gtiyhzciot.html

@dataclass(slots=True)
来源：http://dali.jiagoushi.top/Article/details/gtnghhxtwd.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gtzgxwucga.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gtcyywszku.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtqhwspfrp.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtvvknfzpa.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gtvixfdmvp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtptaekafu.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtohotgjoi.html

chardet.detect(raw)
来源：http://dali.ydzc1.top/Article/details/gtqhduksgs.html

[U35] Py：发送邮件
来源：http://dali.redwolf501.top/Article/details/gtyfwajsbd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dashuyun.cn/Article/details/gtystsvxlo.html

[U36] Py：定时任务
来源：http://dali.daria6918.cn/Article/details/gtnpopeynk.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenlongwang.top/Article/details/gtujexouuc.html

[U37] Py：读写 Excel
来源：http://dali.shangyingyoupin.top/Article/details/gtxwpzjwzl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gtdfnbvuxw.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtmzybjffw.html

Path(__file__).resolve().parent
来源：http://dali.yangfankeji.com/Article/details/gtxclbjnce.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gttgvhkrnb.html

sys.stdout.isatty()
来源：http://dali.meibo888.top/Article/details/gtdgzbeeza.html

[U40] Py：打印到标准错误
来源：http://dali.ivvv.top/Article/details/gtpbaedgsl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtbucbahno.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gtcywyjxlu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnxiangtu.top/Article/details/gtfamhsuzo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gtdiwfsenc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jiagoushi.top/Article/details/gtjjaydkmb.html

[U43] PHP：声明命名空间
来源：http://dali.tianlin.xyz/Article/details/gtiisetgbo.html

namespace App\Http;
来源：http://dali.jiagoushi.top/Article/details/gttnkkpcsl.html

[U44] PHP：开启严格类型
来源：http://dali.zdqjudy.top/Article/details/gtbuezoadv.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtknsndosd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gtdombvldv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtxrhdgeks.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gtqtzgxdns.html

?string $name = null
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhyztkjt.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gttkcxnkmp.html

int|string $id
来源：http://dali.yj202588.top/Article/details/gtlkcphzfd.html

[U48] PHP：纯枚举
来源：http://dali.zycfv.cn/Article/details/gtlaikteef.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gtsyqnacyw.html

[U49] PHP：只读属性
来源：http://dali.yanxiufei.cn/Article/details/gtkmudedkl.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gtdueloiuk.html

[U50] PHP：构造器属性提升
来源：http://dali.0kj1m.cn/Article/details/gtayjxnxcu.html

public function __construct(private int $id) {}
来源：http://dali.gogol.net.cn/Article/details/gtgjdyxyaw.html

[U51] PHP：数组解构
来源：http://dali.guannengcc.top/Article/details/gtebpdfway.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gtjpunxnnj.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gttzepmbht.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gttlyikzil.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtoklpzkvk.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigufen.top/Article/details/gtqzwpekzt.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gtfhjehlqp.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gtepvgrbfg.html

[U55] PHP：match 表达式
来源：http://dali.ivvv.top/Article/details/gtrfryeweg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sweek.top/Article/details/gtdnrynrbk.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gtklnwzpgi.html

f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtegkfxxiu.html

[U57] PHP：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtwhjilvam.html

"值: {$a}"
来源：http://dali.tianlin.xyz/Article/details/gtjkxtetqn.html

[U58] PHP：数组三件套
来源：http://dali.jqgfzy.top/Article/details/gtvtobrhnw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtgapuufui.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gtrxayrbsl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtmxuswqfx.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gthmjukczc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gtintiwswn.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gtcuwkmagd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtmhfqwvcn.html

[U62] PHP：日期对象
来源：http://dali.yj20258888.top/Article/details/gtskxxmbqz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gteppqsmkq.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gtdrwdlvzg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xziqi.cn/Article/details/gtvdmujxfy.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtnobkqjta.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigfzy.top/Article/details/gtmasvzjvn.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtrohjppmm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuegwcho.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gthgqxdmeb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nwbrower.top/Article/details/gticwktrfs.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gtsrbaofrs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gthlasvsab.html

[U68] PHP：PDO 连接
来源：http://dali.gogol.net.cn/Article/details/gtuyupkbkp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gtmqdsqvkh.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gtvojrceyk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtcsptihuu.html

[U70] PHP：PDO 事务
来源：http://dali.chenzaomai.com/Article/details/gtjvazlvrb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxuanxn.top/Article/details/gtdwlhlufg.html

[U71] PHP：抛出异常
来源：http://dali.xuanzx.com/Article/details/gtltoyftkc.html

throw new RuntimeException("失败", 500);
来源：http://dali.smart0.xyz/Article/details/gtelghydms.html

[U72] PHP：写错误日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdckvndn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtnhhadvdz.html

[U73] PHP：读取 ini 配置
来源：http://dali.snrcjt.cn/Article/details/gtriejtirj.html

parse_ini_file("config.ini", true)
来源：http://dali.dashuyun.cn/Article/details/gthrdlylem.html

[U74] PHP：读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtappryhav.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvppuvcgk.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtrmceyyan.html

composer require psr/container
来源：http://dali.jqgfzy.top/Article/details/gtadnzmusv.html

[U76] PHP：简单路由
来源：http://dali.cucudq.cn/Article/details/gtafvgksrr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuetiantiany.cn/Article/details/gtmmcimfve.html

[U77] PHP：模板渲染
来源：http://dali.tanke756.top/Article/details/gtkizpimle.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gtippnldda.html

[U78] PHP：单元测试
来源：http://dali.xuanzx.com/Article/details/gtqlywycxd.html

composer require --dev phpunit/phpunit
来源：http://dali.tian-w.cn/Article/details/gtekdcmuts.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gtzugqjnym.html

composer require --dev phpstan/phpstan
来源：http://dali.xziqi.cn/Article/details/gtiznwbmtl.html

[U80] PHP：代码规范修复
来源：http://dali.jianghu66.top/Article/details/gthmpjefau.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gzhubu.top/Article/details/gtsxzammjw.html

[U81] JS：初始化项目
来源：http://dali.kuanghao11.cn/Article/details/gtivzhxetn.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gtnoggljix.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gteyydgide.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gtegvurhdf.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gtwgkhgrsi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtiwfbmtga.html

[U84] JS：CommonJS 写法
来源：http://dali.ivvv.top/Article/details/gtendxeegt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxuanxn.top/Article/details/gtqwqmnnmp.html

[U85] JS：可选链
来源：http://dali.xziqi.cn/Article/details/gtsuunfbhn.html

a?.b?.c
来源：http://dali.zhoulong.xyz/Article/details/gtitknuxxk.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gtkirqyuwm.html

a ?? b
来源：http://dali.vqdsnc.cn/Article/details/gtdmsojslt.html

[U87] JS：解构默认值
来源：http://dali.kuanghao11.cn/Article/details/gtgqobyvnf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gteuqjbrds.html

[U88] JS：对象展开合并
来源：http://dali.shzxlz.cn/Article/details/gtlgsfdvpj.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuvwceco.html

[U89] JS：数组去重
来源：http://dali.sweek.top/Article/details/gtphbpbpqq.html

[...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtvyaylmxp.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gtupwztmtx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gthwduvwjx.html

[U91] JS：对象键值遍历
来源：http://dali.316326.xyz/Article/details/gtgpcebfsz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhqrwkzw.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gtckbqqcno.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtaxzfwevu.html

[U93] JS：模板字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtwvsrugce.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gtohcehpfv.html

[U94] JS：箭头函数
来源：http://dali.cashguo.top/Article/details/gtlysmivzt.html

const double = x => x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtxafjncww.html

[U95] JS：Promise 包装
来源：http://dali.gotoacloud.top/Article/details/gtbukeparm.html

new Promise((resolve, reject) => {})
来源：http://dali.birdmap.top/Article/details/gtruqootrz.html

[U96] JS：async/await 与异常
来源：http://dali.yj202588.top/Article/details/gtkjbifzlm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtzbbmcuvl.html

[U97] JS：并发请求
来源：http://dali.fengsongda.top/Article/details/gtydesajyc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtokqcqain.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtzfiujfze.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xinyue.icu/Article/details/gtpzgbknje.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gtcwjwlzbl.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gthqphfsxu.html

[U100] JS：DOM 查询
来源：http://dali.snrcjt.cn/Article/details/gtacsxqoyl.html

document.querySelector(".item")
来源：http://dali.chenjidiqi.icu/Article/details/gtmtaucaez.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtgkbpdmxh.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtdhbcvdqc.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gtsksulyht.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangshuangyany.cn/Article/details/gtexqkbxgi.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gtfxzspyes.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gtuyuiygti.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gtkoolilwd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtbbrlddos.html

[U105] JS：节流
来源：http://dali.zhixingplan.top/Article/details/gtzmwmolzm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.snrcjt.cn/Article/details/gtejgsvsjg.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtktiwfhch.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdxatbrv.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtohwojrhd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtjipzpaan.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtznlfjwav.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hfpthk.cn/Article/details/gtieprmiaf.html

[U109] JS：数组分组
来源：http://dali.guowangkeji.top/Article/details/gtvlauyznq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtrohsrlcb.html

[U110] JS：数组分块
来源：http://dali.yonumen.top/Article/details/gtlqmdatuu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gtcohahukr.html

[U111] JS：对象转 Map
来源：http://dali.jianghu66.top/Article/details/gtiervkgwx.html

new Map(Object.entries(obj))
来源：http://dali.ppjwa.cn/Article/details/gtswzbdgkw.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gtfkvatndl.html

"7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gteeiyskbe.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gtgbnbvtdn.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtkfayfpqb.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gtmjfpitgm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtljwotlce.html

[U115] JS：生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtlkowdctt.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtrcxkojly.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xziqi.cn/Article/details/gttyncoaun.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gtojnvqomk.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gtdrhsljxs.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gtbykzbcfg.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gttvydgzzp.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gtpkzilcpf.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gtnoparntb.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gtpqqaztpn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtgdygnres.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkjljchu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkrqphkhs.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gtfzklplmg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtioizyrkf.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gtjwdllvrp.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gttzaffckh.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gthmdwxozp.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gtyezceaqx.html

TypeScript ..... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtbfscfjdk.html

Java ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtycgfukzi.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gtgknscufc.html

Ruby ........... 212
来源：http://dali.ydzc1.top/Article/details/gtafuyjhdb.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtjonnnvon.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gtgbzmwktf.html

C++ ............ 30
来源：http://dali.jinghuilouyu.cn/Article/details/gtbivhwrzl.html

SQL ............ 90
来源：http://dali.jlsjyb.cn/Article/details/gtrwfceczs.html

Bash ........... 80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbetxhtql.html

Kotlin ......... 15
来源：http://dali.ppjwa.cn/Article/details/gtwkebygmq.html

Swift .......... 15
来源：http://dali.jianghu66.top/Article/details/gtxhdazgof.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawgqfoxe.html

Perl ........... 10
来源：http://dali.aibaodan.cn/Article/details/gtdfiybbfm.html

Scala .......... 10
来源：http://dali.316326.xyz/Article/details/gtoaloifkq.html

------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtxubzpdpc.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gtfsgejcnz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gtmvihhizz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtyjpbtinp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gthtqrvbsx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtnhegjvuf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gtmqzlwami.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yanxiufei.cn/Article/details/gtaxhpxnoz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gtdnedrfui.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtpibnqsnm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gttstmqfyw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtmkomenty.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaorqfqr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtsifgjazj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtxtymjgsy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtiavnjxax.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtoovasvid.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gogol.net.cn/Article/details/gtyygxrbiu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gthnsslfjc.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gtxhiwmdul.html

R Bash 专题                             80
来源：http://dali.jiagoushi.top/Article/details/gtylwlivcl.html

S C / C++ 专题                          60
来源：http://dali.fengsongda.top/Article/details/gtjcvaujti.html

T 其他语言补充                          60
来源：http://dali.yj20258888.top/Article/details/gtxeuplxzn.html

U 高频实用片段                         120
来源：http://dali.cashguo.top/Article/details/gtqqcoqyzj.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtrmzadkvi.html

合计                                  2106 条
来源：http://dali.fengsongda.top/Article/details/gtupmotatg.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtdjzkuurl.html

使用提醒
来源：http://dali.aibaodan.cn/Article/details/gtpsujevmi.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtcpulluvh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.iojbl.cn/Article/details/gtskzxrpxv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fzhhl.top/Article/details/gtnigyhafg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gtrxyylsyc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gtviuncxrq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhvxkdja.html

—— 文件结束 ——
来源：http://dali.kuanghao11.cn/Article/details/gtbrzjjinw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzbshpdvr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedcundyz.html

Common Programming Examples Cheat Book
来源：http://dali.bjfxy.top/Article/details/gtixxrvmzh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsqvbtfcp.html

【收录内容】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztdiycki.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zdqjudy.top/Article/details/gtprszfmtn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gtqhvaisxo.html

SQL · Bash · C · C++
来源：http://dali.vqdsnc.cn/Article/details/gtieldvkao.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xinyue.icu/Article/details/gtbhzoxwuq.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gtpzdbahpo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtihdmwpdt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gtdxfcbbud.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnxiangtu.top/Article/details/gtcppxgndo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cqqwz.cn/Article/details/gtrletreuk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tian-w.cn/Article/details/gtxlbexsam.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xylfe.cn/Article/details/gtgavwjgin.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangshuangyany.cn/Article/details/gtrcxbvlfe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.havefunace.top/Article/details/gtxfjpiymg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fzhhl.top/Article/details/gtegpnkdmw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.mhx1999.top/Article/details/gtmewjsbdl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ydzc1.top/Article/details/gtcmzudvmh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.meibo888.top/Article/details/gtojyghoii.html

【文件统计】
来源：http://dali.meibo888.top/Article/details/gtqkeznkny.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.kuanghao11.cn/Article/details/gtycvjofdr.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtcyyiheye.html

目  录
来源：http://dali.sweek.top/Article/details/gtdgxpajfx.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtgqbiqxvd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtfsxnrwpj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtzytwbspr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtzfzrcqii.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gtvvlamtvz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yangfankeji.com/Article/details/gtueycgkfh.html


<!-- 参考信息 -->