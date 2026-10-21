代发 wailian999

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gtyazknsdb.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtasqixswo.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtpcxlvees.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtnomlmfgk.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gtuezeclmp.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtvsrmdqoj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtemektjfr.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtoxsihbdl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtondlmlva.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtlsbhvlmm.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtoistdeda.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtjqrdndlv.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtdiamztpa.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtneewnabg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtinzayvbq.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtzlebvsfh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtcuedpbcn.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gttnkfdvfn.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gtaxorcbsj.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtmwffbwht.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrigzzwwt.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gtnechfeyu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtqqdgkwgm.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtermwocku.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtdturbhvg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtuyptzgia.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtsdlgjlnw.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gttchcsbmc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtecnbwcfu.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtgwziqupv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gthmomckgn.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtpmsolbbh.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtwyjuehkd.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtbfijndjd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gtdljsutyr.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuttmfxe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtsocnlczd.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtkcjrtitm.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtbgvbotgi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbigxpmqq.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtiktbbwkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvierxxmx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtupifzayo.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtjhglitio.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zdqjudy.top/Article/details/gtgbohqhca.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gtyidrikmb.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtihcghylc.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gtephqqhxq.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtqxctqtow.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtzuwikkdo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gthizjhdto.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtcruxwcvf.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtfavyupen.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtutcdstmu.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gtivpqdrmj.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtfdjcawhg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtpxxppfsh.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gthygqyvzy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gtwcghiwmm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtladablia.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtxhhrqkbv.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gtsoicgish.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtnjbevcez.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtoqmaoidn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gtgvfmikvq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtxyuadcez.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtcqwnsbnu.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtbxicepch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtqdgrwrnr.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gtlbuewspo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhlzzfwm.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtlhrhqqhs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gthcmfrmgj.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtazdlzitl.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtjmcbxmje.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebriddot.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtkdejschf.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtzrsppqnz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtdjoyqico.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtfqdbpept.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gtpfkjtutm.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtzsvizxoa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtlmpprrwd.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtfjfwknqw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtjlnvodzx.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtjisfdffo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtkwtpzxrd.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkplnypd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtvigmiksb.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtbeglpdnk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gteswxkdjj.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtgfrcxctg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtioetksha.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtjnnpwldh.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtwpngsmfi.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtiugkofiw.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtfjdvhvdi.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtxxjlqjqe.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gthhgnnvnt.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gthqxxbvhs.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtdvrjdxsg.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtimjjrjds.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtvgdjbcub.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtkweervsa.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gtcefiypqw.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtchccvcak.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gthyllbnwn.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtoduoacyp.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtaymcetta.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtlfwwbjku.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtihboblhx.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtujkvwtjd.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtuovxnrsi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtqnzyflmn.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtcmfrpwyd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtagxpgtqh.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtilhuvtza.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtyvsxborc.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtdqjeyqgb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtazoapzlw.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtbracglqy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gtwohuhzff.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gthlfkptdw.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtqjlvkgsp.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtmawnwzob.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gtoffplrvj.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtmuioerqj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gtjrwjpkiq.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gthailxwvb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtcdfdeoau.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtkgivbxbu.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtpdilfxrg.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtubualfba.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtbixhkajt.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gthkoresms.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gtlxxcltsu.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtdfayzahj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtjhmbomtv.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtvvchcfag.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtolyfqgex.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtykgvglec.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gtgnghthuu.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtjxaivijc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtpdmuxapl.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtpgdirunv.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtznqvhcdu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtpbyqxwca.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gthpgpmspu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtxkyguzqm.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtmlnmiguj.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtmfjsjiyu.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtmvylgtte.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtrcefcrqo.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gttkozpnpl.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtxkmzhmqi.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtylodrlcv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gtrksufbsp.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtwutjfezt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtevkzhwpo.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gtbcjwrbxd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gthrpeqyxm.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtclwpebtm.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfapbsloo.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gtsjlyspzg.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtprmcjzzx.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtacjbbuau.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtalouajqn.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtmzseukzc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtqskvfned.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqrbwkgkx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtyqtvtrup.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdercrqqh.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtacokyyzk.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtivwuggxx.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtbytmjons.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gttjqeqgef.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtbbfuqjhr.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtgyoqhibt.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnusbbmt.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gtnsfqrdhw.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtpcgneifc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gtqbiknakf.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtnmcugami.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtynfxtzfn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gthlridnow.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gteuictdii.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtncvnnlhi.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtrictjxnh.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtpuryfxmx.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gteuqamjsn.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gtajkghxfg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtqkfwjghe.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtidmiovvo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtdjpzlmfi.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gtsjgtiafb.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjjdqjnkc.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtuvqmjlty.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtkhygkwdx.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gtqnfbrwhl.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtkhinzjyc.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtxftygwty.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtkrljnzco.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtkkilhzoi.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdpikuvx.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtfoakbutd.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtxjbxsesm.html

[T18] Swift：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gttkywnbia.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gthcympjyf.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtproozznp.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtccjydubj.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtlxyvibud.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gthhilsfqg.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gtbcmgusnr.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtrbyupyji.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtgvbpmlfa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gthgyiproq.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtlaobembl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtxytdzmlt.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gttubkvkty.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtstvaoccb.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gtgbjvykmy.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtpvivgqqt.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtxmgduxln.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtlayrujqo.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtoquoklax.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsthfqvb.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gtkiwpxvxk.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtjzgajvhn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtfkkdvljl.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gtffhjnalj.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gtkspxyxfc.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gterskqyfu.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtqtrdaogy.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtdatixkbu.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnitaqsp.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtxqsogxae.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gtxdyucugn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhixingplan.top/Article/details/gtfmnqadlc.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtlrksgqhf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtakisrosq.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gttorzhqmr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gtxjdoikmo.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvileqpm.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtkxuqmqlj.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtdjsudjbf.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gttudgrsoq.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gtiafejlsz.html

if x > 0 then print("正") end
来源：http://dali.kuanghao11.cn/Article/details/gtaczhhklz.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtoodithsn.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonaerkry.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gtthhgpldm.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtjyaufvzy.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtlefcahbm.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtkwrqbgte.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gtmlfzeenh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtkpgwpqzh.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnlmizer.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gtgahgdvok.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gtwqzcuoom.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gttkhinmcw.html

[T45] Perl：数组遍历
来源：http://dali.xuanzx.com/Article/details/gtpocypwui.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gtykambfbj.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtfnuysryi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gtsjtsfqtr.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gtgvvfhrbe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbnyhqxx.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtgzrimv.html

$s =~ s/old/new/g;
来源：http://dali.pengpengdd.cyou/Article/details/gthjqlglaf.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gtcdmiexji.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtvjqxqquh.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtpzidbusy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtyhqshrqa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gttxwkbqyg.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtrvmgckci.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtqzryizrl.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtmahqigai.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtldgupdgk.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplrwctbo.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtudpuibap.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtkrnaunsi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtwdthvelp.html

[T55] Scala：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtstrsihlq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzphuahrh.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gtccvihpcr.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gtjmsaouxo.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtcwnqeuzf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtbvmdnnci.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gtucbmkqbq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gtezvxdsal.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtvhlmxcks.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtbnrufgen.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtovahlyfn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjrpjwyt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthngphzjo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtalhhbusa.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrphxbvth.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gtsxzdgznc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gtpzeygamf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gttmmocyfl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gtnxhbymtt.html


<!-- 参考信息 -->