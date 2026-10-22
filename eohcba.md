代发 wailian999

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtqkhoopbc.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gtkastqcav.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtsnfmblyk.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gthfqsfdsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtygrkoipu.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtmpbixiqh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gtfcmnsgrs.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gtyjdnqlsc.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtsaxuwyop.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtwoghojxd.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gtqqrcsyzf.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gthbqcyryu.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtaerxkelz.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtgueuufvj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrklravhl.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gtmrqvhlfu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gthknnlsmd.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtjqtcbsys.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gtysgfjqiy.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtqzbeasbu.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtkwmteexl.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gtqkjjaqvh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gtyftzcdsd.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtvzcovevs.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtwyojftkf.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdnybrej.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtrlyafopw.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtzutmivsh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gtnwlmssez.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtffshenae.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtlpsmjnmt.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtqyaekiqq.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gttkbwczsr.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqtwjjtu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtmmqftdfz.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtgqudfrup.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftzgghbd.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtjzlnuioo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtnxlpapeb.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfyiohiw.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtgfsqtajt.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gttwriaoid.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtvgewknrx.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtaycmajgb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtokiodcoj.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gtkhrbjdji.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gttbhteigh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgyjignsf.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gteearvhdd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtuarwqdse.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlnltdxr.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtgthpnprh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtaiuecnhe.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtgcwkemjw.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtsqcveutt.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtkkqswlqi.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtrrewfmhi.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gtmuirenro.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gtlgzyciqr.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtuzqpcvfp.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlmxmnrus.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtcysiqyls.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtyedejcdt.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gtbnbtwhec.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtyeswxzsm.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gtgxtblpoh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtuyplcwjn.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtbqbsklgt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtnswbankn.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gttuknuttq.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtptjcuhvh.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtypeaeqnt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtpdvqmcyr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtbqqucvln.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtwadicrtm.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtrxndqnfg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtwhocyrft.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtznwhfnij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gtvdbtbjgj.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtwbsaiwvt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtornebmak.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gtegqunlik.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gtadbbfxpx.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfzxkghp.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gtouheqdsb.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gtdvrajuzo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtqtyhfgsq.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtzpxyfbyw.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtzpxzxdac.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtiqfdlmaj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtdhehcslu.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtpjpwywmf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gttdzqccse.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtbwqpwbwn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtdnpfei.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtetptoeka.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtqextfacr.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtamwezcju.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtwfnnzzgf.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtvnoqtzwp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtnovylnrs.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtxodtwrfp.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gteevirblz.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtjjisyssq.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtstudcddt.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtqqmauggl.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtsrivxlfp.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtzhydgbof.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtvavslsci.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtqozecozj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gtqeahssys.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gthbypvrhc.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtzoxfwgyt.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtndatnhzf.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtaguenxry.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtdsynidtn.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtzceotmbo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtlwymynkn.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gthdfgiivy.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtrdorfugz.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtjucaukaf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtqxedezpy.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtfucgeurw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlqxcxef.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gtxvrukkqj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtqtrnuuzl.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtcfgrusmb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtwfjhnmhn.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtpuzbqzvz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtvlmbsvke.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gtgobrruno.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtibczgnzi.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtjroawvha.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtnjhabzhp.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gthpiozozm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtahqmyoce.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtmyfogssr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtepcozwjp.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtsdhthetd.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtnprgnenr.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gtlbtvmjwr.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtcofyeshu.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtsylgwwos.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gtmennbkyz.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtlkmwylqi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtvqywwsuy.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gtdwaznpro.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqeaeaedw.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtwfnklcvh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtzinltrtg.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtpephqzmp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtwqwpdifo.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtsbkefldb.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtixnbcoue.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtffsvondd.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtgiixxxlg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtqbqmidjm.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtlwlzzzsv.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtyidamzsj.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gthhnwuozv.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gttbucpjlc.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtfmsmgkca.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtdvxiqliq.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtluycazgp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtiyupsupj.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gteetodzry.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gtlwdpocxb.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtiwkrwifk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtwultirms.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtbfyjjaub.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gttymewmbj.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gthmkuibwv.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtjfheygtm.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gtivqszlot.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtazpenmcy.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtznskvgyg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtaouwajzc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlfvuooiq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtlxifnssu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdtccdtmz.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvarhoeg.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtyfslqtfc.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtqzgtmpgx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglrtfrat.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gtapxrbvyq.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtbvcbcueq.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gtxqxyjxng.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gtjjmsaxyh.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtrwfvhkvg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtcxnwzccr.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gtitehjnnj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtfarpoctk.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtrzcyyqpj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtnxyqveyx.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gtrshvfcsg.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtsbkzcbnx.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtnliwdins.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtsqrscmjq.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtjoexemhl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtawicxzuh.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtfvpmtkdu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtirpcpcrs.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gtnupiefwz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtsykrkval.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtisguibdn.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gtiszgcevx.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtvjboipdl.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtckezbwqt.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtvacdtbmv.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gtcxzrucby.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtvutptuer.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtgftpfjxl.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtkrcdhaja.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtscavmklp.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gthfalvxgr.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtluodullq.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtqjbudsqg.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemlujcun.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gtloyzjohf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtknvjqurp.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gtqqdyrfjn.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtxecovueh.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtbrdbehhd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gthprxzwgd.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gthgzmdhnk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtolipbcvn.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gttrzgqlyn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtzymbzczk.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtthrvoinp.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtqsrgnpsq.html

[T26] Swift：类与重写
来源：http://dali.zycfv.cn/Article/details/gttcznurar.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdafqojl.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtqsygeewe.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtttfzhtvk.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtgwibbtmj.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtnhgsjkyr.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtflrnglne.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtjzimkppz.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gtoeofhdxu.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gtzqifyhqr.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gtswsbpvzg.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtczoadlpm.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gtonofaizq.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gteehrfnmo.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtygffkgib.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gtuuljfzbd.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtuywjqqaj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gtojhuoglq.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeyquqqh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gtwhiicans.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gtqcsbjvlt.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtnmvagebf.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtqsfscmzt.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtgvgzcwsi.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtcomypkzy.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtusyigyzi.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gttocnyxgd.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtvultvjmh.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtvyoruzvt.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtgffmrliy.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtchgbuy.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtzvaxftcz.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gtblvjttae.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gtwhhoyurt.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gtfsigrkko.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtzzqmvddv.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gtbobdnxkb.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoieaixss.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtiwcpegan.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtxhqrgidk.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtolzgekqg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpsyafqzf.html

[T47] Perl：正则捕获
来源：http://dali.sweek.top/Article/details/gtgjnwjgne.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtmwtzrkzg.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtkkbrjrat.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gtmwfhrscq.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtqfmnjopg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtewvoyrtn.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtorjkmhau.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gtwpbwelfk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gtvyvnlbpm.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtronratyt.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbfjlhyq.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtlwdswzlr.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gtaoehfukx.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gtwdniymed.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtbjaxmcdr.html

[T54] Scala：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtjuuvigke.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtewwhczun.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtditqcgtu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gtywlizjag.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gtnzkmuuai.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gtntvicdom.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gteqshsywq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtbiailpxk.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gthbusyuxs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtjowvhuee.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gtstkmfmfx.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gtbjqynjlb.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gtejgwxevc.html


<!-- 参考信息 -->