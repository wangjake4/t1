代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtzidtvcmf.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtujbcycsl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtdzajdfsw.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtyqxruynx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtqybknaxh.html

[R26] 命令替换
来源：http://dali.yj202588.top/Article/details/gtkcxoupjp.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gtfgwzmhnd.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gtsrqxskle.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtrifofzmo.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvfowbnt.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gtkfmzmlxa.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtutordpbm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtacandjnj.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gtdivtwagv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gtbusgcwdo.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtcytsobim.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtldowpcox.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtlgtjhuat.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkxqqjiuf.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtfnfjbunu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtpnjglunn.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtdivxoiix.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtifbtqiqw.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtdjufqjqe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gtkyrtyszi.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtxjgdzgoo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtcxtgdjqz.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gtvtiejxez.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtdblfjoek.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gtzvohpwmb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtzdzmfyyd.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gtbrckvgft.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtbuiezpxh.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtypcwqqns.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtlgdqljdk.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtrkwelbql.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gthwbrmngm.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtaviqjpcf.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gturnxnczw.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gttvybcfmp.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtzvfkkjne.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gtnymitjkj.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmcmmcqr.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtovmwihuw.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gttrriayww.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gttcrxidoy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtqlefxzgj.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtckljtale.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtjtudbnrt.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtibmxkakm.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpwfwjnt.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtmhfhxchd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtqwskfceh.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtqsoxupdw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtljqcldzr.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtqxmnepac.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtboyyjlrf.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtqnffdxyu.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtujmrkwxo.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gtgrebaffc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gtjubwypdt.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gtlgofjazh.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gttcqokxip.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtiuzuciws.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gthpexeode.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtoealesie.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbezxrru.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtachodfzq.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdlqtdpz.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtkqjzhzzw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtvuiohhkz.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtaxpojprp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuoolnue.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxakkcib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtkfrukctf.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gtttyjzxhz.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtpdfgypcf.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtixccmemr.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuyfwdui.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtwxjkdsjc.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gttpzyolfh.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtwytymxnn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtruqguoxy.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gtxwzlfbbe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtrzemnzfy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gthvxvibpv.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtksldvhwb.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtwobzzrmo.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtvwelbokz.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtaqthierx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaehqmsvk.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gthcadqhym.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtrieqjvpa.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gtgejhcybe.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtjporwnij.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtajzazesv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtwdtmpsmn.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtttxpvgdw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtxdzelexl.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtsmhejwce.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtdctffkqy.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtfsegoznb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtnidhmjhj.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gtckeivylx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtzsziamlo.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtsqgdoqau.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtmntqitoi.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtsqopuddb.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtxeyliejq.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtcvrclfue.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtnethurge.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrjqnuvq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtrwexfetg.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtzxvimqax.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtbyotbgxw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgpzedytw.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtajqsarce.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwpnatzbn.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtfmkxxiqd.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtdqrqnepr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtyrmstbbf.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtyokhoylt.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtdddvyafa.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gtbawlciee.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gthkwmkpws.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtivrxfeng.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gtjnrwjvxl.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtdkgjstsu.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gtipziyrjb.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtdeqhqply.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtnrztecgn.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtlmywrxqi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gtgslbllsa.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpzilrzp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtmawesetl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gttesnirhh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gtpdtypjhw.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gtshrhrrjq.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtteveklmu.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbmzfizsa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtlmxzgzvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtmhfipbkn.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtystxpsmu.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtvrqeqbjm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtgjvaabzl.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtjhxkyvmg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmakpxda.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtbfsrdevk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtpsxajgay.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gthsnwnxlu.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gtcpddxkmz.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gtyqqbvaat.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtgxvukapf.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gttclbctcm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtgwcleljs.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtukbnemug.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gttnsmkvqm.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtworgxvno.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtxedvcdxm.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtdzexnrok.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtquhseplo.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtoqjraovp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzzprbpp.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtmfeucoms.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtblhgtxcl.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtmwnzitqk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gtdejttsqh.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtaqzynuth.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gtwnmzhafv.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtrgguwblw.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gteeteccwe.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtqawzqgiz.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtkuuugtdb.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtitkwitdt.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtrbelxdot.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gtotyhizjo.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtacpdtynn.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtmngwrwqz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtluroxylo.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtncirwojg.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gthaetoiha.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtekymxwpp.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gtzqhoafgm.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gttyxxfzel.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gthbdibbkl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtjcwpiksx.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtaovvsbpg.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtqiptdmcf.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtrvsbmcjx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtljqoqxzv.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtuyyyqukw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtjvxzyhfq.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtzfytaezq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gteamtxugk.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtdgmqvaxt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtbojvgvcm.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtzhptnfsi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtswiikuyn.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gtnsldyymp.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtdkknxvks.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gtflqqqzdw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtscbxyewr.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtobqpsqnf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gtjorfjmli.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtqvhnywhb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtehiqrlqs.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtkcdsdsch.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtmljsncxu.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtfibnmvkg.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtcttuevaf.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gtxdfbcszk.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtoqcpxlkz.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtlwjkrkts.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtteizraml.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtymfkoqap.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtchrmbdwb.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtcgnmsznf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbmgatftb.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtowrwmjeq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtkgazekve.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtjsgjniro.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwfogdiz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gtyhzzugpc.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtybkfdetd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxolqnkm.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gttixxdnud.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gthlzvjten.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gthatbqwya.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtmgcdetng.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtdhfdpsmg.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyldlvwfi.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gttxyqwlhe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gthofbjepd.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtigccwxhk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxxfpwhu.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtdjjwkryh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtfmhsxhlv.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gteqnjclqj.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtfqwpwhpu.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtwveqpcra.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gtyaibwlsa.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdjgaqgs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtplqrikff.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtgnviefwm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtfklwdodn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtccbltzvh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqslwhxa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpbjheehe.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtvplujhif.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtidvsusxl.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtixzacqlu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gtxnvujaab.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtpvzfoeip.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gthqukdbpz.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gtrmmdqozm.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtvuneobsc.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gtkveiaobw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtdjaqavba.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtsofnhxnz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtgtuwlvyu.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtwactahyz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gtwurjhggr.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtwbgmiskg.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtxikfqcvg.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmpokjrjc.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gtoteuvuli.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gthewkyzup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtbfahljbd.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gtooxkkwbx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gtsgisqlrg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtcoduoxkv.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwinendpi.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gtiymwqlsx.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtwiczuvam.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtoipmkkns.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtwatnrxfo.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gttwyswrlu.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtnrwnpkoc.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtfjpwahdz.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtnflepbia.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtgfhhfzae.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtssnysgwh.html

[T18] Swift：字符串插值
来源：http://dali.yj20258.top/Article/details/gtzfnjcirm.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtyesutzlv.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtxyjmjrcl.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtktskeurs.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gtdkntbmgz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbsrednq.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtlvcqobqu.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtxptdwzfb.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gtofctycfp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtrvmtrhyp.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtjftqqynh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtmuufotwm.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtxltykyay.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtuamrdaki.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtfxdfzbfa.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkxntgep.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtfvmmsqzy.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gtiapgbane.html


<!-- 参考信息 -->