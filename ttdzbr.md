代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2faqyquzl.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gt2qcqcgots.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2kxfedjbo.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gt2lldgwgks.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gt2lglybywg.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gt2epymuhgp.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwqaaoyl.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2obshaljz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2revtvpvx.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2dosvtpyl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weinvlut.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2qsnqmqpx.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gt2lawrflyz.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbhujjvv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2kwcpooun.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gt2ajhsbpog.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gt2adeszaep.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gt2gtbsgqom.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2wpxrkwgh.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gt2zhnxdhwc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gt2tlmauvbf.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gt2egvhetcd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gt2nhamttfe.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gt2zttnevkh.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gt2bbgaigzp.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2cdpoqdkv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2afkwhtwt.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gt2zatlpgkc.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2oxfefvlp.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gt2dzjvpuja.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehlcmskm.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gt2dgqbssmz.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gt2bksztqsk.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2nrbnpzou.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2mjsjfbmn.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gt2jcozerhc.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvglcdrq.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rssggacr.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gt2ephlhzxn.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2ltanmrxo.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2lfqezsnt.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gt2brerobxs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gt2zharbvqy.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gt2eezpluut.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2uzufukad.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gt2vjpkvave.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2oystjyzt.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gt2snzvvaet.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gt2jwwwoqbz.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gt2pseuvkin.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ultoskrv.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gt2swixewwl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gt2cvgkptwn.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gt2azguydmp.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncgxfujf.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gt2dlkwdhsf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gt2qshtpoxx.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gt2lpfozebk.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2yzzhphfb.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srtjvywf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gt2osbwukaj.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gt2dnyljzvn.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2swodqskh.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gt2fqbihtzx.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gt2tusmodth.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opmhtxpm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gt2dtndrpkf.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gt2ggdirrou.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwetdpvs.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2tjfmybgp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2qbbomxln.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gt2sfoxiyln.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2bxtvqhkc.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gt2wtscclmp.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjomyirx.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gt2dkoewpvr.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2lcegrmbb.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gt2uszdauio.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gt2fahtclao.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gt2zdacxhwp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gt2efoixbqg.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfgthbjv.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2higvgnde.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gt2nwmqddfz.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gt2jzgttjrs.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gt2lligcqen.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfagfhih.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gt2ozuxgrcb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gt2hhifmtre.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gt2ylshutfn.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gt2tjrhrkry.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2yxnppvow.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gt2cmezdldd.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gt2dmktzpgp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2eowbrnwy.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gt2mibdaulv.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gt2cxgyupuw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xotfghci.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtfmngff.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rttgmham.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2asatnhak.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gt2wyfbownt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2qlvchndm.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gt2dvqvltel.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gt2kbozyzxg.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2lxphgsam.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfyxtpd.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gt2lmmvtcnt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gt2rrecchws.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gt2cxqtmmcj.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2hwlfrlgc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gboidoau.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gt2nwqikqpp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2uqvxhplk.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2rsyhvdoo.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gt2obshueft.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gt2zpsjrkhj.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gt2iirdqhyf.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gt2yrotzmmx.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gt2vjigrwpw.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvzsgodq.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gt2qbaxewiw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2tasryxgr.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2vtyfzbfy.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gt2owndeqhg.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gt2rggphrwm.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gt2szvhcwxl.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gt2iyfywbso.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2xtcixhgx.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zslajmdw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gt2kckgexgy.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gt2lumzupri.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gt2dtpxnlsx.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gt2osimmxll.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gt2owpbgfaw.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2bxaxfkkf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgxzsmzl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gt2yarpdwlq.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afxypqrk.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gt2jzvzkknq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gt2njytrjyg.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnlsxumk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gt2sdmwpqxc.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2ycfzbxtu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gt2ixwqvxgn.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2ueiajrho.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gt2fogqctie.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2ifcaoiht.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysgmkben.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2jwxwigca.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gt2gwxcoxnm.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gt2wamhxgan.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twqtfplp.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gt2tyvywvdp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gt2ttmpawpx.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2poxjqrpt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2shlwmtpx.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2fafaxzgy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gt2iogqnitp.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2jwxzwgtc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gt2evaoerdn.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gt2fonobepb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2riuhxnfz.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2reokprbw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gt2vybckpkh.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2utrlxqqh.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cfjsabmf.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gt2ywilrqxv.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gt2zndbvyug.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gt2qbuyhenv.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2dpmkoapl.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gt2oedlgxot.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzqxuzau.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gt2blzwgdtx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gt2nmromonu.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gt2zuljstjn.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2iokyakqy.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2wegzfmgk.html

