代发 wailian999

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gt2ioqvtjmu.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gt2lnkjrehr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gt2kzjeatyv.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gt2xwdpltjd.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gt2klbzruvu.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gt2aunllduz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gt2rieuounc.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gt2acderpii.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gt2fjbbvnjs.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gt2bufhghkj.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gt2njotztvh.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gt2rkvxofoa.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gt2kfgtdcjs.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gt2aervvzfr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2rzkplupc.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2qxgnzcme.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gt2qlkdxmoq.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wstwooyr.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2jwizlmsq.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2nzglyqvk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gt2kournmep.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gt2lsjoxzdk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2nndzoguc.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gt2huyvpphq.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gt2xwndasbo.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gt2bxxtwfzk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2jsfdlewp.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gt2rjqgaoki.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gt2wwnhxlsy.html

[R76] 使用临时文件
来源：http://dali.jiagoushi.top/Article/details/gt2vftyzfjm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfvepcqp.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2ujqkgarp.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gt2pyoaggau.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2jlrplnmw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2keugalgm.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gt2uswaqmyx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gt2iqyshgge.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gt2afynlhfj.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmzrmmwu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2oaieihbc.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqqldgmj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ktbfrcwt.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2aurkcsnz.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gt2ofdzbmzt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2noqvpocr.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2cwuryzpj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gt2bcaerbea.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gt2vrwouneu.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2vmvpyuew.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gt2kqfhgjlx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnhzfibi.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2mvhuvoog.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gt2gxkdentc.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gt2xwtfewrv.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gt2oruqcbmk.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlrvkbms.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gt2myfsedwk.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gt2jkoartiq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gt2wtmgddnr.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2fyaimegk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2mdfcfumh.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gt2lhfdpjzk.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gt2mdzgvplv.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2vxnskuka.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gt2zznwiwem.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gt2bponrers.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dneyddwq.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gt2szxhimex.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2ficuvjpy.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gt2xwwuleqv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gt2sjbgxvli.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhijzouy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gt2gsgenjku.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2gxtsznte.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqtfuqsp.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gt2kxpbsjcp.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gt2ahybvltw.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2oqleayco.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gt2slqbivwt.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2hqhadvcq.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gt2nbhnajzw.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gt2gpokaegl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gt2fvinewyo.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2wljrbtfv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2nhriejxs.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gt2jyxigcbg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gt2ywdjkuqe.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gt2xqjznpys.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2ztdnixms.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oquzyhsx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gt2yxpksdig.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gt2ubwwlruv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gt2ezdhlkqk.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gt2tubsmian.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnehaeyj.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gt2hhgfakxq.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2vtcpqimp.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gt2gzbkbyek.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2uewxxwxb.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2ehbydirr.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2pruwvsno.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gt2mfityipj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gt2vftlzzru.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2mkpgxywk.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gt2rcavpcmh.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huiuozec.html

