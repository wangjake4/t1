代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axhphoow.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeinjqr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrgqvpk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyejirz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbnuzxb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iacamhhk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyapcez.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jxodmoqa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zendjjbc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sckwkqdt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxgszpv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2frjhkvcx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqpvxad.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcpduql.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xenetqny.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2odqsolyw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uljrwryt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuobdem.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kenlaniv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2chiviinj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2estukcmv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkcukkk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yimjxitw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qjanuauz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2emrytxvi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyzhtno.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbwlfdm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2levbfzbm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zigoedhh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvuyjgr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wsizpkfk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vdopukqy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2foebvzor.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wapbzzaq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lajqycgi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vklwocfd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhriuha.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uktytygo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tymoflmv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2smisjpaw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmgasfb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeqbuyp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htcqedoq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbunuxb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2odblfweq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rndnkiwm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuxfkjz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2irkdbbqv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cmanryjf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcibnvu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agptquaq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2epufnpvd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hydyhjwn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfwvxbw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2slcttkus.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2waqpdfvw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpjodse.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fectqjgh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxknxsh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2taqewzcn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgquafl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yehumtmr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tytfmusi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpfgxza.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmrloeo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntilfndh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqyjklu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pupmwnxx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vewlbfot.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqpvcxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzalkckb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cetxmcho.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2oaucyxjc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tjthohpn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2semclaju.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjclzeyl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ynghdwlw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjpeacb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wotiinvk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2aouxigzi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jeheghiz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2aowvefoa.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzefrvx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrgcmka.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvghtlii.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaaeeaq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaroaec.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpnlxax.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mainusrl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eabsobiq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtxmxgs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcnondu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjkampu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwcsvde.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2krmdqffm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpcqzyl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eeokzuzi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaceuvi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlreldwb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2omrlwlwp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ofokjjqv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zacjwzuo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yrctrsxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xykzmppr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxuxudv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtvhpum.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gcozjihc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2eyldltrs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxgikay.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdnaspv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tarapeaw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjiackc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kipvgrrg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqbnzml.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsqwhnx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmcptge.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvaxtxi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2glebjoqz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyhgzqh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2txxpeguc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2myxibeun.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pivzcqbl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrdeczi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2emmabklo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iebrcmkj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cipeqhqv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjingegn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlelbcuh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqmslze.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbnskwg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2prmsofkh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhtyqlw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcjzdxc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2clnfhptr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2irhcwnvj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yllndvcm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfegonr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iidjzvxm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgshbge.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vrociaqf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kowifwat.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afgxjjuf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuzeqgk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppljkedm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwiniol.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjupodj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmhccxj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ftojqbne.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbisfkt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2joklxpwx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuwthji.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oybedqiv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aednxajh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqhtytx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhflwxbc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnilehj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbpiafw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkvewuv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lznzioxz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjavmzf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgxjwwl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjsfjhz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ookwyzcs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuointxe.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcsovwy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nynoxueu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkzetwg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnitlky.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkkoluu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpcyclr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xntggcbz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfllxbe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2clwepczr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isytfwwh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsxanpq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkcgvfp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2inciyfhh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpraqww.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fimyoami.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwmpkgp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2onnjrmcu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2coibeyai.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzhjyef.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2daiapbhn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gipqrtzm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2djcgcyke.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzjyqvb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwjlubu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpmrdlp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnsfkjj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfqygdd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gozamqbj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euouzjad.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2snqrwpkn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnnyzdx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzjcchu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vgucogsl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cijaebcx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nakcryjr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efuadpgz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ebehjajy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2azdmwxjt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yoopiuhj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbriolpw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2npisshnx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhorrvzu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pztxsmte.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdudqyut.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuzfopl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtupjvib.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsqbsyg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wlihhwdm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hggoueun.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2epsotisp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2krjlgntb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgkyasy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsmmmkf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wjenfkcd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdetejy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzzoatw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpviqfie.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mtifqisg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxxrtzo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bojvozgh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cycwspdn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2akuropjj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgpqxdu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ednkgjfl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlejzzb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vznvsukm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjpqdto.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jaapwahp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkmktme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfugepb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmajxym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlygnkfg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2doqkhork.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhuridw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxongim.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wugbiwji.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ahorikvb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldczidcs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2liknutlx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebknyfxu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2grgfsltv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxkueer.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2axzagcur.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmmqhuz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ldupoctm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdddvjcr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgcbeuu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcixbot.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxwgthe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkqpelo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiqmzxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsxjocu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pgionzvl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdtzdmy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdrwrhp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2klrarrve.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tymecurz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgcwxoi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2chmwyjew.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2femdqzno.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2enktoyer.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qisvzxih.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awpuwamk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmkmyiv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyijozpg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxrkzzh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2igxkvrkq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2olgnbjrd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnjhvhw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxsyfjt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdgiowi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuojtgf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drtervuj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcajtie.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfwxlmz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evthhmuf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwprdmo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nogkhpwf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nrneykpw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjcfpdb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cunlwfam.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2acfmtisw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgsited.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqzmhkm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pupxfbrn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnikbqvi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2inkyshxa.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2esbzwhsq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2krgazrga.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvhkecs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjvisek.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2adcoaeyw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aafhnbeb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvzfehv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lblzebjq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxzzbon.html


<!-- 参考信息 -->