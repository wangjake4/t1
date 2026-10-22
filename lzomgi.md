代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gt2vihlxpca.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2srrrkuuk.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gt2fnuuwykq.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gt2zxuoxrty.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gt2qdxrchnv.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gt2tkqnkucs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2fkgxzrog.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2cisuliug.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gt2ajnquvde.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2ckffrass.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agqrwvub.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyvgqurd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2eayvufvf.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gt2nhvubnct.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gt2ceswjvqd.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gt2cpkkzwoj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2tggjpgoo.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2vptmlkkl.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gt2nlhpivew.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2ztzvjqcq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gt2wjxrshnn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2pgxjjdzh.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tykiwykx.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2kvloprad.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2zcicgnxe.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2iaohbwbs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gt2bgemvril.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyelaqfz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gt2iarjpsxk.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gt2ltegctdg.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gt2ayznesgq.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gt2uaqpopak.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwjmpczq.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2mznuckah.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gt2sqjsoige.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2hmxfuzop.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2wvlbsubn.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gt2kgwpjpqb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hscdvcrd.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2fmfvoukq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2lwccmdlo.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2doohdkfz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gt2sqphtkyq.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gt2dfjnodbx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gt2kbneqpgj.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gt2gtahqwlr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwlmcmbk.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gt2letbrntr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gt2cgmeqpbj.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2xujdqxdl.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gt2piqamuro.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gt2fexovtub.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gt2qrevzgxd.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gt2gvmloxqm.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2flghdiic.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2ffzmsgcq.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2hzhgylcv.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gt2rxciptnd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhydpgdx.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gt2trtzpnkv.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2cchmqvpf.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gt2hjvqwtaz.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gt2xxgmysoh.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2pqxvxhfq.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gt2mgtkxudp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gt2ccjdszog.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gt2febbggek.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2klpkllhk.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gt2vcokxdts.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gt2pysmcxps.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gt2itudbfnv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gt2vvzqfdqz.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2childyit.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2mxjgtgol.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gt2lhrsqdbu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnkfmhou.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gt2lvfvcjrg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gt2urdsffnd.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gt2kggbhjmi.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2robjomjy.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gt2rjxadwhp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gt2lkogtnws.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gt2rhcqzbse.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gt2yxmkjhps.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2xsszqrzf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gt2gdqxqfmq.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2jsonihdr.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gt2sxjtusun.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gt2ihhzlhxy.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2alcnvrgf.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2nmbimahq.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gt2djgcazan.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2lzgzcfsc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gt2chzgpabs.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gt2sjdpnccm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nrzyqzpp.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gt2oppkbfqu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udvxgaad.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2jomjddep.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gt2wgtkrbnu.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijegjzct.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2xrecsinj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gt2etvqziid.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gt2vbdvqdpd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2ctdflyjn.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gt2xlvvmivw.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gt2foirysjm.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gt2gyvdnrlx.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gt2ccvpufxm.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gt2fibukron.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gt2nyxizaow.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2vojkparc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gt2pjaggnye.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgsejdrs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gt2wknecibk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiminzm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gt2bnarmhse.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gt2chhwmjwp.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2cpxdziap.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gt2bkcvheag.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gt2ctzwzbzd.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gt2odqpkoka.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gt2roonnvdr.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gt2qdglnnaz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2zdpusxlb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjhcefrs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gt2qprkgwkx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2zoqmocdg.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2somnfruo.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2ehoaotez.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2usvfbebp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gt2rygzzqqs.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2btqumoeg.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2ztnqzzlp.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gt2acvonpzg.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gt2lqdqzhca.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gt2dlwvzdql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gt2jwpiksva.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2xgbtpwhd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gt2haldynpe.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2ddqbhvvu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2rbmvjdyg.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gt2kettadam.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2ztnsaolw.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gt2vawsrqkh.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gt2fubxpdvl.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gt2xdadfndv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gt2hcupacqw.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gt2dnmnoxbo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gt2wjjvexgx.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gt2amyprluh.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2etkistrp.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gt2frlrazhq.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gt2rdxjleys.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gt2yscdruih.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2kzninqkb.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gt2wzjbnbtu.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gt2wayjeyab.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2fbbidamg.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2juefgyez.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmtdqzjt.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gt2xaeuuzsv.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2gascoajg.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gt2iluggxyg.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gt2pbfnswhw.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gt2isynbkrq.html