#endif
来源：http://dali.aizwys.cn/Article/details/gt2wccfcemm.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2nnrvmuhg.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gt2pnbqelpy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jftmipfb.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofvcvcvl.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gt2axthugpx.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gt2nhlqsdgs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2wkgnojsk.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssmtheno.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2jmabdyix.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njuzskwa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2ehvaueri.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gt2mdrxvbcy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2bplakwna.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gt2bzqxvuqf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drsvoiuk.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2rsqierch.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2bgcmfzjp.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gt2cccqkkxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2kpqkrdpr.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2ytqeoqcd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2ajabzvhk.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2fjvknrue.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2ggmncwjv.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2netcrovt.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gt2zuvrpxcf.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czhuxbyd.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2ymdgaazx.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gt2hqhnprbn.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gt2tggeqfow.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2qfbzddph.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gt2epbvrzky.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2gurihqxg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2xsebpvhw.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gt2axgxqjsa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gt2qmquvhcp.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjimuafu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rofmmymn.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2jhdclstc.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gt2qgeguuum.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gt2pasdcegb.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gt2cextkixe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2nonqhjkm.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2oxyyeedr.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gt2rnuxgnec.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rahmqwag.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gt2fsltfwxk.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gt2swnfwszy.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2ecxsdouj.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gt2anojqbop.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsbvhqxi.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2qkqmodqr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gt2fxkunxhf.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gt2jugpegub.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gt2btswemre.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2sqqioixu.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2keisfzoa.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gt2giccvxem.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gt2mexlzxkv.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gt2dguxaynm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gt2dpctpxua.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gt2gurbqwzz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gt2flhlvigc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2mfwxymak.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gt2mebfbkfb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2gavzmsdb.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2fpexjjvt.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2zsqbdqhn.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2rjrlrpfu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gt2ueseqwcx.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gt2bcpfucis.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gt2buwtgesv.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gt2ldytutjq.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gt2mstidtfr.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2ttzgufah.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gt2pprtzcew.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2zqltguuq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2czmzxesa.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2efwmqwju.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2uhxmeapk.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gt2hpgbzgap.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gt2lmmtjhah.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gt2lwruursr.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gt2anrmnnrx.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gt2kzfidurh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gt2zxjqoyra.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gt2ssfukzla.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gt2sjtvuhis.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gt2thjeocum.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2zbqmoqbs.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gt2vkwvkgje.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gt2dyetxnmo.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gt2iiqgdwxj.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2tmdwffyd.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gt2ydwokhtd.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2tsvwxcyc.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2xabzvwvn.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2llbudugx.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gt2rsmnnovn.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gt2bkwwauhz.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2nwelwrbg.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdqihibu.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gt2xltfjulp.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gt2cdfalvwh.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gt2zsgdksvu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gt2draixobe.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gt2suackrot.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gt2nyreumei.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2ohjnlqmk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gt2bdnibihy.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gt2ebspnhsq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2nvpexazt.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gt2xiirnvmz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2thrlnwpg.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gt2ddpupheq.html

struct P { var x: Int }
来源：http://dali.tianlin.xyz/Article/details/gt2uthhufzx.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gt2tqellbsw.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubjjhdei.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2ocjckbgr.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2imkicrmj.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaqlizzr.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gt2dtubhujv.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gt2kaytviyd.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gt2vmqxmhap.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gt2prdcyeux.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpaghiwh.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnaofxzt.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2yhotkjer.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gt2dxqmhngl.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2wqgjwcfh.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gt2lflsjzwt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gt2cisbxegm.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gt2uyhqgqot.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gt2dusmyxkl.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gt2tlrzefej.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gt2pegvnslo.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gt2kfnkhxzf.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gt2etwaapsu.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gt2fudxaqni.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybpzozwp.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gt2psjybaxd.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gt2eganyimt.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2nahksove.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2sfetegcx.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gt2ygvplvrv.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gt2gvlsumbv.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gt2bqovqtvo.html

print "Hello\n";
来源：http://dali.gzhubu.top/Article/details/gt2yipctufw.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gt2glzyjuvw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gt2uvwkiltr.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2rqxiyieb.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmwbppoa.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gt2pqmoretw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrpxazcx.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gt2aiumofsb.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gt2gjkycman.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2msnvxvno.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gt2jeuvszea.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njyyldlv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbdhdypg.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2bylmuphm.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqacwwkz.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ethcrigl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2cvpmergn.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2dqailqro.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gt2pgrnmjco.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gt2sqhwscbq.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2gxiqhugf.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2xfjfqdpu.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gt2beyfkugj.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcnzgsbq.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2ibnctxuw.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2mpencumj.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gt2agzhlyti.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gt2mmfqcvsm.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2phvbektn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gt2gjecpaqu.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gt2xhvdxzub.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gt2wcdkfbio.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2djixhalo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gt2ddhmlgor.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gt2cxmfnlau.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gt2mflwppxb.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gt2kaaulcub.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gt2aoqmdkgi.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gt2xnihxaku.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gt2nfitjkws.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2gdtflhdf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gt2ngunijld.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2neqgmhlt.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gt2cnfwxdpc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gt2qroxkvgl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gt2xcpvzbnt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2icvffltq.html


<!-- 参考信息 -->