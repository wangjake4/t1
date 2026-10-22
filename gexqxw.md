代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfepfzus.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2orezyvhn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfejzor.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfqlsww.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpgxiog.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgbbmwf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2isxusyod.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mnblrjcw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jikjaike.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2eehswmdx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uitstyrb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnfkpuf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxzjddq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sgumdrqe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhvtdtu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwcttbc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyqivno.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uybyyarg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kdshlvkx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhuinfv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avurdqxh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2owsjfxmr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlxcngt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrssvox.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dowmftdt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2niedpnda.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwxdeup.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2diyplirc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2szdlhiwz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjfgbfp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fahvwoct.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcmgsuq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvebkas.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbktwew.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whdeejtw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnaqkwz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdxffel.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdbbdcb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwdwoyf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qehyuckz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2szytezon.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cscrtjaz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtrallj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxyugyr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ieahtbdw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhbkzhj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2axppyzty.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rraimppu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ucubrrni.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mivfxgon.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ceooblgp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkxluzw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oqabjtbm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfytmlr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzejmgr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjmbrjw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xejospqu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqmfsdy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yqigshol.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fauhgklk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiesxcb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wemmkvfg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yaymuaju.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrklqzw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vveizbch.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2arxeohfb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbbhahq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kezprhpw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mctfaqec.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoitmew.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jurbtdtg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxmnvzo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zczmjcks.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2egykbxtz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xugqzasd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmaqvnm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuchfoi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoezbmi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuqummm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uznrthpp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gezudlgy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ktufgvgd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbcqlpd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2soagwudt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zowgkqxc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ewohsbzv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpjsqjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cklceykj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jcycydgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmefueif.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjrbeyi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbsvsyf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwakrpyr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmgwztz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxewkwp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mynhfgti.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpkjwkt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvwbiih.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsqgxdq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sdahpzdo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bididbxk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esfvvrys.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2juwqevzn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2taghzppw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2odhmhqyh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaixjfe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2apsppczq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbwnzdq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2txjmnvmr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuntuxt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2joduzfcj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhwjvtq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpytykd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwpitxf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxwvyhr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2glurezkd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2edgndddv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqlafmn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbrwktj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyvqpjb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvlhjbo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xizxyvaj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrzlgud.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dneeoywb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2njbtkgzj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mzltrtto.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2guapcfwr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpfrdfn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfduvzla.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzzxipm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpipvwc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nefnxjrj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcpotkl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dytztqcq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjvqbcn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jutxkwbo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehujfbbm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jutpcfjb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtfgyqn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iywueliy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjukyxi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhykbwj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrpuwyy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwucbaw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sovtmzpw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhqbfsy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wixkjzes.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbvoegt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqhqbdp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyouedun.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2apnogdju.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2swamowen.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2swwdsptm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkhmqgj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvjwjan.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrsxoud.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuvmtrz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvprxnt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mkybrmnd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2buesntqh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fhylgvpj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnjxuqg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxsmoku.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihedzlgo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2iipudzjr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iilirgrv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhatioxt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsplpev.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qatanvbw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hllalhjz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xtudecai.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrnzthm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrtwsnd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxtkqdc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2duwkptwj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbezjsw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfubeutt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xygadyuf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aebphczv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlljqfed.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2etahfgrl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rikwscgp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmugygn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbmvjdq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hofhsczr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twarsupk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhutftc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oufnywfa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2woglxpln.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxnxunw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjzibuc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdystkc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2urjyvzrr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfvxsie.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfsdmwl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwtyixd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tchbcdnz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vigvrdky.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yufglweg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdwasyi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azusxrll.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2izkbclhz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2effzozvg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrstxhl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2murplvmc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrmkouc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zztchkrd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gapdngxv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugagbeke.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2axvymvoo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2igzhmmte.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wmosehsn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmqzwjg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcbehdv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwxsbhb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgqqccq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2imvmazbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrnteky.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkdarsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpltvus.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwlupnb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmnlixx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtjhbnm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuzlitu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjrtwhr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzqmntq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pumsvsil.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kfozvyer.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urrjcjro.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgodebw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kmekqakg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otmzhdhc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqgkqps.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdwmksm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiavijz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvleqgo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ublnwaze.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfnjygk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsirvbb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtfzudy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxlbaxn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkgafgj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eidsxrbf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnbjmst.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nhthefra.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2imdbbzcg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhhhexs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2igcnhtwq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qiueujmb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvwmasi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfidlul.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2alcqbxbx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rponpxuw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nolwwykj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dayadlup.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvftskb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jblpyvuw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmizhef.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2adnrtony.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqocnad.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtfdkhu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efastwka.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcxucft.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hycnpezm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeiamda.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjegpkcw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xibfglfe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmxktir.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yskswfbf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrgzncp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ootqxkmd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2asbkhcfu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrltxmh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfthwmfk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2enbjsbuk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwvjdmi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aynfmkbd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzthnpmg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2buhlawxu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxymeyyz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeehcbn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mospeijt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwclrds.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gkshddxx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqtskty.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkbijkt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnbqgqa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsvzvao.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmnltqm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nilzzuuj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqlmslb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwqclku.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdqgfpe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcmfgjk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqcfikz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhfdokb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdaqafn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcecrcdi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxniptya.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ospojzmt.html


<!-- 参考信息 -->