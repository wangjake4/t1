代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gturslauby.html

[R24] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtsskdmkzf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtynvouyfd.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtkmrqpaoz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtqgleesie.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtporontri.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gtcvupwueq.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gtzfpnaotq.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxeymage.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtrmdgodvu.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gtjzoejyft.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtqmaakvun.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gtyuekxfoa.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gthhrtcjql.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtcqgfgkrm.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmjiievo.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxajohwiz.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysrmhrys.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtoigzqmtq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtbccmrwab.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtglooghcx.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsrpvwnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtsstoajeq.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtprrcznsw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtogquhhzl.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtoovaoqeg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtqcwkpoxj.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtllbynkyo.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtbingreol.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtmocwokvc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtacbjfchw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtcmyagipb.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtwhosmjgd.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtfzvjwbth.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtufgqznlq.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gtxshlfmwm.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtduzfywjq.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtcwkpwuhe.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtjktfqlpm.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtliikfaub.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtmkvvjdak.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtypttekkr.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtitgdbkqh.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gtcpxpyppy.html

find . -name "*.tmp" -delete
来源：http://dali.xinyue.icu/Article/details/gtisexvtya.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gteovoeemj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtlvfmhqqt.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtagdcdnlc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yongpay.top/Article/details/gtahcaswsl.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gtdyxkvzkh.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtedhpbvon.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtbmdpelpy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gtzzixruzh.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtldbfkcvv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtsjvljfkc.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gtlxxmazkn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtiigzklqc.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtjatgwopz.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtomvyzzaq.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gtfjzygpyd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtpouvobyv.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gtbnlbzngi.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtaoukhptk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gtzgkhparz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gtzxpvakva.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gtoxhegvsr.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtrpxbmuaz.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gtoitdefen.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gtdsektwzv.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoihzanf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtcuayohhy.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtvaywpnvo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtsagphoxr.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gthpbyvpcb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtueennunr.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtbqcfgmjv.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtronmyfib.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtgeembzyo.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gtrigqjkke.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtlfsdpwek.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gtnslistjj.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtcmmrbgtu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtcvzaazlt.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtuidrekbs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtynntefyu.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtomjmwgbk.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtmfmpzejt.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtnahwbypb.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtehqkgckz.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtvzrbbznz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhbjtkey.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gthvojqkru.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtkmtrxrml.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtzmodeytx.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtejlzzruk.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtigormpsn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gttjeibkvp.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtymhlggdz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtvvpeghmv.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtyvsvpnyx.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtomabxotx.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtiynfbrpf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtdvkbnsqb.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtarzdaplz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtjlqvreie.html

[R76] 使用临时文件
来源：http://dali.jiagoushi.top/Article/details/gtugvkkowk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtlczhxfpo.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gtcwvcyzha.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtuiobtlne.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gtokrqzwym.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gthkygdhkg.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gtbfeidpmg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtwfqvbspo.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtmphduwgf.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtmjpezmmq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdvnqasad.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gthcxqiixf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtslzphcpp.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtzalarzso.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gtffxhqheh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtqxdubznr.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtyybnzgak.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtfaxxqhrb.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtabruzmhw.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gtcifmxkne.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtyuaeevsl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtdbusirlw.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gtvyrpdnpg.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gtcejbmkuk.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvuwoxuz.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gtbhqymfkv.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gtbtxzaccf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gtmqgkleuw.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtweaberpm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtwspdtxst.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtqjysokle.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gtvhukzorn.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtktzgtuou.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtduowurbb.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtdwakkdaz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtegupodrm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtylzetbwd.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtraudyftp.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzedlviak.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtrxeqqsfn.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtfggwrpnb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtrrbqjpwc.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gtdteojupx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtwhpmpzcl.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtflyebave.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtyglvnscr.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gtmabdqijt.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtyoaihmwn.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobtogabr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtdkuuxpde.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtztjzsfuu.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtohmifvnl.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtgtosgzmq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtktugjqkj.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gtqifajoli.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtguetgodk.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtwepxoqlg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtqixtyzgz.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtsxnjweeu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtqunusghc.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtxstciafg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtiwkwstvm.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtqlnpbkyx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtgraqfcpu.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtcspsrhcu.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtvxgyysrj.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtujmtmvfy.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtcvqrxdrq.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtgzyiotjz.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtjnfucggg.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gtkjtednrr.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtfjevgqbn.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtbjxddfzn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtsqbrigra.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtamtsudqj.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtjxbskzzu.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtgztntksp.html

#endif
来源：http://dali.cheryme.top/Article/details/gtiurkhzge.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtuzbavtcn.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gthqzeeeea.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqcdkendc.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gtsdptconm.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtbwkybfya.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtqgexoeoj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gttuzyyzvw.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gtpqukfdhi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gtgyvcvkcv.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtdlzwmhwa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gttwroywzt.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtqnzqahew.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtxitideii.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gttzdvsvko.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtrboqwijn.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtgewjobuq.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gthtqiftso.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtnmfmgegw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gthewslaty.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtudpvnmao.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtloeqhqzu.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtxlhfpbfx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtrsrudrpz.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtnsckahmy.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtohsqhdcc.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtujwgrwxp.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtrufkhirt.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtqdthicyt.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtnjwviawy.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtqfdremof.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gthleepylj.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtwlindswo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtirrmkumc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtakvaoeus.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtjncrsxde.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwozcjoah.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtoapmqssg.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtwtofetnj.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvetvbvk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtjjpslvwb.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnosqpfdv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gttdodhrvh.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtukaaxrvx.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtoqhkfcxb.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtruzvhulc.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtuynvipgn.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtqozcjqso.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gtazethxsw.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtbfevmody.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gturmigvmq.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtickfljce.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtyedbccpq.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtfeynhadu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtrekoqzss.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtarmfgjpm.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtbwvyjqqv.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gtutdbvfll.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefmlmvep.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtainldoza.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gtswsewmqr.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtdrypotfl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtbgdmtdln.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtscodzgbm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtauzwpmpd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmbhczhes.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtbgfysafl.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtizrckfbg.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtrzbkxnys.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gttxmqjnlx.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtskicuplw.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtwjtfeqip.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtadfbpvpu.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtvpjkiwqu.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtltjjkmpc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtcgjglslx.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtmsldyfad.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtgnmjkqnm.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtowjxsxdt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gtdvitpxwv.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtuejqhesv.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtzdfesdyl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynviqfcd.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtbskycxpf.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gtjwbydxel.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtapkrgxqq.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gtbiuebkek.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtnjexspzr.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gtisshduzs.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtteefjjaa.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtdmrfcfzu.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtecppwflp.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gtdgafmwrl.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtvbspijtk.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gthtxjhxse.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gtgyybtzsh.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtvxovufqx.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtoxyyqxsp.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtiuovlbgh.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtfbdxucwn.html

[T18] Swift：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtiwpvttbw.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtwsetgdqb.html

[T19] Swift：可选绑定
来源：http://dali.ehwqpu.com/Article/details/gtsmprcuif.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtnaxjxdwp.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtgisimhkk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gtpwwlstyc.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gthvodmwxq.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxocokyoo.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtxqvnlngy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hywenlv.cn/Article/details/gtzaklnmct.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtvagfsfke.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtxuymrqzc.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gthmspwbps.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzcgivzr.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtxpyxucel.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtjoocowlu.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtcfpodsng.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gtsvbcpoge.html


<!-- 参考信息 -->