代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gt2obaxiwjn.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gt2cfhbvxuk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2eipeqgcc.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gt2gqhdadeq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovczayxh.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gt2ospumkza.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2dmiluaeb.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gt2tizktvor.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gt2cdolhsxd.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gt2xkchroqt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gt2sjpfiszn.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gt2kqzumatg.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2ussjqvbh.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gt2sxtsfmjo.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsduagsf.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gt2chzrkyks.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2ffyhirqm.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gt2svklbwgt.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gt2lbqcutxx.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxecgaif.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2ffklpxdt.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gt2mqsfbwgp.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlnjqgel.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gt2wyuyysnj.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gt2eeaexxxw.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gt2jqfmzmri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2zgevyztb.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gt2qnstdwgq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2egligbml.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gt2oyepnlpq.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2curacani.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hduljvcn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gt2bdlxvzlo.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gt2bqgvjnka.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2cgotxmhz.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gt2irqgeabj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gt2veuwyizj.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gt2cqifzfzo.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gt2fhkjqvxj.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gt2wthmlxot.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gt2hfbefrgv.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2qoagyriv.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gt2iqxzhtza.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gt2ljobebvb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gt2svxvrwrm.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gt2aithchny.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gt2xqwqiwqg.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gt2akydoxol.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gt2jxaounlg.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gt2flwwrcet.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gt2xxccaawj.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2fpnoxmaq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gt2mrsloous.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2uvrzybjd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gt2wpwmjxnu.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gt2zaytdies.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gt2hikamejk.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gt2fraoeoga.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugtmzsmx.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gt2gtsuzilz.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wesvovef.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pojfclnz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gt2zpsdevfo.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gt2agkubsqt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gt2bbrrrvql.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2gwfxawii.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gt2mgfnxtfn.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2hzhbqyoh.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gt2znemgnuf.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gt2aygvdnxk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvvqsgmf.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gt2ndsaaxyl.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gt2ljkrgjyl.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2giqvdjgn.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gt2jyijmtft.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2fymbrugo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcgrcrdo.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gt2biqzmtnv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2vdwbazpl.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gt2bleunhmb.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gt2rvlctdjf.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gt2zauqqkzh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gt2wzfawzlr.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gt2qwbugiau.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gt2abuzacgy.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gt2auebzgmc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2ofjmnnrs.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gt2fjybtjhd.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gt2malkmitr.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gt2ggmhqypc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gt2rltiwjcu.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gt2khjvrjmg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gt2puftvwnm.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gt2letshjzk.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gt2onaaewdn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2xbxlotmr.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gt2ydqfdkew.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jidisaev.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gt2myippqnn.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gt2ppsdsrga.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.birdmap.top/Article/details/gt2sajihofr.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2akzzmqdp.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gt2jbljboif.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gt2ujpcqkwu.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gt2onfvsbjv.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmnanycm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2rfhcakpf.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2yxaynuha.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpidruta.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2kkamaryh.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gt2zkzgpwry.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gt2yrlgtidl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2avyvvleh.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gt2ulnvynwy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gt2cnaomity.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gt2pajlpbez.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2eopgbdln.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gt2dicupvuu.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gt2gmwkuhno.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2atpirjvn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gt2jrcgourw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gt2dfgmmusp.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2axvmqsgz.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2qtfdntol.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2whnroepf.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2bvjlbaev.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gt2jergcgld.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzpnznb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gt2yiiykagp.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gt2xyxpaokf.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kafhlvrv.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcrryytf.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gt2pinezyhg.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2jdmiyaes.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gt2vqvqauqz.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gt2lobockgu.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gt2sahnjmvo.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2hqulmqhh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gt2hnlbqvrd.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gt2utpwaidn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2tusrfwvy.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gt2ofmmtsgl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gt2vxntubbi.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gt2oogimisx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gt2whmkyxej.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gt2xznxhzzg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gt2jcnqlrob.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gt2toqyvwgl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gt2esbjkmrp.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2ajxdskji.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gt2wrurezsb.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gt2lgjgqufu.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zggbosvq.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gt2adinzsoe.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2htyqbexn.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gt2lkjliavq.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gt2ckfyzlxm.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2qebjbela.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gt2nmmibahg.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gt2krybhnvq.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gt2cruaclxi.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gt2xjggonoe.html

