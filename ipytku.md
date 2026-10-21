代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdusvufbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtssiqhaar.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtrfmyhmwr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtonativyy.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrabiath.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtapexnnsp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtmniweogz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtbaycbsxu.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gtvnhahhgl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtbwfamfzc.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmytlkct.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gtugnsvbhu.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gtaxizvyfx.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybwmalxh.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gtpenxnzin.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gtqvzngkjt.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtzpptrlqx.html

{v: k for k, v in d.items()}
来源：http://dali.9152youxi.cn/Article/details/gtizoekzjp.html

[U08] Py：展平二维列表
来源：http://dali.9152youxi.cn/Article/details/gtuaxrftnu.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gthuftfzqz.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtvqichwcv.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gtxiqzqawu.html

[U10] Py：按值排序字典
来源：http://dali.gaohongyu789.top/Article/details/gtmqxaujbu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtmsbpwvfp.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gtdfqfbzee.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtuvcuqqos.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gttellrnca.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gtwziikkcu.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacragzme.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtcfmnjflm.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gtpebxtxuj.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gtideuodma.html

[U15] Py：高精度计时
来源：http://dali.zdqjudy.top/Article/details/gtlypwgupj.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtvbygltcw.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtvplfawgi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqukscujy.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtyzzawjwj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtiupvqdjr.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gtzdrkgqbo.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gtxfivbvff.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gtylhmkmpv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtpjqisbvx.html

[U20] Py：缓存函数结果
来源：http://dali.chenlongwang.top/Article/details/gtmcpkrnje.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gtydobbaeo.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gtnzrpgkef.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtjuvsptqh.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gttrwtrjdb.html

list(zip(*m))
来源：http://dali.hywenlv.cn/Article/details/gthpkfnklw.html

[U23] Py：分块读取大文件
来源：http://dali.ppjwa.cn/Article/details/gtdojyqzbh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtcgnijouc.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gtkgjwgogd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfflkzgd.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtkpkwmpjf.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtcajpmwmd.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gtoefncmhi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtgulxyqvt.html

[U27] Py：异步 HTTP
来源：http://dali.yongpay.top/Article/details/gtmodyhrzq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gtvdwhoorh.html

[U28] Py：类型别名
来源：http://dali.chenzaomai.com/Article/details/gtdvivfbwm.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtyjrrsglk.html

[U29] Py：属性校验
来源：http://dali.ivvv.top/Article/details/gtjdetfege.html

@property 与 @x.setter 配合
来源：http://dali.hongshengwenyu.top/Article/details/gttehpwzii.html

[U30] Py：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtczexqnrp.html

@dataclass(slots=True)
来源：http://dali.mhx1999.top/Article/details/gtuyejllbg.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gtvmkuwxbn.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gthmbvzsse.html

[U32] Py：代码格式化
来源：http://dali.sysykeji.top/Article/details/gttzjlzawg.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gtnojlcekq.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gtshqvbvjg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtbleuoclf.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtxwdbrves.html

chardet.detect(raw)
来源：http://dali.hnqzz.top/Article/details/gtvsmnruhm.html

[U35] Py：发送邮件
来源：http://dali.yj20258.top/Article/details/gtwpagnara.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxofyrkcp.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gtitrokylp.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gthaxxemxh.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtqddmkzmc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gtddkusfra.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gttikqmtmx.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gtntmzduip.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtvatehwor.html

sys.stdout.isatty()
来源：http://dali.nanxinkj.top/Article/details/gtexenmwmz.html

[U40] Py：打印到标准错误
来源：http://dali.hywenlv.cn/Article/details/gtqpauawbt.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtxqfhgqeh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gtaepsnfwu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gzhubu.top/Article/details/gtsmqiyecp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zycfv.cn/Article/details/gtuwhnipjr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gtgrfkicao.html

[U43] PHP：声明命名空间
来源：http://dali.cheryme.top/Article/details/gtswqzzgdh.html

