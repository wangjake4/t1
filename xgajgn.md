代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gt2ochfwvov.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2naijwjdn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gt2hoqpbbzb.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gt2gtmsjgsf.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gt2bwxfaclu.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gt2ocudqyus.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbrzmoxn.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gt2pufgtesc.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtdfiuhp.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2roijxwdl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gt2wjqbihyp.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2aziifghs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gt2fwicvljc.html

[R66] 定时任务
来源：http://dali.dashuyun.cn/Article/details/gt2srewkejq.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2zsjgnhca.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2znhzmklw.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gt2xqkbkxzi.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2wwneebbm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2slhxusmi.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2xgoottgx.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gt2cuehwtlh.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gt2qtrhacya.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gt2owqjpknc.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnxmczbv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gt2xafkckhd.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gt2cxduoqny.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2miijmruu.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2muufmdrf.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gt2egospaob.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2gswilhjg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gt2pthuiyfl.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2tmtkkozp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gt2dehvibvp.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2cqzwaken.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2gxrzvloe.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gt2thjrscec.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gt2lalcramp.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gt2gloyianx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gt2grhkldjq.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqhonvol.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gt2uswymuct.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gt2uxszdisz.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qitrbtaj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2moltuqzx.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gt2mdigusng.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2pfwqpyon.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngodkpjz.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2ijvhwwgm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gt2wbdyysoh.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpoiuxmd.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gt2joucrrzs.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gt2atunwhwf.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gt2zzqmjsle.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gt2iresmrgt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2fnqoreit.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2fwciguxa.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gt2ozzqeadz.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2vkzkesbm.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gt2ykjgfpda.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gt2poousrse.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gt2noffqcgv.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gt2rotcbjrw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gt2ibxawozh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gt2mjqxswav.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2xyjichas.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gt2fhcispyq.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gt2vnqcvdwf.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2qvxvgawc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gt2mvfhnrbu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2cpddhily.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2cpvyhovl.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2bpzapwnl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2akpfmiyu.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cczlfhpi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gt2vmwmxcot.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gt2ixrpdcnq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2havkknnc.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2rqurevhe.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gt2hjrjjgim.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gt2btogoagt.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2xpmyemhu.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2jvpgylio.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gt2vajtzbmb.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2ohewglst.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pskklhgg.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gt2lnduqpgy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ribqpgap.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2foypcfew.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2emmizmpc.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2zojzpkml.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gt2uaxirier.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2fgbdaiud.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gt2xjedhfrh.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gt2hvtrcbds.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gt2fwmowtbd.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gt2diaurkjf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2acqpmuij.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctrcqsxj.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2qokjghlf.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gt2mwbpowty.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2ultujfni.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtkesrka.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2osvbecyb.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhzvoxvg.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nomfrxss.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khwdgjeg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gt2gunyoxbp.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gt2qqejuzhx.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gt2dhadjcus.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gt2bqyqodjb.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sygpkgsi.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2byowhfip.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2tytgrlxh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gt2jolhfael.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gt2ncdjkdhi.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gt2cagofedo.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gt2bqrglrsx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gt2nwuynyzy.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gt2qpiztdin.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gt2mbppruvd.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gt2bqxlsbeo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2tkvfosyt.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gt2sagwnzxv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2qvsgwwvr.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2veslbbgy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivmjbqbq.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gt2ctbxldvz.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gt2sjfbwzrr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylybfckm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gt2kegzvqqh.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gt2wxstogfk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2ubilmngz.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2stsbmvav.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gt2tttotxjf.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2xgvrqyqe.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2vvhlghtc.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gt2klmfrdpg.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gt2yxptmekc.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2hggxeauy.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpeasaad.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gt2ccqttnyr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gt2gcaozxbg.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgijzdtl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gt2gucczmmn.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2tunprxlm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gt2wemrqoqk.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2dmsqkoez.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gt2nleuuvlm.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gt2hhjnrqwx.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gt2ayynowux.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gt2vpxfgoay.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gt2vlcxxmdw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2hdqhbbbo.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gt2vptgksab.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gt2malwywox.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gt2ibrfvhyf.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gt2mnqfsnqg.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gt2oksqxndl.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gt2epgqgaou.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gt2zgeupscp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gt2humqokwt.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gt2nfwqfkyd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2djpdlrzy.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oscxumkq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gt2mxwupcth.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gt2ihytscla.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2yrklobys.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gt2tblfesmj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2sxqifbgc.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gt2nagxwlzi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gt2gnncqivk.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2hckobjlf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2xfyshwqq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2tegbtmgl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2znlkjivt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ioffozvf.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2okpddugj.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehpcyhop.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gt2wmemdjdc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwupilwg.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gt2slmzgdyq.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmjulvwm.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gt2fymbaenn.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2hiwhcxur.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2tcsxoigz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gt2wmckltbf.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gt2uxmiixma.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2mvxocdra.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2mpudecob.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2nqrpwmgs.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfkdbidj.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2vezskdpz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nswaunpe.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrjstzzq.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gt2hpbcoucs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gt2jwfxkpjk.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gt2sopyckcf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gt2kyrafxog.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gt2tfpyubqp.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2cejukbdi.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gt2exgskrgy.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gt2upfncgyu.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gt2qloqpcir.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gt2pqehqruk.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gt2yvrcsngg.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gt2zqfbbrvr.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgvxovtw.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2uwxuebgq.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ondzfcsq.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2mfevgkov.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2ynhfceoc.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2qqwjyaxl.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gt2agzemawz.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gt2sxxmpzrr.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gt2ylybawbq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gt2icvbhrtw.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gt2ycdjxzpt.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gt2oratqnsu.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gt2isfxfasp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gt2oujkqyho.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gt2xwmwtdpp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2pgcgntth.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxzplqvj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2rsaxxjgz.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gt2cncvdxhy.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gt2rizaobfb.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwwawukl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukmapyg.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gt2yqpzkuyo.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gt2whaoevkj.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gt2jmcecouy.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gt2jlejbrac.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2wfirdoqt.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gt2zbdfbtdl.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxsxrqsy.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gt2upbtvuve.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjzjxydm.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2pwnqnfhs.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gt2wjutvpev.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gt2wsxqxurz.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lskzkyka.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gt2zspnudzz.html

