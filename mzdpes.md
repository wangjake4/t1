代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2idyveeum.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2hbosiomm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gt2hpimkyty.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gt2oyvpovez.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gt2nhkezuib.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gt2iayvyywp.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gt2anhqpjhg.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gt2pqsbcjqy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzjmpgie.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxrvzngd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2fhbqbxck.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gt2gkhjzlck.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gt2vqjlcodg.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2jerawrll.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gt2kuixdrlm.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gt2abicefyp.html

openssl rand -hex 16
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjhbffie.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqjsdmtb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2szyedbqv.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmxwimwb.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gt2yytzxizz.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gt2xyqjbbiu.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttyrjglg.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2ewqqsncn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gt2yruuxbdh.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gt2gxxvehtg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2oucscdmq.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gt2nyjpxqyd.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2wpdtuhui.html

[R74] 批量重命名
来源：http://dali.mhx1999.top/Article/details/gt2gypvcbvb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2zzsfhnlm.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gt2jhmmhrtl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gt2trhsmhcp.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gt2qglncwru.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2sgmvvpgi.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gt2yklhpmob.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxytchpe.html

[R78] 交互式菜单
来源：http://dali.sweek.top/Article/details/gt2tzmebszg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2mlfxdohb.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gt2ovzienhu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2peuteydn.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gt2vdpoajss.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gt2jolplxpu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2taockprj.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gt2cyvlivhb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2lollqkpi.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2hlccxvms.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gt2fymolqhg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kizsjiuv.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2ldecvkvj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2litwarms.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gt2ctoewvmj.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gt2xkyeynys.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gt2qilkfxnm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2pkzuhsuy.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gt2zpdpstfp.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gt2xjozqsiu.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2jtblnrss.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gt2fhmnrhqr.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gt2trozlklm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gt2uayxngdv.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2lazdlgrs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gt2vkuqbgeg.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gt2widvyctp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gt2zybwqajl.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gt2xpliulxs.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gt2ubgltoxx.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhflgnru.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptkencpu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2jtzhdgvr.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2owsublas.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2gcoweznh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gt2mtwqamno.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gt2judlfpyq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gt2wgecsrfn.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gt2clilfrey.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gt2vxeoxxzd.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gt2xazwtgsg.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2uovidymr.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gt2wddeznog.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfoqlojv.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2yzjzsslt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gt2ksanpywj.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2tfoxxovp.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gt2wuovfjds.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gt2lwramejn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2nutzswut.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2gjochykx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2eyksjypz.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gt2qyhmxjxv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gt2ijqnppwt.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gt2yrdpfhkb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2tfshocsr.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2qqtdhlxc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gt2llsxsouz.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2bjpraevw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2xfgbddsm.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzzvbdoj.html

memcpy(dst, src, n);
来源：http://dali.hammf.cn/Article/details/gt2odotvzqx.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gt2ebmowdsc.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gt2eqetjbpy.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gt2tmaupdoc.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2wconrgko.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gt2xfqidgif.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gt2kaoewkdl.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gt2dmfqqrea.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gt2peejrbyn.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gt2emkjbhdu.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2cmyvyetw.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gt2xmvfnmna.html

