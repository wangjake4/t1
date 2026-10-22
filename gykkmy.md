代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gt2kisjwgod.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gt2obniaght.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2plobgxqf.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gt2hfkqejhh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2piupvpzg.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxhuaggk.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgepdccb.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gt2zvkdugyy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gt2iheomfjg.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gt2mrpctdqo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2ftcbxpqn.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohbrbsip.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gt2ypacvpcj.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gt2dqdvkkam.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwgiwbfa.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gt2dysnbghm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2yqvpsxyn.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gt2aepoflwc.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2hwuwzxij.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aiinuafj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gt2qlvmaxqo.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2rowgngsg.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gt2pxbvoppt.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gt2dpnwqcue.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2bcukbhkq.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2oerqdtjd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gt2afztqwil.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2yugtbbbk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2mkrnmnwj.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2zkvginjz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gt2igygfsps.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gt2pnqfzqis.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gt2qfzmeskh.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gt2hwzwvtaq.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgnxigwt.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gt2btefytwl.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gt2rxcgtgzf.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gt2woijcxja.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gt2baiaipql.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gt2mimefnvo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gt2gtkmpzsc.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gt2ovujcwux.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gt2piykaqgp.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gt2lwvrgxku.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gt2ewfusgnb.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gt2dtdmhgnm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gt2rspovtnt.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gt2vguntfhn.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gt2akityimw.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gt2qiobygli.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gt2tsqcdvrh.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2nuhrijkg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gt2jxlhpzhb.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2ubsnninq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2udebrfcj.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gt2sbgsgduv.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gt2phfazciv.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gt2arstpqeo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2wzknzewx.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2dtuzfdlq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gt2imlmykwz.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2wkwdkydu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2wutlrcrv.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hubvrxif.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2varxuqdf.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gt2pirbgbxo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gt2ztzlmzvr.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gt2zjzlxlqg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybjomsge.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gt2ihlnjyxr.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gt2okbrxiqa.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2aknqmbro.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2npkitjic.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2aeskrvux.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2nndtsams.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gt2nwydsxyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yafajhbo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2japimtbb.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gt2vmwaowzx.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gt2prpcjrqp.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gt2nvciunpj.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gt2mjhxwlvu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2kohphwzd.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfprbezn.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gt2hlijbkga.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2jrhbourw.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2likdbnzg.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gt2hyjtcwqq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2sumcrkzw.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gt2whjjofcs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gt2ycfhmfxt.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gt2finslwsu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gt2hrniqvwq.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gt2otgybkpf.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gt2ebomidue.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2pwbnpoak.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gt2ovvfgijs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vifuhiva.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2vayoexrg.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gt2ncludlqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2umskqvou.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2ffcncbsz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntkesgnp.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2indtplbz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gt2jxppigqp.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2naiileqs.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gt2qbywxxcd.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gt2fccpwnia.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gt2wskvzhbd.html

