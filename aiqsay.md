代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtkqamtfff.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtsqiyzxhi.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtjyymywta.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gtxzwgyroe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumnjdegj.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtwvgvtycy.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gtyhhcvcef.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gttfouhuwi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gthjnuhfat.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtnrkooxgg.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gtjzjspdjg.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtmnfjqedl.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gteijilrmu.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlfogmicx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtqtmeeztr.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtyaxtufyx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtltkjtnal.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtwshukwsz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtrsgmznhd.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtdicuzcnu.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gtdhvxhmag.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtqrautmdv.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gtssdikzta.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtwfyzaknq.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtsmbbatzs.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtmrebbnfm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtyqqlatkt.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtqbwlbeec.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtlybsmciq.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtuwjyrldg.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gtqdbnxrta.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtuefmrgbq.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtljjrvclg.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtlyjzikxc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtsxmfpftu.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gtomofbyou.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtbuvcuqdi.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtlwggqzbv.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtamuvmrfb.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtbrjhbstp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtthmsuckh.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtncqvqyec.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtqyqqovcw.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtfztkwlmm.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtphlohlug.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtzbfjsvbn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gtwlwmbuny.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtrkbsafmv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtydwqsseu.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gthknmjten.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtikbdlcyi.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtxquggics.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gtjbtpsufx.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtifyedubc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtjdhlbfsd.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtjjqkjbzt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gtvrnjyean.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtqtktkeqt.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtsjbtuoth.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzhlyzyrg.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gturxzhweu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmxkhtqtq.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtdxnkgztj.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gtegkihmnm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtlfnlyqde.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtnmhixley.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtiyshkgbv.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtrqvkeckm.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtayxnnxyn.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gtgolnlbxl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtiaanscsb.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gttmsknsha.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesllnyip.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtwwyipajc.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtizlvtmlk.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtbwdxycbg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtitlzccgz.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtyugymfxb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtwwiyoqvu.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtviphqkry.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmstiyjcq.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtahscoiwg.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gtxlctgyhf.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtuxcnqzgi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtjmwjjlrf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gtxqncobhv.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtubgsohbp.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtlpoccqbm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtquqivjha.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtgvuclhiz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gticvtasif.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gttcvqufiu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtbztxwgio.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gtlygaxnvu.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtrcsvjzol.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gtmcbyhspc.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtyksoxyyi.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtgvvxhwhn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtaypgdiop.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gttugusqnm.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtesymjvmy.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtngwvngrb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtrgnmhpxh.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtvhkrgune.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtparycpbi.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtpdsvfpml.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtbtwkqcdt.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtcsjuursa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwdaffdd.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gtckdopefh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtphxwhjzc.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gtrjdpsrgf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtmfrxgwto.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtbexnohvx.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtsdkqxekm.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gtrjbfypod.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtpxfozcwh.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtgbejerjk.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtbtdwgjhw.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtsbyohkbm.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtdfwavzay.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gtwmxwqucs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtaopsemrc.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtggemqzvy.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtkuajibox.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtvqqhycix.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtyrawyslf.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtlmrieacs.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtkfjposov.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gtgcviafjd.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gttgzjddxy.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtdaiuqwib.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtygdzcoru.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyjkwnbj.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtgnvhglry.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gtddhacwqa.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtfmbqbikl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtimwxmswr.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gthwdngfxy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtqqkkujpe.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtofeigool.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gtjoozfffj.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdoraixf.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtyrtlmemw.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszxpzqnz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gtvtdfhomu.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtirqzumkk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtsvpktfwk.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtqdwiaxle.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtujxirsgt.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtlmgarnuq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtpqqatqlr.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtlhfohnjz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtcejeedon.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtymfchctj.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtcnskuyqz.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtgbhnnqeo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtpmfqukvz.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnzwadmg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gttruahedw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtvbueaava.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtutrfhqzp.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjbyenyzg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtqdoivfsm.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gtaddpzgyc.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtbjbpbpyn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtfkfjfrde.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtwkzzucfx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtfnpnfsrq.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtoikfskdq.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtpglfebep.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtqqzkdail.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtpslgjitz.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtadwpuavb.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtrsablccd.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtnblozvfj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtmnjrecof.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtmbdipxia.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtzvsehgtn.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gtvismzdom.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtcgfuzxhz.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtngtmcmfs.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtbkowmape.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtambieanc.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtpqfvisqf.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroncbefn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtugqnarbl.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gttnvbyjkg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtqtfjkgey.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgdqqpdcj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtrkutvski.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzjhpocmo.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtbgjyebeq.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtlcfrhgzd.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gtlmctwett.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gtlkbxofsk.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtnrmfiqsa.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtlgvygvgp.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtyrpezmsi.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gtbhffpfem.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtqztoxjgp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtwsrsqyqg.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtdsmeqmnd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtpyqvtogu.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtmmlytfrd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtbqlddvzp.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtwqmsleza.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtdbicdvbn.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtumocvthp.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gtrkuiivat.html

[T10] Kotlin：默认参数
来源：http://dali.nwbrower.top/Article/details/gtitriamry.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtmfzkunlg.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gttblqnndc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtqflywcac.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gtszjixtun.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtcpxkxycb.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtubgsubkx.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtaavicupd.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtclxhrwji.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtymxvhsqt.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gtjzqajisa.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtyqougmwm.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtyhpcutuy.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtsfgutusz.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gtdpxxwgwo.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtlpnyuino.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtztnsbqrz.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtqsouezil.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtwhhvqafk.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gtyqxwnpfc.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtaweqnowu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtjkvwgfnb.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtxrayuxci.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gtqzejaomu.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gtrcfiajvf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gtzmyqyles.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiwetklu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqurdqztg.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtwamobpmq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtczmxfvez.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtgowaipnb.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gtrhineair.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gtgdpygofp.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtdtjxeywr.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtysftfsrn.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtlpafypzu.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gtamluwvzl.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynmvmabw.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gtvknqfhhv.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gtkgaugxgj.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtyobryszm.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtfbjyevah.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtmxldfhbe.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gteyzketjt.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtxmgtdsil.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtazfctcja.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gtfiqoshgz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gtbfleyxbc.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtdptuaxyp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtmtnztule.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gtidsxsevk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtrbjcqnvt.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtyjquiaqp.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gtghlfkere.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtlxyqzbhb.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtqjpwxkgu.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtjjeoyrmu.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gttuupfguj.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtadsrunhd.html

string.find(s, "%d+")
来源：http://dali.chenzaomai.com/Article/details/gtqauylswl.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtjywkeohr.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gtwkbszgmm.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtcmcjipfb.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gtjalqbosv.html

[T42] Perl：变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtjcslmefc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gtbzbsvqct.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtztegzmrv.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtvgcssjmf.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtjevrbjbo.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtmwhrnech.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtsooekabh.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvznbqxbj.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gtmgxidoli.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zdqjudy.top/Article/details/gtgmxwzhmz.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gticohzwmx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtslebayei.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteszqsbob.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gtgebjutkv.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gtewvtrilz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtciukocca.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtyhknudqo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cdnleiting.top/Article/details/gtdwigxngx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ehwqpu.com/Article/details/gtymlmaelh.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gterfqzeqr.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtflkghyjw.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gtsudsfete.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtmvsuqpoc.html

[T53] Scala：字符串插值
来源：http://dali.yonumen.top/Article/details/gtuifisdns.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gteykhflqc.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtzofsnzhp.html


<!-- 参考信息 -->