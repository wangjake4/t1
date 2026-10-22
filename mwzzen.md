代发 wailian999

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gtpnbqvfru.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtglydhfnq.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gtuirraldc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zdqjudy.top/Article/details/gtgzyydfyq.html

[U17] Py：初始化日志
来源：http://dali.gogol.net.cn/Article/details/gttdlujown.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gotoacloud.top/Article/details/gthsevunzd.html

[U18] Py：预编译正则
来源：http://dali.jianghu66.top/Article/details/gtjhssdlgy.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gtotuuvvhf.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gtzvroihcb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gtlwasoyuk.html

[U20] Py：缓存函数结果
来源：http://dali.bjfxy.top/Article/details/gtddzuqpoc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.havefunace.top/Article/details/gtbzixfqpa.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gtnvlgcdvq.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gtunjobnem.html

[U22] Py：矩阵转置
来源：http://dali.hammf.cn/Article/details/gtkzjxsgbr.html

list(zip(*m))
来源：http://dali.haohaochexian.top/Article/details/gtfrliadld.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtzxcrbzti.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cashguo.top/Article/details/gtnicxduwy.html

[U24] Py：路径操作
来源：http://dali.fzhhl.top/Article/details/gtcoiuyvyr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtmxwekfra.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtwlozerui.html

csv.DictReader(f)
来源：http://dali.smart0.xyz/Article/details/gtstpbwghi.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gtmldhkinh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhiwuduotai.top/Article/details/gtitrppkrt.html

[U27] Py：异步 HTTP
来源：http://dali.ivvv.top/Article/details/gtcwszheql.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gtxejbdepr.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gttvgfeqeb.html

UserId = int
来源：http://dali.yj20258888.top/Article/details/gtkpdtpfxb.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gtnbvkrakm.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gteztxbmce.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtcwwjtzrw.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcqpeoxa.html

[U31] Py：单测
来源：http://dali.aizwys.cn/Article/details/gtkhtlipyc.html

python -m pytest -q
来源：http://dali.wangdashe.top/Article/details/gtyiwkgtzb.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtorkgquto.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gtrrwwytwj.html

[U33] Py：打包发布
来源：http://dali.jqgufenzy.top/Article/details/gtoakksjva.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.c1oappe.top/Article/details/gtoiflsqlo.html

[U34] Py：判断编码
来源：http://dali.xziqi.cn/Article/details/gtcffazwgi.html

chardet.detect(raw)
来源：http://dali.daxiang520.top/Article/details/gtaqqnbqyy.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnmvbusi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gthvemztsq.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gtdvhxekwj.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtfgtmangg.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gtimrqcutz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gtzjocinbj.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gthlaypycm.html

Path(__file__).resolve().parent
来源：http://dali.guowangkeji.top/Article/details/gtkghadokw.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnxiangtu.top/Article/details/gtxionzpkr.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gtgxpjddsj.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtwvphixch.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtskiyabkp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gtzyogzmoi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gtpaemakvk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.andypj.xyz/Article/details/gttexwyfzs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtduivougg.html

[U43] PHP：声明命名空间
来源：http://dali.zhoulong.xyz/Article/details/gthccfdguj.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gtzjdoqgvd.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtwmvwhrhi.html

declare(strict_types=1);
来源：http://dali.gaohongyu789.top/Article/details/gttyqxdenr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gthultlsca.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtykutxmdb.html

[U46] PHP：可空类型
来源：http://dali.nanxinkj.top/Article/details/gtrgwoptoe.html

?string $name = null
来源：http://dali.nanxuanxn.top/Article/details/gtwtfnrpgx.html

[U47] PHP：联合类型
来源：http://dali.cheryme.top/Article/details/gtdssrtetp.html

int|string $id
来源：http://dali.xuanzx.com/Article/details/gtehohrbpd.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtaacaguqj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gtmuimobar.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtlgildcsz.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gtdamajmnu.html

[U50] PHP：构造器属性提升
来源：http://dali.nwbrower.top/Article/details/gtpdmmzlkl.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gtcexxdqvf.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqlbdhoh.html

[$a, $b] = $arr;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpzicekl.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtvwqorlpc.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtckvgjoqd.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gtcwpfpeat.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtflzync.html

[U54] PHP：空安全调用
来源：http://dali.nanxuanxn.top/Article/details/gtvbevcjzk.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gtsnrumrfy.html

[U55] PHP：match 表达式
来源：http://dali.andypj.xyz/Article/details/gtoabfozla.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gtnvcqmqkn.html

[U56] PHP：命名参数
来源：http://dali.fzhhl.top/Article/details/gtlddydyxo.html

f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtrbmodcwr.html

[U57] PHP：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtdsgttmsy.html

"值: {$a}"
来源：http://dali.cdnleiting.top/Article/details/gtlqohtlws.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gtzurzpoxv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gtknwzywsv.html

[U59] PHP：自定义排序
来源：http://dali.hongshengwenyu.top/Article/details/gtxjecwynh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtxjmivjzv.html

[U60] PHP：JSON 编解码
来源：http://dali.cashguo.top/Article/details/gtkpkpzcjh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gtgpekrcrs.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gtcodtxded.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtmmsnkfex.html

