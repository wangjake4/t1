代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gt2ujukhcbu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ethykizq.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2xgxcxwrh.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gt2iopswcbr.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2fkjwnuiv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2kjrucqpd.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2rafdqnuo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gt2oyjbpqas.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrrmcpdp.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gt2gbvlxtpn.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2dnsjjhrk.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2zyhhvrwq.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtjoketv.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2rtkzezot.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gt2gelhcftb.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2nvkbulwq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gt2nhxbcucj.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2yqmufntq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gt2tybizojs.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gt2wzjrilja.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gt2kxjsurqb.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2rwhvafpj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2vkmqrmvd.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gt2srbifcxn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gt2xdiryjag.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gt2vfsmigoe.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gt2firhihbr.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gt2ebgffgyz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcppgvcd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rmhoayle.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gt2boumafnq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2sprqgpkx.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gt2rlyxlvow.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gt2wiexchet.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gt2evvxgsxb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gt2ydructak.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cbciodlq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gt2oogcceuj.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gt2rgrtsmdl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gt2mcblzahs.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gt2yujmqzjj.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2kcoqcvmx.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gt2gbcinjxm.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gt2gjzxexpp.html

[U07] Py：反转字典键值
来源：http://dali.yueranfly.top/Article/details/gt2qfbduphj.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gt2vrgowyqy.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gt2uaxexqks.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gt2pclojgbh.html

[U09] Py：字典取最大值的键
来源：http://dali.sysykeji.top/Article/details/gt2qkimdwbt.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gt2xalhycic.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gt2zffftkcc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gt2nwtvmkdh.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gt2wuqnowrw.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gt2baugogpk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gt2eksxcfhb.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gt2dfmackbj.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gt2pqstopxv.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxbkywjz.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gt2dxjgbnan.html

defaultdict(list)
来源：http://dali.vqdsnc.cn/Article/details/gt2tljlbffd.html

[U15] Py：高精度计时
来源：http://dali.iojbl.cn/Article/details/gt2adjzuudq.html

t = time.perf_counter()
来源：http://dali.c1oappe.top/Article/details/gt2swhletvd.html

[U16] Py：命令行参数解析
来源：http://dali.redwolf501.top/Article/details/gt2ocehnknf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuydupkv.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gt2dcdsoihx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gt2esayujaf.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gt2gootgdbj.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2tpmbyrep.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gt2snoflijt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gt2utnczaws.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gt2htxupbrh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gt2urairwoi.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gt2sginewth.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gt2twoquuhp.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gt2jluugkki.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gt2fzvgyiim.html

[U23] Py：分块读取大文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2wusdjnnt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gt2wferxqoh.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gt2hblqdeny.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gt2bwwymphh.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gt2tspjdhmp.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gt2bjuxsefp.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxdngegp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gt2aeskeapg.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258888.top/Article/details/gt2aoaxjlcn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gt2arrqicol.html

[U28] Py：类型别名
来源：http://dali.gogol.net.cn/Article/details/gt2kcggfpzm.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gt2ndesnnog.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gt2foojaosz.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gt2vkijkvay.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gt2ezslzxbo.html

@dataclass(slots=True)
来源：http://dali.yonumen.top/Article/details/gt2iiyoigsl.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2hebztalz.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gt2qfkqmvng.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gt2vmdznbol.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gt2omxtfqea.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2girgtctu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigfzy.top/Article/details/gt2pqpfxdgi.html

[U34] Py：判断编码
来源：http://dali.chenzaomai.com/Article/details/gt2wzjlqarc.html

chardet.detect(raw)
来源：http://dali.jianghu66.top/Article/details/gt2hqxsrucq.html

[U35] Py：发送邮件
来源：http://dali.daria6918.cn/Article/details/gt2ghuvpfux.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwtitypy.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyxjenij.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gt2vvmknvbo.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gt2dsttndub.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rownlbqm.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2fgxowuxf.html

Path(__file__).resolve().parent
来源：http://dali.wangdashe.top/Article/details/gt2swndpknt.html

[U39] Py：判断是否在交互环境
来源：http://dali.andypj.xyz/Article/details/gt2nxcmvclc.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxkwvbrr.html

[U40] Py：打印到标准错误
来源：http://dali.gaohongyu789.top/Article/details/gt2qwkztyml.html

print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gt2pcpyogmc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybbvfodr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxsxkkqj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tian-w.cn/Article/details/gt2rhujscso.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yongpay.top/Article/details/gt2wbkdwjmd.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigufen.top/Article/details/gt2jihdhwry.html

namespace App\Http;
来源：http://dali.guannengcc.top/Article/details/gt2efsnamiu.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkovpmfa.html

declare(strict_types=1);
来源：http://dali.vqdsnc.cn/Article/details/gt2ptfxafov.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gt2zpgliywp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lecmdcnk.html

[U46] PHP：可空类型
来源：http://dali.cucudq.cn/Article/details/gt2ftneyadl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqwzklc.html

