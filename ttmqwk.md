代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gt2fefaapgk.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gt2ctetgbgr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2eijwxqhl.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gt2qusdkomb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gt2qjpwlsyo.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gt2pbxkelsm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gt2isyllhre.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2lnklvekb.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ydxrkqrg.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gt2ndghnvhh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gt2knzsbtiw.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2nszuzoua.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2xaqiqaly.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxcochia.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gt2iiqflxli.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gt2ogplxqom.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2jtseohpv.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gt2coqjaxgo.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2ihwmsnah.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gt2eckgbafq.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gt2pkdlzymv.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjmxtqix.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gt2xyiitknj.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gt2dbuaaoow.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gt2hejpysgb.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgqyykws.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gt2eieewpkl.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gt2coxmdvoc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2nvywjnds.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gt2rejewtwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2ecctjirf.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gt2nnwaxaad.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2uvzegkoj.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gt2kqbcokxn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2wxaiwclq.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gt2yxgeagwx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gt2urbzkuud.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gt2dmbzmyai.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2twdqbgqe.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gt2rsbuxabt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkthsidr.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2hyvtphbz.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smzbezik.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gt2pnjuicru.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gt2aqyjnzxi.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gt2sjumupzw.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gt2calakhyt.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gt2pmwjthhb.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gt2dfbkrxaf.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gt2oxvfpfnh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gt2slyeuduj.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2ewowfsze.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gt2jcasxtee.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byhongxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2koxcylqr.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2rstobtyl.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gt2rwinpadl.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gt2ueprjpkk.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2kfzjzjxn.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gt2bjnjeaph.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gt2iathxntx.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gt2mrclrttl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gt2cupuccgt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ruacqlze.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gt2qrkskhjz.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gt2jkqidlcf.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gt2fvwliovu.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gt2movbddvs.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2vkdfxctu.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gt2cuykcukg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2ccfjrfze.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gt2azhgpbll.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gt2drgzhsia.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gt2kanlxjll.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gt2vtezzasq.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2fkzgfcwp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2ktdobzkl.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gt2xhsbovzp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfafrfsp.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gt2qflxtuun.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gt2uygqvtha.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gt2dhljlyvz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2zhbeohto.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyvvwjxf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gt2jhzhbrpe.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gt2jvpxxklr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gt2kmlpoies.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2olqomgxi.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wutuywqc.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gt2dfbbdzed.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gt2gidixlab.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gt2nvmmoxuu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgpebkun.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gt2cjtzsuuw.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gt2lcoqahgg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2btdywzin.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gt2wwutkkjj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2kfggdgcv.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gt2ehyxbelb.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbnydanb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2szayicrf.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2nyibtdyz.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2ukynxvjl.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gt2yonswqud.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gt2byenfhgo.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gt2dfbuvcrw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2hxuzqquv.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gt2vsbnxruc.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2dqdmtirq.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuezzoxs.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gt2lwmeoxnb.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gt2xgplwknf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gt2kbimkgzp.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2oyxthgro.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gt2pnwfkqaq.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgywopsp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gt2gssvnawu.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gt2xohwqemy.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nznlfikq.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdbeixkw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gt2zzomfyez.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2chotdmkv.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2xzgoqgqe.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2fmsbsmby.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvmoounf.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gt2ucuxqkkn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gt2zikdkmyi.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gt2vbjanfsb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2rtjpkwsp.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmzkejdh.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gt2wizfslup.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gt2hjtumsbs.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gt2caxlhack.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2wdixeahw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gt2khuuvwfd.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgplbxsp.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljryjbsm.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2aaxnoplr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2qbepxavb.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gt2cvubryin.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2aoatltxm.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2lpkaspde.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gt2xyzlcwmj.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gt2rdmbtwfm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivzoctgx.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gt2ggsswssd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gt2kmxsfzmh.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2ssmibpoi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2loxtawvt.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2apjvyyoj.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gt2hhmarkza.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gt2wrgrobfz.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gt2eieepezo.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gt2vmzirbex.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2ldfbquhk.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gt2tlqencfa.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gt2wmnpormy.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gt2zjqhjnno.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gt2clwrttiq.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avlatteu.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gt2sdpfpewm.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozpdbcnv.html

