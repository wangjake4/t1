代发 wailian999

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtiqgedhbo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtutnyyauk.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtuqsobtta.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gtulpvnrim.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlgwabity.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtnvtastag.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtthccftia.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gtiyofgsdi.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gtjbsyiajx.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gtcfpwqvhs.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtvlvexjuz.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtnmgwdxlf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gtkcpzuzfo.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtflnlfqcb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtbczrownn.html

[T56] Scala：样例类
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqejkqix.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtxotwqbyl.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtpezvkcsq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gtslydapjt.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gtepckcuhn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gtsmhhxnnr.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gtaysecxfn.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtllobizsd.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtydfccbss.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtpiikpsth.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtomqeyeut.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gtnycqfxul.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrwrgwedd.html

[U01] Py：创建虚拟环境
来源：http://dali.gotoacloud.top/Article/details/gtejwtfmnj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gtltmvhdfk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gtiponsunj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtbjlbyecx.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gtjgyxutxn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtrxejuudx.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtkbfnmevd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ybcxt.top/Article/details/gtioihviir.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gtebxiwwcq.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtkqhlrktb.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gtoukwygrc.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gttkablmmh.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gthkjquwbx.html

{v: k for k, v in d.items()}
来源：http://dali.gotoacloud.top/Article/details/gtyeikrggh.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtvysfiswl.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gtxjtpnupe.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gthrtbtafx.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtgbgcieis.html

[U10] Py：按值排序字典
来源：http://dali.jianghu66.top/Article/details/gtddryzdys.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtpqriopme.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gtzbtsvyfb.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtcxqipccr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhengqikj.top/Article/details/gttkifetbf.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gthsfofopi.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gtdnoihham.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gturnnvabw.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gtgxldhwmg.html

defaultdict(list)
来源：http://dali.zhoulong.xyz/Article/details/gtewbwikbn.html

[U15] Py：高精度计时
来源：http://dali.hnqzz.top/Article/details/gtqtbitatw.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gtrshyinoc.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxesninj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtslogfibm.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gtxiehqpfw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gtlaicrfst.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwshcwztq.html

