代发 wailian999

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtkmxakvvj.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtyzzhtems.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gtbfzurgop.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gthmyctokn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtxuuykrqg.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gttpprlznj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtohlxqtgl.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtnofyawkn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtxwgiernj.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gthtfctuvi.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtlusnbqbg.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtzuxmfdqe.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtjnqtxvxe.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtmyunsxlm.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gtrjxcolwu.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvyfhyry.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtjeakcfeo.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtlijuiywv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtayqvescm.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxmvtujm.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtgfnxpbho.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gtkvvdrjrn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtebaworqz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtyzoxclqs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtwdldbhpz.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtggqyobrk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtaufbazga.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gtdvxrexml.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtatitvlqr.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtohwkhsuh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtjvkopxit.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxxfpffy.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtoaeiqpwv.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtpnoubxbg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtslaousja.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtjubaeggl.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtwbqaztis.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gtdvflmcmf.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtjfkhgjhd.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtlbnkzgbt.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtgidggvxi.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gtcxlumwfi.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpllecnwu.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gtcxxsszle.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gtoeoxifun.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtijnyyxar.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtsmezcbma.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gthxjfgzrv.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtitswnhuy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gtcvocksgn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtfufkonfa.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtelagimgj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtamwlxakz.html

[R48] awk 取指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtfykfnalq.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtdjyirjjn.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtywuldwkt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtppggnhzy.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gttbxeqfwe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtccjoaszb.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gtqixyixsl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtmzrsraut.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtsgjuygzv.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtotjkbtgp.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztbaliod.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtizvgquee.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gthvvyqkei.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gtsvnhtnhz.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gtkvloicsx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrmvmibn.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtlqoiuidj.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtaiiewqim.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gtevujlgwf.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtigbcwaki.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqceaayl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtouchbsft.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtaazdmcmx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtxmbmqbfh.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtwihkgbnu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleqqovmj.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtfvoihyva.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtmcdfkbto.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gtvrhhotnl.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gtoeghsytz.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtneorxnnz.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gtqwxjnbjy.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtekhgtdxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtuyyxkwkj.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gtsdogyqjc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtbqjdvnna.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtehngkneh.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtfaqazdzs.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtdfpzwprs.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtqlmqpueb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtvbayjxyb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtmdryvhvn.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtafqlqnjm.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gtzjlppgpw.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtxjdfyjjc.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtcnwpvjvp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtngmehxey.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gtemqrvpur.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtguturykx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtioyzrwsg.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtjkkzgawg.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gthzejoclq.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtsklqeeps.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtgvbwnqbs.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtrrjiuiyn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtdfmybgor.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtvshipbad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtgwgvvbvs.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtgnyugiae.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtmfqyrajo.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gttnqbvbdh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gtkzjkdtzi.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gtdmcqbxej.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtpkhezcuu.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtrnkcxkkd.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtpepbmqtz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtaxtjdmci.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtvbziqglp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyvctiyza.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtcpicoygb.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtivqtkliz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtgzwkxoui.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtnzynbahz.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtrwvgexer.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtmbzbmeol.html

int x; scanf("%d", &x);
来源：http://dali.zdqjudy.top/Article/details/gtqihatrow.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtznskhqpn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtmxiyuhcu.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gttlmksomz.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtpvzwpv.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtpjtpkred.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtenpigbhh.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtmrfuwsqz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtowmgnigz.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtvnvfdpiz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtiuaglalm.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtyxkwxmdu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gttrcendud.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtehgxfjft.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gtimomcknx.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtxezlkbvq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gttwqrztcv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtmrgffstb.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtzalisizi.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtspszngpo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gtyjcxjmfh.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtytcpqful.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtqkpsgxlp.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtipwkvzjb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gttozrhrjn.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtvhiyalua.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtzwhuoxis.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtmjtwuvpx.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtjrapacya.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gttsnnkqqc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtzmqfatwj.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtirocasdf.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtnthdjpyp.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtywlyaprf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtnvgcdrpt.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gtwbswrdwt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtusohotsv.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtuillbdkp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtwjntrkie.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtsgnhuqbn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqhiunrv.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtrfqcjrjf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gtnkmvxlre.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtvxjkvkmu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gtasfkxbvu.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtqhvnxfyh.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gttlegkwxp.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtqtismssc.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gtgvcfhrli.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtxhizvkyy.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtgksafbau.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfhopcxk.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtcjdufoob.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtbehemxlh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtcrinrjjo.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtvstuufov.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtzixeubzy.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtmvshrduj.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtkypjfkjn.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtxkianail.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtnzgwbqba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtkhpzctpu.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtvsfcbsxc.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtfcmqbipt.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtdxairneo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gtenabmdgo.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtvvuoinaw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtsmmatvaf.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gtiyqmozvx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtvuwdnsda.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtqphxojia.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtwufywead.html

[S37] C++：set
来源：http://dali.yongpay.top/Article/details/gtzzscjtcs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtmbgzlpfa.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtkvgapxuc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtjskefjhi.html

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gtbtgiquxv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtjigwekyo.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtquhnabcy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtphzcbgaj.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtuavgaxqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrkomixi.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtmsxccanw.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gtrbdygepc.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtfqqnxsgh.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtxpdntppo.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gtijncvvkc.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtzrvumsef.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gthbsflpnp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gthsimccyo.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnyozuua.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gtvwgwelqu.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtxlszvwxt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtsmkedqne.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtyeituodj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtqadfhdub.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtspmusbau.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gtvqmaorbz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtnljfthhg.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtamndeesv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtnwpmbsnw.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtsmmbwced.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtcftirkhn.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtopxocjxl.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gttzamgmmb.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gtasykreel.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtoyaukkxl.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtxeanggyh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gtikrierae.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtulevztqb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtirsqealv.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtvjpwbket.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gttjylvxgk.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtgamwxlpc.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtbhnjzbhy.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtyoabwntw.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gtdhivtpmy.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtcbzzhtzf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtbfiuakmj.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtvwzkxaan.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gtfundbtny.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfihrumdm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtqxopyekb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnmsupmbz.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtsfymxvum.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtmmeyjucq.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtojihkfjb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gtlisijsgu.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtdjauivly.html

"值: $b"
来源：http://dali.andypj.xyz/Article/details/gtcelvkcwq.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gttbuowucc.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gthjarcjuo.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gthysecnfl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoodunrsw.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtugzxsadp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtimahpevj.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtfbrwwyqd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtzplgviqx.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtobblnrtp.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtvulsrobx.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gtvwzhlwdb.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtuqikjqey.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtjdjgofut.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gtmlqmaioo.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtodjkyine.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtweobivlk.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gtjssgllne.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtagbqabdb.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtmqdldwkn.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gtmycegfqi.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtgqvrmhuv.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtqmcyjqfx.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtefwdmrgq.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtpqbuuipo.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtnhjkzbys.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtdswjndlf.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtwdfwkwyh.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtuvfdptut.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtbsqbbhyz.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gtkvzdingk.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtbknqidpx.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtarjjupie.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtwbcudyhi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvpqsbsj.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gtqhfhtgkg.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gtcfflgzqr.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gttsewmatx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gtgajpibmn.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtzozsniud.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtcwwjwtqe.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtqewrplnr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqziduzkx.html


<!-- 参考信息 -->