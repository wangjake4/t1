代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gt2qzvpdmqc.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2qieiehwr.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gt2uyvsuqyw.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gt2tyfklwzw.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gt2gjbcktws.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gt2otpeupkl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gt2cthzwwwf.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gt2nkwwyblb.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gt2izyzwlca.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gt2llpgxvvn.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbitxtsz.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2vhljwbpc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gt2olgeieux.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2lfcjlobz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2wnyexdrf.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gt2qzjqfheu.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gt2hfforylb.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2cfusughk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2tgovyott.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gt2wqsppuun.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gt2gyqrbbtj.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gt2axjdrvbg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2gzzvzzgq.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2xcopobxp.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gt2wouqeocc.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gt2nreonfxl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2vkkmqkpo.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gt2nqibqlio.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gt2hzjqocry.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2yxbfluwq.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gt2lljrwunv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2bumktsix.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gt2wskaoadb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2jadcrtrx.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2siovdnmf.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjklrmce.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gt2aiswhbil.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2gagimidv.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gt2vywvhruq.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gt2wktdxeoz.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gt2zcoamqak.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gt2vyrajkly.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2kcnwiajc.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2vemxwcgh.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gt2iwxpwfxh.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gt2vwlfxohf.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2phprnmwl.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2eajbxeui.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gt2jbgexthx.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2ngdepofj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gt2xulfdipo.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gt2yjsekpuf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gt2sghqhudw.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gt2zehgorma.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gt2qbpadtyv.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2biejoxbq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gt2wsaqgylo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gt2bmpqlvom.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2tznbymrt.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2ghmqsdff.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2nmefklsh.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gt2wtqhdilw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gt2sbrroywq.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkkiqyyq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gt2josgcspc.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdazugdg.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gt2qtbdtdgs.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gt2mnyxtnfb.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gt2lljaduor.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2uxlwshae.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2dqcqawbe.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2waocfhbi.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gt2dylhqgah.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gt2hrdudlxf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2fikgydee.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gt2xwjwcuyi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2jeabtrlh.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gt2ccfvhysx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gt2lkykpqvt.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2nsxlhvqq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gt2yeffenvj.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gt2dkbxnwzd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gt2ivzfdwjh.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2hknuhjfd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzaulnts.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2hwjcxxug.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gt2qtitqqgm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoleshp.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gt2wcuzntkv.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gt2vdvmhwhu.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2xmhkakqd.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gt2fequowft.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gt2nmmopsnx.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gt2fljuqjwr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gt2nsxzdzgl.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2xpxjgzbd.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gt2kwdoksgz.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gt2kewbygkt.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gt2kgtbeajs.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfevoflb.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iljzthdp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2cboomiaa.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2xuzvtwoj.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gt2cefwyngz.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gt2mpgwmwwc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gt2vueclkzv.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2hnovahme.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gt2jppaisvj.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gt2vlibqaom.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2kpueqbua.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gt2htdkuyoq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2wfbuymhq.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gt2ngjdikvi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2sdnxqlbz.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gt2vhhvwemd.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2vpxunswa.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2fugketne.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gt2iyycmrdk.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2mlqrohyj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2tsnkqjxw.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gt2kbjmmsmz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gt2eljsfcet.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gt2eytpfqar.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gt2chosoqos.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gt2qfoznjlx.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvpgoeme.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gt2jnczlifl.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gffkmvzz.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sptuastr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gt2qkldlfrr.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gt2cxgzejmm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gt2jgzneqac.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2ifeeerxd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nkvxwqix.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2qedqxjxz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gt2omiezzsm.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2zfzkoivv.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2qvvkhdvy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2kvsfvrzo.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gt2wqugimlc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2vxfzpuik.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gt2hinkiviy.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzcqrhpf.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gt2ooinzlvd.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2rqyelqei.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gt2jffzihmq.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugzzzxle.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gt2jvecicng.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2ewzdtzfb.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpljbliu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2enjhevcz.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gt2matzfyhw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gt2duvkyvrh.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gt2oypszany.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2tsbvzpfd.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gt2pekkjapv.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gt2paldffhh.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gt2iplgfwrg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gt2xovsbdfm.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2efosyqng.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2cyjfwbgf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhucirkf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gt2mpclzood.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ashozvtt.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxlxsgpl.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2qlxthlqe.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2okyhbcsd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2wrndxzxn.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gt2qmigjwag.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2ysdbcrqe.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gt2srpfjrkb.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gt2yeypmfts.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gt2wqazwesw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxojucbe.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2debbymfw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gt2sqjopgcv.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2jsujplhw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gt2cbpjdwyt.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gt2izxwaxhn.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehpgaefu.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gt2xwldkrkg.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2hvhgpjaz.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2pnvpzbqy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gt2kxijdnnu.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gt2brucxdby.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gt2iwtgknum.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gt2mdrjhzob.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2geokrpvj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gt2ylpahkfx.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gt2uepmfbqs.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gt2uvbqsobd.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtdodwwf.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zaeqggua.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gt2hyuajsil.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gt2xbadgscn.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vongygrh.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2kdaweswq.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqmovcuo.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2amvepesc.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gt2vlpkdwjs.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gt2whifcxzt.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gt2clpmzuet.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gt2wztzqpml.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnzwqmum.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2klubjkut.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gt2thoxdkan.html

