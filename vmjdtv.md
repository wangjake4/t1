代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtfgswzwjt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtefdhyvkl.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gttwzzfbei.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gtgzxdbbbd.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gtzfjoiojh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gtcccnkuxp.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtboufgajp.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gtilsizhjm.html

[T37] Lua：字符串拼接
来源：http://dali.sweek.top/Article/details/gtlutdxdef.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtaodpkdbj.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtfvekwjfy.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gtxbuoogeo.html

[T39] Lua：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtplskpuqu.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtbrqfpiry.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gthtafuepu.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtyahntybg.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtizhyomsy.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gthntvcvhk.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtvwcticft.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gtatuzyphh.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtfyqdkrci.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gtyqadxypz.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gtlpustotc.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxvfhksk.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtnhoryuro.html

for my $x (@arr) { print $x; }
来源：http://dali.wangdashe.top/Article/details/gtewwmjelp.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gtnatrnwcs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtzllhqbnn.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gtnqlewdwg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xinyue.icu/Article/details/gtzhdsymdp.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gtzidqwblv.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtopmpamcv.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gtmvhxpbiw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtusmosjbk.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtokugxljt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gtwbenunyc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gtoagkcmvf.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gtizmtdzeu.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtymnerdbg.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gtfrdtasyw.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtvcpicpuu.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gttkxbqqly.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gttzlvdijl.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtmbidxndx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqcfanphs.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtrhnwphrq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemjhfbuo.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtakisdumr.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtqtpupozv.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtooowhgrj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtkkssocjw.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gtefntfsbw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtyvljwebo.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gtqfsmqrlt.html

