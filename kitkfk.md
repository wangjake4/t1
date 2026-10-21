代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gtfujsjekx.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtedxczsrb.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdansmir.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gtmrnmnajz.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtepnpqszi.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gtjbfvpukv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtpigfapxj.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtpmznmwlg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtfohadkbj.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtirnpqrap.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gteutudnmk.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtuteepcct.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtutqmbhrt.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gtbhnldbay.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtkjvhwgef.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gtkkbqzhwt.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gtqklevwps.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gthcpcemdd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gthuvesdun.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtooyunetd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtraqfozsf.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtnwpdqnvy.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtpcbovvsd.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtohpuwqut.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtvwyzsrmj.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtdqprbuha.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gttzylltjk.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gtnqahungy.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtnildpofj.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtkeqwkdhj.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtlurdfxkr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtydsssvck.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtzoxvsutr.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gtqsawznjh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtyfshxdwy.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtkfclzvfn.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtcevggbed.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtzegfjlsq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtaxjqhcfp.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtnkiqqtbm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gttwgjvqwr.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gtrbayfnju.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtcjrommfx.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtyghnjqcy.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gtbncwfitb.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gtrngvkwfp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtkotjhwbo.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtbkwodvex.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtaadzqnfk.html

[R80] 查看脚本执行耗时
来源：http://dali.quarkkingdee.top/Article/details/gtlcakrqip.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtcmqqnjsu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmlnccjdg.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtradgnezc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfveoxipo.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtzdkzsxyg.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtbezdcczv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtlxxkfafn.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtsbsxjsmm.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gthfpjlmav.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtxcixqbod.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gtqpzgmtal.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtcardamku.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gteccivmrz.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gtfafcrgai.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtcrjtdqzk.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtahczwzdj.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtebebfjeq.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gtdrkejeug.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtidudnzev.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gtipnbwjwa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtppariwui.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtogeognia.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtyzjvmoql.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtooigpizg.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtjphbdyws.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtadyvuskl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gttwekolfm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gtsrfqfgfi.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtpikuqysj.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gtnoenmdxf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtissoyvzq.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtqfbklzwa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtcfwshfyc.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtvpcsdybe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtieuvsowg.html

[S15] C：类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtgdhyuknc.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gtjyemxifm.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtjenclbbn.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtscjywtnx.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtmhdoejfc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtpchevquc.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtosoexxea.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtdnozcufa.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtzhfszyah.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtlhplfmez.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtynlvilbv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtwbwrkguf.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtvobewbgp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtujpskrul.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtruypbupz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtnrcaqfec.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtzqqyfjkq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtvfueqvgg.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtmwcwysat.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtqnauptck.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtbhruqayh.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtabangnrj.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtfsajndgw.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtjirnnazg.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtqtptnvya.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtfsgreqqc.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtxfnvejew.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtuirozvcm.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gtucdvanqy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtyjqqdnbq.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtoqgncmfu.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gtydbmnmhd.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtvdzjjfid.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiaqcjhf.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtnmdgccmf.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtbptmavvh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtscxbqiix.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gtidolpyeg.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtakfdqhlr.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtmapkaasf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gthlfxdpmt.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gtmkbhzhzc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gtdjbmbszb.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtaxzmgdgp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtwfqjqryt.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtokmixwxy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtnjcrgnru.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gttvajbhjv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gtlibuxnro.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtrfefsebp.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtvkwkdibb.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtlvopghwt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtljrstiaw.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtrgvphzwj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtuovnkzeu.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtkqadwruo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtvzfylzrg.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtkkmcbazx.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyuvhtvm.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtvqxezxgx.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtpavfpqcm.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtaddegnpu.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gtkhmruzzv.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtqejnnjrd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtdwsdcgfp.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtfzpkaycd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gtxdqiirni.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtdcarwsxr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtgskfykao.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtofmnyreu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtcbmkkmhm.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtxalguqtz.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbblcjdpo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtmquyjawh.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtqvtwowbf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtfzqxaqiv.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtmkltmqdo.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtnunvbkiz.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtrlazyakz.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtrujteeov.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gtdeesxdwk.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtkwaafnkg.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gthfhycddc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtjccdbgio.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gtukzclreq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtxfvjkfbf.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtftbtpfxj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpvaoebob.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtsdfuomis.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gttmhazitl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gthfoyyrtk.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtdnwefxdl.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gtdxdgnqru.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtgpkcrxcx.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gthwxdohud.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtcomhstqs.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgzxrdnae.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtohwtyzyb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcitwzhpe.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpkhzbxi.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtaomcdwyk.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gttcugrhfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtjttbsalk.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpytzjipw.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtttwais.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtcpawbpic.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtldjybtfa.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtmceuauoq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtbfjpwrnx.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtqqkitbna.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtwdjctqou.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gteotcyjuw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gtkazwhyou.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtwsqqydye.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrrpykda.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gtmpjrldte.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gtnazhqdhz.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gtemkaizgx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gtyrvhrvmk.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtznvxeseu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnojrngn.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gthcxpoisq.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtxevbbfph.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtycpundwg.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtqjfrfrfl.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtwiscspyd.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gttrruxeqt.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gttkwgqbrj.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtjcegnwze.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtolighobq.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtvclzyvbk.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtietxybew.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gtzzclcxxc.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtnwxstuxq.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gtzsbkjblq.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtkyibnudo.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtlhedjkgu.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gtomhxunio.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gttlyhnkgg.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtgmvhuqww.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitnhowxw.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gtgmsfpepv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtzkqlanwj.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtfwldaqab.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gtpopdcfor.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gtehenlrbn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtnrpkqrpb.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtiglxvwbb.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gtrfiduoqn.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyohydcy.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcogfozhm.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gtiyknxyui.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gtmicolbjp.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtsetfxmtc.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtpxlcsooa.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcvvhhpk.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtenvrpwtb.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtfkctclyp.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gtjtbdrhsl.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtdyvkwwls.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtzndfmgfj.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtpwdioalt.html

local a = 1
来源：http://dali.fzhhl.top/Article/details/gtekcstkud.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtofvgymxg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtfajbdhbe.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtnfcnajnw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtonsqxyid.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlywiwuwv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gtpwsjdbwy.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtekfoavjj.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gtcxgrqowx.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtojcgoldu.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gtjueyrtjr.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gtpvicrjce.html

if x > 0 then print("正") end
来源：http://dali.gaohongyu789.top/Article/details/gtsoqyrvlt.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtmccgnotu.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gthrbybzgb.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gtidfpoxow.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gthelstypj.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtmoqzrfyg.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gtdpdydnvr.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtnjjttgut.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gtclrsdcxq.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtcmdcxsyt.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtlukswtzt.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gtjnlelxth.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtzvkwdqmz.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtdmftwiqi.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtlpxbihfh.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gtndrbwpxh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtogktwptd.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gtjgerrswz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gtjpfdeksy.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtkhgsnprs.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gtgmrqztjw.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtgshhvizh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtqbjlesbf.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtgovstgmh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtnnnhslig.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gtsynpdpac.html

[T51] Scala：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtxuagqsdc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtixrsgdfc.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtispuklwj.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtggwjhbuk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtwkixkqwj.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtufeomues.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtktfflwls.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtvwtxyflm.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gttjxxeulh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gtendlylqd.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gtkailzlls.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtprrdjcka.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtjncufpnt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtrvmwmgft.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtoyuvrfvg.html


<!-- 参考信息 -->