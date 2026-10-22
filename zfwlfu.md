代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gt2dtjisvpt.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gt2bnhgmpfh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysmbgpxk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bniluknt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gt2eqqtlkbs.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gt2boashraf.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gt2xmqtnsqv.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gt2xrolbgjf.html

openssl rand -hex 16
来源：http://dali.guannengcc.top/Article/details/gt2ojsonsea.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2yxamgcjk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gt2rkoyitgl.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gt2dqiotiik.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gt2pnpngssz.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2yezgqqph.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gt2zrpjbzjt.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdjaxbbm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gt2plciipgo.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gt2szqnwxux.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2bqkquwlk.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gt2lqnzwtyp.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2humqidkm.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gt2tjtgvcju.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gt2pklajhmc.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnacrqzd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2huhsvvtc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmynjln.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epihzbyi.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gt2gzwjfwhy.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gt2gsvtvbgm.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gt2sjazcdzb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2iamewsya.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gt2umsfaaed.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gt2rrdwpjlm.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gt2tudeodgj.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2xcflzith.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xekxuhiz.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2dqcjvbyg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2jykuvrno.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvwdoizn.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gt2fsgrcgco.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gt2xmqmcicg.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gt2mjyqibxk.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2aaqbgwnt.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gt2mflcodgk.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gt2veabilup.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gt2ypyfwltt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2krhcoqwt.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffprrdoz.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2cmqiagnv.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enmdvmqy.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gt2atgemouy.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2hintjwrj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzmbmikd.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gt2mltmfprl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gt2einzrjgt.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gt2reegsshr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gt2ugxsdaqv.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gt2wewhtkwq.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gt2ylsglqgb.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2rggoqviw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gt2wnggdfeq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2cmoabpur.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2yaerbdxd.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2mmdrjoor.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2ddepgbik.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2rflmtbmu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrzixecw.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gt2trkftmmq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2qwxishuz.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gt2ftnvosnk.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gt2fxwrbfbe.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gt2menbbiel.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2lpxbfrth.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2rovuhenn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gt2djzzqalq.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqnosftc.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gt2abzhenij.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2spdxjucx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gt2iabhepvq.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gt2twfemnhd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2pdcbnfys.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gt2mdmuipsm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2bbqdqdox.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2gongffvs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2rhbptbjy.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gt2ogipdxgp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2pyexkswj.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gt2ubizixyi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqycgxxr.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2vrpkijru.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gt2mdvzckjg.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gt2npmbizcz.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gt2ijqtekmp.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2mihpilid.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2tnfnrhby.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gt2bmuydzhd.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gt2zzkrghsp.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gt2phqhltwx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gt2kevqjkxp.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2zoxiwwga.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gt2rirfjdev.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcabxpgm.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2hasxpias.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2xgkpqevc.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gt2yaxhxejc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2zkxbreel.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2sdtfztpe.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gt2udagnczi.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gt2phgesilk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gt2icwluvrc.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gt2muwzugax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bowuahdp.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gt2oflkrral.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2uljtywpq.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2kcsnyygy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvnwghdd.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gt2rqjcglqn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltccutuy.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gt2xdemvmqi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rclvzhfy.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gt2owtdcssf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gt2pxsjxfwq.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2bgrrtbon.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gt2vpflxbwu.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gt2yuxdituh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gt2ikkdmlsx.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gt2ldlevhzu.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gt2ukjwayzc.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2hwkxjwep.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2pmsyokbe.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gt2kqnooyjc.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2znxijbip.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eufsgyyd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gt2rsfwfpwl.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gt2ikwzuroo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gt2nnhlepga.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gt2muxsiwdn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyeshsqr.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yiaryjpv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2hcuqaiwn.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gt2wdxfuaxc.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2mamooptv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gt2huzczkaf.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gt2xrnjevwh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2ntexmeoe.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2snhprjnk.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2kaxxfuxj.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2qmointtd.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gt2wmolaxdf.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gt2ahsklfzz.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqutrkip.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2imssichl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gt2ajuebpog.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gt2qpbehnmb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrtzoxfs.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gt2nfynglkg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gt2tzmzquly.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gt2hcwpxuln.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2eiakzmmi.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gt2mrabofyr.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gt2ojbwjrze.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2gargeukt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gt2vummacah.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2dtcyjxfh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gt2acfmkcla.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2sqgskiza.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gt2mdzgyiiy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mjznqhtd.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2vmcodted.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2hdkijbxd.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2qdxfhpcx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gt2hzagfbeq.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gt2evkpwtme.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2nudhioff.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2iguvktti.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gt2zakzfppp.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gt2oppnoqsx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gt2vxzyhhsb.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gt2mpsqymxk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2uorimqtt.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2buubrxmb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxaedaty.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gt2algopkzm.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gt2ajkdmkkv.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gt2xoajqoro.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gt2fmymdycj.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gt2xwamzdon.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gt2jbzztpjf.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gt2hxelmgnw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yonumen.top/Article/details/gt2xiognrsj.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gt2rvylpqnz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2rpzornzz.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gt2dkdmwexd.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfzbxoyj.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gt2jxeozjrp.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2wojojbra.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbozlwor.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gt2pisotzpq.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2schuyhft.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2cwzzxyxn.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gt2ducohgrt.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2vxaeiahk.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxzubecn.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gt2dxxinjbp.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gt2idguilfm.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gt2nkdmfrtv.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gt2ilxobmes.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gt2kfxycogd.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gt2bjfqeddo.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gt2rdejgqka.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gt2ayeqyrjz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gt2yhojvqla.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gt2apkpkqnw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wznqnevn.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gt2tvjitvtx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2xtbjaddd.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gt2njbcavco.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2abezbtoi.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gt2plgdnbaz.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gt2keotoyjv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mycotxuq.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gt2ywcvmgus.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gt2mxgxgtiw.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gt2wmcfprtc.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2unxxiatf.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gt2woibxgfm.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gt2drniozzm.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gt2ktnlrkql.html

