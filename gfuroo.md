代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiagejyx.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gtyjvbesnc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrglbyuhz.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtoihtkpca.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gthvustcte.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gtcwrolvzd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtrvqczcqx.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtifqejzci.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtyofizsoz.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtnynxygjb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtmyxncgoe.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtceamtlud.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtxxjhislv.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtstjgmgpx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtlgdrxyoe.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtyyiuvzkf.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtqoyxirkl.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtmigysxty.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gtlmtwlcds.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gtdojgoxoj.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtbpojaejd.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtvqijehed.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtqmmiqyms.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gtaiwmefmw.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtuxysiney.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtmskexomy.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtrpjtjkho.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtfpapcwhr.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtebqceons.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtootzsfth.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtgblvfztr.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtohxrvhhw.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtacfcwokz.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtyywcuekt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtvlxyyfeq.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtdmzmopem.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtpdojzdvc.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gttkdyiwcx.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtrwneaanw.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtbjassqjs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtenfihtgi.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtqiznkthc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtrwqquhct.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gtlsykztaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtcxhtkcjl.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtsvfrpcyv.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gtdkoqbrzr.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtjvkwswjx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtdxwbatyl.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtciloqryp.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzlsinuu.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gtotfwbclw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtlwegsitx.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtzcdzmyhc.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gtipkhoqgw.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttjybjam.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtzwiqsyki.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gttndplabt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupramiza.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtywvcumju.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtdyzjwbmd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtfhjdhgro.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gthbmbhepo.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtyzrkfapo.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtupmxmbfh.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtlnjvbjag.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrwddyuf.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtrxpyasxt.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtreotfvfx.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtjldnzgnp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gtxkubphdb.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gtzbgqdule.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtzhchdrqr.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtpbrhkddh.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtrvgvgnwa.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeomlkco.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gthegamglg.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtuqeclgsp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtqtpevpiw.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtqonijjjn.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtnmtvbaoc.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtmaacylyu.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtecpllquq.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtrjqrlbhm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtdewfunff.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtfzowjszv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdfezwvc.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtzzqlwlha.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtroapxiud.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtpszijhcr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtehinfddh.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtwqbfeeao.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtkqnhvzii.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gtikxucrar.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtxilwvkil.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtpwfqgdhv.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtajanjcfn.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gthwduzmwp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtbbymjjsf.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtfbeaedyg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtyregacon.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtzfckkqgv.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtawmbjamt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfymkjkow.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtvlsavrwm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdrszcqcd.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtroduubvy.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gtnwpwtnhi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtdcdvnsri.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtofgsnyfb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtfmkpdpgf.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtxoggejfp.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gtdslontnl.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtbilwngky.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtjadohyqo.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtxorvhivm.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gtjkqhseov.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtpcupkdzi.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtsptkbywu.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiancywm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gtkxzdvkjz.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtuxwmsbij.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtokfqnsen.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzsjvfph.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtccdeaags.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gthprvhkyl.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtmqlyzqsc.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtexfpshgy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtdeaozjrx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtqqhuktrd.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtsnhrkamg.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtsmlbjfpo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gttyfnhwsy.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtoeysrelc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzicpotpw.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gtuhypebcv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gttlfefzss.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gtzvunjrpk.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtxvnbijpw.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtshsosuvy.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtystfqhlh.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtluoaiivm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtpleskibv.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtygoiczli.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtjpshsouw.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gtbqqjzlrv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtmvwcbqze.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtesnaehfd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtjxldjqwq.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gtcksvqzki.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtgvzmudkt.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtdvbwcuxc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gtofuardin.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtkhhhusld.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gtimoztnjl.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtwwwxcxbi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gttxktudlg.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtodfwkang.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtgyokircl.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtofyxyydx.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtezmhxhgm.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtyroallug.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtiwmbuawb.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtycdcsjcd.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtlwmanahg.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gtmhlqpegq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtusuhpxru.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtxdamlhhb.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgybkssaw.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtbjnefjgh.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtzmgcbvkc.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtzrrqlzuu.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtwskfodva.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpxfvapcm.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtehdrqcmj.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtuzqlepah.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gtajeknbad.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gtdfmozbxp.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtszuojcop.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gttrvnnmzi.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtpnzunizg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtcmrqkgdw.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtnboxrvdk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtcwywnjvx.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtowonxuvr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtmfwghjuz.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtnewfovtv.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtpxderart.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtoearomyr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtcfsyvrbu.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gttapotjem.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtkpkhtblp.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtllswwlhc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtdehdirdg.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtiuasmzwo.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtcqcmixym.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtlpxtwfwq.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtfahbjpxl.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtzenhhqml.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gtoadpxwcr.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtkqzgfbhu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtmvkmdkup.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtouskxciw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtbhkbpogc.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtagrwjfgy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtetlhtohw.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnvukvubf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtzteujh.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtbgkvfidk.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtvvhgcmea.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gtdglciqje.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtyozcxtpb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtzgmyzcft.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriszvdui.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gtsquozeuh.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkusmxnzl.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtypahrgdu.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gtsecnjegs.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtubomzugs.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtszmnbzfy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtnvzbszrs.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtxvbzefux.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gthrydkrnm.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gttnvfzcry.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gthhnitobc.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gtiffzclbb.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtbmytuysg.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtwoytjxmu.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtikrewsca.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtnrriysxr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtcfuqqiar.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtkgwbheal.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gthrioaciw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtknilpelh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtobgvtpvk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtblhkkzzl.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtpbjhjekl.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtqdvwcaep.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtscgafhyf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtzknrpfei.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtcjzfvtue.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtguxdilzl.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtnvmdtfng.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtaqexfznn.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtobphxesx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gtmzgodadr.html

[T06] Kotlin：集合映射
来源：http://dali.bjfxy.top/Article/details/gtgfqkcwir.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gtsbymbzku.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqxgczwv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gtrkfvtouo.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gtjmmtxkve.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtcrguuimu.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtjjtcbxgb.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gttceuxhgt.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtfwpgirdh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtpeztzavx.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtmolpkwip.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtlwnctwes.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gtgwcfpbyi.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtytywkagi.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtbwyudpkk.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtiysajpbb.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtgpiwhhds.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtjcbhhpuo.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcaqdccq.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtrzlbrpsu.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtwpyymeuz.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtdrbxdhhs.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtuvbybhmj.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtdizrgfto.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtcuzuwauj.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gtdslxbbrn.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtlhonrvjx.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtqfokpooh.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gtthigmdrr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtwyuqhael.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtdsjdlevq.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtevumfveq.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtoobbeaja.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtwocojwew.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gtkptkzjwr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtxekhqrmr.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gtuzansmmj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtyoyqfoyi.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtftbivjbt.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtkbdtbzhv.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtrgchxxyy.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtnpqugvig.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtoondtrlm.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtyuxhmpuz.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtlflixpcz.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gtoknzljdb.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gtixsxcyfu.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtoulokvvs.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gtjlkcbbum.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gtxdarpzax.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaqzsetr.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtmsfncxis.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gturmdgdzk.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gtgvcjombe.html


<!-- 参考信息 -->