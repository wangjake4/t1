代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtwlrndjzg.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gthtnsouok.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtrsobvliu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtkjzewoye.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gtqbconnny.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gtwxzxrrve.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtqofwnosk.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gtpmnuxcms.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gtorczlcfi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtmtzrcbhi.html

[T50] Perl：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttomckkju.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gtrfsrqlyi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gtjyhyerqu.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtwcqwsmfw.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtfwpmkgky.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtwamfjgvk.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gteerfcjve.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtgkzsflgd.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtuijntfde.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gthlvdyarh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtdsbrwcjd.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtcpgjohnn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gtdxmwfadz.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gtmcyezuej.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gtrwlihjlx.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtqchldugs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtopyjnvmd.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtgioyxqdi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gtprohhsae.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtmhxywplv.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtudjuvgib.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gttyzusofs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gtvfyjcdsk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuconswgj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtngrcnbzl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcudhuepk.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrekrbjnx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gtwcywwrue.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtlphpqmsy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gthowqouyl.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtbccvwiso.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtrqxmkjhh.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtdbqzrzpz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gthjufpgwo.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gtdqoflmgq.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtroatbtdi.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gtlrzyzibj.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtslyptunp.html

[U07] Py：反转字典键值
来源：http://dali.iojbl.cn/Article/details/gtagpgosyp.html

{v: k for k, v in d.items()}
来源：http://dali.jlsjyb.cn/Article/details/gtropgtrbb.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtyjoliknn.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gtjhlexgzu.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gtzmfvnpxz.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gtmkcjyecb.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtxyvohevz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gtcscdngnx.html

[U11] Py：生成器表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtafpdwfke.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtyteotaky.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmbhvlsy.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gtmxccvmng.html

[U13] Py：固定长度队列
来源：http://dali.wangshuangyany.cn/Article/details/gtmhsqgalb.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gtmtgmetlv.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gtnprapdpr.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gtopgmosbn.html

[U15] Py：高精度计时
来源：http://dali.sxryk.cn/Article/details/gtqrlrrshv.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gtknkkynfh.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvfmvcff.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdozvcub.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gtedvyxcpj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tian-w.cn/Article/details/gthvrkubue.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtyxrxclph.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtwlwlbfek.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gtemnazyno.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gtxqobflzo.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gtbacksnfh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtdpnqsbzq.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtjrmmtcem.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gtihnjeikv.html

[U22] Py：矩阵转置
来源：http://dali.zhongyouzk.top/Article/details/gttyllojno.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gtoalqswva.html

[U23] Py：分块读取大文件
来源：http://dali.aibaodan.cn/Article/details/gtytndjsmw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gteaizsugj.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gthfpsbbop.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtzpigyrfr.html

[U25] Py：CSV 按字典读
来源：http://dali.guowangkeji.top/Article/details/gtgptdpego.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtjcrhskrt.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gtgflgmprz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhoulong.xyz/Article/details/gtigkmvcxy.html

[U27] Py：异步 HTTP
来源：http://dali.ppjwa.cn/Article/details/gtjpmclrgw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gttpkghhls.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gtgcztyhko.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtiazsbcup.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gtfjsxqpht.html

@property 与 @x.setter 配合
来源：http://dali.sxryk.cn/Article/details/gtjtwfonwb.html

[U30] Py：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtxxpioebw.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gtxkrsxpim.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gtmxfphxiz.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtznpvhmyi.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtyxzziedr.html

ruff format . && ruff check --fix .
来源：http://dali.chenzaomai.com/Article/details/gtumqfccvt.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gtejlrlkko.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgowzvgr.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gtadxoynhd.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gttemqkhns.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlhhfwoe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gtneelfzpu.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gtcdzgglcl.html

schedule.every(10).minutes.do(job)
来源：http://dali.hfpthk.cn/Article/details/gtdlvrjgkf.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtwoafzzsp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gtcnvatkbu.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gtdfnxpbhw.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gtohybhkig.html

[U39] Py：判断是否在交互环境
来源：http://dali.yanxiufei.cn/Article/details/gtspzkhrbq.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gtbacvzoxh.html

[U40] Py：打印到标准错误
来源：http://dali.quarkkingdee.top/Article/details/gthcxmvwrp.html

print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtsmujsrqb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuxming.cn/Article/details/gtpzijxshj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.birdmap.top/Article/details/gtkytzwtzj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gtxuwmtslx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gtngsdfawj.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gtdpjzslwd.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gtgmgpqpel.html

[U44] PHP：开启严格类型
来源：http://dali.yongpay.top/Article/details/gtoqxnrxlu.html

declare(strict_types=1);
来源：http://dali.tanke756.top/Article/details/gtnzwfwsdv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gtnkubcpts.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucuavxlq.html

