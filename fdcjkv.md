代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtfbcgvsgg.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtjdeignle.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtpqsgtkca.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtbhgtzyzd.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtsuhuokco.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gtmeyzjzlj.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtmhcnhtxj.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtnfgipjlv.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtvrhajzdf.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtbkxwnuid.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtjkubgzpg.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gtfcpzelxi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtqmjzrjmp.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gteubjsprk.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gterijdwmg.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtweiehipy.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtnvwnwsrg.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gthkehpfxs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gtfwkwnvln.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gthxybhups.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gticxtpkqc.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gtjirgiyiv.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtgkljfges.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtpmjlyaaa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gtrinyjdtj.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gttjpdfndr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtplxoktda.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtouullbzr.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtwalyrqnl.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gttsohwmko.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gteifigzoa.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtkxlwtqse.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gtzznkmrfm.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtipsugfsh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gttmqzazka.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtrubpvvhh.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtswgioygo.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gtfhsytjda.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtbiquvefe.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtrigtparm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtafpljhma.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtlxycjiqx.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtnhdfoehu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjhsybqsj.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtehfiratv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtluracsvc.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtjvuyogau.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtujseadmy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtkaipocbg.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtfenrwecv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gtgecfdnfm.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtwzekofwy.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtudikoipq.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gttjhbrpqa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtigdjrvey.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtaenjnupw.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtsktmqsrg.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtkspcdcll.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtkwevdxyr.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtelrvlatk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtksnoblom.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtmouhfnlf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtsgyrljso.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtzojgqmor.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtionalzaw.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtgipiwaks.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtuizgdonl.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtbeqpjlhf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtuhtavwce.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gtlpovpfjk.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtnsjkvbgc.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtwbrgnnes.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtrmllkvtw.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtrhhdbpdj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gthstcwaoe.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfovmgkqy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gtdrpwngps.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtsgkypmby.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtbxpfcfpk.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfjkyukf.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtpgxyanpm.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtuglicumc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtcthqulqo.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtoqnsjile.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtarfohfbx.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtgndwkrcc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtkitbvepe.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtjqjxvbot.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtnmqeetxh.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gteesufmth.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gtkgpsyyxd.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtkgmasdni.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtnkbakakj.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtptqelqeg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gtuijrgjkm.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtbchmicsg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtodeaddse.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtewkhmpoi.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtummxlfgy.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtdgzqsquu.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtyyfrvsnc.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gtstovnzho.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtypmljung.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gtrqycwcsc.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtksznyyxc.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtdiigkqls.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtlrdjrdbf.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtkfetfrye.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtskaqwpdl.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtnxwcruso.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtalyeizvi.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtqrftjfbh.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtmlomxsia.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtufpcecvz.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtcdvcspos.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtiwnymdok.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtitnauntu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtcvpfzpyf.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtcmsxnsnt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtomljejpe.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjsldcxm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtvemaporg.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gtmngxhsmy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtiqsfekur.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gtzmieeetm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtbgrbrrrz.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtvbmwbygq.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtrtbywxki.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gtfpbhqvos.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtgzkbxytj.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gtytbduwna.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtzkdpwqaj.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gtbmwviwdo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtiujwqrfk.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtfrqqhpwg.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtwwllrpac.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtyaizmtyt.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtflixvwfp.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtuzmfnlrc.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gttlszmmvp.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtebkkqlnw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtoiipaxnx.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtctjjbyrk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtsxdbggdw.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeinyijz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtdjuvrnez.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtrdplhuhx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtjktgdnjy.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gttpkcabyc.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gthfamslww.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtryefihmc.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gttvkqxpdl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtnhuhuvpo.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gturpuqvon.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gthctpuski.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gtlxmusqfq.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtynzqhssr.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gteplxenya.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gtygxtjyzp.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtcyrqdata.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gthiihofen.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtachrbzih.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtzdyijdve.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gtcaqahhjy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtzafgycpw.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtyasnkhpj.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtktxzvljk.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtiaywwann.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtuebqvnbk.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gtybragcrn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtlwcnpg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtnoibdakq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtrtxrxzul.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjkfxgymi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtzoomixhm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfxafusx.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtbbccyssb.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtzivsalda.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfecgdvk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtopitbvvq.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gtyoerkjos.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtqihnvsba.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtqgblgris.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtqkzxaulo.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtbltcloyc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtyluhqzqu.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gteuhuxsks.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtxwwoudxb.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtvlydzmfb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtiuxceoku.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtfjlvokkh.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtvcijrbpm.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtkyogclgt.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gthkmvtbkg.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gttkimeotq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gtrjptwaus.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gthacelxis.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtlnsuuomg.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtiseffieb.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gtxotujhhk.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtttyvbcxj.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtnaliwfwa.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gtqhptlafp.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtsyricbpp.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtldysuoou.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gtguypvyla.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtjwpfvadh.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtwenmkknj.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gteaxpngiw.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtospzagxy.html

[T18] Swift：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtiqzeqqte.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtcayzliuo.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtpqnlyupa.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gttlnnofmx.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gttoglwsqn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtxpsguxha.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gthgbmtgyh.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gtgkqiamhg.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtbkblsbhp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gthnrjpjvw.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtcetjrkkf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtrgzbjytt.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtyvdsdlps.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gtszzzbikz.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtmbjcejnv.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gtrxfkputn.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gtlhrbsdob.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gtvxmkvfig.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtodxxutwi.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gtnvwsekik.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtzndbtllx.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtzygcymdi.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gtelzibwqj.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gtaddxvimx.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gthnpkoclc.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtmykfndio.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtkknyzcmo.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtnqrcawec.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtldcscviy.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtscdxvgyt.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtunlhizhd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gtlczdmxou.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtvispcfay.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgpdtooz.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtlwaosxzq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtdihuioid.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtttcjuvdh.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gtvhpqbnlc.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtrswsrpbg.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtaofbvtaf.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtnmjwcnqa.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtznsneydy.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtvijlpfjz.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gtstfutsio.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gtazloexov.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtrhyiahnz.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtxmtjrhio.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtcwgzincp.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gtjxgdxzdn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtpxkkrxqc.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtcukncaqj.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavjfbccw.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtpmwvcnmg.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gtoylnpwtq.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdqhiqaa.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gthlofkvqx.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtugyirnfu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gtlptzuezd.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gttszhxhyu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gtnnordhmq.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtzqhhksxw.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gtpadtgzfp.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtbreqcxkd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtposhuyzt.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtbglrolge.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncomhkma.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gtnfeyaiiw.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtekjffagb.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtxrxeuyrk.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtectudgyy.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gtcvswfyoy.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtxyiaqblp.html

s"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtiinapwib.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtwzrriijv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gtqbywihbe.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtsuwavlfu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtqlvgadxg.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtfcggjuuu.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtzfunzbws.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtlejzjpak.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gtzngrpnep.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gtcbfrmmwd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gtxeoxnbvq.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtcrxtdcah.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gtjtzmjbgr.html

[T60] Scala：折叠
来源：http://dali.zhengqikj.top/Article/details/gtxkvzbwub.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtrkozxnno.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gteiusrywm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtenfmpyzm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwsenldkn.html


<!-- 参考信息 -->