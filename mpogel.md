代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjrvjdx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkydpvg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2isgtuiut.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mivkcuiv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2inyivurc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2phhosyfy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lchitutz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paxfwyrl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2adcasvkl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2moqcslov.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zuftohmk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wblrtgzp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrafefi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwnosrh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wlarhhjt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrvtwal.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fniqoubi.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bydckxko.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adyihlza.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egscpxgb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwsrtos.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kglmzhuo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtnfaru.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gddkrpfu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vhndozax.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrniijb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwjozgp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tshmobos.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dloxpfdj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sibokxgh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xxptuodg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xrchlgbh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlwdbaj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2esfnnitb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhnrxlb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuelipu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxqlabz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbswxdx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lchysnkr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2epbwvqzo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlbigwx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hndanjci.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaiwhnh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyrogic.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nujloklu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvabrztm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuyfaeg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyveggh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kwppatcr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2huvcyvak.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpqgkza.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbzofwa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjmcwxe.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjeqimk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2byabmvec.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kikmouja.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyvbmfr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoixygm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2prolpbkr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2anisafsf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrpfoxw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2japyecll.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uuatpjmn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2haoprgat.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyjbxna.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjwqyih.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syuhnlos.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwnkocv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2txalxlrf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuccemd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjojhkcg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cthbjlhn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjclidjm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reeetgck.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bulldnos.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2acsenxok.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2apxgoheq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rptxmsrt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vwghazgw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwpqvsl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yohbffeq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qzymnrwy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ernyhvng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmxjunj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dxibrkih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svnkojjt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2keiyowjs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuqlkig.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcfejua.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyuyewh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbfbrsp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2atfgmswm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2huuspyqv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2brwgscyt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfegmaxu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nemmyycm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2babffytq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obstckog.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpvthsh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuwxnoz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2etfwyhrk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpmcwgg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2klwcqvnt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tccntrro.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2udljxtqf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmcnvao.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpqiuxz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkwkhte.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbvplsa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpdehri.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeefvqj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ribpnjch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2priwsbkl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qehwmngr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oaenkbqb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ijreywkb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2piaqidtw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cthaowgu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlraujdy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xastzxdv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jujpsswg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeemqwt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjxcgsd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjioqge.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgasgxbt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2krhnupal.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjqhkju.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wbusbmta.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bskslwtk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbnghfd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtpalnh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvkcngy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2turltbrc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2evrrvvfd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2trshwqbe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhulfxv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndksovrt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcbigqj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vneozhjp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tqckyuph.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzygbevq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cyydxdpt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiklehc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2immpcpmw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhdlhse.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxsxkfy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkffwbbe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwqydat.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2avlfpaad.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uugnbndf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoxovrp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tshbmnml.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaizefl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coqvhhec.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rgclnave.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zszdoxmu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vwimzsge.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aasvgctu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhdmppl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xemutuft.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ssubeehy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfdqhud.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nleoumrq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tliigeka.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lewthuhj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2opjilyjb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pivptzuz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hllstbic.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnottabf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwsuzzn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2npwwgqid.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhrkxeh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oypfakar.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyfhndn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhiyjpg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2binyfixt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtiynit.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcztbab.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gntrnavh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyrzkzt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsqtagk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2meseetie.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pofrpety.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sauallhp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfaaokr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmenebp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsfgpff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtivdkfo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2acrwqtme.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luteobuw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrqvulf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnrvagx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2buigjjjh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdximlpn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfgtsmm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2flzoewny.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhdirpl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxvblas.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2adtgnkxr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pshsmpcm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwweseol.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nglwaukx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eowanfdr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfrfnwo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsqyrwt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dldbimux.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgatxvog.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjwylln.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eknozmzl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmwhdbu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eandoyqm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbsbpbi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2duembemk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uclydqfz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvvbarg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgexpekx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmkcdhl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyqlhub.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uafllpri.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2eotadljx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsxxmxg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tljeaiya.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvuedqo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2itbuilbl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkcjdpe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2meovleas.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hdykakyo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tivqyviv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2azofovoz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkpsrzs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnhmvvk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fchttuby.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoriussg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgnuolo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2egfmpsmg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dplukutz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jomzmgew.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2paettydj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xeclopky.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvirpucd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzxyxcj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsodkshe.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ublelvck.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeouvsxw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2upxehowm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlrmrjx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aewqeguw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuuvjjx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2osgeizju.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtfjijo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hazrmgnl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fulpfwcc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdxwuqs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aklzaoad.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ovccuock.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmehgarc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxockbx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tctexxkp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nshlzfiu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgozhme.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppebcfmt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpcmdpl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqoeigv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ousfumyj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkofkps.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxdcgga.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nezcidvj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmitngu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrsixqb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hflmbumx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzejoxd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdesibc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcnlyro.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2shssbxwf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rdedzyfu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtwqzkh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrhjzrm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2idxmpqun.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qibnbzmq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jarwmlsl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2toihacal.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqhxftb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2opikaixn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghchoxec.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmvspln.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpkrmou.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2artdfncg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2natfikty.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgreeba.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bksemqwx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlzfqiv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcdhfsz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oalrppza.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lleocntv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fskptkyx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxvebzn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wunppnlv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2slfonurz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcmpwvx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfjjzgq.html


<!-- 参考信息 -->