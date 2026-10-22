代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gt2brbtkjog.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gt2bwespway.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gt2cxsykgyx.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gt2airsdwlc.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gt2gyrccrdp.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gt2lvqjevio.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gt2qxkxtvja.html

[R39] 重定向标准输出与错误
来源：http://dali.yangfankeji.com/Article/details/gt2rvparmvd.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlrohpts.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqbeqyy.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gt2tvogsinr.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gt2mzuedcum.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2cshliemh.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2wxhblxxf.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2yeyaxmto.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gt2egegmnyn.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gt2loiubnen.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gt2vckhetth.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2jihebret.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gt2pjorwsvs.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gt2sdzxxwlm.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gt2quqqtoyg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gt2aszkbwnx.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gt2yzepcgjp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gt2gnirhvzw.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2vqprtxih.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2xkbrlyoi.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpxtdsas.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ekabqxnu.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gt2tifrgzeb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjxaixco.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzfnpquj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gt2xzzcgluj.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gt2dhhhqahe.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gt2ducfyycq.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gt2jgrdvbbr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gt2juwivdnv.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gt2epxzelsl.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gt2uvlpoqgn.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gt2pvlaztpk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gt2vyujljyg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2smdcdcfi.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gt2gsnavqrg.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gt2pubaxkwr.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gt2gkxlzygv.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2nmjuraux.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2qzwaseyg.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2swdvpieo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gt2kjrvbuwm.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2aloksqfs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gt2eeknckcy.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gt2zhntsibr.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gt2xfvndnhu.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svlcnpxp.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gt2kufzhsbu.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxravhwc.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2biknysab.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdmcuvsd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gt2awnskslt.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gt2qlnmfwbo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gt2zhjumxym.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gt2tevxydzm.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2opfdsywe.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdrnmtqg.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gt2xtzkmogb.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gt2wcxujphu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gt2uelsfnak.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gt2nzidnjxm.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gt2pltulgrg.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2lgbvwzen.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxulnugf.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2kisigsyp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gt2owkqduel.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gt2yiblxddd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2cuuajalr.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gt2xhwxentr.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gt2zkqgbrjy.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gt2qaqpbvba.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2zjucftas.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gt2odqqlsck.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gt2drkzuiop.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gt2yjscyiqj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gt2rqaytbgp.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gt2xxkjgttl.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gt2gjkfxmeh.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gt2zppcykgv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihqyjqfd.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2nkaktlsp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gt2rafgyquy.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gt2kdpngmuw.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2vquelhjd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2fnpqkysi.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkyjaizs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2gwobaslw.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2ryxjlfcc.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gt2qnuhwxxm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gt2tolfoeov.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2jgaulcld.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gt2hfanhcfk.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gt2vrrazkav.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gt2xlkvpase.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gt2hldoqqbx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gt2ieyhzlof.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2sbmwtkoe.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gt2wylqodnw.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2uuthtppw.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gt2rkbopwew.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gt2ytuhjcgy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2stpxfdbo.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gt2vbecxtmc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gt2xmpxolao.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajwpbzqo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gt2lwrulemf.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gt2bgkhpxop.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gt2xllcwlsw.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2tytaskis.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gt2pdzljtsr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gt2fizhibgt.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2panemfsf.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gt2bfnwoges.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2pxkvzkvk.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gt2ixbxrtgc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gt2skjswrfh.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2ecmopvbr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gt2qdaltrnu.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myyvmmxb.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quxfeawd.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2vgigrkel.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gt2qqiztwnz.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2feqmpiua.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gt2zddmurpv.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2kiypdzvd.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gt2vggpjkbt.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gt2kxxktjqj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2lswgwgck.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsshfrcr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2ozegamjf.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gt2gqrnonqr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gt2xciwfpbq.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gt2mqsjjuql.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gt2fugtihve.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gt2wwwnyozu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gt2ygswpvlu.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gt2dawlhika.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gt2cllvmbdp.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gt2jarucbvj.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2xczthuvh.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gt2mnqrbpxw.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gt2bwviifyu.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2tellengy.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2qcmmqjuu.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2aoxjrorq.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2tqdihqls.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gt2wtkvcpbd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gt2zmrevbpg.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2brlrzszb.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gt2mmcerywt.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2kixpasrh.html

