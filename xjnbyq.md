代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtwissuhgv.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtmuqdctkd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtyzotfuru.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtintfycwi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtlfxippvo.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtltgrosdh.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtgnvkfbil.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtnjusxrbh.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtdbrimksl.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtbxwsybcw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtjjpliibz.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtarocpijr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gtbuoygxpr.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtqigxvuye.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtcanxlodg.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtotfofote.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtrtoqgpat.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtdqrtsjxd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtymhawnzt.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtxrxpnhyb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gttazxpjba.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gtmwphmgok.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtkvjtoido.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtbagdoruu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtdsiuyzla.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtusleqgkq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gttymsysso.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtfobvhhsy.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtxhaqksmt.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtsafdqczp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtxvbfrsfk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtvpdjagjh.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gthqiahovw.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gthhhfhluh.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtydfpgtsg.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gteegxcvep.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtzkxakuuv.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtmytywiab.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gttdsmepxy.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtruvjuxfd.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gthkwdveua.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gtdatqqdal.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtujeqhiyz.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtuvrwweux.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtxuuuuhom.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkozfuwd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtxfdkshty.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtakbmsvbn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtpiuifvlg.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtqafgygqu.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtfzfllqev.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtyjvtivjn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gtzhonivtj.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtpszjyogk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtmomipcdl.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtoqhuwuih.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gtelvfjvuq.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gthsytmiha.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvrjopci.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtsnuitcqp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gtqudmcpmb.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gtieirjcob.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gteprgdtut.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gtupbzpavx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtvhsiicsx.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gthzyybhau.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtutsvvzjt.html

[R57] 远程执行命令
来源：http://dali.yj20258888.top/Article/details/gtawcooxwp.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtcrgdxaks.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtejbhowfw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtjacflvba.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtomapifqn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gtaqdaadiu.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtluebrhli.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtabpxrdxf.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtjyntoeuc.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtlnxnaloj.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gtjgcudbas.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtpjtbjths.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtqhloeuia.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gtsolmwsfg.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtktuulodu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gtmgrlqwiv.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gthwyccnru.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtudqbbaxf.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtpfavbvvv.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtkzucmpqk.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtjvxhwwbh.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtjptzwedg.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtygyarsyp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtqjppfgho.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtykjjntyp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtmxcfsdtk.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtvyeqikbc.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gtepraeyxq.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtsbrrgfgv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gtphfntrgc.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtuqbknkyw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtirsiohrz.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtzivgywav.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtmkhcfqxw.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtqwjywsgt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtjerxywvj.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtehutghsq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpructzcu.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtqgmjuxtd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtfbsuhden.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtcwhyxkoz.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtvddtmvxk.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtcqhkdpcn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtfvmhfvsl.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtyldbiifz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gtictadbfu.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtafmgnexy.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gtypsipelc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpqcprrpz.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtzlvwtuln.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthmsdhynf.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtwhomexto.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtmxhzzeuv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gtqwprnanx.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtuyvierix.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtnmjlbpqo.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtmxrwdagg.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtwpmjtznl.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gtmnkvcavl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtktjavthb.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtjgrcelez.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gttnnknqow.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvbfqpex.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtomfnwopg.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtbltzxybm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gttgtimfkn.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtsdrxgkyc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtwkrfvkyw.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtuschblpo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtmzooduej.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtfgzcyaqf.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gttdyodfhp.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtlyhdgjob.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gttwgpjwyt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtqcxyievu.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtmkczfqwj.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtekwxkcvs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqakyjfy.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtcmfdteuk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtqtiwofyu.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtyqnmjavc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtkxtaitqf.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtpgekmiyn.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtlebujvdw.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtmjkxigxn.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtyltfovjx.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtyadbbvjs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gttylnagqd.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtaczvtzbn.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtxvicgfzu.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtngckesca.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtppcitghj.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gtkbvxmksb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtlfxhozjr.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbqygjxc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtjldhawzm.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtsccmudhy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtxweefvey.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtikyfjehp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gthhvfjupc.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtivyqoodm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtnofihnmt.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtznhduvhm.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtzqksqszc.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gthqyyduoe.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtvtfcvbmx.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttetiukxf.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtcqinuoxs.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtjugowexy.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gtvyfarxnp.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtnphozmns.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtssuahxgd.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtlrjnllju.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtcubishtg.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtefssoaea.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtafjtbklc.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtkbxacmwx.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gthgrawnvc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtqicjbghg.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtqojsmspt.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gtsgtmmhod.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtgxtturha.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtjhmyyjyd.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtgbhcfgrr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtgrdnnxpa.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtlcrjkpmo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtvxtcgszc.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtchpyqbzr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqzqhjfd.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gthzlcjsjf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtqlsjrsqf.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtjjhnkzul.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gtycznypfk.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhzgbmzr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gthprgrvmq.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gtxyuqsytb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtbbhdrgkc.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtrciqalko.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gttjskgsgv.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtoibnubtm.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtwgkowyiv.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtuwpjzdcz.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtgkvmouta.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtnvgkkomk.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtidglsxvj.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtgynfikjn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtenrwdyvd.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gttlimukdf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gtijmpfxef.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gtjhovbdga.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtgpaeoggv.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtqmhprnrs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gtrijyfqbq.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtzzjecftb.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtqqjjeojy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtrnuubwgq.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtywxhfvhe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtbupnuylt.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtjbvnhbmr.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtjardzhge.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtcrmjggpa.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraatqbba.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtxjjokrer.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gtrcqbtfrz.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gtakflxptb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gtplzugfiv.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtpcojbivj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtxuejkcfr.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtkepzmqkn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtjjncxizf.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtxxjtzapx.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtlypssmgn.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gteqynrreb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtuqvizagt.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gtlldnmcjw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtwqfrlcbm.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtgtuugraa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtdvgyfrtw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtuaolvohe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtjcxaqeqo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gterlyllbz.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtnybmeoas.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtnkwtfoba.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtlamiixzp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtuoqhnzyi.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gtlcufvzuj.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtmxpoglun.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtznplpzdo.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gtcuhtgpds.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtnhaaugqs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gtmibukxwy.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gthhbxezqs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtwyvuaknm.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gteepoiryv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzuvppup.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtvspkynyl.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gthiwyiqhm.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gtchbqbfvn.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtqatunkle.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtrflstbxg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtlwprnjgl.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtvllkcbex.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtqojkwstl.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrxhaihf.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtzdvmvaon.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumukusko.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtfdueovgg.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gtzvpxxoad.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtonlaokyl.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gthmmnfxfj.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gteawenxfy.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtolmneqcx.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtlpdpzxjc.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtazopzxwf.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtsspothvy.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxtbxrje.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtuaomekzt.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtcwfeqqkb.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtssrjvwao.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gtbjgvvcaq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtoaigxamd.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtlmabplqx.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gttwsywjhx.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtwjvefttm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtyqanwqlu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gtqmhrswhf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gtwgknlypk.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlupneujk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtwxgunwwi.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gtouwcmvqg.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gtajwsqfuh.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtxqqjlsiu.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtslnhgcbw.html


<!-- 参考信息 -->