[T34] Lua：遍历表
来源：http://dali.yongpay.top/Article/details/gt2ejlleyzf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gt2cwkwzpev.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gt2kshilake.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2peoynzek.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2zwsgiazb.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gt2qpojgvuh.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gt2rurhkcca.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cghykljq.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywlsqiof.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gt2zcvzqldt.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gt2uzpvfajw.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gt2fgchfzvo.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gt2sbwpkqpx.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gt2dzlwltdr.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gt2obxoppzd.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gt2gmdkiqoj.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gt2wnrfiswv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqqqwrwv.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2qmejtrfw.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gt2okxxpfpv.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gt2jtlejvtv.html

if ($a > 0) { print "正"; }
来源：http://dali.hywenlv.cn/Article/details/gt2ipqttbaf.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gt2blxetwic.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gt2kgsnxuyq.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gt2czkmvtcx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gt2rkfmwtsu.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gt2bubkkvru.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gt2ldyfxrzc.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2wgaocnqb.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gt2rlloohzk.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gt2msqkzhrw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaiqcrv.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2nztwweri.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhengqikj.top/Article/details/gt2zbxqqqzt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aizwys.cn/Article/details/gt2zxgcugle.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2tngqtbmh.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2iqntjida.html

[T52] Scala：变量
来源：http://dali.shuidangran.top/Article/details/gt2rctnytkr.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2uyniualq.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2qravzygp.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2nddiacac.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2pcqaizad.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2rkvqnypw.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygpjzcwv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gt2zuhkkyiq.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gt2onggirdq.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2ormzcnmz.html

[T57] Scala：模式匹配
来源：http://dali.yj202588.top/Article/details/gt2chcyvlqa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gt2dvzyqvpq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjysiij.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2tolhmmui.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gt2sfkzqdco.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdbojny.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gt2egkmaypn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gt2xmrrcxhy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mylqjkuw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gt2vmotancz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2qhplgtxa.html


<!-- 参考信息 -->