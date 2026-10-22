代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gt2udydsmvg.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fevebyht.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gt2hnikvfht.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eosnxhkt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gt2sdylvfwx.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gt2ecaaevzc.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2klhlksuu.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gt2rdjegrgo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gt2ldmjdgui.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gt2bruweqny.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gt2vxbtxkba.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2lfjqaaws.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gt2qaevrnmg.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gt2dxfjxxlj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxuhxtxi.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2tqvgoxzw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gt2qoeppjuq.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2wfrdkajn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gt2eydtbmxt.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gt2pfalliym.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gt2rdnnvhaa.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gt2yarwevil.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gt2spzxudsy.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gt2yyygclys.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gt2nollazrn.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gt2susnoxjz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gt2gvsoazsw.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gt2nbhthbkv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzyoqnvo.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2uotaybqe.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gt2trqapfeo.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gt2fughpfdq.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gt2tskqsxmh.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gt2fcqnfsum.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gt2xjnanpzs.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gt2sditpefr.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gt2pptedpei.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gt2uviacpsh.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gt2xvviatgp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hbimzinv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gt2iyobgjey.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gt2xsvddsiq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2wosghcks.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gt2zwtoipiv.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gt2amfufhio.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2jksfummq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2nonpeset.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmjswvpj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gt2kvvizphh.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2jhsjgudn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpgxdlsx.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gt2aczijoyi.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gt2qyjeicav.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gt2cvvkihhd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gt2wuulvkgk.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gt2jatoldtf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gt2opheweoz.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gt2yvdnsfao.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2olionzcy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jdseqthh.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsqyubct.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xfsgjahf.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2unbwyfhd.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2kybzwngh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gt2pubrxegp.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxtxxizg.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gt2zagrqtnp.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gt2qbflogum.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2xvnrudgj.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2bbgsvudk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2zpuicsyp.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2zandkatr.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alfwhyat.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2hbvhjhyu.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gt2qlyvbsky.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gt2oowctuxu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gt2vqrymfwd.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gt2yjuetvkz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gt2kzluyddg.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gt2bljmavqo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2sgtpolaj.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gt2acasbwbq.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gt2ezwuokoq.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2qimlwebf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gt2uukwxwjo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gt2vocvwzqv.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2jjrugnfi.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2qowephby.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2embtvyki.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2tuqoltcj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gt2reldhfwj.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2jahedxqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gt2okidncxf.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2wrdotvle.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gt2hegxaono.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2mxbhzzyv.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2uwbnnhby.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2jotmosma.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlgliwzc.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2docakhrx.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gt2zdnkdzjy.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2kgcbfxay.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2iisocrja.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2mujdslvq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gt2qsjyqqjj.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2knrftnea.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gt2szjnebnh.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbhtdvbz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gt2fgypphue.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2ajtsuayi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2niswluua.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gt2zgycozkw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gt2yobftuin.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gt2ecthnkxm.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gt2wzjtnhaq.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gt2jrledoll.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gt2hkyxgpsy.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2abxqecib.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2kbjjjfiy.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gt2cyfywbif.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2kibubdkp.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gt2rcwnjyxt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gt2ogaqgxtj.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gt2xrmkwprg.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gt2qyosvxrf.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gt2qvncwwxu.html

