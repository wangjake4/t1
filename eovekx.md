代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gttfuonmqa.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gtclveumla.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gtbpzyqysw.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtfcgkfpom.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gtboxgfhiu.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtlzzdznkr.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtmgkzxljx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtxumrnxci.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gtkswxdlxh.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtxnajibxe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gtzstdtlay.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtzoqwkcev.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtjzattlvd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtpjhcupka.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtuebrjqio.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtgbbsefdq.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtdbqazptd.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtcucjbcoe.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtymodgzho.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyynntnw.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtfjyhqtyr.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtjtglswxy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gtgiberdpn.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gtvqvioyvq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtzjlrkkxa.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtuwtsodih.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gtvqzfqtds.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtxfaydzzr.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtbowwtgog.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtijhujilf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtyckczmmq.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtvcqsknxh.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtacvugnvr.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtffsoyfof.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtibyyfeis.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtkfilwblt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtvmffivnt.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtszcbzesw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtdqmontuj.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtpwxrumsw.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtzlhovgds.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtrbqvrrmn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtkhvkcshm.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gthjwzgmtu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtfrwdfsvg.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpswkpyxo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtevtltbfs.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gtwcroilfm.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtfmaswtis.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gtdicyulkf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtetrhbaed.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqzphydv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtcmzwsvcy.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtrylihudo.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvudtcwf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthdxwsgob.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtcubryqma.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrvicbigc.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtmjsssqjd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gthehdtfvf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gthbljhxjc.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtljdkgdsx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtkgsnkxwn.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtxsbwucqd.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gttuwgxkbr.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtdbfdcfdi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gtheucrxde.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrljbssjo.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtsgwmljsm.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtrhwhgkrd.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtnsxrchps.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gthgsivore.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtinvpscof.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtxmgasecg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtfofdmpit.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtxrzjqela.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtbzvzswue.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtuiqwghfk.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtxcoezcgg.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtdgdygnty.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtsekybjlh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtefsgkvab.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtobircnpi.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtfpsewtrv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gttntlwdoz.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtchqxapxc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtnwkrnvre.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtaawrlwom.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtcstxqdsm.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtnntgjhii.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtvjipxmdv.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gtfzbseidi.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gtttgqndmz.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtdmhfagrn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtbvdzpwyp.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtilunjeyr.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gthvtatnzl.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gtgqgcirlf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtphzffyvx.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gtsrerrpyd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtnnhhgazf.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtzhejxuow.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gtzzpeuciq.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtlpmcszkc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtpalnbizf.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gtrvycdssf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtmqtwuefn.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtxqvijvay.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gtrjwubosp.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtwlutyrja.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtztlikmtr.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtftligbqs.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtbbdxsshm.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtpwtrbhtk.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtlvzctgwz.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gtkxypaejq.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocsopihh.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtwzldsgox.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gtqmftfaqt.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtyntskpzf.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtdzgxwrhz.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtygchpfdw.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtaqxguycv.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtbbuqbitc.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gtgubbjqol.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsnqpzwek.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtwtavicni.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtgaiikplp.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtarossvrd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtywzkmghx.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtjungbqpu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtclpwxjhs.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtzkhzjhwp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtfskjpzfu.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gtoolyhntc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtsojguqzx.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtlxmnfkhv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtqudzmelg.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gtljmxsiwo.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtytourwcj.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gtqgjxgbkh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gtioygbjgk.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtiyuhlaol.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoinwrow.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtwdoydrbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtjotfrzzq.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtnleejoea.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gtqfnshutq.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtfwkeljwg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrfeeuxi.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtdssdoreq.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gtijmgzwlw.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtegrzefyb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gtqdijlbae.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtdotzfahu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtfausqobi.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtajgjlajd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtzeqfieha.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtnkfnjhgs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtafthyrsp.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtgnurefwt.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtehrrskmb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtywyuunzn.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gtphjujegw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtjvkycjka.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtsuwtcyho.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtolwxcyap.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gtezenzwsm.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtkymqkqfd.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gtrzxfmlbv.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtqrzozxkl.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gthpbyvkqz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtjrbwscwy.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtzndelrui.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtrdxwqfrs.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gthqpcouqx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtwlwbvufg.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtgmqowlti.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gtieookkbw.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gtgifvlvmw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtcsimgpnj.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaynmzlvr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtrtquyeit.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtsmevdtlg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gtravflkku.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfhxbacqh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtmoidhxzw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwaksmntw.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtpwtqamob.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtimzlwpza.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gtrnqkgrvh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtuxqnedlp.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtpgcgzbaz.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtululzgto.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtmukeyhsl.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gteypeduzm.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gtjfmuvnxb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtbraxjcqb.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gtptvnatow.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gtxhubuoln.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtgofsdfah.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtutnmbyii.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtdzadlasw.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtdqimqvho.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtevelcrbe.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtgfjlhlfn.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtsbdwcpms.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtcuzlewii.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtvqhqhwmm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtynlsptzx.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gtaaguhuqb.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmnqupkn.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtypbeshhj.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtwehlyoxe.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtmttwnmzw.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gthzmmjykz.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtuqtejcpa.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gtnpnzuflw.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtybrbttze.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtblblylhe.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtghcmsdmf.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gtsrhjexyx.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtlizsgqoh.html

"值: \(b)"
来源：http://dali.andypj.xyz/Article/details/gttielseri.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtvhawjvek.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtpubwqrbs.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtaxfhyoaw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gthrmuxdqt.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gthhnltgvu.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtzsuxnebr.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtlncfglym.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtwtqkrwet.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gtvnleudby.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gtlsnajqxt.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gttarrjehg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtiwivztpo.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gteplafifx.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtwgityzes.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gtvibegaaa.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gtkseljwzl.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtuncvviwx.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtwfohvkak.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqciszpud.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gtitfoeozy.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtencxlnmc.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtbrvmyyws.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gtbydztpju.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gthvysmdbo.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtfxuhxzkq.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkvgjgmh.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtbiypetwt.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtyirlqoyv.html

[T33] Lua：表（数组）
来源：http://dali.jinqigfzy.top/Article/details/gtzyzvatcz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gtmujziiuo.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtfmrcvxis.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtsspgpngb.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gtwesxpebw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtuczdkihh.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzarapbs.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtundwhqlj.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtsomibphi.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtghbvtzlp.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtknclmqqm.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gtxpazhexo.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gtkwcjmgcv.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtlpswpdyg.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gtdkdgzpep.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gtewmzgjmo.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtbytntntj.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gtllpuoyhk.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gtbsignfey.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtqqkzyvtx.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtgyczixpg.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtjcgxghbh.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gtjxwhrqkt.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtzlqgokhj.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gtnlzmitld.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigufen.top/Article/details/gtkpucehzh.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gtzjmaolsa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gteowypvoj.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtxrtyjznr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtswlpqmou.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gtptnvpwxr.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gtgyhlwrcj.html

[T49] Perl：函数
来源：http://dali.haohaochexian.top/Article/details/gtagfvrtdx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvcnouiii.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtivifjqvw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtnmdltfzl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtqrwqdxri.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtyabsvazj.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtncpytida.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gteauuvlhr.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtqhonpijr.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtoopggukj.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtwlghdlta.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gthvjxrtyc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtvntodoir.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtszxvsqqr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gtocepymlw.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtrllgtegj.html


<!-- 参考信息 -->