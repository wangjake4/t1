代发 wailian999

[T49] Perl：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtktrhyope.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtiknpehlb.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtrlksyifl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gtqxwgklba.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gthvvicrch.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gtxmisbwby.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtgliotgpr.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gtwnhgtssr.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtbvlqsqtl.html

[T53] Scala：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtrlzngwbd.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gthliqijbm.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtcrhlmkuv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gtpsekxezu.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gthklzgmua.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtztyeznvo.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtxfwrrkvl.html

case class User(name: String, age: Int)
来源：http://dali.yj20258.top/Article/details/gtjwifxqas.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtapyasqbb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtwmuztfxv.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtfixlbwjk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtdhkhmhdc.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gtypidbole.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtufgevcye.html

[T60] Scala：折叠
来源：http://dali.snrcjt.cn/Article/details/gtkjeaermf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yanxiufei.cn/Article/details/gtfpvpmnjz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqrfxqdpm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtiqpdhioc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxminolig.html

[U01] Py：创建虚拟环境
来源：http://dali.haohaochexian.top/Article/details/gttyehepof.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gtqgaqeewy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoxxekbu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gtxzhhlrcc.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtezqzgdzx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtqpxybseg.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gtyoedsfjt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtvlxljqjw.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gtmcofkxir.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtubjqwima.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gtauyhlkbp.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gteugueaov.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gtkewjptga.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gttrfrfjgz.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtdtgolxzf.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gtmrlbctmf.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtivfmnjhv.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtbuqiirro.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtrhgrkhnn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsrkrgww.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gtxnxwdapw.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtycvaevhb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nwbrower.top/Article/details/gtxtjfjtda.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gtbjcbsien.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gttjahvfji.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gtjcmtfeqa.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gtoxhzkjhl.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gtxdoabguf.html

[U15] Py：高精度计时
来源：http://dali.fzhhl.top/Article/details/gtedrqhctu.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtabytdowx.html

[U16] Py：命令行参数解析
来源：http://dali.fzhhl.top/Article/details/gtbpekospo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gtodsawcti.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gtdaewijdq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cucudq.cn/Article/details/gtiuhqdavr.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtdkvxifne.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllzyynif.html

[U19] Py：正则替换带回调
来源：http://dali.gzhubu.top/Article/details/gtpyixkgel.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtfgugwnru.html

[U20] Py：缓存函数结果
来源：http://dali.zycfv.cn/Article/details/gteottwjjv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gtwhnrtyqa.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtzzsklrio.html

@contextlib.contextmanager
来源：http://dali.c1oappe.top/Article/details/gtvhkdhrsj.html

[U22] Py：矩阵转置
来源：http://dali.hammf.cn/Article/details/gtsbasgaaz.html

list(zip(*m))
来源：http://dali.havefunace.top/Article/details/gtssrlfrdq.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtzmaegbot.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtxrmumshn.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtqhtmzaga.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtufzicucj.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gteyssyyeu.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtneymsxcx.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gtswgbcwbj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtlvbajnbx.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvzfisrh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gtnccfddly.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gtaiqhstqi.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gtfpmiygbv.html

[U29] Py：属性校验
来源：http://dali.zycfv.cn/Article/details/gtqpibyklh.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gtxunzcwik.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtuefebsyt.html

@dataclass(slots=True)
来源：http://dali.nanxinkj.top/Article/details/gtcrdvpjhz.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gtgoqpmvcl.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gtjsfnrjpg.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gtakfwjmgl.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gtxppccbot.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gtkzohqrbt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlynoqfhz.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gtdwmfmtlj.html

chardet.detect(raw)
来源：http://dali.bjfxy.top/Article/details/gtjmpifddo.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtxaaddtra.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhixingplan.top/Article/details/gtmvqlvjfn.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtpgozhdmx.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtzddhmlrv.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gtqymmojym.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hammf.cn/Article/details/gtwccqqihc.html

[U38] Py：获取脚本所在目录
来源：http://dali.jlsjyb.cn/Article/details/gtxhxrmrmi.html

Path(__file__).resolve().parent
来源：http://dali.svipenyu.cn/Article/details/gtjkevfpvp.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gtnkrzdofa.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gttyarenna.html

[U40] Py：打印到标准错误
来源：http://dali.guowangkeji.top/Article/details/gtzcvpqpvf.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqvvyzam.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangtech.top/Article/details/gtydalkssx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gtonagkexa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gthotykwdl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gthvyeqlyg.html

[U43] PHP：声明命名空间
来源：http://dali.daxiang520.top/Article/details/gtpkflcvtt.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtdxwqufph.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gtorxaldzm.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gtahlucica.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtyeunrgjv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtdrwpritj.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gtamobrwkj.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gtuegpwtun.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gtrmgnzapt.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gtrlosxjxh.html

[U48] PHP：纯枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtfdbpvpyl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gtlsgxfjwz.html