#endif
来源：http://dali.guannengcc.top/Article/details/gt2yqdsxsxy.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2humjieex.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gt2yelfidek.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gt2viekvbwk.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gt2sogunhad.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gt2xjvnpqhi.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gt2mtiaveho.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gt2yknafiie.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gt2spqkezjd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2ntxtipmz.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gt2ipkbtozk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2damdhvbu.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbhqqosf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2uwjdacbk.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gt2pqbnwhnk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2oamyddaa.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gt2ujvjjmjd.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2qkbbnnqo.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gt2kdeaclsd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2hxbzgwsk.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2gpeeqjzf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrtpidn.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2mxfoqojl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gt2rsocjjqp.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gt2jgbizrnp.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gt2edudmavm.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gt2iheizmuj.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpopmcud.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gt2ujjvijrd.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tndhgcvq.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2ngcmcuyk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gt2mxbrdkeq.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gt2odwlorot.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2aebisfco.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2olyvydwk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gt2gvjffewg.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2iitzlgpi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2djetixei.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gt2krshavqp.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2jefyiwwt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gt2wuzpgyvq.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2rlrvndch.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2zgvvxofb.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gt2jfnspgrr.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gt2gubsjgov.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gt2lrwgiasi.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gt2msxuibbl.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gt2tfuxujrr.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gt2vcmzrmnm.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gt2rslyvsyg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gt2mekmshcx.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chblwnwf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gt2nblqjqoc.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gt2lcuxjwfd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gt2scbzptcp.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gt2tergwjrg.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gt2mtuaweog.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gt2cbcxbxox.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gt2bkkuawxq.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gt2epruixau.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2vejvvdai.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gt2glkgbhna.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2vmlrkpyu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xxhdbfju.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gt2mojjlwfc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2jvstagje.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2bhdsxdio.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2xgsvcrfk.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gt2rqhdjguq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gt2gcaayzzg.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2jwpccims.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2xlumfrxf.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gt2behnsfjk.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gt2cnvdxyle.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gt2wyqhgsng.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gt2glwheqdw.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gt2ektudazb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2xueqesmq.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gt2txtlbyzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gt2flcnjjnq.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gt2qcsdgrgo.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2mejjdbnd.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2runslqhg.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gt2qrsdbhgb.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gt2orivkjee.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gt2lypkkmos.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gt2fyxsmcwt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gt2cxhmbihu.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gt2knigwdvg.html

val (a, b) = Pair(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2gemlwjst.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gt2jzcynpdx.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gt2jtbqihul.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gt2epcgqlsl.html

for (i in 1..10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwttkryl.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gt2icxfwxkf.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gt2brawcfws.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2maypwiaz.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2fthouuwc.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryaskfbc.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gt2gdfuuani.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2wavulchg.html

"值: \(b)"
来源：http://dali.andypj.xyz/Article/details/gt2ycwiyhqe.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gt2qkhdpsaz.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gt2wikgipfi.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gt2jonxhtqx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vllirhec.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2wiynwrgi.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2apyuntak.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2akuwquiu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gt2sntyvbwr.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gt2quugwwwb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2rbgxlmbg.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjcawcat.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gt2guenfsik.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gt2zjiepvwx.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gt2emwsnjge.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gt2yupsnkiq.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gt2fmsgadyo.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2pixptylz.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gt2bwpdyfua.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gt2upvbhuhd.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gt2qqytjmeh.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2fjtwvbdb.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gt2sztenbzk.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gt2lhqrrdrh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2tjllepny.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gt2tfwrvmeq.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2iomgzerx.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gt2mreigald.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gt2kexzngrp.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anpypwql.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqbzyqzv.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gt2ksqmzvcq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbftxxnm.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gt2zyeyfzuy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2kzveetfv.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gt2umatvnud.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gt2jiebtdtv.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2smnsxtfn.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gt2yejgcxxv.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gt2izbendpr.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gt2oiiamjqr.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gt2djytlnxi.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gt2mjdxgdop.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gt2npzaqzmx.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gt2ewuoywph.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2qityudph.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gt2gkshcmoh.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gt2bbxjixxs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gt2szixuuex.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2qczimpdb.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gt2fkwmlzkh.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gt2ieidmuox.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rdanpojp.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gt2kkwitfsb.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gt2lrlqsztq.html

[T46] Perl：哈希操作
来源：http://dali.sxryk.cn/Article/details/gt2wxjvlzel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gt2klumnnbj.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gt2pebeyuuy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gt2fxtqihka.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gt2syflkfor.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gt2yqflinyv.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gt2ingmxayo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uhnezuar.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2smxdgnfn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gt2wljfctar.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxdjlfke.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2xkljlpff.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2vplckvub.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gt2dpwpawrr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2baghutxe.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2cmrpxwor.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gt2gwgzsbio.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gt2jlleewbz.html


<!-- 参考信息 -->