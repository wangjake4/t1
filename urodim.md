代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gttbrcgwex.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtmayepznq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtvisshjqz.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtrsingbqe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtuscrjimt.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtgjvdbjls.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtjppnkgzx.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtpavupsuv.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtahytibif.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtkzqjmlii.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtyazsoibv.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtjgjqtwik.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtvrdwapbg.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtjdfdhdpn.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtutphqueo.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtujekzywp.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gtitfqzetl.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtsjaxyzso.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtwkwdjhfu.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtoqmtzyxu.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtbdmvtnie.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtobruxvzu.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtsmgzhfjd.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyrfjwkb.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtadaamjkg.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiexbdad.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gthknmjjki.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtohtzekvu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtnkaplawd.html

[R48] awk 取指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtmclquuci.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtejqqjsyl.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtclsllobv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtsalqrxal.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gteqedydcf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gtzryagxoj.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtdwhbnupu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gteydeccfn.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtmhxrcpgc.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtkwvdltgo.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtnhawyjms.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtsmnyrmlv.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexapimiu.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gthfenuefi.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gttxxajdis.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtygzjsdjh.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtmhfspdwa.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtbqqzwsfw.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gtasupvmwy.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtswnpqkop.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtxjbymujg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gtzgmccywe.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtunpopkpn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtgqmmrbdz.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtflfgypia.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtqexxdbmy.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtknkzpvvu.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtlpxiczgx.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtuhcjivom.html

du -ah . | sort -rh | head -10
来源：http://dali.hnqzz.top/Article/details/gtrnjibfej.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtowsnbrcw.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gtfisaxasw.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gtjsvyfarw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gtjpydacmc.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtfhrayvbr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtxdqeffms.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gtcehaqeve.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtdemxqihb.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtzgzxqttu.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtmncwwqzp.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtodifadsj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtrkebimry.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gtnzjbumfw.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gthvdbjloe.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtqiujeqlu.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gtnkohyxna.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gttupuhlsz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtkxyhkpsb.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtwgqbotyi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtrymljvei.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtgkwxdqta.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gtisxcegtf.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gtwtuqkinh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtzuumsldl.html

[R75] 导出环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtsssymoja.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtcsaermrb.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gthmchkejf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtnrnvgmhf.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtdzunyvjn.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmihovrte.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gtjxgnsluj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gthyscsdha.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtjsqoolgm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtlwjzisiq.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbmlkldr.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtsnfttjje.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyolobvfy.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gthtnidovw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtlvwlriky.html

[S01] C：Hello World
来源：http://dali.iojbl.cn/Article/details/gtopcdphry.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gtnxexrnko.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosymunoj.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtgfksqpis.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtxphijhgw.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gtcdsutgqf.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gtijkulxax.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gtzubxlkor.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtkelwkroj.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gtsvsnltcy.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdjfonzbi.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gtklonojaf.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtkehmncfe.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtwuutsgkd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtwuqoopon.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gttjtjfhqe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gtkmzrckza.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtpklljlhu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtltljjrfx.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gtnzhhamdy.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtgkyqtkhu.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtqbrcxdzd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtzprigfix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tanke756.top/Article/details/gtllhwmtlg.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtrfzagjbs.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtlxyuvvbv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtsxaxxzch.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtfmywplzo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gtckwhezuv.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gtgvvsmtvq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtoejvaaro.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtvojwwzbn.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtkadxzzds.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtotdergru.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gttqqdjjtg.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtlrbbsudv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtmfhydprn.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtalqcgwdd.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtdhcvhoyz.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtffxiwvaf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtwtrjppyh.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gteiesmvoa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtkattncts.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtlnwywpav.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtwcsvtnyi.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtkhajrdkk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtfmaytqbu.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gttienxblp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtirwkucvn.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtojopctsm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gotoacloud.top/Article/details/gtyfcquwbi.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtfxnoqyfj.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gtyhvtuxvj.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gtobloipok.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gteownfkxw.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtreowcieb.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtxufmpuoq.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtezqzcknh.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtrwrqhrgr.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtrhcaqlpc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gtziuyllmb.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtfnnsnreb.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gttinzxspf.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtcuquursd.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtxnwewmwl.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtgkpfjdjp.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgxsjraq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtjmrgksro.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtorvlflsq.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdidtyddg.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtlvzdpbvf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtqxzqomyp.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtgehzhvda.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtsavjaaiu.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gtsdrrtwtp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gthgxxazlf.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtqzywmija.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtzmigbafk.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtrafuedmh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtuigxkcmk.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtpuvgydmv.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtxdihdshj.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtwlozsvlv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtvnkcuaqp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtwxxszdkk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guannengcc.top/Article/details/gtfsygmoso.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtamksdecg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtcymtobqr.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gtstnmjdlq.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtwhtxwjax.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtuoqyqfqi.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtarxsrgkm.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtweedpyxk.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gtxicbarte.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtkzhgznvz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gtyfxevqsy.html

