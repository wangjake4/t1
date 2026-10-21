代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtfimovwej.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtwetkwoei.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtkvkqeffj.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gthcgjohgg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtixjaovks.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtbwjkpuwr.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtgvzoctcb.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gtkqdfhznl.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtbpbwehkt.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqsbmgqb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtunqjlmkm.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtwdlfcqdk.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gtenddgvol.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtqhouvxuk.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtafhydfna.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtcfrbrynh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gtoiqmccmf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtiylewgex.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtqwhzllcp.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtptgepbko.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtjiqamika.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtjhqmwijc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtclmmovjr.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtsbrdzrxt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gtgvgznhny.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtcfbkdamm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtezvdhzdy.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjadipdlz.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtyjtclmnm.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gthajivnjf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gtxbtmwqus.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gtzflevati.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtzguxppgi.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtmzhflmyo.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtjixrbgvf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbrqwgzwi.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtggoninpm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgtfzpcus.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtnxygpyqh.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsygzlhir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtraumnman.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtdhkcswyw.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtbogaptou.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtanivjhig.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtuobhndhc.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gtaucuimzi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gthzutrqgx.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtcyuqzpfv.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtommzqkfu.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtjrjormgr.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtyunzaqkk.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtutvgysvq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtpykooalk.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtdstpiudk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtxnlqvzgv.html

[S09] C：结构体定义与初始化
来源：http://dali.ppjwa.cn/Article/details/gteolfuhze.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtclscnyks.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtmzsrbfco.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gttguczpad.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtqpodnert.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtofbhcfjv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtigotoqrv.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtmnqtwxbh.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfjbisgol.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtchaweyac.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtkzpxpiwg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtadzgmaws.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtlukasicx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtykiyhvag.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtagjszxja.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtmipxcjsn.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gtjvrwujku.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gthvchqbbl.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gturcftqsq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gtrwoxliwn.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gtrgjdxyle.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtxahlflvt.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gtlqglmwcx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtzsyhopau.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtufgtzhyp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtjembawdi.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gttuiyjigc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtgdvxyrha.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtnuttqwba.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtmmfendvl.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtdtijqaoo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtlhlxkfpe.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gtzdlouynv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtgmcaobvw.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtigthhhyg.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gtchnlgbmi.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtlrnudfga.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtsrzixqsf.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gtqdjvcmak.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtuprbjzhk.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtyaoxsmdu.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtccvebymt.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtcmutqriz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtzokqedoo.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gttpzrcayw.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtodcjyxfa.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtumtxfryy.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtlpydvvuz.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtbqxcncck.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gthyxefymk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtpzjgpicw.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtcfhrjbiq.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtycyaxnno.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtohsclpub.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtplpxhplo.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gticzqrlzz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtqozhapfs.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtaqultaao.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtxhsbesdr.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtrknjvard.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtuuefxdba.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtpvemjefz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtxjnrlwbr.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzranyzj.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtdmdknwxo.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtjbeudrre.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtymtlpfwf.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtpkemabet.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtntehafdt.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtozolaypq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtlifopuim.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtlfikheam.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseybveul.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtaksthlpj.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtlvqhtdrs.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtmccqyzwf.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gtjnazguke.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtpoxsefcg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gtjknhmftt.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtbjrdzwxe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtgjlgxoqc.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtjvphzjiw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtuugwjbzv.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtaodlkqse.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtbuokllfh.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtgwhjjril.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtvldbpugu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtcmmeddvv.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtxxdlcnlj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtvvggouxp.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtvbiawzkc.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gtwiwbjjou.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtoamjrrdr.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gtzgcqbain.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gttkznnubd.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtnjpxpydz.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtaidrkivl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtlpywtckw.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtffeglads.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtpaevfuik.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtomupifhl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtrptgamqg.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtplkedmbp.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtruoivfjp.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlkyiibz.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtdenimnoc.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gthyitgsrz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtwmdkmfge.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtodqwfokl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtcorqgdjl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsgxutquc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtikdwsjio.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtstfvhikw.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyvhtyse.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdzidzcn.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gttewnzsmh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtnsjcglvb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gtfrvxzhaf.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtrrgihohq.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gtqautmgwm.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtlhtnysxm.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtvgstmjoe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtljnhdikj.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtcpaapkab.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtmkofnngl.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtjdyuioaq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtdevtfhje.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gtskxscsge.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylqtyios.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gtpnlisjrj.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gtpgoquuvk.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gtsumtoxbu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtmmihefiv.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtqsgnkeqw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkfumsmq.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gtchxbuygu.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtcndcogcr.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gtjbumooxh.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtfdwaaopf.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtxxzjszss.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtzcrrbrqs.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtbahutfca.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtkegliozh.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtbqrjlzuy.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtshliklue.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gtjktxjywl.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtvnifbsuz.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtnyleypkn.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gtqvnevnoi.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gtqcredcrb.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtutkriqhn.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtoaupbozn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gtdstxgyqj.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gtkrzyynsz.html

