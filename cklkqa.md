代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzqcywwx.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gt2xvzryqbw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gt2uarxgwek.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gt2hofdzbri.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2zxxwymme.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gt2tasgkvjc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gt2mjouhimv.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gt2jahskejk.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2jtskfizb.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gt2zdigzvlz.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gt2siygmwlc.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouixkvum.html

cmd >/dev/null 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2unayimhc.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbfocvck.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2lehnmhdi.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gt2kqalscth.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2gfziijqv.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyifplpr.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2xonsnhgd.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gt2rtubzufq.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gt2wmgrljuk.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gt2hiowlchs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gt2sypglxxj.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2guxnevor.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2ayemzvxf.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gt2pilfbavc.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdvcxnlq.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gt2lzepdtsi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mngbyzvt.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gt2yhhpetzx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2ntjfyfsb.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gt2vslxjrnc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gt2kvvsusmo.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gt2bppqwhwe.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2rgngktek.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gt2pffxdpes.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gt2wmfkbjwl.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2orwgbwvv.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gt2yftelomp.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gt2qafrwkaj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gt2gwqkwwnk.html

[R56] 远程拷贝
来源：http://dali.fengsongda.top/Article/details/gt2twstsuef.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gt2ascjnfpt.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gt2zbfrziuk.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gt2rermrypi.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gt2jiqyeggc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gt2ysxrwytr.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2gsvtcfay.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2lbtatrzd.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gt2ztionrya.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtfdxmwc.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gt2umivgbsj.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gt2yxwonswq.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mypiqgfa.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gt2evxpochr.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2mxklegit.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gt2hiwtjfgn.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gt2nkwwccie.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gt2dtfwdmks.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gt2zwfvihbm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gt2kxotprya.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2unizeboa.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gt2gotjkvpv.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gt2adsiuubz.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gt2ajccgvoq.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gt2ngtatzka.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gt2cksclfks.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlsvbwme.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2fswchafc.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gt2hvgrmbzd.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gt2ppdwhzhd.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2qemqxbyn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gt2uszputgc.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gt2iulgrukf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2fjjnpozq.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsfvjxdr.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtjvhlnj.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2hblbmvkv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gt2gsaxziup.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2mtawiwdi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gt2oxxbnigb.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gt2acnkfxti.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlkxsfml.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeqhnigq.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gt2kkqqpvwt.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gt2wrphalkw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gt2ddrxdjjc.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gt2euhtvevw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gt2rgwckbto.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2dldeuruh.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2ljsyzant.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guwrybke.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gt2ndsiavvf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jsxghsos.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2cdshepjq.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2oanjkqzq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nrfzliih.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2jjbukbmd.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfcowlqd.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gt2zsbyqouj.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oswpzaep.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2bhfnxnzo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrtkznky.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2vybbumqi.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gt2xyanjghq.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2hhhrslry.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gt2ciqfwgyp.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gt2frsrydxv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksybxvil.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywlaezbl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gt2pumftplp.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2zlarvruv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xexenexm.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gt2beblvvof.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gt2vqcvsyom.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2mugcotkx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gt2vsnwxoxk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gt2fqqugrto.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gt2hrnbnodl.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2ebcbyqwf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2zfmvjbfq.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzixfskm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gt2oehcfwst.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gt2sdnnjcxe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gt2oobmrgnk.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2ztkeqqov.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gt2dlpfdsis.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gt2jvevudjw.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gt2seoflkjf.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2gmizooer.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gt2eoaeqlmk.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2anizkcol.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2pjnixkrr.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gt2zblzdgui.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emencdon.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gt2lpyzoawl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yntkynbd.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gt2emdsxaxi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gt2snewaugt.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gt2trarbgiz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gt2szuwqpfd.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gt2vuwyxylt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2qanuxqxl.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gt2espqweqr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxldgpwu.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxoxhvvx.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gt2hhtnqcsf.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gt2qtkbqtzv.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gt2dxbiglgz.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gt2gigdfrxf.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2lxjarwtd.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gt2slhvbmem.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gt2yxgfdkae.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxakcgmg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gt2stntzbcn.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gt2dadhhhqu.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thifnagd.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gt2jcwkqodm.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmxkwmay.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gt2gjlsyyny.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gt2ladjkgvx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gt2bsnsrwve.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikvljfga.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gt2ikpcyhhg.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gt2hmnbjcwm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whofbvuf.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2krpikpqe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gt2ifkxgaln.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gt2rmjpmlin.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2edqbdzrs.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gt2dtcbilkv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zaktrmpy.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gt2qrnwxyqi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gt2fgwkfwyi.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2beqqxtyx.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2ioupzyzx.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2efssqfua.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gt2semywccd.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gt2hjwaifkp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gt2uylwtqmj.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gt2vxgedwpq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gt2jjrlpvhh.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2ysuxqonj.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2epgafjrh.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oegxnivw.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2kcpjywre.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gt2dvytwzgj.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ftsktqlh.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqbjpwcj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gt2oqzkdevh.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gt2eqrvkweo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gt2fkmyxciz.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqbumiua.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gt2eksccmnu.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2naopqgkj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2nqhcomal.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gt2qgyqprdi.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2izvplyzc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2xjqrvjgq.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gt2ifbzcrcq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2fbskemxb.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2asbzegnm.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gt2wayqtrvo.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gt2kyhoswwu.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gt2tbhxcygc.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2mmhrgyxa.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gt2wcinxcfe.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gt2tpbiling.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gt2zhxzdtmb.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2kzjgqkul.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gt2glbrnqig.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gt2iapgzbik.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xtkgncij.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gt2ikajxckx.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gt2rmigebvv.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrgtrbmb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gt2fefszurk.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gt2zuknusxp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gt2kgapnimv.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gt2gyhyfcsp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2foolrgga.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ngpjbxiy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gt2jxmjflvh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2iunvtvvj.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2qqusgttu.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2dmxijrvv.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2btvvynpl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gt2ezmrbmwo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chnfyuem.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gt2umpedbcx.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2rujugbiz.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gt2frhlvyoa.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gt2mrnewlea.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gt2jtlbqccq.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gt2qhieeilx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2jstsiksd.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2dmbdmubk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gt2ncqhxvzz.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gt2bznhzmwh.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2cdjtkngo.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gt2lewyelwg.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2sfurkkgy.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2dioblnkw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gt2sdttawni.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gt2zkgxlons.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gt2mueuzbtb.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxpbscdn.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2oeihkaiq.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2aseuznzi.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gt2kzwvqnsw.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gt2xjveuzxf.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gt2zcktmasq.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gt2cfwwrnzh.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gt2xhhgarli.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2wxeuxitj.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2vdylskoj.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gt2jlihzzya.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gt2hqfwspgi.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2maemjpja.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gt2hfjsgcvm.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gt2aidrrehi.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gt2owrkkgee.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gt2ngxnubvd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gt2hnkorrjl.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2hlsvcrib.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gt2twcjpono.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gt2ofcxomjy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2hegdgbne.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkqeutoc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2gmtrqjso.html

[T24] Swift：闭包
来源：http://dali.yongpay.top/Article/details/gt2clrkzteg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2nrcgbneb.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gt2gpxkdcrd.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gt2vulfjaqd.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2tgjntvif.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gt2rlgqhmkv.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gt2ioufeodw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcsaizu.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2jdjkaucz.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gt2beezritw.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gt2tpqjiiui.html

guard let x = opt else { return }
来源：http://dali.daxiang520.top/Article/details/gt2rosblfon.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gt2loepquds.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gt2nuwxpxjl.html

[T31] Lua：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2fuogucfz.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2jrufhnuj.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2bchdmtqm.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2rqvycupw.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2hoyfqlsb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhixingplan.top/Article/details/gt2lnakddxn.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukmppdzz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gt2ldjmvqvi.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gt2wuqvpnni.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gt2dggurnxd.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gt2fpymbeoe.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idjhxbqy.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gt2agwuhpap.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gt2czptqgkz.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gt2eqhanzpy.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gt2vulojudp.html


<!-- 参考信息 -->