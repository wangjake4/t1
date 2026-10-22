代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2ummbprnc.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gt2puysgihv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gt2lciyrrkm.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gt2vubuegky.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2udxxzgmc.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gt2xtbgqbgi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asjcfupv.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gt2zrexqkdd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gt2rscjfunc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2sjyeisxm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2isrgnkvk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jxgvmdqk.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gt2qqkjxxep.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gt2haoqqbdx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvflzpjv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gt2xubrlsoz.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gt2kamjingd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gt2ixaexkkj.html

[U04] Py：变量调试打印
来源：http://dali.chenlongwang.top/Article/details/gt2cdidponm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gt2broejlae.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gt2arqqndyq.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2fvtsyeay.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gt2eifvvszs.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gt2ipuyusum.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2rrkxhdqf.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssbjibxc.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gt2kcldqvgf.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gt2tchopscu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gt2zoqcourw.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gt2vnwddsqt.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gt2orgfaicp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gt2rvxarfkl.html

[U11] Py：生成器表达式
来源：http://dali.svipenyu.cn/Article/details/gt2czpbnrrl.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gt2qluynlju.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gt2lccqcktg.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gt2kmjrjcjj.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gt2kdpmglfp.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gt2sbrxaijs.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gt2delgkxxo.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gt2pqbwzzuk.html

[U15] Py：高精度计时
来源：http://dali.sysykeji.top/Article/details/gt2nbbmgnmg.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gt2tnptstrr.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gt2xuchehas.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gt2xjcebndf.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2griupqua.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gt2uwanqxpz.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjxerehg.html

pat = re.compile(r"\d+")
来源：http://dali.gotoacloud.top/Article/details/gt2ebakwiyd.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gt2eehrhrdx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gt2bazpsdfy.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gt2jnlvbrbf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gt2fdtbpqpd.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tykmbaid.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgjgtiuw.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gt2vykojoak.html

list(zip(*m))
来源：http://dali.meibo888.top/Article/details/gt2nmjolmut.html

[U23] Py：分块读取大文件
来源：http://dali.sysykeji.top/Article/details/gt2znamttwa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gt2bpfqswtx.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gt2ruhspxtd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2qesudoux.html

[U25] Py：CSV 按字典读
来源：http://dali.svipenyu.cn/Article/details/gt2lwvdrgmf.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgocxfaa.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gt2emnibkhh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuxming.cn/Article/details/gt2evpntymb.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gt2tmpwqumq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gt2izhbuipa.html

[U28] Py：类型别名
来源：http://dali.hnxiangtu.top/Article/details/gt2naxcxjcw.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvvufrqu.html

[U29] Py：属性校验
来源：http://dali.daxiang520.top/Article/details/gt2glczttxy.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gt2mhwnkoxe.html

[U30] Py：数据类
来源：http://dali.tian-w.cn/Article/details/gt2bkifgkbh.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gt2eyfzwipf.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gt2nvezjoei.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gt2zfdhoffd.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gt2jwemmwid.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gt2hrcnqzsz.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gt2yrxvnzxg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ppjwa.cn/Article/details/gt2jwbmcsdt.html

[U34] Py：判断编码
来源：http://dali.guowangkeji.top/Article/details/gt2wdgtlhvg.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gt2bcigvdjf.html

[U35] Py：发送邮件
来源：http://dali.zdqjudy.top/Article/details/gt2hdmvtmuf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gt2yrysnids.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gt2sxhnnywz.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gt2bfmbcddd.html

[U37] Py：读写 Excel
来源：http://dali.cucudq.cn/Article/details/gt2oconbwvg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gt2zsawtapf.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gt2mtyggkir.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tilfmepy.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gt2iugykexa.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gt2uowgqoai.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2whbnolhd.html

print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2inpnzazy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gt2ensshspu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gt2bgfpfjmo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aibaodan.cn/Article/details/gt2bqxwdzxb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ivvv.top/Article/details/gt2uakarqwy.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gt2ugginmdi.html

namespace App\Http;
来源：http://dali.redwolf501.top/Article/details/gt2bpudpebl.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gt2wweavrpy.html

declare(strict_types=1);
来源：http://dali.havefunace.top/Article/details/gt2kbbvpigl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gt2bdxhtfhx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2mukqpoal.html

[U46] PHP：可空类型
来源：http://dali.jyoumei.cn/Article/details/gt2urhsdqmu.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gt2iynrghmk.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwdoesgi.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gt2slxrqmbf.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2iaysgopv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gt2eaqucgvx.html

[U49] PHP：只读属性
来源：http://dali.tanke756.top/Article/details/gt2anzidepi.html

