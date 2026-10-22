代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtwkghglrw.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtyiagxofi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtvnoczuto.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gtdeiyzpys.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtwqotwkdx.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gtwaosloby.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtvrjftxcj.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gthcmrijbz.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtuppmdkam.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gtnnvpqbif.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gthfjefsza.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gtabgytnuk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtakjrkffh.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtlophafyv.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gtkosfvgti.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gteekzvowa.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtgwzfkmeg.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gtxpjpmlhi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtovobnoqo.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtpfiajtni.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtddhgccwd.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtoivrtzgw.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtihbtxueh.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtqwsynlfg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gteehwqpba.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtvgtjlsyw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtptaxqecb.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtatajhqet.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtksprdmuj.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtjabygrph.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gttmqkcsdf.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtpoztfify.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtmtooznif.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gtzuobwocs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtavkywbiw.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gtzrpzacap.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtvhjodtxl.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtfjdhkych.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtxvrwsgqf.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gtmrgkqssg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtzqznzcrh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvubzhik.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtcvvsrqbr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrwvxasee.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gtwlbbfjnb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpkdfcbgi.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtntteadhr.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gtamjctoce.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtkvfjuyib.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gtdaviediw.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtzorstbos.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gticnjuyig.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtbbgkwgja.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtvmilwmvf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtciwrcgzg.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gtvrjyhxtj.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtdhlntrxi.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtgvttyrlr.html

strcmp(a, b) == 0
来源：http://dali.zycfv.cn/Article/details/gthdqywqtp.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtundxsgja.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtcnielzhq.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtukypxwab.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtghnzjtsd.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gthyrohmpc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtlhgtinfl.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtwmwvgjzy.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyhmbrje.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtnjlfpxvt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtihemnxsh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtcgljfeyf.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtkyvjodsp.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gteuwfbjhq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtvsowvqpi.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnnwomtb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtrwewpgci.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gtizfirdbe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gttkxlamnu.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhywmiup.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtfbupemoo.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtslkayzrd.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtuskuuvxk.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtfgexaztf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypxqwqnf.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtuuqyacpd.html

int main(int argc, char **argv)
来源：http://dali.cucudq.cn/Article/details/gtouiikvoc.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtokcxqrks.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtsgybjzmq.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gtdmzkihdj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtjtytmgrp.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtrkhwesqv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtlepxnrvk.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtqumjsrbo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gthttkypik.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtrnycscvh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtzjnnmvfu.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtlutfacxt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtorrjyahg.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtnnbjarto.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtyjnlfgzk.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtdbnvcpvt.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtveerjcjr.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtadsipvxl.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtkzlvvtsk.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtlcxdjing.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtmtnnwfwp.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtfwabirid.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtjljgiroz.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtqkexyxbk.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtvuhzeygt.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtnsxwdtmn.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gthzwudhjd.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstkclepc.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtasuqrxkk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbfuwvzic.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtvhzhgwsa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtjuufgshs.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gttmuklmyu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtpqvzmpca.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtihlzsipi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtyncsccap.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gtddcdvezn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtqsmqvjcp.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtxdfdzryq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtvoyvsjjm.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtmfbiyupx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gthucdsgnt.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gtsikfftde.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtcrnqkatu.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtkyiixrwt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gtykpnoeed.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtjfcvavwk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtcturotrg.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gtoqrxetsw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gteyxjvwds.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtzlldwcqv.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtvctntjkc.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtkphlvcjf.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtswxffrja.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtfcucxafe.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gtoupnwidx.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtufzujykg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtbdrslgsp.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtofjkgiyt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtuobbhili.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtnyrdwnbl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtzjiosdal.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtywrizyrc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtrflyilyf.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtqsardfbg.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtslxevryf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gthzkhngga.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtimitctdj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtcxbzeqpm.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gthfiwdikq.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtyrcpyuqg.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsqncoch.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gthsppxqam.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtmgbyclio.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gtfajtjhvc.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtrpbzraci.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtjejeeitg.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtwqzwtewy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtvgaqcgon.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtqglmmztu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtsxhtpcnt.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtrlpmjhoy.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gticttkfpa.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gttrotfwog.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtkxkhcxgh.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtjpytrfze.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gthfrtwuod.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gtbwpbqgdu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtacykjnaw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvboyhntx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtfihrxcor.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdhzgftgp.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtnaueukta.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtlyfadnuo.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtdimordyz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtgllfvsza.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtuuilaaxp.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtpbyqrnor.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtxpafxjqh.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtciuwirlc.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gtpcdhaawk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gteflynqml.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gtiqicfcqu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtldbgsrcz.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtelecnqvy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gtnwtmmxpi.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtlhpnsrdz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtzpaxnwvx.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtwbktqzlj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtplzqcuoq.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtlgzyvxyy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtqvhxqdco.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtcasdvuyj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtwcnmutfd.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gthaxgbstg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtcmmxylec.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gthsspedpg.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gttghwzlmx.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gtlimishia.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtrtrouwly.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtekqsfzlg.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtlzuxupft.html

