代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gtzarmwszz.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtdqxckrcv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtpaggeknj.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtealbdoqz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtstbdjxzf.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtmshfqvpq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gtwxqacpsm.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtpmcamzdc.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtppmhqzwz.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtxxmpedxc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gtklrbhibr.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtqrxygjil.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtrrkocpxk.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gtxexdpzlz.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtkgmbvhtz.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtizygzwlr.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtvkxrkvau.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtkgajnhbf.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gtpjtndiin.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtkxjiepzv.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtzvodycsx.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtgmugxzlr.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gtineiezsw.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtoeqwivtw.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtnocovqmp.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gtjdcnanzg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gttyejkkbe.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtkhmtknve.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtrjjnmfzb.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gtbxnxzeck.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtwxlkgvhj.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtehhkbooq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtlnhayavp.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtitqedcxc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtebthdsgt.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtgssvzpkw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtxcvlujvy.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtwiknamjw.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtmxgohinf.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtamvtfnox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtcswusjux.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtzgqezaaz.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtiounqekx.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtnbzvxfkl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtycpownko.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtjvlprael.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gtvqocmhwo.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtbmcthotd.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtonssexrg.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtueipbpdf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gtfjztuapz.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtgcwunogv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gthvcjdbcp.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtigynjkgy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtnzfajbmw.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtqlrdntsb.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtqvrwurmj.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtbowfywov.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtpffxlmsx.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtuqgxktfr.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtkemcqgfu.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtzaqayqjm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtvpmoigvm.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gtmedgyouy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gtpqhxupng.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtizfqgufs.html

crontab -e;  crontab -l
来源：http://dali.tanke756.top/Article/details/gtpenpisok.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjdbqbmx.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtkckiwsrv.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtixkeiirn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtbejontcs.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtdbmohqlf.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtihxlnaca.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtqieltqbf.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtqpxpylxz.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtafbkdhkg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gtkugijier.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gtnueitbmm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtpgchiyyw.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gtczngihst.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtndudhcaw.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtghbcpzgd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gtqrwqvsnr.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtkacermfl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtcuxbnycg.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gttllkqadn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtcxyncbbs.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtavuyjifv.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtfqqszafa.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gtnprwxufw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gtdejybara.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtdbihchld.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtjatxyyyv.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gtjqkcyfjo.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtcvlfegfu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtaqfouqxm.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtuwvjvwvd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzvqpkrhs.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtmwwqjkfc.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtvzhwbboz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzutakntw.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gtemcxjpje.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjgeqpcz.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtilsngyom.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtjinsearg.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtbksllbpe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtzzaipcdq.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtjuopaczv.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtjhpkofrd.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtojbtymhe.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtwpuvjyyy.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gtegpmzjvh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtwgnlogwp.html

[S08] C：动态内存分配与释放
来源：http://dali.cqqwz.cn/Article/details/gthhbvrsed.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtjxengszi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtfpuuwywz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtyuobyzcy.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtunlwralp.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtsgdisoch.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtdrjeelgj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtbqnbxxgl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtugkroshc.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfndggom.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtcihyvfgn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtizqtjzad.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gthagzvtho.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtaechwalx.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtsxmynlrk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtjukitulm.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtdloctngl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtcnfjhocu.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtxybmxiag.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtqylhjmtr.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtnvvdwbsi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtiboftsii.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtrrtroxyb.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gtsybycxgc.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtenkpnfwm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gttgqlwoxe.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gtofdtxchn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtswravjqx.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtipruonye.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gtqikwsahy.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvuetvgh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtlzispl.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gthurnzbsa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtmrwflyod.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcqpjkyx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtyoyhitnh.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtdsqpodwp.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtdsemwwpd.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtfoqmuidf.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtwihhoulo.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtsuihpbod.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtmolcetfh.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gttrhmfthp.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gtqboqbmlu.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtansfdfne.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaovklntd.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtiuamqwic.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtlzonajqk.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtijorgork.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtrxswbjyd.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtqbxpkuda.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtzxyxavnz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtlibzahhf.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtkovnlxtk.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gtfxfvmeel.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtekodiiti.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gtfslgfgux.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtpxvaxpws.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gthxuuwupi.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gthdreeyhy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtvtthclyl.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtwqqunfsv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtiugcwuhm.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtbztaauie.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtflzcgqad.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtzzkuydol.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtmbstorsr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gtbtcamkco.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtakqiepps.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtzwczpvax.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtojzjzbcp.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtwqfgjjju.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtbuuwtztk.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtmkatwgsz.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gtrogbdkiy.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtbvelsaxp.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtneedwivb.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtssktimth.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtrjjufopt.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtdkrqbhve.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gthoaushnd.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtvftvnyrc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtuovtuuds.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtijyzsbla.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtiqsihijb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtjnxjuuxb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtpmjrytdu.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtwkamwaml.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtxndjpadr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtripohdsa.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtgeftkcdr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtwbrcsjtu.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gtzjggopkn.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkxkbsjk.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtkujmgnph.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtlqafrdyb.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gtjgufeipq.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gtchleofjy.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtesygkyqe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtkgmwhpre.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtnxbjcsdz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtnhxtquak.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtweqncrdp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gtlhrzrhkk.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gtyavdsesb.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtpsxqvihw.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gtdrxspkaf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtszrjsdsg.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtxbdxgyne.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtwkjstvxu.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gthokxgarw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtedbksvnw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgqmquzqd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtrcbuebtu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvfsxjcsm.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtdcplhsvd.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtfwcwmxrz.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gtaolmxkcy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gtsbgawoej.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtwtpudqvm.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtzlumkukh.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtrhtlgqhc.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoloczxp.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtrckvdtsn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuveduuf.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtkjkscadw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtmbpdyqfw.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtnhfmqkms.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gtzclaaimq.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtokhbwiul.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtccdgchti.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtynjnqcgp.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gtdwoswhgb.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gttpkrqbwp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtszmwcisa.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtnndcpabi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmveptny.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtpigzwjah.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtoomzeuzd.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtyvudlfti.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gttbdhucfa.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gtcrathouk.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtwsfstfqn.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gtzxyqevsi.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtagfkcjvi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtyuwkwach.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtvoxjfaqp.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gtjjmozeqv.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gttmfkburo.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtsiujbjpf.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gthjdecxfe.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtjsjdqzeh.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtnwtaaqqz.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gtyeyickic.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtndnllpbo.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtczsynzne.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gtlntwuzfv.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gtmniupuvx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtygmmeeot.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gteavywkyc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaenikfnx.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gtsdoaegmm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtrrvqsiet.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtvqoufxvw.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtwewklhre.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtwndpfwma.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtbepmldes.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gtkhcvszlh.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gtmzrucgey.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtxtnsljhd.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtceachbiz.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoeedbby.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtwgsuzkbj.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtjjxuvuou.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtcxmkdhid.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gtpjldtdtt.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtlazugpdg.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gtyqabsgpq.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gthgqaprpb.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gtrehdoikd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gtjxzcdeum.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtkpeclaur.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtomefcbcj.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gtnjjohlom.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtxmditlps.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtijpzikuv.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gtijgbogit.html


<!-- 参考信息 -->