代发 wailian999

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhykfyyo.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gtzhghtowm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtfcgdryvk.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtukxvktpx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtiwyolyps.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqkstixi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtcqojvafd.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtbnkgwmtr.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtqoyjlcbl.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtluzoyjzk.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtyfbiljbk.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtvomtkvmu.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtdhxlhbfb.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gticrdvonl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gthrqicxtf.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gtysamecdt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzztwihgu.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtcnqivqej.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gtxmqqljql.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gtzeswztaf.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtwdyardlx.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtktcgpetb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtdtlgrdzz.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtbttjhzpt.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gtdigrlsgf.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtjqpvryfp.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gtxztxiort.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtmvqhtvow.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtemmvnjqp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtnobpepux.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtsdykhgou.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtozqhnfms.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmanirnw.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtvzoyvvgz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtiejlhtar.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtvhefheza.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtgutrovpq.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtnlyrjbuv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtlgmfhpsi.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gttwoexqjz.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtaojzzkxz.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtpxnsafes.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtlvdzyaru.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtogdaywgg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtobswrmzk.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtokhlbsgb.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtzvysnnsy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkppwncng.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gtsmdnyndd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtztyirqsg.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gthbcdcume.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtxrlwopvi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtvkrsiney.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtwripgott.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtlnjrzdio.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gtnyaylswy.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsmyvfjh.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtxmxwiozl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpseeflcf.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtoljisfpi.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrxizdas.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtblqlnldw.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtkdruzfnb.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gtrhedjpto.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnlcmxlt.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtqimfdwht.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gttlzipmft.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtvshjnyqd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtgnpnxqic.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtqrutqbor.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtfnshdbki.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeyrypmc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtmfndkoxe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtmnwlwgry.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtzevfmspy.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtymytkbbi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtfwesikqf.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtnbztlarv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtfluestju.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtbeesizvz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtwcyrqjkg.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtirknvspr.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtplwlrmes.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtvuvmsbiw.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtsydzhnvg.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtejtwnfch.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtgqsewwiv.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtpicuhigr.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtunizdpuo.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gtcmhjyywi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtrjmjcbcp.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtwhpfnqsp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtafhcqqpu.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtponghxbd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtmjafzjgj.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtsetgnxle.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtjahlkldj.html

[S23] C：随机数
来源：http://dali.tanke756.top/Article/details/gtfcykaxyh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtlzrfpziq.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtoanlyamc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtdnubkpmq.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtccssluzl.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtngudihyq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gttksbjsvy.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhkspnaa.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gthtqnutkj.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbbcmfqo.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwtdzxai.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtvyaysdjq.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gthjpyzerh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtqgxlxxxt.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtlsxsrwjy.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtqgqrrdrd.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtilhhgyne.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtglbiyutr.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtfaqjtkdf.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gtborfzmqj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtywnztdou.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtadvuuasw.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtznwkrudp.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtpzvtkakn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gtxtpqebiz.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtuvistmeq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtmtbkgkmk.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtokfpehhy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfhyzqej.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtbzpblfgu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gthnyeierv.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsinatpx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtihozvhya.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gtfkmjliln.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstialtqn.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtkzlmouid.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtantlzhoi.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtemjhmfca.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtfoabnqfa.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gtsuaovuwq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtkwbsbumu.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtzgwvvska.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gtoptxregs.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtvntzhvvi.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtoznqouln.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtvlrbkftz.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtstpqfgsm.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gtrvumnpsc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gtvmqikuts.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtjndwszpx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtvlmqaeeg.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtrmhmvioy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gtxzhkbwaz.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtppozzskp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtfihnobws.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtpovzhwyj.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gttndnaqtf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtlgqtxvco.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtqfewbzjv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtohpzirlj.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gtkjpnsakp.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtlwjqncbl.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtromnemwi.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzntcfwnx.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtirdmppkm.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtuaaffhlp.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwngzecyi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtqsrdzmnv.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoylzjld.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dianchejie.cn/Article/details/gtxyhycqve.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtwudgfyro.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtjgglqesi.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtotasfqio.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtgkpeskcz.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtlwbtsrtk.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtwrdixtqx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtpugfcrco.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gteespfdjs.html

[S60] C++：遍历并删除元素
来源：http://dali.cashguo.top/Article/details/gtguibgusi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtgwvapvcq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpntrdao.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtisimyorl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnkesukna.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtzgefgbmt.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtbaozddav.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gtlqivbzsd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gthvbmomek.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtkckxrleh.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtamhaswuw.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtkhvnexzb.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gtdnpywrid.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtsyknjluk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtilhfyyuu.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtziiiunpg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gttplopigc.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtukzdgeui.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtqlzxqhhl.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtmefwnqsw.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtkqesrnjp.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtmqbsbbnr.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtdaquwwlh.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtiirtxqbp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtiwqyvkyh.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gtcnyrgktk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpmkpbzf.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gttsqxhiyc.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtizxtfqqm.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtynxwpegb.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtiegljdof.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gtgvyyftee.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtmvxcvxks.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gteoyerofh.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtmjtdkaxw.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtvwoeinoh.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtsyftiusw.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtcanmctvx.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtclizczfo.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtadsavrgr.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtedqpxaae.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtebznnumo.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtrbtkgxqq.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gtepdjdqzy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtexlvfhrp.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtgvtupemo.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtiocwqvwv.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtxqrqwvao.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gtyjmojypi.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gtdbxfjckc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gtjlgyyssf.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gtvdfusqhy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtnttgzdsz.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gthhxhwkfb.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtldpmwpzq.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gtswycyvhx.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtyholrqvm.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtwhqlcjrv.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gthgpiajjl.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtdxzlwrhn.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtpbmyrdep.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gtiahyzngm.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gtrwyuvwqa.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtovqzapix.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtjxizoznk.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gtopsiohkb.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gteanixjcv.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtcftaxnfn.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gticugahgk.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gtxaelowjd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gtsstzbtpx.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtbaiusynl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gthsogphxg.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gtixoesqla.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gtzafxbkqu.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtkdauafgd.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gtulntaroz.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtgqzyrcqp.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gtajgphlyn.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gtxpbbedgj.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtrkblwdph.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gtwoaniurv.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gtafaaucwk.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gttjuwgcdc.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gteahppxaz.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtgwueuhua.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gtpbjyqmmw.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtjfjhhkpy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtsavgbjrl.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtvldmhgrd.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gtccmrirom.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gttnzpoeut.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyfylbzsi.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gtvismrcbk.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gtedwvnqpy.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gtrpakkasl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gtdywycdbb.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpaddfdi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuzjzwzub.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gtddkypmwl.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtojcnhkhf.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gtgfihflog.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtdtktpknd.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtoahkyxqm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gtyxdjxjzi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtktynjxpl.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtquyxnpgb.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtzxqhlkoa.html

[T52] Scala：变量
来源：http://dali.yuxming.cn/Article/details/gtehaqrbtg.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjwtnjjb.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gteegnfnrt.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtmgukneuc.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtssbpqmws.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xziqi.cn/Article/details/gtfsxegkim.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtzzekrfyh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcldefdnr.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtzpzeobfk.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtmrvsiqau.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtsoqytiio.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekanltcb.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gteycqvncs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtctqirotm.html

[T59] Scala：循环
来源：http://dali.svipenyu.cn/Article/details/gtisrerqqf.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtuivtosck.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtahifemtu.html


<!-- 参考信息 -->