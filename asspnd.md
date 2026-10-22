代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gt2febjketc.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2qqcmlayi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gt2ubyeitrh.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gt2wcyqizqg.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2flhiuumj.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2oltcjzjz.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gt2eexksqui.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gt2pltnksqr.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2pubgnqvs.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gt2iagjthpy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2itkwxtba.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2fzfqmmyv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gt2xqpdilhf.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gt2webmautp.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nokvwzca.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gt2uuwbtrnd.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gt2kdxclhus.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gt2bdoehmdl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gt2zyzkhjku.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gt2wthgsjxv.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrwweowt.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gt2gbtfrstg.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gt2exfudvzx.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2ageiemvt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gt2khzupsxe.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gt2gygzbvah.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gt2swtfrdcd.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gt2akycqrvv.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbotfioz.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gt2gjbhiknw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2pucnrnhu.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2wonvitsq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2uhdypkel.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2eezgyerz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gt2mhlnpbhp.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2hwlbwfmf.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gt2uzdgrtyf.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycknpilu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gt2hxicnyty.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2zqdqpext.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gt2vrviuiuo.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2scqggjml.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gt2yeugodds.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2kvjuujgc.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gt2uvpnzwxv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2dffomxvx.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gt2ayddijef.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gt2zpxshwng.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gt2oiqzcpbv.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gt2zxdvhjer.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gt2vkpvyvzp.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gt2hbqfjrtx.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gt2lqdwiszg.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2olbmsczv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kirqhkrb.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gt2tuqtwzfx.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqzbavny.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2ztdzapmq.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gt2pkidbhuk.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gt2snxglxcj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gt2yxynvagi.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2xdrujqmn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gt2rsmxrdbp.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gt2oenimjun.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gt2ndrzymir.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gt2bxlpptyf.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gt2tcyleuhw.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2ipjeitup.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkqkjnyj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gt2kerwpbds.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2btotqdoy.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gt2nualzuvz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2istugdpz.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gt2ckamizbk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2mddlgmee.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2rcmpuoxe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gt2srewfyfa.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2vpvtlloe.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gt2bailnxrf.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gt2cwitffxc.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gt2rpsfdtfa.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzhiassq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gt2fmnknlzq.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfhbytvf.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gt2gcsocogk.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gt2ykaiqvdt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2qyxyuymo.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gt2aelenhgd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2qwezqkhl.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqffspna.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gt2xepqzxkg.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gt2asxqhqgk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2pclidozv.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gt2ztdxzyoc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gt2aucnlmig.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2frmcdyxt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blbkoymz.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gt2lituakrw.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2nwprkjoj.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gt2pjetsync.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gt2tbgenjtm.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gt2oehvnaew.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2irdyvzxg.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gt2hlcunkgk.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gt2iicdsgho.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gt2ozjqohtv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gt2pdjiyxer.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gt2dqlmmusb.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2otwuaydg.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2exvvgqsd.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnnrxlgg.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2ofzvarjt.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2vsabarql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rszcbcsb.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2nfpwtfjt.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gt2jdmhfzva.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2erqfgdhz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gt2wazgejgg.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlnipdav.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gt2ilmpdlxf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2miqilmht.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2xmywgpmr.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vizaklmg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2aoawvxfh.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gt2pcadeost.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2ohvrdjpc.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gt2ojwnngdd.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gt2tipiajol.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gt2xtyruhms.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gt2xszrlkwu.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2homkijtt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gt2fofylsyr.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2mjgcxgwq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gt2vzkrilmk.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gt2nrfqjmvk.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fblqtofp.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gt2ofgdkrvt.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gt2ptcjpnlr.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gt2sfciuxwk.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gt2aunhlqlf.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gt2rwrvzeic.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gt2zhlazsix.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gt2rbpxrozv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gt2gtgmlqdm.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zofkdcmw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gt2jsydhpkk.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2hbxntzup.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gt2lovjflel.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gt2lkjcfhhw.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gt2kpjahkif.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gt2ltvbbgcw.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gt2ttildlfm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2svnckmwm.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gt2ebjsvkow.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gt2zfkkbdnq.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gt2akujdjgi.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gt2zsoxxvjy.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gt2srgghjni.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gt2vrrrefoy.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gt2ootoriey.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2mfomdhac.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2nchqqmgs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gt2vxwxtbeb.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gt2yhzikiuh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gt2wxhmmyae.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gt2cgorvifd.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2fdbxzpkq.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gt2agacsotm.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gt2gszsaygt.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gt2ddbvwstq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlotntv.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gt2uzvrpowu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2rrkxeywi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zoeguztg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2zsifetho.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2cmvpmnfr.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gt2cbmiifld.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2qksmpjev.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gt2hyfvowhg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gt2ugbxwieq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gt2elontmzz.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzuppxph.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gt2hqlldbzf.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2ycvmjxau.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gt2etrqxhjx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2zzluebll.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gt2juyyakke.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkjndmn.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfgehyht.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gt2euijvsqa.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2stkdaugl.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gt2xtmsyncp.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gt2vdozvock.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gt2edkibfiz.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2ifgknyyg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gt2qxjwntfq.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gt2rfljmqjt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gt2jlsdpaag.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gt2ypgbosje.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2xosqfvtk.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2vrykjrgy.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gt2fjjfumtq.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gt2wtvmrzhi.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gt2ukgpsjip.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwolgemw.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gt2uzlxobyd.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2nqhwucym.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcgyhidn.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gt2nbtxpxat.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gt2dkehradm.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2isegonqw.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gt2mkhmttoy.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gt2zjdlmfql.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gt2bbxehahl.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gt2mzukumni.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gt2qytaqkhd.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2sxjsorsf.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhlobmna.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2egtzsnoc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2ebwgbqza.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2cytwqinf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gt2vvqsgnkq.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2cabhwrxv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2ujqxuwzx.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gt2rddbzhkw.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gt2vlyfvdqp.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gt2thsvewju.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tydsuqey.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxpazou.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjsfolmd.html

