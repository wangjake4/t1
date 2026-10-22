代发 wailian999

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccvvyduq.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2qzytjfpu.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gt2xdgvhjhl.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gt2kchmherl.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gt2txosfyhd.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gt2vuxejqeq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2lndogugu.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbezlspl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gt2nuepjsmc.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gt2ersovcvl.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gt2iumnuhsw.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gt2qosoopcz.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gt2qhdlbakc.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gt2rdvridft.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gt2dofdkxqn.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2ieflhhet.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gt2mdudzbwl.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2dsmizrkq.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gt2iskedldp.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skhbkbkt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gt2zmhrtkiu.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gt2yomljbpc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gt2bmsnsbor.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sleoyczv.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2bzzcsowt.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gt2wbxqgyga.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gt2djxvrbam.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gt2pzfkgdww.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gt2akltexas.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ordthrce.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2zvqhvkre.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2qvotxbfn.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gt2ybwrsxxb.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gt2kzfbfjhy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gt2xhmqzliv.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gt2rzdjabzu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gt2zdfphvrv.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gt2tvrztbki.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufvealqh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2yendonqu.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbgyxnvk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ccmmlrhu.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gt2utxjfrjr.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gt2gehmyior.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gt2boqnlgzm.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gt2kcnhtxir.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gt2truahrfo.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gt2yggryksa.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqzldnjn.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gt2wdrnvisx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2dgzbsgek.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2nxjspeex.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gt2gdnvoyum.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gt2jiawxoxm.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2tjsyfvsz.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2crzdinxn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gt2nxnkkitp.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2dtydjjqo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gt2ochuzglm.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2uokfiatx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gt2urcbbepy.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjwuiplz.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gt2nidmfcju.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2najrrfwc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqqqjizx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gt2yakpltfy.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gt2vzyjpqhn.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2urfalvac.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjcgbtyl.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2blbakgxz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2dgsgmrwu.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gt2jxswmupz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2tixvnilo.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gt2gdeaeouh.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gt2qalgwlcx.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gt2rzpvphln.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2latnmhts.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgsltfnw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gt2atqwmavh.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2rwamvfnr.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gt2mwyetudx.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gt2dseqpaaw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2hfydlawn.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uszjjmjd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2emzmiyiq.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gt2ptkqkuxr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sswgrqqy.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2ruxovzej.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2unkaomfp.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2zizlejgu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gt2qiftmawm.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gt2pthbrrzt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwepypeo.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2phvapuoq.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gt2kkbkvrik.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjblegbw.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jopxomsa.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqzsewrg.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2jbbmmxbc.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gt2yxtnqiaj.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdyxapag.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gt2vnhaggii.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2vfpnsefm.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2zwpcrauj.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gt2qgsptict.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbiwtnhb.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2zcjoetnz.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2uesjgvhs.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gt2kuyhmgck.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2fkliqhqm.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqdkshym.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gt2kqgmlbgc.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gt2zsawjugt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gt2puisvsdg.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gt2mtuqrcnu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2aykwosrk.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2uuxcjeol.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2fexhbrli.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gt2zszpmwfb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2olnmomso.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gt2uhvdppuz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2meyeimvd.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gt2mkmrscmx.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsxddebq.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gt2wxdavejn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmpzguaq.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gt2hwqsixyo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gt2oawfrbwv.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gt2futebifa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lttwydsj.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gt2uhkmxrgc.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjgutjqp.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gt2kvijphig.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjrjmtez.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gt2llbbbjwx.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gt2vlxudzqf.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2tbmfbwom.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gt2grlkrbtl.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gt2psqignxf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2piuorfec.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2tzivrmlt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gt2cucuwxaa.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2cogfufzg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2fvlmiwoz.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvzeywfs.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gt2ciicccty.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gt2vhphnrlo.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyfnssor.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2ahrpyymb.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2xseauhol.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gt2xzyfngtr.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwlvohdp.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gt2doycbwvv.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gt2vrqnunvm.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gt2rycxfwvy.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2pyuwkmqv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gt2iaiyvbvq.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hikygdwg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2fmeabgxc.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2kiqwesfy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gt2yswoelru.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2bvsjfbij.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2ozsoxsgk.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gt2qzuxrull.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gt2ooihuxrs.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gt2nzmvmqld.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gt2xghnczce.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kauvwnol.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bymcbjov.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ndgpimbu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibpghfwe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkfbtgar.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2qebpbyed.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2owapejyn.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2xejkqovt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gt2sjmekgol.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2oawclpht.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gt2ttzmbult.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gt2dqhrpmvo.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gt2rjiudnqy.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcaicgvn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gt2sedjwqea.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gt2bliatnvi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2mlquwmim.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2bkwiwuae.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2wygqccgm.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gt2kwylepqj.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gt2hqrypixj.html

