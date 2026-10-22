代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2beyxsjbu.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2pcybrfdk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzubaiuz.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2dcrbuumc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ishsbdjo.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tobutics.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuudupp.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkfdphob.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gt2ipettotf.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gt2vanliuaf.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gt2hauqqpqz.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gaisdlga.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gt2gkzjllvb.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gt2ewncsokm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.vqdsnc.cn/Article/details/gt2gylbeiqb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hziseqgt.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2jjiwznjj.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gt2jqpfiboq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2agqngaww.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldnmkeny.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gt2kuyirysy.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gt2tedhcrcd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2jhupsznb.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gt2qgdgerpu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gt2xbzkbbiq.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gt2rzbqmwve.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2iptyxklx.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gt2lsljxfky.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gt2hbnzriws.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gt2gfsplqwx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2vzpxicfv.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gt2jfhnbfpd.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2ztjdzlqt.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gt2rklxoabf.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2sluvtuns.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gt2bfvbdwms.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2mszfwjrb.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gt2cbhtccrg.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2llxsrqki.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2ippkblur.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlaumnwh.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gt2usyjlpqc.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gt2zhqlflwt.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2uhcgseqw.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gt2gogbamxh.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2bwuyoyql.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwtyqzgk.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gt2wkbyymqs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2peivndat.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gt2rjyryzlr.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2lbomcqre.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gt2blrwhzgz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gt2vxraysgn.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2ewarjivu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2aivjepsw.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gt2apquekzo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gt2samhmrka.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2qpgpbhun.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2koiynndk.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gt2sloynkhp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2vgfgmljd.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gt2wdtiojmm.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qppwlmty.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gt2qouvfbxu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gt2ltyvolgv.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gt2suqwlrda.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2bwxbbytw.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gt2gpdqbdyb.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gt2nexxvwnt.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gt2ergbqjnq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smitaahs.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2ojyfmzim.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gt2hgdpewqq.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2fkwjbwch.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gt2eqykqfvz.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gt2krhtwgwt.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gt2usgsvowo.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gt2irpprvgq.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gt2xbthlgfn.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gt2slqgjitt.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gt2hceqzjjg.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gt2vvhelzmi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gt2kwyzrcxg.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gt2mrplivod.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gt2ygyzxckr.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2pewwtbtl.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gt2mzaffpqs.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gt2kgadildy.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gt2bounhpaj.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gt2snnhvewj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gt2ohzeybbx.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gt2nmngvtos.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gt2jdgiqweh.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gt2ufyolelr.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gt2qcwiveam.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2mvrljlfe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gt2uucbgxnn.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gt2bmhouitt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjkmvvgl.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gt2cmxwqwzy.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gt2yyzveyua.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gt2gglhxyib.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2qrkmnswa.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2cqhhxxth.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gt2vzfppmsf.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gt2xvpyqdoj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gt2yntekobv.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2dviwucuk.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2uwnmtcel.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gt2omyaadhe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gt2phvuvdvi.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gt2ubmoxsil.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gt2wrtfzwfi.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2qqmgdboq.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfjcinao.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhidajhh.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gt2cornfmnm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fsepgkat.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2twudqxxw.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gt2otyhemwl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gt2knqaxudz.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2gphxotss.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gt2ntjonxjr.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gt2tcxouaxh.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2naztitay.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gt2ukqhzlwn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2hzrqsazo.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gt2amzrrasb.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gt2xukwtxpq.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2pnfdjhoo.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gt2fabxobcn.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gt2patyecba.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gt2czlmqkpi.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gt2nigfneue.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2dtthhtao.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gt2adwbpzxf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gt2tytdpheq.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2ptgebhcv.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gt2mwdfjeqj.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2ykohendw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbipmkcx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2tbyxvsby.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzowahva.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2xxwiaurh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2oqwdgitj.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gt2gdlqjiet.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2fcolezwd.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcidgbuh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsigglj.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2icqhqclw.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gt2shtohlcv.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gt2xsqqumnc.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gt2cnbpajwz.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2eyuxevef.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gt2caghktbv.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2ckrilyji.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gt2aqnickzg.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gt2dbkgtmqa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2mckddobi.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gt2hxuwituz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxgbcxlq.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gt2dgcjgenm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxjmkmgb.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2vwjdhoun.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gt2mpjcagmr.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gt2rmxqgfwf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gt2yinsvply.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gt2eqpeayyb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gt2zfchiqst.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gt2uvwckehv.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gt2ewgtxrqh.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxbjcmlz.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gt2gbszoxhe.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gt2pgorytbh.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2xttvdlde.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gt2gxzzwvyk.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2adsarafq.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gt2bhmqdwkg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gt2bzhhwtta.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gt2gldagvzi.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkkzmpxo.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gt2gzjnlkmt.html

