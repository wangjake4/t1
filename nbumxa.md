代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gtzraqncsv.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gtlfiqwegu.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtbmhoqsap.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gtwgpeadfa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtiyezsmet.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzpcypvuq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtqpqjwoiq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtochjocrm.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtoocjxypr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gtpltayaqh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gtipsgxxpc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gtyqjuauzy.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtiyegynyn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gtckobuyxc.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvooelzm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldfwitqt.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gtxcyzfbiw.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtyvoashcp.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gtkiqvqitb.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gtkmtrgzxm.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gtprztzprx.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpbhmhff.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpyfxhsa.html

[y for x in nested for y in x]
来源：http://dali.xuanzx.com/Article/details/gtgzrqrxfg.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gtfrknxwsc.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtovneittb.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gtuqeoszvy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtadijabwa.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtkdcpnwft.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtequnfhfx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtahrmodnv.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtkstumllc.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtxwveoflh.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtfymwdrpj.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gtwhcqturv.html

defaultdict(list)
来源：http://dali.smart0.xyz/Article/details/gtqipawaav.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gtvugzgjuk.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtllwsnjjs.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtlosecbpz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gtmbggkuki.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gtpigjsobt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhiwuduotai.top/Article/details/gtqkqevavn.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gtburavrlq.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gtdlttblpv.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigufen.top/Article/details/gtlvnxiljw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gtrjrwmehg.html

[U20] Py：缓存函数结果
来源：http://dali.316326.xyz/Article/details/gtsymkkpii.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gtgrjpoqkv.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gtmwklpbgi.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gttwijhokv.html

[U22] Py：矩阵转置
来源：http://dali.yj20258888.top/Article/details/gtykhznfvp.html

list(zip(*m))
来源：http://dali.shanyushiyangtech.top/Article/details/gtaydsrkjt.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gtubuwtgst.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtshiidbmu.html

[U24] Py：路径操作
来源：http://dali.snrcjt.cn/Article/details/gtkryfxdtq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtdpiviygu.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gtinyarnhl.html

csv.DictReader(f)
来源：http://dali.hammf.cn/Article/details/gtpmfhunql.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccbnsmyw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gtwcsmylli.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtljpyxgpx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gtmzdhdsmu.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gtutitojdg.html

UserId = int
来源：http://dali.tianlin.xyz/Article/details/gtaxswnxey.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtzjhysxiv.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gtobezixsj.html

[U30] Py：数据类
来源：http://dali.yuanzhike.top/Article/details/gttjpdrgvx.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gtctojpujk.html

[U31] Py：单测
来源：http://dali.andypj.xyz/Article/details/gtktebpnje.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gtvtfjmyla.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtqzpmashy.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gtskrvrkun.html

[U33] Py：打包发布
来源：http://dali.haohaochexian.top/Article/details/gtxctuaebe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gtdpgedikh.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gtizoqyufg.html

chardet.detect(raw)
来源：http://dali.cheryme.top/Article/details/gtnavaaexe.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gtqcgckohu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gtvumuhnay.html

[U36] Py：定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtyfrhpxpz.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gtqtntgfjz.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtiakldbwz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gthjkpvohm.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gttabkdqll.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtuvltxcet.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gtifjapfrh.html

sys.stdout.isatty()
来源：http://dali.nwbrower.top/Article/details/gtsjhewarh.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gtayngdooz.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtsueiewzf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hammf.cn/Article/details/gtjonbdrmr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jiagoushi.top/Article/details/gtmsvcavgy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.9152youxi.cn/Article/details/gtpsqzjpzw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gzhubu.top/Article/details/gtytaefuls.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gtuxkyzzwd.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gtfrxdfwhv.html

[U44] PHP：开启严格类型
来源：http://dali.9152youxi.cn/Article/details/gttdywlgio.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssehyqvv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xylfe.cn/Article/details/gtmfowhiun.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtyxfrojyq.html

[U46] PHP：可空类型
来源：http://dali.ivvv.top/Article/details/gtxzbtiyyk.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gtdzsbdtps.html

[U47] PHP：联合类型
来源：http://dali.0kj1m.cn/Article/details/gtmhydwjnh.html

int|string $id
来源：http://dali.gogol.net.cn/Article/details/gtxfwywelc.html

[U48] PHP：纯枚举
来源：http://dali.jinqigfzy.top/Article/details/gtfuiecyox.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuxming.cn/Article/details/gtjvhcunlh.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkxmuqep.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gtzydwjgjw.html

[U50] PHP：构造器属性提升
来源：http://dali.gotoacloud.top/Article/details/gtubmgvfza.html

public function __construct(private int $id) {}
来源：http://dali.zdqjudy.top/Article/details/gtcsffghxk.html

[U51] PHP：数组解构
来源：http://dali.ppjwa.cn/Article/details/gtthvrzedt.html

[$a, $b] = $arr;
来源：http://dali.mhx1999.top/Article/details/gtvqpcxqag.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gtkbzupzsn.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtkfllcpjf.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gtxcucsurd.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gtwuuekktd.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gtrpnbddoh.html

