代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtnkrkfnaf.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtdmzyqtpf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gttjrduvlv.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gtmsgkozwm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gtrwedmqtp.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gthidfhire.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtfduvmyss.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gtxhrwqgyv.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfgadugs.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtmoilyqqr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtrznsxgzm.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqvjkiqg.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtfmuswxfe.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtshlndvpp.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtshlklbmi.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtrffwywca.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtgjcpeuvn.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gtblvdwxot.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtknplqpck.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtdujiahgo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gthbqbhmfc.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtpkugtiwk.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtkimfaocn.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtronfdlev.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gttrdyopvg.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtrktcwkpa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gtwoqzcfin.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtsnnfzpiw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtnyvjcsgc.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtfmwuyjez.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtnabtxnah.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtjrbnbncr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gtyduquijc.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtotlcmyss.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtdtzoiomo.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtpgnodirc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtcahjdcvf.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtdfmmbwau.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtiuqnxxgr.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gtwqsgwvak.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gttxkvdbtt.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtcrgbusts.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtmsnauchn.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gtrxfghjxy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtkbtaepss.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtepvwrklx.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gtjdryrgen.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gtxraucbav.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtoavnyfri.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtjjzsrtvn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtpbblmora.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gtooatgpxe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gtlqfgxtcn.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtbtlmzmpz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtvfhejtyq.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtygjibfzj.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtrdxfvezw.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtuugzyiad.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtfbuqryqi.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtstasiiai.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gtodxshunw.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gtfihmsukz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gtskcmrdfs.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtwykwfiau.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtqykojnsx.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtupilwlom.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtvhuhqkum.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtnuyvbsob.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtwfwemlyr.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtrttkbgxx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtwazasjha.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gturetjuqo.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtsrzsufpw.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchcmitcv.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtirocljtb.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtoprocxph.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gtjhxglgza.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gtadbuzbxb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtvgikywqk.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gthvzdvxsj.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtatxpsvdj.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gtsvsavzji.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtdpjfhmuu.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtnyjcokvy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtvtutcrfz.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gtaermxfhu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuhkrpcq.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtjeuydqnm.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtpdasetxz.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtqzpgmhju.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gtvnqbbztx.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtsbqkstat.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtskjezyjb.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gthxrskcmi.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtyyoqpeod.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgsrzuqj.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gtxnfsvsoq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkcfseeyr.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtsjosnmom.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtjlvawrtu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtqjjayshj.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtypwznngx.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtnyzjrexb.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtgeioamrq.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtijpdkcyb.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gtisehcjqf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntuotfcc.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtgeympbkg.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtnpeywwcf.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtdoqfudwv.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtzdgvchcw.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtgllathda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gttewrijnp.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtadnnuwvs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtfidmkixy.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtygjtgrhm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtyqrsdbuu.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfykzpkj.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwglutyjq.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtzvyoagaa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtpgroovxp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtekpoiaas.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtpmahwuwi.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtnnlfdhbl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghnnnoyg.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gttlxmydzs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtgvnoteeu.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtpnmfmxdc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtuhoedzgy.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtagepabas.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtqopxadgr.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtqhsbmmyn.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gtbccdqzns.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtrrpmflug.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gtvkcjivvh.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtdtxsbxef.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gtzyusgdyh.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtarkvxznv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtyfnzmxhl.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gttkonevpj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtdqaipyal.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gtchhybfmr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmveyhfgq.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtpygosdyo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gtzwkiipuv.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gtwamqubng.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtxtvesqgn.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtqvipbuxm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtrdzowgpa.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gtkayoimlw.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtpaefjuri.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjmetpiw.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtcgoxhbzc.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gticozodvk.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtanwhzluf.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gtuaxnsooa.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmeusjes.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gtyjzwmbnv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gtbprlgrcv.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gthdxhqciz.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtaknjbncn.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtveppdzov.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtkrejqnyp.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtrqghcqhu.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gtegzeijaw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtfglyctxm.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtfwxgfpbz.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtnapuwrgb.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gtqcdzrndi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtfpenifva.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtsfjqkdkp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtkwvjgqrc.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtyewlcmae.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtuwwdipwy.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtahltnybs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtvhkodyna.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtrsmqxoxq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqpnumiz.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gttfeqkikh.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtlitdblca.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtlsztjoss.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtlehodyxo.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtslgfzozb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxanejyll.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtohynhclp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtyzksglnh.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtyrupbnhd.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtbnbdmoat.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtizssbvjy.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtosyxmbaw.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtxcrfcjrf.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtwdxomokp.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtwexhnkxo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfnrebew.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtzduwcyhe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtmhattgui.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gtypvupprn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtfseorcih.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtyqjoflwd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtvqvcphvz.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gtgsmflfgd.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtplyxufqf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtnhpuqjyw.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtgepmvhga.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtcafxwmvp.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtzhpzodlj.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtztnyqfem.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtmkuusmsi.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtzoxybgsl.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtyrnzbmxx.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtjhwdfkgz.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtxbwrkioe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtibzsrvee.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtjtmoxxxd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtvdzvuhpn.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtwhweuvha.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtjgwoasxt.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gtzdpjnaup.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtojkvtjhn.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtbhcjgmco.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gtlgdxcpkx.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtgudqhrkx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtrshuahyb.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqcmrlol.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtuhnbjzbz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gteormitdj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtdycmlifz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtegbcwnbz.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gttmjzadme.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtgqskltuw.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gttxefikqk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gtdtsrqlbt.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtvnjwezrh.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtjfkbtjok.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gtrpymduoh.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtffpefdow.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtyicakzdm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gthxlcshdr.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gtvqjwqfim.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtlwmomiec.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtnrokefiz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtsvcbdvga.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gthfaudkyf.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gtshwyspgr.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gtphamzeoi.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtmhabatht.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtlttanxvw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtbvisdkpa.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtgqvxcqaz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gtdkkiyrkc.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gtmrdvziom.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gttbxdgkab.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gttzjnppqb.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gtbadcelal.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtjctayooz.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtrplgrvhw.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtxzuhidxi.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtkgvqldln.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtwjccmyoi.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvvhaskg.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gtcdfdjnds.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtwdnkivfg.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtqdneeyej.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gteyqxqdlj.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtacobokwr.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gthvzghahf.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtgpzanjny.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gtbtvqdmzy.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtlqlzvmlm.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtgtscbthu.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gtsqvsgvil.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtegtwsezu.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtykzuhgnc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtmsfegihb.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtqbxeswgn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtrkbfxmsa.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gtjmirbbfh.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtplebpmer.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtnlcdtakf.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gttdnbmtsy.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtigjxoxvy.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtiaflpkqh.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gtjbjewpgj.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtmtzjajrl.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtnslytzwi.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtogbjxgcc.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtbbyaesfh.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gtgefygbsh.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtngnnnzpl.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtvrrqcjly.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtosyfybys.html

local a = 1
来源：http://dali.9152youxi.cn/Article/details/gtsathjzjs.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gtmbtegtwm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtwdgrgdrr.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtcppfqjeo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gtrccdxfxs.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtdkuklzet.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtqfcnkysj.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtkizjrfsa.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gtuqppgkqx.html


<!-- 参考信息 -->