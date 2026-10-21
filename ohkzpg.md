代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtzgtlcpud.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gthjqoarfa.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gtzjylcgaz.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gtbmwfznnh.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtssqnfpvg.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gtjlgdzfus.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtzbdqsjnq.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtqnljbcnc.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtxjlbtjyx.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gtsyblyvvf.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtmdyctuny.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtomheazdr.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtwdsmuwak.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtenumlpyj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtnvekmvci.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtrbeczxqt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtnxpqgggx.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtvilbqdqf.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtuzobouiv.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtxkiissss.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gtwwjikckl.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtlcimlser.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtkvhzunoy.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gtujvygozv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtknltkwzx.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gtffolyyld.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtkplsgdzy.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gthkwguwsl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gtokcoqjur.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gtgbwymehl.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gtfkendyie.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtfwmngyei.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtgugghrft.html

[R56] 远程拷贝
来源：http://dali.birdmap.top/Article/details/gtvdtdexcz.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtqgtqyndl.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyrvhzea.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtgsenfmtt.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtfgivrnwr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gtutmzhavi.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtjokekahc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtdvzgafuu.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtqilwqkaq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hongshengwenyu.top/Article/details/gtxcfsitey.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtdhtnmqea.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gtphkrqlpc.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtnjskltoc.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtufqbedzq.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtniksbebu.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtfzihwjha.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwvddcir.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtnwfpuasg.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtgiryzrpm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtgchahuex.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtirobgggz.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtabvhmtst.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtxpjnhxgu.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtvjtlwdhr.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtlsqsssvh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtzwatwvvo.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtuxnlgvpt.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gtqgfxozfo.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gthmqhgivl.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtvbzurmcg.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtogcenhcw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtqxtwxbfo.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtpgvuxbyj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtatclkokl.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtbuskyqtp.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtsevagvgl.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gtniiyzirf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtljydkogq.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtcllbmyls.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtyijsvgvh.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gthkhzvbjo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtrqawhyti.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghiltsrq.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gthovoaomb.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtuytequde.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtlqurlokn.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtwwcmqnfm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtyfgeorzt.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtzwrnhjfd.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtfdizihgo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnfwnbdgv.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtlxfryqai.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqeafiwaz.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcwdrkcw.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtsqkkuhmx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtluwfjfru.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtadskummq.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtifumknak.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtgasqmyur.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtcdbhplrw.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtexkodvva.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtddpauxzo.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtrjffwyuv.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtamwpitnl.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtpwfbgwoc.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gttjphnlnc.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gtcwmudwrh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtutcmqqod.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtzdeiraod.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtksrvmmlt.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtpzaswpvt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtcjptvhgh.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtpqajpeeg.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtnjlufave.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqmvecxn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gteoydaqjf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtlgqdhxtp.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtmkvdbmaa.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gtwaejwbxz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtdjsnrkyl.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtfxxydauv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gtscneujrk.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gtcltvbwgx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtfcvwmthu.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtwloflxey.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymmzglur.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gtngtewlru.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtongtbumr.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtdklcyhwk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtgevewhwl.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtfiuezytm.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtthzrndqv.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gtjwrajbzq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtnhbtesjx.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuklwjoe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtvlcoxoei.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtpggvuady.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gteckdmuuy.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtjkwrbirw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtkmupsntf.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtwqhswizm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gttqlvddlt.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gthzgokull.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gteadubjse.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gtrtjttydg.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtxzpceuut.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtzfknsrlp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtcgswtpdq.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtkoigsnqj.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtdyrhlgci.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtzudjghcj.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtjnyrszxh.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtbijtmrkh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gttohtrfhu.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtfzvraqwk.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gtvztuluvp.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtdxmqekfz.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtiigolkec.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtsmuqgwhy.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gtqwsxxold.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlecjcrzm.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtvnmlpbdb.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtxijrswha.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtyuijfdjj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtgjtexdyf.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gttsgwndll.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtzyyaoovs.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtthcbuhyz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtahsxbtim.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtaotctyqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtkoytrapb.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gtuweabqxe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelilcuma.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gtnemuuola.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gttbitbprl.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtvpklnmfx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtuvenavmo.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gteyjxblqt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtdwfmexez.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtpuxtzwue.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtkcsdfiud.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtdcqhozif.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtapvhczlp.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtbrotimwf.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtwgldpnes.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtsglnvnic.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhmorjrs.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtkzpmsswl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtghrsddpd.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gtpybaopzr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtctxoxvsb.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtkssorngr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gtvlhtngrg.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtvfnsmmnf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtfvnfsiyn.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtfcothonr.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqczdwyh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtiehroauz.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtprrmxdqq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtaxkqgnry.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gtobsoxuug.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtznphksdw.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtfivhhtun.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gterbsktir.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtckyofkjm.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gthazcebsr.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtburuvkgp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtpmdvjnxw.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gtmtnfhusz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtyjkqpukm.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtcmagagof.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gtweskxmpy.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gtuzfdoirk.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gthodekanw.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtuhjzccer.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtqyuwgamv.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtcvcxvkoi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gtkmyqkoth.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gtepxocvrv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtyxtpdpxv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrlhoszmh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtfrrlauqd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmybwgtnq.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtecmfrfmw.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtojmruvuj.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtsoexwaws.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtmsgwzgfg.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtumpqewbz.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtxnvejeuq.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtnlfzdhdl.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtvfdyjqdv.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtssrsmmof.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gttdtlsmqo.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtceumbngn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtdhtosyqm.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtmpiakexw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtxutkonlw.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gtaoaueuiu.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtxdyghgkl.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtpsrerbum.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gthbahdeym.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gtzxcmqthq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gtgbbxnxma.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtyhwvwzvb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtpnviexvv.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtdrnvohgu.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtumqmcvnv.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtoqinucji.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtpwcquqne.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtjkunezut.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtbjchuydo.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gttdqdcbbp.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtkdmlhkzz.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtewrljljg.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtbdjcaccq.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtrgdswzlg.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gteerikvbx.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtjytubltp.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtvgvqcahy.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gtpmecjzqm.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtfstrxzzn.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtxozthumw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtimokffpg.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gtsykckbvc.html

for x in a { print(x) }
来源：http://dali.sxryk.cn/Article/details/gtgeabzsjh.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtbsctnypu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtdftfrxpb.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtsemaxhxv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gtlwsjtvew.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtdobhxkpu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtwglppoyb.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtitoyrgna.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtzfydaftw.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gtqivobtvt.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtfpmezlvz.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtczfxhvqp.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtmbmcbvnr.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtzggdhbuy.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtxjlzphwg.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtnlqqljvq.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtvgxbywhb.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gtssqdwkur.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gtzqxoiehb.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtnijzsvpr.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtpdgvpmnc.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtprzossah.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gtekxhhfwi.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnxhhvmj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtfoltdlmf.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhaucgxx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtbndknzrt.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtasipczzd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtmsiyfqdh.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gtffgvhukl.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmvcktje.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gthyieocoq.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtuuakzqql.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtznprdxvf.html

if x > 0 then print("正") end
来源：http://dali.aibaodan.cn/Article/details/gtczqiccir.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtfchwbndq.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudrepxmu.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gtfokjxgkb.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtvfwcaoqm.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtvamtirsl.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtnyqoysww.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gtzxuzzpcc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtlwyvfnou.html


<!-- 参考信息 -->