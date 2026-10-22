代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtahpbuynp.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gtbwcwswvt.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gtdgpvdpyl.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gteylzelbs.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtjrcgsajb.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuxzblyp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gtttnkrwsg.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtzhazgcva.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtgvyczhvy.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtmfoslpgs.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gtudfmudnj.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtgyltfywh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtbvtbukan.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtwyvueeth.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gthpxezffh.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtoojcqnxb.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtaitzzyhu.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtfgbrstxa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gtvttllpad.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtxwnzhcwo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtblwxeycg.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtptrtwnau.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtcckogxzc.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtwnvwovdh.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gtmfkbssqd.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gtpdepvuuf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtlpdjlgqb.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gthhpdmahl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtbxicgkej.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtgrvjlrwi.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtaaolrftx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpcrhzpg.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtviicvsem.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtiucbgqvv.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtypipbdbw.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtqoimxngw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntyklhtw.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtoxzewoug.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gttccitqwt.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtimezvfoi.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gtbpnldnlh.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtdlvppqte.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtazwwyihl.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtuytzwxaw.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtmtsfakme.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtlscdrvlw.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtjhfvvfjc.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gtaszjeaao.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtzhixvdnc.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtlnzbston.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtnoqcarrw.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gtilmqambg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtwghaqrpw.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukgoitaa.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gtelcehdly.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtegwakuqs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gteybapwgv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gtisguiays.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtpjpoffex.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtxlbxqvqs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtyowibmsu.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtzifxagkw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtqltiucdy.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtgxwlqkpa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gttrwkolyp.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtltehyspt.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtvfwhtyro.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtgpaghmhv.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtosbemlbe.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtaqtnvuaj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtekoraiai.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtuagffkke.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtfmeyvcls.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtplqqgtsv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtanrjcfiw.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgdhqaeq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtxnifgmfi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gttbjmcxvw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gtiqelaadj.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gttcrvewbf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtramazypt.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtukylvbxw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtfczsumro.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtwnaatjpu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gtejkeobkz.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtpbucahgz.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtaughbwoi.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrswlkdpn.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtzasqfuyr.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtxouvrgbs.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtldjesqsj.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtssgipold.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtvcmudfcg.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtxquvhtma.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gttukuykpk.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtdkkzjbhk.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gttjbxqyei.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtqjsekcbt.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtpgftdsqi.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gtdgatpgnb.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtiangovyv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtwrxkcugg.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gteoqrkfvn.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtlccaolja.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtevocmgkf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gthfxvewai.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtbqxxrhrf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gtclvuvuwt.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtzljvhmsr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtzjtdojto.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtgslnpzng.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtbhqdjwbt.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gttsrykfze.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtlijbvzuu.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtkodnafma.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrmxzyhu.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtvurpvzvc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtrosuokog.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtwhiulypb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdihrgth.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtlogrweaw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtqhofrdrn.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtkvvhxefy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gttqvjagyk.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gteyuuannr.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtnpotashi.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzdnrffc.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtkulvwkjs.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtobgrxzus.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gtpaypdiev.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtcdfcxfxb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtxqnvoqlc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gtmskwyqpc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtspxgimxz.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtbvrfghyp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtkvshnczy.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtsxsqcrym.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gtiyknnbsk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtgstjgmmf.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvlpokvp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtfmlsfmur.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtwjcnlttu.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtnjqqwraj.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtqzqvrqef.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gtboohvuvs.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtnoavqvwq.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gtkntwmcbg.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtmlctrbop.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtdtxdlhjn.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtwriiyluo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtzjhwjvgn.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gthdvgcuxf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtunhjpldf.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gtztdjbqfu.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtfzkadogn.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gttdpyezvp.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtfetriauj.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gtzjhjrdci.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtwiqyvrbo.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtuqiqyhcx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtazhwebgn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdjgoyga.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gtzcatajnj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnccwptkq.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtfyqkdhtl.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtpmryzrro.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtnrddwbab.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gtokhdrewy.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtdnjpscez.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtuanayvyo.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gtuytwvaxy.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtnitytjch.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtmhenlmax.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtheirdjdy.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtqznpmfoy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtmwzpaufm.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtkjbsoifm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtyluogwsc.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtmtwrjujb.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gtsrkyrhpk.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtszisggse.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwmjadei.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtwvdhuyea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtewjzqrxb.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtialqfiqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtsftrmwyj.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gtwasvvfys.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtwtmirdkn.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtosorincp.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gthpzjcvhf.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtjtpdplbv.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtggpbsgbj.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtkycxncbx.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gtzdpilavk.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtzalpwbgp.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtydfaxoui.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gtlcawpxan.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtxgajkpdn.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtduxnnaqa.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gtsfcecllj.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtwiudxrny.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gtltxebtxs.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtyxcsdpja.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtafnavxnx.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtxhfglfku.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtpysuecay.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtxoepptbj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtsrpwgxtg.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtabnnggon.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtornzrnhs.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gtahkjdttk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtaziygezr.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gthtgsfvsw.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtgykuvtoo.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtyrqnuzmd.html

class A: Base { override func f() {} }
来源：http://dali.hammf.cn/Article/details/gtxrjecinp.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gthfaoqebf.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gtvpulgcrl.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtralwwezf.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gtpleiypth.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gtoipfhjck.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gtctwiftby.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtlwlsqsda.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtlnnmzstg.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gtujvpqlxp.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtersrlzyi.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtxqlziroi.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtuhxkhlrx.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtgwyfjyqv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtecmiyrie.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtnhgqxzpg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gtksrpnboc.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtkefqokha.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipfyynfx.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gtdnbhtqwd.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtenecgtmv.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gttfpoiqcx.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gtbosjbcyb.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gtsoduwkmb.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gthcayyujd.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtobohtndm.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtxqwnquoo.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gtdgejhrmb.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gtkmwdhozz.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtaqjjcynv.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtodsfijtz.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtjlppxmuj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gtjmpflkrs.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtndfkullv.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gtzfrpewyw.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gtgyvnfcem.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gthoivvvpe.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gtiicqpsdx.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtvoczblza.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtfqaozzic.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gtvtglrfiy.html

[T47] Perl：正则捕获
来源：http://dali.jyoumei.cn/Article/details/gtkifgsozb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqynityv.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gteczlzzsl.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtlbtqzjip.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtfkbdrzyl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtkeysifsb.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtwiplohwo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.meibo888.top/Article/details/gtncllxhsf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gtjujbyszw.html

[T51] Scala：Hello World
来源：http://dali.yj20258.top/Article/details/gtbhlicqwl.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtxagqaklx.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtkqrqzfwh.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtatbrrdra.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtuzmwvmwl.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtpvifnzch.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtqkorazcj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtlxinujbs.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtxkhcxnef.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gtcafpdovm.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpsqpyxx.html

case class User(name: String, age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtgynuhwyk.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtrqylxsxy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtqkjegyto.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gtxwjquhhg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gtnqdbzmft.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gtbzapzvhk.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gttefahrrv.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtneohbldu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtfahragvr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtslctgeam.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtfpvkignl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlidpiodb.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtfzptffts.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gtgluevpbc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtaenfuyqo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtzmjbcwus.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gthjklcbxw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gtotkqyxei.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtvvaawtvn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtbzpnqskh.html

[U05] Py：列表去重且保序
来源：http://dali.bjfxy.top/Article/details/gtklfemwks.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtwapagnya.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gtzbbrnaki.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gtcrzpwjso.html


<!-- 参考信息 -->