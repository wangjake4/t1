代发 wailian999

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2ozjyscic.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2tqznuzln.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gt2npkhjcbl.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikvpxxiq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytvzespy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2itxzsvyc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2fywnoiql.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gt2hifdwvnj.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gt2enejttky.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gt2xayhrbxk.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gt2oeyhdqgj.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gt2qbzrsjjv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxgtikuo.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gt2ejxljmgy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gt2spatgwpd.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gt2ydmwllhs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gt2almuznps.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gt2steaqyhb.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gt2hivwiayi.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gt2lqjhyepb.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gt2hucdtamu.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gt2udjiqlsh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2jandzbxq.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gt2lgpczist.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2sodyfqwl.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2ukaacnci.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gt2tjccasah.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbqxnztw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2ovjasceo.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2lprsbhyq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njcyowfc.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2oapolyii.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gt2cigmmrwo.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gt2dtrjlesr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gt2kccgvpyg.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gt2plugapml.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gt2duwtrcyb.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gt2vikteupo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2rwlhdpwz.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gt2fokepkdx.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwqdivmx.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brlokfzm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2mdtarrca.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2ybqejibk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2tbjmtyup.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxabnuvu.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gt2cufhpnvw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2dhvfkbkk.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2jzleevro.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2hxfkqktz.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2snausxgk.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcgctcfx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gt2jjibezwe.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2uayhtteh.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gt2sbgonhab.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwwzpcgm.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2kmtlegia.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gt2exevarzj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2vszcrdjr.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2rgdxcyce.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2jznyxyfp.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2uvkjsvyf.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2bokjydpg.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gt2ppyotpiw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gt2haclbkpd.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gt2enimglzu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgmlyedn.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2hgpolpfq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gt2okcuztvx.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2leklfhui.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gt2nnxyfiud.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2fkmiyecq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gt2rmwgdttl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gt2ccsfxvip.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2zceoxwki.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2avqmspmi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2kewvsbdr.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csgcgigg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gt2vtecnjwv.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2gexntpkd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2lvfwkviy.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2myzemsux.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2yhyqprbi.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gt2irpgkaps.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gt2ybywkivo.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2kzncfjhm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gt2fydhimlp.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2volbulip.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gt2hpnlumje.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gt2qlefulcr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gt2hwcyrlmf.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2meajgicr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjmrrubz.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gt2wxvyoijp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2waiavwqr.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2rgpzautm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gt2eytgpbnz.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gt2bfpzpulz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gt2efoztclw.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2uxlnpoii.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gt2pdluzenj.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2twwytfrq.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gt2trdbtacn.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gt2zsnfenfr.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gt2nrqeqbef.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gt2xbtbnyhv.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2oyznmtdw.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2weidqtno.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gt2isgsivjm.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2hwaidsqm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gt2wyavxels.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gt2fytnzafb.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gt2dbtdppzp.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gt2gupuhjyi.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gt2vpupgwtz.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2yyvwvlrb.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gt2unnnbvxs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwsmjcve.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2xcqabitg.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqxbpttj.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gt2xtsertld.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gt2fhhaorcq.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2axsdsskk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nplfnyrk.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gt2mebwpcnp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2ubzhwxxs.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gt2jpzvzosa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2wzbobsyv.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gt2nljiglon.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gt2ssfsfoao.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gt2fwsykmme.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2uiqoivbh.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gt2voraxltr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gt2ienyswgs.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2onpwxrgf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2fckdaakg.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2cdkakqii.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqwidnle.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqnyrsda.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gt2wvpztjtx.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gt2xeysamga.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gt2ryuaiujt.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adosforo.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gt2izbradyu.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gt2crkuubbm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gt2lewansjz.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gt2xillwqxy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gt2tcfgfvcl.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjjlwmpe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gt2hghncvno.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2hrvvwruu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gt2ovwqkpwd.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2fjfsgurr.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gt2epylebvs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2rnztqqvr.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2ebpmslyv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2tkkpifgd.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gt2tcialiwb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcnmorw.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2adesfcen.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gt2uiexnwzj.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gt2qqkhelzo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwipiqsg.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gt2yihojqsd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gt2wybwtbvi.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gt2cwggeowl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2iwpqooup.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gt2rtrcwzel.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gt2hslcfidq.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gt2bdbdjhwr.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2nphxcwsx.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gt2bsvqytam.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gt2brvwbijd.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gt2pbswidln.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gt2vzclswgc.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gt2gbfjbybx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gt2nadxbakv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wjpunuvz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2wonpxizb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wajvknxi.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2ujpwsops.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqowyvkm.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gt2mekudgof.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gt2eftwdyng.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2lzmbfcmj.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2ivqvwzvq.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gt2ttiprnfr.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gt2qetikyty.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2xauomdsi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gt2zxdmntkb.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqahdzmf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2bgwlyjcf.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2mayybbpn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2exmjfkok.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gt2ufqohxmp.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2obufgoad.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gt2frcgbyuv.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258888.top/Article/details/gt2philpphn.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqhccrwu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gt2ulklskbq.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztkgooxz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gctnhipb.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gt2jyjaghxg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2olenpnji.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2vzyqtatd.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpzitbde.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gt2htqyazyl.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2xgztjwhp.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gt2yuygakyr.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gt2ypopfqpl.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2tzivtqza.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2qajhqlqx.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2koecxmhl.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2ahwmsqxr.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2ctixnuxz.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2eghiziec.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2xostqgzl.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gt2ehbnapnv.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gt2uvzyxueq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uulmlnxt.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltmmzvkh.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gt2jeavxqnb.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gt2ghnzryjp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gt2jsshvsxr.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gt2uyayujjw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2amnyiihh.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gt2hdowcowa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2pjphlwht.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2mvlqkabh.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gt2wzobbeua.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gt2gmwvxnqx.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gt2qvvcopto.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2kfaqvksg.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gt2pdekqygv.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gt2cjfqcaey.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gt2cayothya.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gt2zrchsqmw.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gt2lcpaubra.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gt2nswiopmk.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gt2lwngdnrn.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvmrhjvx.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2pntwjawy.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2nvxwetpr.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyhdzkgk.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gt2anuiottt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sxryk.cn/Article/details/gt2jioqehsf.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzzzrnlo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gt2ncwkhkmj.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gt2irgtvusc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gt2tfmznjwc.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbganpet.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gt2yvxvsjqd.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2ykiiemxc.html