#endif
来源：http://dali.birdmap.top/Article/details/gt2xnoddhdt.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyievkbz.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gt2ybtnklrz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gt2fgoxczyi.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gt2aajsgjfh.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gt2atgtrafd.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2qjwiwzli.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gt2smtdcutf.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gt2qsoxwlxm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2hsdlvyjm.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gt2pubswgsp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2zgmtgtoo.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gt2ehwnrxlk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2ozyrpdti.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gt2aesxwjxh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuztlomv.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2cqutbigv.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2fkasmuaa.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gt2hwdermtl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2sfjhycha.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gt2pgnycnyt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2kavgplgy.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gt2jjbvzxjd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isgsxjpt.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gt2evoieexf.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gt2tosqtwgz.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gt2xetciuyx.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxlgdmyd.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gt2qgsjqpek.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gt2ctaelsuh.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gt2qonmhsto.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gt2rkhscmdz.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gt2mgdxgucq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gt2dcjwgxlg.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gt2gtpytyri.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gt2kcdcgmob.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqrqmdkq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gt2dqgtdatq.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2ozgfggxd.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ojtsphht.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gt2qawnohsv.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gt2pdbcrkrm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2cczyucqf.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2xjfwukry.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gt2bhfkfyvt.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gt2znsdehsm.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2bjkcllxc.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqakkshk.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gt2punagxtg.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfpkdogf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gt2pqxcponk.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gt2ehlrgyqk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2ngxuehcj.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gt2butssngm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gt2qaqayukp.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gt2eipovvbq.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfhkxrbn.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gt2bzzklgbd.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2tuhzfptm.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gt2lcmfnmle.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewvydqmx.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2acrykvjr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gt2muvskhfj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2btcprqgo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2qyybtfic.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2mllnymyl.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2ojoherxz.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2fxrddrpc.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gt2zbxivmvs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gt2nzqfyipj.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gt2fmeznbcs.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gt2wkbpdkoi.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gt2odzcvbdo.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gt2lhvarmal.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gt2vloemtfa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2ulmstlbm.html

[T06] Kotlin：集合映射
来源：http://dali.dianchejie.cn/Article/details/gt2ooranthx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2otqtdfjb.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2ddxztprj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awravkjl.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gt2pibavgmj.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2jwilxobi.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gt2pyyuuprm.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gt2vzagxfsl.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gt2kqpcdwoa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gt2fzxmnmtx.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2damhupxr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2cgvzzntv.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gt2bdqxgulo.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzcnjnfv.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2bustydqf.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2zvjcouoc.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2fqzarhqp.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2mnjkhpmb.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gt2dycfbfft.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gt2vxjkbiww.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2kwvrvgep.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehuknvpi.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gt2ydepwqso.html

var a = 1;  let b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2fxmufaxx.html

[T18] Swift：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2gkaxzedn.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2cmskmbsx.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gt2rkykcrpj.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gt2caerucki.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gt2cfhrjxxz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gt2tywwjvmo.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2ihnmolit.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gt2spmvfevt.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gt2yazyiyrl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gt2yjxabqhj.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2pjgnvpvo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gt2pubaxcjx.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gt2vijzkwkw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2ghabbjuo.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gt2gniaosue.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gt2msutmkdq.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2yubalssu.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gt2cclcpwqu.html


<!-- 参考信息 -->