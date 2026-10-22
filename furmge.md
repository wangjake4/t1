代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gt2dxxxnfqx.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vswpnaem.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2olzenpzz.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2aitvkcmw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gt2vwrhpxzl.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gt2ztiibohb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gt2zzoqsbvl.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gt2sayxjdas.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2hxooroel.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuofacgo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2yccfmwvn.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gt2xulqvzrr.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gt2rrcocudh.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gt2mhcyfxxm.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gt2tcchrusc.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gt2ypkfbfic.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gt2hyawyttv.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gt2mirxyvxb.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2wghsmxie.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gt2ragcrhsr.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2nrshoagi.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gt2gmrhtxlw.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gt2jpzeiwui.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gt2maibxohy.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfjgquqj.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gt2fglwgqhl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2xbwhwvfw.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gt2hqifrlpq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2yjgndqan.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhxpgqen.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2djnsospd.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2ehkjzkip.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gt2uvvrqtrp.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2skueqazn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2gxwjlrej.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gt2jjbdsuik.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2labhuxbo.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gt2onbkerkk.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2ngadppwv.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gt2ojelmwre.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2irbqjooj.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2lftuxios.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gt2gbnegcgf.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gt2foisubsw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sahpdswc.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2jwgyckui.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svnirrqa.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2rauyxugh.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gt2wymkjgup.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gt2zpazwmpo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gt2egeouugp.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2qfzhycxe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gt2twqaivmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2mcwhkioi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2rhyomijm.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gt2hcpsewau.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gt2usjqsqdg.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gt2xyxtgsos.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fktiekpu.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gt2zneesfzt.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gt2vyfbuwpf.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2ttfsrhtx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gt2rfcuydwe.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gt2fiqktayx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gt2pgokdfdg.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gt2dhgbajuh.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gt2xneyyvoh.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gt2cupttzme.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gt2xbaxgbzy.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gt2phvinghf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2cbrojied.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gt2ziwrmxft.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gt2zwihhhvz.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gt2wuyvjjhq.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gt2nekaxdqq.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2xnkrmclo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gt2kpupktvy.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gt2ppmckzzx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvuplwg.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gt2ehwvegev.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gt2jjgfaukp.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggjnbcvv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gt2mzhuwkpm.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gt2bioufjlm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pndlsizj.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gt2ocjyjpgw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gt2vwoqcmjo.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gt2uigbwgqo.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2ktybaatr.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gt2qngbfnkm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2mzyqzuqh.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gt2tzogcmps.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxzdqstv.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gt2vopvdlva.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gt2rqcaczyr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2tzecbmjh.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gt2fhyvqyvp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xhoyqjcm.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2meslazwh.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gt2cldsalgx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gt2wgwubccv.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gt2jnvjofrh.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gt2rfegwacb.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gt2fmpqgztw.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aclrjyja.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gt2bldoqqfc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2bwnkwuyc.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2olbfyiig.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxwyrzgo.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2ckmaigof.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gt2rycocfta.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivkmlpqm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2npjkdykb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gt2qqkjdycv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gt2yysdzufk.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjteovpt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gt2xcihouyq.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gt2uwwhssqy.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gt2pyfpftlj.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2wifkgfuj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gt2ryvpqmmz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2yqftuspr.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gt2yzynlnua.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gt2cqmdzric.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2jzbowvdi.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2jxhopamp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gt2lpnxqtap.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2oobwyyfv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2khxuclfe.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2koykkxle.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gt2zmcxwrsc.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gt2riaflmyc.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gt2vztajzaw.html

