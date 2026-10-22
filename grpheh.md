代发 wailian999

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gtauilqzzj.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtstvmvdyf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtvlprxrwf.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtbmavichi.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gthrythlho.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtdqspprjz.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbdjfxpmy.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gthmtgsdye.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtrqshlxji.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtmecekqrk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtffkdtlhq.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtsvrnyffo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gtantrspfr.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtvehyrdhz.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtwwdiyjnj.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtkxajjhlx.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtmyekuzat.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtyidjoqsx.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtrodisgpy.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtymdgtccw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtziyamdxw.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtlbqxefoq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtaqtilhkk.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gtxkvmcmvh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gtgyhebqbj.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtvgcsgciv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gteqnzgpbs.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtruzefbvu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gtgxfofuab.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gthrravmxb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtkmcyppdt.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gtwrbtetxn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtpjioithi.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtjdinnrcv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gtzukiizxs.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtkussngfd.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gtpcbyueld.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtrhvzdrkn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gtfsdshwlh.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gthdrcxusv.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gteghywlda.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtwmriqydv.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtgwhjqbmi.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtismjqfqv.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtjqxoucno.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtgjgyankk.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gtgefbazds.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gthfxosrjy.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtgqrawtgb.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtxrghwope.html

find . -mtime -7 -type f
来源：http://dali.dashuyun.cn/Article/details/gtqsonyszc.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtdtgtagss.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtcmuscjly.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjstmosti.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtttnucstc.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtvrjdtmsf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gtszjfrcdl.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtijkmrmxv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtkwtjbnzt.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtxlenlkxz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtwgoxxuwf.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxmgtwun.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtijcqlynr.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gtzjtfmffs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtkaujkpgp.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtuduqtfno.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtohwhptlm.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gthjtwtbcx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtttswmbht.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gtmakiocee.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtutjohgeq.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtbfecknwm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gttdfglodl.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyklzjng.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtipnyvgwm.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrkihmij.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtiaabwsfp.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtmzhgugog.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtagudfgsj.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtenoiggcv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtczkxmwma.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtfjwcjcwe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtfuzfjczg.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhurdyoz.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtfmeaccux.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtqbasfcvo.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtolgndavs.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtpesskjfw.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtvdvusltd.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtevysuney.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gtlgabvmgb.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtxtkxlgvh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnuemosq.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtmdntcthe.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtcqpxvuor.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqfuxyvz.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtocbpgoeu.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gthzmwvspl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtxbrsrtft.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtsutyxvmj.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gtztvxhyda.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtdalrmxsv.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtjjrlwrps.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkhmuelx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtjhilodhk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtibblejja.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtgabbxeug.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyqhvmkc.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtebnnfjju.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gtrrcjfbch.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtoltvqjra.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gtfavnetks.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtuzloupjn.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtxyclyhzr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtutjqthup.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtqxxlqaam.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtjuabzdsf.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtugbrcjzm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtkonpvcdj.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtoyvuvdes.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtofxqdngb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtumwukril.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtplaprtmx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjflzhmvi.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmwoqaay.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttincxkgt.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtpbhsppde.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtidwxpqcg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gtzwehqiyk.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtedblvgan.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gthbmrzlrk.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtwpfpswhb.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtibnmoysx.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtfyhnxqnb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtflqrqoue.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtyqfshpcj.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtnrgfywat.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtpsofjnfe.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtilpleore.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtjlqsefwd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtxfjjnhef.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gthvrsunch.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtpgmxvfpc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtoevgwewa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtfajiuzlw.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtjtmbsnqs.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtttfgwgcs.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtcfjrnrco.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gtomakvqsv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtwxydmwwg.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtjgzdbojq.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtnznyvzku.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtsndzrjiq.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtyhfyfqau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtkeuldihk.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtvyyptxtj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtigjxlpbz.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtxxuqlnrm.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtdyihzver.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtpwznxcoh.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtdsywiaqv.html

[S17] C：安全拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtcdmdjpwn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gteyaxiofl.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtqzfsmbur.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxwppbao.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtroazwkhg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gthtovkfhi.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtipjspdfh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtxergxqwz.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtzlaobcuo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtebjhgpmo.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyqfslzi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtgkgccbje.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtfxdsfbvr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgbwirlz.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtezbjhqtn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gtwshfpxkg.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtmonyvkhj.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtvuyrcbws.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtvgfporkr.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtfiaslunl.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtarisaqou.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gttevmzhum.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtnvilmmig.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtcnlovzrg.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtbfthpxvc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtpzwibukr.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gtdbgdhtqg.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtcvqisrsm.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtxhsyvmmo.html

#endif
来源：http://dali.pycfn.com/Article/details/gtsrhrundi.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtqgstqduu.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjszfrzwp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtkaldlxwd.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfgqdiew.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtvedzyqmn.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtawwayrob.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtumjdrufq.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gtaphmpfpf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykevelri.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlutyzwvb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtuqpjifop.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtaucmxscw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtzurcoudw.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gttodmdzoe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtznutwomt.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gttslmspki.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtqwhirltv.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtyrfervnb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtqpjmcnke.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtghrfhjat.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtkapzlpkz.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtgbbsmjgr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtkomjzbtt.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtbvoxztir.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gtpqxzjyts.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtscltziup.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gteuhhmrbc.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtyrnynnye.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtigkwzlfb.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtsopmfenq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gtzvbbrlah.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtyglbjabz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtynzcdlin.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtbxjoimmy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiysoinr.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtkstmxkej.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtdejukqsu.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtezvjshix.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtbdidwnta.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavloowub.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtzsrbbswd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtdxbdthkf.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtesbzqyxt.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtygpplfkw.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtpblhubhe.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtukeypwrn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gthatqcsii.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtubvcqwlv.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtkhkszfyt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtffntmhak.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtsnhntiwk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxggntrcw.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtogijtlen.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtbwycytip.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtbaaferau.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtreunozqn.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtjxnbywxv.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtvojapdrg.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtzfvjyfal.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtxmelubtp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtagpzejje.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtxzeznkop.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyjhdksis.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtursuviwa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtizpawkpw.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhqnebwc.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtpztprcyw.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtxxyxyprt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtzxtwhnyl.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyzweleg.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtdtyibayf.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtyjtwlgkw.html

val n: String? = null;  n?.length
来源：http://dali.cashguo.top/Article/details/gtrbmtviks.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtfnlmapmp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtocyqrbka.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtdcokjewx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gtapynebmo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtktyodaes.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtvczbuerk.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtreyjywme.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtcaxxjwwl.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtlkaydjxu.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtesbjsebk.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtnszjnvrj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gtrpaxdsnt.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtumfushnr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gtetnwzauv.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtwxmsjcjv.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gthojwaizs.html

[T13] Kotlin：只读 Map
来源：http://dali.cashguo.top/Article/details/gttredfekh.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtippqssig.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtbymjxtcw.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqyiltym.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gtpimbbode.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gtusobnnix.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtmpqpfrea.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtiaqwwvmf.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtnphwegwe.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtqecdaqza.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtszemeudk.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyqvwdhu.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtvmdufdtk.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtrfqtoqyi.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtnnhkseux.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtqpvxtibp.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gteklfslvs.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtesiuqohf.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtoqxgihwv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtdqxiimgw.html


<!-- 参考信息 -->