for (i <- 1 to 10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtrmgzhcha.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gtrslwjivm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtslesvuni.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtaizgdsyp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtzlwpnfjp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtltjuzlmp.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gtpivfrghm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gtjvaqyiax.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnqzz.top/Article/details/gtpwsayvqr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gtpzuhggmk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtllolcpad.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtpqrejpdf.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtczrjcanj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtsfadjyfw.html

[U05] Py：列表去重且保序
来源：http://dali.ivvv.top/Article/details/gtskcsrheb.html

list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtrfckahdw.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gtwisblvxk.html

{**a, **b}
来源：http://dali.dianchejie.cn/Article/details/gtzbnjwgzt.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtxxspxthp.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gtumnratpw.html

[U08] Py：展平二维列表
来源：http://dali.birdmap.top/Article/details/gtfugusgjs.html

[y for x in nested for y in x]
来源：http://dali.vqdsnc.cn/Article/details/gtjfifpnln.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtyjccquxi.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtbfnrtwea.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gtostniixr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gtcavxsygc.html

[U11] Py：生成器表达式
来源：http://dali.svipenyu.cn/Article/details/gtmoludfze.html

(x * 2 for x in arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtjeyfuxbo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtzcxekule.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtpgrvageo.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtkwjhkhcr.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gttkibscjj.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gthgfsazkk.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtmrmxyvch.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtgcbedqaf.html

t = time.perf_counter()
来源：http://dali.yangfankeji.com/Article/details/gtdgfqrhuq.html

[U16] Py：命令行参数解析
来源：http://dali.zhengqikj.top/Article/details/gtbdiggwij.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtpoitcpca.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtktpizdeo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtpaptdtlu.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtvaaqenel.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtzyinrkzv.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gtjhqgvkgi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtijrngavl.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gtzpeunavm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gtcuksjwhs.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gtdbaofvlk.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtdwlivmlx.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gtwdnilugk.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtlpzkxeob.html

[U23] Py：分块读取大文件
来源：http://dali.xylfe.cn/Article/details/gtquslitrv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.redwolf501.top/Article/details/gtrmpwspqw.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gtqzjudapr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gthwrfyryv.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gtbllrmcbz.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtqqvektbr.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gtxvrppbfp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gtjuaxgoqf.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gtbvdhirbx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gtucwhvddr.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gtvnaabevm.html

UserId = int
来源：http://dali.yvedp.cn/Article/details/gtopkddexw.html

[U29] Py：属性校验
来源：http://dali.wangdashe.top/Article/details/gtuhtdgpzg.html

@property 与 @x.setter 配合
来源：http://dali.pengpengdd.cyou/Article/details/gtafgtuhcp.html

[U30] Py：数据类
来源：http://dali.jinqigufen.top/Article/details/gtetxivtyr.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gttehzegil.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gtmfmwsoeu.html

python -m pytest -q
来源：http://dali.shzxlz.cn/Article/details/gtcspriybl.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gtkfemdqrj.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gtwkpfhfnz.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gtbwqfbofe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gtmsglwljb.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gtkczebree.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtmyaoryme.html

[U35] Py：发送邮件
来源：http://dali.meibo888.top/Article/details/gtkdtiqdrp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbmgaecv.html

[U36] Py：定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtsifsyxpk.html

schedule.every(10).minutes.do(job)
来源：http://dali.sweek.top/Article/details/gtpmowdzqb.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gtumpayidr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwegyvlr.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gtlukmbarh.html

Path(__file__).resolve().parent
来源：http://dali.snrcjt.cn/Article/details/gttkydsrej.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenzaomai.com/Article/details/gtntimemrj.html

sys.stdout.isatty()
来源：http://dali.yj202588.top/Article/details/gtqwzsdnkj.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtoumsezgc.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtqoaboqlo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtaqpecotk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gtuoecfuap.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gaohongyu789.top/Article/details/gtzbndbdyw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gtkzzciebx.html

[U43] PHP：声明命名空间
来源：http://dali.xylfe.cn/Article/details/gtyvefuvst.html

namespace App\Http;
来源：http://dali.redwolf501.top/Article/details/gtzcaytnti.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gtpzjpfnjz.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtozojfeif.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gttkukmoxi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrhpvaekw.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gtfiqvwoxg.html

?string $name = null
来源：http://dali.ivvv.top/Article/details/gtahriizrx.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gtajudfzrd.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gtmjxvkfay.html

[U48] PHP：纯枚举
来源：http://dali.316326.xyz/Article/details/gtysymcjqj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gtretbxrty.html

[U49] PHP：只读属性
来源：http://dali.smart0.xyz/Article/details/gtrtzyxoqn.html

public readonly string $name
来源：http://dali.yvedp.cn/Article/details/gtjmljwzmi.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gtrphbfjoq.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gtgfdnjbcc.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gtpmckfwhn.html

[$a, $b] = $arr;
来源：http://dali.cashguo.top/Article/details/gtwmaltgit.html

[U52] PHP：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtojzupboe.html

$double = fn($x) => $x * 2;
来源：http://dali.ybcxt.top/Article/details/gtzkkeubqx.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gtqlrlepnv.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gtwmtywmup.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gtrnubywrn.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gtuidyrfdz.html

[U55] PHP：match 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqsrrvqt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyonidlo.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtuagexvcz.html

f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtqaznquzt.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukznnicd.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtkacufomp.html

[U58] PHP：数组三件套
来源：http://dali.jqgfzy.top/Article/details/gtwimvtkjo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gtukuegeak.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gtmiwwiboo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtwbyosesh.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgfzy.top/Article/details/gtlrfesozh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hywenlv.cn/Article/details/gtekwlrmvt.html

[U61] PHP：正则
来源：http://dali.gaohongyu789.top/Article/details/gtfngvdgjh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtqrrdhfir.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gtlvnytxxt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yonumen.top/Article/details/gtefujcmwm.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtjobgowbj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.haohaochexian.top/Article/details/gtbdtqriyb.html

[U64] PHP：目录遍历
来源：http://dali.sxryk.cn/Article/details/gtprfxxntv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hongshengwenyu.top/Article/details/gtxmooouhf.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gtvkpebvfu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtlmjkawpq.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gtqihewcyo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gtzgjnplmf.html

[U67] PHP：处理文件上传
来源：http://dali.haohaochexian.top/Article/details/gtfxhgezbp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dashuyun.cn/Article/details/gtqrecwoqz.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gtzdmpjioh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtepjiuvcq.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdtmzoni.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gtmwothxkf.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gtdlbkfsbn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtjxxdvizy.html

[U71] PHP：抛出异常
来源：http://dali.yvedp.cn/Article/details/gtzjvdkjop.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gtocxontuo.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gtrkgyravj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dianchejie.cn/Article/details/gttidzrxvk.html

[U73] PHP：读取 ini 配置
来源：http://dali.yonumen.top/Article/details/gtaxsmoteq.html

parse_ini_file("config.ini", true)
来源：http://dali.hongshengwenyu.top/Article/details/gtxncodwte.html

[U74] PHP：读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtadluoiwt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gtnowkepvh.html

[U75] PHP：依赖注入
来源：http://dali.yongpay.top/Article/details/gtunvkpqcg.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gtpnpkgkye.html

[U76] PHP：简单路由
来源：http://dali.sysykeji.top/Article/details/gtbtyfcfqw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuanzhike.top/Article/details/gtjmihtscd.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gtvhjdwtnl.html

composer require twig/twig
来源：http://dali.wangshuangyany.cn/Article/details/gtbdkhehva.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtmeerxdnc.html

composer require --dev phpunit/phpunit
来源：http://dali.xuetiantiany.cn/Article/details/gtlmakqluz.html

[U79] PHP：静态分析
来源：http://dali.hfpthk.cn/Article/details/gtgqxlhctw.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gtuikdrsnk.html

[U80] PHP：代码规范修复
来源：http://dali.yuxming.cn/Article/details/gtcnqwjifh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gtrovqlsuq.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyqxcxuw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gthxbyezko.html

[U82] JS：package.json 脚本
来源：http://dali.yonumen.top/Article/details/gtxtzplyws.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jyoumei.cn/Article/details/gtuwrnkjhz.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtapkpgijk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtpvqahiip.html

[U84] JS：CommonJS 写法
来源：http://dali.birdmap.top/Article/details/gtwhhmzrho.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sufxvd.cn/Article/details/gtlgjjphca.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gtqgghtcvr.html

a?.b?.c
来源：http://dali.jinqigfzy.top/Article/details/gtewparele.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gtuvlckojg.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gthlcetbez.html

[U87] JS：解构默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdengjhd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xylfe.cn/Article/details/gtmtqihxyi.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiparbrt.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gtnjaaevuc.html

[U89] JS：数组去重
来源：http://dali.xylfe.cn/Article/details/gtgwpcpwzk.html

[...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtfnffngzs.html

[U90] JS：数字数组排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaspkdzx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtzaonwoxt.html

[U91] JS：对象键值遍历
来源：http://dali.tianlin.xyz/Article/details/gtmqzytynk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nanxuanxn.top/Article/details/gtnuvhsvrr.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gtwhosvkdj.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhorucdv.html

[U93] JS：模板字符串
来源：http://dali.ivvv.top/Article/details/gthdamydbg.html

`共 ${n} 条`
来源：http://dali.wangshuangyany.cn/Article/details/gtizecpjsg.html

[U94] JS：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gtlpmgqlnt.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtpsnzydny.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdmtdtvv.html

new Promise((resolve, reject) => {})
来源：http://dali.shuidangran.top/Article/details/gtdrxvfpwf.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gtuvzjshdc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gttetzptfo.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gttdvlvmdx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gthgownbmx.html

[U98] JS：fetch 带 JSON
来源：http://dali.sysykeji.top/Article/details/gtyfzlkulo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gtwlhuumxw.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gtrlzbritv.html

el.addEventListener("click", e => {})
来源：http://dali.jlsjyb.cn/Article/details/gtiqggaxcb.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gtigskcfzf.html

document.querySelector(".item")
来源：http://dali.sweek.top/Article/details/gtrqlrilzp.html

[U101] JS：classList 操作
来源：http://dali.cqqwz.cn/Article/details/gtsnwzgfld.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gtocygmueu.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxmlgozw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcihbkgey.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gttzsqnazy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gtfspeicqg.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtjvwmigzc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtmmqenqxk.html

[U105] JS：节流
来源：http://dali.vqdsnc.cn/Article/details/gtabhungfk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gtswgtxiub.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gtryqhfttd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pengpengdd.cyou/Article/details/gtwetgrvlb.html

[U107] JS：数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtnhzcujrs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtlblndymu.html

[U108] JS：随机整数
来源：http://dali.tian-w.cn/Article/details/gtgibmcqok.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gtywiblops.html

[U109] JS：数组分组
来源：http://dali.pycfn.com/Article/details/gtytnqoygz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gtxxnpthsc.html

[U110] JS：数组分块
来源：http://dali.yj20258.top/Article/details/gthtpysnmi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxinkj.top/Article/details/gteodenogi.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtpzyrxjrt.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtzqkxgdaj.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gthxilvgvj.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpczclzbm.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gtnuhqzgex.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtsylzcvlp.html

[U114] JS：JSON 深比较
来源：http://dali.gotoacloud.top/Article/details/gtitcjoqpq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtpgtxulas.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gthqzckfbu.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtzanrogth.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtomrzbizx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gtxazblpuq.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtjoyalytx.html

npm i -D vitest;  npx vitest
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnchiuenq.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gttcqyzneo.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gtrunmombq.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtlwanvhdr.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gtyjhwmjia.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gtqrieetsv.html

import.meta.env.VITE_API_URL
来源：http://dali.hywenlv.cn/Article/details/gtqsygxwqf.html


<!-- 参考信息 -->