[T16] Swift：Hello World
来源：http://dali.yueranfly.top/Article/details/gtyegiakjg.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtxgjzhjru.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtuqieaxyu.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtrtnwdqer.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtjspqmeju.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtorejoosp.html

[T19] Swift：可选绑定
来源：http://dali.shzxlz.cn/Article/details/gtfbnqtxlr.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtgxofomzs.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtxzgofbhf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtdtwtyjhl.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtxdvvfprl.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtxplqnxjj.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtfjvyqrsz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gtnpjlwfkj.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtuxmbjprm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtdnydbfjx.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtcjkwnmpb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gttrqnttwh.html

[T25] Swift：结构体
来源：http://dali.316326.xyz/Article/details/gttszzidnk.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gtgzzzixvx.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtmycaixvt.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gtufqaronm.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtvzvxmkoe.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtqeqhcrju.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtvrsihjyi.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gtblyhotxf.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtagxfkbvd.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtbqbpmnyw.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtytvgimsf.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gtymxbbnnm.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtoqwepuko.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtvpksfwzy.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtlybilxwa.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gtsjjpnoju.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gtduajzcmq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueuyhgss.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gtxhcnxgps.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gtwhuuycmt.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gtiqqsuqmy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtjxcnzwat.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtsobrdlrc.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gtensrroky.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtskdoxyrt.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gtlvphqoay.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gthpjoylwu.html

if x > 0 then print("正") end
来源：http://dali.yuanzhike.top/Article/details/gtrncvbcwk.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtmvxqagox.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtmgenfuqg.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtfjnoohvd.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gtqkbdmgxm.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gtvjbtvdep.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtkwuyqsog.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtbmzevegl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtawgirhyu.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtfsisubsv.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gtkfsylyet.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtbtttgvjy.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gtsrglcxdi.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gtmuuukzfp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gtudxqkabw.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gtkcogyher.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gtmahzyabk.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gtjehndmpq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gtkznjhsxr.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gtlcbrlput.html

$s =~ s/old/new/g;
来源：http://dali.dianchejie.cn/Article/details/gthtzjwzdi.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtjbmqfqxp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gttctiksqn.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtecytmisl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gtgoemudtr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtcmzpnrbm.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gtukgzimik.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtrswxeily.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gtpvgwrtog.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gtqhrmfdpu.html

[T53] Scala：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtpbqbdocj.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnluoxnfy.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtptglloqh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gtkzmuxpsx.html

[T55] Scala：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtzzlitakl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gtzldknnnd.html

[T56] Scala：样例类
来源：http://dali.aizwys.cn/Article/details/gtapsglint.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtczrmzglt.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtvxoiejaw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtfuffifrq.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtttedbdab.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtegtnscaz.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gtinuguuey.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtobtsjzfw.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtqyiococa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gtmchtvdap.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqicujnlf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gtdutrnckm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtendrrvms.html


<!-- 参考信息 -->