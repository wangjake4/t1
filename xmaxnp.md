代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gtnhlttyah.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtrxmtovwa.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtonlirgca.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtapnonwxc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtdoijgegl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdcsjhylz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtmmycbegi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwaeepiym.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gtjpejjfqt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gtihznoeac.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtbsjazvum.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gthjtutfdi.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtshhriymx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gtrcolxedz.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gtxchqlzgh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gtdwtdezus.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtzbncfeqt.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtskleilwh.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtawbnsuxy.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gtmbwkzcat.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtgbdpbwwd.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gtrrwmsfgp.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycfvhxip.html

[y for x in nested for y in x]
来源：http://dali.jinqigufen.top/Article/details/gtyslacfol.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtlxxldrbm.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtctmflmuf.html

[U10] Py：按值排序字典
来源：http://dali.cashguo.top/Article/details/gtukktthvv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gtrojvzkvz.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtmjtjil.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gthmflqdvy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.havefunace.top/Article/details/gtbbxohycp.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtrvvzgjro.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtmeoxqhkq.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gtsqicoaya.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtyfjnkyma.html

defaultdict(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtmmwglpqj.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gtlyknujpe.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gthuljrhtv.html

[U16] Py：命令行参数解析
来源：http://dali.zhixingplan.top/Article/details/gtbllndvrn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pengpengdd.cyou/Article/details/gtcrxxhfdr.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gtepzipcwx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzercbgxb.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtxrwvjnhd.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gtegdmrttq.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gtjludoldi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xziqi.cn/Article/details/gtimwbugtq.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gtkabrdbyr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gtnlxoeelt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gtyrqsunim.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtrpzqwjzp.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gttvrduxab.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gtzulrgwwl.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtnxvinjxt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gtkuwemluy.html

[U24] Py：路径操作
来源：http://dali.jlsjyb.cn/Article/details/gtgyxmpxlz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtlxtyuwkd.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gttznyzhri.html

csv.DictReader(f)
来源：http://dali.hnqzz.top/Article/details/gtpaufuzgv.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gtitiambtc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtgjxxhxkd.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gtrznvjmsf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gttuxqbydn.html

[U28] Py：类型别名
来源：http://dali.shzxlz.cn/Article/details/gtylqvrmhr.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gtghjyudph.html

[U29] Py：属性校验
来源：http://dali.c1oappe.top/Article/details/gtmmbcbgop.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwxpjaiu.html

[U30] Py：数据类
来源：http://dali.andypj.xyz/Article/details/gthpgouach.html

@dataclass(slots=True)
来源：http://dali.haohaochexian.top/Article/details/gtolouftrz.html

[U31] Py：单测
来源：http://dali.feifeiyinyue.top/Article/details/gtbyiepnqb.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtafrxbcbc.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtadgqpvbr.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gtexvgzhsh.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gtqbksukif.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gtvdfrolpn.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gtcfbgyqrs.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gtfqahgwye.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gtenmfxtgr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gtgxvhsacz.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtiyatquny.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenzaomai.com/Article/details/gtafyhskwm.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtbzumfijs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xinyue.icu/Article/details/gtfvlapmhr.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenlongwang.top/Article/details/gtgurihucm.html

Path(__file__).resolve().parent
来源：http://dali.hongshengwenyu.top/Article/details/gtcbbcyalu.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtoopcmeag.html

sys.stdout.isatty()
来源：http://dali.wangshuangyany.cn/Article/details/gtmqprqtll.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtkvngqerg.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtxfgctblh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.vqdsnc.cn/Article/details/gtrpmfxxzb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gtaypcysbm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zdqjudy.top/Article/details/gttxgfldms.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hongshengwenyu.top/Article/details/gtlmvpdfvc.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gtkmxyznvy.html

namespace App\Http;
来源：http://dali.jinqigfzy.top/Article/details/gtdsacbawu.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtoylcqckd.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gtbhejocoi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gtlwjpdijc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtoecmwvlz.html

[U46] PHP：可空类型
来源：http://dali.jyoumei.cn/Article/details/gtpzkejbxp.html

?string $name = null
来源：http://dali.ydzc1.top/Article/details/gtxcmqchke.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtybjmtxta.html

int|string $id
来源：http://dali.chenzaomai.com/Article/details/gtnkffbwph.html

[U48] PHP：纯枚举
来源：http://dali.cashguo.top/Article/details/gtcbxshwpe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cheryme.top/Article/details/gtfxiauwmo.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtushhdeux.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtgslkxeay.html

[U50] PHP：构造器属性提升
来源：http://dali.yvedp.cn/Article/details/gtecsttzvp.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gtsthqbgyi.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gtdrfehlup.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gtgbnfeuaf.html

[U52] PHP：箭头函数
来源：http://dali.jqgfzy.top/Article/details/gttvsdivqa.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgsmxxoh.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtcfvqpvak.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gtdgsdzqcl.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gturcduwhi.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gtucrznrii.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtmuevcwiw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtguitswjd.html

[U56] PHP：命名参数
来源：http://dali.iojbl.cn/Article/details/gtyhryszpb.html

f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtbnwpqssf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtvqfspryf.html

"值: {$a}"
来源：http://dali.xuetiantiany.cn/Article/details/gtiprtzgme.html

[U58] PHP：数组三件套
来源：http://dali.birdmap.top/Article/details/gtafiojged.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtbosncqzv.html

[U59] PHP：自定义排序
来源：http://dali.0kj1m.cn/Article/details/gtdakfqcjv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtqgwgxlof.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gtzyqchovn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gtnqhkgjtv.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gttrsssugb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtrmalfdsv.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gtrgvkhaob.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.kuanghao11.cn/Article/details/gtducincrl.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gttdrpqife.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmfqcntc.html

[U64] PHP：目录遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgdumlbk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zdqjudy.top/Article/details/gthgbdetwi.html

[U65] PHP：会话
来源：http://dali.gzhubu.top/Article/details/gtkclweeng.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfjmqomw.html

[U66] PHP：设置 Cookie
来源：http://dali.birdmap.top/Article/details/gtspptmxlb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigufen.top/Article/details/gthfkslnle.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gtgyktpndj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtazbqgqtc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gtqaanrjgq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gtqvuauiqd.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gtadrfliog.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.iojbl.cn/Article/details/gtffwuscqc.html

[U70] PHP：PDO 事务
来源：http://dali.nwbrower.top/Article/details/gtsspcqapl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zycfv.cn/Article/details/gtejjhptqb.html

[U71] PHP：抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtoptaxeyu.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gtangpslll.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gttbavovfq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gtwrqncpxo.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuxming.cn/Article/details/gtssntsvhi.html

parse_ini_file("config.ini", true)
来源：http://dali.chenlongwang.top/Article/details/gtzxngcvbj.html

[U74] PHP：读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gtlttsplmz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.kuanghao11.cn/Article/details/gtrikbaeiy.html

[U75] PHP：依赖注入
来源：http://dali.jiagoushi.top/Article/details/gtrafczxks.html

composer require psr/container
来源：http://dali.guannengcc.top/Article/details/gtxnembovt.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttldqxlip.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpftijntb.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gtzncvatem.html

composer require twig/twig
来源：http://dali.yonumen.top/Article/details/gtmhcrywgk.html

[U78] PHP：单元测试
来源：http://dali.yj20258.top/Article/details/gtvtlhngoc.html

composer require --dev phpunit/phpunit
来源：http://dali.daxiang520.top/Article/details/gtinizdyzg.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gtcyjhxwcg.html

composer require --dev phpstan/phpstan
来源：http://dali.svipenyu.cn/Article/details/gtnseatuoz.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtviymcnud.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvhdnsco.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gtejauzaqx.html

npm init -y;  npm i express
来源：http://dali.kuanghao11.cn/Article/details/gtuebyyodp.html

[U82] JS：package.json 脚本
来源：http://dali.cashguo.top/Article/details/gtwlcfwyak.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guowangkeji.top/Article/details/gtuphtivdx.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtwynetvdk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunfrbexi.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gtdhsotynj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fzhhl.top/Article/details/gtdzowxses.html

[U85] JS：可选链
来源：http://dali.wangdashe.top/Article/details/gtncsxeznn.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gtvotsfwwd.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gtissktgfg.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gtdscpgonq.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtlhetviav.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj202588.top/Article/details/gtshztmwcv.html

[U88] JS：对象展开合并
来源：http://dali.wangshuangyany.cn/Article/details/gtvytrwytt.html

{ ...a, ...b }
来源：http://dali.jlsjyb.cn/Article/details/gtevetcmbl.html

[U89] JS：数组去重
来源：http://dali.gogol.net.cn/Article/details/gtnhtimidf.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gttuutcslq.html

[U90] JS：数字数组排序
来源：http://dali.sxryk.cn/Article/details/gtpaxkmsdl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtpenuxzxe.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gtzffohyzo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjudrssdm.html

[U92] JS：深拷贝
来源：http://dali.nwbrower.top/Article/details/gtaszsvlai.html

structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtyfbroaiy.html

[U93] JS：模板字符串
来源：http://dali.aizwys.cn/Article/details/gtzwwxhnku.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gttkvwnuex.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtcmdfhrtu.html

const double = x => x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtdacjpysc.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gtyaldxfiu.html

new Promise((resolve, reject) => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtkfkfjzcw.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gtfbgzqzon.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjtbmpboi.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwzkuwwt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtqumavjoy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gtklaxuraw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nwbrower.top/Article/details/gtrwpxgzpb.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gtjpauklhx.html

el.addEventListener("click", e => {})
来源：http://dali.gotoacloud.top/Article/details/gthgfpionb.html

[U100] JS：DOM 查询
来源：http://dali.gaohongyu789.top/Article/details/gtlslkazeb.html

document.querySelector(".item")
来源：http://dali.yuxming.cn/Article/details/gtusosblwr.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtyfgnzbes.html

el.classList.toggle("active")
来源：http://dali.jqgfzy.top/Article/details/gtfvsrwynf.html

[U102] JS：本地存储
来源：http://dali.shzxlz.cn/Article/details/gtxfsgovrj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yongpay.top/Article/details/gtthzwlrzn.html

[U103] JS：定时器
来源：http://dali.aizwys.cn/Article/details/gtlozeopgj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtgzqfmfks.html

[U104] JS：防抖
来源：http://dali.hywenlv.cn/Article/details/gtsgviycze.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtmgtdlgqi.html

[U105] JS：节流
来源：http://dali.hnxiangtu.top/Article/details/gtfqunjmnc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cdnleiting.top/Article/details/gtqbdfgmpc.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtyyidrtdc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtrlbaipwk.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtddchqskm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.mhx1999.top/Article/details/gttzpalzsg.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwptwgkv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.snrcjt.cn/Article/details/gtcqmrinqp.html

[U109] JS：数组分组
来源：http://dali.chenlongwang.top/Article/details/gttxlexkgv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtkctlzdyh.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gtipywafcc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gthdovucpn.html

[U111] JS：对象转 Map
来源：http://dali.tianlin.xyz/Article/details/gtuafsktiv.html

new Map(Object.entries(obj))
来源：http://dali.tian-w.cn/Article/details/gtqjvzupkb.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gtvmtdbktp.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtvckabupr.html

[U113] JS：正则替换全部
来源：http://dali.shzxlz.cn/Article/details/gtdqwcqfxi.html

s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gthnucpgcd.html

[U114] JS：JSON 深比较
来源：http://dali.zhiwuduotai.top/Article/details/gtjekggavv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtraswlqvq.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtdrqlsgsv.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtygqoxusg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yanxiufei.cn/Article/details/gtlhiwosfl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gtqxxmntja.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gtgcenoedu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gtowbnidlw.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gtpbcrmkig.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtonrkqqyi.html

[U119] JS：生产构建
来源：http://dali.nwbrower.top/Article/details/gtyvjzyhzr.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqifzijv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglwvxvvm.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gtukuteetc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtduvqmipc.html

统计汇总
来源：http://dali.wangshuangyany.cn/Article/details/gttdnzogxd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrjveeelg.html

按语言统计（条）：
来源：http://dali.jiagoushi.top/Article/details/gtonjdsdqs.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gtxnhstzff.html

PHP ............ 252
来源：http://dali.cdnleiting.top/Article/details/gtnudhztej.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gtqcfryvpp.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwfnlkuc.html

Java ........... 212
来源：http://dali.mhx1999.top/Article/details/gtrpchnfeq.html

Go ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtpqcrubcl.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtswdqmkas.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtiqrpxxew.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gtezrfxbnm.html

C++ ............ 30
来源：http://dali.nanxinkj.top/Article/details/gtkhknquqr.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gtaycflybk.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gtwojbwifi.html

Kotlin ......... 15
来源：http://dali.svipenyu.cn/Article/details/gtxvixsrtd.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gtzopyplte.html

Lua ............ 10
来源：http://dali.hammf.cn/Article/details/gtamntgpwc.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gtsbkiukiz.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtsyrugspe.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtlkzevxlk.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gtvrhqxlpp.html

按章节统计：
来源：http://dali.tian-w.cn/Article/details/gtxegxrybr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtpnytwyrh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtrajvwbpn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtegfuuydj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtrifqewsd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.meibo888.top/Article/details/gtfspwcxph.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtnhztbxaq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtrldlbhje.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtrtijupra.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtcxxmgqum.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtqynpsfwv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtaxfgvikb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gthkotzxwi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtyvckkurq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gtwidrsnyk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.316326.xyz/Article/details/gtqhurchib.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtxsmcmsde.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gtsgmuelmf.html

R Bash 专题                             80
来源：http://dali.ppjwa.cn/Article/details/gtigrbirnb.html

S C / C++ 专题                          60
来源：http://dali.chenzaomai.com/Article/details/gtefwodqmb.html

T 其他语言补充                          60
来源：http://dali.pengpengdd.cyou/Article/details/gthxwokjln.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtgfajfepd.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtlrylhxej.html

合计                                  2106 条
来源：http://dali.shzxlz.cn/Article/details/gtotnzvsxp.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtttlmxfrh.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gtrzfudzbb.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gttsqomxdz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aibaodan.cn/Article/details/gtdcysrxyx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtxgiqybnw.html


<!-- 参考信息 -->