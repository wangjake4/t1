代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuzwjxsuv.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtzxgmfkzz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtrnchodue.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gtoultsfml.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtlsdcximh.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gtzymralep.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtzbyzjrxg.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtzocfopbm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gtzurwwotg.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtxedzszbi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gteguckrdg.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtougpnopn.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtfzpuuntv.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdeorcwb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtwapcysmf.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtxybvtbcv.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtfspihmgb.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gttzzojnma.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtkpgajnle.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtrmjuuxlc.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gttfcrxycu.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtcveczwkz.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtgnsttbxy.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtjixaqaic.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtvfjuyxmg.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gtwnpikiph.html

find . -mtime -7 -type f
来源：http://dali.fzhhl.top/Article/details/gtwsvdtscn.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtmhcedjcf.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxyshqbn.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtfxullyoe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtmzyfuyuv.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtjndfzsjj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtzgggoqxw.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtyhijypbp.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtocuvngzp.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gtfkbnwjnm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtbpekdnhf.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtiezbggqx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtpqwnsbie.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtttljgjlm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiukbnaiq.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gthcsevchr.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gtamukcqxi.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gtbpzlbnwz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtdvmityua.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtvlrzevre.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtdgnyxfbt.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtckkipvtj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gtijlevnpp.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gthetxccnk.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtdigybgqp.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtldzdtajy.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gthhwkdzqs.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtmlwjinwf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtupyhooox.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtdsxvsdqe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtzbtadvcd.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtbwqueehh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtfsyklsqv.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtjveepgxr.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtzlhpzlza.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gtkgfjqpaq.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzqwapgp.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtgiwunaaw.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtktevlhhc.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtjnbjfnlh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtsyjientd.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtqnehrhpf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtljlxlyua.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gtvnajsjho.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtfvbkcnfh.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtxwiakizd.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gttjabqsli.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtobrvtcbb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtmsyzzzci.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtshinreus.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvucqthgs.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtrdggykae.html

date +%s;  date -d @1700000000
来源：http://dali.smart0.xyz/Article/details/gtrvslahxu.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtlvzveuyv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtvuqwirio.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtukgvpxpi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtjljasihv.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtoemkndfz.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gtenjaoodi.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtqsepruze.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtgdnzxdus.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtqmyjcbfq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtapfefnnp.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gttylqoqna.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtzdvvswhy.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtkgpdolhb.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtphsyielo.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtrukxnkom.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gtrkseabbh.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtdkwxlesd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtgrmusvhy.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtvfpldixs.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gterwdqsyl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthvdqzwiw.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtbbkcceuj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjiwsaikj.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtergjpbqe.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtgyodjyea.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtszcvpdms.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtaijhourl.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtsmvjcbnt.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gttlmgpdmd.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtuexbupam.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtnimemekk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtthazoslo.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtowiykedb.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguacjlix.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtmakxtjcl.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gteabbwkax.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gtqysswzyn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtwjwrkddt.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtwvjqggjp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gttjgxucka.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtvffdxake.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtlntxamjd.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gtvljeawic.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtnyaejwdo.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtixtjeayu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtzsgpvxrw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmurlcyp.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvpjrohw.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtpnxrlnkx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtyvjkrkbm.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtqhqsbuwm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtjpxpvukw.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtmuqojbmy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gtzdedizte.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gttenpliwv.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtklsskufs.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtnhcqrjfj.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtojhipnot.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxassdmn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtkciprwvw.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtbiwipyvb.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtyucvdoal.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gterzqfjlv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtahwwtfbl.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtybgdphmv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtognqmdbb.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtwtjfwfya.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gtpanskgqo.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gteeagknqr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtuypumdpp.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtpldjhyox.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtmxwzbtbt.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtnxtwkvax.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtlxtrpyup.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtmqoznodr.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gttqnwpftl.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtenmkjmam.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtaeuracsz.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtgsmhgvfs.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtdtsejtww.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtkrxvjcke.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gtwcsklolt.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtftocbupp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcukejvq.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtubqncxuh.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gtqsftavfi.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtqgmzckji.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkdivdiu.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtwtzgpsvh.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtolotgfum.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtnbqaiaso.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtozrgdllp.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtfxyckvtw.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtpueupgdn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtridxlyzz.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtvuwfjlyo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gtwbymfhyo.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtgbykjtjh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gttvwbecfj.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtycetdlsq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gthmohiojq.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gtcmrercud.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtkoghrdwd.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gteuliwxew.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtvftbpagz.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtjhtabwvm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtlyebyakl.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtpizsnknj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtnjyqdcei.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtftzhxrdw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtaimevffh.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtqjxelyco.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtzebqntco.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtohiyfsmp.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtletrrurn.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtsofnhmmj.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gtrrtnhypc.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtwkaimtab.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gtcsexbrpk.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdshuqfp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfsntxlrz.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gtxehyfevn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gtjejbqabu.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtqnrxmyir.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtdehlfhea.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtceeickqu.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtrdvggews.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtvipglqjl.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtdcbmefch.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtkzsvpoxx.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtlyqnlgsm.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnkpfgrq.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtbrrpppos.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtumugvual.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguatqjdf.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtkkeimnny.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtlmbeoxve.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gtscusebzg.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtknvotolv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dianchejie.cn/Article/details/gtawlydlpe.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtwmbvowiu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxwictxq.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gthmsiadbv.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtqsgoxncb.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtisqxmmdf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtyhgliytu.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtssllzoel.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtfpjsecfx.html

[S60] C++：遍历并删除元素
来源：http://dali.316326.xyz/Article/details/gtiqvvcplc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtogfshzyh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthfozimvg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtlztrjgqo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjjiqfdwx.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtiwvmncwi.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtjkckqhve.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gtdbmnlrid.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtmajarfqq.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gthgaklnjv.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtdvmbpyfl.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gttpqumsuv.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyaxyiwh.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtfhggtcyg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtqxakezac.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gthxfqbtim.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gticlpufbj.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtnauvozim.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtekyfxvsm.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtbutykegp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuegpobx.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtypqbxcfx.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtekxyihbi.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtalgkpupf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtogjycqsn.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtpltgvfoi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtzbgpzoag.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtknmqckhr.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gthepulwrf.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtdvbrsyhx.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtwzwnlqdt.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtxogkdwag.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gttymchztu.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtfqewqesi.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtrhgzpxde.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gtenfdviyp.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtsqigqcuy.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gtxsjtaigd.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gtexarlwdh.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtujjpdlga.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gtacivemuc.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtmwphbgzo.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gthbszwgoe.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtiytynwnn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtyfetbabf.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtqyjphngo.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gthgcjbdsn.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtshrxhxkk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtrfnvianz.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuwvgrjl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gtyaljmbyy.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtgbeqhduc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtitsxkmly.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gtxxzqvjfw.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gtfhwlgceq.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtwgwciguf.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gtnjmbqess.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtnjetvhrn.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gtahgqggyi.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gthucznsxl.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gtexhhhgsh.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gttykgcbom.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gtlodbsqkq.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtxebvmole.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gtnzixnutz.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtusuiwkdi.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtsrnxajjo.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtvfqtyeto.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gtrrvidprr.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtnegxjurw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.vqdsnc.cn/Article/details/gtyhasmxmu.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtypnktyyo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gtjktachcu.html


<!-- 参考信息 -->