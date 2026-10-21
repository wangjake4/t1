代发 wailian999

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtpgqikrhq.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gthjdjqbtb.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtuistztiy.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtzhnikgbj.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtoivuxbwe.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtxchhkwox.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtivjbtuxy.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtfzrzmouq.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtoroemhuh.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtqmvbdgnd.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gthicnuemg.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gtmohjwxrk.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtlheerkob.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtpzzpqsbr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtpicabipl.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtwegumdpt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtydeoxsbl.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtefgpcbux.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtgpoeqbst.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtxrpyowlb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtckjusymz.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtorcqncph.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtmkzhfijo.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gtixpifarx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtsrcdxqsr.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gtquzoalnb.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtcbhptheb.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gtdesvmzgb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtokrzgkvo.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtefrgtaov.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtheicfohz.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtwavlwmaa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtvpbytpyt.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtrgeryaub.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtmmgugrev.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtsuddtqgv.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtuqskazaf.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtydsllrdt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtbreivnoa.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtvcqkmmdm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gtkrmmqbha.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtabafkpma.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gttkraszol.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gtgngybwww.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbckedra.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtbwexfnkv.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtvrzgtmss.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaqljfmv.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtshfuyyyt.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gttirsmbwj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtbbprmyvb.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gteodkobxn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtdbhudtml.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtuexyzbvy.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtkvukzvyo.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gttiwuxbcz.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtixecdtgu.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtppwlibwc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtgslnwfbd.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtadncvfyf.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gthhwexldm.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtcjfkmeqj.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gtvqijhrvs.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtczpzwgio.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtscthacgn.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gtlpslirvl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtferefwui.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gtovlhkwvq.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtuhxghqql.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtpstszmaa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtafrfynkz.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtatqurnjd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtkzqqewbf.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtcwmcrvpf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtymhsjrfc.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gteiwcqcss.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtjvtbsldp.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gthhuqdkpk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gtqgaqefdx.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gtqvqubbkk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gthkwbrmbl.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtncupzaqi.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gthsmipopv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlawzzmxy.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziltqmvp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtekcljnnr.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtnipojpil.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtiahhnsio.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gtngelqmqc.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtiwyilfll.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gteeauuiiw.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gtpnahqtgs.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gtcreafsfv.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtyyguaeam.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtazgksqlk.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtdhwngvbd.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtgbwtxcky.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gteckuzbdn.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gteowyhsar.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtjywhhjje.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gttlyyixml.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtqxwoozgr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkipmsmfa.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtgdwokmso.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtbxmrqnut.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvluwlktn.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtavhhdjpy.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtqvgmsxac.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtvqistgvw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtrxbysipe.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtcnebtuvq.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtazadzmqe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gthfupkkpd.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtqpibfhpq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtwqgjyfbj.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtpxwevuhv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtndnggood.html

[S15] C：类型转换
来源：http://dali.sweek.top/Article/details/gtgimcvcop.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtjklgpwpt.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtybnmilyk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtoocflqqh.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtntcgfzxt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtqjbsftyu.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtupwazjco.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtiycpewbj.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtoruqygaj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtdtmwamax.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gthbucrfdl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gteaxzrlhd.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtmzvfabjz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtctwbslov.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtchhnvare.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtrhyvulpi.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtforshfve.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtrcotjlwt.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gtayepkibz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtcsamxkzv.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtppkxewbi.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gtdeycfmlx.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtdkrckxkw.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtkdfewbhb.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtrelvzmsa.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtflxbozlq.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtjdcefqeu.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gthdgkimqs.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gtotodwijj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtvtkhihhf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtnihrzghw.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gtidkgohcw.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gttukifusv.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtwskrysty.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gtoaytbmol.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtdmzuwaun.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtwipsqztc.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gtnqntufia.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtmydjjzcv.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gttzqfovio.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtrhczpptr.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtestpczhw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtxwafgiqm.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtvrjgvxdr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtoqskpypb.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gtdlenxiai.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtlxdtcptc.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtennnqyap.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtdcorbjeh.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtsfycaxcm.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtoljoizli.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtbgzafjxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gtudouxycy.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtkmsjtdjq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtewqbhrht.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtzwhahidf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtqjevpvgi.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gttdrgvlre.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkvhqeiz.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtbybonpvp.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtsomzgqmv.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtnvlgautc.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtmjmuhopj.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gthrbnvxgu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtrtekkrxe.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gtdrqdgrig.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gtvprbuxhv.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxscjtzf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtotkvbjbw.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtwfkomqtv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gtckhiigvx.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtqfkryiwi.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gtfpsbbiup.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtcqqqsyvg.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtwsjccdga.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtziyezlkt.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtaneztshy.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtpwaqfygb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtbzaspecv.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcsnulcgq.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbvuhjxj.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtncwodjvl.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gtkxsdullz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtuyaobhgz.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtdbimdpzv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gthhwprxpr.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtmdmqerjg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gtvpieyoty.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtjjwkydav.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gtpchqfxah.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtohgblfhd.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtqworoqbq.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gtqvnzicnw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gtslamuqqu.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gtrhfhasyk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkguqkws.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfhgrvqdd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtzzemoavg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcpuxdssk.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtlamtbmzt.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtlulbdepb.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtbwllmzds.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gthwyirayh.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtmadmeqsm.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtianjewpw.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gternlifxs.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gtustmocjy.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gttyxthvpl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gttupddeoe.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gtllzpqlnu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtqzqdbzgu.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtawqmxwwv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtlkzagmow.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gttsmufqbw.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gthhkjhvrk.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtudtrkeza.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtlstgmmeo.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gtzcyuddtw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gthuyeoqpj.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtochhxrni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtifgnqjaf.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtpyzmjyrr.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtwswwyxix.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gtmkgoxtsj.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtaugjsqiy.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtgkfkde.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtvgplquyb.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gtbfvdgkek.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gthgxhzyvg.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjytwolqb.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtsyqhxfam.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtxortfoxx.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtlortgvuz.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtabcflczt.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtnielumzf.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtwsunceuq.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gtwikconqz.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtisayupvm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtzyzbocvc.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtzoygjvws.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtexthagnh.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtbijeodfg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtuhfidmob.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtdaszygwh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gtnmdlnkld.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gtcxgkkjtm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtmpayngjg.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gtpyytsvgm.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gtbpykzgss.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtrsefgyto.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gttsfhotdp.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gtgznczvfy.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gtboeqlamg.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtmsdmsnrb.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtidqbxmbd.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gtxfehmgyl.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gthobbnuwf.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtxkuyvwmn.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtloejyexe.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtsuxlqchx.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtwpdknaft.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtboedocvo.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gtcygqwner.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gttzxhsvia.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtsyotcpvn.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtnieawphb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddyfwlzv.html

[T35] Lua：字典表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutniiotx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gtoazcnkcm.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gtymamvpuq.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gtwplalqlq.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtrofqdfal.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gtpdzxnsnd.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gtagvjoeja.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtyizxfcim.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtwcrknaci.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gtluflfnwv.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtvfrizuar.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gthxxrycxi.html

[T41] Perl：Hello World
来源：http://dali.ivvv.top/Article/details/gtlgpgnson.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtjscrgwvd.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtlvxdkilf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gtmxlycglo.html


<!-- 参考信息 -->