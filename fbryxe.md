代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtatjibgjn.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtolluccwx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtkwftrrnf.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gtulwptuhz.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gtvrdylrwn.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gthcdxwkrl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gttvlhgfyg.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gteqmsdwir.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtdqlzbxup.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtbsfltdhs.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gtyshpnkwu.html

[R41] 丢弃输出
来源：http://dali.hnqzz.top/Article/details/gtxjhunhie.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gteshyjbzz.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtxjlaectr.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtcwjuxili.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtcqcczkph.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gtpeqbooxe.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtvcdirwto.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtslabhmvn.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtzzmxsser.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtxsshjwut.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvlesscw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwnwjdgk.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrispzbb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gthijzognb.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtewjdzeur.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtzzjbhdlo.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtjuyhgvyz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gtzdxyliaq.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtdncoktfm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtflelvmmo.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gtpzqdytcz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gtiouefgaj.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gtzlpjpggv.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtloxibswv.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gtttqnnxsu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gtvadoxtht.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gthuiczktk.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gthcjuleae.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtcrgavmoh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtsolzsfwg.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtmvmqrfzp.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtmuvswwbx.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtrbqpsciw.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gtsxwxwhcz.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gtxdrntgvj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtgjpazvns.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtzesjdbrt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtuwauqsst.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gttlhiofcq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gthhtzdssd.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gtoriekiux.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwthinzl.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtvanzizas.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gttwgsbvxk.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gtxbafvbix.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtkomnfytl.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtgioxczbs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtgyswetmd.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gtxnftoied.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gtsjufrhtr.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtiawxamey.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gtwxqgrcxr.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtcprrcxop.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtthhfpinq.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtmflanhey.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gtfugxhwez.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtjfsnkqyz.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtzjngmxws.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtfpikxeoa.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtaaxrompr.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtgmhdwbfl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtdwkjcsew.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtojzhowpa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtlwupmfbl.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbzneiqm.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtrkpauhwa.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbpppnbo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtxzsvyheu.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtwrwbfamd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtolzpcmlb.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtyobkkzox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtrnndwhzz.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtlyqzfnip.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtwhwlxabc.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtrqvejzdk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gthsvkutdo.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtrstgkuhg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtwedbtuxe.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtwbxbctys.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtfleanjiy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtacgrnhnp.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gthbzlguik.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtinlrtytq.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeyyieqa.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gtpdjxhhbe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtpblhawnu.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtctjwqwnh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbtnsvgw.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtpngxtnef.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtrdpieqym.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gteaicsbtq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtscyorzdz.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gthritctav.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gtthuuakca.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtmrjwxcfh.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuqeeasf.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtskctdjmw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtyjhlxaeh.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtefebtslh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtofqkuful.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtackkolyl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtgbfivbgg.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtwnzydnvt.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtqdwdtujj.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtzdasdfip.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtbeoohofh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gtilxniqel.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtvcqxkddu.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtasdywctx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtaylouydz.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtjcyavejn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtfxxqeizt.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtpidvlzkz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtaxfhmdkq.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtzrchykvl.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtfjjjgrmr.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtvctsjecg.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gtrqnmkmwv.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gteahpmomk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtdpypdopa.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvvkszvr.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtryvnuevq.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtljxeexdy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtyrtfwosw.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixlnmfld.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtyewhefbm.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gthdeeuesu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtkceerjoe.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtnwufcrjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtvyvbwatn.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtyjzrwvkf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gtqdwhhjsy.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtnyjvxral.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtahxczaew.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtglkbensj.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtxjgofyhb.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtfjlbkxjb.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtotknxuwc.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtkqmghyhh.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtbycycevz.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gtezuvcoiz.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gtlufaixpx.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtdglpnowb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtvwbapjuc.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtrfcnbexo.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtmkgpnfei.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gtrxidnycu.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtkhmzctdi.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gtblqncjgj.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwarvalv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlrztmupl.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtzhyvgyjb.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtrpknoshs.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtfunnxtgv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gtvxbuufdg.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gtpmvdxtjd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtpjbswqjt.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtxyhesozs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtegjfitel.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtgsrjqtvv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtwqfkrstb.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtzjefmnuv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtxjvpjbxa.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtuxkgelsu.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtrdxxpbjk.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtrfkztmrq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gturxbwacr.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtgxqprfsb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtnnjzmfyr.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtuziuieih.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtcrwamigc.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtmdgqkpqt.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtbeoxcixf.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtbuowjlxy.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtcksgxkea.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtgjcsjdyw.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtinfngdpd.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtyxqignyn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtvulaspmj.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtabsrstqe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdnesdubo.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtdumjjcse.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtyvabhqts.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuhocbhsm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gtblhjfphn.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gteoomtlbo.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtcnazskum.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxboflyz.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtubyhncdq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtypkaaklk.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtfjvskfqu.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtnawlorum.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnndpeyu.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtfclwfpkj.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gtnnkkglkt.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gtzobwwzdq.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtjpyianfh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtlmfjjbws.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtixebzpzu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtdcmegipb.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtuikucbcn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtfuelgzst.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtbtnopixc.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gtpfuoxigx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtrbujtyus.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gtlbftocqs.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtakbeamuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtzvakfixx.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gtzqrlvrqd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtedfcdpyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwtvzeqjw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtncwcdlog.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqypoghu.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtdwcckabo.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtwvvndhhq.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtdtxxvvna.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gthbmlnzdp.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtdrpvmhop.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtxfqzdlmw.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtzhmnyenu.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihlwcbow.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtxbdanrwh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqkxlyiv.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtecwatkbx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gtuzosmbmf.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtmzswegsw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtuqobakcf.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtarfjfvar.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtnnwnjruw.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gtnjkpgtsj.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gthqsxscfr.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtifrzfkxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gtawooblna.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtuhqfiqbk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gtbjlhclnq.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gtahkikabv.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtzkspheto.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gthaalvvht.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gtbgmseqif.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtcxtlxqzu.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtelvhzmuf.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gttlbmzfuz.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtcwybmjgr.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfslsrdtu.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtuwnbtvaw.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gttilgtmac.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gthswpyxvb.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gttibixrig.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gttdzprcvk.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gtaflswwif.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gtxkfaihca.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtnjgrdgst.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprjtmbao.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtmoduqvyn.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtnvcxsikk.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gtjpymputa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtiuksbvhg.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtwwegznkf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtyfpcxnbk.html

[T24] Swift：闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtftosymaa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtneahffbc.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtkphtqvnt.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gtydiqmchx.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtryqjlhqy.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtfrduxmes.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gtpwpztwlc.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtjuqleswe.html

[T28] Swift：枚举
来源：http://dali.guowangkeji.top/Article/details/gtazuepzkq.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtuktiqbgz.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtuqbqwfqe.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtzsjcgrpv.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gtsrqheydp.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gtwaoplqig.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmqunxlc.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkhtqsfx.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtusjhleyd.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtvljqtayd.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtwxjslnqv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiapkxvn.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gttwijfbsn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtijxmcygy.html

[T35] Lua：字典表
来源：http://dali.chenlongwang.top/Article/details/gtutzfxljn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gteemxmwfj.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtddbzkmra.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtapjjqkcn.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlajzreu.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtmgzsefjz.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtxzsjcmfy.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gthwtjkphs.html


<!-- 参考信息 -->