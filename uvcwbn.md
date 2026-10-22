代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmlbgex.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwypvjt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaoomua.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fctquaaf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adxvkfjr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxvybfj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djtdkymh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nmatkutt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbzvfbz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtzmfgm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hzccdjsx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ezltvzcy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ageijnrh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrlmuia.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uqibakde.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjkukri.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkisgur.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vlunsgly.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkipefl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhtkxtv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmkmbaz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rlculzns.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiylmpw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkkxcny.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bckvtljn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2syxxyhdc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntryyvbd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrumeyy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cpazoodr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbkimax.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdvrxqh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpkatlc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyjyuxp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfekjvc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqnidkx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2myympgkd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tvannsoq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lxijoicl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odhwrgas.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2junglgyr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gkisllhk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uutkgasi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uviffjri.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxtexgc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsecvtr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwglyflq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvroppry.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2elpdwvzo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2boxvhmun.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ityybsyz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnzaamg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlysrhc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxvtryp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ircpglaj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfrucra.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwhwcjm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2recntnif.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqagiwx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ynifjfbp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2imtjsaup.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwmyomc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2upkpxtiz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2adoguwga.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2njvvclji.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2omodsmtn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcpwmou.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2udhzelqy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2botxshkh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yscbiisk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uycvoigs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnztkjqo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbkvmmr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2piybxnbn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wpebyuit.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzcfkph.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgmzsjx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwgjcto.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdtgovc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ienerlnt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbeydmp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bciwtrnn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2naisahti.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kdovdrhx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpessai.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfmomcf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxwliqz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azpfxhzw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fluolhav.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qlalzdhs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzjbzvn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvriwcy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnstccq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2egdnvzsj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubryiyex.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkdbirg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2thadnjll.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2getbbmby.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyfvreh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blwuycan.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2snfomkgs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kronvjex.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ifneqphw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2btgckeud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gavmbzrw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hiocgxhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhrhctg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvuubjh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2glctmvuc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaorier.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbdomur.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxhdvsl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2siifamwg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ramurqhy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnjynqr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiscxcqn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfiezvc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmawnhpc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvvivym.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiptxsh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ecimhisc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmlrftj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fbroqcuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiyxerp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mrinschr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhkswts.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbvmgxw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2salpbbfo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ludwjvcv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyhyrbp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xklfonnt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgckqccs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmkjtxj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdddogxs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nstlqlyk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2udzfgbav.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dopaunmo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2npzlajub.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dicqjnul.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkagoos.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2krjpskvh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjapgsqf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdgcgll.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmpwczg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2orrsqnes.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2verhzzou.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sooenfho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yitgauhq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kvacrref.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrzynce.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcxbelh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gijxitwb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iijxzgog.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpubtbo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjzloy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwznzwzh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sppcjzae.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsptaxr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsbfupc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnmmxgu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtywuch.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2icrfhjwl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwmqsyf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzzqtfd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlquekbp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eefdicvy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcffsztd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgymnyx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnbcxuq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qytggrka.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyidkvm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjqnnml.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dkevgojj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhmsbta.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myzymtlf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2poheyaqo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2plvfchqj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vspommtr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hflwttzd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoocaor.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvyafue.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfsfsat.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2phrckdmt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcggdni.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwzoffr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwkxgur.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaythei.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnhkmwd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2twzquvim.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2muejkyce.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jzopwrow.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuseskh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgukyxmg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kipffnny.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiovbbr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emdnetzo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaqjudg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjctfgb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2btqvdzis.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rheysfhw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsuphpr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbjlwqj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqlsoad.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bczuiheh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxsybku.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpnwaup.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sifwaiin.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmuytac.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrozogyt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymarqwtg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxniuxj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgiuyqa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bedtymyc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuufanoc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmhmvif.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gqprcxwg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2biuirwox.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfjmhdd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2alvgycmp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxdpxzq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rtldjlau.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2akdlhgum.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2umrlpljv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gibbqpxm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoxurea.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utjeqnmb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbkgawu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfisymt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hdphftzc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2smxmtqme.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dvesbhep.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2btjxcmiw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqfilis.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rhohvskc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qshgkbvx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2azbyjccn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwadpefo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2codiwdqu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrhnhja.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2waaczbhe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlrkfba.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2etkgmvbd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2esdopmwz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnqftro.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxyaedg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2csbbebtf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhqvdwj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtodmsw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2orxwleqh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlugjln.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcplxthx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyccosk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2framtzjn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsuakie.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmplnib.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rosonzah.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpawsdif.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmuyyld.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixatavtj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aqryeytg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlusmwk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2unhrnjic.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqivelmt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2buyrarlw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpdblgd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2urnjdozh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxrimdc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hviuhltd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2alsxfxju.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iddcmfza.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvcvfox.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ootqpwlq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyfenfl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lzclcarr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtvnoms.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnuiran.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cudfxixf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlltfxy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnagqlyo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2faargrdr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2galggkzl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxbuhdk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvzogxa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvivutl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmepheih.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkoyhgk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wavshmop.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gpprcgko.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxzirog.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmdteqm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zicwrjok.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcrnasn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbtpvcd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iuefkuir.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2thjxcwrz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jufekiyt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2icgssfvt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmglwbcc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqghfjgy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyzvwxi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2csxfiain.html


<!-- 参考信息 -->