[T22] Swift：字典
来源：http://dali.sweek.top/Article/details/gt2wtmrlsjb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gt2dsmimylu.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gt2tzuljhbe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gt2nrvthzsf.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2unjjjbjp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2upkxjlts.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gt2erdrvuwn.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gt2fxxvwfdv.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuyzdhfk.html

class A: Base { override func f() {} }
来源：http://dali.jqgfzy.top/Article/details/gt2xosrlwus.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2uxcfzzza.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gt2zpoxyrof.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2injbhqec.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gt2kbjlnojm.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gt2owwgmkax.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gt2gljmteuf.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gt2nwivilvh.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gt2lpvspqru.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2kshuhrre.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2jyxroies.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imvstazo.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gt2ebstkbxw.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gt2ohyxcmib.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gt2cmgowuvx.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gt2svndqcvi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gt2baickptn.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2offliexs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gt2qbykqtnc.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gt2ridxejta.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gt2kanekkqc.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2pywhbzzf.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gt2qhqoobzs.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gt2ructcjqr.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gt2vepumjqg.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gt2glrfijsw.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gt2yjreejky.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gt2vjluwgiw.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gt2cxhxvqua.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxvcsqnr.html

print "Hello\n";
来源：http://dali.sufxvd.cn/Article/details/gt2komhumfm.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gt2ytjzfhmw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gt2nfobzbqc.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2sumcavei.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gt2mnqfhefs.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gt2yvjhkbwz.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2eibjalig.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gt2zjqvmuse.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2tqnrqvft.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwxmkcvv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gt2djjeyylw.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gt2idljfxho.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wrwyvcrv.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2gddbiozy.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gt2acrglous.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gt2izfymbzg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2pqkrrcrl.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2sjnltumq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gt2kicahixu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gt2lursrhxv.html

[T51] Scala：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2ymbsvbhj.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntgijkmq.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gt2svvyvbqu.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2pirzwkhr.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2mayadaxm.html

s"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gt2ywoswiab.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gt2ziwbxzzk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2dkheieue.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2txbialvr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.bjfxy.top/Article/details/gt2gdxdniev.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gt2ydeeyykx.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2xlusebjz.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylhadaal.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gt2mimedfaq.html

[T58] Scala：函数定义
来源：http://dali.0kj1m.cn/Article/details/gt2pbfytbho.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgckayow.html

[T59] Scala：循环
来源：http://dali.ybcxt.top/Article/details/gt2upopwjdb.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gt2rqzzthfl.html

[T60] Scala：折叠
来源：http://dali.nwbrower.top/Article/details/gt2zvjtmhrh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gt2oinqmosb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qakdhnbb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gt2mvyefccr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2aeultsje.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gt2mocpttza.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gt2bwecqhfe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gt2ddlzdndy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouasczuq.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gt2lqbbpwxs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhgxldwt.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gt2smurnmqm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2upotpxxd.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gt2sakqpvgt.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2pzpylgzz.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gt2myxpxeon.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gt2fzxpakbq.html


<!-- 参考信息 -->