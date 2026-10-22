代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtkcgxacen.html

(x * 2 for x in arr)
来源：http://dali.xinyue.icu/Article/details/gtdhmdubpv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hysaishi.cn/Article/details/gtxefwytny.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gtkvmvfycl.html

[U13] Py：固定长度队列
来源：http://dali.shangyingyoupin.top/Article/details/gtegqoylzb.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gtuwwplbqt.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gtuipoqjji.html

defaultdict(list)
来源：http://dali.jiagoushi.top/Article/details/gtnsjakdck.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtlbwwafga.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gteouneyxz.html

[U16] Py：命令行参数解析
来源：http://dali.zhengqikj.top/Article/details/gtoeirboff.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gtqbqmcrhy.html

[U17] Py：初始化日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtczgaaxzk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gtgbxzvfhm.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtbiurcxts.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gtlogiuura.html

[U19] Py：正则替换带回调
来源：http://dali.xziqi.cn/Article/details/gtmxcoehhr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.quarkkingdee.top/Article/details/gtqrfdnopt.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gtifqvcxgx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gtvbxpzlvz.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gteexwbyqt.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtgmgwnosv.html

[U22] Py：矩阵转置
来源：http://dali.pycfn.com/Article/details/gtoviayefq.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gtamtgmyhf.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gtxfcjpjzl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gthrewpzcv.html

[U24] Py：路径操作
来源：http://dali.tian-w.cn/Article/details/gtydlrtfxe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtznuidtye.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gtiepavzgu.html

csv.DictReader(f)
来源：http://dali.hnxiangtu.top/Article/details/gtnimdhsut.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gtjpuvfxkb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gtckapmilu.html

[U27] Py：异步 HTTP
来源：http://dali.jqgufenzy.top/Article/details/gtckrjiiuz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gtiqrmjksr.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gtmuhrtxtb.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gtnlkdnvcv.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gtesqarurq.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gtrvbnmadb.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtodqnbnbj.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtwnfffjrv.html

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbzoeevo.html

python -m pytest -q
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbqzuote.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gtwjxdgvmi.html

ruff format . && ruff check --fix .
来源：http://dali.tian-w.cn/Article/details/gthtcrvkmk.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gttmovwohz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuanzhike.top/Article/details/gtycyxhkwv.html

[U34] Py：判断编码
来源：http://dali.haohaochexian.top/Article/details/gtvujvyfym.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gtcpnhepki.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gtonyorjcq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gtwxwpeurq.html

[U36] Py：定时任务
来源：http://dali.mhx1999.top/Article/details/gtvswzxhng.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gtafaddaro.html

[U37] Py：读写 Excel
来源：http://dali.xuetiantiany.cn/Article/details/gtpzzyhfcu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtciodowwy.html

[U38] Py：获取脚本所在目录
来源：http://dali.ybcxt.top/Article/details/gtnzhyprea.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gtiukteqnz.html

[U39] Py：判断是否在交互环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpeanyfj.html

sys.stdout.isatty()
来源：http://dali.sxryk.cn/Article/details/gtuqohtryd.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gtcxnslshd.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtlgywgdgz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yongpay.top/Article/details/gtghpvfaqc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.smart0.xyz/Article/details/gtqpeyyhzp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gtflwklswf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gtfxjrvtrg.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtmfmwdrym.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gtnkkqsgai.html

[U44] PHP：开启严格类型
来源：http://dali.sufxvd.cn/Article/details/gtaunybyfy.html

declare(strict_types=1);
来源：http://dali.nanxinkj.top/Article/details/gtuegqzfvg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gteuyczaib.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtaayxxhuk.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtxxogivlm.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gtkodtvhvt.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtymprwbea.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtxjkrdppg.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuklenguy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ehwqpu.com/Article/details/gtnitpnaxp.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gtutrjbdcb.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtnmagnvkc.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gtyctylfdl.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtspbnzwhc.html

[U51] PHP：数组解构
来源：http://dali.pengpengdd.cyou/Article/details/gtnxmdlysg.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gticrlcifq.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtpqewfjrd.html

$double = fn($x) => $x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwbcwogx.html

[U53] PHP：空合并运算符
来源：http://dali.sxryk.cn/Article/details/gtisgkfmhi.html

$v = $a ?? $b ?? "default";
来源：http://dali.jlsjyb.cn/Article/details/gtipdgvbtw.html

[U54] PHP：空安全调用
来源：http://dali.nwbrower.top/Article/details/gtkxvnalxa.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gtjlbtjldh.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gthuqynhpu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sxryk.cn/Article/details/gtjafyvzgl.html

[U56] PHP：命名参数
来源：http://dali.guowangkeji.top/Article/details/gtyrxzyyic.html

f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtmurhdhbj.html

[U57] PHP：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gteyjczzrj.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gtnvrwwlsw.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydpeejgm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.316326.xyz/Article/details/gttfiigsdr.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gtkwmrfbxw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtxagysilu.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gttiuprqiy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.svipenyu.cn/Article/details/gtlplkowmu.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gteuewzhpo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtyfbjztdu.html