[U62] PHP：日期对象
来源：http://dali.shuidangran.top/Article/details/gtagexuzmz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gtnklcxvwu.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtpsonahkx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pengpengdd.cyou/Article/details/gtssdwzicp.html

[U64] PHP：目录遍历
来源：http://dali.ppjwa.cn/Article/details/gtjwvneesm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.iojbl.cn/Article/details/gtrvwggapk.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gtildsdzjk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtdgvlopvg.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gtirozzjht.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnqzz.top/Article/details/gtlhtfjnsk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gtmdjuglfj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.quarkkingdee.top/Article/details/gtkwqkciem.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtqkdlmnxy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gtpqfxteyx.html

[U69] PHP：PDO 预处理
来源：http://dali.316326.xyz/Article/details/gtlazihvsd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigfzy.top/Article/details/gtmwlnupcn.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gtagdmimxv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yueranfly.top/Article/details/gtuolaugbu.html

[U71] PHP：抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtbafzqfkt.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gtnxxsobti.html

[U72] PHP：写错误日志
来源：http://dali.aizwys.cn/Article/details/gtsfuevttn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hammf.cn/Article/details/gtezvypsgu.html

[U73] PHP：读取 ini 配置
来源：http://dali.yonumen.top/Article/details/gtwqrgxttx.html

parse_ini_file("config.ini", true)
来源：http://dali.hywenlv.cn/Article/details/gtyygubohz.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtafifmqvd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.kuanghao11.cn/Article/details/gtsmlmmboa.html

[U75] PHP：依赖注入
来源：http://dali.xuetiantiany.cn/Article/details/gtphrzojea.html

composer require psr/container
来源：http://dali.daria6918.cn/Article/details/gtudoldpvy.html

[U76] PHP：简单路由
来源：http://dali.sweek.top/Article/details/gtpzrkqmwx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj202588.top/Article/details/gtojjsgorq.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtsjuybhzm.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gtfaeyraif.html

[U78] PHP：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gtaiumtafo.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gtpuuqeltf.html

[U79] PHP：静态分析
来源：http://dali.svipenyu.cn/Article/details/gtlzpefylw.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gtgapqeqek.html

[U80] PHP：代码规范修复
来源：http://dali.chenjidiqi.icu/Article/details/gtbrjmupzb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gzhubu.top/Article/details/gtaqxmgayv.html

[U81] JS：初始化项目
来源：http://dali.ehwqpu.com/Article/details/gtslzchcjk.html

npm init -y;  npm i express
来源：http://dali.yuanzhike.top/Article/details/gtpoalymnp.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeraxifc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yanxiufei.cn/Article/details/gttwdwfroz.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtdtcasjru.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gtlvrpgzlb.html

[U84] JS：CommonJS 写法
来源：http://dali.hongshengwenyu.top/Article/details/gtmcovwttb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhiwuduotai.top/Article/details/gtkqflfkod.html

[U85] JS：可选链
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzqcvshz.html

a?.b?.c
来源：http://dali.chenjidiqi.icu/Article/details/gtsyqoidxr.html

[U86] JS：空值合并
来源：http://dali.wangdashe.top/Article/details/gtjlwispgh.html

a ?? b
来源：http://dali.gzhubu.top/Article/details/gtheqrllfe.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gtqjvybcdi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zycfv.cn/Article/details/gtzslrsuxc.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gtzkmgcadg.html

{ ...a, ...b }
来源：http://dali.yj20258888.top/Article/details/gtexdhzlhk.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gtirdpqiet.html

