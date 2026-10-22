代发 wailian999

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtgsknwdpe.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtijzfiqex.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gtybfraish.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtdwqbqznw.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtbfdafkat.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtzibynmtc.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtuvoovkfo.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gttfahpwmz.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtbfzbykod.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtguexftgw.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtctmihxcp.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtyfdzzsgk.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gtlwbaggod.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gttqlumwqt.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gtuziasflb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtarjhrqpv.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gtiqnlafhg.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtvsvrdwue.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtkbkymlix.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtvyjzorub.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtonmqiunv.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtuzimpils.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtsrydzygj.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtzoufkutq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtzzfhwjks.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtdrffuglo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtoeagpbff.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtjfzazelt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctmlcvzq.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtgwhqkjnv.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtwqvugplv.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtxikjiyyz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqfrozeo.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gtercyrfwu.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtsmwzmvul.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtlmkuwmoa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtyrchajoi.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtchixmerr.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtbiylrkaz.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtbvtfsjkd.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtezipfrxm.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gtbzxsvnjt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtnoxruwzd.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtxgybrnua.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gttcjrfjua.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtytozhagt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtkrivwlnf.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gtkbicnapm.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gtwukvpzfy.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtgjnhqxjy.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtrqyvalvl.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gtecegrdtc.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtdsziqgny.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtsiqvkunk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gtcmwtdyyo.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtbghtusns.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtnjrilksq.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkaczdnc.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gtiinzgyde.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtrqsanjev.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtxvflywzi.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtahwdpcdm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gtmotpxnzb.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtucbwwour.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gtoictqmec.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtwrbkppcv.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtxhfjgfbk.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gthxrrhmic.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddxpbzfk.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtxnhygvcv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtmgdvfckm.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtjtooroqe.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtvfasfsut.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gttlfaqjrm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gthptkedlw.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtfrcdlvdb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtpscnbcdp.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtqjyqrgoo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtsjoeecvv.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtpyogigbq.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtgvjdxfte.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gttifvittl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtvlfhxigc.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtoytgggvq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtinikmesk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtrgmixvln.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtpbixoxtm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcjnaibhk.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gtyrqkapxq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteofzscvp.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtwvoatzed.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gtsntqfpya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtrnzzlpqw.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtzpiyrgyb.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtrowxtevf.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gttqhoidmv.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtsytgdxnk.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gthigxwjfx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gteakavoqi.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtznqrswgf.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtrqoqkgcd.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtxdichzai.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlqqjcxn.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtciffnjzn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtknhytpto.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtxfjqhxyg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtctoweskg.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtrpxxpjwv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtvcawdmrn.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtkrzmlvhc.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtfuhxnrqw.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtjbkgzbgr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtxheslbnu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtinayyzmz.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtozmnwidw.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtmeodasch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtbvxsenxw.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtxtkvzmnn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjbmrlto.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehjpfafh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtjpuqegpn.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtqtqkvkya.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gtbmqqdqna.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gthlbfedun.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtffkwkpco.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgfhopfq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtsgzmttwz.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtzpawvlub.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtvdovaayv.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtsbvgipow.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtlqpncmez.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtjjybuzxt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtjuxqodar.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtuvmwugbm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gteebgkkqt.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtnvxqfcpu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gttqvikaym.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gtaktruxfv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gteoiakxrv.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gthfmxaaez.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtzclhxnyi.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtivgslyna.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtktgltwez.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtisfheozy.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtfgpdmxif.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gthrroylvj.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtqjdendhp.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtcmpltflr.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gtthciokbs.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtfvgrzoxw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtjxgmueao.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtbaocskob.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtjhunbnrd.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtubjvuizc.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtgekysjdu.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtzeggjzup.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtliefdxzj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtdjnlrpvc.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtjxstxogc.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gtosrstquw.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtpjykmwax.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gtbxpdcfgp.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gtwmwbeatx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtkpwxskhi.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtnthsrucd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtszhmvoda.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtyiqawtpl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtoynmpvmn.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscqnzhpx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtnhyadhfo.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gtifbvirio.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtjqbwwfns.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gtqxathedc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtrhvribzo.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gtrnlqvytz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gtdwknhlfn.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtrrrlsoez.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtumsjxlpr.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtojbcfyiz.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtibjfpani.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gtodduyjnh.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gtpvepxfqd.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtrhwvwosa.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtrfbrcgxw.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepnjzllo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gtgpokeezt.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtluqwcxkc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtgrbgpxce.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gtmfpwszsj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtiusqudwp.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtjddmyxun.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gtnpdjcqjy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtxryufjba.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrelkerkz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtbyuqqncp.html

[S50] C++：格式化数字
来源：http://dali.sxryk.cn/Article/details/gtkxspxelv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtlhrqswcn.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtftobumkt.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtellnqwud.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtjaopkaub.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gthgiojwtj.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtembrlnnn.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gthgaczqvv.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtquvwtsel.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gtobpmobjd.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gthejzqsek.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtqgqobibt.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtdjdlnxbg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtdmgelmua.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtmtydgyao.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtcvbduuwe.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtjaizlkvx.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gtaapiqmpt.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtjguwqvoo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtjpjrwmue.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtafmfsjst.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtczpcvmaz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfwchfixa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtpxaxfumj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtktlyuhgm.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtnbymewiu.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtkykhdils.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtlcgmifte.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gthgpwvptd.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtnflanvzz.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtsjfnhkfd.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtiqiqblbr.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gthhyfzcbx.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gthosliyrb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gttabowief.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtqyxdnibk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtsxlnxsmi.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtuxtshfkh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyltrlvi.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtgtcqcyof.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsznxwefo.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudjevdco.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtxwopcgpf.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtjodxgsgr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gtidmvoewv.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gtcqvrcmsu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gtwvvnhxjn.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtruxcoggc.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebcrzlac.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gttebitrqb.html

val m = mapOf("a" to 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwauzzmra.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gtlvxwcazs.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtfydfyetk.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gtmmdqijel.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtwewwfqoh.html

[T16] Swift：Hello World
来源：http://dali.fzhhl.top/Article/details/gtheqpoqmy.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtwemhrizp.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtoxbflwlq.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtzasryeax.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtjxdbnggj.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtazspgonc.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gtvrjbjqma.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtypcemuvu.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gtjwjizmjt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtfrvjwohx.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gtnrepofpw.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtaffhsmqo.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gttzyisxuj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gthgjiuqqv.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtchibprnm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtqrmeraim.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtiuxdhsom.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtpmcnwmba.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtryhxxllv.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtfwfmglmz.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gtrparhdpc.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtavudegqz.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gtssxcatdc.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gttjtrvtju.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtfhflexmu.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtauuvtfhb.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtjbyrtzjo.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvborrsw.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gtwmbxxldx.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gtcnmrcrsv.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtuikjohib.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtvviijkbm.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gtyasgoqnl.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gthrbovkoe.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtonduvtib.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pengpengdd.cyou/Article/details/gtdluymfjg.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gteyzhzpri.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtfcvzuymg.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gtbflizdbr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtvrdjitsf.html

[T36] Lua：函数
来源：http://dali.aibaodan.cn/Article/details/gtujplzwfn.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gtibwldnhe.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtgvjvecdj.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtgvagvgpf.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gtawjxupox.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gtzkzjtbaz.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtrptvhwju.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtyiomvbkq.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjbrbrxg.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtwqxlipbu.html


<!-- 参考信息 -->