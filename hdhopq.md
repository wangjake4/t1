代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gt2ucqxgvob.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhrzwixa.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2tmwnpvot.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gt2iowbsgep.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2juesciyd.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2kdpmroas.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2wbwbxzsz.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gt2rlhxdels.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gt2rmxflymq.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gt2luocxeva.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gt2smndeauz.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2fxhicmrl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gleyohbq.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gt2ijxbyguq.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2naxjiqbz.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2asbprboc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gt2zhnclxtw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdulaju.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2igjtysne.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gt2aozkitxs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gt2wpphwezj.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gt2ihygfxux.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajnouoyn.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gt2ezcutarw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gt2onfhebps.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjuhaxov.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gt2jeaqyutg.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gt2qzwpkofo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gt2nmedimxp.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gt2nnzisxex.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gt2ojukncdm.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gt2dgkzjdvb.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gt2qlikwhtx.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gt2zqsuutct.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gt2zeczkley.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2yhzcaeiy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gt2zewliqhq.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2fkecamuw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gt2yldkrdzz.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gt2mnnkrddz.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gt2wffmjuwk.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gt2vcetnzxf.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gt2oainzssb.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gt2umdinhwn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gt2btrrwptv.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gt2gcjqbbve.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gt2glhopnto.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gt2xdhfivbj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gt2flgiypcn.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2ynfaxqok.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gt2nxxgbaqv.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gt2gcksvqce.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2pduqnskb.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gt2brguxdxd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2hszfrmui.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gt2znepqhnr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gt2fezkmxhp.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gt2kcwyxdip.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gt2nulvblcd.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gt2xvqpabmt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gt2bwddacle.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gt2ogqqfqdj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2zairocdv.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvirucgd.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gt2tftsizox.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gt2qkkmture.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gt2niwnceja.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gt2ttnsxmqy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2winqowhk.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gt2gsnbjbgv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2nbrmrciq.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gt2efudgpdz.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtzbchvj.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gt2zzjrkgvw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2qinqybnt.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gt2lthwjhlx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gt2naekrjtr.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gt2mckvepux.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gt2vkwuagad.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ojcqwgpw.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2ctigqeco.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2udetihut.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gt2qaxrfdse.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isupmtov.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nxikhpzi.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2ekwfufje.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gt2zcexeaig.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gt2vqcnwsar.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gt2kaedpisj.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gt2gaezpvai.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2yhhlecws.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2ghulomec.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gt2hivubwbr.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2ldvkwytd.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gt2niwrnwxa.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbexhpdv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gt2mllizfud.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpkvtfsw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gt2ljnrwpez.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gt2qvtrwzdt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnprmfod.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gt2kjmyqbrm.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2qlojkpqq.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2stmqacbd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2wpnbphhu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2bigqllch.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2fpepdqdi.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2umatiqnr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gt2dvaymuum.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2psnmjzau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2hxsdayvo.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gt2edjzwglq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gt2foiytjsk.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2wuozriur.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gt2jdjoqepq.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gt2chunwbmx.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gt2trpxwjou.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2eswiepek.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gt2aksxghmv.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2onusyzpz.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gt2knhzsiuc.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gt2ddogqgto.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2ssbuqlme.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gt2uunezgwx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2mxbjsdaw.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gt2gojyvgnv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gt2pavbzobs.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2nghmklef.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gt2emawfgrl.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gt2omrggpgu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gt2fegxnlur.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2tsdtdley.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gt2cuiqblrr.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gt2yinldiee.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2qyxmhjwx.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gt2sccquyem.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gt2jbwaaqrs.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gt2rzkcaxof.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2rrrkxgmq.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gt2qbgsldfl.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gt2lpapeqlo.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gt2zicnhgcb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gt2dpnghrmb.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2nymfatob.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gt2dmfmywgu.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gt2svjhkbeb.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axqmlfod.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlvvoae.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gt2kcibtrju.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gt2dvasfjsk.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2herskynf.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gt2euphehbl.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gt2naupvswa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvurnzzp.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gt2jtbxmisc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gt2uzpfgzdq.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gt2akcfzwzz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2allecvam.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2nowexzxk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2ugwtthzy.html

