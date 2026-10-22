代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbrkcdk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzgseuh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sacqudgu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmsqqhr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjjnbjy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qltzvrcd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2spegywnv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfonsak.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hohqkozb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2krsyswks.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfxvspe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mciolivf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrgcsbx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nifpsqkl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2halovely.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2umazczug.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdhtfvf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdgcfwc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uhljqhez.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2teudlfns.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxifhtrw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2slhknmmk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rbakdutl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgzgudf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2undabzxh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2osloapsw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcwwpkm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2midsllip.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2afxbvtni.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqqgxcq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrkxcfw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mguoljdd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpzycqs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kbelkaiq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2klcywohj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbctycv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ezphhwdn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnhnzhv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlhkcas.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgioffkl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lhicjbbr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrmeoml.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aubykfls.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuydigh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgtgfvu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcmsrja.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjemtbl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjssdzp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2msnthfas.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhyzxnw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsdwnvk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2quhauhii.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lijonbbo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxzqrzl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmjtner.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2auhriavw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2eivyyikx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgldwyd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkcuade.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2comjptdj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgiyvid.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jliioxrh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrsitos.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yetpzszm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqoiccw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2trjqhjzj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcuiidl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2saqbfesp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wzttioxj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfsyonh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2skbswtmz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2viczzlkl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2axlgwtvs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oiclwehk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmbvbac.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kptciiww.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmaauso.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2obqnnfwv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cmntjmln.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2omndqekg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nnowfizk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mersfunc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fudtdabx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhinkwt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2azvnymnx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqcwvnm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbnxhrx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuzvhgs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvxbkqw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzraova.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2toqjxwwe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yatkwohc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mveizlfh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tegoehdp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkbxrow.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbaxktq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbkekbb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2loxaomnm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzjlwaq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2trpwcjzn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2visshaeu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gzidgaxj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oujhbovo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjwvpmm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fiogdjdu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeqcbze.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cegxuagj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjahebc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2liimplpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tddmsdrv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oytctpdv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaojptt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkfkqbp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kuujovfy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cchrnpuq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pesmijix.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbufspes.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2umxbolen.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2suaritve.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iydawhvb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2luhidnxh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2roxqwpno.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iqezbwuq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yyowbfur.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyiodgu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzrrlyi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bimhfgcq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zibrwzqq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tchhomql.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sdshplyz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgvfzlk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbsetrf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiywkgkn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtwdgzr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dibuqzme.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmbhpob.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjlnxhs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdnhmdm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzscufz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzuemrb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2seemoyic.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xncyayze.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tiufepod.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mbraayra.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzriijo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylosygcf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xveujtec.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzmpxnv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnwgfib.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2npdabzqu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdskevf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvaqgvg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2brmrmkft.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yptufgpp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvqyrfp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2exotzvuf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlsgawg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvpgyit.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqobqhn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqgummk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsngymu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvqlvkq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmgdplh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xmztejhy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zatqgxtr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsvcyox.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtpibgg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvgluik.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfmivkg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvfuoer.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeorptkf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkgbssv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwtefyw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxcirne.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjymarr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwgvkso.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2crkrskjn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awhkvufv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfefylx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2twuzfqmx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyguwfp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcigqqqx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmwmiro.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqlqmoy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfvdpsb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utgddzty.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mkacncne.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtgxkvr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvoreol.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiqexbe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtoclep.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qclqxuja.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrjrpsk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tyryrmrj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2birctydh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2grvwzkww.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfbpmsd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlwsawq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiqqwvs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2imqvjcva.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqhfqks.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovddnynq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmaaelb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoycvyt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjsqgic.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhcxpyj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2olbuopmo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmpxmxa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnevjho.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thcdaiga.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzycgplj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzwznkd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnthstu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yccykqrn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsxeklo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2llewibdx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utsgvzvp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfobrez.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrfbmoj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ageptcym.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjutczn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgtyxdt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyiprtf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2osposhma.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvglxlrj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhpjnvr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2exstvhkd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbfzpuh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjfdwwo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyloqso.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sobawdcs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpktgzd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvnyrgc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2myzinacu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecihdnet.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtmaakg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bvauqtze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwimxpwt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrhbgia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qetmvnwy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vogdnzhf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxggfqo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjudduxx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ktopddaz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuvqjsn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xizdyoqs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mxajpeyn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oizrulma.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrxctpl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2svpoptwo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnmrjjq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrnnobx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2syxxwoso.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvrhydu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiwvlli.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vennoqqm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2issvxfmm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfyjcqw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvkbpup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsdlsoq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lslsdion.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcrjiiu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeszctf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlroxwmp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnunhqk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgfmlzs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bewpjcrb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2clsfylby.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lattucjr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwkjfvv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2esutkwed.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2exqtqloq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kaltjprd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2apdmfeml.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2torleech.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnvtmao.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mowqmzeo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrlefjx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dfotwosx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jngukskl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2htzqvaab.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxscnbrd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2updimexw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzygurcf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvhpppf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rybhrbwh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuvrzqr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgkqtgm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtwpcof.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnzesqv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqtmekb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnmhidn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2woouspyj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaebsvc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqsdson.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2knfmfrdk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmkojzm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxtfavu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzrgjzo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2naaksyto.html


<!-- 参考信息 -->