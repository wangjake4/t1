代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtfzpejvwf.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gthblgverg.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadihamch.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtvnagiapm.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtxifexgjs.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gtpwylxgrc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtogdxhjgi.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtoitcedyp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtpjvyjeyz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtbxekntsu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtzthzkdqf.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtknnponuw.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtbgxikycq.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtcaesjtku.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtkcfdmlzq.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtsnhcxqci.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtihlpxepj.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gtyuphhevm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtqdqcvnfu.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtgdngxzwg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtszozhjnk.html

[R66] 定时任务
来源：http://dali.dashuyun.cn/Article/details/gtqjrpzyxt.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtjpnjyywf.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtidsqlsdu.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtdktgbnda.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtdttfjrxp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gthqokgcla.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gthsmujael.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gterhfdeng.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtxmqozxbp.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtlkcauvuu.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtepqlhows.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmbfaqsd.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gtwmjzwaxm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtyilncyom.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtwokbruit.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqijnebk.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtioqeljli.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gthydlxasz.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtmpgrpqrf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gtrhlvingw.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gtfdxhggkh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtsuxrvags.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtgreishus.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtswvoaxsn.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gthxihihrd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtcjvrjnig.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtmxpxvrhz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gtuwrkxqdf.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtbfsyepzv.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtjgtgirff.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtshdnvlfz.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gterkawkrw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzhryediz.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtzmphsncr.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gthestbvyd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtegsaviic.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtihyjghqx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gtrzwpodlq.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtyzczuxro.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtgnlsphgp.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gtrvfcyobe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtullzqfeh.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gthtlshcig.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtmmxmfrij.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gtgybxjfcn.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtibdfikyu.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtxnujuyeu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtxbuxqevs.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtiemarzpe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtyhndatef.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtffyxjqxr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gttwexshwu.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gttvvqubaw.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gtrwcfurlv.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gthqoljwwv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtdgmfxkxr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtofyyjkdv.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtvxllrcng.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtwgpztikp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtetyttdkg.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtzgdtkowc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtzfssxclv.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gtnheewmsm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcymmsfss.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtoieawzji.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtasllpbve.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gttdrxzmoy.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gthctbqout.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtkikdvqqy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtchxbbnru.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtgqwpuryi.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtszrrodcp.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtvvqkptjx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtzvjaxxqr.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtiwwoaeab.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtwjwhiqmq.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtlpzhbmtn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtydbelzcy.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtmscufmmj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtikiubjaw.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gttbnegbvb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtgmssnggx.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtgmwfvnry.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtadrlfvkx.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtoiqthces.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gthgqlrjar.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtujlyslqt.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtbhyzmmxz.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtwcypxhpk.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtuknbpvmb.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtmkwimpbu.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtzbqahjqh.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtvxxuahim.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtzahcubmv.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtxzqzoorm.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtmunkiruo.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtzbnbymjk.html

#endif
来源：http://dali.wangdashe.top/Article/details/gtyuluosyi.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gtxunoupnx.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtasoviduv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gtijpvofgt.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtsytdtzvx.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtrqodpmdx.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gtsznmhkmy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtytosytoj.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtgrppjotd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gtjabscqqp.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrhlwcos.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtvryfxhfu.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gtlvfdelfw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtrrpdaehm.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gtdmciiyib.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gtexatvkgh.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gtzyhisrzs.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtjjmxoubz.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtfmuogdog.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtderzfqko.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gthikgekbr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtiaggkdks.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gttqlefyje.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtuxzyjxho.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gtycugpojm.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtqwbwzyfj.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtbasuovev.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtjiotzoxh.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtsheolbpx.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtaknwnaxw.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gttjebmwue.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtlyosheqh.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigcovbgd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtqutxtfij.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtsludekvc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtwpsbqhif.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtscmknezb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtyialfnkj.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtprwzqjhp.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gtponxsoos.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtanwpexex.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtpjdfmlkt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtxeglldlb.html

[S51] C++：显式类型转换
来源：http://dali.fengsongda.top/Article/details/gtnvnnkthn.html