$obj?->method()
来源：http://dali.haohaochexian.top/Article/details/gtpjgtnlrg.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtsfqyoyhz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.meibo888.top/Article/details/gtlfjiouda.html

[U56] PHP：命名参数
来源：http://dali.pycfn.com/Article/details/gtafifcxbr.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtqiykwsje.html

[U57] PHP：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtytgwezbv.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gtuuqskqic.html

[U58] PHP：数组三件套
来源：http://dali.jlsjyb.cn/Article/details/gtfrrywhld.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcdblkqh.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gtenuiijbi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtsabmibqm.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gtkuleyscy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gtqloqdpqb.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gtliuznqzt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtgfwbbind.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gtdlfkyuhh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtexmbgstq.html

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gtdbgnrwxo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduhmzvfj.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gtnmqdqrnl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigfzy.top/Article/details/gtokoephqw.html

[U65] PHP：会话
来源：http://dali.jianghu66.top/Article/details/gtjnmwltle.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtavmmfcav.html

[U66] PHP：设置 Cookie
来源：http://dali.jiagoushi.top/Article/details/gtnqxdxftl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtugorruez.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gtmqysncrl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gtdtywvfyp.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtbsxjwpjt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tanke756.top/Article/details/gtkybzlzbs.html

[U69] PHP：PDO 预处理
来源：http://dali.tianlin.xyz/Article/details/gtsrlhefac.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258888.top/Article/details/gtpngfzegx.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gtftrtnrwv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphkkucbn.html

[U71] PHP：抛出异常
来源：http://dali.ybcxt.top/Article/details/gtdupjpvgk.html

throw new RuntimeException("失败", 500);
来源：http://dali.dashuyun.cn/Article/details/gtcmhajafw.html

[U72] PHP：写错误日志
来源：http://dali.haohaochexian.top/Article/details/gtckhdixyi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gtoourqsgh.html

[U73] PHP：读取 ini 配置
来源：http://dali.andypj.xyz/Article/details/gtaobdhgkt.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtihrymmvy.html

[U74] PHP：读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtmrrluqxx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yonumen.top/Article/details/gtvxbecxhb.html

[U75] PHP：依赖注入
来源：http://dali.yueranfly.top/Article/details/gtnnnfhwxy.html

composer require psr/container
来源：http://dali.yanxiufei.cn/Article/details/gtmkuvumap.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gtbfavenmx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.snrcjt.cn/Article/details/gtpzmsyhlv.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gtmmtmhkmc.html

composer require twig/twig
来源：http://dali.cheryme.top/Article/details/gtvkwnalhg.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtsyoywuur.html

composer require --dev phpunit/phpunit
来源：http://dali.jinghuilouyu.cn/Article/details/gtncwhtewe.html

[U79] PHP：静态分析
来源：http://dali.jinghuilouyu.cn/Article/details/gtsboquxbv.html

composer require --dev phpstan/phpstan
来源：http://dali.iojbl.cn/Article/details/gtilgyidur.html

[U80] PHP：代码规范修复
来源：http://dali.pengpengdd.cyou/Article/details/gtmtuslpbe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hywenlv.cn/Article/details/gtabhsfueb.html

[U81] JS：初始化项目
来源：http://dali.gzhubu.top/Article/details/gtkbrmlnvj.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gtxnptlolu.html

[U82] JS：package.json 脚本
来源：http://dali.gotoacloud.top/Article/details/gtswupjvcf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gtwjbngnca.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuetiantiany.cn/Article/details/gtefrpsojg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtznjovaov.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gtnfyfdmum.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuetiantiany.cn/Article/details/gtevintzho.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gtqktdwima.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtoyschwbd.html

[U86] JS：空值合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvjhevql.html

a ?? b
来源：http://dali.wangdashe.top/Article/details/gtdlmaebwo.html

[U87] JS：解构默认值
来源：http://dali.jqgufenzy.top/Article/details/gtinpmbswj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gtdidsmesl.html

[U88] JS：对象展开合并
来源：http://dali.9152youxi.cn/Article/details/gtenavflbj.html

{ ...a, ...b }
来源：http://dali.nanxinkj.top/Article/details/gtjaoxngyh.html

[U89] JS：数组去重
来源：http://dali.birdmap.top/Article/details/gtkofkinev.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtlejbxjzi.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gtincbzemo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtazpofsca.html

[U91] JS：对象键值遍历
来源：http://dali.c1oappe.top/Article/details/gtoimyxfiv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigufen.top/Article/details/gtsqqbpwxm.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gtjmoalawh.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtpdenrwiu.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoyreebz.html

`共 ${n} 条`
来源：http://dali.hnxiangtu.top/Article/details/gtfubqxnmy.html

[U94] JS：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtysdruemu.html

const double = x => x * 2;
来源：http://dali.fzhhl.top/Article/details/gtebzckxjh.html

[U95] JS：Promise 包装
来源：http://dali.mhx1999.top/Article/details/gtyyqfcdso.html

new Promise((resolve, reject) => {})
来源：http://dali.meibo888.top/Article/details/gtberuqkqy.html

