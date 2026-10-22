代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gt2vdzfeobz.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2qkcaiwoi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gt2rbtjndlx.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gt2tmbxmvhi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2cithxwcq.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gt2rtdvbyos.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2tcjopiub.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gt2qvrfamak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gt2pwtdkdmy.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2hilpcotg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2hbucijcy.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gt2xcrnqiym.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gt2zvhmqzmf.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gt2oxfoaluu.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2nbkbfazz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tggboosv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2wptfbghp.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gt2xftfsswb.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gt2urqxlxxf.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhwgudhz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gt2kuiouznp.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gt2lpdqnobh.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gt2ronrhwka.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyxmuwpu.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gt2ddzuoxha.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gt2cbetnlaf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gt2xzxxkbuz.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2dgsvipkw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gt2npvommza.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2ytytwdza.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfvrbusd.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gt2gynvcmpr.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gt2yeskwqhl.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gt2rdlxpood.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gt2hwfzydsd.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gt2esgoqqqf.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gt2hnovxfkf.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gt2ispiouxm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gt2vpidttfi.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gt2muobnapa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gt2nqosuvbu.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gt2rjsjbvle.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gt2kdlouoqf.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gt2uiettdre.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gt2brfwcuie.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gt2noygxcew.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gt2ffzxysvg.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gt2jaaqtpku.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gt2uamrnwkc.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2uhhimdpn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fepvfyuy.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2lxjtjaxe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gt2kbojmkkg.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gt2lkcrheyr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gt2afgldrnm.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gt2xxchttdd.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucxuutqx.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gt2vdjirvqr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gt2yyujwkme.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2zokcxgjw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gt2npaymkym.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gt2wjcgvfej.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scyeyszt.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gt2nzagijih.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2ysqfwoii.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdjvnegi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gt2xagbpskp.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gt2crnfyjyi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gt2qxzjkumd.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2iankjcnh.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2pxhaxpme.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2gftnvhqp.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gt2fdmlvkta.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2riheocuc.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2gnxvlhog.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gt2spnzjjqy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2uzupkhgb.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2xhiafrtg.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gt2wyvneqaw.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcvsupgi.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2fohvvems.html

