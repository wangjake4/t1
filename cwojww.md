代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gt2zrzlotic.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrnjqmad.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2lqxovnpi.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gt2rsixpisc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gt2xrmafskw.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gt2tpbyfncg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gt2wngoress.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2qqhocofd.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gt2xrolqrdu.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gt2ehutjyfk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gt2beqriazz.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2jlxfslqt.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2nwawkfwq.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gt2gmythejx.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gt2bnjjquzn.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2mglczznq.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2cibxgupx.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gt2jymcevim.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2oehylsyo.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gt2vevsktbu.html

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gt2sezxdtzv.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gt2chuikwzn.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gt2ldvvwemo.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gt2slkvlosk.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gt2lidffzrf.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gt2uozgccng.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gt2wxwoeytt.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2jteyllft.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2fdtkcfmb.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gt2fbfjvhlr.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2tjkporat.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gt2zztynbiw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gt2whnsqkby.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gt2fateefwg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gt2gjpcwvio.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gt2dmixyfaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gt2iagrplet.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gt2ogigytbv.html

wc -l a.txt
来源：http://dali.xuanzx.com/Article/details/gt2gqydpshc.html

[R53] 查看文件头与实时尾
来源：http://dali.cdnleiting.top/Article/details/gt2ztxwkdtd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gt2ezuygkgc.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gt2ypsmzubl.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2eezeozbx.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjrnyclv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2qekozsxu.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2hviihrpj.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gt2dchzfebr.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gt2dmplylmf.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gt2mwcbazze.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqiffmfb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gt2hhikegwl.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2saqrcrsr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2suyjvwkd.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2hopspljt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gt2nfsvnsya.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2ybdzlzeg.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gt2zoptbvsl.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gt2xqhhvosc.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gt2qluiaoct.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gt2bovxiegs.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gt2vbfjmeng.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2ckybjogn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2jpqhmcrs.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gt2qpitbrts.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gt2ydkdhvlo.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gt2bsosyyuo.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxehbxia.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihaytscg.html

openssl rand -hex 16
来源：http://dali.guannengcc.top/Article/details/gt2guxnghlf.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gt2pdtyyyqs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gt2zxxsofos.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gt2glbpsaxs.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2nvodnjgd.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gt2hryvmnbm.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2ednulhod.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2hteoaept.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gt2xcptytzt.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gt2aqyyibcc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2rxgjcora.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gt2begdgegj.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gt2efpyjbxw.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gt2wchiyilk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2nltuczru.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gt2dndinfyr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gt2sklxwlsm.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gt2tmgglqdq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2fuwrafkd.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gt2hrxqotri.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpbplgrj.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gt2lwnjjipc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gt2lxecuurx.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gt2ahdbrhfx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gt2ykppdldk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gt2fuusyfue.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gt2dyvbeiqt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2viynfayj.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gt2gdixhjsh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qzlhtvsv.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2nmiatadf.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gt2uwhzjdvg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gt2lhckcemy.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2fjtftsin.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gt2gwjsytut.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2domlrurh.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gt2svrudsvi.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gt2xqjbdvbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2pjskgtmh.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2cphzwtlk.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2mjpjasci.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2nscxpzlx.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gt2isglmbkm.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gt2dvasbclb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gt2imivvwxc.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gt2ofnnnagt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gt2wkhhfvpf.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gt2fgnfujgz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gt2hkxqabqw.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnlifnhw.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxrngmhl.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2iifiijbd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gt2eynrhbkv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2exxicaou.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gt2dherwnux.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gt2mtablafo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2hleoftqx.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gt2ldfqzpog.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gt2hojrragg.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2ocmsndvi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jyoumei.cn/Article/details/gt2xbbtamvd.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2pjokhija.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gt2sdgejepa.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gt2nkxdiyks.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gt2ygnqrskq.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2norhvgis.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gt2pkgswbfo.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2ddldsqmm.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2qfypjmky.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gt2pithybts.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2navmdeuo.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gt2fqtexdqc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gt2vpcvrulh.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gt2yuykkexw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2priuizwc.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gt2aiwbbwjw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gt2wctwfebp.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gt2jdgfcakr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gt2dcdieytg.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gt2mlpovqjx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gt2eldnrrpj.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwqewdbn.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gt2gadrawoq.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gt2szulhiif.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gt2ohpdvjre.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gt2eartkjsg.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2kehzxbbo.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2buvhemmt.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gt2daxgbmcn.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gt2evrtmktp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gt2mblwwtbv.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gt2zjpnlmal.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzlxyfmc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wcugfgpt.html