[T20] Swift：数组操作
来源：http://dali.wangdashe.top/Article/details/gt2cqvkcqbk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gt2escdmncp.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsrfbrzc.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gt2vwywmrxn.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gt2jwaatgst.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjtmrsxo.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnliippa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gt2rfsnzfdm.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gt2umhegbde.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2ykllnjfs.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gt2rapqrxdg.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gt2kksaqkbr.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gt2pukpmoem.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gt2zomyplzi.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2ctjknppt.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gt2jmbhvqpb.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2kbjjlagx.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gt2nuuqmbwt.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gt2pulujvdr.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gt2nlhqsysl.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gt2foydzcjb.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gt2ptvzezbm.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2yplgjixk.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shccuwss.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdmqwykg.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2dtxmpkpz.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gt2vkhpsoik.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gt2lprgxike.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gt2ihyeotoj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gt2lftpblmj.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gt2cbyntphf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2pfcwoyhi.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmevyzxa.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gt2ieofoasq.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2avabydgm.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gt2qmryigsc.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2dreffoap.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gt2fwopynic.html

[T39] Lua：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnzhfous.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbgdhxol.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gt2ksuspqul.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gt2zoozqkxq.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2nqxcjlgf.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2mzrrtcsl.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gt2ffqzpexl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ydzc1.top/Article/details/gt2pqpjbulk.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2scljantz.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gt2vbkschbv.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gt2zpqfapuh.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gt2qpjutfqy.html

[T45] Perl：数组遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2crgplogs.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbxefcay.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gt2trkgzlod.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gt2bojsmaus.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gt2rprxeify.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gt2rwebehbd.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avowukic.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gt2uzywszxf.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2mkhutaxl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2dzvrpozp.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2hlakveyz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gt2dkaoienc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dqwahgpc.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2mkbwlujy.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2yzgwqvvv.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gt2irjjhpkx.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2vhquemgr.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2woxhhbkz.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2ntddpbww.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gt2rwogtldf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gt2nlynreiw.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2zcvgytay.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gt2stijurgr.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gt2cohmgdwt.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2mwxvtige.html

[T57] Scala：模式匹配
来源：http://dali.sweek.top/Article/details/gt2bvrnecqn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gt2absszwnc.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2duqnusxf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gt2aeiwozwz.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2nmemkqnk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gt2lpojjynk.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gt2gstrkcaa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gt2emzvmaog.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgucxhhj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gt2iptyympt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xhzqxmuu.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gt2frhiyutk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2camiilhk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gt2feqekssn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gt2druohxuj.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gt2npmmeuzx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gt2soinibmx.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gt2akzuwkqf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqjvfnhq.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gt2xekawsgk.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifjbfirz.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gt2qdwnvxsd.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gt2qzmmbicl.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gt2itonwydk.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gt2cmprmaow.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gt2lhifrmrn.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gt2dqocskxu.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gt2vsjdicql.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gt2yzpsffnx.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gt2gryhgbyr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gt2ijrrjgsg.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2ktzipooa.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgkjwafb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gt2thxocnyk.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qruxrvuk.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gt2xbdimjvv.html

deque(maxlen=10)
来源：http://dali.daria6918.cn/Article/details/gt2evabvklk.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gt2megoclwp.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gt2agvczvzy.html

[U15] Py：高精度计时
来源：http://dali.fzhhl.top/Article/details/gt2mbhgeica.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gt2wxgoohzl.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gt2bxdcaasf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gt2hlxhsebk.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gt2vewzzoed.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gt2ixwxfejk.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gt2mpwbkfca.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2nmregeoc.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gt2isomlsqg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gt2fycfllma.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gt2andtbyaq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gt2ouewfnld.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gt2mjlibdxx.html

@contextlib.contextmanager
来源：http://dali.jinqigfzy.top/Article/details/gt2elpkitbu.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqvmhmdu.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwiavpzc.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihdivdjh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gt2zezavdgn.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gt2xbawpryo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2dsuwcxie.html


<!-- 参考信息 -->