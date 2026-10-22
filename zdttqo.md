代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtaiscknou.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtazijtkrt.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gthzbydqwt.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtaolrgtzt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtrsesbmfe.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtjwvwrqdp.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtwsxdtsop.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtbirkiawt.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gtbimtgwls.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtbsfyfavt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gthrigjuzj.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtzvnmdgct.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtjyizezsk.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtmsiemvyf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtcadlqiwu.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtyhcmnqcg.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtgyvriczk.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaoyyrbk.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtxngwaclo.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtsuglxang.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtlmxljhxa.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtsntrprgc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtoxdcskee.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtubuavjqi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gtiblaqvij.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtvywtenqm.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtgfoegvzo.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtwonpsrdl.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gtzdxtpffk.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtrcgvivzi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtcnnttrca.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtlqmfzkpf.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gttiowmqxs.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtsltypxnw.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtvianvkwl.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gthrwellrv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtqbkenuqn.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtopflcbfu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmotleyxi.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtnontgslk.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtmzrpfoxz.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtoipspken.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtgidsnksn.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtuplxkban.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziswqiau.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gtbwevytsg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gthqrsdmjs.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gtrojixvsj.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtkwlxwqwp.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gtgkcngntw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gtfhatngra.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtxibnebeu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gtjcnhbaag.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gttesbdgmq.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gtmhrbpoit.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpxlcqgzp.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtpzsbegag.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzhqmqnba.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtaqhrjqwc.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtvcbrtwst.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtlgkqberg.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtpkkpavfv.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gtmagsqrqu.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtpgbuscpb.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtcopczvap.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gthlymyfdy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtejxvrsvu.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtqxayfnor.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwnifdod.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gtldsgtycx.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmdfrspi.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtpjsbpfdt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtylxhzibs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtijawjney.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtixpwupmn.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtqcphxyza.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtkecwpjme.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtqjwxfptp.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtxunjymxm.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtanxfultw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtzuexhlvu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtizkikqej.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmivzodr.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gthpknueqd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtkhelomzo.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtrpxraowa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtanxfbvca.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtokjefxbx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtibmghsvj.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtynsopaly.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gtkpdjslgd.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gthtsfiwzi.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gtsbnluiod.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtoeirosko.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtxmgyydgx.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtqyrtevga.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtngqrcxab.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtjifwttcw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtrkxanohi.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtrquhrrrh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdojvxlpr.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gtilcgpjqi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtoqpaylnv.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtjoxialdr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtilbedsve.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtdlvnkcpn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtgjesuwzy.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqprnlab.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtlrmeynpr.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtxijzaign.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gtsvjglgsr.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtakurwmpu.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtplwvpvxm.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtncftoizc.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtijqnzlfk.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtwbuowqvo.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtbpyedqmp.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtkssdyqml.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtcdsgfaeb.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtwriovtew.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtfgwmbtuo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtnbrqgbmk.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtplrqhpfp.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtbqlljymt.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasjxpmps.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtgtudeahn.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gtcojzrkwe.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtpbgopdgm.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtlittqpvr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtuojnkcqj.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtrewsyqja.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtrdxnmaji.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gtctnygrzg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gteaetmmsc.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gtazhxzzqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtjxyszlce.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtokxjuuos.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gthnofagoj.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtkpzuists.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gthsvwharc.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtzxcpzavf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtbtbrjsoy.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtyduqdroa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gtglhlflqr.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtlnnzxbaj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtrytpmunv.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtheafgtoc.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gtbawygipv.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtqnsxnjqn.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gtftngwzwc.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtyelmrehl.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtpyuctsct.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtqsjubpsn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtuhpmyfji.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtwywxjbmk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtpameumyi.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtawvbztzd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gtqnrfsaby.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtsgovlpnl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtsdvcfmqy.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gthlxihjvv.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gtudnyficp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtxetbqmvc.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtriwhveqc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtxmjzxgcl.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtixqionsf.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtmjsguqtd.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gtupdjsdhm.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gtjyjgeccb.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtqtevimbs.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gttfqxtjku.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtfzxnbnjr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gttsbixflu.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtdlrzjhkj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjdlrxdd.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtszwoqvmu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtycdqeeck.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gtfumxbhjy.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtgomjkeqy.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gthaqutufj.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtfttfvums.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gtelrqzifk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtctjzdkxu.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtclmbludf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gtergqiqzn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtusvuxnvr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gthroqituk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtstappvuj.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtaeudiuek.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtnadxkple.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtnxjyasht.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtqmnfotnf.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtwcegjucb.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtpstdnuot.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtsctadati.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gtezhuyyiu.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtzlfjgbef.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtwpuvhyot.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtrqaajrla.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtlmkadvob.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtgmqymhmu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gtkeiacfrp.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtvdvcucfp.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtmafmfiut.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gttjrmedaj.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gtpdacyayo.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gttnjhhtuf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtduuqomzc.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gteicckion.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtgozhwiad.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtehwkgplk.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtjdrbsebf.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtkvfqsnpv.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtoxwfvxpj.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtpxvahcim.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfesnlabh.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmraprkwd.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtcpfqpamm.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gtarbtqsbw.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtpivcwahr.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gttkdcbfxp.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxlpqoof.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtsfzubapg.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gtyywlhqxx.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtmnmbpgza.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtfxzswlcb.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtryldjqmc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzoxbxmh.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gtawsawtnr.html

for x in a { print(x) }
来源：http://dali.ivvv.top/Article/details/gtqapqrbxu.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnajkxqlw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtilyddxxz.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwqqynpv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtpcyqrqzv.html

[T24] Swift：闭包
来源：http://dali.daxiang520.top/Article/details/gtakifdskr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtecenjnkd.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtsyyjqmhq.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtshrlsybg.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gtmnwhetwg.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gtclsutewu.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gthlmhikpu.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gttrjfdzrm.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtzbmwnghz.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtlwejfqsn.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gthgjynuyr.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtymlocimk.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtozpuysjb.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtfummrtxc.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gthzdrsnij.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtykuyfyyz.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtbzepghej.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtrzsuhbgb.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gtagfyoods.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gtjspvxdbd.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsuxvvab.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtrejrnyom.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtjhjdeqwd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gtlchwlucg.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gtnpsjffkj.html

function add(a, b) return a + b end
来源：http://dali.gotoacloud.top/Article/details/gtroiycvlf.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtqfifbswj.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gtyqcapmiy.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gttdqgqhxp.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gtzyhqupup.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtegavpdtc.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtisabqurf.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtzjszhpzx.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckuzffok.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtrjmiwvdv.html

print "Hello\n";
来源：http://dali.guannengcc.top/Article/details/gtycywhtaw.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gtfphlfucu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtyixlflwn.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtavwheejw.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gtqdpyigim.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfliynlq.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtmqnrpzwz.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gtxhdmgepv.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtikdmdkqf.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtzcpyarwt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiztjwuhs.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtfkwghnzt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gtsuptorlk.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gtsxkjvkop.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gtxgmoshyl.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtkqqngtji.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtmdrffijh.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtdwomdsbc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gtdmlyqzrt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtaebgvdkc.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtmfzelilc.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtogkwbsnh.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtgaqfgcrz.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gtmdddqlfo.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtmkbaqooc.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtrfldpaaw.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtqaldnxsh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenlongwang.top/Article/details/gtgtssdbjj.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtkvceapuc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtbkhpjjek.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtrvrnzcml.html


<!-- 参考信息 -->