代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwmdkjih.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigfzy.top/Article/details/gt2isooevmy.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gt2bubvczly.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2cdfpsvdc.html

[U19] Py：正则替换带回调
来源：http://dali.cqqwz.cn/Article/details/gt2lsnamktm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenzaomai.com/Article/details/gt2lmpcvivq.html

[U20] Py：缓存函数结果
来源：http://dali.hammf.cn/Article/details/gt2cxwubihm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gt2jyhjjjkc.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gt2cjmfvbav.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gt2znbcojfr.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gt2axnnhmhj.html

list(zip(*m))
来源：http://dali.nwbrower.top/Article/details/gt2wgprghyz.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ogczudjf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gt2fmhmmhql.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gt2eqtveizp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2wmgkrntb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gt2ielnnuwv.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gt2mwsqgatl.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gt2yvhhdyui.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gt2ilrvptvo.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwoihjiw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzvqyuso.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkwqcgtl.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gt2bnlrixbe.html

[U29] Py：属性校验
来源：http://dali.yj202588.top/Article/details/gt2cbruzpfj.html

@property 与 @x.setter 配合
来源：http://dali.kuanghao11.cn/Article/details/gt2qegrywqd.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gt2qrnemxwi.html

@dataclass(slots=True)
来源：http://dali.andypj.xyz/Article/details/gt2nqhtydvg.html

[U31] Py：单测
来源：http://dali.yj202588.top/Article/details/gt2nnlytbeg.html

python -m pytest -q
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjoewpwm.html

[U32] Py：代码格式化
来源：http://dali.tianlin.xyz/Article/details/gt2hcvruocu.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gt2xuuepswh.html

[U33] Py：打包发布
来源：http://dali.hfpthk.cn/Article/details/gt2moaabhmg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.mhx1999.top/Article/details/gt2zqchgncb.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gt2wdbztxgy.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gt2dwurbgrh.html

[U35] Py：发送邮件
来源：http://dali.pycfn.com/Article/details/gt2nondhgwq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gt2evjqdwpb.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2xwzysagu.html

schedule.every(10).minutes.do(job)
来源：http://dali.gaohongyu789.top/Article/details/gt2adlbxyoz.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gt2qfsfsqgl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gt2xeiauwdu.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gt2hetpojin.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gt2odkesfaf.html

[U39] Py：判断是否在交互环境
来源：http://dali.hammf.cn/Article/details/gt2ngnktldg.html

sys.stdout.isatty()
来源：http://dali.gotoacloud.top/Article/details/gt2gjhwljwl.html

[U40] Py：打印到标准错误
来源：http://dali.zhixingplan.top/Article/details/gt2mveunsoq.html

print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gt2edccpilb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tian-w.cn/Article/details/gt2cdbmpxzq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sweek.top/Article/details/gt2aizgdvop.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gt2ghpebpjs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gt2degrssiw.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gt2lwymkrwq.html

namespace App\Http;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxjgsvrq.html

[U44] PHP：开启严格类型
来源：http://dali.xylfe.cn/Article/details/gt2lyusxxxa.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gt2bskunzga.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ucydynib.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdmvlikp.html

[U46] PHP：可空类型
来源：http://dali.jyoumei.cn/Article/details/gt2wkwsbcxm.html

?string $name = null
来源：http://dali.ybcxt.top/Article/details/gt2dysbouyv.html

[U47] PHP：联合类型
来源：http://dali.yuanzhike.top/Article/details/gt2vphwoydy.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gt2yyvpsbfe.html

[U48] PHP：纯枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2vuixghrr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gt2zreejxlq.html

[U49] PHP：只读属性
来源：http://dali.daria6918.cn/Article/details/gt2vzsvutya.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gt2mdapvhtt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgeueazh.html

public function __construct(private int $id) {}
来源：http://dali.smart0.xyz/Article/details/gt2vbayrftd.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gt2uaizbqxs.html

[$a, $b] = $arr;
来源：http://dali.zhiwuduotai.top/Article/details/gt2edlznzrl.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gt2kttbkgdf.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gt2lbdqoyiy.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gt2duavpuuo.html

