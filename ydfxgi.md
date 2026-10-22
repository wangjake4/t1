代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ywppzwtv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sruoygyh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmffiod.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyylyps.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwvqlxn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pqauvqtn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2heyxcess.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqrqgfy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uqskrgat.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhrhrri.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2psojdgdd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hioeyxco.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdjrpeu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2batyidpu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrbswwj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2snmhkpnc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtuxpns.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfndusha.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaftnqs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksorbwep.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2whsbsvqe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzfrtux.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpocvlwx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2atbnauvl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfcefbo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqphjgi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfumrsbc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuvvmyd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2knddxikc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyccqblh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvbxpzi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dygfcurb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ynudtgaz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvjtsed.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2txoougvc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dripfygw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2toihhhea.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrrywic.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmziswe.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2daobkibv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twgptonc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eqacdefr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhyukcd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhguuiy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgicawy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxlzfly.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zksygulk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmidvgg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaldxcz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bimhdpiv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2imqbcqqm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zazfagvj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwakegy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vgetaywy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2unxzombh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uterdtug.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ervetxxw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jymwqtqh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igjmqyac.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrfhfyi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlnczgn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuanbif.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjtinds.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hujlbzbh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2eldjujmg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pionqlts.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uikefpvb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxdslmy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnubvpz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbzbxjd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysozkjgw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zreucdsi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrfhuuk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyxfjvv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbuzhny.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jczzopnl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kzecmspr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzsrtnl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbamiod.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uauvvcak.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sydyfnlc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wwndybgb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzggoxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stxrbikk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwiqlum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ellgamna.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prbpqeph.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnmxmfq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gonyhkmk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yerqfots.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iytiajih.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2owdoirjg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2orbztayl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uevrdwxa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2femzvdak.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjnxero.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulinduhb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dgexvzea.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zebuxrzb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqeazxk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2guoejrdq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zjocyzxv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxhjekn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwwiqio.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkhdgal.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfpemow.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tksinrqo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ernasofp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2alzgjspq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsbsyvl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2adavsicx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnigtsz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqomajtk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hjblsjnv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kztxkyfb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwsruiw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvkioqh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2krflxuim.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkdqsvc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyxfdfx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uozngdzg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkbqfdj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcrymml.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbawlqjn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgzhcux.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxncunzv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2arbotabo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpgmlpz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2taerrobi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbtfdik.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iforwwmy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfzzqxa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxkubpi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvhruig.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqokhwp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hekfrcok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihluxwip.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2thuzujnc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxwtiok.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2afbylhid.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnmkwll.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgrcyvo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mruaumbc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvincotj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2puzvcndo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhkaqzl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcwqrbx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhdiefa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kizqdqmt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2flkilbxj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgbqsic.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2invwrgni.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfxwynl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqebyua.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxvfvhg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2idmwhbwg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qxycqwuz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmtvwdp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzgilbc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkaaaue.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsgtqvj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrniefhb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpresob.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ennmgqor.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2txrrgkat.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fehgvsiy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cntuxkzw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzuhnjv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hewpzigg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhqdblg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lokqviiv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnhngtt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfrihak.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rsusnhko.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbhzgiu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkphpxl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2daddjmnq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bybjxuje.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lkizbpbm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djoxunjb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkmexsx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2harpfykv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmzobsj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnkexme.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbciqcq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxvvreg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pccdzyow.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2euuzupfg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tetucirw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhulthu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxrguhl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwvixev.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2npzxxwcl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2euutkylx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxqmrcs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqfzhps.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfztokxh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2btsbxxyj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgewvglz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcfpbwy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nafsrgld.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2skjxaudz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jabyftbx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2obtepqpp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkzkyrx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2odsiwzce.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfdzisb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2btrrdfgs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyqwrgm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2njdfgfpw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlseiwzx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbolmdt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zpekfubu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bphbphzl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkcixcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eszsnwqx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhnrhrp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjuuslw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dptyxbtt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtbrepz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kndxnepc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyzpszx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2abteawrl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxjdlhy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vyieeoad.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzqownc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vviaucbb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2owtslguc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rifpimae.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjictks.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xemuonas.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzziwur.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqxcide.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfzrwbj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtjlytu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpanwapo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yaojgacp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yayenvom.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bowypose.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hunxrtzi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoqznuc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pngnmcmi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddohmurh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiurlvy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2awpkytqo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbzbgqn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2myaucyno.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zohjicpe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2negqvgwi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2joklvwuj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvqhutc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcezyqyc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqccgdj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fryxauzu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxcgqer.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srtvltbp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aapyaoqg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2juqqsrwu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvmuumz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eskbpeoi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lamvvdlx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2anoghidz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsymmdl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2phtdbinm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2itpwoxka.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnzzrrn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuxfarr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfydvrit.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpmjzph.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbixydzn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxgtheh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kecesvqh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdzylsr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzqyzhx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjvuypg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrasdov.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjurbce.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcptmzl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhlofur.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qahfiknk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pialjeur.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhexvld.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sctiempf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2azrppwck.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2phjibkni.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xudsency.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aiozdvkq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyaatcr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoidylo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlnorsv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwxausb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzikkyb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uigybpyr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iryqihpg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlhfgox.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jjobzmuj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzklycrn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiwbhfz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmiaotv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kahxouup.html


<!-- 参考信息 -->