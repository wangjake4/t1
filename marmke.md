代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gt2xftbskia.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2ipogtgig.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gt2cwrymtsm.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2vxxydgjz.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gt2smezisgw.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2wqzjdwbg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2pyyguzmu.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2tohxbzzb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2lxdegykb.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oopqjnpx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2zwvesihi.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gt2fpazodsi.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gt2fulrdbvf.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gt2elvgykjg.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2azvjpaun.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gt2evanirox.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2dhxomqrz.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gt2wbqmqwlj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gt2wxwtykgj.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gt2qtzgpyip.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gt2ahxiyumo.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gt2pugliubf.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbvnwwha.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gt2orrfmqrh.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gt2bmgxbdzz.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gt2jezccqqb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gt2zmkvthwk.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gt2viyhmkom.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gt2zrrzbayz.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2pdxahnxs.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2oqisfeph.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyusnzq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gt2mkgzfhgr.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gt2yvtrsqth.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2grflmndd.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gt2rutbeqtg.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gt2ewlivjpg.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gt2ozwoojev.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gt2ucelwgml.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2xzzgxrgg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gt2bxicihwh.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gt2lmwflpgj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gt2uywhfzrl.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gt2iirjdmuj.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gt2dwidozar.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gt2okerbspp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2qjomhmcm.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlxmeode.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gt2yipwxqpe.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhnaouep.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gt2zjhwkkiq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2wivrphsl.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gt2itnikdho.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2crrlsqom.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwiiewup.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gt2lmnapnwy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gt2nhkjbdvb.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2ziodncfu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwewzsdy.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gt2odhvclll.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gt2malvloco.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2evqzarcl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gt2xskmtfrg.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gt2kxregmhy.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gt2tucjyyxm.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2zojaqrde.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pclkeguc.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gt2fjlyikwh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gt2tlholqqu.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdwzbzww.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gt2pvuriiwc.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gt2aasccxrk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gt2ltrbguyh.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2kikptzun.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gt2flugfasp.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2zdoozdmq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gt2zksmbuyh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2rcxetfee.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gt2skzbwdfp.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gt2ngdabcuc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2ncqmludu.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gt2cmrsohwy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gt2ffmiijks.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2llkggzqg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gt2cqhhaibs.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2lmvfvzbj.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gt2hbxfdvcb.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gt2eopxlthm.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gt2qegwnztk.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2qvtodwso.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gt2xzaurdta.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gt2qddtbyxb.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2iqgzvmut.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gt2eakphxej.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2qwrrjigu.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcxaxelg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2cjqpkmkl.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gt2ctdvlggi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gt2gqafaaqv.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gt2jlrnnjgf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2scdvwazk.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2ibveffrg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gt2ouohsski.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gt2gcaqsmnf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gt2vtwidvlh.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2ntlqenns.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gt2lbgkqyvp.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gt2swutzclr.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gt2stytfsdk.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnwzldxa.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2ebzeholn.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gt2ecqdasqr.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gt2igqstvpf.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gt2guifmahi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gt2znkwensf.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfctbric.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2aaorsehh.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gt2dhudbcgc.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2joaieiqk.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2ibykywcu.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcgtbriv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gt2aipzvhgf.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gt2ajfuvitj.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2ytenujhs.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gt2faegcnod.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gt2arwdqqha.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwyljbda.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gt2bpkmubsh.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gt2oftdozyi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2svtpjlwl.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2cmixtpov.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2kcxmlpyy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtmmrem.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gt2xnpxkttt.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2brvjcnhp.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2szzjlxur.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gt2kgzwpkwq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gt2qdugvuml.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gt2ykqaylpc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2sagfozqx.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gt2gokcmcgq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gt2gcjevsrp.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gt2wzwrorva.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gt2xdaahlrg.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gt2fxayctyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2rvhhkayx.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gt2blvgtmtq.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gt2htlforwh.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gt2yvkunrbn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gt2vpooqplh.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gt2bqxsorpy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gt2sdqlohmz.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gt2vmyfazzl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gt2yagqeqzz.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2vhdipzfi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gt2cdgkvhrj.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2efclnoue.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gt2rfipetfu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gt2attqceng.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gt2lmuaycxt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2duyemsrm.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gt2kodngrou.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2zmzwdhwi.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gt2odjbalnh.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tjduifjf.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gt2zeqfmlle.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gt2vxcwanjk.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gt2jytzgdng.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gt2kpkzyrsk.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gt2vjqxlxkj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgpxxdnh.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2vavwgdcw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gt2diqykccm.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gt2unnbnwah.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gt2wwnjnpxu.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2pahcninx.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2hzfpqsjq.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gt2rbxlqclx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gt2yuxlnnud.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2nurcnspk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2kermkbre.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ajjiqowv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2csbjzjjf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2fzfvpmun.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2jtfzamma.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2tkdmtydl.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gt2vxcdwxmf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gt2gukzkldw.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gt2tllkptrs.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gt2dypjevte.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gt2dwxwqvov.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2lgwinehv.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gt2rwygwtac.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gt2ziqignfb.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2qpzchvxo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gt2mklmueoz.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2ohngfezj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gt2itqlnlkh.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gt2rutbjhkp.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2bscedkuz.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gt2fuvydfqe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gt2xvfgyryo.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gt2yzlouhka.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gt2qmsskkbj.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gt2exmtkjfg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gt2qtwyvwwr.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gt2ngdrwief.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2ymnknunx.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gt2yxujrbyd.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gt2dvuexrht.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gt2rtzjvsyr.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gt2gyrznrcg.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gt2dpsidouc.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gt2uocnqkyi.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojwadkpn.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2twacwyla.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gt2amqvckeh.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fncsoiok.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2wrrwutkf.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gt2oayahmic.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gt2trwrbgrc.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gt2fckyrorr.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gt2gaxpajls.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gt2hbwrzwtc.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gt2tpajojqo.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gt2fmpaworb.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2copdxqdi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gt2gxelscvv.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gt2rwycqzwi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2uqcpidra.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gt2uhnfgqxc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2vyrviakz.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvrtrqyw.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gt2fnodpwcs.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gt2hammcaoy.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2mbehlxxi.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gt2hzzfcdjb.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gt2lhsdrklv.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqskpwvs.html

