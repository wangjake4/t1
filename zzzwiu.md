代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glnttypb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrqvrwh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvnokr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xejtmayy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zcahfbbs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oslewynu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjqgykf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aplgrpto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxynseuf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bktflybu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lomyvpik.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsaydow.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpryqmek.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmbiqbq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2levsnqtr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2exyofovy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkwwpus.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvtsbor.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmctkbz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxclxah.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mryxrfoy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbyrfbw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nxinxrus.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwaccnm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcuyofj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzndvlf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xibgyahm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqtwjvm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jadxodbp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcuvgbn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kungryex.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huhqqllp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsmtvgk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uukkived.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gljzguzm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkujhqxc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbhmhki.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2akvkydmx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpzamhh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2szhcuggu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgxcrlu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2klbfegfl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyrakrk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2byaisoye.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nasoxoqf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksklsnen.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpjsjai.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lidsuqpp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pimzqpta.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrgerso.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dckqxqzt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hoslgsnv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xkapeovd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aipgpgxf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bldsvqkj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxkktlr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2igpeonpb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2htpudwfm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsodtcc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqvukvj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrffizq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qptqbrja.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2candtvax.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pktycghv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2innpgvdu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vviesaqq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwezioe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfpaslq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nwunjtlg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jgomjfkr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbwbgow.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gilelimk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ofobjvjs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpcsojp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aczibrqm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2epcstgtz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbdzqyh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qvazayyf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2puqhaqok.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gjulrqmo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fotkbwgg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nenvakyy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2smdeayde.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aczfilfy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrjlcue.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fsppdazh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsdtnwo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdgfolg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzqjncb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iogxnrjn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiypfzg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnwcdaz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqzatlx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cisuwmlz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gksycehz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2itgtqxig.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmtkxex.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vihvolxe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjwwhsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcotcvk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zozkcfek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aptkpnby.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwxpoke.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrdaolf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nojszhzf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eizdoaox.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkuvooe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqwwnpx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qccrtnva.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuvikob.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2soyupygz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2janzeydk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2evykliei.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2psqvzqlz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdedtdo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsdauwt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ysejehdw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrwfuep.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcpxvfn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zadipuus.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqqhjqm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqzkmif.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqvwpbh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzswrhkc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsgegup.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpbgfjh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbhigeh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sokhpnjf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpkmves.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2khpyfyoz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqhwwiy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uaozirjz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqxkxyz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsdhvir.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mojiiooi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxahawn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjbagzf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrhzdee.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzknzgg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxfufqa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nawypakt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzsxfzz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2elkqoowd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ebddjqje.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjuiscp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqtpqav.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcauvsnt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fvacdpbf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbobqxu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeticrok.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqahwzv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bwacpils.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jayfygza.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcwmrlg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2waurtmys.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hspzixhn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvodhrmf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gywdxjka.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwbnnue.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rferjotg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uibihcec.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jefgoful.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zueydefx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fgefwafu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjnnhxb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzqbqmx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eovmhpvs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxjknci.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuofxiw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwlqlgs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2muafvuyi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsarzipd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzjmoas.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2itwfewri.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbwjjyq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlszdfa.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfeiqxv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaaplen.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wptitpfc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfnezpq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsdxlsp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsirxdb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgxacct.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxegkcz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgcpmeu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpmhwgx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfupgyt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogabnmbl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoooysmy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2otidjmmb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiodakjq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2flhumphj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hrddillx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsidkesh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vdokbedn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnrxocs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2djhyxezx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdumfcd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqoymxq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woggqaov.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuwgwje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brykqjcr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmywoq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjqfsrb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjwcgeq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avddmujp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbeoavi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qlecfknp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2giwvtqyx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yatsxqaw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbfrtnf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hicrymfu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvbzgdc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsrlaui.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2icwztmlf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwfcghs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxohjpl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgrzwwq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzldswev.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfwrsev.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plbaopto.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwpbuyg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiaqcbd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tssvmgej.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgketlbz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgczknv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyhnrwp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ribexmgf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2elinzrzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vybaojlc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtrgfpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlctltp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfjglnh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2odshetbq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyddwyd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeudpvg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrerjjq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxkbiac.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnnhhci.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jywdwtur.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nukqediy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqegvqt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iexobhtk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vivdpxli.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vgajfatx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzmujqv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbtjsww.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2luhekazt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emyyqhtv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuabphf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbapqax.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaejrst.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjzmxas.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhgspgi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqrooug.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsfdbjc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ppogcvuy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2koplkjlw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrpigis.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2snhzgksx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nicesmfe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuqtxzc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbcnrhn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2logjtqdq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghawqztk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axtlslui.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpioian.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cczydbhg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhlanlp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxncyuop.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zputicol.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkevetd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrixxpd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2usvbzjoe.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlovyzx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tpljrfzo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoawhdf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2esotswxr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eabqnnic.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qywqlsib.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnphphq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvwrfyx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2oketyizl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqboqhtf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2detkqzei.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2toosafvm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsytgxz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbbtefm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ejciwrem.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvyiygy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zoumvaqi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ownveomv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgkxwex.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrmqncp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbxshui.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qurnbbsp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zquksmal.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yeealosf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2flelgdij.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkioxpmk.html


<!-- 参考信息 -->