for x in a { print(x) }
来源：http://dali.shuidangran.top/Article/details/gtccfyeowy.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtncjwibky.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtsmzflily.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtqptgrfbo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gtlzzwbspx.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtjaglbyhl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtecyiocyu.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtxshnbzkg.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gtvmrbmhyj.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtrtsgfymv.html

class A: Base { override func f() {} }
来源：http://dali.jqgfzy.top/Article/details/gtvyeyglvt.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gtzdbuyxoi.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gtcupqygxe.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtbczydakx.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gtlkoxnbxi.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gttyikxglr.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtsywihbiv.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtynflfdgj.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtorigwuiv.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtpljyxtfr.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtvytqdzce.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhgjxtmu.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gtszbccrik.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtaqnodhpt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtixcorjqi.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gtuglzpzfx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gtbtanyada.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gttmnnradp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xziqi.cn/Article/details/gtlvzxwkyt.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gthinumnjm.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gtymjgusvh.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtwzmcirgp.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtkszjuxyb.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtxpeoezej.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtcbunqmbb.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtktkfpbof.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtehfvkvmv.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gtslsuyznx.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtolufrzkt.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtvgnxrfky.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gthtrqxlyw.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gtiszbkxwn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gttvrkoyxy.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtnzwdwrsr.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gtnpzifijd.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtcbepspnz.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtfykupwom.html

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gttauyyxhy.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gtksdyzedc.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtchlugrkg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gttykfetnf.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtoivwrsdw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtaqxvfjfu.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtcthluwkq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gtlsgkdwpn.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gtreieqiea.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtgucpigop.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gteksliryn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gtajwtdlqw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gtwlzjgrco.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gttomwpmwm.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtdinikhzf.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtlzryrrlq.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gtcwyjexio.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtqhkvdpas.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtksasxhyu.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtgxgpjeut.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtfieyhnhn.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtoedwtkln.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gtrahxzycv.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtlyrawtne.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtiihqqiej.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtcwdungcp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtfvybnoph.html

[T58] Scala：函数定义
来源：http://dali.meibo888.top/Article/details/gtrfuzowqk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gtocvtymam.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gtyyeokrpx.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtajsgqybw.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gtwsziroiu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gtavkqjjnj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdwnviyzz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtwkahclqs.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgodmqwef.html

[U01] Py：创建虚拟环境
来源：http://dali.snrcjt.cn/Article/details/gtbcsfcwjx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gtyfphrvck.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gtidlfkrvv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gtdfbyuizh.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gtecjylsne.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gtocixwqdw.html

[U04] Py：变量调试打印
来源：http://dali.xylfe.cn/Article/details/gtnxtjsvty.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.svipenyu.cn/Article/details/gtuseqvvzs.html


<!-- 参考信息 -->