#endif
来源：http://dali.shuidangran.top/Article/details/gt2dznkigxv.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2koyjhozd.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gt2fiuiepiq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gt2wwodowcy.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2buknzmfe.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gt2ebnqiuhe.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrfhzvqu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gt2iqxanijz.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gomyuffc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gt2hgnelylg.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2ixhvpzqp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2dobweqsd.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gt2vkxtqcmb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2jrojkttb.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gt2nvwaijmx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2iqytjlhi.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gt2pgiflgia.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gt2gvcmggrv.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gt2gmkswgva.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gt2rmchdafs.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gt2lythahqu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gt2nvvwvhjd.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gt2zorsvxzo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2uwrrxmgb.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gt2fkdcjudh.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gt2llvxyboz.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gt2dtvelxms.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gt2jsirwvbz.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gt2bovfuyqs.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gt2rvsscuvu.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gt2wjtmbxak.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gt2xflimtdl.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gt2stnipawj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2ttfgusjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2hlecgeni.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddzlmhob.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2sdcstakj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gt2zrrptlar.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2nniitspg.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2qareekwb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gt2quaxmhid.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gt2zfddenys.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2kwpbwwhn.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2jmvqthos.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gt2lmmayipv.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gt2ayjjfnyu.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vzihhsub.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gt2vavrkhyy.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gt2iwiyxevq.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gt2ppdmqcjd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gt2yvawgplv.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gt2dsguhbke.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2qrjufsja.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gt2nxxkodve.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xknxbuzg.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gt2rjmfcuxm.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gt2amzwohyi.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gt2kxkjlkxo.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gt2gklqcoft.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2dboandmq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gt2qyjuiaex.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2glmmdtrw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gt2yzsggpzo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2rgltrmrb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gt2spsenfzh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dlrclzbw.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2zxjyxqob.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2wnhikjgq.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gt2ypfdpsrv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gt2ooabecdr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2htfsiypt.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2tmmyvctv.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgfimkxe.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gt2infugnzc.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gt2vicpmrjk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gt2auxamyoe.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2nqlyclqf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2otxwuxax.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gt2lkjbdict.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjjzdahz.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2atksscmu.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkiashvh.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gt2jwtmzsjz.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gt2qazgntir.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gt2fwbtekmh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jidkypdp.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gt2zhbkoauh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gt2nnkpmyvh.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gt2okaujhei.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwfvmygi.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gt2iplswkcn.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gt2xuqvzvbc.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gt2dkhxogzd.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2dglrjcby.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gt2czewooav.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gt2gwdnnqmp.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2wftdpcnh.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2iduienjh.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gt2hmfbibfr.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2puenpkep.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2tvlgdzor.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gt2mnwktuhk.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gt2udwpmvpt.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gt2iyhgeoxb.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gt2udxpcvog.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gt2kzqlhfkv.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gt2tcitfnmb.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gt2esthevmr.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gt2gehstkvq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gt2zbuichzf.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gt2idefgkny.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gt2cyfhlxyj.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gt2atmfdlvq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2ftrzhcez.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gt2zxexuwjh.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gt2sspkqffr.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gt2tfdpmelr.html

class A: Base { override func f() {} }
来源：http://dali.ivvv.top/Article/details/gt2yowscgld.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gt2hvzbgccm.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpanrtrc.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gt2cjtqjcvz.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gt2odbenznf.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gt2ufzpiknr.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gt2fiqxyxyn.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdmfdwht.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2fmkbcwjm.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2mkheifde.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2zwqfbmfn.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gt2qgmimlak.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gt2bsubaljt.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gt2rtzownol.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gt2pimsciaz.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gt2uegtkmeb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gt2leikxbcn.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gt2ugcwifnu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gt2qbjauerp.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gt2avmotoyg.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gt2yheeggtw.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2qidrqopz.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gt2zzsytble.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gt2kikcgopt.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gt2yxdhajea.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2vnbdzndl.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2oewzaohg.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gt2ansbkvgg.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgeyxoxd.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gt2amcsxnkk.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gt2jjkqoxlp.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ikcsxumy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gt2stzpslei.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2ueltfbpl.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gt2vxdfiwoe.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gt2ybsoahed.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xfogbqdh.html

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obzmpcwg.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozijrgiy.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gt2fiivzjpz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gt2jphginkl.html

[T47] Perl：正则捕获
来源：http://dali.zdqjudy.top/Article/details/gt2hzmjokuw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gt2wacznuoy.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gt2mfdegrew.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phslgswk.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2obweqlch.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ecrnytkx.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2yhdezojf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gt2dyqdohfr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gt2wpemhjis.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2flbnodje.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2pwncjsze.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gt2wevpawoj.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2hzfutqhp.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqvpaszi.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gt2knrbwpqj.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2vnbiesxc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gt2mtwdkbda.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2cfbifgdf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gt2kbegjsnf.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gt2pejtrevu.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2owlowhwd.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwmhnjyh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbqduism.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gt2qurjjgtc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnxwusfx.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gt2zxuelfna.html

for (i <- 1 to 10) println(i)
来源：http://dali.tanke756.top/Article/details/gt2bmoevrok.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gt2osnykbei.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gt2hhvryhes.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2cdxltekr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gt2tbzprrfz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2yicmalmi.html


<!-- 参考信息 -->