[T09] Kotlin：扩展函数
来源：http://dali.cheryme.top/Article/details/gt2xsuoaori.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gt2lcjymaiw.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gt2hxuauaxu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gogol.net.cn/Article/details/gt2ejykoejn.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gt2radznlub.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2acdnmlku.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gt2umlwzghn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2dtfahztj.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gt2nftinbmp.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gt2qqowpeni.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gt2atjuouoz.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2bushrzag.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gt2ymmgjlmt.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gt2uiokneip.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2kqonnbrc.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2jraivqum.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gt2ydahungv.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gt2tguwfaho.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2epbrkgvp.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gt2iuyxqnxf.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fztwiosy.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gt2oxcucsuc.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gt2mkwuxnne.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gt2alnydaea.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gt2jgpsnupl.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oexrcerp.html

[T22] Swift：字典
来源：http://dali.zhongyouzk.top/Article/details/gt2pgpclruz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gt2wfiaohar.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2smoawhsk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxdywnxt.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gt2qwswgral.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvtrnfjt.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gt2xcnldlvf.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gt2zfmayexl.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gt2kpjjbidg.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gt2pahyyvnk.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2ftyqlkmr.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gt2mxhybgdj.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2peaarqvw.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gt2dcnplhgq.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gt2wyvywmcx.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gt2zrcfazqp.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gt2sdspyjub.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gt2miibgfmz.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2oljzuxgr.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2kyzkjuxn.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrxrybev.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gt2zdojlkzj.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gt2ovmxtpud.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzathmti.html

[T34] Lua：遍历表
来源：http://dali.yongpay.top/Article/details/gt2wgxlgeeg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gt2etvemirw.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gt2sriuuyrq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gt2hgvukkaw.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2mkzncifh.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzptyuoe.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2kiavoucu.html

"a" .. "b"
来源：http://dali.gaohongyu789.top/Article/details/gt2quffipsp.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gt2mokawmft.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gt2cebztulm.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gt2qhiztppi.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2cazwrzju.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gt2ottrkjqa.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gt2ahtegdsd.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2hocsjlws.html

print "Hello\n";
来源：http://dali.zhengqikj.top/Article/details/gt2oqpdcgfi.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gt2auoijdev.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gt2uelrjpyb.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2brskmime.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiapqeal.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gt2mhyzsbqf.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gt2lvevcxol.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2unotozbz.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gt2ysoyxpcn.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gt2dqyzcnxa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gt2ctetmkdm.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gt2xkmpzipr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyggokpd.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2blmxzxek.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gt2gwjnskpq.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gt2suqvfjdf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2esmtcuct.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcqgnvv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gt2nrdcsztd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cpwkqmdy.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2pfotuarj.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2vawvrfbt.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gt2gnywsaku.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2amysjbmw.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2etqrwhcc.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gt2nrcrbbuy.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2yggyvukn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2gjzdimcq.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gt2frfiatsj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyqutpvg.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gt2diqdplvm.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2aoiwcwpg.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2udaijzcc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gt2fcnmaefs.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gt2oyflnsck.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gt2njgfcruv.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzpszirg.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zijusjte.html

[T60] Scala：折叠
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwdaanlc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gt2furkirul.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2toavybdb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gt2eycroapb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lhfkjeri.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gt2hdulfbmy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gt2gjjsycdf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyfldakd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gt2mhvalntb.html


<!-- 参考信息 -->