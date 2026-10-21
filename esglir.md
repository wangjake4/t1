代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtfcuttdlx.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gthegnpizp.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtfwruuqwq.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtbiovyqgs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gtkkpkbkxk.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtwfwdpsaj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtdbjzytos.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtssegjtad.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtrejdkkts.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtoxyvndsr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtfciqysvr.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtvgjqrpxz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtgmydegqt.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtpgwzyorc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gteyrssvjd.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gttpldente.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gtwswujznl.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gtzvpdukfr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtvstbgcsw.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtzvqbdyfy.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtacttasyv.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtsnxozrie.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtgsdhlhdv.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtffkkhxqb.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtjltpgokc.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtgkyerltd.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gtlbhqezfi.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtlyktbblu.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtgptrwekb.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtiyxvsrqm.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtyqrtnndb.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gtgsygynns.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gtolmjdpzg.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gtiakbexua.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtlkuucixl.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gtgnsddchy.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtaehainco.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfuureqj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtwfbqtajz.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gthdhkoouq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtqsuddezs.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gteitaofzc.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtnpifattm.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtrmmgchhp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gthjmvsfzp.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtvyegehuv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtlhyvrgcr.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtqouboqtp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gtfcachhsj.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtipddxbql.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtzymblmzj.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gttnikqyva.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gtkjsgfgdm.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtihbabktv.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtmzmybpxp.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gttdpxfxne.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtobspstia.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtjozqfnwg.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtvfeockww.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gtishvejmv.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gtggacskjf.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtkgprsjdy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtvoxknqya.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtwbhkrxxi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gtfayhzsau.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtwblaewtg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtxtkspwdq.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gtolwkllqd.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gtcinssjmx.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gtljifatxr.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtuvicyfwh.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtblvnsrqk.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtkesburvv.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtwpjxcaor.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtugcxslop.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtcdvujcne.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtvyvdmjqw.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gtqlieupbp.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtmoqptpkd.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtbhqliglx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtluffdeww.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gtyerhxzmx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtjzefevsl.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtihsrmych.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gtorzamaga.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gtoyymsdrd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtdzbfezta.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtjzgfpxle.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gtoaomhcan.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtfqzxawqb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtyqfklgvl.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtppmvrukj.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtfwjyhdzd.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtwwjcfokx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtktiqsiaq.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtywhjwviu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtldphrijl.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gtwwgmqfcp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtgegyybil.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtmjrwwyjf.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtfkkvuvrq.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtxugzxvfk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtlazizaxb.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtatfulnza.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtcdhzgmop.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtegxvsreb.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtjelwqqfa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtuhsizuic.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtrufmkvaa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrhqwrjwx.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtkhxixgbz.html

#include <stdio.h>
来源：http://dali.yj202588.top/Article/details/gtykqzsszd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtjfbhftrn.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlkldzgo.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gttmxspsgp.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtictgjmfe.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gtkdobczwi.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtlfwieykl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtsfmhjzjl.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gttmhnbbek.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtqcbtarov.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtqppkcrvk.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtseqpqret.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gttllllhrb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gttgoiznij.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtmfkoqhiu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtddexkltp.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtplbcstnt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtwapfzvuf.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gtqhgircxa.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gteclposyz.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtgoqwhcay.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gthblhmvqg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtpycgcths.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtrkheyvau.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtediircmv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtozufwizo.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtnbpgdpgx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtvclmbyov.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyssfsrri.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtysxqbcbt.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtqynatcqr.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtmbnddohs.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtepztkgsa.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtglxpaiam.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtrwwnknlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gthtverdws.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtdtfyhzjd.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtlaclhzfq.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtnxrvwpmr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbnbrcup.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gtkyrbdjgn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtwmanstfz.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtkmetcfre.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtomklotii.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfkubzbp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziasyviq.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtotpskuou.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtxdgsprbq.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtsuaypahc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtacaoyhgj.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtvfinrbja.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtbqsimens.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gthiljacdx.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtvmdjtqyq.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtzcrsumdl.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtoxrrhljr.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gtlhtiabmm.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gtcdentzpd.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtfqzmswit.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gtdijhpiyb.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gtjvcwqxoz.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayxgdbmy.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtfvhznmcb.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtpaaqnlqf.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtjqwtmyhw.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtlxrpgmjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtcwrnpgti.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gtjcxpwuwb.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtzwomkibj.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtgxfpdydo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtytfmscwe.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtlsrbdgtk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtethvvdus.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtfxhqphgm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtzrayybao.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtakyxftzk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gttqepkgup.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtvehhbgnx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gttecxqdwj.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtdbscunch.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtuiftglnu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtjxnptein.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gtzbksbvvz.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gthzimjzsd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtayqurqlx.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtxzmakxyd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gthiqabrjt.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtcajgxafy.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtqctiqnsj.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtjbuucpgv.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehsdjruv.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtjgxztxyq.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtvfxswncj.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtkhebhbwm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtixmjtrpf.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtfsjucbwf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtfyuschiy.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtwuhjdegr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcmavvbg.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtspnwyvot.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtzqfrtsmy.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtaluymhqc.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtaffdxgsy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtspkuvakz.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gteujyhtjy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtwjycypzp.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtjjvjkzgx.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gttmvmdtmq.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtjqnwnqkg.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjujdopxq.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtksjzwayd.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtninknjgy.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gtbwibawbp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoffpokez.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gttgcqeqiq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gthvmzgtel.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtwpcumabu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtwuqyusna.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtjfvbbmwt.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtesdiczpb.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gteqcletua.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gtpkgoemzh.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtscfaozfs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtgrvoyfuo.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gtostnyhph.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvzdcfld.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdfmsprda.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtmduceupu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfxctxksz.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtupajfpqf.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtpezebqao.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gtqeurivih.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkkawygr.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gtdqosxhwz.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtvwascfud.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtznkmrmih.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gtrngyjqfj.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtklqmullb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gtpjujmesv.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtpznhpeao.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnkqjyugy.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtykocnyzl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gtetmhunzv.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gtxtyzahqi.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtjtkjlwxh.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gtcqwazzgf.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtwnfyqzhu.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtnorjexiz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gtzqcplhtw.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtdyqmedel.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtibvfypkx.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtvtkneljj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gttcdvjzgx.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gtrfculdgw.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtqhfvhmjl.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtvzgzgtmx.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gticqlsdvj.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtyicjdlmn.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpzryicr.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtgcqrrfyb.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gttbcdejui.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gtowofcmzv.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gtctyrvwfd.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtdquliygc.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gtokbwshgc.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gttttylnke.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gthutrbzjm.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gtvfxiwczs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gtqzmuhrgn.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtkppampza.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtthnfvsvk.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtazbxnvct.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtnmkpxwxb.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtzexpczwr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtmkiwkmbj.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtpuchzmwo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtpfwctzit.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtymswqwnj.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtmofzrewo.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwsdjgtj.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtnhgwyksl.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gtntshrcmh.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gtlcsajtmm.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtzxiernnb.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gthltihget.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gtqkbbijzk.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtvgapfvyt.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtnjlftkxr.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtkbkzxdxh.html


<!-- 参考信息 -->