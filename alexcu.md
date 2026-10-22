代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtfxsfllpv.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtxxtppaqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gtzsvixxvp.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gthiqqdxcd.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtwcptjgjs.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gthpqbjyid.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtjydowvem.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtgxyosqoo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtdtvdvjzb.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtppumbwaf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtfddhhxeg.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gthgvkopet.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtmbcuywgq.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtpgxfdkky.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gtlftvlfly.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gtbmojivax.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gteelmaiws.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtnshlzlsc.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtmifratls.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtypbtewej.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtkqdzfxiy.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gtvueviwct.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtcfdhhdse.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtewtxvuxl.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gttlhimdst.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtwysyokyl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtcjpxannk.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gtdhvxbxlj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtgefieqke.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gtjxocpyod.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gttavgeloo.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtahneurcv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtjlknyabd.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtwktecquj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtpuchcyfx.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtvdmqknlb.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gttjocuuoe.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtgoevnfcu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gthfalbiof.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtunzumwvn.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtjaysvfhc.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtlramadjw.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gtwvuwbowl.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtriuqahov.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gtavmdosss.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtwwlykycc.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtctffqgrj.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtympfnjie.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gttyjillnl.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtubrrbvwf.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtgyjzedxy.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gtziadmxab.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtpfqvglws.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gtcdddngnv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gttggmnkzd.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gtabezoixr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gtqpkhvnyg.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtkefiferi.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtchhmuaax.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtfcxnhxif.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtqjywrxan.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlelgpug.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtlxdbqvgi.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtcteqwbhz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtxztxtfqo.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtwunthrdr.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtbfszgcqo.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gtvqpnkbvv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtskrbwshc.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gtmqxwyrmc.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtwpmxpirc.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtiowwbndj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrimvtirz.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gttgevaree.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtoczpsusd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtuwrxlupn.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtksgbhxby.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gtoypphdsi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gtniivlqoi.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtbkkqtodh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtyjmayeyg.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtrgnuqhhs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gtylwacnvj.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gtzdixoubc.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtfkpmwowr.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtsygwjbze.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtybptetsb.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtujyevndt.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtrocexykp.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gtunfhgysd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtsmmwxsab.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtsanygmhg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gtiwxptxpa.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gtlknyuvmi.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gtjqjgmlbn.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtmlvrvdrs.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtspyffcar.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinyglzgs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtnkzehagk.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtummquisz.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtxxnhivst.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gttlnftzsy.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtcqwjukcj.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtaocqgkdc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtlkablxdq.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtxxybnqte.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtwxmqftjq.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckglvnpb.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gttcrloccb.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtdvptsqxv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdnyiidm.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtkpqkcunh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gtepnhbxti.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtkxtmnqks.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gttopucukt.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtssizbmhg.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtzeuutghp.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gtqojiwmic.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gtcixgvggu.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtgrlgkgrv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtmcbijlgg.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtiabwvjuz.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtsmmomkng.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxplztpni.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtkmzlrels.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtausaqilh.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gteppyjyyl.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtjihwmssd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gtazfnkhpj.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtpyjpbthd.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtiededilu.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtdxuweota.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtiacgngxy.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtviwxyrpf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ydzc1.top/Article/details/gtvtwheabn.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gteryuxcys.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtrzepprxo.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtddzelkhx.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gtmekpaaog.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gtosgkdswn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtzoresjjg.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtszdarqlv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtwhxismdw.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gtqsugjvyy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtaxafhjyx.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gtgouphkax.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtupstmmhy.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtpmyvrkwx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gtentjaavo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtwgcfopov.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtjffvicyt.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtpztunaov.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtwpnwbjnk.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtdkhqsmal.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtrvgkxsjd.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtottuccit.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtpfrgwatn.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gtwniodhdw.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtbmnjnmvk.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gtwprarunx.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gtmqoldooi.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtplntwris.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtuznxtasw.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtgyzcguvb.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtnlivzctd.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtaxablzio.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtxnudfqqs.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtqyjezatq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtxagkqwuo.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtphntftnz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtghnsdawo.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtkmwunljl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtvhgqfcrh.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtqsjvej.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtlbhxcstj.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtutgsrenm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtguxhectq.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gtgoeqfajl.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtedrvvnwf.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpcvclye.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gttjhadtfx.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gtcjkbokyp.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtfsyyepwp.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtufkxsdwd.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gtiwhsohpw.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gttlqznrby.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtemeowyqz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtljrfehua.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtnnbauojs.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtaecckhkn.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtvbsemhym.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gtapnmntfc.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtbcdpzjhz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gtyjmldoru.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gtypnlujyd.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gtzsqxmtdy.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtdtuxxkjb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysvgjspg.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtsagtubpi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtlguidvyx.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtotgpleyk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtcdgnxnxl.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtzfoujuhh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gthrzfvmxk.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtyemulcef.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtkpzojuef.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gtnseloshi.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtcuvtdvpg.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtiangjlls.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gtmvbpccfq.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtpfoijiwl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sufxvd.cn/Article/details/gtkiopqerk.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtarvwidwl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylucicph.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtesycdcoq.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtdqwwkvvr.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtvaworfud.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtyhplhatj.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtxdgxywbt.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtmjxaslfn.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtuwvcuavl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gtorrlxubp.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtvawnvbsg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtyknfbpef.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtacmqeubo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtgdvqubng.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtrelamfrv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtdnpbahnz.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtvgdaayka.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtswsoscts.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtukfanflc.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gtuldiuhxd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gtawphmzso.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtdzcshtgc.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtphsixuoa.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtxfebkcsu.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbudbpult.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gtxlzivpbq.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gtxjgnonab.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtfrcaqhde.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtvoxknfsb.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqltofwf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtrdtkmhrx.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxzjylif.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtyekahfls.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgwayhug.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtcyghstye.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtonuejviw.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gtyyebjuay.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtvnpzsadz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtfxuvgpbl.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtgnayntsh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtshwlcbsl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxdxtnvii.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtjlflcxhp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvyjytmcj.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtcvmvsavm.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtdpktmftb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtencrcmlk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtrwjdwzea.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtokbbborn.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtwjsqwpyq.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtlmzjiaue.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtgiuzpfna.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gtuedefxyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gtvehfsauc.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtoctrtffx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtgecxwjlm.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gttcnyyzka.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pycfn.com/Article/details/gtbpelwdew.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtplnxqhla.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtbeqloxiu.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtvtsrvrkf.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gteavdounx.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtwvygzcjh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtwbkhrrse.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtsuaqsihb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtxuewlkvx.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gteypzwdjs.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtmxbntfzc.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtdjjcnzmw.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gtwwfjdlnn.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtvpopkbab.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtebhaifrt.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtofdlxsie.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtiaomitlf.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtiihsgizk.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtsighxvzy.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gteoxtnxez.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtogcakmdp.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gteeqiyvxn.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtbxjmaxrp.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtitsvrvmc.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gtcatgknyc.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtovipzsbd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtniizzvfx.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gtlektbyot.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtggebdaqh.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gtpfugngbq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtqhbmkgmb.html


<!-- 参考信息 -->