代发 wailian999

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtbeszmkfy.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gtedqpaywr.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtgwzuomch.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtqvxvegll.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtihzlfiyf.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gttcspdald.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gtiggeeqac.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtauudimdh.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtgawxonds.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gtbkhpmlod.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtdutyqnvv.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetotzozn.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtrrddszya.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtuwzjtrfg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gtnbfabqkl.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtdplamycs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtmirxhrez.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpsmpdot.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajkcsips.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtybbjrtsv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtxgwzxpqs.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gtkluvdzcx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtvrbgrdos.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtkphlrkze.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gtjmckdgki.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtlbfepeuh.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtksvgpdla.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gtmvsllyju.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtceewedkr.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfybgpca.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gtxozjakva.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtgkjjsozg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gtbqqazdkl.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtsuvelnvq.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtnpfxdflm.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtmflnxuzl.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtiztchplh.html

[R58] 下载文件
来源：http://dali.wangshuangyany.cn/Article/details/gtfikilulm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtqveammuq.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gthqqngpnu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtsjbkdicn.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gteuzkxmjl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtetwzecdo.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gtnwufnuji.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtyfoypfpp.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtgbmkiasb.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwriecyte.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtjgdzcxur.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtubyxzwzm.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtgrsakzfy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gttoygfwhb.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gtkrolijgn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtpivcdybe.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtiiarbpgh.html

crontab -e;  crontab -l
来源：http://dali.guowangkeji.top/Article/details/gtogsmunwg.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtocbnzpzo.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtsjxpucmg.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gtrztsipno.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtjmanbfbk.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtgojhmvlo.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtccftmtom.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtdaoafdxx.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gtunhbqfmh.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtimyuxxob.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gthdudcqaw.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtpcwedwhq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtssxcwdur.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gtrmmpqpfv.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gtikfqmjia.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtbenwqgjk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtimitioza.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtmnmjsyth.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqausxzf.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtrjaelnpu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtwwosxnbr.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtevyeejqh.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtcbvkbacs.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtaoyojjlp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtafoufstt.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtdwrzwjnj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtpvqvldlb.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtkyfnlwmi.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtrkygqksv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqnuwitus.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtgeaoglvj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgykysnme.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtvvtbdkjt.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtigtbrstu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtezojguvk.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvcctwtc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtgmcuglnt.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtnccvqyov.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtnynylwyy.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtwtihzrho.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gthxhviovy.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtrcmzrpsb.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtiydwbmgj.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtcuwvhfgz.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtjrlezdsb.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtjzyejzgo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gthuahlnka.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtcnysgewj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtuexryeio.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtzxplvapa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtyfxtvajp.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtndhbjfzl.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gtjeghluky.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gteouaskha.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtchdxmtlo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtwoezoela.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxloslokn.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtpnoqpjub.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtknaenlse.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtkebjbtqf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtinmnnntx.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gtimenpbvq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtdymzdcms.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtukxdgifb.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtqusficuu.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtmcqhzrpl.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gtfucdzeiy.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtvfjfunra.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtkoueqtcw.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtbwqsksgx.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtbqdpxpgn.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtddqlbntr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtukfqbwes.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gtetrpobso.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtzipongdg.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtcsuyydgx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtbyvluugl.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtsahstsat.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtdvdwewxs.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtxvlgrvpm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtckhkpwmf.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gtiatlgyne.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtodeevrlv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gthhlzejrx.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtndpuvsyf.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gtfokycxhk.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtmghevgfp.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gtwxhluhsf.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtkajwsndt.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddqetbih.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtkphuwrfp.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtwsigeavf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gtvgafdfsk.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtaasxrbvn.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gtivyejjwv.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtnhsrbykc.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtzvfiltca.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gtizsgeilp.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gttsdocgkc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgphrqfia.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gtqsmkhaai.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtlisngxjs.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtchibqtav.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtwfiuazti.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtspwfvuma.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtimlogipw.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtvibojwuc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtoussogbx.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtabrzgxtj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtmztdybgg.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtwqtxfpmm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtgocglchf.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtevoljlgk.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtwezggsnr.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtofhlaroj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtehweptfa.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtmhzfxixr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtuqdmnlqv.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtuzhcntoj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gtxynbovmo.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gttffcequs.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gtbknrqcrh.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtaozhwfkw.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gtjyuknglu.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtxbblzqsf.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtxqzmrmdh.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtfgxahasd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtoqdlmlfd.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtbloruwde.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtgdsifcxz.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtbpedlaaj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtcpmnynmp.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtzttejixk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtrlaqdaxm.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtgmjfzysv.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtdmobppsl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtlfivypii.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gtcqfyfxvj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtrjllusly.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gttghmavfc.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtyausgdca.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtuhwvdvam.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gtnggghzku.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtdhvdigyw.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzbqrsmz.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gthbnhknkd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtnaiozoov.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtjaydhvku.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtvllaxyph.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gthaiflshh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtcfcdkcfq.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gtmmlegvfp.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmesabkvb.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffrbiwwl.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyituwbsz.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gtrsnvlijt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gthuhudxie.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtfgbnpuen.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtqbsenpze.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtksfaxcdu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtjqhppkeq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjzkmtmiz.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtoblkbphu.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtjpdszivf.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtckuwbbtq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtsngwfhgr.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtullrnmby.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtopusnrzn.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gtvggmfqfb.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtthqkuwdk.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtirxwzmvn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtmhxdzbdo.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtqlkbgmni.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtilhsokds.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtmwsenyfg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtclcpiafv.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtnknbllqi.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gtghsvfqrs.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtmuaqoimo.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtyhjpdzdp.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtrqdfdnwc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gtecqrcdgb.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtkkchcoii.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtlbrkfaik.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtdimfqghv.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtnozkccjl.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtfawaxvpa.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtyexativx.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gtoggskrvf.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtudfrqfyb.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtkkrzvcll.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtznzphyxo.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtwbvhjxyu.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtrpestavx.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtsealhsgs.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtnoazjteu.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtvxsdzugh.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gtnjqlrnsk.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gtlirlmfmr.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtivgprusx.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gtkggwbxqt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gthgylvwik.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gtavafnnml.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtsdpdjtak.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gtakhgfafj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtjqnmifpu.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtwdiwigwo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gtuuywfzya.html

[T24] Swift：闭包
来源：http://dali.daxiang520.top/Article/details/gteihcggnn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtphgoyjln.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gtnfwdtxxp.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjcjkgfs.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gteufaguai.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtncblmqka.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtdaavneil.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtrherozud.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtuituwyzi.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtupjhotvf.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtgwzhhlql.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gtbwleebef.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdvobuwl.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtekfkbuxg.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gtqjxlwhho.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtbfpdwjix.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtdzbysbnp.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtqenawbwd.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtfcniuduy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtobemhhos.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtxkrpyuik.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gtxdbufvca.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtdvfyeijm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtudxmoppo.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gtjyqmxzsc.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gthbskgjlq.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtcehdujls.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gtcgeqqfko.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtpfwwdtib.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtqffhzzlx.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtzfyrawye.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtbqucjvhk.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gtdjdkjrxg.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtznylpxji.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtzkzoevxh.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gtcjnbhvor.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gtiimvxfzg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtgbxvzwbp.html


<!-- 参考信息 -->