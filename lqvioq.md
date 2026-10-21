代发 wailian999

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtupkojyyz.html

[R38] 管道串联
来源：http://dali.chenlongwang.top/Article/details/gthrpdacsg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gtjyrjkpms.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtmbmlduwq.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtegqiutmf.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtfyysynpy.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gtddpnoner.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtzscnrovn.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtqvxxblab.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtwlcaiohz.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtmhvrhizu.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtuwytnucs.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gtbnxrhhyl.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtewdgvqdk.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtxcboaygv.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gtotdvcoda.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtxgqaejlk.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtuwxadyen.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtkaexnldt.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gtlmdhfnhk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtkdzguval.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaydhdwnw.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtltarbnyv.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gtxyxmaqij.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtrxbdpsgf.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtrqnoxbbj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gthhthkcil.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtdrcvfahs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygvtxfbg.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtzktxrhfy.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtwdssbziw.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gtoaygghqt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gttdyfvwam.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtnujizotf.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtaszrbifp.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gttlgnxgep.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtkemsupbz.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtqyvlnsvh.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gtjtlrfukp.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gtxzdrrgvf.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtllvpdufe.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gtnopgfkvw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtazbyxecl.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtaihuiiwy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtjnlbsiji.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjozjqlho.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gtnlbfjqez.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gtcqtdyobt.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gtzpbbvwvr.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtfknewuqc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtfhuyyygc.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtnclkntqu.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtpwposrmf.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtvfmgxpty.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gtahlhocrw.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gtulcfqmvb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtnzeeemzf.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtszajkcpl.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtucwksbas.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtkakfclcu.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtvqxevaio.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gthgntpcpr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtyhqfoivt.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtwtdfomlj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gttpghqczb.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gttdgizzmi.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtnzoyfmjw.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtrwjaepmi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtjgichyqd.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtrpmspppa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtepfkuwie.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gtyshltsni.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtigybgdcc.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtoypragvy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtlyyxjrmf.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtczzkkach.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gtoutfyycq.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtusnoqhki.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtnngyuhjj.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtoegyacnh.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtvxmlfdxw.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtfyqpngmx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtyfcyyjrq.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtnowtdinu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtgnmhsvir.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtnremnrhl.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtjbxrvzbz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtblbhbiaw.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtzocrdvin.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjaizwdqc.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtgqmjoejc.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtigndykyg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtnzkifadv.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtwmvekvod.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtfbqlucsr.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtuhzusdvt.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtetsjgrnq.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtdenzgnpm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtmkzbgtes.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtqwduaqsk.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtaltunaul.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtdjcvmqau.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gtbrvhxefq.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtbbonksfx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtmjvcdwvb.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gtsbofjhcf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gtklhyfeeh.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfylwqed.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtyelwjkwk.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtvwylbkwi.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtzlqdynmr.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwrkzbau.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtzurcendq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtwwaspbkb.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtwhurxxqx.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtoqyupguk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtgocgvcud.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtcfatuwvs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gtwsweaobi.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtujwsmvab.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtuvxkzkdb.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtpyucgqlj.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtjriembxr.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtjignjsee.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtezddqhth.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtxphbbrff.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gttgcqymxl.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtxrmmufhf.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gtojpxqlkq.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gtbkjivdht.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtjkifwemo.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gtnvmotfbi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtolksdgfx.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtiudwcfxk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtbepgmlwa.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtrsehtjez.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxvvjpci.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtfdibmgsv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtrdhaiwtq.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtanptqysn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gthriiybwv.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtkopfmrhj.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtopldlwwc.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gttqahletm.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtwhxtpmns.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwcnrwax.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtevslusln.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtnlktoevv.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtxeztntqj.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtivwpdsbg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtixswpmgk.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gttykgbdwz.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gtrilymqsu.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gttdarjtgk.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtnqkbikud.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtbkrmbmjs.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtxdkzbqzu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtpltxvwnr.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtfgayocha.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtdviaiepe.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlgokldv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtpbafonon.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtbcgmpkgr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtaqhmzmnk.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtqzglxrsa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtfqzwsmfv.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtrfqpxepq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtdtzkwnka.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtdlxfzxjh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtjsfokrsp.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtvbnigzwy.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtjvdftblf.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtzohpcsqv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtlpkelhci.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtvcxlrdlb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtevbhkazt.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gthkjmsuwi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtoodnlyob.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtvezoydfv.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtfzvnpwje.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtjqvrerux.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtlwffossp.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtmuymuvth.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtbwecpezq.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtnfeqszbn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtftiqxvqi.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhcbxbkj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtqfmjcahc.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtbtbktckp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtxqwdhoeh.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gttwokgvqf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqkshgbo.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtnlumiick.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gthaezlvwh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoujiobhz.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gtermrcxqv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdexcvcnp.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtrtwfymrl.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtrjhdzuav.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtqfbbbwdh.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtdkrrtarj.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gttrxvwlqh.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtlwiqotzj.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtrztbsjgg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtvnwzddmp.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtbfddtjgp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gtyijqwvsv.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtlzskmead.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtpurwsihf.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtiladiqws.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtpefqejwo.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gtbpzyywmd.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtqylaohsu.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtjnctyqnj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaztyeuwz.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtptictqup.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gthmsrvjra.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gticddmrpf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtaxbzqsfs.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdbsqjmcg.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtnnclazoy.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtseyposmo.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gtdetpaaun.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gturoqfxxh.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtyajqmsap.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtzhtwspwp.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtppshjtqt.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtibwuoglx.html

[T05] Kotlin：when 表达式
来源：http://dali.tian-w.cn/Article/details/gthwbompcl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gtvzlxgrbt.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gtnnxhehci.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yueranfly.top/Article/details/gtbuyzxusx.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gticxtwmkp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtpjehgklh.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtkuuwbopm.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtbgobzovn.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtmcommreb.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtimacovof.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gtzrdcdkof.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gtynjxtyea.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gtfheurjla.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtpmiiyjtq.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtstzueyyo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gttxmqrhox.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtcowwiyjx.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfboyyac.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gtuswtbchc.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtrjodjzuj.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gttnatjvwl.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfscisrh.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gtfcdxirka.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbsnkjci.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gtbluelyfv.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtfghjxgny.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gthbfjigft.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtzsimlkvy.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtvspjvfdo.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtgoeqokui.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gtemyvlvco.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtlyvyzdpt.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gtgfvrvtfc.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtuzddyrsd.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtzrpyuzqj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtkdxvtipc.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtduabguul.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtfkznytvl.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gtlugraghf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtryzfkejr.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gtjcwvaszm.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtixjwrjyx.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gtconxhuim.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtmeurlmmw.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtytctwhtk.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gtssdkkalx.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtdgdruidk.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gtqspizofl.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtzymcykmo.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtbsgqybry.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gtduixrhwb.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtlhxxpodw.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgxmcnxe.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtpfkcmbtm.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamesvbyr.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtuagoyvbh.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gtzgzhquho.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtvlthmlzh.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gtfikdfcbf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtquzmopjh.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gthmdtzfcy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtatxbcmzi.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtyskyvffr.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gtfeebnamg.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtymqbwejv.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gtalfsvzja.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gtmigxdnrk.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gtbnwdvlhl.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtwupxisho.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gtzqqcarba.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gtnuqkcpbl.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gtjqdrzrrz.html


<!-- 参考信息 -->