[U96] JS：async/await 与异常
来源：http://dali.316326.xyz/Article/details/gtqnytxtgn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtbrcilabm.html

[U97] JS：并发请求
来源：http://dali.jinqigufen.top/Article/details/gtusylkhbq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtgdcvkijb.html

[U98] JS：fetch 带 JSON
来源：http://dali.sxryk.cn/Article/details/gtzddakdki.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gtbbqysjjf.html

[U99] JS：事件监听
来源：http://dali.yangfankeji.com/Article/details/gteqysskra.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gthuxnirsm.html

[U100] JS：DOM 查询
来源：http://dali.quarkkingdee.top/Article/details/gtndwyleve.html

document.querySelector(".item")
来源：http://dali.yuxming.cn/Article/details/gtogduexzf.html

[U101] JS：classList 操作
来源：http://dali.tanke756.top/Article/details/gtyohwamkb.html

el.classList.toggle("active")
来源：http://dali.aizwys.cn/Article/details/gtrwxrgfts.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtritocwww.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hywenlv.cn/Article/details/gtitteotru.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gtfmrzebaz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgfzy.top/Article/details/gtxfqoppik.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gtzsxrrbvr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtnjvsnbpu.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gtccdkmifg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gtbuhsztsu.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtawgtakef.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gtbaestmno.html

[U107] JS：数字千分位
来源：http://dali.sysykeji.top/Article/details/gtmkdfyney.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtaixdqzoz.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gtrnpnycuk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gtlvrftcvg.html

[U109] JS：数组分组
来源：http://dali.hfpthk.cn/Article/details/gtgeogvmsg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtkefpkcjx.html

[U110] JS：数组分块
来源：http://dali.xuanzx.com/Article/details/gtpsdsnzwu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gtsqpjhscq.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtazdyzlnz.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gtgxdhsaqn.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gtaikvzxdc.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtemxexqel.html

[U113] JS：正则替换全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyqvvhwi.html

s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtgtmsossf.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gtsgcahjyr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtqjehybhd.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtdgrapcvs.html

crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtumjcytse.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gtgdvtgqix.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gtsofvwrcc.html

[U117] JS：单元测试
来源：http://dali.yonumen.top/Article/details/gtizjiedwh.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gtbgrsjzlz.html

[U118] JS：开发服务器
来源：http://dali.jqgufenzy.top/Article/details/gthmhrcbaq.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtyhjvgzzb.html

[U119] JS：生产构建
来源：http://dali.shzxlz.cn/Article/details/gtbzabitdv.html

npx vite build
来源：http://dali.ivvv.top/Article/details/gtsxpenvmp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtkdipjioj.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gthotieccj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvjmixblm.html

统计汇总
来源：http://dali.yuxming.cn/Article/details/gtsqtbcvoz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjlqakcdr.html

按语言统计（条）：
来源：http://dali.hywenlv.cn/Article/details/gtdmesfqua.html

Python ......... 252
来源：http://dali.zhiwuduotai.top/Article/details/gttltgbplz.html

PHP ............ 252
来源：http://dali.xinyue.icu/Article/details/gtksxczlpr.html

JavaScript ..... 252
来源：http://dali.jianghu66.top/Article/details/gtipdluutq.html

TypeScript ..... 212
来源：http://dali.sxryk.cn/Article/details/gtckcnvubl.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtbdaqfurb.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtcufmlxtu.html

Ruby ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogqxpuqx.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtagqgznvc.html

C .............. 30
来源：http://dali.svipenyu.cn/Article/details/gtxdbemmsn.html

C++ ............ 30
来源：http://dali.gotoacloud.top/Article/details/gtzzbcgybu.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtegfmczhv.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfmjwxqs.html

Kotlin ......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtmwpemhpj.html

Swift .......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaogstbq.html

Lua ............ 10
来源：http://dali.redwolf501.top/Article/details/gtmlmbidfa.html

Perl ........... 10
来源：http://dali.hammf.cn/Article/details/gtaikwekyz.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gtmcbbevri.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtqxmuguxq.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gtzumcakry.html

按章节统计：
来源：http://dali.xylfe.cn/Article/details/gtyzjztlzm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gtpkkettmu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtkvoxsvxn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtbgthlwhl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtkupeiuva.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenlongwang.top/Article/details/gtpcrkyyap.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtgnmmczhd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtajbjoroq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gtigsvdssz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtszmsucgk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtsxipubpw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtlgbphxwu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtxatqlpku.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtepedxqyn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gteoqtwhtx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gtpghorbev.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtcqwwelgm.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gtmjbfwqem.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gtkfokyzue.html

S C / C++ 专题                          60
来源：http://dali.jlsjyb.cn/Article/details/gtbjzttcyb.html

T 其他语言补充                          60
来源：http://dali.smart0.xyz/Article/details/gtzihskvvw.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gtrqjkavkp.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtnrxepntn.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gtgqczlbpm.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtlrqvptdv.html

使用提醒
来源：http://dali.jianghu66.top/Article/details/gtluhxqxxf.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtcqupsusb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangtech.top/Article/details/gtirdcmpra.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gtshftbztc.html


<!-- 参考信息 -->