[S17] C：安全拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwetlpjf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gt2etzjdfge.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gt2sdsqkycd.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxhwiajr.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gt2lrdnyzet.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2xykwvotg.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gt2rzqumruk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2iivuomze.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gt2kkpparxh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gt2nivenngz.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmmxzrhu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gt2jrgidytn.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gt2ubdwhimg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gt2nyzxsuey.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2mvxngejy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gt2gihrxcsu.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2obqnaljk.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gt2tgfrqfnp.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gt2fguglwfs.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gt2vbqjlzcy.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gt2bqhqjcxj.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2qvbncusv.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gt2uyrsckht.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gt2mwstodev.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gt2sustospi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gt2fdqdoixc.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gt2bggrnbeu.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gt2ioowakng.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eylitchd.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gt2vltxibcb.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2ztzjdekp.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gt2krhhtcvh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gt2jdkzlqef.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gt2laxsnplz.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2ebjznwvp.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gt2njjbyree.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2ntfebxjz.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gt2rrdapqzn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rnokmlpz.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gt2fnyruvuh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2icoodinc.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gt2dzngewte.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2tqobkbbg.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gt2iineuesc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gt2pzurcdjr.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2zcobemsv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnfgbeza.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gt2qbrhsliw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gt2caoxfint.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gt2awqqxbja.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2qxtrbbca.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gt2ttindxyf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gt2rehljarn.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gt2xdslrafr.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ollyowua.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gt2kgoozdjf.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2ufrciyxo.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gt2ahltdixd.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwsqwxsg.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gt2esdsbcal.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gt2dtdxttty.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gt2myemuffy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gt2hsrfvftk.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2mgkpuvjn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gt2plfpmogc.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2rkyowiff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2zmhiewrs.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gt2bglecmid.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmnbqlrh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gt2udvujrvc.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gt2mfrlhxez.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2roqnxuun.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gt2yrfdclfe.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gt2kcoezxxg.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gt2jekpbjtb.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2utkgdfxm.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smrqjqdw.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gt2mzzkzxbn.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiqwxqik.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfrqhenr.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gt2iymgqjfk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gt2wjxtshot.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gt2ssaavrif.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gt2pybphroc.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gt2eqjsglxl.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2czlzzuhq.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkvovase.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gt2rddttepm.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2zfgmahyy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gt2gfgzyxfe.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2mmcbkipk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aktfwzdr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wqznndzx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gt2wyhufjgm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2okyunnms.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enfjqasi.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2iywzykdr.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2dampcmuq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gt2obawaxos.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gt2koaqmjrf.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqcytjxp.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gt2ixfnculo.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gt2ukuuormv.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfcchblw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gt2ohpdtutv.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gt2xynjkyau.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2erjnhgkg.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2wzxgrfhe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2arfzhvxv.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2cqebgwed.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gt2xektbcnp.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gt2gewpwmop.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzylwpze.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gt2smebhblf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gt2hcsweyxv.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gt2wggsnwgy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2keygkjjh.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gt2sdhgnpki.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2nxbiyenh.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gt2ifwnfbhy.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gt2mycipcqn.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2nyigbbkf.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gt2pfzcmkcn.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2wtgthofp.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gt2zgyotgyb.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2yqsqsfwo.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2odqpbebt.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gt2xmtinoai.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2hkfvzgzn.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2meovvhot.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gt2keclcpli.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gt2huteittd.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gt2rhloneic.html

[T20] Swift：数组操作
来源：http://dali.9152youxi.cn/Article/details/gt2fdujfgub.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gt2jycbilwc.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gt2mblnqojm.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gt2zwraullr.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2rfasckeb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gt2gvmgrpxf.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gt2hswzuzub.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yonumen.top/Article/details/gt2ukmtozjb.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gt2tootbexs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aumpnsra.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gt2ipsduoap.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gt2exjxlrql.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2wuoukdti.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gt2wmaihbtu.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvbrxmbl.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2odslmxma.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxgsacqs.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gt2qgvbhhvn.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gt2lqrsusof.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gt2nbvjdkue.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gt2fmmluqmn.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gt2gkaotfoq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyfsrdo.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2patqiflp.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gt2jtzyyvgw.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2urshrdca.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gt2gkndpvfx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gt2punsvvue.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gt2ekldduhz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gt2nawmfcqb.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gt2cykuqctp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gt2iaigoxiw.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gt2tuwoxdle.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gt2vgylhirp.html


<!-- 参考信息 -->