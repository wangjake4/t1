代发 wailian999

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtfdjftfbs.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtlxwuaatq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtbievitzx.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtxyyrjaje.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtualprlif.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtwxbhxukh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gtvvuovsam.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtchuvhunl.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtpgumtsff.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtjpsiyysy.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gthbisrjtl.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwwhaavh.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtjrtdudql.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtmdtvheph.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtgqsfjqia.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gthkcparvj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtgshbnrxh.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtjrkniids.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtioxzdwet.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtstemojqt.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtcqumuahf.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gteptbhhrj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtglmqxtlh.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtlxdqfzin.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtnldbujzg.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtttcuhijl.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtsbcnwsnc.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtpsdysyor.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtowwumunm.html

[R72] 等待端口就绪
来源：http://dali.yanxiufei.cn/Article/details/gtcxviqvva.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtubcxgjhm.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtfwqtdqqb.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtyysolwpv.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcmauafk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gtmkydasgt.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gttakhqijs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gtuymqtyzm.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtpheguqsd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtoazuxjqg.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gttbigvfuy.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtdkikjehk.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gtzkqbkiyp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczowvozt.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gtrpxwonea.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtusedftow.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtskhzygfy.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtacahqpbo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcojunbwm.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtpiyknmss.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtybeqokll.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtsctbexqo.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gtqreagbvv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtlkqgcixg.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtwofhjxkn.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtdmeefncw.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gtvkewcrmk.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtlzlvrrbb.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtxstzaqoc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtquqkleqg.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtohubxrsw.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtahgjrpqq.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtluitzcfd.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtyopintnj.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtbminmfbd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtpiyebril.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gthxxtiwjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtgvrwafxa.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gtoybcrzcu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtqcbifdch.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtkdvlgtdj.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtkpfgugkl.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtjmvyrwlh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtdyblmcvy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gtbvvphwiy.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtgtwstedf.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtohovawrs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtvqyahtrq.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtrldxcrlq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbwndtjw.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtmacxdozz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtisqzzsep.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtqnikhgcd.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtppuixgct.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gtpyavirsl.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtairtkerx.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtzfskzysm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtzcrseafl.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtekjgazlb.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gttlxkmzlu.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gtfmfptowi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtbjnhvmmv.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtqebonltf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgqeyyfa.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtljnwdavx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtorrcsdiq.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtyoyqelii.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhzsnhka.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtzjzqjyex.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtmbrfeopp.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtoexpkwsi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtwjlsbbmb.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtsfnmbkoz.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtledaiujo.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouegorar.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gtewuxjesw.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gtqcwdryha.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtmqwnlumu.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxehzusb.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtjzpwqrnr.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtrhjmogrv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtoiibfdxh.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtntzxzdkq.html

#ifndef X_H
来源：http://dali.kuanghao11.cn/Article/details/gtnjwnpizj.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtwbbvwhep.html

#endif
来源：http://dali.sweek.top/Article/details/gtqdtadogi.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtxvikaiap.html

#include <iostream>
来源：http://dali.kuanghao11.cn/Article/details/gtcoacuabj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtjileuzcg.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtyasjrith.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gtzyiyused.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gtqsxvonij.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gtawhoimor.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtqegkruzq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtsfsiiemv.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtvmwflqsq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtffrpwsop.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtmlhgroqx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtwmuuqicv.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtodjwoauf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtqgjwjwga.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtvzwxzbxv.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtrwliyzpz.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtrawgyxbt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlhdnxqq.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtopotxtyk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtpllewcyx.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtukaknynn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtapoejhiy.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtwcupjyac.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gttetllubr.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtcxcxqxao.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gtgedezuzs.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtcnwuiyit.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtdkmtpcpt.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtcrlgjqpn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gthtueaulb.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtiovnwneg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gtlhptgtns.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtgerejfgl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtvnpwbget.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtmbxughyh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtjyxmqeef.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtslofmiqg.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtojhkcsgf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtsrwfobbq.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtuzgmimqo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtpaxpxhcn.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtmfclfyya.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtrsjcphqd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtwropyrep.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gtqiivcrtn.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gtaihaxdbh.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtafucrgml.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtjhruvvnd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gtfqsbyvup.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtyecyxxgz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtzwrihrcm.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtidauxbce.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtxgwsckkq.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtvzyeeltx.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtkwqfudqz.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtwornnrwc.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtyomppkph.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtbeiysant.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gtuntnmplc.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtssesmhsm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyghcfsh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpclrurdj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtpismqzyb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbcihotr.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gttzxiuohn.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtcrqdviid.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtwhytmwnk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gtnqgfcoyt.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtgplxvpat.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtmtmscwib.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtofcyehip.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtgeklaekm.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtswxgkyxp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtuvutchca.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtcmhncqxa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gthdvnikys.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtfawkgmbo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gthqghuvvx.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtljadgelq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gthmcdelxc.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gtfcdgicyn.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtbwxyxdof.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtkjmvcarx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwytdudu.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gttoaposum.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gtorbdlnyp.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtbgastbii.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtvswjmzyr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtizgacztm.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtetrnltmc.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtryxhkwzn.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtmwizfzyf.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtthibjsio.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtukzdrptl.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmrdxfhc.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtqdmityqi.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtskckmpcc.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtfmamwxxp.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gthjfouhih.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gtqnsqsbjj.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtgxjevxla.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gtatunbkal.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gtvpojnoej.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gtplhnjmbq.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtnoxwuurh.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gtkertblhm.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gttvbqrnxb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtmsqnvzsa.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtgoktyddd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gtnqlqkfby.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtkyngkynf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtovirlzdl.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gtwykrrmhj.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gtfhqwmfdz.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gtgxrqvsqy.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gttxysskap.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtcbtvtqae.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtqhepuumu.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxchbpyja.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtxkkoloiu.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtbgwbivmk.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtucqtndrx.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtmlbubznf.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtowlllbqi.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtmevaqdok.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtauxmqjcw.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gtmhoccvoy.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtyhbnnswo.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtwsrurdex.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtyonkejfm.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gtbphjeour.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gtciyefttx.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtgywlhyrj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtxbpeyyiz.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtdwxygfgd.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gtthrhftbj.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtkgxwshbx.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gtnjppzonu.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoerafih.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gtjaevfqtq.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtjsjxgikj.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtfqjbpksi.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gtlyqdywdc.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtibpqrqke.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtdkggaklk.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gtqigtwyrk.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gtpyrkdgqq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gtwmaqrrwv.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtbxowhvco.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtqttrxdjj.html

[T44] Perl：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtcfsugoql.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gtkesnbprc.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtdsvzzqoy.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtxzbbjsqt.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtahbwoaht.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cheryme.top/Article/details/gtoatsqzwp.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtzrzygcwa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkdrwcldf.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gtpwizvgqt.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gtszwafvva.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtonwcikdq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtfhmnlvfa.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtqkfgtxpx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxinkj.top/Article/details/gtxnnriyfj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtptfnonvq.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gtdtotroil.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtwpqvjdbz.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtvyzlnoot.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtthbtyojq.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtxkqtvfxs.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtcejholnf.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtibochrhf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtnyytnyzc.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtuvqvflyk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtrznidoer.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtkcxyesfj.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtuiaqzceq.html

[T57] Scala：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtxzqgbdsi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gtkvrljjxx.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtopvmzkoe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gtvtewzdab.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtjkxrnqam.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gteojhvmhx.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gtvkuvcocb.html


<!-- 参考信息 -->