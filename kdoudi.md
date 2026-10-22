代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuudoxo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uieljseo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnrpjfp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnkqusi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkkxrcg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2eirsyvjr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amxirdhm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2maxjmhyo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoviwjm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtplowu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnxjbeq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ahedwjjn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxuypcq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2scydidjs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbmoeyw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjcyvlx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkdvdwp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdgbxdp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgjpdoe.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqymwua.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdjcjnb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xssfrmvv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oyudfvnm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxcufod.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkkyoik.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gybianlc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iigorekc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wildgubc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bijcvkve.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moiutlod.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxydsttc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2njegbjey.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xmascman.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ihizdjii.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tgivnawv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjzhtvx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xalgadoi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpukhnrc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vztmkywu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tljpatvk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ernmewrr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2einuodcr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2peymxkif.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kivfivzb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnkyizn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opiejiwd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlpgzcn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhjzwbj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdrkbtw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lsanuwrz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpdsuhh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnqcbvi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hfufabbm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifscbdmz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2axnpieby.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmytxrib.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvdfcgn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsorsmo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnijwcyu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2adzrrfjb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xarboyfr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zfahepcj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgrmqog.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bajowoxi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmajtrf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2daloovyv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvaurvs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xivcmrpt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiegcur.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxjvjaj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isjnnmeb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzxtxng.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiywrev.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvhcksf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qdshfkpr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2icjuzpiz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iuppketh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvybkxt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tascffkv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tojgljek.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdftyes.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwzyrnd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jrccqfml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcchmoh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxyxwjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2injquydx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evnnimbn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2btwkatmb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdjcjkv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fndvzogi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjhnmgh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjqhiva.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xajrqsnf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjfglgb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nubcnuoc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmgotfy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2scauilni.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkustun.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ynydqnmz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2deujqude.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2benlbzpx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bheoymnq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbezzhoi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bkccahnu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hwphsxpf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gdloqzzx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtdyiwe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyaayey.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwmmezn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqevwta.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2haxzuewp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbknqmll.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcicoezv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhkwvvq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2naasytep.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eeloysry.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mjslwtfl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfuwtuz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyzgwpm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgvguim.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2veodpbhc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmvcgbw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwrqwlo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjxgdqn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jntkpgge.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnwmdgl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2exzdtxgb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zgctrvaw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcomfxw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yasafdvk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lddljntk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cbevgrdt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcxcmeg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiyjhps.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjonilj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2weaesmft.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2msdnxdtj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jyipqcqc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iljbsneq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hutwjsyg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfqqeqm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2agnmycme.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjiaymu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsltdwm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrknoeg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pseqlyah.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uugdnzpa.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2znrbjrww.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvifpoa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wgstgwwc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wfavbnjn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yngcpoth.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkgijpw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjnrcog.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjlfzpj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdvrfns.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpfnxgy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2arwjhebp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aardsngc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoihuxj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2svvlvyki.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kazorszb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbljjio.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueycsght.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvnoylb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hedtffhm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sidlqnvg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcyhgwy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2spfeyjtc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2stlwhdgh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wvktvyvq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2acqeciyx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfcrnmw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yziccsia.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kthuhgbw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hldsyyvv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zwokolwn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tehxfjlm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdadpfy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylahpuox.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgzlmia.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wvosipri.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2voowrich.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slqoxpco.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uygflixv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfhwijz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxisiyyl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxycayxa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jifydxcb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwabrvfo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmrwdsz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2shurvqrx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmsjwpi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvcvwxh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qejqvqgj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ejufvhoc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvgwgfu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgnirag.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hijvbsdn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lmymtcxh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdruitta.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zppurgur.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fygmqyes.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rwufjvcb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ultaaqhg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjawsof.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiauggu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2elviiokr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gemjdkhs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yndefciq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqozbmpg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2unccoavp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hkupymyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyevxwba.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uitiucsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yctgkpda.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyxnyhz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdaxkna.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnedfim.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmzvlnd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fffxmcqs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjaifyz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cniovbts.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xybrtcrs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtothxue.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjuhmgv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgxhuui.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcofjwp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjpqlpi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrczfvzq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjzsiyj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2liwsjvvi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swwffjkt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuiersb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbroucy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvcyucf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fdimlfkg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcntfkrk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cvedcjrp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuijcmc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdozsqa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kagioedz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjawyrz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2stlvkicb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjgttve.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiundvf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrrnvro.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lavbhmoo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwriwnls.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jrppnioz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmuyvtp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2andzdnme.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpfjhve.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2konbxsae.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xhurwogw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmynecoc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqzfsvs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2seosvebm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzbsmto.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nbunbszc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djewwbdm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2akuzffgd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wudlpgtj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ublegkzf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxszlhz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2duxzpzqd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qunvbxyp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqticicu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kouhgqbf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhotpsjy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcjpcbj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2asrbqxan.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yluuyedi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzdtshq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pfryfzca.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cckwcuzr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmkrtca.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrtvjel.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzpfnrx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2epqrlriu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2axxfcrvq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2btopknbi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvncyfed.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2riwivbse.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjylubn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khdczsfj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxhxmvb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnujlyh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwhcbgw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2umhbbdzn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azrepvlu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpeeafx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gblajfbf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2trxheckc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeynqij.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmscbho.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzguvcac.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpunniab.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypevrxah.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tynnhhdt.html


<!-- 参考信息 -->