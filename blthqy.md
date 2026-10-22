代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2tsdugfzc.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2bmtvgqtn.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2jgprlvsd.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gt2poquqctq.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gt2dczfawiq.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2rkcntutc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gt2efbuxgcm.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mygolqds.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gt2pizygfql.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2bvswsckw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gt2qmlltset.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gt2ylwgslmr.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gt2ozruqwpf.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gt2bcsyqeog.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gt2zkcumokj.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gt2cdparteo.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2xflcrmtb.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vaziluft.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gt2caciogcv.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gt2uwelayll.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2rqnssmjc.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2ofwqajnj.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gt2ggymptju.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gt2egmbqinu.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2sjvihdlc.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gt2xoljhume.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqcdzgit.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gt2hpypiifx.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gt2bgaqrvrm.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gt2ceszvscw.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gt2ispfblvv.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2sxltkplt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gt2gixhymst.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gt2pebtldxr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2jbytrjvx.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gt2twuvorgi.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gt2azscakeg.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gt2bycemgky.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gt2roimciry.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2rtygohmo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evqcbytq.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gt2jlaasifp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gt2ecgecjpx.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gt2vgffkmud.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbelzez.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2xhxskeju.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gt2behzlyea.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gt2hcbhvnnb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gt2ehfkmfqf.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gt2cpzrfhqs.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhhsgjeq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gynpmalz.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gt2kacagbhx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2jqwwouyx.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2tbohvern.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gt2tjwkmdzf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gt2cfchfito.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlvxywmf.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gt2ndsljyky.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gt2yzunurgp.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gt2obqcrult.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gt2xfwgtnlv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2hxznipnl.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbzejeky.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gt2clejwmmb.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2weqqujzf.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gt2raknsloj.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2mcixjzae.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gt2gvcdexnc.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2ldgwyraq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gt2onjazdrz.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gt2xitsephi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gt2oczgcjnx.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcoqdvjp.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2jsvlgdhx.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2coudzslq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmjngudw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tanke756.top/Article/details/gt2rqtgoqhh.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gt2hvpjdndz.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtvldosr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2aultbogd.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltffstis.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2bhdutiog.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2yhebautt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gt2ybyucobb.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2hwimisvl.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gt2kwcsgfjg.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gt2vtjglage.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vueobbap.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2hzgthjmu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gt2ihkzyaon.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2owktpdbw.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gt2pynjgjdc.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gt2rrtjwijd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxhdjkfk.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqddlolp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2oitazvau.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2ksdvymbn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gt2axbaahmk.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gt2pgbawntb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gt2vmycvinb.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wovziicr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gt2wxjqrefr.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gt2gucjvkjl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyonqmuj.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2zugqdilg.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gt2iuqtqobu.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gt2yolplvsj.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gt2hsulbwnp.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gt2ojqffadg.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2fkpljcmj.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gt2rpazvrsg.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gt2jmoczeio.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2ykitngfd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gt2nmedxbqb.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2mmpskfzh.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gt2sbobbhws.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gt2wbriivmg.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gt2vdfpairm.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2dcppikyf.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2idtlfdza.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vojsnhlx.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gt2dlhdavbg.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gt2facrlxzo.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2bfzuukdo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2lyeadsiw.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gt2biolozvs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2jkuveamr.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2vtqabvsz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2htxuutdw.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2spjkuxgz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2fdixvjms.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gt2qrypolmh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2hhjraire.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gt2zhsiltkb.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gt2bvsiqaha.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gt2qylktmou.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gt2phiymfxm.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2eobjijbt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2jibikhsh.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gt2lgxrpskz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2vodxhfxo.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gt2ejkjevpa.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gt2lfxtdsmf.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gt2dwcnyrpt.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gt2zzslcbmk.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gt2fhcalqce.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2cpmwaflu.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2bvlhiovg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gt2aucxpzyy.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdjmyyhz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gt2rnghckbr.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gt2byavkpqc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gt2hedtsqru.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2mkcppimr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2sezlxtkq.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2rhjcjwvg.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2anfkfijo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gt2jgbrkvsu.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2yosudcrg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2imatcbhk.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grgnyujw.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gt2esycjzvq.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gt2kfhhxboy.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gt2wfidlblc.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gt2qqfqqzog.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gt2clvowrxr.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gt2ifaalyhp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gt2aqhtruuj.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gt2urfqlarx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2toslswbx.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gt2tqtremai.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdfjjauu.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsawtgtx.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2lqujfcto.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2igetzhra.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeqtxqpz.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gt2dmhxatyk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gt2xuknhnak.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwdhvbkk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gt2qudbtrwc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jmudpzrh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gt2uytvalbv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2nfmuavkb.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gt2hwcorngb.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2ujclbwrp.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gt2jocqsgnq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gt2noqtunad.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2umsnisez.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmyxisiz.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gt2lamcenio.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqmglrbd.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gt2myazbbvg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gt2ouixvlxi.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2hjuofmjx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2rokoplpz.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gt2vnhwnksf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gt2daczlsat.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gt2nighqzlh.html

