代发 wailian999

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtqjsfaytf.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttstkhfir.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtvrcovaon.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtvxqgslns.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gthaciopeh.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gteqwysgtx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtdebtwahd.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gtqorzcvxk.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtojixebns.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtjrbineuo.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gtqtlpknwj.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtwqgszfiq.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtqovvrmgs.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtomnftqnn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtwmmuodgh.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtizdnjqwa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtftqquypf.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtbrhaqwzh.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtbzbvxtak.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gtvpihuyjo.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtvrcnqyzh.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtxeprbjyw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gtkdeagezk.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtzrrgmosu.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtkdjjsjmw.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gttrqcrtdw.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtskipxkfl.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gttxlqijrm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtkxmjwmmk.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtdnmvuerk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtexelywgu.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gthpiqykmf.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtuefhbzls.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gttylauqyf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtyxpqxbxd.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gteljelaby.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtirvejgxj.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtaioleftv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtcincuyzg.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtzfyilznm.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtlsdwtklm.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtfctmeqkb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtdoazrfxi.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtvpdswhkb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtoosffmgo.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtzwawypcs.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtnpqspdtm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqsjanbqe.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gthcewuofy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gteilwcrvq.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtemxmixhs.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtutgiqftk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtrjpytyur.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtqnjegbwf.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtgdrnhhdn.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtjhyakfzt.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtgfwfflqz.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtlywhyqaf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtuvzlepav.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtawmbnzen.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtbirjurwa.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtskypkcvw.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gtyyyvuqon.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtosokufea.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtvzyamoqw.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtvfbjagmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtkadybgzk.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtdmlzdecq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gtpdfomqnk.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtlpwrxedy.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtyqohists.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtwxvrzntx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtnqvkeghh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtlbxlxjiz.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtctvwsqax.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtnqkptwuj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtnjjsincz.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtvbjobnlv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtvxbqwnpn.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtijtljrxv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtpykgmdpt.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gttyijbqin.html

(double) a / b
来源：http://dali.tianlin.xyz/Article/details/gtlwssektf.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtzflrjqmx.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtfftzzorw.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gtrzufrcci.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtsywcxdcb.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtzrotqeso.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtrwjvrotp.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gttvmrzchs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtykauqxee.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gtvpvurbml.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnttgkfm.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtvhhrpdye.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtpqhrjqwj.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gtoghwncwx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtxqpfxjbf.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtyavmackc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtprtlqjft.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtnbhydbyj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtklmseiqr.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtxnttmjze.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtrzlewncs.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtctedlfkl.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtikadiktz.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtcbnbmkys.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtzeomgkcp.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtiunykwiv.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtiiphhcbt.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtbhsddntn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gtpsidants.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtzacayezu.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gtyfkhipgk.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtyyigjopz.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gtcevoiylu.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtwhukiyer.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtwprbcart.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgodornot.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gtxzvnpqsa.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtypvtvcsh.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtpmtkijpt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtuqljekju.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtrppppqmi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtvohzvcwy.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtvrlzkpws.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtzbbzdzhp.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtaqrkarmk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtqvqycouk.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gthhumqjrn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gtfrrexzlw.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gtzsdxyenj.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtxpbqobqd.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtxlipiqbw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtuohtyytn.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtrpbgzodt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtxkmxugth.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gtxufrkjzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtzrkmjcza.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtiexwbowp.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtreibzajs.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriwzntfs.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbbgfleb.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtcbxteamb.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtathtpvno.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gthvuhimnd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtfcerufcd.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtxrhjzdww.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtqaeyxbco.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtcgncmjkm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gtovslnazw.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtsyvmblvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtjkclccpg.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gtgdilrmzz.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtqcnrirgr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtywqxbnyv.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtbrlgunve.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdkzmgwk.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gthugagnxo.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtmfntcvug.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtrvtcojlu.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtcsgxtfkn.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtoredloea.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtdjymxcsh.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtmkficitq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtshxqpsgn.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtwqkcvqzf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtahqvaxvg.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtskzqqwpf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtgcvycdyv.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtmnmvhxqy.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtgdzqttpr.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtlxnxdray.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gthnlktlfi.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtjzqvnxfx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtuzrdgvua.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtqbubhvah.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtjwgzrefn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtckwlhpcf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtydcvotdg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqturamcq.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gthdpcncwx.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtbonncbas.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gthjvorddr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtdeijwors.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtlwhldieg.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtbdcmccoy.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gthbctywhj.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtyiycagxf.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gttcmgwyly.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtrukfwhxs.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gtsilvzokl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtvbhbyyaj.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtsbdyxjdr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtczyxazgb.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtexhuonii.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtmhfqhpob.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtbglzuker.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gtdarmmoye.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gteyxryyde.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gtqrkconfp.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtzwldanru.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtdfwyxobb.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtruwdgrop.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gteycyormp.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gteiradnao.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gtjntggsaj.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gttfrumaxu.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtbylokfgz.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtcmsxpoqt.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gttvqmllfk.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtqwndkfqk.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtygjxewih.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtmssensex.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gtjjkrwefk.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtjyjskddd.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gtljzvywog.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtbjccwjug.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtkmlypoaf.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtsfrwmijs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtshbjghwg.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtdxeekkne.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gthlbflpip.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitfaifwl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwigoanlx.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gtkpeuoxwv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtuymrhbbd.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtvueqyfol.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtmcuaatin.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtpcntkomg.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtpkceroji.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtoxfbotnb.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwirtnvfh.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtchcvgqqn.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gtxrithjeu.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gtoyvnuhnp.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gtkvfyvhbx.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gtbhxgjwvy.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtwuumgzft.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtejgjrjkm.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtbpfpngpy.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtjfiplvgw.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtiujpnpla.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gthtokbycq.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtolzwmzpt.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtanqqkkou.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtirksimlm.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbejhncjs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gthwvfhrdk.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtjnioftks.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtviblkjsj.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtrtaorbuq.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtssbyhvef.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtiitglyyx.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gtpwyczggm.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gtpmhhgjwa.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtbvwdljvz.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gttrdtvfua.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gtvjeuehpz.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtqednkvdx.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gtzosutqpu.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtnsrffqfz.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtbazneplu.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtrnyholgn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtacscoxxj.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtuekgobjt.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gtvqwwgror.html

[T44] Perl：条件
来源：http://dali.cashguo.top/Article/details/gtvvofumqv.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkqtikodw.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprjelcty.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gtoytxvwgp.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtfjtnpyqh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gtkbswwfxv.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gtodmohevc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xinyue.icu/Article/details/gtmeadsguk.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gtcssinarw.html

$s =~ s/old/new/g;
来源：http://dali.yuxming.cn/Article/details/gtjkbfbyuc.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtufwwzmij.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtvtsbxxjp.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gttjcilisv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtperbotwl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtfpkplzxd.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtohhjrfnc.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtgnoyrrjr.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzfcdfzl.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gtttjsirrn.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtqqhtdlrq.html

s"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtydflovve.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtumyrflpd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtjrecdaln.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtqwfequai.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gtmuvebdxl.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtllpbmsay.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtidkbchud.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtmrdgpjbu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtiburkmym.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfntmszkl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangdashe.top/Article/details/gtfsuyzjog.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtdwlyeuyz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gthzvvvxtu.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtjdaryirb.html


<!-- 参考信息 -->