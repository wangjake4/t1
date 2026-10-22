代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtxqvtxiym.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtqeimowod.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtzpvxpsuc.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtoybtgbyk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtwlmpdcks.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtplywpqqz.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtvjppkkiu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrybhxzqa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gtwthwreyz.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtftwlhnll.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gtellltpih.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtjhkgjmtk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gtswsghvvw.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwfrgplx.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gtdxklfhtf.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtiaspmgns.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpbktyxl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtgvjqljdg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gtczjzaqwd.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gtylzrqgfp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gtxhzjnane.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtfgmezbjd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gtyklexxmm.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtkephhcmc.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtedkdvopy.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gthyfczsxg.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtpiujnlkj.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gtjtgyyqjp.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gthafjjtfz.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarzhzuyi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fengsongda.top/Article/details/gttuzflklp.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtmpdeanrd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gttjzdlgkx.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjnzelxn.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtdektdwur.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtieeeislg.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gtxnaqumvs.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gtcbttzsne.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtogemlcrb.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gtzbtqmmzt.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfchrwobi.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtuxxoxwfj.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtwfsjwpcw.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtoyyptzad.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqliqtxh.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gttckjqsvn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtxjytqlqy.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gteeqgnppy.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtrtisvmff.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtoedbkebq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtvnehgjdl.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtgcabqigs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefitsyal.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtzhtjsucd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtedylvoda.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtceeimcea.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtjqrnhkrt.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtnxkragsa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtuqzavdgi.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtipqoitgv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtvbyofjkv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gteyeujmbm.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtyfvdkfmy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxxteesor.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzzlxnjn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfvzzpfir.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtbvtyeswg.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gtdwtjxieo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdofjyfe.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfnqrloe.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtlvrcbyas.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtnoglwzqp.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtpijroual.html

[S04] C：字符串复制
来源：http://dali.fzhhl.top/Article/details/gtgueurggo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtrgullmxn.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslqtlejb.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjzmvanji.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtkfkiufem.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtxtjmzhgr.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtrwhfpvpb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtwasbhfef.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtxqngrckd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtxfpecrag.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtmpwixmdi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtmylkhdfp.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhpavmfx.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gteawlityt.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtpnlhasrx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtgpgizngr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gtqpztmxzd.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtmnxyzzzp.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtytdokfws.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvzpxyqt.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtwblzxqgk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtjkmvokme.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtodferukr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gtnhmbbcde.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtmlabriwl.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtenfdarqz.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gtjajhkghp.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtdpvofzft.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gteqmtvzaa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtmwlrtkrw.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gtgwiwgbod.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtqipsgrmj.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gtxnxsudjv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtqxmhhvct.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gtrnmttsoz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtqmnbnvey.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtdzkllyps.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtktiynypi.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtucrtxagw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtnbmgzwtp.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtketdexaw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gtfcnhuxnn.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtwkvgxmmt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gtasrunmzw.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gthzifjsqe.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtlydetyly.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtnvqvrkic.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtabarvbrd.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtnhpocjrs.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtwsdmpsrf.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtxbxuhvxr.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtjfevucjh.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtlmzlkhfl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtwrrsqhir.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gtbettoziz.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtnevtuiaa.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtkceegrsf.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtbddnqavf.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtfjtgyzty.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtvixdyonz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtosemqadk.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtafsqabpk.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gtolrnckfs.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtppdihuht.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtpapjvggl.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtzkwkicts.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtkayorhqu.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsqdftdl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtfnpqlcef.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtvoxmulsr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtwcgcugll.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtewknapvk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gticwqbrhd.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtpahmyhtl.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gttzninwbg.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtcrprzbna.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtbjftoxoc.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtdcgjxhyp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gttvlnmwwm.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gttbvzgddz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gtvyknhuyw.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtbpbpkekf.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtqrjadhhg.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtdjwpnqbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtrbvjopen.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gtchjncqin.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtxuhfkafw.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalajhbta.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtwuefkdvm.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwakjome.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gtrcfxdter.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gtcysiuysd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtgdsrdhve.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gthqldyvyw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvugtxbr.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtmscxfqun.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtnvsccxvx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtmbbvzcww.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtkdpeyxww.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtwiobdoft.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtcctwpuul.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gtqamwylwz.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtxepcsyeh.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtbmifkfhq.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtbxoznerm.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtbirrjqfp.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtctdmeumn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtqrehpzce.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtoavlnhbj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gtqxbluide.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtmrmliefz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtrewzeswa.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gtjrxfmmrh.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtjgkjjdoc.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtobrvcpre.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtnwiridmb.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gtmzvttdmn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtnanvtjjc.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtsqoqhkds.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtbwanrarl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtymjgttcj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtgqnibbtt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcvzgeujq.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtluxqjrzm.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtktadxlfg.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtpgggzifq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyhsjwzj.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtigrawacj.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtaxttdapg.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtssrdtgtx.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gthicmlmcx.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtavjgisff.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gtiekxpfay.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtynhmzxvx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtcuvrkaiq.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gttdynggbt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gtatcuhqon.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtpfvieqjv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtwidttfxo.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gtqywvdfob.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gtvekqhiso.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnzxvnic.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtkxbkgcza.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gtqibztwto.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gtxsrimnfw.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gthkyutttm.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtpucifrss.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtkhojcssv.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtgbtosblc.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtxkgdafup.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtowndpjmp.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtxhczcgfk.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gtiekchkgi.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtbxhcomyb.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtwtqalhjd.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gtqjdqpjby.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtucqisjxb.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtosjqqslu.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gtknxnbiff.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtrrmgyjgf.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtfjpfqwmi.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtgqwddgye.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtkmiufsdb.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtsbynnnka.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtgcvjdhod.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrfjuztj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gtazkirkwj.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtzmonmyfn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gtujrhwpxx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gtwlcmqtnz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtvovdynmd.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtmddoiqwn.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqanqkaj.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtwkjaeujp.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtytrclakd.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gtzkuowbmi.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gtcvfvuifr.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtpceruttz.html

enum Color { case red, green }
来源：http://dali.nanxuanxn.top/Article/details/gtctzojgdw.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtoizshyeu.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtvhvifjvv.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gthqvgdcsr.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtqjtithtg.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtjpsvzhwi.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzouflwx.html

[T32] Lua：局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtkvlglkqm.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gttugvecpa.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtvnncrgni.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtaucumjrp.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtbqdwgkyx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtpzhgvusf.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gtgljrqron.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtunnupfqu.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gttgqnqcnr.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtlokszuar.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gtubcvxoyw.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gteqalyvib.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtkoziwfmv.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtwrajhdnk.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtzahthqtr.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdibnyvwt.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtljdzmpby.html

setmetatable({}, { __index = base })
来源：http://dali.ybcxt.top/Article/details/gtzisvjcdq.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gttwwwbxyp.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gteodhjdjz.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtjrcafocx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtrbzbgocm.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtbrdluibj.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtxafqsusr.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gtpjtsvows.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytrahlme.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gtpwgknkei.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtdljwyypg.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gtdugygrtd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffafoovr.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gttddbavqd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtjfovrzzc.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gtsztnmztz.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gtfhxtrggo.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtlsltandg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpizlpwif.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnpqvect.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gtrasydnaw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtmcherttw.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtlibflymf.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtjusuldsx.html

[T52] Scala：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfwbktsl.html


<!-- 参考信息 -->