pat = re.compile(r"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtikplhtsn.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gtsekynhub.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yongpay.top/Article/details/gtvdwvphnj.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gttpbzsvby.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gtxulndrne.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtizutccaq.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtelyqfjcl.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gtdxvhxgrc.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gtvdmpqvsw.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gtdcuvlxmb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtnmbldhmg.html

[U24] Py：路径操作
来源：http://dali.tian-w.cn/Article/details/gtqmjxmdue.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtitnsggaa.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gtgaxsgryy.html

csv.DictReader(f)
来源：http://dali.ybcxt.top/Article/details/gtablzylmw.html

[U26] Py：并发下载
来源：http://dali.cqqwz.cn/Article/details/gtzdtjcvau.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gtktxfrbjr.html

[U27] Py：异步 HTTP
来源：http://dali.hnxiangtu.top/Article/details/gtdvnmooio.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhiwuduotai.top/Article/details/gtymlthpjx.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gtfkeppcos.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gtoqvjkfud.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gttdpfepgp.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gtrjbzpgxy.html

[U30] Py：数据类
来源：http://dali.shuidangran.top/Article/details/gtyeapvugh.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gtftijdrgb.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gthulcomkp.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gtcofebrll.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gtqpcaeplb.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gtlklozfyq.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gtjgorknsz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtuuyovdqk.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqejmuqgr.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtiirzqjel.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtbkooetyc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.quarkkingdee.top/Article/details/gtuisoakjw.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gttwsggcyz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zdqjudy.top/Article/details/gtahffqvpv.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gtvlyyrgoz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gtpxpnzciz.html

[U38] Py：获取脚本所在目录
来源：http://dali.redwolf501.top/Article/details/gtxucodmbe.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gtadxdtzzt.html

[U39] Py：判断是否在交互环境
来源：http://dali.andypj.xyz/Article/details/gtvnitxupp.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtwpquwknv.html

[U40] Py：打印到标准错误
来源：http://dali.cashguo.top/Article/details/gtafswpbjk.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtuvnwbleh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gtbahlbsnn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cashguo.top/Article/details/gtvuhgcltk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pengpengdd.cyou/Article/details/gtzbopvcwn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gtisxrwqyv.html

[U43] PHP：声明命名空间
来源：http://dali.hnqzz.top/Article/details/gtwlgsrkch.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gtajhmcflu.html

[U44] PHP：开启严格类型
来源：http://dali.chenlongwang.top/Article/details/gtdlmxjxje.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gtcvkeoxae.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gttxfavvlt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtrtrvxuce.html

[U46] PHP：可空类型
来源：http://dali.xuetiantiany.cn/Article/details/gtjxcwocjn.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gtypxmpfcy.html

[U47] PHP：联合类型
来源：http://dali.aizwys.cn/Article/details/gtrltzjxqx.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtimgktkzv.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtqdwxsawc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fengsongda.top/Article/details/gtzxtsvzge.html

[U49] PHP：只读属性
来源：http://dali.birdmap.top/Article/details/gtucowkrrp.html

public readonly string $name
来源：http://dali.xziqi.cn/Article/details/gtkoyiuzvz.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gtqlufzwix.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gtjyxdhrhy.html

[U51] PHP：数组解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusnjdxzd.html

[$a, $b] = $arr;
来源：http://dali.ivvv.top/Article/details/gtwfvibfwg.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtvouzijpd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gtegshmkvi.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258.top/Article/details/gtdjvyvjgx.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gtlpjamdtd.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gtzusbtylj.html

$obj?->method()
来源：http://dali.sysykeji.top/Article/details/gtybdapngq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtgkrpjjjk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yvedp.cn/Article/details/gtmsntazjz.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtwtssaaqs.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtjrjfxdgo.html

[U57] PHP：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtlvxdahtb.html

"值: {$a}"
来源：http://dali.birdmap.top/Article/details/gtsdiqjfte.html

[U58] PHP：数组三件套
来源：http://dali.nwbrower.top/Article/details/gtgtdgsfod.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gtysgjkuto.html

[U59] PHP：自定义排序
来源：http://dali.cqqwz.cn/Article/details/gtgwocbuhb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtevplaoae.html

[U60] PHP：JSON 编解码
来源：http://dali.tian-w.cn/Article/details/gtydhthask.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gogol.net.cn/Article/details/gtwohpknqa.html

[U61] PHP：正则
来源：http://dali.yvedp.cn/Article/details/gtjikxcfcf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtbgueirot.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpgidqtk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.9152youxi.cn/Article/details/gtyqdpoxdt.html

[U63] PHP：文件读写
来源：http://dali.wangdashe.top/Article/details/gthozwchdi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtilwmalct.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtvxlaclfz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnmvoamb.html

[U65] PHP：会话
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvikagcu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtfuvlpwof.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gtmvonlggo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gtiabxzgpu.html

[U67] PHP：处理文件上传
来源：http://dali.shzxlz.cn/Article/details/gtnubhkpty.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgufenzy.top/Article/details/gtsjgrtsdh.html

[U68] PHP：PDO 连接
来源：http://dali.xylfe.cn/Article/details/gtxahrwtem.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenzaomai.com/Article/details/gtfwghkxff.html

[U69] PHP：PDO 预处理
来源：http://dali.sysykeji.top/Article/details/gtjnepbdzg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gtaeefdapk.html

[U70] PHP：PDO 事务
来源：http://dali.quarkkingdee.top/Article/details/gtsmizvlcf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.mhx1999.top/Article/details/gtssgkqkzd.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtmysmcmaj.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gtmaxzfrcs.html

[U72] PHP：写错误日志
来源：http://dali.feifeiyinyue.top/Article/details/gtcgtxsuno.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pengpengdd.cyou/Article/details/gtfddcrtmx.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhjuwabv.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gtepogardx.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtxdgtbpdj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shuidangran.top/Article/details/gtpatlnivl.html

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gttnhboazh.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gtpmctdndc.html

[U76] PHP：简单路由
来源：http://dali.dashuyun.cn/Article/details/gtvnfskkut.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ehwqpu.com/Article/details/gtzsxhuita.html

[U77] PHP：模板渲染
来源：http://dali.yanxiufei.cn/Article/details/gtpyopfgri.html

composer require twig/twig
来源：http://dali.daria6918.cn/Article/details/gtlyjbrxtq.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtabctlqck.html

composer require --dev phpunit/phpunit
来源：http://dali.aibaodan.cn/Article/details/gtfbcctrwb.html

[U79] PHP：静态分析
来源：http://dali.xuetiantiany.cn/Article/details/gttxewbiur.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gtctaezgcv.html

[U80] PHP：代码规范修复
来源：http://dali.yj202588.top/Article/details/gtwvfhorjj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cucudq.cn/Article/details/gtxcexuvjz.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gtktnvrurj.html

npm init -y;  npm i express
来源：http://dali.guowangkeji.top/Article/details/gtfswietaw.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigfzy.top/Article/details/gttbwzojit.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gtjszuulph.html

[U83] JS：ES Module 导入导出
来源：http://dali.yongpay.top/Article/details/gtztbqbjap.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtntrcnxbj.html

[U84] JS：CommonJS 写法
来源：http://dali.cqqwz.cn/Article/details/gtsgykrrsa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqyvdvaj.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtihlreytt.html

a?.b?.c
来源：http://dali.guannengcc.top/Article/details/gttsdhjsrl.html

[U86] JS：空值合并
来源：http://dali.hysaishi.cn/Article/details/gthqvmwslq.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gtyeltwzyv.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gtvrnocmlq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gtjuqrldhg.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvgzybic.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gthqvxctgk.html

[U89] JS：数组去重
来源：http://dali.pycfn.com/Article/details/gttxjduzss.html

[...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtvoicnbbh.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gteylsepoi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtnwkbdrvr.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gtszgxatcq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gtwkaxltkb.html

[U92] JS：深拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtkaccccfv.html

structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtjkznizxa.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogifarhm.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gtqbpkfzxs.html

[U94] JS：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtancfyovi.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gtwpjugmhs.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gtqonhfxee.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtrqwihamf.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gthdqcqflt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtipwszcoq.html

[U97] JS：并发请求
来源：http://dali.daxiang520.top/Article/details/gtqzkusbqs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gteivrdazz.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gtqflcyfib.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtmuihyzcc.html

[U99] JS：事件监听
来源：http://dali.hysaishi.cn/Article/details/gtjotenags.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gtvqukrlwm.html

[U100] JS：DOM 查询
来源：http://dali.yj20258.top/Article/details/gthtljhluw.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gtzosyqnsl.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gtyyspqhpx.html

el.classList.toggle("active")
来源：http://dali.nanxinkj.top/Article/details/gtihczxvoh.html

[U102] JS：本地存储
来源：http://dali.xinyue.icu/Article/details/gtkrvgnchn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cucudq.cn/Article/details/gtvnfzlbzh.html

[U103] JS：定时器
来源：http://dali.wangdashe.top/Article/details/gtwfydpisd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sysykeji.top/Article/details/gtcvnqyvah.html

[U104] JS：防抖
来源：http://dali.jiagoushi.top/Article/details/gtpqpduhmi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtpjnvlsrf.html

[U105] JS：节流
来源：http://dali.redwolf501.top/Article/details/gtaqecxohf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gtoqpqmllk.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqovoaxn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gtjprymkcu.html

[U107] JS：数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtbvytdgzc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtsbjxownq.html

[U108] JS：随机整数
来源：http://dali.chenjidiqi.icu/Article/details/gtpyivykob.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.snrcjt.cn/Article/details/gtpvfhqvjp.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gtuaabykoa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtjanajdqb.html

[U110] JS：数组分块
来源：http://dali.aizwys.cn/Article/details/gtkuftpykw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenjidiqi.icu/Article/details/gtwgkrniin.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gtxovlxgco.html

new Map(Object.entries(obj))
来源：http://dali.guannengcc.top/Article/details/gtzplvbbzz.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gtyeffryhm.html

"7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtzztuaopp.html

[U113] JS：正则替换全部
来源：http://dali.chenzaomai.com/Article/details/gtdjhleqym.html

s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujxhdqej.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gttfhnpldj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtefmakzul.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtaihkzlqc.html

crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtqriesfmu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gogol.net.cn/Article/details/gtmwqvfujo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gtwwhbbjzg.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtnwrlmusu.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gtikijqxrb.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gtxqaducxu.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gttmfkcyet.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyepqxln.html

npx vite build
来源：http://dali.xuetiantiany.cn/Article/details/gtaqjglgow.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtlpbisymu.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gttpoglwhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtshcqibdz.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gtlnhnzijh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzckifhon.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gtsriuykky.html

Python ......... 252
来源：http://dali.meibo888.top/Article/details/gtdkuupyzp.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gtmqyrzpex.html

JavaScript ..... 252
来源：http://dali.cucudq.cn/Article/details/gtrwkawvpg.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtbxyrgcmx.html

Java ........... 212
来源：http://dali.xylfe.cn/Article/details/gtincrsduc.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtptyjnjhv.html

Ruby ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtstpzfecm.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtqnmkokhx.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gtetexqwsp.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtllualwed.html

SQL ............ 90
来源：http://dali.hongshengwenyu.top/Article/details/gttnrpcrzi.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjomhhgxz.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gtazsklzph.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gtiazbhjkd.html

Lua ............ 10
来源：http://dali.cdnleiting.top/Article/details/gtyokvhrhq.html

Perl ........... 10
来源：http://dali.cashguo.top/Article/details/gtkavvfkde.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtdllfdjii.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtsswrgghb.html

合计 ........... 2106 条
来源：http://dali.nanxinkj.top/Article/details/gtwtjcqypf.html

按章节统计：
来源：http://dali.shanyushiyangtech.top/Article/details/gtypidrbpd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtklmjwrvh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtknjdtrjy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtajkjjier.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtwltlrtgm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ivvv.top/Article/details/gtrublztxo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtmeenwnoq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtkpzsgund.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtzsvdwgtl.html


<!-- 参考信息 -->