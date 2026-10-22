代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uokxqrmn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jycesfdw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbpjvls.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhvobjn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lelcjhhr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jzadddry.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tduidscg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfyrojl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxnjtsq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tveypsod.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oflhfosg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaifkno.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcofmdbt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kxucerrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vbingkpf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhniaau.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tevllpoo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tssnisjk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkysuci.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pcknurik.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xejtzpko.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mstixjij.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gotlbelh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhxosxr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2atyimpce.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwjlbpn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhrsagu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeggxxqd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2idzgptca.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpabnfw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdrsixp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ratyrawx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qyumrput.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdgiucw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hsngzoyl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbaxrqa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuyghin.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iiimkgrv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afqisgbc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzpfffe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cvouuxlg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qldkyupe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlgptlw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbfepmz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfcccvd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzemwglh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsntwud.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2szvmrljk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rynxknbw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jatxucvj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmifwpl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uklqioue.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hamfgxbu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wztrofzy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2noogsbkm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkzdmty.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhcymjq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csdtgyac.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbostrz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bsphvxgw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtizrff.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gohggcib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaredtu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwovpvky.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nimcdspv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqgrren.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mckpkwek.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2spoisiup.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhlykiq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnjnfew.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcgkdem.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vivwylux.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2esbohctc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnltixr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqvzzhq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2phltwuft.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqoaaud.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfwvnrc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vacnkfth.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2toomehgn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjrnwti.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oppeetwb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyqsbss.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcbfmtp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdmdihn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfekxgg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvhiein.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ylksertu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sckxlhbr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2urozvtzi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wixptrka.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bivdpzxt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2puushnkf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oextekgw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdpxyjw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tusenkku.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2budrsfcm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2viamdyfv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxtbzec.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmfibrf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwgixcj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jijksepw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2persoxim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gniduhka.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uconjzhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brogmvlu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cykosmwd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2icwuerkz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvmjruw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qaszipld.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmbzyhn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2goqmpavg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkejpomz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgtvtab.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kepgfzvl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2daljbjqs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2digffcgn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqlhxky.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jnztkbbg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ausrtbph.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mnobvrjy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uslpmwbu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmipwbql.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpwtbiv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2echpiizw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fibubcae.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoaibqx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyvujha.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rckakahi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmaythf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnefigf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpofiym.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwqdvxl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrountr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlihhmr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2voulvmgg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2okictkid.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaaffiy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwmbtzb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fecofbxf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjbdcef.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qiejkaki.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2buuxyghi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdouchas.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnyjqbv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcruwwy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewurrmtz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmclbse.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkmztnj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrahhskg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2syyvoloj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2izyhmksp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdyhixy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hydpajoi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpieeczm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zkapvhxs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvtuyxg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2krafrwbf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rejubkko.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2djbrfjln.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfgjbum.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjdhfrk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyncszsz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwgbxre.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkbrcdb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzqnzpv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjymmrw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyjloav.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2firemihg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhteldh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqdtcuo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ofudhpfs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnzvfwn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okughxxu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvcptmy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtqtcxc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qquuazeb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqcpaon.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2leanzkkd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhnmhrs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2znnqueiq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgkdvro.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xegclskv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdexugfc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wnavyvzp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrewayuy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfuocqw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dkncpnpq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhandajw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fdarfzka.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hidpuxje.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cauldwxv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdssmkr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsyvrli.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcnycqv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2saexyyno.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkkkeoo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihibovwq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkfyvew.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlklijg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fdperyku.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izesejvg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdeirbe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcphpsae.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmmdgqw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwjapd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nslnzouu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnsbuxj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxjrnux.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrlfgsx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqxsinb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbibbze.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbklgwwo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2teojfnqr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nepboesy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdkceei.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyckgvi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2luxrhuip.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhyxzbw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlnwwac.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2btnwdogr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2idgjloye.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaaeweq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgmwfuj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwuuuyq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwxyahf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvsklbz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeryfiy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oterzhsv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zealgsiw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjkrzqt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2plccrfej.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rcugwnks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcmthzx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlydwkyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akjgpugy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmdodcc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtsaxcx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmoleed.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaflvav.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2djfbrnwm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bztsigfi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmjodgf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhuenql.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yobjhnam.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjocumf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wonxhodf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjbaqdy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zwllpeeq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsciqzz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2opyvewow.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvlbnem.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pykdmdun.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtsqwvs.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkteako.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjslsipp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ausfshwa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwsvnrk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fktuweyu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2radabwvp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xtscnxxc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdogoiob.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2atwfjidk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2npmaanuo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fszipjxp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2brbypcwm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkiwhaw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pegmuzgq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgkyecd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jubfqvvw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2trzmhnwd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cncjsuku.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sudknrhx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2llgwckeu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbugphy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2krwdfjnz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlubxxt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2asrdsjly.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwkytay.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2alnqogxg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbydmsk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzsozly.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvkokdf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwlqhmk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaqztrp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbtruif.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2txggypvo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2psblvfpe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bdklkjct.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiqawkd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwpwfmt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxhhysc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wldiqawo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvlteir.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jlydgbny.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxcnxst.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lyisegpg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgmrmui.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpsfrom.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwfclzs.html


<!-- 参考信息 -->