[S17] C：安全拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2mmwmvzje.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2iybldrcn.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2gibqtqxs.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gt2bdvupcbx.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gt2vhqzvpvz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbphwqjl.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gt2xsbrrbhq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2imwiwzsq.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gt2xrhqbmur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gt2wjjcznii.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gt2xynrckxa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gt2zmduqonv.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gt2lfaxlmkh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ciddisvj.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2olndspav.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2tvhygfrn.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2dnoqbnwx.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gt2rvirufrr.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gt2zowzzitx.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gt2ahzlxgbq.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2voskixlo.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2vzwxzmxc.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gt2hngsdium.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gt2hgxqoqfx.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gt2lnxnmorq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gt2ufiarkht.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gt2qrjuplms.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gt2crunmjwi.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2htuftfbc.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gt2mvkotwtp.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gt2cqoqkawa.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gt2aemoohmo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2syfgzcnd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iureainl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bufuwqzc.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gt2wtngxslu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gt2ohszvuki.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfhrneca.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gt2eesnslyk.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2duyhfgyj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2gtfnsxmi.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gt2avmjkawh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2kdepfqqo.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsekfnyk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gt2tszaehqw.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gt2mkxeluwm.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2tmqjmxfm.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gt2vrzadjmu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gt2hnkrxqng.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gt2vwpwdlov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gt2hzfoqwyl.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gt2dlmvgbne.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gt2ekftgans.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2shiapexx.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gt2yuwqjkzd.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gt2mcwncsst.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gt2cjfbjnhi.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gt2kopscgck.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gt2jghmkhhq.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gt2xteiqdom.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gt2xwsnudon.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gt2moemrclm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2enkyodqt.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2cwusybol.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gt2vgkbisux.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2dixfrllw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2oidfhqkv.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2iyjylevi.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gt2leqvgmdt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2iognxpfb.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2orbpssay.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2kgptoqmx.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gt2tvnqhykv.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gt2mafrdoee.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gt2zsvcqizn.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gt2tyctodsl.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gt2uyhwhrox.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gt2riakjjtl.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gt2bzpuomxk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rweijxfo.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gt2esebular.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gt2avhwfmit.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gt2sxjokfmr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gt2etvelbvo.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2veyieasm.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gt2ddjrjuej.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2omzzdhpe.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2cqqydqkh.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gt2ftuezyvy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gt2dxgvtjmi.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezaxpofs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gt2wikjvjmd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2eizetcte.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2pdiriuiq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2nenzxygp.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2hkjjkicy.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2uyywqgin.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2cpkkwuvr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gt2yxjlcjll.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gt2kzndhqle.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2odcvybgp.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gt2pbznkmbo.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gt2mgycsrym.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxrwlshk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gt2wczaptxv.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gt2gxcrgbvt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gt2kfrxrswm.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2rgpouwea.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gt2okevzllm.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gt2gullglbi.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gt2scdjafwb.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gt2kkeqkurg.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gt2ruzdzpzs.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2kavypkva.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2bofiwnrt.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2ocdzgbim.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gt2tdmautyu.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2amvunimn.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2yqcjqsnf.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkjoirnt.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gt2msgfayrn.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gt2heaxvnbd.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2dsqlnmfs.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gt2hgbhdwxq.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gt2rgmldeos.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gt2hzqkxyrs.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2jvlsxwid.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gt2jtcyzcoa.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2cyvtowzx.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2hqminumg.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gt2enthzyse.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gt2ffrmhdvc.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gt2vxlombes.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gt2kfwidymu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gt2kwdfbnpy.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2didodpmc.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gt2yvzajyue.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gt2xajxbenw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gt2fllhxnad.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gt2poozztmn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ritdtfpi.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gt2qujtekpn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2fkvnhbim.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gt2jgeywdku.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gt2cqjmuqpw.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gt2tehnvsfm.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gt2jakfzaqe.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gt2oitklwgn.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gt2jtrtsxwd.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2dxawunmm.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gt2rcjdcfhb.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gt2gcqqzdos.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gt2zaeiciuj.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gt2yumavavp.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2rcmlohek.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2hakfnpel.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2oaxpteju.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2tcgwqmcq.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2zilmjebo.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2rnysyupz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apzvxthr.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gt2nnxniasp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gt2ztmwkgnd.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gt2dxwlofvj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2qtahhaux.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gt2pzntkvtw.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gt2gceoqyxz.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2qgogywju.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gt2nsdvzxwk.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gt2ugskectc.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gt2lpkxfnvs.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2egbgksdk.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2wkcldfoh.html

[T40] Lua：元表
来源：http://dali.yongpay.top/Article/details/gt2rmzxnwdp.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gt2retfpklx.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2ujgcxfhu.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gt2jejokrdh.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gt2ffcgffwr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gt2qougnrrs.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnmeogth.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gt2ketgbozb.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gt2diycxcnq.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gt2fiufwqzn.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gt2lnkjmvfo.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2pdrhgcnz.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gt2ghkazvkb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gt2siqoixyy.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gt2udjsuxud.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bltznvlx.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2yelhxbuk.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gt2qhdvdtvz.html


<!-- 参考信息 -->