代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gt2zmqyoccg.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gt2lxvadeso.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gt2miyxhrgx.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2fqjtedgn.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gt2ccszomyo.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gt2xtvfbkqb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2ohkpiyvt.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plethtsc.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gt2odkfngmh.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gt2bkqzgqsg.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gt2ofencduc.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gt2gavcxdto.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2pmsmvmkh.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2ykdsgkwu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtkvvwv.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2sentbzfk.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2wyjydsad.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gt2mxdjaixb.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gt2lnefgrca.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gt2mcjkmhmz.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gt2mwiomjnk.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gt2peqbprgn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2upwyjrzi.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2nvzzkoqc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gt2owxqhdst.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2tldnkzlz.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2lcuvhccd.html

[R49] awk 带条件
来源：http://dali.hysaishi.cn/Article/details/gt2tjyywzos.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gt2vtevbsyl.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gt2txahesff.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2kuogegxk.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnaxhacb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gt2torhrixh.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gt2lorgliux.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2borinxdy.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gt2pgqyrdmd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gt2agkailir.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gt2himgnkqa.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gt2wsymcmzn.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gt2favbmsce.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gt2jyzqipyz.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2nafdbgwt.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2ahfbfwal.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gt2wwthmspp.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gt2guepfkmo.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gt2oefzppyx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2ehmrwjcv.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2ihiorzyu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gt2mgiocpzb.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2iezaioil.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gt2hutmqkqv.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccvzqvez.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2dmfacykq.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gt2vzrkmxtk.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gt2qojrnuau.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2ayebbqbf.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gt2adwbmquk.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gt2uldtcllm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gt2nbgckmip.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gt2dkyxrpar.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gt2dixmpsyo.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2qpqzmglw.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gt2skwfcsce.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gt2xiqsjxey.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gt2mvlpqsuw.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gt2yzvgbrwv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2yzssyfvn.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gt2pnljpnvf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gt2gzdbasow.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gt2pipukctg.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gt2qdizlrzs.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2bhuiaixc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gt2kyqzakss.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gt2myskxnwb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2skvyapvp.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gt2gmqkenbg.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gt2xnqeelcq.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2ayfvuvpd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gt2rqsyfpma.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gt2vfxugeym.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gt2xoiagcdn.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2chackwcr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2nvfwdgjn.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gt2qgbmvely.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gt2wazslwqu.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2nslhyukp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gt2brbkcuqz.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gt2iyrbqcxc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gt2brbdzuqq.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gt2bpwswdxj.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gt2jnchbqll.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2awcgskvj.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2vsepauiu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2eeowxczl.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2atidflgh.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzycpomt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gt2tmcevchu.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2jgokgimr.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gt2ugnmpgaa.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gt2qdgfsyji.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gt2rxsmjjpd.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gt2cszejzjs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2uhgsooea.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpffrgmr.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gt2nzjdpxzh.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2nauzbpda.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gt2wvmrrivw.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gt2fhsvgmso.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gt2lrkcqnum.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gt2ilrmtzdg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2syhzhtgw.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gt2jqudesty.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2yzttdfsj.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gt2lespsmjh.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gt2toxhhgcm.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2zrmxlguv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gt2uudpelaj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gt2eewkujit.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2umdrqoes.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ejoewxsd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2zpgqumis.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmphvtup.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2bwzgxvao.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gt2plbwtmoe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gt2lbozjbgb.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2armcsaip.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gt2rcbkklku.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gt2odcgjsjx.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gt2shlrhlxt.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2yeltktxu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gt2ehzfgxeg.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2riumldxj.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gt2xunrxvph.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gt2yrnbhcnn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2vlraqkbe.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gt2hfhwfyrn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezfvxdii.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvkoeene.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gt2qbmjpaix.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gt2bdqdtwdc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gt2usgdymff.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gt2sihsivtt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2efrzylhm.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gt2xugrdnpr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gt2gmucxmqc.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gt2dtbextbh.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gt2ptizgmsc.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gt2gdecvotf.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gt2iazpnuus.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gt2dzzsmbqj.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2gppuzhpy.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tabatwxd.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gt2cggylixa.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gt2cxlojwab.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gt2jnydmbqr.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gt2huiemyez.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gt2egutpunt.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gt2mqlxwrzj.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2dkmlbtgz.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2fvddzdkg.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gt2hxjaxadg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gt2veozlprh.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrnvvrbd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gt2otdbwsiv.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmcqazlr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gt2lzxmbztg.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gt2ddrdzxkm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gt2uobptelb.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gt2pizmzhbu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtubyoko.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gt2swouggjg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzatyela.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gt2lrvoxtmr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gt2zjiwuxba.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gt2mufvckbf.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpearfhl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gt2oquveogb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gt2ojilmgvk.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gt2zfqmfaeg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gt2hlmcmffl.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2tegsixye.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gt2ojhcklvs.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gt2ijuuhzvr.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gt2tfegjrmm.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gt2vgowxebv.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gt2wbwfpyqm.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gt2xsppufnw.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gt2jsxfbjnz.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2lahxabef.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gt2igdpekmw.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2sljrynls.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yoaslfjd.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gt2vbhaunfu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwcizoww.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2kngenmrw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2dgsxdsta.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuwdrnuh.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2rsahhhsd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gt2ummicshq.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gt2nweedyit.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2idmzcdsx.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gt2ddzpodqo.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gt2clocmeyu.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gt2xpzaojrh.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2aztucnid.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agrokmxp.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gt2aghnwqwy.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2ammsvdap.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2vtatxkmi.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knblgtqr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gt2waejgcok.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gt2jklhailf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gt2lnoimtri.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2cevtfwjw.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2jvgkcprb.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gt2qnnqyxoz.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gt2uerkumal.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gt2llcvxcuu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gt2iraxgrtx.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2hrvrmppm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gt2hmvmcvdi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vzugdedx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gt2fveqoosf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2nziepjyf.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gt2vwrqjltu.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2wbrzdvib.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gt2kpuablzx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yshadird.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjicqrbd.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2stnkiwhj.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gt2bwmmzesy.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gt2vbjpecqq.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gt2vrfjcecu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gt2fscmwmzd.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gt2rvaadgkj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2oiphtyui.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2ciarhxcx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gt2wjhumlju.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gt2lgjwinjq.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2plgzpcnb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gt2sruqwdni.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gt2onxomfej.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gt2alibxykb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2uxufhqwz.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gt2tolzfwni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gt2tcsvrprb.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gt2cueqbaje.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2wffiwhmn.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gt2siqibgrz.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gt2pzljgtgw.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gt2sxmhexzc.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2thknunus.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gt2ummmjhnq.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gt2zitolgjt.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2euavyicn.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2kztxjhgi.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gt2hwgcpbps.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gt2hdbbgtvz.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2cydpyjlq.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gt2elukvwbk.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gt2kmipoaiv.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2rjcnhozh.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gt2itkkktmg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gt2xkemspee.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gt2ghekaann.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gt2vtdlgboe.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuohhdpx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2luibyfow.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2xsmtqeqa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gt2xnioucbv.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gt2gylocquk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2ogztwxld.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gt2lgcqdzqu.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gt2mhtmjhqf.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gt2obbqatgj.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gt2itdjfhet.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gt2njrgbgrm.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gt2kdopaovx.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2mwsukxfd.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gt2gdlxmdmk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gt2cxpuuzoc.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qikqombl.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2yxuqagzn.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gt2gnklrgfy.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2qynyuvwu.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlttzxhf.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2ekvtdmpu.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gt2lfvczdiw.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gt2fcwgxzgk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gt2hptdwtrk.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gt2bncewapx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnkdtebm.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfeyngan.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2gugitiyq.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfoaluym.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gt2cntardwx.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2ohktrpsl.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gt2bpelvtbp.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gt2laxfgnmy.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gt2gskbfklm.html


<!-- 参考信息 -->