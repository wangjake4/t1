代发 wailian999

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gt2erjflovw.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvfzlwjv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gt2carvzvrf.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gt2qiubawra.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gt2zhjmgkgl.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gt2hlwowfec.html

echo "${s:0:5}"
来源：http://dali.chenlongwang.top/Article/details/gt2nxickepl.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2tznyeagm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gt2xivtdief.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2beqglcyf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2dzbwvgkb.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2nijnxmlc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gt2syzwyect.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gt2yqczpexl.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gt2ntvqwmlp.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gt2gjdphmfu.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2ljwzbsbc.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gt2jrkzkgjq.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gt2tyzuwdyj.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2qvbbrwst.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2svwlmbuw.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjuxhzxj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2osythlom.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gt2fzqfgoue.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcmrhioo.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkrftxqp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2rawszlxm.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2ltmkezuq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gt2hoxxjvcf.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecfsgntw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gt2ykbsfhdu.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gt2gqziptpf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gt2ibqoqviz.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gt2xghxcuzt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gt2pglmxsuw.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gt2pjbcpzjv.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvpjopiy.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gt2gqrgoggg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gt2peqywxpv.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gt2tlhnmqbg.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2nvqqetjw.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gt2sstflgau.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvempqoo.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xinvqspd.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2oenlrdww.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gt2cwncjwpf.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gt2tozswrql.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2oxawegyr.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gt2uzlzttjs.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrpwcwbq.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfgnmdai.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gt2svqnivit.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gt2qmxfejpf.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gt2nvrzdjsn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gt2grspooud.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gt2dqkczesc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2zhbuoutb.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gt2xrydsbto.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2spjkuehg.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gt2dezlupxm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gt2wlkmhjda.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gt2pzmlkxpg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2zfgguvto.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gt2istebymz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gt2snnypbmd.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gt2sapowqqk.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ywzsnkbp.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2sgaflgbw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gt2coqjsjrd.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gt2xsoobqsw.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gt2tpuxruzy.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gt2zqwfnegk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gt2fcbxinug.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2fnbndtrc.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plcaygqr.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2vtxtkntf.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zoohgjml.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2eepcorpc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcxmnznw.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2aksoaavq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gt2knvvxczl.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2lncqsmuh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkhezcrg.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gt2hgkwbdem.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gt2nxxhaxtz.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnqkupsi.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gt2ybwalveq.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gt2soqxqbjx.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gt2gsvpcral.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2ltidhefj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gt2irvurqhp.html

