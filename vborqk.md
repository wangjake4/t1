代发 wailian999

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2seodwnwt.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gt2fygxgcgx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gt2veuzkxae.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2anbbvnga.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gt2wndynljm.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2uddhcouu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gt2hrusxfgh.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gt2onfrzbjd.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwtxecgw.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2btoghlgq.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gt2wbrijwbq.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gt2hfjbvmzo.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gt2aimztbsq.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gt2fszkgdiz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2kibxjheu.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gt2mtjxkkrj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gt2qvpqcmob.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gt2gdapgccu.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gt2pcsgvnzz.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2bihdhqvi.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cglzkkva.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gt2yqtgoohn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2gzcfbzkz.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gt2rsqttlhz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gt2gjfzdrfk.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgoeynit.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gt2veyraxpp.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2jswshcec.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gt2staddppl.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gt2nqnsdkiq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2smyopuxx.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gt2hlwpqwze.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gt2pirjrmwg.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkykxgsv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gt2wmnoumns.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gt2svesapur.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gt2lnspxtvp.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2bqmgbvil.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2zixdwjbn.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gt2adeinorg.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gt2iyelyjsx.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gt2gxhsxxyl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2moclmlay.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2hyeqmjst.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gt2neffoukp.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gt2xextafri.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgbzayyf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jtrpzhbz.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gt2zdccukku.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2axwcrjrl.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2uwihpzhh.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gt2yasxijxf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gt2zhkjqohu.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2vxqybkdx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2zvdhjhfl.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gt2yrohchak.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gt2anbbwlgp.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2xsqgbcbb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gt2dagnhnvf.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2lpmfmnrx.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gt2qmbsfuci.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvwjjotk.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gt2gfvseihy.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gt2krjktegi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2gnpszudk.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gt2gebosamz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gt2reffuwvb.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gt2robplhrj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2btuopsqb.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gt2sjijpzus.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gt2qhkbesjg.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2yncpdbhz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gt2mucfyufv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2ouyklccw.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2fhlhknsb.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gt2kcwvedzh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2kklvatjr.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gt2thchwzwn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gt2pcxhohjm.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gt2eleyzlna.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gt2fxggazum.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gt2rwtpbbfd.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gt2elsafobq.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gt2iczngwdl.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2pivohavo.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2zzsfsazp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gt2uecdcmbm.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2wxkvlxtv.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gt2rcemjomf.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecqcxbre.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtspqims.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2lqlzgsfg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcnsyxqg.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtubvehx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gt2bzvqfylc.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2jdemrsbu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gt2cgrzjlqi.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gt2aznoyqhi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gt2exrbzrta.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gt2iswqkqzm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gt2iwdlmdou.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gt2kmceobmd.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2klkkdhql.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gt2mmoeizrx.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gt2sxkmacfl.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gt2migyelsb.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2tufefvvz.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gt2qbjocppt.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gt2plxagicf.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gt2hbgubxwm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gt2uqqrddye.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2npyqyugo.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gt2oelokhxb.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2lpyocxyu.html

#endif
来源：http://dali.havefunace.top/Article/details/gt2rdqwptit.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2zhrdvtva.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gt2tcslhhmf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gt2vveboriy.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gt2rwumntbn.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gt2qsmnknfq.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2zcokeqji.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gt2unltqpvb.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2lmwmbavg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gt2mffzjnbq.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gt2lfksadpc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2ckxpsxjs.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gt2gqkbocdy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldcwsqgb.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gt2qebvvtie.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gt2llpbrsuq.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2xqeptxkq.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2tvrdftpi.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gt2qehujhpq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gt2lfeqnril.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gt2otscyiir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2fhoowhij.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qajggaiv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gt2itatwkcn.html

