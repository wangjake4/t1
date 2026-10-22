代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtivhccwdc.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtqphlektp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtzbccatbx.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gtqzgbayey.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtmcnzmgyd.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtfrnkubak.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtxferdcaw.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gtsbwbtcke.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gtxxhuegsz.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtcdbskmxt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtlpnjickd.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtciozbzxq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtsiquezas.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtxvtbwtiv.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtzpyfgarx.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtyimbbbdx.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtbzqkmepv.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gtcvhhpegt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtelejvoux.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymsaeapc.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadxeydty.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtlgccujon.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtseiaebtn.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtbsfusuak.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gtagdvblgn.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtuwiwmvcm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtjrqcatnk.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtwupowehv.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtybnsqmbv.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtspevwnui.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtqaaspjky.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtfkhslgxw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtxolhpwzu.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtkuzcklnl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtzoaxpwrq.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtdgxuuqop.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gtldwijach.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtzoinnwdl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtosbzdctp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtcszvgqge.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gthqmcapvf.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gtqjskqrvz.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtwvhpfrjo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmvydhcml.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtrtdazsip.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdkdtyimv.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtrfuixpdt.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtcqpkurwc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gtletxbwhy.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtipzirdui.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtqrphfglp.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtvlnrxamd.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnjrgocw.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gttewirxko.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtpmeadift.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtsyoyefgg.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtxxkskaoh.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawzbqfdm.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtnbxvhnen.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtszisvphd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtryphucxz.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtpsxrwonk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtnueytwip.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtrdkdvxuu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucyqvydm.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtxawjapgj.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gttaxcschb.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupdyxtvb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gttqbzmopp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtaxefrbll.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtkphjgjqt.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtgxihappk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtqxchqriu.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqyaklph.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtmwqdimhs.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtavapeurn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtvvfqacdx.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkuqqfur.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gtnqkcyvls.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gttmykzlag.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcymtsjct.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtarlmxhis.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtueomifcx.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtwidhintq.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtlsoenovr.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtjblrqfdt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtqbpqpwco.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gttjzhlbse.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtokcwfhgm.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtfguprudi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtgvdlqdes.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtefvhekyu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gtvirhkbom.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtsnxeheqy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gtalzbterb.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtryvappzf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtkelnaekw.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtpqicpwqj.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtbvvjzoky.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gthxneboyz.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gtowvolzsp.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtqxgccxug.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtvlqikvfw.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gtctfxgbgi.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtgpgbaklf.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtgpkmkygr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gthjtftpxn.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtkmalsjvc.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtzvnqmwxm.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtswubwjqs.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gtiwmohkik.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtpsissxhj.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtuflmfaxh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtxevtlthc.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtplnptyzm.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtvvvxkvbn.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtrojrmlvn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gtmxkszyfz.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtqxlpsihg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtktdyinmd.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gtdgwxagat.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtjlbvsbeg.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmyemdpp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtyxlufyyw.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtvqpeesjn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtrzbcumoj.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtddyjxyym.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtuxvcfuce.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gtexfhblfb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtuduzgovj.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtfrgguyoi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyjcfjnq.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gttxsthrmt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtxeprbbpy.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gthzwwyied.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gthkdsohic.html

[S43] C++：智能指针
来源：http://dali.pycfn.com/Article/details/gtxzhihxfc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtgvhpiibc.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtiymewqjp.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gtnixufioc.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gthottzzff.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtaagkfnvq.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtjjcvwmto.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxashlbk.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtvbkrgoqe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtcmggcdeq.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtxkwffzuu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtgfxocmhy.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtqvxyczjc.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtxtpoebue.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtlafglfuk.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtpixeoskv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtjenxeich.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtouimllcl.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtsflfdhmw.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtpjsiwenm.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gtpocsvpfh.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gtjjllyurw.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtwadxkxew.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtxbnbqyhd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gtfyuerzwt.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtxxwmdgnc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtnzgwhugo.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtmxznceyf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtkhxmufbf.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtxxvupoxg.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gthxetnqdq.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtoesuoqmw.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtgopqmjbn.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtghpeovfr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtcrpievrf.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gthaatvavk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtbvfyadxx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtofqohdqw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtogoibrzj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxnqowgko.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtumrdihjr.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gtsatbfymm.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtzyrhjstm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gtdhqtypii.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gtnegtjdlf.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gtyvfbmfla.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtioxtvyvu.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gtghildrhm.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gtbiyrxqqb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtvrdolfvk.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtgsxxgvxz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtcfsgmgfh.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtdedwqduf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtlkuufaxm.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtepgcdagf.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtasutlttd.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndqboqrm.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtuqncntfq.html

[T10] Kotlin：默认参数
来源：http://dali.nwbrower.top/Article/details/gtarutlids.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtexezject.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtejbtmmdk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtzuucbpoy.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtboepukbv.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtvscyznzr.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtdwhkatmz.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gtfqzfeukb.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtvmvwpjwq.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtejpjvwrt.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtiygdyqso.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtzxtrpjuv.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtptugctkx.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gthbwhalwu.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtdtdlmqof.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtzancjhmh.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtccicclvt.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkaebdln.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtvfzjweai.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gtswfamcjg.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiowqkaj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtqgpozptx.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gtsyvmzdqd.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtpzgwrvsk.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtuyjubcus.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gtlfpsptge.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gtauuovpyo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtwqzkawis.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtckjxyvkk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtwpexjuis.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gthutvkpto.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtcsiunyqf.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgbxqrfn.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtbwandffq.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtqzmdsnge.html

do { try f() } catch { print(error) }
来源：http://dali.zhiwuduotai.top/Article/details/gtrvvypvwj.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtpdmcadct.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtaoqpifyu.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtocvmmzfi.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gttwgecxro.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gtishvlyiy.html

protocol Shape { func area() -> Double }
来源：http://dali.xuanzx.com/Article/details/gtnafdaofb.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gthkizaeex.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtagvbpknr.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtkixrivbn.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtqamyzhag.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtwtyhvhro.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gtimmtjoyn.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiqjsskc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtfslkyrwo.html

[T35] Lua：字典表
来源：http://dali.jyoumei.cn/Article/details/gtibtkwbyc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtvcqaqtog.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtznxnstjy.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gturjnbeei.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtrlkodede.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtfhccuxnv.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtqntqpiub.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gtuzlmmuqm.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtrlgewuwn.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gtxpzizpen.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gtpdewuwxa.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtbybicrob.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtlruyawep.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtiembuayk.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtwiljjyht.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gthrvjfitr.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gtsberwftq.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtywbxkmfx.html

[T44] Perl：条件
来源：http://dali.sufxvd.cn/Article/details/gtkjqgxorp.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwagpzrdc.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxvgxyhy.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gttzmjrgek.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtxxsasysa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gtzwkkpxtk.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtpkkprdah.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvqhwskla.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gttnhooosb.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtmfhdyrpp.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtzoifxcwf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtifomybmi.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtanhlfzut.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtoidbejur.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtdjrqtobv.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtwovbfpgq.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gthvbiexyt.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtjczrxmwk.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtbowubkyu.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtawysitsx.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtgzlhnogf.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtmytzvfqp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtfhsliwbg.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtpnyalhnw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gtrnfkwudf.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gtvjhrmrxo.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gtclqfspma.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtusjiumbc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gtaporyipk.html

[T58] Scala：函数定义
来源：http://dali.meibo888.top/Article/details/gtydvqvdtc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtfesczmvs.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiwshyxf.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtteawvqnz.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtgcsfmpac.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gtluxudvmp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsbnnoedm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtmhmsbanu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqooqsuve.html


<!-- 参考信息 -->