namespace App\Http;
来源：http://dali.havefunace.top/Article/details/gtjmiybiik.html

[U44] PHP：开启严格类型
来源：http://dali.cdnleiting.top/Article/details/gtmlwdkzpk.html

declare(strict_types=1);
来源：http://dali.yj202588.top/Article/details/gttlbbcfgj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gtlinyrazv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtwcekrsnl.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gtsnlydzts.html

?string $name = null
来源：http://dali.sysykeji.top/Article/details/gtpjiyxbng.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gttfllkucg.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gtwjqomeuk.html

[U48] PHP：纯枚举
来源：http://dali.ehwqpu.com/Article/details/gtygzwsiqz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gtdiexoooh.html

[U49] PHP：只读属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyrpbcud.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gtxfhckbqh.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gtzjddbkrr.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gtobmlaozw.html

[U51] PHP：数组解构
来源：http://dali.zycfv.cn/Article/details/gtdyqzhojo.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gtxvnlescq.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynxabuvf.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gtykbyibbh.html

[U53] PHP：空合并运算符
来源：http://dali.sysykeji.top/Article/details/gtpbbtiscr.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gtiyfzobgg.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gtugbvlfhr.html

$obj?->method()
来源：http://dali.guannengcc.top/Article/details/gteowtklsm.html

[U55] PHP：match 表达式
来源：http://dali.sysykeji.top/Article/details/gtsgzrbcox.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gtvbrtilnl.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gtckhvtvre.html

f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gttzyxnadl.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtwsuprapc.html

"值: {$a}"
来源：http://dali.andypj.xyz/Article/details/gtlihuegpo.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gtpkcskvae.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtncdvgqlc.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtwmruoxgf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gthywtyeto.html

[U60] PHP：JSON 编解码
来源：http://dali.yongpay.top/Article/details/gtyszwigrv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gtluwmstdn.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gtspfrxnmw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtqxgqvbkf.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gtyzhiuegf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ydzc1.top/Article/details/gtczhutxmu.html

[U63] PHP：文件读写
来源：http://dali.cqqwz.cn/Article/details/gtebvckrsz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkxjyyuv.html

[U64] PHP：目录遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaviftfzw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sweek.top/Article/details/gtlroceojr.html

[U65] PHP：会话
来源：http://dali.shuidangran.top/Article/details/gtmmovkvmg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.meibo888.top/Article/details/gtobnfnnia.html

[U66] PHP：设置 Cookie
来源：http://dali.redwolf501.top/Article/details/gtutfzkiro.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jlsjyb.cn/Article/details/gtvcvjgkoc.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangtech.top/Article/details/gtivvbsuwl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shzxlz.cn/Article/details/gthrknstmn.html

[U68] PHP：PDO 连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnttbxtpd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxuanxn.top/Article/details/gtkviofkbr.html

[U69] PHP：PDO 预处理
来源：http://dali.ybcxt.top/Article/details/gtcftgikhb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gtezzgvjda.html

[U70] PHP：PDO 事务
来源：http://dali.tian-w.cn/Article/details/gtcaavgpvn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gtlbdoygms.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gtkyakzdlb.html

throw new RuntimeException("失败", 500);
来源：http://dali.smart0.xyz/Article/details/gtqztgbktr.html

[U72] PHP：写错误日志
来源：http://dali.yonumen.top/Article/details/gtgtmojfex.html

error_log("失败: " . $e->getMessage());
来源：http://dali.iojbl.cn/Article/details/gtdsugtthk.html

[U73] PHP：读取 ini 配置
来源：http://dali.cheryme.top/Article/details/gtaocnctef.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gtbfrvfxfb.html

[U74] PHP：读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtytdztapm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gtntjvymtj.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gtjwkpnmiy.html

composer require psr/container
来源：http://dali.zdqjudy.top/Article/details/gtypwzsmwn.html

[U76] PHP：简单路由
来源：http://dali.meibo888.top/Article/details/gtffohhgea.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenlongwang.top/Article/details/gtwvajvabs.html

