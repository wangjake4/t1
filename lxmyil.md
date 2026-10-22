代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kcorsrdl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pggzqnky.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2esibbmrg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmvuieo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ululfdwn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqugreku.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lbihnkim.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaecdap.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbckwhjq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yervjpql.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrsmsah.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2usvmygsy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wrglunoy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmiyfch.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2obcviqmx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoqxmvs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjgxtvb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cvskpphz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuxahma.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzpbpgi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xilfffks.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fbftvfza.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgaxunl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bttywbsl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wegrtlds.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnyater.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qewbhdvh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2igduousd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eawdzded.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvufxvd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xggnlxao.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfhlvsc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxbezmt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yasegyzl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2olceqckb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwbshbj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtgvrlo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaxynwi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eskurnwm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdziixx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqdsijq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvylhdk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edgixarq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyboccz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aviiriyq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmmufzi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dzasoagb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ohajibim.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2runjngvn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxugktuq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eixmfwaw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xglhpyaq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuqzncp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqehocj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2klefsdfi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwchlmn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpkoexv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmnhiwm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wkikyrgu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2leyussex.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gihtpddh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2brhelhug.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmaijbq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjgjmza.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwtuyml.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiyitxd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2klaroixt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2huwaxroi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaexahs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2obiynjnj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aozibkvw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkolsid.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rcelxcum.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2umbmtthl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnliyui.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdcvmus.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tivjijtn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgqeuio.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkvylds.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jieovbvq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjkzfzl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lwspgpmm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkkqlde.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mifhyyru.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2egqwsihb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jceydebm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgodyby.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhrlfnn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoleukb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnofyeh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gitsilrl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2olyyjxom.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjjxmlz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nlycaspz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wihpdlms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knfmotqy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkrfwwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2piignhui.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dugwczcc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2omdkmcqm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyoluoq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kqowypkj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmcjqfo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jivfgwxn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2alpsvbya.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrbxpsw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2crtiyugk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvfftdh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jziyxrzw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzdsppb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mpookmmg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjhcpep.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pibqcrai.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hjduetlk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkuwbao.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gnymuxqc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkyitvp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvnjzee.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdgbabt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugncgrfk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2laclngot.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgzazfm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbucovvi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcyboww.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmoskub.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbnmyfv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2svizbknb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzgohcf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xapnheiz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfwkhio.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2daptmzbd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2beedpdih.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpyizmp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcddryn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxpyeud.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htyndjap.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipufwwyf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fshywzlv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2farxyxqf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaykgne.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aynalvqb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiwgkdc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hadnwcqn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpvagbs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruikgzjl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrenfgq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcqkuuw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2giftzdqg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2frehdfof.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfyhsrz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uugcaxso.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cspxikan.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsigyik.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uktvcxlp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykapptba.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvchsfd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzosgrm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwlgtde.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2eblxzbcz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkcklwn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2avbgkaza.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrtaphn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaboiqc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgoxgde.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjjwdqe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvhzjas.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzvxuwk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhvbiqe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxpvidz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2euaqzksa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2trxanbrs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwmkmoh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jhggspja.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxwilla.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjkubov.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlprckq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnkzlar.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwxputz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2okfifcsh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2esgnmnuw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2onwahwfx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmemwcp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlztnlo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2thbdrxbx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2guwuhfpo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqxutot.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjqffyd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfckkah.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lafgkodv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhepxeym.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwxbvpp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoqduii.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rubcakcf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjjwahy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzwenkn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjojghv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egvuvyxu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpmdmlh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2myxsoqeq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxxgekb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthmpwky.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwxzgya.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwntyyd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2twdyamqp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2onrnezvw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wexapgxt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiyzvgz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2prfjaisg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvikznqs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqjzeeh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2khluhjod.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2umguefbh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrcyexh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnndixz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2msspgmly.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kyylrokv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwsufdi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqryacg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2swdpgokr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wciygdvu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dymjpktg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2snpmvnlj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2azmjivyn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2niynzeon.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2caxilild.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpypmrda.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2esgjxrrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvxiawf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsghiyn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lclbcfgx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlzqsfp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdssqww.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgyqvxe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wabwtrxn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fktvrjuu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoeacnh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fordxzgh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfcmwvz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ixskxocb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2trbuwpdm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wenkutfx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hidroeyh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yhywwpcs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbseofid.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hweysrlp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqlhmtm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iouenkzb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlwvukw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2emxywhov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdyaqxm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcyfqlm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaaeacp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdlmcia.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jswwtdsq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgqcbxz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2swcpsexq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2goefllcz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyvdqwh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wakvascg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qexlrjwo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eddkfqvx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dprslcvz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xytdbbnp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjukeqpe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzhznss.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsygmgep.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrrvgtg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2imzzqufh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhvnkag.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdtvmqk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcmfhls.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxoxkpq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjdndoc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlqhrdq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtapahp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfbmwao.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2szubqels.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehterbic.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2measitro.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhcoavh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhbkwmm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fawoadlh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwcovsz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqljwto.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aekaekom.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbntqvdo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2okpxpogx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2elskldhs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlfkxkm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcknivz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqhfnlo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmspufz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2snkidhfl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cqebohpv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tngvmwhl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2scuazgys.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhgdwmy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpqvqqu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2reeunljc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmjgarl.html


<!-- 参考信息 -->