[U62] PHP：日期对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcmnegff.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgfzy.top/Article/details/gtbfoyrepl.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gtczesxzxf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gtjvhgcxvg.html

[U64] PHP：目录遍历
来源：http://dali.hfpthk.cn/Article/details/gtkdnoxemi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.svipenyu.cn/Article/details/gttbqlcobq.html

[U65] PHP：会话
来源：http://dali.yongpay.top/Article/details/gtvrboidni.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtzsnfeoue.html

[U66] PHP：设置 Cookie
来源：http://dali.guowangkeji.top/Article/details/gtctxelhni.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gtbbciwiwh.html

[U67] PHP：处理文件上传
来源：http://dali.jlsjyb.cn/Article/details/gtotodjowy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gtmpcscxcd.html

[U68] PHP：PDO 连接
来源：http://dali.tanke756.top/Article/details/gtelfhgqpb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tanke756.top/Article/details/gtamdphyfi.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtwbjxxlyk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gtzsdqkeml.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gtzmlxhiud.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gtcbijlzra.html

[U71] PHP：抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtfwechngf.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gttqqtlvwz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gtgrdusqqj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gtmepxwdxn.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258.top/Article/details/gtvrvicriq.html

parse_ini_file("config.ini", true)
来源：http://dali.aibaodan.cn/Article/details/gtsjeoshat.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtshofrrff.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hongshengwenyu.top/Article/details/gtaghxyoke.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtrlbkvvxc.html

composer require psr/container
来源：http://dali.xuanzx.com/Article/details/gtyznvdcqp.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtmpvbcnti.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gtpxfigruy.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gtdiafusbm.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gtagipobkp.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gthwcuneay.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gtwlssrjnp.html

[U79] PHP：静态分析
来源：http://dali.nanxuanxn.top/Article/details/gtrtyqpnou.html

composer require --dev phpstan/phpstan
来源：http://dali.cdnleiting.top/Article/details/gtjfrkygry.html

[U80] PHP：代码规范修复
来源：http://dali.wangdashe.top/Article/details/gtkqejmrzs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ydzc1.top/Article/details/gthjxsjpwu.html

[U81] JS：初始化项目
来源：http://dali.kuanghao11.cn/Article/details/gtlvkchrfm.html

npm init -y;  npm i express
来源：http://dali.yangfankeji.com/Article/details/gtgfujdopr.html

[U82] JS：package.json 脚本
来源：http://dali.jiagoushi.top/Article/details/gtgvcfhcse.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gtjlglctmt.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gttmlptqwp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtkyycakgs.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtoperoogc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.feifeiyinyue.top/Article/details/gteohflgoy.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gtheueowdr.html

a?.b?.c
来源：http://dali.zhiwuduotai.top/Article/details/gtpjpocqkg.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gtedgrozfz.html

a ?? b
来源：http://dali.haohaochexian.top/Article/details/gtyirogslj.html

[U87] JS：解构默认值
来源：http://dali.jinqigufen.top/Article/details/gtthmlmrhl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gtwksrkaad.html

[U88] JS：对象展开合并
来源：http://dali.zhengqikj.top/Article/details/gtpraqebzp.html

{ ...a, ...b }
来源：http://dali.nanxinkj.top/Article/details/gtsufqfavj.html

[U89] JS：数组去重
来源：http://dali.hnxiangtu.top/Article/details/gtiuwqcpmu.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtqoivtrzd.html

[U90] JS：数字数组排序
来源：http://dali.tanke756.top/Article/details/gtytaahddr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtdedcjlpp.html

[U91] JS：对象键值遍历
来源：http://dali.daxiang520.top/Article/details/gttqaeohze.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigufen.top/Article/details/gtxtlvfgnf.html

[U92] JS：深拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtgwenksbr.html

structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtjoejtcui.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gtbhzmafkd.html

`共 ${n} 条`
来源：http://dali.fzhhl.top/Article/details/gtdybfconc.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtdbrclzhz.html

const double = x => x * 2;
来源：http://dali.xylfe.cn/Article/details/gtwtmoxjbw.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gtaszhxvow.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gtzuefbhdz.html

[U96] JS：async/await 与异常
来源：http://dali.9152youxi.cn/Article/details/gtwrloeuur.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gttmiawbji.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gtyhwqpoxv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtcjgijfno.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gtkntlpoyz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ydzc1.top/Article/details/gtdlweojsh.html

[U99] JS：事件监听
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcaahjyd.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gtffrgtvhb.html

[U100] JS：DOM 查询
来源：http://dali.cqqwz.cn/Article/details/gtcdvhkqog.html

document.querySelector(".item")
来源：http://dali.havefunace.top/Article/details/gtjdhacvvt.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gtmhyopimp.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gtytgyezdn.html

[U102] JS：本地存储
来源：http://dali.chenzaomai.com/Article/details/gtifhymfop.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtkpekfioh.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gtpqysbckc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gtbhowcfrc.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtaqmnlsgg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtuxajkshn.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gtpuvfnnaz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258.top/Article/details/gthbewdkbw.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtrxetpubd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gtydogolhq.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtygllscwm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtppfbobsa.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtritepfrs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daria6918.cn/Article/details/gtbdfpdwbz.html

