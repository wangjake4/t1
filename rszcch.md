代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gt2zvmhhknd.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2dxdrllsx.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gt2woirktot.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcwfatpz.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gt2nmpjfytf.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gt2iurxzmds.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gt2zwqzhzpf.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gt2vjttylxj.html

[U09] Py：字典取最大值的键
来源：http://dali.meibo888.top/Article/details/gt2akhlapmq.html

max(d, key=d.get)
来源：http://dali.yj20258888.top/Article/details/gt2qjhdvnbp.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gt2hhzzdmjq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gt2cibigotv.html

[U11] Py：生成器表达式
来源：http://dali.zhixingplan.top/Article/details/gt2xqoikorm.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gt2gkxswkbk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycmmarli.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gt2oaqlcpkr.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gt2wpcbpfxe.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujzmpqpt.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gt2hyowggzu.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gt2rellqnyp.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xssxytrm.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gt2qhzwnoyr.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gt2ilmcrjqh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gt2pbmuyoty.html

[U17] Py：初始化日志
来源：http://dali.nwbrower.top/Article/details/gt2xtnstwrg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tanke756.top/Article/details/gt2fiikergp.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gt2cieqcupm.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2jjmhvnhi.html

[U19] Py：正则替换带回调
来源：http://dali.chenzaomai.com/Article/details/gt2wnfbngtd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gt2silwirpn.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gt2ounpnuog.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gt2ppfjqihu.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gt2zmncmhwb.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gt2lotenxzv.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gt2vfmpoomi.html

list(zip(*m))
来源：http://dali.zdqjudy.top/Article/details/gt2tvgymxos.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gt2ldzycvyk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.316326.xyz/Article/details/gt2wqtlopfm.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gt2bjqhhzrd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gt2bxihpvqa.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2jpildbxk.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbbrgexf.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gt2ammmtypt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gt2ebiwqehh.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gt2ppvzwbzk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gt2rysoisck.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gt2ykkvwzfi.html

UserId = int
来源：http://dali.xylfe.cn/Article/details/gt2wwpraqcj.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gt2mjbruoxv.html

@property 与 @x.setter 配合
来源：http://dali.vqdsnc.cn/Article/details/gt2mljfycqc.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gt2lfflaxrl.html

@dataclass(slots=True)
来源：http://dali.hysaishi.cn/Article/details/gt2ckjiopoc.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gt2ixikpfll.html

python -m pytest -q
来源：http://dali.cashguo.top/Article/details/gt2qqccuaow.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gt2nhcundfx.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gt2awysmbza.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gt2gznqvcrc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tian-w.cn/Article/details/gt2otwsexud.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gt2bgvamwux.html

chardet.detect(raw)
来源：http://dali.quarkkingdee.top/Article/details/gt2chlmybyw.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gt2thuqhqaw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwgsiwed.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gt2cehipvvx.html

schedule.every(10).minutes.do(job)
来源：http://dali.meibo888.top/Article/details/gt2lzmkrked.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gt2ysegtlcy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gt2meqkxxos.html

[U38] Py：获取脚本所在目录
来源：http://dali.jlsjyb.cn/Article/details/gt2mpzwhsct.html

Path(__file__).resolve().parent
来源：http://dali.hysaishi.cn/Article/details/gt2cigdtrtf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhoulong.xyz/Article/details/gt2pvstjlea.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gt2jpfthlmz.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzkjorad.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2pnxhneqb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqiexyyz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhixingplan.top/Article/details/gt2virfryij.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gt2lamlouls.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gt2mroywrnk.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gt2eamevlgs.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gt2gckfmxqv.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gt2uokgfhey.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gt2tsdvhqsg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ffmyctzr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxncpine.html

[U46] PHP：可空类型
来源：http://dali.ehwqpu.com/Article/details/gt2dexzsjwb.html

?string $name = null
来源：http://dali.nanxuanxn.top/Article/details/gt2pwzudtje.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gt2pdyastty.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gt2avdazvsg.html

[U48] PHP：纯枚举
来源：http://dali.yuxming.cn/Article/details/gt2valfwouu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.316326.xyz/Article/details/gt2ftgvsveu.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gt2mclcopon.html

