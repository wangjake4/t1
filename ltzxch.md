代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyabfibmy.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gtozaiawga.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuutfskk.html

[R53] 查看文件头与实时尾
来源：http://dali.cdnleiting.top/Article/details/gtqjzlhwlz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtaksvlxlc.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtjcxvtgkr.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtemdiqxyj.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtfaxwsvan.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtgqnhpgjd.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtbhnaawif.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtwsvaapbz.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtjstveknv.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtxxcuhmdc.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtjrqrujnf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtscwgfklz.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtijcbmrio.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtxmkcodww.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtnplfyouz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtacqrbotu.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gtlfregwys.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtpotuylpd.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtztqtydel.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gthqijckwi.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtzalydpoi.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtokxeulsj.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gthfkxfinh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtdbtzoutj.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtoxldaqtm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtkjmepccy.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtnetaeibr.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gturggbkbs.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtdixafbpa.html

openssl rand -hex 16
来源：http://dali.guannengcc.top/Article/details/gtutllzdom.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtlqollxii.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtmlwzfogk.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtxpzlpmyq.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gtfiyfvkmf.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gtlixjvlqx.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtjdooagtx.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtfdmrbtpf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtpooueloq.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtdwsitnxy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtaewrvund.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyasinwca.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtvujpdcsw.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtfnlruduc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtwiviekza.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtnmgpxops.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtdhjvesop.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtychqzcvu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtizizngrm.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gtdoialibv.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtealglffm.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gtopaztsqs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gttunstufb.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gtesdjnqmg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtuuxmmcfp.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gtstdjzzyb.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtdgoqlyhi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlazaxudz.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtjdhatzlc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtalvdewll.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtmqzyyxpf.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtivxyiyfk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtgblljxdc.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtfkrzsuut.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtsiyymzdn.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtwehnquqy.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtimtxvtcp.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtzdcfftrb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gtdsbcgwgo.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtxivamrss.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtqyigewjv.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtzvopyyfs.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtvcswhkiv.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtgvsznjfi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gttdbramdp.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtfepnzxhb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtgiejabpq.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtotklhfhc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtesjcwokp.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgghvxkr.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtsgqwrqko.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtwctdlxtj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gteuqobohl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtsentwdyj.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtwarzgthd.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtbopwxeoh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtyepiauaj.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gtnsojfmrt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gthvtkexbk.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gtdqxizdtg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtpnenjyjz.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtecidezfn.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoyqiqum.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfyhytwn.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtldlptglm.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtxtqraiue.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtszipckfq.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtpemklokj.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gtvssnpfld.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gthlaqwedh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gthsifecpk.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtdplqiwir.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtucmqlqfc.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gttrxebvgb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtaykwzfot.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtpkwmzoji.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtwlbwyvmg.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtcrcilmnj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtxhtqidtm.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynjechsw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtujszikcn.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtoeylpaoo.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gtzxmfbqox.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gtreiawzkf.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtruwfdhbx.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtwvttbedm.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gthahteksc.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtjsqhlmat.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtpwrbuzfx.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtbtmzxbwj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gtyncovdna.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtziensncs.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtocfinegq.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtxsekvgms.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtguhtnmiu.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtybzpqkaq.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtbduhsgsq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtbnmpixqz.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gtgvbgtycg.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtbxhqfxko.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtjzsdppqv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtioommgca.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtfivxotcg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtsjlqmswm.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtnmkpawjv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfskxjliw.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtfaxbcsmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtaufsgnfl.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gtwemeqiyb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtdsttiumw.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtgicceoyg.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtfxcqssgw.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtvvxctfeg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtjzacxyed.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtukwwoife.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtfzgzkqau.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtxnyikbrv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gtotrhsbgk.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gthelhjmpp.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtktvpgbxh.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtmgnwpjpq.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtsdmovlsx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtkxkaxlcv.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gtfssndbjk.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtljibphzb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtwbxszbym.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtyulprsdq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtlmvlfzmg.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtefpoazkr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtdfsycdff.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtqtrfkcuo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtnrnecqrf.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtoeqralst.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gtitfzaged.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtmrxhbnle.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtvkslnhuz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtdeicfadk.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtsbygipye.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtdioqybbm.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtfqsgwkzj.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gtpbhdxcyn.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtihwtkmhq.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gtsfjqpoud.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gtwzwuqbuz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtdzycmjye.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtiuikyfbv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtiyionxvy.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtyadkzfel.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtorxadwdk.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gtgqrtsuvl.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtruyawphv.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtapbebknx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtngrxkrfr.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtwtdcpchi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtzfjdqujc.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtgqghdrmy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtwiiyuocy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrfulcsnl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtzklwowxv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyugbgnyg.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtutzimzwk.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtnoxahkhy.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtsoqbcyed.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtdqxjhnaq.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtjhfsjmlj.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtrdefzotk.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgorzzngz.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gtblosbtto.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtrdmkfklu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtpxyskkux.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtzezervxh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gttuigeybv.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gteovgmaix.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbmibwjn.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtzduifrvn.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gthfmjjxmn.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtzyibcovm.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtwcwjnfea.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gtmncrzxfs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtdqtyxlxq.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtjzijghtc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtighvepvt.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtendozfcj.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gttfqhbdby.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtesogwzmf.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gtojsuujon.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtcbfmrlaf.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtcprujvld.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gttrgmluhe.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtiklopcwn.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtqxznsrof.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtuluxnfeo.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwbqbyki.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtwpachzfz.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtjuxdatbv.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtbnxbzozx.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtmnovyrkh.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gtpihjodhk.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdwrcepd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gtbyzzhwxg.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtkbfocspt.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gtrwsughhf.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtxswwllqq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gtrrylrlcj.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzajlowx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbfazidg.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gtebkfasdr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtkmcytrfn.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gtoywlhgua.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gthuktxhak.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtjopjoulb.html

class A: Base { override func f() {} }
来源：http://dali.vqdsnc.cn/Article/details/gtcijkplea.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gtchbybvlu.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gtaujgzsax.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gtrbtbfnbv.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gtkbtiidev.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gtlprripmo.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gthamzkukt.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtzpustfzx.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtcvfritsd.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtcvflrabe.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtvbnwdvxf.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtfxdxzlgk.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtsqcduaze.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtmihgvwkd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtpslfxdgz.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gtqscmdvtq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtzhdqngbg.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtycesygrh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtjcgmqgue.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gtoafnqmns.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gtwfjbfiim.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtebkejvhd.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtqiyjmzex.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gtknpilizs.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gtfjbvxjtt.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtemdvqzrh.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtgdvhjfql.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gtusuaithc.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gtmygmpcar.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtylzxtbuv.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohriwere.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtxzqrvlwy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtdegrqsen.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gthjkjutmp.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtptpmcpgk.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjmmdzou.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gtahebgqwc.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gttxkieeek.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtywarsogs.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtamyfemjs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtsulaqxdm.html

[T47] Perl：正则捕获
来源：http://dali.c1oappe.top/Article/details/gtyewlvulh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gtnsuvwhvm.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gtmliheozd.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gtlhgbusho.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gtfnbovttf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtvlftiivj.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtzmzsisjn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtxzesniao.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gtfutnowap.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gttknxjjlz.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtablizqoo.html

[T52] Scala：变量
来源：http://dali.tanke756.top/Article/details/gtbldjuxcf.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtlbmslfxw.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtkkhwlmuy.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtenupnbzb.html

[T54] Scala：集合映射
来源：http://dali.yj20258.top/Article/details/gtbhgxnsmc.html


<!-- 参考信息 -->