#endif
来源：http://dali.wangdashe.top/Article/details/gt2cxicdybu.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2pkiwsboq.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gt2bkhzudui.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2oeuhtnbi.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gt2jieexwxq.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gt2hdjycjys.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gt2dypixrmy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gt2tenjkiqz.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gt2pqcnekyo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gt2iyxribby.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2oiuglyhx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2ftbwxzxj.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gt2icafatar.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2jeeijftk.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2qmffnxtt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gt2ftrhtjjk.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2witmacji.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysmvtzfp.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2wsjmdher.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2bbrelqto.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gt2filaduwa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2jdnkrztn.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmbtonyn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gt2bdponvot.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gt2cyxpnvqy.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmfqqpjq.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gt2sxsxsjax.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gt2cubqhfjk.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gt2fhnghcmb.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2tlijcwkd.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gt2jdfozazk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2vjxkdldk.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gt2zyddlyzw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gt2udfbzexb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtjgqmb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2gcccdwuj.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2lwwawwsc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gt2wsnwmctx.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2zrinsvdj.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gt2zcgvywwe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gt2oqzjypjf.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gt2eyuyfymd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2ssjebiwq.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gt2rerbpiwz.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gt2nmwhwtqa.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2jsleyjvu.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gt2oxshfswg.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gt2mduezjti.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gt2vkjfeqaq.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gt2msieuceg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gt2sjleqfhv.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gt2vrpdjoxa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gt2vmyraeve.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2cqqodlex.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gt2nbxeqcqr.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gt2dizsftwx.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gt2yemqvget.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gt2mwzmiqyl.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gt2yclmaxxt.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gt2ypnuolbw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gt2lqygkrle.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxhvmzxh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2ppfhonuk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2etwefcxu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2ucobgoag.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2omysodpc.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2wacvvnxx.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gt2hufdswsu.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfjzease.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gt2fpvrbdtj.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gt2bdkrvudo.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2bpomnwvf.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gt2ireymxzo.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gt2mwymokee.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2yqalradx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gt2rbazyflz.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2pyqiadvm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2ldwwbcny.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbchqiwd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2qfqmrbfh.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gt2rmlglfvk.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2saanrtqd.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gt2bnzzmegh.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gt2nscplkyj.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gt2nwwcxvim.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gt2wniwtdiq.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gt2eyjowhmv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gt2qnrtyijf.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gt2qrdmjdoa.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ibxtebpb.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gt2fmcixnoa.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tgiroxsj.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gt2oxlokiuh.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcplmywn.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gt2yemcxzng.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gt2wjtjejxv.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2hnlhwtus.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2fqlxltbu.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2vgdcfhpb.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gt2tacexojs.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2zkzzmdft.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2zeloxjfd.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2eunfnhgl.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jukzarwj.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2oorgjidk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssgijjpv.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnahgtui.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gt2vauxwckd.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gt2uhsnshoz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gt2rufeljib.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2fggszzql.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvqgsfcm.html

[T24] Swift：闭包
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayllqutn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2knkrgglk.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gt2kbrrnvgf.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gt2jonvkiuq.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gt2qmqmezmo.html

class A: Base { override func f() {} }
来源：http://dali.cucudq.cn/Article/details/gt2jcmntbfy.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2lhzimbst.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gt2xnvrwmjl.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gt2saqktiyz.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gt2zpamszua.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gt2ttbythmm.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2eddlhqsf.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gt2uwmmslsn.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gt2fmqakbty.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2eusmwovm.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2kquuslyw.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gt2odrnuydi.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gt2sinatzaw.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gt2vsuwxfnw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gt2kgatdyci.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gt2ugmaaddy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gt2ihkqifvl.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gt2ueqeyzxc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehvckqgh.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2nxaajecw.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gt2ibmrfbyj.html


<!-- 参考信息 -->