[U77] PHP：模板渲染
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptuwkupv.html

composer require twig/twig
来源：http://dali.yanxiufei.cn/Article/details/gtrxarrjfv.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gtjtfzgapy.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxinkj.top/Article/details/gtlbfpxscd.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gthsqfmwke.html

composer require --dev phpstan/phpstan
来源：http://dali.svipenyu.cn/Article/details/gtovwaiyfl.html

[U80] PHP：代码规范修复
来源：http://dali.birdmap.top/Article/details/gtwyofohtc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.andypj.xyz/Article/details/gtuvgerzkf.html

[U81] JS：初始化项目
来源：http://dali.yanxiufei.cn/Article/details/gtdtwxrhtx.html

npm init -y;  npm i express
来源：http://dali.kuanghao11.cn/Article/details/gtgwzthpvk.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfpodvmz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gtreemnvoo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhongyouzk.top/Article/details/gtjedxzuhc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtsjtvibqg.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtdmnehgyn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gthzxabznk.html

[U85] JS：可选链
来源：http://dali.ehwqpu.com/Article/details/gtartrwlxa.html

a?.b?.c
来源：http://dali.jinqigufen.top/Article/details/gtagmakgrl.html

[U86] JS：空值合并
来源：http://dali.gotoacloud.top/Article/details/gticqwfxan.html

a ?? b
来源：http://dali.aibaodan.cn/Article/details/gthmpvjfxm.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gtzkkinjhd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxuanxn.top/Article/details/gtbuuuqohx.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gtpoobgrqt.html

{ ...a, ...b }
来源：http://dali.jianghu66.top/Article/details/gtlkmopgkt.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gtlzyqbbif.html