[...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtldfjuyah.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gtpuuqcjgl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtyvqaspeb.html

[U91] JS：对象键值遍历
来源：http://dali.zhongyouzk.top/Article/details/gtombkvlyl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gtjlolaqfe.html

[U92] JS：深拷贝
来源：http://dali.wangdashe.top/Article/details/gtfjgsrdvi.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtyqerlypw.html

[U93] JS：模板字符串
来源：http://dali.nanxinkj.top/Article/details/gtilujxber.html

`共 ${n} 条`
来源：http://dali.jlsjyb.cn/Article/details/gtuzltbfgf.html

[U94] JS：箭头函数
来源：http://dali.jqgfzy.top/Article/details/gtqdeczdxx.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtezkhcjla.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gtrpdggkit.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gtmmcbdfgx.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gtpqnklwoe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtlqtavymu.html

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gttrtlvevw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtuigepxod.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtstqivwbr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuanzhike.top/Article/details/gttmvmygtk.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gtuwgrtvcm.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gtuusosein.html

[U100] JS：DOM 查询
来源：http://dali.hnqzz.top/Article/details/gtsunxafmb.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gtmocawmut.html

[U101] JS：classList 操作
来源：http://dali.daria6918.cn/Article/details/gtzgxdbbiu.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gtgruemjop.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gtxbemjbvp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gtriexjtpl.html

[U103] JS：定时器
来源：http://dali.aizwys.cn/Article/details/gtksbaecut.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gtzdrmlzll.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtdrrrwhrn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtirhcvtui.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gtefdnybcr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gtbivfdcpz.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gteafbcocx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gtlgkjoomg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtjkizchsm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtrsvujeea.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gtqkoqvgjl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hongshengwenyu.top/Article/details/gtzhjxcami.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtrytcsgnm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomaekqfx.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gtcrbqvfpm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ehwqpu.com/Article/details/gtjihcngve.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxohvyhal.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gtavqjjian.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gtsnfymaqv.html

"7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtqxvaaohp.html

[U113] JS：正则替换全部
来源：http://dali.yanxiufei.cn/Article/details/gtffmzdoto.html

s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtkapanpbg.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gtbufgepzp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtvjkolxvi.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gtwzvochyk.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtrqcfvtpc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbhqadcd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gtoyultgxb.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gtjlghrbez.html

npm i -D vitest;  npx vitest
来源：http://dali.yvedp.cn/Article/details/gteoxhdrlq.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gtucfxeuqu.html

npm i -D vite;  npx vite
来源：http://dali.feifeiyinyue.top/Article/details/gtpvceabkq.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gtqzxmebtw.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gtfisqmbbm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gtjginfwrk.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gtbltzkkca.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnbucajoy.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gtcimwnicj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthouqjrzm.html

按语言统计（条）：
来源：http://dali.cqqwz.cn/Article/details/gtxpsffklx.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gtzqjymvhp.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gtpgopeqxo.html

JavaScript ..... 252
来源：http://dali.mhx1999.top/Article/details/gtvrewacda.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gtqjrshbgo.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gttqukaekr.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gttqtnsbti.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtebcatdkm.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gttcuixqdq.html

C .............. 30
来源：http://dali.ivvv.top/Article/details/gtpqcheqkk.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gtrchuodbp.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtfnwlrmey.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gtaajqpqzm.html

Kotlin ......... 15
来源：http://dali.svipenyu.cn/Article/details/gthhemcawj.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gtzitmvvdp.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gtlkmibany.html

Perl ........... 10
来源：http://dali.bjfxy.top/Article/details/gtrcxbpoqn.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtqkyfbjvx.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtgaoaglsm.html

合计 ........... 2106 条
来源：http://dali.gzhubu.top/Article/details/gtnhmrsfmx.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gtmuuwzfbz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtujettcsl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtkxcqnwuh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggcqtcxv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtzfxtwwsu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gtpbxdezkm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gttmevduot.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtmyjowlmn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtgahokdmi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtsqedzcsz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gticdboznx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtohhsokql.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gthkmzeykq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtnarwoaug.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtudpeboxf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.andypj.xyz/Article/details/gtubbiyxkk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtbhzdpxqz.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gtjwohcaqt.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gtisqagdcb.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gtklvkmxta.html

T 其他语言补充                          60
来源：http://dali.ehwqpu.com/Article/details/gtjqyfyjxh.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gtxhodqxxo.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtqohujshp.html

合计                                  2106 条
来源：http://dali.zhengqikj.top/Article/details/gtmiobwbow.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtojxlfwub.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gtfnvduhix.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtlpjntlxn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtnorhowox.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.haohaochexian.top/Article/details/gtucolhsrs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jiagoushi.top/Article/details/gtlvjkhwnw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gtdrxbfugy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gtzotriovs.html

—— 文件结束 ——
来源：http://dali.jinqigfzy.top/Article/details/gtkppsgsuc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtuanklcnx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndyviuqy.html

Common Programming Examples Cheat Book
来源：http://dali.yongpay.top/Article/details/gtqqbhtdiz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvdibzxwa.html

【收录内容】
来源：http://dali.gotoacloud.top/Article/details/gttmdozwcb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fengsongda.top/Article/details/gtgencixpp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shzxlz.cn/Article/details/gtlfrvylok.html

SQL · Bash · C · C++
来源：http://dali.chenzaomai.com/Article/details/gtanbqewzu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangdashe.top/Article/details/gtzpcoaiif.html

【使用说明】
来源：http://dali.zhongyouzk.top/Article/details/gtyvdondug.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zdqjudy.top/Article/details/gtudeysyhk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuanzx.com/Article/details/gthitkpaph.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.bjfxy.top/Article/details/gtvzhvdzzy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.haohaochexian.top/Article/details/gtnkciscth.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gtxpchxqeo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sysykeji.top/Article/details/gttoaxnjxr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tian-w.cn/Article/details/gtvjqsrecr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.feifeiyinyue.top/Article/details/gtlkrgqwml.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenjidiqi.icu/Article/details/gttylacflm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtehwriapw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sysykeji.top/Article/details/gtyttsqqew.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj202588.top/Article/details/gthxxnmqwf.html

【文件统计】
来源：http://dali.havefunace.top/Article/details/gtskqoegvu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aibaodan.cn/Article/details/gteewwldmm.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtnhegzlbb.html

目  录
来源：http://dali.wangdashe.top/Article/details/gtvjcoongq.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtqvqfviyy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtnszjiqcn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtoullwefb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtqfjqlyuv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtnrmrfdfa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gtvgzsdwtg.html


<!-- 参考信息 -->