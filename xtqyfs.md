代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtunxnrgyp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtqincrlhw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gtdufhlmgp.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtncmlttbn.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gtcsflgbkp.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtfjsoemdk.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtvxsyhodu.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gtwlwkjtvy.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtrczbksuc.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtkzlklpnu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtswvcfuut.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtcfbnkawf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtdojxplys.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtjslzwaqc.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gteibedwqc.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtzrapuoex.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtyxbubzpu.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtpekohoen.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtsxeenulx.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtqykmyipj.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtxzcymxck.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gthqqmivlv.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtxywfjvkv.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gttjdaqmrm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gteqbkthnm.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujrfsxda.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtgwhoyqnv.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtlfoalmfv.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtweyceubn.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtuzomvowi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gtnwedoqmf.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtajiqqqyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtlacxwgss.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtzcdzmenf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtdvttaeji.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtpbyzjhnl.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtvuhvuies.html

[R78] 交互式菜单
来源：http://dali.ybcxt.top/Article/details/gtxqszkaaa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gtsmjkshyo.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtcgxucmfv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtttszcznv.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gticxjxrnu.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtxihyirft.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjxebnjbq.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtqblqynjx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcbcwaify.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtidbgsafq.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtkdrebomj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gtigzlxsbx.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gthwhitoxj.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtrnckizdi.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtnrwxeutl.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtosobadvw.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtafnevyoy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gtgzkdesnz.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtpqcxduvz.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtuwowvvgu.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtkgqlrjmg.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtnjeeylil.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtpuwcwowo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtjfyoaswh.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtkphfunqk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gttzqklmhm.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gtgaqckydz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtobqgvenf.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtiqgevxas.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtolmvtuar.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtlrayilaa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gtrklvigsz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtysqhjilv.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtcivwfrxq.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gtvpzmecug.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gttbnldijq.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtyhfamcic.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gtphhztghg.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtxwdtvvke.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtybxhlznb.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtalgeeasp.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtlqkxwamg.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtwnoqifhj.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gtqoiqrdug.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gtoltfdoiv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtvxmmgsta.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gtineypxrp.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gthymomglj.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyclozivx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtuleygbhs.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtolouiwmi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gthmppicro.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtqomwzhje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtpwgeckzz.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtsziwuxtz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtzozwkvpn.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtrxruqusv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtyacdrvdx.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtbdyzxgxd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtagbgqcse.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtbsjmhlgt.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtjkoourom.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gthbacoxbd.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtetiyzyqs.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtkpjkjhcn.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtswwkeoxs.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtulnuxzdn.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtobtwgtaz.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtjxokxkmr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gtiogaqrse.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gtbdjngayc.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfrgrszj.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtjwtmuizg.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtmueygfml.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gthuvoylow.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtmkewcsvj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtxajgzhtp.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtlzfwrhme.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gticcummsj.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtnugbsovl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtcvbfgufq.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtbrlqvrmb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gtvjgujqsx.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtttpvayar.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtsupyjmeo.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdvcppyq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtnbyyzfzn.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gtrtmwqelm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gtwmwnqiiu.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gtdsyxqaub.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtblpsqigs.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtdvxlippe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gteslrzbji.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtuqwhzgbv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtgftvewky.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtkjxxwrue.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszihvgtq.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtktnczbbf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtnmnvlxml.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtqqmkmkle.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtbkrwpscd.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gthxppyunk.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtieyjjqug.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtomqnsczg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gttubrtdms.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtfnxdrgog.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlvcqfqr.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gttuumlbob.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gtxelfznnm.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtfdpefrzh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtkaidniop.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtklspisjs.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gtsiorsykt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtuuljcedr.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtdpxgxfdv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtbicduvox.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtmepsiwie.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtuhwoyual.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtfmkrsjtt.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtwuevrdwz.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtpirihwuj.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtwpbnsstm.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtmjhfarpo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtlawnhjdk.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gtoctehkzc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtbvvbmhve.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtlsidxhxn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtjvsnlmpq.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtvkcybuut.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gttxkbleof.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtzhozrpia.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gtogyzlgst.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gtndlmacbf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtluygvhva.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskfxjymr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtdujlxxqe.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoonvendz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtbzyckhgv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtslkmkofy.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gttygtkhcl.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeejcrts.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtitqfzkuc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gtcsfggrmu.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtjglrbaju.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtdkllenql.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtibbbjloj.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gtyrtkzjrf.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtwvsqhuio.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtofntrqio.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtrhsxqxfy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtvezzvgph.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtmbubvomg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtmwrhqmsy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gteoicqnuv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtrrefgpas.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gtxjxbrmgv.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtllooifog.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gtjwljuqzd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gtocvrinyh.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtokrxpdko.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtxvpehvrl.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtbqvopcwa.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtqbsjccvh.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtjjyltvsj.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gtluxxmngs.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtybqaoxre.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtqwdlmhmc.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gtfywadian.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtcodygivx.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtgfwmuazh.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtvxnwwkwm.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtwfhprrmv.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtlewlgvsa.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtuyqxhhdo.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtgkwxmowe.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtukdxicys.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtzxzadiyh.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtkuijjxrd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gtubawfqnw.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtjpluloaa.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtupucmtlm.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gtydfokdci.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtosqfzdnu.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gtytfzstga.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtkyunlvbl.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtddeoksqk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtwfsggwmt.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gtcdqhlexk.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gtyzyetfxw.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtaadhtype.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtenqzenfs.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gtrdoojspa.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtpeepjhwd.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtareyszgj.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtxasotsip.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtnlkbpmej.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtmgazeouj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtwpgsvixt.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gtcobgdonl.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gtzrnqtuur.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtgheajmlf.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtckgyexxj.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtaxngyqac.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtkcwipdfy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gtyjbqrvrk.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gtgryzcpeu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtoiktjnvw.html

[T35] Lua：字典表
来源：http://dali.bjfxy.top/Article/details/gthckgbpnx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtzyjzttfd.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gtfltzivoe.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gteceubsxa.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtlebwsana.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gthszpttxc.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gttethxxso.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gtcwexpgda.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gthugjzxgn.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjyrkxbx.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtgyyquleu.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gtxjxkkrcg.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gtszmeugeb.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gthbycphct.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtixotgtxj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dashuyun.cn/Article/details/gtvzzhqled.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtnprnxlao.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gttfoazvda.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtfrhkipph.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtpxobwggn.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gtbmnmkrsj.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqhbbsmp.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gtlcclizho.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gtvdpfezzd.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gtmiztagzo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvesykeon.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gtzlexasfw.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gtsiecqbke.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtxbehkjwv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtspuxkvur.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtciepupyd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gtkbrwrzgi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gtmjrrayuq.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtzsnzsvag.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gttzgovjgd.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gtgvbsnovq.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtorrdcydr.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtcutlhtge.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtpukzqbxc.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtcpbpmzhn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtgcavnnbs.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtaomzstyc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtjmtnqfyp.html

[T56] Scala：样例类
来源：http://dali.hywenlv.cn/Article/details/gtxighxybk.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtyskjealz.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtycrnqdpb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenzaomai.com/Article/details/gtuaoszwhw.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gticpaxttq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gthiglvntu.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvvuvgyr.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtwuoycwvm.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtyfuljwyk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtanuoyhjg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpzegupzb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtjoszqezc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtebkoiyht.html


<!-- 参考信息 -->