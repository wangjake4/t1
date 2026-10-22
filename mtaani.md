代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csddnirx.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gt2omiufsqf.html

[T44] Perl：条件
来源：http://dali.xinyue.icu/Article/details/gt2zqayvnjv.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gt2nskrcala.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gt2eajrpaud.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2poqeirle.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gt2gdowgskg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fjixkple.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gt2wxmcinfl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gt2itzaumiq.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2oowxybmj.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cucwaxyr.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gt2iietsogt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmdcnbna.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2cchovlwy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gt2bapyaxgt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xiezcoro.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2yeouckzy.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2coztlzwf.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gt2halcxhna.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhbazzxh.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muzdcuto.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2xowxxfoc.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2tidayfgn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gt2nzlfbxgh.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2zohgtcpa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gt2uzgeyqio.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gt2ustoookh.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gt2auavcsff.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gt2gtmpthmu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gt2ttnrssvk.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcrpnczj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gt2ambnniwc.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gt2ozclqcdz.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gt2ysqwiyfh.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gt2fdslnbfy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gt2xztlmxgw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2nichccsn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gt2ktupwrij.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fumzjnse.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gt2cblriixi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sysykeji.top/Article/details/gt2abxdemyp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gt2smwnvvwm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gt2icolutbo.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdxjaalr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gt2wilvpymy.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gt2libaqhkh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gt2xgmkoric.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gt2jcqrejkl.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2buvhovjw.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gt2ylnlydtj.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gt2dayczkfw.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gt2shdgntru.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjijvubn.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gt2hwsksfxj.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gt2skbptxey.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gt2tuykbukp.html

max(d, key=d.get)
来源：http://dali.c1oappe.top/Article/details/gt2cwpjmqya.html

[U10] Py：按值排序字典
来源：http://dali.andypj.xyz/Article/details/gt2jgqsronw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzolrqjr.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gt2yesbvgyh.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gt2juageksk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gt2mopgkvwz.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gt2pwnvefpo.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gt2gpojgwkl.html

deque(maxlen=10)
来源：http://dali.yanxiufei.cn/Article/details/gt2rpvfomxo.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gt2cvselbcs.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2txcxykcg.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gt2khdbelfx.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gt2eczfzlcg.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gt2zhunmkbq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gt2vlwxgupn.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gt2tfhlcapu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xziqi.cn/Article/details/gt2bukzpaof.html

[U18] Py：预编译正则
来源：http://dali.andypj.xyz/Article/details/gt2xrqrbssc.html