[U49] PHP：只读属性
来源：http://dali.jiagoushi.top/Article/details/gtixnjpxzb.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gtjcccfqhc.html

[U50] PHP：构造器属性提升
来源：http://dali.nwbrower.top/Article/details/gtcriqrbug.html

public function __construct(private int $id) {}
来源：http://dali.zhongyouzk.top/Article/details/gtiobowzzt.html

[U51] PHP：数组解构
来源：http://dali.jlsjyb.cn/Article/details/gtbmfdposw.html

[$a, $b] = $arr;
来源：http://dali.haohaochexian.top/Article/details/gtckbmvflz.html

[U52] PHP：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gtuodivgws.html

$double = fn($x) => $x * 2;
来源：http://dali.zhengqikj.top/Article/details/gtcrfyfqvz.html

[U53] PHP：空合并运算符
来源：http://dali.hnxiangtu.top/Article/details/gtjjpskuhy.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenlongwang.top/Article/details/gtiimjihpz.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gtjhyvexgl.html

$obj?->method()
来源：http://dali.xylfe.cn/Article/details/gtrqlzerln.html

[U55] PHP：match 表达式
来源：http://dali.tianlin.xyz/Article/details/gtwidxgpmo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolgseyzk.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gtyvwrzvsv.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtqagysuxc.html

[U57] PHP：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtndluhmxc.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gtmhievpao.html

[U58] PHP：数组三件套
来源：http://dali.fengsongda.top/Article/details/gtqkujualg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gtjgjhyjzr.html

[U59] PHP：自定义排序
来源：http://dali.gotoacloud.top/Article/details/gtkqosyejl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtevpzivoi.html

[U60] PHP：JSON 编解码
来源：http://dali.hnqzz.top/Article/details/gtiosiejfk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aizwys.cn/Article/details/gtbujeurfr.html

[U61] PHP：正则
来源：http://dali.cashguo.top/Article/details/gtcxoypaav.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtcqfbwxmc.html

[U62] PHP：日期对象
来源：http://dali.zdqjudy.top/Article/details/gtslncshhp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenjidiqi.icu/Article/details/gtwkietwoi.html

[U63] PHP：文件读写
来源：http://dali.nanxuanxn.top/Article/details/gtklgyquaz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gtjbqmdqmx.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gtensjccxf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtbxjrcxrc.html

[U65] PHP：会话
来源：http://dali.xinyue.icu/Article/details/gtxvdymuih.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtdnnnkrve.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxinkj.top/Article/details/gtuhopvlpi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gotoacloud.top/Article/details/gtedkpdpql.html

[U67] PHP：处理文件上传
来源：http://dali.cucudq.cn/Article/details/gtgynwicqw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dashuyun.cn/Article/details/gtsgxecyun.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gtzocvoggz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gthgzezfqn.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gtgabrftlx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tianlin.xyz/Article/details/gtmbepwkdg.html

[U70] PHP：PDO 事务
来源：http://dali.jqgufenzy.top/Article/details/gttopxmmhv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.redwolf501.top/Article/details/gteovlrwjw.html

[U71] PHP：抛出异常
来源：http://dali.sxryk.cn/Article/details/gtythnvsox.html

throw new RuntimeException("失败", 500);
来源：http://dali.hysaishi.cn/Article/details/gtchkgedsi.html

[U72] PHP：写错误日志
来源：http://dali.aizwys.cn/Article/details/gtfdvjdzuy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shangyingyoupin.top/Article/details/gtagzaanqg.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtmtvbgnek.html

parse_ini_file("config.ini", true)
来源：http://dali.yueranfly.top/Article/details/gtsqqtpxrf.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gthzacwayu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gtcwilguql.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gtpxtghxpq.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhkeogwq.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtxvrzltfg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gtwimpmkbx.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gtlsyaptzs.html

composer require twig/twig
来源：http://dali.yueranfly.top/Article/details/gtaweuppzm.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmycpddx.html

composer require --dev phpunit/phpunit
来源：http://dali.hywenlv.cn/Article/details/gtgyjwnabj.html

[U79] PHP：静态分析
来源：http://dali.iojbl.cn/Article/details/gttveehgjf.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gtzoxtiglz.html

[U80] PHP：代码规范修复
来源：http://dali.pengpengdd.cyou/Article/details/gtsfnkbkxo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.svipenyu.cn/Article/details/gtaeucciro.html

[U81] JS：初始化项目
来源：http://dali.xylfe.cn/Article/details/gtvcegprbz.html

npm init -y;  npm i express
来源：http://dali.xuetiantiany.cn/Article/details/gtxlnumtsn.html

[U82] JS：package.json 脚本
来源：http://dali.hammf.cn/Article/details/gtbaqplzzi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gtjeispbqn.html

[U83] JS：ES Module 导入导出
来源：http://dali.daxiang520.top/Article/details/gtldwltjcg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtecjbhdgo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirmitpmf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shuidangran.top/Article/details/gtpldiahwh.html

