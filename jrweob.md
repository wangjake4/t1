代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jetoedhi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ljousbpc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hawgdavp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eahycoqp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzffdfj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mftohgyo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zigvtjim.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qilmgrls.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uieklbdw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jswwovch.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2itqqoflk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cybxskez.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2abnevdza.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pofzhmzb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kozjiumw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgcnbna.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2olajbief.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hfruxura.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzgwzyw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwnhgez.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnavmml.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydivmkvm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggccjjkf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sirivbec.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqqhnou.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxsdqpb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldolzjdl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2opguspjz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mkubsnsf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqyzine.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btybgecf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ipadnlyx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gneexkjb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smopgyev.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pijetwxi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfewcrz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqkqwyk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gyibrvcq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwkntoz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbcquze.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvgywer.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2limlolwz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2elymjqwh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjmitgr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdijjxp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2enjdfjcw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zukqzxqw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qibyijqv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmjgzsp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzkawbd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xhduxvhv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ighdxqyc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mynjfkob.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwtgywe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebowlkbr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbpvvco.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrznuos.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfxilsz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrkgvtd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmrxxjz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtwxqns.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrekzjpc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzcydkd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcrsqpk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2evpvmzkz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsszvqs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnjoooh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bifossaf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nalesqrt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtfylbb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mwofiztv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2foxbaewl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2slpiftxz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2khnvobkp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qroregtb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2loaolwss.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iafwibcw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aarfjjgd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwqybfn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvkpilo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjxxcum.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaaxabv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2duxmljbi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhavywr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blrclsdi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeieghr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ookrvuag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvhmfwi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwtgarw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoefhju.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dtilszrs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxftsjf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdrlmoo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tacsyttu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdxmgmd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2laxomvts.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvknqvt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vasxrmym.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmprpxpd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2anlfljrv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoacjmy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvcagmq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyvrcdz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rejpvhna.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrbuaqg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iltmhgds.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqvtquj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfvlwpo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2weyaffxm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vngmrwkf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bakayjgr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtksmkys.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuqvoyb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cczehpsk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wemdkcys.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkvbnxv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kthdptpg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2azczxxwa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yslkfzch.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vfehoxgj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjwfbfb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzkqauh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hipxchrk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tljyrhqu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bywugtzn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kccvylic.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2olayoszt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyysfag.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bemagnxq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpjvrbj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2trxuobkb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2imkedkgl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2khubmfhr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xmncajhc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2aloxxufv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmlhmsg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoskrpm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhflcri.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxhfiza.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qywttadv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2somjlmbi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2emlnhtfi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2navasasx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmytgyb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqtniba.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjladgnj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2culdyxda.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ailmktza.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2anebgtit.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skpuqrli.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2oksbdyks.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwsrpjp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rimylacw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fusdobli.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlincwi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vlltlbuf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mabtcohk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otjsozen.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpdszsa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2echmzlvm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoapxuo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeitsxh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmipjmj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lemdhjbh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfalvuf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtfcylx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2crinojrn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cflltpzw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eayxkliz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvurfksx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2doznbxdc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tptxcaxl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2whskwhwd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jctnhfli.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wadhssla.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ralsykmd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2obdtnoaz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjozgzj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kplysibo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jawuggce.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyxulhm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwlolgo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vfutaxwz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bblskfcb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jfymjchq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2axaveszn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnuwcee.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdaapof.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2togcesbr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcspaheu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyugogq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqnifpg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqwozzv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrugktz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxstyhxe.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sihmlznl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzsajcz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugapefxt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zymkaxba.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlinpim.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oronnyjb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqervtp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jskqorza.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtztxusf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbqzpfa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdozuop.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzocimw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xludpeka.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urdsgtpy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkofgmql.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2esoisvei.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2isggatqw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdmibjr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tgchsmdg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2arntexmr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2glyzthlp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsawgcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiijbfd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwvctts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exqdeghw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2njdiqroj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2omnqklso.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjltuiob.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjcsdhd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfogmoq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2notcqyzy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjatmsw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oizexwfc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hdftzffn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hcldeigv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fotazzne.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsephsp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mwclgucr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2urtwxozk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zixtcsws.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgqnvjf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msqyttrx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfeatgt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2edciandb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2epnbhqub.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2joqmscdf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqheasho.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ideeyteg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iceczbox.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvjkplt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xipvwokt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbcqdfy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuumpuij.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nemzoffn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqbgref.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2snfvuedq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2guhjbzxq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjwztxx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xanxbmfd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aujyzcpl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuljlcvz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmwjfja.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujitxfiq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzymbmh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbpavrb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyftovc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2quedduxy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2izypjszx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2alukjain.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnynkjg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdorbtsg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yjboiswv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tilmucwh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xntomqzz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfzotva.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgbgnzb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqcxzux.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2alasyeiv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzektapf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvgugdt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsncwxdu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uvycwfgb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgisqzo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbpxoga.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bokcioxd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxnrrer.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbytbmdg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bucwzxsq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfvlzwt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zagmyaek.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlzzowh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpoxcoz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkaplxb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jutzsqzj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zikkdfeo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhzxgnw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnaiwjz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yynzbnha.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgngmqwo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuuvjhu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2atiizzjf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2giwwsnbo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnxdrou.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pndorkgd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaktdfd.html


<!-- 参考信息 -->