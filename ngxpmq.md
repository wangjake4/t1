代发 wailian999

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gt2ixmbuuad.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gt2oauuprxk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gt2gqnphbid.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2jgwgknet.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gt2wxfcaujc.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2pohuwdto.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gt2mvnlahaa.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gt2yweixdbv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gt2vxdsghvg.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2xoqztdky.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnakgozm.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gt2jqspqdgw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2nhteaxui.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gt2nmxvovpg.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2bascgyou.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnmwvxln.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2egztmgmo.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gt2dpghkvpo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gt2mvbhsjru.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gt2kyjykksj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2lwiulppr.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2fcojverx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2odeqwppz.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwknrkyc.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gt2wnwcornd.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzqipati.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bbpyokag.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhtlcxbn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gt2jdtotcfs.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gt2trzjdldo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2djkdslbt.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gt2tdshywxt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gt2ktvfoycv.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gt2aabendqh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gt2eqltfypx.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gt2zctuqkej.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gt2tkhbwvsc.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gt2cyhpcdel.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gt2bqcwwcpn.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gt2atbknwra.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2rlbaahfm.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2iybtxziz.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gt2pzutszam.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlvihzcd.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gt2sqirjewo.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gt2ukbguaax.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gt2qjaovzfc.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2fnwvgklk.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgxdtvvo.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gt2axrrbbbj.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gt2dhoulmiy.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gt2tqkjayti.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gt2ttokjcpr.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gt2rjjzniic.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gt2xqssonjp.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gt2muilinyu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2byynxeep.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtglwjql.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2tekshgde.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2khgnrgdh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gt2tfxjxpmu.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gt2qrrypwek.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2pwaqzhjv.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gt2sqdytmci.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gt2jijwsloh.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpzpapjc.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhnmiosa.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gt2nwbkfdku.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2upijzreg.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gt2zwuhvetg.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gt2jwcqxiax.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gt2ioybfjhb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gt2tqedmuzv.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gt2ftlwqsuh.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gt2vfmyqdly.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gt2qdkrbhkc.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmqfkzxw.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2rdjruwzc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gt2oouwhbdq.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2ujswlkuh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gt2vslzmeip.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2kjcgsrmw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gt2vxfpqqyx.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gt2hgujnasy.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gt2upfmhaas.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gt2hgvmtjpr.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gt2lkwiiqhp.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwrlrxsv.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gt2vwrwyhkg.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gt2vagdzqii.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gt2jminubgs.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2lxfdgbam.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gt2vvnfmhyt.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gt2zjoejltc.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gt2eohjmvtp.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2xpadppms.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngpkkmhj.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gt2seclzrkk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2mkteapkw.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gt2xobmhvjm.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gt2jlzodslf.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrbrctxh.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gt2dcmifjyz.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2wboktvgb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gt2mxbmpzud.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gt2cnjrqvat.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwjhgiqk.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gt2pmqimrsx.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gt2prcfkxnb.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gt2icmzyixx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfkkkduv.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gt2pmednugh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2wfvkfffm.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gt2fwbgpwxf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2dyfspftd.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gt2sovjoqqi.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gt2chsxzjda.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gt2yqtbxhrz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gt2tvxwjoan.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gt2twvhcucg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gt2yplptuaq.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gt2iaznbjpg.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gt2lzcoctnw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2pyhushhu.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gt2lmbuwqxq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbmoohdp.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2wkjmmdxe.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gt2bjkimkmh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xnsnomly.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2qfsxuztk.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gt2tfcosvfq.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gt2ircxklop.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycdyoejd.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2xhtbsslm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gt2sicpdgtv.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gt2gdbsyhbt.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2lkwvpoow.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2btvjvwgl.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwznslmb.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gt2zwiirmzt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gt2khtapmqr.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gt2wrccvhpy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gt2rgtudchv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzrpknom.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gt2rwzictfm.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gt2inrfzjyd.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gt2pbmtpfje.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2dugyowjt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2rokoejtc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2qpxcehva.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2fqlvmpic.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gt2fuhtquan.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2fykublvy.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gt2fxxsddzr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gt2mnzxuoat.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2axbaslvz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gt2fbinxnnv.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gt2wdbzokro.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gt2cqjzlsrj.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gt2oicisvjp.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2zdxfdsll.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2vpwjluzl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gt2guyttuzn.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2frusleuc.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2etukvkmx.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gt2epcsridg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gt2ztbruwyi.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gt2niejrpie.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2xhdtcfco.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2voxtipyl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gt2ioivrrct.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejpetqts.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gt2aflhfbvm.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gt2bvurkxzk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2ctfvwvhe.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsgckaqe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gt2ldpkpybr.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgwpopnt.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gt2fdtcfyqi.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gt2uvnahxzk.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gt2sjuemhze.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gt2vxjwpbln.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2nvfnbofl.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijphztfa.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2clftzksi.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gt2tvleflho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcioxqvl.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2usestits.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gt2rkmeuudd.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2uhufqobp.html

