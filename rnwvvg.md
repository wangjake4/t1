代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gt2kmlwtmkx.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gt2ydflsbwg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2rtuqtpxw.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gt2ekvyejqu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gt2mlljvzbj.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gt2nlgzgkrf.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gt2goevintm.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gt2dhqgzdfl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gt2wrjjwelr.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmajlqjs.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gt2orlwzzhk.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gt2kturgffv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gt2xlgzztiw.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gt2lyyenhdu.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gt2ltmpigsn.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2sppvhukk.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gt2supiibjr.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gt2igkhymkv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gt2jqyojnuk.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2hiheyokv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gt2uvcqsons.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gt2fdcrsqui.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2yhjdtrnc.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2dzenqdtu.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gt2xpnrfmrj.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ldmqdrkr.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gt2okcgtzfe.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmnkrzys.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2seyymadw.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gt2goooyesc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gt2tulnzmmv.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqvcnmjv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufpfumbp.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2acoltehf.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gt2jaysorjm.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gt2nrpeztxq.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gt2foaqccrv.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gt2bunhkhya.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2scyydxjh.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gt2sufxdcoe.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gt2mggelipt.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gt2fdadndpm.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gt2zrzddmqi.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2rqheammd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyhltumy.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gt2rrvgdcnh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2btcsdmkz.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gt2rudaighn.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gt2qapnwvux.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gt2mhakauuh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gt2bigcfkkh.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gt2ftfocyoq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gt2jjndyyww.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2fiyapgsu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2xckgpmkr.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvfpiwgk.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2hmkaqepf.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gt2hhkartyv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gt2sbqsxgkx.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2iwtijvso.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2pdjzanfd.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2bogpzkxy.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gt2pulgzrqc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2wenbddaz.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gt2xurogpfo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2rvxhdmkn.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2djfndvxy.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gt2ihzywiet.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gt2jqisqdje.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gt2dvheinru.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gt2kukaniej.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gt2gcjnqxgi.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gt2ihkpivtw.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcdhgsjm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2dpvfusma.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gt2xjnwtkww.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gt2uswogmxo.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2dghkrfzj.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2sixjantl.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gt2pfnhlpsl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gt2alnyhpmn.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gt2yvimmswn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gt2ltefmarb.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svyvutun.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gt2sozvbixk.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gt2hcunvbsi.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtpetgse.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2eghmtzdz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gt2oiuukybn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2mhuuycon.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2fdupqqks.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emkaoweu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gt2eyrbdqfb.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2cqmxakzk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gt2cnaxlzet.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2chfvyurx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gt2yyirmclx.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gt2tdulvpwa.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gt2wdnpxscs.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gt2qqqagzsl.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2mttbpdec.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2vsargnhq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2nxmzkkdk.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2gqbkgdvk.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gt2qehtduyb.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvhpnewl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgldwbut.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gt2yvswsjfh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2ixvjozbr.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gt2awvykbve.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gt2rhgtnsmd.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gt2cdyjouwr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2rswqijrn.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2radgwzrh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2tjkpbnxj.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esogsqjp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2cdilrrag.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgnaxpyy.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2jceznkyk.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gt2hpsezjqp.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gt2enjtlqaq.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2rffjzdeg.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2nryjoiay.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2tsbylbbp.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gt2bcryrcik.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypxiatdh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gt2dozxgqcx.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gt2enoozqld.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gt2vjjgxrbi.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gt2pmbryzjm.html