[U47] PHP：联合类型
来源：http://dali.dianchejie.cn/Article/details/gt2gwlqciwg.html

int|string $id
来源：http://dali.snrcjt.cn/Article/details/gt2fuylffwt.html

[U48] PHP：纯枚举
来源：http://dali.smart0.xyz/Article/details/gt2mzexvoyu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gt2ttnydbfu.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2grdrriuq.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gt2mncnpewc.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gt2dtjhdsqs.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gt2eoxhhzma.html

[U51] PHP：数组解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2osihnsex.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gt2xdkxqqze.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gt2aycagcpc.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gt2rvowytee.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gt2culsyzad.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wisqauhv.html

[U54] PHP：空安全调用
来源：http://dali.tianlin.xyz/Article/details/gt2nkymberz.html

$obj?->method()
来源：http://dali.zhengqikj.top/Article/details/gt2ejllrwen.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2rplyrxlt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gt2davdahim.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gt2wwdqowvs.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2idkjoouc.html

[U57] PHP：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2igqmyuzt.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gt2txwyzrxb.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gt2hfhlynsq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2malvrjyn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zrupjnvy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2ukkrzpzj.html

[U60] PHP：JSON 编解码
来源：http://dali.gogol.net.cn/Article/details/gt2wppxpeao.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gt2bqbqtwqj.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gt2guvsnpcp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2hmbwjotl.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gt2denlhbcy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.andypj.xyz/Article/details/gt2ozrgpqzq.html

[U63] PHP：文件读写
来源：http://dali.yongpay.top/Article/details/gt2tpglmxqh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2midsafvh.html

[U64] PHP：目录遍历
来源：http://dali.cdnleiting.top/Article/details/gt2gkbkgedm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjpdbmuw.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gt2fzjrckgl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgzeddch.html

[U66] PHP：设置 Cookie
来源：http://dali.zhongyouzk.top/Article/details/gt2fhiqhdfe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2yunxpnzu.html

[U67] PHP：处理文件上传
来源：http://dali.meibo888.top/Article/details/gt2hcpvcwfp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daxiang520.top/Article/details/gt2aulwhkdk.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gt2bfgksmwc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gzhubu.top/Article/details/gt2evysmjrm.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gt2jdrfnrki.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tianlin.xyz/Article/details/gt2hnpnywyz.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gt2glqjjfgc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gt2zymtrvse.html

[U71] PHP：抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plfdqvbz.html

throw new RuntimeException("失败", 500);
来源：http://dali.redwolf501.top/Article/details/gt2otcorngo.html

[U72] PHP：写错误日志
来源：http://dali.dashuyun.cn/Article/details/gt2ewomksal.html

error_log("失败: " . $e->getMessage());
来源：http://dali.snrcjt.cn/Article/details/gt2nmunzecm.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gt2xeyfprfa.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gt2moghmegv.html

[U74] PHP：读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfiukpdo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj202588.top/Article/details/gt2abviqiiy.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gt2eonobyoq.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gt2byiuzemd.html

[U76] PHP：简单路由
来源：http://dali.zhengqikj.top/Article/details/gt2hminlauh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gt2sufpfxig.html

[U77] PHP：模板渲染
来源：http://dali.c1oappe.top/Article/details/gt2uykxbfmh.html

composer require twig/twig
来源：http://dali.cheryme.top/Article/details/gt2aynjufyo.html

[U78] PHP：单元测试
来源：http://dali.yongpay.top/Article/details/gt2furgtuyl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gt2zyhmooxx.html

[U79] PHP：静态分析
来源：http://dali.tian-w.cn/Article/details/gt2pgmulusn.html

composer require --dev phpstan/phpstan
来源：http://dali.xuetiantiany.cn/Article/details/gt2glhextqq.html

[U80] PHP：代码规范修复
来源：http://dali.shuidangran.top/Article/details/gt2kzhiqjed.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqlhwass.html

[U81] JS：初始化项目
来源：http://dali.gogol.net.cn/Article/details/gt2edbmztlo.html

npm init -y;  npm i express
来源：http://dali.zhoulong.xyz/Article/details/gt2khzyttzr.html

[U82] JS：package.json 脚本
来源：http://dali.ybcxt.top/Article/details/gt2voamiblo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ybcxt.top/Article/details/gt2khuzjcfk.html

[U83] JS：ES Module 导入导出
来源：http://dali.havefunace.top/Article/details/gt2wrqnnwwy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haybatqu.html

[U84] JS：CommonJS 写法
来源：http://dali.xziqi.cn/Article/details/gt2brbxzhkn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gt2yacysove.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gt2qvpfbbfo.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gt2zbadstpo.html

[U86] JS：空值合并
来源：http://dali.jqgufenzy.top/Article/details/gt2pvcepwgm.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gt2kghywybg.html

[U87] JS：解构默认值
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcaieisr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gt2fwmvqrro.html

[U88] JS：对象展开合并
来源：http://dali.0kj1m.cn/Article/details/gt2ypiitqiy.html

