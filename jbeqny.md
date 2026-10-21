代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtabjqwiep.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gttgsmwlfg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtmosfdtth.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtjiniixzz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gtgmnjdyfv.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gtjhuekpws.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtakupdsfl.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtfwedzqze.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtjrvjenyz.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtwdjipizq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtqqpctlac.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gttnmgvveg.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtujarpjjh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gtzubkqlkv.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtflatmrfu.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gtjpebusev.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtlcvrckcr.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gtrmjvsitp.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtadmcajvo.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtgxwuicug.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtfsjtfsmj.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gtrnelfelh.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gtcnugxxuy.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbyyacgs.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtquuoutda.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtbdyghvvn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtcdrlsuxf.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtgwbjaqxr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtmfdssqyo.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtzbhyomdk.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtxjjvsenb.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtwjfxenig.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtuhztkrjt.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtxycvonfj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtdthczzdn.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gtomqqakxh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtahhpvjvj.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtdcpcaqic.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtwydizwof.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtoytemvoj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtymcmabxj.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gtqdyibajh.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtzbzgiily.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtudptmxnr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtaeqtikch.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtrzjkemoy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtechwjbiz.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxhnwcfl.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtqueyaqjw.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gtqwzdalpt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtmauyutey.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtyzxyffjn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjprtonv.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtillhodlf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtilecqslx.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtzlyixzrz.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtqcaphurf.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnhrndsof.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtgxeagcqf.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gthmudmdqx.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtwodsmuxf.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtwuwejtdr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlqwmnli.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtsdwallxl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtwuwggyrw.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtzhulpbrq.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuuthdvb.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gterivvldr.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtxheokqzc.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gtmwlaslst.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyfurkpp.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtsjpjwqlb.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gtskcxmlph.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtpxjgmsow.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtsfxqqciu.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtyutkerpd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtxzfpjubf.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtpvorzywi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtobuheqtu.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gtyipjgodt.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbjtpgvy.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gttdckfhzm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtmerukwie.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtwnaxsndj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.mhx1999.top/Article/details/gtawzbkqkh.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtaukwzgns.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtnhpelwdz.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtzkibjhty.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gtvmrvckdb.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtxvyddkiz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtessyzzne.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtdchnlxip.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gthywwqsdq.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtihgxuzab.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtlpwjpsqm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtipthjdlc.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gttfnvtgzv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsxdrrvrh.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtphnhtsab.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtcvxtnemm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtxnriieao.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gtedudlzdz.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtgsxvfipk.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gttdxdnuwr.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtxehybziu.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtohkpoggl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtqnflehsm.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtwedvyxaw.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gttqxpqbeb.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtthvmqbxa.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gteiorkaiu.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtkjfoqbel.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gtbwpxnwen.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtknvrruew.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtqdsjfhan.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtfeoxkvtr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtnquitbqr.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gthmcadqxq.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gtidozfcot.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtfpfcmqpr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtvrpykany.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmbrcxgi.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtxaduadyb.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtiwbctweb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtirvbnvnw.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gtwrplmhvz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gthuxjzgiy.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtyeylrwua.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtjhfjjxor.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtgqjxhekr.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gteqjcxuvu.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtgvipafpb.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gtvmzziqxh.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtvazghixc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtxixyylml.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gtarqjmsif.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtoynubpsf.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtyznxjoce.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtfvoaklxh.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gthisixwpr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtusltyipq.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtiyhlobcn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gthmnvzced.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtvzijbkdu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gtcqlhapes.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtmxsfqvjt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtnwptfinp.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gtnnmbkgpw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jiagoushi.top/Article/details/gthezlneaz.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtouxhobox.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqpzmtvi.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gteimjkgph.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtrqucdxkk.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gteyqbrbwd.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtggcpckze.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gttjjqefvu.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtalqdbirs.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtrhajmyvy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtbbdumdrw.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtjkmknqld.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtddzdgrqo.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gtayqknwmk.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gtyyheupbq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtqsidugik.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtadpuyvuc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtrbainzum.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtncvqqlcy.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtfatvymsu.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gtdcbrdukj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtjtndfpus.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbfuhsir.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtmzkqjeny.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtdmvnknpq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtwwzjkgfa.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gttdpadsax.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtoqadvlnq.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtzpickwzl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtdgcyxfrv.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtjujxgrwn.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtqjuoqckn.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gtrqdakgwj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtfdpvvmhh.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtoiheempc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gtfsplhdwn.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxwwsxqlp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigufen.top/Article/details/gtvovkguij.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtuguftjyu.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtruvhykzs.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtnkutdkwb.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gthibuyrnj.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtdoupcrxd.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtdufnvysm.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtbkfrfase.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gtelownxen.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtcgapfbfm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtozjuupwy.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gtjlxoumxv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gthakexorf.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtfmxfbbuv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtjcwetlzf.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjatlxilx.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtdpqkqohy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtuvzqpqtw.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtwxttbgcr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gteycemguz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtorojjgam.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtniyzwpuj.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gttkinujqt.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtkpzgndbz.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtuxbxives.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtqkyjhuyt.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtnugdimut.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtdmwirrdy.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gthvaptgpz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtzapmiqgu.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtgeucolpe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtvfqhuexk.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtqdsivwjh.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gtqofyvtla.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtsddrowsh.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtypeafnfn.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gtslbjavji.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtckvbdebk.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtmvlgtfgl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtbemmjeau.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtabslyhul.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtsjlthsdc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpqzhyzli.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtwbfjrpet.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtgxwpnnpo.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtgesvuqbp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtgoupljpc.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtseykkrjt.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtdqdjkkgt.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtdxonguvi.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gthopdybfe.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtkffishmm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gtzlvknjut.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtyyvqpzxk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gtqhkzkahc.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtbztmgayy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gtecqvgepg.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtqmvwqxpo.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtboeuggek.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmlscjkr.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gtzdbkdhoa.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtbejwypbh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtducsjfmb.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtyagdgchk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtilnxagka.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtyhbdqwgv.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtsmatsaqx.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtybymrydn.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtykfbkkep.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtnrlfmxvc.html

for (i in 1..10) println(i)
来源：http://dali.yj20258.top/Article/details/gtzjuluvvy.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtqhsahwyy.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtsnoilfhr.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gttqtiurlx.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtbslqnnhv.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtogsbffwa.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtkpgirbqf.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtaedhieef.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gtwnkjtisr.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtjuknhysy.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtipmxnfcg.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtbtnmfeja.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtvpwnomyc.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtpjnyvcwz.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gtydqeibey.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtqijbahsy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtknynflrs.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gtnckbtkkj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtlhdptlhz.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtlytafxca.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtdbezheia.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtcoyavdtl.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqilosdal.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtlldxyxii.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gthouifviu.html

[T27] Swift：错误处理
来源：http://dali.bjfxy.top/Article/details/gtgvnqrnld.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gtnzvzlrsg.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gtrcjdhdsj.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtlbdahpyx.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtlyixqtmx.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtfxmogzfs.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtfwnrvkvq.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtpkagnhll.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtdzhvwihz.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtdsfruacw.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gtomatqxss.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gtdvybtufx.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtydmtgdkc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gtkcznjyxo.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtuiwxkfqr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtgappwqvw.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtzhzyjkgk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtfusqgcnb.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtjhhrjlpg.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gtmuvqxlqo.html


<!-- 参考信息 -->