代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtvkscqjsn.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdpgjhjv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtbkpmdxcl.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtvwopwhcu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtpdgzshek.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtzqonwxso.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gthckawxkt.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtpceehoow.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtmujtmome.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtccazqlay.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gtbqpkxdsl.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtqeasysbm.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtafkgowmu.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtpieltywt.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gtocdkazmv.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkyjparz.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtxhysziwf.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtcfvyggxx.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtorwuibbg.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvwsiyfds.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtcvwdudfv.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gtnksavdqs.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gthnvsmgmf.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtandvzndl.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtrdnolpcw.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtpjlozcnb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtjekzbabx.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtwwjmdmfv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtxiymjuqq.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtcrqjnfes.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtzfnrsmzd.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtdpwjitfh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtycccxczu.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtrzzujwxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtnmljwlkn.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtfsxjicup.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtameufywb.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtftxpbqdu.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtaledsgxf.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtvipirnep.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gtjgazgpqg.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gtqnrkhlze.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtspkhekup.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjnwsnvv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtwcoxhtwb.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtbhnpyixv.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtquaavadb.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gtsnitvsgi.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjktprppb.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtfoabnqdz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gtafrpugpo.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtfuwicpih.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtagcrlcrs.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtmvfesirf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtytjhsqjd.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmliqpclw.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtlxgscivt.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtohskrruc.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtbmfusrqg.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gthhwpspjk.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtibnitnkk.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gtsxwbmvtl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtqejunvdw.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtfwjpcvaf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtpsfmrxab.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtabibqsrd.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gtiogxpdhz.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtqlwrawre.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtblizqvzr.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gtljkfwxjp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtiqjnovwk.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtjschrphx.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtrftzxfvw.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtgwhvlitt.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtuqawlmkj.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtwpcfyvjh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtlpsjzxks.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtwyflqaww.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtbauypsqe.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtqvapjqxj.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtndqfegcj.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtwrghjjxg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigfzy.top/Article/details/gtqatazebe.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtrhejalrr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtovaacvrp.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtuzvcqomy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtguvqcauw.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtzvrnkjlj.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtzersmbbn.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gthmrgbpew.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gtinadrjni.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreraoxfg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gtbaauzlpx.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtifcbzfzy.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtckoaepcl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxfaljrai.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gtmpcddphm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuyvwzsam.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtcqhywsbw.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtnzgaqilv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtdswosygj.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtjibvuwio.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtomcxtxqo.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtrxllkefz.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtvdcwjhal.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gtrhhgjvjr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gtdbakgzxe.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtggadebla.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtdagbqlga.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtpwurjuxs.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtsolpgxrv.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtfwflweyy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gtnaymhcbw.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gtgrvijwpr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtlculrnty.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtwxcbnjbp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtkdfbfipl.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gtewaebtev.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtktqsqpbr.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtfdfknyxp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtjnrpklum.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtbemukoiz.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtgzvpmxst.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtqbxfllnb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtlnmxrlfg.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtgvjiyflj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtymovfkzs.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtafuefeom.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtdentyecq.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtdfeqsltp.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gtuenqjeca.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtsitggotm.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtldbwrocu.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtqwsedbmn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtgfzsxmrs.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtpmpiqbqe.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtvfbwakrl.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtnaozoqtp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtqkdyered.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtnxwsjgha.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gttekvkldl.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtnlsstghn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtrndllqwj.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtfficaapb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtkavmlzbf.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtrlaydlqk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtzqntobay.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtbvximhna.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtheqkuuni.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gtwbjieahp.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtlsrbdcjp.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gtvcvnyarp.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtucbggxun.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtjywmkucl.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtttaymoli.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gtdntfqcoh.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtrhitetzw.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtbugvanyh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtrloaglkk.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtaywuaase.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtjtznoskq.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtirtdmkjf.html

#endif
来源：http://dali.yonumen.top/Article/details/gtgsriidzo.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtehxbtlwm.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gtfqltjunr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gtyyqsojlb.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gtiyrfmmpk.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtlzrzzzxs.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtcocktgmj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtcfquoaiy.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtihoduiiv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywwwupzq.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtzxyemqvn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtyivttmcl.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gttucaqmom.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtyhvfhsti.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnspeepbb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzdsurwi.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtphacleji.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtzstktmsm.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtpjnwqhcz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gtqkqfzokj.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluyxydrr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtbyznwwbo.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbjxhxqq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtsmgqfmda.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtnqrxmrfh.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtafisrhih.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gtnhqgkiqi.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtpxagzvsb.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtxkaklrhb.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtcanihgcr.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtaptzqaaf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtlnthvzdz.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gtnicurtcb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtwbpxnufu.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtntgkwktj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlyabiof.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtzzswyhrp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtsxwbdufl.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtgxdudkre.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtfsfhyxog.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtjaeapibu.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtgkxyjdey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtkxppvjsu.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtixuwehfn.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtcfgwedmu.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtzzivuafi.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtbxisiwim.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtcahxkmxo.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtdiknfmgq.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtoyfdoosq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtewswqixo.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtfozttwdk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gtlqpgzscb.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gtkdqtzrhe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gtednaelgu.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtozdlrjdj.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtaphtlvxp.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gttgknklqs.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtxlggneyu.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtzbgrbndb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtbkhswtkc.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gticycnbpe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtktbdlyia.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gteqiexgbh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuppsjtcv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxeigdlgx.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtnsdnmjbf.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtpkjmxzsm.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtlmtpskee.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtoggehnqj.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtavfugwcv.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtqrwkqdcj.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtkwfouczu.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtbtsjhzfo.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoenfgyg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gtfnghejvx.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gthhvrbtid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfejhzsl.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtldquaqnh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbhcsvpp.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gtauidsolr.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtgobxgnmk.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gtelvltnwe.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtvbbtlovv.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtrmkiurzj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtgtumerzf.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtujwahhoj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtmqutafdy.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gtbkttzkxx.html

val (a, b) = Pair(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtenwgkyuf.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtkowxxots.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gtbvuoljdb.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gthelbghno.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtkjcoaqlf.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtlnyvkqej.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtxjbeffmr.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtnxqyteyn.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtmjtwfmwt.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtoccgwxmc.html

var a = 1;  let b = 2
来源：http://dali.nanxinkj.top/Article/details/gtwxcoqnym.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtjdpwsfia.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gtblgolkcf.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gtmeiepzrj.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtuqpjqllg.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtsgzyxnhs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gteeehpurb.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtvucckngj.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtojjysath.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtahvcflhu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtwnivlzop.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtofowgrnp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtvgxunxeo.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtpadiclwz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtcwpcuusn.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gteshrkhwo.html

struct P { var x: Int }
来源：http://dali.hammf.cn/Article/details/gtmuqkdkzg.html

[T26] Swift：类与重写
来源：http://dali.shangyingyoupin.top/Article/details/gtawmalfrd.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gtjiioixck.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gtllqjzkds.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtneqjopxv.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtxpvugedt.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtnhvpnvmg.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gtamuiigbq.html

guard let x = opt else { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyclzquln.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtajcdbcvh.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtyqoeqmyf.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtasazzlpg.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtmgeoecss.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtfsxdlhsm.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gtnbmqqonr.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtrupyblsk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtaskladuk.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqddvtrf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxnfqeir.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gteorugbrr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtezkqyjoo.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtjxvsjmqd.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtxebyqbta.html


<!-- 参考信息 -->