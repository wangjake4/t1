代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gterqqppao.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gtxixibmkk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtsyrxcvai.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtxmdmdlck.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtmcsufipu.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtcvukvbgh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtbzjuumsz.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtqmbvqnxf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtjawmpfwi.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtphizlpmw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gtmndtvaav.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtjoosavaa.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gtqfbzrlvg.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtbhacgipm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtvjtldycb.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtgcutwrcu.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtjmgblomi.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gtdbuavvmo.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtpqixxhtt.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtmofzvfcd.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtadqqvgrk.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtjasunxrt.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gtohwheohz.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gtsexmngyp.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtilctjcco.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gteckkevta.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gtfikkeahu.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gtnqllsqbv.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtuzxscwnd.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gthuxbrueo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtfjnzfxnq.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtxxyoszpp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtjjcusoik.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtguezlapl.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtbikdomjo.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtsotdbcjt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtajjslpjk.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtevbegyxx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtrtmwxufp.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtgdjtdmcf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtgatmwgsf.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gtjlytkycn.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtgkwghkbh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gtuohmpavl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtpmpqbvcg.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gttwmitiuq.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtsgcpbopz.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtkdgmbjow.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gttnvtnxdi.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtlutdishg.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtcjnoqhsf.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtsrtativf.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtfvrxalgl.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtmfndacsd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ivvv.top/Article/details/gtcpavcoib.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtmvgqdqnp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gtbxxotlyr.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gttqkpkyex.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtcanospci.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gtjdqfkmcj.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtofroobuc.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gtjmnzdbab.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtpktzwbui.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gteouffaud.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtuzibpreq.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gtcxzfkoen.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gthrjeyacj.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtlpwwkdet.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gtlauwvmtr.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtjlfvsuxi.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtsvcklsds.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtwienvmst.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gtpgufuylp.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gttvfjwgys.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhoqenbl.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtaskderxm.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtqjecekpc.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gtrqbhjkwh.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtaoqrvsob.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtzscheido.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gtwiqrhcha.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gttqkflfgg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtsoowrfxa.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtxeposewj.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtixwewjno.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gttnvzbfup.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtspjhnlli.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gtnaefbwft.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqtpznrh.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtpkvfuawy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtuhtzdbcd.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gttmtlvgsq.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtsdsxhprw.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtlxnkcavw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtjkfijpta.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtjvrheteo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtpeaueaxw.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtdrgtmxtk.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gtkuafmlyg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtybmztaij.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtaykhhvfg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtoapwymfc.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtaqunukof.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtiqxwgksm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtghrzphhf.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtkcxhwprt.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtzvxyyhsq.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtgsgcvljy.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtjifngiee.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gtctqbrwmu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtockhqrus.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtmslhgiox.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gteacduqnx.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtmssypghu.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtruryuymt.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtgdneiwqw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtslncuavp.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtukwbvswb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gtdpoknggd.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtqdarbokq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtqgtzybwy.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gttxzatmfe.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtdocvrqjk.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtkwqangud.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gtmgnpnzub.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtgpobaikp.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtddmjhbgm.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtaqyhsvek.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtutqwvlsa.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtdejjswsw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gtzockyhlg.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtzkqgheav.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtydtglfmf.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtapuoowlm.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtkfvtpomy.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqutczlpo.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtqlamqtzf.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtaylhlcey.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtcnkvhdlk.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gtdxldasem.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gtyfsnxhdf.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtucolifas.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtuluvytpj.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gttwdmqrqt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtqwiqkren.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtgqvhevlr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtciywxfbs.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtbbdhumhe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtantyfxot.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtsvvhpnqx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtoepnahsf.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtgujbokan.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtvvnaonlj.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtfyjparre.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gtlujleezc.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtbayhswlo.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtzupukehe.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtnynoujao.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtofnedevg.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlbujjrm.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtitihpjpr.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtcimpdwqe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtobfofaps.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtrzzrkssy.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtptusgfxa.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtktixfils.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtezgnczko.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtjejupfjx.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcercobjn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtvmejvlev.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtkkykgyrq.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtipvmisrp.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtqjuzdxcz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gtylemvdbl.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtlohicpkf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtmbrclnna.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtbsblriqb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtiystjeeg.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gtncsyusmg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtoyjgztdr.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtwutaxojv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gtkbmxcbsk.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtihubhwfw.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtpkcuhbgg.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtwlkjhkzl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtwqvkbmsm.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsdgluad.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gtyzowqldz.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtiqqfhute.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gtczyrooyj.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtgxgisjmz.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtlyjhkiof.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtznuvkene.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtkqxytvwk.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtzztxugur.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtotpwqcrg.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtbtpdjgfc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gtfskuuzvv.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtxfzmbkam.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttrjbhwak.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtllvdanch.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtdogsjqsn.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gtdelssprz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtfopxzdoj.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtuexunqzi.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtdwgqkshl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtvzbkawyd.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtjafqlqoe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtirxcommj.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gttotxaigh.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtlyfsxfuo.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtbfvpddif.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtursvaifp.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gtbipwgyfe.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzoqchjby.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gtygloljtx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcvxzkvm.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gttkmbneby.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtsoimitpc.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtxnnpkvys.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gtoqhzbbhg.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtiidmnwuz.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtzeazyuvn.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtsmikwprd.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gtxdytpktt.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gtcvysfgkw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtlimngnfx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gthpbmdthp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtdgsxhtgk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzlajilcz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtcseevvjz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpufdkbgf.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtkbnolmpm.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gthqnjtafz.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtqdqqfpax.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtlpjeykof.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gttzrbjwzz.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtctgczzqd.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtxnzzzkyp.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtpfusvcit.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtzznwisad.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtrcjufuaj.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gttgfwprls.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtabzaztyg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtlwzzohjy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtabwwmcuv.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtcptjjbjt.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloszqhxf.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtszvrymnt.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gtzuovgwrs.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtaiasobyu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtasggylbr.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gthqwjeujn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjrrgubs.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtjgcgamsb.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtbgboutoa.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gtcyttbwin.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtpqhthkwj.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtjiygjofa.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtwmpahdev.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtuwzmoljx.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtzibelvmw.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtvlfcbbhc.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhpdhaxm.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtwurkgqnq.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtjfskbzfa.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtzpxcfozv.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovamvyzf.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gtollamopn.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gtvmippgwv.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtpgwzjlia.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtzdkcxgzj.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtmleusdfw.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtltlcyrix.html

[T22] Swift：字典
来源：http://dali.sweek.top/Article/details/gtgmaylfuq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gtzdvragyt.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtjradqdtu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtdvbonlsm.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gttglukjah.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtaxtuxzwh.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtrawpmcjl.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gtiyrodqvj.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtvjhmineb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtsxzvktya.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gtqlyswbcr.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtthrobaqh.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gttaundrbw.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gthsjnfdvo.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtwwavqwme.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtsfttaiid.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtmcnotrbe.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtrohdznkv.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtbkuhjdmi.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtlgcnbeiy.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gtulbppars.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtqsrkgupa.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtcwtwsjie.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtifmyblej.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gtwtyxiijm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtlkwycvsd.html


<!-- 参考信息 -->