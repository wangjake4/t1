代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gt2ijmavplf.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gt2mvfexakd.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2jtezyyjj.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2wlplvqkt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gt2vegfgdxv.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gt2uinbfjsj.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gt2irpockxv.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gt2zxcexasq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gt2ctscdtwg.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2znsgwhkp.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gt2ekhcvdan.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gt2yihzqhhz.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rghztqxg.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gt2blapzcah.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2tzovjrnq.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2tzwiqotk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2umokcsgl.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2shclsiot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suaibwio.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gt2qxubrwxe.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gt2qgjaxflr.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gt2pcdtnsop.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gt2yrhtvuao.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gt2cklmvhvl.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gt2gsbdrzqz.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gt2eqiifqdu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gt2eakyljrv.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gt2druttthm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gt2aqhzzetk.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2nfblsxty.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gt2iyvehtrz.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gt2bdyjrpmg.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gt2myuntaon.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gt2gpoljpaj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2dndysncv.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gt2wpbzvhxm.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2aqoanjyq.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgpxwqmb.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gt2sjdgqcjl.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2uwnuwnag.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaexnoh.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2wwdlhaoh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gt2stuyydrk.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvwconmu.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxdlhzwy.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gt2afvgrgwy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2jmhrlwpj.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2dcwvzqal.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2vgfjhhpx.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gt2mkzivnyp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2ypjhimso.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2uqyvimjr.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uftuzwrx.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2weldrpac.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gt2gyzsvgoh.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gt2zvmvfsdf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gt2qozwzkru.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gt2minhyisx.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gt2dgleubxs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2yzvmbfhz.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnwirjas.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwmnpdjt.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2rhosyyed.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gt2cbrcvcdc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gt2tdufnafi.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2nqquodhb.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkzcesrf.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gt2okhbwpac.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gt2fdfnflus.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gt2rxtlcivf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2cfbdzvfj.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gt2fwptfjir.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gt2kykmvdkm.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2jlxvgsby.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gt2bjauvugp.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gt2ohdplbxf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gt2idsjqvaa.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gt2pqkiegmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gt2uvyzmbqy.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gt2pavwugkv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gt2pnpisuho.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gt2cxlqvnfy.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gt2umiixzaj.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2zyhvseaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gt2fjzdpnty.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rakshhia.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gt2klfvnhlq.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2hpvxtduu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2cpmussum.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gt2eqkpkmkf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gt2wdhgpuad.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gt2ougcdwtj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gt2sxiuczvy.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2uuraeifg.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gt2frxxwxeq.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gt2caniympy.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkcakada.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2kwizdtfc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gt2eswhzuvl.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2tyqehimf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdottwa.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2ehlysnrw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2cswaogst.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gt2obnjmkkg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2husxfqxh.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gt2ynkssaye.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gt2jiwqtbyy.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2wlhntieb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2ktcqgxza.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2relpxwaz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gt2gbnjvivm.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gt2gbkrwici.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gt2heqieasw.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2zhogjzci.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gt2zbluandw.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gt2nluyufsv.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuagzikr.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltchwjmh.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2fkozdfdn.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gt2mihefplu.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2wfvjhrow.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gt2sjszxhir.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2nxuntrdm.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gt2bawcpoob.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gt2lggkbhhv.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gt2axqiwqqw.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2bqnbszwq.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2dztxfaln.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gt2ywznqnyt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gt2uiziaspi.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2wgefqzam.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gt2eevqvpdv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlotjdw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2wmswazzc.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gt2dmwjafuw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gt2yorgliuo.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2uljsslbf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hszizsdz.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gt2cirzztek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2ivwpqkkz.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gt2uayhazcs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gt2nkvpivup.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gt2jhauwblt.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2endxixny.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gt2zyxgarxi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gt2jfalbcwy.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gt2ctdtqotx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gt2zhpplali.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2uhkanebq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uilmzykl.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gt2vsdcgtnk.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gt2vshdkrtg.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gt2fyfzhryr.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gt2mkrejajc.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbfxqdei.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2iyqrjziu.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gt2uyqmqhot.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gt2baljszpo.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gt2jgvngeey.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gt2pziflqmg.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2simvyntv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gt2vbkoqnnl.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2eygsbauf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gt2fuftzblx.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gt2pqgqhgyc.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gt2eqowtzvb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gt2xlmzvusy.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gt2ixaflvwv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gt2ixtfcful.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gt2irdmgazp.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gt2iendvgap.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gt2cmttrmek.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gt2fhcnxkjj.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gt2urhqemqv.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2sggjxkyu.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gt2roqvjqpf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2avlsrhwv.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhfblyvp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2weewdorp.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2lbuukfho.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2uevowgpa.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2hevkcpll.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2yitlvgpj.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdyhsvay.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2ogliyypp.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gt2pvmnqshp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gt2thjymdhd.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2dvysbexx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2kvcmlqbt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2xegtrcnx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jomipjil.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccxtqrrs.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gt2ofyrcqmz.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2rjfvjhnx.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gt2hvnxngpo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfopvyti.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gt2eeqesweo.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2tcauzxnp.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gt2vshaxdct.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gt2tduidkwk.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gt2tacdyizd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2orlveluw.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2jxxihekk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hiaorxrr.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2efihmlns.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwvbzczz.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gt2cehlrjlu.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2uhazmsnv.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wikbffoh.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttcuyibz.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2jbiolwtd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2kqoeastx.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gt2aarxykpf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gt2khkbfgot.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mtamxyzc.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2ukvcxnxj.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gt2spcsguzn.html