data class User(val name: String, val age: Int)
来源：http://dali.sweek.top/Article/details/gt2tazthrqf.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gt2izjrfxmx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cacjctpg.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gt2xktbammx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gt2axuuknpv.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gt2dtjaetak.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gt2msyhfodx.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gt2ufzymjsd.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2bjdhqegb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbwsdem.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gt2sqwholeh.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gt2ilaubbrj.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2iqoqetcx.html

[T15] Kotlin：接口
来源：http://dali.shzxlz.cn/Article/details/gt2nhmlfswd.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gt2qcsppmlw.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2epresmaf.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2mpaeoctl.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gt2ootsmejx.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gt2crgzjssc.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2fjurnqqr.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gt2sjziweyh.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gt2mkezlmgu.html

if let n = opt { print(n) }
来源：http://dali.ehwqpu.com/Article/details/gt2hhoilouy.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gt2lpzkltsb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2nkbdxdxd.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2tqehpngg.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gt2hjlmqnjl.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gt2yvxjtkny.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gt2ymeqhgyf.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gt2nwyztuyq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gt2lftxyauf.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gt2ulwytehr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2manpthno.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyzssfat.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gt2tshlitrt.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gt2skbojyeg.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gt2aibqxlhb.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwntbqeq.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2kycxssfz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqvtpau.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uucejopg.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gt2kpjoyuuw.html

guard let x = opt else { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ponzpusm.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gt2ypwjhslc.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gt2rdyzazhe.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gt2kywlzzuc.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2pvivjlal.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2dvqylnrg.html

local a = 1
来源：http://dali.sufxvd.cn/Article/details/gt2eceisxcx.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gt2hhykgmen.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gt2ujyvoekb.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gt2jaofrmwg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gt2pnxhfoou.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gt2mhlcmpbe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2wmdohqvh.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2pcfbphrl.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gt2vtucebdu.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixoaboll.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gt2oxsjgwig.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gt2ciongnhu.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gt2mnvqiwhx.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gt2vmfshwqo.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gt2dubnsnys.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gt2fhskvnzy.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gt2kjmvmuzs.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2umqqrxog.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gt2sweqrdhz.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gt2whwjftiz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gt2phfqyiso.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2volkvzge.html

"值: $a"
来源：http://dali.hnxiangtu.top/Article/details/gt2wsepiada.html

[T44] Perl：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfbngpfr.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gt2xtjlamsn.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehdjbyij.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gt2rbdxsnmm.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gt2ilezzdcl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gt2vorgfxdq.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gt2vphldtyo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikrckjpc.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gt2qpozwmhf.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gt2tupkwupr.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2iofoiqvv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gfvpywxu.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2jkjsyemi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gt2krtgwtdn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gt2tezapmyf.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gt2juhavgio.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2bprjtvno.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gt2ciyiprht.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2awofzlbc.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2gzzkkvhm.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gt2ikaiwkij.html

[T54] Scala：集合映射
来源：http://dali.hnqzz.top/Article/details/gt2ynqwfawu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2vlwflibj.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2erhenplb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gt2rqxtarpz.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gt2bihezelz.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2xmxprnok.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlnsqbpj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gt2htfmngsy.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gt2ifvjpqnc.html


<!-- 参考信息 -->