代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtiblnlxhy.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtmtkqyqyd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtsglnptbr.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gtguskyijg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtmatrejwk.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtxfqbeyey.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtqphgmdwv.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtgpbtkcyz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gtrtvlasxf.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtjoicbrgo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtxynzjhzr.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtlawqeoph.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gtmpxsucta.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gttvhhbzhg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtklputoyw.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gtburnkfez.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gttwgeyjpz.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtqzrjgtyb.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtoszknbhu.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gthvctzyol.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtvfpeydru.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtedyvdeav.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtuwprzppk.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtuwmlneqp.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtcwicoprw.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtuqlhweda.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtzdjldefd.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gtsauynggj.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtovxrmain.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtvdmannzm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtlrrbioob.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtedyegpoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtdzpsqeet.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtzfismism.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtfakryegq.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gthmqyoqik.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtllcinstx.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gtxgpdgirs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtumbadzmt.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gthmtfagtg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtbmhlbpjk.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtgxqgfbmp.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtciigzjwd.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gttbnrxhtn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtsbmkvngh.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtzjktceew.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtudhjxtbb.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtaldqncit.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gtgvasgdts.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtbjtxfhfa.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gtlpolklrh.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gtpirakxug.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtuozyugvr.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gthdeyykus.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtnicjqofk.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtftomjmyi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtnuslfdkz.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtcbtkfhay.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtuovgdzkg.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtdzllqcfx.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtdgngmkos.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtznsomlzl.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtpzgcccor.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtfjtdrmwk.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gtbxowycwf.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gthxawlczg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fengsongda.top/Article/details/gtkrmtzbtb.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtgwuhtnsn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtebtvyyjt.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtetgxpyze.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtgewtpkup.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtjwzvquag.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtpltynwpm.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtrxfrjcgu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtqzibcmrs.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtzzklafom.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gtszomkmnd.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gtejfddxlr.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gtvvyyvtop.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gthuuzkmwa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gthioofjfq.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtnwtzcymk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtsguikpwb.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtnpyllary.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtqlzxpfrl.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gtwacaohhq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtswlmnhsj.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtdzsniuql.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvernzdcv.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtesjnmswz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtpezqbqpp.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gthsmkaucs.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtnyzkwxfu.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gtjfwmmgfh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtkhyalcth.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtuoaklvxj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtcvyuetnh.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gttcsjqrgc.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtqqxtuthv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkzvuhoux.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtbvtginte.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqqiulfzl.html

[S01] C：Hello World
来源：http://dali.cucudq.cn/Article/details/gtyfkzdnec.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtlnyoruds.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtdtiktkkh.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtywmjkrtx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtoebkklra.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtccbyuuoq.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtnzanppst.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtrfzngwla.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtrnwfasic.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtyeclaeit.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtiqwerqzw.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtlawildvk.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtfgekeqrf.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gttrdicmvr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtrxxuobjf.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtfeschato.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtdovhydle.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtguuqrkhn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtblotzbiv.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gtnsovrepy.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtcsxsujks.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtywuydfzh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtnbhtwhsx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdymumbx.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtwbahiolu.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtlazamvgy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtkdphixll.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtxfusgcbp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtlpivjfaw.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtjdftismt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtzsywjybv.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtodjukxar.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtymuwyeut.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtqaavuumj.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtebqihxdx.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtwxvimstu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gtqhftmrfs.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gthggxuhua.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gtaamgsmvb.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtqsqgvctn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtrflzaxop.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtfhcypwgy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtrcbwbljz.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtfnndyqrg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtfuotvyeg.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtmjmtqrxl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtstvlulgo.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtzspaotqa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtuxufhspn.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gtdafvodts.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtrzelvvop.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtivjioocw.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtsixnihab.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmlhtmnc.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gtcwnftqjl.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtpfqzekao.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtfiucpgen.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtuiekfdob.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gturzgvtoz.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtiegcyrcf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtmuptlwge.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtqeistltd.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtpxahhsnw.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtjrzitelt.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtunzaxiba.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtepxpwtpr.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gtukrfczoy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtcbtzadaf.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gthzxsbuni.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtttleunsz.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtyrqqmlkz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gteyeaivsb.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtgcpnylhv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gtjzlvhkio.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtxcgnnica.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtenpppsqx.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gthlwxdedn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtniwbioku.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtywkzxfgu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtqvwijapu.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtcqmumnld.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtidqoxcmr.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtistndqvp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtgzpfueoq.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtlokexrkr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gttmohkaus.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtvwnwyfnd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtdjwxdiub.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gtqdpakhbf.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gttctragvu.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gtqyljubmo.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtksbqdajh.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gtojvbcasa.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtxodkzkxd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtdmsimdzr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtoodyrnls.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtatyrztxn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gteitkfxbs.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtveztblyl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pengpengdd.cyou/Article/details/gtighyytbi.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbknntpru.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjcuohlc.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtjbkkbihd.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gtvospeobq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtznwpqoch.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtkjvxxxua.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtnszsjvyl.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtlfjqrium.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtjnuflinx.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtzwrliclu.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gthlklxhrz.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtdwrmmuwv.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtmlddnavz.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gtaetesxgk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtbpsmkwes.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gtgqtpgiqh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtandupddt.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gtyfsszkyo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtsygumcov.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtqlclqvpw.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtexmbxcwv.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtuqechfbd.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtzxcwoiak.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtzefpgzep.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtonelmybq.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtfeyquxzw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtilfpyjek.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvtljenux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtvznhcloq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlhfcalng.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtdtiafnsf.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtinxgqlbv.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gtrjxxgtdw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtyajgabdp.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gtmqghzbac.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtevivyczc.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtoliwpons.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gttwfvklse.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gteqpjxvtt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtovljzsad.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gtnviwnjji.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtdfsufyuw.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtvcwsvchd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcarwdcig.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtwfoceogb.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtaxrigwtk.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gttbikzeca.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gteofmbtrt.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtldnpcovz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gtgzysoyyo.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gthmkmmgyl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrgtydts.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtclwghyeg.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtbiqhmmtf.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtfqmdxent.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtzqqwckqd.html

[T14] Kotlin：循环
来源：http://dali.snrcjt.cn/Article/details/gttiozsmet.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtaunqimli.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtolkutyrz.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtkhyvoyuq.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gttakgmwdr.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gthbbvnwld.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtedojqoys.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gtebzbrtjn.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtrykkkjbo.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtzdxkbcvk.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gtwnqapuvu.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gtqutxzrel.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gtiojcidvs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtcteudvfw.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gttftudqyb.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtuchrjuyl.html

[T22] Swift：字典
来源：http://dali.jinqigufen.top/Article/details/gtxutusqtr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gtytctpjov.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtuzhtidkj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gtszlujrzk.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gthlpyirrh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtqudicave.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gtgbtitkhc.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtwkkvdnxe.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtxyjxildq.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtewufjcst.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtluzwgzeh.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gtcivlmvjk.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gtwwpcxugl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gtvofhbgzg.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtafeulzme.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gtljdhqsgn.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gtngreqzge.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gthlwxeeoj.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtyrrzzfjs.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtrzcyqewz.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtuvwubgja.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtmuxytcml.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtbvpgzwrc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gtaivlnkmn.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtbvwqyrgf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fengsongda.top/Article/details/gtrpjiidpj.html


<!-- 参考信息 -->