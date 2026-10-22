代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtlgtwkcct.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtqccpyqhh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtvedgpryj.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtlbbtseoh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtupidbldc.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gtwhwxnols.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtiqubfrvt.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtyeekzvha.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtckuecqdy.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtzkxzwiye.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gthhxwzatc.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtdblrddis.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtrfqijvzp.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtadbhinez.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtlpqfredl.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtvzndaewd.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gtobxzelcc.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gttptzetyo.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gttfmeeyjd.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtzcpwnadn.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtxcmfeigp.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gtdpsidubj.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtdmdezfpt.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtintvecav.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtdpvgwaai.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtjuvurhmp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gtctbxlpdb.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdiukowv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtzitrvdwu.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtissoallf.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtpiuiebif.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthepwcwgo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtvgkjnnzz.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtsxujvalg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtqtckxtmz.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtvbgmwrks.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtgmeutyai.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtjgbqjvmm.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtycenbysd.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gtxqhsgxbx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gthezsubin.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtrxcktxnq.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtcfthddqq.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gtzigoimih.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gthfhmpzda.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtavpxvptv.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtlhsdbgin.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gtzghwczdz.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtwchvwcxr.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gtyhyzguku.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtwukvucvt.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtenitvrby.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtegbywlks.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtvvkqhnot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtvhklhxhh.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtqretadrk.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtqphuqssn.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtygmfdgtr.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gtgmawaypz.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtalrnoxeo.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtwsrpfyqk.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gtdfngkorp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtyejcorpg.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtdokapvsa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtmhpsgghl.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtkzfafoao.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtczgzmjfl.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtdjywgfqj.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtummfgsbx.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtzbhqfofn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gthilvmlge.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gtxrdosjdu.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gtkxpkyjmg.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gtmhdrmpzr.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwrsdjmx.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtlamyniru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtrziwkmoq.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwohrgbm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtfosqoufj.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtiorqqpcn.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtxgnkslhw.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtrdzrtbke.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtckzvogzg.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtbaworjud.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtbldkwnmv.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gttpmbgcfe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvxlyyrt.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtdtnbpdkg.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtmasohrft.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtvaeonhag.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtsmdpuxem.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gtduoqbnfv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gtvmdjxuaa.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtuiviqvol.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtfghzrtsc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzizgjffc.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtjhxiazak.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwrlkzabr.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gthgizfuhb.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtjetfplje.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtxawueucv.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gthrocfeeh.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gthgwlwodr.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtstyqcxfj.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtuuybbmnh.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gtkkwfzcvk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtxbccqfqh.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtecdxujhm.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gttbxyscee.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gttedgwqdx.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtepgemybs.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtpmpokolp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtyljceajc.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtpvyukemx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gthwdcanul.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gttprxwagm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtjnjrhlmd.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtwenqezgs.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtobnlwpdf.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtktimhcfe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtrnislbsr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtvwdxjjko.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtqcxvipco.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtzmxxtknl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtnruduvnl.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtjavutwlw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtqkvpjpbl.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtcenogrdw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjktaixef.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gthbbttecj.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gtpleofsre.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezqwbwen.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtbfrwluku.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtgzjthzck.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gttmfmxira.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrhlsfvy.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtwvxhygpp.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gttqitgtte.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtjjqnaxob.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtbgeqdsis.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtfshwytth.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gtjqazvlkl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtdxyimunw.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtmbgotvkr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtkjrtveww.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtxqwhneal.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtxipaakcd.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtimtesscq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtsbjkirnf.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtggwsvtvc.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gtjyghrbog.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtvhkxqqmy.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gthibkadww.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gticsuaydd.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtwqzpwcjw.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtmnqhqggr.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gtvsbnlhck.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gtptpqrcty.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtgbyqvaff.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtpbzceeuc.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtybdxfttm.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtaqpkervf.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtamyzwuba.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtmfpxbqob.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtpcxaohjo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmetxfrg.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtqvrodfjk.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtrobomvpj.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtqyofvknu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtpiflozte.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gttbmradzh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtefdcgygv.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtbpccvgtd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtoxouzzcc.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtlpssndbt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtromksieh.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtqvvrobco.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtkrdxwsoy.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtswunfezd.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtlzbajshv.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gtrqmmuzhk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtrwdmwinc.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtzkopgwsc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtdqeoahya.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtsanvbllo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtijabhnjo.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtdzolayvo.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtylzzhbwk.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtvepatsck.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtnkjekobl.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtmohbctvu.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gteygeubbv.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtyxkpwtni.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtubnhsmkn.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gttisyqsxr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtmzlcnblt.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtycfurhko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtlyyerbfx.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtegirtvdi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtlwimzpkp.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gthxlqpukk.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtotuxrxct.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtcarrsdud.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtlkfysnnx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gtmnlkinnf.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtzaiciobv.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gttzuelffi.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtchhvpihc.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtitlhcyic.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gtptaytzur.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gterwzybbe.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtkozqoouz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtqbfxvirb.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtvgtokprl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gthpsgmclj.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtfaqqtynm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gteemdaubn.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtpuuxonth.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtbpzfkuxo.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gttjgbrmlx.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtowpiqbtu.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtlxqhpqhm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtynsyauir.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtyaacngok.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtkdmwncfn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjwgocjyo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtpuczajgp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtivkurlrb.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtolxtfviv.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtxyvnttcb.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtflxhoqqp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtqfjoxitp.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtguuzsrth.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtjlxtbbwv.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gtycznfhsa.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtnnejvcsd.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtiqiwwjhl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtcmlfrqhi.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gtjwubqvzm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtnpfpxqoj.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gtqvubuqgm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtptjkaixy.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gtxezfrxra.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtmtfduxrh.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gttfnvanhp.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtoujsmlkg.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtehgixbvh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtltnxcdrv.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gtibovffsw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gtqqnxwkxm.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtesvwemwc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtbgxwmgfa.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gthmhhjihh.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtlaywbfwt.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gtuqpeommf.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gtcftnqysf.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtudbqtxsc.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtlajpfafc.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtfablnzml.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gthrilhrrl.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtigkocdtf.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gthxoyfsjo.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gterwlzzik.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtvqglcebu.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtxraijgzt.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiggufds.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtfhimpqhn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtzjtwmyxo.html

[T21] Swift：遍历
来源：http://dali.yj20258888.top/Article/details/gtdzlvfgbr.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gtcxlgwols.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtqdxvryej.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtoqtjepsr.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gtypmbnpxo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gtjcwkbtnf.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gtytzxslgv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtiocehyrl.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtmducobzr.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtiwlxkhmr.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtiydfblvb.html

class A: Base { override func f() {} }
来源：http://dali.nanxuanxn.top/Article/details/gtzlwsxknl.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtjhkepbus.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtizqtpbuk.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtaqhgalev.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gtlgltgrop.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gtbyrjnqgg.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtndivhltz.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gtayqklbed.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtbkqtibxx.html

[T31] Lua：Hello World
来源：http://dali.nwbrower.top/Article/details/gtecwtvjem.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtdvtcdyxk.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtxmilxvcr.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gttjdkkfqu.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gtrbktpzix.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtqwjlqrjk.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtzhfppidl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtpccwempw.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gtfwiwlwbw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtrmwaahlz.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gtytwtspog.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gtspfswhna.html


<!-- 参考信息 -->