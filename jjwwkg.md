代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gt2ebyhayfc.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gt2uuwmyspg.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2shjkuppr.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gt2rrdgyoyt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2markxnqc.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qltibgyf.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gt2mltsmbdl.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gt2fjbjqvjl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejelruwd.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2fbixirhz.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2iodwfzto.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcqrxvjs.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gt2hkotnzqq.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gt2dfnhgazt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gt2aferajgf.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2xhrxuiso.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gt2rkxryumh.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pektmxgd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gt2praosmvl.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbqardbd.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gt2rumfafhs.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gt2uepifnoy.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gt2cyughozx.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gt2dpbitzto.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gt2hdpaexzj.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gt2xsgwanui.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gt2zdcuiujv.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gt2zmwwjriu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2koywxlcp.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2ixekglhu.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gt2hyduzdhr.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gt2ygcyoetm.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2ctpfpzbs.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gt2iflpfrlg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gt2fvugkzhq.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtgagetb.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gt2hiayjlbl.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2wvgvbjum.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gt2hltgllvb.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2biablkel.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gt2estkgdfc.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gt2achpsvci.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gt2zjjfmehj.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gt2vopfzgbl.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gt2ijbhvhmf.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gt2widhtbhv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gt2hcivjdaw.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gt2rwokqflp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2okzienqc.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2bnlzedhk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvrnxvpq.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gt2gkvyywcd.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gt2uqhmizcc.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkvfyinq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gt2llfcboar.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyjyeivl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gt2elnymegt.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gt2ywaabusd.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2vdumqmyf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2yepvjcmg.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gt2nfvzbbgu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2yayybhfr.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2qjqssssi.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gt2fwnjfypf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2krsfivia.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2byriyjzs.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gt2lrjsshtm.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gt2bsixmeex.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2wawzgxak.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gt2llhkronh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gt2duslzoyu.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2xnbacpad.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqpuitxe.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2rcxifbly.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gt2yzcijpji.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gt2wpiuchvx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gt2jayzewph.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gt2ztlsmfqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gt2rgizawoe.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gt2huspblwt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gt2vwvbnuvd.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2gmwfjivm.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktomaeye.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2cfsmrsxf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aibaodan.cn/Article/details/gt2dhcggieq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2oaazrgfg.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2uruffnsi.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctwqzojx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2kbyeinvh.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gt2vabkxixb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gt2epsbxuoq.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gt2skuottlt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2fayimflb.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gt2ewpcnlwr.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gt2hwtnlyab.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2nhbwngya.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gt2eewlntib.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2paopgaco.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gt2pwsqwkhi.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2mrdkonkh.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfnsfwtz.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gt2bhpdmlhg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2mtmvnfpf.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gt2hexbsbay.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zglfexcn.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gt2zibxbqkg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gt2atmbbqtn.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2dakedfac.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gt2anpenjnr.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2oukjvfne.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gt2nklddaxo.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gt2vacmusmv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2iursxmjd.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gt2efvmvoxd.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gt2mllwvquc.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gt2rboztdfv.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gt2kkeditzh.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gt2mgkwjqdt.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2uwdfugfv.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gt2fyzgnwku.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gt2bppospcw.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gt2ttofzkgb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gt2exyumcdf.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gt2ortrfpfe.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gt2gueppzsu.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwaxhhux.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlhexjas.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2zysbwitb.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gt2wjhlvhip.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gt2cjvlmfwu.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2ufbsjgzz.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gt2xhfoxvkw.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gt2yfmbaxgy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gt2dwzxjagn.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gt2qlmdogvq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gt2cqcwmpbc.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gt2qecoutjb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2dukkdkyr.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gt2owothrgd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2ftudlyeq.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gt2wudflfer.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gt2ubbpujal.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gt2djrqdcch.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gt2altzukqa.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldneesmf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2lpcvbgbv.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gt2razzsqbl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkfwmbnd.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2wuqgsecw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gt2keogkurr.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gt2kjvtiijs.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gt2dwbwgflk.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gt2mxgnbohj.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gt2qbopuouu.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2jqonllzz.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsonbxlt.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gt2arfxfbsj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gt2wjoxfzvd.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbgzmsgi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gt2xozsvdvg.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gt2qsjowlzf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gt2wwoimqsp.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2jkeudjie.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gt2mourtwbi.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2sdeoxeun.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvtbezmj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gt2cyvnvaxo.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gt2nutqtiph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2vmconkpq.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofpsrisy.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gt2btrnkags.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gt2sgtwmjdy.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gt2czvfpqew.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blycafeh.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gt2keracjdy.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gt2jjgyyjla.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gt2kjdlksly.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gt2wozbcqcs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2tjtsdjcn.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2bnrkxddx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gt2azatjsml.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gt2nbaxvxlh.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2rahryeou.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gt2hkeqqzdx.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gt2squuzywb.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gt2znqvaada.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gt2zupkafsu.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2xxmmgxwt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2agximgxr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2mazowtzn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gt2mgixpeuq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzbnzecn.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2meaifmln.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfzqgpbz.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gt2ekukfjsc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gt2rautbecy.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gt2ggcrvdls.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2hijkviwa.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gt2kzyqwjdu.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2uefzqbft.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gt2kqqsmbre.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2nhzfwpyx.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2glpqeics.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2wdfmkgpk.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2zjiurpot.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gt2bdwjakoj.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2rdqqacho.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2vdkwyzsj.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gt2sqyjmmqh.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gt2glafgbhy.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gt2lzcbnfas.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gt2rgqvvlrh.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2yxxyzrol.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gt2unpsxeee.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gt2rxqfclhq.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2fwgeziwi.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpbcgavm.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gt2gahnqgof.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gt2xymbgbae.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2khhgovzi.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jarndeqh.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gt2esqgacvv.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2recemdrk.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2tsxktthx.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2iaunqtzb.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arnuaqnz.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2vpnbrjqe.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gt2uolurcpd.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gt2qlmqsvwd.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gt2jabstguk.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gt2pgtewent.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cabhrglo.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gt2pdkcafhf.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gt2qrvbvodh.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gt2tvedinzd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlqgziqw.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gt2uejyfipd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2kdhgbfow.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gt2ecgiezcl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2wtwwblol.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gt2igevzuma.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gt2narbkymz.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gt2qhuokbcq.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gt2ifmmwurf.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gt2ncfwvqnq.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gt2kiyfaxea.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2lovxgrvy.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gt2feewymdx.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gt2pbwjretr.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gt2fryrfouc.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gt2ovaaqfcy.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gt2uvgszcch.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2mttawaug.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2ijnondbd.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmgcsgys.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gt2xbqnfcey.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gt2ibzoryko.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gt2yazwtdvh.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gt2pcyatepc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrioimvz.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gt2pdwceacr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2rlmamsas.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlaoujdk.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gt2mlpmnxvu.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2hihsazte.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gt2ernqwxjw.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gt2rrbewdrg.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gt2prptldot.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2itmyldpa.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcogdtni.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gt2loymuhbc.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gt2ofrlfsdb.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2lblvboam.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gt2nehskclr.html

[T42] Perl：变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjcdeaqo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2trxelimo.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2vlhlitqk.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gt2zkbmllib.html

[T44] Perl：条件
来源：http://dali.jyoumei.cn/Article/details/gt2pfvqlhdw.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gt2ooltbgtf.html

[T45] Perl：数组遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2dvwrznxx.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gt2otshexrl.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gt2kppbjlfi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gt2fchmacsw.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgfgccge.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gt2aukxhdgr.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2hxxbdyqj.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gt2awzqurye.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gt2trdtvaib.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2kbliojrq.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2zevompjw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gt2jnveukdy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2obbijifi.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2ssosnnuc.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2cvsvfqco.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gt2tweuader.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivhnxkau.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2yzmmuccy.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2syornyuv.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gt2zwfpesih.html


<!-- 参考信息 -->