static_cast<double>(a) / b
来源：http://dali.xinyue.icu/Article/details/gteqhplelj.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtsweautdj.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtnevdtcvr.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffktfzel.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtzciwuspp.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtklljsnts.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtopafusdf.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtliybddrk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtautvkkba.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtyhjbaxab.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtxjavcqje.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gtcwqygrsc.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtndsrilgu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtjcfpzllc.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtluvdaaei.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gtmmaahkrw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gtemfvsiqy.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtgnaqcuzs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtndieqatg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttefkqmpm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtxsqngsiu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjrtcadqn.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtjrabyyrz.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtxfcmucay.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gtyedjhdzv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gtibvwyxtw.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtzhjheeby.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gttvmnejta.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtnqokrlhc.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtupfkhbux.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gtrqdiwikw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtciscoyco.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtqoaoxkcs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtqstuchbm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtcukgloxm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtgrngdaki.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtxghdhdwh.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gtmipiwydg.html

[T09] Kotlin：扩展函数
来源：http://dali.cheryme.top/Article/details/gtqquxgtdm.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtrmhrcolk.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtkukaragu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtdzcgmzag.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gtldvlsjxh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtveofktky.html

[T12] Kotlin：解构声明
来源：http://dali.vqdsnc.cn/Article/details/gtbqubtglq.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtrigmvczn.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gtjtebstno.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gtwqisalfs.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtssddixwk.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhwnbern.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtcijttuzu.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtrjtghitf.html

[T16] Swift：Hello World
来源：http://dali.yueranfly.top/Article/details/gtfnqubzur.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtxkcqolrn.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtcxssrpob.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtqnupxgus.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtmmsafhfo.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gtvqitliip.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtjrsvzbuv.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gttcsrjmup.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtjsutmwqe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gtcqbwzzgd.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gteonyexyz.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqihguqag.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gteqbbiehn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtalqrxvjd.html

[T23] Swift：函数
来源：http://dali.meibo888.top/Article/details/gtjjmclgyz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtuheqthdf.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtecswrlsh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gtmxzrzxon.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbggttfm.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gtiyluwrch.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtmzysbfpt.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtbvnyjpjw.html

[T27] Swift：错误处理
来源：http://dali.bjfxy.top/Article/details/gtuulrrjrc.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtqbgwjtwe.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gtnivmbbde.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gtzzdzuwtf.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtusgrsvpi.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gtpfowyevw.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtfunuufkc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gtgibdqjvk.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtetknqnof.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtrkttkhdg.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtuuocxumh.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtknbngvbz.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtyaotybmd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtkigtrsro.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtoecccfsx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gtmxeliqsh.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtqrtohput.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtqeikcnuc.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtzswyfarn.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtudkrpsuk.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtdkotvdwx.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gtszbchtja.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtxbjbuzkz.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtahbxrzlg.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gttwvsnchu.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbipgpikb.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtfgxqynst.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gtlnoomntv.html

[T41] Perl：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtfuwkryqm.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtlcmgeyaw.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtxflmbvcx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtoyhglzfv.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtxpwlwinm.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gtzwgdlebg.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtaidypqbi.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gthbjiucgp.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtaxzbsbvf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gtdfmxubcx.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtxbguhmzp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gttlmzkxkz.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsorjnjy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gteikselsr.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtbihemvno.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdztjkxuo.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gtwnerimpp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtvublwpnl.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmyorcio.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gtmhodcxkg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gtrnzszdll.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtbtsvgtoi.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtztlrbrzr.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gtyebpvfbz.html

val a = 1;  var b = 2
来源：http://dali.tianlin.xyz/Article/details/gtivcgungw.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtchaoxiam.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gttesapqzl.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gtkxzkkxsx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gtcaceylbm.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtgaqrqaza.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gtispurfdv.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtmymdorqa.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtrgvlqevo.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtopcpndhg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gtpsjrueyr.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gtwnuouyfb.html


<!-- 参考信息 -->