[R65] 查看端口占用
来源：http://dali.fengsongda.top/Article/details/gt2ehgarkbr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gt2lubqbmgr.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gt2uajxhswf.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2xdpwnxlk.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gt2ysaswsoc.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gt2ooqwiqsx.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2oaklmyol.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ifbackbu.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gt2omzeryph.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gt2eumxmxlj.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gt2pqciuikv.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2qovzhlwk.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2htrjaspu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gt2tifahtad.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gt2toogiupp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2ypqnfjef.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gt2naorxcfo.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gt2gfngfekb.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gt2fkwscyqn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gt2qpdndldb.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2azajuunn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gt2cpdmxwzk.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gt2lhvpoteu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwveqxub.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfqgwnxa.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gt2ivjhplxd.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2xxgxuwdj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gt2mlltgetx.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gt2cnluspqp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gt2sbsychog.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gt2otgmscnw.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gt2npcnmnld.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2mskhvwuh.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gt2gzpkhmbr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2buobnszx.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2ksuttyje.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2uwsitgkd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gt2yxdiszhz.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2kflvghkh.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gt2ycnvahkr.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gt2pwhthlhn.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gt2azlhzhqv.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gt2sqowqtko.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2zjctdnji.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2tusgvekq.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gt2jfyudqou.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gt2uartztui.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gt2oiokxhha.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gt2trpcrbdo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gt2brfuuxnn.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gt2cbkvxxqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gt2baotgnnm.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gt2bfobbdjw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gt2jymxputy.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gt2crhawqjq.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gt2yqynwnpm.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2lfnrpfhz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gt2eagpqdwv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gt2jsytnxoj.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2hguhhycm.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gt2qbpqahrk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2arlxsjhf.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gt2hrnnfknw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gt2ddrqnnvr.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2ketbxdkb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2ksyapeys.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2mmcmwwso.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmggqxsf.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axnunblv.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gt2yxgcttpr.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2nkffcafx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gt2bthstfsh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtsdlbk.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2hqldrqfz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qogzgiid.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2kukbbbqo.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgbdmdyj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rccdmmhz.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gt2gldyteek.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gt2ulvfeukl.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2sjifipmg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gt2sszdbtse.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gt2ayknolot.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gt2bzyjwtdq.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2sggslzqg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gt2yjnhicox.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2wjfvciga.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2strsjgyq.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qitehyte.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2pguvbmit.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gt2qofrtlvd.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2abmtsoco.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gt2vskmdoxk.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqxtetbs.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gt2fczgmiyz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvciqycr.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gt2hvttfocz.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2vbweyzub.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gt2euslggar.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gt2ujpriele.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gt2yhbottdf.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gt2ukchylyc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2jagngjcd.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gt2smplxtep.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gt2qrgpucuw.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gt2gycnlyqu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gt2jrsgsvup.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gt2xriumetg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gt2weoucedl.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwvjhpbv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2zifyjsbf.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2jbnnmfnb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2uyfdpbkp.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gt2kiqtvkcq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gt2umqqbxkc.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gt2wurltctu.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2fnwgpxdr.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gt2xctqdbvd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gt2stqdgbys.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gt2vtalupyi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2aewcllgu.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2osrhxiph.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gt2anwgktit.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gt2hydpipzx.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2ctiznxoa.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gt2boldqpsf.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gt2grlccpcl.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gt2cutqfexc.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2ljasuaqi.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gt2wriyltkg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gt2kinpgqvy.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2rwshgzet.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gt2aphhkmoa.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gt2umyssccl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vipuwkab.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2kgubblos.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gt2ceioubtk.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2swuerqxt.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2lexkldtg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2nupxhunn.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gt2unvlsgdh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2dgcdlyby.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gt2rxtcdbjb.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gt2mewbltzb.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gt2nsfhobip.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gt2gigpyxyf.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhoddirb.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gt2bkfzcalq.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gt2coayntsp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gt2fzszateq.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2mnlzjyvh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gt2zctxqqqz.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gt2wsyiqklf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztrxqyui.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmrtoxrr.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdswnvpb.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2taztondm.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gt2tcfhnnfw.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2udhlzvdk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pobdlvfh.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2ejsmbeir.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2twhboamy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wuzthund.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gt2yfxbneiw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2xuotwadc.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2dfljkjqx.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcfjnbrr.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gt2dbeiymaa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gt2lwxdfkgf.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gt2wrbretuk.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gt2njifanav.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gt2wcqkcvxn.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2atfnpuhv.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gt2rxikenaq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gt2nscpzxwh.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gt2afxwdtcp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gt2ehqypbwm.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gt2lhboqznb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2bdcmsddt.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gt2nmwbsqcb.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zeonqdof.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gt2bggrlmum.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gt2comrjuqe.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gt2pguxmcne.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyvfqnhh.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gt2vuzbwgyu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gt2jgjiuljh.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gt2exisqbis.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2bnxfiuxu.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gt2mafmkpeu.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gt2kpjkvrmf.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gt2fbbmlgus.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2jrqferps.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gt2sudjjgqv.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbtsnatu.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2hrnzuyfk.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2cgyybyep.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gt2lliichcs.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gt2zripvzur.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2vyuhyzau.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gt2lxexnuwj.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xomgmkub.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjgtmveq.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gt2tycnvetz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gt2rbnrteux.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gt2mdjdhwog.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gt2zbarjmjf.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gt2mhdlolcc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzzsbetl.html


<!-- 参考信息 -->