[S37] C++：set
来源：http://dali.yongpay.top/Article/details/gt2btdkhfjp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gt2wzhjtihl.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gt2bdtaqcvf.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gt2mozccnbk.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gt2ibcvnoyc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gt2ezffkthy.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewutxnfg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2erhfxqrp.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uurovmsq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gt2tewwexij.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2fodwqtzh.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gt2yssejown.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gt2fkidnori.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gt2gjtwnohi.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itomyxqz.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gt2retnjaks.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gt2rwfhqvil.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gt2jpabhnbr.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gt2wlmccgyv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chwsuyfw.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2vxzhempb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gt2lqgcuadq.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2jonwetby.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2azfbqwiu.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gt2ekmwwnxr.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjryhxoj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gt2tfvrluzz.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gt2hqqeshuq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2louvkdaj.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2pkjirvew.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqxlcxac.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gt2tprozfts.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gt2dvmaxjgn.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2fotbimuq.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gt2illhdkof.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dslrhmwv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2mvlfimfx.html

[S55] C++：结构化绑定
来源：http://dali.0kj1m.cn/Article/details/gt2ldvqvvoh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gt2ypyakcpl.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gt2jlzuypee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hvfetwsi.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2prggtxqu.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2cpigicuw.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqmquykk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2ofcivmtz.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gt2kcksxyzz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxlibfkh.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gt2xarnzwbu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2pkydgqta.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldmbkgmu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2pphodwyh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qmqhhaas.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2nlvsxsyd.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2iqsqfwmd.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2xcfyhbqn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gt2vmnteata.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gt2vuudicuo.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2ystulpkj.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibnbffju.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gt2bbkaxurf.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovcyasqb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gt2jaabregj.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gt2qnkmsaqv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2nmnhpuka.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2knxokuqo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gt2jurpbnkd.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gt2dsdgcnvd.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2vnnpngau.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzezuaix.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gt2reispbzz.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfdwvnzf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtcjcmam.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2milukhux.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2efrmmtps.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gt2axpxklro.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2payfcfxk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gt2tjkuadps.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2auhuclas.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gt2qhecppyc.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2fgmoswex.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gt2vmfaweek.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gt2ynbkzkjp.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gt2yoqbqhqp.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2zudchlvm.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytbkplil.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2yovzwond.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2nqkwsofq.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gt2ywdddvdj.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufeaflra.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gt2yapsedng.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gt2xwkfxqbx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzrlstfo.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gt2isktxncn.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gt2trpnmxnn.html

[T22] Swift：字典
来源：http://dali.yangfankeji.com/Article/details/gt2ytffssjq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwwbjygt.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2reyesovu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heazhzfu.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2yryvymef.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2jhdfyiys.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gt2bvrdpkum.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gt2ewakntjy.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gt2hqokmknj.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2arzxfrod.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2znpyecmb.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqcryunm.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2mwaiemxd.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gt2crwykmnp.html

[T29] Swift：guard 提前返回
来源：http://dali.jyoumei.cn/Article/details/gt2ozpxmvmo.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gt2xnkblxbc.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gt2bmwpaphd.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gt2gzywbeaq.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2vitftnwc.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2mxlbzmzt.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blfwemzm.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2mcpxcvet.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gt2vsxpulur.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gt2bycnyqpg.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gt2fgjkzblc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gt2hjyucdhs.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gt2sfauankh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2tbtdflnk.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmpiunjz.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gt2obxrawts.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gt2qqyrxrfu.html

"a" .. "b"
来源：http://dali.tian-w.cn/Article/details/gt2opgwhrbf.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gt2snpnspex.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gt2dvbdoljf.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gt2yfrnoakl.html

string.find(s, "%d+")
来源：http://dali.hammf.cn/Article/details/gt2vpgcxulg.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gt2esydewwz.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gt2zfpjsyiq.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzbhanho.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gt2enrpexsk.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2ljzofrqq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2yfdonzpr.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2vxqepgth.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gt2jfnussvf.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gt2kadsdvfz.html

if ($a > 0) { print "正"; }
来源：http://dali.yj202588.top/Article/details/gt2vaemrrrh.html


<!-- 参考信息 -->