代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gt2dpcpgpmr.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2uahoxbqx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gt2vcbbmagn.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gt2jdzrpafl.html

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gt2qcbfyofr.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gt2kgbhbvsr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2mvjyeqxt.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gt2uouivtnx.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gt2unygrlii.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gt2vaeessuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gt2xlojmgdt.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gt2khpbuwpq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhzuijub.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inricimf.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gt2diavgsuu.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gt2mczlrnzc.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gt2wbsrvufm.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2qrnsgkxj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2qirqylac.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gt2ezmwsysv.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gt2kqsarulf.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eyokucxv.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gt2pndxooes.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqdjyrwe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqhmnemj.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gt2emvoxtsy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gt2vrhosnnp.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gt2cfvpekbp.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2pkqdumne.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gt2hijutxfh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gt2gdyfspeg.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gt2yzgpncre.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rihhkzrp.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gt2yhlpfcxj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2rfnimkfq.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gt2mbjfbxyi.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gt2bmaassze.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gt2uulllwea.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gt2uwxdopoa.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gt2ppgrsfwm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gt2drbewear.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gt2nkrebqny.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gt2mmwfrspb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2whkewyxe.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gt2bxgohkkb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ufxaoumc.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2giecxpfi.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqccwntz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gt2vddbjsyu.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2jbydmnbt.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gt2pveedakg.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzshemjl.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2qgcxpodn.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gt2icsbkzgk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gt2uqhpawog.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2sbfemain.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2owktshxx.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2nljigllq.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gt2vmallfax.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gt2noistipy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2baspweif.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2lvybcgod.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gt2fynizfix.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2uicoxqlo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gt2pbxempgm.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gt2calblpvq.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2pssrwtdt.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2fmiqarok.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gt2stqcteex.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2dqwdwtrs.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2brruztxm.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gt2ddpicnjk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2lozczlwo.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2tqvoxchi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gt2camqgzvi.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2strchqur.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gt2aswyhfxm.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gt2opszlzxx.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2eagsupml.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gt2izhmsupe.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gt2jdjvmglu.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2febgvhcy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gt2lksqjzcb.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2xoixnvyz.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gt2gexrhipi.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gt2qdrsetut.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2dwlnvepl.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gt2xkwtchld.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2mobyradg.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2knrsyngo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gt2ahkorotk.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvcuupcv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2flpvhvxa.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gt2qqxgnjtm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gt2iwljciqp.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gt2rwhuycdl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gt2iomfbrzu.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gt2ldnrlese.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gt2bghvgvsd.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gt2zqkphrfs.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gt2sxkomkhs.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gt2nyuytlgi.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2plwiquxz.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gt2bvbklabj.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2gowtbdgw.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2dgqfcqnw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gt2ajbdohww.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gt2zrmvnrpn.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gt2gwvcbzzx.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gt2igrjndcp.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2ihgjimxf.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gt2lgkmqwoq.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnwduxmi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gt2xsxhbdlt.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gt2hhovdwqd.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gt2zjbyhcch.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gt2zuwlbbab.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gt2bjyzwfdr.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2zenvgdpa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttvlvhbc.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gt2erwcdogg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2mdiuruaz.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gt2wspnubzj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2burcvfjd.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2ucwjbvmj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gt2fjiisvrp.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gt2hppwapyl.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2mewnlbos.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gt2pqmeyexo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gt2ftxvpdng.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gt2keabdwbb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gt2gucbkozj.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2amykiwmo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gt2vqbsvxgs.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gt2ooktzotc.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gt2cbezajyp.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gt2ofuqqkzc.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2cdsmnvyv.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gt2ddenfyid.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gt2oqoysywf.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gt2bwchguey.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkuzrlzc.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gt2rwvxtpyo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gt2yvvjqkpr.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gt2lcppiugq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gt2tkyrcimd.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2nnwhiuot.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gt2ovanijwz.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2qohrbygi.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gt2mtjeolrj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2bajmobpp.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gt2gibxpfmk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2slnhpnle.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2yfazgzqp.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gt2hqxckcdx.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2nkaeunbm.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vjeqkxqm.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gt2anzyogsh.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gt2inwzfgqp.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gt2pkfrytiq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2ekmnazxz.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gt2rqhpqapa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gt2nbiniikl.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gt2vlvdkyjd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gt2elaohell.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2cszdztdx.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxdpgwoe.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gt2uylaxjjy.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gt2anrzohet.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gt2qramaakf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgqxkvxi.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2kfarfbei.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2vqmfmbds.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jrdlhewj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2hwipswdp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dradohqt.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2uonhaujj.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2qcddrhbh.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2isasmdsd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gt2fkmervpi.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2loryrraj.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gt2djjjeycg.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gt2mqvxijaj.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gt2knovfcju.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gt2tbxtxsho.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2zglfkqds.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gt2bbqlxmoe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2orrotllc.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2hnwdytmy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acsztomu.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2kyunjiqm.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2xlwplxxd.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2nehmbywp.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gt2dvfpublp.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gt2hpyxfpkw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gt2xwqnuyak.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gt2frjoanoi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2pomwgusu.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gt2hmvcjqnt.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2ucdmyxvb.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gt2xqbmmhvw.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gt2qtneoyoe.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gt2cqpzczyy.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gt2redquysx.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gt2onixpfrw.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gt2ocgdqumv.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2iibmwodu.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2dbadbzvo.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gt2gdeowxis.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2bnonbklw.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2xizjrnos.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gt2eijxadvi.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gt2rabtyusx.html

