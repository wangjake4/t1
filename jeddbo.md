代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ydzc1.top/Article/details/gtgchklznz.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtfmugejai.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtiwxkmvuh.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtxdqulwfk.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvizdrvbs.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtyyibaabt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtyvjghumq.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtwlqfadph.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtbmbuzvpy.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtnwembwbi.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtqhrqpkaa.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtawzffcre.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtnbbwkkqg.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtoqvpjblj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtlsznfwwf.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtpmnvcksz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gtyujukajd.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtsmassjaz.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtodlojprk.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtkxtuqoxd.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtxatowwhr.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtssyepogb.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtdkwfkorx.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gthkokeljs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtwopyknkj.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtibmzftdt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtqgljzpqe.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoktaqhdn.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtmouvqgkl.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtpaddfpvh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtatigiiym.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtokmwhquc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gturbqvwxf.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtuyfaifnk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtnluazgpv.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gtjhjhjdgo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtotnaqfmz.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtiqdpzxpc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gtkrtrsjgf.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gtqdlrlyen.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtkfwplimb.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtsafjtedo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gtmseiswsf.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwrkekjv.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtajzunafc.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtjralyseb.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtkswjocig.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gtxyxxqbrv.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikmpdyof.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjscbrpc.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtlvzvjhnq.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtgufsoapr.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtlmwgolxp.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gttflwpnuh.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtgrdboixq.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtjetazewx.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtydenwyif.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtfcsuqzoy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtedlbqlhd.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtvsodgtin.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtsjcgmdjo.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtfxrwgwnz.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtjttffghk.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtvhhxdgwp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gtzzsirpjx.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtjfouhjms.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtnsakeznh.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gthxgbkpvw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtysadsuti.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtakzegbey.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtkdooivmz.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtcuqrfwaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtvxupyacf.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtdkrobvpa.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtwabuybco.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtgxxpvrst.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtejhlfnjo.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtsudloyaa.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gtzejtglfs.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtzbqsgrvm.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtmouzzzce.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtmnzmznsh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gtbzitonwu.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtgqgkpfrj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtozjfumwq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtraividfd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzwflusd.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtaqrkgxln.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtegetqgpf.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtcswzhbsz.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehmbsxwg.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gtezmczvvh.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtsbyohkyw.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtygydwkuc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtlwwiudts.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtqyustrla.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtfmyrlwxx.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtgzohtalb.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtouuxhymy.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtkzhjzpvs.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtkgxxhlag.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllpdsfkk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtggthdvhw.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtqadegsyo.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtckmivhxc.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gttpszfqmh.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gtiwhcuevw.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtpfabsrkc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtykasoabf.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtcdbptqom.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtmpvrookq.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtessnsmrd.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqwqihhc.html

[R74] 批量重命名
来源：http://dali.mhx1999.top/Article/details/gtqqedtqlk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtcqmiabhm.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtbknbpsyb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtinultyzc.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gtmivwviyg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtidlqlpgp.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtnwtqlhlk.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtfwjdzrtb.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtfpqtbwog.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gthxgyavdz.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtsaydwboa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gtsbxjejpg.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtfsbrequt.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfuapzlr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsrqxfsws.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtbmlvlbfo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxmiysltz.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtwawnutyl.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtmpvlwyor.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtzltyxqui.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlnknmul.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtlovsqvez.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gthywwsrwi.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtuweugeeb.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtlqlntbri.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtgbkfinhb.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtzabdcyns.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxzersjts.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtviuruofq.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtegukpmkm.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtxobhtvsn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtxwgxiovz.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gthdfuujkz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyobpbmr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguonkcqe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtnkbsvqxc.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtulocteja.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtrummnobr.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtovwtynpk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtpjjufaqu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtuqdbkweg.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtennuqwkg.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtcllfapyu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtijwbgvum.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtjavplbez.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guowangkeji.top/Article/details/gtamrdlozy.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtpvogijlv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gttiqudeyp.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtjapthcmt.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtklwghnxw.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtdtdqedri.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcahiyyob.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtwejezmij.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtvqzyrdug.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejazmnmw.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtglhkugnl.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtohzflmbu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtidmgiapn.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtrfpgsfqn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtwczfqlox.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gtrpitglfc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtcnbmysli.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtfdahwjdr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gtlboibmos.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtkdrcjowq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtixuztmll.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtvmhurqal.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gtnbzhsemn.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtfikrohns.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtsmsyelfg.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdefhgacp.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtkabtkgji.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gteowehvqv.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtcjbjffzs.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gttudxbdpl.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtblqhrvzu.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtvwfcdnwl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gterrmccyq.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtwlwvnwao.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtoyxwnzza.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtpytydwmd.html

#endif
来源：http://dali.havefunace.top/Article/details/gtdmstqchj.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtidzqodfv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gtnngualez.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gtidtmuxip.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtxdtnvxga.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gtlcqnityw.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtuneazsks.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtxehfsmht.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtgtyzdbko.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsqjxsfc.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtimenlbzp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtbqlxkzcl.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gtjjkdkgiy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gttmhminla.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gttwqifeoe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtcmjrqzsv.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtnnednpkn.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtawfyhciu.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtsrznqybt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtpiyxmvnq.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtnmttbell.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gtlqlfzsjl.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtphdcnall.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtvobvhegn.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtdckjnjdu.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtnfaslsib.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gtbsvewedv.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtvhpryhso.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gtwhgnbhox.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gtgwdygcmp.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtqjcnqzys.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gtsgcbsmrd.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtttyeblbo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtzciyyyha.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtbyimnaqw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtfgojcziy.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmkwqolf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gticnzpznx.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtjtjsgjuf.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtqnpshycp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtvbsnyrem.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gtjksgftlo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraksvwyi.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtraetwyrw.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtqmsxrhvs.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtsjiysice.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmyxhwtf.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtazhkqfld.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtxddqlnpv.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtxgslumwl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnafclle.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtuoqddobt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtxngfhpjq.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtetrdczky.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaccbtqmu.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtctqksaxe.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtwpaobtln.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gtooklknvc.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtbafkyucg.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtdbcvebkf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtkoybqp.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gtkryfgpco.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtvsjncvgn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtozzqdlou.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtqyazewdf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdajmbrzo.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtfkkddkeb.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtpsrvkngx.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtasilupvo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtpiaersvx.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtthmkqyle.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtdsypqctf.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gtxkjglogc.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtiwwoodvc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtphfyekup.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gtnroepwpc.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtksepcbgt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtkmpsswym.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtvmehwwsd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtcxwpalrp.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtkntqmtyw.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtfbjwdknz.html

[T09] Kotlin：扩展函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglsimwfw.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gtaxfxpiph.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gtsghrdajb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gtxslcdxns.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtgujvcqoz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtzoqcgsui.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gtwrjdgdin.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtsfciwmqn.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gturwqbwlb.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypiuojpv.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtbqdgchqd.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtjhronfsx.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtjcpduffb.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtfumlhtpj.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtiswgtwdm.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtyxvtclmq.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtralzohfz.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtzxqiclex.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqwpasna.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtgyjoxqjr.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gtczvdnzjc.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gttprprydc.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxuqaufl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtokfbygyx.html


<!-- 参考信息 -->