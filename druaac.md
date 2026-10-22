代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmmeexxt.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gt2viajjrlw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gt2zefuwawt.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gt2emwrajrx.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umpbbqqj.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gt2khofewqw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gt2lftnhswf.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2guirhnht.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2zdednrdc.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gt2yqvtaucc.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gt2cvgtadrv.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gt2rtgqjlha.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdpnpskd.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gt2nooecaoc.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gt2ejoltumc.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wsbjrrdn.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gt2yrioayde.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gt2vsvcbkqx.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gt2squmrlth.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gt2akytwqdl.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gt2vghojiyb.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gt2rsqwwgap.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2byriwgze.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2okroizrj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2xujsyzmd.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gt2wlckypfo.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2ibhxgvdu.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gt2tqdpwmuh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifkgmboz.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gt2jdszbnus.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2xsbfuisp.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gt2zyfbyjem.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.snrcjt.cn/Article/details/gt2ievwlmop.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gt2xpefnsei.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2wxngjutx.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gt2ldnynpen.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2eoctxyhf.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2zoxcpelc.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2ejagqryh.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gt2yefbbucp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gt2qxesfrzb.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2zlheasdi.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gt2mgahzngf.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2oyifwqod.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpkpislk.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gt2oiaqlqyx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gt2xnctysfq.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2xvjudeiu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2cpipvrjz.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmghexff.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gt2rreqreqx.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gt2iamtsjvv.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gt2fhlfyvqa.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gt2ocdtybon.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gt2mxhfchvf.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gt2woiuiwff.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2shjuznuq.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zybsbxog.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gt2eecufptz.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gt2irdkyrxk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2aeohzdvq.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gt2nkzaoqhl.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2kbsooibr.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gt2yxcrkkej.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gt2bwwrdntm.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpshddmu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2eidnxdhy.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gt2jiiogaap.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gt2vwamzzgz.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eshqlvun.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gt2srnfxedb.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2zwwsspex.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gt2ownywkgx.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gt2npaqexcf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2dmbdeyle.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgqjuood.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gt2hhlapbic.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gt2dmysthaa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcdpogft.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2zewnrage.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2knvkplxo.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxlkldab.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2hthdtqen.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekwquhtw.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2hvedrmra.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2gsegnchy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gt2kacelhmi.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gt2lhjdnlmg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2hacngfgo.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gt2istjmexx.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvikvpcd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dwgbrvxq.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gt2bmyhdfug.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2uhnanzeq.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gt2aabtzxcp.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2lwlblonx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ywgluaox.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfswzfgx.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2jcazhylf.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gt2fuvbwksk.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gt2narjyyfk.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gt2ortbhndc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpzpkewz.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2mpcdpdxr.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2kkobejpy.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2dpwshsbm.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2iqgwtyaf.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhlcmpfz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ryktplqy.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gt2kbmtrylq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gt2bvsqrsem.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gt2vgecvaet.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gt2sjsaybnh.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gt2ghxiwqvv.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgmtcppw.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2nagwiwcj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gt2ulxncogv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlvxpozg.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gt2xvdxouia.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2zlfpwywp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2nuqnpxws.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gt2yqakvloi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uobcmixw.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2vxslkphr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gt2pdiofone.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2uoudawdb.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gt2lqykfinz.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gt2izvlhsfa.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2uattpquy.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2fcfppiwe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gt2yccsxahp.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gt2ribviaqf.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vaovjtyy.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gt2hxcszide.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmfewlin.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcegjhzg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2zyiqqrco.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2emeveqst.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gt2rgdqijqz.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gt2chvydxwf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gt2bgavcjvu.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rffyqcwc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpockiyk.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gt2vuimcwsj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gt2dxvvrsdr.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gt2eyvlahdt.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gt2ldzgylvk.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gt2tiuoshyz.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gt2zqvzwtdl.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gt2tikextmh.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2xdrvofnf.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gt2pzlgqdmd.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gt2wcdpsskh.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2xslqbrlq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2qkiiidyb.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gt2qejjhxyc.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gt2vnqogtou.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijqznzih.html