[T31] Lua：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2mwphckxm.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2nrbbvnto.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gt2pdjkppfd.html

local a = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrqjcvhu.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2idhvxcno.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gt2zntrehwy.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gt2ysumopug.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gt2vqmtmuxh.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gt2rxjihhnh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2ktplozkz.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gt2otzlexfa.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gt2ambyddyt.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2bluphpeo.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gt2oaquhpvg.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2pirytjon.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gt2mtdkapvb.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gt2xoeqolkj.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gt2lirhxzva.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gt2lysyteae.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gt2gdyxgfef.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2vumsdjml.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gt2ozrwjluv.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gt2dqvslafc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gt2ogtdcqzg.html

[T43] Perl：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2kbtjuxjv.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gt2gjwoowjs.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbfeoklz.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vokbcruo.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2txdugecc.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gt2cyxotjxb.html

[T46] Perl：哈希操作
来源：http://dali.zycfv.cn/Article/details/gt2wdgksful.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gt2qaierojs.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkeajccj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gt2niwomikb.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2inranuut.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gt2ylvfager.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gt2ylufilay.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2pzdwdngq.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2rwgryfqq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gt2kgaypqqx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgfzy.top/Article/details/gt2etyuqzcu.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2xntcsdeo.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2yccrytsf.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gt2nnupqnng.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2jofjfaiq.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2uyfynmxw.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2gxtkxqmf.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptcbsosh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2iogbsxlt.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2bkjaliog.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gt2dspdtxdr.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gt2upxiqxln.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2fshjseel.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2dhwjodyf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gt2eprrncwr.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gt2azgsdwlj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gt2rfnskynz.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gt2mdyhqeex.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2wesczdmn.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gt2otgvtule.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gt2nvjeclpv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2bkwlmipt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2bovvspie.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2debujxxw.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gt2wnjmetfe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gt2zlflrnzn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gt2vgzlyqhr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2wtfsqcvv.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2wqyhxfvb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gt2nhjymlxb.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gt2aaizfklg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gt2wdvyzgmm.html


<!-- 参考信息 -->