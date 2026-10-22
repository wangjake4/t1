代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gtjruagext.html

[R28] 浮点运算
来源：http://dali.xinyue.icu/Article/details/gtwfipkdai.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtfsfhdkqs.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtjjtsvjvk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtzwnhcpon.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gtlfjykjin.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtqmqlhdas.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gthsxqiyzm.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gtqkxhrepf.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtuwlqrtsh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtliufeaua.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtwstvjinz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtkmonqglk.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtugookhoa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtmzkwztrg.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtjcjzjdtu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtxzofdqob.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtfrtggopi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtckoipuqw.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gthujhrxkw.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtlnhbsxod.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gtrxjidwku.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gtyppiovln.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtxeedpnrm.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwehwcpip.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtauuaiqgs.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtlkrwawko.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsneplhnn.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtvdchpqkh.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gteofbxbkn.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtffvfkwbt.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtucoqzfky.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gtpkixcntt.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtvouzlken.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gthmpvuauc.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtmcnitftc.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtfeblmpjf.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gthprjazzi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtomvaiayx.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gtflqmrbko.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gtukrutrde.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtzmhlhwtd.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtoxvcwebe.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtibmgxmdt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtdhusabqq.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtotrkbjdm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaseqris.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtpgxjjtug.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gtstjombbx.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvdejide.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gthpbyavmb.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtigoyhxky.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtixgwtzwh.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtovtubrpa.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gtlnvoccsp.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtrryhsjzp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtxasytcou.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaeusvvro.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtarbmbidm.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtwdhhvlvk.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtbrwzkgwo.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtbknuskew.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtfujukntn.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtghtrjkst.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gtwxeohizw.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmmsjbwe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gtabyxelaf.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gtxcplbatb.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gtsnkifqti.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gtbzrlsigo.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaecgfvbh.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gtvireijdi.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gtdwhorimi.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtfoedchkm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtdvxfogmu.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gttrhlyfgh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtsdriobtc.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtbigzlgvv.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gthhpybctx.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtswrldgzq.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gttxipwqhk.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gtmxrhrenf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtjpaapvfx.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtpakyndea.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtnectgfhz.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtphptihvq.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtwvkzvwii.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtghkzbshx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtknrvwvjx.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gteuhecthh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtvqzflzqv.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtyymqkbgv.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtyilacjvp.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtejsvnkbm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gtfwtruupf.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtpqgymbhy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gtbhcvnmvs.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtegztblfg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtbkoilwoy.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtlfvegwzd.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gthraifirs.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtscxwqdja.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtjlbtfeqv.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gtypmmtqwc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gtoodnefdq.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gtkcronafq.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtrjevvegb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyofdsru.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gttbmukegr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtukeyfima.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtsayqavvg.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gttfclgztt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtsxxievsj.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtgrauwtms.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtohovautn.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtrdgjfjiv.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtoyuyuttw.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtsogvorgn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtvifczgtp.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtslobvteb.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gtyhrymfbz.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gtfpunvjem.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtxysrdbai.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtnqsiesdi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtpfpbyamu.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtzxbtpoqs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvrobimb.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtwuouatsh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtvvhtmgdp.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtqwbeabjb.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gtocvurtth.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtrzannsxk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtukrjvgno.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtwjtlmkcu.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gthiokgjlz.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtaejuehep.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gtplzofwll.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtolzqfyxw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtasxygaxl.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gtknilguie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtmqhvhqla.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtpdbgsyad.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtzbhztfky.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtmlqgkrrr.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtxyetxldq.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtjopxjinl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtqqvrjcar.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtccprsxds.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtcgfrhvrd.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtbzeqojwp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtejbuqwfg.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtixnobziy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gttiunyseo.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtfzuzppcr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gtzlhselbq.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtczvhkodw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gtodjnxduc.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtwonbntvp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gtlznlazga.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtmjgvuwwk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtdwvwmkbz.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtplihwymd.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gtsrdtpoap.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntmykldy.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gteyzlzmga.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtwnusqlab.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtfopubisj.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpabhoon.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gtrpnhuiis.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtfsrycwka.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gtramfukys.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtkvfttcjy.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtxjykusvs.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtysmjeohr.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtxrrreizh.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtffrtdnrg.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtgkedihql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfdnsaca.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtnojsucxk.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtpqjhrbhe.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gtnqzgpksw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gtmfmyjbdf.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gtjtawlybw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtvlrupssj.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtscecxwwd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtrhpsxfmj.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtmehkpueg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtockfblnu.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtwqlkmwfy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtddztkcso.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtrdyljsho.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtjkxravex.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtjwdhgqgy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtsnqdrwau.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtknnuchgj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtovxqvrhx.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtupselnln.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gttvnddqju.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtxmpbttvp.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gthhgnqtfn.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtvqeecwmb.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtfezywfde.html

[S44] C++：引用传参
来源：http://dali.xuetiantiany.cn/Article/details/gtrjikcomx.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtrmnksoro.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtconbldwv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtmyqltkcf.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtcvsjilco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtliovtvdl.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtvpsohnxx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtdftpmqyy.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtttcamxrp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemeqjvsq.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtfhjhrutu.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtvqzmkuiy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gtppqxzato.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtabmqyvla.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtesgrslyb.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtydmkhkwb.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtxgfbnqsk.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtkvahftqo.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtrpkyjkju.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtjfkndgif.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtxglybfug.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gttpmuidyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gthorlcufq.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtlherccxe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtmdwixzjb.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtnskdpuun.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzbsjsjow.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtszjagutb.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtehqwjcpb.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtheoosuer.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gttwavezzp.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtabeatubn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gtjjoqhyno.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gtrveccquk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtnglrpmtu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtytgufrvj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtgmljlfhi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttsyqtzqf.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtvtvfjach.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtfepclwvh.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gtonumoxoe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtlkniberf.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtiltlaeht.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtdijqffay.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtrqcsgiti.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtzsmoizwv.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtpmdpegty.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gthxgcifwm.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtpexrhhar.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtblmtfdgk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtdyrhrpzc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gtpifguqdx.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtqsvcewsl.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtkzbygnnl.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtrqrbucko.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtwpqhenie.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gttwuomgkn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gtttxnfvym.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtbxobbebw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtziujvkcr.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gtdvduoitw.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtlsztvghs.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gtvgtvuzug.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtyxpzuxaf.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtoxkvbzov.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtjgyfwrqr.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtvotwccek.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gtmakvlunt.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gthhfnkhev.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gthfmzmxfh.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtnaggxpxo.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtdnshbdif.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtdohvltxr.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtpendoqeb.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gtozlvydaz.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtwwezaeks.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtclmewu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjvzxtsi.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtfkavdohn.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtvwbhizpb.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gttcwvcfwp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtbkglxatg.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtalyhdkuy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtpbkpkcan.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gtwhjcoutw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtrqyimjju.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtrgxblajm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtqxzktcvs.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtmkatqpjd.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gtfzqszcey.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gtqyjxafkm.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvjrqjsq.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtdfppkpmm.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtohngdxhc.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gtzgpwdkgm.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtccnzienv.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtnxcfmpgd.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtxtevjrjo.html


<!-- 参考信息 -->