[...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtbbslrcce.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gtykcascth.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtpdqacpwy.html

[U91] JS：对象键值遍历
来源：http://dali.jqgufenzy.top/Article/details/gtnsalltmk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gtyvzmqbce.html

[U92] JS：深拷贝
来源：http://dali.snrcjt.cn/Article/details/gtmwswlbox.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkxxnryxh.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrivtwoab.html

`共 ${n} 条`
来源：http://dali.hnqzz.top/Article/details/gtcfncboni.html

[U94] JS：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtkcowgagm.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gtnjqsuaby.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gtmzqhjkdg.html

new Promise((resolve, reject) => {})
来源：http://dali.zycfv.cn/Article/details/gtrubynpgs.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gtpgptwpcy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtyxgaldwf.html

[U97] JS：并发请求
来源：http://dali.daria6918.cn/Article/details/gtthavamyv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxpvxssp.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gtbtwgiwcs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhongyouzk.top/Article/details/gtiwuoqbex.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtjgyqlkrt.html

el.addEventListener("click", e => {})
来源：http://dali.tanke756.top/Article/details/gtuinqhuyy.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gtlszacgju.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gtgtvqdeus.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtjqwhlbma.html

el.classList.toggle("active")
来源：http://dali.fengsongda.top/Article/details/gtbwmcxaqt.html

[U102] JS：本地存储
来源：http://dali.feifeiyinyue.top/Article/details/gtigttxmpo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gzhubu.top/Article/details/gtxtsldyjh.html

[U103] JS：定时器
来源：http://dali.9152youxi.cn/Article/details/gtvdnonolr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gtacqttfuf.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gttvlteoxr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gthqluqhxn.html

[U105] JS：节流
来源：http://dali.yonumen.top/Article/details/gtksicwrmu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtxctdrgzx.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbjtaidw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sxryk.cn/Article/details/gtfnvbchzq.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtncpddppn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtnaouwjxn.html

[U108] JS：随机整数
来源：http://dali.hnqzz.top/Article/details/gtsuddynzz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guannengcc.top/Article/details/gtnktdlkqq.html

[U109] JS：数组分组
来源：http://dali.wangdashe.top/Article/details/gthcnubryv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgjadwho.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtshghxzgh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gtysbbczco.html

[U111] JS：对象转 Map
来源：http://dali.chenzaomai.com/Article/details/gtkgwnzvwn.html

new Map(Object.entries(obj))
来源：http://dali.yueranfly.top/Article/details/gtpuvhguuk.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gtpdkokcnn.html

"7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtexlnzagm.html

[U113] JS：正则替换全部
来源：http://dali.xuanzx.com/Article/details/gtzxwjmpgn.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtqzmhsvkh.html

[U114] JS：JSON 深比较
来源：http://dali.aizwys.cn/Article/details/gtapjfonzz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtryjkanny.html

[U115] JS：生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtsbrpyllu.html

crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtlwjzmlko.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj202588.top/Article/details/gtehgjqeia.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtexmjtjvi.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gtxwvqjdsa.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gtuysogapj.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gterbpawmn.html

npm i -D vite;  npx vite
来源：http://dali.jlsjyb.cn/Article/details/gthjgqsikl.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gtapeuqdme.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gtmwysxded.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtejubggul.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gtxeukokvh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvjuzkyxs.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gthityyxgx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtywodzjrl.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gtimaxgvkw.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtnibtvdtx.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gtpupubazw.html

JavaScript ..... 252
来源：http://dali.sysykeji.top/Article/details/gthoulgtxq.html

TypeScript ..... 212
来源：http://dali.feifeiyinyue.top/Article/details/gtlttevapq.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtmybvxmua.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gtqgoxhwga.html

Ruby ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtaxweztmq.html

C# ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtcskyszsr.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gtzwmzlugg.html

C++ ............ 30
来源：http://dali.smart0.xyz/Article/details/gtrarwsfec.html

SQL ............ 90
来源：http://dali.fengsongda.top/Article/details/gtwwimpngb.html

Bash ........... 80
来源：http://dali.chenjidiqi.icu/Article/details/gthqtcuaqn.html

Kotlin ......... 15
来源：http://dali.svipenyu.cn/Article/details/gtbqmahbjw.html

Swift .......... 15
来源：http://dali.tian-w.cn/Article/details/gtzlmhfahl.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gtvpzltpxf.html

Perl ........... 10
来源：http://dali.tianlin.xyz/Article/details/gtckstbsnh.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gtwpejeslw.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtwmgxcaej.html

合计 ........... 2106 条
来源：http://dali.gotoacloud.top/Article/details/gtqzisnsbk.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gtkwkmjlgr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtuqdgtbwy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtlyynxoek.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gtirgxnmlm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtnzkryppp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.andypj.xyz/Article/details/gtubsqrvkq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gtkfrjtljn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtzymlnvwj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtrvvducsk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtvyurarcj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gteclexlln.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gttfromtsp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtmmzcpnxm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtvxtltpjt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtpmftpfkj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gtqhyahepl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtmkpqkqjw.html

Q SQL 专题                              90
来源：http://dali.redwolf501.top/Article/details/gthjxjyzjc.html

R Bash 专题                             80
来源：http://dali.pycfn.com/Article/details/gttmnramou.html

S C / C++ 专题                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtmszazacy.html

T 其他语言补充                          60
来源：http://dali.bjfxy.top/Article/details/gtjqudjmbx.html

U 高频实用片段                         120
来源：http://dali.tianlin.xyz/Article/details/gtywsanbmd.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtjpgubxln.html

合计                                  2106 条
来源：http://dali.tian-w.cn/Article/details/gtlxmrjwty.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtvistqlrn.html

使用提醒
来源：http://dali.cashguo.top/Article/details/gtqqnarjnb.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gthigslnsw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.svipenyu.cn/Article/details/gtaeciyago.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigufen.top/Article/details/gtmrgyffdt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gtmeprbmpa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtclqadsvw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.havefunace.top/Article/details/gtyzdhszsc.html

—— 文件结束 ——
来源：http://dali.sxryk.cn/Article/details/gtrsnyvdem.html


<!-- 参考信息 -->