public readonly string $name
来源：http://dali.fengsongda.top/Article/details/gt2yfoqybgy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbwngrdw.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gt2chtrbrvc.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gt2qhnultve.html

[$a, $b] = $arr;
来源：http://dali.guowangkeji.top/Article/details/gt2rkamgabt.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gt2khrtarke.html

$double = fn($x) => $x * 2;
来源：http://dali.yuanzhike.top/Article/details/gt2zhcabygs.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gt2hlmofnhf.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangdashe.top/Article/details/gt2lqwhzbqc.html

[U54] PHP：空安全调用
来源：http://dali.ivvv.top/Article/details/gt2ruflsanp.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gt2hjacppom.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gt2bjuncsko.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ydzc1.top/Article/details/gt2vdoxwofk.html

[U56] PHP：命名参数
来源：http://dali.yangfankeji.com/Article/details/gt2qvveokmz.html

f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2ltofsrud.html

[U57] PHP：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2mawfbpkh.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gt2zljlzjby.html

[U58] PHP：数组三件套
来源：http://dali.sweek.top/Article/details/gt2qxafmebx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gt2dmkoiavc.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gt2yvxacwzk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gt2yrtpfxwz.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gt2rvbcvaep.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gt2ihncnyjr.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zabqoegf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2vffhgwhd.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gt2lkfcwpek.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gt2bbmqsyus.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gt2deuhrgbs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gt2vvpgkxqx.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2isutmhvb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258888.top/Article/details/gt2effuwpba.html

[U65] PHP：会话
来源：http://dali.zhengqikj.top/Article/details/gt2vhqjwapq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2nzgzlfqf.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gt2acqynqik.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aizwys.cn/Article/details/gt2tjyblgfl.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gt2dgqawhqo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gt2wwupmalo.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gt2musvzglu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzpnxlnj.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gt2dztaqczb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigufen.top/Article/details/gt2zunikwjt.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gt2eqlixzqg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xziqi.cn/Article/details/gt2yhjwazsy.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2ikxcoyzl.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2vwuuiayc.html

[U72] PHP：写错误日志
来源：http://dali.cdnleiting.top/Article/details/gt2hbmdwfxe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofmamqlw.html

[U73] PHP：读取 ini 配置
来源：http://dali.shuidangran.top/Article/details/gt2zlvulxff.html

parse_ini_file("config.ini", true)
来源：http://dali.daxiang520.top/Article/details/gt2waoxvffp.html

[U74] PHP：读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2uowmoysl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gt2fkvdveah.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gt2vfaxboby.html

composer require psr/container
来源：http://dali.zhengqikj.top/Article/details/gt2yobjddks.html

[U76] PHP：简单路由
来源：http://dali.yj20258888.top/Article/details/gt2opvpevyj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ppjwa.cn/Article/details/gt2nyitcehm.html

[U77] PHP：模板渲染
来源：http://dali.fzhhl.top/Article/details/gt2fuyameme.html

composer require twig/twig
来源：http://dali.bjfxy.top/Article/details/gt2sehdvumy.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gt2atforubl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhengqikj.top/Article/details/gt2fgowltuy.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gt2izcdwwvn.html

composer require --dev phpstan/phpstan
来源：http://dali.yvedp.cn/Article/details/gt2cfihxdcp.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gt2puvdsjdv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gt2fgvcpiqs.html

[U81] JS：初始化项目
来源：http://dali.yanxiufei.cn/Article/details/gt2zqfrvtxd.html

npm init -y;  npm i express
来源：http://dali.jinqigufen.top/Article/details/gt2zthktvvr.html

[U82] JS：package.json 脚本
来源：http://dali.yangfankeji.com/Article/details/gt2ywhniapv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gt2bvdqkdep.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gt2xqyxsekx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.birdmap.top/Article/details/gt2oefuhtru.html

[U84] JS：CommonJS 写法
来源：http://dali.tanke756.top/Article/details/gt2hfujfibn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ybcxt.top/Article/details/gt2iqaxbvby.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gt2akbtgnjr.html

a?.b?.c
来源：http://dali.zhoulong.xyz/Article/details/gt2xqqbsvwk.html

[U86] JS：空值合并
来源：http://dali.cqqwz.cn/Article/details/gt2oksptyet.html

a ?? b
来源：http://dali.pycfn.com/Article/details/gt2tltwdhwq.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gt2mrcthtdo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gt2sovbsktd.html

[U88] JS：对象展开合并
来源：http://dali.fengsongda.top/Article/details/gt2jseggegq.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfcgfhqj.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gt2gdopigad.html