{ ...a, ...b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2exmqbmum.html

[U89] JS：数组去重
来源：http://dali.hywenlv.cn/Article/details/gt2xghdgfox.html

[...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2drkvdqyo.html

[U90] JS：数字数组排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwryosmf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbdtawgf.html

[U91] JS：对象键值遍历
来源：http://dali.wangdashe.top/Article/details/gt2yivxbemu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gaohongyu789.top/Article/details/gt2awpvowds.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2soxqiiha.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2ijpjccee.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gt2xouefhio.html

`共 ${n} 条`
来源：http://dali.cheryme.top/Article/details/gt2zymwnocz.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gt2crorsjvs.html

const double = x => x * 2;
来源：http://dali.jyoumei.cn/Article/details/gt2cdqplkbh.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gt2iwyhvyla.html

new Promise((resolve, reject) => {})
来源：http://dali.wangdashe.top/Article/details/gt2oeblqjms.html

[U96] JS：async/await 与异常
来源：http://dali.gzhubu.top/Article/details/gt2kwchzhgo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2imnotsoe.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfbaipgs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2lxzuziho.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2pojrzcyf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gt2ecpcpfus.html

[U99] JS：事件监听
来源：http://dali.haohaochexian.top/Article/details/gt2orzqzqpd.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gt2wpngmjvs.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gt2dtzxpakc.html

document.querySelector(".item")
来源：http://dali.quarkkingdee.top/Article/details/gt2cbffrrkt.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2nflujnrc.html

el.classList.toggle("active")
来源：http://dali.cashguo.top/Article/details/gt2hirilffq.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gt2ngfghstv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ehwqpu.com/Article/details/gt2cbnzxryy.html

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gt2ulylybvz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gt2heulwokn.html

[U104] JS：防抖
来源：http://dali.hnqzz.top/Article/details/gt2rrqdrxrh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2pdjvgfbz.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gt2jyiahpjd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pycfn.com/Article/details/gt2llgmxwyj.html

[U106] JS：日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2hphkvbnb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gt2rnmeepdb.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gt2lfabqqjt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gt2aenwdmfx.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gt2ksjekszs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gt2lzudprkb.html

[U109] JS：数组分组
来源：http://dali.dianchejie.cn/Article/details/gt2ydwrkrly.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2gviliyro.html

[U110] JS：数组分块
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqfykzfr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhongyouzk.top/Article/details/gt2hjjaagyb.html

[U111] JS：对象转 Map
来源：http://dali.yuanzhike.top/Article/details/gt2ovtjmiej.html

new Map(Object.entries(obj))
来源：http://dali.fzhhl.top/Article/details/gt2nohwmvje.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gt2sdomutlm.html

"7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2frqmbwap.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gt2ylpvmlqg.html

s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2rmtjewhq.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2slxjjnrv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gt2stezlrcf.html

[U115] JS：生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2ksdylqri.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2vvpfwpmp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tianlin.xyz/Article/details/gt2vmowxeky.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2mkiejina.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2usfobfet.html

npm i -D vitest;  npx vitest
来源：http://dali.smart0.xyz/Article/details/gt2sbrsuhkq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2prvonnqd.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gt2wdzfplzn.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gt2htojngtr.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gt2qbzouzee.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gt2ecykrodi.html

import.meta.env.VITE_API_URL
来源：http://dali.ydzc1.top/Article/details/gt2omtlvyiw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2mymqjcjn.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gt2acckvkhx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ytxavjml.html

按语言统计（条）：
来源：http://dali.yvedp.cn/Article/details/gt2ykxfmoaf.html

Python ......... 252
来源：http://dali.sysykeji.top/Article/details/gt2nyhtdltj.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gt2prgajriy.html

JavaScript ..... 252
来源：http://dali.ppjwa.cn/Article/details/gt2mfzkcbpg.html

TypeScript ..... 212
来源：http://dali.sysykeji.top/Article/details/gt2tblmatfa.html

Java ........... 212
来源：http://dali.smart0.xyz/Article/details/gt2mtsoxkff.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gt2qnthqsmy.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2blynprcq.html

C# ............. 212
来源：http://dali.aizwys.cn/Article/details/gt2aywgwtgz.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gt2wayaqsox.html

C++ ............ 30
来源：http://dali.redwolf501.top/Article/details/gt2tinylefu.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gt2uneuynmb.html

Bash ........... 80
来源：http://dali.guowangkeji.top/Article/details/gt2ashrofbt.html

Kotlin ......... 15
来源：http://dali.zhongyouzk.top/Article/details/gt2bflgdqvu.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqhiiiqu.html

Lua ............ 10
来源：http://dali.tanke756.top/Article/details/gt2xmungouq.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gt2gysapjqx.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gt2rygcxmzx.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gt2ragykpoi.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gt2uornfxtt.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gt2ilxiiwdz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gt2ruryrulp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2rnnakrct.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fibhfgks.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2uuigjirx.html


<!-- 参考信息 -->