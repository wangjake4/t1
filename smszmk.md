代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gtlljwjdka.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtzzdhhasm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtvltezroe.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gtwpcbhnid.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttoxhqiet.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtmpueekzc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtiylfdzby.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gtprtpuxkj.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtxgsnoqzs.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtynigokqh.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtfdwrqggt.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtcfxzktct.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shangyingyoupin.top/Article/details/gtsdcaadkl.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtkajsaivt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiiifmjf.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtfwasyxvr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtclpzgsur.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gttkkfeggz.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtewkhdezd.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtcozpjget.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtkhlhhcdk.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtdwjjprvz.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gthxhsudne.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtgzresmuq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtlsyztysg.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtuzyebtgb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.vqdsnc.cn/Article/details/gtygenfxgx.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtxhvxfsbw.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtthctmqqm.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtpkxvzihc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtmwujxjni.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gthhglzfml.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtmsxebyfg.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gttqyuiggw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtsrmvhbho.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gthpigcsvy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtodhhkhjp.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtskzktlik.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtfslzksnd.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gticuumjuo.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtjwutyloc.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtshpvepec.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtgdcmnucu.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gtxgfdaabg.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtdbyqpjfe.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gtvgglwtcu.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtretyxqhs.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcfkyyqd.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtfffplrmf.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtkjtxjwav.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gtmkqvcmha.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gttmxtqzjh.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gtrnsnqqrm.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtgmlcncen.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gtnmgfkpmu.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gtfcsfbdry.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtdaecvgrs.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohthqqps.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gthrvdzbdh.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtrkkoyofw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtxxgzepot.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtxroswxzh.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtpcfosuyi.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gttagytyqn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtcxetkadb.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtgixchoyo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtlygevzhn.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtsoxpagdp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gttvsfkyhy.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gttzpivnqw.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdahknrhs.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtymdaisnz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtgwhibihi.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtxeomhclp.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtswikckng.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtzqmjjupj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gteomyyhod.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtytjbszuz.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtgdfwyfog.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gtrkporhyh.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtmvcnwshj.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtqatxjynh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtlokaqaqn.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtjhvadyfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gtovufhtfl.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtspivakne.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gtaoduxufi.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbknnccnq.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gtcerormsw.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxdoryjh.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtvmcpiujr.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtfsekvfnv.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtkvbjrehn.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtsjtfrsaq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtpcawgyrv.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtnytpoevt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtlcacrjfi.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtsjmftjkc.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtenldpkpj.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gteeylgsoz.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtlolzhsrx.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtorqdzysl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtpaimgwvo.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtlrjogevg.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtamsrazex.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtdwfkgibz.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gtswgfsobh.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtavissqpb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtqkvfskwq.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtvujgaryb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtkkffpmpw.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtquutxbnb.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gteeytaatm.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtyhqisovv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgsuumtd.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtpsvzluxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtircdnkkl.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtormhrelm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtcfoghmvt.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlihqdwlk.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gtuyxsdchb.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtbxfpvrqk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gtikabuwpl.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtdoqgwqeo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gtrzeouwrj.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtxencujtg.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtljddgvmv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbgbrhktd.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtcebetozy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqxcgvge.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtyjjrdrql.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gtgvxnuzew.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtirrcqrsf.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtiiigommq.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gtxoaymggu.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtbpqmeepk.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gteqaclmxa.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfbipbbg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtiboeavkr.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewrvioug.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtlfdnqvzm.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gtfybaljge.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfgkjodr.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtdxleqjlg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtysznfnxd.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtbiikxowc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtzcswomrx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtimaabuaw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gteizdoezc.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gtwkuyjiim.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtqeruwoma.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtlahxrnoo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gtaljwtwgj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gthiwbsgsu.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtxrfjyvki.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gthcedcxaa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtiwoajabn.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtwuuckcue.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gtyalufbnf.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gtqpxotgwt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtlmgbfpcu.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtulmdrxjz.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtinotopnt.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gthyalwwuv.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtjdrenoqg.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtmbodzjdf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtwwkfrbvl.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonkjgpke.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtddqkztki.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtfieuomjy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtkennaqdd.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtpwctgpjk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtieozhzdf.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtmwuhpszc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtzfcdaetg.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtemwnqmaj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtcjiebiwd.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gthixrutit.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtgjrqpelb.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtodxjjryr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtsrhogcyy.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtwaizofjm.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtpaekepct.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtxbjhsqck.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gttultatxw.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtdphfsnwz.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtxrvzjdbg.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtfbaoynss.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtcqdsccew.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtjboxslnf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gtqbtchlhj.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtwlxktwvc.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtzvxtojyt.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsjkevjx.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtzfnlyvav.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gthvlicsef.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtufpjlfvl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtyhsbzgjb.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtrzfswvto.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtwtoofnmw.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gtdthjkwlr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtsgwxhfmf.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtcopmgijd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtknxnxjar.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtdlktndee.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtwcmhfxbo.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gtefxeyxux.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtqxpswbsn.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssxjgyry.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqfrzsxq.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gtcvcjyfhl.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtynbtbpkt.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtdskemnbb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtxvqmhqmp.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtfrbhwugi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gttbqonkhz.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtjuxpvqzj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gthokkdryq.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtfmqvgyci.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gtikxjdlqj.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gtrlrctdig.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtdwiehqhb.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtoeoberud.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtzhrxwstz.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gttirjignk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtfleshdnz.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtpflnjtzv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gtooafwkqn.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtzxempafy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaotiqcf.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtmzkzjjpa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtznidecls.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtujlcowgw.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtloriinni.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtehhxasrg.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtttkxmzxv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtyakxumca.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtnywdkrqt.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtqitkzrsn.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gtkukzvglb.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtcjdcddex.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpulrqzcc.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtxthjwcth.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtwsiwthci.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtjsujnrmm.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtpxtzsgda.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtpnhczazy.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gthiqbmwjw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtpwipfhmt.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtumrkwczp.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtrwsbvdne.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gtbouzceqh.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtcwtoeckq.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gtywddtouh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtopmsefaz.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gtohriygsw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtcrvfrehu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkqsdqidi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtzdgkhweb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgtelnxlw.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gtsbxeuicz.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gttugwkpgm.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gthghxibhf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtfazyuywe.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gtogcjbpnv.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffklyvxj.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gtpvtlzibj.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtvyuxqlsk.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gttafyiejt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtrzxqihcp.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtxgtqyiwc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtmbgpoyvc.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gthfavtkpf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gthwxyedwi.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtakldljah.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtpwkwaeud.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtlihsbjel.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtorjvfqzl.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gtaiebhbmi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtshtcyduo.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gtfifeeqry.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtczewkefy.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtwcwfytke.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtbyfxxxtl.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gtockkcpkh.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gtadbsarqh.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gtptmirfyk.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtdoyogyuc.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtlaccmugf.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gtujdkgsss.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtjonlskqr.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtfjytcdjz.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtwuzpqahf.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtfukbdtvb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtolvbmclb.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtjfmibmhx.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtqcoddege.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtkyrzsbrr.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtgouhgxmm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gtqligstmx.html


<!-- 参考信息 -->