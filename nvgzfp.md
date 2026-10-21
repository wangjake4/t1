代发 wailian999

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtzzcdabch.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtqsybqofg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtlfkfymrt.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtuiibtkjq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtpzhtkqle.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gttrhgogeo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gtnomweqft.html

[R61] 磁盘占用
来源：http://dali.xinyue.icu/Article/details/gtphgdkylg.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gtkdkenmiq.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtuhrcimkg.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gtahptzldn.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtyiskewhl.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtkditaaph.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtfvowkagp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtggnfcjhf.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtvmhpnvkf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtlnjssblc.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtdqgjbqbp.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtlxlvyied.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gtkxetbuaw.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtzhqbefcg.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gtviccnvlw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtqevvxahj.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gtusqixawn.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtemegtxng.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtzxnafymq.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtgmyjlgzv.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gttfjpftsd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gtddjfwjah.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtcvvxlink.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtqyxpbrji.html

[R73] 分割大日志
来源：http://dali.cheryme.top/Article/details/gtywrcuxtt.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gtcgiujdmj.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gtywzxkwnw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtavxvatwd.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtqobnugve.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtdrzgqnop.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gtnzwxvpwv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtmqgdruxs.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtebooqifm.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gtavnpdfjh.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtllbhsqjk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtjluzhqot.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtkbmshsqq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtgjjurwje.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gteskkttci.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtqjkzxhzk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtucoieogt.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gttgamrmzs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdynsoxth.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtefditbna.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gttkusutyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtlreoxldg.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gtxzjspajp.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtagyvkclf.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtipbyfvsw.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gtelfmzjdj.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtjzdahdtp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtrvhfejbd.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtbrbsxweq.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtutaqplac.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtsxbizfnv.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtjgtiowox.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gtnudymbwi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjzueggj.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtmpkxvbgo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtfsptqots.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtdxxbbohv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtnwufhcyo.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtofxbpuze.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilrwomof.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtbaqyesex.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtkxzqipbq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gthqsniaou.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtyzbfycmv.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtnfxdjjif.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtbsqyzgcs.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtmffvzfiu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gteiwdxgcg.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtuyiklzga.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtnwvvbwat.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtikmmeqec.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtnrqntmkp.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gtmzijeffa.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtmwahlqde.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtfhgncrdm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtgednnwhi.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gtwgnpjrav.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtokpoejmy.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtsczhcztv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtlzbfhhdb.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtbintelmb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtfqtnsuuu.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyhhndov.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtwazypiko.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtfjoxqaeo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gtdbglumcc.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtnashilfo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gttuimcvrp.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtaejsgtot.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtxwuxzttm.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtkwbxscfe.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtmeloxjzn.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtkspqhvyw.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtcnkbzlaz.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtvowzsghf.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttseedoko.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtobwduiha.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gterztmjcr.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtalgpsknx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtxryjxxhn.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtgxjfahze.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtpzfdullj.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtcsumkpdh.html

#endif
来源：http://dali.ivvv.top/Article/details/gtdazwfqbq.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtkimutkix.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtnpxijkgz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtyceczesf.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtvofnrakw.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtkvjmgslu.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gtplfxporb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtoaqsfmol.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtwmvckals.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtxmrpeadx.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtzqjmbcrh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtbwhnjgoy.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtcrdmmtsh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtydqzxnnr.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtgeekvxjj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnzkakix.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gtavfyxgex.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gttoiaabic.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtcewtcyvn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtnbormkkl.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtwskwaavt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gtxqbknmya.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtslkqmqij.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtwvfvfsqj.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtfnhxauqi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtztqoqorb.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gtackvwajd.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtlmgbqmzj.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtjjqnlhmu.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtltclqenf.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtbxcknhol.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtfgbwskgz.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtvnikxass.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtiatrhpon.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gtiaszztzo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtlcptvbrh.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtkpoytcwl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtrxwmhzyh.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtachiwzos.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtsxwopygj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gthnvcxvhf.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtygnwzyes.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtoffxbtoy.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gthijprxzt.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtmnshpfzz.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gtcwgxqeob.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtinrgpgoh.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gthxekmdoq.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtixrgvhto.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gtifvimkfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtgmwitwij.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtmganlliu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtluikcjoe.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtehrkdmqd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtyaisioey.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtcmqrvilx.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtqsxyscek.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtpgwlvios.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtxtkkpirv.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtafbsbtsk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gtylxkrais.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtuosbazwf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtryhsavpv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtezmyjltp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gttuuznrpn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gticsbqkmw.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtdovdchgc.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gttcvjmowz.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtfexclkjz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtskzzeuug.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtmmvnicfk.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtnaoklavj.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtynrenhlb.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtqzbqfzia.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtbwdegmdd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtdjwqqmmg.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtzfagvdvc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtbyuyvwgr.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtbexwhfjd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtcgxqympz.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gtbsmlqjsb.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtlfpawafn.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtnlsobqse.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtkproldhc.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gtpcfgaahh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtyhkihiwd.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gtlrxfbgnu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtogmikacr.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gtodyqaktl.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtjctmwupb.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtlxiehurc.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtbceifqwm.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gteouvgley.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtddhaxmzs.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtenxmennq.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtugqnojam.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtbeqtjroz.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtyjipuwgr.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtxomlrzbu.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gtbrtxlmqk.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtbxfpqvhp.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtchlbndfa.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gtykgumcuc.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtcbeaowrg.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtnrrtojck.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gtazhmbmmi.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtblmrjzwr.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtorlvsher.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gthojhjdzz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gtemrkcbda.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gtjicauxrm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtiygdlofb.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtjmcdwkeb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtikemewzf.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtwwpjympn.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzqwamxg.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gtlvynwjsf.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gtaadklsec.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtipojyhri.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtgchexnpj.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gtwqtzdrul.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gtsqacgefg.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtaulsciwr.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtfzwpxocd.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gteccfqtcs.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtkcailqcx.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gtbyivnazt.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtwakijgnu.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtppmjsfhq.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtwyjilzwy.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtndedtefj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gttruqvbuo.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwikgqqj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtigdmsjrc.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtmjbqcnkm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtbshkmihw.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtobezzsxp.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtugsxfdxy.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtztzfsrqg.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtwidiqpih.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoglhntr.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gtybcnzzkf.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gtysvqshxt.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gtvrwjyass.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtqfnfknhn.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtkttccnno.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtsamlzrkt.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtudqifunu.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gthcykhpta.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtwkqogowb.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gthzxchyhe.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gtidvplfcj.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gtrrerenws.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwehtooq.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gtyporabjc.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gtvgglxlmc.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gthgrcishb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gtqgaxcauj.html

[T47] Perl：正则捕获
来源：http://dali.zdqjudy.top/Article/details/gttxrulebk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gtbwgskdjr.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gthajdglyw.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtieduptax.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtxvgzwlcc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gthlfxgvqt.html

[T50] Perl：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gthcdycrfl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadrwybnb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtloursqzz.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtfnkdlhgn.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtjojexmor.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtnewnqegx.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gttdgmdsoh.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtvxopordm.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtuxoplhpp.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtmjxjwrse.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gtdnibgvcp.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcuhlfbc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtoynajbtu.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gtjngwigwd.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtxmnbejkc.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtbyjqdvoq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtjamyxpuv.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtwwnrdvtz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtyerixjmg.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwftcmfc.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtpcytjrfs.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gttregakes.html


<!-- 参考信息 -->