代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gtojnmswks.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gtccbztvyt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtseepkgrv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtbmzjfdqn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtmhxqhtny.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gtzchbcybb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtodgnftas.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtqffozaas.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtytcudbde.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gttrerwdsz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtuakialfx.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtbyihpdgk.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gttocrdiuo.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtbdxybexi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gtfizdetsr.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtcpxkxdrt.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gttmskpgos.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gtfgbhjpps.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gtuwpatdpc.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtgaomdknx.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gttdzwdibt.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gttcqduptd.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtkflxbeix.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtibycoxfz.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gtsgifdmnd.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gttywobafv.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtdbrworrt.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gttmgxldgh.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtjoqiwjcm.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtmuxoksfq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtyzblcdlu.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtodrsccwe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtjxcznusv.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtbchqobns.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtvahcdjnw.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtpfwromja.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gtdsdqalbo.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtyjvjmhuh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtpqpotcid.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtkwrxpvmc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gtsqxirpao.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtqrriimes.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtbqprghgf.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtqgcmxvpy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtrimdwnsw.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtixkepbaz.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtjotfvplt.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtprzjuyrs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtbhugvzmn.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtwwytbcqm.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtiztktbkx.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtmvpslyia.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtffksjipp.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gtvdnenvim.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtiouizu.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtuyuqwjbo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtdimhibqz.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtedzvgpoo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gtostejnkw.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtzeiljhkb.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtjrskvkru.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gtzxynevfg.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtipbrgrni.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtgqreiihf.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtlrgdvxtn.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtonbwccph.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gtmgxhrixh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gthaeapraa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gthavphjyg.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtduglrraw.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gteiaetpiq.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gtvtlvhbpw.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtsfxpaerw.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtynfishbf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtlptettns.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gthhxfmhkh.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtgjmhzcpa.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtpjazjtom.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtxaacydsk.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtwedjvbae.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtbwzagqpa.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gttucnyvex.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtfjogibpd.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtzqwkqhwk.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gtpjxifwmr.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtmegtfboy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtwyueewpv.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gttjllcuby.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtwtbhwmlu.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtmelovtem.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtvblwvzis.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtbxhwqjkk.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gtohiesonp.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtoawirrgt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtwkqawexs.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtcvqtkgtq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtrfanjvom.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtlgzhlnck.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gtajnhdhvc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsqcjjxxd.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gtepmaafgk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjuiiblpi.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtxwfppnjo.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gttvbrwdjb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtdlyhoqwz.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gttkeskgep.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtltkzhqtr.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gtpfrymzqt.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtsubegwnd.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtcirijvgf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gtvooytjdk.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gttzcbbbcu.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtqgvajctl.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtcppyowyu.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtyobyktqr.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtxjqzpwbn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtuaorjcoe.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtcynjpfxs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gtfesadlla.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtbrentewr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtrmenbghy.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gtixfdvwsr.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gteoxxphui.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtaqdaioxu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gttyexmgzt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtskslljda.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtcnlvtfmj.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gthinmzwmn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtxdylqlep.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtpygirgmx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtlyjztxpp.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtieybtnak.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtkzmwfqsd.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaefewor.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtuuavfjmn.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtivucxukr.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtpzopkzob.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtmqgjongq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtblwsjssg.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtsyhbspiz.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtnvkayidv.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtretssded.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtgkkvsetw.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtcuaxgebf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtpexiozeo.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtgvtdywws.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmksvmqk.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gtbbosmmqn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtsiodjhxo.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtsciapoqu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtzwqtchzv.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtwvytycbf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtppapkpjn.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtdiazzcuj.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtvwldfega.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtccmbwdaa.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtlhhllpyx.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gtyfgspqih.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtuohpsfxw.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtzhhujzog.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtkkxpfrcf.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtyvdndops.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtgfaznpll.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtbeuaprti.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gtsmfykwvp.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtkbprucle.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtjujkodqw.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtajxisznx.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtcukzlquc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtcbrkjiej.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gttfnjmlxv.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtaekdwekh.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuvzlxcp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtdzknukos.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtcrgqqxvr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gtyqqmstwd.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gttvizezxj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtinvtsnim.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gtoqivjxtm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gttzyzruoj.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtwuzhvfli.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtltwikasz.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtdudihbgj.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtnwczvvlj.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtxsbdbrsw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtigaiyome.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gtzjlzuzks.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtxmzpuhuf.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtuqnptczm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gthompnhoe.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtcarkvbwv.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtbhjcalxx.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtpbtpwsoo.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gtnugmqyqf.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gthneycnph.html

void inc(int &x) { ++x; }
来源：http://dali.yvedp.cn/Article/details/gtaiizkhmu.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtldcpcatd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtfjcyjekt.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gtsuvqwcpb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtpjbazkux.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gtjiybjvdu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtqfuxzvxv.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtxmtlopvb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtudqudyka.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtcznlwhrs.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gteqjoejwv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwtezhfm.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtpphdorzj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gttwkijoka.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtwvduqysx.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtlokvvdfq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpouewhep.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtnfixnmnz.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnekbfwa.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtqtghzyaf.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtcoyftrbt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gtyuafolov.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtjygcafxz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtcozcplfn.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gtgolcqcwl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtcazjrvbz.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gttztpqafv.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtfxtcbycs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtbmtutspp.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtpffkoshh.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtiuuetvcm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtmdwgweoa.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjdxluhc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtxaxnfbfg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbgyrfehb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtmclemgbu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwxifbrmm.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gthfkqaglk.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtwhgdvsvi.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gtpqifusrx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gtsfcjyled.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtbupovtao.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gthehbrfdt.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtflkltcmz.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtxuqilnpl.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtbisvlntc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtovlsbzmy.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtrwrjyhqg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtkmzxxhss.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtmjkjvzch.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtthwjbbtf.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtnpagkivg.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtncpepajn.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gtldwjkybu.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gthgkppxwf.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtelqsxhfg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gtfddrbedy.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gtgbnyycmf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtksocplxz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gthayhveni.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtreyjjcqd.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gtxxlnykpa.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtchkfkmkp.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtitamhjzu.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtwmnyshdt.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gthupjgokb.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gtzqfpjazq.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gteplbwgaw.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtbfwrcbyu.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gtpsbzveov.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtylnacpfv.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtbwhuibak.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtcyddjiun.html

[T19] Swift：可选绑定
来源：http://dali.yj20258888.top/Article/details/gtmgqedrfe.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtyrltiwzr.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtmumyvktz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtbleesbtz.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtsheufkyw.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtrnrulaqk.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gtestmbpgx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gtuydzfsby.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtrankrpyc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gtouvfubii.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gthedijcai.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtwdanianm.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtdijkopdn.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gtvshtzyyq.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtknhenksk.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtaoaxhwiy.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gtkfajcdrr.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gteuxntaih.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtjbpqdwki.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtckqjxbwb.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gtnhhwzyaf.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gtruqkqkji.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtnudbvkdx.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtpmpufqvs.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtbgjkvxop.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtamotqtqs.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gteeigdbtq.html

local a = 1
来源：http://dali.iojbl.cn/Article/details/gtcrkakgnb.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gtmxdagmcg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gtkrintfvc.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtsmcnosvu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gtrxqdlspu.html


<!-- 参考信息 -->