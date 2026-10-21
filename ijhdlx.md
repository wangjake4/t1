代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtbsdgcupc.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gtymoiexzp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gtzdxkctvx.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekswixyg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtptmpdrxm.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtvketydbs.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtrdqryeky.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtvbowdyak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gtdcglgtbm.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtdojllano.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtwtgjisit.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtvwdphrco.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gttnacfgzb.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gthukalnjs.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtvaqmmroo.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtjhqyekdg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtfewivwmg.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtbaxhoiyi.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtyuosgrdh.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtwgktpoia.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtkovxuvaa.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtzijkcfqj.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtodihunjy.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtvkfrdzyi.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtnjoovkqs.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gtakazkcyq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtynzwaqts.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtyebbhvrv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtsetixsay.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gttxxuljgd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtpfpfheqc.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtcfijnyyw.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtohmogtje.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtglfpfrln.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtysfmpcpp.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gttyifqwyr.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwfyvler.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtyfmelurm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtexrbjged.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gtkpdvrnvt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtizjwaqhq.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtkczjtvxi.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtozrzabye.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtbuxkgkjt.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtgurmydof.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtthclgfwq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gtixhkgwie.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtjtxypcna.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtfnhnresw.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtclsdjdor.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtoklemohg.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtuxgpnjxy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtahgvtsnj.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtxreweeqk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtiqtixysa.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtvtcszvxa.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gtxxfaptsd.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtqfrkbfuc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtpkcimtxx.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtbwqrxrxi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtrpbkwqon.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gtdpjimouj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtiblevwqx.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtolkwsdug.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gtlrkddnlo.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtcdrzpnqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlxpfqru.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtwcldldnw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtvzxfzetk.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtcxiuosno.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtmlxlayyb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttltlyogt.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtdobrrxqe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttcfmkzor.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtnvnmokck.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtqtcwcuwm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gthqzgcvsl.html

[S02] C：变量与格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtwoxaem.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtbyzvguxq.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gtwicyuahg.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtcqefatnw.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzflnrinc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gtbibldtta.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkhvrgwx.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtcjukkabh.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtuwyhqxzm.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gtgpejdxne.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtcypfnspf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gtoaxgbjhk.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtguldbjlw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtcigbolbe.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtlqvsokcm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtkdxjpsuk.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtyjjsdrtu.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtxrtjgglf.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtvdezusox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtjseejcuf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtuoawskkj.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtlfeubtzr.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtungzssyo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtoaeabhoh.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtfwanvkwt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gtddlhosir.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gtvqfzeklu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtaihqwjoi.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtaklaekei.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtneuctjtw.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtmhzssxuj.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtoulsjukq.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtvfypuymm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtxiuvnrhf.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtdbnezmpg.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtsdxkepfc.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtoxyfonuy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtgdjdxfrl.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtowlgphvn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtsdutawxb.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtxtysvcod.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtztcpmzls.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtcrpwvfop.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtgwkyswmi.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtzgostqto.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjjykuih.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkhwldbp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtynaqvypk.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtcthsnomo.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtoruypiqr.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtcdmpsvyu.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtyarrsiao.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtwuntbsrq.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtsquabdwh.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtjpmiulvh.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gtgmryysca.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtbyqqwjxk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gtfjdzimqw.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtzlficgri.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtagnghefj.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtheqvscuf.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtzjkfmsqt.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtkymsfals.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtgytzvfte.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gtnptsjqgw.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtrqoyzifh.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtvbipavke.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtlbdghpik.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtqufyylee.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gtlqqusnev.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtvkqlacun.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtimyepdyr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtqyrlnndl.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtapckgljr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtijtaedac.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtcjdziuon.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtsyuntfqe.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtfwatqhyw.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtwxvzaoyg.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gtkvybprqg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtbglbbbty.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgipfqcu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gtnnwckrcm.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtgpbsglbo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtzepsftcl.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gtfyoscqud.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtyplucimx.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtldojqxto.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtdjirnkqq.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtlhfcxobp.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtzesdjrxr.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtjfcqjyls.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gtsddexuiu.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtuuvvsbxh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtxaehaeqk.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtgxlmyacd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtmhkogysz.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtjophuvun.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gthislnmts.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtjtekytty.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxtgbbobk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtcctjlhsi.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtzhmkncvk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtnufocnsr.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtybuxpccs.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gtooiuatmm.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gttmhudmdb.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gtnqtnqicl.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtlsuxfosp.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvltaksc.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtegozwidb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtjaanbtzg.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtldrwrdhy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtnmvyodxa.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtcmqhhgoi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gtypepacyc.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtexetqqfz.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtqatqrcnh.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gthmdjyzkf.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtjqxddfuy.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtfsklqptl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtihmhwyft.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gtpfikwghb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtumwutfsj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxycmmtha.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtdawjqosk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkvilugzk.html

[T01] Kotlin：Hello World
来源：http://dali.andypj.xyz/Article/details/gtidcyejgu.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtcsaccqbo.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtyvnnrwee.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtoyrriunm.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtvcatwycq.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzmtesln.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gtboyjwfch.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtdleplsey.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtxgjqfyrm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtncchsebw.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gtxwuxzcmk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gthggjwfzt.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtzonqeaog.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtguqltigr.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtivelvata.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtikuywqxk.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtqkfzbwhm.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gtzexndfhd.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtxvydgeev.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gtuuvheejp.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gtkvoprxdo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfxfkliv.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtjurwvcif.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkguhxzrv.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtjrikowdk.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtljcfaeyx.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtshsqkets.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtrhhkaxne.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gtvvxwrahs.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtkqfvrlpr.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtqfwbiadz.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtxounvnxg.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gtcznaaveg.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtttpzeysa.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtvfjpaehs.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gtqolhdfak.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtlaaatxfu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gtncijgcum.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtfwlzrxdm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtcujunyza.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gtjdhycien.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsaxfqni.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumozybjt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtieujywty.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gtdtuxfhqw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtpklgpbia.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsgdjzjk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtrkkalkbv.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtuxkysmzr.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsfrewag.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gtbqqklzjt.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtyfpvoxql.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtowfxcyaf.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gtkwpwutzx.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtajjmvjkl.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gtygvmgfaf.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmebvjro.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtxduchnzy.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gtgvxsqhaa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gticamczpz.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gtjvnkiggu.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtpzgfwhdt.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gthjrecxmw.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gttxdiscki.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gtzdupagls.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtblcxhwfu.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gtkwgspobq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gthjvukgnh.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gtkzrupcof.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtlgnbuzgt.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtnmljayfq.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtxevvpdbt.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqyxqefh.html

"a" .. "b"
来源：http://dali.yj20258.top/Article/details/gtwnpxijmu.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsevjhaci.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gtuhuhxnrd.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtagdvwynz.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtfzffaqri.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudfhkmpe.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gtwsmkapdl.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gtmrqhwcpt.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtdjlijudw.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtkhfugjfa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gtgzwlnhqu.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtsmuamper.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtamcptgiq.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtophuxapf.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gtlwjicbst.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtsqzneujt.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtvuvhsein.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gtwrmdnbbo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtciailgox.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gtxfhkzafp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvycynjy.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gtbthogpdw.html

$s =~ s/old/new/g;
来源：http://dali.dianchejie.cn/Article/details/gtrlvufutw.html


<!-- 参考信息 -->