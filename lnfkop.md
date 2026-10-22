代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtghhdkbfg.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtxcoyjiql.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtoebeizmn.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtwsdlzpzm.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtozsnnnek.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gthwfbxqfv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtdydwprbc.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekonsbzo.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtqdmqddau.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtysisjvhy.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtghwptmoe.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtlpozhdhs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtkxgshhps.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtzvglryrz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtonclkarp.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtfnwhxkdo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtipnwnlmc.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gtumklagmb.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjycfnqv.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtmsoptyta.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gtzlqsjcgc.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtswyshdmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gtjdhmjsej.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtswnltnzg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtdpcwzkbv.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtouqstwxb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtotclegdy.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtpbqkgyji.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtzwydhybc.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtodlxkhqk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtgmwkfwpm.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtixhaonvh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtxfooxyyi.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtdbnipwwa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtleufwppb.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtspnpcruk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtsjszgapf.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gteopkvvsg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtqwidmqns.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtddwzyqde.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtrtutrlok.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtjndfhgin.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gtpdzqqlqv.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtjossplvw.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtxnjklcnk.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gtlnxnwegl.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqgkodxt.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtlpkejunf.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gtaghhpdpj.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gtupscxkxw.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtfrhwwvhk.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtolbgcbdr.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gtpxsduoqa.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtgtfjtfge.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gtavuwnyep.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtbqshnlgg.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtarofrsbv.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gteefwwagj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtzubjaymx.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtpecxkxuw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtpatehxyx.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gtvrjzvdbc.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblxfcfqz.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtxpvpykzd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtrdbqdxlh.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtnnoreitf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtikkivppg.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtsemmnrxu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtmbmbjcyp.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtvoiqgxjq.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gtbdtkylxi.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtjaiiyzgu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gtczvqjdyf.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gttneutskh.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtxadfmlhp.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gtlnkcxssq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwolsfgg.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gthumtczqk.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtghatrvdu.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtlrrvsokg.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gthbwqcbxv.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtdbbplurc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtwecltmlq.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgygdnoyz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtvrycclns.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtoqoiodym.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gtsbsgxujf.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtvusnyauo.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvbtjsry.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtufadkzsc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gtcojrhksa.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtekpopowz.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gttbcxnppv.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtrcrjexsd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gtoemajxfh.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gtqnpctmwr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gtyubcqaic.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gthioxxyoe.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtcbcmpfvq.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtraxpvurs.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtfejndhjd.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gtwpawwnpl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtvrhiiike.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtkcnkpmkn.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gtetvyegvh.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlokpvqi.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtyakzklyd.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtwqfoqfrg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtjpmnufbg.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtxtankpik.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtpawulxmw.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtvdxhahfp.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtpuoloryz.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteugbtquq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gtyngtlfoc.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlljjiapn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtlnzojywl.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlipuugko.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtrjlvwrwp.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtutdjfggo.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtbufkxvvp.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gtkcyvpeib.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtlthpveit.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnggjgmh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gttncwiflk.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtvktcwxrz.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtzhgfplcl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvyvkrywg.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gtjszufasv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvqyghogd.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtsvhuoroj.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtiukekmpt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gthsjbvkgw.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gtslmztypf.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtpjkkizfs.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtmmvkrnfs.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtrmwxtwkb.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gtfdifpvqt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtcsaiczuu.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtudrnvscl.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtrbvhbgkw.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtuachgeay.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtpwrbtgdw.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtenxvqwgp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtsgbgzjii.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gtxrlydkru.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtdkbnyiui.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtokudxjpd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtnrphiluz.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtppapzg.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gthqdhrhsz.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtmlfutmxf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtdnilljnz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gtndojkvce.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtxgydtxbs.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gtlfzsvdip.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtlbdcaemy.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gtpyoguuin.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtbyyawbte.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtjinhsirj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtxrzvllkx.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtugnooijw.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtdmhuoubm.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtnsjyzplb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtqigyuwgz.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtjulmuajb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gthkpngyox.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtnndikauu.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtpugetozy.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtmayjzrnd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtzktfhsmi.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gttkdmqrip.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtrfvtxnaj.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtswoxdsyr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtgcvjpiau.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtgdlsdgcy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtuvefxpzy.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtfhxmfoms.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtxkppaezj.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtmkegbzyl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtrevsimaz.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtrfnqmumn.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gtahjkikwx.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtqbcemosg.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gthfmqhgkk.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtioidxcrh.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtnshqojhs.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxtpuzzn.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtbkvqynwu.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gttdjfqchv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtrpvpvhls.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtyhypcfnd.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gthhfeziuo.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtyhntcpsh.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtafpdjztm.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtniyfkolr.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhgxayuv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtfvzajbvz.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtunzxjuug.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtnbfpnfgc.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gtpodfgeze.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtuzzsqdpw.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtxsfwubfx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtgypmxlhr.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gtonvbidyh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtwlxuikqq.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtyohstfkw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtiseuhmxq.html

[S37] C++：set
来源：http://dali.yj202588.top/Article/details/gtnralgiif.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gthdwperyt.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtlaqtrnes.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtskqkrmfj.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtsvdpruph.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtlnzooamb.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtsctrjces.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gteumphcmo.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gtdndhrryz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gttadrqzco.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtbybnewwc.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtjmnfaikn.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtcbysjfsz.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtaupyruyj.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtamxqukzu.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtndsqtpnc.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtgyjfuahv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtavxmbisp.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtkxijkgdz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gthdfsegfu.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gtjqdptfrs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtqahpevkz.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtxyxgoivv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtbfqsutyc.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtokvzesow.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtvrsbgdms.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtdqhdcilq.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtklbuogvd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtyivfgmaq.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtnmdhmdom.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtxvwxxmyc.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtyngrrdzk.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gtrdcjghyp.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtadgxlesm.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtyftbwxve.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtdqhvodlb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gtdoajlnwc.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtqjbztzbf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtafgwbpvw.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpofqonvb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtdhhjfbwv.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtiffahpeo.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtjppzajwf.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtojrwikbo.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtyjjrhwuk.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gtsywnpjvp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtlfshpkmm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtgtatcxva.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gtlopcqslr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqqyjfdci.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtimmcgbcg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkcpzvdse.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gtomigktfm.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gthbpegxho.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtxeptktxa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtorscypli.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtuepkddju.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtyhpjehxy.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtdfpezorm.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtmqyqcazp.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gttssjwebc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtxsqzknaa.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtmcmtkeap.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtykxvmbli.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtwexydtqg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gttlsohwex.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gtjaypfjhz.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkblvzxlj.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gthttwxgqr.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtxgxhzmhk.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gttnifddbs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtitujzilg.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomcnnbzz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtaypfqjla.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrrccymm.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtxkvjbmwo.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gtcyiicxbu.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzwffunt.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtuovxjgqf.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtqgplzpcb.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtpgprnaod.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtogvnizpy.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtwnxgsbgg.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtrigxnkbh.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtinglxqpi.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtucoetzyy.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtdgujyqhi.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtmpimitjt.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtmkwumzrq.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtfjtzqxxp.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtvhmycuvx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtaxltceje.html


<!-- 参考信息 -->