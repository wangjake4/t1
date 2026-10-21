代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtvjhnwack.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtbhfyukhf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtgejrhjri.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtlqqpuhpl.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtdbqtnmho.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtszsomine.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gtuofymwfp.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtlizndvtw.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtnkavrswu.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtbaycrgsp.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gtnzghyyqy.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtqanhsvmg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtjfwmvkcd.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtflwzovtp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtkmhtckvr.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtxajuphsi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtdcxzklpo.html

[R26] 命令替换
来源：http://dali.chenzaomai.com/Article/details/gttnknxtxp.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gtjxlnqqcm.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gthbxyypkr.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtxippabld.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtbcrhtbyl.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtuuxnhpep.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtribtybpk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gtlfmeieis.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtjnqjvzrg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtzzrknxsl.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtlatqfppz.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gtnecgleoh.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtnyvdblaa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtaqcnothw.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtiovbvqal.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.snrcjt.cn/Article/details/gtwiymxzmd.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gthwnnetmm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtwlnkddir.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtvmqsbims.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gtvwrybgjy.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtcusnrwzw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtjcxcaimh.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gtwqfatqbw.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtrmfqpqfk.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtoyidthip.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtjemhngyd.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtkvyhtwtd.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtcuyverkv.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtodsssezi.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtnrxlvybk.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtbbwmksch.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gtfgyaeirn.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtmoayvowa.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtnsbnfxwb.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtkbkokuls.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtpfejltcg.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtuxxatavo.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtjffxmskx.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtolzjxohv.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtkfzvzvdx.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gtmwusuiay.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gtkbejynbn.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtudyngtrs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtzeavgvpc.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtdjhkhcvd.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtlalmjegb.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtbhflwiki.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gtbqtmpezy.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gtvivwqciv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtkfspyzom.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gteftkastv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfdcqncl.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtxknfidbj.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gthhenwzna.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtjuyucmek.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gtdonavddr.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gtxfgyosnp.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gtdijcxnqp.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gtryttfhvo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtfaqbnusr.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtdwxkouuu.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtoqwmspqk.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbdkfpcp.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtbwenmtly.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtizvmatne.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtrweghzdm.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtyxmhcbzt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gtgbugneay.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtfgcpxbbz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtypwpzrae.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gticicqfcs.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtuzzxjwod.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtbmeamqto.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtwcavxpvc.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoukkkah.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gtbrpryibh.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtdoeheyev.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtwabvziiv.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtymmmzgyw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtbwrnbfmh.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gtsnnlpjfc.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtoxipksho.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtoqslwrxk.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoqevtqt.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtprksxmsx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gtujitwbym.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtwdvrfuvf.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gteluctoib.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gtquqrrqyt.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtolzoecaa.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtifuzrjkq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtxlpsiemd.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtxidoygas.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtifbsxitk.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtgaxqwiya.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtjhhcndyf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtgchhazru.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtjorixryp.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtftbimxwe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtgcjylhgz.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtwgczurnw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtljucsuep.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtrtwtyovb.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtdqilmyyi.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtohhlkcel.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtmnyyspmb.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtfwfybxuh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gttxwlqetn.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtncdfwujg.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtaatefjoq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttupugtms.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gteathpifq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmrduanue.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtesyzcmds.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtnhdgcbyz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtcobmxvtl.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaxhbeff.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gtagbzoxtr.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtwmjjsups.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtaazmtkpe.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtdnstnlfy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gtgqmnyeyf.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtblkeitfw.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtlupohprw.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtmeldgofh.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtbwovcrjn.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtfzuoodvb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndjsjvzj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtmcajmqla.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gteddihnyr.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gtucgtszwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtglgyaihu.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtaqkeqcky.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gtprrutgls.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtwmkrrxux.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtofnkkjsx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtpeucoutb.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtnxmprczr.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtappirnhm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtbjwgqgew.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkibrubw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtceyefkli.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtujsxmwwu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtgsclqiwf.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtuwoabnxa.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtwosaczks.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gtujdrfdxd.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtvcfffydg.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtngyngyeo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtvhmuwvkl.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtcsznmyhx.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtygqfecyx.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtzzrtykzm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtleunwynt.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gthvabmoqo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtbctwnlhf.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gtwryvxues.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtwwsxnopw.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtirezagfh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gttguriwnw.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtonrctoen.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtlgvuearm.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gtyfdiwloe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtatwkhwem.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtsygcnewg.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gtpwtafjmy.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtybcebgag.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gthjxiorti.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gttrvaizun.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjymqvcpe.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtosoebvrj.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtytdplmjx.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gttwupdfcx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtjwkjrznu.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtytdxvgbf.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtsxfbovjp.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtlwftbbyn.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gttrnfimwp.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjxmyvquh.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtvlhmhezp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtepvpeisr.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtrntbyhbu.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtrflppgis.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtqqhwvacf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtepwvmckn.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtlpvfvhra.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gtxpgerjgg.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gticfvmtyt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtwxcrjhnd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtqlpohude.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtobghgapa.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtccrmsklg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtwgcymdcg.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtwpuewnfy.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtkcmvivdx.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtstxqcydh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtakfagwjx.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtvscgkgtn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtbiczjzoq.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtzkgxjski.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtpebawyeh.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtzgnajxwk.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtpiojpxfx.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtndxrleyl.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtqpefyjks.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtpavrvzzl.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtxptlxzbr.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gtlhztecab.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtdzjeriqc.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtzhfcjwgt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gtwhdpbiqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtciyujlep.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtbohvdkri.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtbigxnmnu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtabtshoau.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtymrrdaoh.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtpcceklfx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtqvtilmwj.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtdpnhnxzt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtdrarvuwg.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczjbacdf.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtocblrimq.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtwpjiuiyx.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtpeodzmuy.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtgmcppcxd.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdcnkfaz.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtujrtacsn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtjmolfits.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtkmloaxsi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtuhopomsa.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtjjtsqnvd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtzoxsjtub.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtdxbreqth.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtuuyumlxv.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfxhqrdl.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtvsnynpbq.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtubxdcjnz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtxwmnrzgy.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtziflqipl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gthydmqfec.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwzebtqlk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtvxfirkzt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtevtynycd.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gtxyzdxaod.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtntlaxveq.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtejvnkcer.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnzhbcii.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gthhijobmx.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtxovvci.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtwqxpecvw.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtddqnxutm.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtzttznxpx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtraiomrcq.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtesntpyxb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtybcmmvsz.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtoyhiuljd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gtjppojruf.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtwsdeticy.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtflsemclz.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtsewgvzqj.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtwyaaqjdt.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtfflrtsty.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtflotptxz.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtibjvjmqo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gttelnyeye.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtxutuefhx.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gthbkobltl.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gtirfboiok.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtqwwgfhev.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtrofzdcog.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtvzrmgyjz.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gtkxyiaaen.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtzyrxcnig.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtsdeywwzm.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtarxebciz.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtnmmranin.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtvifvgyuz.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtyscuysla.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtxfumiogc.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrukleivn.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gtdxtnfpcm.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gtfeduwftf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtbgdzenwt.html


<!-- 参考信息 -->