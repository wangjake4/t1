代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtvtrzbyfp.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtvevasbrd.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtqwslesam.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtcukucibx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtruwuiuea.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtgfqbziou.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtzqnqtmpr.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtuhavpqmt.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtnfsetwff.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtexkgxont.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gthazznbqj.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gthvrnmmcb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtvltjvayi.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtvotbgoaj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvovqkjwj.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gteootjlhk.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtmxitxsnv.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtqolrmemt.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtijpxknra.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtdermuwet.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtaniwvvcn.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gthlblgour.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtzufrxkyo.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtrldcujpg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gttesxvjni.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtpnularyc.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtwtplycav.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxclvbajb.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtpbreqxwd.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtxacxnmrl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtehbcfdhd.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtpgezgkmv.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gtyfebaloe.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtywojhzkl.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtktzccahm.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtglxiarff.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtxdlqahxp.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtgljbhtdm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtvoeugnxn.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gttosysqyd.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtmsbcutkk.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtkbmylxuv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtbhirosol.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gttfifmpvg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtjngwcnxd.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtujpfmpva.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtqywpwvjx.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtfsqewacp.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtxuqsedjs.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtsczompde.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtpygqxzvr.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtxdcjuhno.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gtnbkidwam.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gtftabesgl.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtbvcozjyr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbtzijzcp.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuxjmtlf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtncodcqnk.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtyryjrcge.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gtktcrfrat.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtbacdwuhp.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtklyekfek.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtktgtbxqo.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkrzfvcb.html

int x; scanf("%d", &x);
来源：http://dali.zdqjudy.top/Article/details/gtepzkqnjz.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gtjtcccvnq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtmtmaoodi.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtoxwvgirm.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gtywibolte.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gthhvwtpnn.html

strcmp(a, b) == 0
来源：http://dali.iojbl.cn/Article/details/gtzilzvqoz.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtbdeyngvb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthouypwbe.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtpojylbyk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtoapqutwa.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtjqrtckie.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtkkbkslbu.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtdtplupwr.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtmlcxauey.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtagsesgrz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.bjfxy.top/Article/details/gtgtxfpfhj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtvxulnspz.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtsrwqdhgr.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gttcsunsiz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtxfpnmtae.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtswnuuxuh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gtpemwuoju.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtzqbzvgbo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtmjehfjer.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtcwccjxxa.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtppqpsrjb.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtwbwgqgia.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtsxrbxjvg.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtndxzuqbt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gttqazavlo.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtjuhglydb.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtsrsccuoo.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtwrbuhyoe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtoqckoxmt.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtnmtzikkj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtzcexqhkh.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gthbocpayr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtsspthyns.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtwhexsjgd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtqsxiyljz.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtesqmmywr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtudiisfla.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gtgliikooo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtmryzmjot.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gthurwhgmq.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtmucmrtzf.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsrfhfuo.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtlogzihza.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtrmfopfkd.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtxtfcaloy.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gtclhwlekz.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtqzfnuzgl.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqqutfyi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gtjzruuvvt.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtjbhxbmne.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gtoehhxeqb.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtzbvdbbbd.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtbrkzdstr.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtawcldtan.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtgscgqcry.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gturrpzsdm.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmodhlym.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtwlkmefgy.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtmqfdesgn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtrbhmfkoz.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtrjoiepgk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gttsdqtfsf.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtbuxlhrxt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtricebqjx.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gtbhbkuvjj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gthcugevwv.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtworkaaqk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gtnhmxvrdy.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtrgyaanoq.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtnglueedq.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gtopplgots.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gtonvenmwf.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtonfgkodl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtokbsrrcp.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gtxpakxngm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gtibybojzm.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtzemyxdzd.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtyxtmchbj.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gthvkxhoxu.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gtfwxewqpe.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gtlhzyxkgp.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtbuskrmcx.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtigahcnoz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtnacjbvap.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtkfbrossx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtnjmjgcdr.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqimjmksb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlqzhvqcd.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtumhsrhrl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtyahdmfur.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtptlicjrc.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtykrezhyf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtdvshlwrv.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtlvwlkyta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtydiwegps.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gtqyqwbqus.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtrtpuwuax.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtcpkyliqm.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtntmscrnl.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtpmmgyztj.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtixmcvbgv.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtzsrnermy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtcezsjjlq.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtkrofqkth.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gthamgxckw.html

[S56] C++：optional
来源：http://dali.shzxlz.cn/Article/details/gtmvxypyqy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gtxkkscaqh.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtwcsdpipq.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtdtygkafe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtsjhfjezx.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gteogwlmyd.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtvvllgtga.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtsinuzndl.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtfacryzrf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtqoyiprad.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfkfenxal.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtsfxdrxpp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsqzeofbs.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtxcqglyqx.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtgvvwyafl.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtxqaqgtyt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtuvljvprj.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gtqbsxfckg.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtffmxombu.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtpgbncohm.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtakrwknkg.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtcbdcvnft.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gtjtjnqtdc.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtdytiwhqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtpfziplag.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gtgvysodmh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gtfpbfrxdm.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtsrooqxsl.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtsxazemvf.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtdqpndrns.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtzpxfrhch.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtemvmmsil.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtylwwxdua.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtcnbchmoz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtavbrfrvk.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gtmhxgzbnx.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtrfiwcjng.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtcywwzrsq.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtczaejedg.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gtytpdfcen.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtofiwkeyq.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtartkmzbt.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtgnuenzxz.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtlocdpuuw.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtmrswsuws.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gtvjiohiwa.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtketqmnvu.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtciatofaf.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtbtqvgx.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtvffstshs.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtcxomrcqk.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtjkgmfcep.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtijvgyzll.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtayrjgztk.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gtpevehviy.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtorcgcoxc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtakjfkolt.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtlhcmdbxf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtdfszlpij.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtztfnzgmd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gtjkorkfln.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gthuopkpyh.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gtqdmuqznc.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtlhefonzr.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gttrpcxazc.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gtngrfoywh.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtcnzqmhcy.html

[T28] Swift：枚举
来源：http://dali.pycfn.com/Article/details/gtpuqvoxol.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gtiiqibgix.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtewqhujxm.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtkgremzkj.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtjhopqumb.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtwxsqkuvq.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtuqbclmkn.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtmoqoodas.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtakfhtjrg.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gtqesfoylk.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtufyfqgsn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtasjoxihe.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtwpnfchng.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtabldbtxm.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtbgjxmcrp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtvvfqhptn.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gthtdohbwo.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddndekzl.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtintdkdxp.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjwponlg.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gthwncttpq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gtqzueaemw.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gthsrsfsgx.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gtgrgxzjsa.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtxzgxyees.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gthkzszodd.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtbnvedqvl.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtnpwiamsr.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtejrtcijv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpubfkaiv.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtyesenalj.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtfaqtyrra.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtydjmicms.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtmjywrbkq.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gtjqbodpzp.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigufen.top/Article/details/gtcseqrchi.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtgpvocziu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtomiccgdv.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtrtpnmchp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gtvwdbowbn.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gtrkskcvti.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gtmozjosaj.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtdgzavrdz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtdidtwsrd.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtsixllmev.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gtowcwjsha.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gtgpibbgds.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtnahlqzfi.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtmnnyzzsf.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtcyhdcbim.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtfnkjoulg.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtutjlztdy.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtefdrelzd.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtcihsltrp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gtsrothcly.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtwhchhscy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gtanxeadsx.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtcrufnozf.html


<!-- 参考信息 -->