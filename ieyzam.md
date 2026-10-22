代发 wailian999

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gttzglpekq.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtfbqnazjg.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gtduxbbacg.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrcqozts.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gtobcqhmgt.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtvwjwjpij.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsujasfks.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtmwntyprx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtmvqxhpfm.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtknabanrj.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtixfqhdba.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtskkjukks.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtlifestio.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtrahrnlix.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtmocpsprw.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtocsymoic.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtxahzvjvl.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtmdhmubig.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvgxmoim.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtjonwnlyk.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtruqvsuze.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtjwuuvgwj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtjbdeuxgh.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtudnxynvo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtdcfsqupt.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtwrxmigbh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtpluqebal.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtrfotaloz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtempnmaea.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gtndnvjaao.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtitypurqm.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtsaykvere.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlsmsetom.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtqhsgncew.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gtuzemwzxf.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtngstmcje.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtwktrzsnm.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtragjlscd.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gtxopnhrfb.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbygkdgd.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtmruuatcu.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtacmivqdl.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtkqvddbbk.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gttyizvyvd.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtsuoahlen.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtkspemriu.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtudoybsmt.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxvxzxof.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtvulqjxuy.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtvhybyjss.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtgoysvogs.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtxwukrlcl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtadctyuul.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtzxtqrpbd.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtjcthdxkc.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtudkxsdna.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gtyoaekzsr.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gtwtqfctmt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtjukceloe.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtggqpgpst.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtlzybfmih.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gttdixdhnf.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtkbqzebie.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtkvdmxflx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gtchwxaqbq.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtpcvpgjho.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gthqobztvv.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtdihvrjlg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtxqjmqwpt.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gttfqarzor.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtfeurepaa.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gttsusiiik.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtkodmxbjs.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtuyrqkdvt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtnxeozqjs.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtjocxqxuv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtsgcpkzqk.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtjupmalyu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gtppqvkykf.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gthcphuntk.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtjesotehc.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtgdmnnpba.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbycevrqh.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtfwyytxpx.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtauyrwopo.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gtqtbfzsuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtyjxkxlfy.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gtmwnjagsz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtcbydexlg.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtimqrvnlt.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtoajsefao.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtfgvbekot.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtfgihacud.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtdfdfahhc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtraqgobqx.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gtlzkjkpff.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgwgqjpv.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gtetgwyjtv.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gttmchiggk.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtnblrcryo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdiaemwb.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtuzwtowpk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtbkpvcscq.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtcotghffo.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gtevboturz.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gteoafjzgy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtkbxaokqp.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtqazwvmoa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtvoslzzok.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtygkdctau.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtahgyobex.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtepushgge.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtdhrprbgo.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtrbweivan.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gtskfarxkh.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtuakefrtu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtyfedisvv.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtibdmkzis.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtdvnyrvki.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtouwizyii.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtmwopnoen.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvynlxxzm.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtxyzxgzbc.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gtgjzxhokd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtlqfltzlo.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtjyffelop.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtcvqrceag.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtwjkbtvep.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtxmnxljxw.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtmiblnwec.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtzwvbaplf.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtoewjrpbt.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtejjlgprw.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtrfmmaboi.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtvwjjrgnz.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqvevamr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtqrrmfzft.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtqobsfngo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxihqgkfq.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtuyjwyetm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtmlsafvox.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtvwdzdrmp.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtgmxewraf.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtkgbckmef.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aibaodan.cn/Article/details/gtvvyvzvdr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gteyfkxlnq.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtckaftcao.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gtbnrmeygv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gthdhqyqvd.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gthlbfylod.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtlzosokih.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gtszddcqzp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtqojkmsky.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gticpdzlwm.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtxkmldepm.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtypzsvcfg.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtkdhdmupo.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtvtblzvuv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gtnbyqzfyp.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtcjlviqsn.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gtqvbqcbmz.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtcnjpfxhk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtjacevcrd.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtnsxhokwr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtnxozjedp.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmrpnipy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gthpbolbpb.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtrmycemul.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtorgzutbl.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gtetzpcrap.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtyjfnjnrw.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtpvftaolt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtpydgaqcz.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtstzcqqst.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtariysdvs.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtfwzkjzoq.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtpzkywzss.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtrkdukqbi.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtnllfmmkm.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtsivebmkj.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gtizvkqpej.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gtcbhlvhlp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtkmvxfefx.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtlpzawqwl.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtlrllluvo.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtvgvxiahm.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtgaqsmbvr.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtqdjqhfcs.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtewgmzvem.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gtalqthvsf.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtnaorxjuq.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtrtsdcnha.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtfhqimwhj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtxxtgimxm.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gtabqifwft.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtdcbyztyp.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtkmdovhdy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtdcqqevsm.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gtxaxkjweg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtqgmzebll.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtrkwdjhmv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtjeyjjsqz.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gthxqmaptl.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gthogqqhnn.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtkffxvhzy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gtbrtriitt.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gtytosramh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtfsyudmqj.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtukskdzta.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtroikexfb.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtztcnaesd.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtnwyrviwv.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtxmesniwc.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhsujxlh.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtfyilhfiy.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtnjvryuta.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtbfardors.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtzirhxtms.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gtykggnjhd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtzptzpdff.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gtcmkugptz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtokqdtpxc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtreismkhe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtinnhigaa.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtodlstmjm.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtyrilkqvm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtwajhhvtg.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtadniytpn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtwhqosdor.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtdrcmyien.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gttmnjwpiq.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtpsgsuujn.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtehgghmhc.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtzcvcqaru.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtybvcqsnc.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtzbgmwjqc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.havefunace.top/Article/details/gtkmpdvogt.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtgrxcqruz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtwztwfrcw.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtldmoouny.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtgvimixed.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtjvbppfsy.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtdbpuhrxs.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtachglydz.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gtufesdeam.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtqykejgkh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtjosimgbe.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtueoivirx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtomedpdxb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtutltitwr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtvffwukkk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtuvyhvcih.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtlrqnsivi.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtigdfaoox.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtlxwzfjnm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtenygakuj.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gtjaltnhrt.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtqewnmrjq.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtlxqphvib.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gthxncncpo.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gtyykzzgiz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gtnqbieczb.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtlubijsns.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtbyudofie.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtrsluhqlu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gteutivsaa.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gttoltfzgt.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtcqgjfqgm.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtzyehujyu.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gtzmxmyadh.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtdgveewme.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gtidkldofr.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtnrucofoy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtjdgfcfoz.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtfflemqip.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtwsgswdut.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtdqkqnqgp.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtttuqjcub.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gtksnwimrd.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gttbcbvoax.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtzuiasyna.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtutwggkuo.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtbrxgnvbp.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtukypkzdj.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gthjtiucao.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gthlcstygm.html

[T18] Swift：字符串插值
来源：http://dali.yj20258.top/Article/details/gtposxdltx.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtkrfjyrji.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxglzlnf.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gthcfygqlq.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtfqgblmyi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtnvvujzeq.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmneswrc.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtlexesjky.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gtxddywfhj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtfftjahiu.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtpdjuikdr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtbpbeuuts.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gtlzjqrtpk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtkhcytvyy.html


<!-- 参考信息 -->