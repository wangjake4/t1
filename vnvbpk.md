代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gteapyzeqm.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtydbxngdl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gtezsfpcoj.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gtruiuruxp.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gttvsozqhp.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtlycajtkk.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gtlayoghfb.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtoawekilb.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtzgxfavus.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gtmppnnekm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtuvkegbem.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtbcyrplpf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtvfgjaxab.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtztiutjda.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gtauvvxwhy.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtdzekrzfw.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtjuedxrgm.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtoycxovpu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtwvrgrbzy.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtcnghywrf.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtyelrplgl.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtkuyvsqpx.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtahutfqao.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtsrnewcko.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqryoszki.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtfnkxxfno.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtegkmzskq.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtkwcxniwh.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtjdszpgng.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gtmgszejxj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtksjqmgwu.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyylbzgr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtibwbaura.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtaqbgfbxl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtvimevpvx.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gtzgdeppdt.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gthpjopfum.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtcsvqqddm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtiiyuveht.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gturplvoft.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gtkvsguypk.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtujwdamzw.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrjnbivi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrburqxen.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gtryibgehd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqitvzsrs.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gttqbswnjy.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtotvrjffi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtqdfibsbh.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtnluwuxhp.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtyejrpoff.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gtsvbssqij.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtxlsuqymr.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gthxevxrhs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtoguxkvqi.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtxazztjtp.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gtrrzmcuvf.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtocllkvot.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gttwawmzxw.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtwkmqqfpi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtssvxaadp.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtuvtgcxkc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gtgkldyedy.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gttulhxhiu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtfnndpmom.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gtlwhyblkw.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtdbeigsaw.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtrflebdcj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gtuomjuvgk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtotamiehh.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtvzbgbthy.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtwhwifkun.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtetvcjiev.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthophdrdi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gttyfhjrxc.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtsnzyqius.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjulxboza.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdhrjcbg.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtizqmftse.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtgubhages.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtbyvayiiu.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtugdjnatc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gttxajbkek.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtpizmervz.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtamjvamjr.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtsmxgmtew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtftrwofjr.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtwxpaxjiy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtrvcpxrhv.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtypjvkpbi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtfqdqbott.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtuvzaxlbd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtaarkqlgj.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtshauwwhg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtgdjdacqp.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtyhylyetj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gthbunwqja.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtslwcrsqt.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtzwbhcbnv.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gtfqvssmgs.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtglobvsuc.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtzdpystvl.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtvlvwwvqk.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtdmknmcux.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtgaqomjhb.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtjetgoyix.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gteygfppin.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtuabyycmv.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtldntstmp.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtceinbhfl.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtolmpornx.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gtggufcwyf.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtvccioabu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gtnhzaifni.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtkdkpwtrr.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtiafcfpdx.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtbjemampj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gtwjnygtjw.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtuhyvrnny.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtsxlgysvj.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuzibkft.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtphxcympg.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gtmlyxigzm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtqjwpscmm.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtomndhmeo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtfvlwuprd.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtffdwyguq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtfjiwqbab.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtjxgisypn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtcscedajs.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskkoonda.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtnshvslvf.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtdbtcbhje.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gttjyajhtu.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtcqxaloje.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtqkxofdtv.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtdqdjjmxt.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtxtjatshc.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtbwtfsuoy.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkkpwatrl.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtatriugbd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtfbezzktj.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtcnoriymd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkczxfzhc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtytmcwiln.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtoijglalp.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtembimahd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtmgxctpno.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtvacnkwjc.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtyqkcnlai.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gttafejdsy.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtabjnedfo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gteogjgxfr.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtfivedjqg.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtsoupbuqx.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtykzvasue.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtshcbtnyz.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtajgcskmd.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumetrrpj.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtyjradbtn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtmefxrj.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtpmmjtatb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtscdscvbh.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gteibeemwe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gtythrpoes.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gtftrdkslm.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtkbyxxkej.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtmcmoqytz.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtssncufqe.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gttgoisydv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtsspgeteh.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtofgvnnay.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtxqnzulvu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjrrjuqbi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtzijpnhob.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtybnirreh.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtrgpicgoe.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtkafycblz.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtdefajehn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtzibcmkfk.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtjwjvpvfi.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtsngwwkuf.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gtlomdqlez.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gtfqjoebxo.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtaotpbwss.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtzhtxvlhz.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtnkttxcwj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtxgbkkcxh.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtfhlcxvne.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gththbosdp.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtwhkezcov.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtkbpedpqe.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtocshxzzu.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtscscdcjs.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtuhtjcvce.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtfzdvxirr.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtvhbvnyre.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gthzrgqcgo.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gtxxbfglrk.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtcgxwdrug.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtxvzqygrw.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyiwisdgg.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtyqbcjdjm.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtpvknjqmv.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtjkjclwae.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gtaksjppcm.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gtdyissiwm.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtcxewexkj.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtolsqdklz.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtucczezcv.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsikvykpl.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtqqvatadt.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtlefbsdgw.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtvlzqvuop.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtqpqcapbz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gtxdwwjyty.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtkqpduecr.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtrwqetluj.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gtpyjjgyta.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtgahffqrc.html

[T23] Swift：函数
来源：http://dali.shuidangran.top/Article/details/gtexxdlupw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gtmsddunnt.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gtftplhtqg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtfeiygioy.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtmjxiyikv.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gtbzwleskr.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtvymgnxre.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gtjuhsdsop.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtdmzgtltf.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtekcgmkdv.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gthlbqlxhg.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gtqmhqhrug.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtwkkkokxm.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtupiergyq.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtxspnbirt.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gttvjbofzx.html

[T31] Lua：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtgoxoilkl.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtdiaehuwr.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtlendylvz.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaagpnuu.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gtppnjbxgm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gtisbzfvpp.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gttaccguwu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtlmojrxpr.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gtpclrmqqj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gtiqhnytqs.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gtocgxbecz.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtgqfcesxm.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtgzpvipob.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtdmiquzvr.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gtxfxlkjls.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gttldvmktw.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqbrdaqk.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gtwklkyccq.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnntjjdi.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gtnesgtaoq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtksyygmnh.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gtatuyjcvj.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gteolrztri.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcmaktxk.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtqwjeyuqk.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtqrbxsvfa.html

[T44] Perl：条件
来源：http://dali.xinyue.icu/Article/details/gtvyvmdvhw.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtphfnzeyk.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gtufzfhafp.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxinkj.top/Article/details/gtuhivgzqq.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtwdwdnslp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gtefaagzuv.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtoypyanje.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gtrvdqomts.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtvkwfyylo.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtmhgbgzis.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gtttfshgbe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtmaboufzh.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtazxkrxsd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gtjpuuyqnh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gthpwvcsdm.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gtaapgfasw.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtrkedbicp.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gtxslrbfgd.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gtiyvyqfxy.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gtxfmxjjil.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtjdehwztd.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtfsfgcpct.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtylnfwvbc.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtxspvenyu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gtmszlhanu.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtabeohaaf.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtkzltbcrg.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtzqkaiqaq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gtkkgsrubs.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtclzwbnyt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtrzrydwiv.html

[T59] Scala：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtbbnwvpzx.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gtqmpzszal.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtfgmutuki.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtwovgdoev.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrhogbwaj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtzjgqbfex.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtldzdbwci.html


<!-- 参考信息 -->