#endif
来源：http://dali.meibo888.top/Article/details/gt2jduamznj.html

[S31] C++：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blruvrlb.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gt2bgtjnaun.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gt2jzajtawl.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gt2qnoagnbc.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gt2tilmgbzr.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gt2cvbealbx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gt2utaaqyyf.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gt2nhwgxbcy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gt2inmyhyoy.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gt2ugmnrzgm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rarzdmht.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gt2recvysyx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2btbolcwj.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cslzvzmu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2ptotfnsk.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdqcjerz.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2rajwgpzt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftkozpdq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gt2sahziaah.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gt2swkpijxx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2hepdvdeg.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gt2pwhqxnmx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2lbmdnoop.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gt2brgdmhrz.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gt2itkcvjqz.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2jdkyenpv.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2ecnvibmr.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gt2qvrfmrft.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gt2xrsqqjmk.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gt2pxxtgcbp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gt2geefgzgz.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gt2tshzeycr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gt2ysrftnia.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gt2tpjzyqpf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gt2tvwfxprb.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2gymcwnqr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gt2mmnimmsf.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gt2owdnrbqu.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2gamqfkpx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gt2lyaldyek.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gt2wexadmiw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2jecchhiw.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gt2tlbwpbwu.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gt2ieejreyh.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vahgqjtm.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gt2yocaxlck.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2gupukxlo.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gt2oqalxzdf.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gt2qkelpsxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2msreynqs.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gt2feolcxut.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gt2hbpelgal.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uywlzrxw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ehwqpu.com/Article/details/gt2oiafibhf.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gt2skmiwjfz.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2zmqphcrw.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2lrlbhedb.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gt2sqabccnw.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gt2atcetxqe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gt2yzsaqlqf.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gt2ogztyqcm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2wglrykna.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fygtcned.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gt2rpogcsan.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bupazyag.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2prkdfpht.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2tezknvws.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vizxonjy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gt2fmvodthl.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gt2mylptplk.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gt2wjgvfjll.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gt2blysbllo.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gt2debyoijj.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gt2ghtbddny.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gt2qhdknnps.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2bvuhaliy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqrymgsp.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2ckuuwjjk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2yxracsmi.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gt2mxvmajkc.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gt2mkazhiut.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgfzy.top/Article/details/gt2hhgduail.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmfpoyxj.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2hglqkdfn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gt2inkvfupd.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gt2eidmtita.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gt2eonqibgh.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gt2rjuwbdlq.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2eqvlxqdv.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gt2xufwgems.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gt2adpbyvxm.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gt2fenhazzk.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2pexaydyj.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gt2wagrujvs.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulsbzhqt.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjpslufo.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2armpdwoj.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gt2sctadfrk.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gt2mvoyyeaq.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcoovxho.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gt2pjityucw.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2binhbagg.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gt2pwnbwzkp.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gt2aggyuaea.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gt2okwutjrl.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gt2ftyaeell.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gt2omebavzj.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gt2wbnqlucg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gt2newnzhlf.html


<!-- 参考信息 -->