$v = $a ?? $b ?? "default";
来源：http://dali.yvedp.cn/Article/details/gt2qprtiqqd.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2fssrybic.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gt2ceozxjfz.html

[U55] PHP：match 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2fidrbffc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nwbrower.top/Article/details/gt2hinnahiv.html

[U56] PHP：命名参数
来源：http://dali.nwbrower.top/Article/details/gt2gtwjsaoc.html

f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2kuqfjxdz.html

[U57] PHP：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sialdwyz.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2quzfxhgw.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gt2oltdfmre.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.birdmap.top/Article/details/gt2retaobqw.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txjmxfmy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2gtsczxiw.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gt2yhedtycb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xylfe.cn/Article/details/gt2pnqilzne.html

[U61] PHP：正则
来源：http://dali.jlsjyb.cn/Article/details/gt2weryduwu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2oxlkjgvh.html

[U62] PHP：日期对象
来源：http://dali.tianlin.xyz/Article/details/gt2xozxebbt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yangfankeji.com/Article/details/gt2rjutqjlm.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gt2hkuwouog.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gt2sfcfpneb.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2upbnstsg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnxiangtu.top/Article/details/gt2zypziolw.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnzynstz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2upgflqkc.html

[U66] PHP：设置 Cookie
来源：http://dali.cucudq.cn/Article/details/gt2crmwomxy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gt2krvjqvaq.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yscblzdh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gt2mboptlqn.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gt2ydvarrrn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gt2djjbrjoe.html

[U69] PHP：PDO 预处理
来源：http://dali.dashuyun.cn/Article/details/gt2barmcizn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gt2yqpctvsf.html

[U70] PHP：PDO 事务
来源：http://dali.zhengqikj.top/Article/details/gt2tqepgvdc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gt2qryqprje.html

[U71] PHP：抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2tnmsyadm.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gt2moxbignj.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gt2zxffrmmq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nanxuanxn.top/Article/details/gt2vwrxifms.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlwsxcur.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gt2uypaairw.html

[U74] PHP：读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2eweevrms.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sysykeji.top/Article/details/gt2nghpednu.html

[U75] PHP：依赖注入
来源：http://dali.daria6918.cn/Article/details/gt2bbgopdqz.html

composer require psr/container
来源：http://dali.guannengcc.top/Article/details/gt2vaypnnis.html

[U76] PHP：简单路由
来源：http://dali.jiagoushi.top/Article/details/gt2nkwdfznf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yangfankeji.com/Article/details/gt2mkouaump.html

[U77] PHP：模板渲染
来源：http://dali.0kj1m.cn/Article/details/gt2rwhgtbgo.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gt2kygcufbs.html

[U78] PHP：单元测试
来源：http://dali.hysaishi.cn/Article/details/gt2toncrtdr.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gt2rwpeauyv.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gt2kwfzuzgb.html

composer require --dev phpstan/phpstan
来源：http://dali.zdqjudy.top/Article/details/gt2bzgjaiqg.html

[U80] PHP：代码规范修复
来源：http://dali.bjfxy.top/Article/details/gt2zfxfxxjk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shangyingyoupin.top/Article/details/gt2kakucdtl.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gt2cbbfaoxt.html

npm init -y;  npm i express
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrpysaxe.html

[U82] JS：package.json 脚本
来源：http://dali.pycfn.com/Article/details/gt2zkobmewm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.mhx1999.top/Article/details/gt2jpawqoky.html

[U83] JS：ES Module 导入导出
来源：http://dali.daria6918.cn/Article/details/gt2lweckjpn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gt2dqhuppln.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gt2zawxjafj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gogol.net.cn/Article/details/gt2upbjmyrh.html

[U85] JS：可选链
来源：http://dali.yj20258.top/Article/details/gt2pxkukbxs.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gt2wsetxcoy.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gt2ypulkshb.html

a ?? b
来源：http://dali.shzxlz.cn/Article/details/gt2cmpgwxku.html

