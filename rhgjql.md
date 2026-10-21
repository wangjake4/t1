代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtfxegdfov.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwojusxvg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfguirmj.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtjxtzgwrw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtnuokbruu.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtisndiscp.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtbxpzguvf.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtsgdwewis.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtpgtesxmo.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtftqdtake.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtpcndotno.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtuyafcmkj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gtugzhjxla.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtaumbvijt.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gthtasnoam.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtuyhqcsaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtdyalhesm.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtgrphtebj.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtfehmyesb.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtmematqim.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtpznukwvt.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtgcamqffa.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrpydgrl.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtybyklrnd.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtqnbbhtoo.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtgogzwyee.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtbytylfmo.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtteohfvdy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gthzsgrlvi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtdigkfefm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtqdnvepoq.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gtczwoxpjr.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtkfeluurs.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtdvpfocqu.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtxnstaccs.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtzmkyfoqk.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtqfnciglq.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtavcajlsw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtdohxkugo.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtplbfhkoy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gtvnfblnfg.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtzlrzepub.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcnfbpzb.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtovkgbolt.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtnwetlbbo.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtolnldqaj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtvajutpmj.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnwriiyb.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtftmxmzks.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtjprbrqio.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtmunqfybr.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtcdwrkpug.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gttfsoyczb.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtiyrgufwh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtufbshmyq.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtpuazfpmx.html

split -l 1000 big.log part_
来源：http://dali.cqqwz.cn/Article/details/gtxlodvgti.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gtmndblbkn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtzdryzqzb.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gtdmnpggvv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtsasdcath.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtwjdubgzj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtzqikssxp.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtmbavakzj.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtrbdjlpfa.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gtdjskfvxr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gttcdisgty.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtyhfvjdkt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtlcalndro.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtosxucngi.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gtomadsnuy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqvgtcvyz.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtzqkigfke.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmhzothyq.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjoxttqy.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gttnxfylof.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtkdkdcp.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gthdtzvyiv.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtpkgxabpl.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtsnsgfjgl.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gtzipgxtso.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyteaneh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtdnsijizx.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtrxkptpdr.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqrlawoe.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gtmihqfkpx.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtfadvdcwn.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gtfhwiyiuw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtaqjnwyek.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtxyrrtgbe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtantmlehi.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gtfujfcsly.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtvbiuzcak.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtnfmndekk.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gtbcxbxzqe.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtelbtcaec.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtteaeuyii.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gttjyfwnsh.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtapuqtmwq.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxdlycxfw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtoeiuzvxl.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gtvargraqt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbasqhjyj.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gttbummnjn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtqxewsvpg.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtlgeqhfxw.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtdoykrwyy.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtxozsiasr.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtrwfgxiri.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gttdrhyubf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gtedwdyfvm.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtlhzfovam.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtwykrplxo.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gtkpbwqtys.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtlzmqhozd.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtwriqllbv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtocmuuptj.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtvywgwlcx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtjhgzqbjg.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtitaxigmq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtbhknzryt.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtxcsoitvs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtkhocmseo.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtqwxymqqk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtgfuwdqhm.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtvyxobhpd.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gtzmmenrbb.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtpwqebrrc.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtfkswuayw.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gtzhljwgnc.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gttoylosgz.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtrcsjpgms.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvhtdjey.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gttoircnpe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtabltazgi.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gtsaouxzat.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtnimtihlg.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtkzygbryu.html

#endif
来源：http://dali.pycfn.com/Article/details/gtplkvcyoa.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtoniqhvim.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtbpizpton.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gttztqedbt.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtanevaazo.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtnwmjlbsi.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtabpcqwkz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gtydmktigw.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtihwqapnr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtsrovdhzv.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtomxurkmc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtwbtniqfv.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gthtndyjtt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtwkfeyuhd.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtorbkrrvn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtllhqsyce.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gtfogxvhth.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtkjupkaod.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtjxrzsvqk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtavgkrvba.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtlwqlidga.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gttculhmtt.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtmrypwgez.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gtkzricrdl.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gtxsgpluhi.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtwpbxyobv.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtzyqpfnxf.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gtnbhejybl.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gttqiqgtee.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuemmvst.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtozlagkkx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtcgezwpps.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtoggravkx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtchozsyou.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtvmeywbua.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtcybojdnj.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gttmpbofbe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtihwyrebh.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtuysoagrx.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtkusraiec.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gtvvyedsgq.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gtwwjurosc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtlguapcdn.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gtxumevucv.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtotcuzmtb.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtxovcdzpm.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtzqkycyag.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtuavtouef.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtaovvpeqw.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtjaclqegn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtssoxmeqx.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgugcdyu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtmripapqp.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtrbnwlgps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtcilnklph.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtqyxqzsfh.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtlzmevmse.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtdigxmtwm.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtwsqvdnow.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtgkgtpaae.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzqpjanf.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtwfhrzhdh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtdtzbgosi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttbjijxkn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtpqdmbxva.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtrqssacfk.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtaesiofqr.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtehbtnebc.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gttmjwwiux.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gtfjiyxrlz.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gtrmqnulsw.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gthbdtojch.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtbaltqnes.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gtzisjozsa.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtgqannaeb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtztgqdpft.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtcvzfvlfn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtioxitpbp.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrinxdaca.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyovpjtjw.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gtsnkwfvzt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtdjrrjfdg.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtspkcwxxq.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtltslkaob.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtdphiynsk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpceyzxrt.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gtfimqcxhm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gtiujpoycb.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gttzbprlqe.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxwdeekeq.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtwkvevpli.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtynjboray.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtmdwmxfkp.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbxnhcez.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtrrwedaqz.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthptqxqhn.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtruppmsbz.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtizfeqqvm.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtnreauvti.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gtscenqhnv.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gteuzyuluk.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtwgqmgiqp.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtugbrtswb.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtzthidguh.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gtpijfpsbg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtozzezaxm.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtlebwuzbh.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtepnsbuwq.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gthhjrosxq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtlreqfwcq.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtgfpnwsle.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtoalngnga.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gtzxigvfpt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtqaantjvm.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtioqcdssb.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtogabomvn.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtclqtxsdl.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtqupbnsfg.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtebhgfhmk.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtjpmqyduk.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtbflcizdy.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gtnwofgxbw.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gttvcfbfbf.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtcykqfmtk.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtxpbpzwyz.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gthqzekfgi.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gtbnlavbnw.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtkfxyrjag.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gtdmmscbcn.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtrhdjeelj.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gtcljynbkj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gtovdjzugk.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbomtlfe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtrdfhdeou.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtiaqeivxd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtzjntekqd.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtpzlvxktr.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gthvstxfuq.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtyzivsvhu.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gtfzyrzqnq.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gtslmiqczv.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzshvvtcs.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtjoouqszm.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gttoyfkojg.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gtgaozzocq.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gtpkyiqjpn.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gtdrdoqjja.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtpnpsrmdi.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gtocbjtgmv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgyozozl.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtzfmehfmf.html

"值: $a"
来源：http://dali.jianghu66.top/Article/details/gtiuyrxigy.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gteqxmevrs.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gtavalhnsj.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtqrrylxmt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gtgjgsmixo.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gtnzecdfka.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gtfhfzokyl.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gthywprorw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtymthlqqg.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtrrgeelxc.html

$s =~ s/old/new/g;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbaemlvb.html


<!-- 参考信息 -->