[U109] JS：数组分组
来源：http://dali.nanxuanxn.top/Article/details/gtsecrzopl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtlgcqqhhv.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gtpenzrprk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.smart0.xyz/Article/details/gtdjucfzzx.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gtqnxyhcgo.html

new Map(Object.entries(obj))
来源：http://dali.316326.xyz/Article/details/gtjjwralwm.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gtpbjlhnbb.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtkktbhovr.html

[U113] JS：正则替换全部
来源：http://dali.jqgufenzy.top/Article/details/gtxvdugboz.html

s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gteahzferg.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gthhrooxmk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtvektykxv.html

[U115] JS：生成 UUID
来源：http://dali.yonumen.top/Article/details/gtzfrokobs.html

crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtkkyqffgr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gtrbhmdgui.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgmrnryst.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtchpaejfk.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gtjibeupvc.html

[U118] JS：开发服务器
来源：http://dali.zhengqikj.top/Article/details/gtjynbvmwz.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gtrfugozrr.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gtnfdiisws.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gtolkptlgf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gtcvizmwnq.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gtcgvytsbh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpmftkima.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gthihyhlkn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtljjzveky.html

按语言统计（条）：
来源：http://dali.ivvv.top/Article/details/gtfikyozor.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gtvgjkffyg.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gtocgdvime.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtzcbcdesm.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gttlafuwxl.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gthgicznwh.html

Go ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtoszkrqgy.html

Ruby ........... 212
来源：http://dali.daria6918.cn/Article/details/gtkjwkyzna.html

C# ............. 212
来源：http://dali.cashguo.top/Article/details/gtccbjgcou.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtvfpodtex.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gtbigqxjts.html

SQL ............ 90
来源：http://dali.chenzaomai.com/Article/details/gtbqblaltt.html

Bash ........... 80
来源：http://dali.jqgfzy.top/Article/details/gtjdbuqdqb.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gtapnuhnjk.html

Swift .......... 15
来源：http://dali.jianghu66.top/Article/details/gtzoaocwhh.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhrreato.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gtikmtqrlf.html

Scala .......... 10
来源：http://dali.aizwys.cn/Article/details/gtlmacvglc.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gturflqyxo.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gtoazidfjo.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gtffabibrc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gtxpslimqm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtvmwrgeeh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtlutqipmc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtzgcevudq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gtjewsvkfv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gtloacqwsf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtfhrltoec.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gtsmkafbbm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtiqnunkzs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gtgmcjskus.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtteyrxmtf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtvfsblrws.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtkncgghck.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtclkmrmoa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gtyotanetd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtfyisfqhe.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gtluviorwa.html

R Bash 专题                             80
来源：http://dali.yj20258.top/Article/details/gtpjgwqitf.html

S C / C++ 专题                          60
来源：http://dali.cucudq.cn/Article/details/gtoupeexjs.html

T 其他语言补充                          60
来源：http://dali.ybcxt.top/Article/details/gtxmnmwuoy.html

U 高频实用片段                         120
来源：http://dali.shangyingyoupin.top/Article/details/gtlnhwjgly.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtqwffwnqs.html

合计                                  2106 条
来源：http://dali.gogol.net.cn/Article/details/gttnsazrmy.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtdttoosrc.html

使用提醒
来源：http://dali.gogol.net.cn/Article/details/gtueowxqqw.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtxpljxetl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jiagoushi.top/Article/details/gtvsusdajb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gtiplmmyka.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gtxboqqhzj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yangfankeji.com/Article/details/gtkbfflhru.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cqqwz.cn/Article/details/gtbcipxosf.html

—— 文件结束 ——
来源：http://dali.chenzaomai.com/Article/details/gtpnspglor.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhvuraqw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gturwlljsg.html

Common Programming Examples Cheat Book
来源：http://dali.c1oappe.top/Article/details/gtabdqrhym.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwzqhhepw.html

【收录内容】
来源：http://dali.sweek.top/Article/details/gtmsrjlazg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sysykeji.top/Article/details/gtzfazjbbp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jiagoushi.top/Article/details/gtepsfuqjc.html

SQL · Bash · C · C++
来源：http://dali.hnxiangtu.top/Article/details/gttvjgflzy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.vqdsnc.cn/Article/details/gtvsmcrltc.html

【使用说明】
来源：http://dali.zhongyouzk.top/Article/details/gtcsqddgvk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gthcciyxhb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tianlin.xyz/Article/details/gtewyrwnoa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ehwqpu.com/Article/details/gtsaosasav.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.quarkkingdee.top/Article/details/gttgqtxgdz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gtruagfbik.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gtnicuawad.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.kuanghao11.cn/Article/details/gtweeupnvv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gtadhdiglg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.c1oappe.top/Article/details/gtdkojonhi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuanzx.com/Article/details/gtqeiojwmp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhiwuduotai.top/Article/details/gthtnaekun.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gtmsfjwpsz.html

【文件统计】
来源：http://dali.hnqzz.top/Article/details/gtnfpgdeud.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gzhubu.top/Article/details/gthsvjslgx.html


<!-- 参考信息 -->