[S04] C：字符串复制
来源：http://dali.nanxuanxn.top/Article/details/gt2kqmxjcay.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2xrzjfrze.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2qwcequvv.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2xkqrxlyt.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2jjnqtizx.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gt2iunnotes.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gt2dhbnjgbk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2xvwweqgk.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gt2wvitzbbm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gt2uxtmrgfa.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2bkpxhexu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2qyirpcim.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atuodcgl.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmweiczs.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2ywuqcawh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gt2arkbwnly.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gt2phggupzm.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gt2knelioch.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2euowbjsz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2cqxdbzdr.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gt2zcewunzg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtedojhb.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gt2oczpyjgy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzqlnfyv.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gt2gwqwamkt.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gt2izqlavfo.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2htlvlpwn.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqehzjqj.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2hhhdwakp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpqepsku.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2xglpbuys.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gt2khnxwkmo.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gt2azuuaonf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gt2gbrrngay.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gt2pctsmzce.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayvxttpe.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gt2htrtldui.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sardliff.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gt2zlfflzpj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gt2onzbayrb.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2hunvitsz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gt2vkowhmjm.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2yihhwtic.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2dpoexxsq.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gt2hanmzoln.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2megnvwsg.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gt2nkelodmf.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gawjhple.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gt2kikllrbq.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2jxdbkxur.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2bfoynqxy.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gt2yjvgcnbw.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2dhwueovz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gt2yuwxlwkg.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2coibfgll.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2hazrqzme.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gt2tlowsogx.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gt2oiozhicf.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gt2wdjtelco.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2tmvmqrrt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gt2pverbpvn.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gt2dnjncffh.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gt2gjylqyxl.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2kjxcvtpb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ailuhxsw.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkzlwsmw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gt2vxszfrpk.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gt2oxeunuqw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2nxhhgfiu.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gt2lypdiuuc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2fnkwujpd.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2ytvwromq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2lyrcbplq.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gt2qfmakocy.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2qduucvzi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qibhxuls.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gt2lwtsrbce.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdphstgh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvsmoztu.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gt2ipihdqnd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gt2otpticxl.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gt2dsuutgeq.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gt2perfudqg.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gt2prkwcjol.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gt2mpvbukbe.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gt2awghpkpr.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gt2aepycuvl.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gt2caingqpg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gt2azesrzum.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afxlsfkb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gt2karchnka.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gt2knxpfoah.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gt2oguatryf.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2vhxhrwsi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itksjcpf.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rekchqvd.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ogftqwbe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gt2ouqynjnb.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gt2xxckafzz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2stmvjywx.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2fvyyernw.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gt2tnkqwxar.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gt2cbawijuf.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gt2dcbfymti.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gt2crbpuaax.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gt2majnjmok.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsceuptu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2xvwaoqro.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gt2kdxzklxo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsibmmei.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgvmfiif.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ppjpythh.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2msyatsaj.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gt2hvkzypxd.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gt2ddmztaju.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gt2zvmbzook.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlykqssf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gt2quqhcmbh.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2sqrbwmmi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2aqmsobuh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ibqkhqrg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2txkmofjv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lxfvmhyf.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfznvsle.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iboodlqw.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gt2ytoeorgq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gt2wraqvdtb.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2zifaqpgo.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2hntijtwj.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cadylvdl.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gt2hpexbjkc.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gt2kzcllfkx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gt2yhvxgune.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2gvtxoldp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2sulstrdi.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2pfzstaxf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gt2cbkuxbmt.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2mtivqufa.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gt2aoxccvyr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2rhisrmhz.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gt2vpnpmdmj.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gt2loqmixmf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2jghddado.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2ildybvoo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2lofsfhmg.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gt2oymrvght.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2xcedsdhh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gt2xxcfxxpl.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gt2kxgkxuky.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gt2cbomrbcc.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gt2ppkfysrl.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gt2ijykbfyu.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwsutshi.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gt2muifleov.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2ypmzlrrp.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gt2rhhfngvz.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gt2amwgjxhk.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2nfrexgvo.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2xcpmqqun.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gt2ngjinqkw.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gt2secbhure.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2zayhkqrk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gt2tyucrpif.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gt2ahbjzoml.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gt2kddpgfup.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gt2azxxxrop.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gt2cmxfjkmh.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gt2gdocfkhw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gt2zpgmnqvb.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gt2jnwfqjeh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gt2dsfxfwkv.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2ngppncil.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gt2eyndghqb.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gt2oydgkiai.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wffigzjn.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2pwhzraiq.html

do { try f() } catch { print(error) }
来源：http://dali.yonumen.top/Article/details/gt2oedbdcex.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2mfijnmwk.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gt2tujynpda.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gt2sroaoqzm.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2brgohuod.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2utalhfkp.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gt2lbgiscqp.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gt2lsxhnsji.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2uahgbetg.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayrtkqmh.html

local a = 1
来源：http://dali.9152youxi.cn/Article/details/gt2hgkaiqma.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gt2yxavurwr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gt2apxngzmv.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gt2ihogybjq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gt2mekuihcy.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gt2faxmoeld.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2gtfbsdzh.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gt2wxgxuaxe.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gt2siqeovdu.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2bhgihdec.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gt2dftfjofx.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gt2ejwxhdxa.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gt2slzzpyea.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmgraxgo.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkxnjkgd.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcgfohiq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqzujca.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2sdmtqody.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfrgscif.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gt2dqznzkil.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gt2tmwqtzyn.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2uqluiuyw.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gt2lxxzptjh.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gt2pvhxiibn.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gt2pcmaerzu.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2jlrcndnx.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gt2jxhetkzk.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gt2koifjvqb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gt2uuvhcyco.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gt2lfryssgk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gt2pcnfsrbt.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2qvrzxocl.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gt2vlbhcvfd.html


<!-- 参考信息 -->