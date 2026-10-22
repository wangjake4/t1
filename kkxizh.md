代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gt2mvcedxbw.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gt2mbjxlnan.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2mlthuxux.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2tmackxlt.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gt2nwaaogtr.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gt2jpacelum.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2mvqdwsjd.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gt2yyvwmylu.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2mjxzvkpk.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gt2yczapwec.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gt2ceqojfyl.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2lijjgdez.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tuhlwfuh.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gt2isqwzlko.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2txrexfzy.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufodpcac.html

find . -name "*.log" -type f
来源：http://dali.jinqigfzy.top/Article/details/gt2nmeqcfzc.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gt2wngduvhg.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2mdxcneca.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftppiqlc.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gt2zqupmpmk.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gt2xsljukkj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywwtzrds.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2oibuzvss.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2tnmaocsj.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2tibyyfra.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gt2gbodwzpb.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2vaxqbjxb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gt2plrvmidg.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gt2pkbgprmn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2uxwxnrdv.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gt2semdnljt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2hdhhzcfb.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gt2kpcxfqhp.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gt2ogcwnhin.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2exkzgwtd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gt2ieunypnn.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gt2wdmukgeb.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gt2keibgeff.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gt2snitwcmk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gt2ahtvnvqw.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2nkqljvit.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gt2exnojgul.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dstivlqe.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gt2hdcmeozc.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gt2pivkjcfe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gt2xficktjo.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oeiyfsby.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gt2fgiaakbk.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2qpaiomuc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gt2xwxsvbby.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gt2eppmyvdt.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gt2adfncdzm.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gt2ufevlqpx.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gt2hymulukp.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gt2zjbvnpej.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gt2ejixemhw.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gt2mnciousz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gt2coumbcem.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2fwcqrzmg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gt2jkfemrje.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2bojwtwrd.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gt2ulazegln.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntuzgtrn.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gt2xcxpgyqj.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gt2inqnshpw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2otapijec.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gt2wuyuoxqg.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gt2unnorogt.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gt2cioynxbm.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2hwxgnlrn.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2pivjbtye.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gt2psmmxawy.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gt2vmluslay.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gt2zfqfsgpv.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gt2beiyodam.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gt2rrhrpunu.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2sqolbupi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2tfjvcega.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2kmtiicpc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gt2baqrxivf.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2npthudjr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2xyinxlox.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gt2kfcetizk.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvjoppsz.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2phmlanjl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gt2smaybpeh.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gt2oniarwfx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcnljgki.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gt2mgezqzak.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gt2zrjgwnjn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2abiulupn.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gt2dvzmvpuq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2bcpbfmdc.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gt2vpxfhruf.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdzdlapv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rkmvfsch.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2serhuxos.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gt2jnnszikw.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gt2llytpxka.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gt2twtrfbpy.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gt2rdilctvo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2xcompiws.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gt2bqprvcuo.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2aymsyzft.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnpqqytb.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gt2gzkpvobd.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gt2okyppspo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gt2pvgbwpql.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gt2kczpiiee.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmuchuum.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2zbmxcaui.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gt2ubnerxip.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gt2nyxyfigr.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gt2lvmnxrpf.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmjkzccf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gt2szpijiyu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gt2oxhigbad.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2djbtawmb.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2brugzffk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2kvcqravy.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gt2eskjdbno.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2isdrokzh.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2paajqnqy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gt2kqbsuvle.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2gdrvslcn.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gt2whiohaee.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gt2iqngdcbt.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2utzoaita.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2anxrqoml.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gt2ghunymry.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2isjuxzrp.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gt2nazppwmn.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gt2luewfnyt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2tkheusus.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqqjusih.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2uedwyrlt.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gt2gxsvkypx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gt2obkbsvkt.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgecsjml.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gt2vygqqtdl.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2zyebhptp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2mjzybqto.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gt2xaeckxrp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2probnhqk.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2fwcrnrxq.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gt2scyktqnu.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gt2gmyfkkoe.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2ogdswzeg.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gt2ebcctjho.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2wbywcojo.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2btrkqruy.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrrzjmjt.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gt2eygfssuf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gt2hvdvxwhs.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gt2hlrdnyvn.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2kaxpyrij.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gt2wbnrfuue.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gt2vocwddns.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2zciwjrwq.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gt2dhwafxgj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpcshxyn.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gt2izwbveep.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gt2weafmncr.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xniweeqd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gt2jvobwnrm.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gt2fuqfcfkc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqgpvfpo.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gt2gfnvhqei.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2sesxrzyx.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhskilqd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2midtzevl.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gt2tjsgyhqw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2oumkarpj.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2ksfhhqix.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2hnvngnyu.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjqwfbqe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gt2mfnijkdx.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2dkcuqrcp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gt2memlkkzv.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2iltznmsv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gt2ktbefekk.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gt2rgbuwyzm.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gt2wtlssfkp.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmkjzkvz.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gt2mnittafg.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gt2eibxryvl.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gt2vidgoona.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xeuiuxiw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2chyzagzi.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gt2ejjtsdgz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gt2xvdaavwy.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gt2gjuyhrqo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gt2akxvojtr.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2plojekcq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2worlbrze.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gt2yzgndeeh.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gt2xwixhhgi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gt2gjyswwqq.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2phabinlg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2xjyeiizw.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2peqnbcwc.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gt2mnwuavpj.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gt2lyvqqwpt.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gt2ejtgdaxj.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gt2sspzkesw.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gt2ewrohxhc.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gt2oaztyltb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gt2mkdvizfl.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gt2hnrelicz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2yvdfzpcc.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2rkfanhpt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gt2ckkpavhv.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gt2jeermted.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gt2mjiabekp.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gt2ydzcceji.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gt2hhwtkbrr.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gt2gkfcczwi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gt2akzsizbr.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gt2fsdtvqqw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2zgotgnjy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2diskcqxk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gt2usjturyt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2iimnknce.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gt2kpuxmfjd.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azojfldt.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngqkxjhz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gt2rwsmlftl.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gt2nqhbflnc.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2sswariqd.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gt2ywaepbxg.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gt2ecjfwaqm.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2zbtgdvry.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2oxpljess.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2gllyzmoa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2wgrojeht.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2tktqxajk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2kyqvklwm.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gt2qbquqkix.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iecntlmj.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gt2ydeqnjhh.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gt2gwqpsghh.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2dcxomokt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gt2udlmhrra.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gt2mzacuuox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gt2ljqrurwl.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gt2rfskvkby.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2pultrkri.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2zhqgipsm.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jpjzvrkg.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzhacctc.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ninzdjef.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gt2gvximgix.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gt2xjlajfjl.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2jjdorquf.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2bwmiokig.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gt2tctezmxm.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozdmsngs.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2kuawcjap.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2ijsiaywa.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcgxsjwq.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gt2dsomnpji.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2joywjsqi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gt2mxtcltxo.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gt2hfejwzlm.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gt2qlsyuyxe.html

[T22] Swift：字典
来源：http://dali.9152youxi.cn/Article/details/gt2atqkhkqd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhupeml.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2hosykgvu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2ndpzzylh.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gt2bwgomsxv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2zcjykaux.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gt2wmlobmhe.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gt2vhdnbsmm.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gt2yajxvqgd.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gt2gbkwaxyp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hndngqaz.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gt2peqqzeqy.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gt2emplujet.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gt2zxjmymgf.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gt2yupshbqq.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gt2yzcyxkqt.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2rimlkkgi.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gt2rfnwqowv.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgjtrtnq.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2rabevayv.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2afedafrd.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gt2oykisaoh.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gt2xpbymswu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gt2sjzvhuyt.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gt2ynwqrqys.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgimaitm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2poaktibp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gt2ktdpyjka.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gt2tufupybz.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gt2fnqsdxyi.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wyfukzcc.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gt2pdpyupcz.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2kzvqjvwt.html

if x > 0 then print("正") end
来源：http://dali.kuanghao11.cn/Article/details/gt2pttardzc.html


<!-- 参考信息 -->