[U85] JS：可选链
来源：http://dali.svipenyu.cn/Article/details/gtifplykcl.html

a?.b?.c
来源：http://dali.aizwys.cn/Article/details/gthbahikcm.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gtywleiwsi.html

a ?? b
来源：http://dali.daria6918.cn/Article/details/gtmqvqptxt.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gtqkigzbfb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jyoumei.cn/Article/details/gtvbddysyi.html

[U88] JS：对象展开合并
来源：http://dali.yongpay.top/Article/details/gtuqzxcjmr.html

{ ...a, ...b }
来源：http://dali.kuanghao11.cn/Article/details/gtyrfruztu.html

[U89] JS：数组去重
来源：http://dali.jqgufenzy.top/Article/details/gtfwtolojr.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtyowheoda.html

[U90] JS：数字数组排序
来源：http://dali.wangdashe.top/Article/details/gtknaxehyo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtbakjmykb.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gtcrvkdbtv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnqzz.top/Article/details/gtmbsgftgu.html

[U92] JS：深拷贝
来源：http://dali.yj20258.top/Article/details/gtqumdjywz.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtsbnesotm.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnabhpqt.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gtmivxhqqs.html

[U94] JS：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtimfqqeur.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtubkgilbz.html

[U95] JS：Promise 包装
来源：http://dali.dashuyun.cn/Article/details/gtvpwjjgno.html

new Promise((resolve, reject) => {})
来源：http://dali.cqqwz.cn/Article/details/gtwzhhupkl.html

[U96] JS：async/await 与异常
来源：http://dali.dianchejie.cn/Article/details/gtiylpfhgl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhtdlfqi.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gttrjdspdr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtwmgjktno.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gtxahjjdfo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.vqdsnc.cn/Article/details/gtzgvzdcmj.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtuolmiuau.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvhkqwqu.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtrhmynhbn.html

document.querySelector(".item")
来源：http://dali.dashuyun.cn/Article/details/gtqwbxumuw.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gtsfhmpwpv.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gtztqeyyyq.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gtmaredzsp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gtfbzodpcw.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gtwledxbkc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuetiantiany.cn/Article/details/gtrrmjtcxc.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gtgbzxpnfy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtizhufwxi.html

[U105] JS：节流
来源：http://dali.yuanzhike.top/Article/details/gtxhthhldz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gtyumaosyg.html

[U106] JS：日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtrrhhivca.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gtptzizkwr.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtkyyfxfcs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtpeguzsec.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gtvmdbxutl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtvjkfqoqk.html

[U109] JS：数组分组
来源：http://dali.wangshuangyany.cn/Article/details/gtildrkzsi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gtyuyyovaq.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gtuzmqhjnq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gttiktmzlu.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gtppvvrgbm.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtsrpaanyw.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gtvkogghax.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtbztneeoq.html

[U113] JS：正则替换全部
来源：http://dali.316326.xyz/Article/details/gtjzhwozsn.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtfcujepsl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gtytfoyuss.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtxitabvrs.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtaipjjoar.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtrckimlug.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtkjfjfcfr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gtkxjjuwck.html

[U117] JS：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtdtfvsikp.html

npm i -D vitest;  npx vitest
来源：http://dali.0kj1m.cn/Article/details/gtugblsaqc.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gtaakibwnd.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gtakhcktfy.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtwdrnudlg.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gtdrxrtrbe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gttiawghrh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gtuqlohkpq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrsphaznj.html

统计汇总
来源：http://dali.cucudq.cn/Article/details/gthgodxdgw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtuknpbebq.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gturljcbja.html

Python ......... 252
来源：http://dali.guowangkeji.top/Article/details/gtoctdcjkm.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gtbnjfdxcu.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtotxlywtu.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gtoxlciwdi.html

Java ........... 212
来源：http://dali.xylfe.cn/Article/details/gtdylwdvwa.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtxrypwoic.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtbottsshh.html

C# ............. 212
来源：http://dali.havefunace.top/Article/details/gtmyfrqbbz.html

C .............. 30
来源：http://dali.daria6918.cn/Article/details/gtpjatfilh.html

C++ ............ 30
来源：http://dali.sweek.top/Article/details/gtrczuxvcl.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gtdlgpovac.html

Bash ........... 80
来源：http://dali.meibo888.top/Article/details/gtbgousbfg.html

Kotlin ......... 15
来源：http://dali.jyoumei.cn/Article/details/gtgtlfpebh.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtfccnstzc.html

Lua ............ 10
来源：http://dali.tian-w.cn/Article/details/gtjymonzwp.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtsawzhsqa.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gtvkeplhhg.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtchkljiyo.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gtqxlawtfy.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtyfslenyz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gtbbjiishn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtszqpbkwk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtilotqvkp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtjtgyugda.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.meibo888.top/Article/details/gtcctlqvsk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gtevajurza.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtsmnzpfxe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtfuirzcqq.html


<!-- 参考信息 -->