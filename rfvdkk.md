代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtdhhzxisx.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtzxyakddh.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtlehesmbo.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtwhomseuz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtlpqsitvc.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtwspvcafo.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtmdwyvrhp.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtklaahwnk.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtoadziqhh.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtoyscnpgl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtwlpezvxt.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtmepnvrzu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtacrluhcf.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtgwzlvofg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtincxbfwa.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gttqezwwhn.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtdrfompsb.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtvvvrfgks.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtrjbevrjq.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtjdqacsll.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtrhxoldtc.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznjjmzah.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtuzsgiipz.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtjfbzatcr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtmoxwnqcw.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtdhnmjrgz.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gtkdznsxry.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtoicgevfa.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtorknaghz.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtqqpaknzd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtzaravxoh.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtrgxskoat.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuyxlsoo.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtqjpmulfv.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtstsqvrxi.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gthfpmzpbz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gtnnwqfipb.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtwjhfrkvu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtcntapzqw.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gtiwygndla.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtgrgoeaqw.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtpkibxfkg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtugbuvnig.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gthfmtwcsm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gtvkksycdr.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gtvbmhspoq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gttswcceyb.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gtfufbrcpl.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtklxmpwzi.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtkniulypv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtjbwhoenu.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gtwqmfdute.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpiovrto.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gtscjzntpp.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gtpbxunkbe.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuathwjqb.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtyxvyyout.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttvoknnlk.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtizgzyhol.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtmwpbwxsq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtfsndguck.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtxkkkkvyd.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtgvlronji.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtrkdtgwrl.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtqkrrbegf.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gthbsuhwrb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtzqvipmoe.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gthlhccjlf.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtqouhpvjv.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtxpocxxdu.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gtyfhtyrzt.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtoegjzmeh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gthktgtswj.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtejwtkeot.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtjzepnrky.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtxrntychc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gtfkluuepu.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtdqtqawti.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtfmtzcdfs.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtxxdxsadm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtobzvzlfv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtxblwfowa.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtfvrtnwnc.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtjelinspy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtrzzdggxs.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtupngixrh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtrqnykxnw.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtszoowjas.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtfdskmali.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtjiaxober.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gthyvkvcgn.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtoseynbqh.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gtxueoytyv.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtzyjhkfkr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtzezucuhv.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gtfyalqaxg.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtbnhnjjyy.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtmfaqmilj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gthktwmgbn.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gttgafkpfd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtqatmakag.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gtnpubxpcu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gttbumnsyi.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtqvnesxph.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtmukhomol.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gthqzsblfw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtqkrhbqte.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtscetylyr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gthefcshjb.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtreiqvvec.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtsxqkimjy.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gtezgnkhzx.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtefkrnyxz.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtfzqckbql.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtmszmgbsd.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gtyvfkitmh.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gtjhigmwsd.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gtxppnscnz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gteffmjegf.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtkluqfpum.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtdvvszwhi.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gttkddwnun.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtxammcido.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtroycspqp.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtljzkuvdv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtmshyoshs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtksnyzeyl.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtkqcmcyhu.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtffxszzfp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtpaxoamlg.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtowocnmyb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtthztkylh.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtlyrfisyd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtyzzhklxm.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gtsmzzngze.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtpfxdrewu.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gtxxcqtugh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gtwxadddpg.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gtjbajqova.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtiswyqpdz.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtipeumcep.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtntuionsu.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gtadasmppj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gtppwlvukp.html

[S41] C++：类与构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtfquqyhgi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gttsngbqik.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtykvcpwou.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gtrjncpvws.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtotbchfke.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gtqavnocgh.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gtjzvydbsy.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtqknfmvkh.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtqmzyqcqq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtxxptadxt.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtrbfvevis.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtusbfaowg.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gthrdtwoli.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtbrbokvcm.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtsimoxssh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtwtojsdvf.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtnlavmvqz.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gttfzcgoeq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmcsdvim.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtuclfvizh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtrlzauvqf.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtuhqhfxsb.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtuxsejeuy.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtswozpemp.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gtqttlpanw.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtkxbnshlp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtpvkddubd.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gtvgezmvdp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gthuricviw.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtutrnnqme.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtgshgxjie.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtxwaczmel.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtcgndmcwu.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtavepbpyo.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtdnngpine.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtgluiiglg.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gtfxruyzbz.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtwynjuatl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtagcjirqs.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtzazxynpq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtgigukcpu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlqphbwqa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtvvzygmqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgikfzkdd.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtelgkjuun.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtjwekwbmj.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtoyygpkzz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gtmiohyswq.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtykaodjtt.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtpzxkrfdy.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gtirhxwopp.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtifuewcnd.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gtxrgvzilq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gtnzxgghgt.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gtqgsdeabn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtwhkvisnm.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gtwruxftdk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtziyljqgs.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtggtnvphj.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtaswfrpcr.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtxbyjboql.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gttnwlijsg.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtyfnmrrno.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtqijwunwj.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtjtsynemp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gtndsiogfd.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtoocxmtml.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtlarilpya.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gttapopavj.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtuesaspnl.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gthhmzrzvd.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtdbgpekel.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsykqzpm.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gtwbkqjrcr.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtulgdslzc.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtgziitupi.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaxhapjx.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gtgzydhveu.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxidjyhr.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtzgjzqwxs.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtoovarnyu.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtpuuirifb.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gtpcundlrf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gtfgzdmmqd.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gtayevzmqo.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtdxnscchv.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gtcoipaghb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtwuwohmum.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtlibzmnwy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gttzmlucwk.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gthfeotrrl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gttachdkvp.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtzmhrtmqr.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtqyfuuiri.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtdgeaqqwe.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuiewddj.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckrwxvmh.html

do { try f() } catch { print(error) }
来源：http://dali.hnxiangtu.top/Article/details/gtmwpynzap.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtiitjzhkj.html

enum Color { case red, green }
来源：http://dali.hammf.cn/Article/details/gthpphhvci.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtofeqomod.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtyfaafxox.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtdtotkkae.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gtjipisdbx.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtpdftjjwg.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtieeovdzs.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiprrccx.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtyzcdtiuk.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gtxytvyhfb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtzbkfpgya.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtofbwbwqx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtipnhekko.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtinzzsqfu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtffwprvsu.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtaxqzxyks.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gtbsscdpim.html

[T37] Lua：字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtptqzpces.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmkxjyim.html

[T38] Lua：条件
来源：http://dali.hammf.cn/Article/details/gtjqfpekxk.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtyehyzjvm.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdzckvys.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtgdfhctso.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtierahwnh.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtjzyhrgvi.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtcjjljoed.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gtsykrhvmu.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gtdlijntbf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlioreysr.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtvflcpusw.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gtczeesaga.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gtmunpioxd.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtfaoygreu.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtsjsflkrh.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtptppisoe.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gtxlgmuudm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsodfvqz.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gtwjolgtox.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gzhubu.top/Article/details/gtmtcwxujb.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gtmkyyywum.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gtmiszxkiw.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtsgsjvmnr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtdwonilac.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtvdadgbjj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gthaepznqj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gtzhjkmspe.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtiktsbhjk.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtrwljslsz.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtpctmwglx.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtzfqnfnca.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtffjlitqn.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtzyyywpjf.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtwtysahqk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtihjxuxrm.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtuheetbdg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtmrlcctxe.html

[T56] Scala：样例类
来源：http://dali.kuanghao11.cn/Article/details/gtwkpfbtzc.html


<!-- 参考信息 -->