public readonly string $name
来源：http://dali.sweek.top/Article/details/gt2aegdjcrj.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gt2clyjiarp.html

public function __construct(private int $id) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ojwqxmkl.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gt2wvlifwnt.html

[$a, $b] = $arr;
来源：http://dali.9152youxi.cn/Article/details/gt2fanbnwbf.html

[U52] PHP：箭头函数
来源：http://dali.tanke756.top/Article/details/gt2zivbtjir.html

$double = fn($x) => $x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gt2mxyftodg.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gt2usicqqnq.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gt2sstdbjmn.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gt2shreueoo.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gt2lqxwvusp.html

[U55] PHP：match 表达式
来源：http://dali.meibo888.top/Article/details/gt2bwwgtnse.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.meibo888.top/Article/details/gt2ohyngfxq.html

[U56] PHP：命名参数
来源：http://dali.andypj.xyz/Article/details/gt2mbpjkwkz.html

f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2djussodq.html

[U57] PHP：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2pkkfekqs.html

"值: {$a}"
来源：http://dali.snrcjt.cn/Article/details/gt2nrxqkdka.html

[U58] PHP：数组三件套
来源：http://dali.quarkkingdee.top/Article/details/gt2kzgfskcd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.smart0.xyz/Article/details/gt2yuqmhtrb.html

[U59] PHP：自定义排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2fiyhkaid.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2fzmkmxis.html

[U60] PHP：JSON 编解码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdhblapp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gt2zrunviiz.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gt2wnwnrrdx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gt2bxrqwsdy.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gt2qjoehiqn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gt2pnpzornm.html

[U63] PHP：文件读写
来源：http://dali.ybcxt.top/Article/details/gt2hsfhyjfc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nwbrower.top/Article/details/gt2ujcdvyjx.html

[U64] PHP：目录遍历
来源：http://dali.redwolf501.top/Article/details/gt2trvcvuay.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gt2ncwsjibo.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpcxlevs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2jantndkv.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gt2vioetlxc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gt2fbpvunmk.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gt2btkhuegr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkwgxqgb.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gt2gsytpywe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gt2xcfcweeo.html

[U69] PHP：PDO 预处理
来源：http://dali.shzxlz.cn/Article/details/gt2mzjmmvwe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hysaishi.cn/Article/details/gt2xgqtcooc.html

[U70] PHP：PDO 事务
来源：http://dali.316326.xyz/Article/details/gt2lnbimebh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxinkj.top/Article/details/gt2jskydqzb.html

[U71] PHP：抛出异常
来源：http://dali.pycfn.com/Article/details/gt2yyjemyly.html

