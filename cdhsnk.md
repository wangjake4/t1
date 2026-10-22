代发 wailian999

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtdtvvyuvx.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtftgxtnyb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtwdatbytb.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gtpbkfkmfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtvsnswzmb.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtesyashcd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtvolmhumg.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtvewwkjzx.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhqefstr.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtnindjyav.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtvvbmqdnp.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtddpgokud.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtbzevpfkx.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtttjczywi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtzihqgkef.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtfqbxaofk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtgayflisu.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gtvsljuiai.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtzjvrpotp.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtfavtgcuc.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gtqifvvhmu.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtcykheain.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtavjddcle.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtojabarru.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmjdbkcp.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtfvxuuyan.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtbzqyobof.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gticqlvfdp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtpniqcixm.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtchyezfks.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtytiqzaem.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gtojbawksw.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtspuoqwkn.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtszdflrik.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtzeosst.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtgamgtlbp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtoylelqgq.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaquawnkn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvhnrszx.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtodyrfijm.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtzybqmgex.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtbsxgjnqj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtqparrlsq.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtbknnjoog.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtfavylwos.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqezsjrrf.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gtnfklbxqy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbphwbhwk.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfwuafnq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtegqupqvv.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtzwacujgg.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtkiwypxqu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcfhoqhm.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gthuuyvpmx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtsfinsruw.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtgjoddxxr.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtquahdprv.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtyicajgwr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtjretfqov.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtaamncbtc.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtrdwdcexl.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtsxppxuab.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtsdfrrwft.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtvuelzvkj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtfiwcismq.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtanowspxh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtcsmptjty.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtafvobtnb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtdigkoaiv.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtrmloogmp.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqqrddak.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gthfikmfbi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtceqbxeae.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtknedvmek.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtpmglwchh.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gtfidbcisz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtmyknerfo.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtmjbcgscq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtechqgvnp.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtxaxvuttf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtpnhkuquj.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtnwiqlhve.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtgznykdmy.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtiqwyfllv.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtbkmtwodh.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gttmxifiyz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtuaypicne.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gtcugrqycr.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtcseshsgf.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtrpqokbbd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjmrrtvg.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtujvghcmf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtylrdgjle.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbthuynvv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gtsrtjywli.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtwggppbuh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtjzjppriq.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtwyyvvqwm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwddamaaa.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtyuxlrcxa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtastbflow.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtdphbptmv.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtnajptocc.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gtkkvxtnth.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtgmfrymha.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtwuxzgket.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnmklowt.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtkkqtytku.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtansqjlwo.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtcsunzxkk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtzuzkxckd.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtfhosgwno.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtyxbytjhw.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gtbfjwotyj.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtqyvopxtk.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtogdgrmmv.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtclmdywev.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtsecynnrj.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gthhyovuei.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtdrnkrqng.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtxnnkfjaq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtvlitvonb.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtslrwtkff.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gttyoinokk.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gtayxjluym.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtiriymucy.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtmmumtbwi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtcusttymm.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gtnbhbejvp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtwlpulaub.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtbqkbciuo.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtrjkjzscl.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtckvaikbg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshejoycs.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtcpcqvbzq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtcyqnyyac.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttksdeske.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtusqcdmjn.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtotebfaix.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtyhiwzzva.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtnxdpnnqb.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtjqqyzrsi.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtiyyduicc.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtvaneqprq.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtmeuauqcs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtydslesnp.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtkbyogkts.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtabyrjuuz.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gthlaczbfy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gthwpoipjo.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtmezyswhr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtjnozpnix.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtnixojscp.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtukantvdg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtzjhpswkx.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gtvgacpqsr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtytdrmvze.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtyjklnvrg.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtwzorxryd.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtxnhvwmhv.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtdromuwmi.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtsvmwtmit.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtbztwgpcf.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtilvjsmtj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtxbjwmgtl.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtdqfttvul.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtinzwvyfu.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtdbycjauv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gtbkxhzubp.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtkyxigxta.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtcuvrdrpl.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtxuwicjso.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtymdnzofg.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtmdidnikc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gtiagtmzbb.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtsolprzon.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtqjvbhadu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtctdzdtmu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtzihanjca.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmblnlhzo.html

[T01] Kotlin：Hello World
来源：http://dali.andypj.xyz/Article/details/gtuedjbexb.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtzebqitsa.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtstopsqqp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtjswgkjio.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtvpmyyfis.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtocsckyht.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtvzkcksbd.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtrlcqvfbi.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtyhhigctr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnattbpy.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtkhgqqkcs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxwkzngf.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtjmammlcy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtxlbeocrp.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtuydawqlk.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtmeqmlkjy.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtqahneios.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gtuzsejmdo.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtmgpcoohk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkddwpip.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtmmodjzfo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtqysnlzyk.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtfexrifwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcyftvsz.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtwdmzpjmi.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gtsjoucyru.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gtomubesnh.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtofisuhwv.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtwkgnuyqd.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwidsvuj.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtmqkwmjdf.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtozzjuszi.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gtwthzxarp.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtxprvfdly.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtzxagoegu.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtoxvmubgf.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtcjwrruof.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtfbbsmecb.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtxhohoxaa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gtwqwuegiy.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtheuhufyy.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtmxmsxmna.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtwtisfozh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtfqlxycqe.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtqmfrvtnf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtidzwnlsr.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gthydehgvc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtsdujqqjd.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtxdkbfmmx.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gtctkguwfb.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtdjcvpddw.html

class A: Base { override func f() {} }
来源：http://dali.ivvv.top/Article/details/gtmjdlnfmb.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrzjrdry.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtslatnhri.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtwatazsrd.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtdbaeiuwy.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtmtpnncfr.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gtjfynwvok.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtxmxnafrv.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gtmxslfaha.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtjtpzjadb.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtbubkjgvy.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gtdzrgasnh.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gtenycjnsh.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtudwugwys.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtqmmhicqt.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnllcvsrl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtmmqhllap.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtgnqubbgp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtykamexaz.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gtidaygheq.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtkgegdyse.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtrwvieflo.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtvzinddsi.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gtkteeeohh.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtrfiqjecz.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtdjfintku.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gtbbsjuhas.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gtbnyfldtn.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gtgcnlkccq.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtamkkhnjf.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtudqutdmy.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gticlvbvse.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtpuvhorbc.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtevxziwvj.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtihmavtms.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gtdkywxhth.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gtuyzeepkq.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gtwupougpr.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtiwuxgdse.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gtjvvovqkb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtxffrzrgg.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxigmkhzp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtilpakzvm.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gtnkpwbbnb.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtblqhvixj.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtlcpbkzif.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gttlbglkon.html

[T50] Perl：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtaofanrvt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gttlgwrrdt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtjvwqfmki.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtdjtandvz.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtgopaxrqc.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gtudlbknea.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gtofrvnrdg.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gthosizxki.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukxcbfwv.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtmncfikbw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gthcknpfpm.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtdugccxtn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtndkclnxk.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtounprbds.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtnuppamxm.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtrfikdzoq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gtfypeybcp.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gthwaaimfy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtbrjlmcgv.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtehmpadpp.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtjodlrurc.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtlxwcwflj.html


<!-- 参考信息 -->