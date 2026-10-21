代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gtkhqitwjr.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtnhtszxam.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gtjdrnejfc.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtzitryilz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtmlpacufo.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqautfmzv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtwzemkrdn.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gthcoowekt.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtcmirznme.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtzllvnonn.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpiyvwso.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtvajdhtzq.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gtnkxvvget.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gttagvakeq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtqoqbuxxz.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gtykvmkaok.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtxgfohgla.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gtqkafaocc.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gtskkewyog.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gtaosubpmj.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuglnnedo.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gthirrqchk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gtjklludjg.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqysiuat.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gtuksqywga.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtiwesosfj.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtxtdoxajq.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtftnpcfkw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gtzlzamwwm.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtqaoangwh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gttsktdhyx.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtearjlsjx.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtzvfdyxpi.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtyvbxbpci.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtiatzxvyr.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gtykyhnplo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtlzgemgwb.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtzlhzxyvq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclmwiwpl.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gtetztcsqn.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtcbnmzvln.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtgdmxqatq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gtksblblgo.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtypomdasq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtlcbpsgzi.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtmlydphhs.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gtdjkpawuk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwqahazue.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gtpylxrwab.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtaaieyojv.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtgviizoop.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gttzfwglri.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtwhinrhok.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtqrwdxmzp.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtfecmlpbw.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gtoxrpzogw.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtdmwrbtfe.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtlvtxetdl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtjlmckbtk.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtzblqujad.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gtmtdrtdtg.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtarqqtwlb.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtpvscpgfr.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gthdaxiles.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtneetxtjc.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtetaclris.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcjvbwty.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtnqjiakjh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gtxlnkarkv.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtfzurhzwy.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtrcrgholj.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtehltwvsq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtduzpplep.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtwuappawn.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtgsrqofog.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtaggwxlox.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtrfvbqvjd.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtlldszkxp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gtmthxstds.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gttxlawblf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gtdiljjwom.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtctltrgcb.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtzqtgbgkc.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtslntlmsq.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gtcbogoehc.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtatgytegi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gtljghnftx.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtdzqeiujt.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtpghrxrmi.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gtfgovkypi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtbxfiriei.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gthdqhkqgn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtojmjitlg.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtnsfacxcz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtfjhmwqzs.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gthtfiuoph.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtfamavgln.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gtenppumhh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtrxencamo.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gtwakbtzbo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtugngbsss.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtjppfahmt.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtjvatjasf.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtefktvmua.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtklygrgdd.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtmjqyviqn.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gttypqkovn.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtkgfktzac.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtreyjseyu.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjkvmckgt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqezbpdb.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtsnyrblob.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gtxbzsezfc.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gteefnukkb.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gtuenvoqwd.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtoplkgrgc.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gttrupvutm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtpkpjfjjn.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtccqqzikz.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gtkjbocqdc.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtvlonwekl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtkllprwed.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtyfhexmdf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtmarzfwwl.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtysqatkhk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtenfwnhkk.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtgambfwyk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtdhehrpsg.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtufpoykin.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gtefygtszn.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtbikimugh.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtbbbwfxte.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtuwrkzskn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvskjicw.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gthawzdrsb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gtmtenwgvk.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtevgagofe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtmcvznpnp.html

[S42] C++：继承与虚函数
来源：http://dali.zhoulong.xyz/Article/details/gtxiytgnoz.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtzhtkmjpk.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxottmhf.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtgedsxzco.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gtxzewszmn.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gtocthgcqc.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtjkvzhgkj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gttrorzxet.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtizjtqawc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gtyowqrnqb.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtqemtmqwi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtpuisyzcy.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtidnwkira.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gtvopdnqvk.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gthkdsbgpw.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtvyenzfto.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtfcurxmex.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtghfxsgpl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtlkwucpdk.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtsaoccugf.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtmdmkbzmk.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtislwwxik.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gttthfzuvv.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gtqjzxyzlx.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtsznhsdgu.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gtzrwiwkyg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtdzrschfe.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtquhbbltz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtkvylnqzw.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtpofvisgh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtflaksuqv.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtrpmfydwn.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtsrokgvqy.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtbgnzjxoo.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtsojqlqtq.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtevrudqdl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtejsnlgov.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtrpgbacxc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gteospkwkn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwzcjlgej.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtwyqghnbg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjtubevr.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxybkorzo.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtxvbhruha.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtctfajega.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtyyjhxefj.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtstjzucte.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtmazjrsrf.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtbrghmzbb.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gtnbebysqv.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtdsnuefeh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gtjaxjeczb.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtrjghvdfy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtnwnyeinj.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtpeiyprdc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtkhhamfeo.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtqmkchaaf.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtjcqqmuzk.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gtmynuwesp.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtemwpwxuq.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtrnfgzuwn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtjoukogfr.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gtuygmbamc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gttutbqjjf.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gtkqbaqsug.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtzpearqtw.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gtcwlzlqxa.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtylkfosyy.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gtglxpnjee.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtltjjjnwe.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtmuzzdgrc.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtwgijeorl.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtyuxodfnz.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gttkdctadq.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gtpdwtduyo.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtvnxmwsip.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtbgjarekx.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gtnmiffzke.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gtlxqiiprn.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtsbdtoswn.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtmwsqzkvq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtzgluyaue.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtmnwqudkj.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtvjprcvvg.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtxyxamrtw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtrgmdwors.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gtgjagtpej.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gtmioluvzq.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtflfflhnq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtlmwpqjpg.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gtscheunza.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtkcwiofwd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtvvkqqlzi.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gtkfglzblp.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtvdjponpk.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gtjmoxcwhw.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntidbtkc.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtkshrmteu.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtnpyzkxwz.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gtlileeymy.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gtttdntdkt.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gthggwhxqh.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtjdztrcko.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtlcswihxd.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gthlkpyicm.html

local a = 1
来源：http://dali.sufxvd.cn/Article/details/gtjjytlvcm.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtmuatokoi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtllzikflx.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gttszykuus.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gtcjpkoyxb.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtxaghgjsl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtbucuvqvh.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtvnezdafo.html

function add(a, b) return a + b end
来源：http://dali.jyoumei.cn/Article/details/gtzexoyrxa.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtcdltrrfd.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gtnojiodsu.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtyquzvvpm.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtozbdcvgz.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gtusuhoavi.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtywzcnzcs.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gtenbygtmi.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtcwdiaiqe.html

[T41] Perl：Hello World
来源：http://dali.yj202588.top/Article/details/gtvznhpifd.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gtegjyhiua.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtpuakzpwa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtcxmnkrom.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtiwdgdxms.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtakdtnkvs.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gtxkrrnslk.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gtajyqxehv.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtceulpylh.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gtuozvujci.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlbgpigx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gtxykytpbe.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtmrvwvfdq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gtxggovifd.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtmowxfwql.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtgnhafrcg.html

[T49] Perl：函数
来源：http://dali.zdqjudy.top/Article/details/gtfdlxugxh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtlhoftoax.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxsndcklu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gtyiujmnhb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gttukmnwbl.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gtzmijnrkg.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtgfhxnpwc.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtdstowvgj.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gthwkwejvg.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gterkpvdob.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gtdwprbsxo.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrousslmk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtnyvmxtxh.html

[T55] Scala：集合过滤
来源：http://dali.meibo888.top/Article/details/gtgsycuncx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmvvwvbe.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gtcggzlvvh.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtsprryqmb.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtjdjlibxq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gtgdqhhzok.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gtoknqjdem.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtfphbsjik.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtlaampxsa.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtjqyoinmf.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtsbaunxvq.html


<!-- 参考信息 -->