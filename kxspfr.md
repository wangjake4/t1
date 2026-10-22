代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gt2gzxdanfh.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gt2dfsptsry.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyeyrvif.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gt2gjcwnygs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gt2aryithow.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2ibflknpw.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykidxkcg.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gt2jkrfkjtn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gt2bioawhur.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2izixldmc.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gt2pwwhgbsd.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2bvoqmaef.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gt2gmnoavtu.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gt2trtsfiql.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2ssyyspsc.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2mchkghsh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gt2lzxmaxxc.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zudbftay.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjlnial.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gt2rdllqkqe.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2vevlkyuf.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozzmrwwv.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gt2mtyfaikb.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gt2qhejqqwt.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjrudwuv.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2okskfasr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gt2yqywxbps.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gt2talrmoac.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gt2qfhoyzbu.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2nrtvilhv.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gt2zerxkvip.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gt2uentcdry.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2onpivrxu.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gt2yosxhfip.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gt2ssfhjnpi.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzgvfxzh.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2frqwxscx.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gt2eqxmhrru.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gt2rqlxrvie.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2gzhsniwq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gt2jsevaxtl.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gt2lvpxefoz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrznkjwc.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gt2tjpaahwy.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gt2mbtbcbdl.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gt2jkfxckho.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gt2tanoqwvd.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2oyveafzs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gt2merrqata.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gt2orrlrbzo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2ddbshgju.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2nzrxybjo.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2tiiexzwk.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gt2rginugol.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2qvamekrt.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gt2njemsqgx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gt2qqtubkhz.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gt2bazppsxu.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gt2jstrkfkr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2aqvtlbfa.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gt2scxitxcy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ikcresnz.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2sevcznew.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gt2fejnjxwk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gt2heeyvhvr.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2umaarbdu.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2hmobayix.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gt2yehbnhum.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcjgppvr.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gt2uqoplxgs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2ukeqdjow.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcjfbzfe.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbodbtlo.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2hctjzzrq.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gt2aphlfimb.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gt2xgxqvvzt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svyuzlfl.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxvvomqt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gt2mvoperby.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgntfhsh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gt2qnpweihb.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gt2ijlloeld.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2ororngys.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2hkypjjpi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2makqmdxi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhlspivd.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2rafgyuuz.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gt2qguloyam.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2wqmbjtqu.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gt2jeduhnjc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gt2dnutqbzs.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gt2yrfzhlbj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gt2hbpujzpu.html

[S15] C：类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2iddqrckw.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgafrmgv.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gt2bqyjgzmp.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2xrbpergq.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2mibzanzb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gt2jacpqjxx.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2ovounjra.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2bjirlybj.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gt2bzitosdr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2rffqopvc.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gt2pumatbmb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gt2zmkflspl.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gt2tdxaebgf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2bypofblf.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gt2jpobfzvr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gt2vhnvsxvw.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gt2bdizxvdm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gt2fdxjuacf.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gt2oiytgcfu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqfcbrym.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2exdshhcm.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfgjwyck.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gt2cnvufysq.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gt2rwbmdyef.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gt2ulokxqlg.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yptnopoi.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gt2pkkjfpca.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gt2wywbaqrz.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gt2ygnufxgz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gt2alxliyzg.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gt2tanuahed.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2ykvlfwqs.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gt2kmtlijrh.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gt2dbooprlz.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2evwraydk.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gt2cbnxggqh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gt2lamwjxde.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gt2siuoxgih.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgbswqvg.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gt2udigmuvn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gt2dkypvjgn.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gt2uznyknwa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2snnhdmas.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gt2qzwpipdc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2tvjtditd.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyjuxlwt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2bjsebith.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgozvucx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ybcxt.top/Article/details/gt2secenyml.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2ueseypkl.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2pxdfervg.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxhfxkiz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gt2vwkhveou.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gt2dhziktow.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gt2rqbqffyb.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2etomhsnu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gt2dwsahweq.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gt2ccwnhqcz.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gt2qndovjcs.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2tjbjgjsk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2qsmoeawe.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gt2hyeoyugc.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gt2lwdyazdr.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gt2aeksumgq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gt2rovowkhq.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2jorssobz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gt2jkatgpmv.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gt2cmwgfnes.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gt2ggdyglkg.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2itpgjpaf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsrrniks.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgtnqter.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gt2mzmdwqsd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gt2yutdibeo.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gt2tkgkihrg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2nmlbztvu.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gt2rllsdxvn.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gt2tobysxwx.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gt2oneluvdm.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2ptobpoxs.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gt2pminyyhi.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gt2ljtmumvp.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gt2yhulajqb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2ehwvkojy.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gt2bhzmwxyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcbfnoc.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gt2dvvvlxre.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gt2bpofnrte.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gt2yqpxmrcv.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gt2nbnroroh.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gt2didsnibz.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2fwaxjymm.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gt2yhsvzbmk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gt2zipyngtw.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2tacxvggn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2tidmnpgy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2dzlixejc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2zyhwjoaz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xpxsfelb.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2oidahsug.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gt2hrpbvbiq.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2tuhapqst.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzskstfg.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gt2syolofqi.html