[...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gt2thqmyafe.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gt2gdxhjvml.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2ymrbmjvq.html

[U91] JS：对象键值遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2annohqwd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.svipenyu.cn/Article/details/gt2glxbshvv.html

[U92] JS：深拷贝
来源：http://dali.cucudq.cn/Article/details/gt2cxrmlctw.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2abjnxhej.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aonhfwks.html

`共 ${n} 条`
来源：http://dali.tianlin.xyz/Article/details/gt2cnhmwltt.html

[U94] JS：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywqjckbb.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gt2blwjavns.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gt2njgowalh.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gt2pkfkyczo.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gt2embuxshm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2earrzszy.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gt2dwbppbtk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gt2drdpigje.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2kpyostaq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gt2qpjiljuy.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gt2laldshfc.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2swdvkqnb.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gt2rialbtix.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gt2wxmbqqvd.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gt2ioeuuhkm.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gt2kzomqohs.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gt2dmazaanx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gt2nsspvcxc.html

[U103] JS：定时器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vahzwqfl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sxryk.cn/Article/details/gt2sivudglp.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gt2kiuwehps.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2psubsveo.html

[U105] JS：节流
来源：http://dali.cucudq.cn/Article/details/gt2kdszqbbe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqjwcha.html

[U106] JS：日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2akunesyc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gt2lqgcurha.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gt2liuxucma.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gt2wudivauo.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gt2exybcbhv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gzhubu.top/Article/details/gt2krhzwtll.html

[U109] JS：数组分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2aakafjse.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gt2dcudskuc.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gt2slpjzmeg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gt2khlpkpyv.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gt2iehpyyeh.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gt2nbicbisx.html

[U112] JS：字符串补位
来源：http://dali.fengsongda.top/Article/details/gt2wgwqkzwr.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2qokgmhpd.html

[U113] JS：正则替换全部
来源：http://dali.xuanzx.com/Article/details/gt2vaaeuwpe.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2hpxoemsx.html

[U114] JS：JSON 深比较
来源：http://dali.jlsjyb.cn/Article/details/gt2sfvkhkfl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gt2usvvtwiu.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2dinzrdeh.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2zfgawods.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugzuqkii.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yvedp.cn/Article/details/gt2cswqfbvj.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjqihmbq.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gt2csgzewkz.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gt2qiusvqhk.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gt2kykwkxvc.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gt2cgxpffyy.html

npx vite build
来源：http://dali.c1oappe.top/Article/details/gt2znemlqlu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnvkolwr.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gt2cvgjerds.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2flkwmqbq.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gt2hjmhuxva.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2bymtmitk.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzittudv.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gt2azkvawsc.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gt2luymyfbb.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gt2jexkuqqe.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gt2dovbbjxx.html

Java ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvndkbms.html

Go ............. 212
来源：http://dali.yueranfly.top/Article/details/gt2iyqmtwzg.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gt2augtgsua.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmfbsygg.html

C .............. 30
来源：http://dali.cqqwz.cn/Article/details/gt2bxxvoplo.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhidzerb.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gt2dmnzblvk.html

Bash ........... 80
来源：http://dali.fengsongda.top/Article/details/gt2lhugdwmw.html

Kotlin ......... 15
来源：http://dali.snrcjt.cn/Article/details/gt2wigyplec.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gt2nlyvvqcs.html

Lua ............ 10
来源：http://dali.yongpay.top/Article/details/gt2godbwgsn.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gt2jgbspaqy.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gt2txqcinol.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2xmtuzzjh.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gt2xmcukpht.html

按章节统计：
来源：http://dali.yuanzhike.top/Article/details/gt2jfhmaula.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahxiivep.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2umrtsfam.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gt2wxgxkblr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gt2zegbjbjg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yanxiufei.cn/Article/details/gt2okjjixwx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzmlxrgr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzxccicv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gt2xtylgxuj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2eitgitjw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gt2gwfveprg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gt2cksuzskn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2uipfapfs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2srvnmdoz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gt2dsvdaarm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gt2qeliqcxv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtxylgrh.html

Q SQL 专题                              90
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oivgdgfo.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gt2exqypstn.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gt2zyqqblpt.html

T 其他语言补充                          60
来源：http://dali.jianghu66.top/Article/details/gt2fbgdmyyc.html

U 高频实用片段                         120
来源：http://dali.tian-w.cn/Article/details/gt2yvqkmlot.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2sbkrcuur.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gt2xcgwlwtt.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2otnvemxx.html


<!-- 参考信息 -->