代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtvucsphsz.html

[R56] 远程拷贝
来源：http://dali.nwbrower.top/Article/details/gtujjnmtvv.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvzneroy.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtygviwwes.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtmuasbgms.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gthozzumcs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtrmeoddgj.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtxdtrotdb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gtvzlnugsl.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtvjwtcbun.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtdvulzjsw.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtqilsvrrt.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfrmkyhk.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gtqlxbsvnz.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtcskhhrdw.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gteeqdomad.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gtouendetu.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gtwjymehtb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtvymmswjf.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gtttahaoca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtukefrgsw.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtdehwmnkh.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gtripqscxa.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtqbfvqydh.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtlbmlfdcq.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtbvncpiat.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtwzsazreg.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtakmixtnh.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gttnyovbpx.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gthpxmqnft.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtdaoeuwdx.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtvnyralea.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpiqeuiw.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gtgscxeplt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtmdkxxlqr.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtvidhkuox.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gtdwcwnvkx.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtkmznkqit.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtielfrsga.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtahtewute.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtlwoofgye.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtyntjxpag.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtzmutidqy.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtgtsdynzj.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtmiggthza.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtgsctpolt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtyptbmsvd.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtnnselvsf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtzutzsnvg.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gtjtdqexhi.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gtxpwamqss.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtakqueloy.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtkpjfcomm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezltvxza.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtlrryhgtq.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtldsgoknk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtgentmelk.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtossexrlc.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtvvqlfanr.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gttwyplcjx.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtryhcuffj.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gtuwuqzgmt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtlrormyaa.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtgenlhwql.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtcabfvsgo.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtdiahdgws.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtmqzbxomq.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtjogzqpqa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtgiedkljw.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtjcilpyky.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gtituldarr.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtdflzbeci.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtbmgghbre.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnadilen.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtixffocii.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjdzxbfa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gttuwmsmfk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gttasjrtql.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtceblvfud.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtvsyakztp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtyomkmmbc.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtvpviiayq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtyyvaolog.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtdnvygmwn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtikzharbd.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtfaaotlkz.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtivvjgepz.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtpkbcnbaq.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtqoqzurpc.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyxkpibg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtnipokqfd.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtsyyfakwa.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gtlvxicpwa.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtnmnjzdgw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtbchdwpvl.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtsrddoggn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gttomjeksx.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gtvrcsgdms.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gthfiokocv.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtzxkgplel.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtrrevqqxy.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtfzeksjdg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtpuplxegu.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtdsctupwp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtwduhmfut.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gtrjuxnraq.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gtsomcvryy.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gthojvyfqq.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtyufrunwq.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtlizozeye.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtslksvilw.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtgqpyfoyh.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtrqynxjyd.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gtguemyblc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtajpovovu.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtlhpyuqfr.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gttjjzgezv.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtcyospzvn.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsakefzwu.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtrgcvqjgt.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gthwtwniah.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtkenuapxy.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gtsuuqvcuw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifsyfijo.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gteicmyorj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gthgztccmg.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtbtalcces.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtgrsputat.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtslnwdytg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtmblhuilm.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtbhrkfjbl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtnfzmcjir.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtszzdgwur.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtabcofdgh.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtffljeeig.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtqhwrhhyo.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtmooufqhf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtmjiiddqa.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtksxukhds.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sufxvd.cn/Article/details/gtmvzkijdz.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtmlmphnxh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gtjqvfbonm.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtmrbkmmib.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtvugbpwzg.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gtwxdxgwte.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtdrikyomo.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdhohhfa.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtawhhyztx.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtedzuinxs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtocnyrvbb.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gthsyochww.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtsckwtbxw.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtbjyqxciu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtveehxcxh.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkphvyix.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtscsfwucp.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtkbssqszu.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtmceykgip.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtsmjyebzt.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtdwtuetpy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtpkcpwhrp.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtplfwvrlc.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtpobnmgki.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gtutpadtxj.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gtliqicdem.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gthmovtpwn.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtylsdyztf.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtbnnywpll.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gtnbjfponp.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtjjujoeww.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtwmflwppa.html

[S56] C++：optional
来源：http://dali.shzxlz.cn/Article/details/gtxcclzfvz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtvjlmyrsz.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtdwvhuylf.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtrdmfaaee.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtnlyyebec.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gtmgfwtzjx.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtjvmkpzrg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtajldnanw.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gtdmtopysh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtqlztohkq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpdhdgohj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtmrhwthhg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcuounoaw.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtohsagdcx.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtdaowedur.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtbkfucvsx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtwippyzqg.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtjmevephg.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtoepfouwc.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gtlcrvbqla.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtusgdarkr.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gttrikcbuk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gtrregubqf.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtcgplobzs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtgygubrqh.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gtfxfpfywt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gtqgehcbgc.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtdasapsgz.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjpjalsu.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gtodxndwpq.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtprylqijc.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gtvolufvpv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gtutzeaarb.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtyjdehd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtvukwtiig.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtrxsjchua.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtqvtgudnq.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtcpxadvxk.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gtmtfsikki.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtocsogteu.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtfprvlqyf.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtbtanhnmx.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtztkouvcq.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtdlefjelg.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtzlaobuuq.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtoqqeprwi.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtmwhsdntb.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtdvfooufv.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtjcuzkqgl.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsymhdsf.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtuzpzenjq.html

[T20] Swift：数组操作
来源：http://dali.wangdashe.top/Article/details/gtlkbjckfr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gtxffbqsnr.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtsftdxgru.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbwbtyqs.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtrbuzogjc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gtgoiifvos.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gtskpkqbki.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gthszefhkz.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtvcxrhgho.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtkwrwgkol.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gtjtqbewfu.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gtopumcwyh.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtsguyijla.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gttvydjweo.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gttouaqdvq.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gtcctliyme.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtkhskeiqn.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtqksqdrjc.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtzoenoywo.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtxnqwvubs.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gtymhuyppp.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gthjmzzusg.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtlwgcbjil.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtvnmantqn.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtzedpiyhf.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gtdizwsckg.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gtiurybhah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gtzfgclgec.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gttjmkdgul.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtktarjdby.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtlfsaqzmr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtjvprqftq.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwklltkwn.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtyoagbayh.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtongqibge.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtaszkuvyd.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtuwjiawvp.html

if x > 0 then print("正") end
来源：http://dali.nwbrower.top/Article/details/gtumolmggt.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtjwbwgeqk.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gthxmdzavt.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gtjrvffpsk.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gtppxcwlcb.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gtbrloleei.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gtevoxncjp.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtxiprxvmy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gtqvvcogia.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtltpjdutt.html

"值: $a"
来源：http://dali.xziqi.cn/Article/details/gtfoywfrmf.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gttnddtvbw.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gtxnrbxapk.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcivafvfx.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gtcjkekhnk.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtwtsasrte.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtbnyellej.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtppktibta.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.svipenyu.cn/Article/details/gtmfdtjenz.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtecmbotql.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gticrscbri.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gttcjmjiwp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtfxtovvnq.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtxmtkljmo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtnzltnnri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtasjryqtn.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtvjjukoun.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtxaqqgpxd.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gttzmkmkkz.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gttxmanrtb.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtocfcrvmv.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvvwsizs.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gttilesfuk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtimtecngy.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtgkxqdgcn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtqvsqahvu.html

[T56] Scala：样例类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxfbppxd.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtiyzwzzdt.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gtfaqgosun.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gtrakmurmu.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gtcsobbsqt.html


<!-- 参考信息 -->