throw new RuntimeException("失败", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2tzznahzy.html

[U72] PHP：写错误日志
来源：http://dali.smart0.xyz/Article/details/gt2pqyinbuo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shzxlz.cn/Article/details/gt2hdvdmjej.html

[U73] PHP：读取 ini 配置
来源：http://dali.jyoumei.cn/Article/details/gt2iiwoklsz.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gt2mrbcunop.html

[U74] PHP：读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2glazexoh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zdqjudy.top/Article/details/gt2gtqqmtbr.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gt2zkurutzf.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gt2sxmblscu.html

[U76] PHP：简单路由
来源：http://dali.pycfn.com/Article/details/gt2jfrzyapq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chypivpv.html

[U77] PHP：模板渲染
来源：http://dali.kuanghao11.cn/Article/details/gt2qrwyhufw.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gt2gohqpzpd.html

[U78] PHP：单元测试
来源：http://dali.mhx1999.top/Article/details/gt2npghgcoo.html

composer require --dev phpunit/phpunit
来源：http://dali.quarkkingdee.top/Article/details/gt2ggacbtgr.html

[U79] PHP：静态分析
来源：http://dali.jqgufenzy.top/Article/details/gt2aisliytq.html

composer require --dev phpstan/phpstan
来源：http://dali.yongpay.top/Article/details/gt2yvnwoaht.html

[U80] PHP：代码规范修复
来源：http://dali.nanxinkj.top/Article/details/gt2kqelwrjs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gt2oqjqvkas.html

[U81] JS：初始化项目
来源：http://dali.316326.xyz/Article/details/gt2tfifbqun.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gt2ukwfpqwa.html

[U82] JS：package.json 脚本
来源：http://dali.xylfe.cn/Article/details/gt2gfxxuyds.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shzxlz.cn/Article/details/gt2jekxdcnl.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gt2pawulvww.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2xuhvqzjx.html

[U84] JS：CommonJS 写法
来源：http://dali.haohaochexian.top/Article/details/gt2elwecczn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yongpay.top/Article/details/gt2jccwkinx.html

[U85] JS：可选链
来源：http://dali.tian-w.cn/Article/details/gt2nckefggr.html

a?.b?.c
来源：http://dali.ivvv.top/Article/details/gt2jlfzisea.html

[U86] JS：空值合并
来源：http://dali.smart0.xyz/Article/details/gt2njsdtgiy.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gt2eplzcecq.html

[U87] JS：解构默认值
来源：http://dali.zycfv.cn/Article/details/gt2hntuyuhc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.smart0.xyz/Article/details/gt2ngjfzyjb.html

[U88] JS：对象展开合并
来源：http://dali.sweek.top/Article/details/gt2juqucpmy.html

{ ...a, ...b }
来源：http://dali.zdqjudy.top/Article/details/gt2cqdvxhgp.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gt2wpymhvks.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2txghigxe.html

[U90] JS：数字数组排序
来源：http://dali.cdnleiting.top/Article/details/gt2svnflqcl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2fakmavhp.html

[U91] JS：对象键值遍历
来源：http://dali.gogol.net.cn/Article/details/gt2wuomvavs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gt2mfeunzav.html

[U92] JS：深拷贝
来源：http://dali.birdmap.top/Article/details/gt2sakfyorm.html

structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2qtstggfk.html

[U93] JS：模板字符串
来源：http://dali.xinyue.icu/Article/details/gt2ttluupky.html

`共 ${n} 条`
来源：http://dali.jqgfzy.top/Article/details/gt2otyeofhf.html

[U94] JS：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gt2htvduxtz.html

const double = x => x * 2;
来源：http://dali.chenzaomai.com/Article/details/gt2avbetlvn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxcfdlp.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gt2cmwpkdhq.html

[U96] JS：async/await 与异常
来源：http://dali.sysykeji.top/Article/details/gt2noqwdair.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2jdesxxre.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gt2jrvixgck.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2pncosmdb.html

[U98] JS：fetch 带 JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2oxobzalw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wntzzawb.html

[U99] JS：事件监听
来源：http://dali.dianchejie.cn/Article/details/gt2axjhtotw.html

el.addEventListener("click", e => {})
来源：http://dali.gzhubu.top/Article/details/gt2ehjtykcp.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gt2fufqlbgo.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gt2mrgilonm.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gt2gfcgaiqc.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gt2zxekwnac.html

[U102] JS：本地存储
来源：http://dali.jinqigufen.top/Article/details/gt2ruzifegu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cqqwz.cn/Article/details/gt2qwewcvfu.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gt2juzjlocc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.kuanghao11.cn/Article/details/gt2djuagvzn.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gt2djutukxz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2csuprivo.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gt2kkjiswde.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dianchejie.cn/Article/details/gt2wweeurzq.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gt2mpjmriqv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gt2gwyxoloy.html

[U107] JS：数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyhlziwe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gt2nlsyrdkc.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2zlsijqwh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fzhhl.top/Article/details/gt2tvgrypbn.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gt2kbxafftt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unnwyomi.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gt2twtflrvy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gt2rpujkoxx.html

[U111] JS：对象转 Map
来源：http://dali.zhongyouzk.top/Article/details/gt2ezkmxiwx.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gt2tcfoenyj.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gt2bfenbqgr.html

"7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2guczmxwp.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gt2tnosaokj.html

s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2jfmryfjn.html

[U114] JS：JSON 深比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2elixsmjj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2sjcangsy.html

[U115] JS：生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2liuxoxtq.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2bmygczlm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgfzy.top/Article/details/gt2jwqcsrib.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gt2tizywrry.html

[U117] JS：单元测试
来源：http://dali.guowangkeji.top/Article/details/gt2zyrogdyw.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gt2xtnkfxtu.html

[U118] JS：开发服务器
来源：http://dali.ybcxt.top/Article/details/gt2jdbrcjfc.html

npm i -D vite;  npx vite
来源：http://dali.havefunace.top/Article/details/gt2jyibdiit.html

[U119] JS：生产构建
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktjtqafp.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gt2sgvqulrm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pycfn.com/Article/details/gt2afqfpimt.html

import.meta.env.VITE_API_URL
来源：http://dali.quarkkingdee.top/Article/details/gt2xzjghquu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2sbdinauy.html

统计汇总
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijnudniu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tfgcgiof.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gt2peqfqsyd.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gt2szqkfdty.html

PHP ............ 252
来源：http://dali.guowangkeji.top/Article/details/gt2ycwudbxb.html

JavaScript ..... 252
来源：http://dali.jlsjyb.cn/Article/details/gt2ouwefdnk.html

TypeScript ..... 212
来源：http://dali.yj202588.top/Article/details/gt2wckxbbxc.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2ionbqmnv.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2jarxfhgj.html

Ruby ........... 212
来源：http://dali.gotoacloud.top/Article/details/gt2spphbtjm.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2efbjkqtv.html

C .............. 30
来源：http://dali.ppjwa.cn/Article/details/gt2enhlrnpn.html

C++ ............ 30
来源：http://dali.nanxuanxn.top/Article/details/gt2nidifszo.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gt2yjophruj.html

Bash ........... 80
来源：http://dali.shuidangran.top/Article/details/gt2onacmfds.html

Kotlin ......... 15
来源：http://dali.vqdsnc.cn/Article/details/gt2libardws.html

Swift .......... 15
来源：http://dali.guowangkeji.top/Article/details/gt2wjlelrqc.html

Lua ............ 10
来源：http://dali.yj20258.top/Article/details/gt2ynlygbso.html

Perl ........... 10
来源：http://dali.gzhubu.top/Article/details/gt2lnzxzcir.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gt2sykplznv.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2jtjlvtjt.html

合计 ........... 2106 条
来源：http://dali.zhixingplan.top/Article/details/gt2qlkagjxx.html

按章节统计：
来源：http://dali.daria6918.cn/Article/details/gt2dykghlpy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.pengpengdd.cyou/Article/details/gt2agmrpgii.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2yfwlmpru.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2ahmwxrbo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gt2vwqfzbts.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gt2avpompha.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gt2txxdclrj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gt2wdemlbqk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gt2kztakvyh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2mrvhxhms.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gt2btxammfl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2ezrwueql.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2mzggsxkj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2cndzwpte.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2xojswnaa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jianghu66.top/Article/details/gt2yqnqxequ.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2arszdzyp.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gt2ufazqgnb.html

R Bash 专题                             80
来源：http://dali.yj20258.top/Article/details/gt2lcvhnwgm.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gt2dtruddfc.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gt2ilacfjbq.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gt2gxuxaauq.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2svdnmrlt.html

合计                                  2106 条
来源：http://dali.yj20258.top/Article/details/gt2ppvmcqye.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gt2npqwvjsu.html

使用提醒
来源：http://dali.xinyue.icu/Article/details/gt2kaqmgewp.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gt2guhklbwa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewpntvxg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gt2wnzjkakv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gogol.net.cn/Article/details/gt2xtxvqecd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.9152youxi.cn/Article/details/gt2rziwbqrc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenzaomai.com/Article/details/gt2ywddnzso.html

—— 文件结束 ——
来源：http://dali.hnqzz.top/Article/details/gt2yznejcdk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qurhfjcq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gt2aieeairf.html

Common Programming Examples Cheat Book
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdmmkoeu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ippktwuj.html

【收录内容】
来源：http://dali.hongshengwenyu.top/Article/details/gt2lexykgkp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fengsongda.top/Article/details/gt2scsvrvyc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gt2jneimngw.html

SQL · Bash · C · C++
来源：http://dali.gaohongyu789.top/Article/details/gt2cjzmdelr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulbgfqho.html

【使用说明】
来源：http://dali.pycfn.com/Article/details/gt2sucnqcyr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkabixpz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gt2mruydwsy.html


<!-- 参考信息 -->