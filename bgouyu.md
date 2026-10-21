代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtixqocrzf.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtqzthoxuy.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gtsazhersv.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtnsgbgrpd.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtrwprpqmg.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtwsggekpf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtkhhsskue.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtbidsocrc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtuapfqthg.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtybljambw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gtmclheyvt.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtpvuxswed.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gttoqhsbyw.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtfodwbtje.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtsdalhqfh.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gthyhvmwoa.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtaxibrvuu.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtxkrraumc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtooqlqrqs.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtgyeplhmx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtyohivjiy.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtxgdabyzs.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtmmwescgs.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtzbedgafv.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtcmbpyade.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtwfmlgzmg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtsiilxcph.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gtwniysuws.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtnjaxxhel.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtxunrrtch.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gtfvwwlnws.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikmoavtz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gtglcbekdx.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtiuwzwpke.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtolufdbcc.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gttydpdcrj.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtywjnqzvm.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtgntroolr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gtvvhqeqpx.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gteehqoyjh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtdiccsktf.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtreuljsvk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gttwazqopo.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gthpqdjsxa.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gtbruesiku.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gtfkhlnsyq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gthyikhmaf.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtmeiurjdl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtaqrnennz.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtwtfkrkxr.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtdbnzdevo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsfnxdpqt.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtmxlhkcfd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsneuledu.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtrbxplicp.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxphpwokh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcixwiag.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtwhbmtqyb.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtpfctpfik.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtzparttex.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtnksboipf.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtetronbsa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtqapeprld.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtlbcwwyrr.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gtgjoflgvy.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gtiyzmpevj.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtzyjowtkw.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtjjsaswgr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gtejqmabcc.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujepdnnr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtzbexmdhe.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtsvcfplwr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gthtozxivk.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtafhipxbm.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtreyvkzyk.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtkuiwwnzv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtimbptmfu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtbaqgktsx.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtknpqghrf.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gtudelnppm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtdkxwwcws.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtivxfqmiw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gtffpqcggs.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtzyjevjcm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtowgslnnw.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtjfimmxjj.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtgrrkmnlb.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtxrjocnbp.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtkihvhdtm.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gtmfadaeqz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gtmbyjckqv.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtadfduiqq.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtdhjtrrrc.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtpabdrnho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gticanstmz.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtwnxbjhmf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtfweiqtcw.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtsrzogdfw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gtsugthebt.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtqmispggh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtbxxcpjqz.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtksgbkjej.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtlojeyacb.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtaxztmyvf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtxcwswajk.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtijpjszab.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gthykvjzoy.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtfzoqpbqi.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtramjufla.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtypczdjop.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtiqrgfude.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtpbnrljbx.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtkjzaibja.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtnamsbtfr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gtyjbldexo.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtymdpfwvq.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtadvltgwd.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gthbeklxzj.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtggwxzrkk.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtuzmwejra.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtirhmmszg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gtfuiydvsi.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltpajbss.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtccvojaps.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfjnqpir.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gthwecsssv.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gtbdzvhmtd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqpmiull.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtwekuxrhb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtuosemons.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtbpwkxotu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtpieqrtsk.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtcvrjczpz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtukbmmgcf.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtpxgpshoz.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtloxuapfs.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtnpqfrvmg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtlnatuedw.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtevlesesn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtnvietwvq.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gtgdjeroyu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtqekgtwzl.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gterwxmaxs.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtzwbnfbwc.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtebuuhgxo.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtjbeeuykg.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gtouaqydmg.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gtdbpnywsj.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtadeusphp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtpgfzknsc.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtgwrvvnqq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtbcddhoqn.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtqusfgler.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtsnwafspi.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtwaciidne.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gtvmfowadj.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtysmrbvum.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtvdopgnif.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtbkmcmshi.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtufvclgog.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtkkuqafwz.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtmpyrncod.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtjybvbbxc.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtqmpafwbi.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtzcurqwte.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtpnjmgqkc.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtyaokkgiy.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtdeznjded.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtxfrptods.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnmlkypr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gthvudrfxe.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtrxkbkxms.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwumfcgji.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtszelkkpq.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtnxpjjtxo.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtgvlrkrvr.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtlegzdflp.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtyrxxckge.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtnixeuzsh.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtigfhvgew.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtaiyuqjus.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmvuehipl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtrggoiibg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrykbuomq.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaohvrho.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtwmogmfsr.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtydkrpqor.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtjmcyujiu.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gttweqtqfb.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtnmljzqxx.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gtmpaqafro.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtiwyursjj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtxprjdrel.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiuaqiib.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtwiegnbul.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gtydqrynel.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtnriiaper.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtkxzxxcks.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtuycxarvv.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtfthirgjy.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gtdxmjnbsq.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtqdesmmcl.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtqdpbyopa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtimoqsknl.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogkpspvy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gtzrxrvnob.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gtoofdpesx.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtcewrexxn.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtixfamgob.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gtqxrrlkev.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gtbferdamj.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtbkypmkpd.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtrfmgpivt.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtdgiwwyzu.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtetyhhsax.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtbvenhijk.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gtckuknkez.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtpgfvtaeb.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtamnarxfr.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtagwbabvp.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtozxbfonl.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gtoohlnifx.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtzbwkvcyx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gtpdhytwfy.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gtdjbamfvp.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gtjutoxinh.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gtgoxixekl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gttpygyytk.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gtsorsecet.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgkbotya.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gtxnxqhfjs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtrtstofei.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gtbugmbtfv.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtbswgwkts.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gteanwhbwc.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtekzxlcgh.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gtlrgajssb.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gttoptzdeo.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtstcdjsbh.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtgbdcaiio.html

[T29] Swift：guard 提前返回
来源：http://dali.cashguo.top/Article/details/gtygsxdyse.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gtnvcrawgq.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtiiwrfbvb.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtyntsktvg.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiuanrfc.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtbnkmktal.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gtgcmlbdes.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gtwoxjtqyo.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtsitdourj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gtfdizgsyc.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtqmwqumze.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gtmctcyech.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gtjwajrawe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gttcuaxvtx.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtabagchkv.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtpzlrateo.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtutvacffz.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gtcllexilo.html

[T38] Lua：条件
来源：http://dali.cdnleiting.top/Article/details/gtugsnetom.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtqbyetnov.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtpcvpbpbg.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtzagdkeqp.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gtwafoiyop.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gthvwsseys.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gtbakbcsfs.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gtoudrauja.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gtsnfrqtve.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtsdbhjdqv.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gttpkzybqu.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtiydrlvme.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gthzdvvtfs.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjefbuno.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gtillibdkg.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtqsevjeog.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gtkwlcgpte.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtqtjrirlk.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtvuahikxj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtxmwlhlme.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtkdycyfzr.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtgyeueidd.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtjmwlkowu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtnbmgmzub.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtnerivwyw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtvamtufpo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvatwptjm.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlzljizd.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtzpupmbli.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gtouksxxct.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gtzumyrhex.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtrsezkycy.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtloqzxvve.html

[T54] Scala：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtchvtmtfr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gtgsfkuadh.html

[T55] Scala：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtdcgnplcj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gtpfjrauqu.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtaumerbqq.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gtopvtgvmj.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtzbjylakc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtcjgxdlpd.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gtyvvbgflw.html


<!-- 参考信息 -->