"a" .. "b"
来源：http://dali.yj202588.top/Article/details/gt2gqhoqdax.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gt2zujrgvux.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gt2ezvjgbtw.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gt2tkktmiyu.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gt2pjcsdxpu.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gt2mrotteje.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gt2gfoyfnlf.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2egphaxrp.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gt2ikoannbx.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gt2myawdlph.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gt2lfmxjkki.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2hbbpguog.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gt2ncghovdc.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gt2mosojyuh.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gt2qqffrkqt.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2odofsldk.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2ssjqmgdg.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zszschdx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gt2yymjcjgu.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgdaihsv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gt2pmczgyya.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbrxdbcp.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gt2ffondozh.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2icepuaba.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2fsqrgjlk.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2xndfbxrj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gt2fhyjobci.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2eqczefiv.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2pwyocmfg.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2ogfefnrm.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gt2suthoomz.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2ugotodvw.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2pjhalrfm.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2uwrjpasr.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2ffifqxlc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gt2akfwcfps.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2cdgpqmkr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gt2uxopmuhe.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gt2bxwfxrsm.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gt2gferuuag.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gt2jbfepdka.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gt2ftsttyxu.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gt2fchfczpc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gt2igefpeqr.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gt2ubfqxrch.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2squnbsbe.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gt2teyxwcmg.html


<!-- 参考信息 -->