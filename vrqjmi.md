代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gt2xzwcjegv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayyxjkng.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gt2vaojsoof.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gt2lcljflzk.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gt2cqvcthrs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gt2lalzjwag.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gt2bgyyrslv.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gt2namxysyq.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xutoldrs.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gt2momuhlrf.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2ekyyktoh.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gt2pbkhwvgd.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2pgxhpyhq.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msadzkss.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gt2oxvdwapf.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzwibpjv.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2ybmpvnvs.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gt2wspgtlqs.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gt2dkvrotnu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2aeglzfdr.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2oihxyzay.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gt2udiuhnws.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gt2yrdjjikt.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gt2evomevik.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gt2szqfwojp.html

for my $x (@arr) { print $x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kecuterr.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gt2uxuirprc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2sjjcehdg.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gt2walyjogi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gt2hyqrwfac.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2pdrcyzsw.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gt2dfocakiq.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gt2qzpdonxj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtvfleve.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2lcipugeg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gt2gofenxhs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2ceeyidnz.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2aytjwcnw.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2pnbkulnq.html

[T52] Scala：变量
来源：http://dali.jiagoushi.top/Article/details/gt2syfvwvwx.html

val a = 1;  var b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2nmwhiovc.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2otprtbwm.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2sfickfqu.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2vwulpwxg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gt2pjnobtmw.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2zedgejlc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gt2tdthssjy.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gt2odxjqijk.html

case class User(name: String, age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhaklnwe.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2jbqewgtw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gt2fzncwnjj.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gt2udbsvbpg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gt2qnnixxec.html

[T59] Scala：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsceoubq.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gt2rbfrodsy.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gt2lbqybgrz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gt2uzkjbqjn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ryyzqdbs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gt2lmijfcjc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2zhqjffmy.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gt2bwzjkemm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gt2inpfbrxd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcwldkkg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gt2lcmhrmss.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gt2gbkknhqi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gt2hnxeidal.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glrddmgi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gt2reruavuj.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gt2reumfird.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2utnvpybt.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gt2qswmuldi.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfhyizai.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gt2dlyyfogz.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gt2stucgdnl.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gt2qlutjapp.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gt2iggievig.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gt2vhdtjwbu.html

max(d, key=d.get)
来源：http://dali.svipenyu.cn/Article/details/gt2edgrahom.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gt2ojaxnghm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gt2rvgqpegd.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gt2cpgrjzpo.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gt2aovkkjnz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gt2qsszufpk.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbgsflzl.html

[U13] Py：固定长度队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phzvdevo.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gt2yaumjqvu.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gt2wdahostd.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gt2nzouebrk.html

[U15] Py：高精度计时
来源：http://dali.kuanghao11.cn/Article/details/gt2dtbmiwam.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gt2kzkmwbtp.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gt2vogrerdm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zycfv.cn/Article/details/gt2jcnkjxqs.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gt2qvihyjca.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gt2wixlbakm.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgehaqfc.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2byradnad.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gt2bykmklse.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xziqi.cn/Article/details/gt2lkhcspha.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gt2yaemsgqf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guowangkeji.top/Article/details/gt2cykwnewh.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gt2nymalxah.html

@contextlib.contextmanager
来源：http://dali.dianchejie.cn/Article/details/gt2brlraran.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gt2vdjqzozw.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gt2wzymmrqo.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ywvtmewf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gt2ezwcuprr.html

[U24] Py：路径操作
来源：http://dali.dashuyun.cn/Article/details/gt2haqxuzbe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2npdlbvez.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gt2pammldsz.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gt2bqqygwji.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gt2hlwmhlgh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gt2bjolscpy.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gt2azhcuvkm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj202588.top/Article/details/gt2aqxiuopi.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gt2pugcunrv.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gt2pnedmpue.html

[U29] Py：属性校验
来源：http://dali.gzhubu.top/Article/details/gt2vdygyqaq.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gt2nnoxrhpe.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2evhashye.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyogooff.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gt2wqqfbyvw.html

python -m pytest -q
来源：http://dali.shzxlz.cn/Article/details/gt2rynpktch.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gt2agjtvgre.html

ruff format . && ruff check --fix .
来源：http://dali.guannengcc.top/Article/details/gt2nvdmxems.html

[U33] Py：打包发布
来源：http://dali.pengpengdd.cyou/Article/details/gt2wenwqkdc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gt2zpbvqdpt.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srrngyyr.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gt2gzrihgev.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gt2yffknlew.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gt2exqdxpbj.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2jbfjappq.html

schedule.every(10).minutes.do(job)
来源：http://dali.gotoacloud.top/Article/details/gt2ylnomwep.html

[U37] Py：读写 Excel
来源：http://dali.gaohongyu789.top/Article/details/gt2nvmypekz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gt2ikwptkwh.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gt2qyvrhdcn.html

Path(__file__).resolve().parent
来源：http://dali.vqdsnc.cn/Article/details/gt2uxbstyxl.html

[U39] Py：判断是否在交互环境
来源：http://dali.dianchejie.cn/Article/details/gt2nzagsvoi.html

sys.stdout.isatty()
来源：http://dali.zdqjudy.top/Article/details/gt2fthrzdvk.html

[U40] Py：打印到标准错误
来源：http://dali.cucudq.cn/Article/details/gt2ufzpbrjl.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gt2khmjmvya.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gt2dijexblw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gt2hcowarez.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.mhx1999.top/Article/details/gt2ximjxgof.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cldnobsu.html

[U43] PHP：声明命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2pwbdpqyr.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gt2xpzfkcpt.html

[U44] PHP：开启严格类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpfcgvzp.html

declare(strict_types=1);
来源：http://dali.cashguo.top/Article/details/gt2tujgwloo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gt2posufnva.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2czpvfljn.html

[U46] PHP：可空类型
来源：http://dali.nanxinkj.top/Article/details/gt2wndcsnaq.html

?string $name = null
来源：http://dali.jianghu66.top/Article/details/gt2uzxefjxy.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2oipftbpq.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gt2mwpoanbl.html

[U48] PHP：纯枚举
来源：http://dali.yj20258888.top/Article/details/gt2oxmhophs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gt2ktewfpmz.html

[U49] PHP：只读属性
来源：http://dali.cdnleiting.top/Article/details/gt2mzobajlp.html

public readonly string $name
来源：http://dali.iojbl.cn/Article/details/gt2htjdbogk.html

[U50] PHP：构造器属性提升
来源：http://dali.wangdashe.top/Article/details/gt2nfcfsaln.html

public function __construct(private int $id) {}
来源：http://dali.yj20258.top/Article/details/gt2xtztusee.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxcyrfhc.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzyusyzd.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gt2axvhfsuh.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gt2wrqujokh.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gt2ncaeyvpn.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gt2cbtrqokw.html

[U54] PHP：空安全调用
来源：http://dali.nanxuanxn.top/Article/details/gt2qciyjsqi.html

$obj?->method()
来源：http://dali.snrcjt.cn/Article/details/gt2guestere.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gt2lnjwwfry.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jprufvut.html

[U56] PHP：命名参数
来源：http://dali.jqgfzy.top/Article/details/gt2ftwldcuh.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vljrftqy.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2tjdjrczo.html

"值: {$a}"
来源：http://dali.yj20258888.top/Article/details/gt2ktmjgzfp.html

[U58] PHP：数组三件套
来源：http://dali.hysaishi.cn/Article/details/gt2hopmkagw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2pkvzexyi.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gt2xwpttnvb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2eslzpqyq.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gt2ojcbjiml.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gt2iukriviu.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gt2ghtcjfuc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2whgrrhum.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aewbfprv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.svipenyu.cn/Article/details/gt2ldkllcxx.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gt2raejvdym.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.andypj.xyz/Article/details/gt2avyadebe.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gt2omdgexel.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zdqjudy.top/Article/details/gt2atmatepx.html

[U65] PHP：会话
来源：http://dali.sufxvd.cn/Article/details/gt2mcukbfii.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2tkbtoavn.html

[U66] PHP：设置 Cookie
来源：http://dali.sweek.top/Article/details/gt2jdnufgbm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.meibo888.top/Article/details/gt2tjiswqos.html

[U67] PHP：处理文件上传
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwdhapea.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gt2mhmgfbye.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gt2kvhmirou.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gt2jdmglzsb.html

[U69] PHP：PDO 预处理
来源：http://dali.tian-w.cn/Article/details/gt2krxrnxgl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.redwolf501.top/Article/details/gt2peraurxm.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gt2vkxvqxub.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gt2ibkjgvvx.html

[U71] PHP：抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2ewkflojf.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gt2pvcwjnbz.html

[U72] PHP：写错误日志
来源：http://dali.hywenlv.cn/Article/details/gt2efxvoeko.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuanzhike.top/Article/details/gt2fecpnttf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zdqjudy.top/Article/details/gt2yjkovoas.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gt2xlfjdxfo.html

[U74] PHP：读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2mvvyctdd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shzxlz.cn/Article/details/gt2ytowuakc.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gt2ghvsmniv.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gt2pffzzdpm.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gt2jlrdzbam.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgufenzy.top/Article/details/gt2vvkwllld.html

[U77] PHP：模板渲染
来源：http://dali.shuidangran.top/Article/details/gt2gquymadm.html

composer require twig/twig
来源：http://dali.yanxiufei.cn/Article/details/gt2plqelwpj.html

[U78] PHP：单元测试
来源：http://dali.iojbl.cn/Article/details/gt2resorirv.html

composer require --dev phpunit/phpunit
来源：http://dali.nwbrower.top/Article/details/gt2haulszlk.html

[U79] PHP：静态分析
来源：http://dali.cheryme.top/Article/details/gt2eguaclss.html

composer require --dev phpstan/phpstan
来源：http://dali.ppjwa.cn/Article/details/gt2vrwrcbjc.html

[U80] PHP：代码规范修复
来源：http://dali.316326.xyz/Article/details/gt2zdnxrgtj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yueranfly.top/Article/details/gt2pgjcmiih.html

[U81] JS：初始化项目
来源：http://dali.chenlongwang.top/Article/details/gt2dgycpzsc.html

npm init -y;  npm i express
来源：http://dali.xinyue.icu/Article/details/gt2mpkcnzhh.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gt2bamnufxp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.9152youxi.cn/Article/details/gt2trwrbbmq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zdqjudy.top/Article/details/gt2vqaemuko.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gt2scpbvorf.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gt2qleonroo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gt2yqwiycmz.html

[U85] JS：可选链
来源：http://dali.snrcjt.cn/Article/details/gt2evixawlw.html

a?.b?.c
来源：http://dali.yj20258888.top/Article/details/gt2houkszqd.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gt2qgbtxmzy.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gt2wtwzmhjj.html

[U87] JS：解构默认值
来源：http://dali.sxryk.cn/Article/details/gt2bxloixoi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guowangkeji.top/Article/details/gt2joqjkgzq.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gt2zkcrptzw.html

{ ...a, ...b }
来源：http://dali.gzhubu.top/Article/details/gt2lmalcgol.html

[U89] JS：数组去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2naqvhzji.html

[...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2szwmejst.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gt2bsaeysxs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwsbmhbo.html

[U91] JS：对象键值遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgjsupel.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gt2pilqfbvy.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gt2vksizvtm.html

structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2bqaapbhd.html

[U93] JS：模板字符串
来源：http://dali.ppjwa.cn/Article/details/gt2vncdyjix.html

`共 ${n} 条`
来源：http://dali.yangfankeji.com/Article/details/gt2ftjyxayh.html

[U94] JS：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2kaksdotx.html

const double = x => x * 2;
来源：http://dali.hfpthk.cn/Article/details/gt2wvyodkhk.html

[U95] JS：Promise 包装
来源：http://dali.hongshengwenyu.top/Article/details/gt2trtkrwbb.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258.top/Article/details/gt2cowykvxa.html

[U96] JS：async/await 与异常
来源：http://dali.gotoacloud.top/Article/details/gt2oxujcoeh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2pmuenemx.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gt2zaonngns.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2dfuslhbd.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258.top/Article/details/gt2txegdehp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tianlin.xyz/Article/details/gt2nokeoedm.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gt2injuthqo.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gt2samnpwju.html

[U100] JS：DOM 查询
来源：http://dali.yj20258888.top/Article/details/gt2mbqphylu.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gt2mwyaxvcz.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gt2portrzst.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gt2pqfaorwq.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gt2nkzrpwgp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhoulong.xyz/Article/details/gt2qgsxoljr.html

[U103] JS：定时器
来源：http://dali.jinqigufen.top/Article/details/gt2kaybrhcb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gt2rwjbgobv.html

[U104] JS：防抖
来源：http://dali.hnxiangtu.top/Article/details/gt2gfqowqdy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2wwkujmue.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gt2qduttqib.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dashuyun.cn/Article/details/gt2phuubtcd.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2rfyxofrs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gogol.net.cn/Article/details/gt2lgdyusyz.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzxgxrvc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2ftbyakow.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gt2ocqdfpic.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenjidiqi.icu/Article/details/gt2ephfnuli.html

[U109] JS：数组分组
来源：http://dali.fzhhl.top/Article/details/gt2zyspabkj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gt2mjtlbrfi.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2pfpogjlk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gt2tymsplnb.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gt2driebkpl.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2asoxknay.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gt2gunmtfbi.html

"7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2vielowca.html

[U113] JS：正则替换全部
来源：http://dali.mhx1999.top/Article/details/gt2pvxeqdys.html

s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2tagbbwjy.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gt2fhyoksgn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2pfsaoqmv.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osctjkur.html

crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2ujgjvxbp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sufxvd.cn/Article/details/gt2elsdkedz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gt2ejsbjlwn.html

[U117] JS：单元测试
来源：http://dali.ivvv.top/Article/details/gt2wohajhyr.html

npm i -D vitest;  npx vitest
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohtperrf.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gt2gqgisjoj.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqpnpxrp.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gt2bzkkiaoq.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gt2txddcdpf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gt2bsjzeqxn.html

import.meta.env.VITE_API_URL
来源：http://dali.guannengcc.top/Article/details/gt2jajxuvdp.html


<!-- 参考信息 -->