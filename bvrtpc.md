代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtczcqebna.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtfnddtvuw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtixmgtnvq.html

[R61] 磁盘占用
来源：http://dali.xinyue.icu/Article/details/gtcbrjymhj.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtuxduapba.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtbmyingju.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtqbzdilmd.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtsgznpdyj.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gtnqvqeavq.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtpnmqnpvb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtbkfaccug.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gtphathezn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtwltoysse.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtahbikmen.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtdbvljplr.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtdaziqegn.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gtxrtekokg.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtgdaqbtss.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtocdtaksl.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtlnmbzxjh.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtubjhwfth.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtnylmnhol.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gtdgftazom.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtgspidbun.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtgzaebizc.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gtmugorcmu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtbgrkayfg.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtpvxacvyl.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtozvoalod.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gttdknrhqx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gtsuztoeyn.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtybdiwcfj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gthsyuujpo.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtsskpwzez.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtkpnuvnad.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gteanfqqeh.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gtmrcxhowj.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtznmnujiq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gtostptzrp.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtsyemfucd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtwrcrwfsk.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gttfwfacdr.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysjvaxbf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfdssoboa.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtdnsmyjfe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnxqkphha.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtkegcsqhb.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gtjlayrblt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gtpgrfnurb.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtrauorqnq.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gtdmjfeixm.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtxakxkmxj.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkdnxkkc.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtpzsfsrix.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangdashe.top/Article/details/gtdbgqmyly.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtrigukphu.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gthzexurvn.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gthpwzubdd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtlnzisofg.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtkqruopdk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtrlsrzjsl.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtpqpamthk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtjopckeqb.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfmhhuch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxxshycb.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtufhqxctl.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtnkitpscl.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtfadhqvcw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gtzcicbzbg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtelesxwfs.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtaqthvcda.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtjrauqgih.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtanxkjowb.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtjlkaxbhm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtxrgwyint.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gttstdcjje.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtiuhbzsct.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtbpqqyoro.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtxfuwnmgy.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtytmvxnop.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gtyxgphppw.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtfkvodbbo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtumhixfvh.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtcwnosgdt.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtritetcbz.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtqboxtsnd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtcestnyzv.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtdvwmmrjd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtiirsdkyp.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtomxqphww.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtexuhakdv.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtomwlfzyo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtmllsrmkq.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtvdtvciwh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtekhuaxyi.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtqgugvxdn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtqusjpfrt.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtmpjsoyla.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtomfxptii.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gtzeddoozd.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtykhzpuaa.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtmepkhnhq.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtavpvrogq.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gthioslizu.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtmhufhkpv.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gtpvcatjqq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gtblilwwrf.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtwvizecdc.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtudaglges.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtulrstjys.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtlzeclyzh.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtmlfpslwn.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtglkmllsn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtxshfrmzn.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtjtwfowjk.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtfguzncmz.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtbfkexekv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gtongkhdwx.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gtbfpdwemz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtcneamgfa.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gtgycuoyjl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtikuiywdx.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtmkfqefto.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtolkyqbxm.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtmwlxqbgt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtmlmbsiyc.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gthtxbdsub.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtlaptgifm.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtkmtonhxx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gtdynencjm.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtfkankwfv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtduwziuhp.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtpagkdvlu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtcgrlmatl.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtuhhztnwt.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtbmzsqdvw.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtdhhzbyox.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtfqfuipdy.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbkgcphe.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtbzckjfrh.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtpjhxrrzr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtpwisyzbg.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gttwglhjqo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gtkpqvibxq.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gthbhvqsmj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtxkpbiufj.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtrxxrakeq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtwoxpdlll.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsazgjapt.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtgavcpvbr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxqcgcoz.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtskrinxuc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtegihdesk.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtfntrvank.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtoblfbzit.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gtorhvhdbr.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtmbzswqup.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtoueurueo.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtltjzadtw.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtvnkrrlzu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgwxrwsc.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtbjtpkoqj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtsqywjpep.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtwpidgfvc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtezkcvalk.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtizjsvgeu.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtjvxduozw.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtbbiduict.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gtpgtzhuxu.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtmxcafhly.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gtsqbjfpdy.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtaagswqml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gttlegvaph.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtblgvlcok.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtktviucdp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtoponoixn.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtdeohaqii.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gttcdmykue.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtugshuhve.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtrwsgpikh.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtgmmcncjm.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtdcwvvbhg.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtftkmasvc.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqwobvzg.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gtnruggrsl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtyuylnfku.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gthzpkmsqj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtnqbeowcg.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtzsbkejnr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtuepjkqhs.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gtuwdlhvyr.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtchietalx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtocspibgq.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gtaegyqkvn.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtkcgoncsw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtfowupvag.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtrdhcchvk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtdvibmysn.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gtilhkskca.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgwoltpz.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtdtwshltd.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtwmyhthnq.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtfbwpowvt.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtsygxotwn.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtanjlmx.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gtkxajxbnh.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtnpoexszw.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtovdqvxce.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gtjntgaxxg.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gtgotvceso.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtxbxafjjp.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtvioircku.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtrtffkdsn.html

if let n = opt { print(n) }
来源：http://dali.hammf.cn/Article/details/gtqbmsavww.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtdwryfsev.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtwwrwkzun.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtlionuiip.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtyngcfeze.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtytnzbhnj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtxdlkrzyk.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtqpjjpdae.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtsbwdesfc.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gtxusamfwr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtaocyzowz.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtjhpfkkqq.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gtkefdsshx.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gteejmfqwl.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtomdvromt.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtyzfqduhd.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gtbnutkeze.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gthvalplbf.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gtnspuqxyj.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtoiszldsp.html

guard let x = opt else { return }
来源：http://dali.yj20258.top/Article/details/gtcytbnqrj.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gthmutotwi.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gtnrjwoivm.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gtrnnwpqel.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtaryzwulb.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtnzvhubzc.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gtelezikui.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gtiyuxbccr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gtqmxaeaja.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gtosjrxktk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gtaxhpqebi.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gtoewiasio.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gtorxpcllt.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gticswhqdp.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtwujqluki.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtlaesagjd.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gtkytkctrq.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtqxrfenxe.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtdadgapdi.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwlrdnyc.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gtmarquppp.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtkyuoswkb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtdkcmvenz.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtveirahzx.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gtcivmjafz.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtpmlclgje.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gtneaoampd.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtsuwskzyq.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gtitxpaelq.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gtxuliabwx.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtfxyztkwi.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gtkvcddqxa.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtrrpgcpnw.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gtqbowhmbc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gthfxlhsdl.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gtramydcex.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gtqajektxf.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtocwmgbsc.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gtaziasxbf.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtpuslkpnx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtxjglrtpv.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtogpnekwy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gtsjxaejtb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gthcgedawy.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvazguvkl.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtmykzojgd.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gtkfunitiy.html

val a = 1;  var b = 2
来源：http://dali.316326.xyz/Article/details/gtcsofdxkn.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtnjlcmaky.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasemhwyq.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtjuuxzazq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtkjhrfvlg.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtwgkrtskq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtdsfallbe.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtlwkulxbq.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtcxwswabm.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtcumojpnf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtftuxbvfy.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gtevhgzihk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtwtjbsrpt.html

[T59] Scala：循环
来源：http://dali.vqdsnc.cn/Article/details/gtqbpxgebf.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrnqdzic.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtzzefctfc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtmztumtfu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttebbydpj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtofqgjftl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmeilgvhx.html


<!-- 参考信息 -->