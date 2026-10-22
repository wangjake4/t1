代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtsoahmadt.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gtoyvzfbod.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtyvcmqtyi.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtcfywowtm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtlaassyvn.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gtvsiywjdp.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtejjeywgj.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtmlmmcedy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtiyejsixp.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtdhbfhixz.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtrcvddsjj.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtrkmdjlgc.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtbvfubxgj.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtoqbqpsce.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtozfsdsyt.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtqkvdupkm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtentxtmms.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtlvavlhtj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gthsuxfoqq.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtdadklgfo.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtiyurbzeg.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gttzmoclss.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gtdnitxjpe.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtiswdnrjh.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtaxtbujgr.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtfxrhhqfg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtyiluxzoi.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtifhnoosn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtczmltfdc.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtwofwimjg.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtziqqkerj.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtroytjzzj.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtanvwqotv.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtweamclvx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gthrtmtwxr.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtbhtewvky.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtxhvsmxfo.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkhddylh.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gttxcqcbiy.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtybrcevqs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtykyyvzvk.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtzqngphft.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtefonxhkf.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtgfmjvovu.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gtbujaiztv.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtsdlwnydz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtylrryppw.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gtoplerczc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtdcddudyv.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtmyejksqt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtpictpayx.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gtnntfygpo.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gttyooqiod.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcdggdfv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtsivugtai.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtmfnarwdd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveezwnnq.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtrudhjxqq.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtlojrvwyo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtstyogbyn.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtooblgexh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsqrnwufs.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gtrxokqksk.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwabdwlb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtyxwtocpc.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtmtulxofc.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtttnjfnmg.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtvoctferb.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtwrocyooj.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtpmkzbpda.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gteqdgwyke.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtpzqfvzxm.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtzjizzuvw.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtnzuwrpin.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtwdxfdraa.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtjlwxrgbs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gttlyhqzfw.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtwwpoppwh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtbpqooepa.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtxbtduhlz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gtugqqqadh.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtqfpcigoy.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtlemlrfmi.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgfhcdylx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtlxhrocoh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gtzabcfhcf.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtjecmbglc.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtaeovecwj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtveuifjmp.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtcbwunsgq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtqtcvxfkp.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtjbtauanh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gttucdqofh.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtthxqsrnb.html

(double) a / b
来源：http://dali.hammf.cn/Article/details/gtxjaysmhh.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtfkmrtdtk.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtjulrswno.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtehblfeyr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtdpzewyvn.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtbdngldpg.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtgixhwddu.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtuiklhdtw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtvfxjdgzo.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtfjdtppgp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gthixrjfcb.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtfwqqdlig.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtffpnfyvv.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtsjlsmaui.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gttcgqxwtw.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtqfcbirov.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtafhzvieu.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gteateltuy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoriymae.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtgjqnliid.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtbhoabnad.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtaiziozpf.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gttrinnnhy.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtzspprtru.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtjlmssuuv.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygeuoarw.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtshsqtfnn.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtegfynsgl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtwgauoyuy.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtvwrhzavi.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gthxamjpfh.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtmqmqcfmn.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtijhbilbj.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtnewwhfdw.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gtiqbbotwk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtrlakqfnf.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gtfaiputzk.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtygazugti.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtqavwxgoj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtyewoewio.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtmoqlnmyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtsavvcwis.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gtfemdwtgv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdlkzfwf.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtmjchduls.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtdnmocnuq.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtbvhwxqqv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtakxbsidt.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gterwqojxs.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtnbjaftkh.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrvherna.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtmmmbilqe.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtcmywnbrd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtdxtntaln.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtarcubtnt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gtjetqdjyo.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtkcikxqcj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcfjgjax.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtvoawhpja.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gthqrkuvmh.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gtvebnxawx.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtsbzdqrnp.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtawhaufyc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtdaenqpru.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtnsxgfoto.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtfjimlyec.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtjtcnquvh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtizlhribv.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtzjbiexgv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtnfxfxqga.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtmlthopfg.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrkcdbfm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtqmagxofc.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gttqvldpxg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtnjaygtkp.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtgokvzcwu.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gtvalxpcfi.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtbjdaxurd.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtiwvhufzd.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gtdlcwcchw.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtrdyjmygn.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtvctkxesc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gtoodhtyji.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtxsvyvhvd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtczrwegcu.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtwogsgbrg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtjoqnrpcw.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtqycicaub.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gthoqqgnre.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gtplufbmig.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtstnkwjmw.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtgvxknyaa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtcvwlpwnq.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtplzjcwkr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtoimjwvtm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtocrdbleb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtbbpxebvt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtiqompdwg.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtdtlenzno.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtrnwyrchg.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtsjnykiof.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtfwxqppkj.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtpwhoitzd.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtnmzenrvj.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtpmwoxars.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gtkelhctxf.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtzmeymoxu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtnadhonhe.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtwpxyneip.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtdjnukewx.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtisaypzax.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtqdndhqnw.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gtduokhvqw.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtygggvajh.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtkbasdjje.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtckwjmqfu.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtdyzlqypx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gttbvbhxon.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gtvffdzmnu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtzblhxsgl.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gtvdkejzsv.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtsfbpacja.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtynegwmoj.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gttjjpnmye.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gtpoqpczmx.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasegzhzq.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gtndhnqpmf.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtxvbywycw.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtesuqtshk.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtcblpdofi.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gtiyhvppvr.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtmrvudruk.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gttiafebmk.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gttzmlqpvh.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gtffgglrit.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtdwwbxwua.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtyorcxvli.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtjvwrhawy.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbruvzyu.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gtfbcyksgi.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gttmmjjrkv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtdehxxtuq.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtrcdhrmlg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtbuczhvmg.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtlmtgenhb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtmdcyvorb.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gtvdmyhvnm.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gtiwehyxnj.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gtoqbmhjqh.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gtbwfkrumu.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gtevnpkqyh.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtvybufpmp.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtijzrubfk.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtpmqwnrhp.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtsnmwivms.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtjocbofqq.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gtmnflwbza.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gttgqmrngl.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gtsgntqmqm.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtemlmvczm.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gtzphndawm.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gttnuozwtx.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gttufzwvkc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gtdstybzsa.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtrxzeaftt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtkkewbgoo.html

[T35] Lua：字典表
来源：http://dali.yueranfly.top/Article/details/gtrntpngej.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtgqqypvic.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gttkfamhlc.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtainhtgxa.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gtijjyvbed.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtwygzklmv.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gtmglxmdnb.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gtgplsjhlb.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtmrbajgnq.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gtdjkebqns.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtvirhmtsu.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtpmyijwep.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtbkvlgujb.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtxmrtzvdn.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gthfupepzo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gterccinyb.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtvemuuxul.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtnayioopm.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngaoiqiz.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefwkwziy.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtvgyabmhp.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtsoqwysdr.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtqqrfnyos.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gtsodocnfy.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtpujnvdlx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtwysnvexd.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtojhfpeeq.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gtnqcvwddv.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gtwoinlioc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtcmljkzdc.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtoalfghar.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yangfankeji.com/Article/details/gtibuswrbs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gttjqqfnqn.html

[T51] Scala：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtcpughiry.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtagklzrfu.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gtndzxowzh.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtzrabjfzf.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmwqxnws.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gttcnimros.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtydczuhty.html


<!-- 参考信息 -->