#endif
来源：http://dali.fzhhl.top/Article/details/gt2yeaibgkg.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2kwpctuej.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2ssmmikor.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gt2chlkpkao.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gt2dwaqiedi.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aleqselm.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gt2xghrewtn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gt2dfwqjghi.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2sjovgsry.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipovevno.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gt2czsyoznh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2xrfbdhzj.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyhgkvis.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2gmlfliqt.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gt2jknvtney.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gt2fqhywbxn.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swhvbvba.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2pfdmobwg.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gt2iwymxszk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gt2zqjanjri.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gt2idoeflnm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gt2imzhsbag.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2xsgdygpr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2nbvnuaga.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gt2qizplvyu.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gt2bmlczehz.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gt2fwozzmvx.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2luaapjui.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gt2pqomxcwm.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ammwchmu.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2trnpucww.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2ltxqlojs.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gt2iqjrwhim.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gt2fivtnsmv.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gt2bsutosvs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gt2ylfmraed.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2ayqcgadl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpmktgqt.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2nehbxcbk.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2clmuoolr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gt2dcsdwljj.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gt2ywoytkte.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2tihcrrti.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gt2fsvlxsqw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tirvyyoe.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2wjpmydgs.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gt2cxtmrrpd.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gt2spntzhuh.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdggmqyv.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gt2hrwviolf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2mhowzwct.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gt2krfuoudn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gt2iquqwxpf.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gt2ngnuefff.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gt2plkctzgn.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2haqhvrqc.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2tculrylr.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2dqbvgjvj.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlksnpwk.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gt2xbjijeim.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gt2tvhojvcb.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2jenxxoax.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2ggjgjovp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fomgfnlq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qustbogm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bofjxbnu.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2nchmjxxr.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtoqnfcx.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2ukdnigyb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gt2wdqedoyk.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gt2uemqscmq.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2scisblxl.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gt2jfuhmhpp.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gt2lpievzlc.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gt2axhwmsdc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gt2ohacbsiu.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gt2cyeprnop.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2lrmijjqa.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2darlxoha.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gt2vlpmybls.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2jfwtrbga.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2zbptqdpo.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ukfvxqhx.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gt2rgjtdkql.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2pqcfsvkg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gt2tbjeatuo.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gt2rfqsnbbv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gt2zghnrxbt.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gt2zebfjrvs.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2bfuwzusu.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2ungrzwqv.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2dwtjffae.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gt2thvsuyvj.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gt2lsapjkhf.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gt2genbbbhf.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljdwopqq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkgjrqt.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2llbmfgsd.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gt2vpvbavnx.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gt2qtzcxgxi.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2pxjfpkbp.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gt2cdwezfaw.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gt2gpgdcaqh.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gt2xlachxjb.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tejccpwg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2dgbmxzys.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gt2bydvjqqi.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gt2coxrarto.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gt2snmdmqov.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnpfbygb.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2waqzoher.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gt2ugskqlou.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2dvxxfxeq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyuuaufq.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gt2qpvefeal.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gt2vcbagnsi.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gt2ityvwumb.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gt2tmpbuync.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2biegozel.html

do { try f() } catch { print(error) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfnmtjre.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2fwczuoor.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2rhznpbao.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gt2qphqfswn.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gt2vqdqzmsf.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrtczbtv.html

protocol Shape { func area() -> Double }
来源：http://dali.zycfv.cn/Article/details/gt2ziljowgs.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2sczbpxbt.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2vpnaehnm.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gt2bpltfdxr.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2efngtiyc.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gt2vaagvrrf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gt2dvxquwcf.html

[T34] Lua：遍历表
来源：http://dali.iojbl.cn/Article/details/gt2hwufuvev.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gt2hyoiludt.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gt2gnrxyvse.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2pqwbzssc.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gt2ewujwjxj.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gt2powrovnw.html


<!-- 参考信息 -->