#endif
来源：http://dali.cheryme.top/Article/details/gt2pbasnura.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gt2busehqks.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gt2rbikqvyb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gt2vigkptzn.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gt2rteqtxag.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gt2wbdqiqoo.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gt2xdwmakiu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2cwutpbny.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gt2adabuzgv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gt2eaqsusoy.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrldlmyy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2cxomngtg.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2dirtlezh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2cjeteqly.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gt2xolklzgi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gt2lomsostl.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2fcxbjdzp.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2elpdfozs.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gt2dvjpggsm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzhevtd.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgpufmtw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2vmxklprt.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2kufruesp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gt2ayehmtly.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gt2tnaodpoy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gt2inaaengl.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gt2owaahpyz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2zfixabey.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gt2btwhqlvf.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gt2jkggeraa.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gt2ynaoxxtj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2isghgrbv.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gt2jnrjggfq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gt2tnkljjgb.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gt2eorrvogr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gt2viixjpos.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2gmdhwlhk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gt2lakbprfw.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2lqlayknx.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gt2leeiapqm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gt2ilwkosem.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gt2wuijyyee.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2yqomomcd.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gt2iuqjbzem.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2euzpbmgd.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gt2tpucxlnd.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gt2wfvpznib.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2rxpsvnac.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gt2vnfmhaie.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gt2aodtkymf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gt2sutwxlmj.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2dabfpgcp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2rlwjwudz.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gt2cunjgepf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gt2guwqrbyq.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gt2wdzkjlkl.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2dsqobkas.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2imlfsaoj.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gt2ogvglpcj.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gt2vqpxaegf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gt2zkgawswa.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gt2nomvghop.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2ciochnkl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xhjysdtp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gt2vtyhvcuv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ucvtikix.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2dubtkrrv.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftpoqvtz.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gt2whcaxxjk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2msgcybja.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2kkysejbw.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihmxuxsq.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gt2lnxlzeau.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gt2ffvkdxqk.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gt2wdmdjiko.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjaqmstm.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gt2hhtqbocb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gt2rcqvlbjc.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gt2lrkpiowa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yylxylxk.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gt2oizeiaho.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2xrjiywmp.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gt2seqmfzim.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubwhadzb.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2ypoxhvcz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gt2uurxgirz.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gt2bgcbjikm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gt2dgydssxc.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gt2sonpucgc.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2zfqoshzv.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2nobtmkos.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2axnthpiw.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkzhejmg.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2eskosrqg.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gt2dormxmht.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gt2ehguvowl.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2msbqtcps.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2jfpbesjz.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gt2endzkmxp.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2batmysbn.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2pcwxcncu.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gt2icyzdhuv.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gt2zaaxbjqq.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhztlbyc.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gt2etusckld.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gt2csqityid.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfeweotj.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gt2bjgeaesw.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gt2qwcyazte.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gt2mxigefbm.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvyuyzfs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2hbqgprye.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2pzkexqzu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2axziuwvw.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gt2gtdyljzd.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gt2kufgjllu.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gt2lvnmbntp.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2tjnikzlf.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2iveuptyz.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gt2kaehnclp.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gt2abdbtkwb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kosnrkjm.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ledfyefv.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gt2mpiqeryy.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gt2yykrywvh.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgmexbvi.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2xwbhyxbi.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsqcggug.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlcsbswo.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gt2tzerzbml.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gt2xjrtaboh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gt2wmavxvjp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkybynp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gt2dicmuiif.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gt2vlqozdeu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2eyurrrol.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gt2porjmooq.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilhaxjpv.html


<!-- 参考信息 -->