if let n = opt { print(n) }
来源：http://dali.chenlongwang.top/Article/details/gt2fjetsjdp.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gt2dhlloqiq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gt2bdzpqwee.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gt2cglirklc.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gt2nfwqfitp.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gt2fdpaftir.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gt2ajaoxsxu.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkhknrqx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gt2twvpcbdu.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gt2abaoqylt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2jchcjthz.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2ywsghddk.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gt2kpegsshr.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izrskskc.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gt2ekdwdgiz.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gt2lrizgxoy.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gt2supabhcp.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2emdskzed.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gt2nwppsbfp.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2vwvbjjax.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gt2uawikxui.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2uyckqqnm.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gt2kijbzmur.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2ewzzampz.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2tpmracot.html

[T32] Lua：局部变量
来源：http://dali.quarkkingdee.top/Article/details/gt2auiserex.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gt2iwdsxaym.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gt2taxvmgkv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gt2lghrgnqd.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gt2iwrgfphr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gt2cdpvfbyl.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gt2jzzodphj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gt2tkyzxkmt.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zldmrual.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gt2akmdiwzm.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gt2adpwbtsv.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxwyonsf.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gt2mwgeukha.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gt2kdyudcnq.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2ctpeycsy.html

string.find(s, "%d+")
来源：http://dali.daria6918.cn/Article/details/gt2mdiceaxx.html

[T40] Lua：元表
来源：http://dali.nwbrower.top/Article/details/gt2ogbkrevl.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvgcyvxz.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2ulgfyxzz.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chtfzzuj.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2gdvzwacd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2cdgbuvkm.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asorhrdw.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gt2tvauiaev.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2geeggeec.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjubvxce.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2obpatvue.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gt2btiixtvc.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gt2nyuhzxhl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2lqqtyxtf.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gt2ddgyqxen.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ieziuuat.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gt2qkittyyp.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqgxfekc.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2wlxjispb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2vqzadcru.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2soyzukfb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gt2dmylczvt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wwobgxkv.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2fzmpxgxh.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2hqrkdbqi.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkaixfge.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gt2uxurjcno.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2ibamexzm.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gt2ezcayfrm.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2typctgwu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecwcyumr.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2kriwyngh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2sigcqoxb.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gt2qeetdgpp.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2fmxaoxej.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2gjkdjtbo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gt2aprmqyni.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2bhrflrev.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gt2lupljeom.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gt2xdesptyf.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gt2wlkdvjao.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gt2lpjnjhma.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gt2ofmydrxr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mfpgawta.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gt2sutuwwsl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2laexpgkl.html


<!-- 参考信息 -->