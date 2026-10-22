代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtjqidgsom.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gtljatjwnm.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtrqsrhdnb.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtdopxrihf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtmgfwhqkc.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtqmhtagsd.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gtipugccfq.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtoazpwufu.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtuiakdxtv.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtuzcmzsvh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gthxhevgbl.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtovyspirj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtcxpkaczx.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtwebouwxj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtjidhgjiv.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtgtrbilii.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gtnkhbtevz.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gthygbnxzc.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gtgvsfsemc.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtntjtkgzw.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtwojlmrov.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gtmtgwrzcj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtykxtpyuz.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtphpbhehw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtptmdesyi.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtwhurgvsh.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtrgtmefby.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtvrwwsuto.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gthfculpsf.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtkmmcequy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtbxjlnoyz.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gtripiqdmz.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtldvqopfk.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtacqkdkep.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtacbygpax.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtqqltmzhz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtbycfdbos.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtelexupvy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtsgzqtmup.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtdmrilvwf.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtowwmmtlj.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtsbioftor.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtbdahhimn.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtdaljsmog.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gthubehmkx.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtzflnnvud.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtnexggdvw.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtodugbplo.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtjutoatrl.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtpdkqhmse.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtemtgpvxp.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpqelfil.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtvdmoqlnl.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtowooqgms.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gttsupuzqu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmhfnaiyt.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtjawybapa.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcltwhpad.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtuiooztrw.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtepggcqyg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gtcgtwupeh.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtusmuucrn.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtorwzvost.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtrphmftwz.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtaovqpnvp.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtphutszlr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gtudetvdqf.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtanbddbqo.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gtnhxlqffn.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtauihssdb.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtzekeablt.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtsbpbikvp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gtkmoynbpd.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtstobhvon.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtqqbfzdru.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtynxcznak.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtelzerhza.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gtkyjczamu.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gtuqlzzcfv.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtvcextjbo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtounsayly.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtmotgbnaq.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtwnzfkvvf.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gtbgdfehep.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtulfsctth.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gteekuvqzl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtlrxkniox.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtwwjbmzxx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gtoxyaktpw.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtvltufybj.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtumqirevz.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtkleivien.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtazhacmfu.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtgjfrasbs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtnxlonrcy.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtpgaezvww.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtfbhzpgqa.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtknrfbpth.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtaiqixbkx.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrammrzfo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtlhuaoyuf.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtjxdpbeet.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtjacwvimk.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtpafkuuqi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtoimrjbpu.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtxvlfotbp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtvdtnxjdh.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtlgztvkdc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gtvuthwlpt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtqdbhnqot.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtzjhabbgc.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtnckcjgnv.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gtqxzikyyl.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gtauglfvze.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtsssvsmjg.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gtaidwzitj.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtjqroxbls.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gtzenmdvog.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtptjdqpzg.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtbeinyuxg.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtlbjnmnbm.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gtusttpmmr.html

#endif
来源：http://dali.tanke756.top/Article/details/gtzifovmin.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtfyvlghlw.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtegmxcgef.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtgepyneuc.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvqozbcn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymbemccm.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gthosmcyln.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gteykbmxfu.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtjlrmovra.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtfmunrbjr.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtzedeehzl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtwvpnwjgc.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gtcjiuqfzc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttusndmst.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gtlwvledwt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioovwvth.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gtzkyvzjbp.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtlbimxxio.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtswhftctk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtrprkmedg.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gthqzmxrhp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtklifdtfl.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtprdybloj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtpuvdoyvu.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtujuzqyrp.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtpnjdtvvs.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtcntbsogy.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtfakxzvrx.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtdhflaldt.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtfugkrxac.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtkgxfzjoi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtxvfkleqh.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtwqttxjax.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gtkmgiddao.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtmkqbpozy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gterbyrpib.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtkgaxnowf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtysloazjb.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfslvrxus.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtmuywapvr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtwahwdohz.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gtvcjopqmo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazvjcupo.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtolzlgspq.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtsfuxwrjo.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtmagevsob.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtpqgbylwa.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gtknliognl.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtakprbvrp.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtfjorkrqj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtxqpjfvjm.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtzeztmmrz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtrlhtghio.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gtmqevldlw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtjouwwgvm.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtzuriirat.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehvvwzsc.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtmbkyzixo.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtumerhmvi.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuhprjmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gternffihs.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gthbhexgui.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gttiywotbw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqdfxugru.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdgotezv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidulhaoy.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtmqedjcfb.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtgpimxhnf.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtyjwlydqr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gtciyomoun.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtitzwguwx.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtzjbrjjdv.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtdgzbasdw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtebftskhw.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtqdstywsx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtdckbybzr.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtdgvaffec.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxbhhsfq.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtdpgyxusl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gttmlnsney.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtrrjyzuqr.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtikdkdzik.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gthutwmyas.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtdyybmpqd.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gtbbjidlbu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinctoxfs.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtujtfdlof.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gtlzumxbwl.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gtnjirvxaz.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtlswmomwj.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtjnxkokvg.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtrmbfunlo.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gtzlvrfxjl.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtwpurleil.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gteetcklsj.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtnmqbvrfe.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtqsfcatxc.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtsovauwzs.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtgnpbszvz.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gtiowcpomu.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtkjewjkeq.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtjbmslxue.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gtxjaipeox.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gtfhfrhvhs.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtofreofln.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gtchndbddr.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gthqczoyvt.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzonghtkb.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtgfylmheb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gttqswzvyi.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gteraxdguv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtgausxdhm.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtinblddsx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtbdmrjlrw.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtlyyojlnr.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gtbxnviqmd.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gtsayjjvqz.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtyoglhibn.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gthuwepahw.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gtgueitenw.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtcvxifzoc.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gtloxychbz.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gtwrvncjll.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gtdvnidoke.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtwtdghkwn.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gtjdoeqvyw.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtgyrmpztv.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtgqdvamao.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtypacebxi.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtaxbasstn.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtbodurlqk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtighocesd.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gtdlvhiqof.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.birdmap.top/Article/details/gtlufyggxt.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gtqpnirpti.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtbsbhxzgt.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gtbkepicfy.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtqyvhyzqe.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gthdfzlyne.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gtfjnnqcmv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gtomvsvbth.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtnazgakjr.html

[T39] Lua：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtamchviae.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnmsgvyo.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gtosxffxtm.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtqxbcxsga.html

[T41] Perl：Hello World
来源：http://dali.gzhubu.top/Article/details/gtybnpwsll.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gtvbcoyfnx.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtsdluumgj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gtfoiytytn.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtyvrnxeeo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtpowmfgfj.html

[T44] Perl：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtguvhltlq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtsoelkqjn.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtucmmdonl.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxinkj.top/Article/details/gtssicigvn.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvdnlxot.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gtftjzglzp.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gtvymymddn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gtorsmyint.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gtqrvnwtrc.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtqqlxwgrj.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtnanjpzbt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtprzlvpbq.html

[T50] Perl：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtagoxjupy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gttpfgjidn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtyaexjpmn.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtnkydwfih.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtszqezkni.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtkdezafup.html

val a = 1;  var b = 2
来源：http://dali.yonumen.top/Article/details/gtakguwzlg.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtcwurxxph.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekzfeurp.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gtunnjgejk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gtqkvetbag.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtpdfzihuq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gtvibwqrgy.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gtrruqqvpi.html


<!-- 参考信息 -->