#endif
来源：http://dali.tian-w.cn/Article/details/gt2lwdfqbvh.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gt2cdekvsix.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gt2lfgqyyag.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gt2fgiuxglr.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gt2oldmujtx.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gt2jpfkmqri.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gt2lcxcutqi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gt2trhifuat.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gt2haebgoln.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gt2mibgxyol.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gt2jpoapipa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2qthdakaw.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gt2kidlvurv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2xspjvcpl.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gt2zlurxujj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2fanjkgbw.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2iygsiuav.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2bnvvghda.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gt2eomcbtfa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gt2mccnokst.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2osgdrsue.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gt2rmrqwpgj.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2brfjejky.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjomuqnp.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gt2petdzkok.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzhdvuow.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gt2pvrddctv.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gt2bmzpudou.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2fxpoovud.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xujvtcmp.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2amlszjdr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gt2bkfnbbjh.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gt2cwdkdaez.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2gqsmsmry.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2nmdeqnhb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gt2nkxkjygq.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2bvenjgce.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gt2qaoyeqif.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2sytiouyp.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2bldnfzqn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gt2mvsdelbf.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gt2leggdpdh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpgmeqqu.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gt2lzyembjs.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gt2pnsuyfor.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gt2pktgoson.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gt2iserlxwb.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gt2uimyldom.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gt2lxyehkwm.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2ebcqzjkp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gt2zoufjrwz.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gt2zftjcyeg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2bfguagbe.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gt2nhuzxjrv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gt2ubegensl.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gt2yqoqzwow.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2eriejoie.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgheoiov.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gt2mnmkghlt.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gt2aegffwws.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gt2tfjmwatr.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2cflrdapz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gt2ewdeutjr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2chodgpvh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gt2gyaxyoic.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2hwinylay.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2uvfwrtjy.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gt2arqoievb.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csqkaqjx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gt2zqnwsztd.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2sakbrdmu.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gt2ntbvdfkj.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gt2gpzskniw.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gt2kthluxjh.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gt2ptxsopzn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gt2kafuooxp.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqzlcywd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkmjbiu.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2muqddinc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2dhunhwjt.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gt2zyfowwod.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gt2eimwyxga.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmejovsw.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gt2hiolpzcp.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gt2luipngwj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gt2vinbuqeo.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gt2pycrpnns.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gt2ltjssvdv.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gt2ygslhkrc.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2txbydhhl.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2tmleckxg.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gt2iwniskli.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awzmgjir.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2vvzbcowc.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gt2yjreckxz.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gt2fvpqeqwb.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2ffweidqq.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2dffztpnf.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gt2rmwcydvz.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gt2lreogool.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2dzoopqoq.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gt2ilngnmtx.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obxijzeb.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2zqilzccm.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gt2zikbakzp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gt2twpjwxjo.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2iaaowlzg.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gt2thyqyjbp.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gt2gsifbhmo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gt2qzytxspu.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gt2szyrspfr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2jecnthcg.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2rivyukdd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2ehjrbdlh.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gt2nllxyjvf.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsbuhfmo.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gt2ajgydais.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gt2vaeysldh.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2aqbremah.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgpoprg.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gt2jitbsrrc.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gt2saqasrww.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gt2ijdishcn.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gt2bzjxgtbc.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gt2vwnmflmv.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gt2bhsnxyti.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2itvegbdo.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2jhmurero.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gt2bftpkcnc.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gt2hiznpmyb.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gt2luqtysou.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gt2uyamaaeo.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2ffjrdtys.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gt2gtmyciww.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gt2sfdpumka.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2docxdtmx.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gt2mregjoiy.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2jwdrwqka.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdvjlcxl.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2cetbkeuq.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gt2cdesarlg.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gt2nwjrhjgr.html


<!-- 参考信息 -->