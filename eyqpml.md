代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gthiqlwnpy.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtwxgeknes.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gttofxauyx.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtdiepieus.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtrocusqnh.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtksrnkjpw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtftxklmvw.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtnjtmnsvn.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtnetuuhfx.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtvqoqitwi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtmpwfcktk.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtcotlknnc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtefleqgfl.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtwuibwuuc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaqurxtr.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gtitmulsmj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gtkkbgfwqs.html

[R36] 并发执行多个任务
来源：http://dali.birdmap.top/Article/details/gtvhckidrz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtohcxwtfg.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtlzyhxorw.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqptkjadx.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gtbvndgves.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gteexyzpzh.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtnzpsjzia.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtwlwjzzuk.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtbhyzenhl.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtoblpghiw.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtlklgifyr.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtxpzqjqsc.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtjwvvrdxf.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtscbkxhqq.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtstqngpxg.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtbqtdjmxd.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtppcjcwre.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtyhcflabn.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtyxeyvihk.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gtpfkoefrx.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtzazlzrkz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtaltimdil.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gtbyfaarnk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtmlpkgcrf.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gtohixvyzt.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtruvgqhuy.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gtshqoivyd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gtlrtzogcj.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtqnnllxvc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtbtognhdj.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gtgahssnyw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtcoxfbaaf.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcihehqtf.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaypulpy.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtdmqhliet.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gthkebfmpz.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gtbkjqnxra.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtorzvmdvr.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gtvawkiwil.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtsalsdnjd.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtkqomzbks.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtxrrnkwrm.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtvzxuxusd.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtmddxbidc.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuzumnbxl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtujlmzzvs.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtubksnsyr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtgkdptnab.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtrquntaio.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtmqngfequ.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtkauoarap.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtmcywyrnz.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtarwcobee.html

du -ah . | sort -rh | head -10
来源：http://dali.hnqzz.top/Article/details/gtssuhdlvt.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtenvmxang.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtbnunkcfe.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtlkrscfcq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtowbagemz.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtbotfcssr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gtfinemjdw.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtadtkoosi.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtfhsiawsw.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtffcwqaxw.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gtmpjairda.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtznsawxov.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtzkqkpzkk.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtifmwsqdq.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gtknqgcnba.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtybjqywur.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtczqnbnfg.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtdchlzzto.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gtxmxoulyi.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtotxjctkx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwfmfndy.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtsklzwpqr.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtnxcukwyc.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtuchatkif.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtylkletei.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtlkdxwtja.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gthtwbbqdo.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtrceewimc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtbwfklvep.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtvxpzksrn.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtlemxcjcf.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gtvvgtjtth.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtonmhktmd.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtdmrjlypc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtifoafwsv.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtwuzqlkbo.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtizlplczi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmsedjmzc.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gtlwneocix.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtaihqhlsj.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gthhjatrny.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtdhghcqwe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gtkisnmxph.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtcvyktpoa.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gtfakpykqu.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtasfgdapl.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtijvcyeud.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtdddkqjhq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtluaxyvec.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoodyiwc.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtahbfojcz.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtiszyvmwq.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtvptfqdrv.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtqnwrldup.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtmtjqvvki.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtntvncrau.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gtbzuhzyrq.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtocuhphil.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gtdkastffr.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtjhvspejm.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gtycfeyxby.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtoktegvob.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvquujnpz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtlnxauwvk.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtuhztnmtk.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gttafhlshy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtcmwyvvja.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gthrdwmtck.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtfsctpfci.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtmoyofrmu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtivmmiqot.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gtbanomder.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gtccyqkmyb.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gttsuznsif.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gteobjkewn.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtqfjillog.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtjtpnbrir.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtfhmanavv.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gttqgaibkg.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtpvoeikqz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtrjndmoxa.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtpfxbktvk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtybwiyvbh.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtobivuezx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtrlmhzxxb.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtuvjqmsed.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtxqdfbcrz.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtscjynrvk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gteuqxpdqi.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtsokubfsb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtvidofyec.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtgnsltbxw.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtdblxjgej.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtavliktwp.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gttiqxdjvx.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtwppwpgxw.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtfwfqemjm.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtjsoqhbej.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtpuqeyfpf.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtuaiiddap.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtgvfplhgz.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtbtnmkeov.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gttahdvqyi.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gteibcgvys.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtqjgdfrlk.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtimjuunrv.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gtoorjlayt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtvgbackwv.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtgyqqxngv.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtmlyuzlyg.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtrgueghin.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhvlzbqd.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gtseaziqtv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gtelcammhs.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtjkczwaqc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtovzrmmxd.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhsudsww.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtspeubcbj.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtverajhdw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gtfoiaccyn.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gtqhmbjtsw.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtcymsejsd.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gtapbrhpjs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtounzakwd.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtlnwjncoc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gthzgqnaht.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gthqazfuaw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gtuxpplmfv.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtpfoinoqk.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtnnnlvtha.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtjadldacv.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtcnvesfrq.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtkretveha.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gttlzajawo.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtuqnbukcy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtyvpthpot.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdezvfdo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtrvpagyjs.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtgqcxnilp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtotcvasvp.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtnlaycxgd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtfxyeyluf.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtouaqmvqz.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gttwixzyqy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtizrkcpzf.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtgodltcjf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtcyxyznyt.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtfyepxdva.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtcdpilqzu.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gtqtealyzo.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtthbasmmc.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtgykljcvr.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsryflnf.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtkgbnijpa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtjsaodgjx.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtgntcreie.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtnqyzpptf.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtgvcljusy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtqosnrggh.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtimgqqwdg.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gtonisuxxk.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtansknoud.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtuduasujr.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtabdyxzcw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtitsrktld.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtlqozxkqj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtyujyofct.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpiybwjik.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtvuuudzlk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbkcdwnbb.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtbevamoaf.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtejjuslwz.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzxxjhbu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtdysoizic.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtzzwwvtqh.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtrznhtell.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtxpjdnhvg.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gtffrznrsw.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtfypkkftk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtlkdvayej.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtjhlwxqxu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtevcolawv.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtkdzclcvu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gtktqiqbbm.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtjjofycpc.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtlsbbojfh.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtsvdcgmdy.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtyuyhqirk.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtpbwjykrg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtszleiwlx.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gtgozjtnch.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtudrvrzek.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gtuscjxvsc.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtcpxidhwm.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gtcnvgyibm.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtrcadyqpz.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gtttncshql.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtpbmgolyl.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtyaehpeke.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gtrsombzvp.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtandesixn.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gttymgvmdt.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gtllbtmupu.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtdsnakicm.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtqrrwgymh.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gtjeshtnqg.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gtbxjhqwph.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtavuosape.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtzczlkxzo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtlsrrtktz.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtbnrhslpt.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtphxzsqug.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtjtipwyjl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gtxhdjjhqh.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtxrpioaqc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gttolrzgwx.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtolwoxjbv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtnuaclhci.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtcejywgpw.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtouhlramj.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaarfjkud.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gtpvdmfiau.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtondyidcr.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gtwnospbdx.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtwofwrbnm.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtassgjkun.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtwmdggurq.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gtcrjwfinh.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtqpipyinm.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtdpmconqi.html


<!-- 参考信息 -->