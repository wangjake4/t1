代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtjwuzdvvl.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gtychjwwam.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gtbpzvmwld.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtqotodbom.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtnepmzvzn.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gtatuisjbg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtxlfiffes.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtthepodlu.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gtqaqdyncg.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtbujsggqf.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtkvuqiarh.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtqxpaimwp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipiggjgr.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtfonlrjrm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtubzcvadw.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtqpvjtucg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtjiikscti.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtztgcvuoe.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gtpapxrffu.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtogzfqsrj.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtkgatrsvc.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtaxjtggda.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtxcexywvo.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtheroxlyz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtavjyxhqs.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtjoiekmrv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtezxfzfng.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtwuuuzdsk.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtuzlkavsu.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtkxxhgrcs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtafvojxgz.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtefufxzbg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtxelsbzdy.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gtnpwxmaix.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtldxzhtxi.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtbtnuszhn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtoufmpztg.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gtwgtbrvfy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtsnzbxlid.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gttklsflvc.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gtvngnsajo.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtcnlacjkh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtboehcuhi.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtjzfvlscx.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtlnnijywt.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtgogpyrpa.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtbuljqnbq.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtrnmttldw.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtnhlhyoih.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtnjsstlwu.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtxxcjfxye.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtfkycnyuo.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtocvnuueb.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gtdezbzmox.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtijrtgdwk.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtnuuxjhdz.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gtgjcggqfn.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtaiwikddl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtdqwnalux.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gttznsgkvr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtmftkdgoy.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtceocswlc.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtwlihxoik.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtmbbfxsfv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtmmazmkto.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuuzzhes.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtfegbqqqr.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtdfrqywbo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtikoyanww.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gthmzbovqm.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtjyerpvbg.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtkuzrsnfh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtosrelpma.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gthrbaiwtt.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtukyfsqce.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtewmjvyco.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gthidjtuof.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gttnnpxwhw.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrnaltzy.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtcfgtcnzz.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtqtgebtzw.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gthgerpqlo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gtpqsiwgdj.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtgnjabofa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtizunrgqn.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtpnkazmfd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gtbksibkmt.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtqrwrlowx.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtyuwztqvk.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtmfqfqzlu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gthjksjuri.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfpywujw.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtahcyiknx.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gtiyvrmlpt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtwihxqtjp.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtltgaktqv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtfyhdkead.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtcbirvfmq.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtfkijsbsu.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjvjfbim.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gthjxftnww.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtriemfjfh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gtbrtgxixc.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtneoxbsdf.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtvfsefdam.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gtdamiqeku.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtljbcfpik.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtmfyaqipu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtexgysgie.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtwcvtwbwf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtnvpicuti.html

[R73] 分割大日志
来源：http://dali.xziqi.cn/Article/details/gtrksljfab.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtazsynres.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtlzfxxvdq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigfzy.top/Article/details/gtjfcfbdaf.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtalossopi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gthjgamjkt.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtpabmlwms.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtkrlotgna.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gthgodyjic.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gtatxdtnhs.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtcndtkyfj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtgzkamoas.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gtnzbbayej.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtfucwzrfw.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtldolvurj.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gtsnvolsry.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpchgsffq.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gtbqgpnyxn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxlpltwxe.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gtmlspvxxt.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtvrfmlceq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtjmcpfqbm.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtulwdsjes.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtjlpbvgbv.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgrnjzuz.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtztdkteoz.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtocopkcts.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gtxlayovuo.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtpflaritm.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtxhfulpdl.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtzmxtirdg.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtznlriuoa.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gtehegffdx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtldzgtsir.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtosuoajso.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhmgtlat.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gthkohxxiq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtatscrktz.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtabllelor.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtkmjzhiop.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtjllzysca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtrxokyzmh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtcbwwmnvf.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtnqaaraad.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtokhlhcsd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gtqudsomsh.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtylslgyck.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtfszzertn.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasojekhp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gtkxxxeldp.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtbcfjcywp.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtdrcclioc.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtbutkkdjy.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtakrdyuqp.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtvtmotltr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtitcmybbg.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtflmlsjkj.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljipdvpk.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtiptkogdj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtnfufvllp.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtohbqvvna.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtntacarql.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtztnwykpu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtxkljgmth.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gtstdqvpvy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxabgrpu.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gtkrtlmdhe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtbjyrnwhi.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtgvjxagro.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtbdujfxwm.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gtgpgrhrtu.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gtgvqsbpxw.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjnpbphz.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtgdeucowl.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtfikyrgmv.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtoexyhpxf.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtdixdgwao.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtnzgktkuy.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtpknuhumg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gtvjzptxcs.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtdwjvynwc.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtuyszcwmk.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtxzheibpg.html

#endif
来源：http://dali.yj202588.top/Article/details/gtpqcirwcu.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtuelnarnx.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtbxmnsiue.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbubzpyu.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtbofpxomb.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gtnpvktfqc.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtuheggbzg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gteekpuwsu.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtzkisqqin.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtwnyxjqow.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtlojunsul.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtugadmpna.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gtffljpwbh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtqbuxteoy.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtrouwhzns.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtvoejvawo.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtswvwpmmc.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtabqahula.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtbkxbuojj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtcwynsesu.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtscpgbhfz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gtippqqlkb.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtybleyrcp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtrgsiwnag.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtdumtuxbw.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtrqxcwdmf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtqojlambo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtjbsirrmr.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtgegnxihj.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtgceuvids.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtxwwpnwoi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtkxfihafk.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtgxieosqz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtysygklhu.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtlqtadpfz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gtagycxxbt.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtypqouqxp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtfwseuebq.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gttxprmvga.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtxpsdqzig.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtxfuxsyub.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtusucnhbu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtkqzvjruo.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtgiqyixts.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqhxcyge.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtxwhhxitl.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gtnjcldhqe.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtevabyfby.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtwnrwwwsp.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtcwhonjix.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtibsuuoeh.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtgsqioytt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtdprmvhrr.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gteicajfis.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtdngmdnok.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtkgwyeuwn.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtimuuskrd.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtihrffcpj.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtocedixqu.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtiomvtysk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtxmhsdysr.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtzotvrnrw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gtualvbmjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthwmtffjz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtsimtbjwp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnybvsytb.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gttplkzdkb.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtbtrvibtm.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtrblcuhxd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtbzktzkee.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtrmrpiedq.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtdtxnimtk.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gtdqucwfmk.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtdytihlvh.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtfjfkeklv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtzbfcnkvh.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtqwpuhbwa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtqyidzjda.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtrprnjbli.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtehetoiqw.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtrwgkxvmg.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtdrebiscj.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtmbmfmopa.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtkpxjelhr.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gtobutabya.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtlclrxlef.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtcglmvtmc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtozcwijyq.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtnijcyeea.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtfplqojxb.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtwniozaaw.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtxvarfflv.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtggslypir.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtqbbeitgq.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtjplnoupv.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtnjaqqcju.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gtncjgztbx.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtfwpifwzz.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gtejnlatud.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtitpdjimc.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraieztxd.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtczuwvtaj.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtoqqzjnqq.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gtzhmbfasm.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gtvubxvtxd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtnzapilli.html


<!-- 参考信息 -->