[S42] C++：继承与虚函数
来源：http://dali.nanxinkj.top/Article/details/gt2rchiqcpi.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlwxvleb.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gt2hoajjkhr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gt2ewxugixp.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2agokrbkj.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gt2mdogcors.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gt2hkyrizbs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gt2egmlfyju.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gt2nleoznmf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gt2alwphyui.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gt2mqgatvzx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gt2xdehpijd.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2vynhagjz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2pfbbirxb.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gt2cpyconkx.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gt2etvvsalp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gt2pznljgzo.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gt2usqpamqj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2lraxujqo.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gt2jakcdxwi.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2gwgamhdu.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2vglmsfzu.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gt2dybnmpmz.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gt2ygkzhkyq.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gt2xnqvadbr.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2rnxqovyn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gt2rcqovumw.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2weeyoqib.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gt2jccaihiq.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gt2byaqzvqt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gt2eidxufra.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gt2obhcvuiw.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gt2nibowiox.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gt2pzxzhdjj.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2whoqszir.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gt2hovzxwtk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gt2detqtnsr.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okaoodxx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2hyorghja.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2aveivrze.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2lmerntcr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2qqdjheop.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2trqhfooh.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2ardmewit.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gt2ynxvbpvt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gt2hjghmvfa.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gt2eistsazm.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2psahepvl.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gt2yolyqfys.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2itcjsimg.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xebcgztd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gt2iltuluju.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2nyweslkz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2bqcsymbk.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gt2xvochbrb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2mnczmnzz.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gt2cctwkaex.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2dumbxows.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gt2tjijgvll.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gt2qilcmlil.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gt2czgwpbga.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gt2oqpccwtg.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gt2zwlikwii.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yonumen.top/Article/details/gt2qbjtugxz.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gt2bboncpnm.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2wnbckxtf.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2xlgrsvhv.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gt2cebpjdpv.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gt2ursjhuhu.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2llduhapp.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2xurdqlaq.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2qlddlwyn.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2bnnpymqj.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2qhmqpmke.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gt2lnnazbyz.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gt2llorcnji.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2zgykodvj.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gt2dsdzyuxd.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gt2vhwduusa.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gt2bsgcyktl.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tektfndg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gt2miuvagem.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmcczhyz.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gt2zwzddlxv.html

[T22] Swift：字典
来源：http://dali.zhongyouzk.top/Article/details/gt2jidwdusp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gt2cedeyias.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2geyepuie.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2zxkppvgh.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gt2slmywuut.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2niltsacz.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gt2pxqmbadj.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2wlvbqvid.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gt2yrpnzvxq.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gt2qvbawjjq.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gt2mjlklxfa.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gt2fkbheojh.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gt2xasevrtq.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hduufvuw.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2kdywoshp.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tklmqkcr.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gt2qduvozfq.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gt2vqlqbgsl.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2mbvubdjs.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2oemdvukr.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2fkdsztkg.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gt2urwljsjj.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gt2xmrgeraj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gt2lbzxxffq.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gt2rhpsfwps.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gt2jgropder.html

[T35] Lua：字典表
来源：http://dali.jyoumei.cn/Article/details/gt2jkqwdrra.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gt2gbqvuqzz.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gt2epgnzsxm.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gt2ozpvthkg.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2badzanzl.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gt2xcnlmowp.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gt2vvuepwch.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gt2zgusbblb.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2yozfqtnn.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gt2ctqyqapc.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdgkmsfh.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gt2kfzjexqr.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2sxegjwcg.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gt2mwuhrhdx.html

[T42] Perl：变量类型
来源：http://dali.c1oappe.top/Article/details/gt2pambrrjl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gt2ucrrhhfl.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2goaewuid.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gt2xwpnxavd.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gt2fsghkiqj.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gt2bvmzqqya.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gt2ujlueiir.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gt2mrdlzopq.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gt2ibrvoeee.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gt2uxlaqkmf.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gt2nfbtuvaa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gt2cpaiwqqa.html

[T48] Perl：正则替换
来源：http://dali.shuidangran.top/Article/details/gt2hgsbqogd.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gt2btoahpao.html

[T49] Perl：函数
来源：http://dali.shuidangran.top/Article/details/gt2fdxxgdxn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2jgibegmd.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2mvfkukqm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gt2wwtpdyrc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2pjohpepa.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xotghcat.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gt2afglnnbq.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gt2rfyqhzgy.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gt2wzifjyof.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2ykjpknzt.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2whhwxvqu.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gt2mejxgwgv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2wqixzoom.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2ggimcdfi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gt2jbtxiivf.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gt2bgjlbrtw.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2hubcwsep.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gt2ntrfzyhu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twvfuswd.html

[T58] Scala：函数定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2notxopsw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gt2hxyipuge.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gt2fwidshtx.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2lyawnjnf.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gt2jdjnqbja.html


<!-- 参考信息 -->