[U46] PHP：可空类型
来源：http://dali.chenlongwang.top/Article/details/gtyeacngmy.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gtkwpxgxdy.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gtzpwxetkq.html

int|string $id
来源：http://dali.xuanzx.com/Article/details/gtyrjcuwoi.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gtgewymmtc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gtlooosded.html

[U49] PHP：只读属性
来源：http://dali.sysykeji.top/Article/details/gttaerwwui.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gtobvxilct.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgufenzy.top/Article/details/gtiesiclqz.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gtetirkwyp.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtwhaxrslr.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gtbmiqspia.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtzvvvapgn.html

$double = fn($x) => $x * 2;
来源：http://dali.fengsongda.top/Article/details/gtgjkdueic.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gtzvddiyos.html

$v = $a ?? $b ?? "default";
来源：http://dali.guannengcc.top/Article/details/gtqaqdmokn.html

[U54] PHP：空安全调用
来源：http://dali.yvedp.cn/Article/details/gtzdqawhon.html

$obj?->method()
来源：http://dali.xziqi.cn/Article/details/gtmlrlujmf.html

[U55] PHP：match 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtjfrbnugw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtailreuld.html

[U56] PHP：命名参数
来源：http://dali.tanke756.top/Article/details/gtjhfesvyp.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtjaafrptf.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtjtwerzje.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gtprarwykd.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gtiprjyqsz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtfihpfxda.html

[U59] PHP：自定义排序
来源：http://dali.yj202588.top/Article/details/gtywbbqklq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflvnrzjt.html

[U60] PHP：JSON 编解码
来源：http://dali.hywenlv.cn/Article/details/gtytifsfhr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphbxcyfx.html

[U61] PHP：正则
来源：http://dali.xziqi.cn/Article/details/gtyusnqton.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtwlanjkcv.html

[U62] PHP：日期对象
来源：http://dali.yueranfly.top/Article/details/gtrbiblsrk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sxryk.cn/Article/details/gtypykesbr.html

[U63] PHP：文件读写
来源：http://dali.guowangkeji.top/Article/details/gtsnvelbvy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkcsnoco.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gthbpedoaa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gthaoiilhc.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gtqridsjlf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvbfhnhz.html

[U66] PHP：设置 Cookie
来源：http://dali.mhx1999.top/Article/details/gtybkstaxk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtdcxhkyfg.html

[U67] PHP：处理文件上传
来源：http://dali.hnxiangtu.top/Article/details/gtynmvdsgm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gtjtwcvdir.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gtexuvottv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigfzy.top/Article/details/gtbxwepjyv.html

[U69] PHP：PDO 预处理
来源：http://dali.zycfv.cn/Article/details/gtmufkkdsw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sysykeji.top/Article/details/gtnmirgrqc.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtmqtvndqw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtzqpgfuom.html

[U71] PHP：抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtnlaaztjt.html

throw new RuntimeException("失败", 500);
来源：http://dali.cashguo.top/Article/details/gtyohqcowu.html

[U72] PHP：写错误日志
来源：http://dali.xinyue.icu/Article/details/gtqcsaxuby.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gtypbksjqa.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj202588.top/Article/details/gtoxudunte.html

parse_ini_file("config.ini", true)
来源：http://dali.smart0.xyz/Article/details/gtcjydvmni.html

[U74] PHP：读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtiawvupbk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.quarkkingdee.top/Article/details/gtquimediy.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gtoyzwsoxd.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gtfykwqudr.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gtrloefdrg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zycfv.cn/Article/details/gtrvuqayur.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gtsxipgwks.html

composer require twig/twig
来源：http://dali.gotoacloud.top/Article/details/gtarplmoyh.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtmzhzuwpc.html

composer require --dev phpunit/phpunit
来源：http://dali.jlsjyb.cn/Article/details/gthbogvphn.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtjzeqvfwt.html

composer require --dev phpstan/phpstan
来源：http://dali.havefunace.top/Article/details/gtyhfdkstx.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gtmemzaduc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.birdmap.top/Article/details/gtfqzkwwwn.html

[U81] JS：初始化项目
来源：http://dali.zhengqikj.top/Article/details/gtihcfokuj.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtlzzssenj.html

[U82] JS：package.json 脚本
来源：http://dali.zhiwuduotai.top/Article/details/gtuihsgwql.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yanxiufei.cn/Article/details/gtbhhzxogj.html

[U83] JS：ES Module 导入导出
来源：http://dali.fzhhl.top/Article/details/gtbbxxeimj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtwlfvtbha.html

[U84] JS：CommonJS 写法
来源：http://dali.vqdsnc.cn/Article/details/gtufbrkcpv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tanke756.top/Article/details/gtmprqqume.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gtzhydeiwl.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gtsxqznott.html

[U86] JS：空值合并
来源：http://dali.kuanghao11.cn/Article/details/gtcxlmsbzw.html

