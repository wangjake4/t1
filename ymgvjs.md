代发 wailian999

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtekmskvzv.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtoadobnus.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtkvqooqoj.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtpgcbryzw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtpoqrowgs.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gttsmzrtld.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxycyrkmg.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtbocrapuy.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gtryybiiyv.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtbnojuguc.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtoiofpsyq.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtycxdcggo.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptafoosu.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtejihgczi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtejiooctn.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gttkibnobo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtziunlbnc.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtombidpnx.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtybeljjju.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtjmxojxjw.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtmmqzspky.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtswwprahx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtebrngroh.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtpfwwpuej.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtgdfevdik.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtdqmvarxg.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtzgchkmur.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtotlxdtkk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gtthmuqnzf.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtkvneeiid.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtxjlcxaut.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gtwjhtchie.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtrprlmlmx.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtfgagcdah.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gthqafjute.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtnyuxdjcf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtubhytiwd.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjralnens.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtrofaynni.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gttpbmngot.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtuceqbcxk.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtqgqeclaf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtajaymwdb.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gtljnxdcqr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtshypwqbo.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtdczyfmco.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtyznwjmew.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtacizokxg.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtwxprhebm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtolyhasfq.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtvgrpozgc.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtgypnfwvb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gtzpypalqs.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtixjnsynn.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtlufvqnvt.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtisddkghr.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtdmhvfzmk.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtjcmmstap.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtsgtkcdlr.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtoazxkwnx.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtizpqrdxm.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtzsimdgvd.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtbfesuzjm.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtnxwemseh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtwzkbwbrl.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtrcktzhrh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtuicdvezq.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtiqtvsaum.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtpqrwazxx.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gtddqssjmx.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtefzutcab.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtmzprstqs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtwfvehuyy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gthszlcgdh.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gthvrjtlhq.html

[S12] C：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsydknyzp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gttkqarawe.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtzydxxbch.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtcvsyztoo.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtobpzbuka.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtvscypdmt.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtuiefaudg.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtsurctyvw.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gtkrpeqybh.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gtktloytbo.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtachltoul.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtxvbrljgx.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gttwomaypr.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtvcpcturk.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gtawjiovfj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gthfotuevq.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkkdexvf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtxdnqmtxu.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtdwlvhvcc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtyxdbocwv.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtqdndrtfl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtveajuztc.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtlvzoqdhh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtbceoizkf.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtkmutkcls.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtzhbotxwt.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtybshnagr.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtbnxikbop.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gteptwsqam.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtylbcibre.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtcqqcebaq.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtleumfwho.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtybxqxcoh.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gtdrlmehmi.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gtzgsetbtu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtoynybptd.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtdkqawvpk.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtcwbbhrmt.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtmxhjdvng.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpbulpdv.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtgxcodncm.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtccbmjisg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gthnwojmnt.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtutxfssel.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtkvlyvrxw.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtfjzelnxl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtldcptamv.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtyhjczmaz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtsfpriqrk.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gtnnnzmkqo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtfqcrbory.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtvdvnnlxg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtvybnvuid.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gtiegojyij.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtfthlmsoe.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gtqalcryyo.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtvlzsjpwe.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtimglcrsm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gthzmzxlfu.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtxdpcignl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtxzzugpec.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtjhymkyto.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtulxjrucc.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtvbufqkqn.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtbmmjrlqj.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcfaqnqn.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtlnznzxyy.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtiqauksru.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gtespxzvzr.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtnygyaqud.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gtrwqkjjhm.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gtesjvsfuu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtacuonxbm.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtahldiynn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtrbigvvvf.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gteecyzlxa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtccexvpui.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtigoherls.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtlbskxxfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtcdlteidq.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtxrlheutz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtnriuukrl.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtldkxwvag.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtmwukwjkc.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtasfingpm.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtgtlndwgt.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtgxsuaaul.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfeksvpw.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gthdqvwwnp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtgqnewvml.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gthbayhfwj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtzefsyveb.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtnptmzvvs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtmhapcmog.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtfnyikqtq.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtflpolzyb.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtrpcczmia.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gteiejbqmz.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtefmejdws.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gttjnmlnyr.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtrvjgvcep.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtzfmtdxeu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkggiwffz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtolzizkvq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtayarxhwj.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtyzdtxqta.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtyftcjhhh.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtkizvoyds.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtkzovmhtl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtjioomuvf.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtbvfckadr.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtvgsvnspo.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtxqcxjtyz.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtexgiiqkz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtdbabncaz.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtwfnszxth.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtfkmhmdie.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtumthqfme.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pycfn.com/Article/details/gtsbiuqqkb.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtmiyarrxc.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtlhglfdbn.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtucnxtxww.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtyzsuoxdh.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtyfcmzrwt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gtvowikyrh.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gteyzsbhau.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gthjfvcyno.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gtaiqkqlpa.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtaewwjuef.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtunukgrth.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtruuzctao.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gttdvzkrmz.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtzrkyfnsz.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtwdcvupkm.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtnjsrcapn.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gtnpbfkhyh.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtvmxfodsx.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtdzmtsgew.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gtesmuqizd.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtrczrjcam.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtawrnvyut.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtxuvqedpc.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gtzwliljml.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gtaahctczs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gtcwrmhuqo.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtrwwotskm.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gtjtxduvfg.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtgayrqead.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtljuimckl.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gtksdbvpod.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpbvdopb.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtszawtunp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtjlvsncsk.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtpgzohsqm.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtcnprulal.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gthdigqwnw.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtbpivuvju.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtzyofkcln.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtuhlorrsb.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtbkzoawlc.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtfmjkhrtp.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtrbgqyadw.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtcfsqqekv.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gthhrnnhzn.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtqboxccmj.html

[T31] Lua：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtsuwtnoei.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtdgcpafny.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gtxngudkji.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gtnlkjecsl.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gtqxgowqpg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtxhpfqbmh.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gtuqmftjwv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gtzjykoxiw.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtciyqihen.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtrhyibgmk.html

[T36] Lua：函数
来源：http://dali.hfpthk.cn/Article/details/gtzujulger.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtgqsakgcm.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gtusvgwpax.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtdnijqxfs.html

[T38] Lua：条件
来源：http://dali.xylfe.cn/Article/details/gtuxiaycro.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gtianmenqc.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtpcufjauq.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtiukdwtkb.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtqllicydl.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gtdamghdad.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gtzxzkovro.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gtbvuemmpx.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwjfyjkv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtylxltuxt.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtyyxunnkn.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gtryjvbcmb.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gttqrxlagm.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gtcxkreqfi.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdkmsqrt.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtuhcxtknd.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtxewtizbz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtlrchpomw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtbuxinrgw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtvqsiirfr.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gtestatkjh.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gtockllvyt.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtkxlhawsg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtxxtxclik.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtkpuxrecu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtwnosbtzl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gtbeoczbpd.html

[T51] Scala：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtwclfrnsc.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtfproeasy.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gtdezixhza.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtkxaydfmi.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtmvlmfqko.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtytrnoror.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtmixihssx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gtnmflkxaw.html

[T55] Scala：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtperkyxde.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gtirnlakzs.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtdptmktbx.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtjwcypeeo.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtqikxzzzb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gtzqbyxucs.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gthgnrufpo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gtvdxkaxby.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtgdvhdasb.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtkyluescp.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gtgkmvegkq.html


<!-- 参考信息 -->