"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2adghjlod.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gt2lwhjmosc.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2aetglwst.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2obpgtjih.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gt2ozeeofol.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gt2hdhmmiel.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2gdoqhtag.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2vhrkhowu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gt2wziaxxbt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kxennflf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gt2unzyunsr.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gt2rlmoebkk.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gt2kxvkwdlx.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gt2kubjikpu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gt2ylxhsbqm.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gt2tpbqtjdh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gt2jssqjuiz.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2erqstrpu.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2lhrcmnkn.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gt2ergmamlm.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gt2qtuaumci.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gt2mzznthpp.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2glqyxkjm.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gt2zsylvndy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yveqtanj.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gt2fuuwitwe.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2yictoiit.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gt2geasfghp.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhoovgry.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2vvbmokbt.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2jxoaccem.html

[T19] Swift：可选绑定
来源：http://dali.ehwqpu.com/Article/details/gt2xtyeozoi.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyukigeq.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2cuhiuefk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gt2cavwsiyy.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gt2kyywuiec.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gt2mexqpfww.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gt2hikdzyvb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqvntlqq.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gt2lxzgcyms.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gt2gcyisyww.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gt2slwzudsg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2bqboftee.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gt2ehsytbgf.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gt2edtnrzts.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gt2pomevfqm.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gt2nhwxgilm.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gt2ioucyjbv.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gt2uhuqhxeu.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2gxarcucg.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gt2ktlvzpvh.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2shfhwxer.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2tozkxotd.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2pggvbkow.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gt2kgehdwhu.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2vgzghojm.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2eouqcajc.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gt2txvmzerf.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gt2wfgbvgqr.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gt2cfsfqueb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gt2kytzjmqj.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gt2ofxxreft.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2wuvzvwje.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gt2mdfvwufj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gt2jtidtpen.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gt2mzhmyeid.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gt2plwyhupj.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gt2exfgnfwd.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gt2pokuyqgl.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2jksrsaou.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gt2sgmgpiam.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2vhuyeeoc.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gt2lofunkft.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaygitrx.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dskyesot.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2nfqnessm.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gt2fewvpfgk.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2lozzxkij.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gt2ogjtiifd.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2heheanqb.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gt2ieqxdrgt.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gt2ttimjmav.html

if ($a > 0) { print "正"; }
来源：http://dali.cheryme.top/Article/details/gt2enmblsau.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pspiolkn.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gt2oqgsdkqf.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gt2tcxwhzcf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gt2pmhimtpx.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gt2tluqcjtu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gt2pdwfqjxv.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2hfmztgad.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gt2fjqmhrxu.html

[T49] Perl：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fucwowpb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2asiobokr.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2omrianae.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gt2giiqkhcc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gt2hurfoswo.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2jobwmlaa.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2ladvqamq.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gt2npcwzcli.html

val a = 1;  var b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2kjqgjdby.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2quqjeilw.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2otwegmev.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gt2iskjqcms.html


<!-- 参考信息 -->