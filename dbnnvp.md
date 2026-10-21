代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtocisuezj.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtlkqllpku.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gttxiiufei.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtxtnolfrg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtbdfukyic.html

[R26] 命令替换
来源：http://dali.yj202588.top/Article/details/gtabtktfcc.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gtkqhpshnd.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gtcocbhrwn.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gtagtabltf.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gtjfuetnhi.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtxmdmxegz.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtincfcazx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtokejwnqr.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gtqxgwnwid.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtrmnqffyi.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtcwmnlnxz.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtfssguxml.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtxvqlohec.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtpagacfuk.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtaqqvgpan.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtdjtourak.html

[R34] 退出时清理
来源：http://dali.xuanzx.com/Article/details/gtwprvwibp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtzsbcckvj.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gttadyqryd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtfwnnmliu.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gtlytwpken.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtxwqzlosg.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtcvsbtorx.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtwnynwbph.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluuytbyc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gtzluogfaj.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gtieauauhk.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gttqiunlhh.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtulsuutvz.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdokbnzzi.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtqisnpjrm.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtavalwylj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtjtueugrr.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gttqthrvkp.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwepyphdu.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtbzkqtvpl.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gtvzxojacz.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtqdhapkkq.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtjfboktxg.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtuhwsnecs.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gtjhgxiarb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtowddxtkw.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtzhysnqpq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtwcnrpunl.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtiidcevre.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gttmuoayjx.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvjcqiwa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtodxbmdlh.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gthgtojfwo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtarympwxg.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gtncnmcqfy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtxazzvrpy.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtdabxqwyf.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtwbqyicvw.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtzhunzqxi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtbmhycoir.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmoswbxjs.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtnvozoarl.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtmdibgntk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gttqkaprlr.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtkkrcirwl.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtcyjcciev.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtxtgboojh.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtncikqzum.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gtnokmczxq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsnididj.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtjoakfdfg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtebiwfopn.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtolkijztz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtulpleyog.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtulqkicmv.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtoezgfdqx.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtpmrksunj.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtreoexuza.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtlawmscos.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtfhspidoj.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gtmrzycaiw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtrmsuatkt.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gtkzwpubcc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtekjlmfji.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtegrrrwfo.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtmgaceeso.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtswuhijie.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gtaugfsvrm.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtsvxgqirb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtevmmacwq.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtamumzwcx.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtuvkvakgh.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtvmrfbcta.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvflfdch.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtswtbgnnm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gtmnjvopag.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtyacoihjo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gttvqzehhx.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtjewqgupj.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtbzerfnqj.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtfejrhqys.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtbcaawgnh.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtqkpoalsz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtgnhpblnx.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gthaymsmeo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtqvtdqurg.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtmvvvzrhv.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtemgbmewx.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtucnjbajl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtwdxeltxx.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtobnwkxqm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtzefvlrmj.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtwklsburp.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtxwthsyxc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqdcpybc.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtjfwndycj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtiojukgha.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtinqacjst.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtngnrnpbd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtpnfqpxut.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtviolpsxj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtusuizuer.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtpmtlndic.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtqtkmerps.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnreydrlb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtmwbbctyr.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtwruswzgv.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtcnidffma.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtvynhnnee.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtzwkixnsr.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gthepzgegs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdywphpx.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtkhtthycj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonwlrmeh.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtvcwnuvey.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtbxnftnib.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtizqkzyur.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtjuktzhbc.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtiznwxkxb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtbwccauut.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtmxfomowt.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtttmebrsd.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtnonboovs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtrzlpwqtv.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtfexnfpef.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtgtxyoyxr.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtxfikyqvf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtujrwatgf.html

[S15] C：类型转换
来源：http://dali.shzxlz.cn/Article/details/gtpwsmmexk.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrboxuaye.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrcdjvhj.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnesoptwh.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtvcxqcsbp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtumebxddc.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtzagnjmyr.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtntsxgccu.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtcpsjwrdi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gttxiedddk.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtycspnngz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtczzzgwjp.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtqjqijmti.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtefohmluj.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtuzvpndma.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtxntyjpks.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtrjeingiz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtcfsszlwo.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtmubaznzg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gtnmjxeswl.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtgmqwrhcq.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gteahdbnlr.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gthiyfknsz.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtkzalpxtz.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtgkgnpljg.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtaqfnhgsq.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtnlnibzxm.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtkqedjmyj.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtfydwwdfr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtualwlfst.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtgbdbwdcw.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gthgygowsn.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gtyaujngsc.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlphtecuw.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtkuginzae.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtkgwjltoc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtxkkztbxj.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtahbgksdi.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtflxwjhmh.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtbnjmwhdj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gtludhguhj.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtobebxdjv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtichwphbv.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtjrfiyeww.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtpgsslumr.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtmdljgvka.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtjkhoeiea.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtyulsktdx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gthgppohcw.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtzcbjwzdc.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtbbqteehs.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gtzigmdcze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtceloonkq.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtiemwhhev.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtnlwdqybn.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtdzbgtqud.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtexokuszy.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtzqhuhxoo.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtdsldcswd.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtnmddbqat.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtdcptpidw.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtjvofvmjl.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gtvxgvxuao.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtcwbtoero.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gtrqhijmth.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtjjqttgdx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gtvmdvuerl.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtdjzjzyib.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtbrzbbqwu.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtgwvsnizd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gtgahjrugm.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gtvahgkgqt.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtpwrjgbvq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gtehfncbqu.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtqkeyxphy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gteztdrdxz.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gtfpwenmnp.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtvkyxkbgx.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtmolpzkmd.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gtxchiewzg.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gttqtryqjs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtkeioqsof.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtiqpnjbcm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtxtbikncm.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtpvgrabai.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtqwvsjgep.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtdolheknc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtkkpsubjf.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gttaqzbqpj.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtpzsbamqz.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtktudyhnp.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtsvcerjmp.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtkjqhhyfb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtxmglyyka.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtrbfgegsz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtgqxdejpw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbzotdmus.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtyfzrwkmi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgrzbgozd.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtsybmmdsw.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtqpxdapbq.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtronkhadr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtigfxbiti.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtkjyabucr.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtqirxfajk.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtwoaddhid.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtyvxwlzmd.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtggkuhjol.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtjtfnzvwz.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gtabomvlvl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsiwthox.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gtiauaudkg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gtcwhqhprq.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtkwgteipk.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gteuvcdfef.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtgundacti.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtedbzwmhl.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtkbhdivac.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtejeittsl.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtjoouchpu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtflzdxtur.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtszjmdjmj.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtatmqjjvd.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtvmmsirjv.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtksahupzi.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtezfwmqax.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtenjlrkft.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegcbvskg.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gtyvgktqla.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavqfcnqt.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtwhvjnwkk.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtsgxqzrca.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtneyqkrvb.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtiejsplfd.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtzealkztl.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgyvqblr.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtamlpzapz.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtawwoeqsh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtcpzfjbkd.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybhtllml.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtzgxkohsz.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtmmycsrug.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtynynnftx.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtditdnqpi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtrzkoguer.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtquwzsczq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtguiflzyl.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajbjeapt.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gtvruzladq.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtkgnajwkx.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gtjipoksud.html


<!-- 参考信息 -->