val m = mapOf("a" to 1)
来源：http://dali.meibo888.top/Article/details/gt2tvwsaqce.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gt2llfuhaep.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2qhdgqago.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gt2sqtuwifr.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gt2htlzxbxk.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2nopqgsla.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2qwehkzfr.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gt2dvbtaznu.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gt2ggiwsjjp.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2uqkuciqa.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gt2rphntrov.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gt2lxralgej.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gt2fzcvoniu.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2xooyevcx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gt2bmclfabs.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsyrxqiu.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2iljgilwj.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gt2zilmjtja.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gt2tpkhfvvc.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gt2sdgzhwaq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gt2pddflkay.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gt2sqptjlih.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2uydrjhfw.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gt2tlpacpez.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gt2mdsrztxh.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gt2pxziqxmf.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2kwlhhfcf.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2qjporwee.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gt2ddgokvsf.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2gzbztlfq.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gt2ynkpxqmb.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2idgaiuti.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gt2cvhdxssj.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gt2uozqmsjx.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gt2ftwmftdn.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2lzxuuyip.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2yxfsktkh.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gt2iwlhpaav.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gt2fisqryxh.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gt2dmylzjuk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gt2hbnuxkys.html

[T34] Lua：遍历表
来源：http://dali.andypj.xyz/Article/details/gt2rovzicks.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gt2kskvyden.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gt2ojoarmmt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2axpoiaqq.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2rnvjvctx.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ardrecve.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2krerfrbn.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gt2ahwdwxsn.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gt2ryrpldko.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gt2skdcbddu.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2xtjqldya.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuatkzvb.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gt2kmnyprgn.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gt2nokzqugt.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjmszvyj.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gt2hkekgoce.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gt2oecqjkjg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gt2xzbdfhso.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2jabpsgfd.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovxtkrnb.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gt2cnooyozo.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ngjfqmun.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gt2hzdmwsov.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2czcgzdto.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gt2qwvtpjos.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gt2auyvyjqb.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gt2nhkovjzu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oepzyivm.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gt2vkwfnttt.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gt2nitobcfp.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkgaffuz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2jgunneje.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2vhotfuri.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gt2njuodgou.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gt2xybojttk.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gt2dkxcebpl.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2txpnnfce.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gt2lqdotudb.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gt2qtagwbpo.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2cbtyimkv.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2yktgsfcy.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gt2cbjskhau.html


<!-- 参考信息 -->