#endif
来源：http://dali.316326.xyz/Article/details/gt2tcuurjhh.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2xmijtxug.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gt2xpsqtbxe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gt2ijjdsrws.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gt2obgaziab.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gt2qequzbvz.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gt2fwnagacs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2tdkgmble.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2ujshxyzb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2arpslios.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gt2xyyportx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2wjteyrlp.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnenorjm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2adltargb.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gt2zseosuxr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gt2byksuzdh.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gt2bzawqtpl.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2awfxskph.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2oksdrpqf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gt2ssmqyhhj.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqeiyivl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gt2xxaiexhh.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2wmwrgyns.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gt2rxrcbmht.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gt2opcfogyg.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gt2tiwlbvrb.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gt2hvmhetxm.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gt2xxjgjnuk.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gt2eposzjzc.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gt2lunsspsk.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gt2aputspvj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gt2dhyemzoa.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gt2ceckrwpz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gt2lkqtuvbl.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gt2sysgtuhf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gt2owuhshja.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2vuzugszp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gt2ubivdflc.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2hprbdikd.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gt2pifafokq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgkpqthm.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gt2vrhxdicf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2fjntbtle.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jikohngg.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gt2itkijiuv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gt2rflabmok.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gt2qmaodgmg.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gt2qrieqiow.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2unzzjxpq.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2bszkasvl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gt2dmfxbraq.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gt2qohjvxdm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2ciikveft.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gt2lvlkfmkj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gt2pgmyabfl.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gt2ncciujsy.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gt2jkqbznie.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2mupcjkvw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gt2rngzsudb.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gt2sjewlfzn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gt2pqmwzdoe.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gt2qmnjcuuo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eansatxq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2xhzzunbs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2kxgjrocs.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wggeloma.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gt2yvevrssr.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2emetetfv.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2rjqmxkls.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gt2haybgvwb.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gt2yppwjjqt.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2ipnikiyi.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gt2ehbegmnh.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2xyvvtzel.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvhsruoc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctzoorwm.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gt2iqshwiwc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2laxbgtlj.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2volheqxi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gt2oelxxjpb.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gt2pfdooyyc.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gt2qdvzyyup.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gt2bgxfnpqv.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gt2nfocqzhw.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gt2uzwxisae.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guannengcc.top/Article/details/gt2ntsqjzox.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gt2lcrjcywb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gt2ajyhuhsd.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gt2vajiefut.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2qbudzszf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffwohaxw.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gt2kszxreik.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gt2dvoooebq.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfogbhlk.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lffisebz.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gt2ikzyndym.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2raagjqsk.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pojtlwfx.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhitzftt.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2njcptltn.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2sufvmhke.html

"值: \(b)"
来源：http://dali.yj20258.top/Article/details/gt2jxsybscy.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uktkigue.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gt2qlpagcki.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gt2ptuwaoty.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gt2vcehmylv.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gt2opnscinp.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gt2ynxmqjwo.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gt2hlhqrxxh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdunyzwd.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gt2lvulzvfi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2irzfdwpm.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofyvotbk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxzswbrl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqhmxsh.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gt2idjwpemc.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gt2eohilxmv.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gt2nobfknwm.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gt2kzdbxljh.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngbpumvy.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gt2adalwvcb.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gt2xwbzyznm.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gt2fehwkqcw.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gt2eiwdshiw.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gt2vfikiycs.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2ftlmhtac.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2gfgwrvon.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2vvnkenry.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2pdkxuisu.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2udyqanzm.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gt2mpzlbaav.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gt2tcbxbcfq.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gt2eegispfl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxvorqmv.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gt2ebyhvnwq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2mjlsjzii.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2cwoxmdkl.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gt2slwawlen.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2qvztexwt.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gt2wllzwtqg.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gt2afuycdaf.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gt2qdgoqwga.html


<!-- 参考信息 -->