[U87] JS：解构默认值
来源：http://dali.haohaochexian.top/Article/details/gt2vpvkqpid.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gt2jhoeppyb.html

[U88] JS：对象展开合并
来源：http://dali.cqqwz.cn/Article/details/gt2ixqjfjaj.html

{ ...a, ...b }
来源：http://dali.cucudq.cn/Article/details/gt2uqdarbjm.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gt2njkvkmlx.html

[...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gt2epanxtlo.html

[U90] JS：数字数组排序
来源：http://dali.tianlin.xyz/Article/details/gt2nhfdxqqp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2efysxgyy.html

[U91] JS：对象键值遍历
来源：http://dali.pycfn.com/Article/details/gt2vqtsjzja.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gt2xjhlqvdv.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2eakiejmq.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2smfeiyjk.html

[U93] JS：模板字符串
来源：http://dali.aibaodan.cn/Article/details/gt2gpibsjjl.html

`共 ${n} 条`
来源：http://dali.zhixingplan.top/Article/details/gt2wmudivvz.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gt2zhwfevsg.html

const double = x => x * 2;
来源：http://dali.0kj1m.cn/Article/details/gt2qsvfjwry.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gt2kqpjsdwt.html

new Promise((resolve, reject) => {})
来源：http://dali.pycfn.com/Article/details/gt2cbvkalyr.html

[U96] JS：async/await 与异常
来源：http://dali.redwolf501.top/Article/details/gt2lwehkdjq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2kbymlimy.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gt2nexekpte.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2ezmmacgk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2qiaefkef.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ioxldtjd.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gt2wubbahdn.html

el.addEventListener("click", e => {})
来源：http://dali.tanke756.top/Article/details/gt2acoczmrj.html

[U100] JS：DOM 查询
来源：http://dali.tianlin.xyz/Article/details/gt2wdkgvfrl.html

document.querySelector(".item")
来源：http://dali.aibaodan.cn/Article/details/gt2pmcxpnvp.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gt2bctkrupm.html

el.classList.toggle("active")
来源：http://dali.yj20258.top/Article/details/gt2utayqaad.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxlphivt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gt2drlogazw.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gt2kacmexab.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efowhbvr.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gt2jcaeqkvb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2malhzazz.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gt2jjhczkmo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2aagjcnzm.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdcazeoc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gt2qwjhtomx.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gt2pockzovc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.fzhhl.top/Article/details/gt2drgekymg.html

[U108] JS：随机整数
来源：http://dali.chenjidiqi.icu/Article/details/gt2juujijcg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.birdmap.top/Article/details/gt2bdbhopsh.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gt2jmtljfxe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2jqsxeaau.html

[U110] JS：数组分块
来源：http://dali.xuanzx.com/Article/details/gt2wvnrsjpy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gt2arrgwkie.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gt2eqplsatx.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gt2tlyvcykq.html

[U112] JS：字符串补位
来源：http://dali.sufxvd.cn/Article/details/gt2elzhqwmv.html

"7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2iqxxlsww.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gt2mytscgxj.html

s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2jvhayjpj.html

[U114] JS：JSON 深比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkjlebxk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gt2mjymmwqe.html

[U115] JS：生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2ondgqhht.html

crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahbzuozo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj202588.top/Article/details/gt2azmavzio.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2sndwxykc.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2ppjzitcu.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcbpokga.html

[U118] JS：开发服务器
来源：http://dali.wangshuangyany.cn/Article/details/gt2shvpwnhc.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gt2dtzkrfzd.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gt2ygvrwddn.html

npx vite build
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyijxdug.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ybcxt.top/Article/details/gt2bisdqdpt.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gt2htgbkclt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2fkkhkzji.html

统计汇总
来源：http://dali.ydzc1.top/Article/details/gt2ilgenpmg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2txjezvrn.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gt2nbviddpv.html

Python ......... 252
来源：http://dali.9152youxi.cn/Article/details/gt2ivrtwmmw.html

PHP ............ 252
来源：http://dali.jqgufenzy.top/Article/details/gt2oovjzvtc.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gt2cpltcfsu.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxngkguh.html

Java ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2bntxgwyn.html

Go ............. 212
来源：http://dali.shzxlz.cn/Article/details/gt2eqvwdbfn.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2clbiolar.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2wqkxqqsw.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gt2vapfneey.html

C++ ............ 30
来源：http://dali.andypj.xyz/Article/details/gt2iwncimuo.html

SQL ............ 90
来源：http://dali.ppjwa.cn/Article/details/gt2rtpvuues.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gt2fhvazyvq.html

Kotlin ......... 15
来源：http://dali.tianlin.xyz/Article/details/gt2tsydfckh.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gt2mwsowrdv.html

Lua ............ 10
来源：http://dali.xuanzx.com/Article/details/gt2gnqpducf.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2pqocsqwd.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gt2qzdozvix.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2vlncqtyj.html

合计 ........... 2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2afnvjgan.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gt2lccsxoll.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gt2thhiyvec.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gt2aewpxpdl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gt2mxzuahbi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gt2fgzqsjtg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gt2zpefhuld.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gt2qjfzblsu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gt2aedyozsb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gt2wehygmek.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2lnysgyxj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gt2pqlldand.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2vwtlgtrz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2ndehgrqk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixjsglow.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gt2ppfalrte.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jyoumei.cn/Article/details/gt2nqptpxdm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2xxbxxrao.html

Q SQL 专题                              90
来源：http://dali.fzhhl.top/Article/details/gt2ejfrqtxh.html

R Bash 专题                             80
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbqlnpfn.html

S C / C++ 专题                          60
来源：http://dali.ehwqpu.com/Article/details/gt2afpddmnf.html

T 其他语言补充                          60
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxyvgwrl.html

U 高频实用片段                         120
来源：http://dali.ivvv.top/Article/details/gt2gaursjaw.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txzhlxzl.html

合计                                  2106 条
来源：http://dali.kuanghao11.cn/Article/details/gt2serjjbsv.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2nuobqovi.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gt2uhmbpdvs.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2fuulthbt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yvedp.cn/Article/details/gt2iqkkqhpo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fengsongda.top/Article/details/gt2qztyxnip.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tianlin.xyz/Article/details/gt2kmfnmzki.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgccmlka.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gt2alohvjpb.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gt2lkvtglov.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xiaflvtw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gt2mlmzkree.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gt2vleprjlq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2tmosvqxt.html

【收录内容】
来源：http://dali.hnqzz.top/Article/details/gt2yymxzruc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hammf.cn/Article/details/gt2stzmxgfh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangdashe.top/Article/details/gt2xufnresl.html

SQL · Bash · C · C++
来源：http://dali.gaohongyu789.top/Article/details/gt2uxjqbghg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecmngjmw.html

【使用说明】
来源：http://dali.zhongyouzk.top/Article/details/gt2txjmdbcr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gt2jkomnoqk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2migymzxs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gt2nhfklvvg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fzhhl.top/Article/details/gt2fvwzjrij.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngyucmmi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxuanxn.top/Article/details/gt2vtiamkad.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gaohongyu789.top/Article/details/gt2vespmbez.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.havefunace.top/Article/details/gt2vwouykdd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sxryk.cn/Article/details/gt2wjvfymfo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cashguo.top/Article/details/gt2ayphjcvw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.redwolf501.top/Article/details/gt2afklyccv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nanxuanxn.top/Article/details/gt2puunjaxs.html

【文件统计】
来源：http://dali.c1oappe.top/Article/details/gt2cxqxtzuj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gt2tlcyrbzv.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2japyoocf.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gt2yktlyhfs.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okeuwwde.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2frrstnjd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gt2hyfudryo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gt2zobjzusa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gt2qnmgiruz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuxming.cn/Article/details/gt2uzrhwsap.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gt2fhzercnc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gt2mwvvbvuj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gt2wmyieers.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehdtjdms.html


<!-- 参考信息 -->