[S46] C++：函数模板
来源：http://dali.yuxming.cn/Article/details/gtdzmkvkop.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtbxsnhfod.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtnndnjrec.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtkxjzwcsj.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtcocxoffq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtwkcgtwlu.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gttgrxvgxy.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtupoxxcnp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtsxezqlxl.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtujfimiqw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxwiqnif.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtbtnghckm.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gttpftstmv.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtphhgeuww.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gtopkfnpfe.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtblayudvz.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtffdtbepl.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtotlrzzzc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtlehmdemj.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtkehxtdom.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtdcscquqr.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtfvkskmfu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtastzfbnr.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gttjyiwshq.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtrcgmmjyl.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gtpoevewtf.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtuoucevgc.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtipxrdyfb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gttbqfkqkc.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtejaxduno.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtsvkublpx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkhhlzqjm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtxibojwru.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbhguxixo.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtqucqchyc.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtxsdlmxly.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtsknkgocf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtqcufydkz.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtakqtzrid.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtevpnezhi.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtssqsmyuz.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtdovyurgd.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gtqaliasfx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gtigodjoju.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtzskpaokc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtidagssub.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtkkzjrhsz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtlvwdlwdr.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzjxtaqh.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtwlzpbeiq.html

[T09] Kotlin：扩展函数
来源：http://dali.cheryme.top/Article/details/gtjsktmodl.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtuehbxyna.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gtxxbzkjfj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtxkyiwbrt.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtxugfcwry.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtwiagcgpg.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gtzoqfqzdb.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtoxgdypom.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtclmsqxvo.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtnayhnxrt.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtbhuzpapm.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtsbkbhtql.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gttrnqicdn.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gtphduounp.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gteqlwmspu.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtgbggnvzw.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gtxqixsjci.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtehtaplmd.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtoodtekkf.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gttadcdpdn.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gtuuhwqrmb.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtahjnywnt.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gthcyqjwtf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtowxlxjzb.html

[T21] Swift：遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtrnvtovcy.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gtahybyjfo.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibenppns.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuanzhike.top/Article/details/gtgfxzjjjx.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gtfxahqacd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtxtswsiom.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtshzsmraj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfpcqjdb.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtskpmmkae.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtgachjgtf.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtrghppsvt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtzwpdzxzq.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtquuoaumc.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvmmgycv.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtmzkgxrgr.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gthlpgbwwi.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtqunflvfj.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gtcnfvjbvm.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtsaodrcdx.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtwwvxbphl.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gtfmimhvuo.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtsoxgouin.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtbeifhfsf.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtqfsbkzgt.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtcypslnnx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtqcrauiqm.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtlmptevtq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gtutozbeqq.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtfwyzzarz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gtbldbashf.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtvvuyvvdm.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtqohtrcfv.html


<!-- 参考信息 -->