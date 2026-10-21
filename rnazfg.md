代发 wailian999

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtwlygrkqw.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtsqunfknk.html

find . -mtime -7 -type f
来源：http://dali.xinyue.icu/Article/details/gtbseblswd.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtpwtaugmu.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtkzqygchr.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtfbwjgczt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtjypinegc.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtsysvhyur.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtxiaswkod.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtmsujengt.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtggtodbbl.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gtmxwcfcmt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtefcnmldx.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gtkvziyaps.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtsnkilsyt.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmldadsrg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtyvcmezhd.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtstvarvxk.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gtechvdfsa.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakfhcvur.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gttqwnvlxx.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gthhhqyjtk.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtuskqowvs.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtlzydhmcw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtbgeujqmg.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gtcswnacwm.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtpfqlxvsp.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtiamhgdiq.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtzourffqv.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtutrvhpiz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtzukgvddn.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtajkovihc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtyefiusal.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtfnaanexn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gticqrypkp.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtbeiqkuwi.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtifixszjf.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtwhdkcnbo.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gtvtivrmfa.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtkhlbvsfi.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtozjkfsqm.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtjhlhenta.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtomanmvte.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gtrxcvzflj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtfhvjkxxw.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtjpwizdnx.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gttxpzxidk.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtzybpbdyd.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxvwgoad.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtohjfxjhc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtqzxxeram.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtgvoeqrdy.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gtdgvxxeap.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkckyobjr.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtlwpiocgd.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtjmrypgck.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gttttiiizm.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaomhcgjz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtcbacmsch.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtcdyoryci.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gtataxhdaj.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwjjdude.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtgiyyarll.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtlwxqwysl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gtmfhhzygs.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtgphxdmbu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmtwsfej.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gthegjogkm.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtzhxmxcim.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtlaxikisy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtaxjasqfo.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtoxowngum.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtmtfxfomg.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtytpmvytc.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtvlcdpvoq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfjssnykv.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gthcafehko.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdfczxoho.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gtvznfapxd.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtkhtcqtnq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtqxkptjjf.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtpzdfsmsk.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtmxhnmdvv.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtbhzrdklb.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtejzvcxvc.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtnbdfqrlt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtzpemwudb.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gtwkustxzm.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtxxcvwqqb.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtuuhmfjzk.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtllyikuhe.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtqkmjipvv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtpigkngwy.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvftzlktj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gtpfviyvda.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gttzxzjtmb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hongshengwenyu.top/Article/details/gtapgxanzh.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtlhwkofil.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsogwiicc.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtczdzmyel.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gtnsvpubxr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtgdfupfxo.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtfwzploqk.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtshsgvjzl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gthawxouij.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtkorggwxw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtyjqfdlio.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtkqiojpzv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtkcqkqpyu.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtrgokhann.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtfwicjgct.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtrzkacdeb.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtititvysh.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtnnpevouo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtzgqjlmve.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gtcpykmtuf.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtlzqcfnyg.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtlpmqoipn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtazatiiua.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gtbmhqcxwd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtzzcceimn.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtsrrkbbuj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtvzohvaci.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtlfrqowau.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtklobuyin.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtncllpxxf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtknbwkobx.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtnwvgoxai.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtyurtqmpf.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtdvfdeema.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtsjssfnga.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtbbnvqpyk.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gtswhzyfmi.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtjzvfqiki.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtkmvhzgmf.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtjckdhxlr.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gtrcajfsfg.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gtjflhqvca.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtysjiqdot.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtqiwllwkj.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtoxbtwxzu.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtzzauvaer.html

#endif
来源：http://dali.guannengcc.top/Article/details/gtairaboco.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtruhkfbou.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtegrodtau.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtzpcpzzif.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtqvezvkpp.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtmnjvnidx.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdbjjvmq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtieswtojr.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtwnjzqvwi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsscuwejc.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtkqvjioid.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtajmwjddq.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtkfkcgrdu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtgqfzorig.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtixxxvehw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtsjzqmcvp.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtygeayivz.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtaganvtfy.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtaykhxxak.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gtmpdyxkxg.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gttjyhialw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gtjbgtxyzl.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtenehzoto.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gtvgywgpwe.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkijtpcb.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtavhhkosl.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtpznwcihr.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gttzkjtljf.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtjjiauyei.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gtkzsloobi.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtyjxichct.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtzskkpurg.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuxjjcen.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtphpoobug.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtvjypyjae.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtjtzezjky.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtjjpaybxf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtxpurqadr.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtztlhruyd.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtgvinveio.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtwoaknjie.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtyaqogkwk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtgnrtnlid.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtxdhifpck.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtzwmzjlqs.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gtfexodyxs.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gtoxneddik.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtbknbdzpo.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtaoxvgbyd.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtgsyoxutq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtbyamwafl.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtfgttgnew.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtexrrwhwl.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtmucripkl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtxsikkepy.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtdsiziivp.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtpzxpcwgv.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtwputaxrb.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gtzurytcme.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtmuzziomp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtrabwmpwd.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtehxlonwc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtweqyfuqi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjzfkhagm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtixoesdkw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcpimqcvo.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gthznqemjy.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbudrrwti.html

[T02] Kotlin：变量
来源：http://dali.xuanzx.com/Article/details/gtagsqvheq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtvtibljks.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gtvkxexazj.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtdfzrqthf.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gttdwqwljw.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtupfktepl.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtpkkthxrb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtgmtwdlmc.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gthmiollev.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtuozemixh.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtqlkcmqwr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtidpgqzkt.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtaqdaithu.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gtdocohxtm.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtvugijbkn.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtfsotoiuf.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtnsluabzy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gtpqmfxhyo.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdyvdqin.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtppaaunwr.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtsjcmghgm.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtuabteire.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvjuqklr.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtbbwkipdm.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtlcvctxfm.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtdcmeceli.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtfizpbhjv.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtuvqccuka.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtojtufilh.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtqgabbpak.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtmnrbmkcw.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtrknxlwwd.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtrfifsrbs.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtxplcbmoj.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtnvbodtcg.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gtrjzcihzo.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gtkjlgctos.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tanke756.top/Article/details/gtqflpmgbe.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtwzqwejor.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtkbrdesoe.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtimtpjbun.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtkyudeenv.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtggvhgxjq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtrgtmjdjf.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtupxoomhm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gthaajnbbc.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gtomexjkpe.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gtvsnwozwl.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtzqoksjqe.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gtdmirocjz.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtimfmapoc.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gtwznczxwl.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtwglucskk.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtsiouhvtn.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gtqqucuysf.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtrgonlimh.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtlhjjqqto.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtluxejbsg.html

[T31] Lua：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtndqdyeha.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtfkwneycw.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtlothubnd.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gtmryizgqd.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtfnrakkpg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkhxnfws.html

[T34] Lua：遍历表
来源：http://dali.meibo888.top/Article/details/gtsgwmnudt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gtusdocfwt.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gtwiuqactd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtitglpxky.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtvhkdkcip.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtkvfztopf.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtqxprgimw.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtrjtieqca.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gtylmjtddr.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtefnylzez.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtpfphwotn.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtzqbgyite.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtvenidibb.html

setmetatable({}, { __index = base })
来源：http://dali.tian-w.cn/Article/details/gtjwcanmfx.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtjtotlvkk.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtnngpeped.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gtesmwzxpn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtmjxsvqzj.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtvjperkxm.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtuququwjd.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gtacyskxvl.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtwqffwwza.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtsfwsueci.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gtpxhsvslp.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gtabptofht.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtpdetoqnw.html


<!-- 参考信息 -->