[T28] Swift：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2yqoqymas.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gt2psrchtvf.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2xisizsqy.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gt2ytnknykt.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gt2vqiuhgsq.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gt2snwvzbfh.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gt2lbykqqiv.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqwcirih.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gt2epftptna.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gt2dstiiaxp.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gt2lmvofhsv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gt2tlltqiaq.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gt2imswzwcx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gt2xyahciwh.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gt2vgtnyolz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gt2bbehphtk.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gt2fuciiqzj.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gt2kfhxpeeq.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2dvxmywmg.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gt2cxjuvhrp.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gt2bkqmhtrl.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gt2aftatvze.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gt2rwtnbunc.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gt2yvctcobd.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gt2btqckcqg.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gt2veasyarn.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2nkhkcmoh.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gt2szgycdym.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkckapuo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gt2wqjkjalb.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ciwqxfsx.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gt2povncnqz.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gt2hioaeebe.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hktngauc.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gt2aifrrvff.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gt2oebbxphx.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gt2kswjpuhg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2vehiqspp.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gt2gthgmdeq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gt2dnjhyhmz.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gt2mlvtepus.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2pbquwskl.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2hhzecchd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2dtrxxceg.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2viqjcqfr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gt2lhwubhkd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gt2fodgycjm.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2caidtrqp.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2csguemft.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gt2wsexsdhr.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gt2czhiemyv.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2qyooznls.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2zeaajshh.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gt2awuockeh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucnqxwkz.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2bjpuwzpn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gt2qywhyfgj.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gt2vqseawjy.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2zouemhfg.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2mqehehzj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2govtitai.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knslajsh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gt2gacmqmcg.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuuejknb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2fptdiisr.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gt2ltgviytr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gt2buzbmxmf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2htzabomq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uaizkhpb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2mbtvbsbb.html


<!-- 参考信息 -->