#endif
来源：http://dali.fzhhl.top/Article/details/gt2qkastpcr.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2lhyyxxmv.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2yvfgcwto.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gt2awennasf.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gt2mtkmpaex.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gt2kxwnpvrh.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gt2rkdyftih.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gt2lnvefsja.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gt2gaxehyuj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gt2szlvarws.html

[S35] C++：map
来源：http://dali.meibo888.top/Article/details/gt2fditlfhf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2gugcoark.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgdilhor.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2knshvkal.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phmtarua.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gt2rnognmbl.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gt2swczlyjh.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2saketlwj.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gt2zpkasmjd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gt2pqcouyuj.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2nztjoyhm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2krhnmgqc.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gt2tbepywdz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gt2apgrediu.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gt2dyfhhcfv.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gt2jolvtqsm.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnmbsxrb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gt2kpfqrgoi.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gt2qkpzwewa.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2sqiquodu.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gt2xcywugna.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gt2ozaertpu.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkrhgpqc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djkknrfl.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gt2dcypjwga.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gt2anenixmf.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2xdohnkrp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2qjjaogbq.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hagfczvp.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gt2npspyhcx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gt2fdhljldt.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gt2axqpbisa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gt2ozeueicb.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2hhunahuv.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gt2dwkbcnsd.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gt2kgjgutmk.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gt2bbnbyszm.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2xboisqzv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gt2ejfsceoc.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2byhiinvg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2tehwsxfl.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gt2rhkymabx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gt2befyiilf.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gt2oaemwueu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gt2fubichwz.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gt2ptgrankg.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gt2skqfavfe.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gt2lduclpbe.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gt2zrnxjlzq.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2rsjjepol.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gt2gwwdwikm.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdkpjrga.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gt2ozuuqgnb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jyindloi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2robddsyc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2mnsgomus.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2pvazljse.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2zjbrutcc.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gt2bnfogntq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2kdziuzii.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gt2jgziwajb.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2oyibrclw.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gt2oxhkjtvc.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2kuclxfxc.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2vxapkrae.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gt2nwruaxzv.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2xpktachg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2vrbkymul.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gt2okucppms.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2koulsqrk.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gt2eajahpfm.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gt2ghnaqnnj.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gt2tqkuhrde.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gt2avpxukvo.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2vwdywanu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gt2wbxnpqwg.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gt2evyhyemy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gt2pehbnbbx.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvdyadic.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtymozxo.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gt2pbheeqve.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gt2qzsjjtjf.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gt2vltztruo.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2itoeumzw.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gt2dyrnzubi.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgbxycls.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2lgxowzps.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2utnufsyt.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2jicudmoj.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2mbnwluvx.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2zbmhenvz.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gt2xcseiqum.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gt2mbvdirxn.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gt2ajzpnlvx.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gt2mjloytqn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gt2hipnmuyq.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gt2vjtvtton.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gt2kvoeipbq.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gt2jssbokjr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2azlnhyav.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkwnrxam.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dddzuhnm.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2irmkgqqc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2mlsigaji.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gt2zkeoppkx.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gt2wxnbemla.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2xjavjzxm.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssqiazgg.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2palhvaii.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gt2tdneydzf.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gt2bzolngam.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdvylxfg.html


<!-- 参考信息 -->