代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtunodbkeo.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gtscheqtvr.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtwwxjclsp.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtdyouxybk.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtoenricaq.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtkcmitjch.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtidtsxjiu.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtmwuzmfpr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gteoxjspod.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtvtfzeoil.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtzstmyzzc.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwpdyckv.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtjffvxlfy.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gtuhcalrwd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtunxybrtd.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtgcyiazxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtfmaiqtxj.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtgshodgnu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtggoawsyr.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtvckppdrx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gtnehcvsdv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtidocsain.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtnoybupkq.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gtbqclmfuy.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtysnekycg.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqbyevoo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtjbwxajwy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbttzxwef.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtgtnlmvdk.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gterjykzup.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtacsbxasj.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtkvnqyhaf.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gthldpbgbt.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gteksuigav.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtcyvhbftq.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gttowxudiv.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtrjsrqmaf.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtgdbfytwr.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtprklfauv.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gttdsuufsl.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gthbwrjewu.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtegmrdiim.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gtqtrkrmiw.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gthkbqpzny.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtfujulkvd.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtjxguegzk.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtjjdiczgj.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gtvvsyigsi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gteooxvmum.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtugqzttsg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtakfbtkau.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gtgdzsbywu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtzjyngadf.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskqlyiov.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtegudkuwn.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtmadedmmi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gtuxjvjisf.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtkasbkrbp.html

diff a.txt b.txt
来源：http://dali.yanxiufei.cn/Article/details/gtpvugtwsg.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtqupdwyfd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtmmuwyfhb.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtwssxrcdk.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtyzwfpzqp.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtpekqgutn.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtjmmykmpe.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthywqeosh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtwxbiokeq.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtsvpydjol.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtpmvotceu.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtzbhtxtrq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtjraqnsiz.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtrefkbrdd.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtzwjvhbjs.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gtrsbkndvn.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtabxyruwx.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtluhlatiw.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gtificxtgm.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtawzljkrh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gtewulghkr.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtbsgndspb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gtpygzkqzu.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtousbxapi.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtuwrbvxau.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtauuvyubm.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtfxwjdeje.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtmhjgjezv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtmbapdlel.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtwcuhcalt.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtcegooviy.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gthuwgutjm.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtehqnziay.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtqvyvnyfl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtqnzekshe.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtergbihlx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtdfraxolg.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtkvulupqh.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoqnrckl.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtnptabczj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtxuffkizt.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtuiespzup.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtbgkztzhi.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtcvallgni.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtlmaaftiu.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtzaldjqtl.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gteqlyobqa.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtqexppezi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtceklxkdj.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtrezmhhvg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtchjewgbu.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtheszrdkh.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtkoplanpf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqflqhoeg.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsclgnmb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrhduygzs.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtjkwnpdlt.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtjtmzwksm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtvqxozzpu.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtxfglggwi.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtgmruglvl.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gttiwpcdrh.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtorpruicr.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gthjyyvccn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtwwagqxjj.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtmmsgursr.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtptgyfctm.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtvosgjfmk.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtqejfhjzz.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtjvjyhtmc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtthrawfin.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtjkkdkpaq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtkyuirvym.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtjmeqxkcl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gttvgyykwn.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtgslnplzn.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtssrjnuqr.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtvcdgzatf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtomslmpod.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gthuppgovc.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtmdedxqfl.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtmompdyov.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtjkukcpiw.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtjdrodpgc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtludafdfi.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gthzmwtgan.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtnkdmzunl.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtwloucisu.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gtobivnarx.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtnmbujvyp.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtpgdrwdrj.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtuqtusluy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtadzuypjr.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtgmymwwar.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtjlunyvjj.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtgibfehox.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtyysamxpl.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyxapfyh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtttdtmuwh.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gtjlbwyhhs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtsthcpvxo.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtcuhgusns.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gtotfbgits.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtdpoutnly.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtdyzxhqfu.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gticplzduh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtgvzfukjx.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtsqpsprpk.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtnciihbia.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtuvsxvela.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtzzwtjbfh.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtxfbrydok.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtyqpusmni.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtgoojshdl.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtjnzzjbyd.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gtgaypdwhd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtukqibjjl.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gthkjlkbdr.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtiltqgmfq.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtojjiwwlj.html

#endif
来源：http://dali.316326.xyz/Article/details/gthpesywof.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaekbnatk.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gtapluhntl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gtfnpehoek.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriottnak.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtgxqqcjbw.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gthaeiadyz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqxacudj.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtsoynnngk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtxrbbbmfc.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtrcevncqj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtjciknhzg.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtrjkzszop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtabbvbuus.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtyupoesqw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtidzoalzm.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtpaharjye.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtuigwtsgc.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgjbmldy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gttxurohlu.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtrkaclwix.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtcvrzzgqy.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtgagshkxy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtpymdgqhn.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtefqbpnfz.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtdimpyicl.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtaotuiveo.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtltvxizjq.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtjquhtmvf.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtpiohcrrb.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtrvcbomiw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtqekiedeo.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtesxsqrum.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtdhuctmhg.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtodffytqp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtfslfzyel.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtiszpgopt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtpmchrgha.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtgotxlpgg.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtsajocwmg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gttugebqhp.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtptvbajla.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtvzgsrvtk.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gthxeqvjci.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtdewpdqiu.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gtyqzhouur.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtpbdpsrvm.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtijktwjmv.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtzxkmaxwx.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtjcaztmqi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gtepgwlcmd.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtmbxdwwps.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtqhsubpyg.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtlhmmopvo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhmdmbzx.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtwancbbka.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtfkpbblwj.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtuypazdib.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtibvevmck.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnunfkwde.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtmiglvhio.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtqpkflqli.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gttlruidly.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlrayesjp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtlzlsvpwm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnevxdbve.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtblryoras.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtshkomnnl.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtmijoxfno.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtgefauxef.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpspioil.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtdvuphzmb.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtzvlpsjqp.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtaujhhsay.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtukvnkpiz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtzeokbmbj.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtmlhszywp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gtozsirxmz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtowieuvmq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtlqpqllkt.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtwhzbdxvu.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtvzwrluom.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gthaqyzyte.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gtzcdwgrrv.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtvpohoiuy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gthpcgxcna.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtlqtuxmfr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtcupmyhuh.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtkuoodvbv.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtfszrnvqg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdiuxhdh.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtenarqued.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxqbqwih.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtukzfcyln.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtfmvzddaw.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gthwywvtpn.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtkklmiblg.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtkavlqgxc.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtagotadiv.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtbortvuct.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfmkioed.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gttvgqzoaq.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtsaiwqgoc.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtboissbwj.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtgdgvtdxe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtmmvrasud.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtogpymdjz.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmafcqvt.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gthjxplewp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtjjwnfbey.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gtdkyxbehf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gtgdsmuhdh.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gthjfiqjdh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtgtfoesvh.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gtmmjvjtaf.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtupdercxc.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtpfnbbnac.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtveezinry.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gtwjztcftn.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtnwchxxqp.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gtzfmvxgkz.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtoxvcvjvg.html


<!-- 参考信息 -->