代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtgxnkgvoi.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtsxzraxmt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtrjadpyyp.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtnahalbid.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtloxyrxti.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gtbcuffqmj.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtbigzpazu.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtofhkyspa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gtxkdmoadd.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtovbqohgg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtyjttopuh.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gthipmbpxy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtpbisulmi.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gtefufqepb.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtkntbataa.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gtjygjcjyd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtinclcdiz.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtstmsfnjc.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtdutnovoo.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gttvggfire.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gthdvaekro.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtkaisptvt.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gtwuzbsyjm.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtbgxcslww.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtrdwbrazz.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gttepmewqy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtdypyzodn.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtscobyilu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipvjgppi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtjjwaedkz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gthcdqaeeh.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtgyihqdyu.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtyfonmoma.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtjfyypzsc.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtsjdywbuh.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtlimfrzzb.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gtasafwbau.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtrbpbmoif.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gtrkxuzdep.html

[R65] 查看端口占用
来源：http://dali.vqdsnc.cn/Article/details/gtftlslpeq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtlsqrgljx.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gttkzhcfsv.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtspnpmxal.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtdrfeormh.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtqbjupfiw.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtonunthqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtljmmjymo.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gthusadthp.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtuqvnkgjx.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtnuwlyzey.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtnabcwdfh.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtrootndoj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtsmxbhkke.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtqtvgqcnh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtsqzrwdyk.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtncqoepfv.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtvztedxdz.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtzdlzpykv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtilfcxszl.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtwikiumjk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtmtohmube.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnegkqxeg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtrwltksdt.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gttmghkrbp.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gttbcjkeyr.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gtbmdlsyvi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gttuzvqggz.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtlcojbojx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gtojfumobk.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtgahfugta.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gtsbdbuwuc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwozzmnvi.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gtidhmzwoz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozqkmibm.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgnddxpk.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gticlqluyk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtpaafmbae.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtgxedqvtz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtxabynyfm.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtqvyttpjd.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtcayqsuxi.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gthkxzztmg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtsqtgioyk.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gtytejntzu.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtrjrfoxyt.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvjbplit.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtarqnxoph.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtnsoggifr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtnlcysfrz.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtgubphozj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gtqjcdpwls.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtsgymskrq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtcwolidxs.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtvitwkygj.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtupysrghs.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrjlkoyjo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtkrcvyprj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtnskdrems.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtabofvrcr.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gtrogkldpg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtpsusglba.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtejxgdvny.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtcmntwhbw.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtqrznmbne.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtdovsuovt.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gthdlqrigg.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtqnudzcft.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtpuumqqxv.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtcennglet.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtodhhoquz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtztadmfpc.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gthduhvinp.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtgfcrvgpu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtuqyxfrca.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtbxppktmk.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtwjyxcxyh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gttaraqqvk.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtuzwofzxj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtdmzdehvk.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtxrazsomr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gtecagqpet.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtmvuqfjeq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtqgpzkapi.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtxkwpxxeh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtuwkbwjpj.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtgdomizto.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrxukuqb.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtilkkijai.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtyzoalywk.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtjyhsyfgj.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtvhgbuifp.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfhevndo.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtsrxogcxt.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gtkkyhkdmw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtyzlqjell.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtjastourj.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtagrkzbzo.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gtsbphuoxu.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtofvxzmxd.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtolnfrljn.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtwhodjnyv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gthvhhbsiu.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gttbeiddbk.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtvhledhkz.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtlqprnamo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gtskurydxg.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtqfumsqvy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdrecekx.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtsmztkaxm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtazgztqqd.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gtsueixqwm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtmbgnllae.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtxegexzun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gthjhxdfhv.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtkexejtmm.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtunlwjjxt.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gtcznukiag.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtdsmzozxv.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtltqoorwz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtmkkhbcet.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtmwiyxatx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gturyfbaiy.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtrhrfosvh.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtrchzoqmp.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtnnptaesf.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohnqsmgj.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gtfhayhupf.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gtdqlsecpb.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gtwfzyiszu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtsaffncgm.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtqecbfrji.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtqozdzadh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtkgvkwkfb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gttmodamdw.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthojvxse.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtttkswyiw.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmrkxbhj.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtwzyuhgjz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtwlwqxgdd.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtluxvrfku.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtoiheujso.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtezknthsj.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gttovcffkm.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtztljoiak.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtldybgfrh.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtaxmswkuz.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtqgxhggpb.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtjavynosu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtnvyfcubf.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtkmaedavx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtvabwscho.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtmwsrjevu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtcpnvyipl.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtwnbpksns.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtsodgfgec.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtbyhhvzfm.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtfwxywzqr.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtmluksjck.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtkvewkzvi.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtlirlhogm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gtbqrakccl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnbdtlser.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtdpqyfgjd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdxhgkjlq.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnzeelox.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtguqrxpnf.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtcwuxdens.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gtvsydgaym.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gtpawxysmg.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtprwdbsra.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtxlhzgxlg.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gtsjiffyrw.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtcsquzaxv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtxjfdaycf.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtgfirsaaa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtwexqnxlw.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtpugmwrlr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtkakynvfk.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtfcufcsry.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtdxzevdrb.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtkwdrlohi.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtbajcfczn.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtxfoepbvu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtnjitzvgl.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtbdvhldoa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtnnmzmbdg.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gtlovqfhja.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtglqcznlb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtkfubjhxo.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gtjcddsfry.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxenrtre.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtwcnqxosd.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtkoxegymr.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gtcomhccdy.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtqdtenpvw.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtmbdqxomc.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtfsenykep.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gtyqucmdwb.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtuqcdoshv.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtqqbnrnfw.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtnvxpwqen.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gthinsougx.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtbdxpmphq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zdqjudy.top/Article/details/gtifhkvrba.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtlsaamruz.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtmlxsrrxu.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtgchiojpc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gthxgdxtqi.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtlpcercme.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtcofognsx.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtpkzvemmh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gtaotkzatt.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gtaxwslugn.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtuhihqike.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gttehjhxpg.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbgrtzph.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtnnofwldr.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtflqpooim.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuqkomwr.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gttusibrlv.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gtegizzbln.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gthmxvqcvr.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtpeiqcjva.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gtspazterg.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtwzonwnsm.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gthoieucei.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtqvqfoenl.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gtwhdunaiu.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gtxidlathb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtipdgbbaj.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtbcixcjzo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtfbpssody.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtacwrxvfs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtqtrjhnke.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtumumpjjx.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtaqalkabl.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtnyegyoyg.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtudskxjbu.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtsvbknuxl.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtjhvfwvwn.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtztasjlch.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gtqsmnilra.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtdhwqdqvw.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtgeifgirm.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtczhgeqxv.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gtdhzqmrxh.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtdtvwebmu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtykgdzgel.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtdghwrjpr.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtxwlzvmxr.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgjgnmub.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gtmqszrxum.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtkjtjknwx.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gtyyqfjbhn.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtbaygzmrx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxdyrznqn.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gtyqfgjkls.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtjvttktzm.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtpymbfmyr.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gtgpjlrbzu.html


<!-- 参考信息 -->