enum Color { case red, green }
来源：http://dali.quarkkingdee.top/Article/details/gt2qjiqapin.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gt2cuuzbunu.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gt2mwxhmpgr.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gt2dljkhogj.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gt2olwehsrv.html

[T31] Lua：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2sashxyka.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2kcrpcbrg.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gt2owequnek.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvtlmruc.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2girnvihd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gt2pyoggevm.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gt2gzrkwwew.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gt2inxpndxe.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbtwquge.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2emwfyxjs.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gt2ohcogbao.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gt2ucjuaxrz.html

[T37] Lua：字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2tnknvsst.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gt2ssuhxgoy.html

[T38] Lua：条件
来源：http://dali.cdnleiting.top/Article/details/gt2rjkkxnqp.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gt2ylgfifsv.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gt2thahquka.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gt2lerlhpww.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gt2huaghfrt.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gt2vnwczqzj.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxmiwcwx.html

print "Hello\n";
来源：http://dali.yj20258888.top/Article/details/gt2ggiyrczs.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyarpuwf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gt2szcsiahh.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2oxyhbaje.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gt2elayehrr.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gt2mbhfmwki.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zxkqxvrp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjqecjd.html

for my $x (@arr) { print $x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eejpmryl.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2difdjcgo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xedjczwg.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gt2laeqtppv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gt2fhemjyuj.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwlobhxp.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfwmqgeq.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gt2qmqgawjn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2wxbtgeud.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2fzaqegjz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gt2lorfbpcs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gt2mhedbbwy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lukadkhw.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2otdzpdsk.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gt2vnfnssue.html

val a = 1;  var b = 2
来源：http://dali.316326.xyz/Article/details/gt2wkmydstc.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2eivzkwtq.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2gyjaqyfq.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2euzbmxmd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gt2rwtenyyf.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2qhhheblr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gt2wlqaxjtp.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gt2nehslxlm.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2ucimxyci.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2ycfeckgd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gt2wqdfyypg.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gt2ytzjetiz.html


<!-- 参考信息 -->