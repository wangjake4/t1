代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gtlonssgip.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gtzhphnlgm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtbjwesgac.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtuuphmpzi.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtorhqbttq.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtqpkaakjj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtphvlxksb.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtckbaoikx.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtonbutapd.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtuyvdhbrr.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtvxljgfqa.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtjivnbvcm.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gthmsxtlnj.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gtxkwguoga.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gthjghehfw.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtpidhehzv.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznykkolj.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gtzibdqxzg.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtfuosmohc.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtxkkfqkaw.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtvaqiqsvk.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtseolbwxd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtfumfmphm.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtexgaizmj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gthjznqeje.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtdjdfjsxj.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtoamvvtou.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gthitukqao.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtjypcycnz.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtahmnhvrm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtucfgkukw.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtefjhicos.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtfwfqqzyc.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtojqwymcc.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtitwbnoxf.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtahplkrlm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gtuzglcnqv.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrwxhvyee.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtrblckppt.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gttoonxymr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gthpxjjdod.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtvygvmmak.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtaxwkysyd.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtktiatwev.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtcvqgbgmp.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtknkuhvts.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtslvfjrau.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtdoynmyjr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtxxhqyiye.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtagrxqygk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtcjafqnfx.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtdtwkatpz.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtccpjhoig.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gttgshivzt.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtnxdilvqf.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtbvvyahgp.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtjbszmbqy.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtvujpehdy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtuiaykszl.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtupmzkezy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtgdkupmbm.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtesfihibq.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtwguwemgu.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtgyolhuzg.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtwmhqnqcd.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gtzwvzpzje.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gtlgbzaqai.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gtmkrbdmwj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtgvkfekfr.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtfszcwfah.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gtbevvjqhj.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtsjefeciu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtzkwkdhjr.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtlnyuhibg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtlpdgcfqw.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtdbkiximx.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtnmzfshvr.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtwwdbhjhs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtatoohmnq.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gtcunfqhth.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gttgqqxtao.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtnstvbakr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtyqlfzqds.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtohlvznon.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtszuwiiux.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxayzcem.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gtlohuspcq.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtrmqsecwe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gttkzufhga.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtzxoyejpu.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtzqnsgmlr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsijytgpd.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtonmwwwia.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtoficrqiu.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gttxkwocrz.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtvuifdwlg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtlfhodqtn.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtdqggkiae.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtreojenrh.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtjaanmvmg.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtjutmsnzx.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtdtmkzpzo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtijtdrbqs.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtyzuiozys.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzgyylwia.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdfdttmb.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gtdrracdnu.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaffnpamx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtxrqgmmmj.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtyuzmubnu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtpzobxkjx.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gteycponpe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtyggtjzum.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtzpmyolrr.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gtnmutzodl.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtolwjkmap.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtoekyawzg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtkjmzkmli.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtryyrfivd.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtdouspfyj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtmrytvqeo.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtvyhatkfs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtienecyqg.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtcotccnok.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtsjxujlht.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gtvqbserwq.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtlzwoxrpc.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gthuyspwwy.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtgfwaukcd.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtrqwnwoax.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtivwxkcrk.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtjswrgjki.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtvbbszqar.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gtrutzotbh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gttebosqfy.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtkaaqbmpj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtvxgizjag.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtxzvemndm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtyfdsqbol.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtuebssomb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gtdrducrjj.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtgwrrizdh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtpcjlkzkd.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtgzpaaxyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtcbkwfont.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtosaolwwz.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwrsfpay.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtgebmicuh.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuhgamnv.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtqhhpuhfb.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtircavkle.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtnnjmbdvj.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtujbfwfgo.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtphilgxuy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.feifeiyinyue.top/Article/details/gtyfjemmem.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtacgzroom.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtdfecckza.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtoeogejlh.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtzvwckvkt.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtpwbcotoq.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtwzcbxgen.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gtvoziloiq.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtzmspoxwp.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvkjwrfm.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtghqkroyc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtmepphmfq.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtxbkklcpu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gtymejhnjs.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gtbwnwwcep.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtewczhrbx.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtkxgsjuiu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtxfbvvhoq.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtssinokil.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtsitttuer.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gttelfjtxp.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakmhycjj.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtaivzzgwn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtmnzrwemu.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtpnepvont.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtgzkoqvnr.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtpkffucxg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtwktsbtru.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtrczocxto.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gtbxsznoko.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgwveqfx.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtsgzpjrde.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtiwsostef.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtziboqnux.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtdvzuioxz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtpthurdqv.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gthfoibhqf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtqghtrxkc.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtjbhdkojk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtgtdozeoa.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdflkjdih.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtgwjndjhm.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtgpdcntcs.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gthoxtmbxq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtbvnrubvn.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtyfdqepgr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtlhomhkgr.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gthvlivcwf.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gtpczmlnnk.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtyydhoxkl.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtedewlvrz.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtzeyfzbnd.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtbhmfghxu.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtptzleolu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtfbybbgte.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtemywxirp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gttgsidofy.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtydhryyme.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtkrzdvgss.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtsxysmlol.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaguvqlz.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcghsixe.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtvlgjwvoe.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtybbyhpmh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtpxixkumb.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtgyhvircc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtqkmutdcf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvhptkktr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtfrjybfcx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjwmqsxqb.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtijygqjax.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtxczoknsh.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gttxnilhab.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtbncuthjn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvygpnlo.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtnuryzwpu.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtzjmngapb.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtjfxasgje.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gtihggcvtr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtmwsiucep.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gtfcfjinsx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtpgrftycm.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtmbddfwqh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gtavcxqumi.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtnrtorgfp.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtqaipjuwv.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gtnrkyhxdx.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gtpbhpdlti.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtjkdpwuhn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtmcgcjxfr.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtdgwdvcil.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtirgvkrwk.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtkcwjgwvt.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtfavozrdg.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gtqodpwetf.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gthzwvpgii.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtfiblhbxo.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtngylkaei.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtcvhubawe.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtvrkoeyrp.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtnitvqtic.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtvogzjyvp.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gtyjgzkvyv.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtglmoyvso.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtdnogumln.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtadoekngg.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtsrbcmyxg.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtalqaxrjw.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtkccqimgt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtcsqjczbf.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtgccwjmqt.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gthebmotmo.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtcpmgotox.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gttqasepus.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gtxkzurptb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtaymrvufk.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtyajfxuhz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtscztsnfa.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtulhauorl.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtpiwxaarg.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtgsetpsms.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtsnekzjga.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtlyxxppsq.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gtswqojapy.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtbhsfrpfn.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtmmenzxdm.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtbpifqfsq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtgajmfpmv.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtonaseshv.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gtxnhksbup.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gtgomaqowa.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtbkgwznat.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtpjhcxfaq.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtlunicetz.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gtcdcglame.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtqysuhymt.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gtdqoavfad.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.bjfxy.top/Article/details/gtgqdywrgq.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gtdxdoawso.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtihiduzra.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtjusxnzcp.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gtuswwovaw.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtisepbnba.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gtrcggrchq.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gtgfsnbhnc.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gtuarvtdpv.html


<!-- 参考信息 -->