pat = re.compile(r"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2pkyzfjpa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdvtjnx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aywwclqh.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjkczonu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shuidangran.top/Article/details/gt2xrpbugdq.html

[U21] Py：自定义上下文管理器
来源：http://dali.gaohongyu789.top/Article/details/gt2gsrprozd.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gt2qzhosots.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gt2bxukjqbe.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gt2tmrhnqtp.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gt2gzrouwyd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcubwhff.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gt2mqfamexo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2kwbtkrot.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gt2ljjfsmuu.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gt2zzpixfts.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gt2exfraisf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gt2snpveqxf.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojpkdxvh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddrgpqzn.html

[U28] Py：类型别名
来源：http://dali.meibo888.top/Article/details/gt2iancbzmm.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gt2tpvfodaj.html

[U29] Py：属性校验
来源：http://dali.xziqi.cn/Article/details/gt2jnnzgpjz.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gt2kyhjpyuq.html

[U30] Py：数据类
来源：http://dali.tian-w.cn/Article/details/gt2iofzrpcc.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gt2shlrtbae.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gt2amgljynd.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gt2pmsvehox.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gt2urjbdbsc.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vawvhfwi.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldpfcgun.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gt2rfozibuk.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gt2xtdiofgu.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gt2nkutkwks.html

[U35] Py：发送邮件
来源：http://dali.jqgfzy.top/Article/details/gt2fzoiscmr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnqzz.top/Article/details/gt2pnesvkrh.html

[U36] Py：定时任务
来源：http://dali.mhx1999.top/Article/details/gt2nlsstqzh.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gt2awphgxll.html

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gt2ecohoaix.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuetiantiany.cn/Article/details/gt2sykowuwy.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gt2yoaeqdys.html

Path(__file__).resolve().parent
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxatizuy.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gt2szjbhsfm.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gt2crvkssqw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bonlhrve.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2pytwlxjq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xylfe.cn/Article/details/gt2zqjtulaw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gt2ilniaiqo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gt2voyboilk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tysazvwf.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gt2gimdyswr.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gt2yufawouc.html

[U44] PHP：开启严格类型
来源：http://dali.sufxvd.cn/Article/details/gt2xckpuced.html

declare(strict_types=1);
来源：http://dali.jianghu66.top/Article/details/gt2xmjjipdn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuxming.cn/Article/details/gt2gsjqxbys.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjszxzpz.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gt2prqcukiq.html

?string $name = null
来源：http://dali.hfpthk.cn/Article/details/gt2pcdwdyfo.html

[U47] PHP：联合类型
来源：http://dali.yuanzhike.top/Article/details/gt2echxkhqp.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gt2wwtpjgpg.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gt2xxjusnpy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gt2ycvoryyg.html

[U49] PHP：只读属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytpxznzy.html

public readonly string $name
来源：http://dali.jinqigfzy.top/Article/details/gt2eesnymkh.html

[U50] PHP：构造器属性提升
来源：http://dali.svipenyu.cn/Article/details/gt2hmlrkikd.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gt2gkibudge.html

[U51] PHP：数组解构
来源：http://dali.cdnleiting.top/Article/details/gt2rqbdeowz.html

[$a, $b] = $arr;
来源：http://dali.xylfe.cn/Article/details/gt2qtzcjyng.html

[U52] PHP：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gt2daurzyfj.html

$double = fn($x) => $x * 2;
来源：http://dali.shuidangran.top/Article/details/gt2popgpide.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigufen.top/Article/details/gt2ijdhfjzz.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gt2uaqzyzgh.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gt2qznwhgkl.html

$obj?->method()
来源：http://dali.hnqzz.top/Article/details/gt2oelitmxr.html

[U55] PHP：match 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2isscfnrj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gt2hxlxddvm.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gt2iimvhtle.html

f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2hymftwjx.html

[U57] PHP：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2sivxamsn.html

"值: {$a}"
来源：http://dali.c1oappe.top/Article/details/gt2ratqraca.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gt2rfedfgxg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gt2jajqmtkp.html

[U59] PHP：自定义排序
来源：http://dali.9152youxi.cn/Article/details/gt2qbvrlmgy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snckjifh.html

[U60] PHP：JSON 编解码
来源：http://dali.shzxlz.cn/Article/details/gt2shivrugw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cashguo.top/Article/details/gt2oztkahag.html

[U61] PHP：正则
来源：http://dali.xziqi.cn/Article/details/gt2toazayfe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2pqwdwdql.html

[U62] PHP：日期对象
来源：http://dali.gotoacloud.top/Article/details/gt2ahnrrorw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gt2epxcmcgi.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gt2xstimbsm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nwbrower.top/Article/details/gt2uozipnjk.html

[U64] PHP：目录遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnxerxqv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yvedp.cn/Article/details/gt2jxctbral.html

[U65] PHP：会话
来源：http://dali.xuanzx.com/Article/details/gt2jtalpcko.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2pzgfxurr.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vspijyqx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gt2qdycxsfn.html

[U67] PHP：处理文件上传
来源：http://dali.ppjwa.cn/Article/details/gt2fjwdgpai.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhenilsl.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gt2hnrblyfk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gt2oydhwkwm.html

[U69] PHP：PDO 预处理
来源：http://dali.ydzc1.top/Article/details/gt2mmehujmu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbgllksj.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbiqbvfm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gt2fiexgocu.html

[U71] PHP：抛出异常
来源：http://dali.daria6918.cn/Article/details/gt2cwhlowjp.html

throw new RuntimeException("失败", 500);
来源：http://dali.xziqi.cn/Article/details/gt2avvssowm.html

[U72] PHP：写错误日志
来源：http://dali.jianghu66.top/Article/details/gt2lmcmhfrm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gt2vceghivr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2wrdojvjk.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gt2sjzhdvsf.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2hjjggewq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fzhhl.top/Article/details/gt2iluveqen.html

[U75] PHP：依赖注入
来源：http://dali.yj20258.top/Article/details/gt2agmtfzht.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvxcsfrm.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsbmymnq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigufen.top/Article/details/gt2yasxvnpj.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gt2gpsaqcip.html

composer require twig/twig
来源：http://dali.gotoacloud.top/Article/details/gt2gplapklf.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gt2igatqwfz.html

composer require --dev phpunit/phpunit
来源：http://dali.yonumen.top/Article/details/gt2pdxilkco.html

[U79] PHP：静态分析
来源：http://dali.ehwqpu.com/Article/details/gt2ycmldkuc.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gt2gbdjlhwp.html

[U80] PHP：代码规范修复
来源：http://dali.yonumen.top/Article/details/gt2ncxgxanh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gt2gognhyeo.html

[U81] JS：初始化项目
来源：http://dali.gogol.net.cn/Article/details/gt2cfvkyefl.html

npm init -y;  npm i express
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywapacts.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2updaqefq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tianlin.xyz/Article/details/gt2xqrfyhjd.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gt2xbybaeck.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gt2iwvyrboz.html

[U84] JS：CommonJS 写法
来源：http://dali.fengsongda.top/Article/details/gt2cgfjhypn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgufenzy.top/Article/details/gt2govbngmf.html

[U85] JS：可选链
来源：http://dali.shzxlz.cn/Article/details/gt2jkunavhl.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gt2ckdqxoho.html

[U86] JS：空值合并
来源：http://dali.jqgufenzy.top/Article/details/gt2oshglrsp.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gt2gafhalba.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gt2djkpztrz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gt2znykpmgm.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btuoapwh.html

{ ...a, ...b }
来源：http://dali.jqgfzy.top/Article/details/gt2gybexvjg.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gt2wkbtghug.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2yecvtbyg.html

[U90] JS：数字数组排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgeixfwv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2jbwbgrzp.html

[U91] JS：对象键值遍历
来源：http://dali.sxryk.cn/Article/details/gt2zppcpskm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daxiang520.top/Article/details/gt2tqovyfjg.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gt2mmwmleyc.html

structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2yktqkfmd.html

[U93] JS：模板字符串
来源：http://dali.zhixingplan.top/Article/details/gt2rnjksyaa.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gt2kqpilyby.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gt2kiajersa.html

const double = x => x * 2;
来源：http://dali.chenzaomai.com/Article/details/gt2piklvcll.html

[U95] JS：Promise 包装
来源：http://dali.iojbl.cn/Article/details/gt2irmvyybg.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gt2kolhhwrh.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gt2qnnajagq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2miywibjs.html

[U97] JS：并发请求
来源：http://dali.cqqwz.cn/Article/details/gt2jgcbejbj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2rcejrudy.html

[U98] JS：fetch 带 JSON
来源：http://dali.aibaodan.cn/Article/details/gt2efazcjuk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gt2dalqieoe.html

[U99] JS：事件监听
来源：http://dali.tanke756.top/Article/details/gt2smzkyzxz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wskjfuhu.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gt2snngbslb.html

document.querySelector(".item")
来源：http://dali.zycfv.cn/Article/details/gt2hacujteq.html

[U101] JS：classList 操作
来源：http://dali.sxryk.cn/Article/details/gt2dmqfgeqw.html

el.classList.toggle("active")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgscygbi.html

[U102] JS：本地存储
来源：http://dali.fzhhl.top/Article/details/gt2papccdfl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dianchejie.cn/Article/details/gt2bqeokcct.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gt2gmdjyagy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gt2sfroffyw.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2liynipjd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2ijkovygk.html

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gt2bxwzoydp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gt2yjzpiaeu.html

[U106] JS：日期格式化
来源：http://dali.cucudq.cn/Article/details/gt2vurzvbbe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gt2lhfqfyqz.html

[U107] JS：数字千分位
来源：http://dali.havefunace.top/Article/details/gt2oilkuhza.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2uzyqffkf.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itjyiscx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gt2xjyeafpc.html

[U109] JS：数组分组
来源：http://dali.hywenlv.cn/Article/details/gt2auzmwfjb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2roqumbyb.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gt2cseigsai.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258888.top/Article/details/gt2juadkzgs.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gt2pyeswkzr.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2qadrepop.html

[U112] JS：字符串补位
来源：http://dali.cheryme.top/Article/details/gt2yoabhrqq.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2tojstmjb.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gt2leynuzsv.html

s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2rgcmkblb.html

[U114] JS：JSON 深比较
来源：http://dali.havefunace.top/Article/details/gt2mkagzuea.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gt2pngrazqq.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2nccgyvut.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehnqmsyk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gt2swthjmjj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gt2pxcfpegp.html

[U117] JS：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gt2oqbiisxz.html

npm i -D vitest;  npx vitest
来源：http://dali.chenlongwang.top/Article/details/gt2rotkjvti.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gt2nvhtelyb.html

npm i -D vite;  npx vite
来源：http://dali.0kj1m.cn/Article/details/gt2iwrqmmea.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gt2rdjhxayu.html

npx vite build
来源：http://dali.zhixingplan.top/Article/details/gt2kdoypjyo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gt2cmiqdecr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gt2plpawzkc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2izzgbhik.html

统计汇总
来源：http://dali.gzhubu.top/Article/details/gt2izmounad.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wszxitxt.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gt2dnawooqm.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gt2jvoxkpra.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egvdzlkm.html

JavaScript ..... 252
来源：http://dali.hysaishi.cn/Article/details/gt2vbsbseos.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gt2rtthcvuy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qdamrfyt.html

Go ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwtmjddq.html

Ruby ........... 212
来源：http://dali.fzhhl.top/Article/details/gt2hnpuwymv.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gt2ocvlkkeu.html

C .............. 30
来源：http://dali.snrcjt.cn/Article/details/gt2ynisnbhk.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gt2nuuyzocp.html

SQL ............ 90
来源：http://dali.aibaodan.cn/Article/details/gt2iwjdexlk.html

Bash ........... 80
来源：http://dali.ivvv.top/Article/details/gt2zgghieee.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gt2xuxynpjy.html

Swift .......... 15
来源：http://dali.kuanghao11.cn/Article/details/gt2pccyibzg.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gt2amcpvink.html

Perl ........... 10
来源：http://dali.xylfe.cn/Article/details/gt2yyqzjrmr.html


<!-- 参考信息 -->