a ?? b
来源：http://dali.sysykeji.top/Article/details/gthzozvgpq.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtludnishu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jyoumei.cn/Article/details/gtehlwatyw.html

[U88] JS：对象展开合并
来源：http://dali.yuanzhike.top/Article/details/gteglsggxq.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtltsdkvlo.html

[U89] JS：数组去重
来源：http://dali.yueranfly.top/Article/details/gtyrgenpbx.html

[...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtkakmmzxz.html

[U90] JS：数字数组排序
来源：http://dali.sweek.top/Article/details/gtwxpiaxna.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtmnpzveln.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gtoehyimxx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgfzy.top/Article/details/gtybdzkxpg.html

[U92] JS：深拷贝
来源：http://dali.jianghu66.top/Article/details/gtmnvjoytn.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gteujxrgbw.html

[U93] JS：模板字符串
来源：http://dali.cqqwz.cn/Article/details/gtfrtsdfev.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gtidwmjhgj.html

[U94] JS：箭头函数
来源：http://dali.sweek.top/Article/details/gtlcrihkaz.html

const double = x => x * 2;
来源：http://dali.chenzaomai.com/Article/details/gtiqwybefd.html

[U95] JS：Promise 包装
来源：http://dali.hnxiangtu.top/Article/details/gtzwbefqju.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gtxugwtddl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gtuvhuloml.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtclortzsw.html

[U97] JS：并发请求
来源：http://dali.xinyue.icu/Article/details/gtstkjxdqg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtegmfwezg.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtpvtcxtyw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gtzubjimok.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gtjwogjaky.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtwknivtov.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gtxoscumsa.html

document.querySelector(".item")
来源：http://dali.jqgufenzy.top/Article/details/gtdeatyavn.html

[U101] JS：classList 操作
来源：http://dali.9152youxi.cn/Article/details/gtfrhjadfb.html

el.classList.toggle("active")
来源：http://dali.jqgufenzy.top/Article/details/gtoftvdsud.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gtyggixnai.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gtqhcabgaz.html

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gtzjrcqtlx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.svipenyu.cn/Article/details/gtciuwfqur.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gtananrlxb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtffsdcyju.html

[U105] JS：节流
来源：http://dali.cashguo.top/Article/details/gtggeqwxia.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenzaomai.com/Article/details/gtvazpsfpg.html

[U106] JS：日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuffpuwsf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gtvugroodg.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtsyxxsyen.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtukoflpqu.html

[U108] JS：随机整数
来源：http://dali.daxiang520.top/Article/details/gtkuqmkdrd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gtevfpozoc.html

[U109] JS：数组分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvepinxwm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtjhygfclc.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gtotzdczok.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenzaomai.com/Article/details/gteioskqhr.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gtjtzgrnwu.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gtfeuhwlym.html

[U112] JS：字符串补位
来源：http://dali.9152youxi.cn/Article/details/gtbuaoepcx.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtossxwcqa.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsakblbpf.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtnbbexntg.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gtdayonarx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtngaidect.html

[U115] JS：生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtngnjajlb.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtvqrkthql.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gtxnoxhqcz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtnmnkgcfl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtlhmihqai.html

npm i -D vitest;  npx vitest
来源：http://dali.nwbrower.top/Article/details/gtbhjsgvdb.html

[U118] JS：开发服务器
来源：http://dali.yueranfly.top/Article/details/gtldgnptmj.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtesxswuyo.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gthyaphehk.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtilvpeccn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gtlpwineny.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gtaowsfwum.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrlflhicl.html

统计汇总
来源：http://dali.ydzc1.top/Article/details/gtnjkybzyz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjihlpswt.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gthkmijflm.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtzoprkwgr.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gtvipzyzft.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gtpmhteitq.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gttnwbdpfg.html

Java ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtahpkiexa.html

Go ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjixddrvv.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtooljngbl.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtuvqqjdcm.html

C .............. 30
来源：http://dali.mhx1999.top/Article/details/gtsqtbkscn.html

C++ ............ 30
来源：http://dali.sxryk.cn/Article/details/gtxmamrsqp.html

SQL ............ 90
来源：http://dali.meibo888.top/Article/details/gtdrgfyddk.html

Bash ........... 80
来源：http://dali.chenjidiqi.icu/Article/details/gtnosyvcgs.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gtkrroyghh.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtcjrcappl.html

Lua ............ 10
来源：http://dali.ivvv.top/Article/details/gtovauffsa.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gtjmzrkfis.html

Scala .......... 10
来源：http://dali.yj202588.top/Article/details/gtkvfwqxpb.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtsraaleuz.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gtzlqsduzf.html

按章节统计：
来源：http://dali.yueranfly.top/Article/details/gtfhmpqwcj.html


<!-- 参考信息 -->