#endif
来源：http://dali.xylfe.cn/Article/details/gt2dpefwawc.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqtfkiyh.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gt2jnntxlsd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znhjjqke.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqjszzpi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gt2etwvsluj.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2dvkhecgu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gt2cjpokida.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gt2pehdgujr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gt2hobtpmpl.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gt2ebhlesqr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2yitkghvp.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gt2blzjxbim.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2qvgoqzzt.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gt2fsgcrwcm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gt2qjtwmntx.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gt2wvrhdffz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2lhjwoqyz.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gt2ifjvuckt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gt2cvhmdrrs.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gt2gpeufibc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gt2yhriuabv.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnoaoheu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gt2yenohhtw.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gt2dpocpuwt.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gt2jkbkophg.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gt2inzvntyt.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gt2yeiunznd.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gt2zgnbmybs.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gt2cvpievvl.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gt2rdddudju.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gt2imtuagiq.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2hllzcuue.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gt2jvfttges.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gt2hiptyiwg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gt2asojrjwi.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2zpfperrw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gt2fkktoxut.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2xgqohsdd.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2fcjwqhic.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gt2ksjoezug.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnmergnc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzonqmei.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gt2dlmhdhwg.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gt2gvoypbac.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gt2hrakwhzy.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtbkyvpi.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2splrvplx.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnoakdgm.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gt2tiwjcyty.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gt2twpaacuq.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krgwhrow.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gt2ddmlcvav.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gt2rqogcpfp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gt2bgtprhwg.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gt2bfopejhu.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gt2hadhewpl.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gt2lxrsnlja.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gt2qwdxzdlo.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gt2bqikvktr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gt2tzmcxuzd.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2quorgaeb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2zayyuqxg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2wpzcdvfe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gt2ukrwoowo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ndfyggyr.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2svyrimva.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dugvufxj.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhiiszvu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2zkxggnjl.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gt2nuzztrqm.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufkzvsqn.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gt2pacccody.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2oumhkjge.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psljerzv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gt2xqbomdvb.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gt2wtxhpcsa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gt2uyfsecug.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2tveeyklm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2sujtzmov.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2obrjqqcs.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2mzmytzxr.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gt2vaoooteo.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gt2feutyvxt.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gt2gqgcenqr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gt2rurmsfex.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gt2sesbbgir.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gt2ldaqykwu.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gt2bbphfhbn.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2rggsrmvq.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gt2bjeoqmsx.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gt2ugathxfj.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gt2taflvxxr.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2qhbpieqv.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2bdclqqrx.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gt2gfknpmtf.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nldpmoud.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2gkujwkqd.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gt2myyquvid.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gt2wiosckcv.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2sipjsjdv.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2krnumsss.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gt2pluagviq.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gt2gbcevufy.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gt2tbnslgzi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gt2guulfhdw.html

[T21] Swift：遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkpmdudo.html

for x in a { print(x) }
来源：http://dali.yj20258.top/Article/details/gt2uuszugyz.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gt2dvjqjomq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2yebvsbil.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gt2oyotmelz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2ozhunzju.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gt2kdeaaryw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2dnxeughu.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gt2lsvajrrp.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gt2vpvrjaik.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gt2mwttoefi.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gt2hazkcmzq.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gt2vbyyamgp.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gt2hupyseuy.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2oyodpqhk.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gt2rexnpfqp.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gt2iobfyjrp.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gt2jcsdiqun.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gt2vznwlewk.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gt2wbnpahco.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2cltkumwq.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2dxmrfbum.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gt2jvzrpbqv.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gt2ucsalosn.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jebckwxx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqmvljyy.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gt2mqocoash.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gt2xatdzjns.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gt2funosiru.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2yfrzzhnm.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2xjiikcpl.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gt2tjhbjmcl.html

[T37] Lua：字符串拼接
来源：http://dali.ybcxt.top/Article/details/gt2wtrthpnk.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zttpccjr.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gt2ymhnhewv.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gt2rcmsmrsv.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gt2cxareleu.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2ejlrotty.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcmefisi.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gt2emudsrpu.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2wqopruuu.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gt2duranogg.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gt2xgosqoif.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gt2lqsgvcde.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfghexdz.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gt2lieqfijr.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gt2rudjhcrs.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gt2icsrroag.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gt2udnepwpf.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gt2pnyfkdhh.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkhbwndt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gt2dkozvfsx.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gt2ghisyryj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gt2yfxjgxsr.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2fmspitos.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gt2bffqbbqt.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2vzrqzcpk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jqaijyld.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2udbxywrm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gt2xmzibqco.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gt2jtbyvzvk.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2qcsonlun.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2qyfvussq.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gt2tptxvpsh.html


<!-- 参考信息 -->