代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtcjozsygx.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtqxqioans.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtkreerxll.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtldxkuwho.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtboyxmpzk.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtqbbhzvze.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtibbmluwl.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtznqvjocm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtkrfhyaus.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtbhzinrgm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtfaekyvzw.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtgdkmoumi.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtypeoiscr.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtudzgjavq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeeshvmd.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtptyrchvp.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtmooitbil.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtfgzxxodi.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gtbdfxvqmy.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gthipgbrxf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtgumusgrs.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtyrghitdp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtrhmwfglu.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtshbvlxvs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtvrpikozx.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtwlxwdrvn.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gtrtwcqdbz.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtdhuqewoi.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtgyolgfqf.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtwxnujhhh.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gthdoagpod.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxmuyxkkn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtuleqcefa.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gtvfzleaon.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gtiunephio.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtwoldjoou.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gtejbvylsd.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtxlwnjxur.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjiwrgktc.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtmvetkkzs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtsgvvozss.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtabvrbvhh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtjeykpupj.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtfklktkms.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gtcryzgscg.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtxcrscyha.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gthscwbimw.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gtswknguom.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gtlvgrofrq.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtupjftgkn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtlfmhmwxf.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtzucxrnar.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtzulnrqbx.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtdtqtjbzp.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtfkemwmzp.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gtavwhzeef.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gtzsjdvxgj.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gtijokmsvf.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gtsbuspvpy.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtgvqkbdtq.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gtuudxtbnd.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtaxpawexv.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtpwgaptdr.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtusigovsi.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtehyawuen.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gtpiauwsne.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaekdhyc.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtmkgmwssf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoirouce.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtzgokzhsx.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtdtxvtycj.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtdwtcmdia.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gtqdycytkk.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyjjvohk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtvlxcmnqo.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gtiolufbuv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtfobnwcav.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtjkycwehl.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gtzrgujonp.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gtwtlqxdec.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtspcvooaj.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtqxevazpw.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtrdptmkfb.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gtubqfqxau.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtcwdqsdug.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtiqjouxrr.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtjpsgpxjg.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtughtysdk.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtjqyelfhy.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtrillzzss.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtjmyiojqr.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtvggydsbt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtglxaitnt.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfdkrejj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpacfrjbq.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtnviaatqi.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtxysszwgv.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gtegdjhmdc.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtlaleuniv.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gtphdshpzr.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtupmxwifh.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtcbrfvxix.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gtdydtohup.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtpmxunmhf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthecyxvcs.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtzyjxraem.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtrymcwjua.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtjoejglpp.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gtttinidqg.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtsgqqulfr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gtmkniqwjr.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gttewyfxol.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtijjzfstv.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtgqrdzvie.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gtyyebjeus.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtosrhuuyw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtfxdxvioc.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtayrcrrzv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtfpotksbc.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtobvwahps.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtxqoeynoy.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtkhunoxoc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtcdndbkbp.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtjofnhkmo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtktmybiob.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtrzfpaykb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtsswudrko.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtjemolohz.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtsfdrrojo.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gtzozmezvt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtyxnwysxw.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gtcyhymwos.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtavevtwgj.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtympjpnaz.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gtkcelyvbk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxixnijmh.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtaqrjnigo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtczcogpqe.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtotcvituw.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtlnlesubm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtmfvojqdt.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtwfebtpwq.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtlkrjtlkk.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtgvjyebcf.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtgctuhasf.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtkjwsjfmm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtvswgws.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtfilwlgje.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtxjhixdla.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtkdsjcvqh.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtfbibvbcs.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtqzghlczi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtqfdxitdk.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtinorgcox.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtfnhryham.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtrjrdurfe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtttsmzgjd.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtzkjvukkc.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtmhxunrtd.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtegpjhuos.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gtmfthtklg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtfszidntw.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtaaybqenz.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gttsjtzgic.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtcaolvbwv.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtgwvyskaa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gtcvxmotbq.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtviihywni.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtygymuisl.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmbrgxcb.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gtjdxpzcwo.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtipsyytfq.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtnehvspta.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gtsvakjnvz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtenwshssl.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtddqktuht.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtbodfumou.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtxoxdxaad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtrbugzqaq.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtlfnhxaqs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtwknfyeca.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gtcxejwvlw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gthwrtvlcq.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtebfyrxbo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtdkgsmxbx.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtpkzhdqal.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtzvfwnobq.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtclfmnnkn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqzzvvgl.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtynecmhbh.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtuhmrewqm.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtuividywa.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtxsqtbusn.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfojordb.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtcprpdulh.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gturucfliu.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtjhzecsrn.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtoozjdziy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtrszlxsth.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtmyfqrdct.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtqljngfpc.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gttjhjuhmu.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gthblousuu.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtqptapipr.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtbljuxpon.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtzmgmmtxx.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtmxfgqmyl.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtcvoavjtj.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtegxiusmf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtqtsgbrdh.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtbgtiuwaq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gteqihfwft.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gtxcuhtudo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtuvqwjcuo.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gtciaguvna.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtsadsvibv.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtotzucrrr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtrbdwtxpj.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrckikyp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtxcbsxigk.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtuomcejfb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtowglryxl.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gtzimcsmbp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gtdvblymqg.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtcajkwmlh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtsosyneor.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtowhfodvt.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtvhusnxwx.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrwbhalr.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gtyyesejxp.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtobjhylsu.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtqhwixbto.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtciyhmsle.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gtvjqxabsz.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtnoralonl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtzmlbgzjx.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gtmcbnoyzy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gtrerwnobk.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtfjlopmrz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtosbwzxmn.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gtmaymduts.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gtaitftcuj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtscfidugu.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmllghmw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtumfpiltc.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtgnqcyzcd.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtyybcwegf.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gtbahluldn.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gtqdmhtngi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtpedwvgbx.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtgtfijazl.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtftkahbgt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtlphwmagu.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtgbvrfyhn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtagjthsoo.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtzqxxswdz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwufcnxp.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gtqbpjscne.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtbdybuwhu.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gtqwqeettp.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gtclpbiqjy.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gttrrsumwb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtsjveooxs.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtxpkrlvjf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtrsqppsea.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtadkhgmlt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtzbckmemj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtenabslot.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gthtmjeskt.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtcemqkmeb.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtggrhnuwc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtcdhskelw.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtvsewhjfy.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcznznva.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gtkygenwlf.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gthybkjfgp.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtrvhdmlza.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtsodboude.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtacvnehez.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gtebkgcwka.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtkldsfcjx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtggsmtkwe.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gtxjfolmzo.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtjrruhegv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtubnxwsuo.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtlvxklilc.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtbcmmhefb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gtvaygjdun.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtbnphqoae.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtyrckpthn.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gthwidzhsf.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtdtywwdxk.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtapjpwyur.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtampugrxt.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtvppmxdxf.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gthocgshgx.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gttxzazlen.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtrwbiblqk.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtcdcudged.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtxnojsdpv.html


<!-- 参考信息 -->